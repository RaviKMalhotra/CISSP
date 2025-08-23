# Domain 2 - Asset Security

Chapter 2: Asset Security (Domain 2)
SUBDOMAINS
2.1 Identify and classify information and assets
2.2 Establish information and asset handling requirements
2.3 Provision information and assets securely
2.4 Manage data lifecycle
2.5 Ensure appropriate asset retention (e.g., End of Life (EOL), End of Support)
2.6 Determine data security controls and compliance requirements
Angela wants to implement data security controls that are part of the NIST 800-53 Security and Privacy controls. As part of the process, she works to determine which controls are appropriate to her organization's business processes and data handling needs. What term best describes the action that she has performed?

Scoping

Bounds checking

Data stewardship

Tailoring

Answer:
A.  Scoping is the process of determining which controls are appropriate to an organization, environment, or implementation. Bounds checking is the process of making sure that data does not overflow a variable. Data stewards provide oversight and data governance. Tailoring modifies controls to fit a specific situation or need.

Control Objectives for Information and Related Technology (COBIT) is a framework for information technology (IT) management and governance. Which data management role is most likely to select and apply COBIT to balance the need for security controls against business requirements?

Business owners

Data processors

Data owners

Data stewards

Answer:
A.  Business owners have to balance the need to provide value with regulatory, security, and other requirements. This makes the adoption of a common framework like COBIT attractive. Data owners are more likely to ask that those responsible for control selection identify a standard to use. Data processors are required to perform specific actions under regulations like the EU GDPR. Finally, in many organizations, data stewards are internal roles that oversee how data is used.

Nadia's company is operating a hybrid cloud environment with some on-site systems and some cloud-based systems. She has satisfactory monitoring on-site but needs to apply security policies to both the activities her users engage in and to report on exceptions with her growing number of cloud services. What type of tool is best suited to this purpose?

A NGFW

A CASB

An IDS

A SOAR

Answer:
B.  The best option for Nadia is a cloud access security broker (CASB). A CASB is designed to sit between a cloud environment and the users who use it, and it provides monitoring and policy enforcement capabilities. A next-generation firewall (NGFW), an intrusion detection system (IDS), and a security orchestration, automation, and response (SOAR) tool could each provide some insight into what is going on, but they are not purpose built and designed for this like the CASB is. The NGFW and IDS are most likely to provide insight into traffic patterns and behaviors, while the SOAR is primarily intended to monitor other systems and centralize data for response, making it potentially the least useful in this specific scenario.

When media is labeled based on the classification of the data it contains, what rule is typically applied regarding labels?

The data is labeled based on its integrity requirements.

The media is labeled based on the highest classification level of the data it contains.

The media is labeled with all levels of classification of the data it contains.

The media is labeled with the lowest level of classification of the data it contains.

Answer:
B.  Media is typically labeled with the highest classification level of data it contains. This prevents the data from being handled or accessed at a lower classification level. Data integrity requirements may be part of a classification process but don't independently drive labeling in a classification scheme.

Which one of the following administrative processes assists organizations in assigning appropriate levels of security control to sensitive information?

Data classification

Remanence

Transmitting data

Clearing

Answer:
A.  The need to protect sensitive data drives data classification. Classifying data allows organizations to focus on data that needs to be protected rather than spending effort on less important data. Remanence describes data left on media after an attempt is made to remove the data. Transmitting data isn't a driver for an administrative process to protect sensitive data, and clearing is a technical process for removing data from media.

How can a data retention policy help to reduce liabilities?

By ensuring that unneeded data isn't retained

By ensuring that incriminating data is destroyed

By ensuring that data is securely wiped so it cannot be restored for legal discovery

By reducing the cost of data storage required by law

Answer:
A.  A data retention policy can help to ensure that outdated data is purged, removing potential additional costs for discovery. Many organizations have aggressive retention policies to both reduce the cost of storage and limit the amount of data that is kept on hand and discoverable. Data retention policies are not designed to destroy incriminating data, and legal requirements for data retention must still be met.

Staff in an information technology (IT) department who are delegated responsibility for day-to-day tasks hold what data role?

Business owner

User

Data processor

Custodian

Answer:
D.  Custodians are delegated the role of handling day-to-day tasks by managing and overseeing how data is handled, stored, and protected. Data processors are systems used to process data. Business owners are typically project or system owners who are tasked with making sure systems provide value to their users or customers.

Helen's company uses a simple data life cycle, as shown here. What stage should come first in the company's data life cycle?

Larger View
A flow chart of a sample data life cycle. It begins with data analysis, followed by data usage, data retention, and data destruction.
Data policy creation

Data labeling

Data collection

Data analysis

Answer:
C.  In a typical data life cycle, collection is the first stage, although some may replace collection with creation. Once collected, data can be analyzed, used, stored, and disposed of at the end of its useful life. Policies may be created at any time, and organizations often have data before they have policies. Labels are added to data during the analysis, usage, or retention cycle.

Ben has been tasked with identifying security controls for systems covered by his organization's information classification system. Why might Ben choose to use a security baseline?

It applies in all circumstances, allowing consistent security controls.

They are approved by industry standards bodies, preventing liability.

They provide a good starting point that can be tailored to organizational needs.

They ensure that systems are always in a secure state.

Answer:
C.  Security baselines provide a starting point to scope and tailor security controls to your organization's needs. They aren't always appropriate to specific organizational needs, they cannot ensure that systems are always in a secure state, and they do not prevent liability.

Megan wants to prepare media to allow for its reuse in an environment operating at the same sensitivity level. Which of the following is the best option to meet her needs?

Clearing

Erasing

Purging

Sanitization

Answer:
A.  Clearing describes preparing media for reuse. When media is cleared, unclassified data is written over all addressable locations on the media. Once that's completed, the media can be reused, although it may be possible to retrieve some of the original data using retrieval tools. Erasing is the deletion of files or media and may not include all of the data on the device or media, making it the worst choice here. Purging is a more intensive form of clearing for reuse in lower-security areas, and sanitization is a series of processes that removes data from a system or media while ensuring that the data is unrecoverable by any means.

Mikayla wants to identify data that should be classified that already exists in her environment. What type of tool is best suited to identifying data like Social Security numbers, credit card numbers, and similar well-understood data formats?

Manual searching

A sensitive data scanning tool

An asset metadata search tool

A SOAR

Answer:
B.  Sensitive data scanning tools are designed to scan for and flag sensitive data types using known formatting and structure. Social Security numbers, credit card numbers, and other regularly structured data that follows known rules can be identified and then addressed as needed. Manual searching is a massive undertaking for an organization with even a relatively small amount of data; asset metadata needs to be set first and would have already been identified; and a SOAR is used to automate incident response and orchestrate security actions.

What issue is common to spare sectors and bad sectors on hard drives as well as overprovisioned space on modern SSDs?

They can be used to hide data.

They can only be degaussed.

They are not addressable, resulting in data remanence.

They may not be cleared, resulting in data remanence.

Answer:
D.  Spare sectors, bad sectors, and space provided for wear leveling on SSDs (overprovisioned space) may all contain data that was written to the space that will not be cleared when the drive is wiped. This is a form of data remanence and is a concern for organizations that do not want data to potentially be accessible. Many wiping utilities deal only with currently addressable space on the drive. SSDs cannot be degaussed, and wear leveling space cannot be reliably used to hide data. These spaces are still addressable by the drive, although they may not be seen by the operating system.

Naomi knows that commercial data is typically classified based on different criteria than government data. Which of the following is not a common criterion for commercial data classification?

Useful lifespan

Data value

Impact to national security

Regulatory or legal requirements

For questions 14–16, please refer to the following scenario:

Your organization regularly handles three types of data: information that it shares with customers, information that it uses internally to conduct business, and trade secret information that offers the organization significant competitive advantages. Information shared with customers is used and stored on web servers, while both the internal business data and the trade secret information are stored on internal file servers and employee workstations.

Answer:
C.  Commercial data classification often takes into account the value of the data, any regulatory or legal requirements that may apply to the data, and how long the data is useful—its life span. The impact to national security is more typically associated with government classification schemes.

The organization leverages memory-resident databases to improve system performance for both customer data and internal business data. What term best describes data that is resident in system memory?

Data at rest

Buffered data

Data in use

Data in motion

Answer:
C.  Data is often considered based on the data state that it is in. Data can be at rest (on a drive or other storage medium), in use and thus in memory or a buffer and often decrypted for use, or in transit over a network. Data that is resident in system memory is considered data in use.

What technique could you use to mark your trade secret information in case it was released or stolen and you need to identify it?

Classification

Symmetric encryption

Watermarks

Metadata

Answer:
C.  A watermark is used to digitally label data and can be used to indicate ownership, as well as to assist a digital rights management (DRM) system in identifying data that should be protected. Encryption would have prevented the data from being accessed if it was lost, while classification is part of the set of security practices that can help make sure the right controls are in place. Finally, metadata is used to label data and might help a data loss prevention system flag it before it leaves your organization.

What type of encryption is best suited for use on the file servers for the proprietary data, and how might you secure the data when it is in motion?

TLS at rest and AES in motion

AES at rest and TLS in motion

VPN at rest and TLS in motion

DES at rest and AES in motion

Answer:
B.  AES is a strong modern symmetric encryption algorithm that is appropriate for encrypting data at rest. TLS is frequently used to secure data when it is in transit. A virtual private network is not necessarily an encrypted connection and would be used for data in motion, while DES is an outdated algorithm and should not be used for data that needs strong security.

What does labeling data allow a DLP system to do?

The DLP system can detect labels and apply appropriate protections based on rules.

The DLP system can adjust labels based on changes in the classification scheme.

The DLP system can modify labels to permit requested actions.

The DLP system can delete unlabeled data.

Answer:
A.  Data loss prevention (DLP) systems can use labels on data to determine the appropriate controls to apply to the data. Most DLP systems won't modify labels in real time and typically don't work directly with firewalls to stop traffic. Deleting unlabeled data would cause big problems for organizations that haven't labeled every piece of data!

Why is it cost effective to purchase high-quality media to contain sensitive data?

Expensive media is less likely to fail.

The value of the data often far exceeds the cost of the media.

Expensive media is easier to encrypt.

More expensive media typically improves data integrity.

Answer:
B.  The value of the data contained on media often exceeds the cost of the media, making more expensive media that may have a longer life span or additional capabilities like encryption support a good choice. While expensive media may be less likely to fail, the reason it makes sense is the value of the data, not just that it is less likely to fail. In general, the cost of the media doesn't have anything to do with the ease of encryption, and data integrity isn't ensured by better media.

Chris is responsible for workstations throughout his company and knows that some of the company's workstations are used to handle both proprietary information and highly sensitive trade secrets. Which option best describes what should happen at the end of their life (EOL) for workstations he is responsible for?

Erasing

Clearing

Sanitization

Destruction

Answer:
D.  Destruction is the most complete method of ensuring that data cannot be exposed, and organizations often opt to destroy either the drive or the entire workstation or device to ensure that data cannot be recovered or exposed. Sanitization is a combination of processes that ensure that data from a system cannot be recovered by any means. Erasing and clearing are both prone to mistakes and technical problems that can result in remnant data and don't make sense for systems that handle proprietary information.

Fred wants to classify his organization's data using common labels: private, sensitive, public, and proprietary. Which of the following should he apply to his highest classification level based on common industry practices?

Private

Sensitive

Public

Proprietary

Answer:
D.  Common practice makes proprietary or confidential data the most sensitive data. Private data is internal business data that shouldn't be exposed but that doesn't meet the threshold for confidential or proprietary data. Sensitive data may help attackers or otherwise create risk and typically refers to any information that isn't public or unclassified, and public data is just that—data that is or can be made public.

What scenario describes data at rest?

Data in an IPsec tunnel

Data in an e-commerce transaction

Data stored on a hard drive

Data stored in RAM

Answer:
C.  Data at rest is inactive data that is physically stored. Data in an IPsec tunnel or part of an e-commerce transaction is data in motion. Data in RAM is ephemeral and is not inactive.

If you are selecting a security standard for a Windows 11 system that processes credit cards, what security standard is your best choice?

Microsoft's Windows 11 security baseline

The CIS Windows 11 baseline

PCI DSS

The NSA Windows 11 Secure Host Baseline

For questions 23–25, please refer to the following scenario:

The Center for Internet Security (CIS) works with subject-matter experts from a variety of industries to create lists of security controls for operating systems, mobile devices, server software, and network devices. Your organization has decided to use the CIS benchmarks for your systems. Answer the following questions based on this decision.

Answer:
C.  The Payment Card Industry Data Security Standard (PCI DSS) provides the set of requirements for credit card processing systems. The Microsoft, NSA, and CIS baseline are all useful for building a Windows 11 security standard, but the PCI DSS standard is a better answer.

The CIS benchmarks are an example of what practice?

Conducting a risk assessment

Implementing data labeling

Implementing proper system ownership

Using security baselines

Answer:
D.  The CIS benchmarks are an example of a security baseline. A risk assessment would help identify which controls were needed, and proper system ownership is an important part of making sure baselines are implemented and maintained. Data labeling can help ensure that controls are applied to the right systems and data.

Adjusting the CIS benchmarks to your organization's mission and your specific IT systems would involve what two processes?

Scoping and selection

Scoping and tailoring

Baselining and tailoring

Tailoring and selection

Answer:
B.  Scoping involves selecting only the controls that are appropriate for your IT systems, while tailoring matches your organization's mission and the controls from a selected baseline. Baselining is the process of configuring a system or software to match a baseline or building a baseline itself. Selection isn't a technical term used for any of these processes.

How should you determine which controls from the baseline should be applied to a given system or software package?

Consult the custodians of the data.

Select based on the data classification of the data it stores or handles.

Apply the same controls to all systems.

Consult the business owner of the process the system or data supports.

Answer:
B.  The controls implemented from a security baseline should match the data classification of the data used or stored on the system. Custodians are trusted to ensure the day-to-day security of the data and should do so by ensuring that the baseline is met and maintained. Business owners often have a conflict of interest between functionality and data security, and of course, applying the same controls everywhere is expensive and may not meet business needs or be a responsible use of resources.

The company that Henry works for operates in the EU and collects data about their customers. They send that data to a third party to analyze and provide reports to help the company make better business decisions. What term best describes the third-party analysis company?

The data controller

The data owner

The data subject

The data processor

Answer:
D.  The third-party company is a data processor—they process data on behalf of Henry's company, which is a data controller. The data is collected about data subjects. Data owners are tasked with making decisions about data, such as who receives access to it and how it is used.

The government defense contractor that Selah works for has recently shut down a major research project and is planning on reusing the hundreds of thousands of dollars of systems and data storage tapes used for the project for other purposes. When Selah reviews the company's internal processes, she finds that she can't reuse the tapes and that the manual says they should be destroyed. Why isn't Selah allowed to degauss and then reuse the tapes to save her employer money?

Data permanence may be an issue.

Data remanence is a concern.

The tapes may suffer from bitrot.

Data from tapes can't be erased by degaussing.

Answer:
B.  Many organizations require the destruction of media that contains data at higher levels of classification. Often the cost of the media is lower than the potential costs of data exposure, and it is difficult to guarantee that reused media doesn't contain remnant data. Tapes can be erased by degaussing, but degaussing is not always fully effective. Bitrot describes the slow loss of data on aging media, while data permanence is a term sometimes used to describe the life span of data and media.

Information maintained about an individual that can be used to distinguish or trace their identity is known as what type of information?

Personally identifiable information (PII)

Personal health information (PHI)

Social Security number (SSN)

Secure identity information (SII)

Answer:
A.  NIST Special Publication 800-122 defines PII as any information that can be used to distinguish or trace an individual's identity, such as name, Social Security number, date and place of birth, mother's maiden name, biometric records, and other information that is linked or linkable to an individual such as medical, educational, financial, and employment information. PHI is health-related information about a specific person, Social Security numbers are issued to individuals in the United States, and SII is a made-up term.

Which of the following information security risks to data at rest would result in the greatest reputational impact on an organization?

Improper classification

Data breach

Decryption

An intentional insider threat

Answer:
B.  Typically, data breaches cause the greatest reputational damage as a result of threats to data at rest. Data at rest with a high level of sensitivity is often encrypted to help prevent this. Decryption is not as significant of a threat if strong encryption is used and encryption keys are well secured. Insider threats are a risk, but the majority of insider threat issues are unintentional rather than intentional, making this risk less likely in most organizations.

Full disk encryption like Microsoft's BitLocker is used to protect data in what state?

Data in transit

Data at rest

Unlabeled data

Labeled data

Answer:
B.  Full disk encryption only protects data at rest. Since it encrypts the full disk, it does not distinguish between labeled and unlabeled data.

The company that Katie works for provides its staff with mobile phones for employee use, with new phones issued every two years. What scenario best describes this type of practice when the phones themselves are still usable and receiving operating system updates?

EOL

Planned obsolescence

EOS

Device risk management

Answer:
C.  This is an example of an end-of-support (EOS) scenario. The company is intentionally ending support and needs to address what happens to the devices next—secure disposal, destruction, or re-sale—depending on data security requirements and policies set by the company. EOL is when a device or software is no longer made or supported, in contrast to end of support, which may be when it is no longer serviced, including via patches, upgrades, or organizational maintenance. Planned obsolescence and device risk management are not terms that are used on the exam.

What is the primary purpose of data classification?

It quantifies the cost of a data breach.

It prioritizes IT expenditures.

It allows compliance with breach notification laws.

It identifies the value of the data to the organization.

Answer:
D.  Classification identifies the value of data to an organization. This can often help drive IT expenditure prioritization and could help with rough cost estimates if a breach occurred, but that's not the primary purpose. Finally, most breach laws call out specific data types for notification rather than requiring organizations to classify data themselves.

Fred's organization allows downgrading of systems for reuse after projects have been finished and the systems have been purged. What concern should Fred raise about the reuse of the systems from his Top Secret classified project for a future project classified as Secret?

The Top Secret data may be commingled with the Secret data, resulting in a need to relabel the system.

The cost of the sanitization process may exceed the cost of new equipment.

The data may be exposed as part of the sanitization process.

The organization's DLP system may flag the new system due to the difference in data labels.

Answer:
B.  Downgrading systems and media is rare due to the difficulty of ensuring that sanitization is complete. The need to completely wipe (or destroy) the media that systems use means that the cost of reuse is often significant and may exceed the cost of purchasing a new system or media. The goal of purging is to ensure that no data remains, so commingling data should not be a concern, nor should the exposure of the data; only staff with the proper clearance should handle the systems! Finally, a DLP system should flag data based on labels, not on the system it comes from.

Which of the following concerns should not be part of the decision when classifying data?

The cost to classify the data

The sensitivity of the data

The amount of harm that exposure of the data could cause

The value of the data to the organization

Answer:
A.  Classification should be conducted based on the value of the data to the organization, its sensitivity, and the amount of harm that could result from exposure of the data. Cost should be considered when implementing controls and is weighed against the damage that exposure would create.

Which of the following is the least effective method of removing data from media?

Degaussing

Purging

Erasing

Clearing

For questions 36–38, please refer to the following scenario:

The healthcare company that Amanda works for handles HIPAA data as well as internal business data, protected health information, and day-to-day business communications. Its internal policy uses the following requirements for securing HIPAA data at rest and in transit:

Classification

Handling Requirements

Confidential (HIPAA)

Encrypt at rest and in transit.

 	
Full disk encryption is required for all workstations.

 	
Files can be sent only in encrypted form, and passwords must be transferred under separate cover.

 	
Printed documents must be labeled with “HIPAA handling required.”

Private (PII)

Encrypt at rest and in transit.

 	
PHI must be stored on secure servers, and copies should not be kept on local workstations.

 	
Printed documents must be labeled with “Private.”

Sensitive (business confidential)

Encryption is recommended but not required.

Public

Information can be sent unencrypted.

Answer:
C.  Erasing, which describes a typical deletion process in many operating systems, typically removes only the link to the file and leaves the data that makes up the file itself. The data will remain in place but not indexed until the space is needed and it is overwritten. Degaussing works only on magnetic media, but it can be quite effective on it. Purging and clearing both describe more elaborate removal processes.

What encryption technology would be appropriate for HIPAA documents in transit?

BitLocker

DES

TLS

SSL

Answer:
C.  TLS is a modern encryption method used to encrypt and protect data in transit. BitLocker is a full-disk encryption technology used for data at rest. DES and SSL are both outdated encryption methods and should not be used for data that requires high levels of security.

Amanda's employer asks Amanda to classify patient data that is not medical data but that includes data such as phone numbers and addresses. The company's data owner believes that exposure of the data could cause damage (but not exceptional damage) to the organization. How should Amanda classify the data?

Public

Sensitive

Private

Confidential

Answer:
C.  We know that the data classification will not be the top-level classification of Confidential because the loss of the data would not cause severe damage and is not medical data covered by HIPAA. This means we have to choose between private (PHI) and sensitive (confidential). Calling this private due to the patient's personally identifiable information fits the classification scheme, giving us the correct answer.

What technology could Amanda's employer implement to help prevent confidential data from being emailed out of the organization?

DLP

IDS

A firewall

UDP

Answer:
A.  A data loss prevention (DLP) system or software is designed to identify labeled data or data that fits specific patterns and descriptions to help prevent it from leaving the organization. An IDS is designed to identify intrusions. Although some IDS systems can detect specific types of sensitive data using pattern matching, they have no ability to stop traffic. A firewall uses rules to control traffic routing, while UDP is a network protocol.

Jacob's organization uses the U.S. government's data classification system, which includes Top Secret, Secret, Confidential, and Unclassified ratings (from most sensitive to least). Jacob encounters a system that contains Secret, Confidential, and Top Secret data. How should it be classified?

Top Secret

Confidential

Secret

Mixed classification

Answer:
A.  When data is stored in a mixed classification environment, it is typically classified based on the highest classification of data included. In this case, the U.S. government's highest classification is Top Secret. Mixed classification is not a valid classification in this scheme.

Elle is planning her organization's asset retention efforts and wants to establish when the company will remove assets from use. Which of the following is typically the last event in a manufacturer or software provider's life cycle?

End of life

End of support

End of sales

General availability

Answer:
B.  The end of support of a device or product typically occurs after the end of life and end of sales. Support may continue for a period of months or even years, but eventually support stops too. General availability is found during the main part of a life cycle, rather than at the end, and helps note when the product is out of testing and can be acquired or used by customers or others instead of specific groups like beta testers or early release partners.

Alice has been asked to ensure that her organization's controls assessment procedures match the specific systems that the company uses. What activity best matches this task?

Asset management

Compliance

Scoping

Tailoring

Answer:
D.  Tailoring ensures that assessment methods are appropriate to the systems, services, and other assets that are being validated and is the best answer here. Scoping is a related term and involves setting the boundaries of security control implementations. Asset management involves how assets are overseen throughout their life cycle, and compliance is a broad term that describes ensuring that regulations, contractual terms, or other requirements are met.

Chris is responsible for his organization's security standards and has guided the selection and implementation of a security baseline for Windows PCs in his organization. How can Chris most effectively make sure that the workstations he is responsible for are being checked for compliance and that settings are being applied as necessary?

Assign users to spot-check baseline compliance.

Use Microsoft Group Policy.

Create start-up scripts to apply policy at system start.

Periodically review the baselines with the data owner and system owners.

Answer:
B.  Group Policy provides the ability to monitor and apply settings in a security baseline. Manual checks by users and using start-up scripts provide fewer reviews and may be prone to failure, while periodic review of the baseline won't result in compliance being checked.

Frank is reviewing his company's data life cycle and wants to place appropriate controls around the data collection phase. Which of the following ensures that data subjects agree to the processing of their data?

Retention

Consent

Certification

Remanence

Answer:
B.  Providing consent, or agreeing to data collection and use, is important in many data collection scenarios and may be required by law. Remanence occurs when data remains in place, sometimes inadvertently, after it should have been removed or disposed of. Retention is the intentional process of keeping and managing data. Certification is not a data life-cycle process element.

As a DBA, Amy's data role in her organization includes technical implementations of the data policies and standards, as well as managing the data structures that the data is stored in. What data role best fits what Amy does?

Data custodian

Data owner

Data processor

Data user

Answer:
A.  Amy is a data custodian and is responsible for the technical environment, including things like database structures and the technical implementations of data policies. Some organizations may overlap other data roles, including data controllers or data stewards, but the best answer here is a data custodian. Amy is not a data user and is not a data processor who uses the data on behalf of a data controller.

The company Jim works for suffered from a major data breach in the past year and now wants to ensure that it knows where data is located and if it is being transferred, is being copied to a thumb drive, or is in a network file share where it should not be. Which of the following solutions is best suited to tagging, monitoring, and limiting where files are transferred to?

DRM

DLP

A network IPS

Antivirus

Answer:
B.  A data loss prevention (DLP) system can tag, monitor, and limit where files are transferred to. Jim's company may also elect to use digital rights management tools in combination with a data loss prevention system, but DRM controls how data can be used, not where files are transferred to or where they exist at any point in time in most cases. An intrusion prevention system (IPS) may be able to detect files that are being sent across a network but won't stop files from being copied on workstations or thumb drives. Antivirus is not designed for this purpose.

What security measure can provide an additional security control in the event that backup tapes are stolen or lost?

Keep multiple copies of the tapes.

Replace tape media with hard drives.

Use appropriate security labels.

Use AES-256 encryption.

Answer:
D.  Using strong encryption, like AES-256, can help ensure that loss of removable media like tapes doesn't result in a data breach. Security labels may help with handling processes, but they won't help once the media is stolen or lost. Having multiple copies will ensure that you can still access the data but won't increase the security of the media. Finally, using hard drives instead of tape only changes the media type and not the risk from theft or loss.

Joe works at a major pharmaceutical research and development company and has been tasked with writing his organization's data retention policy. As part of its legal requirements, the organization must comply with the U.S. Food and Drug Administration's Code of Federal Regulations Title 21. To do so, it is required to retain records with electronic signatures. Why would a signature be part of a retention requirement?

It ensures that someone has reviewed the data.

It provides confidentiality.

It ensures that the data has been changed.

It validates who approved the data.

Answer:
D.  Electronic signatures, as used in this rule, prove that the signature was provided by the intended signer. Electronic signatures as part of the FDA code are intended to ensure that electronic records are “trustworthy, reliable, and generally equivalent to paper records and handwritten signatures executed on paper.” Signatures cannot provide confidentiality or integrity and don't ensure that someone has reviewed the data.

Susan wants to manage her data's life cycle based on retention rules. What technique can she use to ensure that data that has reached the end of its life cycle can be identified and disposed of based on her organization's disposal processes?

Rotation

DRM

DLP

Tagging

Answer:
D.  Tags that include information about the life span of the data and when it has expired can help with life-cycle management processes, part of data maintenance for organizations. Tags can be as simple as timestamps, or they can include additional metadata like the data type, creator, or purpose that can help inform the retention and disposal process. Rotation of files like logs is commonly done to limit how much space they take up, but rotation itself does not address disposal requirements and information that would guide the disposal process. DRM, or digital rights management, and DLP, or data loss prevention, both address data security and use but not disposal.

Ben has been asked to scrub data to eliminate any information that is no longer needed by his organization. What phase of the data life cycle is Ben most likely operating in?

Data retention

Data maintenance

Data remanence

Data collection

Answer:
B.  During the data maintenance phase of a typical data life cycle, activities like data scrubbing occur to remove unneeded, incorrect, or out-of-date data. Data retention is not a phase; instead, it is a decision that organizations make based on requirements, laws, or their own needs. Data remanence is also not a phase. Data remanence describes the problem of data that remains after data is removed. Finally, in the data collection phase, data is acquired and may be scrubbed, but the question describes a process occurring after data is no longer needed, not during acquisition.

Steve wants to ensure that assets in his organization are properly secured. What should he do to make sure security practices match the data security requirements for each device in his organization?

Sanitization

Asset tagging

Tailoring

Encryption

Answer:
B.  Asset tagging is used to make sure that individuals working with assets can determine the security level or practices they require. Tailoring adjusts security requirements to organizational needs. Other controls, such as sanitization and encryption, may be required by a specific asset classification but are not sufficient to meet a full range of security requirements.

Alex works for a government agency that is required to meet U.S. federal government requirements for data security. To meet these requirements, Alex has been tasked with making sure data is identifiable by its classification level when it is created to help with data asset inventory processes. What should Alex do to the data?

Classify the data.

Encrypt the data.

Label the data.

Apply DRM to the data.

Answer:
C.  Data labels are crucial to identify the classification level of information contained on the media, and labeling data at creation helps to ensure that it is properly handled throughout its life cycle. Digital rights management (DRM) tools provide ways to control how data is used, while encrypting it can help maintain the confidentiality and integrity of the data. Classifying the data is necessary to label it, but it doesn't automatically place a label on the data.

Ben is following the National Institute of Standards and Technology (NIST) Special Publication 800-88 guidelines for sanitization and disposition as shown here. He is handling information that his organization classified as sensitive, which is a moderate security categorization in the NIST model. If the media is going to be sold as surplus, what process does Ben need to follow?

Larger View
A block diagram depicts the guidelines for sanitization and disposition. It includes three keys. 1. Security categorization low, followed by leaving org control, if yes then purge, if no then clear. 2. Security categorization moderate. 3. Security categorization high.
Source: NIST SP 800-88 / Public Domain.

Destroy, validate, document

Clear, purge, document

Purge, document, validate

Purge, validate, document

Answer:
D.  The NIST SP 800-88 process for sanitization and disposition shows that media that will be reused and was classified at a moderate level should be purged and then that purge should be validated. Finally, it should be documented.

What methods are often used to protect data in transit?

Telnet, ISDN, UDP

BitLocker, FileVault

AES, Serpent, IDEA

TLS, VPN, IPsec

Answer:
D.  Data in transit is data that is traversing a network or is otherwise in motion. TLS, VPNs, and IPsec tunnels are all techniques used to protect data in transit. AES, Serpent, and IDEA are all symmetric algorithms, while Telnet, ISDN, and UDP are all protocols. BitLocker and FileVault are both used to encrypt data, but they protect only stored data, not data in transit.

Which one of the following data roles bears ultimate organizational responsibility for data?

System owners

Business owners

Data owners

Mission owners

Answer:
C.  The data owner has ultimate responsibility for data belonging to an organization and is typically the CEO, president, or another senior employee. Business and mission owners typically own processes or programs. System owners own a system that processes sensitive data.

Shandra wants to secure an encryption key. Which location would be the most difficult to protect, if the key was kept and used in that location?

On a local network

On disk

In memory

On a public network

For questions 56–58, please refer to the following scenario:

Chris has recently been hired into a new organization. The organization that Chris belongs to uses the following classification process:

Criteria are set for classifying data.

Data owners are established for each type of data.

Data is classified.

Required controls are selected for each classification.

Baseline security standards are selected for the organization.

Controls are scoped and tailored.

Controls are applied and enforced.

Access is granted and managed.

Answer:
C.  The most difficult location to secure for encryption keys and similar highly sensitive information is in active memory because the data needs to be decrypted to be used. When data is at rest on a drive or in transit via either a local or public network, it can be encrypted until it reaches its destination, and you can use strong encryption in each of those circumstances.

If Chris is one of the data owners for the organization, what steps in this process is he most likely responsible for?

He is responsible for steps 3, 4, and 5.

He is responsible for steps 1, 2, and 3.

He is responsible for steps 5, 6, and 7.

All of the steps are his direct responsibility.

Answer:
A.  Chris is most likely to be responsible for classifying the data that he owns as well as assisting with or advising the system owners on security requirements and control selection. In an organization with multiple data owners, Chris is unlikely to set criteria for classifying data on his own. As a data owner, Chris will also not typically have direct responsibility for scoping, tailoring, applying, or enforcing those controls.

Chris manages a team of system administrators. What data role are they fulfilling if they conduct steps 6, 7, and 8 of the classification process?

They are system owners and administrators.

They are administrators and custodians.

They are data owners and administrators.

They are custodians and users.

Answer:
B.  The system administrators are acting in the roles of data administrators who grant access and will also act as custodians who are tasked with the day-to-day application of security controls. They are not acting as data owners who own the data itself. Typically, system administrators are delegated authority by system owners, such as a department head, and of course they are tasked with providing access to users.

If Chris's company operates in the European Union and has been contracted to handle the data for a third party, what role is his company operating in when it uses this process to classify and handle data?

Business owners

Mission owners

Data processors

Data administrators

For questions 59–62, please refer to the following scenario:

Eric has been put in charge of his organization's IT service management effort, and part of that effort includes creating an inventory of both tangible and intangible assets. As a security professional, you have been asked to provide Eric with security-related guidance on each of the following topics. Your goal is to provide Eric with the best answer from each of the options, knowing that in some cases more than one of the answers could be acceptable.

Answer:
C.  Third-party organizations that process personal data on behalf of a data controller are known as data processors. The organization that they are contracting with would act in the role of the business or mission owners, and others within Chris's organization would have the role of data administrators, granting access as needed to the data based on their operational procedures and data classification.

Eric needs to identify all of the active systems and devices on the network. Which of the following techniques will give him the most complete list of connected devices?

Query Active Directory for a list of all computer objects.

Perform a port scan of all systems on the network.

Ask all staff members to fill out a form listing all of their systems and devices.

Use network logs to identify all connected devices and track them down from there.

Answer:
D.  While it can be a lot of work, the most complete inventory of active systems and devices can be created by determining what is connected to the network and then finding those assets. Port scans can help to find some systems, but firewalls and other security solutions can prevent systems from being discovered. Staff may not know about all of the systems and devices on the network or may presume that someone else will provide information about shared resources such as printers, security cameras, or other devices. Active Directory is unlikely to contain all devices, particularly if an inventory is needed!

Eric knows that his inventory is accurate only at the moment it was completed. How can he best ensure that it remains up-to-date?

Perform a point-in-time query of network-connected devices and update the list based on what is found.

Ensure that procurement and acquisition processes add new devices to the inventory before they are deployed.

Require every employee to provide an updated inventory of devices they are responsible for on a quarterly basis.

Manually verify every device in service at each organizational location on a yearly basis.

Answer:
B.  In most organizations, changing processes so that new systems and devices are added to inventory before they are deployed is the first step in making sure asset inventories are current. Yearly or quarterly updates are too infrequent for most organizations and will lead to gaps as devices are forgotten.

Eric knows that his organization has more than just physical assets. In fact, his organization's business involves significant intellectual property assets, including designs and formulas. Eric needs to track and inventory those assets as well. How can he most effectively ensure that he can identify and manage data throughout his organization based on its classification or type?

Track file extensions for common data types.

Ensure that data is collected in specific network share locations based on the data type and group that works with it.

Use metadata tagging based on data type or security level.

Automatically tag data by file extension type.

Answer:
C.  Eric should use metadata tagging to allow him to use technical tools like DLP and DRM to handle and track data based on its type and content. File extensions do not reveal data security or type, and relying on network share locations to secure data or inventory will lead to gaps in security as files are moved, copied, or stored locally.

Eric has been tasked with identifying intangible assets but needs to provide his team with a list of the assets they will be inventorying. Which of the following is not an example of an intangible asset?

Patents

Databases

Formulas

Employees

Answer:
D.  Patents, databases, and formulas are all examples of intangible assets. Tangible assets include things like hardware, cables, and buildings. Personnel assets include employees, and most organizations would be quite concerned if their employees were intangible!

Which of the following is not a common requirement for the collection of data under data privacy laws and statutes?

Only data that is needed is collected.

Data should be obtained lawfully and via fair methods.

Data should be collected only with the consent of the individual whose data is being collected.

Data should be collected from all individuals equally.

Answer:
D.  There is no requirement that data collection be equal or equivalent. Instead, data collection statutes and other requirements often require that only required data is collected, that individuals are made aware of the data collection, and that they consent to the collection. Similarly, data should be collected only lawfully and via fair methods.

Susan works in an organization that labels all removable media with the classification level of the data it contains, including public data. Why would Susan's employer label all media instead of labeling only the media that contains data that could cause harm if it was exposed?

It is cheaper to order all prelabeled media.

It prevents sensitive media from not being marked by mistake.

It prevents reuse of public media for sensitive data.

Labeling all media is required by HIPAA.

Answer:
B.  Requiring all media to have a label means that when unlabeled media is found, it should immediately be considered suspicious. This helps to prevent mistakes that might leave sensitive data unlabeled. Prelabeled media is not necessarily cheaper (nor may it make sense to buy!), while reusing public media simply means that it must be classified based on the data it now contains. HIPAA does not have specific media labeling requirements.

Data stored in RAM is best characterized as what type of data?

Data at rest

Data in use

Data in transit

Data at large

Answer:
B.  Data in use is data that is in a temporary storage location while an application or process is using it. Thus, data in memory is best described as data in use or ephemeral data. Data at rest is in storage, while data in transit is traveling over a network or other channel. Data at large is a made-up term.

What issue is the validation portion of the NIST SP 800-88 sample certificate of sanitization (shown here) intended to help prevent?

Larger View
A screenshot displays the certificate of sanitization. It includes options for person performing sanitization, media information, sanitization details, media destination, signature, and validation.
Source: Certificate of Sanitization / NIST / Public Domain.

Destruction

Reuse

Data remanence

Attribution

Answer:
C.  Validation processes are conducted to ensure that the sanitization process was completed, avoiding data remanence. A form like this one helps to ensure that each device has been checked and that it was properly wiped, purged, or sanitized. This can allow reuse, does not prevent destruction, and does not help with attribution, which is a concept used with encryption to prove who created or sent a file.

Why is declassification rarely chosen as an option for media reuse?

Purging is sufficient for sensitive data.

Sanitization is the preferred method of data removal.

It is more expensive than new media and may still fail.

Clearing is required first.

Answer:
C.  Ensuring that data cannot be recovered is difficult, and the time and effort required to securely and completely wipe media as part of declassification can exceed the cost of new media. Sanitization, purging, and clearing may be part of declassification, but they are not reasons that it is not frequently chosen as an option for organizations with data security concerns.

Incineration, crushing, shredding, and disintegration all describe what stage in the life cycle of media?

Sanitization

Degaussing

Purging

Destruction

Answer:
D.  Destruction is the final stage in the life cycle of media and can be done via disintegration, incineration, or a variety of other methods that result in the media and data being nonrecoverable. Sanitization is a combination of processes used when data is being removed from a system or media. Purging is an intense form of clearing, and degaussing uses strong magnetic fields to wipe data from magnetic media.

What term is used to describe information like prescriptions and X-rays?

PHI

Proprietary data

PID

PII

Answer:
A.  PHI is protected health information. Personally identifiable information (PII) is any information that can identify an individual. Proprietary data is information that helps organizations maintain a competitive edge or that they want to keep to their own organization or a controlled set of individuals. PID is not a term used for data classification.

Why might an organization use unique screen backgrounds or designs on workstations that deal with data of different classification levels?

To indicate the software version in use

To promote a corporate message

To promote availability

To indicate the classification level of the data or system

Answer:
D.  Handling requirements and tools include visual indicators like a distinctive screen background and can help employees remember what level of classification they are dealing with and thus the handling requirements that they are expected to follow.

Charles has been asked to downgrade the media used for storage of private data for his organization. What process should Charles follow?

Degauss the drives, and then relabel them with a lower classification level.

Pulverize the drives, and then reclassify them based on the data they contain.

Follow the organization's purging process, and then downgrade and replace labels.

Relabel the media, and then follow the organization's purging process to ensure that the media matches the label.

Answer:
C.  If an organization allows media to be downgraded, the purging process should be followed, and then the media should be relabeled. Degaussing may be used for magnetic media but won't handle all types of media. Pulverizing would destroy the media, preventing reuse, while relabeling first could lead to mistakes that result in media that hasn't been purged entering use.

Which of the following tasks is not performed by a system owner per NIST SP 800-18?

Develops a system security plan

Establishes rules for appropriate use and protection of data

Identifies and implements security controls

Ensures that system users receive appropriate security training

Answer:
B.  The data owner sets the rules for use and protection of data. The remaining options all describe tasks for the system owner, including implementation of security controls.

NIST SP 800-60 provides a process shown in the following diagram to assess information systems. What process does this diagram show?

A triangle diagram depicts the workstation and server and their connetions. A is labeled user workstation, connected by B, internet C, connected by D, and server E.
Selecting a standard and implementing it

Categorizing and selecting controls

Baselining and selecting controls

Categorizing and sanitizing

The following diagram shows a typical workstation and server and their connections to each other and the Internet. For questions 74–76, please refer to this diagram.

Larger View
A process diagram for assessing information system. It begins with process input, followed by identification of infpormation types, selection of provisional impact levels, review provisional impact levels, adjustment information level, assigment of system security category, and process output.
Source: NIST SP 800-60 / Public Domain.

Answer:
B.  In the NIST SP 800-60 diagram, the process determines appropriate categorization levels resulting in security categorization and then uses that as an input to determine controls. Standard selection would occur at an organizational level, while baselining occurs when systems are configured to meet a baseline. Sanitization would require the intentional removal of data from machines or media.

Which letters on this diagram are locations where you might find data at rest?

A, B, and C

C and E

A and E

B, D, and F

Answer:
C.  A and E can both be expected to have data at rest. C, the Internet, is an unknown, and the data can't be guaranteed to be at rest. B, D, and F are all data in transit across network links.

What would be the best way to secure data at points B, D, and F?

AES-256

SSL

TLS

3DES

Answer:
C.  B, D, and F all show network links. Of the answers provided, Transport Layer Security (TLS) provides the best security for data in motion. AES-256 and 3DES are both symmetric ciphers and are more likely to be used for data at rest. SSL has been replaced with TLS and should not be a preferred solution.

What is the best way to secure files that are sent from workstation A via the Internet service (C) to remote server E?

Use AES at rest at point A, and use TLS in transit via B and D.

Encrypt the data files and send them.

Use 3DES and TLS to provide double security.

Use full-disk encryption at A and E, and use SSL at B and D.

Answer:
B.  Sending a file that is encrypted before it leaves means that exposure of the file in transit will not result in a confidentiality breach, and the file will remain secure until decrypted at location E. Since options A, C, and D do not provide any information about what happens at point C, they should be considered insecure, as the file may be at rest at point C in an unencrypted form.

Susan needs to provide a set of minimum security requirements for email. What steps should she recommend for her organization to ensure that the email remains secure?

All email should be encrypted.

All email should be encrypted and labeled.

Sensitive email should be encrypted and labeled.

Only highly sensitive email should be encrypted.

Answer:
C.  Encrypting and labeling sensitive email will ensure that it remains confidential and can be identified. Performing these actions only on sensitive email will reduce the cost and effort of encrypting all email, allowing only sensitive email to be the focus of the organization's efforts. Only encrypting highly sensitive email not only skips labeling but might expose other classifications of email that shouldn't be exposed.

How can a data retention policy reduce liabilities?

By reducing the amount of storage in use

By limiting the number of data classifications

By reducing the amount of data that may need to be produced for lawsuits

By reducing the legal penalties for noncompliance

Answer:
C.  Data retention policies can reduce the number of old logs and other files that may need to be produced during a legal case. That can reduce organizational risk, but retention policies need to be in place well before a legal hold is filed. Reducing storage in use does not reduce liability, but it can reduce financial costs, and data retention policies don't tend to limit the number of classifications in use. Legal penalties are not impacted by a retention policy.

What data role does a system that is used to process data have?

Mission owner

Data owner

Data processor

Custodian

Answer:
C.  Systems used to process data are data processors. Data owners are typically CEOs or other very senior staff, custodians are granted rights to perform day-to-day tasks when handling data, and mission owners are typically program or information system owners.

Which one of the following is not considered PII under U.S. federal government regulations?

Name

Social Security number

Student ID number

ZIP code

Answer:
D.  Personally identifiable information includes any information that can uniquely identify an individual. This would include name, Social Security number, and any other unique identifier (including a student ID number). ZIP code, by itself, does not uniquely identify an individual.

What type of health information is the Health Insurance Portability and Accountability Act required to protect?

PII

PHI

SHI

HPHI

Answer:
B.  Protected health information, or PHI, includes a variety of data in multiple formats, including oral and recorded data, such as that created or received by healthcare providers, employers, and life insurance providers. PHI must be protected by HIPAA. PII is personally identifiable information. SHI and HPHI are both made-up acronyms.

The system that Ian has built replaces data in a database field with a randomized string of characters that remains the same for each instance of that data. What technique has he used?

Data masking

Tokenization

Anonymization

DES

Answer:
B.  Tokenization replaces other data with a random string of characters. These tokens are then matched to the actual values for secure lookups as needed. Anonymization removes all personally identifiable data to ensure that the original subject cannot be identified. Data masking obscures some, but not all, data. Pseudonymization uses a pseudonym or alias to replace other information.

Juanita's company processes credit cards and wants to select appropriate data security standards. What data security standard is she most likely to need to use and comply with?

CC-Comply

PCI-DSS

GLBA

GDPR

Answer:
B.  The Payment Card Industry Data Security Standard, or PCI-DSS, is a credit card industry data security standard that defines how businesses must handle information related to credit cards. CC-Comply was made up for this question. GLBA, or Gramm-Leach-Bliley, modernized financial institution standards, and GDPR is an EU data privacy regulation.

What is the best method to sanitize a solid-state drive (SSD)?

Clearing

Zero fill

Disintegration

Degaussing

For questions 85–87, please refer to the following scenario:

As shown in the following security life-cycle diagram (loosely based on the NIST reference architecture), NIST uses a five-step process for risk management. Using your knowledge of data roles and practices, answer the following questions based on the NIST framework process.

Larger View
A security life-cycle diagram. It includes five steps, begins with categorize system and data, followed by select security controls, implement security controls, assess securoty controls, and finally monitor security.
Answer:
C.  Due to problems with remnant data, the U.S. National Security Agency requires physical destruction of SSDs. This process, known as disintegration, results in very small fragments via a shredding process. Zero fill wipes a drive by replacing data with zeros, degaussing uses magnets to wipe magnetic media, and clearing is the process of preparing media for reuse.

What data role will own responsibility for step 1, the categorization of information systems; to whom will they delegate step 2; and what data role will be responsible for step 3?

Data owners, system owners, custodians

Data processors, custodians, users

Business owners, administrators, custodians

System owners, business owners, administrators

Answer:
A.  The data owner bears responsibility for categorizing information systems and delegates selection of controls to system owners, while custodians implement the controls. Users don't perform any of these actions, while business owners are tasked with ensuring that systems are fulfilling their business purpose.

If the systems that are being assessed all handle credit card information (and no other sensitive data), at what step would the PCI DSS first play an important role?

Step 1

Step 2

Step 3

Step 4

Answer:
B.  PCI DSS provides a set of required security controls and standards. Step 2 would be guided by the requirements of PCI DSS. PCI DSS will not greatly influence step 1 because all of the systems handle credit card information, making PCI DSS apply to all systems covered. Steps 3 and 4 will be conducted after PCI DSS has guided the decisions in step 2.

What data security role is primarily responsible for step 5?

Data owners

Data processors

Custodians

Users

Answer:
C.  Custodians are tasked with the day-to-day monitoring of the integrity and security of data. Step 5 requires monitoring, which is a custodial task. A data owner may grant rights to custodians but will not be responsible for conducting monitoring. Data processors process data on behalf of the data controller, and a user simply uses the data via a computing system.

Susan's organization performs a secure disk wipe process on hard drives before they are sent to a third-party organization to be shredded. What issue is her organization attempting to avoid?

Data retention that is longer than defined in policy

Mishandling of drives by the third party

Classification mistakes

Data permanence

Answer:
B.  Susan's organization is limiting its risk by sending drives that have been sanitized before they are destroyed. This limits the possibility of a data breach if drives are mishandled by the third party, allowing them to be stolen, resold, or simply copied. The destruction of the drives will handle any issues with data remanence, while classification mistakes are not important if the drives have been destroyed. Wiping the data before destruction does not make a meaningful difference for data retention policy concerns. Data permanence and the life span of the data are not important on a destroyed drive.

Mike wants to track hardware assets as devices and equipment are moved throughout his organization. What type of system can help do this without requiring staff to individually check bar codes or serial numbers?

A visual inventory

Wi-Fi MAC address tracking

RFID tags

Steganography

Answer:
C.  RFID tags are a common solution for tracking hardware assets and equipment. They can be queried wirelessly at varying ranges depending on the tags and may be built-in to handheld readers or even included in doorways or arches to track items as they enter or leave a facility. Visual inventory relies on staff checking items, MAC addresses are hardware addresses for networked devices, and not every asset in inventory is likely to have a wireless network capability—or to be on! Steganography is hiding messages in images and doesn't help at all with inventory.

Retaining and maintaining information for as long as it is needed is known as what?

Data storage policy

Data storage

Asset maintenance

Record retention

Answer:
D.  Record retention is the process of retaining and maintaining information for as long as it is needed. A data storage policy describes how and why data is stored, while data storage is the process of actually keeping the data. Asset maintenance is a noninformation-security-related process for maintaining physical assets.

Which of the following activities is not a consideration during data classification?

Who can access the data

What the impact would be if the data was lost or breached

How much the data cost to create

What protection regulations may be required for the data

Answer:
C.  The cost of the data is not directly included in the classification process. Instead, the impact on the organization if the data were exposed or breached is considered. Who can access the data and what regulatory or compliance requirements cover the data are also important considerations.

What type of encryption is typically used for data at rest?

Asymmetric encryption

Symmetric encryption

DES

OTP

Answer:
B.  Symmetric encryption like AES is typically used for data at rest. Asymmetric encryption is often used during transactions or communications when the ability to have public and private keys is necessary. DES is an outdated encryption standard, and OTP is the acronym for onetime password.

Which data role is tasked with applying rights that provide appropriate access to staff members?

Data processors

Business owners

Custodians

Administrators

Answer:
D.  Administrators have the rights to apply the permissions to access and handle data. Custodians are trusted with day-to-day data handling tasks. Business owners are typically system or project owners, and data processors are systems used to process data.

What element of asset security is often determined by identifying an asset's owner?

It identifies the individual(s) responsible for protecting the asset.

It provides a law enforcement contact in case of theft.

It helps establish the value of the asset.

It determines the security classification of the asset.

Answer:
A.  Knowing the asset's owner also tells you who is responsible for protecting the asset or for delegating that task. While asset owners may be law enforcement contacts, this is not a critical item for asset security. It does not directly help you to establish the value of the asset or to set security classification levels for an asset.

Fred is preparing to send backup tapes off-site to a secure third-party storage facility. What steps should Fred take before sending the tapes to that facility?

Ensure that the tapes are handled the same way the original media would be handled based on their classification.

Increase the classification level of the tapes because they are leaving the possession of the company.

Purge the tapes to ensure that classified data is not lost.

Decrypt the tapes in case they are lost in transit.

Answer:
A.  Tapes may be vulnerable to theft or loss in transit. That means tapes that are leaving their normal storage facility should be handled according to the organization's classification schemes and handling requirements. Purging the tapes would cause the loss of data, while increasing the classification level of the tapes does not align with the standard practices for data classification and handling. The tapes should be encrypted rather than decrypted.

Which of the following does not describe data in motion?

Data on a backup tape that is being shipped to a storage facility

Data in a TCP packet

Data in an e-commerce transaction

Data in files being copied between locations

Answer:
A.  The correct answer is the tape that is being shipped to a storage facility. You might think that the tape in shipment is “in motion,” but the concept is that the data is not being accessed and is instead in storage rather than being sent across a network. Data in a TCP packet, in an e-commerce transaction, or in local RAM is in motion and is actively being used.

A new law is passed that would result in significant financial harm to your company if the data that it covers was stolen or inadvertently released. What should your organization do about this?

Select a new security baseline.

Relabel the data.

Encrypt all of the data at rest and in transit.

Review its data classifications and classify the data appropriately.

Answer:
D.  When the value of data changes due to legal, compliance, or business reasons, reviewing classifications and reclassifying the data is an appropriate response. Once the review is complete, data can be reclassified and handled according to its classification level. Simply relabeling the data avoids the classification process and may not result in the data being handled appropriately. Similarly, selecting a new baseline or simply encrypting the data may not handle all of the needs that the changes affecting the data create.

Which of the following data roles are typically found inside of a company instead of as a third-party contracting relationship? (Select all that apply.)

Data owners

Data controllers

Data custodians

Data processors

Answer:
A, B, C.  Data owners, controllers, and custodians are typically found inside of a company, while data processors are typically third parties.

What commercial data classification is most appropriate for data contained on corporate websites?

Private

Sensitive

Public

Proprietary

Answer:
C.  Public data is just that—information that can be made public without any harm to the organization, and in fact, it is often information that the organization wants to make available. Private information should stay private inside of an organization, sensitive data may cause damage to the mission of the organization if exposed, and proprietary or confidential information is the most sensitive data that an organization wants to protect.

Match each of the numbered data elements shown here with one of the lettered categories. You may use the categories once, more than once, or not at all. If a data element matches more than one category, choose the one that is most specific.

Data elements:

Medical records

Trade secrets

Social Security numbers

Driver's license numbers

Categories:

Proprietary data

Protected health information

Personally identifiable information

Answer:
The data elements match with the categories as follows:

Data elements

Medical records: B. PHI

Trade secrets A. Proprietary data

Social Security numbers: C. PII

Driver's license numbers: C. PII

Medical records are an example of protected health information (PHI). Trade secrets are an example of proprietary data. Social Security numbers and driver's license numbers are examples of PII; if they were used in a medical context, they may also be PHI, but this question does not ask you to consider them in that context.

Michelle wants to ensure that her organization's policies are enforced across all of the cloud services that it has adopted. What type of tool would be best suited to ensuring her organization's policies are enforced, regardless of the cloud service her users are accessing?

A SIEM

A DLP

A CASB

A NGFW

Answer:
C.  Cloud access security brokers (CASBs) can be on-site or cloud-based and are security policy enforcement points that operate between users and cloud services. A CASB can provide insight into what users are doing, enforce policies, provide threat protection, and even provide data loss prevention capabilities. An SIEM collects logs and event information as part of security monitoring and event management. A DLP system focuses on data loss prevention and data security but won't address an organization's full set of security policies and practices in the cloud, and NGFWs, or next-generation firewalls, provide a variety of security services but are not specifically designed to implement cloud policy.

Devices in Adam's organization are no longer receiving updates, and hardware support contracts cannot be extended. How should Adam describe the devices that are impacted by this?

End of support

End of development

End of life

End of sales

Answer:
A.  The devices have reached end of support (EOS), and the vendor will no longer provide updates or support for it. End of development occurs when no new software updates or patches are being released. End of life and end of sales often occur at the same time when the vendor no longer sells the device. Support will typically continue even after end of life (EOL).

Gary is responsible for the procurement, management, and life cycle of network devices in his organization. What role best describes him?

Data owner

Asset custodian

Data custodian

Asset owner

Answer:
D.  Asset owners are responsible for assets in an organization, including their procurement, management, and life cycle. Unlike data roles, there are typically fewer asset roles in play, and asset custodian is not a commonly recognized role. Since these are hardware devices, Gary's role is not as a data custodian or owner in the scope of this question.

Jessica has adopted the CIS benchmark for Windows 11 workstations for her organization. She has modified what settings are called for in the benchmark to fit her organization's needs as well. What has she done?

Tailoring

Scoping

Editing

Defining

Answer:
A.  Modifying baselines to better suit an organization is known as tailoring. Scoping occurs when baselines are reviewed to ensure that only controls suited to the environment or system are used. Editing and defining are not terms used on the exam for these activities.

Why is data location a significant concern for data owners, controllers, and custodians?

It prevents the data from being lost.

Geographic location may impact compliance requirements.

Geographic location may drive storage costs.

It ensures that the proper data custodian works with it.

Answer:
B.  Data location, particularly at rest, may drive compliance requirements based on local or national laws. This concern drives the majority of data location concerns. Ensuring data is not lost is a data handling and management practice topic, geographic location may be related to cost but storage media and services drive cost far more than physical location, and data custodians are likely to work with data regardless of location.
