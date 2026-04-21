# TryHackMe: Offensive Security Intro

## 🔍 Concept: Content Discovery

To find pages that are not linked on the main website, we use a process called **Directory Brute-Forcing**.

* **Tool Used:** `dirb`
* **Command Example:** `dirb http://fakebank.thm`
* **Process:** The tool tests thousands of common folder names from a "wordlist" against the URL.
* **Success Indicator:** If the server responds with a **200 OK** status code, the hidden page exists and is accessible.

---

## ⚠️ The Vulnerability: Broken Access Control

In the simulation, navigating directly to `/bank-transfer` granted access to the admin panel without requiring a login.

* **The Flaw:** **Security through Obscurity**. The developers believed that if a user couldn't see a link, they wouldn't find the page.
* **The Reality:** Hiding a link is not security. If the server does not verify **Authorization** (checking if the user has the right permissions), the page remains public to anyone who knows or guesses the URL.

---

## 💡 Key Lessons for my Notes

* **HTTP Status Codes to Remember:** `200 OK`: Page found and accessible.
  * `403 Forbidden`: Page exists, but access is correctly blocked (This is what *should* have happened).
  * `404 Not Found`: Page does not exist.
* **The "Golden Rule":** Hiding a door is not the same as locking it. Always implement server-side permission checks.

---
**Date Completed:** 2026-04-21
**Category:** Offensive Security / Web Pentesting