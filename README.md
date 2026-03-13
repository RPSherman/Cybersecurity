# SOC Investigation Project: Brute Force Login Attack

## Project Overview
This project simulates a Security Operations Center (SOC) investigation into a brute-force login attack. The goal is to analyze authentication logs, identify suspicious activity, and document findings using standard SOC investigation techniques.

## Scenario
Multiple failed login attempts were detected on a Windows system. The SOC analyst must investigate the logs to determine whether the activity represents a brute-force attack.

## Tools Used
- Windows Event Viewer
- Splunk (SIEM)
- MITRE ATT&CK Framework
- OSINT tools

## Skills Demonstrated
- Security log analysis
- Alert triage
- Incident investigation
- IOC identification
- MITRE ATT&CK mapping

## Investigation Steps
1. Review Windows Security Event Logs
2. Identify repeated authentication failures
3. Correlate login attempts by IP address
4. Investigate suspicious login patterns
5. Document indicators of compromise

## Key Findings
- Multiple failed login attempts detected
- Repeated authentication failures from the same IP address
- Activity consistent with brute-force login attack

## MITRE ATT&CK Mapping
Technique: T1110 – Brute Force

## Recommended Mitigation
- Implement account lockout policies
- Enable security monitoring alerts
- Monitor authentication logs for suspicious activity
