# NETWORKWALKS-B083-Week2
2nd Week Work on Cybersecurity Internship Program

Week 2 Penetration Testing & Reconnaissance Report
Overview
This repository contains the Week 2 deliverables and final report documenting passive and active reconnaissance activities conducted against authorized target domains. The assessment focuses on identifying asset footprints, technological stacks, and potential exposure to establish baseline security hygiene and risk profiles.

Scope & Target Assessment
Reconnaissance and fingerprinting operations were performed across the following scope:

Primary Domains Evaluated: networkwalks.com, microsoft.com

Methodology: Passive OSINT collection, DNS enumeration, technology stack fingerprinting, and non-intrusive active network mapping.

Methodology & Tools Used
Domain & Ownership Analysis: WHOIS registration lookup and DNS record analysis.

Technology Stack Fingerprinting: WhatWeb for web server, framework, and CMS identification.

OSINT & Intelligence Gathering: theHarvester for email, subdomain, and public endpoint harvesting.

Network & Port Scanning: Zenmap / Nmap for service discovery and port state mapping.

Key Findings & Risk Summary
Findings from this week's assessment have been categorized into a structured risk matrix:

Medium Severity:

Exposure of administrative or staging endpoints identified during subdomain enumeration.

Detailed service version disclosures enabling targeted exploit research.

Low Severity / Informational:

Publicly available DNS and WHOIS records detailing organizational assets.

Absence or misconfiguration of non-critical HTTP security response headers.

Remediation Roadmap
Asset Management: Enforce strict access controls and hide unnecessary public-facing staging/subdomain endpoints.

Information Disclosure Control: Suppress verbose web server banners and software version details.

Security Headers: Implement missing security headers (e.g., HSTS, X-Content-Type-Options, Content-Security-Policy).

Repository Contents
W2-PM-Final Report-Christ.pdf — Complete final report document including detailed findings, scan outputs, and executive summary.
