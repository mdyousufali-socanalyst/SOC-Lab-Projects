Project 02 – Windows Failed Login Detection with Wazuh
Objective

Monitor and detect failed Windows authentication attempts using Wazuh SIEM by analyzing Windows Security Event Logs. The goal was to identify unauthorized access attempts and establish a foundation for brute-force attack detection.

Lab Environment
Wazuh Server
Windows 10 Endpoint
Wazuh Agent
Windows Security Event Logs
Tasks Performed
Installed and configured Wazuh Agent on Windows 10
Enabled Windows Audit Policy for logon failure events
Verified Security Event Log ingestion into Wazuh
Generated multiple failed authentication attempts
Investigated failed login events in the Wazuh Dashboard
Filtered and analyzed Event ID 4625 records
Key Event Details
Event ID: 4625
Event Type: Failed Logon
Log Source: Windows Security Logs
Detection Platform: Wazuh SIEM
Authentication Package: Negotiate
Investigation Findings
Failed authentication attempts were successfully captured and indexed
Wazuh collected relevant login failure details including timestamps and source host information
Authentication failure events were visible within the Threat Hunting module
Log ingestion and event monitoring were validated successfully
Security Relevance

Repeated Event ID 4625 occurrences may indicate:

Brute-force attacks
Password spraying attempts
Unauthorized access attempts
User credential misuse
MITRE ATT&CK Mapping
T1110 – Brute Force
T1110.003 – Password Spraying
Results

The detection workflow successfully identified failed login attempts and demonstrated Wazuh's capability to monitor authentication-related security events in real time.

Screenshots

Screenshots of the Wazuh dashboard and Event ID 4625 logs are included in this repository.

Conclusion

This project demonstrated the implementation of Windows authentication monitoring with Wazuh SIEM. The lab provided hands-on experience in log collection, event analysis, and detection of suspicious login activity relevant to SOC Analyst operations.
