# Project 01 – Bank of America Phishing Infrastructure Investigation

## Overview

This project presents a complete Open-Source Intelligence (OSINT) investigation into a phishing domain impersonating **Bank of America**. The investigation began after the identification of **bank-of-america.directhr.cn**, a publicly reported phishing domain detected by multiple security vendors.

Rather than relying solely on reputation-based detections, the objective was to determine whether the observed phishing activity represented a dedicated malicious infrastructure or the abuse of a legitimate organization's digital environment.

The investigation combined multiple intelligence disciplines, including infrastructure analysis, DNS analysis, domain registration research, IP reputation assessment, certificate transparency analysis, technology fingerprinting, and organizational validation. Throughout the investigation, each finding was correlated to continuously reassess the initial hypothesis and produce an evidence-based intelligence assessment.

The final assessment concluded that although phishing activity had been observed under the investigated domain, the broader infrastructure exhibited characteristics consistent with a legitimate and professionally maintained organization. This investigation demonstrates the importance of validating technical indicators through contextual intelligence before reaching attribution or risk conclusions.

---

# Investigation Objectives

- Investigate a publicly reported phishing domain.
- Identify the infrastructure supporting the observed activity.
- Determine whether the infrastructure is malicious or part of a legitimate environment.
- Validate the associated organization using publicly available information.
- Produce an evidence-based intelligence assessment supported by multiple independent OSINT sources.

---

# Investigation Methodology

The investigation followed a structured intelligence workflow:

```
Target Selection
        ↓
Domain Analysis
        ↓
Infrastructure Analysis
        ↓
Website Analysis
        ↓
Organizational Validation
        ↓
Intelligence Assessment
        ↓
Recommendations
```

Rather than relying on a single technical indicator, each stage contributed additional context, allowing the initial hypothesis to be continuously reassessed as new intelligence was collected.

---

# Tools Used

| Category | Tools |
|----------|------|
| Threat Intelligence | VirusTotal |
| Domain Registration | Whois |
| DNS Analysis | DNSChecker |
| Infrastructure Analysis | Shodan |
| IP Reputation | AbuseIPDB |
| Certificate Transparency | crt.sh |
| Technology Fingerprinting | BuiltWith |

---

# Key Findings

- Identified a phishing subdomain impersonating Bank of America.
- Confirmed that the investigated asset belonged to the larger **directhr.cn** infrastructure.
- Discovered a mature infrastructure hosted on Amazon Web Services (AWS).
- Verified continuous domain registration since 2008.
- Identified professionally managed DNS, SSL/TLS, and email configurations.
- Validated the legitimacy of the organization through OSINT.
- Determined that the available evidence did not support attributing malicious activity to the organization itself.

---

# Intelligence Value

This investigation demonstrates a core principle of intelligence analysis: **initial hypotheses should be continuously challenged as new evidence becomes available.**

Although the investigation began with strong phishing indicators, infrastructure analysis, organizational validation, and technical correlation produced a substantially different assessment than initially expected. The case highlights the importance of combining technical evidence with contextual intelligence rather than relying exclusively on reputation-based detections.

The project demonstrates practical experience in:

- Open-Source Intelligence (OSINT)
- Infrastructure Analysis
- Threat Intelligence
- Digital Footprint Analysis
- Domain Investigation
- Intelligence Reporting
- Analytical Reasoning
- Evidence Correlation

---

# Investigation Report

📄 **Full Investigation Report**

👉 [Project_01_Bank_of_America_Phishing_Infrastructure_Investigation.pdf](Project_01_Bank_of_America_Phishing_Infrastructure_Investigation.pdf)

---
