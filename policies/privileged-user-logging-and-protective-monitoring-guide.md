---
Expires: 2020-12-31
---

# Privileged User Logging and Protective Monitoring Guide

## Introduction

This guide outlines the security procedures and advice that privileged users must consider when undertaking logging activities. Maintaining and monitoring system logs will help to ensure that suspicious activity on the MoJ�s systems is detected early. This guide is a sub-page to the Privileged User Guide.

## Maintenance of system logs and protective monitoring

Privileged users are responsible for maintaining system logs (syslogs) for the systems they administer. Privileged user log management responsibilities include the following.
  
 - Implementing logging and monitoring on the systems they manage.

 - Ensuring that systems are synchronised to the centralised MoJ timing source to enable effective malware detection.

 - Working closely with the Operational Security Team (OST) to define requirements and ensure that when possible, automated log analysis and alerting is integrated with the MoJ�s SOC which provides the MoJ�s central monitoring function.
 
 - Establishing the baseline activities for systems they are responsible for. This is essential to ensure that monitoring systems are able to detect when there is unusual activity.

 - Performing regular maintenance of the logs and logging to ensure that configurations are correct. 

 - Reconfiguring system logging as needed based on the MoJ�s policy or guidance changes, technology changes, emerging threats or other business needs. 

 - Implementing automated real-time log analysis where possible.

 - Reviewing results from automated real-time analysis quarterly to ensure its relevance.

 - Where real-time log analysis has not been implemented, then manual log analysis must be performed at least weekly.

 - Monitoring and investigating all suspicious activity. Where sensitive information is accessed beyond normal user behavior, such as accessing information outside of normal working patterns, these must be investigated and reported to the Technology Service Desk. See further details in the IT Incident management Policy and Guide. 

 - Ensuring that audits and compliance checks of IT systems do not adversely affect business operations.

 - Documenting and reporting anomalies in log settings, configurations, and processes to the OST and the Cyber Assistance Team.

 - Managing long-term storage of system log data, monitoring log rotation, and the archival and deletion of log data. 

 - Any suspicious activity must be reported to the Technology Service Desk (contact details below) who may escalate it to the OST.  

## Protection of log data

To ensure that there is an audit trail for log data, privileged users must:

 - protect the information held within system audit logs in accordance with its Information Classification (refer to the Information Classification Handling and Security Guide for further guidance on classifying information)

 - establish log archival processes while filtering out entries that do not need to be archived to ensure log availability

 - ensure that systems are designed with access controls to prevent privileged users from erasing or deactivating activity logs of their own activities, without the additional approval of the product or service manager

 - review the activity logs of other privileged users on a monthly basis to ensure that privileged users remain impartial. 

## Contact details

 - Contact the Cyber Assistance Team for advice � [CyberConsultancy@digital.justice.gov.uk](mailto:CyberConsultancy@digital.justice.gov.uk)

 - Contact the Technology Service Desk to report a suspected incident � 0800 917 5148.