# Cisco Junior cybersecurity Analyst

## The World of Cybersecurity

Cybersecurity is the ongoing effort to protect individuals, organizations and governments from digital attacks by protecting networked systems and data from unauthorized use or harm.

- **Personal:** On a personal level, you need to safeguard your identity, your data, and your computing devices.

- **Organizational:** At an organizational level, it is everyone’s responsibility to protect the organization’s reputation, data and customers.

- **Government:** As more digital information is being gathered and shared, its protection becomes even more vital at the government level, where national security, economic stability and the safety and wellbeing of citizens are at stake.

### Your Online Identity

When choosing a username, it’s important not to reveal any personal information. It should be something appropriate and respectful and should not lead strangers to think you are an easy target for cybercrimes or unwanted attention.

Some other useful tips to help you generate your username:

- Don’t use your full name or parts of your address or phone number.
- Don’t use your email username.
- Don’t use the same username and password combination, especially on financial accounts.
- Don’t choose a super-odd username and then reuse it again and again — it makes you easier to track.
- Don’t choose a username that gives clues to your passwords such as a series of numbers/letters or the first part of a two-part phrase, such as knock-knock or starlight, or the department in which you work, such as IT.
- Do choose a username that’s appropriate for the type of account, i.e., business, social or personal.

Remember to check your points by clicking on the shield icon on the top-right hand corner of the screen.

## Types of Organizational Data

### Traditional Data

Traditional data is typically generated and maintained by all organizations, big and small. It includes the following:

- **Transactional data** such as details relating to buying and selling, production activities and basic organizational operations such as any information used to make employment decisions.

- **Intellectual property** such as patents, trademarks and new product plans, which allows an organization to gain economic advantage over its competitors. This information is often considered a trade secret and losing it could prove disastrous for the future of a company.
Financial data such as income statements, balance sheets and cash flow statements, which provide insight into the health of a company.

### The Cube

The McCumber Cube is a model framework created by John McCumber in 1991 to help organizations establish and evaluate information security initiatives by considering all of the related factors that impact them. This security model has three dimensions:

1. The foundational principles for protecting information systems.
1. The protection of information in each of its possible states.
1. The security measures used to protect data.

- **Confidentiality** is a set of rules that prevents sensitive information from being disclosed to unauthorized people, resources and processes. Methods to ensure confidentiality include **data encryption**, **identity proofing** and **two factor authentication**.

- **Integrity** ensures that system information or processes are protected from intentional or accidental modification. One way to ensure integrity is to use a **hash function** or **checksum**.

- **Availability** means that authorized users are able to access systems and data when and where needed and those that do not meet established conditions, are not. This can be achieved by **maintaining equipment**, **performing hardware repairs**, **keeping operating systems and software up to date**, and **creating backups**.

### The protection of information in each state

- **Processing** refers to data that is being used to perform an operation such as updating a database record (data in process).

- **Storage** refers to data stored in memory or on a permanent storage device such as a hard drive, solid-state drive or USB drive (data at rest).

- **Transmission** refers to data traveling between information systems (data in transit).

### The security measures used to protect data

- **Awareness, training and education** are the measures put in place by an organization to ensure that users are knowledgeable about potential security threats and the actions they can take to protect information systems.

- **Technology** refers to the software- and hardware-based solutions designed to protect information systems such as firewalls, which continuously monitor your network in search of possible malicious incidents.

**Policy and procedure** refers to the administrative controls that provide a foundation for how an organization implements information assurance, such as incident response plans and best practice guidelines.

### Case Study: Razer Data Leak (2020)

- **What Happened:** A server (Elasticsearch cluster) was misconfigured and left open to the internet without a password.

- **The Impact:** Over 100,000 records (emails, addresses, order details) were exposed.

- **The Lesson:** This was a failure of **Access Control**. Even with the best hardware, a simple "Inbound" firewall mistake can destroy user trust.

- **Remediation:** Implementing automated security scans to find "Open Ports" or "Unauthenticated Clusters".

### Case Study: Equifax Breach (2017)

- **Root Cause:** Failure to patch a known vulnerability in **Apache Struts**.

- **Attack Vector:** Remote Code Execution (RCE) via web application.

- **Major Failure:** Poor internal communication. The "Patch" was available 2 months before the
hackers arrived, but the server was never updated.

- **Key Lesson:** "Security is only as strong as your weakest link." As a developer, I must ensure all dependencies and frameworks are kept up-to-date.

### Consequences of a Security Breach

- Reputational demage
- Vandalism
- Theft
- Loass of revenue
- Damage intellectual property

### Incident Analysis & Prevention Strategies

After analyzing real-world security breach scenarios, I've documented the following key measures required to transition from a "reactive" to a "proactive" security posture.

1. **Continuous Monitoring & Log Analysis**

- **Concept:** Implementing a 24/7 monitoring system to evaluate logs, alerts, and unauthorized network activity.

- **Goal:** Identifying the "footprint" of an attacker in real-time to minimize dwell time.

1. **The "Developer-Security" Feedback Loop**

- **Concept:** Generating weekly security audit reports to be shared directly with the development team.

- **Developer Edge:** As a former frontend developer, I prioritize translating technical security vulnerabilities into actionable bug reports for the engineering team.

1. **Strengthening the "Human Firewall"**

- **Concept:** Delivering ongoing cybersecurity awareness training to all employees.

- **Focus:** Training staff to identify social engineering tactics and phishing attempts before they bypass technical controls.

1. **Proactive Vulnerability Management**

- **Concept:** Continuous scanning of the organizational infrastructure to identify and patch "holes" before they can be exploited by threat actors.

1. **Advanced Malware Prevention**

- **Concept:** Deploying endpoint protection and response (EDR) tools to block malicious code execution and prevent lateral movement within the network.

### Find out More

Search for a new additional examples of recent security breaches. In each case, can we identify

- What was taken?
- What exploits the attacks used?
- What actions could be taken to prevent the breach from occuring again in the future

## The Threat Landscape: Types of Attackers

Attackers are categorized based on their technical skills, their legality, and their motives.

### 1. Amateurs (The Beginners)

- **Script Kiddies:** A term that emerged in the 1990s to describe low-skilled attackers.

- **Characteristics:** They lack the ability to write their own exploits. Instead, they use pre-made tools and scripts found online.

- **Motive:** Often curiosity, learning, or minor vandalism. While they are amateurs, they can still cause significant damage to unpatched systems.

### 2. The Hacker Spectrum

Hackers are classified by "Hats" to represent their ethics and legal standing.

| Category | Description | Legal Status |
| :--- | :--- | :--- |
| **White Hat** | **Ethical Hackers.** They use their skills for good, finding vulnerabilities so organizations can fix them before an attack occurs. | **Legal** |
| **Black Hat** | **Unethical Hackers.** They exploit vulnerabilities for personal gain, financial theft, or to damage a company's reputation. | **Illegal** |
| **Grey Hat** | **The Middle Ground.** They may find a bug without permission and then demand a fee to fix it, or publish it publicly if they aren't satisfied with the response. | **Semi-Legal** |

### 3. Organized Attackers (The Professionals)

These groups are highly coordinated, well-funded, and technically advanced.

- **Cyber Criminals:** Motivated strictly by financial gain (e.g., Ransomware).
- **Hacktivists:** Attackers motivated by political or social causes.
- **State-Sponsored:** Hackers hired by governments for espionage or to attack another nation's infrastructure.
- **Terrorists:** Focus on creating chaos and fear by attacking critical systems like power grids or water supplies.

### Internal and External Threats

1. **Internal:** Employees, Contract staff or trusted partners can accidentaly or intentionally.

- mishandled confedential data
- facilitate outside attacks by connecting infected USB media into organization computer system
- Invite malware onto the organization's network by cliking on malicious emails or websites
- threaten the operations of internal servers or network infrastructure

1. **External:** Amateurs or skilled attackers outside of the organization

- exploits vilnerabilites in the network
- gain unauthorized access to computing
- use social engineering to gain unauthorized access to organizational data

### Cyberwarefare

Cyberwarfare, as its name suggests, is the use of technology to penetrate and attack another nation’s computer systems and networks in an effort to cause damage or disrupt services, such as shutting down a power grid.

## Module 2: Attacks, Concepts and Techniques

### Analyzing a Cyber Attack

- **Malware:** The Cyber Criminals use different kind of malicious software, malware, to carry out their activity.

- **Types of Malware:**

1. **Spyware:** Malware designed to secretly monitor user activity and collect sensitive data.  

**Functions:**

- Records keystrokes (keylogging)
- Tracks browsing activity
- Steals credentials and personal data  

**Impact:** Privacy breach and data theft without user awareness

1. **Adware:** Malware that displays unwanted advertisements on a system.  

**How it spreads:**

- Bundled with free or third-party software  

**Functions:**

- Shows pop-ups, banners, or redirects  

**Impact:**

- Slows down system performance
- May track user behavior  

1. **Ransomware:** Malware that encrypts user data and demands payment (ransom) to restore access.  

**How it works:**

- Encrypts files
- Displays ransom message  

**Goal:** Financial gain  

**Note:** Paying ransom does not guarantee data recovery  

1. **Backdoor:** A hidden method used by attackers to bypass authentication and gain access.  

**Functions:**

- Provides remote access to system
- Allows execution of commands  

**Impact:** Highly dangerous and difficult to detect  

1. **Trojan Horse:** Malware disguised as legitimate software.  

**How it works:**

- Tricks users into installing it  

**Functions:**

- Creates backdoors
- Steals data
- Installs additional malware  

1. **Virus:** Malicious code that attaches itself to legitimate files and spreads when executed.  

**Key Feature:**

- Requires user action (e.g., opening a file)  

**Impact:**

- Corrupts or deletes files
- Affects system performance  

1. **Worm:** Self-replicating malware that spreads automatically across networks.  

**Key Feature:**

- Does not require user interaction  

**Impact:**

- Consumes bandwidth
- Spreads rapidly across systems  

1. **Rootkit:** Malware designed to hide its presence and maintain privileged access.  

**Functions:**

- Hides files and processes
- Avoids detection by security tools  

**Impact:** Very difficult to detect and remove  

1. **Scareware:** Malware that tricks users into believing their system is infected.  

**How it works:**

- Displays fake alerts or warnings  

**Goal:**

- Tricks users into installing fake software or paying money  

### Quick Revision

- Spyware → Steals data silently  
- Adware → Shows unwanted ads  
- Ransomware → Locks data for money  
- Trojan → Disguised as legit software  
- Virus → Needs user action  
- Worm → Spreads automatically  
- Rootkit → Hides deeply in system  
- Backdoor → Secret system access  
- Scareware → Creates fake fear  

## Methods of Infiltration

1. **Social Engineering:** Social engineering is a human manipulation technique used to trick individuals into revealing confidential information or performing actions that compromise security.

**Key Points:**

- Exploits human psychology rather than technical vulnerabilities  
- Relies on trust, fear, urgency, or curiosity  
- Targets human weaknesses like helpfulness or lack of awareness  

1. **Pretexting:** A social engineering technique where an attacker creates a fake scenario (pretext) to gain trust and extract sensitive information.

**Example:**

- Pretending to be bank staff to ask for OTP or account details  

1. **Phishing:** A technique where attackers send fraudulent emails, messages, or websites that appear legitimate to steal sensitive data.

**Example:**

- Fake login page asking for username and password  

1. **Tailgating (Piggybacking):** A physical security attack where an unauthorized person gains access to a restricted area by following an authorized individual.

**Example:**

- Entering an office by asking someone to hold the door.

### Revision

- Social Engineering → Manipulating people  
- Pretexting → Fake story  
- Phishing → Fake emails/websites  
- Tailgating → Physical access without permission

### Denial-of-Service

- **DoS:** the Denial of services is the type of network attack that is relatively simple to carry out.It create a intruption in the Network services of user, devices and application.

**Type of DoS Attack:**

1. **overwhelimg traffic:** attacker send the enormous data packet on the user application. this cause a slowdown in transmission or response, or the device or service to crash it.

2. **Malicious packet formate:** The packet is the collection of data the flowa between send and reciever computer or application over a network. when an malicious packet is sent, the reciever can't be unable to handle it.

### Distributed DoS

**Distributed DoS (DDoS):** attack is similar to a DoS attack but originates from multiple, coordinated sources. For example:

- An attacker builds a network (botnet) of infected hosts called zombies, which are controlled by handler systems.

- The zombie computers will constantly scan and infect more hosts, creating more and more zombies.

- When ready, the hacker will instruct the handler systems to make the botnet of zombies carry out a DDoS attack.

1. **Botnet:** A botnet is a network of infected devices (bots/zombies) controlled remotely by an attacker (botmaster).

**How it works:**

- Devices get infected via malware
- They connect to a Command & Control (C2) server
- Attacker sends instructions to all infected devices

**Uses:**

- DDoS attacks
- Spamming
- Data theft

**Key Point:**  
Bots operate without the user’s knowledge.

1. **On-Path Attacks (Man-in-the-Middle):** An attack where the attacker secretly intercepts and possibly alters communication between two parties.

**How it works:**

- Attacker positions themselves between sender and receiver
- Captures or modifies data in transit

**Example:**

- Intercepting login credentials over unsecured Wi-Fi

**Impact:**

- Data theft
- Session hijacking
- Communication manipulation

1. **Wi-Fi Password Cracking:** The process of attempting to gain unauthorized access to a Wi-Fi network by discovering its password.

**Common Methods (high-level):**

- Dictionary attack (common passwords)
- Brute-force attack (trying combinations)
- Exploiting weak encryption (e.g., outdated protocols)

**Risk Factors:**

- Weak passwords
- Outdated security (WEP)

**Prevention:**

- Use strong passwords
- Enable WPA2/WPA3 encryption
- Disable WPS

1. **Advanced Persistent Threat (APT):** A sophisticated, long-term cyber attack where attackers gain unauthorized access and remain undetected.

**Characteristics:**

- Highly targeted (organizations, governments)
- Long duration (months/years)
- Uses multiple attack techniques

**Attack Stages:**

1. Initial access (phishing/malware)
2. Establish foothold
3. Privilege escalation
4. Lateral movement
5. Data exfiltration

**Goal:**  
Steal sensitive data or conduct espionage

---

### ⚡ Quick Revision

- Botnet → Network of infected devices  
- On-Path Attack → Intercepting communication  
- Wi-Fi Cracking → Breaking network password  
- APT → Long-term targeted attack  
