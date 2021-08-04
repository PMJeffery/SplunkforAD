# SplunkforAD

Various Splunk Dashboards and Reports for Windows Domain Admins

Domain admin and have Splunk?  Need more that out of the box reports and Dashboards?

**Prerequisites:**
Splunk:
- Splunk Enterprise/Cloud
- Splunk TA Windows installed: https://splunkbase.splunk.com/app/742
- AD Objects installed and configured: https://splunkbase.splunk.com/app/3177
- Splunk App for Windows Infrastructure installed and configured: https://splunkbase.splunk.com/app/1680
- Standard Windows Indexes must exist: perfmon, msad, windows, wineventlog

Domain Controller Data Inputs:
- Splunk Universal Forwarder installed and sending Data from **ALL** Domain Controllers (DCs) where Domain Admins make changes
- All DCs that handle authentications must also be sending Event Logs to Splunk for full coverage of events

**How to:**
Dashboard XML files
- Web UI - Create a new Dashboard, Edit, Edit Source, CTRL+A, Delete, Paste XML code, Save
- Double-Check your Dashboard permissions to allow access to others using Splunk

**To Do**
- Create Splunk App?!



=========================================
Credits
=========================================
- Dylan Simmers
- Paul Jeffery
