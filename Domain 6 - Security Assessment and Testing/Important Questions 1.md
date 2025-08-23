# Domain 6 - Security Assessment and Testing Important Questions

SUBDOMAINS
6.1 Design and validate assessment, test, and audit strategies
6.2 Conduct security controls testing
6.3 Collect security process data (e.g., technical, and administrative)
6.4 Analyze test output and generate report
6.5 Conduct or facilitate security audits
During a port scan, Susan discovers a system running services on TCP and UDP 137–139 and TCP 445, as well as TCP 1433. What type of system is she likely to find if she connects to the machine?

A Linux email server

A Windows SQL server

A Linux file server

A Windows workstation

Answer:
B.  TCP and UDP ports 137–139 are used for NetBIOS services, whereas 445 is used for Active Directory. TCP 1433 is the default port for Microsoft SQL, indicating that this is probably a Windows server providing SQL services.

Which of the following is a method used to automatically design new software tests and to ensure the quality of tests?

Code auditing

Static code analysis

Regression testing

Mutation testing

Answer:
D.  Mutation testing modifies a program in small ways and then tests that mutant to determine if it behaves as it should or if it fails. This technique is used to design and test software tests through mutation. Static code analysis and regression testing are both means of testing code, whereas code auditing is an analysis of source code rather than a means of designing and testing software tests.

During a port scan, Naomi found TCP port 443 open on a system. Which tool is best suited to scanning the service that is most likely running on that port?

zzuf

Nikto

Metasploit

Sqlmap

Answer:
B.  TCP port 443 normally indicates an HTTPS server. Nikto is useful for vulnerability scanning web servers and applications and is the best choice listed for a web server. Metasploit includes some scanning functionality but is not a purpose-built tool for vulnerability scanning. zzuf is a fuzzing tool and isn't relevant for vulnerability scans, whereas sqlmap is a SQL injection testing tool.

What message logging standard is commonly used by network devices, Linux and Unix systems, and many other enterprise devices?

Syslog

Netlog

Eventlog

Remote Log Protocol (RLP)

Answer:
A.  Syslog is a widely used protocol for event and message logging. Eventlog, netlog, and Remote Log Protocol are all made-up terms.

Alex wants to use an automated tool to fill web application forms to test for format string vulnerabilities. What type of tool should he use?

A black box

A brute-force tool

A fuzzer

A static analysis tool

Answer:
C.  Fuzzers are tools designed to provide invalid or unexpected input to applications, testing for vulnerabilities like format string vulnerabilities, buffer overflow issues, and other problems. A static analysis relies on examining code without running the application or code and thus would not fill forms as part of a web application. Brute-force tools attempt to bypass security by trying every possible combination for passwords or other values. A black box is a type of penetration test where the testers do not know anything about the environment.

Susan needs to scan a system for vulnerabilities, and she wants to use an open-source tool to test the system remotely. Which of the following tools will meet her requirements and allow vulnerability scanning?

Nmap

OpenVAS

MBSA

Nessus

Answer:
B.  OpenVAS is an open-source vulnerability scanning tool that will provide Susan with a report of the vulnerabilities that it can identify from a remote, network-based scan. Nmap is an open-source port scanner. Both the Microsoft Baseline Security Analyzer (MBSA) and Nessus are closed-source tools, although Nessus was originally open source.

Morgan is implementing a vulnerability management system that uses standards-based components to score and evaluate the vulnerabilities it finds. Which of the following is most commonly used to provide a severity score for vulnerabilities?

CCE

CVSS

CPE

OVAL

Answer:
B.  CVSS, the Common Vulnerability Scoring System, is used to describe the severity of security vulnerabilities. CCE is Common Configuration Enumeration, a naming system for configuration issues. CPE is Common Platform Enumeration, which names operating systems, applications, and devices. OVAL is a language for describing security testing procedures.

Jim has been contracted to perform a penetration test of a bank's primary branch. To make the test as real as possible, he has not been given any information about the bank other than its name and address. What type of penetration test has Jim agreed to perform?

A crystal-box penetration test

A gray-box penetration test

A black-box penetration test

A white-box penetration test

Answer:
C.  Jim has agreed to a black-box penetration test, which provides no information about the organization, its systems, or its defenses. A crystal- or white-box penetration test provides all of the information an attacker needs, whereas a gray-box penetration test provides some, but not all, information.

In a response to a request for proposal, Susan receives an SSAE 18 SOC report. If she wants a report that includes details on operating effectiveness, what should Susan ask for as follow-up, and why?

A SOC 2 Type II report, because Type I does not cover operating effectiveness

A SOC 1 Type I report, because SOC 2 does not cover operating effectiveness

A SOC 2 Type I report, because SOC 2 Type II does not cover operating effectiveness

A SOC 3 report, because SOC 1 and SOC 2 reports are outdated

Answer:
A.  The key to answering this question correctly is understanding the difference between SOC 1 and SOC 2 reports, and Type I and Type II audits. SOC 1 reports cover financial reporting, and SOC 2 reports look at security. Type I audits cover only a single point in time and are based on management descriptions of controls. They do not include an assessment of operating effectiveness. Type II audits cover a period of time and include an assessment of operating effectiveness.

During a wireless network penetration test, Susan runs aircrack-ng against the network intending to capture a password as part of the four-way handshake and then crack the password offline. What might cause her to fail in her password-cracking efforts if the target is using WPA3 in Personal network mode?

WPA3 uses complex passwords.

WPA3 uses SAE and does not transfer the password over the air.

WPA3 requires multifactor, making a password alone insufficient.

The password crack will work due to flaws in WPA3.

Answer:
B.  WPA3 uses SAE, or simultaneous authentication of equals, and does not send the password over the air. Traditional cracking methods used against previous versions of WPA and WPA2 no longer work. This is not because of complex passwords or MFA, but because of how the handshake's elements are created to avoid sending the password.

A zero-day vulnerability is announced for the popular Apache web server in the middle of a workday. In Jacob's role as an information security analyst, he needs to quickly scan his network to determine what servers are vulnerable to the issue. What is Jacob's best route to quickly identify vulnerable systems?

Immediately run Nessus against all of the servers to identify which systems are vulnerable.

Review the CVE database to find the vulnerability information and patch information.

Create a custom IDS or IPS signature.

Identify affected versions and check systems for that version number using an automated scanner.

Answer:
D.  In many cases when an exploit is initially reported, there are no prebuilt signatures or detections for vulnerability scanners, and the CVE database may not immediately have information about the attack. Jacob's best option is to quickly gather information and review potentially vulnerable servers based on their current configuration. As more information becomes available, signatures and CVE information are likely to be published. Unfortunately for Jacob, IDS and IPS signatures will detect only attacks and won't detect whether systems are vulnerable unless he sees the systems being exploited.

What type of testing is used to ensure that separately developed software modules properly exchange data?

Fuzzing

Dynamic testing

Interface testing

API checksums

Answer:
C.  Interface testing is used to ensure that software modules properly meet interface specifications and thus will properly exchange data. Dynamic testing tests software in a running environment, whereas fuzzing is a type of dynamic testing that feeds invalid input to running software to test error and input handling. API checksums are not a testing technique.

Selah wants to provide security assessment information to customers who want to use her organization's cloud services. Which of the following options should she select to ensure that the greatest number of customers are satisfied with the assessment information?

Use an internal audit team to self-assess against internal metrics.

Use a third-party auditor.

Use internal technical staff who know the systems.

Use an internal audit team to self-assess against a common standard like COBIT.

Answer:
B.  Using a third-party auditor from a well-known and well-regarded firm is often the best option when providing audit and compliance information to third parties. Selah could engage an appropriate vendor for a SOC 2 Type II engagement as one example of a reasonable option to provide detail to her customers. Internal staff assessing against a common standard like COBIT would be the next most acceptable option on this list, with an internal standard less useful than that. Finally, relying on internal personnel not specialized in audits proves to be the least effective strategy in this context.

Yasmine has been asked to consider a breach and attack simulation system. What type of system should she look for?

A ticket and change management system designed to help manage incidents

A system that runs incident response simulations for blue teams to test their skills

A system that combines red and blue team techniques with automation

A security operations and response (SOAR) system

Answer:
C.  Breach and attack simulation (BAS) systems combine red team (attack) and blue team (defense) techniques together with automation to simulate advanced persistent threats and other advanced threat actors when run against your environment. This allows a variety of threats to be replicated and assessed in an environment without as much overhead as a fully staffed purple team would.

Monica wants to gather information about security awareness in her organization. What technique is most frequently used to assess the broad range elements that make up security awareness?

Phishing simulations

Gamified applications

Assessment tests

Surveys

Answer:
D.  Most organizations use surveys to assess security awareness. Phishing simulators are also frequently used, but only test awareness of phishing issues and techniques, not general security awareness. Gamified applications are continuing to grow in popularity, but the ease of use and availability of surveys make them the most popular. Finally, assessment tests may be used when compliance knowledge assessments are required to meet a specific standard, but testing is not as common as surveying.

Jim has been contracted to conduct a gray-box penetration test, and his clients have provided him with the following information about their networks so that he can scan them:

Data center: 10.10.10.0/24

Sales: 10.10.11.0/24

Billing: 10.10.12.0/24

Wireless: 192.168.0.0/16

What problem will Jim encounter if he is contracted to conduct a scan from off-site?

The IP ranges are too large to scan efficiently.

The IP addresses provided cannot be scanned.

The IP ranges overlap and will cause scanning issues.

The IP addresses provided are RFC 1918 addresses.

Answer:
D.  The IP addresses that his clients have provided are RFC 1918 nonroutable IP addresses, and Jim will not be able to scan them from off-site. To succeed in his penetration test, he will have to either first penetrate their network border or place a machine inside their network to scan from the inside. IP addresses overlapping is not a real concern for scanning, and the ranges can easily be handled by current scanning systems.

Mark's company has been notified of a flaw in their web application. The anonymous individual has notified them that they have two weeks to fix it before the details of the flaw are published along with example exploit code. What industry norm is the individual who contacted Mark's company violating?

Zero-day reporting

Ethical disclosure

Ethical hacking

The ISC2 vulnerability disclosure ethics statement

For questions 18–20, please refer to the following scenario:

The company that Jennifer works for has implemented a central logging infrastructure, as shown here. Use this diagram and your knowledge of logging systems to answer the following questions.

Larger View
A diafram depicts the implementation of a central logging infrastructure. It begins with a access point, followed by windows desktop system under corporate network, data center firewall, Linux web server, and Linux database server, and finally S I E M appliance.
Answer:
B.  Ethical (or responsible) disclosure practices will provide companies and organizations with a reasonable period of time to fix a flaw and to get that fix into the hands of their customers. Two weeks is unlikely to be a reasonable amount of time for this. Unfortunately, Mark may not be able to persuade the individual to make a different decision, and Mark's company will need to determine what to do about the issue.

Jennifer needs to ensure that all Windows systems provide identical logging information to the SIEM. How can she best ensure that all Windows desktops have the same log settings?

Perform periodic configuration audits.

Use Group Policy.

Use Local Policy.

Deploy a Windows syslog client.

Answer:
B.  Group Policy enforced by Active Directory can ensure consistent logging settings and can provide regular enforcement of policy on systems. Periodic configuration audits won't catch changes made between audits, and local policies can drift due to local changes or differences in deployments. A Windows syslog client will enable the Windows systems to send syslog to the SIEM appliance but won't ensure consistent logging of events.

During normal operations, Jennifer's team uses the SIEM appliance to monitor for exceptions received via syslog. What system shown does not natively have support for syslog events?

Enterprise wireless access points

Windows desktop systems

Linux web servers

Enterprise firewall devices

Answer:
B.  Windows systems generate logs in the Windows native logging format. To send syslog events, Windows systems require a helper application or tool. Enterprise wireless access points, firewalls, and Linux systems all typically support syslog.

What technology should an organization use for each of the devices shown in the diagram to ensure that logs can be time sequenced across the entire infrastructure?

Syslog

NTP

Logsync

SNAP

Answer:
B.  Network Time Protocol (NTP) can ensure that systems are using the same time, allowing time sequencing for logs throughout a centralized logging infrastructure. Syslog is a way for systems to send logs to a logging server and won't address time sequencing. Neither logsync nor SNAP is an industry term.

During a penetration test, Michelle needs to identify systems, but she hasn't gained sufficient access on the system she is using to generate raw packets. What type of scan should she run to verify the most open services?

A TCP connect scan

A TCP SYN scan

A UDP scan

An ICMP scan

Answer:
A.  When a tester does not have raw packet creation privileges, such as when they have not escalated privileges on a compromised host, a TCP connect scan can be used. TCP SYN scans require elevated privileges on most Linux systems due to the need to write raw packets. A UDP scan will miss most services that are provided via TCP, and an ICMP is merely a ping sweep of systems that respond to pings and won't identify services at all.

During a port scan using nmap, Joseph discovers that a system shows two ports open that cause him immediate worry:

21/open

23/open

What services are likely running on those ports?

SSH and FTP

FTP and Telnet

SMTP and Telnet

POP3 and SMTP

Answer:
B.  Joseph may be surprised to discover FTP (TCP port 21) and Telnet (TCP port 23) open on his network since both services are unencrypted and have been largely replaced by SSH, and SCP or SFTP. SSH uses port 22, SMTP uses port 25, and POP3 uses port 110.

Aaron wants to validate his compliance with PCI-DSS. His company is a large commercial organization with millions of dollars in transactions a year. What is the most common method of conducting this type of testing for large organizations?

Self-assessment

To conduct a thirty-party assessment using COBIT

To partner with another company and trade assessments between the organizations

To conduct a third-party assessment using a qualified security assessor

Answer:
D.  Large organizations hire QSAs, or qualified security assessors, to conduct compliance checks. Third-party certification is required for large organizations by PCI-DSS, although smaller organizations can self-certify.

What method is commonly used to assess how well software testing covered the potential uses of an application?

A test coverage analysis

A source code review

A fuzz analysis

A code review report

Answer:
A.  A test coverage analysis is often used to provide insight into how well testing covered the set of use cases that an application is being tested for. Source code reviews look at the code of a program for bugs, not necessarily at a use case analysis, whereas fuzzing tests invalid inputs. A code review report might be generated as part of a source code review.

Testing that is focused on functions that a system should not allow is an example of what type of testing?

Use case testing

Manual testing

Misuse case testing

Dynamic testing

Answer:
C.  Testing how a system could be misused, or misuse testing, focuses on behaviors that are not what the organization desires or that are counter to the proper function of a system or application. Use case testing is used to verify whether a desired functionality works. Dynamic testing is used to determine how code handles variables that change over time, whereas manual testing is just what it implies: testing code by hand.

What type of monitoring uses simulated traffic to a website to monitor performance?

Log analysis

Synthetic transaction monitoring

Passive monitoring

Simulated transaction analysis

Answer:
B.  Synthetic transaction monitoring uses emulated or recorded transactions to monitor for performance changes in response time, functionality, or other performance monitors. Passive monitoring uses a span port or other method to copy traffic and monitor it in real time. Log analysis is typically performed against actual log data but can be performed on simulated traffic to identify issues. Simulated transaction analysis is not an industry term.

Derek wants to ensure that his organization tracks all changes to accounts through their life cycle. What type of tool should he invest in for his organization?

A directory service like LDAP

An IAM system

A SIEM

An EDR system

Answer:
B.  Identity and access management (IAM) systems combine life-cycle management and monitoring tools to ensure that identity and authorization are properly handled throughout an organization. Derek should invest in a capable IAM system and ensure that it is configured to use appropriate workflows and to generate the logs and reports that he needs. EDR systems are endpoint detection and response tools and are used to protect against compromise by advanced attackers.

Jim uses a tool that scans a system for available services and then connects to them to collect banner information to determine what version of the service is running. It then provides a report detailing what it gathers, basing results on service fingerprinting, banner information, and similar details it gathers combined with CVE information. What type of tool is Jim using?

A port scanner

A service validator

A vulnerability scanner

A patch management tool

Answer:
C.  Vulnerability scanners that do not have administrative rights to access a machine or that are not using an agent to scan remote machines to gather information, including fingerprints from responses to queries and connections, banner information from services, and related data. CVE information is Common Vulnerability and Exposure information, or vulnerability information. A port scanner gathers information about what service ports are open, although some port scanners blur the line between port and vulnerability scanners. Patch management tools typically run as an agent on a system to allow them to both monitor patch levels and update the system as needed. Service validation typically involves testing the functionality of a service, not its banner and response patterns.

Emily builds a script that sends data to a web application that she is testing. Each time the script runs, it sends a series of transactions with data that fits the expected requirements of the web application to verify that it responds to typical customer behavior. What type of transactions is she using, and what type of test is this?

Synthetic, passive monitoring

Synthetic, use case testing

Actual, dynamic monitoring

Actual, fuzzing

Answer:
B.  Emily is using synthetic transactions, which can use recorded or generated transactions, and is conducting use-case testing to verify that the application responds properly to actual use cases. Neither actual data nor dynamic monitoring is an industry term. Fuzzing involves sending unexpected inputs to a program to see how it responds. Passive monitoring uses a network tap or other capture technology to allow monitoring of actual traffic to a system or application.

What passive monitoring technique records all user interaction with an application or website to ensure quality and performance?

Client-server testing

Real user monitoring

Synthetic user monitoring

Passive user recording

Answer:
B.  Real user monitoring (RUM) is a passive monitoring technique that records user interaction with an application or system to ensure performance and proper application behavior. RUM is often used as part of a predeployment process using the actual user interface. The other answers are all made up—synthetic monitoring uses simulated behavior, but synthetic user monitoring is not a testing method. Similarly, passive monitoring monitors actual traffic, but passive user recording is not an industry term or technique. Client-server testing merely describes one possible architecture.

Earlier this year, the information security team at Jim's employer identified a vulnerability in the web server that Jim is responsible for maintaining. He immediately applied the patch and is sure that it installed properly, but the vulnerability scanner has continued to incorrectly flag the system as vulnerable. To prevent the issue from being flagged incorrectly in the future, what is the next step?

Uninstall and reinstall the patch.

Ask the information security team to flag the system as patched and not vulnerable to that particular flaw.

Update the version information in the web server's configuration.

Review the vulnerability report and use alternate remediation options.

Answer:
B.  Jim should ask the information security team to flag the issue as resolved if he is sure the patch was installed. Many vulnerability scanners rely on version information or banner information and may flag patched versions if the software provider does not update the information they see. Uninstalling and reinstalling the patch will not change this. Changing the version information may not change all of the details that are being flagged by the scanner and may cause issues at a later date. Reviewing the vulnerability information for a workaround may be a good idea but should not be necessary if the proper patch is installed; it can create maintenance issues later.

Angela wants to test a web browser's handling of unexpected data using an automated tool. What tool should she choose?

Nmap

zzuf

Nessus

Nikto

Answer:
B.  zzuf is the only fuzzer on the list, and zzuf is specifically designed to work with tools like web browsers, image viewers, and similar software by modifying network and file input to applications. Nmap is a port scanner, Nessus is a vulnerability scanner, and Nikto is a web server scanner.

Kara wants to conduct a security audit of her cloud IaaS vendor's systems, infrastructure, and practices. What type of audit is she most likely to be able to conduct?

A third-party audit.

She cannot conduct an audit.

An internal audit.

She may request the vendor's third-party audit results.

Answer:
D.  Most IaaS vendors will not allow customers to conduct an audit of their systems and infrastructure. Kara is likely to be able to obtain third-party audit reports from her vendor, and the major IaaS vendors typically either make these available publicly or to paying or prospective customers. An internal audit will not assess the underlying infrastructure and services, only those that the organization uses.

Why should passive scanning be conducted in addition to implementing wireless security technologies like wireless intrusion detection systems?

It can help identify rogue devices.

It can test the security of the wireless network via scripted attacks.

Their short dwell time on each wireless channel can allow them to capture more packets.

They can help test wireless IDS or IPS systems.

Answer:
A.  Passive scanning can help identify rogue devices by capturing MAC address vendor IDs that do not match deployed devices, by verifying that systems match inventories of organizationally owned hardware by hardware address and by monitoring for rogue SSIDs or connections.

Scripted attacks are part of active scanning rather than passive scanning, and active scanning is useful for testing IDS or IPS systems, whereas passive scanning will not be detected by detection systems. Finally, a shorter dwell time can actually miss troublesome traffic, so balancing dwell time versus coverage is necessary for passive wireless scanning efforts.

Paul is reviewing the approval process for a penetration test and wants to ensure that it has appropriate management review. Who should he ensure has approved the request for a penetration test for a business system?

The change advisory board

Senior management

The systems administrator for the system

The service owner

Answer:
B.  In most organizations, senior management needs to approve penetration tests because of the risk to the organization and the potential impact of the test. In a small number of organizations, the service owner may be able to make this decision, but penetration tests often have broader impacts than a single service, meaning that senior management is the proper path. Change advisory boards approve changes, not penetration tests, and system administrators may be advised of the test but do not have the authority in most organizations to sign off on a penetration test.

What term describes software testing that is intended to uncover new bugs introduced by patches or configuration changes?

Nonregression testing

Evolution testing

Smoke testing

Regression testing

Answer:
D.  Regression testing, which is a type of functional or unit testing, tests to ensure that changes have not introduced new issues. Nonregression testing checks to see whether a change has had the effect it was supposed to, smoke testing focuses on simple problems with impact on critical functionality, and evolution testing is not a software testing technique.

Which of the following tools cannot identify a target's operating system for a penetration tester?

Nmap

Nessus

Nikto

Sqlmap

Answer:
D.  Nmap, Nessus, and Nikto all have OS fingerprinting or other operating system identification capabilities. Sqlmap is designed to perform automated detection and testing of SQL injection flaws and does not provide OS detection.

Susan needs to predict high-risk areas for her organization and wants to use metrics to assess risk trends as they occur. What should she do to handle this?

Perform yearly risk assessments.

Hire a penetration testing company to regularly test organizational security.

Identify and track key risk indicators.

Monitor logs and events using a SIEM device.

Answer:
C.  Key risk indicators are used to tell those in charge of risk management how risky an activity is and how much impact changes are having on that risk profile. Identifying and monitoring key risk indicators can help track high-risk areas earlier in their life cycle. Yearly risk assessments may be a good idea but provide only a point-in-time view, whereas penetration tests may miss out on risks that are not directly security-related. Monitoring logs and events using a SIEM device can help detect issues as they occur but won't necessarily show trends in risk.

What major difference separates synthetic and passive monitoring?

Synthetic monitoring works only after problems have occurred.

Passive monitoring cannot detect functionality issues.

Passive monitoring works only after problems have occurred.

Synthetic monitoring cannot detect functionality issues.

For questions 40–42, please refer to the following scenario. Chris uses the standard penetration testing methodology shown here. Use this methodology and your knowledge of penetration testing to answer questions about tool usage during a penetration test.

Larger View
A circle diagram of standard penetration testing menthod. It begins with planning, followed by information gathering and discovery, vulnerability and scanning, exploitation, and reporting.
Answer:
C.  Passive monitoring works only after issues have occurred because it requires actual traffic. Synthetic monitoring uses simulated or recorded traffic and thus can be used to proactively identify problems. Both synthetic and passive monitoring can be used to detect functionality issues.

What task is the most important during Phase 1, planning?

Building a test lab

Getting authorization

Gathering appropriate tools

Determining if the test is white, black, or gray box

Answer:
B.  Getting authorization is the most critical element in the planning phase. Permission, and the “get-out-of-jail-free card” that demonstrates that organizational leadership is aware of the issues that a penetration test could cause, is the first step in any penetration test. Gathering tools and building a lab, as well as determining what type of test will be conducted, are all important, but nothing should happen without permission.

Which of the following tools is most likely to be used during discovery?

Nessus

John

Nmap

Nikto

Answer:
C.  Discovery can include both active and passive discovery. Port scanning is commonly done during discovery to assess what services the target provides, and nmap is one of the most popular tools used for this purpose. Nessus and Nikto might be used during the vulnerability scanning phase, and john, a password cracker, can be used to recover passwords during the exploitation phase.

Which of these concerns is the most important to address during planning to ensure that the reporting phase does not cause problems?

Which CVE format to use

How the vulnerability data will be stored and sent

Which targets are off-limits

How long the report should be

Answer:
B.  Penetration test reports often include information that could result in additional exposure if they were accidentally released or stolen. Therefore, determining how vulnerability data should be stored and sent is critical. Problems with off-limits targets are more likely to result in issues during the vulnerability assessment and exploitation phase, and reports should not be limited in length but should be as long as they need to be to accomplish the goals of the test.

What four types of coverage criteria are commonly used when validating the work of a code testing suite?

Input, statement, branch, and condition coverage

Function, statement, branch, and condition coverage

API, branch, bounds, and condition coverage

Bounds, branch, loop, and condition coverage

Answer:
B.  Code coverage testing most frequently requires that every function has been called, that each statement has been executed, that all branches have been fully explored, and that each condition has been evaluated for all possibilities. API, input, and loop testing are not common types of code coverage testing measures.

As part of his role as a security manager, Jacob provides the following chart to his organization's management team. What type of measurement is he providing for them?

Larger View
A graph of time to remedian in days versus number of vulnerabilities. It includes a curve that begins with 50, gradually decreases, and reaches 0 between 0 and 15.
A coverage rate measure

A key performance indicator

A time to live metric

A business criticality indicator

Answer:
B.  Time to remediate a vulnerability is a commonly used key performance indicator for security teams. Time to live measures how long a packet can exist in hops, business criticality is a measure used to determine how important a service or system is to an organization, and coverage rates are used to measure how effective code testing is.

What does using unique user IDs for all users provide when reviewing logs?

Confidentiality

Integrity

Availability

Accountability

Answer:
D.  Unique user IDs provide accountability when paired with auditable logs to provide that a specific user took any given action. Confidentiality, availability, and integrity can be provided through other means like encryption, systems design, and digital signatures.

Which of the following is not an interface that is typically tested during the software testing process?

APIs

Network interfaces

UIs

Physical interfaces

Answer:
B.  Application programming interfaces (APIs), user interfaces (UIs), and physical interfaces are all important to test when performing software testing. Network interfaces are not part of the typical list of interfaces tested in software testing.

Alan's organization uses the Security Content Automation Protocol (SCAP) to standardize its vulnerability management program. Which component of SCAP can Alan use to reconcile the identity of vulnerabilities generated by different security assessment tools?

OVAL

XCCDF

CVE

SCE

Answer:
C.  The Common Vulnerabilities and Exposures (CVE) database provides a consistent reference for identifying security vulnerabilities. The Open Vulnerability and Assessment Language (OVAL) is used to describe the security condition of a system. The Extensible Configuration Checklist Description Format (XCCDF) is used to create security checklists in a standardized fashion. The Script Check Engine (SCE) is designed to make scripts interoperable with security policy definitions.

Susan is reviewing software testing coverage data and sees the information shown here. What can she determine about this testing process? (Select all answers that apply.)

Larger View
A bar graph dpeicts the software test for four test. It includes two shaded bars for excluded and failed test. In test 1 and 3. excluded test have maximum ranges. In test 2 failed test while in test 4, excluded test have maximum ranges.
The testing does not have full coverage.

Test 4 completed with no failures.

Test 2 failed to run successfully.

The testing needs to be run a fifth time.

Answer:
B, C.  Test 2's total failure is likely due to a failed test run, but the tests overall show continued improvement with full success in test 4. At this point, most testing processes would consider the testing complete. This does not show coverage, and there is no reason to run a fifth run if the fourth test was successful.

Which of the following strategies is not a reasonable approach for remediating a vulnerability identified by a vulnerability scanner?

Install a patch.

Use a workaround fix.

Update the banner or version number.

Use an application layer firewall or IPS to prevent attacks against the identified vulnerability.

Answer:
C.  Simply updating the version that an application provides may stop the vulnerability scanner from flagging it, but it won't fix the underlying issue. Patching, using workarounds, or installing an application layer firewall or IPS can all help to remediate or limit the impact of the vulnerability.

During a penetration test, Selah calls her target's help desk claiming to be the senior assistant to an officer of the company. She requests that the help desk reset the officer's password because of an issue with his laptop while traveling and persuades them to do so. What type of attack has she successfully completed?

Zero knowledge

Help-desk spoofing

Social engineering

Black box

Answer:
C.  Selah's social engineering attack succeeded in persuading a staff member at the help desk to change a password for someone who they not only couldn't see but who they couldn't verify actually needed their password reset. Black box and zero knowledge are both terms describing penetration tests without information about the organization or system, and help-desk spoofing is not an industry term.

In this image, what issue may occur due to the log handling settings?

Larger View
A screenshot of a log properties and application. Subscrition tab is selected above. It provides options for application name, log path, log size, created, modified, and accessed. The maximum log size is set to 20480.
Source: Microsoft Corporation

Log data may be lost when the log is archived.

Log data may be overwritten.

Log data may not include needed information.

Log data may fill the system disk.

Answer:
D.  The menu shown will archive logs when they reach the maximum size allowed (20 MB). These archives will be retained, which could fill the disk. Log data will not be overwritten, and log data should not be lost when the data is archived. The question does not include enough information to determine if needed information may not be logged.

Which of the following is not a hazard associated with penetration testing?

Application crashes

Denial of service

Blackouts

Data corruption

Answer:
C.  Penetration tests typically do not involve blackouts. Application crashes, denial of service due to system, network, or application failures, and even data corruption can all be hazards of penetration tests.

Which NIST special publication covers the assessment of security and privacy controls?

800-12

800-53A

800-34

800-86

Answer:
B.  NIST SP 800-53A is titled “Assessing Security and Privacy Controls in Federal Information Systems and Organizations: Building Effective Assessment Plans” and covers methods for assessing and measuring controls. NIST 800-12 is an introduction to computer security, 800-34 covers contingency planning, and 800-86 is the “Guide to Integrating Forensic Techniques into Incident Response.”

Michelle wants to assess her organization's disaster recovery readiness. What type of test could she run to most effectively assess readiness without the potential for disruption?

Conduct a tabletop exercise.

Conduct a failover test.

Conduct a simulation.

Conduct a plan review.

Answer:
C.  Simulations are the most complete test that can be conducted without the risk that a full failover test creates. Michelle should conduct a simulation to validate as much of her organization's plan as possible. Tabletop exercises and plan reviews provide less complete coverage.

Lucca wants to conduct an audit of a hybrid cloud environment. What potential challenge should he identify for his management team?

On-premises audits are difficult to complete.

Hybrid audits cannot be conducted by third parties.

Underlying cloud infrastructure may not be auditable.

There are no differences between hybrid and cloud audits.

Answer:
C.  Hybrid environment audits involve the complexity of both cloud and on-premises audits. That means that the underlying cloud infrastructure may not be auditable, although Lucca's organization's use and configuration of the cloud will be. On-premises audits are not any more challenging to complete than other audits, hybrid audits can be conducted by third parties, and hybrid audits include both on-premises and cloud auditing challenges and requirements as they are not the same as a cloud-only audit.

If Kara's primary concern is preventing administrative connections to the server, which port should she block?

22

80

443

1433

Answer:
A.  Port 22 is used by the Secure Shell (SSH) protocol for administrative connections. If Kara wants to restrict administrative connections, she should block access on this port. Port 80 is used for HTTP, 443 for HTTPS, and 1433 for Microsoft SQL.

During a third-party audit, Jim's company receives a finding that states, “The administrator should review backup success and failure logs on a daily basis and take action in a timely manner to resolve reported exceptions.” What potential problem does this finding indicate?

Administrators will not know if the backups succeeded or failed.

The backups may not be properly logged.

The backups may not be usable.

The backup logs may not be properly reviewed.

Answer:
C.  The audit finding indicates that the backup administrator may not be monitoring backup logs and taking appropriate action based on what they report, thus resulting in potentially unusable backups. Issues with review, logging, or being aware of the success or failure of backups are less important than not having usable backups.

Jim is helping his organization decide on audit standards for use throughout their international organization. Which of the following is not an IT standard that Jim's organization is likely to use as part of its audits?

COBIT

SSAE-18

ITIL

ISO 27001

Answer:
C.  ITIL, which originally stood for IT Infrastructure Library, is a set of practices for IT service management and is not typically used for auditing. The Control Objectives for Information and Related Technology (COBIT), ISO 27001, and the Statement on Standards for Attestation Engagements number 18 (SSAE-18) are all used for auditing.

Nicole wants to conduct a standards-based audit of her organization. Which of the following is commonly used to describe common requirements for information systems?

IEC

COBIT

FISA

DMCA

Answer:
B.  COBIT, the Control Objectives for Information and Related Technologies, is commonly used as an audit framework for evaluating the governance and management of enterprise IT in an organization. The DMCA is the Digital Millennium Copyright Act, IEC is the International Electrotechnical Commission that defines standards for electrotechnology, and FISA is the Federal Intelligence Surveillance Act, not an audit standard.

Kelly's team conducts regression testing on each patch they release. What key performance measure should they maintain to measure the effectiveness of their testing?

Time to remediate vulnerabilities

A measure of the rate of defect recurrence

A weighted risk trend

A measure of the specific coverage of their testing

Answer:
B.  Kelly's team is using regression testing, which is intended to prevent the recurrence of issues. This means measuring the rate of defect recurrence is appropriate for their work. Time to remediate vulnerabilities is associated with activities such as patching, rather than preparing the patch, whereas a weighted risk trend is used to measure risk over time to an organization. Finally, specific coverage may be useful to determine if they are fully testing their effort, but regression testing is more specifically covered by defect recurrence rates.

Which of the following types of code review is not typically performed by a human?

Software inspections

Pair programming

Static program analysis

Software walk-throughs

For questions 62–64, please refer to the following scenario:

Susan is the lead of a quality assurance team at her company. The team has been tasked with the testing for a major release of their company's core software product.

Answer:
C.  Static program reviews are typically performed by an automated tool. Program understanding, program comprehension, pair programming, software inspections, and software walk-throughs are all human-centric methods for reviewing code.

Susan's team of software testers are required to test every code path, including those that will be used only when an error condition occurs. What type of testing environment does her team need to ensure complete code coverage?

White box

Gray box

Black box

Dynamic

Answer:
A.  To fully test code, a white-box test is required. Without full visibility of the code, error conditions or other code could be missed, making a gray-box or black-box test an inappropriate solution. Using dynamic testing that runs against live code could also result in some conditions being missed due to sections of code not being exposed to typical usage.

As part of the continued testing of their new application, Susan's quality assurance team has designed a set of test cases for a series of black-box tests. These functional tests are then run, and a report is prepared explaining what has occurred. What type of report is typically generated during this testing to indicate test metrics?

A test coverage report

A penetration test report

A code coverage report

A line coverage report

Answer:
A.  A test coverage report measures how many of the test cases have been completed and is used as a way to provide test metrics when using test cases. A penetration test report is provided when a penetration test is conducted—this is not a penetration test. A code coverage report covers how much of the code has been tested, and a line coverage report is a type of code coverage report, both of which cannot be created in a black-box test since the code is not accessible to testers.

As part of their code coverage testing, Susan's team runs the analysis in a nonproduction environment using logging and tracing tools. Which of the following type of code issues is most likely to be missed during testing due to this change in the operating environment?

Improper bounds checking

Input validation

A race condition

Pointer manipulation

Answer:
C.  The changes from a testing environment with instrumentation inserted into the code and the production environment for the code can mask timing-related issues like race conditions. Bounds checking, input validation, and pointer manipulation are all related to coding issues rather than environmental issues and are more likely to be discoverable in a test environment.

Robin recently conducted a vulnerability scan and found a critical vulnerability on a server that handles sensitive information. What should Robin do next?

Patching

Reporting

Remediation

Validation

Answer:
D.  Once a vulnerability scanner identifies a potential problem, validation is necessary to verify that the issue exists. Reporting, patching, or other remediation actions can be conducted once the vulnerability has been confirmed.

The automated code testing and integration that Andrea ran as part of her organization's CI/CD pipeline errored out. What should Andrea do with the code if the company needs the code to go live immediately?

Manually bypass the test.

Review error logs to identify the problem.

Rerun the test to see if it works.

Send the code back to the developer for a fix.

Answer:
B.  While handling errors and exceptions can be something of an art, the first thing to do in circumstances like these is to review error logs and notifications to try to find out what went wrong. From there, Andrea can make a decision to remediate a problem, send the code back for a fix, or take another action. She might even opt to send the code forward if the error occurred after testing was completed and was with the process flow or another noncritical element, but would do so only if she was absolutely certain that was the case.

Michelle wants to compare vulnerabilities she has discovered in her data center based on how exploitable they are, if exploit code exists, and how hard they are to remediate. What scoring system should she use to compare vulnerability metrics like these?

CSV

NVD

VSS

CVSS

Answer:
D.  The Common Vulnerability Scoring System (CVSS) includes metrics and calculation tools for exploitability, impact, how mature exploit code is, and how vulnerabilities can be remediated, as well as a means to score vulnerabilities against users' unique requirements. NVD is the National Vulnerability Database, CSV is short for comma-separated values, and Visual SourceSafe (VSS) is an irrelevant term related to software development rather than vulnerability management.

During a port scan of his network, Alex finds that a number of hosts respond on TCP ports 80, 443, 515, and 9100 in offices throughout his organization. What type of devices is Alex likely discovering?

Web servers

File servers

Wireless access points

Printers

Answer:
D.  Network-enabled printers often provided services via TCP 515 and 9100 and have both nonsecure and secure web-enabled management interfaces on TCP 80 and 443. Web servers, access points, and file servers would not typically provide service on the LPR and LPD ports (515 and 9100).

Nikto, Burp Suite, and Wapiti are all examples of what type of tool?

Web application vulnerability scanners

Code review tools

Vulnerability scanners

Port scanners

Answer:
A.  Nikto, Burp Suite, and Wapiti are all web application vulnerability scanners, tools designed specifically to scan web servers and applications. While they share some functionality with broader vulnerability scanners and port scanning tools, they have a narrower focus and typically have deeper capabilities than vulnerability scanners.

Frank's team is testing a new API that his company's developers have built for their application infrastructure. Which of the following is not a common API issue that you would expect Frank's team to find?

Improper encryption

Object-level authorization issues

User authentication issues

Lack of rate limiting

Answer:
A.  APIs typically transfer data for web applications via HTTPS, meaning that the API itself is not responsible for encryption. If Frank's team discovers that TLS is not enabled, they will need to work with the infrastructure or systems administration team to ensure that TLS is enabled and in use rather than making API changes. Authorization for object access, authentication weaknesses, and rate limiting are all common API issues. If you're not familiar with the types of issues you might encounter in APIs, you can read more about them in the OWASP API security top 10 at https://owasp.org/API-Security/editions/2023/en/0x11-t10.

Jim is working with a penetration testing contractor who proposes using Metasploit as part of her penetration testing effort. What should Jim expect to occur when Metasploit is used?

Systems will be scanned for vulnerabilities.

Systems will have known vulnerabilities exploited.

Services will be probed for buffer overflow and other unknown flaws.

Systems will be tested for zero-day exploits.

Answer:
B.  Metasploit is an exploitation package that is designed to assist penetration testers. A tester using Metasploit can exploit known vulnerabilities for which an exploit has been created or can create their own exploits using the tool. While Metasploit provides built-in access to some vulnerability scanning functionality, a tester using Metasploit should primarily be expected to perform actual tests of exploitable vulnerabilities. Similarly, Metasploit supports creating buffer overflow attacks, but it is not a purpose-built buffer overflow testing tool, and of course, testing systems for zero-day exploits doesn't work unless they have been released.

Susan needs to ensure that the interactions between the components of her e-commerce application are all handled properly. She intends to verify communications, error handling, and session management capabilities throughout her infrastructure. What type of testing is she planning to conduct?

Misuse case testing

Fuzzing

Regression testing

Interface testing

Answer:
D.  Susan is conducting interface testing. Interface testing involves testing system or application components to ensure that they work properly together. Misuse case testing focuses on how an attacker might misuse the application and would not test normal cases. Fuzzing attempts to send unexpected input and might be involved in interface testing, but it won't cover the full set of concerns. Regression testing is conducted when testing changes and is used to ensure that the application or system functions as it did before the update or change.

Jim is designing his organization's log management systems and knows that he needs to carefully plan to handle the organization's log data. Which of the following is not a factor that Jim should be concerned with?

The volume of log data

A lack of sufficient log sources

Data storage security requirements

Network bandwidth

Answer:
B.  Not having enough log sources is not a common consideration in log management system design, although it may be a worry for security managers who can't capture the data they need. Log management system designs must take into account the volume of log data and the network bandwidth it consumes, the security of the data, and the amount of effort required to analyze the data.

Ryan's organization wants to ensure that proper account management is occurring but does not have a central identity and access management tool in place. Ryan has a limited amount of time to do his verification process. What is his best option to test the account management process as part of an internal audit?

Validate all accounts changed in the past 90 days.

Select high-value administrative accounts for validation.

Validate all account changes in the past 180 days.

Validate a random sample of accounts.

Answer:
D.  Random sampling of accounts is the recommended best practice if all accounts cannot be validated. Selecting only recently changed accounts will not identify long-term issues or historic issues, and checking only high-value accounts will not show if there are issues or bad practices with other account types.

When a Windows system is rebooted, what type of log is generated?

Error

Warning

Information

Failure audit

Answer:
C.  Rebooting a Windows machine results in an information log entry. Windows defines five types of events: errors, which indicate a significant problem; warnings, which may indicate future problems; information, which describes successful operation; success audits, which record successful security accesses; and failure audits, which record failed security access attempts.

During a review of access logs, Alex notices that Michelle logged into her workstation in New York at 8 a.m. daily, but then she was recorded as logging into her department's main web application shortly after 3 a.m. daily. What common logging issue has Alex likely encountered?

Inconsistent log formatting

Modified logs

Inconsistent timestamps

Multiple log sources

Answer:
C.  Inconsistent timestamps are a common problem, often caused by improperly set time zones or due to differences in how system clocks are set. In this case, a consistent time difference often indicates that one system uses local time, and the other is using Greenwich mean time (GMT). Logs from multiple sources tend to cause problems with centralization and collection, whereas different log formats can create challenges in parsing log data. Finally, modified logs are often a sign of intrusion or malicious intent.

What type of vulnerability scan accesses configuration information from the systems it is run against as well as information that can be accessed via services available via the network?

Authenticated scans

Web application scans

Unauthenticated scans

Port scans

Answer:
A.  Authenticated scans use a read-only account to access configuration files, allowing more accurate testing of vulnerabilities. Web application scans, unauthenticated scans, and port scans don't have access to configuration files unless they are inadvertently exposed.

Brian has discovered a vulnerability in a website and has notified the company that owns the website about the issue. What has he done?

A penetration test

Ethical disclosure

A web application test

OSINT

For questions 79–80, please refer to the following scenario:

Ben's organization has begun to use STRIDE to assess its software and has identified threat agents and the business impacts that these threats could have. Now they are working to identify appropriate controls for the issues they have identified.

Answer:
B.  Notifying third parties of security issues and vulnerabilities in a confidential manner to allow them to address the issues is considered ethical disclosure. There is not enough information in the question to determine how it was found, and disclosure is not necessarily part of either penetration tests or application tests. How the information as found is not listed, so OSINT is not a useful answer either.

Ben's team is attempting to categorize a transaction identification issue that is caused by using a symmetric key shared by multiple servers. What STRIDE category should this fall into?

Information disclosure

Denial of service

Tampering

Repudiation

Answer:
D.  Since a shared symmetric key could be used by any of the servers, transaction identification problems caused by a shared key are likely to involve a repudiation issue. If encrypted transactions cannot be uniquely identified by a server, they cannot be proved to have come from a specific server.

Ben wants to use a third-party service to help assess denial-of-service attack vulnerabilities due to the amount of traffic during denial-of-service attacks. What type of engagement should he suggest to his organization?

A social engineering engagement

A penetration test

Load or stress testing

Testing using a fuzzer

Answer:
C.  Ben should engage a company that can perform a load or stress test to validate how the application performs under both expected and extreme loads so that he knows what a denial-of-service attack based on load will look like. Social engineering does not test the ability of sites to handle load, and penetration testers may conduct denial-of-service attacks but typically do not. Fuzzers send random input to test how applications handle unexpected input rather than relying on extreme load. They might help test for flaws that could result in a denial-of-service condition, but the question specifically asks about load-based conditions, not software flaws.

Chris is troubleshooting an issue with his organization's SIEM reporting. After analyzing the issue, he believes that the timestamps on log entries from different systems are inconsistent. What protocol can he use to resolve this issue?

SSH

FTP

TLS

NTP

Answer:
D.  The Network Time Protocol (NTP) allows the synchronization of system clocks with a standardized time source. The Secure Shell (SSH) protocol provides encrypted administrative connections to servers. The File Transfer Protocol (FTP) is used for data exchange. Transport Layer Security (TLS) is an encryption process used to protect information in transit over a network.

Ryan is considering the use of fuzz testing in his web application testing program. Which one of the following statements about fuzz testing should Ryan consider when making his decision?

Fuzzers only find complex faults.

Testers must manually generate input.

Fuzzers may not fully cover the code.

Fuzzers can't reproduce errors.

Answer:
C.  Fuzz testers are capable of automatically generating input sequences to test an application. Therefore, testers do not need to manually generate input, although they may do so if they want. Fuzzers can reproduce errors (and thus, “fuzzers can't reproduce errors” is not an issue) but typically don't fully cover the code—code coverage tools are usually paired with fuzzers to validate how much coverage was possible. Fuzzers are often limited to simple errors because they won't handle business logic or attacks that require knowledge from the application user.

Ken is designing a testing process for software developed by his team. He is designing a test that verifies that every line of code was executed during the test. What type of analysis is Ken performing?

Branch coverage

Condition coverage

Function coverage

Statement coverage

For questions 84–86, please refer to the following scenario. During a port scan, Ben uses nmap's default settings and sees the following results.

Larger View
An output page displays Nmap scan report for 192.168.184.130. It provides a list of port and state service. Finally I P address scanned in 54.69 seconds.
Answer:
D.  Statement coverage tests verify that every line of code was executed during the test. Branch coverage verifies that every if statement was executed under all if and else conditions. Condition coverage verifies that every logical test in the code was executed under all sets of inputs. Function coverage verifies that every function in the code was called and returns results.

If Ben is conducting a penetration test, what should his next step be after receiving these results?

Connect to the web server using a web browser.

Connect via Telnet to test for vulnerable accounts.

Identify interesting ports for further scanning.

Use sqlmap against the open databases.

Answer:
C.  After scanning for open ports using a port scanning tool like nmap, penetration testers will identify interesting ports and then conduct vulnerability scans to determine what services may be vulnerable. This will perform many of the same activities that connecting via a web server will and will typically be more useful than trying to manually test for vulnerable accounts via Telnet. Sqlmap would typically be used after a vulnerability scanner identifies additional information about services, and the vulnerability scanner will normally provide a wider range of useful information.

Based on the scan results, what operating system (OS) was the system that was scanned most likely running?

Windows Desktop

Linux

Network device

Windows Server

Answer:
B.  The system is likely a Linux system. The system shows X11, as well as login, shell, and nfs ports, all of which are more commonly found on Linux systems than Windows systems or network devices. This system is also very poorly secured; many of the services running on it should not be exposed in a modern secure network.

Ben's manager expresses concern about the coverage of his scan. Why might his manager have this concern?

Ben did not test UDP services.

Ben did not discover ports outside the “well-known ports.”

Ben did not perform OS fingerprinting.

Ben tested only a limited number of ports.

Answer:
D.  Nmap scans only 1000 TCP and UDP ports by default, including ports outside the 0–1024 range of “well-known” ports. By using the defaults for nmap, Ben missed 64,535 ports. OS fingerprinting won't cover more ports but would have provided a best guess of the OS running on the scanned system.

Lucca is reviewing his organization's disaster recovery process data and notes that the MTD for the business's main website is two hours. What does he know about the RTO for the site when he does testing and validation?

It needs to be less than two hours.

It needs to be at least two hours.

The MTD is too short and needs to be longer.

The RTO is too short and needs to be longer.

Answer:
A.  When Lucca reviews the recovery time objective (RTO) data, he needs to ensure that the organization can recover from an outage in less than two hours based on the maximum tolerable downtime (MTD) of two hours.

Diana has engaged third-party auditors and wants to release an audit attestation to third parties without including details of the audit. What type of SSAE 18 SOC report should she request?

SOC 1

SOC 2

SOC 3

SOC 4

Answer:
C.  Diana should request a SOC 3 report, which is intended for distribution to third parties. They include the auditor's opinions and management assertions, along with information about the service organization. SOC 3 reports are specifically intended for external release, unlike SOC 1 (financial reporting) and SOC 2 (confidentiality, security, and privacy) engagements. SOC 4 was made up for the question.

While reviewing the software testing output for her organization's new application, Madhuri notices that the application has produced errors that included directory and file information shown to the web application tester. What issue should she include in her report about the application?

It does not perform proper exception handling.

The software does not handle misuse case testing properly.

Debugging statements need to be removed.

The code was not fully tested due to errors.

Answer:
A.  Showing end users error information about the code, particularly with directory and file information included, means that the application does not perform proper exception handling. Errors should be logged or noted in a way that the administrator can handle, but end users (and attackers!) should not see that information. The software may be handling misuse properly, as the problem does not note if this was due to normal testing or misuse testing. There is no information about debugging code causing the output, and test coverage was not noted in the question.

What action might a pen tester perform to identify potential exploitable services to gain an initial foothold in a network?

Data gathering

Port scanning

Getting permission

Planning

Answer:
B.  Port scanning is the first step toward identifying potentially exploitable services. Data gathering is used to acquire information to prepare for port scanning and other activities. Permission and planning are not used to identify exploitable services but are critical to the overall process.

The president of Josh's company is concerned about a significant increase in cryptographic malware that is impacting other companies in their industry. She has asked John to ensure that the company's data will be recoverable if malware strikes and encrypts their production systems. What process does Josh need to undertake to be able to tell her that the company is covered?

Encrypt all sensitive data.

Hash all of the organization's data to detect cryptographic malware.

Perform backup verification.

Use anti-encryption technology to prevent the malware from encrypting drives.

Answer:
C.  Validating that the organization has secure and usable backups is Josh's best answer. In case a system is affected by cryptographic malware, it's important to have reliable backups that are not encrypted by the malware. This requires keeping your backup systems separate from your main systems and potentially implementing version control so that your unencrypted backups are not overwritten by encrypted ones that become inaccessible. Encrypting sensitive data won't stop attackers from re-encrypting it, making it inaccessible. Hashing to detect the attack won't stop it or make it possible to recover, and anti-encryption technology does not exist.

Joanna is her organization's CISO, and in her security operations oversight role she wants to ensure that management oversight is happening for security-related changes. What system should she focus on to track this type of data in most organizations?

The SIEM system

The IPS system

The CMS tool

The ITSM tool

Answer:
D.  IT service management, or ITSM, tools include change management and thus the type of approvals and review processes that Joanna is looking for. A SIEM helps with security logs and events, an IPS looks for intrusions and unwanted traffic, and a CMS is a content management tool.

Henry wants to validate that his backups are working. Which of the following options is the best way for him to ensure that the backups will be useful in a true disaster recovery scenario?

Periodically restore a random file to ensure that the backups are working.

Review configurations and settings on a regular schedule to validate backup settings.

Review the backup logs to ensure no errors are occurring.

Regularly perform full restores from backups to validate their success.

Answer:
D.  All of these are useful parts of a backup strategy, but performing full restores from backups on a regular basis is the best option listed. If regular restores work, then individual files will be recoverable, but individual files may not show larger issues with backups. Configuration and setting reviews are important but will not validate the backups themselves, and error messages can indicate problems but won't demonstrate intact logs either.

What type of vulnerabilities will not be found by a vulnerability scanner?

Local vulnerabilities

Service vulnerabilities

Zero-day vulnerabilities

Vulnerabilities that require authentication

Answer:
C.  Vulnerability scanners cannot detect vulnerabilities for which they do not have a test, plug-in, or signature. Signatures often include version numbers, service fingerprints, or configuration data. They can detect local vulnerabilities as well as those that require authentication if they are provided with credentials, and of course, they can detect service vulnerabilities.

Jacinda wants to measure the effectiveness of her security training as one of her security metrics. Which of the following measures are the most useful for assessing the effectiveness of security awareness training? (Select all that apply.)

How many people took the training

The level of security awareness before and after the training

The length of the training in hours

The number of training events each individual attended this year

Answer:
A, B.  The number of staff who took a given training and the average change in their awareness from before the training to after the training can provide insight into how many trained staff you have and how impactful the training was. Over time, this will allow you to determine if your training is helping and if awareness is increasing. The length of the training does not assess its impact; in addition, the number of events each individual attended does not mean that staff are becoming more aware.

Elaine has discovered a previously unknown critical vulnerability in a product that her organization uses. Her organization has a strong commitment to ethical disclosure, and Elaine wants to follow common ethical disclosure practices. What should she do first?

Build an in-house remediation or control and then publicly disclose the vulnerability to prompt the vendor to patch it quickly.

Build an in-house remediation or control and then notify the vendor of the issue.

Notify the vendor and give them a reasonable amount of time to fix the issue.

Publicly disclose the vulnerability so that the vendor will patch it in an appropriate amount of time.

For questions 97–99, please refer to the following scenario. NIST Special Publication 800-115, the Technical Guide to Information Security Testing and Assessment, provides NIST's process for penetration testing. Use this image as well as your knowledge of penetration testing to answer the questions.

Larger View
A floe diagram depicts the process for penetration test. It begins with planning, followed by discovery, attack, and finally reporting.
Source: NIST SP 800-115 / Public Domain.

Answer:
C.  Ethical (or responsible) disclosure norms include notifying the vendor and providing them with a reasonable amount of time to remediate the issue. Public disclosures before notifying the vendor or in a short period of time are considered unethical in most circumstances. While this time frame varies, 90 to 120 days is not uncommon across the industry due to the complexity of software and other technologies.

Which of the following is not a part of the discovery phase?

Hostname and IP address information gathering

Service information capture

Dumpster diving

Privilege escalation

Answer:
D.  Privilege escalation occurs during the attack phase of a penetration test. Host and service information gathering, as well as activities like dumpster diving that can provide information about the organization, its systems, and security, are all part of the discovery phase.

NIST specifies four attack phase steps: gaining access, escalating privileges, system browsing, and installing additional tools. Once attackers install additional tools, what phase will a penetration tester typically return to?

Discovery

Gaining access

Escalating privileges

System browsing

Answer:
B.  Once additional tools have been installed, penetration testers will typically use them to gain additional access. From there they can further escalate privileges, search for new targets or data, and, once again, install more tools to allow them to pivot further into infrastructure or systems.

Which of the following is not a typical part of a penetration test report?

A list of identified vulnerabilities

All sensitive data that was gathered during the test

Risk ratings for each issue discovered

Mitigation guidance for issues identified

Answer:
B.  Penetration testing reports often do not include the specific data captured during the assessment, as the readers of the report may not be authorized to access all of the data, and exposure of the report could result in additional problems for the organization. A listing of the issues discovered, risk ratings, and remediation guidance are all common parts of a penetration test report.

Alex is using nmap to perform port scanning of a system, and he receives three different port status messages in the results. Match each of the numbered status messages with the appropriate lettered description. You should use each item exactly once.

Status message:

Open

Closed

Filtered

Description:

The port is accessible on the remote system, but no application is accepting connections on that port.

The port is not accessible on the remote system.

The port is accessible on the remote system, and an application is accepting connections on that port.

Answer:
The status messages match with the descriptions as follows:

Open: C. The port is accessible on the remote system, and an application is accepting connections on that port.

Closed: B. The port is not accessible on the remote system.

Filtered: A. The port is accessible on the remote system, but no application is accepting connections on that port.
