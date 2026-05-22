# OA.Report 2026-04-29 post-incident report

This post-incident report summarises what happened, what we did about it, and what we’re changing as a result. We are sharing this because we understand that trust in OA.Report’s data is critical, and we want to be transparent. With the actions we have already taken and are currently taking, we will be better positioned to respond to any issues that may arise in the future and to continue delivering high-quality data.

### Summary

On April 29th, 2026 at approximately 1:00 am UTC OA.Report’s production index was deleted, causing missing data and incorrect figures on all reports. Automated monitoring detected the deletion within minutes, our team engaged at 7:30 am UTC, customers were notified by 9 am UTC, and by 10:30 am UTC we had mitigated the issue and OA.Report’s data and figures were correct. We mitigated the issue by utilizing a copy of the data used day-to-day for OA.Report’s development, and May 6th, we released a fresh production copy of OA.Report’s data.

### Impact

Customers viewing reports between roughly 1:00 am and 9:00 am UTC on 29 April may have received missing data or incorrect figures without any notification. There were delays to some routine data updates during this time, and it wasn’t possible to send actions in the days after the incident. We also had reduced team capacity for routine questions and development.

### Investigation and fix

We carefully investigated the issue and were able to reproduce the data loss in a test environment and verify that our fixes prevented the issue from recurring.

### Action plan

To help prevent similar incidents in the future, or recover faster, critical areas we are working on include:

1. Hardening our system against unexpected deletions.\
   \
   We have already limited the routes by which data can be deleted from our system, and we will refine those over time.<br>
2. Improving backup and restore processes\
   \
   We have already increased our backup frequency and allowed more team members to restore from them. Within 10 days, we will automatically make daily back-ups of OA.Report’s production data and have anyone on our team restore from them within minutes.

The incident also spurred additional investment in the monitoring and testing infrastructure we use daily to ensure high data quality and to enable faster communication with customers about issues.
