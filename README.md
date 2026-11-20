# DMARC, SPF and DKIM Guardian | TAVARDT United Kingdom

[![Technical Audit](https://img.shields.io/badge/TAVARDT-Email%20Security-5b3cf5.svg)](https://tools.tavardt.com/uk/dmarc-checker/)
[![Jurisdiction](https://img.shields.io/badge/Jurisdiction-United%20Kingdom-00C853.svg)](https://ag.tavardt.com/uk/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

DNS email authentication auditor for spoofing prevention, phishing mitigation, and technical compliance with NCSC guidelines and Cyber Essentials.

Developed and maintained by the cybersecurity and infrastructure defense division of **[TAVARDT United Kingdom](https://ag.tavardt.com/uk/)**.

---

## Features and Verification Capabilities

* **DMARC Policy Enforcement**: In-depth inspection of enforcement directives (reject, quarantine, and none), subdomain policy (sp), and percentage enforcement rate (pct).
* **SPF Record Audit**: Validation of authorized sender mechanisms, DNS query lookup limits, and strict enforcement qualifiers (-all vs ~all).
* **DKIM Signature Verification**: Cryptographic public key verification across specified DNS selectors.
* **Forensic and Aggregate Reporting**: Verification of aggregate (rua) and forensic (ruf) feedback loops.
* **Regulatory and Standards Compliance**: Designed in alignment with NCSC Email Security Standards, Cyber Essentials, and UK GDPR.

---

## Installation and Quick Start

Requires Python 3.8 or higher. Built strictly using the Python standard library with zero external dependencies.

```bash
git clone https://github.com/TAVARDT-UK/dmarc-spf-guardian-uk.git
cd dmarc-spf-guardian-uk
python guardian.py company.co.uk
```

To test a specific DKIM selector or export results in structured JSON format:

```bash
python guardian.py company.co.uk --selector mail --json
```

---

## Online Web Diagnostics

For continuous perimeter monitoring and graphical reporting, access the official web diagnostic suite:

* **[DMARC and Email Authentication Checker](https://tools.tavardt.com/uk/dmarc-checker/)**
* **[TAVARDT United Kingdom Corporate Portal](https://ag.tavardt.com/uk/)**

---

## Enterprise Defense Consulting

For dedicated cybersecurity architecture, threat modeling, and incident readiness in United Kingdom, contact **[TAVARDT United Kingdom](https://ag.tavardt.com/uk/contact/)**.
