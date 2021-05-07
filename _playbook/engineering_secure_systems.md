---
layout: post
title: Principles for Engineering Secure Systems
author: Adrian Wheldon
date: 2021-04-02
---

## A Baseline for Achieving IT Systems Security

The following principles provide a foundation upon which a more consistent and structured approach to the design, development, and implementation of information security capabilities can be constructed. While the primary focus of these principles is the implementation of technical controls, these principles highlight the fact that to be effective a system security design should also consider non-technical issues such as policy, operational procedures, and user education and training. The principles described here do not apply to all systems at all times. Each principle should be carefully considered throughout the lifecycle of every system. Moreover, because of the constantly changing information system security environment, the principles identified are not considered to be a static, all-inclusive list. Instead, this document is an attempt to present, in a logical fashion, fundamental security principles that can be used in today’s operational environments. As technology improves and security techniques are refined, additions, deletions, and refinement of these security principles will be required.

### Principle 1 - Treat security as an integral part of the overall system design.

Security must be considered in information system design. Experience has shown it to be both difficult and costly to implement security measures properly and successfully after a system has been developed, so it should be integrated fully into the system lifecycle process. This includes establishing security policies, understanding the resulting security requirements, participating in the evaluation of security products, and finally in the engineering, design, implementation, and disposal of the system.



### Principle 2 - Clearly delineate the physical and logical security boundaries governed by associated security policies.

Information technology exists in physical and logical locations, and boundaries exist between these locations. An understanding of what is to be protected from external factors can help ensure adequate protective measures are applied where they will be most effective. Sometimes a boundary is defined by people, information, and information technology associated with one physical location. But this ignores the reality that within a single location many different security policies may be in place, some covering publicly accessible information and some covering sensitive unclassified information. Other times a boundary is defined by a security policy that governs a specific set of information and information technology that can cross physical boundaries. Further complicating the matter is that, many times, a single machine or server may house both public-access and sensitive unclassified information. Therefore, when developing an information system, security boundaries must be considered and communicated in relevant system documentation and security policies.



### Principle 3 - Ensure that developers are trained in how to develop secure software.

Ensure that developers are adequately trained in the development of secure software before developing the system. This includes application of engineering disciplines to design, development, configuration control, and integration and testing.



### Principle 4 - Reduce risk to an acceptable level.

Risk is defined as the combination of (1) the likelihood that a particular threat source will exercise (intentionally exploit or unintentionally trigger) a particular information system vulnerability and (2) the resulting adverse impact on organisational operations, organisational assets, or individuals should this occur. Previously, risk avoidance was a common IT security goal. That changed as the nature of the risk became better understood. Today, it is recognised that elimination of all risk is not cost-effective. A cost-benefit analysis should be conducted for each proposed control. In some cases, the benefits of a more secure system may not justify the direct and indirect costs. Benefits include more than just prevention of monetary loss; for example, controls may be essential for maintaining public trust and confidence. Direct costs include the cost of purchasing and installing a given technology; indirect costs include decreased system performance and additional training. The goal is to enhance mission/business capabilities by mitigating mission/business risk to an acceptable level.



### Principle 5 - Assume that external systems are insecure.

The term information domain arises from the practice of partitioning information resources according to access control, need, and levels of protection required. Organisations implement specific measures to enforce this partitioning and to provide for the deliberate flow of authorised information between information domains. The boundary of an information domain represents the security perimeter for that domain. An external domain is one that is not under your control. In general, external systems should be considered insecure. Until an external domain has been deemed “trusted,” system engineers, architects, and IT specialists should presume the security measures of an external system are different than those of a trusted internal system and design the system security features accordingly.



### Principle 6 - Identify potential trade-offs between reducing risk and increased costs and decrease in other aspects of operational effectiveness.

To meet stated security requirements, a systems designer, architect, or security practitioner will need to identify and address all competing operational needs. It may be necessary to modify or adjust (i.e. trade-off) security goals due to other operational requirements. In modifying or adjusting security goals, an acceptance of greater risk and cost may be inevitable. By identifying and addressing these trade-offs as early as possible, decision makers will have greater latitude and be able to achieve more effective systems.



### Principle 7 - Implement tailored system security measures to meet organisational security goals.

In general, IT security measures are tailored according to an organisation’s unique needs. While numerous factors, such as the overriding mission requirements, and guidance, are to be considered, the fundamental issue is the protection of the mission or business from IT security-related, negative impacts. Because IT security needs are not uniform, system designers and security practitioners should consider the level of trust when connecting to other external networks and internal sub-domains. Recognising the uniqueness of each system allows a layered security strategy to be used – implementing lower assurance solutions with lower costs to protect less critical systems and higher assurance solutions only at the most critical areas.



### Principle 8 - Protect information while being processed, in transit, and in storage.

The risk of unauthorised modification or destruction of data, disclosure of information, and denial of access to data while in transit should be considered along with the risks associated with data that is in storage or being processed. Therefore, system engineers, architects, and IT specialists should implement security measures to preserve, as needed, the integrity, confidentiality, and availability of data, including application software, while the information is being processed, in transit, and in storage.



### Principle 9 - Consider custom products to achieve adequate security.

Designers should recognise that in some instances it will not be possible to meet security goals with systems constructed entirely from Commercial Off The Shelf (COTS) products. In such instances, it will be necessary to augment COTS with non-COTS mechanisms.



### Principle 10 - Protect against all likely classes of “attacks.”

In designing the security controls, multiple classes of “attacks” need to be considered. Those classes that result in unacceptable risk need to be mitigated. Examples of “attack” classes are: Passive monitoring, active network attacks, exploitation by insiders, attacks requiring physical access or proximity, and the insertion of backdoors and malicious code during software development and/or distribution.



### Principle 11 - Where possible, base security on open standards for p0rtability and interoperability.

Most organisations depend significantly on distributed information systems to perform their mission or business. These systems distribute information both across their own organisation and to other organisations. For security capabilities to be effective in such environments, security program designers should make every effort to incorporate interoperability and portability into all security measures, including hardware and software, and implementation practices.



### Principle 12 - Use common language in developing security requirements.

The use of a common language when developing security requirements permits organisations to evaluate and compare security products and features evaluated in a common test environment. When a “common” evaluation process is based upon common requirements or criteria, a level of confidence can be established that ensures product security functions conform to an organisation’s security requirements. The Common Criteria provides a source of common expressions for common needs and supports a common assessment methodology.



### Principle 13 - Design security to allow for regular adoption of new technology, including a secure and logical technology upgrade process.

As mission and business processes and the threat environment change, security requirements and technical protection methods must be updated. IT-related risks to the mission/business vary over time and undergo periodic assessment. Periodic assessment should be performed to enable system designers and managers to make informed risk management decisions on whether to accept or mitigate identified risks with changes or updates to the security capability. The lack of timely identification through consistent security solution re-evaluation and correction of evolving, applicable IT vulnerabilities results in false trust and increased risk. Each security mechanism should be able to support migration to new technology or upgrade of new features without requiring an entire system redesign. The security design should be modular so that individual parts of the security design can be upgraded without the requirement to modify the entire system.



### Principle 14 - Strive for operational ease of use.

The more difficult it is to maintain and operate a security control, the less effective that control is likely to be. Therefore, security controls should be designed to be consistent with the concept of operations and with ease-of-use as an important consideration. The experience and expertise of administrators and users should be appropriate and proportional to the operation of the security control. An organisation must invest the resources necessary to ensure system administrators and users are properly trained. Moreover, administrator and user training costs along with the life-cycle operational costs should be considered when determining the cost-effectiveness of the security control.



### Principle 15 - Implement layered security (Ensure no single point of vulnerability.)

Security designs should consider a layered approach to address or protect against a specific threat or to reduce vulnerability. For example, the use of a packet-filtering router in conjunction with an application gateway and an intrusion detection system combine to increase the work-factor an attacker must expend to successfully attack the system. Adding good password controls and adequate user training improves the system’s security posture even more. The need for layered protections is especially important when COTS products are used. Practical experience has shown that the current state-of-the-art for security quality in COTS products does not provide a high degree of protection against sophisticated attacks. It is possible to help mitigate this situation by placing several controls in series, requiring additional work by attackers to accomplish their goals.



### Principle 16 - Design and operate an IT system to limit damage and to be resilient in response.

Information systems should be resistant to attack, should limit damage, and should recover rapidly when attacks do occur. The principle suggested here recognises the need for adequate protection technologies at all levels to ensure that any potential cyber attack will be countered effectively. There are vulnerabilities that cannot be fixed, those that have not yet been fixed, those that are not known, and those that could be fixed but are not (e.g., risky services allowed through firewalls) to allow increased operational capabilities. In addition to achieving a secure initial state, secure systems should have a well-defined status after failure, either to a secure failure state or via a recovery procedure to a known secure state. Organisations should establish detect and respond capabilities, manage single points of failure in their systems, and implement a reporting and response strategy.



### Principle 17 - Provide assurance that the system is, and continues to be, resilient in the face of expected threats.

Assurance is the grounds for confidence that a system meets its security expectations. These expectations can typically be summarised as providing sufficient resistance to both direct penetration and attempts to circumvent security controls. Good understanding of the threat environment, evaluation of requirement sets, hardware and software engineering disciplines, and product and system evaluations are primary measures used to achieve assurance. Additionally, the documentation of the specific and evolving threats is important in making timely adjustments in applied security and strategically supporting incremental security enhancements.



### Principle 18 - Limit or contain vulnerabilities.

Design systems to limit or contain vulnerabilities. If a vulnerability does exist, damage can be limited or contained, allowing other information system elements to function properly. Limiting and containing insecurities also helps to focus response and reconstitution efforts to information system areas most in need.



### Principle 19 - Isolate public access systems from mission critical resources (e.g. data, processes etc.)

While the trend toward shared infrastructure has considerable merit in many cases, it is not universally applicable. In cases where the sensitivity or criticality of the information is high, organisations may want to limit the number of systems on which that data is stored and isolate them, either physically or logically. Physical isolation may include ensuring that no physical connection exists between an organisation’s public access information resources and an organisation’s critical information. When implementing logical isolation solutions, layers of security services and mechanisms should be established between public systems and secure systems responsible for protecting mission critical resources. Security layers may include using network architecture designs such as demilitarised zones and screened subnets. Finally, system designers and administrators should enforce organisational security policies and procedures regarding use of public access systems.



### Principle 20 - Use boundary mechanisms to separate computing systems and network infrastructures.

To control the flow of information and access across network boundaries in computing and communications infrastructures, and to enforce the proper separation of user groups, a suite of access control devices and accompanying access control policies should be used. Determine the following for communications across network boundaries:

- Required external interfaces.

- Whether information is pushed or pulled.

- Required ports, protocols, and network service.

- Requirements for system information exchanges; for example, trust relationships, database replication services, and domain name resolution processes.



### Principle 21 - Design and implement audit mechanisms to detect unauthorised use and to support incident investigations.

Organisations should monitor, record, and periodically review audit logs to identify unauthorised use and to ensure system resources are functioning properly. In some cases, organisations may be required to disclose information obtained through auditing mechanisms to appropriate third parties, including law enforcement authorities or Freedom of Information (FOI) applicants. Many organisations have implemented consent to monitor policies which state that evidence of unauthorised use (e.g., audit trails) may be used to support administrative or criminal investigations.



### Principle 22 - Develop and exercise contingency or disaster recovery procedures to ensure appropriate availability.

Continuity of operations plans or disaster recovery procedures address continuance of an organisation’s operation in the event of a disaster or prolonged service interruption that affects the organisation’s mission. Such plans should address an emergency response phase, a recovery phase, and a return to normal operation phase. Personnel responsibilities during an incident and available resources should be identified. Contingency and disaster recovery plans do not address every possible scenario or assumption. Rather, it focuses on the events most likely to occur and identifies an acceptable method of recovery. Periodically, the plans and procedures should be exercised to ensure that they are effective and well understood.



### Principle 23 - Strive for simplicity.

The more complex the mechanism, the more likely it may possess exploitable flaws. Simple mechanisms tend to have fewer exploitable flaws and require less maintenance. Further, because configuration management issues are simplified, updating or replacing a simple mechanism becomes a less intensive process.



### Principle 24 - Minimise the system elements to be trusted.

Security measures include people, operations, and technology. Where technology is used, hardware, firmware, and software should be designed and implemented so that a minimum number of system elements need to be trusted in order to maintain protection. Further, to ensure cost-effective and timely certification of system security features, it is important to minimise the amount of software and hardware expected to provide the most secure functions for the system.



### Principle 25 - Implement least privilege.

The concept of limiting access, or "least privilege", is simply to provide no more authorisations than necessary to perform required functions. This is perhaps most often applied in the administration of the system. Its goal is to reduce risk by limiting the number of people with access to critical system security controls; i.e., controlling who can enable or disable system security features or change the privileges of users or programs. Best practice suggests it is better to have several administrators with limited access to security resources rather than one person with "super user" permissions. Consideration should be given to implementing role-based access controls for various aspects of system use, not only administration. The system security policy can identify and define the various roles of users or processes. Each role is assigned those permissions needed to perform its functions. Each permission specifies a permitted access to a particular resource (such as "read" and "write" access to a specified file or directory, "connect" access to a given host and port, etc.) Unless a permission is granted explicitly, the user or process should not be able to access the protected resource. Additionally, identify the roles/responsibilities that, for security purposes, should remain separate, this is commonly termed “separation of duties”.



### Principle 26 - Do not implement unnecessary security mechanisms.

Every security mechanism should support a security service or set of services, and every security service should support one or more security goals. Extra measures should not be implemented if they do not support a recognised service or security goal. Such mechanisms could add unneeded complexity to the system and are potential sources of additional vulnerabilities. An example is file encryption supporting the access control service that in turn supports the goals of confidentiality and integrity by preventing unauthorised file access. If file encryption is a necessary part of accomplishing the goals, then the mechanism is appropriate. However, if these security goals are adequately supported without inclusion of file encryption, then that mechanism would be an unneeded system complexity.



### Principle 27 - Ensure proper security in the shutdown or disposal of a system.

Although a system may be powered down, critical information still resides on the system and could be retrieved by an unauthorised user or organisation. Access to critical information systems must always be controlled. At the end of a system’s lifecycle, system designers should develop procedures to dispose of an information system’s assets in a proper and secure fashion. Procedures must be implemented to ensure system hard drives, volatile memory, and other media are purged to an acceptable level and do not retain residual information.



### Principle 28 - Identify and prevent common errors and vulnerabilities.

Many errors reoccur with disturbing regularity - errors such as buffer overflows, race conditions, format string errors, failing to check input for validity, and programs being given excessive privileges. Learning from the past will improve future results.



### Principle 29 - Implement security through a combination of measures distributed physically and logically.

Often, a single security service is achieved by cooperating elements existing on separate machines. For example, system authentication is typically accomplished using elements ranging from the user-interface on a workstation through the networking elements to an application on an authentication server. It is important to associate all elements with the security service they provide. These components are likely to be shared across systems to achieve security as infrastructure resources come under more senior budget and operational control.



### Principle 30 - Formulate security measures to address multiple overlapping information domains.

An information domain is a set of active entities (person, process, or devices) and their data objects. A single information domain may be subject to multiple security policies. A single security policy may span multiple information domains. An efficient and cost-effective security capability should be able to enforce multiple security policies to protect multiple information domains without the need to separate physically the information and respective information systems processing the data. This principle argues for moving away from the traditional practice of creating separate LANs and infrastructures for various sensitivity levels (e.g., security classification or business function such as proposal development) and moving toward solutions that enable the use of common, shared, infrastructures with appropriate protections at the operating system, application, and workstation level. Moreover, to accomplish missions and protect critical functions, government and private sector organisations have many types of information to safeguard. With this principle in mind, system engineers, architects, and IT specialists should develop a security capability that allows organisations with multiple levels of information sensitivity to achieve the basic security goals in an efficient manner.



### Principle 31 - Authenticate users and processes to ensure appropriate access control decisions both within and across domains.

Authentication is the process where a system establishes the validity of a transmission, message, or a means of verifying the eligibility of an individual, process, or machine to carry out a desired action, thereby ensuring that security is not compromised by an untrusted source. It is essential that adequate authentication be achieved in order to implement security policies and achieve security goals. Additionally, level of trust is always an issue when dealing with cross-domain interactions. The solution is to establish an authentication policy and apply it to cross-domain interactions as required. Note: A user may have rights to use more than one name in multiple domains. Further, rights may differ among the domains, potentially leading to security policy violations.



### Principle 32 - Use unique identities to ensure accountability.

An identity may represent an actual user or a process with its own identity, e.g. a program making a remote access. Unique identities are a required element in order to be able to:

- Maintain accountability and traceability of a user or process
- Assign specific rights to an individual user or process
- Provide for non-repudiation
- Enforce access control decisions
- Establish the identity of a peer in a secure communications path
- Prevent unauthorised users from masquerading as an authorised user.
