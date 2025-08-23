# Domain 8 - Software Development Security Important Questions

SUBDOMAINS
8.1 Understand and integrate security into the Software Development Life Cycle (SDLC)
8.2 Identify and apply security controls in software development ecosystems
8.3 Assess the effectiveness of software security
8.4 Assess security impact of acquired software
8.5 Define and apply secure coding guidelines and standards
Susan provides a public RESTful API for her organization's data but wants to limit its use to trusted partners. She intends to use API keys. What other recommendation would you give Susan to limit the potential abuse of the service?

Limit request rates.

Force HTTP-only requests.

Avoid tokens due to bandwidth constraints.

Blacklist HTTP methods such as GET, POST, and PUT.

Answer:
A.  Limiting request rates can prevent abuse of APIs like this one. The other suggestions are all poor recommendations. In general, requests should require HTTPS, tokens are used for security using tools like JSON web tokens (JWT), and HTTP methods may be restricted, but GET, POST, and PUT are some of the most common methods used for API access and are far more typically whitelisted.

Darren is conducting a threat-hunting exercise and would like to look for botnet indicators of compromise. Which of the following are common ways that attackers leverage botnets? (Select all that apply.)

Mining cryptocurrency

Conducting brute-force attacks

Scanning for vulnerable systems

Conducting man-in-the-middle attacks

Answer:
A, B, C.  Botnets are used for a wide variety of malicious purposes, including scanning the network for vulnerable systems, conducting brute-force attacks against other systems, mining cryptocurrency, and sending out spam messages. They are not commonly used to conduct man-in-the-middle attacks, which are normally waged through DNS poisoning or similar mechanisms.

Which one of the following statements is not true about code review?

Code review should be a peer-driven process that includes multiple developers.

Code review may be automated.

Code review occurs during the design phase.

Code reviewers may expect to review several hundred lines of code per hour.

Answer:
C.  Code review takes place after code has been developed, which occurs after the design phase of the system's development life cycle (SDLC). Code review may use a combination of manual and automated techniques or rely solely on one or the other. It should be a peer-driven process that includes developers who did not write the code. Developers should expect to complete the review of around 300 lines per hour, on average.

Kathleen is reviewing the Ruby code shown here. What security technique is this code using?

Larger View
A screenshot displays the ruby code script. The first line reads insert new user equals D B dot prepare double quotes insert into users name, user I D, gender, and user type. The second line reads, insert new user dot execute davids, 194567, male, admin.
Parameterization

Typecasting

Gem cutting

Stored procedures

Answer:
A.  This code is an example of parameterization, which can help avoid SQL injection. Note that each parameter has a placeholder, which is then passed to the query.

Jessica is reviewing her organization's change management process and would like to verify that changes to software include acceptance testing. Which process is responsible for achieving this goal?

Request control

Change control

Release control

Configuration control

Answer:
C.  One of the responsibilities of the release control process is ensuring that acceptance testing is performed, to ensure that any alterations to end-user tasks are understood and functional prior to code release. The request control, change control, and configuration control processes do not include acceptance testing.

Ashley is investigating an attack that compromised an account of one of her users. In the attack, the attacker forced the submission of an authenticated request to a third-party site by exploiting trust relationships in the user's browser. What type of attack most likely took place?

XSS

CSRF

SQL injection

Session hijacking

Answer:
B.  Cross-site request forgery (XSRF or CSRF) attacks exploit the trust that sites have in a user's browser by attempting to force the submission of authenticated requests to third-party sites. Session hijacking attacks attempt to steal previously authenticated sessions but do not force the browser to submit requests. A SQL injection directly attacks a database through a web application. Cross-site scripting uses reflected input to trick a user's browser into executing untrusted code from a trusted site.

Arnold is creating a new software package and is making use of the OpenSSL library. What term best describes the library he is using?

Open source

COTS

Third-party

Managed

Answer:
A.  The OpenSSL package is a widely used implementation of TLS encryption that is available as an open-source package. It is not commercial off-the-shelf software (COTS). While it might be developed by third parties, it is more accurate to describe it as open source. The library is available as code for free use, but not as a managed service.

Jaime is a technical support analyst and is asked to visit a user whose computer is displaying the error message shown here. What state has this computer entered?

Larger View
A screenshot displays an error message. It reads page fault in non-paged area and technical information.
Fail open

Irrecoverable error

Memory exhaustion

Fail secure

Answer:
D.  The error message shown in the figure is the infamous “Blue Screen of Death” that occurs when a Windows system experiences a dangerous failure and enters a fail secure state. If the system had “failed open,” it would have continued operation. The error described is a memory fault that is likely recoverable by rebooting the system. There is no indication that the system has run out of usable memory.

Joshua is developing a software threat modeling program for his organization. Which of the following are appropriate goals for the program? (Select all that apply.)

To reduce the number of security-related design flaws

To reduce the number of security-related coding flaws

To reduce the severity of non-security-related flaws

To reduce the number of threat vectors

Answer:
A, B, C.  Software threat modeling is designed to reduce the number of security-related design and coding flaws as well as the severity of other flaws. The developer or evaluator of software has no control over the threat environment, because it is external to the organization.

In the diagram shown here, which is an example of a method?

A table depicts the account details. The first line reads, balance currency = 0, owner = string. The second line reads, add funds deposit-currency, remove funds winthdrawal-currency.
Account

Owner

AddFunds

Balance

Answer:
C.  In the diagram, Account is the name of the class. Owner and Balance are attributes of that class. AddFunds and RemoveFunds are methods of the class.

Wanda is reviewing the application development documentation used by her organization and finds the life-cycle illustration shown here. What application development method is her organization using?

Larger View
A life-cycle diagram. It deals with requirement planning, followed by user design, construction, and cutover.
Waterfall

Spiral

Agile

RAD

Answer:
D.  Rapid Application Development, or RAD, focuses on fast development and the ability to quickly adjust to changing requirements. RAD uses four phases: requirements planning, user design, construction, and cutover.

Which one of the following testing methodologies typically works without access to source code?

Dynamic testing

Static testing

White-box testing

Code review

Answer:
A.  Dynamic testing of software typically occurs in a black-box environment where the tester does not have access to the source code. Static testing, white-box testing, and code review approaches all require access to the source code of the application.

Lucca is analyzing a web application that his organization acquired from a third-party vendor. Lucca determined that the application contains a flaw that causes users who are logged in to be able to take actions they should not be able to in their role. What type of security vulnerability should this be classified as?

Data validation

Session management

Authorization

Error handling

Answer:
C.  Given the list of options here, the root cause is most likely an issue with an authorization check that does not properly limit users to the authorization that they should have. Data validation issues are more likely to allow injection attacks or to allow bad data to be input, while session management issues would allow session hijacking or might actually cause them to be logged in as another user. Finally, error handling would show up as a problem when errors occurred, which this problem does not indicate.

Bobby is investigating how an authorized database user is gaining access to information outside his normal clearance level. Bobby believes that the user is making use of a type of function that summarizes data. What term describes this type of function?

Inference

Polymorphic

Aggregate

Modular

Answer:
C.  Aggregate functions summarize large amounts of data and provide only summary information as a result. When carefully crafted, aggregate functions may unintentionally reveal sensitive information.

Taylor would like to better protect the applications developed by her organization against buffer overflow attacks. Which of the following controls would best provide this protection?

Encryption

Input validation

Firewall

Intrusion prevention system

Answer:
B.  The best protection against buffer overflow attacks is server-side input validation. This technique limits user input to approved ranges of values that fit within allocated buffers. While firewalls and intrusion prevention systems may contain controls that limit buffer overflows, it would be more effective to perform filtering on the application server. Encryption cannot protect against buffer overflow attacks.

Kayla recently completed a thorough risk analysis and mitigation review of the software developed by her team and identified three persistent issues:

Cross-site scripting

SQL injection

Buffer overflows

What is the most significant deficiency in her team's work identified by these issues?

Lack of API security

Improper error handling

Improper or missing input validation

Source code design issues

For questions 17–20, please refer to the following scenario:

Robert is a consultant who helps organizations create and develop mature software development practices. He prefers to use the Software Capability Maturity Model (SW-CMM) to evaluate the current and future status of organizations using both independent review and self-assessments. He is currently working with two different clients.

Acme Widgets is not well organized with its software development practices. It does have a dedicated team of developers who do “whatever it takes” to get software out the door, but it does not have any formal processes.

Beta Particles is a company with years of experience developing software using formal, documented software development processes. It uses a standard model for software development but does not have quantitative management of those processes.

Answer:
C.  Each of these problems is caused by improper or missing input validation and can be resolved by handling inputs properly. In many cases, this can be done using libraries or methods already built into the language or framework that the developer is using.

What phase of the SW-CMM should Robert report as the current status of Acme Widgets?

Defined

Repeatable

Initial

Managed

Answer:
C.  Acme Widgets is clearly in the initial stage of the SW-CMM. This stage is characterized by the absence of formal process. The company may still produce working code, but it does so in a disorganized fashion.

Robert is working with Acme Widgets on a strategy to advance their software development practices. What SW-CMM stage should be their next target milestone?

Defined

Repeatable

Initial

Managed

Answer:
B.  The Repeatable stage is the second stage in the SW-CMM, following the Initial stage. It should be the next milestone goal for Acme Widgets. The Repeatable stage is characterized by basic life cycle management processes.

What phase of the SW-CMM should Robert report as the current status of Beta Particles?

Defined

Repeatable

Optimizing

Managed

Answer:
A.  The Defined stage of the SW-CMM is marked by the presence of basic life cycle management processes and reuse of code. It includes the use of requirements management, software project planning, quality assurance, and configuration management practices.

Robert is also working with Beta Particles on a strategy to advance their software development practices. What SW-CMM stage should be their next target milestone?

Defined

Repeatable

Optimizing

Managed

Answer:
D.  The Managed stage is the fourth stage in the SW-CMM, following the Defined stage. It should be the next milestone goal for Beta Particles. The Managed stage is characterized by the use of quantitative software development measures.

Which one of the following database keys is used to enforce referential integrity relationships between tables?

Primary key

Candidate key

Foreign key

Master key

Answer:
C.  Referential integrity ensures that records exist in a secondary table when they are referenced with a foreign key from another table. Foreign keys are the mechanism used to enforce referential integrity.

Brynn believes that a system in her organization may have been compromised by a macro virus. Which one of the following files is most likely to be the culprit?

projections.doc

command.com

command.exe

loopmaster.exe

Answer:
A.  Macro viruses are most commonly found in office productivity documents, such as Microsoft Word documents that end in the .doc or .docx extension. They are not commonly found in executable files with the .com or .exe extension.

Victor created a database table that contains information on his organization's employees. The table contains the employee's user ID, three different telephone number fields (home, work, and mobile), the employee's office location, and the employee's job title. There are 16 records in the table. What is the degree of this table?

3

4

6

16

Answer:
C.  The degree of a database table is the number of attributes in the table. Victor's table has six attributes: the employee's user ID, home telephone, office telephone, mobile telephone, office location, and job title.

Carrie is analyzing the application logs for her web-based application and comes across the following string:

../../../../../../../../../etc/passwd
What type of attack was likely attempted against Carrie's application?

Command injection

Session hijacking

Directory traversal

Brute-force

Answer:
C.  The string shown in the logs is characteristic of a directory traversal attack where the attacker attempts to force the web application to navigate up the file hierarchy and retrieve a file that should not normally be provided to a web user, such as the password file. The series of “double dots” is indicative of a directory traversal attack because it is the character string used to reference the directory one level up in a hierarchy.

When should a design review take place when following an SDLC approach to software development?

After the code review

After user acceptance testing

After the development of functional requirements

After the completion of unit testing

Answer:
C.  Design reviews should take place after the development of functional and control specifications but before the creation of code. The code review, unit testing, and functional testing all take place after the creation of code and, therefore, after the design review.

Tracy is preparing to apply a patch to her organization's enterprise resource planning system. She is concerned that the patch may introduce flaws that did not exist in prior versions, so she plans to conduct a test that will compare previous responses to input with those produced by the newly patched application. What type of testing is Tracy planning?

Unit testing

Acceptance testing

Regression testing

Vulnerability testing

Answer:
C.  Regression testing is software testing that runs a set of known inputs against an application and then compares the results to those produced by an earlier version of the software. It is designed to capture unanticipated consequences of deploying new code versions prior to introducing them into a production environment.

What term is used to describe the level of confidence that software is free from vulnerabilities, either intentionally designed into the software or accidentally inserted at any time during its life cycle, and that the software functions in the intended manner?

Validation

Accreditation

Confidence interval

Assurance

Answer:
D.  Assurance, when it comes to software, is the level of confidence that software is free from vulnerabilities, either intentionally designed into the software or accidentally inserted at any time during its life cycle, and that the software functions in the intended manner. It is a term typically used in military and defense environments.

Victor recently took a new position at an online dating website and is responsible for leading a team of developers. He realized quickly that the developers are having issues with production code because they are working on different projects that result in conflicting modifications to the production code. What process should Victor invest in improving?

Request control

Release control

Change control

Configuration control

Answer:
C.  The change control process is responsible for providing an organized framework within which multiple developers can create and test a solution prior to rolling it out in a production environment. Request control provides a framework for user requests. Release control manages the deployment of code into production. Configuration control ensures that changes to software versions are made in accordance with the change and configuration management policies.

Tom is assessing security risks related to a database he manages. Examining user access controls, he determines that users have access to individual records in a table that match their clearances, but if they pull multiple records, that collection of facts has a higher classification than the classification of any of those facts standing alone and exceeds the permitted access. What type of issue has Tom identified?

Inference

SQL injection

Multilevel security

Aggregation

Answer:
D.  Aggregation is a security issue that arises when a collection of facts has a higher classification than the classification of any of those facts standing alone. An inference problem occurs when an attacker can pull together pieces of less sensitive information and use them to derive information of greater sensitivity. SQL injection is a web application exploit. Multilevel security is a system control that allows the simultaneous processing of information at different classification levels.

Ron leads a team of software developers who find themselves often re-creating code that performs common functions. What software development tool could he use to best address this situation?

Code repositories

Code libraries

IDEs

DAST

Answer:
B.  Code libraries are packages of reusable functions that may be incorporated into individual development projects. Ron could use libraries to easily share code among his team. Code repositories may be used to manage the distribution and updating of these libraries, but that is a second-order use case, making code libraries the best answer. Integrated development environments (IDEs) are tools used by developers to create software, while dynamic application security testing (DAST) is used to verify the correct implementation of code.

Vivian would like to hire a software tester to come in and evaluate a new web application from a user's perspective. Which of the following tests best simulates that perspective?

Black box

Gray box

Blue box

White box

Answer:
A.  Black-box testing begins with no prior knowledge of the system implementation, simulating a user's perspective. White-box and gray-box testing provide full and partial knowledge of the system, respectively, in advance of the test. Blue boxes are a phone hacking tool and are not used in software testing.

Referring to the database transaction shown here, what would happen if no account exists in the Accounts table with account number 1001?

A screenshot of a database transaction. It reads, begin transaction, update accounts, set balance = balance plus 250, where account number = 1001, update accounts, set balance = balance minus 250, where account number = 2002, and commit transaction.
The database would create a new account with this account number and give it a $250 balance.

The database would ignore that command and still reduce the balance of the second account by $250.

The database would roll back the transaction, ignoring the results of both commands.

The database would generate an error message.

Answer:
B.  In this example, the two SQL commands are indeed bundled in a transaction, but it is not an error to issue an update command that does not match any rows. Therefore, the first command would “succeed” in updating zero rows and not generate an error or cause the transaction to roll back. The second command would then execute, reducing the balance of the second account by $250.

Brandon is a software developer seeking to integrate his software with a popular social media site. The site provides him with software libraries that he can use to better integrate his code as well as other tools that make his work easier. What term best describes the service he is using?

SDK

DLP

IDE

API

Answer:
A.  Software development kits (SDKs) are code libraries and other tools made available to assist developers in creating code. An integrated development environment (IDE) may be a component of an SDK, but it is not necessarily part of every SDK. An application programming interface (API) is a set of functions made available to external developers, but the code does not execute on the users' machine, as would a code library or other SDK tools. Data loss prevention (DLP) capabilities are not a component of software development toolsets.

Kim is troubleshooting an application firewall that serves as a supplement to the organization's network and host firewalls and intrusion prevention system, providing added protection against web-based attacks. The issue the organization is experiencing is that the firewall technology suffers somewhat frequent restarts that render it unavailable for 10 minutes at a time. What configuration might Kim consider to maintain availability during that period at the lowest cost to the company?

High availability cluster

Failover device

Fail open

Redundant disks

Answer:
C.  A fail open configuration may be appropriate in this case. In this configuration, the firewall would continue to pass traffic without inspection while it is restarting. This would minimize downtime, and the traffic would still be protected by the other security controls described in the scenario. Failover devices and high availability clusters would indeed increase availability, but at potentially significant expense. Redundant disks would not help in this scenario because no disk failure is described.

What type of security issue arises when an attacker can deduce a more sensitive piece of information by analyzing several pieces of information classified at a lower level?

SQL injection

Multilevel security

Parameterization

Inference

Answer:
D.  An inference problem occurs when an attacker can pull together pieces of less sensitive information and use them to derive information of greater sensitivity. SQL injection is a web application exploit. Multilevel security is a system control that allows the simultaneous processing of information at different classification levels. Parameterization is a security control used to reduce the likelihood of attacks that rely upon improper user input.

Greg is battling a malware outbreak in his organization. He used specialized malware analysis tools to capture samples of the malware from three different systems and noticed that the code is changing slightly from infection to infection. Greg believes that this is the reason that antivirus software is having a tough time defeating the outbreak. What type of malware should Greg suspect is responsible for this security incident?

Stealth virus

Polymorphic virus

Multipartite virus

Encrypted virus

For questions 37–40, please refer to the following scenario:

<script>alert(‘Alert’);</script>
Answer:
B.  Polymorphic viruses mutate each time they infect a system by making adjustments to their code that assists them in evading signature detection mechanisms. Encrypted viruses also mutate from infection to infection but do so by encrypting themselves with different keys on each device.

What vulnerability definitely exists on Linda's message board?

Cross-site scripting

Cross-site request forgery

SQL injection

Improper authentication

Answer:
A.  The message forum is clearly susceptible to a cross-site scripting (XSS) attack. The code that Linda discovered in the message is a definitive example of an attempt to conduct cross-site scripting, and the alert box that she received demonstrates that the vulnerability exists. The website may also be vulnerable to cross-site request forgery, SQL injection, improper authentication, and other attacks, but there is no evidence of this provided in the scenario.

What was the likely motivation of the user who posted the message on the forum containing this code?

Reconnaissance

Theft of sensitive information

Credential stealing

Social engineering

Answer:
A.  The script that Linda discovered merely pops up a message on a user's screen and does not perform any more malicious action. This type of script, using an alert() call, is commonly used to probe websites for cross-site scripting vulnerabilities.

Linda communicates with the vendor and determines that no patch is available to correct this vulnerability. Which one of the following devices would best help her defend the application against further attack?

VPN

WAF

DLP

IDS

Answer:
B.  Web application firewalls (WAFs) sit in front of web applications and watch for potentially malicious web attacks, including cross-site scripting. They then block that traffic from reaching the web application. An intrusion detection system (IDS) may detect the attack but is unable to take action to prevent it. DLP and VPN solutions are unable to detect web application attacks.

In further discussions with the vendor, Linda finds that they are willing to correct the issue but do not know how to update their software. What technique would be most effective in mitigating the vulnerability of the application to this type of attack?

Bounds checking

Peer review

Input validation

OS patching

Answer:
C.  Input validation verifies that user-supplied input does not violate security conditions and is the most effective defense against cross-site scripting attacks. Bounds checking is a form of input validation, but it is typically used to ensure that numeric input falls within an acceptable range and is not applicable against cross-site scripting attacks. Peer review and OS patching are both good security practices but are unlikely to be effective against a cross-site scripting attack.

Hannah is a software developer working on creating statistical software using the R programming language. She uses the RStudio tool, shown here, to assist her in writing this code. What term best describes this tool?

Larger View
A screenshot of a page displays a code script using R studio tool.
SDK

IDE

API

DLP

Answer:
B.  RStudio is a tool used to assist in the creation of code, otherwise known as an integrated development environment (IDE). Software development kits (SDKs) are code libraries and other tools made available to assist developers in creating code. An application programming interface (API) is a set of functions made available to external developers, but the code does not execute on the users' machine, as would a code library or other SDK tools. Data loss prevention (DLP) capabilities are not a component of software development toolsets.

Which of the following configurations within the Scaled Agile Framework (SAFe) is specifically designed to support enterprises in building and maintaining large integrated solutions with the collaboration of hundreds of practitioners?

Large Solution SAFe

Portfolio SAFe

Essential SAFe

Full SAFe

Answer:
D.  Full SAFe is designed to support enterprises in building and maintaining large integrated solutions with the collaboration of hundreds of practitioners. It provides the most extensive level of guidance, with roles, responsibilities, and activities needed to sustainably deliver complex solutions. Essential SAFe focuses on the basic elements of the framework needed to be agile, Large Solution SAFe is for developing large and complex solutions that do not require the constructs of the portfolio level, and Portfolio SAFe is for aligning enterprise strategy with execution but does not address the complexity of building large solutions that Full SAFe is designed for.

Alan is deploying Java code to a variety of machines in his environment and must install the JVM on those machines first. What term best describes the JVM in this case?

Repository

Change manager

Runtime

Sandbox

Answer:
C.  The JVM is the runtime virtual machine that allows the execution of Java code on a device. The JVM implements the Java sandbox, but that is only one of its many functions. The JVM itself is not a change manager or code repository.

Christine is nearing the final stages of testing a new software package. Which one of the following types of software testing usually occurs last and is executed against test scenarios?

Unit testing

Integration testing

User acceptance testing

System testing

Answer:
C.  User acceptance testing (UAT) is typically the last phase of the testing process. It verifies that the solution developed meets user requirements and validates it against use cases. Unit testing, integration testing, and system testing are all conducted earlier in the process leading up to UAT.

Alexis' organization recently moved to a CI/CD approach for software development where they intend to speed up the deployment of code supporting their website. What is the most reasonable frequency that they can expect to achieve using this type of approach?

Monthly deployments

Weekly deployments

Daily deployments

Hundreds of daily deployments

Answer:
D.  When organizations adopt a continuous integration/continuous delivery (CI/CD) approach to software development, they may deploy code extremely rapidly. In fact, some organizations deploy new code to production hundreds or even thousands of times per day using this approach.

Amber is conducting a threat intelligence project and would like to find a source of information on threats to her organization's web applications. Which of the following organizations is widely considered as the definitive source for information on web-based attack vectors?

ISC2

ISACA

OWASP

Mozilla Foundation

Answer:
C.  The Open Worldwide Application Security Project (OWASP) is widely considered as the most authoritative source on web application security issues. They publish the OWASP Top Ten list that publicizes the most critical web application security issues.

Chris is a software developer, and he is actively writing code for an application. What phase of the Agile process is he in?

Planning

Sprints

Deployment

Testing

Answer:
B.  Chris is in an Agile sprint phase and is likely developing code based on user stories. Planning includes stakeholder stories, as well as design and test case preparation. Testing involves ensuring that the code works properly and meets requirements. Deployment includes the actual deployment of the application, as well as additional verification and testing.

Alyssa's team recently implemented a new system that gathers information from a variety of different log sources, analyzes that information, and then triggers automated playbooks in response to security events. What term best describes this technology?

SIEM

Log repositories

IPS

SOAR

Answer:
D.  Security information and event management (SIEM) systems do correlate information from multiple sources and perform analysis, but they stop short of providing automated playbook responses. That is the realm of security orchestration, automation, and response (SOAR) platforms. Intrusion prevention platforms have a more limited scope, allowing the blocking of traffic based upon analysis performed by the IPS itself. Log repositories simply collect log information and do not perform analysis.

Chris is reviewing the code of an open-source application that he is planning to use in his organization. He finds the code excerpt shown here:

int myarray[10];
myarray[10] = 8;
What type of attack is taking place?

Mismatched data types

Overflow

SQL injection

Covert channel

Answer:
B.  This is an example of a specific type of buffer overflow known as an off-by-one error. The first line of the code defines an array of 10 elements, which would be numbered 0 through 9. The second line of code tries to place a value in the 11th element of the array (remember, array counting begins at 0!), which would cause an overflow.

Which one of the following database issues occurs when one transaction writes a value to the database that overwrites a value that was needed by transactions with earlier precedence?

Dirty read

Incorrect summary

Lost update

SQL injection

Answer:
C.  Lost updates occur when one transaction writes a value to the database that overwrites a value needed by transactions that have earlier precedence, causing those transactions to read an incorrect value. Dirty reads occur when one transaction reads a value from a database that was written by another transaction that did not commit. Incorrect summaries occur when one transaction is using an aggregate function to summarize data stored in a database while a second transaction is making modifications to the database, causing the summary to include incorrect information. SQL injection is a web application security flaw, not a database concurrency problem.

Belinda would like to better protect users of her organization's web application from cookie-stealing attacks. Which one of the following is the most effective control against this type of session hijacking attack?

TLS

Complex session cookies

SSL

Expiring cookies frequently

Answer:
A.  Transport Layer Security (TLS) provides the most effective defense against session hijacking because it encrypts all traffic between the client and server, preventing the attacker from stealing session credentials. Secure Sockets Layer (SSL) also encrypts traffic, but it is vulnerable to attacks against its encryption technology. Complex and expiring cookies are a good idea, but they are not sufficient protection against session hijacking.

In a software configuration management program, what is the primary role of the CAB?

Approve the credentials of developers.

Facilitate lessons learned sessions.

Review and approve/reject code changes.

Prioritize software development efforts.

Answer:
C.  The purpose of the change advisory board (CAB) is to review and then approve or reject proposed code changes. The CAB is not normally involved in the approval of developer credentials, the conduct of lessons learned sessions, or the prioritization of software development efforts.

Which one of the following tools is commonly used by software developers to interact with and manage code that is stored in code repositories?

grep

git

lsof

gcc

Answer:
B.  git is a version management tool that is very commonly used by developers to interact with code repositories, such as those hosted by GitHub. grep is a command-line tool used to search files for specific content. lsof is a command used to list the open files on a system. gcc is a C language compiler used to transform source code into executable code.

While evaluating a potential security incident, Harry comes across a log entry from a web server request showing that a user entered the following input into a form field:

CARROT'&1=1;--
What type of attack was attempted?

Buffer overflow

Cross-site scripting

SQL injection

Cross-site request forgery

Answer:
C.  The single quotation mark in the input field is a telltale sign that this is a SQL injection attack. The single quotation mark is used to escape outside the SQL code's input field, and the text following it is used to directly manipulate the SQL command sent from the web application to the database.

Which one of the following is not an effective control against SQL injection attacks?

Escaping

Client-side input validation

Parameterization

Limiting database permissions

Answer:
B.  Client-side input validation is not an effective control against any type of attack because the attacker can easily bypass the validation by altering the code on the client. Escaping restricted characters prevents them from being passed to the database, as does parameterization. Limiting database permissions prevents dangerous code from executing.

Jason is reviewing the documentation for a software development project and comes across the diagram shown here. What type of diagram is he examining?

A pert chart depicts a sample software development project. 10 is divided into 30 and 20, 30 into 40 and 50 while 20 into 50.
WBS chart

PERT chart

Gantt chart

Wireframe diagram

Answer:
B.  PERT charts use nodes to represent milestones or deliverables and then show the estimated time to move between milestones. Gantt charts use a different format with a row for each task and lines showing the expected duration of the task. Work breakdown structures are an earlier deliverable that divides project work into achievable tasks. Wireframe diagrams are used in application UI design.

In what software testing technique does the evaluator retest a large number of scenarios each time that the software changes to verify that the results are consistent with a standard baseline?

Orthogonal array testing

Pattern testing

Matrix testing

Regression testing

Answer:
D.  Regression testing is performed after developers make changes to an application. It reruns a number of test cases and compares the results to baseline results. Orthogonal array testing is a method for generating test cases based on statistical analysis. Pattern testing uses records of past software bugs to inform the analysis. Matrix testing develops a matrix of all possible inputs and outputs to inform the test plan.

Haley is reviewing code created by her organization for its possible exposure to web application vulnerabilities. Which one of the following conditions may make an application most vulnerable to a cross-site scripting (XSS) attack?

Input validation

Reflected input

Unpatched server

Promiscuous firewall rules

Answer:
B.  Cross-site scripting (XSS) attacks may take advantage of the use of reflected input in a web application where input provided by one user is displayed to another user. Input validation is a control used to prevent XSS attacks. XSS does not require an unpatched server or any firewall rules beyond those permitting access to the web application.

Roger is conducting a software test for a tax preparation application developed by his company. End users will access the application over the web, but Roger is conducting his test on the back end, evaluating the source code on the web server. What type of test is Roger conducting?

White box

Gray box

Blue box

Black box

Answer:
A.  In a white-box test, the tester has access to full implementation details of the system, including source code, prior to beginning the test. In gray-box testing, the tester has partial knowledge. In black-box testing, the tester has no knowledge of the system and tests it from a user perspective. Blue boxes are a phone hacking tool and are not used in software testing.

Which of the following statements is true about heuristic-based antimalware software?

It has a lower false positive rate than signature detection.

It requires frequent definition updates to detect new malware.

It has a higher likelihood of detecting zero-day exploits than signature detection.

It monitors systems for files with content known to be viruses.

Answer:
C.  Heuristic-based antimalware software has a higher likelihood of detecting a zero-day exploit than signature-based methods. Heuristic-based software does not require frequent signature updates because it does not rely upon monitoring systems for the presence of known malware. The trade-off with this approach is that it has a higher false positive rate than signature detection methods.

Martin is inspecting a system where the user reported unusual activity, including disk activity when the system is idle and abnormal CPU and network usage. He suspects that the machine is infected by a virus, but scans come up clean. What malware technique might be in use here that would explain the clean scan results?

File infector virus

MBR virus

Service injection virus

Stealth virus

Answer:
D.  One possibility for the clean scan results is that the virus is using stealth techniques, such as intercepting read requests from the antivirus software and returning a correct-looking version of the infected file. The system may also be the victim of a zero-day attack, using a virus that is not yet included in the signature definition files provided by the antivirus vendor.

Tomas discovers a line in his application log that appears to correspond with an attempt to conduct a directory traversal attack. He believes the attack was conducted using URL encoding. The line reads as follows:

%252E%252E%252F%252E%252E%252Fetc/passwd
What character is represented by the %252E value?

   .

   ,

   ;

   /

Answer:
A.  In URL encoding, the . character is replaced by %252E, and the / character is replaced by %252F. You can see this in the log entry, where the expected pattern of ../../ is replaced by %252E%252E%252F%252E%252E%252F.

An attacker posted a message to a public discussion forum that contains an embedded malicious script that is not displayed to the user but executes on the user's system when read. What type of attack is this?

Persistent XSRF

Nonpersistent XSRF

Persistent XSS

Nonpersistent XSS

Answer:
C.  Attacks where the malicious user tricks the victim's web browser into executing a script through the use of a third-party site are known as cross-site scripting (XSS) attacks. This particular attack is a persistent XSS attack because it remains on the discussion forum until an administrator discovers and deletes it, giving it the ability to affect many users.

Which one of the following is not a principle of the Agile software development process?

Welcome changing requirements, even late in the development process.

Maximizing the amount of work not done is essential.

Clear documentation is the primary measure of progress.

Build projects around motivated individuals.

Answer:
C.  The Agile Manifesto includes 12 principles for software development. Three of those are listed as answer choices: maximizing the amount of work not done is essential, build projects around motivated individuals, and welcome changing requirements throughout the development process. Agile does not, however, consider clear documentation the primary measure of progress. Instead, working software is the primary measure of progress.

Gavin is an internal auditor tasked with examining the change management practices of his organization. He would like to review a series of changes made to a software package to determine whether they were properly documented. Where should he turn for a description of each proposed change?

CAB

RFC

SOAR

SIEM

Answer:
B.  Each change should be the result of a reviewed and approved request for change (RFC). These RFCs may be approved by the change advisory board (CAB). The security information and event management (SIEM) and security orchestration, automation, and response (SOAR) platforms used by the organization would not normally contain information about the change management process.

Neal is working with a DynamoDB database. The database is not structured like a relational database but allows Neal to store data using a key-value store. What type of database is DynamoDB?

Relational database

Graph database

Hierarchical database

NoSQL database

Answer:
D.  A key-value store is an example of a NoSQL database that does not follow a relational or hierarchical model like traditional databases. A graph database is another example of a NoSQL database, but it uses nodes and edges to store data rather than keys and values.

In the transaction shown here, what would happen if the database failed in between the first and second update statements?

BEGIN TRANSACTION

UPDATE accounts
SET balance = balance + 250
WHERE account_number = 1001;

UPDATE accounts
SET balance = balance - 250
WHERE account_number = 2002;

COMMIT TRANSACTION
The database would credit the first account with $250 in funds but then not reduce the balance of the second account.

The database would ignore the first command and only reduce the balance of the second account by $250.

The database would roll back the transaction, ignoring the results of both commands.

The database would successfully execute both commands.

Answer:
C.  A database failure in the middle of a transaction causes the rollback of the entire transaction. In this scenario, the database would not execute either command because doing so would violate the atomicity property of the transaction.

Tareck's organization makes use of a significant amount of COTS software. He recently discovered a significant buffer overflow vulnerability in the code of a COTS software package that is crucial to his business. What is the most likely way that Tareck can get this corrected?

Work with his software development team to modify the code.

Notify the vendor and request a patch.

Deploy an intrusion prevention system.

Update firewall rules.

Answer:
B.  When using commercial off-the-shelf (COTS) software, customers do not generally have access to the source code and must depend upon the vendor to release security patches that correct vulnerabilities. Other controls, such as intrusion prevention systems and firewalls, may be able to help mitigate the issue, depending upon the nature of the flaw, but they will not correct it.

Which one of the following statements is true about software testing?

Static testing works on runtime environments.

Static testing performs code analysis.

Dynamic testing uses automated tools, but static testing does not.

Static testing is a more important testing technique than dynamic testing.

Answer:
B.  Static testing performs code analysis in an offline fashion, without actually executing the code. Dynamic testing evaluates code in a runtime environment. Both static and dynamic testing may use automated tools, and both are important security testing techniques.

David is working on developing a project schedule for a software development effort, and he comes across the chart shown here. What type of chart is this?

Larger View
A gantt chart depicts the development of project schedule for a software development effort. It includes W B S 1 and 2. In W B S 1, activity A is 50% completed, activity B is 75% completed, and others.
Work breakdown structure

Functional requirements

PERT chart

Gantt chart

Answer:
D.  The chart shown in the figure is a Gantt chart, showing the proposed start and end dates for different activities. It is developed based on the work breakdown structure (WBS), which is developed based on functional requirements. Program Evaluation Review Technique (PERT) charts show the project schedule as a series of numbered nodes.

Barry is a software tester who is working with a new gaming application developed by his company. He is playing the game on a smartphone to conduct his testing in an environment that best simulates a normal end user, but he is referencing the source code as he conducts his test. What type of test is Barry conducting?

White box

Black box

Blue box

Gray box

Answer:
D.  In a gray-box test, the tester evaluates the software from a user perspective but has access to the source code as the test is conducted. White-box tests also have access to the source code but perform testing from a developer's perspective. Black-box tests work from a user's perspective but do not have access to source code. Blue boxes are a telephone hacking tool and not a software testing technique.

Miguel recently completed a penetration test of the applications that his organization uses to handle sensitive information. During his testing, he discovered a condition where an attacker can exploit a timing condition to manipulate software into allowing him to perform an unauthorized action. Which one of the following attack types fits this scenario?

SQL injection

Cross-site scripting

Pass the hash

TOC/TOU

Answer:
D.  The Time of Check to Time of Use (TOC/TOU) attack exploits timing differences between when a system verifies authorization and software uses that authorization to perform an action. It is an example of a race condition attack. The other three attacks mentioned do not depend on precise timing.

What part of the security review process are the input parameters shown in the diagram used for?

Larger View
A flow diagram dpeicts the security review process. It deals with configuration input parameters, user input parameters, control input parameters, and back-end input parameters.
SQL injection review

Sprint review

Fagan inspection

Attack surface identification

Answer:
D.  Each of these input parameters makes up part of the attack surface of the application. Attackers may opt to target any of them to attack the code or its supporting infrastructure.

What application security process can be described in these three major steps?

Decomposing the application

Determining and ranking threats

Determining countermeasures and mitigation

Fagan inspection

Threat modeling

Penetration testing

Code review

Answer:
B.  Threat modeling commonly involves decomposing the application to understand it and how it interacts with other components or users. Next, identifying and ranking threats allows you to focus on the threats that should be prioritized. Finally, identifying how to mitigate those threats finishes the process. Once complete, an organization can take action to handle the threats that were identified with appropriate controls.

Which one of the following approaches to failure management is the most conservative from a security perspective?

Fail open

Fail mitigation

Fail clear

Fail closed

Answer:
D.  The fail closed approach prevents any activity from taking place during a system security failure and is the most conservative approach to failure management. Fail open takes the opposite philosophy, allowing all activity in the event of a security control failure. Fail clear and fail mitigation are not failure management approaches.

What software development model is shown here?

Larger View
A sample software development diagram. It deals with determining objectives, alternatives,and constraints, evaluating alternatives, identifying and resolving risks, developing next level product, and planning next phase.
Waterfall

Agile

Lean

Spiral

Answer:
D.  The illustration shows the spiral model of software development. In this approach, developers use multiple iterations of a waterfall-style software development process. This becomes a “loop” of iterations through similar processes. The original waterfall approach does not iterate through the entire process repeatedly. Some variants do allow iteration, but only by allowing movement backward and forward one stage. The Agile approach to software development focuses on iterative improvement and does not follow a rigorous SDLC model. Lean is a process improvement methodology and not a software development model.

Mark is considering replacing his organization's customer relationship management (CRM) solution with a new product that is available in the cloud. This new solution is completely managed by the vendor, and Mark's company will not have to write any code or manage any physical resources. What type of cloud solution is Mark considering?

IaaS

CaaS

PaaS

SaaS

Answer:
D.  In a software-as-a-service solution, the vendor manages both the physical infrastructure and the complete application stack, providing the customer with access to a fully managed application.

Which one of the following change management processes is initiated by users rather than developers?

Change request

Change control

Release control

Design review

Answer:
A.  The request process begins with a user-initiated request for a feature. Change and release control are initiated by developers seeking to implement changes. Design review is a phase of the change approval process initiated by developers when they have a completed design.

Teagan would like to better protect his organization against database inference attacks. Which one of the following techniques is an effective countermeasure against these attacks?

Input validation

Parameterization

Polyinstantiation

Server-side validation

Answer:
C.  Polyinstantiation allows the storage of multiple different pieces of information in a database at different classification levels to prevent attackers from inferring anything about the absence of information. Input validation, server-side validation, and parameterization are all techniques used to prevent web application attacks and are not effective against inference attacks.

Ursula is a government web developer who recently created a public application that offers property records. She would like to make it available for other developers to integrate into their applications. What can Ursula create to make it easiest for developers to call her code directly and integrate the output into their applications?

Object model

Data dictionary

API

Primary key

Answer:
C.  While Ursula may certainly use an object model, data dictionary, and primary key in her development effort, external developers cannot directly use them to access her code. An application programming interface (API) allows other developers to call Ursula's code from within their own without knowing the details of Ursula's implementation.

Nathan recently completed a software development project where he integrated the organization's network operations stack with their development processes. As a result, developers can modify firewall rules from their code on an as-needed basis. What term best describes this ability?

Agile

IaC

SDS

DevOps

Answer:
C.  This is an example of software-defined security (SDS), where security infrastructure may be easily manipulated by code. Answering this question is tricky because several of the other terms are closely related. Software-defined security is an example of infrastructure as code (IaC), but SDS is a more descriptive, and therefore better, answer. SDS is commonly used within an Agile development framework. The DevOps approach links together development and operations but is generally called DevSecOps when it also includes SDS.

TJ is inspecting a system where the user reported a strange error message and the inability to access files. He sees the window shown here. What type of malware should TJ suspect?

Larger View
A screenshot of a page titled crypto Locker. The page has a message box titled personal files are encrypted. It is followed by a list of key points. The page includes a logo along with date and time left.
Service injection

Encrypted virus

SQL injection

Ransomware

Answer:
D.  Messages similar to the one shown here are indicative of a ransomware attack. The attacker encrypts files on a user's hard drive and then demands a ransom, normally paid in Bitcoin, for the decryption key required to restore access to the original content. Encrypted viruses, on the other hand, use encryption to hide themselves from antivirus mechanisms and do not alter other contents on the system.

Charles is developing a mission-critical application that has a direct impact on human safety. Time and cost are less important than correctly functioning software. Which of the following software development methodologies should he choose given these requirements?

Agile

DevOps

Spiral

Waterfall

Answer:
D.  Despite many organizations moving to Agile, DevOps, or other more responsive development methodologies, waterfall remains a strong contender when clear objectives and stable requirements are combined with a need to prevent flaws and to have a high level of control over the development process and output.

Which one of the following types of artificial intelligence attempts to use complex computations to replicate the partial function of the human mind?

Decision support systems

Expert systems

Knowledge bank

Neural networks

Answer:
D.  Neural networks attempt to use complex computational techniques to model the behavior of the human mind. Knowledge banks are a component of expert systems, which are designed to capture and reapply human knowledge. Decision support systems are designed to provide advice to those carrying out standard procedures and are often driven by expert systems.

At which level of the Software Capability Maturity Model (SW-CMM) does an organization introduce basic life-cycle management processes?

Initial

Repeatable

Defined

Managed

Answer:
B.  In level 2, the Repeatable level of the SW-CMM, an organization introduces basic life cycle management processes. Reuse of code in an organized fashion begins, and repeatable results are expected from similar projects. The key process areas for this level include Requirements Management, Software Project Planning, Software Project Tracking and Oversight, Software Subcontract Management, Software Quality Assurance, and Software Configuration Management.

Lucas runs the accounting systems for his company. The morning after an essential employee was fired, systems began mysteriously losing information. Lucas suspects that the fired employee tampered with the systems prior to his departure. What type of attack should Lucas suspect?

Privilege escalation

SQL injection

Logic bomb

Remote code execution

Answer:
C.  The critical fact in this question is that Lucas suspects the tampering took place before the employee departed. This is the signature of a logic bomb: malicious code that lies dormant until certain conditions are met. The other attack types listed here—privilege escalation, SQL injection, and remote code execution—would more likely take place in real time.

Which one of the following principles would not be favored in an Agile approach to software development?

Processes and tools over individuals and interactions

Working software over comprehensive documentation

Customer collaboration over contract negotiations

Responding to change over following a plan

Answer:
A.  The Agile approach to software development embraces four principles. It values individuals and interactions over processes and tools, working software over comprehensive documentation, customer collaboration over contract negotiation, and responding to change over following a plan.

What technique do API developers most commonly use to limit access to an API to authorized individuals and applications?

Encryption

Input validation

API keys

IP filters

Answer:
C.  API developers commonly use API keys to limit access to authorized users and applications. Encryption provides for confidentiality of information exchanged using an API but does not provide authentication. Input validation is an application security technique used to protect against malicious input. IP filters may be used to limit access to an API, but they are not commonly used because it is difficult to deploy an API with IP filters since the filters require constant modification and maintenance as endpoints change.

Reggie recently received a letter from his company's internal auditors scheduling the kickoff meeting for an assessment of his group. Which of the following should Reggie not expect to learn during that meeting?

Scope of the audit

Purpose of the audit

Expected timeframe

Expected findings

Answer:
D.  An audit kickoff meeting should clearly describe the scope and purpose of the audit as well as the expected time frame. Auditors should never approach an audit with any expectations about what they will discover because the findings should be developed based only upon the results of audit examinations.

Which one of the following is the proper order of steps in the waterfall model of software development?

Requirements, Design, Testing, Coding, Maintenance

Requirements, Design, Coding, Testing, Maintenance

Design, Requirements, Coding, Testing, Maintenance

Design, Requirements, Testing, Coding, Maintenance

Answer:
B.  In the waterfall model, the software development process follows five sequential steps that are, in order, Requirements, Design, Coding, Testing, and Maintenance. Note that these phases may be further subdivided. The Requirements phase often begins with System Requirements and then moves on to Software Requirements. The Design phase often begins with Preliminary Design and then moves on to Detailed Design.

Renee is a software developer who writes code in Node.js for her organization. The company is considering moving from a self-hosted Node.js environment to one where Renee will run her code on application servers managed by a cloud vendor. What type of cloud solution is Renee's company considering?

IaaS

CaaS

PaaS

SaaS

Answer:
C.  In a platform-as-a-service solution, the customer supplies application code that the vendor then executes on its own infrastructure.

Tom is writing a software program that calculates the sales tax for online orders placed from various jurisdictions. The application includes a user-defined field that allows the entry of the total sale amount. Tom would like to ensure that the data entered in this field is a properly formatted dollar amount. What technique should he use?

Limit check

Fail open

Fail secure

Input validation

Answer:
D.  Input validation ensures that the data provided to a program as input matches the expected parameters. Limit checks are a special form of input validation that ensure that the value remains within an expected range, but there was no range specified in this scenario. Fail open and fail secure are options when planning for possible system failures.

Brian is helping implement a new software testing methodology for his organization and would like to review the completeness of his toolkit. Which of the following would be considered dynamic application security testing (DAST) tools? (Select all that apply.)

Code review

Fuzzing

Static analysis

Web application vulnerability scanning

Answer:
B, D.  Dynamic application security tools conduct their testing by actually executing the code. This is the case for both fuzzing and web application vulnerability scanning. Code reviews and static analysis packages analyze the code itself but do not execute it, making them static application security testing (SAST) tools.

What approach to technology management integrates the three components of technology management shown in this illustration?

A diagram depicts three components of technology management. It deals with software development, operations, and quality assurance.
Agile

Lean

DevOps

ITIL

Answer:
C.  The DevOps approach to technology management seeks to integrate software development, operations, and quality assurance in a seamless approach that builds collaboration between the three disciplines.

Olivia is conducting a risk analysis of a web application that her organization obtained from a third party and is concerned that it might contain vulnerabilities. Which one of the following activities might she take to best mitigate the risk?

Deploy a WAF.

Implement strong encryption.

Purchase an insurance policy.

Discontinue use of the software.

Answer:
A.  Deploying a web application firewall (WAF) may reduce the likelihood or impact of a web application vulnerability and is, therefore, a good example of risk mitigation. Encryption is also a risk mitigation control, but it is less likely be effective against a web application security flaw. Purchasing an insurance policy is an example of risk transference, not risk mitigation. Discontinuing use of the software is an example of risk avoidance, not risk mitigation.

Which one of the following database concurrency issues occurs when one transaction reads information that was written to a database by a second transaction that never committed?

Lost update

SQL injection

Incorrect summary

Dirty read

Answer:
D.  Dirty reads occur when one transaction reads a value from a database that was written by another transaction that did not commit. Lost updates occur when one transaction writes a value to the database that overwrites a value needed by transactions that have earlier precedence, causing those transactions to read an incorrect value. Incorrect summaries occur when one transaction is using an aggregate function to summarize data stored in a database, while a second transaction is making modifications to the database, causing the summary to include incorrect information. SQL injection is a web application security flaw, not a database concurrency problem.

What software development concept was pioneered by the Defense Department in the 1990s as an effort to bring together diverse product development teams?

Integrated product team

Agile methodology

Scrum approach

User stories

Answer:
A.  The integrated product team (IPT) approach brought together cross-functional teams and was designed by the U.S. Department of Defense in 1995. It was a predecessor to the Agile methodology, which uses tools like the scrum approach and user stories to conduct software development work.

Frank is working to select a new cloud service that will provide block storage for a server being built by his team. What category of cloud service is Frank planning to use?

SaaS

IaaS

FaaS

PaaS

Answer:
B.  Storage is an infrastructure component and, therefore, a block storage service is an example of an infrastructure-as-a-service (IaaS) cloud service. Software-as-a-service (SaaS) models provide full applications managed by the provider. Platform-as-a-service (PaaS) and function-as-a-service (FaaS) approaches allow developers to run their own code on an infrastructure platform managed by the provider.

Match the numbered code testing methods to their lettered definition:

Code testing methods:

Regression testing

Integration testing

Unit testing

System testing

Definitions:

Testing on a complete integrated product

A testing method that focuses on modules or smaller sections of code for testing

A testing method that is used to verify that previously tested software performs the same way after changes are made

A testing method used to validate how software modules work together

Answer:
The code testing methods match to their definitions as follows:

Regression testing: C. A testing method that is used to verify that previously tested software performs the same way after changes are made

Integration testing: D. A testing method used to validate how software modules work together

Unit testing: B. A testing method that focuses on modules or smaller sections of code for testing

System testing: A. Testing on a complete integrated product

Match the following numbered terms to their lettered definitions:

Session hijacking

Cross-site scripting

Cross-site request forgery

SQL injection

An attack that injects a malicious script into otherwise trusted websites

An attack that is designed to execute commands against a database via an insecure web application

An exploitation method that often involves cookies or keys to gain unauthorized access to a computer or service

An attack that forces a user to execute unwanted actions in a website or application they are currently logged into

Answer:
The terms match to their definitions as follows:

Session hijacking: C. An exploitation method that often involves cookies or keys to gain unauthorized access to a computer or service

Cross-site scripting: A. An attack that injects a malicious script into otherwise trusted websites

Cross-site request forgery: D. An attack that forces a user to execute unwanted actions in a website or application they are currently logged into

SQL injection: B. An attack that is designed to execute commands against a database via an insecure web application
