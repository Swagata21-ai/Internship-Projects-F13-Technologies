# Internship Projects F13 Technologies
**F13 Technologies Internship Projects – Serverless Payroll, Attendance, and Document Vault | Roles: Team 1 Data Layer, Team 2 Backend, Team 1 Security & Access**

🧑‍💻 My Contributions – Internship Projects (F13 Technologies)
**📌 Project 1: Serverless Payroll Processing & Payslip Delivery Engine**
**Team 1 Role – Data Layer & Storage**
I designed and implemented the data storage backbone of the payroll engine.

DynamoDB Schema for employee payroll records.

Amazon S3 Strategy for secure payslip PDF storage.

Idempotency Tokens to prevent duplicate salary calculations.

Auditability & Compliance by ensuring immutable payroll records.

Integration with Lambda workflows and SES email delivery.

**📌 Project 2: Serverless Attendance System with Face Recognition**
**Team 2 Role – Backend Processing**  
I built the real‑time backend workflow that powers attendance tracking.

Lambda Function URL for secure image uploads.

Amazon Rekognition integration with ≥ 90 % similarity threshold.

Attendance Processor to apply clock‑in/clock‑out logic.

DynamoDB Tables for employees, attendance records, and recognition results.

Event‑Driven Architecture linking S3 events to Lambda triggers.

Validation Rules rejecting low‑quality or multiple‑face images.

**📌 Project 3: Employee Document Vault with Role‑Based Access**
**Team 1 Role – Security & Access** 

I implemented the authentication and authorization layer for secure document management.

AWS Cognito setup with User Pools & Groups.

IAM Roles designed for least‑privilege access.

manager_mapping Table to enforce RBAC between managers and employees.

JWT Validation integrated with API Gateway & Lambda.

Authorization Logic for Employees, Managers, and HR_Admin.

API Gateway endpoints secured with Cognito Authorizer.

**🚀 Portfolio Impact**
Across all three projects, I contributed to critical backend and security layers:

Data reliability in Payroll.

Real‑time recognition in Attendance.

Secure access control in Document Vault.
