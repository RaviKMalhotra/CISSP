# CISSP Practice Test # 1

Chapter 9: Practice Test 1
Lisa is attempting to prevent her network from being targeted by IP spoofing attacks as well as preventing her network from being the source of those attacks. Which of the following rules are best practices that Lisa should configure at her network border? (Select all that apply.)

Block packets with internal source addresses from entering the network.

Block packets with external source addresses from leaving the network.

Block packets with public IP addresses from entering the network.

Block packets with private IP addresses from exiting the network.

Answer:
A, B, D.  Packets with public IP addresses will routinely be allowed to enter the network, so you should not create a rule to block them. Packets with internal source addresses should never originate from outside the network, so they should be blocked from entering the network. Packets with external source addresses should never be found on the internal network, so they should be blocked from leaving the network. Finally, private IP addresses should never be used on the Internet, so packets containing private IP addresses should be blocked from leaving the network.

Ed has been tasked with identifying a service that will provide a low-latency, high-performance, and high-availability way to host content for his employer. What type of solution should he seek out to ensure that his employer's customers around the world can access their content quickly, easily, and reliably?

A hot site

A CDN

Redundant servers

A P2P CDN

Answer:
B.  A content distribution network (CDN) is designed to provide reliable, low-latency, geographically distributed content distribution. In this scenario, a CDN is an ideal solution. A P2P CDN like BitTorrent isn't a typical choice for a commercial entity, whereas redundant servers or a hot site can provide high availability but won't provide the remaining requirements.

Fran is building a forensic analysis workstation and is selecting a forensic disk controller to include in the setup. Which of the following are functions of a forensic disk controller? (Select all that apply.)

Preventing the modification of data on a storage device

Returning data requested from the device

Reporting errors sent by the device to the forensic host

Blocking read commands sent to the device

Answer:
A, B, C.  A forensic disk controller performs four functions. One of those, write blocking, intercepts write commands sent to the device and prevents them from modifying data on the device. The other three functions include returning data requested by a read operation, returning access-significant information from the device, and reporting errors from the device back to the forensic host. The controller should not prevent read commands from being sent to the device because those commands may return crucial information.

Mike is building a fault-tolerant server and wants to implement RAID 1. How many physical disks are required to build this solution?

1

2

3

5

Answer:
B.  RAID 1, disk mirroring, requires two physical disks that will contain copies of the same data.

Darren is troubleshooting an authentication issue for a Kerberized application used by his organization. He believes the issue is with the generation of session keys. What Kerberos service should he investigate first?

KDC

TGT

AS

TGS

Answer:
D.  The TGS, or ticket-granting service (which is usually on the same server as the KDC), receives a TGT from the client. It validates the TGT and the user's rights to access the service they are requesting to use. The TGS then issues a ticket and session keys to the client. The AS serves as the authentication server, which forwards the username to the KDC. It's worth noting that the client doesn't communicate with the KDC directly. Instead, it will communicate with the TGT and the AS, which means KDC isn't an appropriate answer here.

Evelyn believes that one of her organization's vendors has breached a contractual obligation to protect sensitive data and would like to conduct an investigation into the circumstances. Based upon the results of the investigation, it is likely that Evelyn's organization will sue the vendor for breach of contract. What term best describes the type of investigation that Evelyn is conducting?

Administrative investigation

Criminal investigation

Civil investigation

Regulatory investigation

Answer:
C.  This is an example of a civil investigation because it relates to a contract dispute and will likely wind up being litigated in civil court. Administrative investigations are for internal purposes and are not applicable when a third party is being investigated. Criminal and regulatory investigations may only be initiated by those with regulatory authority, typically government agencies.

Ivan is installing a motion detector to protect a sensitive work area that uses high-frequency microwave signal transmissions to identify potential intruders. What type of detector is he installing?

Infrared

Heat-based

Wave pattern

Capacitance

Answer:
C.  Wave pattern motion detectors transmit ultrasonic or microwave signals into the monitored area, watching for changes in the returned signals bouncing off objects. Infrared heat-based detectors watch for unusual heat patterns. Capacitance detectors work based upon electromagnetic fields.

Susan sets up a firewall that keeps track of the status of the communication between two systems and allows a remote system to respond to a local system only after the local system starts communication. What type of firewall is Susan using?

A static packet filtering firewall

An application-level gateway firewall

A stateful packet inspection firewall

A circuit-level gateway firewall

For questions 9–11, please refer to the following scenario:

Ben owns a coffeehouse and wants to provide wireless Internet service for his customers. Ben's network is simple and uses a single consumer-grade wireless router and a cable modem connected via a commercial cable data contract.

Answer:
C.  Stateful packet inspection firewalls, also known as dynamic packet filtering firewalls, track the state of a conversation and can allow a response from a remote system based on an internal system being allowed to start the communication. Static packet filtering and circuit-level gateways only filter based on source and destination IP addresses and ports along with the protocol being used, whereas application-level gateway firewalls proxy traffic for specific applications.

How can Ben provide access control for his customers without having to provision user IDs before they connect while also gathering useful contact information for his business purposes?

WPA2-PSK.

A captive portal.

Require customers to use a publicly posted password like “BensCoffee.”

WPA3 SAE.

Answer:
B.  A captive portal can require those who want to connect to and use Wi-Fi to provide an email address to connect. This allows Ben to provide easy-to-use wireless while meeting his business purposes. WPA2-PSK is the preshared key mode of WPA and won't provide information about users who are given a key. WPA3's SAE mode would be preferable to WPA2-PSK, but it still does not allow for the data gathering Ben desires. Sharing a password doesn't allow for data gathering either.

Ben intends to run an open (unencrypted) wireless network for his customers. How should he connect his wireless business devices?

Run WPA3 on the same SSID.

Set up a separate SSID using WPA3.

Run the open network in Enterprise mode.

Set up a separate wireless network using WEP.

Answer:
B.  Many modern wireless routers can provide multiple SSIDs. Ben can create a private, secure network for his business operations, but he will need to make sure that the customer and business networks are firewalled or otherwise logically separated from each other. Running WPA3 on the same SSID isn't possible without creating another wireless network and would cause confusion for customers (SSIDs aren't required to be unique). Running a network in Enterprise mode isn't used for open networks, and WEP is outdated and incredibly vulnerable.

After implementing the solution from the first question, Ben receives a complaint about users in his cafe hijacking other customers' web traffic, including using their usernames and passwords. How is this possible?

The password is shared by all users, making traffic vulnerable.

A malicious user has installed a Trojan on the router.

A user has ARP spoofed the router, making all traffic broadcast to all users.

Open networks are unencrypted, making traffic easily sniffable.

Answer:
D.  Unencrypted open networks broadcast traffic in the clear. This means that unencrypted sessions to websites can be easily captured with a packet sniffer. Some tools like FireSheep have been specifically designed to capture sessions from popular websites. Fortunately, many websites now use TLS by default, but other sites still send user session information in the clear. Shared passwords are not the cause of the vulnerability, ARP spoofing isn't an issue with wireless networks, and a Trojan is designed to look like safe software, not to compromise a router.

Kevin is reviewing and updating the security documentation used by his organization. He would like to document some best practices for securing IoT devices that his team has developed over the past year. The practices are generalized in nature and do not cover specific devices. What type of document would be best for this purpose?

Policy

Standard

Guideline

Procedure

Answer:
C.  It is possible that Kevin could use any one of these documents. We should zero in on the portion of the question where it indicates that these are best practices. This implies that the advice is not mandatory and, therefore, would not go into a policy or standard. The fact that the advice is general in nature means that it is likely not well-suited to the step-by-step nature of a procedure. A guideline would be the perfect place to document these best practices.

Tom is tuning his security monitoring tools in an attempt to reduce the number of alerts received by administrators without missing important security events. He decides to configure the system to only report failed login attempts if there are five failed attempts to access the same account within a one-hour period of time. What term best describes the technique that Tom is using?

Thresholding

Sampling

Account lockout

Clipping

Answer:
D.  Clipping is an analysis technique that reports alerts only after they exceed a set threshold. It is a specific form of sampling, which is a more general term that describes any attempt to excerpt records for review. Thresholding is not a commonly used term. Administrators may choose to configure automatic or manual account lockout after failed login attempts, but that is not described in the scenario.

Sally has been tasked with deploying an authentication, authorization, and accounting server for wireless network services in her organization and needs to avoid using proprietary technology. What technology should she select?

OAuth

RADIUS

XTACACS

OpenID Connect

Answer:
B.  RADIUS is a common AAA technology used to provide services for dial-up, wireless networks, network devices, and a range of other systems. OAuth is an authorization protocol used to allow applications to act on a user's behalf without sharing the password and is used for many web applications. OpenID Connect is an authentication layer on top of OAuth that allows clients to verify the identity of an end user. XTACACS, an earlier protocol for network authentication, has largely been superseded by more secure and robust protocols like RADIUS, and its proprietary nature does not fit Sally's criteria.

An accounting clerk for Christopher's Cheesecakes does not have access to the salary information for individual employees but wanted to know the salary of a new hire. He pulled total payroll expenses for the pay period before the new person was hired and then pulled the same expenses for the following pay period. He computed the difference between those two amounts to determine the individual's salary. What type of attack occurred?

Salami slicing

Data diddling

Inference

Social engineering

Answer:
C.  In an inference attack, the attacker uses several pieces of generic nonsensitive information to determine a specific sensitive value. In a salami slicing attack, the attacker siphons off minute quantities of money many times to accumulate a large amount of funds. In a data diddling attack, the attacker alters the contents of a database. Social engineering attacks exploit human psychology to achieve their goals.

Alice would like to have read permissions on an object and knows that Bob already has those rights and would like to give them to herself. Which one of the rules in the Take-Grant protection model would allow her to complete this operation if the relationship exists between Alice and Bob?

Take rule

Grant rule

Create rule

Remote rule

Answer:
A.  The Take rule in the Take-Grant protection model allows a subject to take rights from another object if the subject has the take right over that object. In this scenario, if Alice has the take right over Bob and Bob has read permissions on an object, Alice can use the Take rule to grant herself the read permissions that Bob possesses. The Grant rule is for granting rights to other subjects, not for taking them for oneself. The Create rule is used to create new objects or rights, not to transfer existing ones. There is no Remote rule in the Take-Grant protection model.

During a log review, Danielle discovers a series of logs that show login failures:

Jan 31 11:39:12 ip-10-0-0-2 sshd[29092]: Invalid user admin from remotehost passwd=aaaaaaaa
Jan 31 11:39:20 ip-10-0-0-2 sshd[29098]: Invalid user admin from remotehost passwd=aaaaaaab
Jan 31 11:39:23 ip-10-0-0-2 sshd[29100]: Invalid user admin from remotehost passwd=aaaaaaac
Jan 31 11:39:31 ip-10-0-0-2 sshd[29106]: Invalid user admin from remotehost passwd=aaaaaaad
Jan 31 20:40:53 ip-10-0-0-2 sshd[30520]: Invalid user admin from remotehost passwd=aaaaaaae
What type of attack has Danielle discovered?

A pass-the-hash attack

A brute-force attack

A man-in-the-middle attack

A dictionary attack

Answer:
B.  Brute-force attacks try every possible password. In this attack, the password is changing by one letter at each attempt, which indicates that it is a brute-force attack. A dictionary attack would use dictionary words for the attack, whereas a man-in-the-middle or pass-the-hash attack would most likely not be visible in an authentication log except as a successful login.

Ben is designing a database-driven application and would like to ensure that two executing transactions do not affect each other by storing interim results in the database. What property is he seeking to enforce?

Atomicity

Isolation

Consistency

Durability

Answer:
B.  Isolation requires that transactions operate separately from each other. Atomicity ensures that if any part of a database transaction fails, the entire transaction must be rolled back as if it never occurred. Consistency ensures that all transactions are consistent with the logical rules of the database, such as having a primary key. Durability requires that once a transaction is committed to the database it must be preserved. Together, these properties make up the ACID model.

Kim is the system administrator for a small business network that is experiencing security problems. She is in the office in the evening working on the problem, and nobody else is there. As she is watching, she can see that systems on the other side of the office that were previously behaving normally are now exhibiting signs of an infection one after the other. What type of malware is Kim likely dealing with?

Virus

Worm

Trojan horse

Logic bomb

Answer:
B.  Worms have built-in propagation mechanisms that do not require user interaction, such as scanning for systems containing known vulnerabilities and then exploiting those vulnerabilities to gain access. Viruses and Trojan horses typically require user interaction to spread. Logic bombs do not spread from system to system but lie in wait until certain conditions are met, triggering the delivery of their payload.

Barb is reviewing the compliance obligations facing her organization and the types of liability that each one might incur. Which of the following laws and regulations may involve criminal penalties if violated? (Select all that apply.)

FERPA

HIPAA

SOX

PCI DSS

Answer:
B, C.  The Health Insurance Portability and Accountability Act (HIPAA) is a U.S. law governing the healthcare sector that does provide for criminal penalties. The Sarbanes–Oxley (SOX) Act governs publicly traded corporations and also provides for criminal penalties. The Family Educational Rights and Privacy Act (FERPA) is a U.S. law governing educational records, but it does not provide for criminal penalties. PCI DSS, the Payment Card Industry Data Security Standard, is an industry standard for payment card operations and handling. Because it is not a law, PCI DSS violations cannot incur criminal sanctions.

Quentin is analyzing network traffic that he collected with Wireshark on a TCP/IP network. He would like to identify all new connections that were set up during his traffic collection. If he is looking for the three packets that constitute the TCP three-way handshake used to establish a new connection, what flags should be set on the first three packets?

SYN, ACK, SYN/ACK

PSH, RST, ACK

SYN, SYN/ACK, ACK

SYN, RST, FIN

Answer:
C.  The TCP three-way handshake consists of an initial contact via a SYN, or synchronize flagged packet, which receives a response with a SYN/ACK, or synchronize and acknowledge flagged packet, which is acknowledged by the original sender with an ACK, or acknowledge packet. RST is used in TCP to reset a connection, PSH is used to send data immediately, and FIN is used to end a connection.

Daniel is selecting a mobile device management (MDM) solution for his organization and is writing the RFP. He is trying to decide what features he should include as requirements after aligning his organization's security needs with an MDM platform's capabilities. Which of the following are typical capabilities of MDM solutions? (Select all that apply.)

Remotely wiping the contents of a mobile device

Assuming control of a nonregistered BYOD mobile device

Enforcing the use of device encryption

Managing device backups

Answer:
A, C, D.  MDM products do not have the capability of assuming control of a device not currently managed by the organization. This would be equivalent to hacking into a device owned by someone else and might constitute a crime. They do normally provide the ability to manage device backups, enforce the use of encryption, and remotely wipe the contents of mobile devices.

Jim is implementing an IDaaS solution for his organization. What type of technology is he putting in place?

Identity as a service

Employee ID as a service

Intrusion detection as a service

OAuth

Answer:
A.  Identity as a service (IDaaS) provides an identity platform as a third-party service. This can provide benefits, including integration with cloud services and removing overhead for maintenance of traditional on-premises identity systems but can also create risk due to third-party control of identity services and reliance on an off-site identity infrastructure.

Gina recently took the CISSP certification exam and then wrote a blog post that included the text of many of the exam questions that she experienced. What aspect of the ISC2 Code of Ethics is most directly violated in this situation?

Advance and protect the profession.

Act honorably, honestly, justly, responsibly, and legally.

Protect society, the common good, necessary public trust and confidence, and the infrastructure.

Provide diligent and competent service to principals.

Answer:
A.  Gina's actions harm the CISSP certification and information security community by undermining the integrity of the examination process. While Gina also is acting dishonestly, the harm to the profession is more of a direct violation of the ISC2 Code of Ethics.

Gordon is conducting a risk assessment for his organization and determined the amount of damage that flooding is expected to cause to his facilities each year. What metric has Gordon identified?

ALE

ARO

SLE

EF

Answer:
A.  The annualized loss expectancy (ALE) is the amount of damage that the organization expects to occur each year as the result of a given risk. ALE is calculated by multiplying the single loss expectancy (SLE), which is the expected financial loss from a single flooding event, by the annual rate of occurrence (ARO), which is the expected frequency of flooding events per year. The ALE helps organizations to understand the potential impact of risks and to make informed decisions about risk mitigation strategies and investments in protective measures. The exposure factor (EF) is the percentage of the asset expected to be damaged during an incident.

Greg would like to implement application control technology in his organization. He would like to limit users to installing only approved software on their systems. What type of application control would be appropriate in this situation?

Blacklisting

Graylisting

Whitelisting

Bluelisting

Answer:
C.  The whitelisting approach to application control allows users to install only those software packages specifically approved by administrators. This would be an appropriate approach in a scenario where application installation needs to be tightly controlled. Blacklisting, which blocks known malicious or unauthorized applications, would not be as effective in this scenario because it allows all software to run unless it appears on the blacklist. Graylisting and bluelisting are made-up terms.

Frank is the security administrator for a web server that provides news and information to people located around the world. His server received an unusually high volume of traffic that it could not handle and was forced to reject requests. Frank traced the source of the traffic back to a botnet. What type of attack took place?

Denial-of-service

Reconnaissance

Compromise

Malicious insider

Answer:
A.  This is a clear example of a denial-of-service attack—denying legitimate users authorized access to the system through the use of overwhelming traffic. It goes beyond a reconnaissance attack because the attacker is affecting the system, but it is not a compromise because the attacker did not attempt to gain access to the system. There is no reason to believe that a malicious insider was involved.

In the database table shown here, which column would be the best candidate for a primary key?

Larger View
A database table. The column titles are company I D, company name, address, city, state, zip code, telephone, and sales rep. It includes three company names listed below.
Company ID

Company Name

ZIP Code

Sales Rep

Answer:
A.  The Company ID column is likely unique for each row in the table, making it the best choice for a primary key. There may be multiple companies that share the same name or ZIP code. Similarly, a single sales representative likely serves more than one company, making those fields unsuitable for use as a unique identifier.

Gwen is a cybersecurity professional for a financial services firm that maintains records of their customers. These records include personal information about each customer, including the customer's name, Social Security number, date and place of birth, and mother's maiden name. What category best describes these records?

PHI

Proprietary data

PII

EDI

Answer:
C.  Personally identifiable information (PII) includes data that can be used to distinguish or trace that person's identity and also includes their educational, financial, and employment information. PHI is personal health information, EDI is electronic data interchange, and proprietary data is used to maintain an organization's competitive advantage.

Bob is configuring egress filtering on his network, examining traffic destined for the Internet. His organization uses the public address range 12.8.195.0/24. Packets with which one of the following destination addresses should Bob permit to leave the network?

12.8.195.15

10.8.15.9

192.168.109.55

129.53.44.124

Answer:
D.  129.53.44.124 is a valid public IP address and a legitimate destination for traffic leaving Bob's network. 12.8.195.15 is a public address on Bob's network and should not be a destination address on a packet leaving the network. 10.8.15.9 and 192.168.109.55 are both private IP addresses that should not be routed to the Internet.

Brian is considering increasing the length of the cryptographic keys used by his organization. If he adds 8 bits to the encryption key, how many more possible keys will be added to the keyspace for the algorithm?

The size of the keyspace will double.

The size of the keyspace will increase by a factor of 8.

The size of the keyspace will increase by a factor of 64.

The size of the keyspace will increase by a factor of 256.

Answer:
D.  Binary keyspaces contain a number of keys equal to 2 raised to the power of the number of bits. Two to the eighth power is 256, so the keyspace will increase by a factor of 256.

Which of the following data assets may be safely and effectively disposed of using shredding? (Select all that apply.)

Paper records

Credit cards

Removable media

SSD hard drives

Answer:
A, B, C, D.  Traditional office shredding machines may be used for the disposal of paper records and, depending upon their grade, may also be able to shred credit cards. Industrial shredders are capable of destroying larger pieces of equipment, including removable media and both traditional and SSD hard drives.

GAD Systems is concerned about the risk of hackers stealing sensitive information stored on a file server. They choose to pursue a risk mitigation strategy. Which one of the following actions would support that strategy?

Encrypting the files

Deleting the files

Purchasing cyber-liability insurance

Taking no action

Answer:
A.  Encrypting the files reduces the probability that the data will be successfully stolen, so it is an example of risk mitigation. Deleting the files would be risk avoidance. Purchasing insurance would be risk transference. Taking no action would be risk acceptance.

Viola is conducting a user account audit to determine whether accounts have the appropriate level of permissions and that all permissions were approved through a formal process. The organization has approximately 50,000 user accounts and an annual employee turnover rate of 24%. Which one of the following sampling approaches would be the most effective use of her time when choosing records for manual review?

Select all records that have been modified during the past month.

Ask access administrators to identify the accounts most likely to have issues and audit those.

Select a random sample of records, either from the entire population or from the population of records that have changed during the audit period.

Sampling is not effective in this situation, and all accounts should be audited.

Answer:
C.  Sampling should be done randomly to avoid human bias. Sampling is an effective process if it is done on a truly random sample of sufficient size to provide effective coverage of the userbase. It is infeasible for a single person to review every single record. In an organization of 50,000 users with a 24% annual turnover, it is likely that at least 1,000 of those records have changed in the last month. This is still too many records to review. Asking account administrators to select the records to review is a conflict of interest, as they are the group being audited.

Lila is reviewing her organization's adverse termination process. In that process, when would be the most appropriate time to revoke a user's access privileges to digital systems?

At the time the user is informed of the termination

At the end of the last day of employment

At the time the decision is made

Several days after the last day of employment

Answer:
A.  In the case of an involuntary termination under adverse circumstances, the user is being fired and may have a negative and potentially hostile reaction. For this reason, it is important to terminate access immediately upon the user being informed of the termination. Terminating access prior to notification may tip the user off to the termination in advance. Leaving access privileges available after termination poses a risk of malicious insider activity.

William is reviewing log files that were stored on a system with a suspected compromise. He finds the log file shown here. What type of log file is this?

Larger View
A screenshot of a sample log file.
Firewall log

Change log

Application log

System log

Answer:
C.  The file clearly shows HTTP requests, as evidenced by the many GET commands. Therefore, this is an example of an application log from an HTTP server.

Roger is reviewing a list of security vulnerabilities in his organization and rating them based upon their severity. Which one of the following models would be most useful to his work?

CVSS

STRIDE

PASTA

ATT&CK

Answer:
A.  The Common Vulnerability Scoring System (CVSS) is a standardized approach to rating the severity of vulnerabilities and would be the most helpful tool for Roger's work. The STRIDE and ATT&CK models are used to classify the nature, not the severity, of threats. The PASTA model is designed to help with countermeasure selection.

An attacker recently called an organization's help desk and persuaded them to reset a password for another user's account. What term best describes this attack?

A human Trojan

Social engineering

Phishing

Whaling

Answer:
B.  Social engineering exploits humans to allow attacks to succeed. Since help-desk employees are specifically tasked with being helpful, they may be targeted by attackers posing as legitimate employees. Trojans are a type of malware, whereas phishing is a targeted attack via electronic communication methods intended to capture passwords or other sensitive data. Whaling is a type of phishing aimed at high-profile or important targets.

Greg is evaluating a new vendor that will be supplying networking gear to his organization. Because of the nature of his organization's work, Greg is concerned that an attacker might attempt a supply chain exploit. Assuming that both Greg's organization and the vendor operate under reasonable security procedures, which one of the following activities likely poses the greatest supply chain risk to the equipment?

Tampering by an unauthorized third party at the vendor's site

Interception of devices in transit

Misconfiguration by an administrator after installation

Tampering by an unauthorized third party at Greg's site

Answer:
B.  If the vendor operates with reasonable security procedures, it is unlikely that the devices will be tampered with at the vendor's site. Similarly, if Greg's organization has reasonable security procedures, tampering at his site is also unlikely. Misconfiguration by an administrator is always possible, but this is a post-installation risk and not a supply chain risk. It is possible that devices will be intercepted and tampered with while in transit from the vendor to Greg's organization.

Kevin is operating in a single-level security environment and is seeking to classify information systems according to the type of information that they process. What procedure would be the best way for him to assign asset classifications?

Assign systems the classification of information that they most commonly process.

Assign systems the classification of the highest level of information that they are expected to process regularly.

Assign systems the classification of the highest level of information that they are ever expected to process.

Assign all systems the same classification level.

For questions 41–43, please refer to the following scenario:

The organization that Ben works for has a traditional on-site Active Directory environment that uses a manual provisioning process for each addition to their 350-employee company. As the company adopts new technologies, they are increasingly using software-as-a-service applications to replace their internally developed software stack.

Ben has been tasked with designing an identity management implementation that will allow his company to use cloud services while supporting their existing systems. Using the logical diagram shown here, answer the following questions about the identity recommendations Ben should make.

Larger View
A logical diagram. It begins with internet, followed by corporate secure border, internal network, employee workstation, active directory, C R M, database, and others.
Answer:
C.  In a single-level security environment, systems should be assigned the classification level of the highest classification of information they are ever expected to process. Systems may not process information that is above their classification level without reclassifying the system upward.

If availability of authentication services is the organization's biggest priority, what type of identity platform should Ben recommend?

On-site

Cloud-based

Hybrid

Outsourced

Answer:
C.  A hybrid authentication service can provide authentication services both in the cloud and on-premises, ensuring that service outages due to interrupted links are minimized. An on-site service would continue to work during an Internet outage but would not allow the e-commerce website to authenticate. A cloud service would leave the corporate location offline. Outsourcing authentication does not indicate whether the solution is on- or off-premises and thus isn't a useful answer.

If Ben needs to share identity information with the business partner shown, what should he investigate?

Single sign-on

Multifactor authentication

Federation

IDaaS

Answer:
C.  Federation links identity information between multiple organizations. Federating with a business partner can allow identification and authorization to occur between them, making integration much easier. Single sign-on would reduce the number of times a user has to log in but will not facilitate the sharing of identity information. Multifactor authentication can help secure authentication but again doesn't help integrate with a third party. Finally, an identity as a service provider might provide federation but doesn't guarantee it.

What technology is likely to be involved when Ben's organization needs to provide authentication and authorization assertions to their cloud e-commerce application?

Active Directory

SAML

RADIUS

SPML

Answer:
B.  Security Assertion Markup Language (SAML) is frequently used to integrate cloud services and provides the ability to make authentication and authorization assertions. Active Directory integrations are possible but are less common for cloud service providers, and RADIUS is not typically used for integrations like this. Service Provisioning Markup Language (SPML) is used to provision users, resources, and services, not for authentication and authorization.

Dave is responsible for password security in his organization and would like to strengthen the security of password files. He would like to defend his organization against the use of rainbow tables. Which one of the following techniques is specifically designed to frustrate the use of rainbow tables?

Password expiration policies

Salting

User education

Password complexity policies

Answer:
B.  Rainbow tables use precomputed password hashes to conduct cracking attacks against password files. They may be frustrated by the use of salting, which adds a specified value to the password prior to hashing, making it much more difficult to perform precomputation. Password expiration policies, password complexity policies, and user education may all contribute to password security, but they are not direct defenses against the use of rainbow tables.

Helen recently built a new system as part of her organization's deception campaign. The system is configured in a manner that makes it vulnerable to attack and that conveys that it might contain highly sensitive information. What term best describes this system?

Honeynet

Darknet

Honeypot

Pseudoflaw

Answer:
C.  A honeypot is a decoy computer system used to bait intruders into attacking. A honeynet is a network of multiple honeypots that creates a more sophisticated environment for intruders to explore. A pseudoflaw is a false vulnerability in a system that may attract an attacker. A darknet is a segment of unused network address space that should have no network activity and, therefore, may be easily used to monitor for illicit activity.

Nandi is evaluating a set of candidate systems to replace a biometric authentication mechanism in her organization. What metric would be the best way to compare the effectiveness of the different systems?

FAR

FRR

CER

FDR

Answer:
C.  The false acceptance rate (FAR) is the rate at which the system inadvertently admits an unauthorized user, while the false rejection rate (FRR) is the rate at which the system inadvertently rejects an authorized user. Both the FAR and FRR may be modified by adjusting the sensitivity of the system. The crossover error rate (CER) is the point where both the false acceptance rate and the false rejection rate cross. The CER is less subject to manipulation and is, therefore, the best metric to use for evaluating systems. The FDR is not a metric used to evaluate authentication systems.

Sean suspects that an individual in his company is smuggling out secret information despite his company's careful use of data loss prevention systems. He discovers that the suspect is posting photos, including the one shown here, to public Internet message boards. What type of technique may the individuals be using to hide messages inside this image?

Larger View
A photograph of two ancient coins.
Source: National Museum of American History / Wikimedia Commons / Public domain.

Watermarking

VPN

Steganography

Covert timing channel

Answer:
C.  Steganography is the art of using cryptographic techniques to embed secret messages within other content. Steganographic algorithms work by making invisible alterations to files, such as modifying the least significant bits of the many bits that make up image files. VPNs may be used to obscure secret communications, but they provide protection in transit and can't be used to embed information in an image.

Watermarking does embed information in an image but with the intent of protecting intellectual property. A still image would not be used for a covert timing channel because it is a fixed file.

Roger is concerned that a third-party firm hired to develop code for an internal application will embed a backdoor in the code. The developer retains rights to the intellectual property and will only deliver the software in its final form. Which one of the following languages would be least susceptible to this type of attack because it would provide Roger with code that is human-readable in its final form?

JavaScript

C

C++

Java

Answer:
A.  JavaScript is an interpreted language so the code is not compiled prior to execution, allowing Roger to inspect the contents of the code. C, C++, and Java are all compiled languages—a compiler produces an executable file that is not human-readable.

Jesse is looking at the /etc/passwd file on a system configured to use shadowed passwords. What should she expect to see in the password field of this file?

Plaintext passwords

Encrypted passwords

Hashed passwords

x

Answer:
D.  When a system is configured to use shadowed passwords, the /etc/passwd file contains only the character x in the place of a password. It would not contain any passwords, in either plaintext, encrypted, or hashed form.

Rob recently received a notice from a vendor that the EOL date is approaching for a firewall platform that is used in his organization. What action should Rob take?

Prepare to discontinue use of the platform as soon as possible.

Immediately discontinue use of the device.

Prepare to discontinue use of the device as part of the organization's normal planning cycle.

No action is necessary.

Answer:
C.  The end-of-life (EOL) date for a product is normally the date that the vendor will stop selling a product. It is reasonable to continue using the product as long as support remains available. Rob should begin making plans to discontinue use of the product, pending the announcement of an end-of-support (EOS) date.

What principle states that an individual should make every effort to complete their responsibilities in an accurate and timely manner?

Least privilege

Separation of duties

Due care

Due diligence

Answer:
D.  The due care principle states that an individual should react in a situation using the same level of care that would be expected from any reasonable person. It is a very broad standard. The due diligence principle is a more specific component of due care that states that an individual assigned a responsibility should exercise due care to complete it accurately and in a timely manner. Least privilege says that an individual should have the minimum set of permissions necessary to carry out their work. Separation of duties says that no single person should have the right to perform two distinct tasks, which, when combined, constitute a highly privileged action.

Tony is developing a data classification system for his organization. What factor should he use as the primary driver when determining the classification level of each category of information?

Sensitivity

Source

Likelihood of theft

Likelihood of data loss

Answer:
A.  Information should be classified based upon its sensitivity. This may be due to the value of the information to the organization, the damage caused if lost or compromised, or other factors. The source of the information is one possible contributing factor to the sensitivity level. The likelihood of loss or theft is a component of risk but does not contribute to the classification level.

Perry is establishing information handling requirements for his organization. He discovers that the organization often needs to send sensitive information over the Internet to a supplier and is concerned about it being intercepted. What handling requirement would best protect against this risk?

Require the use of transport encryption.

Require proper classification and labeling.

Require the use of data loss prevention technology.

Require the use of storage encryption.

Answer:
A.  All of these controls are good practices for protecting sensitive information. However, Perry is most concerned about the risk of interception while in transit over the Internet. Transport encryption would, therefore, be the most appropriate control, as anyone intercepting the information would be unable to read its contents. Storage encryption would protect against the theft of information at rest, rather than in transit over a network. Classification and labeling would not protect against interception. Data loss prevention technology may block the transfer entirely and would not meet the business requirement if it blocked the transmission and would not meet the security requirement if it did not detect the data transfer.

John is developing a tangible asset inventory for his organization. Which of the following items would most likely be included in this inventory? (Select all that apply.)

Intellectual property

Server hardware

Files stored on servers

Mobile devices

Answer:
B, D.  Tangible asset inventories include physical items owned by the organization. This would include server hardware and mobile devices. Intellectual property and files stored on a server are not tangible property and would instead be included in an intangible asset inventory.

Maria is analyzing a security incident where she believes that an attacker gained access to a fiber-optic cable and installed a tap on that cable. What layer of the OSI model did this attack occur at?

Transport

Network

Data Link

Physical

Answer:
D.  The Physical layer deals with the electrical impulses or optical pulses that are sent as bits to convey data. This is the layer where cable tapping would occur. Attacks at the Data Link, Network, or Transport layers would involve higher levels of activity in the OSI model, such as compromising a device and using a protocol analyzer to sniff network traffic.

Bert is considering the use of an infrastructure-as-a-service (IaaS) cloud computing partner to provide virtual servers. Which one of the following would be a vendor responsibility in this scenario?

Maintaining the hypervisor

Managing operating system security settings

Maintaining the host firewall

Configuring server access control

Answer:
A.  In an IaaS server environment, the customer retains responsibility for most server security operations under the shared responsibility model. This includes managing OS security settings, maintaining host firewalls, and configuring server access control. The vendor would be responsible for all security mechanisms at the hypervisor layer and below.

When Ben records data and then replays it against his test website to verify how it performs based on a real production workload, what type of performance monitoring is he undertaking?

Passive

Proactive

Reactive

Replay

Answer:
B.  Proactive monitoring, aka synthetic monitoring, uses recorded or generated traffic to test systems and software. Passive monitoring uses a network span, tap, or other device to capture traffic to be analyzed. Reactive and replay are not industry terms for types of monitoring.

Kailey is reviewing a set of old records maintained by her organization and wants to dispose of them securely. She is unsure how long the organization should keep the records because they involve tax data. How can Kailey determine whether the records may be disposed?

Consult the organization's records retention policy.

Consult IRS requirements.

Retain the records for at least seven years.

Retain the records permanently.

Answer:
A.  Kailey should consult her organization's record retentions policy to determine the appropriate length of time to preserve the records. The organization may be subject to tax requirements in this regard, and many accountants recommend preserving records for at least seven years, but the organization's own requirements may be stricter than these requirements.

Alan is considering the use of new identification cards in his organization that will be used for physical access control. He comes across a sample card and is unsure of the technology. He breaks it open and sees the following internal construction. What type of card is this?

Larger View
A photograph of an organization's damaged identity card.
Source: Arkrishna / Wikimedia Commons / Public domain.

Smart card

Proximity card

Magnetic stripe

Phase-two card

Answer:
B.  The use of an electromagnetic coil inside the card indicates that this is a proximity card.

Mark is planning a disaster recovery test for his organization. He would like to perform a live test of the disaster recovery facility but does not want to disrupt operations at the primary facility. What type of test should Mark choose?

Full interruption test

Read-through

Parallel test

Tabletop exercise

Answer:
C.  During a parallel test, the team actually activates the disaster recovery site for testing, but the primary site remains operational. During a full interruption test, the team takes down the primary site and confirms that the disaster recovery site is capable of handling regular operations. The full interruption test is the most thorough test but also the most disruptive. The read-through is the least disruptive type of disaster recovery test. During a read-through, team members each review the contents of their disaster recovery checklists on their own and suggest any necessary changes. During a tabletop exercise, team members come together and walk through a specific scenario without making any changes to information systems.

Which one of the following is not a principle of the Agile approach to software development?

The best architecture, requirements, and designs emerge from self-organizing teams.

Deliver working software infrequently, with an emphasis on creating accurate code over longer timelines.

Welcome changing requirements, even late in the development process.

Simplicity is essential.

Answer:
B.  The Agile approach to software development embraces 12 core principles, found in the Agile Manifesto. One of these principles is that the best architecture, requirements, and designs emerge from self-organizing teams. Another is that teams should welcome changing requirements at any step in the process. A third is that simplicity is essential. The Agile approach emphasizes delivering software frequently, not infrequently.

During a security audit, Susan discovers that the organization is using hand geometry scanners as the access control mechanism for their secure data center. What recommendation should Susan make about the use of hand geometry scanners?

They have a high FRR and should be replaced.

A second factor should be added because they are not a good way to reliably distinguish individuals.

The hand geometry scanners provide appropriate security for the data center and should be considered for other high-security areas.

They may create accessibility concerns, and an alternate biometric system should be considered.

Answer:
B.  Hand geometry scanners assess the physical dimensions of an individual's hand but do not verify other unique factors about the individual, or even verify if they are alive. This means that hand geometry scanners should not be implemented as the sole authentication factor for secure environments. Hand geometry scanners do not have an abnormally high FRR and do not stand out as a particular issue from an accessibility standpoint compared to other biometric systems.

Colleen is conducting a business impact assessment for her organization. What metric provides important information about the amount of time that the organization may be without a service before causing irreparable harm?

MTD

ALE

RPO

RTO

Answer:
A.  The maximum tolerable downtime (MTD) is the amount of time that a business may be without a service before irreparable harm occurs. This measure is sometimes also called maximum tolerable outage (MTO) or maximum allowable downtime (MAD). The Recovery Point Objective (RPO) and Recovery Time Objective (RTO) are related but distinct measures. The RPO focuses on data loss, indicating the maximum period in which data might be lost due to a disruption, and is used to establish the frequency of backups. The RTO, meanwhile, is the target time set for the recovery of IT and business activities after a disruption, aimed to be within the MTD but is not itself a measure of the direct impact on the business operation. The annual loss expectancy (ALE) is not directly related to service interruption but is a metric used in risk assessment to quantify potential annual financial loss from risks.

Bailey is concerned that users around her organization are using sensitive information in a variety of cloud services and would like to enforce security policies consistently across those services. What security control would be best suited for her needs?

DRM

IPS

CASB

DLP

Answer:
C.  Cloud access security brokers (CASBs) are designed to enforce security policies consistently across cloud services and would best meet Bailey's needs. Data loss prevention (DLP) and digital rights management (DRM) solutions may be able to detect, block, and control some use of information in the cloud, but they would not provide a way to consistently enforce security policies across cloud platforms. Intrusion prevention systems (IPS) are designed to detect and block malicious activity and would not be relevant in this scenario.

Matt is designing a set of information handling requirements for his organization and would like to draw upon common industry practices. Which of the following practices should Matt implement? (Select all that apply.)

Labeling both paper and electronic documents with their classification level

Automatically granting senior executives full access to all classified information

Automatically granting visitors access to information classified at the lowest level of sensitivity

Encrypting sensitive information in transit and at rest

Answer:
A, D.  Organizations should always label classified information in whatever form, paper or electronic, that it appears. This allows employees to apply proper handling procedures. It is also a common practice to encrypt sensitive information both at rest and in transit. Organizations should grant access to classified information on a need-to-know basis.

Automatically granting access to information, whether it is to a visitor or a senior executive, should not occur.

Jerry is investigating an attack where the attacker stole an authentication token from a user's web session and used it to impersonate the user on the site. What term best describes this attack?

Masquerading

Replay

Spoofing

Modification

Answer:
B.  Masquerading (or impersonation) attacks use stolen or falsified credentials to bypass authentication mechanisms. That term does describe this attack, but you should keep reading the answer choices even after finding a possible correct answer. In this case, replay attacks are a more specific type of masquerading attack that relies on captured authentication tokens, and this is, therefore, a better answer. Spoofing attacks rely on falsifying an identity like an IP address or hostname without credentials. Modification attacks occur when captured packets are modified and replayed to a system to attempt to perform an action.

Lisa wants to integrate with a cloud identity provider that uses OAuth 2.0, and she wants to select an appropriate authentication framework. Which of the following best suits her needs?

OpenID Connect

SAML

RADIUS

Kerberos

Answer:
A.  OpenID Connect is an authentication layer that works with OAuth 2.0 as its underlying authorization framework. It has been widely adopted by cloud service providers and is widely supported. SAML, RADIUS, and Kerberos are alternative authentication technologies but do not have the same level of seamless integration with OAuth 2.0.

Owen recently designed a security access control structure that prevents a single user from simultaneously holding the role required to create a new vendor and the role required to issue a check. What principle is Owen enforcing?

Two-person control

Least privilege

Separation of duties

Job rotation

Answer:
C.  This scenario describes separation of duties—not allowing the same person to hold two roles that, when combined, are sensitive. While two-person control is a similar concept, it does not apply in this case because the scenario does not say that either action requires the concurrence of two users. Least privilege says that an individual should have the minimum set of permissions necessary to carry out their work. Job rotation moves people through jobs on a periodic basis to deter fraud.

Denise is preparing for a trial relating to a contract dispute between her company and a software vendor. The vendor is claiming that Denise made a verbal agreement that amended their written contract. What rule of evidence should Denise raise in her defense?

Real evidence rule

Best evidence rule

Parol evidence rule

Testimonial evidence rule

Answer:
C.  The parol evidence rule states that when an agreement between two parties is put into written form, it is assumed to be the entire agreement unless amended in writing. The best evidence rule says that a copy of a document is not admissible if the original document is available. Real evidence and testimonial evidence are evidence types, not rules of evidence.

While Lauren is monitoring traffic on two ends of a network connection, she sees traffic that is inbound to a public IP address show up inside the production network. It is headed for an internal host with an RFC 1918 reserved destination address. What technology should she expect is in use at the network border?

NAT

VLANs

G/NAT

BGP

Answer:
A.  Network Address Translation (NAT) translates an internal address to an external address. VLANs are used to logically divide networks, BGP is a routing protocol, and G/NAT is a made-up term.

Which of the following statements about SSAE-18 are correct? (Select all that apply.)

It mandates a specific control set.

It is an attestation standard.

It is used for external audits.

It uses a framework, including SOC 1, SOC 2, and SOC 3 reports.

Answer:
B, C, D.  SSAE-18 does not assert specific controls. Instead, it reviews the use and application of controls in an audited organization. It is an attestation standard, used for external audits, and forms part of the underlying framework for SOC 1, 2, and 3 reports.

Elliott is using an asymmetric cryptosystem and would like to add a digital signature to a message. What key should he use to encrypt the message digest?

Elliott's private key

Elliott's public key

Recipient's private key

Recipient's public key

Answer:
A.  When creating a digital signature, the sender of a message always encrypts the message digest with their own private key. The recipient (or any third party) may then verify the digital signature by decrypting it with the sender's public key and then comparing that decrypted signature with a message digest that the recipient computes themselves.

Greg is building a disaster recovery plan for his organization and would like to determine the amount of time that it should take to restore a particular IT service after an outage. What variable is Greg calculating?

MTD

RTO

RPO

SLA

Answer:
B.  The recovery time objective (RTO) is the amount of time expected to return an IT service or component to operation after a failure. The maximum tolerable downtime (MTD) is the longest amount of time that an IT service or component may be unavailable without causing serious damage to the organization. The recovery point objective (RPO) identifies the maximum amount of data, measured in time, that may be lost during a recovery effort. Service-level agreements (SLAs) are written contracts that document service expectations.

What business process typically requires sign-off from a manager before modifications are made to a system?

SDN

Release management

Change management

Versioning

Answer:
C.  Change management typically requires sign-off from a manager or supervisor before changes are made. This helps to ensure proper awareness and communication. SDN stands for software-defined networking, release management is the process that new software releases go through to be accepted, and versioning is used to differentiate versions of software, code, or other objects.

Jen is selecting a fire suppression system for her organization's data center and would like to narrow down the list of potential vendors. Which one of the following suppression systems would be LEAST appropriate for use?

Dry pipe

Wet pipe

Pre-action

FM-200

Answer:
B.  Wet pipe suppression systems have water present in the pipes at all times, posing an unacceptable level of risk for a data center containing electronics that might be damaged if a pipe leaks. Dry pipe and pre-action systems only contain water when triggered in the event of a possible fire. FM-200 is a chemical suppressant commonly used in place of water in data centers.

The company Chris works for has notifications posted at each door reminding employees to be careful to not allow people to enter when they do. Which type of control is this?

Detective

Physical

Preventive

Directive

Answer:
D.  Notifications and procedures like the signs posted at the company Chris works for are examples of directive access controls. Detective controls are designed to operate after the fact. The doors and the locks on them are examples of physical controls. Preventive controls are designed to stop an event and could also include the locks that are present on the doors.

Seth is designing the physical security controls for a new facility being constructed by his organization. He would like to deter attacks to the extent possible. Which of the following controls serve as deterrents? (Select all that apply.)

Motion detectors

Guard dogs

Access control vestibules

Lighting

Answer:
B, D.  Deterrent controls seek to prevent an intruder from attempting an attack in the first place. Guard dogs have an intimidating presence that serves this purpose well. They do also serve to deny, detect, and delay intrusions depending upon their training. Lighting also deters attacks by making potential intrusions more visible, reducing the likelihood that an intruder will enter a well-lit area. Access control vestibules (also known as mantraps) are intended to deny intruders access, rather than deter attempts. Motion detectors are intended to detect intruders rather than deter them.

Thomas recently signed an agreement for a serverless computing environment where his organization's developers will be able to write functions in Python and deploy them on the cloud provider's servers for execution. The cloud provider will manage the servers. What term best describes this model?

SaaS

PaaS

IaaS

Containerization

Answer:
B.  This is an example of function-as-a-service (FaaS) computing. However, FaaS is not listed as an answer choice, so you must also know that FaaS is a subcategory of platform-as-a-service (PaaS) computing to answer this question correctly. This model does not necessarily take advantage of containerization. The cloud provider is managing the infrastructure and only making the platform available to customers, so it is not infrastructure as a service (IaaS). The customers are running their own code, so it is not software as a service (SaaS).

An attacker has intercepted a large amount of data that was all encrypted with the same algorithm and encryption key. With no further information, which of the following cryptanalytic attacks are possible? (Select all that apply.)

Known plaintext

Chosen ciphertext

Frequency analysis

Brute force

For questions 80–82, please refer to the following scenario:

Alex has been with the university he works at for more than 10 years. During that time, he has been a system administrator and a database administrator, and he has worked in the university's help desk. He is now a manager for the team that runs the university's web applications. Using the provisioning diagram shown here, answer the following questions.

Larger View
A sample provisioning diagram. It is labeled A to F. A denotes provisioning system, B for application server, C for database server, D for active directory enabled workstation, E for directory server, and F for incident management system.
Answer:
C, D.  The attacker may attempt to perform frequency analysis or a brute-force attack against the large volume of encrypted ciphertext. As the attacker does not have access to the plaintext information, a known plaintext attack is not possible. The attacker also does not have the ability to encrypt information, so they cannot use a chosen ciphertext attack.

If Alex hires a new employee and the employee's account is provisioned after HR manually inputs information into the provisioning system based on data Alex provides via a series of forms, what type of provisioning has occurred?

Discretionary account provisioning

Workflow-based account provisioning

Automated account provisioning

Self-service account provisioning

Answer:
B.  Provisioning that occurs through an established workflow, such as through an HR process, is workflow-based account provisioning. If Alex had set up accounts for his new hire on the systems he manages, he would have been using discretionary account provisioning. If the provisioning system allowed the new hire to sign up for an account on their own, they would have used self-service account provisioning, and if there was a central, software-driven process, rather than HR forms, it would have been automated account provisioning.

Alex has access to B, C, and D in the diagram. What concern should he raise to the university's identity management team?

The provisioning process did not give him the rights he needs.

He has excessive privileges.

Privilege creep may be taking place.

Logging is not properly enabled.

Answer:
C.  As Alex has changed roles, he retained access to systems that he no longer administers. The provisioning system has provided rights to workstations and the application servers he manages, but he should not have access to the databases he no longer administers. Privilege levels are not specified, so we can't determine if he has excessive privileges. Logging may or may not be enabled, but it isn't possible to tell from the diagram or problem.

When Alex changes roles, what should occur?

He should be de-provisioned, and a new account should be created.

He should have his new rights added to his existing account.

He should be provisioned for only the rights that match his role.

He should have his rights set to match those of the person he is replacing.

Answer:
C.  When a user's role changes, they should be provisioned based on their role and other access entitlements. De-provisioning and re-provisioning are time-consuming and can lead to problems with changed IDs and how existing credentials work. Simply adding new rights leads to privilege creep, and matching another user's rights can lead to excessive privileges due to privilege creep for that other user.

Robert is reviewing a system that has been assigned the EAL2 evaluation assurance level under the Common Criteria. What is the highest level of assurance that he may have about the system?

It has been functionally tested.

It has been structurally tested.

It has been formally verified, designed, and tested.

It has been semiformally designed and tested.

Answer:
B.  EAL2 assurance applies when the system has been structurally tested. It is the second-to-lowest level of assurance under the Common Criteria.

Adam is processing an access request for an end user. What two items should he verify before granting the access?

Separation and need to know

Clearance and endorsement

Clearance and need to know

Second factor and clearance

Answer:
C.  Before granting any user access to information, Adam should verify that the user has an appropriate security clearance as well as a business need to know for the information in question.

During what phase of the electronic discovery reference model does an organization ensure that potentially discoverable information is protected against alteration or deletion?

Identification

Preservation

Collection

Processing

Answer:
B.  During the preservation phase, the organization ensures that information related to the matter at hand is protected against intentional or unintentional alteration or deletion. The identification phase locates relevant information but does not preserve it. The collection phase occurs after preservation and gathers responsive information. The processing phase performs a rough cut of the collected information for relevance.

Dana is selecting a hash function for use in her organization and would like to balance a concern for a cryptographically strong hash with the speed and efficiency of the algorithm. Which one of the following hash functions would best meet her needs?

MD5

RIPEMD

SHA-2

SHA-3

Answer:
C.  The original version of RIPEMD and the MD5 hash algorithms have known vulnerabilities and should no longer be used. SHA-2 and SHA-3 are both considered secure today and provide the same level of security. SHA-3 is, however, less efficient than SHA-2, making SHA-2 the better choice for Dana's needs.

Harry would like to access a document owned by Sally stored on a file server. Applying the subject/object model to this scenario, who or what is the object of the resource request?

Harry

Sally

File server

Document

Answer:
D.  In the subject/object model, the object is the resource being requested by a subject. In this example, Harry would like access to the document, making the document the object of the request.

What is the process that occurs when the Session layer removes the header from data sent by the Transport layer in the OSI model?

Encapsulation

Packet unwrapping

De-encapsulation

Payloading

Answer:
C.  The process of removing a header (and possibly a footer) from the data received from a previous layer in the OSI model is known as de-encapsulation. Encapsulation occurs when the header or footer is added. Payloads are the data portion of a packet, but payloading is not a technical term. Similarly, packet unwrapping is a made-up term.

Rob is reviewing his organization's campus for physical security using the Crime Prevention Through Environmental Design (CPTED) framework. Which one of the following is NOT a strategy in this framework?

Natural intrusion detection

Natural access control

Natural surveillance

Natural territorial reinforcement

Answer:
A.  CPTED implements three strategies: natural access control, natural surveillance, and natural territorial reinforcement. Natural access control uses barricades and other physical elements to create a separation between secure and insecure spaces. Natural surveillance designs the environment to expose potential intruders to natural scrutiny by legitimate occupants. Natural territorial reinforcement uses fences, signs, and other elements to clearly define secure spaces. Natural intrusion detection is not an element of CPTED.

Shahla's organization handles personally identifiable information as part of its routine business. The organization currently operates only in the United States but is considering an expansion into Canada. What new law is most likely to affect the organization if they undertake this expansion?

PIPL

POPIA

PIPEDA

CCPA

Answer:
C.  If Shahla's organization expands into Canada and handles personally identifiable information as part of its routine business, the most likely new law to affect the organization would be the Personal Information Protection and Electronic Documents Act (PIPEDA). This Canadian federal privacy law governs the collection, use, and disclosure of personal information in the course of commercial business.

PIPL is China's Personal Information Protection Law, POPIA is South Africa's Protection of Personal Information Act, and the CCPA is the California Consumer Privacy Act. Each of these laws governs the handling of personal information within their respective jurisdictions, but would not be the primary concern for a U.S. organization considering expansion into Canada.

What type of risk assessment uses tools such as the one shown here?

Larger View
A graph of probability versus impact. It includes four quadrants including moderate risk, high risk, moderate risk, and low risk.
Quantitative

Loss expectancy

Financial

Qualitative

Answer:
D.  The use of a probability/impact matrix is the hallmark of a qualitative risk assessment. It uses subjective measures of probability and impact, such as “high,” “moderate,” and “low,” in place of quantitative measures.

MAC models use three types of environments. Which of the following is not a mandatory access control design?

Hierarchical

Bracketed

Compartmentalized

Hybrid

Answer:
B.  Mandatory access control systems can be hierarchical, where each domain is ordered and related to other domains above and below it; compartmentalized, where there is no relationship between each domain; or hybrid, where both hierarchy and compartments are used. There is no concept of bracketing in mandatory access control design.

Mandy is the team leader for a project team of six people (including herself). She would like to provide those people with the ability to communicate privately, such that any pair of people can exchange communications that are not subject to interception by anyone else (team member or nonteam member). The team is using an asymmetric encryption algorithm. How many keys are required to implement these requirements?

6

12

15

36

Answer:
B.  Asymmetric encryption algorithms require two keys per user, regardless of the number of participants. Therefore, this six-member team would require 12 keys. If this team were to use symmetric cryptography, they would require (n*(n-1))/2, or (6*(6-1))/2 = 15 keys.

Sally is wiring a gigabit Ethernet network. What cabling choices should she make to ensure she can use her network at the full 1000 Mbps she wants to provide to her users?

Cat 5 and Cat 6

Cat 5e and Cat 6

Cat 4e and Cat 5e

Cat 6 and Cat 7

Answer:
B.  Category 5e and Category 6 UTP cables are both rated to 1000Mbps. Cat 5 (not Cat 5e) is only rated to 100Mbps, whereas Cat 7 is rated to 10Gbps. There is no Cat 4e.

Ursula is seeking to expand the reach and scalability of her organization's website. She would like to position copies of her data around the world in locations close to website visitors to reduce loading time and the burden on her servers. What type of cloud service would best meet her needs?

IaaS

Containerization

CDN

SaaS

Answer:
C.  While Ursula may use a variety of different options to meet her needs, the best approach would be the use of a content delivery network (CDN). CDNs are specifically designed for this role, distributing content to many remote endpoints where it may be quickly loaded by local users.

Robert is the network administrator for a small business and recently installed a new firewall. After seeing signs of unusually heavy network traffic, he checked his intrusion detection system, which reported that a smurf attack was underway. What firewall configuration change can Robert make to most effectively prevent this attack?

Block the source IP address of the attack.

Block inbound UDP traffic.

Block the destination IP address of the attack.

Block inbound ICMP traffic.

Answer:
D.  Smurf attacks use a distributed attack approach to send ICMP echo replies at a targeted system from many different source addresses. The most effective way to block this attack would be to block inbound ICMP traffic. Blocking the source addresses is not feasible because the attacker would likely simply change the source addresses. Blocking destination addresses would likely disrupt normal activity. The smurf attack does not use UDP, so blocking that traffic would have no effect.

Which one of the following types of firewalls does not have the ability to track connection status between different packets?

Stateful inspection

Application proxy

Packet filter

Next generation

Answer:
C.  Static packet filtering firewalls are known as first-generation firewalls and do not track connection state. Stateful inspection, application proxying, and next-generation firewalls all add connection state tracking capability.

Frances is concerned that equipment failures within her organization's servers will lead to a loss of power to those servers. Which one of the following controls would best address this risk?

Redundant power sources

Backup generators

Dual power supplies

Uninterruptible power supplies

Answer:
C.  All of these controls serve to increase the reliability of power to a server. However, only dual power supplies address hardware issues that arise within the server, allowing the server to continue operation if one of the power supplies fails. Redundant power sources, backup generators, and uninterruptible power supplies (UPS) are designed to increase the reliability of power flowing to the server.

Peter is reviewing the remote access technologies used by his organization and would like to eliminate the use of any techniques that do not include built-in encryption. Which of the following approaches should he retain? (Select all that apply.)

RDP

Telnet

SSH

Dial-up

Answer:
A, C.  The Remote Desktop Protocol (RDP) and Secure Shell (SSH) are modern approaches to remote access that include encryption features. Telnet and dial-up are outdated approaches that do not provide encryption and should not be relied upon for secure access.

Matthew is experiencing issues with the quality of network service on his organization's network. The primary symptom is that packets are occasionally taking too long to travel from their source to their destination. The length of this delay changes for individual packets. What term describes the issue Matthew is facing?

Latency

Jitter

Packet loss

Interference

Answer:
B.  Latency is a delay in the delivery of packets from their source to their destination. Jitter is a variation in the latency for different packets. Packet loss is the disappearance of packets in transit that requires retransmission. Interference is electrical noise or other disruptions that corrupt the contents of packets.

Gavin is an internal auditor working to assess his organization's cybersecurity posture. Which of the following would be appropriate recipients of the reports he generates from his work? (Select all that apply.)

Managers

Individual contributors

Suppliers

Board members

Answer:
A, B, D.  It is entirely appropriate to distribute internal audit reports to anyone in the organization who has a valid need to know. This may include both management and individual contributors responsible for remediating issues as well as board members charged with oversight. It would not normally be appropriate to distribute internal audit reports to external entities, such as suppliers and customers.

Kim is conducting testing of a web application developed by her organization and would like to ensure that it is accessible from all commonly used web browsers. What type of testing should she conduct?

Regression testing

Interface testing

Fuzzing

White-box testing

Answer:
B.  Web applications communicate with web browsers via an interface, making interface testing the best answer here. Regression testing might be used as part of the interface test but is too specific to be the best answer. Similarly, the test might be a white-box, or full knowledge, test, but interface testing better describes this specific example. Fuzzing is less likely a part of a browser compatibility test, as it tests unexpected inputs, rather than functionality.

Kathleen is implementing an access control system for her organization and builds the following arrays:

Reviewers: Update files, delete files

Submitters: Upload files

Editors: Upload files, update files

Archivists: Delete files

What type of access control system has Kathleen implemented?

Role-based access control

Task-based access control

Rule-based access control

Discretionary access control

Answer:
A.  Role-based access control gives each user an array of permissions based on their position in the organization, such as the scheme shown here. Task-based access control is not a standard approach. Rule-based access controls use rules that apply to all subjects, which isn't something we see in the list. Discretionary access control gives object owners rights to choose how the objects they own are accessed, which is not what this list shows.

Alan is installing a fire suppression system that will activate after a fire breaks out and protect the equipment in the data center from extensive damage. What metric is Alan attempting to lower?

Likelihood

RTO

RPO

Impact

Answer:
D.  Fire suppression systems do not stop a fire from occurring but do reduce the damage that fires cause. This is an example of reducing risk by lowering the impact of an event.

Alan's Wrenches recently developed a new manufacturing process for its product. They plan to use this technology internally and not share it with others. They would like it to remain protected for as long as possible. What type of intellectual property protection is best suited for this situation?

Patent

Copyright

Trademark

Trade secret

Answer:
D.  Patents and trade secrets can both protect intellectual property in the form of a process. Patents require public disclosure and have expiration dates, while trade secrets remain in force for as long as they remain secret. Therefore, trade secret protection most closely aligns with the company's goals.

Ben wants to interface with the National Vulnerability Database using a standardized protocol. What option should he use to ensure that the tools he builds work with the data contained in the NVD?

XACML

SCML

VSML

SCAP

Answer:
D.  The Security Content Automation Protocol (SCAP) is a suite of specifications used to handle vulnerability and security configuration information. The National Vulnerability Database provided by NIST uses SCAP. XACML is the eXtensible Access Control Markup Language, an OASIS standard used for access control decisions, and neither VSML nor SCML is an industry term.

Ron's organization does not have the resources to conduct penetration testing that uses time-intensive manual techniques, but he would like to achieve some of the benefits of penetration testing. Which one of the following techniques could he engage in that requires the least manual effort?

White-box testing

Black-box testing

Gray-box testing

Breach and attack simulation

Answer:
D.  Breach and attack simulation (BAS) platforms are intended to automate some aspects of penetration testing. These systems are designed to inject threat indicators onto systems and networks in an effort to trigger other security controls. White-box, gray-box, and black-box testing all involve more significant manual effort.

In the figure shown here, Harry's request to read the data file is blocked. Harry has a Secret security clearance, and the data file has a Top Secret classification. What principle of the Bell–LaPadula model blocked this request?

A sample illustration. Harry blocked request reading from the data file.
Simple Security Property

Simple Integrity Property

*-Security Property

Discretionary Security Property

Answer:
A.  The Simple Security Property prevents an individual from reading information at a higher security level than their clearance allows. This is also known as the “no read up” rule. The Simple Integrity Property says that a subject cannot read an object at a lower integrity level (no read down). The *-Security Property says that users can't write data to a lower security level than their own. The Discretionary Security Property allows the use of a matrix to determine access permissions.

Norm is starting a new software project with a vendor that uses an SDLC approach to development. When he arrives on the job, he receives a document that has the sections shown here. What type of planning document is this?

Larger View
A sample planning document. The first part is for executive summary section with a high level schedule of key activities and milestones. It is followed by detailed project tasksfor the applicable S D L C phase and special interest area tracked outside the S D L C phase areas as required.
Functional requirements

Work breakdown structure

Test analysis report

Project plan

Answer:
B.  The work breakdown structure (WBS) is an important project management tool that divides the work done for a large project into smaller components. It is not a project plan because it does not describe timing or resources. Test analyses are used during later phases of the development effort to report test results. Functional requirements may be included in a work breakdown structure, but they are not the full WBS.

Kolin is searching for a network security solution that will allow him to help reduce zero-day attacks while using identities to enforce a security policy on systems before they connect to the network. What type of solution should Kolin implement?

A firewall

A NAC system

An intrusion detection system

Port security

Answer:
B.  Network Access Control (NAC) systems can be used to authenticate users and then validate their system's compliance with a security standard before they are allowed to connect to the network. Enforcing security profiles can help reduce zero-day attacks, making NAC a useful solution. A firewall can't enforce system security policies, whereas an IDS can only monitor for attacks and alarm when they happen. Thus, neither a firewall nor an IDS meets Kolin's needs. Finally, port security is a MAC address-based security feature that can restrict only which systems or devices can connect to a given port.

Gwen comes across an application that is running under a service account on a web server. The service account has full administrative rights to the server. What principle of information security does this violate?

Need to know

Separation of duties

Least privilege

Job rotation

Answer:
C.  This scenario violates the least privilege principle because an application should never require full administrative rights to run. Gwen should update the service account to have only the privileges necessary to support the application.

Ed is developing a set of key performance and risk indicators for his organization's information security program. Which of the following are commonly used indicators? (Select all that apply.)

Number of scheduled audits

Time to resolve vulnerabilities

Number of malicious site visit attempts

Number of account compromises

Answer:
B, C, D.  Organizations typically use the time to resolve vulnerabilities, the number of account compromises, and the number of attempts by users to visit malicious sites as indicators. The number of scheduled audits is not normally a measure of the performance of an information security team. A more appropriate indicator in this area is the number of repeat audit findings.

Kara is documenting the results of a vulnerability scan. After reviewing one finding, she determined that the vulnerability did exist. The team then implemented a configuration change that corrected the issue. How should Kara classify this vulnerability in her report?

True positive

True negative

False positive

False negative

For questions 114–116, please refer to the following scenario:

During a web application vulnerability scanning test, Steve runs Nikto against a web server he believes may be vulnerable to attacks. Using the Nikto output shown here, answer the following questions.

Larger View
A screenshot of Nikto output page. It includes target I P value, target host name, target port, and start time.
Answer:
A.  This is a true positive report because the scan detected the vulnerability, and the vulnerability actually existed. The fact that the team later remediated the vulnerability could be noted in the report, but it does not change the result of the scan or its classification. True negatives occur when scans correctly note the absence of a vulnerability. False positives occur when scans report the presence of a vulnerability that does not actually exist. False negatives occur when scans report that no vulnerability exists when one does, in fact, exist.

Why does Nikto flag the /test directory?

The /test directory allows administrative access to PHP.

It is used to store sensitive data.

Test directories often contain scripts that can be misused.

It indicates a potential compromise.

Answer:
C.  Test directories often include scripts that may have poor protections or may have other data that can be misused. There is not a default test directory that allows administrative access to PHP. Test directories are not commonly used to store sensitive data, nor is the existence of a test directory a common indicator of compromise.

Why does Nikto identify directory indexing as an issue?

It lists files in a directory.

It may allow for XDRF.

Directory indexing can result in a denial-of-service attack.

Directory indexing is off by default, potentially indicating compromise.

Answer:
A.  Directory indexing may not initially seem like an issue during a penetration test, but simply knowing the name and location of files can provide an attacker with quite a bit of information about an organization, as well as a list of potentially accessible files. XDRF is not a type of attack, and indexing is not a denial-of-service attack vector. Directory indexing being turned on is typically either due to design or because the server was misconfigured at setup, rather than being a sign of attack.

Nikto lists OSVDB-877, noting that the system may be vulnerable to XST. What would this type of attack allow an attacker to do?

Use cross-site targeting.

Steal a user's cookies.

Counter SQL tracing.

Modify a user's TRACE information.

Answer:
B.  Cross-site tracing (XST) leverages the HTTP TRACE or TRACK methods and could be used to steal a user's cookies via cross-site scripting (XSS). The other options are not industry terms for web application or web server attacks or vulnerabilities.

Who would be the most appropriate supervisor for an organization's chief audit executive (CAE)?

CIO

CISO

CEO

CFO

Answer:
C.  The chief audit executive (CAE) should report to the most senior possible leader to avoid conflicts of interest. Of the choices provided, the chief executive officer (CEO) is the most senior position and the best option. It is also possible to provide an added degree of independence by having the CAE report to the board of directors, either as a primary reporting line or as a dotted line relationship.

Ursula believes that many individuals in her organization are storing sensitive information on their laptops in a manner that is unsafe and potentially violates the organization's security policy. What control can she use to identify the presence of these files?

Network DLP

Network IPS

Endpoint DLP

Endpoint IPS

Answer:
C.  Data loss prevention (DLP) systems specialize in the identification of sensitive information. In this case, Ursula would like to identify the presence of this information on endpoint devices, so she should choose an endpoint DLP control. Network-based DLP would not detect stored information unless the user transmits it over the network. Intrusion prevention systems (IPSs) are designed to detect and block attacks in progress, not necessarily the presence of sensitive information.

In what cloud computing model does the customer build a cloud computing environment in their own data center or build an environment in another data center that is for the customer's exclusive use?

Public cloud

Private cloud

Hybrid cloud

Shared cloud

Answer:
B.  In the private cloud computing model, the cloud computing environment is dedicated to a single organization and does not follow the shared tenancy model. The environment may be built by the company in its own data center or built by a vendor at a co-location site.

Which one of the following technologies is designed to prevent a web server going offline from becoming a single point of failure in a web application architecture?

Load balancing

Dual-power supplies

IPS

RAID

Answer:
A.  Load balancing helps to ensure that a failed server will not take a website or service offline. Dual power supplies only work to prevent failure of a power supply or power source. IPS can help to prevent attacks, and RAID can help prevent a disk failure from taking a system offline.

Alice wants to send Bob a message with the confidence that Bob will know the message was not altered while in transit. What security goal is Alice trying to achieve?

Confidentiality

Nonrepudiation

Authentication

Integrity

Answer:
D.  Integrity ensures that unauthorized changes are not made to data while stored or in transit.

What network topology is shown here?

Larger View
A sample ring network topology. Internet is connected to five systems and a device.
A ring

A bus

A star

A mesh

Answer:
C.  A star topology uses a central connection device. Ethernet networks may look like a star, but they are actually a logical bus topology that is sometimes deployed in a physical star.

Monica is developing a software application that calculates an individual's body mass index for use in medical planning. She would like to include a control on the field where the physician enters an individual's weight to ensure that the weight falls within an expected range. What type of control should Monica use?

Fail open

Fail secure

Limit check

Buffer bounds

Answer:
C.  Input validation ensures that the data provided to a program as input matches the expected parameters. Limit checks are a special form of input validation that ensure that the value remains within an expected range, as is the case described in this scenario. Fail open and fail secure are options when planning for possible system failures. Buffer bounds are not a type of software control.

Match the following numbered types of testing methodologies with the lettered correct level of knowledge:

Testing methodologies:

Black box

White box

Gray box

Level of knowledge:

Full knowledge of the system

Partial or incomplete knowledge

No prior knowledge of the system

Answer:
The testing methodologies match with the level of knowledge as follows:

Black box: C. No prior knowledge of the system

White box: A. Full knowledge of the system

Gray box: B. Partial or incomplete knowledge

Match the following lettered factors to their numbered type:

Factors:

A PIN

A token

A fingerprint

A password

A smart card

A retinal scan

A security question/answer

Types:

Something you know

Something you have

Something you are

Answer:
The factors match to the types as follows:

A PIN: 1. Something you know

A token: 2. Something you have

A fingerprint: 3. Something you are

A password: 1. Something you know

A smartcard: 2. Something you have

A retinal scan: 3. Something you are

A security question/answer: 1. Something you know
