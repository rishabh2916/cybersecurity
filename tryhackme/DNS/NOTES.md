# DNS in Detail

## What is DNS?

DNS (Domain Name System) provides a simple way for us to communicate with devices on the internet without remembering complex numbers. Much like every house has a unique address for sending mail directly to it, every computer on the internet has its own unique address to communicate with it called an IP address. An IP address looks like the following 104.26.10.229, 4 sets of digits ranging from 0 - 255 separated by a period. When you want to visit a website, it's not exactly convenient to remember this complicated set of numbers, and that's where DNS can help. So instead of remembering 104.26.10.229, you can remember tryhackme.com instead.

### Domain Hierarchy

![Alt text](https://tryhackme-images.s3.amazonaws.com/user-uploads/5c549500924ec576f953d9fc/room-content/a168c8511887fff98a6944619c4b5259.png)

1. **Top Level Domain(TLD)**

- Their are two type of TLD, gTLD (Deneric Top Level Domain) and ccTLD (Country Code Top Level Domain).
- gTLD tell the user what is the purpose of domain name like .com for commercial, .ed for education.
- ccTLD was used fo geographical purpose like .co.uk based on united kingdom

1. **Second Level Domain**

- For example rishabh.com so .com is TLD and rishabh is second level domain.
- the second level domain length to 63 char + the TLD.(Not start and end with hyphen).

1. Subdomain

- The subdomain is Left-hand side domain using period(.) to separate it. example raj.rishabh.com so raj is a subdomain.
- the second level domain length to 253 char OR less
- There is no limit to the number of subdomains you can create for your domain name
