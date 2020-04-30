---


copyright:
  years: 2018, 2019
lastupdated: "2020-04-24"


---

{:new_window: target="_blank"} 
{:shortdesc: .shortdesc} 
{:codeblock: .codeblock} 
{:pre: .pre} 
{:screen: .screen} 
{:tsSymptoms: .tsSymptoms} 
{:tsCauses: .tsCauses} 
{:tsResolve: .tsResolve} 
{:tip: .tip} 
{:important: .important} 
{:note: .note} 
{:download: .download} 
{:external: target= .external} 

# 2020-05-00 New and changed features
{: #20200500-new-and-changed-features } 

2020-05-00 New and changed features.
{: shortdesc} 

This section describes new and changed functionality for 2020-05-00.

## Managed Applications Portal enhancements
- A warning message “More than 100 items are selected across all dimensions in filter selection. Please limit your selection to 100 
filter items” is added at the bottom of the Select Dimension Filters pop-up window in the Insights/Metrics portal to warn the user not 
to select more than 100 items (ex: servers). (Hot Fix)
- An option to reset the applied global and batch filters, page size and page number by clicking F5 key is added to the List View pages 
of Servers and Applications portal.   
- The date picker in the Alerts Opened widget will now show Today, 7 days and 30 days instead of Day, Week and Month.  
- Configuration Item (CI) class is added to the Create, Add CI pop-up and Edit Details pages of Incident, Service and Change Requests.
- Following customized date picker options are added to the batch filter of the Incident, Service and Change Request and Alerts (Health) List View pages:
  - Today  
  - Yesterday
  - Last 7 days
  - Last 30 days
  - Last 3 months
  - Last 6 months.  
- New case type Incident with Outage is further enhanced with the following changes:
  - A dialogue box with the text "Please confirm that you are experiencing an outage that has a business impact" is added forcing user 
  to confirm that the outage has a business impact 
  - Ability to enter multiple Emails and Contact phone numbers separated by commas along with country codes to enable users add contact
  info
  - Field name “What is the impact to their business" field name is renamed as Business Impact Statement
  - Summary field is renamed as Short Description of the problem 
  - A note “Please use the Attachment section to attach the errors” near the Description field
  - Affected Item is made as mandatory field
  - Place holder text with samples for Business Impact, Summary and Description fields.

- Once an Incident with outage is created, a slack notification is triggered to the designated trio slack channel of the contract under which outage is created to expedite problem resolution and this notification will also be seen in trm-sev1- hub slack channel in the below given format:
  - Cust P1 Notification
  - @here --- Please validate the request and engage TRMs via #trm-sev1-hub within 15 minutes
  - Incident#:
  - Priority: 
  - Client Name: 
  - Customer Email: 
  - Customer Phone: 
  - TRIO: 
  - CDIR: 
  - Data Center: 
  - Asset Name: 
  - Ticket summary: 
  - Client Business Impact: 
  - Business Impact: 
  - SCO Channel:
  - Trio Channel:
