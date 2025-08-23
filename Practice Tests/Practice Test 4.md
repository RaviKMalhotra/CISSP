# CISSP Practice Test 4

Chapter 12: Practice Test 4
What type of access control is intended to discover unwanted or unauthorized activity by providing information after the event has occurred?

Preventive

Corrective

Detective

Directive

Answer:
C.  Detective access controls operate after the fact and are intended to detect or discover unwanted access or activity. Preventive access controls are designed to prevent the activity from occurring, whereas corrective controls return an environment to its original status after an issue occurs. Directive access controls limit or direct the actions of subjects to ensure compliance with policies.

Which one of the following presents the most complex decoy environment for an attacker to explore during an intrusion attempt?

Honeypot

Darknet

Honeynet

Pseudo-flaw

Ben's organization is adopting biometric authentication for their high-security building's access control system. Using this chart, answer questions 3–5 about their adoption of the technology.

A graph of percent versus sensitivity. It includes two curves. 1. F A R decremental curve labeled A. 2. F R R incremental curve labeled B.
Answer:
C.  A honeypot is a decoy computer system used to bait intruders into attacking. A honeynet is a network of multiple honeypots that creates a more sophisticated environment for intruders to explore. A pseudo-flaw is a false vulnerability in a system that may distract an attacker. Administrators often include pseudo-flaws on honeypots to emulate well-known operating system vulnerabilities. A darknet is a segment of unused network address space that should have no network activity and, therefore, may be easily used to monitor for illicit activity.

Ben's company is considering configuring their systems to work at the level shown by point A on the diagram. What level are they setting the sensitivity to?

The FRR crossover

The FAR point

The CER

The CFR

Answer:
C.  The crossover error rate (CER) is the point where the false acceptance rate (FAR) and the false rejection rate (FRR) cross over, and it is a standard assessment used to compare the accuracy of biometric devices.

At point B, what problem is likely to occur?

False acceptance will be very high.

False rejection will be very high.

False rejection will be very low.

False acceptance will be very low.

Answer:
A.  At point B, the false acceptance rate (FAR) is quite high, whereas the false rejection rate (FRR) is relatively low. This may be acceptable in some circumstances, but in organizations where a false acceptance can cause a major problem, it is likely that they should instead choose a point to the right of point A.

What should Ben do if the FAR and FRR shown in this diagram do not provide an acceptable performance level for his organization's needs?

Adjust the sensitivity of the biometric devices.

Assess other biometric systems to compare them.

Move the CER.

Adjust the FRR settings in the software.

Answer:
B.  CER is a standard used to assess biometric devices. If the CER for this device does not fit the needs of the organization, Ben should assess other biometric systems to find one with a lower CER. Sensitivity is already accounted for in CER charts, and moving the CER isn't something Ben can do. FRR is not a setting in software, so Ben can't use that as an option either.

Ed is tasked with protecting information about his organization's customers, including their name, Social Security number, birthdate, and place of birth, as well as a variety of other information. What is this information known as?

PHI

PII

Personal protected data

PID

Answer:
B.  Personally identifiable information (PII) can be used to distinguish a person's identity. Personal health information (PHI) includes data such as medical history, lab results, insurance information, and other details about a patient. Personal protected data is a made-up term, and PID is an acronym for process ID, the number associated with a running program or process.

What software development life-cycle model is shown in the following illustration?

Larger View
A sample software development life-cycle model. It begins with system requirements, followed by software requirement, analysis, program design, coding, testing, and operation.
Spiral

Agile

Boehm

Waterfall

Answer:
D.  The figure shows the waterfall model, developed by Winston Royce. An important characteristic of this model is a series of sequential steps that include a feedback loop that allows the process to return one step prior to the current step when necessary.

Encapsulation is the core concept that enables what type of protocol?

Bridging

Multilayer

Hashing

Storage

Answer:
B.  Encapsulation creates both the benefits and potential issues with multilayer protocols. Bridging can use various protocols but does not rely on encapsulation. Hashing and storage protocols typically do not rely on encapsulation as a core part of their functionality.

Amanda wants to use contacts from the existing Gmail accounts that new users already have for her application. What protocol from the following options is used to provide secure delegated access?

Open ID

Kerberos

OAuth

SAML

Answer:
C.  OAuth is used to provide secure delegated access in scenarios exactly like this. OpenID is used to sign in using credentials from an identity provider to other services, such as when you log in with Google to other sites. SAML, or Security Assertion Markup Language, is used to make security assertions allowing authentication and authorizations between identity providers and service providers. Kerberos is mostly used inside of organizations instead of for federation, as this question focuses on. OAuth is specifically designed to provide secure delegated access, allowing Amanda's application to access users' Gmail contacts without requiring users to share their Gmail credentials. It is widely used by cloud services for this purpose. In contrast, OpenID is primarily for authenticating users with an external identity provider, SAML is used for exchanging authentication and authorization data between providers, and Kerberos is typically employed for internal network authentication, not for cloud-based or federated services as described in this scenario.

Which one of the following metrics specifies the amount of time that business continuity planners find acceptable for the restoration of service after a disaster?

MTD

RTO

RPO

MTO

Answer:
B.  The recovery time objective (RTO) is the amount of time that it may take to restore a service after a disaster without unacceptable impact on the business. The RTO for each service is identified during a business impact assessment.

Jill is working to procure new network hardware for her organization. She finds a gray market supplier that is importing the hardware from outside the country at a much lower price. What security concern is the most significant for hardware acquired this way?

The security of the hardware and firmware

Availability of support for the hardware and software

Whether the hardware is a legitimate product of the actual vendor

The age of the hardware

Answer:
A.  Each of these answers may be a concern, but the overriding security concern is whether the hardware and firmware can be trusted or may have been modified. Original equipment manufacturers (OEMs) have business reasons to ensure the security of their products, but third parties in the supply chain may not feel the same pressure. Both availability of support and whether the hardware is legitimate are also concerns, but less immediate security concerns. Finally, hardware may be older than expected, or may be used, refurbished, or otherwise not new.

What process is typically used to ensure data security for workstations that are being removed from service but that will be resold or otherwise reused?

Destruction

Erasing

Sanitization

Clearing

Answer:
C.  When done properly, a sanitization process fully ensures that data does not remain on the system before it is reused. Clearing and erasing can both be failure prone, and of course, destruction wouldn't leave a machine or device available for reuse.

Colleen is conducting a software test that is evaluating code for both security flaws and usability issues. She is working with the application from an end-user perspective and referencing the source code as she works her way through the product. What type of testing is Colleen conducting?

White box

Blue box

Gray box

Black box

Answer:
C.  In a gray-box test, the tester evaluates the software from a user perspective but has access to the source code as the test is conducted. White-box tests also have access to the source code but perform testing from a developer's perspective. Black-box tests work from a user's perspective but do not have access to source code. Blue boxes are a telephone hacking tool and not a software testing technique. Note: as language changes, new terms like zero knowledge, partial knowledge, and full knowledge are starting to replace white-, gray-, and black-box testing terms.

Harold is looking for a software development methodology that will help with a major issue he is seeing in his organization. Currently, developers and operations staff do not work together and are often seen as taking problems and “throwing them over the fence” to the other team. What technology management approach is designed to alleviate this problem?

ITIL

Lean

ITSM

DevOps

Answer:
D.  The DevOps approach to technology management seeks to integrate software development, operations, and quality assurance in a cohesive effort. It specifically attempts to eliminate the issue of taking problems and “throwing them over the fence” by building collaborative relationships between members of the IT team.

NIST Special Publication 800-92, the Guide to Computer Security Log Management, describes four types of common challenges to log management:

Many log sources

Inconsistent log content

Inconsistent timestamps

Inconsistent log formats

Which of the following solutions is best suited to solving these issues?

Implement SNMP for all logging devices.

Implement a SIEM tool.

Standardize the Windows event log format for all devices and use NTP.

Ensure that logging is enabled on all endpoints using their native logging formats and set their local time correctly.

Answer:
B.  A security information and event management (SIEM) tool is designed to centralize logs from many locations in many formats and to ensure that logs are read and analyzed despite differences between different systems and devices. The Simple Network Management Protocol (SNMP) is used for some log messaging but is not a solution that solves all of these problems. Most non-Windows devices, including network devices among others, are not designed to use the Windows event log format, although using NTP for time synchronization is a good idea. Finally, local logging is useful, but setting clocks individually will result in drift over time and won't solve the issue with many log sources.

Mikayla's organization has been notified about an authentication bypass vulnerability in their product by a security researcher. The researcher has stated that they will share details about the vulnerability in question within the next 90 days if Mikayla's company fails to remediate it. However, they are also willing to collaborate with the company to help them understand the issue and provide them with full details on how to re-create the problem. What process has the researcher followed?

A CVE creation process

A bug bounty

Ethical disclosure

Blackmail

Answer:
C.  Ethical disclosure involves informing organizations of flaws and issues. Unlike bug bounties, this does not rely on organizations providing financial or other rewards. Ethical disclosure may involve timeframes to ensure that companies do not ignore issues, but a focus on collaboration and public safety is common. CVEs are created when flaws are reported to the CVE program. There is no blackmail behavior involved in this description.

Carlos is investigating the compromise of sensitive information in his organization. He believes that attackers managed to retrieve personnel information on all employees from the database and finds the following user-supplied input in a log entry for a web-based personnel management system:

Collins'&1=1;––
What type of attack took place, and how could it be prevented?

SQL injection, use of stored procedures

Buffer overflow, automatic buffer expansion

Cross-site scripting, turning on XSS prevention on the web server

Cross-site request forgery, requiring signed requests

Answer:
A.  The single quotation mark in the input field is a telltale sign that this is a SQL injection attack. The quotation mark is used to escape outside the SQL code's input field, and the text that follows is used to directly manipulate the SQL command sent from the web application to the database.

Which one of the following is a detailed, step-by-step document that describes the exact actions that individuals must complete?

Policy

Standard

Guideline

Procedure

Answer:
D.  Procedures are formal, mandatory documents that provide detailed, step-by-step actions required from individuals performing a task.

For what purpose are the CIS benchmarks frequently used in organizations?

Secure coding standards

Performance testing

Baselining

Monitoring metrics

Answer:
C.  The CIS benchmarks are configuration baselines that are frequently used to assess the security settings or configuration for devices and software. Baselining is the process of configuring and validating that a system meets security configuration guidelines or standards.

Carlos' team has detected a compromise and initiated the incident response process. What will happen next?

Remediation

Mitigation

Reporting

Lessons learned

Answer:
B.  A typical incident response (IR) process will begin mitigation efforts after response has started and then will move into the recovery, reporting, and lessons learned phases. It is important to remember that while the IR cycle is drawn as a cycle, it often moves back and forth between phases as new issues or details are identified.

Carlos is planning a design for a data center that will be constructed within a new four-story corporate headquarters. The building consists of a basement and three above-ground floors. What is the best location for the data center?

Basement

First floor

Second floor

Third floor

Answer:
C.  Data centers should be located in the core of a building. Locating it on lower floors makes it susceptible to flooding and physical break-ins. Locating it on the top floor makes it vulnerable to wind and roof damage.

Chris is an information security professional for a major corporation, and as he is walking into the building, he notices that the door to a secure area has been left ajar. Physical security does not fall under his responsibility, but he takes immediate action by closing the door and informing the physical security team of his action. What principle is Chris demonstrating?

Due care

Crime prevention through environmental design

Separation of duties

Informed consent

Answer:
A.  The due care principle states that an individual should react in a situation using the same level of care that would be expected from any reasonable person. It is a very broad standard. Crime prevention through environmental design is a design concept that focuses on making environments less conducive to illicit or unwanted actions. Separation of duties splits duties to ensure that a malicious actor cannot perform actions on their own like making a purchase and approving it. Informed consent is a term used in the medical industry that requires that a person's permission is required and that they must be aware of what the consequences of their actions could be.

Which one of the following investigation types always uses the beyond-a-reasonable-doubt standard of proof?

Civil investigation

Criminal investigation

Operational investigation

Regulatory investigation

Answer:
B.  Criminal investigations have high stakes with severe punishment for the offender that may include incarceration. Therefore, they use the strictest standard of evidence of all investigations: beyond a reasonable doubt. Civil investigations use a preponderance-of-the-evidence standard. Regulatory investigations may use whatever standard is appropriate for the venue where the evidence will be heard. This may include the beyond-a-reasonable-doubt standard, but it is not always used in regulatory investigations in the United States. Operational investigations do not use a standard of evidence.

Kristen wants to use multiple processing sites for her data but does not want to pay for a full data center. Which of the following options would you recommend as her best option if she wants to be able to quickly migrate portions of her custom application environment to facilities in multiple countries without having to wait to ship or acquire hardware?

A cloud PaaS vendor

A hosted data center provider

A cloud IaaS vendor

A data center vendor that provides rack, power, and remote hands services

Answer:
C.  A cloud IaaS vendor will allow Kristen to set up infrastructure as quickly as she can deploy and pay for it. A PaaS vendor provides a platform that would require her to migrate her custom application to it, likely taking longer than a hosted data-center provider. A data-center vendor that provides rack, power, and remote hands assistance fails the test based on Kristen's desire to not have to acquire or ship hardware.

What type of alternate processing facility contains the hardware necessary to restore operations but does not have a current copy of data?

Hot site

Warm site

Cold site

Mobile site

Answer:
B.  Warm sites contain the hardware necessary to restore operations but do not have a current copy of data.

Which one of the following terms describes a period of momentary high voltage?

Sag

Brownout

Spike

Surge

Answer:
C.  A power spike is a momentary period of high voltage. A surge is a prolonged period of high voltage. Sags and brownouts are periods of low voltage.

Greg needs to label drives used for his company's medical insurance claims database. What data label from the following list best matches the type of data he is dealing with?

PII

Secret

Business confidential

PHI

Answer:
D.  Medical insurance claims will contain protected health information, or PHI. Greg should label the drives as containing PHI and then ensure that they are handled according to his organization's handling standards for that type of data.

Marco wants to deploy a network security device that can detect and stop network-based attacks without additional external intervention. What type of device should he employ and in what configuration?

An inline IDS

An IDS connected through a network tap

An inline IPS

An IPS connected through a network tap

Answer:
C.  While both an intrusion detection system (IDS) and an intrusion prevention system (IPS) can detect attacks, only an IPS can stop attacks. This requires the IPS to be placed inline. A connection via a network tap, span port, or other similar tool for replicating network traffic will not allow defensive actions to be taken directly by the device.

Selah wants to ensure that vehicles cannot crash through her company's entryway and front lobby while still remaining accessible to pedestrians and wheelchairs or other mobility devices. What physical security control is best suited to this purpose?

Fences

Bollards

Walls

Stairs

For questions 30–34, please refer to the following scenario:

Concho Controls is a midsize business focusing on building automation systems. It hosts a set of local file servers in its on-premises data center that store customer proposals, building plans, product information, and other data that is critical to its business operations.

Tara works in the Concho Controls IT department and is responsible for designing and implementing the organization's backup strategy, among other tasks. She currently conducts full backups every Sunday evening at 8 p.m. and differential backups on Monday through Friday at noon.

Concho experiences a server failure at 3 p.m. on Wednesday. Tara rebuilds the server and wants to restore data from the backups.

Answer:
B.  Bollards are physical security solutions that are short and strong posts or similar solutions intended to stop vehicles from crashing through or passing an area. Bollards can be used to allow pedestrians and mobility devices to pass while stopping vehicles. Fences and walls will prevent individuals from passing through them, while stairs are challenging for most mobility devices.

What backup should Tara apply to the server first?

Sunday's full backup

Monday's differential backup

Tuesday's differential backup

Wednesday's differential backup

Answer:
A.  Tara first must achieve a system baseline. She does this by applying the most recent full backup to the new system. This is Sunday's full backup. Once Tara establishes this baseline, she may then proceed to apply differential backups to bring the system back to a more recent state.

How many backups in total must Tara apply to the system to make the data it contains as current as possible?

1

2

3

4

Answer:
B.  To restore the system to as current a state as possible, Tara must first apply Sunday's full backup. She may then apply the most recent differential backup, from Wednesday at noon. Differential backups include all files that have changed since the most recent full backup, so the contents of Wednesday's backup contain all of the data that would be contained in Monday and Tuesday's backups, making the Monday and Tuesday backups irrelevant for this scenario.

In this backup approach, some data may be irretrievably lost. How long is the time period when any changes made will have been lost?

3 hours.

5 hours.

8 hours.

No data will be lost.

Answer:
A.  In this scenario, the differential backup was made at noon, and the server failed at 3 p.m. Therefore, any data modified or created between noon and 3 p.m. on Wednesday will not be contained on any backup and will be irretrievably lost.

If Tara followed the same schedule but switched the differential backups to incremental backups, how many backups in total would she need to apply to the system to make the data it contains as current as possible?

1

2

3

4

Answer:
D.  By switching from differential to incremental backups, Tara's weekday backups will contain only the information changed since the previous day. Therefore, she must apply all of the available incremental backups. She would begin by restoring the Sunday full backup and then apply the Monday, Tuesday, and Wednesday incremental backups.

If Tara made the change from differential to incremental backups and we assume that the same amount of information changes each day, which one of the following files would be the largest?

Monday's incremental backup.

Tuesday's incremental backup.

Wednesday's incremental backup.

All three will be the same size.

Answer:
D.  Each incremental backup contains only the information changed since the most recent full or incremental backup. If we assume that the same amount of information changes every day, each of the incremental backups would be roughly the same size.

The following figure shows an example of an attack where Mal, the attacker, has redirected traffic from a user's system to their own, allowing them to read TLS encrypted traffic. Which of the following terms best describes this attack?

Larger View
A network illustration of an attack in mal. Redirected connection to mal's system, forwarded traffic from mal to original destination, and original T L S protected connection.
A DNS hijacking attack

An ARP spoofing attack

A man-in-the-middle attack

A SQL injection attack

Answer:
C.  A man-in-the-middle (MiTM), often referred to as a person-in-the-middle or on-path attack, allows an attacker to redirect traffic and thus read or modify it. This can be completely transparent to the end user, making it a dangerous attack if the malicious actor is successful. DNS hijacking would change a system's domain name information, and there is no direct indication of that here. Similarly, ARP spoofing is one way to conduct a MiTM attack, but that detail is not here either. SQL injection is normally done via web applications to execute commands against a database server.

Bob has been tasked with writing a policy that describes how long data should be kept and when it should be purged. What concept does this policy deal with?

Data remanence

Record retention

Data redaction

Audit logging

Answer:
B.  Record retention ensures that data is kept and maintained as long as it is needed and that it is purged when it is no longer necessary. Data remanence occurs when data is left behind after an attempt is made to remove it, whereas data redaction is not a technical term used to describe this effort. Finally, audit logging may be part of the records retained but doesn't describe the life cycle of data.

Which component of IPsec provides authentication, integrity, and nonrepudiation?

L2TP

Encapsulating Security Payload

Encryption Security Header

Authentication Header

Answer:
D.  The Authentication Header provides authentication, integrity, and nonrepudiation for IPsec connections. The Encapsulating Security Payload provides encryption and thus provides confidentiality. It can also provide limited authentication. L2TP is an independent VPN protocol, and Encryption Security Header is a made-up term.

Renee is reviewing logs and notices that a system on her network recently received connection attempts on all 65,536 TCP ports from a single system during a short period of time. What type of attack did Renee most likely experience?

Denial of service

Reconnaissance

Malicious insider

Compromise

Answer:
B.  The attack described in the scenario is a classic example of TCP scanning, a network reconnaissance technique that may precede other attacks. There is no evidence that the attack disrupted system availability, which would characterize a denial-of-service attack; that it was waged by a malicious insider; or that the attack resulted in the compromise of a system.

What type of Windows audit record describes events like an OS shutdown or a service being stopped?

An application log

A security log

A system log

A setup log

Answer:
C.  Windows system logs include reboots, shutdowns, and service state changes. Application logs record events generated by programs, security logs track events like logins and uses of rights, and setup logs track application setup.

Melissa is in charge of her organization's security compliance efforts and has been told that the organization does not install Windows patches until a month has passed since the patch has been released unless there is a zero-day exploit that is being actively exploited. Why would the company delay patching like this?

To minimize business impact of the installation

To allow any flaws with the patch to be identified

To prevent malware in the patches from being installed before it is identified

To allow the patch to be distributed to all systems

Answer:
B.  Many organizations delay patches for a period of time to ensure that any previously unidentified flaws are found before the patches are installed throughout their organization. Melissa needs to balance business impact against security in her role and may choose to support this or to push for more aggressive installation practices depending on the organization's risk tolerance and security needs.

What level of RAID is also known as disk striping?

RAID 0

RAID 1

RAID 5

RAID 10

Answer:
A.  RAID level 0 is also known as disk striping. RAID 1 is called disk mirroring. RAID 5 is called disk striping with parity. RAID 10 is known as a stripe of mirrors.

Jake is updating his disaster recovery plan and wants to ensure that the third-party data center his organization contracts with can handle the scaling requirements needed in a disaster. What type of agreement should Jake sign with the hosting provider?

A resource capacity agreement

A cold-site agreement

An NDA

A business continuity agreement

Answer:
A.  Resource capacity agreements are used to ensure that appropriate resources will be available in a recovery scenario. Cold sites have only space and utilities and don't provide full recovery resources. Nondisclosure agreements protect information and won't ensure resource availability, and business continuity agreements are not a term used in the CISSP exam.

Diana's organization teaches employees to use a pre-arranged code if they are kidnapped or under threat and contact the organization. What type of solution is this?

A duress code

A panic button

A kidnap code

A threat code

Answer:
A.  Duress codes are pre-arranged codes used to indicate that the staff member is under duress. They are typically designed to be easy to communicate during normal conversation without alarming whomever may be listening in. Panic buttons are physical buttons used to summon emergency services or responders. Kidnap codes and threat codes were made up for this question.

Fred's company wants to ensure the integrity of email messages sent via its central email servers. If the confidentiality of the messages is not critical, what solution should Fred suggest?

Digitally sign and encrypt all messages to ensure integrity.

Digitally sign but don't encrypt all messages.

Use TLS to protect messages, ensuring their integrity.

Use a hashing algorithm to provide a hash in each message to prove that it hasn't changed.

Answer:
B.  Fred's company needs to protect integrity, which can be accomplished by digitally signing messages. Any change will cause the signature to be invalid. Encrypting isn't necessary because the company does not want to protect confidentiality. TLS can provide in-transit protection but won't protect integrity of the messages, and of course a hash used without a way to verify that the hash wasn't changed won't ensure integrity either.

The leadership at Susan's company has asked her to implement an access control system that can support rule declarations like “Only allow access to salespeople from managed devices on the wireless network between 8 a.m. and 6 p.m.” What type of access control system would be Susan's best choice?

ABAC

RBAC

DAC

MAC

Answer:
A.  An attribute-based access control (ABAC) system will allow Susan to specify details about subjects, objects, and access, allowing granular control. Although a rule-based access control system (RBAC) might allow this, the attribute-based access control system can be more specific and thus is more flexible. Discretionary access control (DAC) would allow object owners to make decisions, and mandatory access controls (MACs) would use classifications; neither of these capabilities was described in the requirements.

Nora's company operates servers on a five-year life cycle. When they reach their end of life according to that process, the servers are sent to an e-waste recycler. Which of the following is the most effective control that Nora could implement to ensure that a data breach does not occur due to remanent data?

Zero wipe the drives before the servers leave the organization.

Remove the drives and shred them.

Reformat the drives before the servers are sent to the e-waste company.

Require certificates of disposal from the e-waste company.

Answer:
B.  The most effective control is to remove the drives and shred them, removing any chance for the servers to leave with data remaining on them. A trustworthy company that can provide a certificate of disposal with appropriate contractual controls may be a reasonable and cost-efficient alternative, but the company may also then want to zero wipe drives before the systems leave to reduce the risk if a system makes it out of the recycler's control. The worst answer here is reformatting, which will not remove data.

Chris is deploying a gigabit Ethernet network using Category 6 cable between two buildings. What is the maximum distance he can run the cable according to the Category 6 standard?

50 meters

100 meters

200 meters

300 meters

Answer:
B.  The maximum allowed length of a Cat 6 cable is 100 meters, or 328 feet. Long distances are typically handled by a fiber run or by using network devices like switches or repeaters—not only because of the distance but also because outdoor runs can experience lightning strikes, which won't affect fiber. Knowing that copper twisted pair has distance limitations can be important in many network designs and influences where switches and other devices are placed.

Howard is a security analyst working with an experienced computer forensics investigator. The investigator asks him to retrieve a forensic drive controller, but Howard cannot locate a device in the storage room with this name. What is another name for a forensic drive controller?

RAID controller

Write blocker

SCSI terminator

Forensic device analyzer

Answer:
B.  One of the main functions of a forensic drive controller is to prevent any command sent to a device from modifying data stored on the device. For this reason, forensic drive controllers are also often referred to as write blockers.

The web application that Saria's development team is working on needs to provide secure session management that can prevent hijacking of sessions using the cookies that the application relies on. Which of the following techniques would be the best for her to recommend to prevent this?

Set the Secure attribute for the cookies, thus forcing TLS.

Set the Domain cookie attribute to example.com to limit cookie access to servers in the same domain.

Set the Expires cookie attribute to less than a week.

Set the HTTPOnly attribute to require only unencrypted sessions.

Answer:
A.  Setting the Secure cookie will allow cookies to be sent only via HTTPS TLS or SSL sessions, preventing man-in-the-middle attacks that target cookies. The rest of the settings are problematic. For example, cookies are vulnerable to DNS spoofing. Domain cookies should usually have the narrowest possible scope, which is actually accomplished by not setting the Domain cookie. This allows only the originating server to access the cookie. Cookies without the Expires or Max-age attributes are ephemeral and will only be kept for the session, making them less vulnerable than stored cookies. Normally, the HTTPOnly attribute is a good idea, but it prevents scripting rather than requiring unencrypted HTTP sessions.

Ben's team has been tasked with ensuring that devices that leave his organization do not contain organizational data. They have wiped and re-formatted drives in systems that are being sent to a third-party electronics recycler as part of the process, but a journalist recently reported that organization entrusted to Ben's company was recovered from drives bought from the recycler. What issue is Ben's team encountering, and what solution should they select to prevent it most effectively?

Data permanence, process certification

Data remanence, drive destruction

Data permanence, using a degausser

Data remanence, zero fill

Answer:
B.  Data remanence describes data that is still on media after an attempt has been made to remove it. Destroying the drive is a way to ensure that no data is recoverable. Data permanence describes how long data lasts and is not used in the context of data remaining on devices.

What access control scheme labels subjects and objects and allows subjects to access objects when the labels match?

DAC

MAC

Rule-based access control (RBAC)

Role-based access control (RBAC)

Answer:
B.  Mandatory access control (MAC) applies labels to subjects and objects and allows subjects to access objects when their labels match. Discretionary access control (DAC) is controlled by the owner of objects, rule-based access control (sometimes called Rule-BAC) applies rules throughout a system, and role-based access control (sometimes called Role-BAC) bases rights on roles, which are often handled as groups of users.

A cloud-based service that provides account provisioning, management, authentication, authorization, reporting, and monitoring capabilities is known as what type of service?

PaaS

IDaaS

IaaS

SaaS

Answer:
B.  Identity as a service (IDaaS) provides capabilities such as account provisioning, management, authentication, authorization, reporting, and monitoring. Platform as a service (PaaS), infrastructure as a service (IaaS), and software as a service (SaaS) are cloud service models but do not provide the identity and access management functions described in the question.

Sally wants to secure her organization's VoIP systems. Which of the following attacks is one that she shouldn't have to worry about?

Eavesdropping

Denial-of-service

XSS

Caller ID spoofing

Answer:
C.  Eavesdropping, denial-of-service attacks, and caller ID spoofing are all common VoIP attacks. Cross-site scripting targets web applications, not VoIP systems.

Marty discovers that the access restrictions in his organization allow any user to log into the workstation assigned to any other user, even if they are from completely different departments. This type of access most directly violates which information security principle?

Separation of duties

Two-person control

Need to know

Least privilege

Answer:
D.  This broad access may indirectly violate all of the listed security principles, but it is most directly a violation of least privilege because it grants users privileges that they do not need for their job functions.

Fred needs to transfer files between two servers on an untrusted network. Since he knows the network isn't trusted, he needs to select an encrypted protocol that can ensure that his data remains secure. What protocol should he choose?

SSH

TCP

SFTP

IPsec

Answer:
C.  The Secure File Transfer Protocol (SFTP) is specifically designed for encrypted file transfer. SSH is used for secure command-line access, whereas TCP is one of the bundles of Internet protocols commonly used to transmit data across a network. IPsec could be used to create a tunnel to transfer the data but is not specifically designed for file transfer.

Manesh wants to help his organization build secure software. Which of the following is not a common security best practice for working with security frameworks and libraries?

Use internally developed libraries and frameworks whenever possible to reduce third-party threats.

Identify and inventory all third-party libraries.

Encapsulate libraries to prevent the use of functions that are not needed.

Update libraries and components on a regular basis.

Use your knowledge of Kerberos authentication and authorization as well as the following diagram to answer questions 57–59.

Larger View
A set of three network frameworks. 1. Client workstation A is connected to K D C. 2. K D C-B is connected to client workstation. 3. Client workstation C is connected to service and then D.
Answer:
A.  OWASP recommends four critical best practices for libraries and frameworks: using libraries and frameworks from trusted sources that are broadly used and well maintained, maintaining an inventory of third-party libraries, updating libraries and components proactively, and reducing attack surface by limiting what functions can be used. Building your own frameworks and libraries is more likely to result in vulnerabilities for most organizations than using well-maintained and supported existing options.

If the client has already authenticated to the KDC, what does the client workstation send to the KDC at point A when it wants to access a resource?

It resends the password.

A TGR.

Its TGT.

A service ticket.

Answer:
C.  The client sends its existing valid TGT to the KDC and requests access to the resource.

What occurs between steps A and B?

The KDC verifies the validity of the TGT and whether the user has the right privileges for the requested resource.

The KDC updates its access control list based on the data in the TGT.

The KDC checks its service listing and prepares an updated TGT based on the service request.

The KDC generates a service ticket to issue to the client.

Answer:
A.  The KDC must verify that the TGT is valid and whether the user has the right privileges to access the service it is requesting access to. If it does, it generates a service ticket and sends it to the client (step B).

What system or systems does the service that is being accessed use to validate the ticket?

The KDC.

The client workstation and the KDC.

The client workstation supplies it in the form of a client-to-server ticket and an authenticator.

The KVS.

Answer:
C.  When a client connects to a service server (SS), it sends the following two messages:

The client-to-server ticket, encrypted using the service's secret key

A new authenticator, including the client ID and timestamp that is encrypted using the client-server session key

The server or service that is being accessed receives all of the data it needs in the service ticket. To do so, the client uses a client-to-server ticket received from the ticket granting service.

What does a service ticket (ST) provide in Kerberos authentication?

It serves as the authentication host.

It provides proof that the subject is authorized to access an object.

It provides proof that a subject has authenticated through a KDC and can request tickets to access other objects.

It provides ticket granting services.

Answer:
B.  The service ticket in Kerberos authentication provides proof that a subject is authorized to access an object. Ticket granting services are provided by the TGS. Proof that a subject has authenticated and can request tickets to other objects and uses ticket-granting tickets, and authentication host is a made-up term.

Judy is preparing to conduct a business impact analysis. What should her first step be in the process?

Identify threats to the business.

Identify risks to the organization.

Identify business priorities.

Conduct likelihood analysis.

Answer:
C.  The first step in a business impact analysis is to identify the business's priorities. Judy should ensure that business areas are all represented and that the functions of each department or area are assessed. Once that is done, she can move on to identifying risks, evaluating likelihood and impact, and then prioritizing the resources available to the business to address the identified priorities.

What is the most common risk that cellular phone hotspots create for business networks?

They can provide attackers with an unsecured network path into your network.

They can be used like rogue access points for man-in-the-middle attacks.

They allow wireless data to be intercepted.

They are unencrypted and can be easily sniffed.

Answer:
A.  Organizations are most often concerned about hotspots creating an unsecured network connection into their secure network via laptops or other devices that are connected to them. Bridging a cellular connection to a network connection to the business's network creates a path that bypasses security controls. Hotspots could be used as rogue access points, but this is a less common scenario. They do not specifically allow wireless data to be intercepted and, in most modern implementations, are encrypted, thus limiting the likelihood of sniffing providing useful data.

Which one of the following fire suppression systems poses the greatest risk of accidental discharge that damages equipment in a data center?

Wet pipe

Dry pipe

Deluge

Preaction

Answer:
A.  Dry pipe, deluge, and preaction systems all use pipes that remain empty until the system detects signs of a fire. Wet pipe systems use pipes filled with water that may damage equipment if there is damage to a pipe.

Amanda's healthcare provider maintains such data as details about her health, treatments, and medical billing. What type of data is this?

Protected health information

Personally identifiable information

Protected health insurance

Individual protected data

Answer:
A.  Protected health information (PHI) is defined by HIPAA to include health information used by healthcare providers, such as medical treatment, history, and billing. Personally identifiable information (PII) is information that can be used to identify an individual, which may be included in the PHI but isn't specifically this type of data. Protected health insurance and individual protected data are both made-up terms.

What type of code review is best suited for identifying business logic flaws?

Mutation fuzzing

Manual testing

Generational fuzzing

Interface testing

Answer:
B.  Manual testing uses human understanding of business logic to assess program flow and responses. Mutation or generational fuzzing will help determine how the program responds to expected inputs but does not test the business logic. Interface testing ensures that data exchange between modules works properly but does not focus on the logic of the program or application.

Something you know is an example of what type of authentication factor?

Type 1

Type 2

Type 3

Type 4

Answer:
A.  A Type 1 authentication factor is something you know. A Type 2 authentication factor is something you have, like a smartcard or hardware token. A Type 3 authentication factor is something you are, like a biometric identifier. There is no such thing as a Type 4 authentication factor.

Saria is the system owner for a healthcare organization. What responsibilities does she have related to the data that resides on or is processed by the systems she owns?

She has to classify the data.

She has to make sure that appropriate security controls are in place to protect the data.

She has to grant appropriate access to personnel.

She bears sole responsibility for ensuring that data is protected at rest, in transit, and in use.

Answer:
B.  System owners develop and maintain system security plans with system administrators, and they have to ensure that appropriate security controls are in place on those systems. System owners also share responsibility for data protection with data owners. System administrators grant appropriate access and apply the controls, whereas data owners own the classification process.

During software testing, Jack diagrams how a hacker might approach the application he is reviewing and determines what requirements the hacker might have. He then tests how the system would respond to the attacker's likely behavior. What type of testing is Jack conducting?

Misuse case testing

Use-case testing

Hacker use-case testing

Static code analysis

Answer:
A.  Jack is performing misuse case analysis, a process that tests code based on how it would perform if it were misused instead of used properly. Use-case testing tests valid use cases, whereas static code analysis involves reviewing the code itself for flaws rather than testing the live software. Hacker use case testing isn't an industry term for a type of testing.

Rick's risk assessment for his company's web application noted that it could suffer from SQL injection attacks. Which of the following mitigation techniques would you recommend Rick apply to help reduce this risk? (Select all that apply.)

Stored procedures

Escaping all user-supplied input

Parameterized queries

Input validation

Answer:
A, B, C, D.  All of these options are useful to help prevent SQL injection. Stored procedures limit what can be done via the database server, and escaping user input makes dangerous characters less likely to be a problem. Parameterized queries limit what can be sent in a query, and input validation adds another layer of protection by limiting what can be successfully input by a user.

Chris has been assigned to scan a system on all of its possible TCP and UDP ports. How many ports of each type must he scan to complete his assignment?

65,536 TCP ports and 32,768 UDP ports

1,024 common TCP ports and 32,768 ephemeral UDP ports

65,536 TCP and 65,536 UDP ports

16,384 TCP ports, and 16,384 UDP ports

Answer:
C.  Both TCP and UDP port numbers are a 16-digit binary number, which means there can be 216 ports, or 65,536 ports, numbered from 0 to 65,535.

CVE and the NVD both provide information about what?

Vulnerabilities

Markup languages

Vulnerability assessment tools

Penetration testing methodologies

Answer:
A.  MITRE's Common Vulnerabilities and Exploits (CVE) dictionary and NIST's National Vulnerability Database (NVD) both provide information about vulnerabilities.

Michelle wants to ensure that her company does not keep logs for longer than they need to. What type of policy should she write and implement to ensure this?

An EOL policy

A data classification policy

An EOS policy

A record retention policy

Answer:
D.  Record retention policies are used to establish what data organizations retain and how long they will retain it for. Keeping data longer than necessary can increase risk to the organization, but having data when needed for investigations, legal compliance, or other business purposes is also important. EOL, or end of life, and EOS, or end of support, apply to hardware or software and not to data. Data classification policies are used to help classify data, which may influence how long it is retained, but classification policies themselves typically do not set retention timeframes.

Beth's company uses cloud-based infrastructure that uses a combination of policies and automated security controls to ensure security. The company deploys firewalls, endpoint security tools, and management capabilities to ensure that every virtual system is protected as it is brought online. What term describes this type of implementation?

Root of trust

Software-defined security

A policy engine

Software-defined networks

Answer:
B.  Software-defined security (SDS) is an increasingly common approach to security that involves using software solutions and policies to secure environments, rather than traditional hardware-based approaches. This strategy allows for flexible and dynamic security configurations, particularly suited to the cloud's scalable nature. While a root of trust provides a foundational security element in cryptographic systems, policy engines contribute to decision-making in SDS and other frameworks by enforcing security policies. Software-defined networks focus on network management through software, showcasing the broader move toward software-defined approaches in IT infrastructure.

What three important items should be considered if you are attempting to control the strength of signal for a wireless network as well as where it is accessible?

Antenna placement, antenna type, antenna power levels

Antenna design, power levels, use of a captive portal

Antenna placement, antenna design, use of a captive portal

Power levels, antenna placement, FCC minimum strength requirements

Answer:
A.  Antenna placement, antenna design, and power levels are the three important factors in determining where a signal can be accessed and how usable it is. A captive portal can be used to control user logins, and antenna design is part of antenna types. The FCC does provide maximum broadcast power guidelines but does not require a minimum power level.

What is the best way to ensure that data is unrecoverable from an SSD?

Use the built-in erase commands.

Use a random pattern wipe of 1s and 0s.

Physically destroy the drive.

Degauss the drive.

Answer:
C.  Physically destroying the drive is the best way to ensure that there is no remnant data on the drive. SSDs are flash media, which means that you can't degauss them, whereas both random pattern writes and the built-in erase commands have been shown to be problematic due to the wear leveling built into SSDs as well as differences in how they handle erase commands.

Alice sends a message to Bob and wants to ensure that Mal, a third party, does not read the contents of the message while in transit. What goal of cryptography is Alice attempting to achieve?

Confidentiality

Integrity

Authentication

Nonrepudiation

Answer:
A.  Confidentiality ensures that data cannot be read by unauthorized individuals while stored or in transit.

Ian wants to ensure that his organization is using appropriate secure coding techniques. Which of the following is not a common practice for input validation?

Conduct data validation on a trusted system.

Validate data length.

Validate all client-provided data before it is processed.

Convert all data to the same data type.

Answer:
D.  OWASP's secure coding practices checklist provides a wide variety of input validation recommendations, including conducting data validation on trusted systems, validating data length, range, and types, and validating all client-provided data before it is processed. Converting all data to the same data type isn't possible because multiple data types are needed for most programs and applications.

The company that Gary works for processes credit cards and operates under an industry standard for credit card handling. Which of the following standards will his company need to comply with?

ISO27001

FIPS 140

PCI-DSS

ISO 27002

Answer:
C.  PCI-DSS, or the Payment Card Industry Data Security Standard, is the industry standard Gary's company will need to comply with. ISO27001 and 27002 are information security management standards. FIPS 140 is a standard for cryptographic modules.

James has opted to implement a NAC solution that uses a post-admission philosophy for its control of network connectivity. What type of issues can't a strictly post-admission policy handle?

Out-of-band monitoring

Preventing an unpatched laptop from being exploited immediately after connecting to the network

Denying access when user behavior doesn't match an authorization matrix

Allowing a user access to a specific object when user behavior is allowed based on an authorization matrix

Answer:
B.  A post-admission philosophy allows or denies access based on user activity after connection based on a predefined authorization matrix. Since this doesn't check the status of a machine before it connects, it can't prevent the exploit of the system immediately after connection. This doesn't preclude out-of-band or in-band monitoring, but it does mean that a strictly post-admission policy won't handle system checks before the systems are admitted to the network.

Ben has built an access control list that lists the objects that his users are allowed to access. When users attempt to access an object that they don't have rights to, they are denied access, even though there isn't a specific rule that prevents it. What access control principle is key to this behavior?

Least privilege

Implicit deny

Explicit deny

Final rule fall-through

Answer:
B.  The implicit deny principle states that any action that is not explicitly allowed is denied. This is an important concept for firewall rules and other access control systems. Implementing least privilege ensures that subjects have only the rights they need to accomplish their job. While explicit deny and final rule fall-through may sound like important access control concepts, neither is.

Mary is a security risk analyst for an insurance company. She is currently examining a scenario where a hacker might be able to modify the contents of directories on the web server due to a missing patch in the company's web application. In this scenario, what is the risk?

Unpatched web application

Web defacement

Hacker

Operating system

Answer:
B.  Risks are the combination of a threat and a vulnerability. Threats are the external forces seeking to undermine security, such as the hacker in this case. Vulnerabilities are the internal weaknesses that might allow a threat to succeed. In this case, web defacement is the risk. In this scenario, if the hacker attempts a SQL injection attack (threat) against the unpatched server (vulnerability), the result is website defacement (risk).

The mean time to detect a compromise is what type of security measurement?

An MTO

A technical control objective

A compliance objective

A KPI

Answer:
D.  The mean time to detect a compromise is a security KPI, or key performance indicator. KPIs are used to determine how effective practices, procedures, and staff are.

Val is testing her organization's software using a tool that simulates an attacker's actions against it. What type of testing is Val conducting?

SAST

LAST

DAST

FAST

Answer:
C.  Val is conducting dynamic application security testing, or DAST. DAST simulates an attacker's actions against software to test it. SAST reviews source code to identify vulnerabilities. FAST and LAST are not software testing methodologies or tools.

In Jen's job as the network administrator for an industrial production facility, she is tasked with ensuring that the network is not susceptible to electromagnetic interference due to the large motors and other devices running on the production floor. What type of network cabling should she choose if this concern is more important than the cost and difficulty of installation?

10Base2

100BaseT

1000BaseT

Fiber optic

For questions 85–88, please refer to the following scenario:

Jasper Diamonds is a jewelry manufacturer that markets and sells custom jewelry through its website. Bethany is the manager of Jasper's software development organization, and she is working to bring the company into line with industry-standard practices. She is developing a new change management process for the organization and wants to follow commonly accepted approaches.

Answer:
D.  Fiber-optic cable is more expensive and can be harder to install than stranded copper cable or coaxial cable in some cases, but it isn't susceptible to electromagnetic interference (EMI). That makes it a great solution for Jen's problem, especially if she is deploying EMI-hardened systems to go with her EMI-resistant network cables.

Bethany would like to put in place controls that provide an organized framework for company employees to suggest new website features that her team will develop. What change management process facilitates this?

Configuration control

Change control

Release control

Request control

Answer:
D.  The request control process provides an organized framework within which users can request modifications, managers can conduct cost/benefit analyses, and developers can prioritize tasks.

Bethany would also like to create a process that helps multiple developers work on code at the same time. What change management process facilitates this?

Configuration control

Change control

Release control

Request control

Answer:
B.  Change control provides an organized framework within which multiple developers can create and test solutions prior to rolling them out into a production environment.

Bethany is working with her colleagues to conduct user acceptance testing. What change management process includes this task?

Configuration control

Change control

Release control

Request control

Answer:
C.  Release control includes acceptance testing to ensure that any alterations to end-user work tasks are understood and functional.

Bethany noticed that some problems arise when system administrators update libraries without informing developers. What change management process can assist with this problem?

Configuration control

Change control

Release control

Request control

Answer:
A.  Configuration control ensures that changes to software versions are made in accordance with the change control and configuration management process. Updates can be made only from authorized distributions in accordance with those policies.

Asha's team wants to ensure that all of the functions of their software are tested. What are they ensuring?

Proper misuse case testing

That a breach attack simulation is conducted

Complete interface testing

Complete coverage

Answer:
D.  Coverage analysis is performed to ensure that functionality, requirements, or other elements are completely tested. No misuse cases are described in the question, no interfaces are described, and breach attack simulations are intended to act like an attacker, rather than test for all functions.

Which one of the following is an example of risk transference?

Building a guard shack

Purchasing insurance

Erecting fences

Relocating facilities

Answer:
B.  Risk transference involves actions that shift risk from one party to another. Purchasing insurance is an example of risk transference because it moves risk from the insured to the insurance company.

What protocol takes the place of certificate revocation lists and adds real-time status verification?

RTCP

RTVP

OCSP

CSRTP

Answer:
C.  The Online Certificate Status Protocol (OCSP) eliminates the latency inherent in the use of certificate revocation lists by providing a means for real-time certificate verification.

Xavier's company has been using an increasing number of cloud services, and he is concerned that the security policies that the company has implemented in its existing data center are not being followed in the cloud. Which of the following solutions is best suited to ensuring that policies are applied to all cloud services?

A CIPS

A CASB

A CSG

A CDLP

Answer:
B.  A cloud access security broker (CASB) is a tool that sits between on-premises and cloud systems, monitoring traffic and enforcing security policies. This scenario exactly matches what a CASB is designed to do. The other answers were made up; none of these is an actual cloud security device or tool (at least as of the writing of this book!).

What process makes TCP a connection-oriented protocol?

It works via network connections.

It uses a handshake.

It monitors for dropped connections.

It uses a complex header.

Answer:
B.  TCP's use of a handshake process to establish communications makes it a connection-oriented protocol. TCP does not monitor for dropped connections, nor does the fact that it works via network connections make it connection-oriented.

Susan wants to build a security awareness program for her organization but knows that keeping staff engaged is difficult. Which of the following techniques is often associated with the use of points and scores as part of the assessment process?

Gamification

Phishing testing

Security champions

Social engineering evaluations

Answer:
A.  Gamification uses common components from games like points, scores, and competition to engage participants in a security awareness program. None of the other answers uses these together unless they use a gamification component.

You are conducting a qualitative risk assessment for your organization. The two important risk elements that should weigh most heavily in your analysis of risk are probability and ________________.

Likelihood

History

Impact

Cost

Answer:
C.  The two most important elements of a qualitative risk assessment are determining the probability and impact of each risk upon the organization. Likelihood is another word for probability. Cost should be taken into account but is only one element of impact, which also includes reputational damage, operational disruption, and other ill effects.

Using the OSI model, what format does the Data Link layer use to format messages received from higher up the stack?

A data stream

A frame

A segment

A datagram

Answer:
B.  When a message reaches the Data Link layer, it is called a frame. Data streams exist at the Application, Presentation, and Session layers, whereas segments and datagrams exist at the Transport layer (for TCP and UDP, respectively).

What is the maximum penalty that may be imposed by an ISC2 peer review board when considering a potential ethics violation?

Revocation of certification

Termination of employment

Financial penalty

Suspension of certification

Answer:
A.  If the ISC2 peer review board finds that a certified individual has violated the ISC2 Code of Ethics, the board may revoke their certification. The board is not able to terminate an individual's employment or assess financial penalties.

Which one of the following statements about the SDLC is correct?

The SDLC requires the use of an iterative approach to software development.

The SDLC requires the use of a sequential approach to software development.

The SDLC does not include training for end users and support staff.

The waterfall methodology is compatible with the SDLC.

Answer:
D.  SDLC approaches include steps to provide operational training for support staff as well as end-user training. The SDLC may use one of many development models, including the waterfall and spiral models. The SDLC does not mandate the use of an iterative or sequential approach; it allows for either approach.

In the diagram shown here, Harry is prevented from reading a file at a higher classification level than his security clearance. What security model prevents this behavior?

Larger View
A sample illustration. Harry blocked reading request from the data file.
Bell–LaPadula

Biba

Clark–Wilson

Brewer–Nash

Answer:
A.  The Bell–LaPadula model includes the Simple Security Property, which prevents an individual from reading information that is classified at a level higher than the individual's security clearance.

Sylvia's company's new application allows users to sign up for banking services. Sylvia needs to identify a way to ensure that users are who they claim to be. What is this process called?

Proofing

Registration

FIM

Single sign-on

Answer:
A.  Identity proofing is the process of validating that the entity or individual claiming an identity is the actual person or organization that they claim to be. This commonly relies on additional information like documents or knowledge that others would not have. Registration is the process of creating an account. FIM is federated identity management, and SSO allows a single sign-on to be used across multiple systems or services.

Travis is concerned about the security that his organization's use of Microsoft's BitLocker provides for systems. When are the systems most secure from data loss based on the encryption state of the drive if the systems are equipped with TPM and use full-disk encryption?

When they are booted up and running because the system monitors for drive access

When the system is shutting down because keys are removed from memory

When they are booting up because the TPM checks for a secure boot process

When they are off because the drive is fully encrypted

Answer:
D.  The files on the drive are at their most secure when the system is off and the drive is encrypted and not in a readable state. BitLocker decrypts files as needed when in use, meaning that any time after the system is booted files may be accessed, particularly if the user is logged in and access to the system can be gained or if malware is running.

Andrea wants to ensure that her virtualized networks are secure between virtual environments. She uses virtual machine clusters in multiple locations in her state with third-party Internet service providers between those locations. Which of the following solutions is best suited to protecting her traffic if she runs a flattened layer 2 network between those locations?

TLS

BGP

IPsec

AES

For questions 103–105, please refer to the following scenario:

The company that Fred works for is reviewing the security of their company-issued cell phones. They issue 4G-capable smartphones running Android and iOS and use a mobile device management solution to deploy company software to the phones. The mobile device management software also allows the company to remotely wipe the phones if they are lost.

Answer:
C.  An IPsec VPN will allow Andrea to keep her networks running as layer 2 flattened networks when necessary while providing the security for her traffic that she wants. TLS operates at a higher network layer, although traffic could be tunneled through it. BGP is a routing protocol, and AES is an encryption algorithm.

What security considerations should Fred's company require for sending sensitive data over the cellular network?

They should use the same requirements as data over any public network.

Cellular provider networks are private networks and should not require special consideration.

Encrypt all traffic to ensure confidentiality.

Require the use of WAP for all data sent from the phone.

Answer:
A.  Cellular networks have the same issues that any public network does. Encryption requirements should match those that the organization selects for other public networks like hotels, conference Wi-Fi, and similar scenarios. Encrypting all data is difficult and adds overhead, so it should not be the default answer unless the company specifically requires it. WAP is a dated wireless application protocol and is not in broad use; requiring it would be difficult. WAP does provide TLS, which would help when in use.

Fred intends to attend a major hacker conference this year and needs to connect to his employer's network during his time at the conference. What should he do when connecting to his cellular provider's 4G network while at the conference?

Continue normal usage.

Discontinue all usage; towers can be spoofed.

Only use trusted Wi-Fi networks.

Connect to his company's encrypted VPN service.

Answer:
D.  Fred's best option is to use an encrypted, trusted VPN service to tunnel all of his data usage. Trusted Wi-Fi networks are unlikely to exist at a hacker conference, normal usage is dangerous due to the proliferation of technology that allows fake towers to be set up, and discontinuing all usage won't support Fred's business needs.

What are the most likely circumstances that would cause a remote wipe of a mobile phone to fail?

The phone has a passcode on it.

The phone cannot contact a network.

The provider has not unlocked the phone.

The phone is in use.

Answer:
B.  Remote wipe tools are a useful solution, but they work only if the phone can access either a cellular or Wi-Fi network. Remote wipe solutions are designed to wipe data from the phone regardless of whether it is in use or has a passcode. Providers unlock phones for use on other cellular networks rather than for wiping or other feature support.

Elaine is developing a business continuity plan for her organization. What value should she seek to minimize?

AV

SSL

RTO

MTO

Answer:
C.  The goal of business continuity planning exercises is to reduce the amount of time required to restore operations. This is done by minimizing the recovery time objective (RTO).

Warren wants to conduct an internal security audit. He wants to use a broadly accepted audit framework so that he can more easily compare the results to other organizations. Which of the following options should he select as his base audit framework?

ITSM

ATT&CK

COBIT

CIS

Answer:
C.  The COBIT, or Control Objectives for Information and related Technologies, framework describes common requirements that organizations should have in place for their information systems. It is the only audit or compliance framework on the list. ITSM is the acronym for Information Technology Service Management; CIS is the Center for Information Security, which provides guidelines for system security that can be used to assess systems but is not itself an audit framework; and ATT&CK is a framework for describing threats and attack methodologies.

Place the list of disaster recovery test types in order of their potential operational impact on the business, starting with the least impactful and progressing through the most impactful.

Checklist review

Parallel test

Tabletop exercise

Full interruption test

1, 2, 3, 4

1, 3, 2, 4

1, 3, 4, 2

2, 1, 3, 4

Answer:
B.  The disaster recovery test types, listed in order of their potential impact on the business from the least impactful to the most impactful, are as follows:

Checklist review

Tabletop exercise

Parallel test

Full interruption test

Checklist reviews are the least impactful type of exercise because they do not even require a meeting. Each team member reviews the checklist on their own. Tabletop exercises are slightly more impactful because they require bringing together the DR team in the same room. Parallel tests require the activation of alternate processing sites and require significant resources. Full interruption tests are the most impactful type of exercise because they involve shifting operations to the alternate site and could disrupt production activity.

Jack's data center design calls for dual-power supplies in every critical server. What part of the CIA triad is he addressing with this design decision?

Confidentiality

Integrity

Availability

None of the above

Answer:
C.  Redundancy is part of many availability designs. Dual power supplies allow multiple levels of availability support; they allow you to connect servers to distinct power infrastructures and also provide the ability to run if a single power supply dies. Some servers are even set up to use more than two power supplies. Another approach to this type of availability is to use more systems, rather than more expensive systems with greater support for availability.

What step is missing from the IR process cycle diagram shown here?

Larger View
An I R processcycle diagram. It begins with X, followed by remediation, detection, response, mitigation, and reporting.
Forensics

Retribution

Recovery

Analysis

Answer:
C.  The CISSP CBK uses a six-stage process: Detection, Response, Mitigation, Reporting, Recovery, and Remediation. This diagram is missing Recovery. Other standards differ, using different terms or slightly different processes.

The company that Felipe works for has connected servers they have hosted in a third-party data center to vendor-owned systems using fiber-optic cables for a direct connection to them. What is this called?

Ingress

Peering

East/west

Egress

Answer:
B.  This is an example of peering. Peering can be either public peering, a connection through an Internet Exchange Point via a network connection, or private peering done directly with another entity in a colocation facility. Ingress is traffic coming into a network, egress is traffic that is leaving a network, and east/west refers to network traffic in the same zone or layer of a network.

Megan wants to ensure that the new software as a service provider that her company is signing a contract with will make sure the service works all the time without disruptions. Which of the following is often part of contracts to provide that assurance?

An SLA

An RPA

An NDA

An MOU

Answer:
A.  A service level agreement, or SLA, contains details about how the service will be provided, what level of outages or downtime is acceptable, and what remedies may exist in the case of outages or other issues. Megan should ensure that the SLA contains both appropriate performance guarantees and penalties that will be of sufficient magnitude to compensate her company for issues while motivating the service provider to maintain a reliable service. An RPA is robotic process automation, an automation technology. An NDA is a nondisclosure agreement, a legal document used to help control the risk of information or data being exposed or shared. An MOU is a memorandum of understanding and is used when two organizations want to work together to document a shared vision or the goals they share.

Kyle wants to ensure that his organization's backups are stored securely in case of a natural disaster or other event. What type of solution should he choose if he needs to store backup tapes?

A cloud backup service

A hot site

A media storage facility

A BaaS provider

Answer:
C.  Media storage facilities are frequently used when organizations want to securely store backups like tapes in a secure, temperature-controlled facility. Cloud services are not used for physical backup media; hot sites are used to restore operations, not to store backup media; and BaaS is backup as a service—another description for a cloud backup service.

Norm would like to conduct a disaster recovery test for his organization and wants to choose the most thorough type of test, recognizing that it may be quite disruptive. What type of test should Norm choose?

Full interruption test

Parallel test

Tabletop exercise

Checklist review

Answer:
A.  During a full interruption test, the team takes down the primary site and confirms that the disaster recovery site is capable of handling regular operations. The full interruption test is the most thorough test but also the most disruptive. During a parallel test, the team actually activates the disaster recovery site for testing, but the primary site remains operational. The checklist review is the least disruptive type of disaster recovery test. During a checklist review, team members each review the contents of their disaster recovery checklists on their own and suggest any necessary changes. During a tabletop exercise, team members come together and walk through a scenario without making any changes to information systems.

Ed is building a network that supports IPv6 but needs to connect it to an IPv4 network. What type of device should Ed place between the networks?

A switch

A router

A bridge

A gateway

Answer:
D.  Ed's best option is to install an IPv6 to IPv4 gateway that can translate traffic between the networks. A bridge would be appropriate for different types of networks, whereas a router would make sense if the networks were similar. A modern switch might be able to carry both types of traffic but wouldn't be much help translating between the two protocols.

Henry's company has deployed an extensive IoT infrastructure for building monitoring that includes environmental controls, occupancy sensors, and a variety of other sensors and controllers that help manage the building. Which of the following security concerns should Henry report as the most critical in his analysis of the IoT deployment?

The lack of local storage space for security logs that is common to IoT devices.

The IoT devices may not have a separate administrative interface, allowing anybody on the same network to attempt to log into them and making brute-force attacks possible.

The IoT devices may not support strong encryption for communications, exposing the log and sensor data to interception on the network.

The long-term support and patching model for the IoT devices may create security and operational risks for the organization.

Answer:
D.  Henry's biggest concern should be the long-term security and supportability of the IoT devices. As these devices are increasingly embedded in buildings and infrastructure, the support model and security model are important to understand. Both the lack of separate administrative access and the lack of strong encryption can be addressed by placing the IoT devices on a dedicated subnet or network that prevents other users from accessing the devices directly. This will help limit the risk without undue expense or complexity and is a common practice. Finally, lack of storage space can be a concern but is not the most important when looking at the risks IoT devices can create.

Isaac wants to use a connectionless protocol to transfer data because he needs to optimize the speed of transmission over reliability. Which protocol should he select?

ICMP

TCP

UDP

SNMP

Answer:
C.  UDP, the User Datagram Protocol, is a connectionless, best-effort protocol that is often used when sending data quickly without strong requirements for reliability features like error correction and detection or flow control to make sense. TCP is connection-oriented and provides those and other reliability features. ICMP, the Internet Control Message Protocol, is used to check routes and paths as well as availability but is not used for significant data transfer in normal cases. SNMP is a network management monitoring protocol.

Which one of the following actions is not required under the EU General Data Protection Regulation?

Organizations must allow individuals to opt out of information sharing.

Organizations must provide individuals with lists of employees with access to information.

Organizations must use proper mechanisms to protect data against unauthorized disclosure.

Organizations must have a dispute resolution process for privacy issues.

Answer:
B.  The EU General Data Protection Regulation does not require that organizations provide individuals with employee lists.

Tammy is selecting a disaster recovery facility for her organization. She would like to choose a facility that balances the time required to recover operations with the cost involved. What type of facility should she choose?

Hot site

Warm site

Cold site

Red site

Answer:
B.  Tammy should choose a warm site. This type of facility meets her requirements for a good balance between cost and recovery time. It is less expensive than a hot site but facilitates faster recovery than a cold site. A red site is not a type of disaster recovery facility.

What layer of the OSI model is associated with datagrams?

Session

Transport

Network

Data Link

Answer:
B.  When data reaches the Transport layer, it is sent as segments (TCP) or datagrams (UDP). Above the Transport layer, data becomes a data stream, while below the Transport layer, they are converted to packets at the Network layer, frames at the Data Link layer, and bits at the Physical layer.

Which one of the following is not a valid key length for the Advanced Encryption Standard?

128 bits

192 bits

256 bits

384 bits

Answer:
D.  The Advanced Encryption Standard supports encryption with 128-bit keys, 192-bit keys, and 256-bit keys.

Which one of the following technologies provides a function interface that allows developers to directly interact with systems without knowing the implementation details of that system?

Data dictionary

Object model

Source code

API

Answer:
D.  An application programming interface (API) allows developers to create a direct method for other users to interact with their systems through an abstraction that does not require knowledge of the implementation details. Access to object models, source code, and data dictionaries also indirectly facilitates interaction but does so in a manner that provides other developers with implementation details.

Ian wants to assess the security of his company's new SaaS provider. Which of the following options is the most likely option that he can realistically expect to be able to use to assess a major cloud provider's security?

Run a vulnerability scan against the provider's external services.

Request a SOC 2 Type II report.

Run a vulnerability scan against the provider's internal systems.

Request a SOC 1 Type II report.

Answer:
B.  Ian's best bet is a SOC report, and a SOC 2 Type II report will assess security controls and their application over time, telling him if the organization is responsibly maintaining their security efforts. A SOC 1 report looks at financial controls, and a Type I report only looks at how controls are described, not their application over time. Ian is unlikely to be allowed to run a vulnerability scan against a major provider's infrastructure either internally or externally.

Sharon wants to conduct a pass-the-hash attack. Which of the following is not a common means of acquiring NTLM hashes for the attack?

Dumping the system's SAM

Dumping credentials from active memory

Capturing network traffic

Downloading the hashes from a third-party site

Answer:
D.  Pass-the-hash attacks (PtH) often rely on dumped local account databases (the SAM), capturing credentials from the network while they are in transit or from active memory. Pass-the-hash attacks are not typically conducted by downloading hashes from third-party sites.

Match each one of the numbered protocols with the most accurate lettered description. Use each answer exactly once.

Protocol:

TCP

UDP

DNS

ARP

Description:

Performs translations between MAC addresses and IP addresses

Performs translations between FQDNs and IP addresses

Transports data over a network in a connection-oriented fashion

Transports data over a network in a connectionless fashion

Answer:
The protocols match with the descriptions as follows:

TCP: C. Transports data over a network in a connection-oriented fashion

UDP: D. Transports data over a network in a connectionless fashion

DNS: B. Performs translations between FQDNs and IP addresses

ARP: A. Performs translations between MAC addresses and IP addresses

The Domain Name System (DNS) translates human-friendly fully qualified domain names (FQDNs) into IP addresses, making it possible to easily remember websites and hostnames. ARP is used to resolve IP addresses into MAC addresses. TCP and UDP are used to control the network traffic that travels between systems. TCP does so in a connection-oriented fashion using the three-way handshake, while UDP uses connectionless “best-effort” delivery.
