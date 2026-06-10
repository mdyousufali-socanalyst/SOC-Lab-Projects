# Project 02 - Windows Failed Login Detection with Wazuh

## Objective

Detect and monitor failed Windows login attempts using Wazuh SIEM to identify potential brute-force attacks and unauthorized authentication activities.

## Lab Environment

* Wazuh Server
* Windows 10 Endpoint
* Wazuh Agent
* Windows Security Event Logs

## Tasks Performed

* Configured Windows Audit Policy for failed logon events
* Verified Windows Security Log collection through Wazuh Agent
* Generated multiple failed login attempts for testing
* Monitored authentication events in Wazuh Dashboard
* Analyzed Event ID 4625 logs in Threat Hunting
* Validated log ingestion and event visibility

## Results

* Failed login attempts were successfully captured
* Event ID 4625 was detected and logged by Wazuh
* Authentication failure events were visible in the dashboard
* Log collection and monitoring were functioning correctly
* Security event monitoring was successfully validated

## Screenshots

See attached screenshots inside this project folder.

## Conclusion

Successfully configured and tested Windows failed login detection using Wazuh SIEM. The lab demonstrated the ability to collect, monitor, and analyze authentication failure events, providing a foundation for brute-force attack detection, threat hunting, and SOC monitoring activities.
