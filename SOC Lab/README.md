# Sysmon & Splunk Home Lab

## Overview

This project documents the creation of a simple SOC (Security Operations Centre) home lab using Sysmon and Splunk Enterprise.

The lab was built to gain hands-on experience with endpoint monitoring, log collection, log forwarding, and security event analysis. Sysmon was installed on a Windows 10 virtual machine using the SwiftOnSecurity configuration, while Splunk Enterprise was installed on the host machine. A Splunk Universal Forwarder was used to send Sysmon logs from the virtual machine to Splunk for analysis.

## Lab Architecture

```text
Windows 10 VM
     │
     ▼
Sysmon (SwiftOnSecurity Config)
     │
     ▼
Windows Event Logs
     │
     ▼
Splunk Universal Forwarder
     │
     ▼
Splunk Enterprise
     │
     ▼
Log Analysis
```

## Objectives

- Gain hands-on SOC experience.
- Learn how Sysmon generates endpoint telemetry.
- Configure log forwarding with Splunk Universal Forwarder.
- Analyse Windows events using Splunk Enterprise.
- Develop basic SPL (Search Processing Language) skills.
- Understand how security analysts investigate endpoint activity.

## Technologies Used

- Windows 10 Pro
- Oracle VirtualBox
- Sysmon
- SwiftOnSecurity Sysmon Configuration
- Splunk Universal Forwarder
- Splunk Enterprise
