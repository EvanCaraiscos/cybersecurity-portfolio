# A5 - Cryptographic Implementation Used Online

## Overview
SSL/TLS certificates were examined across 5 websites to 
discover how cryptography is used to secure online 
communications. Each certificate was viewed directly in 
the browser certificate viewer.

## Certificates Examined

| Site | Issued By | Algorithm | Expires |
|---|---|---|---|
| lms.uwa.edu.au | Amazon RSA 2048 M02 | RSA 2048 / SHA-256 | Jul 2026 |
| www.ato.gov.au | DigiCert (ECC SHA384) | ECC / SHA-384 | Oct 2026 |
| *.google.com | Google Trust Services | SHA-256 | Jun 2026 |
| www.bankwest.com.au | DigiCert EV RSA CA G2 | RSA / SHA-256 | Sep 2026 |
| www.cloudflare.com | Google Trust Services | SHA-256 | Jun 2026 |

## Key Observations
- UWA LMS is hosted on Amazon infrastructure
- ATO uses ECC (more modern than RSA)
- Bankwest uses an EV certificate (extended validation)
- Google issues its own certificates via Google Trust Services
- All certificates use SHA-256 or stronger for fingerprinting
- Certificate validity periods are all under 13 months

## Screenshots
cert1.png through cert5.png
