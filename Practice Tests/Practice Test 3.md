# CISSP Practice Test

Chapter 11: Practice Test 3
Fred's data role requires him to maintain system security plans and to ensure that system users and support staff get the training they need about security practices and acceptable use. What is the role that Fred is most likely to hold in the organization?

Data owner

System owner

User

Custodian

Answer:
B.  NIST SP 800-18 describes system owner responsibilities that include helping to develop system security plans, maintaining the plan, ensuring training, and identifying, implementing, and assessing security controls. A data owner is more likely to delegate these tasks to the system owner. Custodians may be asked to enforce those controls, whereas a user will be directly affected by them.

Sally is using IPsec's ESP component in transport mode. What important information should she be aware of about transport mode?

Transport mode provides full encryption of the entire IP packet.

Transport mode adds a new, unencrypted header to ensure that packets reach their destination.

Transport mode does not encrypt the header of the packet.

Transport mode provides no encryption; only tunnel mode provides encryption.

Answer:
C.  ESP's Transport mode encrypts IP packet data but leaves the packet header unencrypted. Tunnel mode encrypts the entire packet and adds a new header to support transmission through the tunnel.

Which one of the following is not an essential process area for the Repeatable phase of the Software Capability Maturity Model (SW-CMM)?

Software Project Planning

Software Quality Management

Software Project Tracking

Software Subcontract Management

Answer:
B.  In level 2, the Repeatable level of the SW-CMM, the organization introduces basic life cycle management processes. Reuse of code in an organized fashion begins, and repeatable results are expected from similar projects. The crucial process areas for this level include Requirements Management, Software Project Planning, Software Project Tracking and Oversight, Software Subcontract Management, Software Quality Assurance, and Software Configuration Management. Software Quality Management is a process that occurs during level 4, the Managed stage of the SW-CMM.

Ben wants to provide predictive information about his organization's risk exposure in an automated way as part of an ongoing organizational risk management plan. What should he use to do this?

KRIs

Quantitative risk assessments

KPIs

Penetration tests

Answer:
A.  Key risk indicators (KRIs) are often used to monitor risk for organizations that establish an ongoing risk management program. Using automated data gathering and tools that allow data to be digested and summarized can provide predictive information about how organizational risks are changing. KPIs are key performance indicators, which are used to assess how an organization is performing. Quantitative risk assessments are good for point-in-time views with detailed valuation and measurement-based risk assessments, whereas a penetration test would provide details of how well an organization's security controls are working.

In the image shown here, what does system B send to system A at step 2 of the three-way TCP handshake?

Larger View
A sample T C P three-way handshake diagram. System A is connected system B, and then continues.
SYN

ACK

FIN/ACK

SYN/ACK

Answer:
D.  The three-way handshake is SYN, SYN/ACK, ACK. System B should respond with “Synchronize and Acknowledge” to System A after it receives a SYN.

Chris is conducting reconnaissance on a remote target and discovers that pings are allowed through his target's border firewall. What can he learn by using pings to probe the remote network?

Which systems respond to pings, a rough network topology, and potentially the location of additional firewalls

A list of all of the systems behind the target's firewall

The hostnames and time to live (TTL) for each pingable system and the ICMP types allowed through the firewall

Router advertisements, echo request responses, and potentially which hosts are tarpitted

Answer:
A.  Systems that respond to pings will show the time to live for packets that reach them. Since TTL is decremented at each hop, this can help build a rough network topology map. In addition, some firewalls respond differently to pings than a normal system, which means pinging a network can sometimes reveal the presence of firewalls that would otherwise be invisible. Hostnames are revealed by a DNS lookup, and ICMP types allowed through a firewall are not revealed by only performing a ping. ICMP can be used for router advertisements, but pinging won't show them!

Jake is conducting a review of his organization's identity and access management program. During his review, he is verifying the privileges assigned to each user and ensuring that they match with business requirements. What element of the program is he reviewing?

Identification

Accounting

Authorization

Authentication

Answer:
C.  Authorization defines what a subject can or can't do. Identification occurs when a subject claims an identity, accounting is provided by the logs and audit trail that track what occurs on a system, and authentication occurs when that identity is validated.

Faith is looking at the /etc/passwd file on a system configured to use shadowed passwords. When she examines a line in the file for a user with interactive login permissions, what should she expect to see in the password field?

Plaintext password

Hashed password

x

*

Answer:
C.  When a system uses shadowed passwords, the hashed password value is stored in /etc/shadow instead of /etc/passwd. The /etc/passwd file would not contain the password in plaintext or hashed form. Instead, it would contain an x to indicate that the password hash is in the shadow file. The * character is normally used to disable interactive logins to an account.

Berta is analyzing the logs of the Windows Firewall on one of her servers and comes across the entries shown in this figure. What type of attack do these entries indicate?

Larger View
A sample log file of the windows firewall.
SQL injection

Port scan

Teardrop

Land

Answer:
B.  The log entries show the characteristic pattern of a port scan. The attacking system sends connection attempts to the target system against a series of commonly used ports.

Danielle is testing tax software, and part of her testing process requires her to input a variety of actual tax forms to verify that the software produces the right answers. What type of testing is Danielle performing?

Use-case testing

Dynamic testing

Fuzzing

Misuse testing

Answer:
A.  Testing for desired functionality is use-case testing. Dynamic testing is used to determine how code handles variables that change over time. Misuse testing focuses on how code handles examples of misuse, and fuzzing feeds unexpected data as an input to see how the code responds.

After 10 years working in her organization, Cassandra is moving into her fourth role, this time as a manager in the accounting department. What issue is likely to show up during an account review if her organization does not have strong account maintenance practices?

An issue with least privilege

Privilege creep

Account creep

Account termination

Answer:
B.  Privilege creep is a common problem when employees change roles over time and their privileges and permissions are not properly modified to reflect their new roles. Least privilege issues are a design or implementation problem, and switching roles isn't typically what causes them to occur. Account creep is not a common industry term, and account termination would imply that someone has removed her account instead of switching her to new groups or new roles.

IP addresses like 10.10.10.10 and 172.19.24.21 are both examples of what type of IP address?

Public IP addresses

Prohibited IP addresses

Private IP addresses

Class B IP ranges

Answer:
C.  These are examples of private IP addresses. RFC 1918 defines a set of private IP addresses for use in internal networks. These private addresses including 10.0.0.0 to 10.255.255.255, 172.16.0.0 to 172.31.255.255, and 192.168.0.0 to 192.168.255.255 should never be routable on the public Internet.

Ben is reviewing the password recovery mechanism used by his website and discovers that the approach uses cognitive authentication through the use of security questions. What is the major issue with this approach?

It prevents the use of tokens.

The question's answer may be easy to find on the Internet.

Cognitive passwords require users to think to answer the question, and not all users may be able to solve the problems presented.

Cognitive passwords don't support long passwords.

Answer:
B.  A cognitive password authenticates users based on a series of facts or answers to questions that they know. Preset questions for cognitive passwords typically rely on common information about a user like their mother's maiden name or the name of their pet, and that information can frequently be found on the Internet. The best cognitive password systems let users make up their own questions.

Megan needs to create a forensic copy of a hard drive that will be used in an investigation. Which of the following tools is best suited to her work?

xcopy

dd

DBAN

ImageMagick

Answer:
B.  The Linux tool dd creates a bit-by-bit copy of the target drive that is well suited to forensic use, and special forensic versions of dd exist that can provide even more forensic features. Simply copying files using a tool like xcopy does not create a forensically sound copy. DBAN is a drive wiping tool and would cause Megan to lose the data she is seeking to copy. ImageMagick is a graphics manipulation and editing program.

Kay is selecting an application management approach for her organization. Employees need the flexibility to install software on their systems, but Kay wants to prevent them from installing certain prohibited packages. What type of approach should she use?

Antivirus

Whitelist

Blacklist

Heuristic

Answer:
C.  The blacklist approach to application control blocks certain prohibited packages but allows the installation of other software on systems. The whitelist approach uses the reverse philosophy and allows only approved software. Antivirus software would detect the installation of malicious software only after the fact. Heuristic detection is a variant of antivirus software.

Donna is a security administrator for a healthcare provider located in the United States and is reviewing their payment processing system. It contains data relating to the past, present, or future payment for the provision of healthcare to an individual. How would this information be classified under HIPAA?

PCI

Personal billing data

PHI

PII

Answer:
C.  Protected health information (PHI) is specifically defined by HIPAA to include information about an individual's medical bills. PCI could refer to the payment card industry's security standard but would apply only in relation to payment cards. PII is a broadly defined term for personally identifiable information, and personal billing data isn't a broadly used industry term.

Harold's company has a strong password policy that requires a minimum length of 12 characters and the use of both alphanumeric characters and symbols. What technique would be the most effective way for an attacker to compromise passwords in Harold's organization?

Brute-force attack

Dictionary attack

Rainbow table attack

Social engineering attack

Answer:
D.  A social engineering attack may trick a user into revealing their password to the attacker. Other attacks that depend on guessing passwords, such as brute-force attacks, rainbow table attacks, and dictionary attacks, are unlikely to be successful in light of the organization's strong password policy.

While traveling, James is held at knifepoint and forced to log into his laptop. What is this called?

Duress

Antisocial engineering

Distress

Knifepoint hacking

Answer:
A.  When someone is forced to perform an action under threat, it is known as duress.

Kayla recently took a position at a new start-up company that runs entirely in the cloud. The company leverages a major IaaS provider for hosting its web services and a SaaS email system. Both of these providers operate multitenant environments. What term best describes the type of cloud environment this organization uses?

Public cloud

Dedicated cloud

Private cloud

Hybrid cloud

Answer:
A.  The term that best describes the type of cloud environment used by Kayla's company, which leverages a major IaaS provider for hosting its web services and a SaaS email system operating in multitenant environments, is a public cloud. A public cloud is where the services are delivered over the public Internet and shared across different organizations. A dedicated cloud, also known as a private cloud, is operated solely for one organization, and this is not the case for Kayla's company. A private cloud is infrastructure operated solely for a single organization, whether managed internally or by a third-party, and hosted either internally or externally, which also does not apply here. A hybrid cloud is a composition of two or more cloud delivery models (private, community, or public) that remain distinct entities but are bound together, offering the benefits of multiple deployment models, which again does not match the company's use of exclusively public cloud services.

Cameron is responsible for backing up his company's primary file server. He configured a backup schedule that performs full backups every Monday evening at 9 p.m. and incremental backups on other days of the week at that same time. How many files will be copied in Wednesday's backup?

A sample file modification list. It includes number of files created in mondat, Tuesday, and Wednesday. A maximum of 6 files are created in Wednesday.
1

2

5

6

Answer:
B.  In this scenario, all of the files on the server will be backed up on Monday evening during the full backup. Tuesday's incremental backup will include all files changed since Monday's full backup: files 1, 2, and 5. Wednesday's incremental backup will then include all files modified since Tuesday's incremental backup: files 3 and 6. Therefore, only two files are included in Wednesday's incremental backup.

Susan uses a SPAN port to monitor traffic to her production website and uses a monitoring tool to identify performance issues in real time. What type of monitoring is she conducting?

Passive monitoring

Active monitoring

Synthetic monitoring

Signature-based monitoring

Answer:
A.  Susan is performing passive monitoring, which uses a network tap or SPAN port to capture traffic to analyze it without impacting the network or devices that it is used to monitor. Synthetic, or active, monitoring uses recorded or generated traffic to test for performance and other issues. Signature-based technologies include IDS, IPS, and antimalware systems.

In what type of attack do attackers manage to insert themselves into a connection between a user and a legitimate website?

Man-in-the-middle attack

Fraggle attack

Wardriving attack

Meet-in-the-middle attack

Answer:
A.  In a man-in-the-middle attack, attackers manage to insert themselves into a connection between a user and a legitimate website, relaying traffic between the two parties while eavesdropping on the connection. Although similarly named, the meet-in-the-middle attack is a cryptographic attack that does not necessarily involve connection tampering. Fraggle is a network-based denial-of-service attack using UDP packets. Wardriving is a reconnaissance technique for discovering open or weakly secured wireless networks.

Which one of the following would be considered an example of infrastructure-as-a-service cloud computing?

Payroll system managed by a vendor and delivered over the web

Application platform managed by a vendor that runs customer code

Servers provisioned by customers on a vendor-managed virtualization platform

Web-based email service provided by a vendor

For questions 24–26, please refer to the following scenario:

Darcy is an information security risk analyst for Roscommon Agricultural Products. She is currently trying to decide whether the company should purchase an upgraded fire suppression system for their primary data center. The data center facility has a replacement cost of $2 million.

After consulting with actuaries, data center managers, and fire subject-matter experts, Darcy determined that a typical fire would likely require the replacement of all equipment inside the building but not cause significant structural damage. Together, they estimated that recovering from the fire would cost $750,000. They also determined that the company can expect a fire of this magnitude once every 50 years.

Answer:
C.  One of the core capabilities of infrastructure as a service is providing servers on a vendor-managed virtualization platform. Web-based payroll and email systems are examples of software as a service. An application platform managed by a vendor that runs customer code is an example of platform as a service.

Based on the information in this scenario, what is the exposure factor for the effect of a fire on the Roscommon Agricultural Products data center?

7.5%

15.0%

27.5%

37.5%

Answer:
D.  The exposure factor is the percentage of the facility that risk managers expect will be damaged if a risk materializes. It is calculated by dividing the amount of damage by the asset value. In this case, that is $750,000 in damage divided by the $2 million facility value, or 37.5%.

Based on the information in this scenario, what is the annualized rate of occurrence for a fire at the Roscommon Agricultural Products data center?

0.002

0.005

0.02

0.05

Answer:
C.  The annualized rate of occurrence is the number of times each year that risk analysts expect a risk to happen. In this case, the analysts expect fires will occur once every 50 years, or 0.02 times per year.

Based on the information in this scenario, what is the annualized loss expectancy for a fire at the Roscommon Agricultural Products data center?

$15,000

$25,000

$75,000

$750,000

Answer:
A.  The annualized loss expectancy is calculated by multiplying the single loss expectancy (SLE) by the annualized rate of occurrence (ARO). In this case, the SLE is $750,000, and the ARO is 0.02. Multiplying these numbers together gives you the ALE of $15,000.

Which one of the following techniques uses statistical methods to select a small number of log records from a large pool for further analysis with the goal of choosing a set of records that is representative of the entire pool?

Clipping

Randomization

Sampling

Selection

Answer:
C.  The two main methods of choosing records from a large pool for further analysis are sampling and clipping. Sampling uses statistical techniques to choose a sample that is representative of the entire pool, while clipping uses threshold values to select those records that exceed a predefined threshold because they may be of most interest to analysts.

Mike wants to ensure that third-party users of his service's API can be tracked to prevent abuse of the API. What should he implement to help with this?

Session IDs

An API firewall

API keys

An API buffer

Answer:
C.  API keys, or application programming interface keys, are passed to services and identify the program, developer, or user. With this information, Mike can programmatically control API usage per user. Of course, if the keys are inadvertently exposed, the API keys themselves could be abused. Session IDs are typically used to identify users of an application, not an API. API firewalls and API buffers were made up for this question.

Fran is a web developer who works for an online retailer. Her boss asked her to create a way that customers can easily integrate themselves with Fran's company's site. They need to be able to check inventory in real time, place orders, and check order status programmatically without having to access the web page. What can Fran create to most directly facilitate this interaction?

An API

A web scraper

A data dictionary

A call center

Answer:
A.  An application programming interface (API) allows external users to directly call routines within Fran's code. They can embed API calls within scripts and other programs to automate interactions with Fran's company. A web scraper or call center might facilitate the same tasks, but they do not do so in a direct integration. Data dictionaries might provide useful information, but they also do not allow direct integration.

Todd's data center facility recently experienced a series of events that involved the momentary loss of power. What term best describes these events?

Fault

Blackout

Sag

Brownout

Answer:
A.  A fault is a momentary loss of power. Blackouts are sustained complete losses of power. Sags and brownouts are not complete power disruptions but rather periods of low-voltage conditions.

Lauren's team of system administrators each deals with hundreds of systems with varying levels of security requirements and finds it difficult to handle the multitude of usernames and passwords they each have. What type of solution should she recommend to ensure that passwords are properly handled and that features like logging and password rotation occur?

A credential management system

A strong password policy

Separation of duties

Single sign-on

Answer:
A.  Lauren's team would benefit from a credential management system. Credential management systems offer features like password management, multifactor authentication to retrieve passwords, logging, audit, and password rotation capabilities. A strong password policy would only make maintenance of passwords for many systems a more difficult task if done manually. Single sign-on would help if all the systems had the same sensitivity levels, but different credentials are normally required for higher-sensitivity systems.

Ed's Windows system can't connect to the network, and ipconfig shows the following:

Larger View
A screenshot pof a sample I P configuration. It reads ethernet adapter local area connection. It includes connection specific D N S suffix, link-local I P address, subnet mask, and default gateway.
What has occurred on the system?

The system has been assigned an invalid IP address by its DHCP server.

The system has a manually assigned IP address.

The system has failed to get a DHCP address and has assigned itself an address.

The subnet mask is set incorrectly, and the system cannot communicate with the gateway.

Answer:
C.  Windows systems will assign themselves an APIPA address between 169.254.0.1 and 169.254.255.254 if they cannot contact a DHCP server.

Gina is performing the initial creation of user accounts for a batch of new employees. What phase of the provisioning process is she conducting?

Enrollment

Clearance verification

Background checks

Initialization

Answer:
A.  Enrollment, or registration, is the initial creation of a user account in the provisioning process. Clearance verification and background checks are sometimes part of the process that ensures that the identity of the person being enrolled matches who they claim to be. Initialization is not used to describe the provisioning process.

Ravi is developing procedures for forensic investigations conducted by his organization and would like to differentiate based upon the evidentiary standards commonly used for each type of investigation. What type of forensic investigation typically has the highest evidentiary standards?

Administrative

Criminal

Civil

Industry

Answer:
B.  Criminal forensic investigations typically have the highest standards for evidence, as they must be able to help prove the case beyond a reasonable doubt. Administrative investigations merely need to meet the standards of the organization and to be able to be defended in court, while civil investigations operate on a preponderance of evidence. There is not a category of forensic investigation referred to as “industry” in the CISSP exam's breakdown of forensic types.

What U.S. legal protection prevents law enforcement agencies from searching an American facility or electronic system without either probable cause or consent?

First Amendment

Fourth Amendment

Fifth Amendment

Fifteenth Amendment

Answer:
B.  The Fourth Amendment states, in part, that “the right of the people to be secure in their persons, houses, papers and effects, against unreasonable searches and seizures, shall not be violated, and no Warrants shall issue, but upon probable cause, supported by Oath or affirmation, and particularly describing the place to be searched, and the persons or things to be seized.” The First Amendment contains protections related to freedom of speech. The Fifth Amendment ensures that no person will be required to serve as a witness against themselves. The Fifteenth Amendment protects the voting rights of citizens.

Tom believes that a customer of his Internet service provider has been exploiting a vulnerability in his system to read the email messages of other customers. If true, what law did the customer most likely violate?

ECPA

CALEA

HITECH

Privacy Act

Answer:
A.  The Electronic Communications Privacy Act (ECPA) makes it a crime to invade the electronic privacy of an individual. It prohibits the unauthorized monitoring of email and voicemail communications.

In the protection ring model shown here, what ring contains user programs and applications?

A sample protecting ring model. The first circle is labeled ring 0, followed by rings 1, 2, and 3.
Ring 0

Ring 1

Ring 2

Ring 3

Answer:
D.  The kernel lies within the central ring, Ring 0. Ring 1 contains other operating system components. Ring 2 is used for drivers and protocols. User-level programs and applications run at Ring 3. Rings 0–2 run in privileged mode, whereas Ring 3 runs in user mode.

In virtualization platforms, what name is given to the module that is responsible for controlling access to physical resources by virtual resources?

Guest machine

SDN

Kernel

Hypervisor

Answer:
D.  The hypervisor runs within the virtualization platform and serves as the moderator between virtual resources and physical resources.

In which cloud computing model does a customer share computing infrastructure with other customers of the cloud vendor where one customer may not know the other's identity?

Public cloud

Private cloud

Community cloud

Shared cloud

Answer:
A.  In the public cloud computing model, the vendor builds a single platform that is shared among many different customers. This is also known as the shared tenancy model.

Justin recently participated in a disaster recovery plan test where the team sat together and discussed the response to a scenario but did not actually activate any disaster recovery controls. What type of test did he participate in?

Read-through

Full interruption test

Parallel test

Tabletop exercise

Answer:
D.  During a tabletop exercise, team members come together and walk through a scenario without making any changes to information systems. The read-through is the least disruptive type of disaster recovery test. During a read-through, team members each review the contents of their disaster recovery checklists on their own and suggest any necessary changes. During a parallel test, the team actually activates the disaster recovery site for testing, but the primary site remains operational. During a full interruption test, the team takes down the primary site and confirms that the disaster recovery site is capable of handling regular operations. The full interruption test is the most thorough test but also the most disruptive.

Susan wants to integrate her website to allow users to use accounts from sites like Google. What technology should she adopt?

Kerberos

LDAP

OpenID Connect

SESAME

Answer:
C.  OpenID Connect is a widely supported standard that allows a user to use a single account to log into multiple sites, and Google accounts are frequently used with OpenID Connect.

Tom is conducting a business continuity planning effort for Orange Blossoms, a fruit orchard located in Central Florida. During the assessment process, the committee determined that there is a small risk of snow in the region but that the cost of implementing controls to reduce the impact of that risk is not warranted. They elect to not take any specific action in response to the risk. What risk management strategy is Orange Blossoms pursuing?

Risk mitigation

Risk transference

Risk avoidance

Risk acceptance

Answer:
D.  Risk acceptance occurs when an organization determines that the costs involved in pursuing other risk management strategies are not justified and they choose not to pursue any action.

Paul is reviewing the contents of an audit report and discovers a finding that a manager in the accounting department has full access to perform every function in the financial system. What security principles have most likely been violated? (Select all that apply.)

Separation of duties

Job rotation

Management review

Least privilege

Answer:
A, D.  Accounting departments are normally required to separate sensitive duties, such as the ability to add a new vendor and issue a check. Allowing the manager to perform both of these actions would, therefore, violate the principle of separation of duties. Also, it is quite likely that the manager does not need all of these privileges to carry out their work, violating the principle of least privilege. There is no indication that the situation does not follow job rotation assignments or that the access was not properly granted and subject to a management review.

Jack's organization is a multinational nonprofit that has small offices in many developing countries throughout the world. They need to implement an access control system that allows flexibility and that can work despite poor Internet connectivity at their locations. What is the best type of access control design for Jack's organization?

Centralized access control

Mandatory access control

Decentralized access control

Rule-based access control

Answer:
C.  Decentralized access control makes sense because it allows local control over access. When network connectivity to a central control point is a problem or if rules and regulations may vary significantly from location to location, centralized control can be less desirable than decentralized control despite its challenges with consistency. Since the problem does not describe specific control needs, mandatory access control and rule-based access controls could fit the need but aren't the best answer.

What U.S. government classification label is applied to information that, if disclosed, could cause serious damage to national security and also requires that the damage that would be caused is able to be described or identified by the classification authority?

Classified

Secret

Confidential

Top Secret

For questions 46–49, please refer to the following scenario:

Mike and Renee would like to use an asymmetric cryptosystem to communicate with each other. They are located in different parts of the country but have exchanged encryption keys by using digital certificates signed by a mutually trusted certificate authority.

Answer:
B.  The U.S. government classifies data that could reasonably be expected to cause damage to national security if disclosed, and for which the damage can be identified or described, as Secret. The U.S. government does not use Classified in its formal four levels of classification. Top Secret data could cause exceptionally grave damage, whereas Confidential data could be expected to cause damage.

When the certificate authority (CA) created Renee's digital certificate, what key was contained within the body of the certificate?

Renee's public key

Renee's private key

CA's public key

CA's private key

Answer:
A.  The purpose of a digital certificate is to provide the general public with an authenticated copy of the certificate subject's public key.

When the certificate authority created Renee's digital certificate, what key did it use to digitally sign the completed certificate?

Renee's public key

Renee's private key

CA's public key

CA's private key

Answer:
D.  The last step of the certificate creation process is the digital signature. During this step, the certificate authority signs the certificate using its own private key.

When Mike receives Renee's digital certificate, what key does he use to verify the authenticity of the certificate?

Renee's public key

Renee's private key

CA's public key

CA's private key

Answer:
C.  When an individual receives a copy of a digital certificate, the person verifies the authenticity of that certificate by using the CA's public key to validate the digital signature contained on the certificate.

Mike would like to send Renee a private message using the information gained during this exchange. What key should he use to encrypt the message?

Renee's public key

Renee's private key

CA's public key

CA's private key

Answer:
A.  Mike uses the public key that he extracted from Renee's digital certificate to encrypt the message that he would like to send to Renee.

Which one of the following tools may be used to directly violate the confidentiality of communications on an unencrypted VoIP network?

Nmap

Nessus

Wireshark

Nikto

Answer:
C.  Wireshark is a network monitoring tool that can capture and replay communications sent over a data network, including Voice over IP (VoIP) communications. Nmap, Nessus, and Nikto are all security tools that may identify security flaws in the network, but they do not directly undermine confidentiality because they do not have the ability to capture communications.

Which of the following is not true about the ISC2 Code of Ethics?

Adherence to the code is a condition of certification.

Failure to comply with the code may result in revocation of certification.

The code applies to all members of the information security profession.

Members who observe a breach of the code are required to report the possible violation.

Answer:
C.  The ISC2 Code of Ethics applies only to information security professionals who are members of ISC2. Adherence to the code is a condition of certification, and individuals found in violation of the code may have their certifications revoked. ISC2 members who observe a breach of the code are required to report the possible violation by following the ethics complaint procedures.

Which one of the following cryptographic algorithms supports the goal of nonrepudiation?

Blowfish

DES

AES

RSA

Answer:
D.  Nonrepudiation is possible only with an asymmetric encryption algorithm. RSA is an asymmetric algorithm. AES, DES, and Blowfish are all symmetric encryption algorithms that do not provide nonrepudiation.

Microsoft's STRIDE threat assessment framework uses six categories for threats: Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, and Elevation of Privilege. If a penetration tester is able to modify audit logs, what STRIDE categories best describe this issue?

Tampering and information disclosure

Elevation of privilege and tampering

Repudiation and denial of service

Repudiation and tampering

Answer:
D.  Modification of audit logs will allow repudiation because the data cannot be trusted, and thus actions can be provably denied. The modification of the logs is also a direct example of tampering. It might initially be tempting to answer elevation of privileges and tampering, as the attacker made changes to files that should be protected, but this is an unknown without more information. Similarly, the attacker may have accessed the files, resulting in information disclosure in addition to tampering, but again, this is not specified in the question. Finally, this did not cause a denial of service, and thus that answer can be ignored.

Carmen is reviewing her organization's web architecture and realizes that the web server is often under heavy load from users in different regions of the world. This load comes at unpredictable times. She would like to find a solution that minimizes the burden on her organization's servers and places content geographically closer to the user to decrease load time. What would be the best solution to Carmen's requirements?

Load balancer

Content delivery network

TLS acceleration

Web application firewall

Answer:
B.  Content delivery networks (CDNs) place endpoints at geographic locations around the world and then cache customer content at those endpoints. The CDN servers then handle user requests for data, greatly reducing the burden on the organization's own servers and improving load time. Load balancers would distribute the load among Carmen's own servers and would, therefore, not meet her requirements. TLS acceleration may improve load time by reducing the burden of encryption on servers, but they would not place content closer to end users. Web application firewalls would be used to protect the servers against attack, but this does not match Carmen's requirements.

Brian recently joined an organization that runs the majority of its services on a virtualization platform located in its own data center but also leverages an IaaS provider for hosting its web services and an SaaS email system. What term best describes the type of cloud environment this organization uses?

Public cloud

Dedicated cloud

Private cloud

Hybrid cloud

Answer:
D.  The scenario describes a mix of public cloud and private cloud services. This is an example of a hybrid cloud environment.

The government agency that Ben works at installed a new access control system. The system uses information such as Ben's identity, department, normal working hours, job category, and location to make authorization decisions. What type of access control system did Ben's employer adopt?

Role-based access control

Attribute-based access control

Administrative access control

System discretionary access control

Answer:
B.  Each of the attributes linked to Ben's access provides information for an attribute-based information control system. Attribute-based information controls like those described in NIST SP 800-162 can take many details about the user, actions, and objects into consideration before allowing access to occur. A role-based access control would simply consider Ben's role, whereas both administrative and system discretionary access controls are not commonly used terms to describe access controls.

Ben is building his organization's security awareness and training program and would like to include interactive activities that better engage users. What techniques would best help him meet this goal? (Select all that apply.)

Policy reviews

Gamification

Classroom training

Phishing simulations

Answer:
B, D.  All of these techniques are valid components of a security awareness and training program. However, users generally find policy reviews and classroom training boring. Gamification and phishing simulations are designed to bring interactivity to the effort and make it more interesting and engaging for users.

Andrew believes that a digital certificate belonging to his organization was compromised and would like to add it to a certificate revocation list (CRL). Who must add the certificate to the CRL?

Andrew

The root authority for the top-level domain

The CA that issued the certificate

The revocation authority for the top-level domain

Answer:
C.  Certificates may only be added to a certificate revocation list by the certificate authority that created the digital certificate.

Amanda is considering the implementation of a database recovery mechanism recommended by a consultant. In the recommended approach, an automated process will move records of transactions from the primary site to a backup site on an hourly basis. What type of database recovery technique is the consultant describing?

Electronic vaulting

Transaction logging

Remote mirroring

Remote journaling

Answer:
D.  Remote journaling transfers transaction logs to a remote site on a more frequent basis than electronic vaulting, typically hourly. Transaction logging is not a recovery technique alone; it is a process for generating the logs used in remote journaling. In an electronic vaulting approach, automated technology moves database backups from the primary database server to a remote site on a scheduled basis, typically daily. Remote mirroring maintains a live database server at the backup site and mirrors all transactions at the primary site on the server at the backup site.

Ron is working to classify information used by his organization and would like to include all information that might trigger a U.S. state data breach notification law in his classification scheme. Which of the following categories of information should he include, assuming that they are connected to a specific individual? (Select all that apply.)

Bank account number and PIN

Driver's license number

Marital status

Social Security number

Answer:
A, B, D.  The specific data elements covered by state data breach notification laws vary from state to state, but most include Social Security numbers, drivers' license numbers, and bank account numbers when paired with a PIN. No state data breach notification laws include marital status as a covered element.

Which one of the following investigation types has the loosest standards for the collection and preservation of information?

Civil investigation

Operational investigation

Criminal investigation

Regulatory investigation

Answer:
B.  Operational investigations are performed by internal teams to troubleshoot performance or other technical issues. They are not intended to produce evidence for use in court and, therefore, do not have the rigid collection standards of criminal, civil, or regulatory investigations.

Sue was required to sign an NDA when she took a job at her new company. Why did the company require her to sign it?

To protect the confidentiality of their data

To ensure that Sue did not delete their data

To prevent Sue from directly competing with them in the future

To require Sue to ensure the availability for their data as part of her job

Answer:
A.  Nondisclosure agreements (NDAs) are designed to protect the confidentiality of an organization's data, including trade secrets during and after the person's employment. NDAs do not protect against deletion or availability issues, and noncompete agreements would be required to stop competition.

Susan is concerned about the FAR associated with her biometric technology. What is the best method to deal with the FAR?

Adjust the CER.

Change the sensitivity of the system to lower the FRR.

Add a second factor.

Replace the biometric system.

Answer:
C.  Adding a second factor can ensure that users who might be incorrectly accepted are not given access due to a higher than desired false acceptance rate (FAR) from accessing a system. The CER is the crossover between the false acceptance and false rejection rate (FRR) and is used as a way to measure the accuracy of biometric systems. Changing the sensitivity to lower the FRR may actually increase the FAR, and replacing a biometric system can be expensive in terms of time and cost.

Which data role in an organization is most likely to perform backups of critical systems to ensure that their availability is preserved?

Business owners

Data users

Data owners

Data custodians

Answer:
D.  Data custodians are typically responsible for the technical environment and procedures related to data management, which include the backup and recovery of systems to ensure data availability. While data owners are accountable for the data and may decide what needs to be backed up, they do not perform the actual backups. Business owners and data users are more focused on the operational and decision-making aspects of the data's business use and are generally not involved in the technical aspects of data maintenance such as system backups.

Ron is the CISO of a U.S. company that is entering into a business partnership with a European firm. The European firm will be sending his company customer records to run through Ron's firm's proprietary credit scoring algorithm. Under GDPR, what role will Ron's company have relative to the customer data?

Data controller

Data owner

Data subject

Data processor

Answer:
D.  Ron's company is a data processor in this instance, as it is receiving records from the European firm. The European firm is the data controller in this case, as they bear responsibility for the data. The individuals described in the records are the data subjects. Data owners are tasked with making decisions about data such as who receives access to it and how it is used.

Tonya recently introduced a new security control in her organization for emergency access to system administrator privileges. Under this procedure, two qualified administrators must agree to retrieve emergency credentials. What term best describes this process?

Separation of duties

Least privilege

Two-person control

Multifactor authentication

Answer:
C.  This is an example of two-person control, where two people must concur to perform a sensitive action. Separation of duties is a slightly different principle, where one individual is prevented from holding the privileges to perform two separate actions that, when combined, would result in excessive permissions. Least privilege says that an individual should have the minimum necessary set of permissions to carry out their job functions. There is no indication that least privilege is violated in this scenario. Multifactor authentication is an important security control, but the scenario does not mention whether the administrators use multifactor authentication to perform these activities.

Attackers who compromise websites often acquire databases of hashed passwords. What technique can best protect these passwords against automated password cracking attacks that use precomputed values?

Using the MD5 hashing algorithm

Using the SHA-1 hashing algorithm

Salting

Double-hashing

Answer:
C.  Salting adds random text to the password before hashing in an attempt to defeat automated password cracking attacks that use precomputed values. MD5 and SHA-1 are both common hashing algorithms, so using them does not add any security. Double-hashing would only be a minor inconvenience for an attacker and would not be as effective as the use of salting.

Jim starts a new job as a system engineer, and he is reviewing a team document entitled “Forensic Response Guidelines.” Which one of the following statements is not true?

Jim must comply with the information in this document.

The document contains information about forensic examinations.

Jim should read the document thoroughly.

The document is likely based on industry best practices.

Answer:
A.  Guidelines provide advice based on best practices developed throughout industry and organizations, but they are not compulsory. Compliance with guidelines is optional.

Evan is reviewing his access control system to ensure that no user is able to read information that is above their security clearance level. What security model is he enforcing?

Bell–LaPadula

Star security property

Discretionary security property

Biba

Answer:
A.  The Bell–LaPadula model includes the simple security property, which says that no user should be able to read information above their security clearance level. It also includes the star property, which says that a subject should not be able to write data to an object below their security clearance level, and the discretionary security property, which uses access matrices to control access. The Biba integrity model says that users should not be able to read data below their security clearance level.

Ben needs to verify that the most recent patch for his organization's critical application did not introduce issues elsewhere. What type of testing does Ben need to conduct to ensure this?

Unit testing

White box

Regression testing

Black box

Answer:
C.  Regression testing ensures proper functionality of an application or system after it has been changed. Unit testing focuses on testing each module of a program instead of against its previous functional state. White- and black-box testing both describe the amount of knowledge about a system or application, rather than a specific type or intent for testing.

Tamara recently decided to purchase cyber-liability insurance to cover her company's costs in the event of a data breach. What risk management strategy is she pursuing?

Risk acceptance

Risk mitigation

Risk transference

Risk avoidance

Answer:
C.  Risk transference involves shifting the impact of a potential risk from the organization incurring the risk to another organization. Insurance is a common example of risk transference.

Which of the following is not one of the four canons of the ISC2 Code of Ethics?

Avoid conflicts of interest that may jeopardize impartiality.

Protect society, the common good, necessary public trust and confidence, and the infrastructure.

Act honorably, honestly, justly, responsibly, and legally.

Provide diligent and competent service to principals.

Answer:
A.  The four canons of the ISC2 Code of Ethics are to protect society, the common good, the necessary public trust and confidence, and the infrastructure; act honorably, honestly, justly, responsibly, and legally; provide diligent and competent service to principals; and advance and protect the profession.

Jim wants to allow a partner organization's Active Directory forest (B) to access his domain forest's (A)'s resources but doesn't want to allow users in his domain to access B's resources. He also does not want the trust to flow upward through the domain tree as it is formed. What should he do?

Set up a two-way transitive trust.

Set up a one-way transitive trust.

Set up a one-way nontransitive trust.

Set up a two-way nontransitive trust.

Answer:
C.  A trust that allows one forest to access another's resources without the reverse being possible is an example of a one-way trust. Since Jim doesn't want the trust path to flow as the domain tree is formed, this trust has to be nontransitive.

Susan's team is performing code analysis by manually reviewing the code for flaws. What type of analysis are they performing?

Gray box

Static

Dynamic

Fuzzing

Answer:
B.  Susan's team is performing static analysis, which analyzes nonrunning code. Dynamic analysis uses running code, whereas gray-box assessments are a type of assessment done without full knowledge. Fuzzing feeds unexpected inputs to a program as part of dynamic analysis.

Kevin's organization recently suffered a ransomware attack, and he is considering paying the ransom. Which of the following statements are true about paying the ransom? (Select all that apply.)

There is no guarantee that he will receive the decryption key.

The attackers have encrypted his data but do not have access to the data itself.

Restoring from backup will not recover information.

Paying ransoms may be illegal.

Answer:
A, D.  Kevin may choose to pay the ransom, and he may regain access to his data by doing so, but there is no guarantee that the attackers will deliver the decryption key after he makes payment. Additionally, the payment of the ransom may be illegal depending upon the circumstances. He cannot be sure that the attackers do not have access to his information, as the ransomware may have copied data for the attackers' use. Restoring from backup is a good method to regain access to information encrypted by ransomware.

What feature of a Trusted Platform Module (TPM) creates a hash summary of the system configuration to verify that changes have not been made?

Remote attestation

Binding

Sealing

RNG

Answer:
A.  Remote attestation creates a hash value from the system configuration to confirm the integrity of the configuration. Binding and sealing are techniques used by the TPM to encrypt data. The random number generator (RNG) function of the TPM is used to support cryptographic operations.

Gary is concerned that the environmental controls in his organization's data center may not be effectively controlling humidity. Which of the following circumstances may result from humidity issues? (Select all that apply.)

Static electricity damaging equipment

Fires in power supplies

Corrosion of equipment

Physical access control failures

Answer:
A, C.  Situations where humidity is too high may result in the buildup of moisture and corrosion of equipment. If humidity falls too low, it may result in static electricity issues. Humidity issues generally do not contribute to fires or physical access control failures.

Evan recently built an alternate processing facility that includes all of the hardware and data necessary to restore operations in a matter of minutes or seconds. What type of facility has he built?

Hot site

Warm site

Cold site

Mobile site

Answer:
A.  Hot sites contain all of the hardware and data necessary to restore operations and may be activated very quickly. Warm sites contain the necessary hardware but not the data. Cold sites contain neither hardware nor data. Mobile sites are easily transportable, which is not mentioned in this scenario.

Hadley is reviewing network traffic logs and is searching for syslog activity on his network. When he creates a filter to look for this traffic, which UDP port should he include?

443

514

515

445

Answer:
B.  Syslog uses UDP port 514. TCP-based implementations of syslog use TCP port 601 when unencrypted and use TCP port 6514 when encrypted with TLS. The other ports may look familiar because they are commonly used TCP ports: 443 is HTTPS, 515 is the LPD print service, and 445 is used for Windows SMB.

Fred finds a packet that his protocol analyzer shows with both PSH and URG set. What type of packet is he looking at, and what do the flags mean?

A UDP packet; PSH and URG are used to indicate that the data should be sent at high speed

A TCP packet; PSH and URG are used to clear the buffer and indicate that the data is urgent

A TCP packet; PSH and URG are used to preset the header and indicate that the speed of the network is unregulated

A UDP packet; PSH and URG are used to indicate that the UDP buffer should be cleared and that the data is urgent

Answer:
B.  PSH is a TCP flag used to clear the buffer, resulting in immediately sending data, and URG is the TCP urgent flag. These flags are not present in UDP headers.

What code review process is shown here?

Larger View
A flow diagram of a sample code review. It begins with planning, followed by overview, preparation, inspection, rework, and follow-up.
Static inspection

Fagan inspection

Dynamic inspection

Interface testing

Answer:
B.  Fagan inspection is a highly formalized review and testing process that uses planning, overview, preparation, inspection, rework, and follow-up steps. Static inspection looks at code without running it, dynamic inspection uses live programs, and interface testing tests where code modules interact.

During a log review, Karen discovers that the system she needs to gather logs from has the log setting shown here. What problem is Karen likely to encounter?

Larger View
A screenshot of a page titled log properties-application. Subscription tab is selected including options for application name, lig path, log size, created, modified, and accessed, The maximum log size is set to 20480.
Too much log data will be stored on the system.

The system is automatically purging archived logs.

The logs will not contain the information needed.

The logs will contain only the most recent 20 MB of log data.

Answer:
D.  The system is set to overwrite the logs and will replace the oldest log entries with new log entries when the file reaches 20 MB. The system is not purging archived logs because it is not archiving logs. Since there can be only 20 MB of logs, this system will not have stored too much log data, and the question does not provide enough information to know if there will be an issue with not having the information needed.

While investigating a widespread distributed denial-of-service attack, Matt types in the IP address of one of the attacking systems into his browser and sees the following page. What type of devices is the botnet likely composed of?

Larger View
A photograph displays two wall photo framesalong with a half visible light device.
SCADA

Cloud infrastructure

Web servers

IoT

For questions 84–86, please refer to the following scenario:

Alejandro is an incident response analyst for a large corporation. He is on the midnight shift when an intrusion detection system alerts him to a potential brute-force password attack against one of the company's critical information systems. He performs an initial triage of the event before taking any additional action.

Answer:
D.  The image shown is from a network-connected web camera. This is likely an Internet of Things (IoT) botnet, much like the Mirai botnet that had a major impact on world Internet traffic in 2016.

What stage of the incident response process is Alejandro currently conducting?

Detection

Response

Recovery

Mitigation

Answer:
A.  Alejandro is in the first stage of the incident response process, detection. During this stage, the intrusion detection system provides the initial alert, and Alejandro performs preliminary triaging to determine if an intrusion is actually taking place and whether the scenario fits the criteria for activating further steps of the incident response process (which include response, mitigation, reporting, recovery, remediation, and lessons learned).

If Alejandro's initial investigation determines that a security incident is likely taking place, what should be his next step?

Investigate the root cause.

File a written report.

Activate the incident response team.

Attempt to restore the system to normal operations.

Answer:
C.  After detection of a security incident, the next step in the process is response, which should follow the organization's formal incident response procedure. The first step of this procedure is activating the appropriate teams, including the organization's computer security incident response team (CSIRT).

As the incident response progresses, during which stage should the team conduct a root-cause analysis?

Response

Reporting

Remediation

Lessons learned

Answer:
C.  The root-cause analysis examines the incident to determine what allowed it to happen and provides critical information for repairing systems so that the incident does not recur. This is a component of the remediation step of the incident response process because the root-cause analysis output is necessary to fully remediate affected systems and processes.

Barry recently received a message from Melody that Melody encrypted using symmetric cryptography. What key should Barry use to decrypt the message?

Barry's public key

Barry's private key

Melody's public key

Shared secret key

Answer:
D.  When using symmetric cryptography, the sender encrypts a message using a shared secret key, and the recipient then decrypts the message with that same key. Only asymmetric cryptography uses the concept of public and private key pairs.

After you do automated functional testing with 100% coverage of an application, what type of error is most likely to remain?

Business logic errors

Input validation errors

Runtime errors

Error handling errors

Answer:
A.  Business logic errors are most likely to be missed by automated functional testing. If a complete coverage code test was conducted, runtime, input validation, and error handling issues are likely to have been discovered by automated testing. Any automated system is more likely to miss business logic errors, because humans are typically necessary to understand business logic issues.

During what phase of the incident response process would security professionals analyze the process itself to determine whether any improvements are warranted?

Lessons learned

Remediation

Recovery

Reporting

Answer:
A.  During the lessons learned phase, analysts close out an incident by conducting a review of the entire incident response process. This may include making recommendations for improvements to the process that will streamline the efficiency and effectiveness of future incident response efforts.

What U.S. law prevents the removal of protection mechanisms placed on a copyrighted work by the copyright holder?

HIPAA

DMCA

GLBA

ECPA

Answer:
B.  The Digital Millennium Copyright Act (DMCA) prohibits attempts to circumvent copyright protection mechanisms placed on a protected work by the copyright holder. The Health Insurance Portability and Accountability Act (HIPAA) governs the security and privacy of protected health information. The Gramm-Leach-Bliley Act (GLBA) governs the security and privacy of financial information. The Electronic Communications Privacy Act (ECPA) restricts eavesdropping on private communications.

Linda is selecting a disaster recovery facility for her organization, and she wants to retain independence from other organizations as much as possible. She would like to choose a facility that balances cost and recovery time, allowing activation in about one week after a disaster is declared. What type of facility should she choose?

Cold site

Warm site

Mutual assistance agreement

Hot site

Answer:
B.  Linda should choose a warm site. This approach balances cost and recovery time. Cold sites take a very long time to activate, measured in weeks or months. Hot sites activate immediately but are quite expensive. Mutual assistance agreements depend on the support of another organization.

Helen's organization handles large quantities of highly sensitive information. To help address this risk, she purchased a cyber-liability insurance policy. What type of risk response action is Helen taking?

Transfer

Avoid

Mitigate

Accept

Answer:
A.  Purchasing insurance is a way to transfer risk to another entity. Risk avoidance actions change business processes to eliminate a risk. Risk mitigation activities reduce the likelihood or impact of a risk occurring. Risk acceptance takes no action to control the risk other than acknowledging its presence.

What type of penetration testing provides detail on the scope of a penetration test—including items like what systems would be targeted—but does not provide full visibility into the configuration or other details of the systems or networks the penetration tester must test?

Crystal box

White box

Black box

Gray box

Answer:
D.  Gray-box testing is a blend of crystal-box (or white-box) testing, which provides full information about a target, and black-box testing, which provides little or no knowledge about the target.

Joanna would like to implement multifactor authentication for access to a restricted work area in her building. Which pairing of controls would best meet her requirement?

ID card and PIN

Password and retinal scan

ID card and access token

Retinal scan and fingerprint scan

Answer:
A.  The combination of an ID card (something you have) and a PIN (something you know) is a reasonable way to control access to a physical facility. The use of a password is not a user-friendly way to control access to a physical facility. The use of an ID card (something you have) in conjunction with an access token (something you have) does not constitute multifactor authentication because both are something you have factors. The same is true for the use of a retinal scan (something you are) and a fingerprint (something you are).

What network topology is used by modern-day Ethernet networks?

Star

Mesh

Ring

Bus

Answer:
A.  Ethernet networks in modern organizations use a star topology, where each device is directly connected to the switch and receives only traffic intended for that device. This reduces the possibility of eavesdropping on other devices.

Reed would like to add capabilities to his network that allow him to hide the identities of his users from remote web servers. Which one of the following tools would best meet his needs?

Proxy server

Content filter

Malware filter

Caching server

Answer:
A.  Proxy servers can act to anonymize web requests by hiding their true source IP addresses and removing identifying information. Content filters restrict the websites that users may access. Malware filters search for and block malicious code. Caching servers store local copies of frequently requested content to reduce loading time.

Evelyn is preparing a training program that will provide cybersecurity advice to users who often travel internationally. Which of the following topics requires special training to ensure that users do not run afoul of U.S. export control laws?

Encryption software

Content filtering

Firewall rules

Phishing simulations

Answer:
A.  U.S. export control laws contain special provisions around the use of encryption technology, and Evelyn should include details about the software used by her firm in the training. These regulations do not affect content filtering controls, firewall rules, or phishing simulations.

Skip needs to transfer files from his PC to a remote server. What protocol should he use instead of FTP?

SCP

SSH

HTTP

Telnet

Answer:
A.  Skip should use Secure Copy (SCP), which is a secure file transfer method. SSH is a secure command-line and login protocol, whereas HTTP is used for unencrypted web traffic. Telnet is an unencrypted command-line and login protocol.

Ben's New York–based commercial web service collects personal information from California residents. What does the California Online Privacy Protection Act require Ben to do to be compliant?

Ben must encrypt all personal data he receives.

Ben must comply with the EU GDPR.

Ben must have a conspicuously posted privacy policy on his site.

Ben must provide notice and choice for users of his website.

Answer:
C.  The California Online Privacy Protection Act requires that commercial websites that collect personal information from users in California conspicuously post a privacy policy. The act does not require compliance with the EU GDPR, nor does it use the GDPR concepts of notice or choice, and it does not require encryption of all personal data.

Grayson is reviewing his organization's password policies and would like to follow modern best practices. What is the recommended expiration period for passwords?

30 days

90 days

180 days

None

Answer:
D.  Modern recommendations from the National Institute of Standards and Technology (NIST) are that users should not be forced to change their passwords through the use of password expiration policies. More information on these recommendations can be found in NIST Special Publication (SP) 800-63B, “Digital Identity Guidelines.”

A consortium of colleges and universities recently worked to integrate their authentication systems so that students registered at one institution may use their credentials to access services at other institutions. What term best describes this arrangement?

Federation

Identity proofing

Enrollment

Provisioning

Answer:
A.  This is an example of federation, where user credentials from one organization are accepted as proof of identity by another organization. The users are not creating new accounts, so there is no identity proofing, enrollment, or provisioning activity taking place.

Olivia is selecting a new biometric authentication technology and is considering purchasing iris scanners. What advantage do iris scans have over most other types of biometric factors?

Iris scanners are harder to deceive.

Irises don't change as much as other factors.

Iris scanners are cheaper than other factors.

Iris scans cannot be easily replicated.

Answer:
B.  Iris scans have a longer useful life than many other types of biometric factors because they don't change throughout a person's life span (unless the eye itself is damaged). Iris scanners can be fooled in some cases by high-resolution images of an eye, and iris scanners are not significantly cheaper than other scanners.

Jen's firm received a new contract to develop information systems for use by a U.S. federal government agency. She is concerned about identifying any required security controls that must be in place. Which one of the following standards describes controls mandatory for use on U.S. government systems?

PCI DSS

ISO 27001

SABSA

NIST 800-53

Answer:
D.  NIST 800-53 is the standard that describes the security controls mandatory for use on U.S. federal government systems. It provides a catalog of security and privacy controls for all U.S. federal information systems except those related to national security. PCI DSS is a proprietary information security standard for organizations that handle payment cards and is not specific to government systems. ISO 27001 is an international standard on how to manage information security and is not specific to U.S. federal systems. SABSA is a framework and methodology for enterprise security architecture and service management, again not specific to the mandatory controls required by U.S. government systems.

Matthew, Richard, and Christopher would like to exchange messages with each other using symmetric cryptography. They want to ensure that each individual can privately send a message to another individual without the third person being able to read the message. How many keys do they need?

1

2

3

6

Answer:
C.  They need a key for every possible pair of users in the cryptosystem. The first key would allow communication between Matthew and Richard. The second key would allow communication between Richard and Christopher. The third key would allow communication between Christopher and Matthew.

Colleen is responsible for protecting credit card numbers as part of her organization's efforts to comply with PCI DSS. She would like to select an appropriate control to protect those numbers while in transit over the network. Which of the following controls would best meet this need?

FDE

SSL

TPM

TLS

Answer:
D.  All of these controls involve the use of encryption, but only Transport Layer Security (TLS) provides a strong, effective means for protecting data in transit. Secure Sockets Layer (SSL) is an outdated method for protecting data in transit that should no longer be used. Full disk encryption (FDE) provides encryption for data at rest. The Trusted Platform Module (TPM) manages encryption keys for use in FDE.

Joe is concerned about the confidentiality of email messages as they are transiting the Internet from his organization's servers to their final destination. What is the best way that Joe can ensure email confidentiality in transit?

Use TLS between the client and server.

Use SSL between the client and server.

Encrypt the email content.

Use a digital signature.

Answer:
C.  The SMTP protocol does not guarantee confidentiality between servers, making TLS or SSL between the client and server only a partial measure. Encrypting the email content can provide confidentiality; digital signatures can provide nonrepudiation.

Brenda is analyzing the web server logs after a successful compromise of her organization's web-based order processing application. She finds an entry in the log file showing that a user entered the following information as his last name when placing an order:

Smith';DROP TABLE orders;--
What type of attack was attempted?

Buffer overflow

Cross-site scripting

Cross-site request forgery

SQL injection

Answer:
D.  The single quotation mark in the input field is a telltale sign that this is a SQL injection attack. The quotation mark is used to escape outside the SQL code's input field, and the text following is used to directly manipulate the SQL command sent from the web application to the database.

Hannah's organization is implementing a new approach to user authentication that relies upon SAML. She would like to protect against eavesdropping on this traffic and also ensure that SAML traffic is not forged by an attacker. What should she do to protect against both types of attack?

Use SAML's secure mode to provide secure authentication.

Implement TLS using a strong cipher suite, which will protect against both types of attacks.

Implement TLS using a strong cipher suite and use digital signatures.

Implement TLS using a strong cipher suite and message hashing.

Answer:
C.  TLS provides message confidentiality and integrity, which can prevent eavesdropping. When paired with digital signatures, which provide integrity and authentication, forged assertions can also be defeated. SAML does not have a security mode and relies on TLS and digital signatures to ensure security if needed. Message hashing without a signature would help prevent modification of the message but won't necessarily provide authentication.

What is the goal of the BCP process?

RTO < MTD

MTD < RTO

RPO < MTD

MTD < RPO

Answer:
A.  The goal of the business continuity planning process is to ensure that your recovery time objectives are all less than your maximum tolerable downtimes.

During which phase of the incident response process would administrators design new security controls intended to prevent a recurrence of the incident?

Reporting

Recovery

Remediation

Lessons learned

Answer:
C.  The remediation phase of incident handling focuses on conducting a root-cause analysis to identify the factors contributing to an incident and implementing new security controls, as needed.

Bethany received an email from one of her colleagues with an unusual attachment named smime.p7s. She does not recognize the attachment and is unsure what to do. What is the most likely scenario?

This is an encrypted email message.

This is a phishing attack.

This is embedded malware.

This is a spoofing attack.

For questions 112–114, please refer to the following scenario:

Kim is the database security administrator for Aircraft Systems, Inc. (ASI). ASI is a military contractor engaged in the design and analysis of aircraft avionics systems and regularly handles classified information on behalf of the government and other government contractors. Kim is concerned about ensuring the security of information stored in ASI databases.

Kim's database is a multilevel security database, and different ASI employees have different security clearances. The database contains information on the location of military aircraft containing ASI systems to allow ASI staff to monitor those systems.

Answer:
A.  The S/MIME secure email format uses the P7S format for encrypted email messages. If the recipient does not have a mail reader that supports S/MIME, the message will appear with an attachment named smime.p7s.

Kim learned that the military is planning a classified mission that involves some ASI aircraft. She is concerned that employees not cleared for the mission may learn of it by noticing the movement of many aircraft to the region. Individual employees are cleared to know about the movement of an individual aircraft, but they are not cleared to know about the overall mission. What type of attack is Kim concerned about?

Aggregation

SQL injection

Inference

Multilevel security

Answer:
A.  Aggregation is a security issue that arises when a collection of facts has a higher classification than the classification of any of those facts standing alone. An inference problem occurs when an attacker can deduce information of greater sensitivity from a lower security level fact. SQL injection is a web application exploit. Multilevel security is a system control that allows the simultaneous processing of information at different classification levels.

What technique can Kim employ to prevent employees not cleared for the mission from learning the true location of the aircraft?

Input validation

Polyinstantiation

Parameterization

Server-side validation

Answer:
B.  Polyinstantiation allows the storage of multiple different pieces of information in a database at different classification levels to prevent attackers from conducting aggregation or inference attacks. Kim could store incorrect location information in the database at lower classification levels to prevent the aggregation attack in this scenario. Input validation, server-side validation, and parameterization are all techniques used to prevent web application attacks and are not effective against inference attacks.

Kim's database uniquely identifies aircrafts by using their tail number. Which one of the following terms would not necessarily accurately describe the tail number?

Database field

Foreign key

Primary key

Candidate key

Answer:
B.  The tail number is a database field because it is stored in the database. It is also a primary key because the question states that the database uniquely identifies aircraft using this field. Any primary key is, by definition, also a candidate key. There is no information provided that the tail number is a foreign key used to reference a different database table.

Kim would like to create a key that enforces referential integrity for the database. What type of key does she need to create?

Primary key

Foreign key

Candidate key

Master key

Answer:
B.  Foreign keys are used to create relationships between tables in a database. The database enforces referential integrity by ensuring that the foreign key used in a table has a corresponding record with that value as the primary key in the referenced table.

Doug is choosing a software development life-cycle model for use in a project he is leading to develop a new business application. He has clearly defined requirements and would like to choose an approach that places an early emphasis on developing comprehensive documentation. He does not have a need for the production of rapid prototypes or iterative improvement. Which model is most appropriate for this scenario?

Agile

Waterfall

Spiral

DevOps

Answer:
B.  The waterfall model uses an approach that develops software sequentially, spending quite a bit of time up front on the development and documentation of requirements and design. The spiral and Agile models focus on iterative development and are appropriate when requirements are not well understood or iterative development is preferred. DevOps is an approach to integrating development and operations activities and is not an SDLC model.

Which individual bears the ultimate responsibility for data protection tasks?

Data owner

Data custodian

User

Auditor

Answer:
A.  The data owner is a senior manager who bears ultimate responsibility for data protection tasks. The data owner typically delegates this responsibility to one or more data custodians.

Carla is conducting a web application security test and would like to automatically generate input that is used to test the application. Which of the following tools would be best suited for this purpose?

Static application testing tool

White-box testing tool

Brute-force testing tool

Fuzz testing tool

Answer:
D.  Fuzz testing tools are designed to provide invalid or unexpected input to applications, testing for vulnerabilities like format string vulnerabilities, buffer overflow issues, and other problems. A static analysis relies on examining code without running the application or code and thus would not fill forms as part of a web application. Brute-force tools attempt to bypass security by trying every possible combination for passwords or other values. A white box is a type of penetration test where the testers have full knowledge of the environment.

Warren's organization recently completed a massive phishing awareness campaign, and he would like to measure its effectiveness. Which of the following tools would best provide this measurement?

Survey

Simulation

Code review

Third-party assessment

Answer:
B.  Warren could use a survey or third-party assessment to evaluate the effectiveness of the campaign, but the best evidence would be provided by a phishing simulation where the organization measures user responses to simulated phishing attacks. Code reviews would not be useful in evaluating the effectiveness of antiphishing campaigns.

Which one of the following controls would be most effective in detecting zero-day attack attempts?

Signature-based intrusion detection

Anomaly-based intrusion detection

Strong patch management

Full-disk encryption

Answer:
B.  Anomaly-based intrusion detection systems may identify a zero-day vulnerability because it deviates from normal patterns of activity. Signature-based detection methods would not be effective because there are no signatures for zero-day vulnerabilities. Strong patch management would not be helpful because, by definition, zero-day vulnerabilities do not have patches available. Full-disk encryption would not detect an attack because it is not a detective control.

Rob believes that an individual he met on an online forum used unapproved resources to cheat on the CISSP exam. He has evidence to back up his claim. Which one of the following statements is most correct?

Rob may report this situation to ISC2 as a violation of the Code of Ethics.

Rob does not have standing to report this situation to ISC2 unless he is an employer of the individual in question.

Rob does not have standing to report this situation to ISC2 unless he holds a professional license or certification that includes a code of ethics.

Rob does not have standing to report this situation to ISC2 unless he is a member of ISC2 or holds an ISC2 certification.

Answer:
A.  Whether Rob has standing to report this situation to ISC2 depends upon the canon(s) violated by the activity. This behavior violates canon II, “Act honorably, honestly, justly, responsibly, and legally.” Any member of the public may file a claim under canons I or II. Only an employer or someone with a contracting relationship with the individual may file a complaint under canon III. Anyone who is certified or licensed as a professional and subscribes to a code of ethics as part of that licensure or certification is eligible to file a canon IV complaint.

Which one of the following components should be included in an organization's emergency response guidelines?

Secondary response procedures for incident responders

Long-term business continuity protocols

Activation procedures for the organization's cold sites

Contact information for ordering equipment

Answer:
A.  The emergency response guidelines should include the immediate steps an organization should follow in response to an emergency situation. These include immediate response procedures, a list of individuals who should be notified of the emergency, and secondary response procedures for incident responders. They do not include long-term actions such as activating business continuity protocols, ordering equipment, or activating disaster recovery sites.

When Jim enters his organization's data center, he has to use a smartcard and code to enter and is allowed through one set of doors. The first set of doors closes, and he must then use his card again to get through a second set, which locks behind him. What type of control is this, and what is it called?

A physical control; a one-way trapdoor

A logical control; a dual-swipe authorization

A directive control; a one-way access corridor

A preventive access control; an access control vestibule

Answer:
D.  An access control vestibule (or mantrap) uses two sets of doors, only one of which can open at a time. An access control vestibule is a type of preventive access control, although its implementation is a physical control.

Bill implemented RAID level 5 on a server that he operates using a total of three disks. How many disks may fail without the loss of data?

0

1

2

3

Answer:
B.  RAID level 5 is also known as disk striping with parity. It uses three or more disks, with the equivalent of one disk containing parity information used to restore data to another disk in the event of failure. When used with three disks, RAID 5 is able to withstand the loss of a single disk.

Match the following numbered system and organization controls (SOC) levels to their matching lettered SOC report descriptions:

SOC levels:

SOC 1, Type 1

SOC 1, Type 2

SOC 3

SOC report descriptions:

A general use report that reports on controls related to compliance and/or operations

A report that provides predefined, standard benchmarks for controls involving confidentiality, availability, integrity, and privacy of a system and the information it contains, generally for restricted use

A report that provides an assessment of the risk of material misstatement of financial statement assertions affected by the service organization's processing and that includes a description of the service auditor's tests of the controls and the results of the tests and their effectiveness

A report that provides the auditor's opinions of financial statements about controls at the service organization and that includes a report on the opinion on the presentation of the service organization's system as well as suitability of the controls

Answer:
The SOC levels match the report descriptions as follows:

SOC 1, Type 1: D. A report that provides the auditor's opinions of financial statements about controls at the service organization and that includes a report on the opinion on the presentation of the service organization's system as well as suitability of the controls

SOC 1, Type 2: C. A report that provides an assessment of the risk of material misstatement of financial statement assertions affected by the service organization's processing and that includes a description of the service auditor's tests of the controls and the results of the tests and their effectiveness

SOC 2: B. A report that provides predefined, standard benchmarks for controls involving confidentiality, availability, integrity, and privacy of a system and the information it contains, generally for restricted use

SOC 3: A. A general use report that reports on the effectiveness of controls related to compliance and/or operations
