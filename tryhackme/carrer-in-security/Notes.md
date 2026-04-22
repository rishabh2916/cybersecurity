# Lab Setup: Virtualization

## 💻 My Tools

- **Hypervisor:** VirtualBox
- **Guest OS:** Kali Linux (Attacker Machine)
- **Goal:** To create an isolated environment for TryHackMe labs.

## ⚙️ Configuration Steps

1. **Network Mode:** Set to "NAT" or "NAT Network" (Allows internet access while keeping the VM isolated from my home network).
2. **Guest Additions:** Install these to enable "Shared Clipboard" (so I can copy-paste commands from VS Code into the Kali Terminal).
3. **Snapshots:** Take a "Snapshot" once the VM is perfect. If I break the system later, I can "Teleport" back to this exact moment.

> **Pro-Tip:** Always keep your host (Windows) and your guest (Kali) separate. Never do your personal banking or log into private email inside your Kali VM!

### Attack Type: SQL Injection (SQLi)

**Scenario:** Bypassing a login form by manipulating the database query.

**Payload used:** `' OR 1=1--`

- **Purpose:** To force the database query to return a `TRUE` result, regardless of the password.
- **Result:** Login bypassed without a valid password.

**Defense (How to fix it as a Dev):**

- Use **Parameterized Queries** (Prepared Statements).
- Never concatenate user input directly into SQL strings.
