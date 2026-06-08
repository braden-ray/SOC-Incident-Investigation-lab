# SOC Incident Investigation Lab

## Overview
This project simulates and investigates suspicious endpoint and network activity in a Windows environment using blue team and SOC analyst methodologies. The lab focuses on identifying malicious behavior, analyzing logs, correlating evidence, and documenting findings using industry-relevant tools.

---

## Objectives
- Simulate suspicious activity in a Windows environment
- Analyze endpoint and network telemetry
- Identify indicators of compromise (IOCs)
- Investigate process execution and persistence mechanisms
- Document findings and remediation recommendations

---

## Tools Used
- Sysmon
- Wireshark
- Procmon
- Windows Event Viewer
- VirtualBox
- PowerShell

---

## Lab Environment
- Windows 10 Virtual Machine
- Isolated VirtualBox environment
- Sysmon logging enabled
- Network traffic capture using Wireshark

---

## Attack Simulation
The following suspicious activity was simulated within the lab environment:
- Suspicious PowerShell execution
- File download activity
- Outbound network communication
- Potential persistence behavior

---

## Investigation Process

### 1. Initial Detection
- Reviewed logs and identified suspicious process execution activity

### 2. Endpoint Analysis
Analyzed Sysmon and Event Viewer logs to investigate:
- Process creation
- Command-line execution
- File creation activity
- Scheduled task or persistence indicators

### 3. Network Analysis
Captured and analyzed network traffic using Wireshark to identify:
- DNS requests
- Outbound connections
- Suspicious communication patterns

### 4. Correlation & Findings
- Correlated endpoint and network evidence to determine the sequence of events
- Identified indicators of compromise and suspicious activity

---

## Findings
- Suspicious PowerShell activity identified
- Outbound network connections observed
- Suspicious file activity detected
- Event logs successfully correlated with network telemetry

---

## MITRE ATT&CK Mapping
- T1059 – Command and Scripting Interpreter: PowerShell
- T1105 – Ingress Tool Transfer
- T1053 – Scheduled Task/Job

---

## Remediation Recommendations
- Isolate affected host
- Remove malicious scheduled tasks or persistence
- Block suspicious domains/IP addresses
- Review PowerShell execution policies
- Perform credential reset if compromise is confirmed

---

## Screenshots
Screenshots and investigation evidence will be uploaded throughout the project.

---

## Skills Demonstrated
- SOC Investigation Workflow
- Threat Detection & Analysis
- Windows Event Log Analysis
- Network Traffic Analysis
- IOC Identification
- Incident Documentation
- MITRE ATT&CK Mapping
