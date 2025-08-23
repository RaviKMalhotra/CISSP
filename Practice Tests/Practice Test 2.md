# CISSP Practice Test 2

Chapter 10: Practice Test 2
James is building a disaster recovery plan for his organization and would like to determine the amount of acceptable data loss after an outage. What variable is James determining?

SLA

RTO

MTD

RPO

Answer:
D.  The recovery point objective (RPO) identifies the maximum amount of data, measured in time, that may be lost during a recovery effort. The recovery time objective (RTO) is the amount of time expected to return an IT service or component to operation after a failure. The maximum tolerable downtime (MTD) is the longest amount of time that an IT service or component may be unavailable without causing serious damage to the organization. Service-level agreements (SLAs) are written contracts that document service expectations.

In his role, Chris is expected to protect the interests of the organization, as well as the customers whose information he is charged to protect. What term describes the preparation and research undertaken before decisions and actions are made?

Due care

Compliance

Due diligence

Regulatory action

Answer:
C.  Due care and due diligence can be a confusing pair of terms to keep straight. Chris is engaging in due diligence when he does the preparation and research. Once that is done, he must use due care while undertaking the actions. This is often described in the context of the prudent person rule: would a prudent person have taken the action given the same knowledge? Compliance efforts work to ensure an organization meets regulatory or other requirements. Organizations typically don't take regulatory action—that's left to the government.

Ade is part of a penetration testing exercise. As part of the process his role is to act as a defender. What color is frequently used to describe defenders in penetration testing exercises?

Red teams

Yellow teams

Green teams

Blue teams

Answer:
D.  Blue teams are defenders, red teams are attackers, and purple teams combine both attack and defense activities. Yellow and green teams are not commonly described as part of penetration testing.

Sharif's U.S.-based company wants to build a data center with AI-focused GPU-based computation nodes in China. What concern about regulations should Sharif express about the hardware needed?

AI hardware may not be legal in China.

The total dollar value of the hardware may exceed what can be shipped to China.

Export controls may limit what hardware can be imported to China.

There may be ethical issues with the use of AI hardware across international borders.

Answer:
C.  Hardware and software can be subject to import and export controls. In the case of AI computation hardware, there are specific limits on what can be exported to China, including limits on performance. Sharif needs to engage the appropriate experts to determine what can and cannot be exported. AI hardware is legal in China, dollar values are not typically the limiting factor for hardware import/export restrictions, and ethics are not a regulatory issue.

Tony wants to conduct a disaster recovery plan test exercise for his organization. What type of exercise should he conduct if he wants it to be the most realistic event possible and is able to disrupt his organization's operations to conduct the exercise?

Read-through

Full interruption

Walk-through

Simulation

Answer:
B.  The most realistic but also most disruptive option for disaster recovery plan testing is a full interruption. The least obtrusive but also least similar to real-world scenarios is a read-through. After that, walk-throughs and simulations are each closer to a true scenario, but parallel operations are often the most popular option because it can be done without disrupting the organization and still reasonably test capabilities.

Brian's organization has a remote facility that it could move operations to in an emergency. While the facility has basic utilities, no additional work has been done to prepare it for data-center operations. What type of site is this?

A hot site

A warm site

A cold site

A frozen site

Answer:
C.  Cold sites are facilities large enough to use for recovery operations with appropriate power and environmental capabilities but without any additional readiness work done for computing, connectivity, or other needs. Warm sites have equipment and connectivity in place but are not actively handling live data. Hot sites have live data and could take over operations immediately. Frozen site is not a term used to describe a failover or recovery site.

Ben works in an organization that uses a formal data governance program. He is consulting with an employee working on a project that created an entirely new class of data and wants to work with the appropriate individual to assign a classification level to that information. Who is responsible for the assignment of information to a classification level?

Data creator

Data owner

CISO

Data custodian

Answer:
B.  The data owner is normally responsible for classifying information at an appropriate level. This role is typically filled by a senior manager or director, who then delegates operational responsibility to a data custodian. Data creators do just that—create data—although data creators is not a commonly used role name in data role lists. CISOs are chief information security officers and are typically the top-level individual responsible for security in organizations.

James wants to ensure that his company's backups will survive a disaster that strikes the data center. Which of the following options is the best solution to this concern?

Off-site backups

A grandfather/father/son backup tiering system

Redundant backup systems

Snapshots to a SAN or NAS

Answer:
A.  Off-site backups are the best option for disaster recovery in a scenario where a disaster directly impacts the data center. None of the other scenarios as described will directly address the issue, although snapshots to a remote storage location can act as a form of off-site backup.

Gabe is concerned about the security of passwords used as a cornerstone of his organization's information security program. Which one of the following controls would provide the greatest improvement in Gabe's ability to authenticate users?

More complex passwords

User education against social engineering

Multifactor authentication

Addition of security questions based on personal knowledge

Answer:
C.  While all of the listed controls would improve authentication security, most simply strengthen the use of knowledge-based authentication. The best way to improve the authentication process would be to add a factor that is not based on knowledge through the use of multifactor authentication. This may include the use of biometric controls or token-based authentication.

The separation of network infrastructure from the control layer, combined with the ability to centrally program a network design in a vendor-neutral, standards-based implementation, is an example of what important concept?

MPLS, a way to replace long network addresses with shorter labels and support a wide range of protocols

FCoE, a converged protocol that allows common applications over Ethernet

SDN, a converged architecture that allows network virtualization

CDN, a converged protocol that makes common network designs accessible

Answer:
C.  Software-defined networking (SDN) is a converged protocol that allows virtualization concepts and practices to be applied to networks. MPLS handles a wide range of protocols like asynchronous transfer mode (ATM), digital subscriber line (DSL), and others, but isn't intended to provide the centralization capabilities that SDN does. A content distribution network (CDN) is not a converged protocol, and FCoE is Fibre Channel over Ethernet, a converged protocol for storage.

Susan is preparing to decommission her organization's archival DVD-ROMs that contain Top Secret data. How should she ensure that the data cannot be exposed?

Degauss

Zero wipe

Pulverize

Secure erase

Answer:
C.  The best way to ensure that data on DVDs is fully gone is to destroy them, and pulverizing DVDs is an appropriate means of destruction. DVD-ROMs are write-only media, meaning that secure erase and zero wipes won't work. Degaussing works only on magnetic media and cannot guarantee that there will be zero data remanence.

Susan is worried about a complex change and wants to ensure that the organization can recover if the change does not go as planned. What should she require in her role on the organization's change advisory board (CAB)?

She should reject the change due to risk.

She should require a second change review.

She should ensure a backout plan exists.

She should ensure a failover plan exists.

Answer:
C.  Backout plans are required in some change management processes to ensure that the thought process and procedures for what to do if something does not go as planned are needed. Validating backout plan quality can be just as important as the change, and you may find, in many organizations, if nobody is watching, that backout plans may read, “Undo the change we made.” Rejecting the change won't fix the problem if the change has been made. A change review is useful to identify problems before the change is made. Failover plans are not a term commonly used in change management processes.

Angie is configuring egress monitoring on her network to provide added security. Which one of the following packet types should Angie allow to leave the network headed for the Internet?

Packets with a source address from Angie's public IP address block.

Packets with a destination address from Angie's public IP address block.

Packets with a source address outside Angie's address block.

Packets with a source address from Angie's private address block.

Answer:
A.  All packets leaving Angie's network should have a source address from her public IP address block. Packets with a destination address from Angie's network should not be leaving the network. Packets with source addresses from other networks are likely spoofed and should be blocked by egress filters. Packets with private IP addresses as sources or destinations should never be routed onto the Internet.

Michele's company operates a private cloud inside of an environment provided by their IaaS service provider. What term describes these isolated pools of resources that organizations can configure to serve their purposes?

A VLAN

A VPC

An SDN

A CDN

Answer:
B.  Virtual private clouds (VPCs) run on cloud-hosted infrastructure providing a secure, isolated pool of resources to be used by organizations to meet their needs. A VLAN is a virtual local area network. While VLANs are part of how most VPCs work, they alone aren't sufficient to create a VPC. An SDN, or software defined network, is used to manage networks through code, and CDNs are content delivery networks used to provide access to content around the globe that helps offload traffic while protecting against denial-of-service (DoS) attacks and other issues.

Theresa is implementing a new access control system and wants to ensure that developers do not have the ability to move code from development systems into the production environment. She wants to ensure that a developer who checks in code cannot then approve their own code as part of the process. What information security principle is she most directly enforcing?

Separation of duties

Two-person control

Least privilege

Job rotation

Answer:
A.  While developers may feel like they have a business need to be able to move code into production, the principle of separation of duties dictates that they should not have the ability to both write code and place it on a production server. The deployment of code is often performed by change management staff. Two-person control requires two individuals to perform an action to ensure appropriate oversight. Least privilege is the concept of only providing privileges required to perform a role, and job rotation moves individuals through job roles to ensure that different people perform tasks preventing an individual from exploiting their job function over time.

Which one of the following tools may be used to achieve the goal of nonrepudiation?

Digital signature

Symmetric encryption

Firewall

IDS

Answer:
A.  Applying a digital signature to a message allows the sender to achieve the goal of nonrepudiation. This allows the recipient of a message to prove to a third party that the message came from the purported sender. Symmetric encryption does not support nonrepudiation. Firewalls and IDS are network security tools that are not used to provide nonrepudiation.

In this diagram of the TCP three-way handshake, what should system A send to system B in step 3?

Larger View
A sample T C P three-way handshake diagram. System A is connected system B, and then continues.
ACK

SYN

FIN

RST

Answer:
A.  System A should send an ACK to end the three-way handshake. The TCP three-way handshake is SYN, SYN/ACK, ACK. FIN is used to end a TCP connection, while RST resets the connection.

What RADIUS alternative is commonly used for Cisco network gear and supports two-factor authentication?

RADIUS+

TACACS+

XTACACS

Kerberos

Answer:
B.  TACACS+ is the most modern version of TACACS, the Terminal Access Controller Access-Control System. It is a Cisco proprietary protocol with added features beyond what RADIUS provides, meaning it is commonly used on Cisco networks. XTACACS is an earlier version, Kerberos is a network authentication protocol rather than a remote user authentication protocol, and RADIUS+ is a made-up term.

What two types of attacks are VoIP call managers and VoIP phones most likely to be susceptible to?

DoS and malware

Worms and Trojans

DoS and host OS attacks

Host OS attacks and buffer overflows

Answer:
C.  Call managers and VoIP phones can be thought of as servers or appliances and embedded or network devices. That means that the most likely threats that they will face are denial-of-service (DoS) attacks and attacks against the host operating system. Malware and Trojans are less likely to be effective against a server or embedded system that doesn't browse the Internet or exchange data files; buffer overflows are usually aimed at specific applications or services.

Vivian works for a chain of retail stores and would like to use a software product that restricts the software used on point-of-sale terminals to those packages on a preapproved list. What approach should Vivian use?

Antivirus

Heuristic

Whitelist

Blacklist

For questions 21–23, please refer to the following scenario:

Hunter is the facilities manager for DataTech, a large data center management firm. He is evaluating the installation of a flood prevention system at one of DataTech's facilities. The facility and contents are valued at $100 million. Installing the new flood prevention system would cost $10 million.

Hunter consulted with flood experts and determined that the facility lies within a 200-year flood plain and that, if a flood occurred, it would likely cause $20 million in damage to the facility.

Answer:
C.  The blacklist approach to application control blocks certain prohibited packages but allows the installation of other software on systems. The whitelist approach uses the reverse philosophy and allows only approved software. It is worth noting that the terms blacklist and whitelist are increasingly deprecated and that you may encounter terms like block list or deny list and allow list as language and terminology shifts. As you prepare for the exam and your professional work, make sure to consider these equivalents. Antivirus software would only detect the installation of malicious software after the fact. Heuristic detection is a variant of antivirus software.

Based on the information in this scenario, what is the exposure factor for the effect of a flood on DataTech's data center?

2%

20%

100%

200%

Answer:
B.  The exposure factor (EF) is the percentage of the facility that risk managers expect will be damaged if a risk materializes. It is calculated by dividing the amount of damage by the asset value. In this case, that is $20 million in damage divided by the $100 million facility value, or 20%.

Based on the information in this scenario, what is the annualized rate of occurrence for a flood at DataTech's data center?

0.002

0.005

0.02

0.05

Answer:
B.  The annualized rate of occurrence (ARO) is the number of times each year that risk analysts expect a risk to happen in any given year. In this case, the analysts expect floods once every 200 years, or 0.005 times per year.

Based on the information in this scenario, what is the annualized loss expectancy for a flood at DataTech's data center?

$40,000

$100,000

$400,000

$1,000,000

Answer:
B.  The annualized loss expectancy (ALE) is calculated by multiplying the single loss expectancy (SLE) by the annualized rate of occurrence (ARO). In this case, the SLE is $20 million, and the ARO is 0.005. Multiplying these numbers together gives you the ALE of $100,000.

Which accounts are typically assessed during an account management assessment?

A random sample

Highly privileged accounts

Recently generated accounts

Accounts that have existed for long periods of time

Answer:
B.  The most frequent target of account management reviews are highly privileged accounts, as they create the greatest risk. Random samples are the second most likely choice. Accounts that have existed for a longer period of time are more likely to have a problem due to privilege creep than recently created accounts, but neither of these choices is likely unless there is a specific organizational reason to choose them.

Cloud computing uses a shared responsibility model for security, where the vendor and customer both bear some responsibility for security. The division of responsibility depends upon the type of service used. Place the cloud service offerings listed here in order from the case where the customer bears the LEAST responsibility to where the customer bears the MOST responsibility.

IaaS

SaaS

PaaS

1, 2, 3

2, 1, 3

3, 2, 1

2, 3, 1

Answer:
D.  The cloud service offerings in order from the case where the customer bears the least responsibility to where the customer bears the most responsibility are SaaS, PaaS, and IaaS. In an infrastructure-as-a-service (IaaS) cloud computing model, the customer retains responsibility for managing operating system and application security, while the vendor manages security at the hypervisor level and below. In a platform-as-a-service (PaaS) environment, the vendor takes on responsibility for the operating system, but the customer writes and configures any applications. In a software-as-a-service (SaaS) environment, the vendor takes on responsibility for the development and implementation of the application while the customer merely configures security settings within the application.

Jill wants to use a breach attack system to test her organization's security. Which of the following is not typically part of a BAS solution's portfolio of testing platforms?

User-owned mobile devices

Software agents

Software-as-a-service platforms

Virtual machines

Answer:
A.  Breach-and-attack simulation (BAS) tools typically leverage SaaS platforms as well as software agents and virtual machines to perform simulated attacks, which they leverage to provide detailed reports about security issues and their relative risk levels.

An emergency button under the desk is a common example of what type of physical security system?

An airgap button

A keylogger

A pushbutton lock

A duress system

Answer:
D.  Duress systems are intended to allow employees to notify security or others when they are in a dangerous situation or when they need help. Duress systems may be as simple as a push button and as complex as a code word or digital system that allows specific entries to trigger alarms while still performing a desired or deceptive but real-appearing action.

Henry runs Nikto against an Apache web server and receives the output shown here.

Larger View
A screenshot of Nikto output against an Apache web server. It includes values for target I P, target hostname, target port, and start time.
Which of the following statements is the least important to include in his report?

The missing clickjacking x-frame options could be used to redirect input to a malicious site or frame.

Cross-site scripting protections should be enabled, but aren't.

Inode information leakage from a Linux system is a critical vulnerability allowing direct access to the filesystem using node references.

The server is a Linux server.

Answer:
C.  While inode information leakage could represent a security concern, it does not pose the same immediate and direct risk as clickjacking, XSS vulnerabilities, or even the contextual importance of knowing the server's operating system. Clickjacking and cross-site scripting are both important issues, and knowing that the server is a Linux server is also important.

George is assisting a prosecutor with a case against a hacker who attempted to break into the computer systems at George's company. He provides system logs to the prosecutor for use as evidence, but the prosecutor insists that George testify in court about how he gathered the logs. What rule of evidence requires George's testimony?

Testimonial evidence rule

Parol evidence rule

Best evidence rule

Hearsay rule

Answer:
D.  The hearsay rule says that a witness cannot testify about what someone else told them, except under very specific exceptions. The courts have applied the hearsay rule to include the concept that attorneys may not introduce logs into evidence unless they are authenticated by the system administrator. In this scenario, George might also be able to provide a sworn affidavit, but the question doesn't include that option. The best evidence rule states that copies of documents may not be submitted into evidence if the originals are available. The parol evidence rule states that if two parties enter into a written agreement, that written document is assumed to contain all of the terms of the agreement. Testimonial evidence is a type of evidence, not a rule of evidence.

Which of the following is not a valid use for key risk indicators (KRIs)?

Provide warnings before issues occur.

Provide real-time incident response information.

Provide historical views of past incidents.

Provide insight into risk tolerance for the organization.

Answer:
B.  Key risk indicators (KRIs) are valuable for organizational risk planning and understanding risk perceptions but are not designed for real-time security incident response. Tools like intrusion prevention systems (IPSs), security information and event management (SIEM) systems, and others are better equipped for immediate threat detection and response.

Which one of the following malware types uses built-in propagation mechanisms that exploit system vulnerabilities to spread?

Trojan horse

Worm

Logic bomb

Virus

Answer:
B.  Worms have built-in propagation mechanisms that do not require user interaction, such as scanning for systems containing known vulnerabilities and then exploiting those vulnerabilities to gain access. Viruses and Trojan horses typically require user interaction to spread. Logic bombs do not spread from system to system but lie in wait until certain conditions are met, triggering the delivery of their payload.

As part of your company's security team, you have been asked to advise on how to ensure that media is not improperly used or stored. What solution will help staff members in your organization to handle media appropriately?

Labeling with sensitivity levels

Encrypting the sensitive media

Dual control media systems

A clear desk policy

Answer:
A.  As simple as the answer may seem, labeling media or even color coding it with sensitivity levels and ensuring staff are appropriately trained on what the levels mean will normally have the biggest impact. Encrypting media can help, but without the labels, files may be stored on inappropriate media. A clear desk policy can help if casual media theft is an issue but is not likely to be an important control in this scenario. Dual control is used to ensure that a task cannot be performed by a single staff member to avoid malfeasance and is not directly useful here.

Alaina wants to use a broadly adopted threat modeling framework for her organization's threat intelligence efforts. Which of the following would you advise her to adopt if she wants to use pre-existing tools to help her threat modeling team integrate both internally created intelligence and external threat feed data?

The Diamond Model of Intrusion Analysis

ATT&CK

Microsoft's Threat-JUMP modeling system

Threat-EN

Answer:
B.  MITRE's ATT&CK framework is broadly adopted by threat modeling and threat intelligence organizations and is used as a default model in many software packages and tools. The Diamond Model specifically addresses how to think about intrusions but does not address broader threats, and the other answers were made up for this question.

Which one of the following is not a principle of the Agile approach to software development?

The most efficient method of conveying information is electronic.

Working software is the primary measure of progress.

Simplicity is essential.

Businesspeople and developers must work together daily.

Answer:
A.  The Agile approach to software development states that working software is the primary measure of progress, that simplicity is essential, and that businesspeople and developers must work together daily. It also states that the most efficient method of conveying information is face to face, not electronic.

Harry is concerned that accountants within his organization will modify data to cover up fraudulent activity in accounts that they normally access. Which one of the following controls would best defend against this type of attack?

Encryption

Access controls

Integrity verification

Firewalls

Answer:
C.  Integrity verification software would protect against this attack by identifying unexpected changes in protected data. Encryption, access controls, and firewalls would not be effective in this example because the accountants have legitimate access to the data.

CAPEC, STIX, and TAXII are all used for what purpose?

Federated authentication

Vulnerability scanning

Threat intelligence feeds

Risk assessment and relative ranking

Answer:
C.  CAPEC, or Common Attack Pattern Enumeration and Classification, is a dictionary of known attack patterns. STIX is the Structured Threat Information eXpression language used to describe threats in a standardized way, and TAXII, the Trusted Automated eXchange of Indicator Information, defines how threat information can be shared and exchanged. All of these are examples of threat intelligence feed standards.

Meena wants to ensure that her supply chain risks are well managed. Which of the following is not a common practice she should include in her supply chain risk management (SCRM) plan?

Using contractual controls such as insurance and liability limitations where appropriate

Relying on a single vendor to provide vendor stability

Ensuring multiple suppliers exist for critical components

Validating the financial stability of potential suppliers

Using the following table and your knowledge of the auditing process, answer questions 38–40.

Larger View
A table depicts the auditing process. The column titles are SO C reports, report content, and audience. It includes S O C 1, S O C 2, and S O C 3 with corresponding content and audience.
Answer:
B.  Sole sourcing, or relying on a single vendor, can create additional fragility in supply chains due to reliance on a single supplier. Contractual controls including requirements for supplier insurance and liability limitations, having multiple suppliers, and validating their financial stability are all common ways to help reduce supply chain risk.

As they prepare to migrate their data center to an infrastructure-as-a-service (IaaS) provider, Susan's company wants to understand the effectiveness of their new provider's security, integrity, and availability controls. What SOC report would provide them with the most detail, including input from the auditor on the effectiveness of controls at the IaaS provider?

SOC 1.

SOC 2.

SOC 3.

None of the SOC reports is suited to this, and they should request another form of report.

Answer:
B.  SOC 2 reports are released under NDA to select partners or customers and can provide details on the controls and any issues they may have. A SOC 1 report would provide only financial control information, and a SOC 3 report provides less information since it is publicly available.

Susan wants to ensure that the audit report that her organization requested includes input from an external auditor and information about control implementation over a period of time. What type of report should she request?

SOC 2, Type 1

SOC 3, Type 1

SOC 2, Type 2

SOC 3, Type 2

Answer:
C.  An SOC 2, Type 2 report includes information about a data center's security, availability, processing integrity, confidentiality, and privacy, and includes an auditor's opinion on the operational effectiveness of the controls. SOC 3 does not have types, and a SOC 2 Type 1 is only conducted at a point in time.

When Susan requests a SOC 2 report, she receives a SOC 1 report. What issue should Susan raise?

SOC 1 reports only reveal publicly available information.

SOC 1 reports cover financial data.

SOC 1 reports cover only a point in time.

SOC 1 reports use only a three-month period for testing.

Answer:
B.  Susan asked for a security controls report (SOC 2) and received a financial internal controls report (SOC 1). This question doesn't specify whether a Type 1 or Type 2 report is desired, but most security practitioners will prefer a Type 2 report if they can get it since it tests the actual controls and their implementation instead of their descriptions.

Which group is best suited to evaluate an organization's administrative controls and provide credible reports to a third party?

Internal auditors

Penetration testers

External auditors

Employees who design, implement, and monitor the controls

Answer:
C.  External auditors can provide an unbiased and impartial view of an organization's controls to third parties. Internal auditors are useful when reporting to senior management of the organization but are typically not asked to report to third parties. Penetration tests test technical controls but are not as well suited to testing many administrative controls. The employees who build and maintain controls are more likely to bring a bias to the testing of those controls and should not be asked to report on them to third parties.

Bell–LaPadula is an example of what type of access control model?

DAC

RBAC

MAC

ABAC

Answer:
C.  Bell–LaPadula uses security labels on objects and clearances for subjects and is therefore a MAC model. It does not use discretionary, rule-based, role-based, or attribute-based access control.

Martha is the information security officer for a small college and is responsible for safeguarding the privacy of student records. What law most directly applies to her situation?

HIPAA

HITECH

COPPA

FERPA

Answer:
D.  The Family Educational Rights and Privacy Act (FERPA) protects the privacy of students in any educational institution that accepts any form of federal funding. HIPAA is the Health Insurance Portability and Accountability Act and protects sensitive patient data in the hands of insurance and medical providers. The HITECH focuses on electronic health records and data security for healthcare data. COPPA is the Children's Online Privacy Protection Act.

What U.S. federal law mandates the security of protected health information?

FERPA

SAFE Act

GLBA

HIPAA

Answer:
D.  The Health Insurance Portability and Accountability Act (HIPAA) mandates the protection of protected health information (PHI). The Secure and Fair Enforcement for Mortgage Licensing (SAFE) Act deals with mortgages, the Graham–Leach–Bliley Act (GLBA) covers financial institutions, and the Family Educational Rights and Privacy Act (FERPA) deals with student data.

Gurvinder wants to test a potentially malicious file while observing what it does when executed. What type of tool should he identify to allow him to do this?

A SIEM

A SOAR

A SAST tool

A sandboxing tool

Answer:
D.  Sandboxing tools allow defenders to execute potentially malicious software in an isolated environment that provides instrumentation to capture all actions and changes performed when it is run. SIEM, or security information and event management, tools and SOAR, or security orchestration, automation, and response, tools are used to monitor environments and to respond to incidents but do not provide the ability to test and observe malicious software. SAST, or Static Application Security Testing, tools analyze source code to identify security issues.

Susan is configuring her network devices to use syslog. What should she set to ensure that she is notified about issues but does not receive normal operational issue messages?

The facility code

The log priority

The security level

The severity level

Answer:
D.  Implementations of syslog vary, but most provide a setting for severity level, allowing the configuration of a value that determines what messages are sent. Typical severity levels include debug, informational, notice, warning, error, critical, alert, and emergency. The facility code is also supported by syslog but is associated with which services are being logged. Security level and log priority are not typical syslog settings.

What RAID level is commonly used for distributed parity, allowing for resilience while being space efficient?

RAID 0

RAID 1

RAID 3

RAID 5

Answer:
D.  RAID 5 is commonly used because it balances resilience and efficiency of storage space used by relying on distributed parity. RAID 0 uses two disks as a single volume, allowing for an increase in speed but a decrease in reliability. In RAID 1, also known as disk mirroring, systems contain two physical disks. Each disk contains copies of the same data, and either one may be used in the event the other disk fails RAID 3 is rarely used and uses byte-level striping and a dedicated parity disk.

Isaac recently purchased a 48-port switch from his switch vendor. The switch vendor has announced that the model of the switch that Isaac purchased will reach its end of life next year. What does this tell Isaac about the devices?

The devices will stop being sold next year.

The devices will stop functioning next year.

The devices will no longer be supported next year.

The devices will be supported for a minimum of three more years.

Answer:
A.  Most vendors use the term end of life, or EOL, to denote when the product will stop being sold. End of support typically comes sometime after end of life, and this problem does not specify when end of support (EOS) will occur. Devices will still function after end of life and likely after end of support, but security professionals should raise concerns about the security of devices or software after the end of support because patches and updates will likely no longer be available.

Surveys, interviews, and audits are all examples of ways to measure what important part of an organization's security posture?

Code quality

Service vulnerabilities

Awareness

Attack surface

Answer:
C.  Interviews, surveys, and audits are all useful for assessing awareness. Code quality is best judged by code review, service vulnerabilities are tested using vulnerability scanners and related tools, and the attack surface of an organization requires both technical and administrative review.

Sharon wants to help her company's developers understand the risks of API calls that allow over-consumption of resources like CPU, memory, or network bandwidth. What is the primary risk created by unconstrained API calls in this scenario?

Inability to attribute actions to an account

Denial of service

Malicious access to files

The potential for request forgery attacks

Answer:
B.  Unconstrained API calls can lead to denial-of-service conditions, one of the top 10 API security risks identified by OWASP in 2023. Attributing actions to an account requires proper authentication and logging, which are not tied to resource over-consumption. Malicious file access is typically due to improperly configured security, and request forgery attacks typically occur when user-supplied URIs are not validated.

What type of authenticator generates dynamic passwords using time- or algorithm-based methods?

A biometric scanner

A smart card

A token

A CAC

Answer:
C.  Tokens are hardware devices (something you have) that generate a one-time password (OTP) based on time or an algorithm. They are typically combined with another factor like a password to authenticate users. CAC and PIV cards are U.S. government–issued smartcards.

Fred's new employer has hired him for a position with access to their trade secrets and confidential internal data. What legal tool should they use to help protect their data if he chooses to leave to work at a competitor?

A stop-loss order

An NDA

An AUP

Encryption

Answer:
B.  A nondisclosure agreement (NDA) is a legal agreement between two parties that specifies what data they will not disclose. NDAs are common in industries that have sensitive or trade secret information they do not want employees to take to new jobs. Encryption would only help in transit or at rest, and Fred will likely have access to the data in unencrypted form as part of his job. An AUP is an acceptable use policy, and a stop-loss order is used on the stock market.

Mark's company is involved in a civil case. What evidentiary standard is he likely to need to meet?

The real evidence standard

Beyond a reasonable doubt

Preponderance of evidence

The documentary evidence standard

Answer:
C.  Civil cases typically rely on a preponderance of evidence. Criminal cases must be proven beyond a reasonable doubt. Real evidence is object evidence—tangible things that can be brought into a court of law. Documentary evidence are written items used to prove facts. Neither of these is an evidentiary standard; instead, they describe types of evidence.

How many possible keys exist when using a cryptographic algorithm that has an 8-bit binary encryption key?

16

128

256

512

Answer:
C.  Binary key spaces contain a number of keys equal to 2 raised to the power of the number of bits. Two to the eighth power is 256, so an 8-bit key space contains 256 possible keys.

What activity is being performed when you apply security controls based on the specific needs of the IT system that they will be applied to?

Standardizing

Baselining

Scoping

Editing

Answer:
C.  Scoping is the process of reviewing and selecting security controls based on the system that they will be applied to. Editing is not a commonly used term in this context. Baselines are used as a base set of security controls, often from a third-party organization that creates them. Standardization isn't a relevant term here.

Dawson is preparing to hire a new staff member for a role that requires very high levels of integrity and trust. Which of the following is most commonly used as part of the hiring process to determine if an employee is likely to be trustworthy?

Signing an NDA

A background check

Signing a noncompete

A COA

Answer:
B.  Background checks are frequently performed to identify potential issues before hiring a new employee. They can identify a variety of concerns and are commonly used across many industries. Nondisclosure agreements (NDAs) are used during and after employment to protect confidential information. Noncompetes are used to prevent employees from working in a similar industry for a given period of time after departure. COA, or certificate of authenticity, is not used in employment situations.

Ben's job is to ensure that data is labeled with the appropriate sensitivity label. Since Ben works for the U.S. government, he has to apply the labels Unclassified, Confidential, Secret, and Top Secret to systems and media. If Ben is asked to label a system that handles Secret, Confidential, and Unclassified information, how should he label it?

Mixed classification

Confidential

Top Secret

Secret

Answer:
D.  Systems and media should be labeled with the highest level of sensitivity that they store or handle. In this case, based on the U.S. government classification scheme, the highest classification level in use on the system is Secret. Mixed classification provides no useful information about the level, whereas Top Secret and Confidential are too high and too low, respectively.

Susan has discovered that the smart card–based locks used to keep the facility she works at secure are not effective because staff members are propping the doors open. She places signs on the doors reminding staff that leaving the door open creates a security issue, and she adds alarms that will sound if the doors are left open for more than five minutes. What type of controls has she put into place?

Physical

Administrative

Compensating

Recovery

Answer:
C.  She has placed compensating controls in place. Compensating controls are used when controls like the locks in this example are not sufficient. While the alarm is a physical control, the signs she posted are not. Similarly, the alarms are not administrative controls. None of these controls helps to recover from an issue, and they are thus not recovery controls.

Ben's organization has purchased cybersecurity insurance. What type of risk treatment has the organization engaged in?

Acceptance

Avoidance

Mitigation

Transfer

Answer:
D.  Insurance is a form of risk transfer. Organizations pay insurers premiums, transferring the risk to them in exchange for the payment. Insurers may mitigate their risk through the terms of the insurance policy and may also insure themselves. Acceptance simply means acknowledging the risk, avoidance would require means to prevent the risk from occurring, and mitigation attempts to reduce the impact of the risk if it occurs.

Brad wants to engage third-party auditors to assess a vendor that his company will be signing a contract with. If Brad wants to assess the vendor's security policies and controls as well as the effectiveness of those controls as implemented over time, what SOC level and type should he request the auditors perform?

A SOC 1, Type 2

A SOC 2, Type 1

A SOC 1, Type 1

A SOC 2, Type 2

Answer:
D.  A SOC 2 assessment looks at controls that affect security, and a Type 2 report validates the operating effectiveness of the controls. SOC 1 engagement assesses controls that might impact financial reporting, and a Type 1 report provides the auditors opinions of the descriptions of controls provided by management at a single point in time—not the actual implementations of the controls.

Lucca's manager does not want to adopt an open-source software package for their organization's web application stack. What software security advantage is the most important when considering open-source software packages?

The fact that the code is not compiled

The fact the code is free

The ability to inspect the code

The ability to change the code

Answer:
C.  The ability to inspect open-source software (OSS) means that organizations can inspect it but more importantly that others can and often have also inspected it. This results in software that has had far more review than some closed-source or commercial packages (although large organizations may perform more review). The ability to change the code can sometimes be important as well, but changing open-source code in-house can create maintenance issues in the future. Open-source software may be compiled, but the source will still be available. The code being free is not a security advantage or disadvantage.

As part of hiring a new employee, Kathleen's identity management team creates a new user object and ensures that the user object is available in the directories and systems where it is needed. What is this process called?

Registration

Provisioning

Population

Authenticator loading

Answer:
B.  Provisioning includes the creation, maintenance, and removal of user objects from applications, systems, and directories. Registration occurs when users are enrolled in a biometric system; population and authenticator loading are not common industry terms.

What phase of the change management process for software occurs when changes are finalized?

Request control

Configuration control

Release control

Change control

Answer:
C.  Release control occurs after changes are finalized. With changes that are ready to be implemented in hand, release managers can follow their process with steps that typically include removing debugging code and conducting acceptance testing. Request control is the start of a process that allows users to submit change requests, while change control handles the process of ensuring quality assurance happens, that documentation is done, and that security testing is handled. Finally, configuration control is part of software configuration management, not the change process.

Alice is designing a cryptosystem for use by six users and would like to use a symmetric encryption algorithm. She wants any two users to be able to communicate with each other without worrying about eavesdropping by a third user. How many symmetric encryption keys will she need to generate?

6

12

15

30

Answer:
C.  The formula for determining the number of encryption keys required by a symmetric algorithm is ((n*(n − 1))/2). With six users, you will need ((6*5)/2), or 15 keys.

Which one of the following intellectual property protection mechanisms has the shortest duration in the United States?

Copyright

Patent

Trademark

Trade secret

Answer:
B.  Patents have the shortest duration of the techniques listed: at most, 20 years. Copyrights last for 70 years beyond the death of the author if owned by an individual, or 95 years from publication or 120 years from creation if owned by a corporation. Trademarks are renewable indefinitely, and trade secrets are protected as long as they remain secret.

Gordon is working on a business continuity plan for a manufacturing company's IT operations, which is located in North Dakota. The company is currently assessing the risk of an earthquake and has decided to adopt a risk acceptance strategy. Which of the following actions is in line with this strategy?

Purchasing earthquake insurance

Relocating the data center to a safer area

Documenting the decision-making process

Reengineering the facility to withstand the shock of an earthquake

Answer:
C.  In a risk acceptance strategy, the organization chooses to take no action other than documenting the risk. Purchasing insurance would be an example of risk transference. Relocating the data center would be risk avoidance. Reengineering the facility is an example of a risk mitigation strategy.

Carol would like to implement a control that protects her organization from the momentary loss of power to the data center. Which control is most appropriate for her needs?

Redundant servers

RAID

UPS

Generator

Answer:
C.  Uninterruptible power supplies (UPSs) provide immediate, battery-driven power for a short period of time to cover momentary losses of power. Generators are capable of providing backup power for a sustained period of time in the event of a power loss, but they take time to activate. RAID and redundant servers are high-availability controls but do not cover power loss scenarios.

Ben has encountered problems with users in his organization reusing passwords, despite a requirement that they change passwords every 30 days. What type of password setting should Ben employ to help prevent this issue?

Longer minimum age

Increased password complexity

Implement password history

Implement password length requirements

Answer:
C.  Password histories retain a list of previous passwords, preferably a list of salted hashes for previous passwords, to ensure that users don't reuse their previous passwords. Longer minimum age can help prevent users from changing their passwords and then changing them back but won't prevent a determined user from eventually getting their old password back. Length requirements and complexity requirements tend to drive users to reuse passwords if they're not paired with tools like single sign-on, password storage systems, or other tools that decrease the difficulty of password management.

Chris is conducting a risk assessment for his organization and has determined the amount of damage that a single flood could be expected to cause to his facilities. What metric has Chris identified?

ALE

SLE

ARO

AV

Answer:
B.  The single loss expectancy (SLE) is the amount of damage that a risk is expected to cause each time it occurs. ALE is the annual loss expectancy (probability of loss times reduction in value if a loss occurs), ARO is the annual rate of occurrence or how often in a given year the event is likely to happen, and AV is the asset value.

The removal of a hard drive from a PC before it is retired and sold as surplus is an example of what type of action?

Purging

Sanitization

Degaussing

Destruction

Answer:
B.  Sanitization includes steps such as removing the hard drive and other local storage from PCs before they are sold as surplus. Degaussing uses magnetic fields to wipe media, purging is an intense form of clearing used to ensure that data is removed and unrecoverable from media, and removing does not necessarily imply destruction of the drive.

During which phase of the incident response process would an organization determine whether it is required to notify law enforcement officials or other regulators of the incident?

Detection

Recovery

Remediation

Reporting

Answer:
D.  During the Reporting phase, incident responders assess their obligations under laws and regulations to report the incident to government agencies and other regulators.

Every 90 days, the staff in Charles's department at his bank switch tasks as part of the organization's normal processes to ensure that an individual does not exploit their privileges. What security practice is his organization engaging in?

Dual control

Job rotation

Cross-training

Offboarding

Answer:
B.  The bank that Charles works at is using job rotation to ensure that employees are not exploiting the rights and permissions that they have in their roles. The practice is intended to allow the next person in the role to identify irregularities and to prevent individuals from hiding malfeasance. Dual control requires two or more staff members to complete a task to ensure that a single employee cannot abuse their role. Cross-training ensures that multiple staff members have the necessary skills for a task, reducing the impact of losing a staff member.

Michelle oversees her organization's endpoint security, focusing on mobile device management and the recovery of lost or stolen devices. Which of the following recommendations will most effectively ensure data protection if a device is stolen?

Mandatory passcodes and application management

Full device encryption and mandatory passcodes

Remote wipe and GPS tracking

GPS tracking and full device encryption

Answer:
B.  Full device encryption, when combined with mandatory passcodes, offers the strongest defense against data loss from stolen devices. Encryption secures data at rest, making it unreadable without the correct decryption key, while passcodes provide an initial barrier against unauthorized access. Although application management, remote wipe, and GPS tracking are valuable for overall device security and recovery, they do not offer the same level of data protection as encryption and passcodes. Specifically, encryption ensures data security independently of the device's network connectivity or physical location.

Susan's SMTP server does not authenticate senders before accepting and relaying emails. What is this security configuration issue known as?

An email gateway

An SMTP relay

An X.400-compliant gateway

An open relay

For questions 75–77, please refer to the following scenario:

The large business that Jack works for has been using noncentralized logging for years. They have recently started to implement centralized logging, however, and as they reviewed logs, they discovered a breach that appeared to have involved a malicious insider.

Answer:
D.  SMTP servers that don't authenticate users before relaying their messages are known as open relays. Open relays that are Internet-exposed are typically quickly exploited to send email for spammers.

When the breach was discovered and the logs were reviewed, it was discovered that the attacker had purged the logs on the system that they compromised. How can this be prevented in the future?

Encrypt local logs.

Require administrative access to change logs.

Enable log rotation.

Send logs to a secure log server.

Answer:
D.  Sending logs to a secure log server is the most effective way to ensure that logs survive a breach. Encrypting local logs won't stop an attacker from deleting them, and requiring administrative access won't stop attackers who have breached a machine and acquired escalated privileges. Log rotation archives logs based on time or file size and can also purge logs after a threshold is hit. Rotation won't prevent an attacker from purging logs.

How can Jack detect issues such as this using his organization's new centralized logging?

Deploy and use an IDS.

Send logs to a central logging server.

Deploy and use a SIEM tool.

Use syslog.

Answer:
C.  A security information and event management (SIEM) tool is designed to provide automated analysis and monitoring of logs and security events. A SIEM tool that receives access to logs can help detect and alert on events such as logs being purged or other breach indicators. An IDS can help detect intrusions, but IDSs are not typically designed to handle central logs. A central logging server can receive and store logs but won't help with analysis without taking additional actions. Syslog is simply a log format.

How can Jack best ensure accountability for actions taken on systems in his environment?

Log review and require digital signatures for each log.

Require authentication for all actions taken and capture logs centrally.

Log the use of administrative credentials and encrypt log data in transit.

Require authorization and capture logs centrally.

Answer:
B.  Requiring authentication can help provide accountability by ensuring that any action taken can be tracked back to a specific user. Storing logs centrally ensures that users can't erase the evidence of actions that they have taken. Log review can be useful when identifying issues, but digital signatures are not a typical part of a logging environment. Logging the use of administrative credentials helps for those users but won't cover all users, and encrypting the logs doesn't help with accountability. Authorization helps, but being able to specifically identify users through authentication is more important.

Ed's organization has 5 IP addresses allocated to them by their ISP but needs to connect more than 100 computers and network devices to the Internet. What technology can he use to connect his entire network via the limited set of IP addresses he can use?

IPsec

PAT

SDN

IPX

Answer:
B.  Port address translation (PAT) is used to allow a network to use any IP address set inside without causing a conflict with the public Internet. PAT is often confused with network address translation (NAT), which maps one internal address to one external address. IPsec is a security protocol suite, software-defined networking (SDN) is a method of defining networks programmatically, and IPX is a non-IP network protocol.

What type of attack would the following precautions help prevent?

Requesting proof of identity

Requiring callback authorizations on voice-only requests

Not changing passwords via voice communications

DoS attacks

Worms

Social engineering

Shoulder surfing

Answer:
C.  Each of the precautions listed helps to prevent social engineering by helping prevent exploitation of trust. Avoiding voice-only communications is particularly important, since establishing identity over the phone is difficult. The other listed attacks would not be prevented by these techniques.

The CIS benchmarks are an example of what sort of compliance tool?

A security baseline

A compliance standard

A secure provisioning tool

A security automation tool

Answer:
A.  The CIS benchmarks provide a useful security standard and baseline to assess systems against or to configure them to. Organizations can adapt and modify the baseline to meet their specific needs while speeding up deployment by using an accepted industry standard. They are not a compliance standard and do not provide provisioning or automation, but tools that do may use the benchmark as a standard to do so.

Residual data is another term for what type of data left after attempts have been made to erase it?

Leftover data

MBR

Bitrot

Remnant data

Answer:
D.  Remnant data is data that is left after attempts have been made to remove or erase it. Bitrot is a term used to describe aging media that decays over time. MBR is the master boot record, a boot sector found on hard drives and other media. Leftover data is not an industry term.

Which one of the following disaster recovery test types involves the actual activation of the disaster recovery facility?

Simulation test

Tabletop exercise

Parallel test

Checklist review

Answer:
C.  During a parallel test, the team activates the disaster recovery site for testing, but the primary site remains operational. A simulation test involves a role-play of a prepared scenario overseen by a moderator. Responses are assessed to help improve the organization's response process. The checklist review is the least disruptive type of disaster recovery test. During a checklist review, team members each review the contents of their disaster recovery checklists on their own and suggest any necessary changes. During a tabletop exercise, team members come together and walk through a scenario without making any changes to information systems.

What access control system lets owners decide who has access to the objects they own?

Role-based access control

Task-based access control

Discretionary access control

Rule-based access control

Answer:
C.  Discretionary access control gives owners the right to decide who has access to the objects they own. Role-based access control uses administrators to make that decision for roles or groups of people with a role, task-based access control uses lists of tasks for each user, and rule-based access control applies a set of rules to all subjects.

Using a trusted channel and link encryption are both ways to prevent what type of access control attack?

Brute-force

Spoofed login screens

Man-in-the-middle attacks

Dictionary attacks

Answer:
C.  Trusted paths that secure network traffic from capture and link encryption are both ways to help prevent man-in-the-middle attacks. Brute-force and dictionary attacks can both be prevented using back-off algorithms that slow down repeated attacks. Log analysis tools can also create dynamic firewall rules, or an IPS can block attacks like these in real time. Spoofed login screens can be difficult to prevent, although user awareness training can help.

Which one of the following is not one of the canons of the ISC2 Code of Ethics?

Protect society, the common good, necessary public trust and confidence, and the infrastructure.

Act honorably, honestly, justly, responsibly, and legally.

Provide diligent and competent service to principals.

Maintain competent records of all investigations and assessments.

Answer:
D.  The four canons of the ISC2 Code of Ethics are to protect society, the common good, the necessary public trust and confidence, and the infrastructure; act honorably, honestly, justly, responsibly, and legally; provide diligent and competent service to principals; and advance and protect the profession.

Which one of the following components should be included in an organization's emergency response guidelines?

Immediate response procedures

Long-term business continuity protocols

Activation procedures for the organization's cold sites

Contact information for ordering equipment

Answer:
A.  The emergency response guidelines should include the immediate steps an organization should follow in response to an emergency situation. These include immediate response procedures, a list of individuals who should be notified of the emergency, and secondary response procedures for first responders. They do not include long-term actions such as activating business continuity protocols, ordering equipment, or activating DR sites.

Ben is working on integrating a federated identity management system and needs to exchange authentication and authorization information for browser-based single sign-on. What technology is his best option?

HTML

XACML

SAML

SPML

Answer:
C.  Security Assertion Markup Language (SAML) is the best choice for providing authentication and authorization information, particularly for browser-based SSO. HTML is primarily used for web pages, SPML is used to exchange user information for SSO, and XACML is used for access control policy markup.

What is the minimum interval at which an organization should conduct business continuity plan refresher training for those with specific business continuity roles?

Weekly

Monthly

Semiannually

Annually

Answer:
D.  Individuals with specific business continuity roles should receive training on at least an annual basis.

What three types of interfaces are typically tested during software testing?

Network, physical, and application interfaces

APIs, UIs, and physical interfaces

Network interfaces, APIs, and UIs

Application, programmatic, and user interfaces

Answer:
B.  Application programming interfaces (APIs), user interfaces (UIs), and physical interfaces are all tested during the software testing process. Network interfaces are not typically tested, and programmatic interfaces are another term for APIs.

Amanda's company has been looking for ways to reduce their costs for network switches and routers and has started to acquire devices from the gray market. Which of the following is not a typical concern for gray-market devices?

API vulnerabilities

Product tampering

Implants

Counterfeits

Answer:
A.  Product tampering, implants of software or hardware, and counterfeits are all common concerns for gray-market hardware. API vulnerabilities are a concern based on vendor software and may exist and require patching whether a device is purchased through an OEM or the gray market.

Andre has implemented virtual routing and forwarding (VRF) on his router. Which of the following descriptions best explains what this allows him to do?

VRF is used to support VPCs.

VRF is like a VPN at layer 3.

VRF is like a VLAN at layer 3.

VRF is used to support multilayer protocols.

Answer:
C.  Virtual routing and forwarding (VRF) allows multiple routing tables to be used on the same device simultaneously. This is similar to the concept of VLANs on a layer 2 switch but operating at layer 3. Routing instances operate independently, allowing IP addresses to overlap without conflict, supporting segmentation and thus permitting flexibility for zero trust implementations and other security solutions. VRF can be used to support VPCs, but that is not its only use. It is not like a VPN, and while it can be used with multilayer protocols, that isn't a primary purpose.

Ben is selecting an encryption algorithm for use in an organization with 10,000 employees. He must facilitate communication between any two employees within the organization. Which one of the following algorithms would allow him to meet this goal with the least time dedicated to key management?

RSA

IDEA

3DES

Skipjack

Answer:
A.  RSA is an asymmetric encryption algorithm that requires only two keys for each user. IDEA, 3DES, and Skipjack are all symmetric encryption algorithms and would require a key for every unique pair of users in the system.

Grace uses her cloud service provider's function-as-a-service (FaaS) environment to deploy her organization's new application. What term should she use to describe this to her organization's leadership?

ICS

A VPC

Embedded

Serverless

Answer:
D.  Function-as-a-service deployments are an example of a serverless deployment running on the cloud provider's cloud environment. Serverless computing solutions like AWS Lambda, Microsoft Azure Functions, and Google Cloud functions require less overhead when applications are designed from the ground up to leverage function as a service technology. ICS is an industrial control system used to manage systems and processes such as utilities or factories. VPCs are virtual private clouds where infrastructure is provisioned and used like a virtual data center, and embedded systems are built into other devices.

What type of log file is shown here?

Larger View
A screenshot of a sample log file.
Application

Web server

System

Firewall

Answer:
D.  The log entries contained in this example show the allow/deny status for inbound and outbound TCP and UDP sessions. This is, therefore, an example of a firewall log.

Which one of the following activities transforms a zero-day vulnerability into a less dangerous attack vector?

Discovery of the vulnerability

Implementation of transport-layer encryption

Reconfiguration of a firewall

Release of a security patch

Answer:
D.  Zero-day vulnerabilities remain in the dangerous zero-day category until the release of a patch that corrects the vulnerability. At that time, it becomes the responsibility of IT professionals to protect their systems by applying the patch. Implementation of other security controls, such as encryption or firewalls, does not change the nature of the zero-day vulnerability.

Elle's organization has had to shift to remote work. Each staff member needs access to specific applications, and due to the quick shift, staff members are working from systems that may be home systems or borrowed laptops. What is the best option for remote access in a situation like the one that Elle is facing?

An IPsec VPN

A dedicated fiber connection to each remote work location

An HTML5-based VPN

Use of remote desktop to connect to an existing workstation at the company's office building

Answer:
C.  An HTML5-based VPN will provide Elle's staff with access to the applications they need without requiring the installation of a client that might be challenging or impossible without managed machines. A client-based IPsec VPN provides additional opportunities for control that a broadly deployed base of directly accessed machines via RDP does not, making it the second-best choice here. Deploying fiber for direct connections for end users is not viable for most organizations based on cost and complexity.

Sameer's company has begun to deploy computation and storage capabilities to their industrial plants to gather and process data where it is created. What term best describes this type of deployment?

Cloud computing

Edge computing

Hybrid cloud

Microservices

For questions 98–101, please refer to the following scenario:

Matthew and Richard are friends located in different physical locations who would like to begin communicating with each other using cryptography to protect the confidentiality of their communications. They exchange digital certificates to begin this process and plan to use an asymmetric encryption algorithm for the secure exchange of email messages.

Answer:
B.  Edge computing is a technology that involves placing infrastructure closer to the point of use. This approach offers several benefits such as reduced latency, improved performance for local processing, and reduced traffic to remote data centers or the cloud. On the other hand, cloud computing is typically provided at a remote facility, is scalable and frequently multitenant. Hybrid cloud is a combination of local and remote clouds. Finally, microservices utilize loosely coupled services that communicate via lightweight protocols to accomplish specific tasks that are then combined to achieve overall goals.

When Matthew sends Richard a message, what key should he use to encrypt the message?

Matthew's public key

Matthew's private key

Richard's public key

Richard's private key

Answer:
C.  The sender of a message encrypts the message using the public key of the message recipient.

When Richard receives the message from Matthew, what key should he use to decrypt the message?

Matthew's public key

Matthew's private key

Richard's public key

Richard's private key

Answer:
D.  The recipient of a message uses their own private key to decrypt messages that were encrypted with the recipient's public key. This ensures that nobody other than the intended recipient can decrypt the message.

Matthew would like to enhance the security of his communication by adding a digital signature to the message. What goal of cryptography are digital signatures intended to enforce?

Secrecy

Availability

Confidentiality

Nonrepudiation

Answer:
D.  Digital signatures enforce nonrepudiation. They prevent individuals from denying that they were the actual originator of a message.

When Matthew adds a digital signature to the message, what encryption key does he use to create the digital signature?

Matthew's public key

Matthew's private key

Richard's public key

Richard's private key

Answer:
B.  An individual creates a digital signature by encrypting the message digest with their own private key.

When Jim logs into a system, his password is compared to a hashed value stored in a database. What is this process?

Identification

Hashing

Tokenization

Authentication

Answer:
D.  The comparison of a factor to validate an identity is known as authentication. Identification would occur when Jim presented his user ID. Tokenization is a process that converts a sensitive data element to a nonsensitive representation of that element. Hashing transforms a string of characters into a fixed-length value or key that represents the original string.

What is the top priority for security professionals when considering facility design?

Limiting access to only approved personnel

Ensuring that the structure supports least privilege

Ensuring the safety of personnel

Limiting the potential for weather or other natural disasters to impact operations

Answer:
C.  The most important item in facility design is the safety of personnel. Once designs take that into account, security, operational effectiveness, and other concerns can be addressed.

Which of the following types of controls does not describe an access control vestibule?

Deterrent

Preventive

Compensating

Physical

Answer:
C.  An access control vestibule (sometimes called a mantrap), which is composed of two sets of doors with an access mechanism that allows only one door to open at a time, is an example of a preventive access control because it can stop unwanted access by keeping intruders from accessing a facility due to an opened door or following legitimate staff in. It can serve as a deterrent by discouraging intruders who would be trapped in it without proper access, and of course, doors with locks are an example of a physical control. A compensating control attempts to make up for problems with an existing control or to add additional controls to improve a primary control.

Sally's organization needs to be able to prove that certain staff members sent emails, and she wants to adopt a technology that will provide that capability without changing their existing email system. What is the technical term for the capability Sally needs to implement as the owner of the email system, and what tool could she use to do it?

Integrity; IMAP

Repudiation; encryption

Nonrepudiation; digital signatures

Authentication; DKIM

Answer:
C.  To ensure emails can be definitively attributed to their senders, Sally needs the capability of nonrepudiation. Digital signatures fulfill this need by using cryptographic techniques to bind a sender's identity to a message, making it impossible for the sender to deny having sent the email. Unlike IMAP, which is a protocol for accessing email, and DKIM, which verifies the domain origin of an email, digital signatures provide cryptographic proof of origin and integrity. Encryption, while securing the content of messages, does not inherently provide nonrepudiation.

Which one of the following background checks is not normally performed during normal pre-hire activities?

Credit check

Reference verification

Criminal records check

Medical records check

Answer:
D.  In most situations, employers may not access medical information due to healthcare privacy laws. Reference checks, criminal records checks, and credit history reports are all typically found during pre-employment background checks.

Naomi's organization limits data access to only those users with roles that require it for their job. What key security operations practice does this describe?

Least privilege

Privileged account management

Job rotation

Privilege escalation

Answer:
A.  Naomi's organization operates under the concept of least privilege. Individuals only receive the rights that they need to accomplish their tasks. This also means that the organization will need to ensure that those rights do not accrue to users over time and that they are changed or removed when user roles change. Privileged account management is the process of properly managing accounts with higher levels of privilege like administrative accounts. Job rotation moves employees between roles to ensure that they do not take advantage of the role and that a new set of eyes can help identify problems. Privilege escalation is the process of gaining additional rights when attacking systems or services.

In the OSI model, when a packet changes from a data stream to a segment or a datagram, what layer has it traversed?

The Transport layer

The Application layer

The Data Link layer

The Physical layer

Answer:
A.  When a data stream is converted into a segment (TCP) or a datagram (UDP), it transitions from the Session layer to the Transport layer. This change from a message sent to an encoded segment allows it to then traverse the Network layer.

Tommy handles access control requests for his organization. A user approaches him and explains that he needs access to the human resources database in order to complete a head-count analysis requested by the CFO. What has the user demonstrated successfully to Tommy?

Clearance

Separation of duties

Need to know

Isolation

Answer:
C.  The user has successfully explained a valid “need to know” the data—completing the report requested by the CFO requires this access. However, the user has not yet demonstrated that they have appropriate clearance to access the information. A note from the CFO would meet this requirement.

Sharif wants to improve his organization's security awareness. He implements a process that gives points for identifying phishing emails and rewards departments based on their point scores. What awareness technique is he using?

Security champions

Gamification

Social engineering

Awareness training

Answer:
B.  Sharif is using gamification, the process of making awareness efforts like a game to motivate users. Security champions are staff members who are selected or volunteer to advocate for and raise security awareness in their teams and divisions. Social engineering efforts leverage human behaviors, and awareness training is training intended to raise awareness of security risks, issues, and attacker techniques.

What type of tool is most frequently used to match assets to users and owners in enterprises?

An enterprise content management tool

Barcoded property tags

RFID-based property tags

A system inventory

Answer:
D.  A system inventory is most frequently used to associate individuals with systems or devices. This can help when tracking their support history and aids in provisioning the proper tools, permissions, and data to a system. Both barcode and RFID property tags are used to identify systems, which can then be checked against a system inventory. Finally, enterprise content management tools are used to manage files and data as part of workflows and other business processes.

Alice would like to add another object to a security model and grant herself rights to that object. Which one of the rules in the Take-Grant protection model would allow her to complete this operation?

Take rule

Grant rule

Create rule

Remove rule

Answer:
C.  The create rule allows a subject to create new objects and also creates an edge from the subject to that object, granting rights to the new object.

Which of the following concerns should not be on Amanda's list of potential issues when penetration testers suggest using Metasploit during their testing?

Metasploit can only test vulnerabilities it has plug-ins for.

Penetration testing only covers a point-in-time view of the organization's security.

Tools like Metasploit can cause denial-of-service issues.

Penetration testing cannot test process and policy.

Answer:
A.  Metasploit provides an extensible framework, allowing penetration testers to create their own exploits in addition to those that are built into the tool. Unfortunately, penetration testing can only cover the point in time when it is conducted. When conducting a penetration test, the potential to cause a denial of service due to a fragile service always exists, but it can test processes and policies through social engineering and operational testing that validates how those processes and policies work.

Colin's organization has decommissioned multifunction photocopier/printer devices used throughout its administrative headquarters. What concern would be most likely to drive physical destruction of the device rather than allowing them to be sold as surplus?

Data remanence

Asset inventory

Asset management

Compliance

Answer:
A.  Data remanence is a concern due to the storage devices often found in multifunction photocopier/printer devices, particularly for devices used in an administrative headquarters. While compliance may be a concern, we don't know enough about Colin's organization to know if compliance concerns would require this. Asset management and asset inventory can both handle either destruction or sale for most organizations.

Which ITU-T standard should Alex expect to see in use when he uses his smartcard to provide a certificate to an upstream authentication service?

X.500

SPML

X.509

SAML

Answer:
C.  X.509 defines standards for public key certificates like those used with many smartcards. X.500 is a series of standards defining directory services. The Service Provisioning Markup Language (SPML) and the Security Assertion Markup Language (SAML) aren't standards that Alex should expect to see when using a smartcard to authenticate.

What type of websites are regulated under the terms of COPPA?

Financial websites not run by financial institutions

Healthcare websites that collect personal information

Websites that collect information from children

Financial websites run by financial institutions

Answer:
C.  The Children's Online Privacy Protection Act (COPPA) regulates websites that cater to children or knowingly collect information from children younger than 13.

Tracy recently accepted an IT compliance position at a federal government agency that works very closely with the Department of Defense on classified government matters. Which one of the following laws is least likely to pertain to Tracy's agency?

HIPAA

FISMA

HSA

CFAA

Answer:
A.  The Health Insurance Portability and Accountability Act (HIPAA) applies to healthcare information and is unlikely to apply in this situation. The Federal Information Security Modernization Act (FISMA) and Government Information Security Reform Act regulate the activities of all government agencies. The Homeland Security Act (HSA) created the U.S. Department of Homeland Security and, more importantly for this question, included the Cyber Security Enhancement Act of 2002 and the Critical Infrastructure Information Act of 2002. The Computer Fraud and Abuse Act (CFAA) provides specific protections for systems operated by government agencies.

Henry's organization wants to meet federal security standards for the cloud services it provides. What program should he investigate to meet this goal?

COBIT

SABSA

FedRAMP

PCI

Answer:
C.  FedRAMP is a U.S. government compliance program that standardizes how cloud services are assessed, monitored, and handle authorization. There is a FedRAMP marketplace for service providers and services that have been authorized by FedRAMP. COBIT is an IT management and governance framework, SABSA is a risk-based enterprise information security model, and PCI is a security standard created by and used by the payment card industry.

What two important factors does accountability for access control rely on?

Identification and authorization

Authentication and authorization

Identification and authentication

Accountability and authentication

Answer:
C.  Access control systems rely on identification and authentication to provide accountability. Effective authorization systems are desirable, but not required, since logs can provide information about who accessed what resources, even if access to those resources is not managed well. Of course, poor authorization management can create many other problems.

What part of the CIA triad does a checksum support?

Availability

Integrity

Confidentiality

Authenticity

Answer:
B.  Checksums validate whether a file or other data object has been changed or modified, and thus, they support integrity.

Scott's organization has configured their external IP address to be 192.168.1.25. When traffic is sent to their ISP, it never reaches its destination. What problem is Scott's organization encountering?

BGP is not set up properly.

They have not registered their IP with their ISP.

The IP address is a private, nonroutable address.

192.168.1.25 is a reserved address for home routers.

Answer:
C.  The 192.168.0.0 to 192.168.255.255 address range is one of the ranges defined by RFC 1918 as private, nonroutable IP ranges. Scott's ISP (and any other organization with a properly configured router) will not route traffic from these addresses over the public Internet.

Jack's organization merges updates to their main application multiple times a day and then deploys it as code that is checked in and tested through their software development pipeline. What type of model is this?

Waterfall

CI/CD

SCM

IDE

Answer:
B.  Jack's organization is using a continuous integration/continuous delivery (CI/CD) model where the application is updated and deployed on an ongoing basis. This can allow for an agile application but requires strong testing and validation practices to ensure that bad code doesn't make it into production. Waterfall is a development model that is based on a slower, precise process. SCM is software configuration management, and an IDE is an integrated development environment.

Sue's organization recently failed a security assessment because their network was a single flat broadcast domain, and sniffing traffic was possible between different functional groups. What solution should she recommend to help prevent the issues that were identified?

Use VLANs.

Change the subnet mask for all systems.

Deploy gateways.

Turn on port security.

Answer:
A.  A well-designed set of VLANs based on functional groupings will logically separate segments of the network, making it difficult to have data exposure issues between VLANs. Changing the subnet mask will only modify the broadcast domain and will not fix issues with packet sniffing. Gateways would be appropriate if network protocols were different on different segments. Port security is designed to limit which systems can connect to a given port.

Which of the following terms best describes the IP address 10.14.124.240?

Public IP address

Private IP address

APIPA address

Loopback address

Answer:
B.  Any 10.x.x.x address is a private address as defined by RFC 1918. APIPA addresses are self-assigned by Windows when they cannot contact a DHCP server. 127.0.0.1 is a loopback address that systems use to connect with themselves. Public IP addresses compose the majority of IP addresses with the exception of reserved addresses like those described in RFC 1918.

Jim is performing a security assessment of his company and would like to use a testing tool to perform a web vulnerability scan. Which of the following tools is best suited for identifying this form of vulnerability?

Nmap

Hydra

Metasploit

Nikto

Answer:
D.  Nikto is a web application and server scanning tool and is best suited to Jim's needs. Nmap is a port scanner, Hydra is a login cracking tool, and Metasploit is a complete penetration testing framework but isn't designed specifically to test web applications and servers.
