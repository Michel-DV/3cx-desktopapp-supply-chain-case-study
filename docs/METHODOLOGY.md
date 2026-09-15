# Methodology

## Research model

CASE-003 is reconstructed as a chain of trust transitions rather than a malware-family catalog. The analysis separates: (1) initial access, (2) corporate intrusion, (3) build-pipeline compromise, (4) malicious release distribution, (5) first-stage execution, (6) reconnaissance and victim selection, and (7) selective follow-on activity.

## Evidence priority

1. Incident-response findings from Mandiant and 3CX.
2. Public-sector malware analysis from CISA.
3. First-wave reverse engineering from SentinelLabs, Volexity, and CrowdStrike.
4. Retrospective analytical conclusions only where they are consistent with the primary evidence.

## Confidence language

- **Confirmed** — explicitly documented by primary incident-response or vendor evidence.
- **Strongly supported** — independently reproduced or consistent across multiple technical analyses.
- **Analytical conclusion** — derived from the confirmed chain and clearly marked as interpretation.
- **Unknown** — not established by the public evidence set.

## Safety and reproducibility

The publication focuses on architecture, detections, and trust boundaries. It intentionally avoids distributing weaponized payloads or operational instructions for compromising third-party software supply chains. The PDF is generated from version-controlled HTML/CSS and checksummed in CI.
