## Internship Projects – F13 Technologies

**F13 Technologies Internship Projects – Serverless Payroll, Attendance, and Document Vault | Roles: Data Layer, Backend, Security & Access**

## 🧑‍💻 My Contributions

### 📌 Project 1: Serverless Payroll Processing & Payslip Delivery Engine
**Role:** Data Layer & Storage

Designed and implemented the data storage backbone of the payroll engine.

- Designed a DynamoDB schema for employee payroll records.
- Architected an Amazon S3 storage strategy for secure payslip PDF storage.
- Implemented idempotency tokens to prevent duplicate salary calculations.
- Ensured auditability and compliance through immutable payroll records.
- Integrated the data layer with AWS Lambda workflows and Amazon SES for automated payslip delivery.

---

### 📌 Project 2: Serverless Attendance System with Face Recognition
**Role:** Backend Processing

Built the real-time backend workflow powering attendance tracking.

- Developed Lambda Function URLs for secure image uploads.
- Integrated Amazon Rekognition with a ≥90% similarity threshold for face verification.
- Implemented attendance processing logic for clock-in and clock-out events.
- Designed DynamoDB tables for employees, attendance records, and recognition results.
- Built an event-driven architecture linking Amazon S3 events with AWS Lambda triggers.
- Added validation rules to reject low-quality or multiple-face images.

---

### 📌 Project 3: Employee Document Vault with Role-Based Access Control
**Role:** Security & Access

Implemented the authentication and authorization layer for secure document management.

- Configured Amazon Cognito User Pools and User Groups.
- Designed IAM roles following the principle of least privilege.
- Created the `manager_mapping` DynamoDB table to enforce Role-Based Access Control (RBAC).
- Integrated JWT validation with Amazon API Gateway and AWS Lambda.
- Implemented authorization logic for Employees, Managers, and HR_Admin users.
- Secured API Gateway endpoints using Amazon Cognito Authorizers.

---
## 🚀 Portfolio Impact
Across all three projects, I contributed to building scalable, secure, and serverless cloud applications by focusing on:

- ✅ Reliable and scalable data architecture for Payroll.
- ✅ Real-time backend processing for Attendance.
- ✅ Secure authentication and Role-Based Access Control (RBAC) for the Document Vault.
- ✅ Event-driven serverless architectures using AWS services.
- ✅ Cloud security best practices with IAM, Cognito, JWT, and API Gateway.

**Core AWS Services:** AWS Lambda • Amazon DynamoDB • Amazon S3 • Amazon Cognito • Amazon API Gateway • Amazon Rekognition • Amazon SES • IAM
