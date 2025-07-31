# Project 4 – Hunting Living-off-the-Land Binaries (LOLBins)

In this project, I will hunt for suspicious use of native Windows binaries (LOLBins) like `certutil`, `bitsadmin`, `mshta`, etc., using Sysmon logs. These tools are often abused by attackers to download payloads or execute code without dropping binaries.

## Objectives
- Emulate attacker behavior using known LOLBins.
- Capture and analyze process creation logs with Sysmon (Event ID 1).
- Build detections using command-line patterns or parent-child relationships.

## MITRE ATT&CK Mapping
- **T1218** – Signed Binary Proxy Execution
- **T1105** – Ingress Tool Transfer

## Outcome
- Understand how attackers evade antivirus by using built-in tools.
- Write detection rules for real-world techniques seen in the wild.
