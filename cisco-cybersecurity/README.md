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
