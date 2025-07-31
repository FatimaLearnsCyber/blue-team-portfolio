# Project 2 – Brute Force Detection (Windows Logs + Sigma)

In this project, I will simulate a brute force attack from my Kali Linux VM against my Windows 11 VM. The goal is to generate multiple failed logon events (Event ID 4625) and create a detection rule that identifies this behavior.

## Objectives
- Generate multiple failed login attempts using tools like Hydra.
- Capture the relevant Windows Event Logs.
- Create a detection rule using Sigma or native Wazuh.
- Confirm alerts and document triage steps.

## MITRE ATT&CK Mapping
- **T1110** – Brute Force

## Outcome
- Learn how to detect brute force login attempts using logs and correlation rules.
- Build a detection use case based on real telemetry.
