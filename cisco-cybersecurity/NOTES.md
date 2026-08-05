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

| Category      | Description                                                                                                                                                       | Legal Status   |
| :------------ | :---------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------- |
| **White Hat** | **Ethical Hackers.** They use their skills for good, finding vulnerabilities so organizations can fix them before an attack occurs.                               | **Legal**      |
| **Black Hat** | **Unethical Hackers.** They exploit vulnerabilities for personal gain, financial theft, or to damage a company's reputation.                                      | **Illegal**    |
| **Grey Hat**  | **The Middle Ground.** They may find a bug without permission and then demand a fee to fix it, or publish it publicly if they aren't satisfied with the response. | **Semi-Legal** |

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

## Security VIlnerabillity and Exploits

**Security Vulnerability** is a kind of **software or hardware defect**. the program is written to be take advantage of **vulnerability** is known as **Exploits**

### Hardware Vulnerability

- Hardware vulnerabilities are most often the result of hardware design flaws.
- **Meltdown and Spectre:** Google security researchers discovered Meltdown and Spectre, two hardware vulnerabilities that affect almost all central processing units (CPUs) released since 1995 within desktops, laptops, servers, smartphones, smart devices and cloud services.

Attackers exploiting these vulnerabilities can read all memory from a given system (Meltdown), as well as data handled by other applications (Spectre). The Meltdown and Spectre vulnerability exploitations are referred to as side-channel attacks (information is gained from the implementation of a computer system). They have the ability to compromise large amounts of memory data because the attacks can be run multiple times on a system with very little possibility of a crash or other error.

### Software Vulnerability

- Software vulnerability are usally introduced by errors int he operating system.

### Categorizing Software Vulnerability

- **Buffer overflow:** The buffer are memory area allocated to an application. when the data is written by beyond the limits to a buffer. this can lead system crash or data compromise or provide escalation privileges.

- **Non-validating input:** Programs often require data input, but this incoming data could have malicious content, designed to force the program to behave in an unintended way.

- **Race conditions:** THis Vulnerability descirbes a situation where the output of an event depend on ordered or timed outputs.

- **Weaknesses in security practices:** ystems and sensitive data can be protected through techniques such as authentication, authorization and encryption. Developers should stick to using security techniques and libraries that have already been created, tested and verified and should not attempt to create their own security algorithms. These will only likely introduce new vulnerabilities.

- **Access control problems:** Access control is the process of controlling who does what and ranges from managing physical access to equipment to dictating who has access to a resource, such as a file, and what they can do with it, such as read or change the file. Many security vulnerabilities are created by the improper use of access controls.

## Proctection your Devices and Network

You’ve just been issued with a new laptop at @Apollo and are getting ready to set it up. What steps would you take to secure it before use?

To make your device safe and secure, you should:

- turn the firewall on
- install antivirus and antispyware
- manage your operating system and browser
- set up password protection.

## Password Best Practices

You probably have a password for just about every website you visit and it can be hard to remember them all. Web browsers and other programs may offer to remember passwords for you, which can be a significant timesaver. However, certain password shortcuts can leave you less secure. The following best practices may help protect your personal information:

- Use combinations of letters, numbers and symbols. The longer and stronger the password, the safer your information.
- Don't use the same password for multiple accounts, especially for the most sensitive ones, such as bank accounts, credit cards, legal or tax records, social media accounts, and files containing medical information.
- Don't use passwords that can be easily guessed, such as common words or birthdays of family members.

## What is Encryption

ncryption is the process of converting information into a form in which unauthorized parties cannot read it. Only a trusted, authorized person with the secret key or password can decrypt the data and access it in its original form.

Note that the encryption itself does not prevent someone from intercepting the data. It can only prevent an unauthorized person from viewing or accessing the content. In fact, some criminals may decide to simply encrypt your data and make it unusable until you pay a ransom.

## Terms of services

The Terms of Service, also known as Terms of Use or Terms and Conditions, is a legally binding contract that governs the rules of the relationship between you, the service provider and others who use the service.

### undestant the terms

The Terms of Service will include a number of sections, from user rights and responsibilities to disclaimers and account modification terms.

### Before you sign up

- Have you read the terms and services?
- What are your right regardings your data?
- can you request a copy of your data?
- What can the provider do with the data you upload?
- What happens to your data when you close your account?

## Cyber security Devices and Technology

### Security Appliances

security appliance can be standalone like router or Software tools that are run on network devices. Their are sim general categories

- **Router:** The router are primarily used to interconneted network segment. Its also having basic traffic filtration. define the which computer network from the given network segment communicate with which network segment.

- **Firewalls:** The firewalls Scanning the incoming and outgoing traffic and detect the malicious behavior that has to be blocked.

- **Intrusion Detection System:** Set of traffic signatures that match and block malicious traffic and attacks.

- **Virtual private network:** VPN create a end-to-end encryted tunnel between the network.

- **Antimalware and Antivirius:** These system use script to detect the suspicious activity and block the malicious code from beign executer.

- **Other security devices:** include web and email security appliances, decryption devices, client access contro, servers and security management systems.

### Firewalls

- **Network layer Firewall:** This filters communications based on source and destination IP addresses.

- **Transport layer Firewall:** Filters communications based on source and destination data ports, as well as connection states.

- **Application layer Firewall:** Filters communications based on an application, program or service.

- **Poxy server:** Filters web content requests like URLs, domain names and media types.

- **Reverse Proxy:** Placed in front of web servers, reverse proxy servers protect, hide, offload and distribute access to web servers.

- **Context aware layer firewall:** Filters communications based on the user, device, role, application type and threat profile.

- **Network address information (NAT) firewall:** This firewall hides or masquerades the private addresses of network hosts.

- **Host based firewall:** Filters ports and system service calls on a single computer operating system.

### Port Scanning

Each application running on device is assigned identifier is called port number. This port number is used on both ends of the transmission so that the right data is passed to the correct application.

### Intrusion Detection and Prevention system

Intrusion detection systems (IDSs) and intrusion prevention systems (IPSs) are security measures deployed on a network to detect and prevent malicious activities.

- The job of IDS is to detect log and report.
- IPS is block and deny traffic based on a positive rule or signature match like cisco sourcefire

### security best practice

- **Perform a risk assessment:** Knowing and understanding the value of what you are protecting will help to justify security expenditures.
- **Create a security policy:** Create a policy that clearly outlines the organization's job roles, and responsibility and expectation for employees.
- **Physical security measures:** Restrict access to networking closets and server location, as well as fire suppresion.
- **Human resources security measures:** Background checks should be completed for all employees.
- **Performs and test backups:** Back up information regularly and test data recovery from backups.
- **Maintains security patches and updates:** Regularly update server, client and network device OS and programs.
- **Employ access controls:** Configure user role and privilege levels as well as strong user authentication.
- **Regularly test incident response:** Employ an incident response team and test emergency response scenarios.
- **Implement a network monitoring, analytics and management tool:** Choose a security monitoring solution that integrates with other technologies.
- **Implement network security devices:** Use next generation routers, firewalls and other security appliances.
- **Implement a comprehensive endpoints security software:** use enterprise level antimalware and antivirus software.
- **Educate users:** Provide training to employees in security procedures.
- **Encrypt data:** Encrypt all sensitive organization data, including email.
