# A8 - Cryptography Used in IoT Devices

## Overview
Cryptographic implementations discovered in use 
across Internet of Things devices.

## Implementations Covered

| Device/Protocol | Cryptography Used |
|---|---|
| Smart home hubs (e.g. Google Nest) | TLS, AES-128 |
| WiFi routers (WPA3) | SAE, AES-CCMP |
| Smart locks | AES-128, Bluetooth LE pairing |
| RFID/NFC devices | AES, 3DES |
| IP Cameras | TLS (often misconfigured) |

## Notes
The Dahua camera found in A13 via Shodan is a real
example of an IoT device with weak/absent cryptographic
implementation — no HTTPS, exposed login page.

## References
- https://www.iotsecurityfoundation.org
- https://www.nist.gov/topics/internet-things-iot
