<div align="center">

# 🔐 NetworkWalks Cybersecurity Internship

## Week 03 — Password Security & Password Cracking

### W3-PM1: Password Cracking with JTR  
### W3-PM2: Password Cracking with NW Tools

![Kali Linux](https://img.shields.io/badge/Kali-Linux-blue?style=for-the-badge&logo=kalilinux&logoColor=white)
![John the Ripper](https://img.shields.io/badge/John%20the%20Ripper-JTR-red?style=for-the-badge)
![Password Security](https://img.shields.io/badge/Password-Security-purple?style=for-the-badge)
![Hash Analysis](https://img.shields.io/badge/Hash-Analysis-orange?style=for-the-badge)
![NetworkWalks](https://img.shields.io/badge/NetworkWalks-B082-green?style=for-the-badge)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Ethical%20Hacking-black?style=for-the-badge)

<br>

**Practical Password Security Assessment using Kali Linux, John the Ripper and NetworkWalks Security Tools**

</div>

---

# 📌 Project Overview

During **Week 03** of the **NetworkWalks Cybersecurity & Ethical Hacking Internship — Batch B082**, I performed practical password-security exercises involving password-protected PDF files, hash extraction, password recovery and dictionary-based password testing.

The week consisted of two essential project modules:

| Module | Project Module | Focus |
|---|---|---|
| 🔐 **W3-PM1** | Password Cracking with JTR | John the Ripper |
| 🧪 **W3-PM2** | Password Cracking with NW Tools | NetworkWalks security tools |

The practical work was performed in an **authorized educational laboratory environment**.

---

# 🎯 Learning Objectives

The main objectives of Week 03 were:

- Understand password-protected files and password security.
- Understand how password hashes can be extracted from protected PDFs.
- Identify the appropriate hash format for John the Ripper.
- Use **John the Ripper through the Kali Linux command line**.
- Perform dictionary-based password recovery in a controlled laboratory.
- Understand the relationship between password strength and password recovery.
- Use NetworkWalks security tools for hash analysis and password testing.
- Compare results obtained through different password-security tools.
- Preserve screenshots and command-line evidence.
- Document the complete methodology and results professionally.
- Understand the importance of strong and unique passwords.

---

# 📜 Authorization & Ethical Scope

> ⚠️ **AUTHORIZED EDUCATIONAL LAB**
>
> All activities documented in this repository were performed as part of the assigned **NetworkWalks Cybersecurity Internship** exercises and against intentionally provided laboratory files.
>
> The techniques demonstrated here are intended for authorized security testing, cybersecurity education, CTFs and controlled laboratory environments only.

The Week 3 project material explains that John the Ripper is used by security professionals to test password strength and can work with password-protected files such as PDFs. :contentReference[oaicite:1]{index=1}

---

# 🖥️ Lab Environment

| Component | Configuration |
|---|---|
| Operating System | Kali Linux |
| Virtualization | VMware Workstation |
| Primary Tool | John the Ripper |
| Execution Method | Kali Linux Command Line |
| File Type | Password-Protected PDF |
| Hash Type | PDF Password Hash |
| Password Recovery Method | Dictionary-Based |
| Secondary Platform | NetworkWalks Security Tools |
| Environment | Authorized Educational Lab |

---

# 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| 🔐 John the Ripper | Password hash recovery |
| 🐉 Kali Linux | Security testing environment |
| 🧮 NetworkWalks Hash Calculator | Hash generation / PDF hash extraction |
| 🔎 NetworkWalks Password Cracker | Dictionary-based password testing |
| 📄 PDF Hash Format | Processing password-protected PDF hashes |
| 📝 Terminal | Command-line execution and result collection |

---

# 📂 Repository Structure

```text
networkwalks-B082-week3-password-security
│
├── README.md
├── Evidence/
│   │
│   ├── W3-PM1-JTR/
│   │   │
│   │   ├── PDF1/
│   │   │   ├── hash1.txt
│   │   │   └── screenshots/
│   │   │       ├── 01-pdf1-hash.png
│   │   │       ├── 02-pdf1-john.png
│   │   │       └── 03-pdf1-result.png
│   │   │
│   │   ├── PDF2/
│   │   │   ├── hash2.txt
│   │   │   └── screenshots/
│   │   │       ├── 01-pdf2-hash.png
│   │   │       ├── 02-pdf2-john.png
│   │   │       └── 03-pdf2-result.png
│   │   │
│   │   └── PDF3/
│   │       ├── hash3.txt
│   │       └── screenshots/
│   │           ├── 01-pdf3-hash.png
│   │           ├── 02-pdf3-john.png
│   │           └── 03-pdf3-result.png
│   │
│   └── W3-PM2-NW-Tools/
│       ├── hash-calculator/
│       └── password-cracker/
│
├── Results/
│   ├── W3-PM1-results.txt
│   └── W3-PM2-results.txt
│
└── Report/
    └── Week-03-Final-Report.pdf
````

---

# 🔎 Week 03 Workflow

```text
                         Authorized Lab
                               │
                               ▼
                    Password-Protected PDFs
                               │
                               ▼
                       Hash Extraction
                               │
              ┌────────────────┴────────────────┐
              │                                 │
              ▼                                 ▼
       W3-PM1: JTR                      W3-PM2: NW Tools
              │                                 │
              ▼                                 ▼
      John the Ripper                   Hash Calculator
              │                                 │
              ▼                                 ▼
       PDF Hash Format                  PDF Hash Extraction
              │                                 │
              ▼                                 ▼
      Dictionary Attack                 Password Cracker
              │                                 │
              └────────────────┬────────────────┘
                               ▼
                     Password Verification
                               │
                               ▼
                       Evidence Collection
                               │
                               ▼
                        Results Analysis
                               │
                               ▼
                     Final Documentation
```

---

# 🔐 W3-PM1 — Password Cracking with JTR

## Objective

The objective of **W3-PM1** was to understand password recovery using **John the Ripper (JTR)** against a password-protected PDF in an authorized laboratory environment.

The official module introduces both **John the Ripper** and **Johnny**, the graphical interface for JTR. It also notes that Kali Linux users can open JTR directly because it is available in Kali Linux. 

### Implementation Used

The provided module demonstrates a graphical workflow using JTR/Johnny. Instead, I performed the practical exercise directly through the **John the Ripper command-line interface on Kali Linux**.

This allowed me to gain additional practical experience with:

* Linux terminal usage
* JTR command syntax
* Hash-format identification
* Dictionary-based password recovery
* Command-line result analysis

---

# 📄 PDF Password Recovery Workflow

```text
Password-Protected PDF
          │
          ▼
     Hash Extraction
          │
          ▼
       hash.txt
          │
          ▼
 Identify PDF Format
          │
          ▼
   John the Ripper
          │
          ▼
 Dictionary Processing
          │
          ▼
 Password Recovery
          │
          ▼
   PDF Verification
```

---

# 1️⃣ PDF 1 — Password Recovery

### Input File

```text
My Locked PDF1.pdf
```

### Extracted Hash

```text
hash1.txt
```

The PDF password hash was extracted and stored in `hash1.txt`.

### John the Ripper Command

```bash
john --format=PDF hash1.txt
```

### Evidence

<img width="1920" height="1020" alt="Screenshot 2026-08-25 203237" src="https://github.com/user-attachments/assets/715b3bc5-7e96-403d-b300-dd246c0172ce" />


<img width="1902" height="441" alt="Screenshot 2026-08-24 214014" src="https://github.com/user-attachments/assets/43066f6b-186a-4a9e-bdde-b11e6145b082" />


<img width="1617" height="663" alt="Screenshot 2026-08-24 214059 - Copy" src="https://github.com/user-attachments/assets/58f302e5-a97f-4962-ad05-7ac18bfd7f8b" />


### Result

✅ **PDF 1 password was successfully recovered.**

<img width="1905" height="871" alt="Screenshot 2026-08-24 214726" src="https://github.com/user-attachments/assets/a5a6d9f3-3318-49db-a21d-49eb850999b8" />




---

# 2️⃣ PDF 2 — Password Recovery

### Input File

```text
My Locked PDF2.pdf
```

### Extracted Hash

```text
hash2.txt
```

The second protected PDF was processed using its corresponding extracted hash.

### John the Ripper Command

```bash
john --format=PDF hash2.txt
```

### Evidence

<img width="1920" height="1020" alt="Screenshot 2026-08-25 203806" src="https://github.com/user-attachments/assets/6e591044-40ce-47e7-a8a3-0ea554806948" />


<img width="1916" height="537" alt="Screenshot 2026-08-25 195951" src="https://github.com/user-attachments/assets/3010e6e9-0c36-4f79-93db-82f2afb00bd5" />


<img width="1860" height="707" alt="Screenshot 2026-08-25 200019" src="https://github.com/user-attachments/assets/aecb8ba2-ff91-4d1c-8775-7b9083c953ad" />


### Result

✅ **PDF 2 password was successfully recovered.**

The recovered password was verified to be the **same password used by PDF 1**.

<img width="1912" height="890" alt="Screenshot 2026-08-25 200246" src="https://github.com/user-attachments/assets/c03798d2-9074-4860-b607-04447abe1e0e" />


---

# 3️⃣ PDF 3 — Password Recovery

### Input File

```text
My Locked PDF3.pdf
```

### Extracted Hash

```text
hash3.txt
```

The third protected PDF was processed separately using its corresponding hash.

### John the Ripper Command

```bash
john --format=PDF hash3.txt
```

### Evidence

<img width="1920" height="1020" alt="Screenshot 2026-08-25 204126" src="https://github.com/user-attachments/assets/34374993-abd6-40cd-8585-bb0b505736cd" />


<img width="1887" height="396" alt="Screenshot 2026-08-25 200415" src="https://github.com/user-attachments/assets/e2f06aa5-1cd7-4faf-9d84-c510fa7034c6" />

<img width="1907" height="745" alt="Screenshot 2026-08-25 200459" src="https://github.com/user-attachments/assets/a03a0689-869c-43f1-b343-0641aaecf5e9" />


### Result

✅ **PDF 3 password was successfully recovered.**

The recovered password was verified to be **different from the password shared by PDF 1 and PDF 2**.

<img width="1916" height="866" alt="Screenshot 2026-08-25 200522" src="https://github.com/user-attachments/assets/40b3bd4f-7510-4e22-be7b-b88adb22f279" />


---

# 📊 W3-PM1 Results

| Assessment Item        | Result                 |
| ---------------------- | ---------------------- |
| Protected PDFs         | **3**                  |
| Hash Files             | **3**                  |
| Password Recovery Tool | **John the Ripper**    |
| Platform               | **Kali Linux**         |
| Execution Method       | **Command Line**       |
| PDF 1                  | ✅ Password recovered   |
| PDF 2                  | ✅ Password recovered   |
| PDF 3                  | ✅ Password recovered   |
| PDF 1 & PDF 2          | **Same password**      |
| PDF 3                  | **Different password** |
| Overall Task           | **Completed**          |

---

# 🧠 W3-PM1 Key Observation

The exercise demonstrated how password-protected PDF files can be assessed when their corresponding password hashes are available.

An important observation was that **PDF 1 and PDF 2 used the same password**, while **PDF 3 used a different password**.

This demonstrates why password reuse can increase security risk. If the same password is reused across multiple protected files, recovery of that password can potentially affect more than one protected resource.

---

# 🧪 W3-PM2 — Password Cracking with NW Tools

## Objective

The objective of **W3-PM2** was to use the NetworkWalks-provided security tools to understand hash processing and dictionary-based password recovery in a controlled educational environment.

The workflow involved:

```text
Protected PDF
     │
     ▼
Hash Extraction
     │
     ▼
NetworkWalks Hash Calculator
     │
     ▼
PDF Hash
     │
     ▼
NetworkWalks Password Cracker
     │
     ▼
Dictionary Attack
     │
     ▼
Password Match
     │
     ▼
Password Verification
```

---

# 🔢 Hash Calculator

The NetworkWalks Hash Calculator was used to process the protected PDF and obtain a crackable PDF hash representation.

### Purpose

The tool provides a practical way to understand how a protected PDF can be represented as a password hash suitable for password-security testing.

### Evidence

<img width="1691" height="867" alt="Screenshot 2026-08-25 200750" src="https://github.com/user-attachments/assets/7f9351e0-6790-4174-99d9-e1e94ee8e3da" />


### Result

✅ PDF hash successfully obtained.

The resulting hash was then used for password-recovery testing.

---

# 🔓 NetworkWalks Password Cracker

The extracted PDF hash was supplied to the NetworkWalks password-cracking tool.

The tool performs a dictionary-based password test by comparing candidate passwords against the supplied hash.

### Methodology

```text
PDF Hash
   │
   ▼
Password Candidate List
   │
   ▼
Hash Comparison
   │
   ├── No Match
   │
   └── Match
         │
         ▼
   Password Recovered
```

### Evidence

<img width="1337" height="826" alt="Screenshot 2026-08-25 200833" src="https://github.com/user-attachments/assets/9c922c39-a002-4456-9370-d1db2515b7db" />


### Result

✅ **Password successfully recovered through the NetworkWalks password-cracking workflow.**


---

# 📊 W3-PM2 Results

| Assessment Item          | Result                      |
| ------------------------ | --------------------------- |
| Hash Processing          | ✅ Completed                 |
| PDF Hash Extraction      | ✅ Completed                 |
| Dictionary-Based Testing | ✅ Completed                 |
| Password Match           | ✅ Identified                |
| Password Verification    | ✅ Completed                 |
| Tool                     | NetworkWalks Security Tools |
| Environment              | Authorized Educational Lab  |
| Overall Task             | **Completed**               |

---

# ⚖️ JTR vs NW Tools

| Feature              | John the Ripper | NetworkWalks Tools      |
| -------------------- | --------------- | ----------------------- |
| Platform Used        | Kali Linux      | Web-based Security Tool |
| Interface            | Command Line    | Graphical/Web Interface |
| Hash Processing      | Supported       | Supported               |
| Dictionary Testing   | Supported       | Supported               |
| PDF Password Testing | ✅               | ✅                       |
| Practical Learning   | Linux CLI       | Security Tool Workflow  |
| Evidence             | Terminal Output | Web Interface Output    |

### Key Difference

The major difference between the two approaches was the execution environment.

**John the Ripper** was operated directly from the **Kali Linux command line**, while the **NetworkWalks tools** provided a graphical workflow for hash processing and password testing.

---

# 📈 Overall Week 03 Results

| Module             | Tool / Method              | Result       |
| ------------------ | -------------------------- | ------------ |
| **W3-PM1**         | John the Ripper            | ✅ Completed  |
| **W3-PM1 PDF 1**   | JTR + PDF hash             | ✅ Recovered  |
| **W3-PM1 PDF 2**   | JTR + PDF hash             | ✅ Recovered  |
| **W3-PM1 PDF 3**   | JTR + PDF hash             | ✅ Recovered  |
| **W3-PM2**         | NetworkWalks Tools         | ✅ Completed  |
| Hash Processing    | PDF hash extraction        | ✅ Completed  |
| Dictionary Testing | Password candidate testing | ✅ Completed  |
| Evidence           | Screenshots + hash files   | ✅ Documented |
| Reporting          | Final assessment report    | ✅ Completed  |

---

# 🔐 Password Security Observations

The practical exercise demonstrated several important password-security concepts:

### 1. Password Reuse

PDF 1 and PDF 2 used the same password.

Reusing passwords across multiple protected resources increases the potential impact if that password is recovered.

### 2. Password Strength

Dictionary-based password recovery demonstrates why simple or predictable passwords should not be used for protecting sensitive files.

### 3. Password-Protected Documents

Password protection should be combined with strong passwords and appropriate encryption mechanisms when sensitive information is stored in documents.

### 4. Hash Security

A password hash should be protected as sensitive security material because it can potentially be subjected to offline password-recovery attempts.

### 5. Unique Passwords

Each sensitive file or resource should use a strong and unique password wherever practical.

---

# 🧠 Key Learning Outcomes

Through this Week 03 project, I developed practical knowledge of:

* 🔐 Password security
* 🔎 Hash extraction
* 🧮 PDF password hash formats
* 🐉 Kali Linux
* ⚔️ John the Ripper
* 💻 Linux command-line security tools
* 📚 Dictionary-based password recovery
* 🧪 Password testing methodologies
* 🔓 Protected PDF analysis
* 📸 Evidence collection
* 📝 Technical documentation
* 📊 Security result analysis
* ⚖️ Ethical cybersecurity practices

---

# 💡 Key Takeaway

The Week 03 activities demonstrated that password security depends not only on applying password protection but also on using strong, unique and unpredictable passwords.

Using **John the Ripper through the Kali Linux command line** provided practical experience with professional password-security tooling, while the **NetworkWalks tools** provided a graphical workflow for understanding hash extraction and dictionary-based password testing.

The comparison between the protected PDFs also demonstrated the security implications of password reuse, as **PDF 1 and PDF 2 shared the same password while PDF 3 used a different password**.

---

# 📑 Final Assessment Report

A detailed final report has been prepared covering the Week 03 activities, methodology, tools, evidence, observations, results, security considerations and learning outcomes.

<div align="center">

### 📄 Week 03 Final Report

final report is shown in report folder in repo .

</div>

---

# 📂 Complete Project Structure

```text
networkwalks-B082-week3-password-security
│
├── README.md
│
├── Authorization/
│   └── authorization-evidence
│
├── Evidence/
│   │
│   ├── W3-PM1-JTR/
│   │   │
│   │   ├── PDF1/
│   │   │   ├── hash1.txt
│   │   │   └── screenshots/
│   │   │
│   │   ├── PDF2/
│   │   │   ├── hash2.txt
│   │   │   └── screenshots/
│   │   │
│   │   └── PDF3/
│   │       ├── hash3.txt
│   │       └── screenshots/
│   │
│   └── W3-PM2-NW-Tools/
│       │
│       ├── hash-calculator/
│       │
│       └── password-cracker/
│
├── Results/
│   ├── W3-PM1-results.txt
│   └── W3-PM2-results.txt
│
└── Report/
    └── Week-03-Final-Report.pdf
```

---

# 🏁 Conclusion

Week 03 provided practical exposure to password-security assessment and password-recovery techniques in an authorized cybersecurity laboratory.

The project covered two essential modules: **W3-PM1 — Password Cracking with JTR** and **W3-PM2 — Password Cracking with NW Tools**.

For W3-PM1, I used **John the Ripper directly from Kali Linux through the command line** to process extracted PDF password hashes and successfully recover the passwords of three protected PDF files. PDF 1 and PDF 2 were found to use the same password, while PDF 3 used a different password.

For W3-PM2, I used the **NetworkWalks security tools** to understand the hash-processing and dictionary-based password-recovery workflow.

Overall, the exercise strengthened my understanding of password security, hash analysis, dictionary-based recovery, Kali Linux command-line tools, evidence collection and professional cybersecurity reporting.

---

# 🔒 Ethical Use

> **IMPORTANT:** The techniques and tools documented in this repository are intended for authorized cybersecurity testing, educational laboratories, CTF environments and systems/files for which explicit permission has been granted.
>
> Do not use password-recovery techniques against files, accounts, systems or networks without authorization.

---

<div align="center">

## 🚀 NetworkWalks Cybersecurity Internship

### Batch B082 • Week 03

**Password Security • Hash Analysis • John the Ripper • NW Tools**

<br>

⭐ **Documenting practical cybersecurity skills through hands-on learning.**

</div>
