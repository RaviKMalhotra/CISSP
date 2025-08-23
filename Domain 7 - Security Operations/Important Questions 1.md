# Domain 7 - Security Operations Important Questions

SUBDOMAINS
7.1 Understand and comply with investigations
7.2 Conduct logging and monitoring activities
7.3 Perform Configuration Management (CM) (e.g., provisioning, baselining, automation)
7.4 Apply foundational security operations concepts
7.5 Apply resource protection
7.6 Conduct incident management
7.7 Operate and maintain detection and preventative measures
7.8 Implement and support patch and vulnerability management
7.9 Understand and participate in change management processes
7.10 Implement recovery strategies
7.11 Implement Disaster Recovery (DR) processes
7.12 Test Disaster Recovery Plan (DRP)
7.13 Participate in Business Continuity (BC) planning and exercises
7.14 Implement and manage physical security
7.15 Address personnel safety and security concerns
Mary is reviewing the availability controls for the system architecture shown here. What technology is shown that provides fault tolerance for the database servers?

Larger View
A system architecture. It begins with internet access, followed by network load balancing, connected to web 1, 2, and 3, connected to database 1 and 2, and finally Raid array.
Failover cluster

UPS

Tape backup

Cold site

Answer:
A.  The illustration shows an example of a failover cluster, where DB1 and DB2 are both configured as database servers. At any given time, only one will function as the active database server, while the other remains ready to assume responsibility if the first one fails. While the environment may use UPS, tape backup, and cold sites as disaster recovery and business continuity controls, they are not shown in the diagram.

Joe is the security administrator for an ERP system. He is preparing to create accounts for several new employees. What default access should he give to all of the new employees as he creates the accounts?

Read only

Editor

Administrator

No access

Answer:
D.  The principle of least privilege should guide Joe in this case. He should apply no access permissions by default and then give each user the necessary permissions to perform their job responsibilities. Read only, editor, and administrator permissions may be necessary for one or more of these users, but those permissions should be assigned based upon business need and not by default.

Tim is configuring a privileged account management solution for his organization. Which one of the following is not a privileged administrative activity that should be automatically sent to a log of superuser actions?

Purging log entries

Restoring a system from backup

Logging into a workstation

Managing user accounts

Answer:
C.  While most organizations would want to log attempts to log in to a workstation, this is not considered a privileged administrative activity and would go through normal logging processes.

When one of the employees of Alice's company calls in for support, she uses a code word that the company agreed to use if employees were being forced to perform an action. What is this scenario called?

Social engineering

Duress

Force majeure

Stockholm syndrome

Answer:
B.  Duress, or being under threat of violence or other constraints, is a concern for organizations such as banks, jewelry stores, or other organizations where an attacker may attempt to force an employee to perform actions. Organizations that expect that a scenario like this may occur will often use duress code words that let others know that they are performing actions under threat.

Jordan is preparing to bring evidence into court after a cybersecurity incident investigation. He is responsible for preparing the physical artifacts, including affected servers and mobile devices. What type of evidence consists entirely of tangible items that may be brought into a court of law?

Documentary evidence

Parol evidence

Testimonial evidence

Real evidence

Answer:
D.  Real evidence consists of things that may actually be brought into a courtroom as evidence. For example, real evidence includes hard disks, weapons, and items containing fingerprints. Documentary evidence consists of written items that may or may not be in tangible form. Testimonial evidence is verbal testimony given by witnesses with relevant information. The parol evidence rule says that when an agreement is put into written form, the written document is assumed to contain all the terms of the agreement.

Lauren wants to ensure that her users only run software that her organization has approved. What technology should she deploy?

Blacklisting

Configuration management

Whitelisting

Graylisting

Answer:
C.  A whitelist of allowed applications will ensure that Lauren's users can run only the applications that she preapproves. Blacklists would require her to maintain a list of every application that she doesn't want to allow, which is an almost impossible task. Graylisting is not a technology option. Configuration management can be useful for making sure the right applications are on a PC but typically can't directly prevent users from running undesired applications or programs.

Colin is responsible for managing his organization's use of cybersecurity deception technologies. Which one of the following should he use on a honeypot system to consume an attacker's time while alerting administrators?

Honeynet

Pseudo-flaw

Warning banner

Darknet

Answer:
B.  A pseudo-flaw is a false vulnerability in a system that may distract an attacker. A honeynet is a network of multiple honeypots that creates a more sophisticated environment for intruders to explore, rather than a feature Colin could use on a honeypot. A darknet is a segment of unused network address space that should have no network activity and, therefore, may be easily used to monitor for illicit activity. A warning banner is a legal tool used to notify intruders that they are not authorized to access a system.

Toni responds to the desk of a user who reports slow system activity. Upon checking outbound network connections from that system, Toni notices a large amount of social media traffic originating from the system. The user does not use social media, and when Toni checks the accounts in question, she sees they contain strange messages that appear encrypted. What is the most likely cause of this traffic?

Other users are relaying social media requests through the user's computer.

The user's computer is part of a botnet.

The user is lying about her use of social media.

Someone else is using the user's computer when she is not present.

Answer:
B.  Social media is commonly used as a command-and-control system for botnet activity. The most likely scenario here is that the user's computer was infected with malware and joined to a botnet. This accounts for both the unusual social media traffic and the slow system activity.

John deploys his website to multiple regions using load balancers around the world through his cloud infrastructure as a service provider. What availability concept is he using?

Multiple processing sites

Warm sites

Cold sites

A honeynet

Answer:
A.  John's design provides multiple processing sites, distributing load to multiple regions. Not only does this provide business continuity and disaster recovery functionality, but it also means that his design will be more resilient to denial-of-service attacks.

Jim would like to identify compromised systems on his network that may be participating in a botnet. He plans to do this by watching for connections made to known command-and-control servers. Which one of the following techniques would be most likely to provide this information if Jim has access to a list of known servers?

NetFlow records

IDS logs

Authentication logs

RFC logs

For questions 11–15, please refer to the following scenario:

Gary was recently hired as the first chief information security officer (CISO) for a local government agency. The agency recently suffered a security breach and is attempting to build a new information security program. Gary would like to apply some best practices for security operations as he is designing this program.

Answer:
A.  NetFlow records contain an entry for every network communication session that took place on a network and can be compared to a list of known malicious hosts. IDS logs may contain a relevant record, but it is less likely because they would create log entries only if the traffic triggers the IDS, as opposed to NetFlow records, which encompass all communications. Authentication logs and RFC logs would not have records of any network traffic.

As Gary decides what access permissions he should grant to each user, what principle should guide his decisions about default permissions?

Segregation of duties

Least privilege

Privilege creep

Separation of privileges

Answer:
B.  Gary should follow the least privilege principle and assign users only the permissions they need to perform their job responsibilities. Privilege creep is a term used to describe the unintentional accumulation of privileges over time. Segregation of duties and separation of privileges are principles used to secure sensitive processes.

As Gary designs the program, he uses the matrix shown here. What principle of information security does this matrix most directly help enforce?

Larger View
A table depicts the roles and their potential areas of conflict. Roles include application programmer, security administrator, database administrator, database server administrator, budget analyst, accounts payable, deploy patches, and verify patches.
Segregation of duties

Privilege creep

Two-person control

Defense in depth

Answer:
A.  The matrix shown in the figure is known as a segregation of duties matrix. It is used to ensure that one person does not obtain two privileges that would create a potential conflict. Privilege creep is a term used to describe the unintentional accumulation of privileges over time. Two-person control is used when two people must work together to perform a sensitive action. Defense in depth is a general security principle used to describe a philosophy of overlapping security controls.

Gary is preparing to create an account for a new user and assign privileges to the HR database. What two elements of information must Gary verify before granting this access?

Credentials and need to know

Clearance and need to know

Password and clearance

Password and biometric scan

Answer:
B.  Before granting access, Gary should verify that the user has a valid security clearance and a business need to know the information. Gary is performing an authorization task, so he does not need to verify the user's credentials, such as a password or biometric scan.

Gary is preparing to develop controls around access to root encryption keys and would like to apply a principle of security designed specifically for very sensitive operations. Which principle should he apply?

Least privilege

Defense in depth

Security through obscurity

Two-person control

Answer:
D.  Gary should follow the principle of two-person control by requiring simultaneous action by two separate authorized individuals to gain access to the encryption keys. He should also apply the principles of least privilege and defense in depth, but these principles apply to all operations and are not specific to sensitive operations. Gary should avoid the security through obscurity principle, the reliance upon the secrecy of security mechanisms to provide security for a system or process.

How often should Gary and his team conduct a review of the privileged access that a user has to sensitive systems? (Select all that apply.)

On a periodic basis

When a user leaves the organization

When a user changes roles

On a daily basis

Answer:
A, B, C.  Privileged access reviews are one of the most critical components of an organization's security program because they ensure that only authorized users have access to perform the most sensitive operations. They should take place whenever a user with privileged access leaves the organization or changes roles as well as on a regular, recurring basis. However, it is not reasonable to expect that these time-consuming reviews would take place on a daily basis.

Which one of the following terms is often used to describe a collection of unrelated patches released in a large collection?

Hotfix

Update

Security fix

Service pack

Answer:
D.  Hotfixes, updates, and security fixes are all synonyms for single patches designed to correct a single problem. Service packs are collections of many different updates that serve as a major update to an operating system or application.

Tonya is collecting evidence from a series of systems that were involved in a cybersecurity incident. A colleague suggests that she use a write blocker for the collection process. What is the function of this device?

Masking error conditions reported by the storage device

Transmitting write commands to the storage device

Intercepting and modifying or discarding commands sent to the storage device

Preventing data from being returned by a read operation sent to the device

Answer:
C.  A forensic disk controller performs four functions. One of those, write blocking, intercepts write commands sent to the device and prevents them from modifying data on the device. The other three functions include returning data requested by a read operation, returning access-significant information from the device, and reporting errors from the device back to the forensic host.

Lydia is processing access control requests for her organization. She comes across a request where the user does have the required security clearance, but there is no business justification for the access. Lydia denies this request. What security principle is she following?

Need to know

Least privilege

Segregation of duties

Two-person control

Answer:
A.  Lydia is following the need to know principle. While the user may have the appropriate security clearance to access this information, there is no business justification provided, so she does not know that the user has an appropriate need to know the information.

Helen is tasked with implementing security controls in her organization that might be used to deter fraudulent insider activity. Which one of the following mechanisms would be LEAST useful to her work?

Job rotation

Mandatory vacations

Incident response

Two-person control

Answer:
C.  Job rotation and mandatory vacations deter fraud by increasing the likelihood that it will be detected. Two-person control deters fraud by requiring collusion between two employees. Incident response does not normally serve as a deterrent mechanism.

Matt wants to ensure that critical network traffic from systems throughout his company is prioritized over web browsing and social media use at this company. What technology can he use to do this?

VLANs

QoS

VPN

ISDN

Answer:
B.  Quality of service is a feature found on routers and other network devices that can prioritize specific network traffic. QoS policies define which traffic is prioritized, and traffic is then handled based on the policy.

Tom is responding to a recent security incident and is seeking information on the approval process for a recent modification to a system's security settings. Where would he most likely find this information?

Change log

System log

Security log

Application log

Answer:
A.  The change log contains information about approved changes and the change management process. While other logs may contain details about the change's effect, the audit trail for change management would be found in the change log.

Staff from Susan's company often travel internationally and require connectivity to corporate systems for their work. Susan believes that these users may be targeted for corporate espionage activities because of the technologies that her company is developing and wants to include advice in the security training provided to international travelers. What practice should Susan recommend that they adopt for connecting to networks while they travel?

Only connect to public Wi-Fi.

Use a VPN for all connections.

Only use websites that support TLS.

Do not connect to networks while traveling.

Answer:
B.  While it may be tempting to tell her staff to simply not connect to any network, Susan knows that they will need connectivity to do their work. Using a VPN to connect their laptops and mobile devices to a trusted network and ensuring that all traffic is tunneled through the VPN is her best bet to secure their Internet usage. Susan may also want to ensure that they take “clean” laptops and devices that do not contain sensitive information or documents and that those systems are fully wiped when they return.

Ricky is seeking a list of information security vulnerabilities in applications, devices, and operating systems. Which one of the following threat intelligence sources would be most useful to him?

OWASP

CIS

Microsoft Security Bulletins

CVE

Answer:
D.  The Common Vulnerabilities and Exposures (CVE) database contains standardized information on many different security issues. The Open Worldwide Application Security Project (OWASP) contains general guidance on web application security issues but does not track specific vulnerabilities or go beyond web applications. The Center for Internet Security (CIS) maintains benchmarks for securely configuring devices, operating systems, and applications. They do not track vulnerabilities. Microsoft Security Bulletins are also good sources of vulnerability information but are not comprehensive databases of known issues.

Which of the following would normally be considered an example of a disaster when performing disaster recovery planning? (Select all that apply.)

Hacking incident

Flood

Fire

Terrorism

Answer:
A, B, C, D.  A disaster is any event that can disrupt normal IT operations and can be either natural or human made. Hacking and terrorism are examples of human-made disasters, while flooding and fire are examples of natural disasters.

Glenda would like to conduct a disaster recovery test and is seeking a test that will allow a review of the plan with no disruption to normal information system activities and as minimal a commitment of time as possible. What type of test should she choose?

Tabletop exercise

Parallel test

Full interruption test

Read-through

Answer:
D.  The read-through is the least disruptive type of disaster recovery test. During a read-through, team members each review the contents of their disaster recovery checklists on their own and suggest any necessary changes. During a tabletop exercise, team members come together and discuss a specific scenario without making any changes to information systems. During a parallel test, the team actually activates the disaster recovery site for testing, but the primary site remains operational. During a full interruption test, the team takes down the primary site and confirms that the disaster recovery site is capable of handling regular operations. The full interruption test is the most thorough test but also the most disruptive.

Which one of the following is not an example of a backup tape rotation scheme?

Grandfather-Father-Son

Meet-in-the-Middle

Tower of Hanoi

Six Cartridge Weekly

Answer:
B.  The Grandfather-Father-Son, Tower of Hanoi, and Six Cartridge Weekly schemes are all different approaches to rotating backup media that balance reuse of media with data retention concerns. Meet-in-the-middle is a cryptographic attack against 2DES encryption.

Helen is implementing a new security mechanism for granting employees administrative privileges in the accounting system. She designs the process so that both the employee's manager and the accounting manager must approve the request before the access is granted. What information security principle is Helen enforcing?

Least privilege

Two-person control

Job rotation

Segregation of duties

Answer:
B.  In this scenario, Helen designed a process that requires the concurrence of two people to perform a sensitive action. This is an example of two-person control. This is different from segregation of duties, where one individual may not have two separate permissions that, when combined, might allow an unwanted action. Segregation of duties applied to a situation like this one might say that the same person may not have both the ability to initiate a request and the ability to approve a request. Least privilege says that an individual should have only the necessary permissions required to carry out their job function. Job rotation is a scheme that has users periodically shift job functions in order to detect malfeasance.

Frank is considering the use of different types of evidence in an upcoming criminal matter. Which one of the following is not a requirement for evidence to be admissible in court?

The evidence must be relevant.

The evidence must be material.

The evidence must be tangible.

The evidence must be competently acquired.

Answer:
C.  Evidence provided in court must be relevant to determining a fact in question, material to the case at hand, and competently obtained. Evidence does not need to be tangible. Witness testimony is an example of intangible evidence that may be offered in court.

Harold recently completed leading the postmortem review of a security incident. What documentation should he prepare next?

A lessons learned document

A risk assessment

A remediation list

A mitigation checklist

Answer:
A.  A lessons learned document is often created and distributed to involved parties after a postmortem review to ensure that those who were involved in the incident and others who may benefit from the knowledge are aware of what they can do to prevent future issues and to improve response in the event that one occurs.

Beth is creating a new cybersecurity incident response team (CSIRT) and would like to determine the appropriate team membership. Which of the following groups would she normally include? (Select all that apply.)

Information security

Law enforcement

Senior management

Public affairs

Answer:
A, C, D.  CSIRT representation normally includes at least representatives of senior management, information security professionals, legal representatives, public relations staff, human resources, and engineering/technical staff. Law enforcement personnel would not be included on such a team and would only be consulted as necessary.

Sam is responsible for backing up his company's primary file server. He configured a backup schedule that performs full backups every Monday evening at 9 p.m. and differential backups on other days of the week at that same time. Files change according to the information shown here. How many files will be copied in Wednesday's backup?

A list of file modifications for Monday, Tuesday, and Wednesday. The maximum files are created in Wednesday.
2

3

5

6

Answer:
C.  In this scenario, all the files on the server will be backed up on Monday evening during the full backup. The differential backup on Wednesday will then copy all files modified since the last full backup. These include files 1, 2, 3, 5, and 6: a total of five files.

A sample file mofodification report. IT Includes number of files created for Monday, Tuesday, and Wednesday with time.
Which one of the following security tools is not capable of generating an active response to a security event?

IPS

Firewall

IDS

Antivirus software

Answer:
C.  Intrusion detection systems (IDSs) provide only passive responses, such as alerting administrators to a suspected attack. Intrusion prevention systems and firewalls, on the other hand, may take action to block an attack attempt. Antivirus software also may engage in active response by quarantining suspect files.

Scott is responsible for disposing of disk drives that have been pulled from his company's SAN as they are retired. Which of the following options should he avoid if the data on the SAN is considered highly sensitive by his organization?

Destroy them physically.

Sign a contract with the SAN vendor that requires appropriate disposal and provides a certification process.

Reformat each drive before it leaves the organization.

Use a secure wipe tool like DBAN.

Answer:
C.  Physical destruction, an appropriate contract with certification, and secure wiping are all reasonable options. In each case, a careful inventory and check should be done to ensure that each drive is handled appropriately. Reformatting drives can leave remnant data, making this a poor data life-cycle choice for drives that contain sensitive data.

Which of the following topics is least likely to be included in a company's user security training and awareness program?

Insider threat

Social media impact

2FA fatigue

Secure router configuration guidelines

Answer:
D.  Secure router configuration guidelines are typically more technical and specific to IT professionals, making them less likely to be included in a general security training and awareness program. These programs usually focus on broader and more universally applicable topics like insider threats, which address risks from employees or contractors; social media impact, which covers the risks of sharing information online; and 2FA fatigue, which relates to the weariness or complacency in using two-factor authentication. These are relevant to a wider audience and are crucial for overall organizational security awareness. In contrast, the specifics of router configuration are usually handled by specialized IT staff.

Which one of the following types of agreements is the most formal document that contains expectations about availability and other performance parameters between a service provider and a customer?

Service-level agreement (SLA)

Operational-level agreement (OLA)

Memorandum of understanding (MOU)

Statement of work (SOW)

Answer:
A.  The service-level agreement (SLA) is between a service provider and a customer and documents in a formal manner expectations around availability, performance, and other parameters. An MOU may cover the same items but is not as formal a document. An OLA is between internal service organizations and does not involve customers. An SOW is an addendum to a contract describing work to be performed.

As the CIO of a large organization, Clara would like to adopt standard processes for managing IT activities. Which one of the following frameworks focuses on IT service management and includes topics such as change management, configuration management, and service-level agreements?

ITIL

PMBOK

PCI DSS

TOGAF

Answer:
A.  The ITIL framework focuses on IT service management. The Project Management Body of Knowledge (PMBOK) provides a common core of project management expertise. The Payment Card Industry Data Security Standard (PCI DSS) contains regulations for payment card security. The Open Group Architecture Framework (TOGAF) focuses on IT architecture issues.

Richard is experiencing issues with the quality of network service on his organization's network. The primary symptom is that packets are consistently taking too long to travel from their source to their destination. What term describes the issue Richard is facing?

Jitter

Packet loss

Interference

Latency

Answer:
D.  Latency is a delay in the delivery of packets from their source to their destination. Jitter is a variation in the latency for different packets. Packet loss is the disappearance of packets in transit that requires retransmission. Interference is electrical noise or other disruptions that corrupt the contents of packets.

Joe wants to test a program he suspects may contain malware. What technology can he use to isolate the program while it runs?

ASLR

Sandboxing

Clipping

Process isolation

Answer:
B.  Running the program in a sandbox provides secure isolation that can prevent the malware from impacting other applications or systems. If Joe uses appropriate instrumentation, he can observe what the program does, what changes it makes, and any communications it may attempt. ASLR is a memory location randomization technology. Process isolation keeps processes from impacting each other. A sandbox typically provides greater utility in a scenario like this since it can be instrumented and managed in a way that better supports investigations. Clipping is a term often used in signal processing.

Which one of the following is an example of a non-natural disaster?

Hurricane

Flood

Mudslide

Transformer explosion

Answer:
D.  A transformer explosion is a failure of a human-made electrical component. Flooding, mudslides, and hurricanes are all examples of natural disasters.

Anne wants to gather information about security settings as well as build an overall view of her organization's assets by gathering data about a group of Windows 11 workstations spread throughout her company. What Windows tool is best suited to this type of configuration management task?

ConfigMgr

Group Policy

SCOM

A custom PowerShell script

Answer:
A.  Microsoft Configuration Manager (ConfigMgr) provides this capability and is designed to allow administrators to evaluate the configuration status of Windows workstations and servers, as well as providing asset management data. System Center Operations Manager (SCOM) is primarily used to monitor for health and performance. Group Policy can be used for a variety of tasks including deploying settings and software, and custom PowerShell scripts could do this but should not be required for a configuration check.

Javier is verifying that only IT system administrators have the ability to log on to servers used for administrative purposes. What principle of information security is he enforcing?

Need to know

Least privilege

Two-person control

Transitive trust

Answer:
B.  The principle of least privilege says that an individual should only have the privileges necessary to complete their job functions. Removing administrative privileges from nonadministrative users is an example of least privilege.

Which one of the following is not a basic preventive measure that you can take to protect your systems and applications against attack?

Implement intrusion detection and prevention systems.

Maintain current patch levels on all operating systems and applications.

Remove unnecessary accounts and services.

Conduct forensic imaging of all systems.

Answer:
D.  There is no need to conduct forensic imaging as a preventative measure. Rather, forensic imaging should be used during the incident response process. Maintaining patch levels, implementing intrusion detection/prevention, and removing unnecessary services and accounts are all basic preventive measures.

Chas is a cybersecurity manager who is concerned that the cloud provider his organization relies upon for disaster recovery may not be able to meet their needs in the event that a disaster strikes multiple customers simultaneously. What type of agreement should Chas enter into with this provider?

Nondisclosure agreement

Resource capacity agreement

Mutual assistance agreement

Business partnership agreement

Answer:
B.  A resource capacity agreement is the most appropriate for Chas's concern, as it specifically addresses the availability of resources in a disaster scenario. This type of agreement ensures that the cloud provider has sufficient resources to meet the needs of their clients, even in the event of multiple simultaneous disasters. It directly tackles the issue of resource allocation and availability, which is Chas's primary concern. In contrast, a nondisclosure agreement is more about confidentiality and doesn't address resource capacity. A mutual assistance agreement typically involves agreements between organizations for support during emergencies but doesn't guarantee specific resource availability. A business partnership agreement is broader and may not specifically cover the detailed aspects of resource availability in disaster scenarios.

Which one of the following is an example of a computer security incident?

Failure of a backup to complete properly

System access recorded in a log

Unauthorized vulnerability scan of a file server

Update of antivirus signatures

Answer:
C.  An incident negatively affects the confidentiality, integrity, or availability of information or assets and/or violates a security policy. A computer security incident is an incident that is the result of an attack or the result of malicious or intentional actions on the part of users. The unauthorized vulnerability scan of a server does violate security policy and may negatively affect the security of that system, so it qualifies as a security incident. The failure of a backup to complete properly jeopardizes availability and is, therefore, an incident, but not a computer security incident. The logging of system access and update of antivirus signatures are all routine actions that do not violate policy or jeopardize security, so they are all events rather than incidents.

Roland is a physical security specialist in an organization that has a large amount of expensive lab equipment that often moves around the facility. Which one of the following technologies would provide the most automation of an inventory control process in a cost-effective manner?

IPS

Wi-Fi

RFID

Ethernet

Answer:
C.  Radio Frequency Identification (RFID) technology is a cost-effective way to track items around a facility. While Wi-Fi could be used for the same purpose, it would be much more expensive to implement.

Connor's company recently experienced a denial-of-service attack that Connor believes came from an inside source. If true, what type of event has the company experienced?

Espionage

Confidentiality breach

Sabotage

Integrity breach

Answer:
C.  An attack committed against an organization by an insider, such as an employee, is known as sabotage. Espionage and confidentiality breaches involve the theft of sensitive information, which is not alleged to have occurred in this case. Integrity breaches involve the unauthorized modification of information, which is not described in this scenario.

Evan detects an attack against a server in his organization and examines the TCP flags on a series of packets, shown in the following diagram. What type of attack most likely took place?

Larger View
A diagram depicts the T C P flags on a series of packets. It includes S Y N and S Y N/A C K.
SYN flood

Ping flood

Smurf

Fraggle

Answer:
A.  In a SYN flood attack, the attacker sends a large number of SYN packets to a system but does not respond to the SYN/ACK packets, attempting to overwhelm the attacked system's connection state table with half-open connections.

Florian is building a disaster recovery plan for his organization and would like to determine the amount of time that a particular IT service may be down without causing serious damage to business operations. What variable is Florian calculating?

RTO

MTD

RPO

SLA

Answer:
B.  The maximum tolerable downtime (MTD) is the longest amount of time that an IT service or component may be unavailable without causing serious damage to the organization. The recovery time objective (RTO) is the amount of time expected to return an IT service or component to operation after a failure. The recovery point objective (RPO) identifies the maximum amount of data, measured in time, that may be lost during a recovery effort. Service-level agreements (SLAs) are written contracts that document service expectations.

Which of the following would normally be classified as zero-day attacks?

An attacker who is new to the world of hacking

A database attack that places the date 00/00/0000 in data tables in an attempt to exploit flaws in business logic

An attack previously unknown to the security community

An attack that sets the operating system date and time to 00/00/0000 and 00:00:00

Answer:
C.  Zero-day attacks are those that are previously unknown to the security community and, therefore, have no available patch. These are especially dangerous attacks because they may be highly effective until a solution becomes available. The other attacks described here are all known attacks and would not be classified as zero-day events.

Rob is conducting a forensic investigation and is looking for elements of trace digital evidence. Which one of the following principles applies most closely to his work?

Kerckhoff's principle

Principle of least privilege

Defense-in-depth principle

Locard's principle

Answer:
D.  Locard's principle is most relevant to Rob's forensic investigation for trace digital evidence, as it suggests that any contact between two objects results in an exchange of materials. In the context of digital forensics, this principle implies that there is always some form of digital trace or residue left behind when devices interact or when data is transferred.

Kerckhoff's principle states that a system's security should not depend on the secrecy of its algorithm but rather on the secrecy of its keys. The principle of least privilege is a security concept in which a user is given the minimum levels of access—or permissions—needed to perform his job functions. Lastly, the defense-in-depth principle is a layered security approach that establishes multiple levels of defense to protect information. While these other three principles are important in cybersecurity, they do not directly relate to the collection and analysis of digital trace evidence like Locard's principle does.

During an incident investigation, investigators meet with a system administrator who may have information about the incident but is not a suspect. What type of conversation is taking place during this meeting?

Interview

Interrogation

Both an interview and an interrogation

Neither an interview nor an interrogation

Answer:
A.  Interviews occur when investigators meet with an individual who may have information relevant to their investigation but is not a suspect. If the individual is a suspect, then the meeting is an interrogation.

What technique has been used to protect the intellectual property shown here?

Steganography

Clipping

Sampling

Watermarking

Larger View
A photograph of a seashore. Two men standing opposite to each others near the seashore.
Source: Bruce Jaffe / USGS / Public domain

Answer:
D.  The image clearly contains the watermark of the U.S. Geological Survey (USGS), which ensures that anyone seeing the image knows its origin. It is not possible to tell from looking at the image whether steganography was used. Sampling and clipping are data analysis techniques and are not used to protect images.

You are working to evaluate the risk of flood to an area as part of a business continuity planning (BCP) effort. You consult the flood maps from the Federal Emergency Management Agency (FEMA). According to those maps, the area lies within a 200-year flood plain. What is the annualized rate of occurrence (ARO) of a flood in that region?

200

0.01

0.02

0.005

Answer:
D.  The annualized rate of occurrence (ARO) is the expected number of times an incident will occur each year. In the case of a 200-year flood plain, planners should expect a flood once every 200 years. This is equivalent to a 1/200 chance of a flood in any given year, or 0.005 floods per year.

Which one of the following individuals poses the greatest risk to security in most well-defended organizations?

Political activist

Malicious insider

Script kiddie

Thrill attacker

Answer:
B.  While all hackers with malicious intent pose a risk to the organization, the malicious insider poses the greatest risk to security because they likely have legitimate access to sensitive systems that may be used as a launching point for an attack. Other attackers do not begin with this advantage.

Veronica is considering the implementation of a database recovery mechanism recommended by a consultant. In the recommended approach, an automated process will move database backups from the primary facility to an off-site location each night. What type of database recovery technique is the consultant describing?

Remote journaling

Remote mirroring

Electronic vaulting

Transaction logging

Answer:
C.  In an electronic vaulting approach, automated technology moves database backups from the primary database server to a remote site on a scheduled basis, typically daily. Transaction logging is not a recovery technique alone; it is a process for generating the logs used in remote journaling. Remote journaling transfers transaction logs to a remote site on a more frequent basis than electronic vaulting, typically hourly. Remote mirroring maintains a live database server at the backup site and mirrors all transactions at the primary site on the server at the backup site.

When designing an access control scheme, Hilda set up roles so that the same person does not have the ability to provision a new user account and assign superuser privileges to an account. What information security principle is Hilda following?

Least privilege

Segregation of duties

Job rotation

Security through obscurity

Answer:
B.  Hilda's design follows the principle of segregation of duties. Giving one user the ability to both create new accounts and grant administrative privileges combines two actions that would result in a significant security change that should be divided among two users.

Patrick was asked to implement a threat-hunting program for his organization. Which one of the following is the basic assumption of a threat-hunting program that he should use as he plans his work?

Security controls were designed using a defense-in-depth strategy.

Audits may uncover control deficiencies.

Attackers may already be present on the network.

Defense mechanisms may contain unpatched vulnerabilities.

Answer:
C.  While all of these assumptions are valid premises that Patrick might have going into the exercise, the basic assumption of a threat-hunting exercise is the so-called presumption of compromise. This means that Patrick should assume that attackers have already gained access to his system and then hunt for indicators of their presence.

Brian is developing the training program for his organization's disaster recovery program and would like to make sure that participants understand when disaster activity concludes. Which one of the following events marks the completion of a disaster recovery process?

Securing property and life safety

Restoring operations in an alternate facility

Restoring operations in the primary facility

Standing down first responders

Answer:
C.  The end goal of the disaster recovery process is restoring normal business operations in the primary facility. All of the other actions listed may take place during the disaster recovery process, but the process is not complete until the organization is once again functioning normally in its primary facilities.

Melanie suspects that someone is using malicious software to steal computing cycles from her company. Which one of the following security tools would be in the best position to detect this type of incident?

NIDS

Firewall

HIDS

DLP

Answer:
C.  A host-based intrusion detection system (HIDS) may be able to detect unauthorized processes running on a system. The other controls mentioned, network intrusion detection systems (NIDSs), firewalls, and DLP systems, are network-based and may not notice rogue processes.

Brandon observes that an authorized user of a system on his network recently misused his account to exploit a system vulnerability against a shared server that allowed him to gain root access to that server. What type of attack took place?

Denial-of-service

Privilege escalation

Reconnaissance

Brute force

Answer:
B.  The scenario describes a privilege escalation attack where a malicious insider with authorized access to a system misused that access to gain privileged credentials.

Carla has worked for her company for 15 years and has held a variety of different positions. Each time she changed positions, she gained new privileges associated with that position, but no privileges were ever taken away. What concept describes the sets of privileges she has accumulated?

Entitlement

Privilege creep

Transitivity

Isolation

Answer:
B.  Carla's account has experienced privilege creep, where privileges accumulated over time. This condition is also known as aggregation and likely constitutes a violation of the least privilege principle.

During what phase of the incident response process do administrators take action to limit the effect or scope of an incident?

Detection

Response

Mitigation

Recovery

For questions 63–66, please refer to the following scenario:

Ann is a security professional for a midsize business and typically handles log analysis and security monitoring tasks for her organization. One of her roles is to monitor alerts originating from the organization's intrusion detection system. The system typically generates several dozen alerts each day, and many of those alerts turn out to be false alarms after her investigation.

This morning, the intrusion detection system alerted because the network began to receive an unusually high volume of inbound traffic. Ann received this alert and began looking into the origin of the traffic.

Answer:
C.  The mitigation phase of incident response focuses on actions that can contain the damage incurred during an incident. This includes limiting the scope and/or effectiveness of the incident. The detection phase identifies that an incident is taking place. The response phase includes steps taken to assemble a team and triage the incident. At the conclusion of the recovery phase, normal operations are resumed.

At this point in the incident response process, what term best describes what has occurred in Ann's organization?

Security occurrence

Security incident

Security event

Security intrusion

Answer:
C.  At this point in the process, Ann has no reason to believe that any actual security compromise or policy violation took place, so this situation does not meet the criteria for a security incident or intrusion. Rather, the alert generated by the intrusion detection system is simply a security event requiring further investigation. Security occurrence is not a term commonly used in incident handling.

Ann continues her investigation and realizes that the traffic generating the alert is abnormally high volumes of inbound UDP traffic on port 53. What service typically uses this port?

DNS

SSH/SCP

SSL/TLS

HTTP

Answer:
A.  DNS traffic commonly uses port 53 for both TCP and UDP communications. SSH and SCP use TCP port 22. SSL and TLS do not have ports assigned to them but are commonly used for HTTPS traffic on port 443. Unencrypted web traffic over HTTP often uses port 80.

As Ann analyzes the traffic further, she realizes that the traffic is coming from many different sources and has overwhelmed the network, preventing legitimate uses. The inbound packets are responses to queries that she does not see in outbound traffic. The responses are abnormally large for their type. What type of attack should Ann suspect?

Reconnaissance

Malicious code

System penetration

Denial of service

Answer:
D.  The attack described in this scenario has all the hallmarks of a denial-of-service attack. More specifically, Ann's organization is likely experiencing a DNS amplification attack where an attacker sends false requests to third-party DNS servers with a forged source IP address belonging to the targeted system. Because the attack uses UDP requests, there is no three-way handshake. The attack packets are carefully crafted to elicit a lengthy response from a short query. The purpose of these queries is to generate responses headed to the target system that are sufficiently large and numerous enough to overwhelm the targeted network or system.

Now that Ann understands that an attack has taken place that violates her organization's security policy, what term best describes what has occurred in Ann's organization?

Security occurrence

Security incident

Security event

Security intrusion

Answer:
B.  Now that Ann suspects an attack against her organization, she has sufficient evidence to declare a security incident. The attack underway seems to have undermined the availability of her network, meeting one of the criteria for a security incident. This is an escalation beyond a security event but does not reach the level of an intrusion because there is no evidence that the attacker has even attempted to gain access to systems on Ann's network. Security occurrence is not a term commonly used in incident handling.

Frank is seeking to introduce a hacker's laptop in court as evidence against the hacker. The laptop does contain logs that indicate the hacker committed the crime, but the court ruled that the search of the apartment that resulted in police finding the laptop was unconstitutional. What admissibility criteria prevents Frank from introducing the laptop as evidence?

Materiality

Relevance

Hearsay

Competence

Answer:
D.  To be admissible, evidence must be relevant, material, and competent. The laptop in this case is clearly material because it contains logs related to the crime in question. It is also relevant because it provides evidence that ties the hacker to the crime. It is not competent because the evidence was not legally obtained.

Gordon suspects that a hacker has penetrated a system belonging to his company. The system does not contain any regulated information, and Gordon wants to conduct an investigation on behalf of his company. He has permission from his supervisor to conduct the investigation. Which of the following statements is true?

Gordon is legally required to contact law enforcement before beginning the investigation.

Gordon may not conduct his own investigation.

Gordon's investigation may include examining the contents of hard disks, network traffic, and any other systems or information belonging to the company.

Gordon may ethically perform “hack back” activities after identifying the perpetrator.

Answer:
C.  Gordon may conduct his investigation as he wants and use any information that is legally available to him, including information and systems belonging to his employer. There is no obligation to contact law enforcement. However, Gordon may not perform “hack back” activities because those may constitute violations of the law and/or ISC2 Code of Ethics.

Which one of the following tools provides an organization with the greatest level of protection against a software vendor going out of business?

Service-level agreement

Escrow agreement

Mutual assistance agreement

PCI DSS compliance agreement

Answer:
B.  Software escrow agreements place a copy of the source code for a software package in the hands of an independent third party who will turn the code over to the customer if the vendor ceases business operations. Service-level agreements, mutual assistance agreements, and compliance agreements all lose some or all of their effectiveness if the vendor goes out of business.

Fran is considering new human resources policies for her bank that will deter fraud. She plans to implement a mandatory vacation policy. What is typically considered the shortest effective length of a mandatory vacation?

Two days

Four days

One week

One month

Answer:
C.  Most security professionals recommend at least one, and preferably two, weeks of vacation to deter fraud. The idea is that fraudulent schemes will be uncovered during the time that the employee is away and does not have the access required to perpetuate a cover-up.

Which of the following events would constitute a security incident? (Select all that apply.)

An attempted network intrusion

A successful database intrusion

A malware infection

A successful attempt to access a file

A violation of a confidentiality policy

An unsuccessful attempt to remove information from a secured area

Answer:
A, B, C, E, F.  Any attempt to undermine the security of an organization or violation of a security policy is a security incident. All of the events described meet this definition and should be treated as an incident, with one exception. A successful attempt to access a file is certainly a security event, but it is not a security incident unless it is established that the individual accessing the file was not authorized to do so.

Amanda is configuring her organization's firewall to implement egress filtering. Which one of the following traffic types should be blocked by her organization's egress filtering policy? (Select all that apply.)

Traffic rapidly scanning many IP addresses on port 22

Traffic with a broadcast destination

Traffic with a source address from an external network

Traffic with a destination address on an external network

Answer:
A, B, C.  Egress filtering scans outbound traffic for potential security policy violations. This includes traffic that is likely malicious, such as an outbound SSH scan on port 22. It also includes traffic that appears to be part of an attack or misconfiguration, such as sending traffic to a broadcast destination address. Finally, it includes spoofed traffic generated by internal systems, which may bear a source address from an external network. The normal traffic that the firewall should expect to see is that bearing a destination address on an external network.

Allie is responsible for reviewing authentication logs on her organization's network. She does not have the time to review all logs, so she decides to choose only records where there have been four or more invalid authentication attempts. What technique is Allie using to reduce the size of the pool?

Sampling

Random selection

Clipping

Statistical analysis

Answer:
C.  The two main methods of choosing records from a large pool for further analysis are sampling and clipping. Sampling uses statistical techniques to choose a sample that is representative of the entire pool, while clipping uses threshold values to select those records that exceed a predefined threshold because they may be of most interest to analysts. In this case, Allie is only selecting records that exceed an invalid login threshold, making this an example of clipping.

She is not using statistical techniques to select a subset of records, so this is not an example of sampling.

You are performing an investigation into a potential bot infection on your network and want to perform a forensic analysis of the information that passed between different systems on your network and those on the Internet. You believe that the information was likely encrypted. You are beginning your investigation after the activity concluded. What would be the best and easiest way to obtain the source of this information?

Packet captures

NetFlow data

Intrusion detection system logs

Centralized authentication records

Answer:
B.  NetFlow data contains information on the source, destination, and size of all network communications and is routinely saved as a matter of normal activity. Packet capture data would provide relevant information, but it must be captured during the suspicious activity and cannot be re-created after the fact unless the organization is already conducting 100% packet capture, which is rare. Additionally, the use of encryption limits the effectiveness of packet capture. Intrusion detection system logs would not likely contain relevant information because the encrypted traffic would probably not match intrusion signatures. Centralized authentication records would not contain information about network traffic.

Which one of the following tools helps system administrators by providing a standard, secure template of configuration settings for operating systems and applications?

Security guidelines

Security policy

Baseline configuration

Running configuration

Answer:
C.  Baseline configurations serve as the starting point for configuring secure systems and applications. They contain the security settings necessary to comply with an organization's security policy and may then be customized to meet the specific needs of an implementation. While security policies and guidelines may contain information needed to secure a system, they do not contain a set of configuration settings that may be applied to a system. The running configuration of a system is the set of currently applied settings, which may or may not be secure.

What type of disaster recovery test activates the alternate processing facility and uses it to conduct transactions but leaves the primary site up and running?

Full interruption test

Parallel test

Read-through

Tabletop exercise

Answer:
B.  During a parallel test, the team actually activates the disaster recovery site for testing, but the primary site remains operational. During a full interruption test, the team takes down the primary site and confirms that the disaster recovery site is capable of handling regular operations. The full interruption test is the most thorough test but also the most disruptive. The read-through is the least disruptive type of disaster recovery test. During a read-through, team members each review the contents of their disaster recovery checklists on their own and suggest any necessary changes. During a tabletop exercise, team members come together and work through a specific scenario without making any changes to information systems.

During which phase of the incident response process would an analyst receive an intrusion detection system alert and verify its accuracy?

Response

Mitigation

Detection

Reporting

Answer:
C.  Both the receipt of alerts and the verification of their accuracy occur during the Detection phase of the incident response process.

Kevin is developing a continuous security monitoring strategy for his organization. Which one of the following is not normally used when determining assessment and monitoring frequency?

Threat intelligence

System categorization/impact level

Security control operational burden

Organizational risk tolerance

Answer:
C.  According to NIST SP 800-137, organizations should use the following factors to determine assessment and monitoring frequency: security control volatility, system categorizations/impact levels, security controls or specific assessment objects providing critical functions, security controls with identified weaknesses, organizational risk tolerance, threat information, vulnerability information, risk assessment results, the output of monitoring strategy reviews, and reporting requirements.

Hunter is reviewing his organization's monitoring strategy and identifying new technologies that they might deploy. His assessment reveals that the firm is not doing enough to monitor employee activity on endpoint devices. Which one of the following technologies would best meet his needs?

EDR

IPS

IDS

UEBA

Answer:
D.  All of these technologies have the potential to monitor user behavior on endpoint devices. The key to answering this question correctly is realizing the emphasis on the user. Intrusion detection and prevention systems (IDSs/IPSs) focus on network and host behavior. Endpoint detection and response (EDR) systems focus on endpoint devices. User and entity behavior analytics (UEBA) solutions focus on the user and, therefore, would be the best way to meet Hunter's requirement.

Bruce is seeing quite a bit of suspicious activity on his network. After consulting records in his SIEM, it appears that an outside entity is attempting to connect to all of his systems using a TCP connection on port 22. What type of scanning is the outsider likely engaging in?

FTP scanning

Telnet scanning

SSH scanning

HTTP scanning

Answer:
C.  SSH uses TCP port 22, so this attack is likely an attempt to scan for open or weakly secured SSH servers. FTP uses ports 20 and 21. Telnet uses port 23, and HTTP uses port 80.

Dylan believes that a database server in his environment was compromised using a SQL injection attack. Which one of the following actions would Dylan most likely take during the remediation phase of the attack?

Rebuilding the database from backups

Adding input validation to a web application

Reviewing firewall logs

Reviewing database logs

Answer:
B.  Remediation activities seek to address the issue that caused the incident. In this case, that was a web application that was open to SQL injection attack. Adding input validation seeks to remediate this vulnerability. Rebuilding the database is a recovery action, while reviewing logs is done as part of the detection and response effort.

Roger recently accepted a new position as a security professional at a company that runs its entire IT infrastructure within an IaaS environment. Which one of the following would most likely be the responsibility of Roger's firm?

Configuring the network firewall

Applying hypervisor updates

Patching operating systems

Wiping drives prior to disposal

Answer:
C.  In an infrastructure-as-a-service environment, the vendor is responsible for hardware- and network-related responsibilities. These include configuring network firewalls, maintaining the hypervisor, and managing physical equipment. The customer retains responsibility for patching operating systems on its virtual machine instances.

What technique can application developers use to test applications in an isolated virtualized environment before allowing them on a production network?

Penetration testing

Sandboxing

White-box testing

Black-box testing

Answer:
B.  Sandboxing is a technique where application developers (or the recipients of an untrusted application) may test the code in a virtualized environment that is isolated from production systems. White-box testing, black-box testing, and penetration testing are all common software testing techniques but do not require the use of an isolated system.

Gina is the firewall administrator for a small business and recently installed a new firewall. After seeing signs of unusually heavy network traffic, she checked the intrusion detection system, which reported that a SYN flood attack was underway. What firewall configuration change can Gina make to most effectively prevent this attack?

Block SYN from known IPs.

Block SYN from unknown IPs.

Enable SYN-ACK spoofing at the firewall.

Disable TCP.

Answer:
C.  While it may not immediately seem like the obvious answer, many firewalls have a built-in anti–SYN flood defense that responds to SYNs on behalf of protected systems. Once the remote system proves to be a legitimate connection by continuing the three-way handshake, the rest of the TCP session is passed through. If the connection proves to be an attack, the firewall handles the additional load using appropriate mitigation techniques. Blocking SYNs from known or unknown IP addresses is likely to cause issues with systems that should be able to connect, and turning off TCP will break most modern network services!

Nancy is leading an effort to modernize her organization's antimalware protection and would like to add endpoint detection and response (EDR) capabilities. Which of the following actions are normally supported by EDR systems? (Select all that apply.)

Analyzing endpoint memory, filesystem, and network activity for signs of malicious activity

Automatically isolating possible malicious activity to contain the potential damage

Conducting simulated phishing campaigns

Integration with threat intelligence sources

Answer:
A, B, D.  EDR platforms do not conduct simulated phishing campaigns. The most common features of EDR systems are analyzing endpoint memory, filesystem, and network activity for signs of malicious activity; isolating possible malicious activity to contain the potential damage; integrating with threat intelligence sources; and integrating with other incident response mechanisms.

Alan is assessing the potential for using machine learning and artificial intelligence in his cybersecurity program. Which of the following activities is most likely to benefit from this technology?

Intrusion detection

Account provisioning

Firewall rule modification

Media sanitization

Answer:
A.  While any cybersecurity activity has the potential to benefit from machine learning and artificial intelligence capabilities, this technology really shines when used for pattern detection and anomaly detection problems. This is the type of activity performed by an intrusion detection system, and, therefore, this system would benefit the most from the use of ML/AI technology.

Timber Industries recently had a dispute with a customer. During a meeting with his account representative, the customer stood up and declared, “There is no other solution. We will have to take this matter to court.” He then left the room. When does Timber Industries have an obligation to begin preserving evidence?

Immediately

Upon receipt of a notice of litigation from opposing attorneys

Upon receipt of a subpoena

Upon receipt of a court order

Answer:
A.  Companies have an obligation to preserve evidence whenever they believe that the threat of litigation is imminent. The statement made by this customer that “we will have to take this matter to court” is a clear threat of litigation and should trigger the preservation of any related documents and records.

Candace is designing a backup strategy for her organization's file server. She would like to perform a backup every weekday that has the smallest possible storage footprint. What type of backup should she perform?

Incremental backup

Full backup

Differential backup

Transaction log backup

Answer:
A.  Incremental backups provide the option that includes the smallest amount of data. In this case, that would be only the data modified since the most recent incremental backup. A differential backup would back up all data modified since the last full backup, which would be a substantial amount. The full backup would include all information on the server. Transaction log backups are specifically designed to support database servers and would not be effective on a file server.

Darcy is a computer security specialist who is assisting with the prosecution of a hacker. The prosecutor requests that Darcy give testimony in court about whether, in her opinion, the logs and other records in a case are indicative of a hacking attempt. What type of evidence is Darcy being asked to provide?

Expert opinion

Direct evidence

Real evidence

Documentary evidence

Answer:
A.  Expert opinion evidence allows individuals to offer their opinion based upon the facts in evidence and their personal knowledge. Expert opinion evidence may be offered only if the court accepts the witness as an expert in a particular field. Direct evidence is when witnesses testify about their direct observations. Real evidence consists of tangible items brought into court as evidence. Documentary evidence consists of written records used as evidence in court.

Which one of the following techniques is not commonly used to remove unwanted remnant data from magnetic tapes?

Physical destruction

Degaussing

Overwriting

Reformatting

Answer:
D.  The standard methods for clearing magnetic tapes, according to the NIST Guidelines for Media Sanitization, are overwriting the tape with nonsensitive data, degaussing, and physical destruction via shredding. Reformatting a tape does not remove remnant data.

Sally is building a new server for use in her environment and plans to implement RAID level 1 as a storage availability control. What is the minimum number of physical hard disks that she needs to implement this approach?

One

Two

Three

Five

Answer:
B.  RAID level 1, also known as disk mirroring, uses a minimum of two disks that contain identical information. If one disk fails, the other contains the data needed for the system to continue operation.

Jerome is conducting a forensic investigation and is reviewing database server logs to investigate query contents for evidence of SQL injection attacks. What type of analysis is he performing?

Hardware analysis

Software analysis

Network analysis

Media analysis

Answer:
B.  The analysis of application logs is one of the core tasks of software analysis. This is the correct answer because SQL injection attacks are application attacks.

Quigley Computing regularly ships tapes of backup data across the country to a secondary facility. These tapes contain confidential information. What is the most important security control that Quigley can use to protect these tapes?

Locked shipping containers

Private couriers

Data encryption

Media rotation

Answer:
C.  Quigley may choose to use any or all of these security controls, but data encryption is, by far, the most important control. It protects the confidentiality of data stored on the tapes, which are most vulnerable to theft while in transit between two secure locations.

Carolyn is concerned that users on her network may be storing sensitive information, such as Social Security numbers, on their hard drives without proper authorization or security controls. What third-party security service can she implement to best detect this activity?

IDS

IPS

DLP

TLS

Answer:
C.  Data loss prevention (DLP) systems may identify sensitive information stored on endpoint systems or in transit over a network. This is their primary purpose. DLP systems are commonly available as a third-party managed service offering. Intrusion detection and prevention systems (IDSs/IPSs) may be used to identify some sensitive information using signatures built for that purpose, but this is not the primary role of those tools, and they would not be as effective as DLP systems at this task. TLS is a network encryption protocol that may be used to protect sensitive information, but it does not have any ability to identify sensitive information.

Gavin is the disaster recovery team leader for his organization, which is currently in the response phase of an incident that has severe customer impact. Gavin just received a phone call from a reporter asking for details on the root cause and an estimated recovery time. Gavin has this information at his fingertips. What should he do?

Provide the information to the reporter.

Request a few minutes to gather the information and return the call.

Refer the matter to the public relations department.

Refuse to provide any information.

Answer:
C.  Disaster recovery teams should always refer media inquiries to the public relations team to ensure a coordinated, consistent response. They should not attempt to answer questions themselves.

Pauline is reviewing her organization's emergency management plans. What should be the highest priority when creating these plans?

Protection of mission-critical data

Preservation of operational systems

Collection of evidence

Preservation of safety

Answer:
D.  All of these considerations are important when developing an emergency management plan. However, the safety of human life should always be the overwhelming priority, above all other considerations.

Barry is the CIO of an organization that recently suffered a serious operational issue that required activation of the disaster recovery plan. He would like to conduct a lessons learned session to review the incident. Who would be the best facilitator for this session?

Barry, as chief information officer

Chief information security officer

Disaster recovery team leader

External consultant

Answer:
D.  Barry should recruit an independent moderator to facilitate the session. Having a moderator who was not directly involved in the effort encourages honest and open feedback. While it is not necessary to use an external consultant, they may easily fill this role. While it is also possible to find a qualified internal employee to fill this position, it should not be someone who was involved in the incident response effort or has a major stake in the plan, such as Barry, the CISO, or the DR team leader.

Brent is reviewing the controls that will protect his organization in the event of a sustained period of power loss. Which one of the following solutions would best meet his needs?

Redundant servers

Uninterruptible power supply (UPS)

Generator

RAID

Answer:
C.  Generators are capable of providing backup power for a sustained period of time in the event of a power loss, but they take time to activate. Uninterruptible power supplies (UPSs) provide immediate, battery-driven power for a short period of time to cover momentary losses of power, which would not cover a sustained period of power loss. RAID and redundant servers are high-availability controls but do not cover power loss scenarios.

Match each of the numbered terms with its correct lettered definition:

Terms:

Honeypot

Honeynet

Pseudo-flaw

Darknet

Definitions:

An intentionally designed vulnerability used to lure in an attacker

A network set up with intentional vulnerabilities

A system set up with intentional vulnerabilities

A monitored network without any hosts

Answer:
The terms match with the definitions as follows:

Honeypot: C. A system set up with intentional vulnerabilities

Honeynet: B. A network set up with intentional vulnerabilities

Pseudo-flaw: A. An intentionally designed vulnerability used to lure in an attacker

Darknet: D. A monitored network without any hosts

Match each of the numbered types of recovery capabilities to their correct lettered definition:

Terms:

Hot site

Cold site

Warm site

Service bureau

Definitions:

An organization that can provide on-site or off-site IT services in the event of a disaster

A site with dedicated storage and real-time data replication, often with shared equipment that allows restoration of service in a very short time

A site that relies on shared storage and backups for recovery

A rented space with power, cooling, and connectivity that can accept equipment as part of a recovery effort

Answer:
The terms match with the definitions as follows:

Hot site: B. A site with dedicated storage and real-time data replication, often with shared equipment that allows restoration of service in a very short time

Cold site: D. A rented space with power, cooling, and connectivity that can accept equipment as part of a recovery effort

Warm site: C. A site that relies on shared storage and backups for recovery

Service bureau: A. An organization that can provide on-site or off-site IT services in the event of a disaster
