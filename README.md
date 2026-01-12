<h1>SOC Automation Project</h1>

<h2>Description</h2>
This project simulates a real-world Security Operations Center (SOC) environment using Splunk as the SIEM to collect and analyze logs from a Windows 10 victim machine and a Kali Linux attacker. Multiple attack scenarios are manually executed to generate realistic security events, which are then investigated, correlated, and analyzed using Splunk searches, alerts, and dashboards.
<br />
<br >
The project follows an industry-aligned SOC workflow, starting with manual detection and incident investigation (failed logins, successful compromise, PowerShell abuse, and privilege escalation) before progressing toward SOAR automation using TheHive and Shuffle. Each attack is fully documented with detection logic, investigation steps, and incident-style reporting, demonstrating both Tier 1/Tier 2 SOC analyst skills and readiness for automated incident response.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Splunk</b> 
- <b>Shuffle</b>
- <b>TheHive</b> 
- <b>PowerShell</b>
- <b>Sysmon</b> 


<h2>Environments Used </h2>

- <b>Windows 11- Host Splunk (SOC Analyst)</b>
- <b>Windows 10- Splunk Clien VM</b>
- <b>Kali Linux- Attacker VM</b>

<h2>Key Highlights:</h2>

- <b>End-to-end SOC lab with Splunk SIEM log ingestion and analysis</b>
- <b>Simulated real-world attacks from Kali Linux → Windows 10</b>
- <b>Detection and investigation using Windows Event Logs</b>
- <b>Custom Splunk queries, alerts, and dashboards</b>
- <b>SOC-style incident analysis and reporting</b>
- <b>SOAR-ready design for future integration with TheHive and Shuffle</b>
