# Examining the Security Posture of an Anti-Crime Ecosystem
**Author:** Jon “GainSec” Gaines  
**Original Version:** 1.0 Public Release (1.0PR) — 2025-11-05  
**Current Version:** 1.2 Public Release (1.2PR) — 2025-11-11  

**Contact:** whitepaper@gainsecmail.com

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17529424.svg)](https://doi.org/10.5281/zenodo.17529424)

---

## Overview
This repository hosts the public release of independent research into an anti-crime technology ecosystem, including a gunshot detection system, license plate readers, and compute modules.

It documents **51 findings**, 22 with assigned CVEs and an additional 8 pending assignment related but not limited to authentication, cryptography, and system design in an anti-crime technology ecosystem.

---

## Research Context
The majority of findings and supporting material were previously disclosed through informal full disclosure write-ups published on GainSec.com. Those earlier posts were technical and informal to facilitate timely awareness and community discussion, copies of the write-ups and technical summaries were also provided to the vendor during the responsible disclosure process.

While earlier publications included literal command strings and example values (full disclosure), this whitepaper and its accompanying materials have undergone purposeful redactions, both for findings that have completed their full disclosure windows and for those still pending, not yet submitted, or not planned for formal CVE assignment. These redactions ensure the research remains transparent, verifiable, and educational while minimizing any potential for misuse.

This repository serves as the authoritative, continuously maintained archive for the research. It consolidates previously released material into a formal, versioned whitepaper and will be updated as pending disclosures reach their full disclosure windows and as any follow on research is conducted.

---

## Responsible Disclosure
All devices were lawfully procured and tested in isolated lab environments. Findings were reported to the vendor following a responsible disclosure timeline. No production systems or networks were accessed or affected. Further details about the responsible disclosure process are available within the whitepaper.

**CVE coordination:** MITRE / NIST NVD  
**Disclosure window:** Feb 2025 → Feb 2026 (as of latest publication)  
**Vendor notified:** Flock Safety "The Vendor" (details provided in the whitepaper)

---

## Contents
- `/whitepaper` — PDF publication v1.2 Public Release (v1.2PR) 
- `/statement` — Formal distributable statement summarizing key findings and material facts  
- `/DISCLAIMER.md` — Legal and ethical testing notice, full detailed disclaimer is available within the whitepaper  
- `/defenders-checklist` — Full Defender’s Checklist referenced in Appendix C (comprehensive version for practitioners)  
- `LICENSE` — Combined Creative Commons / Research Use license terms

---

## Citation
If you reference this research, please cite as:

> Gaines, Jon. *Examining the Security Posture of an Anti-Crime Ecosystem.* GainSec Research, v1.2PR Public Release, 2025.  
> DOI: [10.5281/zenodo.17529424](https://doi.org/10.5281/zenodo.17529424)

---

## Legal Notice
This repository and its contents are provided for **defensive security, academic, and public interest research**.  
Do not attempt to reproduce any procedure or test on systems you do not own or have explicit written authorization to assess.  
All operational details and sensitive technical data capable of facilitating exploitation have been purposefully redacted.
Full Disclaimer can be found within the white paper.

---

## Informal Technical Write-ups

- [Part 1: Bird Hunting Season – Security Research on Flock Safety’s Anti-Crime Systems](https://gainsec.com/2025/06/19/bird-hunting-season-security-research-on-flock-safety-anti-crime-systems/)
- [Part 2: Plucked and Rooted – Device 1: Debug Shell on Flock Safety’s Raven Gunshot Detection System](https://gainsec.com/2025/06/19/plucked-and-rooted-device-1-debug-shell-on-flock-safetys-raven-gunshot-detection-system/)
- [Part 3: Grounded Flight – Device 2: Root Shell on Flock Safety’s Falcon/Sparrow Automated License Plate Reader](https://gainsec.com/2025/06/19/grounded-flight-device-2-root-shell-on-flock-safetys-falcon-sparrow-automated-license-plate-reader/)
- [Part 4: Trap Shooter – Flock Safety Sniffer & Alarm](https://gainsec.com/2025/06/30/trap-shooter-tiny-flock-safety-sniffer-alarm/)
- [Part 5: Root from the Coop – Device 3: Root Shell on Flock Safety’s Picard/Bravo Compute Box](https://gainsec.com/2025/09/19/root-from-the-coop-device-3-root-shell-on-flock-safetys-bravo-compute-box/)
- [Part 6: Fly-By – Device 2: The Falcon/Sparrow – Gated Wireless RCE, Camera Feed, DoS, Information Disclosure and More](https://gainsec.com/2025/09/27/fly-by-device-2-the-falcon-sparrow-gated-wireless-rce-camera-feed-dos-information-disclosure-and-more/)
- [Part 7: Button Presses to Wireless RCE: Shell on Flock Safety’s License Plate Cameras Over Wi-Fi](https://gainsec.com/2025/09/27/button-presses-to-shell-on-flock-safety-license-plate-cameras-over-wi-fi/)
- [Part 8: Formalizing my Flock Safety Research](https://gainsec.com/2025/11/05/formalizing-my-flock-safety-security-research/)
- [Part 9: BirdEye - Tool to Test Flock Safety’s ML Visual Recognition Models](https://gainsec.com/2025/11/12/birdeye/)
