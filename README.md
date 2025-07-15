📄 Privacy and Data Handling Policy

1. Overview
At Codelattice, we are committed to safeguarding the privacy and security of Amazon seller and buyer data accessed through the Amazon Selling Partner API (SP-API). This policy outlines how we collect, process, store, use, share, and dispose of Amazon-provided information in compliance with Amazon's Data Protection Policy and industry-standard security practices.

2. Data Collected
Our application accesses Amazon data strictly through authorized SP-API endpoints with seller consent. We may collect:

Order details (Order ID, purchase date, status)

Buyer information (name, address, phone number, email) — only when authorized

Tax-related information (TRN, invoice requirements)

Product and shipment data

3. Purpose of Data Usage
We use Amazon data exclusively for the following purposes:

Generating tax-compliant invoices for sellers

Mapping buyer and order information for record-keeping

Delivering invoices to buyers via seller-authorized channels

Providing audit trails and historical order data for the seller's own use

We do not use or share Amazon data for advertising, analytics, profiling, or resale.

4. Data Processing & Storage
All data is processed securely within our backend services hosted in Amazon Web Services (AWS). We apply:

End-to-end encryption during data transmission (HTTPS/TLS 1.2+)

AES-256 encryption at rest for all PII and order data

Role-based access control (RBAC) to ensure only authorized personnel can access data

We do not store PII in frontend applications or client devices.

5. Data Retention and Disposal
We retain Personally Identifiable Information (PII) only as long as necessary to fulfill our invoicing and regulatory responsibilities:

Buyer PII: Deleted within 90 days after invoice generation unless legal retention is required

Order Metadata (non-PII): Retained for analytics and reporting (non-identifiable)

Upon expiry, data is securely deleted from storage and backups following industry best practices.

6. Data Sharing
We do not share Amazon data with any third parties except as follows:

AWS services used to host and secure the application (e.g., S3, RDS, Lambda)

Regulatory or law enforcement agencies only when legally required

No Amazon data is sold, rented, or exposed to marketing platforms

7. Employee Access
Only trained employees with a need-to-know have access to Amazon data

Access is logged, monitored, and reviewed quarterly

USB transfers and use of personal devices for Amazon data are prohibited

8. Incident Response and Monitoring
We maintain an active security monitoring and response plan:

24/7 log monitoring and alerting on unauthorized access attempts

Incident response procedures include investigation, containment, and notification

Vulnerability scans and penetration tests are conducted every 6 months

9. Compliance
This policy adheres to:

Amazon’s Data Protection Policy

GDPR (for EU data subjects, where applicable)

UAE local data protection regulations (where applicable)

Any future changes to SP-API requirements

