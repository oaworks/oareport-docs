# OA.Report 2026-04-29 post-incident report

We know users rely on OA.Report's data, and we're sorry for any disruption and uncertainty this caused. This post-incident report summarizes what happened, what we did about it, and what we're changing to better respond to future issues and deliver high-quality data every day. We are sharing this because we understand that trust in our data is critical, and so we want to be transparent.

### Summary

On April 29th at approximately 1:00 am UTC OA.Report’s production index was deleted, causing missing data and incorrect figures on all reports. Automated monitoring detected the deletion within minutes, our team engaged at 7:30 am UTC, customers were notified by 9:00 am UTC, and by 10:30 am UTC we had mitigated the issue and OA.Report’s data and figures were correct. We mitigated the issue by utilizing a copy of the data used daily for OA.Report’s development, and on May 6th, we released a new production copy of OA.Report’s data.

### Impact

Customers viewing reports between roughly 1:00 am and 9:00 am UTC on April 29th may have seen missing data or incorrect figures without any notification. It wasn’t possible to send actions in the days after the incident, and there were delays of varying length to some routine data updates in the weeks after the incident. We also had reduced team capacity for routine questions and development.

### Investigation and fix

We carefully investigated the issue and were able to reproduce the data loss in a test environment and verify that our fixes prevented the issue from recurring.

### Action plan

To help prevent similar incidents in the future, or recover faster, critical areas we are working on include:

1. Hardening our system against unexpected deletions.\
   \
   We have already limited the routes by which data can be deleted from our system, and we will refine those over time.<br>
2. Improving backup and restore processes\
   \
   We have already increased our backup frequency and allowed more team members to restore from them. Within 10 days, we will automatically make daily backups of OA.Report’s production data and have anyone on our team restore from them within minutes.

The incident also spurred additional investment in the monitoring and testing infrastructure we use daily to ensure high data quality and to enable faster communication with customers about issues.
