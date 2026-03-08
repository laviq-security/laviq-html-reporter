# Laviq HTML Reporter 📊

> **The Forensic UI for Runtime Cryptography.** This repository contains the engine used to transform Laviq's raw runtime evidence into audit-ready, human-readable reports.

## Overview
Laviq's **Runtime Truth Engine** captures deep execution traces from Linux environments. This reporter takes that structured JSON evidence and generates a standalone, forensic HTML report—designed to be shared with CISOs, auditors, and engineering leads.

While our eBPF-based collection agent remains commercial, we have open-sourced the reporter to ensure transparency in how evidence is visualized and communicated.

## Key Capabilities
- **Forensic Visualization:** Maps process hierarchies, network triggers, and cryptographic execution into a single timeline.
- **Root Cause Attribution:** Displays userspace stack traces to help developers pinpoint exactly where vulnerable crypto is invoked.
- **Compliance Mapping:** Automatically styles findings based on the `laviq-trust-matrix` for NSA CNSA 2.0 and CCCS ITSM.40.001 standards.
- **Air-Gapped Ready:** Generates a single, zero-dependency HTML file that can be viewed in offline/secure environments.

## Status: Stealth MVP
This repository is currently being populated with our production templates. 

## License
Apache License 2.0
