# 3CX DesktopApp Supply-Chain Compromise — v1.0.0

Initial public release of **CASE-003** in the Michel-DV Threat Case Studies series.

This publication reconstructs the 2023 3CX DesktopApp incident as a **cascading software-supply-chain compromise**: a trojanized X_TRADER package compromised a 3CX employee, access moved through corporate identity and internal systems into Windows and macOS build environments, and malicious signed 3CX releases were then distributed to downstream customers.

## Included

- X_TRADER / VEILEDSIGNAL initial intrusion path
- corporate VPN entry and lateral movement
- Fast Reverse Proxy use inside 3CX
- TAXHAUL / COLDCAT persistence on Windows build infrastructure
- POOLRAT persistence on the macOS build environment
- malicious `ffmpeg.dll` / `libffmpeg.dylib` release chains
- GitHub-hosted ICO routing and staged C2 discovery
- ICONICSTEALER reconnaissance and victim selection
- exposure vs confirmed exploitation model
- UNC4736 attribution with confidence boundaries
- response and trust-restoration analysis
- representative MITRE ATT&CK mapping
- original trust-boundary reconstruction
- original detection hypotheses
- safe Red Team / research emulation notes
- primary-source evidence trail

## Publication status

**v1.0.0 is the final analytical edition of CASE-003.** Future changes should be limited to factual corrections, broken references, or material new evidence.

**Author:** @Michel-DV  
**License:** CC BY-NC-ND 4.0  
**Publication date:** 15 September 2026
