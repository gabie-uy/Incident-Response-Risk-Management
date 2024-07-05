# SAP

## Monitoring & Logging

The utilization of applications such as performance monitoring and activity tracing plays an important role in pinpointing system events. These applications are tools that empower system administrators and operators to make informed decisions and take timely actions when necessary. SAP’s system's architecture relies on AS Java (Application Server for Java), which underpins many administrative tasks and provides a view of the tools essential for their execution. These tasks encompass various aspects of system administration and management, each serving a purpose:

### AS Java:

1. **Technical System Landscape:** Understanding web of technical systems and their interconnections within the environment.
2. **Monitoring:** Employing monitoring tools to track system performance and health continuously.
3. **Management:** Overseeing and controlling the various components of the system to ensure smooth operation.
4. **Software Change Management:** Facilitating the efficient management and deployment of software updates and changes.
5. **Adobe Document Services:** Managing the generation and manipulation of Adobe PDF documents within the system.

### Functions:

1. **Troubleshooting:** Engaging in problem-solving activities to identify and resolve possible issues.
2. **Monitoring with the Generic Request and Message Generator:** Utilizing a versatile tool that generates and manages requests and messages, aiding in monitoring and analysis.
3. **Performance Monitoring:** Employing specialized tools to gauge and optimize system performance, ensuring it meets desired benchmarks.
4. **Parameter Reporting:** Extracting and analyzing parameters to gain insights into system behavior.
5. **Monitoring Using JMX:** Harnessing Java Management Extensions (JMX) for in-depth system monitoring and management.
6. **Portal Activity Report:** Generating comprehensive reports on portal activity to understand user interactions and system usage patterns.
7. **User Overview:** Gaining a holistic view of user activities within the system, assisting in user management and security analysis.

SAP employs its risk management software, specifically SAP Governance, Risk, and Compliance (GRC) solutions, powered by SAP HANA, to bolster its governance processes. This software is instrumental in ensuring the organization's robust management of risks and compliance. As part of SAP's ongoing commitment to risk reduction, SAP is dedicated to continuously enhancing its processes for identifying and mitigating potential threats and vulnerabilities. In this pursuit, they undertake several key initiatives:

1. **Internal and External Audits:** SAP conducts comprehensive internal and external audits across our global operations. These audits are crucial for assessing and enhancing our security and compliance measures.
2. **Monitoring and Control:** Their vigilant approach extends to the monitoring and support of our cloud and IT units. SAP has implemented over 2,800 rigorous, audited, and tested controls to ensure their design and operational effectiveness.
3. **Service Organization Control (SOC) Reports:** SAP provides valuable insights into the design and functionality of our internal control systems within cloud delivery units through Service Organization Control (SOC) reports. These reports include SOC 1 Type II/ISAE 3402 and SOC 2 Type II/ISAE 3000, shedding light on our commitment to maintaining strong internal controls.
4. **External Auditors:** SAP collaborates with internationally accredited auditors to assess and certify their cloud services. These audits adhere to various reporting standards and certifications, such as ISO 9001, ISO 27001, ISO 27017, ISO 27018, and ISO 22301, alongside BS 10012. These certifications testify to SAP's quality, security, and resilience of our cloud offerings.

## Response Tools & Compliance

Patch Day Disclosure: Each month, SAP disclosing vulnerabilities on a specific day (Patch Day) provides customers with predictable and reliable information about potential security issues. This regular disclosure lets customers effectively plan and prioritize their patching and mitigation efforts. By integrating this information into their risk management processes and tools, customers can swiftly identify and address vulnerabilities, reducing the risk of exploitation.

### Compliance Standards:

1. **ISO 27701, ISO 27001, and BS 10012:** These international standards provide a structured framework for implementing information security and data protection controls within SAP's Data Management Protection System (DPMS). ISO 27701 focuses on privacy information management, ISO 27001 on information security management, and BS 10012 on data protection management systems. Compliance with these standards demonstrates SAP's commitment to robust information security and data protection practices.
2. **ISO 29100:** ISO 29100 is a standard dealing with privacy framework principles. Integrating this standard into DPMS helps SAP effectively manage privacy-related controls and ensures that customer data is handled with the utmost care and following international privacy standards.
3. **ISO 19011:** ISO 19011 provides guidelines for auditing management systems, including information security and data protection management systems. Following this standard helps SAP conduct effective internal audits to assess its controls' effectiveness and identify improvement areas.
4. **GDPR Compliance:** The General Data Protection Regulation (GDPR) is a stringent requirement for protecting personal data. SAP ensures that the personal data of its customers and users is handled in compliance with European Union data protection regulations.
5. **Data Processing Agreements (DPA):** Data Processing Agreements between SAP and its customers outline the legal framework for data processing activities. The agreements establish clear roles and responsibilities regarding data protection, ensuring that both parties are aligned with data protection requirements.	

## Data Security

1. **Data Protection and Privacy Guidelines:** SAP has established data protection and privacy guidelines that govern how data is handled and protected.
2. **Data Protection by Design:** SAP integrates Data protection and privacy considerations into the design of SAP's products and services from the outset. This ensures that security measures are built into the architecture and functionality of SAP solutions.
3. **Global Data Protection and Privacy Training:** SAP mandates that employees undergo mandatory data protection and privacy training every two years. 
4. **Diverse Portfolio of Solutions:** SAP offers many solutions and services, including cloud hosting, data processing, and mobile solutions. These solutions are designed with data protection and privacy in mind, providing secure options for customers.
5. **National Institute of Standards and Technology Cybersecurity Framework (NIST CSF):** SAP adheres to the NIST CSF, a widely recognized cybersecurity framework. This framework helps SAP identify, assess, and manage cybersecurity risks effectively.
6. **Cyber Fusion Center (CFC):** Establishing a Cyber Fusion Center further strengthens SAP's cybersecurity efforts. This center likely serves as a hub for monitoring, threat detection, incident response, and collaboration to enhance security measures.
7. **Security Risk Identification:** SAP engages in proactive security risk identification to identify potential threats and vulnerabilities. This helps in developing strategies to mitigate risks effectively.
8. **Threat Modeling:** SAP uses Threat modeling to identify potential security threats and devise countermeasures to address them.
9. **Advanced Threat Defense:** SAP implements defenses to protect against sophisticated cyber threats. These measures may include intrusion detection systems, machine learning-based threat detection, and more.
10. **Application Patches and Container Security Enhancements:** SAP regularly releases patches and enhancements to secure its applications and containers. Keeping software up to date is a critical aspect of cybersecurity.
11. **Vulnerability Disclosure (Patch Day):** SAP follows a structured approach to vulnerability disclosure by disclosing vulnerabilities on a specific day (Patch Day) every month. Patch Day provides customers with authoritative and public information about software vulnerabilities, allowing them to integrate this information into their risk management processes and take necessary actions promptly.

SAP presents an IRP using a high, medium, and low priority scale based on 1) the likelihood that a risk factor will occur within the assessment horizon and 2) the impact the risk factor would likely have on SAP's business objectives were it to occur. The SAP IRP describes the priority levels beginning with the financial amount a specific incident will affect the company. It then integrates this with the likelihood an amount will involve a particular scenario.

With a very detailed table created by SAP, my IRP, with the information I've gathered above, would be very similar, if not the same as the one created by SAP. The overview of the IRP is based on Economic, Political, Social, and Regulatory Risks, Corporate Governance and Compliance Risks, Operational Business Risks, and Strategic Risks determined through Probability, Impact, and Risk Levels.

One of the challenges/limitations that SAP could have is that they have a private IR with their security software and services integrated into their systems. It would not allow others outside of SAP to help tackle new threats and vulnerabilities that come into play when security incidents occur. Because of this, they also do not have an accurate frame of reference to prevent or mitigate security incidents. More work is involved in understanding and predicting security vulnerabilities and threats to secure their systems and products.

## References:
- https://help.sap.com/saphelp_snc700_ehp01/helpdata/en/48/e95541ecfd280ce10000000a42189c/frameset.htm
