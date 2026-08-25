# Attack and defence

## CIA triad

Confidentiality ensures that sensitive data can only be accessed by authorized individuals. If confidentiality is not maintained, unauthorized individuals can access the data, resulting in financial loss, privacy violations, or legal consequences.

Integrity ensures that unauthorized individuals do not modify data. Without integrity, data can be altered and no longer be trusted. Unauthorized changes in data can sometimes lead to dangerous consequences.

Availability ensures that data and services are available to authorized users when needed. Although it comes as the third and last pillar of the CIA Triad, it is no less important than the other two. Most businesses rely heavily on their digital services, and if those services become unavailable, there is no more business, causing a huge loss to them. Even a short period of downtime can have serious consequences on the businesses and users.

### Understanding The basics

- **Plaintext** - A message you can read normally. Like HELLO or Patient name: Alice Smith.
- **Ciphertext** - A scrambled version that's not supposed to make sense. Like KHOOR or Sdwlhqw qdph: Dolfh Vplwk.
- **Key** - The secret ingredient that controls how scrambling and unscrambling work. Think of it as a password that the algorithm uses.
- **Algorithm** - The public recipe—the set of steps that explain how to use the key on the message. Everyone can know the algorithm. Security comes from keeping the key secret.
- **Encryption process**: plaintext + encryption algorithm + key  → ciphertext
- **Decryption process:** ciphertext + decryptiong algorithm + key   → plaintext
- **symmetric encryption** in a nutshell: one key locks the box, the same key unlocks it.
- **Key Distribution problem** If they send it in plaintext, an attacker grab it. if they encrypt the key, they need another key, which brings us right back to the same problem.

Enter asymmetric encryption.

### Two Keys Instead of One

Asymmetric encryption uses two mathematically linked keys:

- A public key that anyone can know and use.
- A private key that only one person keeps secret.

Here's the clever part:

- If you encrypt something with someone's public key, only their private key can decrypt it.
- If you encrypt something with your private key, anyone with your public key can decrypt it (this is primarily used for digital signatures, which we won't delve into here).

The two keys are connected by some serious maths, but it would take an ordinary computer hundreds or even thousands of years to recover the private key from the public key. This computational difficulty is what makes asymmetric encryption secure
