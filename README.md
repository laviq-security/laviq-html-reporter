# Laviq HTML Reporter

> **Transparency by Design.** This repository contains the UI logic used to generate Laviq's human-readable audit reports. 

## Overview
Laviq believes that cryptographic evidence should be defensible and accessible. While our **Runtime Truth Engine** (the eBPF-based collector) is commercial, we have open-sourced the reporter UI to allow security teams and auditors to:

1. **Audit the Presentation:** See exactly how runtime evidence is mapped to UI elements.
2. **Customize the Output:** Modify templates to fit internal compliance formats (NSA, CCCS, etc.).
3. **Local-First:** Ensure that even the reporting layer remains entirely offline-capable.

## Features
- **Self-Contained:** Generates a single-file HTML report with no external dependencies.
- **Process Context:** Visualizes the process hierarchy and library load paths.
- **Forensic Timeline:** Displays the correlation between network triggers and cryptographic execution.
- **Remediation Roadmap:** Automatically generates actionable steps based on the `laviq-trust-matrix`.

## Usage
This reporter is designed to consume the JSON artifacts produced by the Laviq Agent.
*(Coming soon: CLI documentation for standalone report generation)*

## License
Apache-2.0
