Splunk Log Analysis Project
Overview
This Project focus on Log Analysis using Splunk to identify and analyse system logs forpotential issuses or patterns. Logs are crucial for trouble shooting and monitoring the health of systems, and Splunk is an Industry leading tools for parsing, analysing and visualizing log data.
Objectives
To use Splunk to analyse System Logs and Application Logs.
To identify suspicious pattern or anomalies that may indicate security issues.
To visualize the findings through Splunk dashboards.
Tools Used 
Splunk for analyzing and visualizing logs.
Systewm logs (e.g dpkg.log, syslog, etc) from a Kali Linux system.
Kali Linux as the environment for Log Analyses.
Key Findings
Analyses of the dpkg.log provided insight into package installation activities, which can help track system changes.
The logs revealed patterns of system update and package management, which are essential for monitoring security update and changes.
Project walkthrough.
Data Collection: Logs were collected from the /var/log directory on Kali Linux machine.
Log Analyses with Splunk: Splunk was used to index and analyse the logs. This step involves parsing logs to identify useful patterns.
Visualisation: Key findings were displayed through Splunk dashboard, highlighting any suspicious activities.
Conclusion
This Project demonstrated how Splunk can be a powerful tool for Log analyses, allowing you to quickly identify patterns and anomalies in system and application logs. It's an essential skill for SOC analysts to be able to use Splunk for effective monitoring and threat protection.
### SCREENSHOTS
NAVIGATING TO /var/log on Kali Linux:
![Navigating to /var/log](https://raw.githubusercontent.com/iphyboi/splunk-project/main/IMG_7855.JPG)
