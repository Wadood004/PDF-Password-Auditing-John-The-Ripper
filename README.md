# PDF Password Auditing | John the Ripper & Johnny

![Cybersecurity](https://img.shields.io/badge/Domain-Cybersecurity-blue)
![Tools](https://img.shields.io/badge/Tools-John%20the%20Ripper%20%7C%20Johnny-red)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey)
![Project](https://img.shields.io/badge/Type-Practical%20Lab-success)

1. Project Overview

This repository documents a hands-on cybersecurity practical focused on **PDF Password Auditing and Security Assessment** using John the Ripper (JTR), Johnny GUI, and browser-based PDF password-auditing tools.

The primary objective of this project was to understand how password-protected PDF documents can be assessed through hash extraction and password-auditing techniques.

Throughout this practical, I explored the complete workflow, including installing and configuring password-auditing tools, extracting PDF password hashes, preparing hash files, loading hashes into auditing software, initiating password-recovery attempts, and verifying the results.

This project demonstrates my practical understanding of password security, PDF encryption concepts, hash-based password verification, and ethical cybersecurity testing.

2. Introduction

Password security is an important component of information security. Weak, predictable, and commonly used passwords can expose sensitive documents to unauthorized access.

Password auditing helps security professionals evaluate password strength by testing candidate passwords against password hashes.

In this practical, I worked with an encrypted PDF document and explored two approaches to password auditing:

- Desktop-based auditing using John the Ripper and Johnny GUI.
- Browser-based auditing using Networkwalks Hash Calculator and Password Cracker.

The practical helped me understand how password hashes are generated, processed, and tested during an authorized security assessment.

3. Project Objectives

The main objectives of this project were:

- Understand PDF password protection and encryption concepts.
- Install and configure John the Ripper on Windows.
- Explore Johnny as a graphical interface for John the Ripper.
- Understand PDF password hash extraction.
- Prepare and save extracted hashes in text format.
- Load hash files into password-auditing software.
- Perform authorized password-recovery attempts.
- Explore browser-based PDF hash extraction and auditing.
- Verify the reported results using the original PDF.
- Understand ethical responsibilities in password security testing.

4. Tools & Technologies Used

| Tool | Purpose |
|---|---|
| John the Ripper | Password hash auditing |
| Johnny GUI | Graphical interface for JTR |
| PDF Hash Extractor | Extracting PDF password hashes |
| Networkwalks Hash Calculator | Browser-based PDF hash generation |
| Networkwalks Password Cracker | Browser-based password auditing |
| Windows PC | Practical working environment |
| Notepad | Preparing hash text files |

5. Practical Modules

### Module 1: Password Auditing with John the Ripper & Johnny

This module focused on using desktop-based password-auditing tools to assess the password protection of an encrypted PDF.

Practical tasks performed:**

1. Downloaded John the Ripper from its official website.
2. Downloaded and installed Johnny GUI.
3. Explored the Johnny graphical interface.
4. Configured Johnny to locate the John the Ripper executable.
5. Downloaded the supplied encrypted PDF file.
6. Extracted the PDF password hash.
7. Copied the complete extracted hash.
8. Created a text file using Notepad.
9. Saved the hash as `hash1.txt`.
10. Loaded the hash file into Johnny.
11. Started a password-auditing attempt.
12. Reviewed the reported result and verified the PDF.

 Module 2: Password Auditing with Networkwalks Tools
This module introduced an alternative browser-based workflow for PDF password auditing.

Practical tasks performed:
1. Downloaded the encrypted PDF file.
2. Opened the Networkwalks Hash Calculator.
3. Uploaded the protected PDF.
4. Extracted the PDF hash beginning with `$pdf$`.
5. Copied the complete hash value.
6. Opened the Networkwalks Password Cracker.
7. Submitted the extracted hash for testing.
8. Waited for the tool to process the request.
9. Reviewed the reported result.
10. Opened the original PDF for verification.

6. Practical Methodology
The project followed a structured password-auditing workflow:

Phase 1 – Tool Preparation**
Downloaded and installed John the Ripper and Johnny GUI, followed by configuring the graphical interface.

Phase 2 – Hash Extraction**
Used a PDF hash-extraction utility to obtain the password hash from the supplied encrypted PDF.

Phase 3 – Hash Preparation**
Copied the extracted hash and saved it in a plain-text file named `hash1.txt`.

Phase 4 – Password Auditing**
Loaded the hash into Johnny and initiated an authorized password-auditing attempt.

Phase 5 – Alternative Web-Based Approach**
Explored the Networkwalks Hash Calculator and Password Cracker workflow.

Phase 6 – Result Verification**
Reviewed the reported results and checked the original encrypted PDF.

7. Screenshots & Practical Evidence
This repository includes the practical lab report containing screenshots of the activities performed during both modules.

The evidence documents:
- Software downloads and installation.
- Johnny interface and configuration.
- PDF hash extraction.
- Hash file preparation.
- Hash loading into Johnny.
- Password-auditing execution.
- Browser-based auditing workflow.
- Final result and PDF verification.

Refer to the uploaded Word lab report for the complete practical documentation and screenshots.
8. Learning Outcomes
Through this practical project, I developed an understanding of:
- Password auditing methodologies.
- PDF encryption and password protection.
- Password hash extraction and processing.
- John the Ripper functionality.
- Johnny GUI configuration and operation.
- Hash file preparation and management.
- Browser-based password-auditing workflows.
- Password-strength assessment.
- Ethical and responsible security testing.

9. Conclusion
This practical project provided valuable hands-on exposure to PDF password auditing using John the Ripper, Johnny GUI, and browser-based password-auditing tools.
By completing both modules, I gained practical knowledge of the password-auditing workflow, including tool installation, hash extraction, hash preparation, password testing, and result verification.
The project strengthened my understanding of password security and demonstrated the importance of using strong, unique passwords to protect sensitive documents.
This work represents another step in my cybersecurity learning journey, particularly in ethical hacking, information security, and practical security assessment.

 Author
**Abdul Wadood**
BS Information Technology Student  
Cybersecurity & Ethical Hacking Learner
GitHub: https://github.com/Wadood004

---

*Documented as part of my ongoing cybersecurity practical learning journey.*
