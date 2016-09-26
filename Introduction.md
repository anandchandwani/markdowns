##INTRODUCTION

<p>Kustodian has spoken with a variety of its customer in a series of collaborated workshops on the problems with existing commercial SIEM solutions as well as Open source options. The biggest complaint about commercial SIEM’s was the ongoing licence fees, high costs and sizing limitations. The complaints for open source was it required thousands of development hours, documentation integrations that it wasn’t turnkey. Security professionals needed a working product not a framework and support options were just as expensive as the commercial products.</p> 

<p>Kustodian has chosen Elastic’s ELK for the SIEM’s base. ELK by itself does not provide a SIEM but is a perfect base to build a SIEM using fantastic frameworks out there. These include OSINT from CriticalStack/SIEMonster, OSSEC Wazuh fork, 411 Alerting & Data Correlation UI,  community rulesets and dashboards, community and open source free plugins that make the SIEM.</p>

<p>Based on these workshops Kustodian have built and open source SIEM solution to meet companies Informational Assurance visions without the development or ongoing cost but support options are available to clients to need assistance or custom dashboards. SIEMonster can exist both in the cloud such as AWS or in the clients existing Data Centre. Some of our clients were restricted in housing data offshore, so we catered for both. SIEMonster has the following benefits.</p>

* Fully Open Source SIEM 
* No License restrictions such as node or data limitations
* Open Community for additional features
* Completely free unless you require Enterprise Support (custom dashes etc)
* On premise hosted Security Analytics and SIEM Open SOC or Cloud Hosted
* Instant Incident Alerting via email or SMS or Console view via a secure portal and integration 
  with “Slack”/”Hipchat” using 411 Streams.
* Provide continuous Cyber Security monitoring identify, mitigate & respond to internal and  
  external risks in real time
* Full ISMS suite of documentation including Detailed Designs, Build Guides, Maintenance and 
  Standard Operating Procedures etc.
* Full integration with OSSEC Wazuh fork for Host Intrusion Detection and PCIDSS ruleset   
  incorporated into Elastic
* Threat Intelligence using open source OSINT Critical stack and Intelligence feeds
* Incorporate your existing Vulnerability Scans into the Dashboard, (OpenVas,McAfee, Nessus etc.)
* Open Source Incident Response. Alerts maybe escalated as tickets to other operators or a  
  whiteboard to show night shift analysts current issues.

  <p>Organisations have a multitude of security and network appliances all logging security events. However due to their size and complexity these logs are not correlated together in one portal to analyse these events. These security events will provide a clear picture to your team on how the end user is using the network to detect</p>

* User Activity, compliance including PCIDSS
* Users trying to access payroll or Intellectual Property. 
* End point compliance 
* Misuse of the environment including illegal file downloads 
* Hackers accessing the network the network
* Pattern Matching
* Anomaly Detection
* Data Correlation 
* OSINT List Queries
* OSSEC HIDS Rule Levels
* Spike Detection
* Cardinality
* Brute Force Attacks
* System/Appliance Failure Detection
* DNS Data Exfiltration
* Unauthorised Resource Access
* Unusual Email Activity
* Malware Communication Channels
* Event Log Source Heartbeat Monitor

## HIGH LEVEL COMPONENTS
<p>This solution includes the following high level components.</p>
<p><b>SIEM & SIM / SEM - </b>M Is built to provide 24x7 Security Event collection, correlation and Incident response. Risk Identification, visual alerting, analysis and secondary email/SMS/Slack alerts to the operator.</p>
<p><b>Software Components –</b> All open source components that are included in SIEMonster.</p>

<p><b>Hardware Components</b> – Virtual hardware requirements for Virtual environment></p>

<p><b>Configuration –</b> SIEMonster configuration, rulesets, architecture, equipment requirements, backups and maintenance.</p>
<p><b>Dashboards –</b> Visual representation of configured alerts and risks in the environment.</p>
<p><b>Rules and Search –</b> How to configure rules and run searches using Elastic Search</p>
<p><b>Incident Response Alerting and Ticketing –</b> Ticketing system to record Incident Response, and documentation for security analysts and 411 for alerting and UI</p>
<p><b>Host Based Intrusion Detection Alerting –</b> Integration with OSSEC Wazuh fork to allow HIDS alerting and pre-built rulesets including PCIDSS.</p>
<p><b>OSINT –</b> Integration with Open Source Threat Intelligence for real time threats in the wild incorporating Critical Stack.<p>
<p><b>Vulnerability Scanning –</b> Using your existing vulnerability scanning tool incorporated into a world view dashboard revealing hot spots in your network</p> 
<p><b>Reporting –</b> Reporting snapshots of your SIEM via scheduled emails in PDF format</p>
<p><b>Plugin Development –</b>How to develop your own plugins for specific equipment like SCADA or custom equipment or how to get help from the community of Kustodian to monitor specific equipment like Blast Furnaces, paint guns, robotic arms or production lines.</p> 

##SCOPE

This document covers all the software and hardware infrastructure components for the Security Operations Centre SIEMonster product. Separate documents such as build guides, standard operating procedures, troubleshooting and maintenance are in other documents included in the document suite. Training videos, and how to use guides are on the SIEMonster website.http://www.siemonster.com

##AUDIENCE
<p>This document is intended for technical representatives of companies, SOC owners as well security analysts and professionals. The audience of this document are expected to have a thorough level of knowledge of Security, Software and Server Architecture. 
The relevant parts are included here for convenience, and may of course be subject to change. They will be updated when notification is received from the relevant owners.<p>

