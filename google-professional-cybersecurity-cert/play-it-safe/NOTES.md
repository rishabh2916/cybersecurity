# Play It Safe: Manage Security

## More about the CISSP security domains

### Security domains cybersecurity analysts

1. Security and risk management

All organizations must develop their security posture. Security posture is an organization’s ability to manage its defense of critical assets and data and react to change.

- Security goals and objectives
- Risk mitigation process
- Compliance
- Business continuity plans
- Legal regulations
- Professional and organizational ethics

Information security, or InfoSec, is also related to this domain and refers to a set of processes established to secure information. An organization may use playbooks and implement training as a part of their security and risk management program, based on their needs and perceived risk. There are many InfoSec design processes, such as:

- Incident response
- Vulnerability management
- Application security
- Cloud security
- Infrastructure security

1. Asset security

Asset security involves managing the cybersecurity processes of organizational assets, including the storage, maintenance, retention, and destruction of physical and virtual data.Because the loss or theft of assets can expose an organization and increase the level of risk, keeping track of assets and the data they hold is essential. Conducting a security impact analysis, establishing a recovery plan, and managing data exposure will depend on the level of risk associated with each asset. Security analysts may need to store, maintain, and retain data by creating backups to ensure they are able to restore the environment if a security incident places the organization’s data at risk.

1. Security achitecture and engineering

This domain focuses on managing data security. Ensuring effective tools, systems, and processes are in place helps protect an organization’s assets and data. Security architects and engineers create these processes.

One important aspect of this domain is the concept of shared responsibility. Shared responsibility means all individuals involved take an active role in lowering risk during the design of a security system. Additional design principles related to this domain

- Threat modeling
- Least privilege
- Defense in depth
- Fail securely
- Separation of duties
- Keep it simple
- Zero trust
- Trust but verify

1. Communication and network security

This domain focuses on managing and securing physical networks and wireless communications. This includes on-site, remote, and cloud communications. Designing network security controls—such as restricted network access—can help protect users and ensure an organization’s network remains secure when employees travel or work outside of the main office.

1. Identify and access management

The identity and access management (IAM) domain focuses on keeping data secure. It does this by ensuring user identities are trusted and authenticated and that access to physical and logical assets is authorized. This helps prevent unauthorized users, while allowing authorized users to perform their tasks.

Essentially, IAM uses what is referred to as the principle of least privilege, which is the concept of granting only the minimal access and authorization required to complete a task. As an example, a cybersecurity analyst might be asked to ensure that customer service representatives can only view the private data of a customer, such as their phone number, while working to resolve the customer's issue; then remove access when the customer's issue is resolved.

1. Security assessment and testing

The security assessment and testing domain focuses on identifying and mitigating risks, threats, and vulnerabilities. Security assessments help organizations determine whether their internal systems are secure or at risk. Organizations might employ penetration testers, often referred to as **pen testers**, to find vulnerabilities that could be exploited by a threat actor.

This domain suggests that organizations conduct security control testing, as well as collect and analyze data. Additionally, it emphasizes the importance of conducting security audits to monitor for and reduce the probability of a data breach. To contribute to these types of tasks, cybersecurity professionals may be tasked with auditing user permissions to validate that users have the correct levels of access to internal systems.

1. Security operations

The security operations domain focuses on the investigation of a potential data breach and the implementation of preventative measures after a security incident has occurred. This includes using strategies, processes, and tools such as:

- Training and awarness
- Reporting and documentation
- Intrusion detection and prevention
- SIEM tools
- Log management
- Incident management
- Playbooks
- Post-breach forensics
- Refleccting on lessons learned

1. Software development security

The software development security domain is focused on using secure programming practices and guidelines to create secure applications. Having secure applications helps deliver secure and reliable services, which helps protect organizations and their users.

## Navigate threats, risks, and vulnerabilities

### Risk Management

A primary goal of organizations is to protect assets. An asset is an item perceived as having value to an organization. Assets can be digital or physical. Examples of digital assets include the personal information of employees, clients, or vendors, such as:

- Social Security Number (SSNs), or unique national identification number assingned to individuals
- Dates of birth
- Bank account number
- Mailing addresses

Examples of physical assets include:

- Payment Kiosks
- Servers
- Desktop computers
- Office spaces

Some common strategies used to manage risks include:

- **Acceptance:** Accepting a risk to avoid disrupting business continuity
- **Avoidance:** Creating a lpan to avoid the risk altogether
- **Transference:** Tranferring risks to a third party to manage
- **Mitigation:** Lessening the impact of a known risk

1. **Threats:** A threats is any circumstances and event that can negatively imapct assets. common types of threats include:

- **Insider threats:** Staff menbers or vendors abuse their authorized access to obtain data that may harm an organization.
- **Advanced persistent threats(APTs):** A threat actor maintains unauthorized access to a system for an extended period of time.

1. **Risk:** A risk is anything taht can impact the confidentiality, integrity, or availability of an asset.

There are different factors that can affect the likelihood of a risk to an organization’s assets, including:

- **External risk:** Anything outside the organization that has the potential to harm organizational assets, such as threat actors attempting to gain access to private information.
- **Internal risk:** A current or former employee, vendors, or trusted partner who poses a security risk.
- **Legacy system:** Old systems that might not be accounted for or updated, but can still impact assets, such as workstations or odd mainframe systems.
- **Multiparty risk:** Outsourcing work to third-party vendors can give them access to intellectual property, such as trade secrets, software design, and inventions.
- **Software compliance/licensing:** Software that is not updated or in compliance, or patches that are not installed in a timely manner.

1. **Vulnerabilities:** A vulnerability is a weakness that can be exploited by a threat. some vulnerabilities include:

- **ProxyLogon:** A pre-authenticated vulnerability that affects ths Microsoft Exchange server. This means a threat actor can complete a user authentication precess to deploy malicious code from a remote location.

- **ZeroLogon:** A vulnerability in Microsoft’s Netlogon authentication protocol. An authentication protocol is a way to verify a person's identity. Netlogon is a service that ensures a user’s identity before allowing access to a website's location.

- **Server-side request forgery:** Allows attackers to manipulate a server-side application into accessing and updating backend resources. It can also allow threat actors to steal data.

- **Security logging and monitoring failures:** Insufficient logging and monitoring capabilities that result in attackers exploiting vulnerabilities without the organization knowing it.

### NIST RMF Framework

1. **Prepare:** The first step of the NIST RMF related to activities that are necessary to manage security and privacy risks before a breach occurs
1. **Categorize:** The second step of the NIST RMF that is used to develop risk management processes and tasks.
1. **Select:** The third step of the NIST RMF that means to choose, customize, and capture documentation of the controls that protect an organization.
1. **Implement:** The fourth step of the NIST RMF that means to implement security and privacy plans for an organization.
1. **Assess:** The fifth step of the NIST RMF that means to determine if established controls are implemented correctly.
1. **Authorize:** The sixth step of the NIST RMF that refers to being accountable for the security and privacy risks that may exist in an organization.
1. **Monitor:** The seventh step of the NIST RMF that means be aware of how systems are operating.

### Module 1, Terms and definations

- **Business continuity:** An organization's ability to maintain their everyday productivity by establishing risk disaster recovery plans.
- **External threat:** Anything outside the organization that has the potential to harm organizational assets.
- **Internal threat:** A current or former employee, external vendor, or trusted partner who poses a security risk.
- **Ransomware:** A malicious attack where threat actors encrypt an organization’s data and demand payment to restore access.
- **Risk mitigation:** The process of having the right procedures and rules in place to quickly reduce the impact of a risk like a breach.
- **Security posture:** An organization’s ability to manage its defense of critical assets and data and react to change.
- **Shared responsibility:** The idea that all individuals within an organization take an active role in lowering risk and maintaining both physical and virtual security.
- **Social engineering:** A manipulation technique that exploits human error to gain private information, access, or valuables.
- **Vulnerability:** A weakness that can be exploited by a threat.

### The relationship between framework and controls

- **Frameworks and controls** are guidelines used to building plans to help mitigate risk and threats to data and privacy. Frameworks support organizations' ability to adhere to compliance laws and regulations. For Example, the healthcare industry uses framework to comply with the US' Health Insurance Portability and Accountability Act (HIPAA), Which requires that medical professionals keep patient information safe.

- **Security controls** are safeguards designed to reduce specific security risk. Security controls are the measures organizations use to low risk and threats to data and privacy. For example, a control that can be used alongside frameworks to ensure a hospital remains complaint with HIPAA is requiring that patients use multi-factor authentication(MFA) to access their medical records.

### Specific frameworks and controls

- **Cyber Threat Frameworks (CTF)** According to the office of the director of National Intelligence, the CTF was developed by the U.S. govt. to provide "a common language for describing and communicating information about cyber threat activity".

- **International Organization for Standarization/International Electrotechnical Commission (ISO/IEC) 27001** An Internationally recognized and used framework is ISO/IEC 27001. The ISO 27000 family of standards enables organizations of all sectors and sizes to manage the security of assets, such as financial information, intellectual property, employee data, and information entrusted to third parties. Although the ISO/IEC 27001 framework does not require the use of specific controls, it does provide a collection that organization can use to improve their security posture.

### Controls

Controls are used alongside frameworks to reduce the possibility and impact of a security threat, risk, or vulnerability. controls can be physical, technical, and administrative and are typically used to prevent, detect, or, correct security issue.

**Example of Physical Controls:** {Gate, fences, and locks}, {Security guards}, {Closed-circuit television (CCTV), surveillance, and motion detectors}, and {Access cards or badged to enter office spaces}.

**Examples of technical controls:** Firewalls, MFA, and Antivirus software.

**Examples of administrative controls:** Separation of duties, Authorization, Asset classification.

**Note: People are the biggest threat to a company's security. This is why educating employee about security challenges is essential for minimizing the possibility of a breach**.

### The CIA triad for analyst

The **CIA triad** is a model that helps informa how organizations consider risk when setting up system and security policies. It is made up of three elements that cybersecurity analysts and organizations work toward upholding: confidentiality, integrity, and availability.

- **Confidentiality** is the idea that only authorized users can access specific assets or data. For example principle of leat privilege. The principle of least privilege limits access to only the information they need to complete work releted tasks.

- **Integrity** is the idea that the data is verifiable correct, authentic, and reliable. Having protocols in place to verify the authenticity of data is essential. One way to verify data integrity is though cryptography, which is used to transfrom data so unauthorized parties cannot read or tamper with (NIST, 2022). Another Example is Encryption process.

- **Availability** is the idea that data is sccessible to those who are authorized to use it. When a system adhere to both availability and confidentiality principles, data can be used when needed. For example, an employee works in the organization's accounting department, they might need access to corporate accounts but not data related to ongoing develpment projects.
