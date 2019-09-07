# Crossover-Question-4
Postmortem Document for Jira issue AESEDI-53447

Status
Fixed, action items in progress

Summary
Issue with AES CIS service affected delay in sending customer data from AES EDI.

Impact
Records were missed and were not discovered automatically

Root Causes
Issue with the AES CIS service(Jira Issue No: AESCIS-38263) resulted the file with customer data did not get processed and it also affected EDI to CIS monitoring service working on the CIS side. So the missed records were not discovered automatically. 

Resolution
The file was resent and the issue got resolved. The missing records were discovered at 11:56 AM, processed at 1:00 PM

Detection
A Jira issue ( AESEDI-53447) was logged that the customer data was not sent from AES EDI.


Date:
September 7, 2019

Authors:
Patrick Sampollo

Status:
Fixed. Records have been processed. Action items in progress.

Summary:
Customer data was not sent from AES EDI and 486,000 records were affected. 

Impact:
A total of 486,000 records did not get processed. This also affected the EDI to CIS monitoring service working on the CIS side.

Rootcause:
File with the data was sent but did not get processed due to an issue with the AES CIS service.
Reference: Jira Issue No. AESCIS-38263



Trigger:
Jira Issue No. AESCIS-38263

Resolution:
File had to be resent and the records were processed shortly after. 

Detection:
Missing customer data. No automated alert due to EDI to CIS monitoring issue. Missed records were not discovered automatically. User had to report it. 

Action items:

Action Item
Type
Owner
Bug

Action Item:  Need to fix the EDI issue that is causing the Jira issue AESCIS-38263
Type          EDI
Owner         Patrick Sampollo / Devops
Bug           Jira Issue No. AESCIS-38263


Action Item:  Create document in knowledgebase for quicker resolution of the issue
Type          EDI
Owner         Patrick Sampollo / Devops
Bug           Jira Issue No. AESCIS-38263

Action Item:  Create an automated method of monitoring missing file records or of validating that the records were processed successfully after sending it via AES EDI
Type          EDI
Owner         Patrick Sampollo / Devops
Bug           Jira Issue No. AESCIS-38263
Manual checking needed until monitoring is fixed
EDI
Patrick Sampollo / Devops
Jira Issue No. AESCIS-38263


Lessons Learned:
What went well:
Resolution was fast enough.
Simply resending the file resolved it.

What went wrong:
Missing records were not detected automatically.
We should never assume that files are processed successfully.
There should always be a way to monitor if the files sent via AES EDI have been successfully processed.

Where we got lucky:
We did not need to manually update the records to fix it



Timeline:

Datetime
Description
September 7, 2019 11:56 AM
Missing files issue was discovered and logged.
September 7, 2019 12:00 PM
Devops team troubleshoot the issue and try find a solution/workaround.
September 7, 2019 12:30 PM
Devops find a possible solution. Tests are being done. We update the users.
September 7, 2019 12:45 PM
File was resent.
September 7, 2019 1:00 PM
Records were processed.
September 7, 2019 1:15 PM
Problem record created and action items for permanent solution/monitoring are created. We inform the user that we are coming up with a permanent solution.

Supporting Information: 
Jira issue No. AESCIS-38263
