# Project 02 – Digital Footprint Assessment of Deel

📄 **Full Investigation Report (PDF):**
[Download the complete report](./Deel_Digital_Footprint_Assessment.pdf)

---

## Overview
This project presents an Open-Source Intelligence (OSINT) assessment of Deel's publicly exposed digital footprint. The objective was to map the organization's online presence, identify publicly accessible infrastructure, analyze its technology stack, evaluate its external security posture, and assess potential areas of exposure using only passive intelligence collection techniques.

The investigation follows a structured intelligence methodology similar to those used in threat intelligence and corporate investigations, relying exclusively on publicly available information.

---

## Objectives

- Map Deel's publicly exposed infrastructure
- Identify corporate and technical assets
- Analyze domain registration and ownership
- Examine hosting infrastructure and technologies
- Assess external security posture
- Evaluate potential attack surface
- Produce an intelligence-style assessment based solely on OSINT

---

## Investigation Scope

The investigation included:

- Corporate profile
- Digital footprint mapping
- Domain registration analysis
- DNS and hosting infrastructure
- Technology stack identification
- Security configuration assessment
- Threat assessment
- Intelligence conclusions

---

## Methodology

Information was collected exclusively through passive reconnaissance and publicly available sources.

The investigation followed these stages:

1. Corporate profiling
2. Domain registration analysis
3. Infrastructure mapping
4. Technology fingerprinting
5. Security posture assessment
6. Threat assessment
7. Intelligence analysis

No intrusive techniques, vulnerability exploitation, authentication attempts, or active scanning against the target infrastructure were performed.

---

## Tools Used

- VirusTotal
- URLScan.io
- SecurityHeaders
- MXToolbox
- BuiltWith
- Shodan
- ICANN Lookup
- Public WHOIS records

---

## Key Findings

### Corporate Footprint

- Established multinational HR technology company
- Global operational presence
- Mature digital infrastructure
- Strong public brand visibility

### Infrastructure

- Primary infrastructure protected by Cloudflare
- Amazon Registrar used for domain registration
- Multiple subdomains supporting business operations
- Well-organized DNS architecture

### Technology Stack

The investigation identified the use of technologies including:

- Cloudflare
- HubSpot
- Google Tag Manager
- Cookiebot
- jsDelivr

These technologies support security, analytics, marketing automation, and content delivery.

### Security Posture

The external security posture appears mature.

Positive findings included:

- HTTPS enforced
- HSTS enabled
- X-Frame-Options configured
- X-Content-Type-Options configured
- SPF, DKIM and DMARC implemented
- No blacklist detections
- No publicly exposed critical services identified

Areas for improvement:

- Content Security Policy (CSP) not implemented
- Permissions Policy header absent

---

## Intelligence Assessment

The collected evidence suggests that Deel maintains a mature and professionally managed external infrastructure consistent with a global SaaS organization.

The observed technologies, hosting architecture, and security controls indicate a strong focus on availability, scalability, and protection against common web-based threats.

No indicators of compromise, malicious infrastructure, or publicly observable critical security weaknesses were identified during the investigation.

---

## Skills Demonstrated

- Open-Source Intelligence (OSINT)
- Digital Footprint Mapping
- Infrastructure Analysis
- Domain Intelligence
- Technology Fingerprinting
- Security Posture Assessment
- Threat Analysis
- Intelligence Reporting

---

## Full Investigation

The complete intelligence report, including detailed analysis, screenshots, methodology, figures, and references, is available in:

**📄 `Deel_Digital_Footprint_Assessment.pdf`**

---
