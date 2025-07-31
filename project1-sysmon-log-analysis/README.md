# Project 1 – Sysmon Log Analysis (Windows 11)

##  Objective
Deploy Sysmon on a Windows 11 VM and collect detailed event logs such as:
- Process creation
- Network connections
- PowerShell execution

This helps build visibility into endpoint activity.

##  Tools
- Sysmon (with SwiftOnSecurity config)
- Event Viewer
- Log analysis (manual, later SIEM)

##  Detection Goals
- Identify suspicious parent-child process relationships
- Detect obfuscated PowerShell or unusual script activity
- Understand baseline vs. anomaly in Windows logs

##  Outcome
Learn to analyze logs without relying on a SIEM first. This project builds the foundation for later rule writing (Sigma/Wazuh).
