# Activity-audit

NAME: DIVYA S
REG NO: 212225220029

AIM:
To enable and analyze AWS cloud Trails logs to audit user and resource activities in a cloud environment

Requirements:

AWS Console access CloudTrail service enabled S3 bucket (for storing logs) IAM permissions to view audit logs

Procedure
Step 1: Enable CloudTrail Go to CloudTrail from AWS Console Click Trails > Create trail Name: CloudAuditTrail Apply trail to all regions Log events:

Management events: Read & Write Data events: S3, Lambda (optional) Create or select an S3 bucket for log storage Enable CloudWatch Logs integration (optional) Step 2: Review Event History Go to Event history Filter events by:

Username (IAM role or user) Event name (e.g., CreateBucket, TerminateInstances) Date/Time Resource type (e.g., S3, EC2) Step 3: Download or Export Logs Use the Download CSV option to export logs Analyze logs in Excel/Sheets for reporting

Output:
<img width="932" height="760" alt="image" src="https://github.com/user-attachments/assets/5678ecfe-e778-4846-b970-77a6cbcda0e8" />
<img width="930" height="757" alt="image" src="https://github.com/user-attachments/assets/356bceed-ea83-4a6d-890e-d201d0bd2ffa" />
Result:
All AWS user activities, including volume creation, deletion, and permission changes, were successfully audited using CloudTrail.
