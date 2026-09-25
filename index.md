# Privacy Policy – Pi MS (Passive Infrastructure Management System)

Dipa Poros Advisory & Digital Solutions
Effective date: 25 September 2026
Last updated: 25 September 2026

---

## 1. About this policy

This Privacy Policy explains how Dipa Poros collects, uses, stores, shares and protects personal data when you use **Pi MS**. Pi MS is our passive infrastructure management platform, and it includes:

- the Pi MS web dashboard and hosted cloud platform
- IoT gateways and connected monitoring devices
- mobile and web interfaces
- alerts, escalations and reports sent by WhatsApp, SMS, email and other channels
- our websites and support services

We process personal data in line with India's Digital Personal Data Protection Act, 2023 ("DPDP Act"), the Digital Personal Data Protection Rules, 2025, the Information Technology Act, 2000, and any other law that applies to us.

**Company details**
Dipa Poros Advisory & Digital Solutions
Udyam Registration No.: UDYAM-HR-05-0198903
Registered address: Flat No. 2002, Tower 10, M3M Merlin, Sector 67, Gurugram, Haryana - 122018, India
Email: support@dipaporos.com
Website: https://www.dipaporos.com/

---

## 2. Our role

- **Data Fiduciary:** For data about our website visitors, business contacts, direct users and our own operations, Dipa Poros decides how personal data is used.
- **Data Processor:** When an enterprise customer (for example a telecom operator, tower company or facility owner) uses Pi MS to monitor its own sites and staff, that customer decides the purpose. We process the data on the customer's behalf, under our contract with them. Individuals in this situation can also contact the customer directly.

---

## 3. Personal data we collect

Pi MS is built mainly to process **machine and site data** (for example battery voltage, DG status, temperature, door alarms and power readings). That data usually is not personal data. We collect only the limited personal data we need to run the service:

| Category | Examples | Source |
|---|---|---|
| Account and identity data | Name, designation, company, employee ID, login credentials | You or your employer |
| Contact data | Mobile number, WhatsApp number, email address | You or your employer |
| Communication data | WhatsApp messages, button replies (e.g. "Acknowledge", "Escalate"), delivery and read status, message timestamps | WhatsApp Business Platform (Meta), SMS and email providers |
| Operational activity data | Alarm acknowledgements, escalation history, actions taken, tickets, comments | Your use of Pi MS |
| Location data | Site addresses and coordinates; field-engineer location only if enabled by the customer and permitted by law | Customer configuration, devices |
| Technical data | IP address, device and browser type, log files, session data, cookies | Automatically when you use Pi MS |
| Support data | Queries, complaints and feedback | You |

We do **not** knowingly collect sensitive personal data such as financial account details, health data or biometric data through Pi MS. We also do not sell personal data.

---

## 4. Why we use personal data

We use personal data only for these specific purposes:

1. **Providing Pi MS:** creating accounts, authenticating users and running the dashboard.
2. **Alarm notification and escalation:** sending real-time alerts about infrastructure events to authorised staff and engineers by WhatsApp, SMS or email.
3. **AI-assisted operations:** using automated rules and AI models to prioritise alarms, recommend actions, route escalations and produce reports. These decisions concern **equipment and sites**. They are not used to make legal or similarly significant decisions about individuals.
4. **Receiving responses:** processing replies and button actions (for example acknowledging an alarm) through our webhook integrations.
5. **Reporting and audit:** keeping escalation trails, service-level reports and compliance records for our customers.
6. **Security:** detecting fraud, misuse, unauthorised access and security incidents.
7. **Support and communication:** answering queries and sending service notices.
8. **Legal compliance:** meeting legal, regulatory, tax and law-enforcement obligations.

---

## 5. Legal basis

We process personal data on the basis of:

- **Consent**, given by you or collected by your employer or our customer, for example to receive WhatsApp alerts; or
- **Legitimate uses** allowed under the DPDP Act, including where you have voluntarily given your data for a specific purpose, for employment-related purposes of our customers, and for legal compliance.

You may **withdraw consent** at any time (see Section 10). Withdrawal does not affect processing that happened before it. If you withdraw consent for alerts, you may no longer receive critical operational notifications.

---

## 6. WhatsApp communications

Pi MS uses the **WhatsApp Business Platform (Cloud API)** provided by Meta Platforms, Inc. to send alerts and receive replies.

- We send WhatsApp messages only to numbers that you, your employer or our customer have authorised.
- Messages we start are sent using templates pre-approved by Meta. They contain operational information such as site ID, element ID, alarm type, time and severity.
- When you reply or tap a button, Meta delivers your response to our servers through a secure webhook.
- WhatsApp messages are encrypted in transit. Meta's handling of data is governed by the [WhatsApp Business Privacy Policy](https://www.whatsapp.com/legal/business-policy) and [Meta Privacy Policy](https://www.facebook.com/privacy/policy).
- **Opting out:** reply **STOP** to any Pi MS WhatsApp message, or email [privacy@yourdomain.com]. We will stop non-essential messages. Your organisation may need to name another recipient for critical alarms.

---

## 7. Sharing personal data

We share personal data only when needed, and only with:

| Recipient | Purpose |
|---|---|
| Our enterprise customer (your employer or client) | Operating their infrastructure monitoring and escalation |
| Messaging providers (Meta/WhatsApp, [SMS gateway], [email provider]) | Sending alerts and receiving replies |
| Professional advisers and auditors | Legal, accounting and compliance |
| Government and law-enforcement authorities | When the law requires it |

All service providers are bound by contracts that require confidentiality, security and use of the data only on our instructions.

---

## 8. Storage location and cross-border transfer

Pi MS data is mainly stored on servers in **[India / Sri Lanka]**. Some service providers (for example Meta for WhatsApp messaging) may process data outside India. Any such transfer follows the DPDP Act and any restrictions notified by the Government of India.

---

## 9. Retention

We keep personal data only as long as needed for the purposes above, or as the law requires:

| Data | Retention period |
|---|---|
| User account data | While the account is active, plus [12] months |
| Alarm, escalation and WhatsApp message logs | [24] months, or as agreed with the customer |
| Security and access logs | At least 1 year, as required under the DPDP Rules |
| Contractual, tax and legal records | As required by applicable law |

When the retention period ends, we delete or anonymise the data. Where the law requires it, we will notify you before erasure.

---

## 10. Your rights

Under the DPDP Act, you have the right to:

- **Access** a summary of your personal data and how it is processed
- **Correct, complete or update** inaccurate or incomplete data
- **Erase** personal data that is no longer needed, unless the law requires us to keep it
- **Withdraw consent**, as easily as you gave it
- **Nominate** another person to exercise your rights in case of death or incapacity
- **Raise a grievance** with us, and then with the Data Protection Board of India

**How to exercise your rights:** Email [support@dipaporos.com] with the subject line "Data Request". Include your name, registered mobile number or email, your organisation, and your request. We may need to verify your identity before acting on it.

If your data is processed on behalf of your employer or our customer, we may send your request to them and help them respond.

---

## 11. Security

We use reasonable security safeguards, including:

- TLS encryption for data in transit, and encryption of data at rest
- role-based access control and multi-factor authentication for administrators
- secure device and gateway authentication (unique device credentials, mutual TLS, signed firmware)
- verification of webhook signatures for all incoming WhatsApp events
- storing API tokens and secrets in secure vaults, never in client applications
- logging, monitoring and regular security reviews
- confidentiality obligations for staff and vendors

No system is completely secure. We cannot guarantee absolute security, but we work continuously to protect your data.

---

## 12. Personal data breach

If a personal data breach occurs, we will:

- inform affected individuals without delay, in plain language, explaining what happened, the likely impact, the steps we have taken, and a contact point for help
- notify the Data Protection Board of India without delay, followed by a detailed report within 72 hours, as required under the DPDP Rules
- notify affected enterprise customers as required by our contracts

---

## 13. Children

Pi MS is a business platform intended for adults. We do not knowingly collect personal data of children under 18. If you believe we have done so, contact us and we will delete it.

---

## 14. Cookies

Our web dashboard uses essential cookies for login sessions and security. We use [no / limited] analytics cookies. You can control cookies through your browser settings, but turning off essential cookies may stop the dashboard from working.

---

## 15. Changes to this policy

We may update this Privacy Policy from time to time. The updated version will be posted at this URL with a new "Last updated" date. If we make significant changes, we will notify users through the platform or by email.

---

## 16. Language

This policy is published in English. On request, we will provide it in any language listed in the Eighth Schedule to the Constitution of India.

---

© 2026 Dipa Poros. All rights reserved.
