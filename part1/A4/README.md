# A4 - Discover a Vulnerable Website

## Overview
A vulnerable web interface was discovered using Shodan
during the A13 online security tools activity.

## Target
- **IP:** 202.65.83.164
- **Device:** Dahua Technology IP Camera
- **Location:** Perth, Australia
- **ISP:** Superloop (Australia) Pty Ltd

## Vulnerabilities Identified
- No HTTPS — login page served over plain HTTP
- Web interface publicly exposed to the internet
- No evidence of access restrictions (no IP whitelist)
- Default login page accessible to anyone

## Evidence
- Screenshots from A13 (web-4a.png, web-4b.png)
- Discovered via Shodan search: city:Perth port:80
