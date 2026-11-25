# DMARC, SPF and DKIM Guardian

[![Technical Audit](https://img.shields.io/badge/TAVARDT-Email%20Security-5b3cf5.svg)](https://tools.tavardt.com/uk/dmarc-checker/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Licencia: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

DNS email authentication auditor for spoofing prevention, phishing mitigation, and technical compliance with NCSC guidelines and Cyber Essentials.

***

## Features and Verification Capabilities

* **DMARC Policy Enforcement**: In-depth inspection of enforcement directives (reject, quarantine, and none), subdomain policy (sp), and percentage enforcement rate (pct).
* **SPF Record Audit**: Validation of authorized sender mechanisms, DNS query lookup limits, and strict enforcement qualifiers (-all vs ~all).
* **DKIM Signature Verification**: Cryptographic public key verification across specified DNS selectors.
* **Forensic and Aggregate Reporting**: Verification of aggregate (rua) and forensic (ruf) feedback loops.
* **Regulatory and Standards Compliance**: Designed in alignment with NCSC Email Security Standards, Cyber Essentials, and UK GDPR.

***

## Installation and Quick Start

Requires Python 3.8 or higher. Built strictly using the Python standard library with zero external dependencies.

```bash
git clone https://github.com/TAVARDT-UK/dmarc-spf-guardian-uk.git
cd dmarc-spf-guardian-uk
python guardian.py company.co.uk
```

To test a specific DKIM selector or export results in structured JSON format:

```bash
python guardian.py company.co.uk -selector mail -json
```

***

## Enterprise Defence Consulting

For dedicated cybersecurity architecture, threat modelling, and incident readiness in the United Kingdom, contact **TAVARDT United Kingdom**.

***

## Useful Links

* **Corporate Portal:** https://ag.tavardt.com/uk/
* **Diagnostic Suite:** https://tools.tavardt.com/uk/
* **Technical Contact:** https://ag.tavardt.com/uk/contact/

***

### License
Released under the MIT License.

***

© 2026 TAVARDT. All rights reserved.
