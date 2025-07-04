# 🕵️‍♂️ Digital Forensic Investigation Report - Case 2024-0008

## 📋 Project Overview

This repository contains a comprehensive digital forensic investigation report conducted by **CyberSleuth Solutions Ltd.** The case revolves around a **Yellow INTEGRAL USB** device suspected of housing digital evidence related to:

- Credit card theft  
- Drug manufacturing  
- Pharmaceutical theft  
- Check washing operations

**Case Metadata:**
- **Case Number**: CASE-2024-0008  
- **Lead Investigator**: Ahmed Rashwan (ID: 12842713)  
- **Organization**: CyberSleuth Solutions Ltd.  
- **Supervisor**: Sarah Johnson  
- **Authorization**: Oliver Mitchell, CEO  
- **Report Version**: 1.0

---

## 🎯 Investigation Objectives

- Identify and preserve digital evidence using industry-standard protocols  
- Analyze files and communications for criminal activity  
- Document findings in line with legal and regulatory frameworks  
- Reconstruct a comprehensive timeline of digital events  
- Assess the likelihood of criminal activities based on digital artifacts

---

## 📚 Table of Contents

- Project Overview  
- Investigation Objectives  
- Methodology  
- Tools and Technologies  
- Key Findings  
- Criminal Activities Investigated  
- Timeline of Events  
- Evidence Analysis  
- Compliance and Legal Framework  
- Conclusions  
- Repository Structure  
- Usage Instructions  
- References  
- Acknowledgments

---

## 🔬 Methodology

Following [NIST SP 800-86](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-86.pdf) guidelines, the investigation followed four key phases:

### 1. Data Collection
- Device received with proper authorization
- Write-blocked with Orion USB Write Blocker
- Two forensic images created:
  - **Control Copy** (raw)
  - **Working Copy** (E01 format via FTK Imager)

### 2. Examination
- Systematic analysis of forensic images using industry-standard tools  
- File cataloging, metadata extraction, and artifact preservation

### 3. Analysis
- Password cracking  
- Malware static/dynamic analysis  
- Timeline and event correlation

### 4. Reporting
- Documentation of findings in a court-admissible format  
- Detailed appendices and evidence index

---

## 🛠️ Tools and Technologies

| Tool                          | Version    | Purpose                                      |
|------------------------------|------------|----------------------------------------------|
| AccessData FTK Imager        | 3.1.2.0    | Evidence imaging                             |
| Autopsy                      | 4.19.3     | Forensic analysis                            |
| Hashcat                      | 2.6.2      | Password cracking                            |
| Office2John.py               | -          | Password hash extraction                     |
| OneDrive                     | -          | Secure evidence storage                      |
| Corbett Backup Restore Wizard| 4.5.0.0    | Email message conversion                     |
| ShellBags Explorer           | 2.0.0.0    | Registry artifact analysis                   |
| Registry Explorer            | 2.0.0.0    | Registry file examination                    |
| Orion USB Write Blocker      | 1.0.0      | Hardware write protection                    |

### Additional Platforms:
- [Any.run](https://any.run/)  
- [Tria.ge](https://tria.ge/)  
- [Hybrid Analysis](https://www.hybrid-analysis.com)  
- [VirusTotal](https://www.virustotal.com)

---

## 🔍 Key Findings

### 🧑‍💻 Suspects Identified

| Name               | Email                      | Role                        |
|--------------------|----------------------------|-----------------------------|
| John Washer        | chkwasher@comcast.net      | Primary suspect             |
| Rasco Bad Guy      | txkidd@swbell.net          | Technical advisor           |
| Wes Mantooth       | dollarhyde86@comcast.net   | Theft operations            |
| David Thomas       | skimmerman27@hotmail.com   | Card skimming expert        |
| Billy Bob Brubeck  | -                          | Associated individual       |
| Mr. Smee           | smee.rox@gmail.com         | Associated individual       |

### 🗂️ Key Evidence

- **Documents**:  
  - `How To Steal Credit Numbers.doc`  
  - `SLIST.doc` – Stolen card database  
  - `X marks the spot.doc` – Drug lab coordinates  

- **Communications**:  
  - Email & chat logs discussing drug ops, fraud tactics  
  - Planning notes for meth production  

- **Malware**:  
  - `Install_AIM59[1].exe` - Trojan with registry editing & shell spawning capabilities  
  - Techniques mapped to [MITRE ATT&CK](https://attack.mitre.org/)

---

## 🚨 Criminal Activities Investigated

| Activity              | Likelihood       | Evidence Highlights                                |
|-----------------------|------------------|---------------------------------------------------|
| Credit Card Theft     | **Very Likely**  | AOL PassProgram abuse, card data, skimmer tools   |
| Drug Manufacturing    | **Very Likely**  | GPS coordinates, communication logs, instructions |
| Check Washing         | **Likely**       | HTML platforms, chemical processing documents      |
| Pharmaceutical Theft  | **Partially Likely** | Pharmacy theft emails                            |

---

## ⏰ Timeline of Events

Events span from **2003 to 2008**:

- **2003**: Document creation begins  
- **2007**: Malware and credit card data activity spikes  
- **2008**: Identity change and execution of trojan

_(See `timeline/events-chronology.md` for full breakdown.)_

---

## 📊 Evidence Analysis

### 🔓 Password Recovery

| Document                  | Recovered Password |
|---------------------------|---------------------|
| SLIST.doc                 | `attica`            |
| Credit Numbers.doc        | `0utt0st3a1`        |
| X marks the spot.doc      | `camp`              |
| To-do List                | `M3th1sR1sky`       |

Method: Office2John.py → Hashcat → Dictionary & manual extraction

### 💀 Malware

- **Behavior**: Registry edits, command shell spawning, impersonating AIM installer  
- **Detection**: Initially undetected by 72 engines  
- **Result**: Confirmed trojan via hybrid and dynamic analysis

---

## ⚖️ Compliance and Legal Framework

- **Standards**:  
  - NIST 800-86  
  - ACPO Guidelines  
  - RIPA 2000  
- **Chain of Custody**:  
  Maintained across all investigation phases  
- **Legal Considerations**:  
  - Ethical handling  
  - Proper authorization  
  - Secure evidence storage

---

## 📋 Conclusions

| Crime                | Likelihood        | Supporting Evidence                    |
|----------------------|------------------|----------------------------------------|
| Credit Card Theft    | **Very Likely**  | Email, stolen card data, tools         |
| Drug Manufacturing   | **Very Likely**  | GPS docs, chat logs, operational plans |
| Check Washing        | **Likely**       | HTML, user logs, email exchanges       |
| Pharma Theft         | **Partially**    | Opportunistic, limited documentation   |

> This case demonstrates rigorous digital forensic process aligned with modern standards and legal expectations.

---
