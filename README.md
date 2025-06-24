# Elevate Labs Task 2: Phishing Email Analysis

## Overview
This repository contains deliverables for Day 2 of the Elevate Labs Cybersecurity Internship (June 24, 2025). The task involves analyzing a sample phishing email to identify phishing characteristics and develop threat detection skills.

## Task Details
- **Objective**: Identify phishing indicators in a sample email.
- **Tools Used**:
  - `nano` and `gedit` for viewing `.eml` file.
  - [MxToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx).
  - [VirusTotal](https://www.virustotal.com) for URL analysis.
  - [PhishTool](https://www.phishtool.com) for complete email analysis.
  
- **Sample**: `sample-1187.eml` provided for analysis.
- **Deliverables**:
  - `phishing_analysis_report.md`: Detailed report of findings.
  - `sample-1187.eml`: Sample email.
  - `notes.md`: My findings.
  - `Screenshots/MxTool_Header_analysis.png`: Header analysis output.
  - `Screenshots/suspicious_link.png`: Suspicious link image
  - `Screenshots/VT_scan.png`: VirusTotal scan of suspicious link

## Findings
- Spoofed sender (`notification@proton.me` via `jbkellyjowl@gmail.com`).
- Header discrepancies (SPF/DKIM for `gmail.com`, spam/phishing flags).
- Malicious link (`https://danielcacereslopez.com/...`).
- Urgent language (“avoid shutdown”) and spelling errors (“log in”).

## Instructions to Review
- Read `phishing_analysis_report.md` for detailed analysis.
- View `Screenshots/` for visual evidence.
- Check `sample-1187.eml` in a text editor.

## Portfolio
This task is part of my Elevate Labs internship portfolio: [Elevate-Labs-Internship-Tasks](https://github.com/Nucl3arAt0m/Elevate-Labs-Internship-Tasks).
