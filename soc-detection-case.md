# 🔍 SOC Detection Case Study

## Scenario
Simulated a Command & Control (C2) communication using DNS-based beaconing.

## Log Sources
- Sysmon logs
- DNS query logs
- Network traffic logs

## Detection Approach
- Identified repeated outbound DNS queries to suspicious domains
- Observed abnormal frequency compared to baseline behavior
- Correlated process execution with network activity

## Findings
- Detected potential C2 activity (MITRE T1071)
- Suspicious process initiating external communication

## Tools Used
- Wazuh SIEM
- Sysmon
- VirusTotal

## Outcome
- Successfully flagged malicious behavior
- Reduced false positives using confidence scoring logic
