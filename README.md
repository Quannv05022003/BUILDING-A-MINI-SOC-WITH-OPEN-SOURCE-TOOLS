Mini SOC with Open-Source Tools
Overview

This project focuses on building a Mini Security Operations Center (SOC) using open-source tools for monitoring and detecting post-exploitation attacks in a Windows Active Directory environment.

The project simulates lateral movement techniques and security monitoring workflows using Wazuh SIEM, Sysmon and pfSense.

Objectives
Build a centralized SIEM monitoring environment
Detect post-exploitation and lateral movement activities
Improve visibility using Sysmon telemetry
Correlate security events using Wazuh
Map detections to the MITRE ATT&CK Framework
Technologies Used
Wazuh SIEM
Sysmon
pfSense
Ubuntu Server
Windows Server
Active Directory
Kali Linux
VMware
Attack Techniques Simulated
Brute Force
Credential Dumping (LSASS)
Pass-the-Hash
PsExec Lateral Movement
WinRM Abuse
UAC Bypass
MITRE ATT&CK Techniques
T1548.002 – UAC Bypass
T1003.001 – LSASS Memory
T1550.002 – Pass-the-Hash
T1021.002 – PsExec
T1021.006 – WinRM
T1003.003 – NTDS.dit Extraction
Lab Architecture

The lab environment includes:

Windows Domain Controller
Windows Client
Kali Linux Attacker
Ubuntu Wazuh Server
pfSense Firewall with VLAN Segmentation
Features
Centralized log collection
Security event correlation
Custom Wazuh detection rules
Sysmon telemetry monitoring
MITRE ATT&CK mapping
Lateral movement detection

Author
Nguyen Viet Quan
