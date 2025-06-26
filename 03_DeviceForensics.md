# Device Forensics

## Devices

### 1. Apple MacBook

#### Process, Tools, Techniques and Methodology
    
| Tool / Technique Description | Description |
| --- | --- |
| The Sleuth Kit | A library and collection of command line tools that allow you to investigate disk images. Allows you to analyze volume and file system data. |
| X-Way Forensics | An advanced work environment for computer forensic examiners and our flagship product. Produces exact sector-wise copies of most media types, either to other disks (clones, mirrors) or to image files, using physical or logical disk access. |
| Cellebrite UFED | Used for the extraction and analysis of data from mobile devices by law enforcement agencies, public and private organizations. |
| mac_apt | Used for processing Mac full disk images (or live machines) and extract data/metadata useful for forensic investigation. |
| MacOS Terminal | Command line can be used for file system analysis, metadata examination, acquisition, keyword searches, scripting, log analysis, network forensics, hash verification, memory analysis, data extraction, and system information gathering. |
| John the Ripper | Enables security practitioners to crack passwords, regardless of encrypted or hashed passwords, message authentication codes (MACs) and hash-based MACs (HMACs), or other artifacts of the authentication process.

#### Legal Requirements and Potential Challenges

1. Search Warrants
2. Subpoenas
3. Court Orders
4. National Security Letters (NSLs)
5. Consent

The challenges that could occur in here are the restrictions that the MacOS has. The tools and techniques could help in device forensics, however, there are less MacOS users in the technical industry that it may take time to look for professionals to do forensic activities on Mac devices. Aside from that, obtaining legal requirements is also another time-consuming issue that could hinder investigations and obtaining evidence. Obtaining evidence unethically and illegally may cause more serious problems in the investigation that could lead to people or the organizations in false evidence.

#### Role and Use of Write Blockers in Preserving Integrity

Write blockers in digital forensics preserve the integrity and credibility of digital evidence. They protect data, ensuring original data remains unaltered during forensic examinations by blocking write or modification commands. This maintains the data's original state. They also contribute to establishing a clear and unbroken chain of custody, ensuring evidence remains untampered with. Moreover, write blockers are instrumental in providing the legal admissibility of digital evidence, as they guarantee that data is collected and analyzed without alterations, a fundamental requirement for court acceptance.

#### Device Considerations
1. Solid-State Drives (SSDs) vs. Hard Disk Drives (HDDs)
2. Apple File System (APFS)
3. T2 Security Chip
4. Firmware Passwords
5. Disk Size and Space Utilization
6. Cloud Storage Integration 7. FileVault Encryption
8. User Authentication
9. Data Synchronization
10. Time Machine Backups
11. Online Accounts and Social Media

### Apple iPhone

#### Process, Tools, Techniques, Methodology

| Tool / Technique Description | Description |
| --- | --- |
| Cellebrite UFED | Forensic tool for mobile device extraction, supports various iPhone models and iOS versions. |
| GrayKey | Specialized tool for iOS device forensics, used to unlock and extract data from iPhones. Legal restrictions may apply. |
| iMobie PhoneRescue | Software for data recovery from offline iPhones, capable of extracting contacts, messages, photos, and more. |
| Magnet AXIOM | Digital forensics platform with tools for analyzing iOS devices, including offline extraction. |
| Checkm8 Exploit | Exploit targeting iPhone BootROM vulnerabilities for gaining access to locked or offline devices. |
| iTunes Backup | Data extraction from iPhone backups made with iTunes, accessible even if the device is offline. |
| iCloud Forensics | Accessing data from an iCloud account associated with the iPhone, subject to legal authorization and authentication. |
| Jailbreaking | Process of gaining more control over an iPhone's filesystem, may be used to extract data, but it can be risky and void warranties. |
| Chip-off Forensics | Invasive method involving the removal of the NAND flash memory chip for data extraction from the device.|
| iLEAPP (iOS Logs, Events, And Properties Parser |

#### Legal Requirements and Potential Challenges

While legal requirements for iPhones are similar to a MacBook or MacOS device, the potential challenges that anyone would face with an iPhone would be slightly different compared to a MacBook. Some potential challenges that could happen because of iPhones are:
 
1. Lockdown Mode
2. Hidden Assets such as photo albums, Shared Photo Libraries
3. Text Message Editing
4. Text Message Unsend

#### Role and Use of Write Blockers in Preserving Integrity

1. Device Connection: This prevents accidental overwriting of data during the analysis.
2. Preventing Contamination: When an iPhone is connected to a forensic computer for data extraction, the write blocker prevents any write operations to the iPhone's storage. This is important because connecting a device to a laptop can trigger automatic write actions (e.g., creating temporary files), which may alter the data.
3. Data Extraction: This is crucial when recovering files, texts, call logs, and other evidence.
4. Device Imaging: During imaging (creating a bit-by-bit copy of the device's storage), write blockers ensure that the original data remains untouched, which is vital for maintaining data integrity.
5. Verification: Write blockers may also offer features for verifying that no write operations have occurred during the forensic process, ensuring the data's integrity is upheld.

#### Device Considerations

NAND flash memory employs wear leveling algorithms to distribute 'write' and 'erase' cycles evenly across memory cells. Wear leveling ensures that no single memory block is excessively written to, which can lead to premature failure. Data is instead written to different blocks in a round-robin fashion.

When a file is deleted on an iPhone, the TRIM command marks the associated storage blocks as "stale." which means that the blocks are no longer considered in use. They are scheduled for garbage collection, where the memory controller can erase and reclaim them.

Data on an iPhone is encrypted with a strong encryption algorithm, and decryption requires the use of encryption keys. These keys may be derived from the user's passcode, stored in the Secure Enclave (a hardware component), or protected by biometrics (e.g., Touch ID or Face ID). Investigators may need to address the issue of accessing and handling these encryption keys legally and ethically to decrypt and access the data.

### Sony Playstation S5

#### Process, Tools, Techniques, Methodology

| Tool / Technique Description | Description |
| --- | --- |
| FTK Imager | Used to acquire a bit-by-bit copy of the PS5's storage, ensuring data integrity during the investigation. |
| Autopsy | An open-source digital forensics tool that can analyze file systems, extract information, and provide a user-friendly interface for examiners. It supports analyzing various file systems, which may be helpful in PS5 forensics.
| The Sleuth Kit (TSK) | A collection of command-line digital forensic tools, including Autopsy. This can be used to examine file systems and perform basic file and disk analysis on the PS5.
| Volatility Framework | If a memory dump is available from the PS5, this can be used to analyze the RAM for active processes, system information, and other volatile data. This can provide insights into what was happening on the console when it was powered on.
| Registry Viewer | If the PS5 runs on an operating system with a registry, this can help extract and examine registry entries and system settings.
| FTK Imager | Used to acquire a bit-by-bit copy of the PS5's storage, ensuring data integrity during the investigation.
| Autopsy | An open-source digital forensics tool that can analyze file systems, extract information, and provide a user-friendly interface for examiners. It supports analyzing various file systems, which may be helpful in PS5 forensics.
   
#### Legal Requirements and Potential Challenges

Before conducting any forensic examination on a PS5 or any digital device, obtaining proper authorization from legal authorities or consent from the device owner is imperative. Unauthorized access could be illegal and jeopardize the credibility of the examination. Additionally, when dealing with devices in the context of a criminal investigation, the necessity of a search warrant often arises. Law enforcement agencies must adhere to legal procedures when seeking such warrants, ensuring they have legal permission to seize and examine the PS5. Digital forensic experts must also be well-versed in Data Privacy Laws, such as GDPR in Europe and CCPA in the United States, to handle personal data in compliance with relevant regulations. Understanding attorney-client privilege is equally essential, mainly when the PS5 belongs to a legal client, as confidential protections may apply, necessitating consultation with legal counsel.
Role and Use of Write Blockers in Preserving Integrity Data on the PS5's storage device in a read-only mode. Forensic analysts can view, copy, and analyze data without changing the original storage. It prevents any unintentional or deliberate alterations. Write blockers ensure that no written commands, such as creating, modifying, or deleting files, can be executed on the storage media. They ensure the data was unaltered from the moment of seizure, during, and up to its presentation in court. Write blockers typically generate logs and hash values during the forensic process. These logs record actions taken during the examination, such as acquiring disk images. Hash values are developed to verify the integrity of the received data. Forensic analysts can confirm that the data remains unchanged by comparing these hash values before and after the examination. The use of write blockers is a well- established best practice in the field, and failing to use them may lead to questions about the credibility of the examination. A PS5 may be non-functional or damaged.
 
#### Device Considerations

These considerations encompass various facets of the PS5's hardware and software ecosystem. The use of write blockers is imperative to maintain the data's integrity during examination, preventing accidental or deliberate alterations. Given that PlayStation consoles may incorporate custom components or security features, analysts must be prepared to address these unique attributes. Additionally, knowledge of the console's firmware, system software, and potential data encryption is essential, as these elements can significantly impact the examination process. File system and partition structure, including any relevant system logs, event data, and user accounts, is essential for extracting meaningful evidence.
PS5 forensic analysts must consider network configuration, peripherals, and access controls, recognizing that digital game and media content may hold relevance to the investigation. Examining maintenance and repair records can provide insight into the console's history and any potential modifications.
  

## Summary

| | iPhone | Mac | PS5 |
| --- | --- | --- | --- |
| Tools / Technique | Cellebrite UFED, GrayKey, Mobie PhoneRescue, Magnet AXIOM, Checkm8 Exploit, iTunes Backup, iCloud Forensics, Jailbreaking, Chip-off Forensics, iLEAPP | The Sleuth Kit (TSK), X-Way Forensics Cellebrite UFED, mac_apt, MacOS Terminal, John the Ripper | The Sleuth Kit (TSK), Autopsy, Volatility Framework, Registry Viewer, FTK Imager |
| Legal Requirements | Search Warrants, Subpoenas, Court Orders, National Security Letters (NSLs), Consent | Same | Same |
| Write Blockers | All are capable of write blockers up to their limitations | Same | Same |
| Device Considerations | Hard drive, System software, Logs, Accounts, Chips/Processors, Encryption/Decryption algorithms, Cloud integration, Biometrics | Same | Same |
   
