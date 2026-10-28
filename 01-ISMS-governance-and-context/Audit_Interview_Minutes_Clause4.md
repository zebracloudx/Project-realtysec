# RealtySec India Pvt Ltd
## ISO 27001:2022 ISMS Audit Discovery Interview Minutes

**Date:** October 26, 2026  
**Auditor:** Lead Auditor (GRC Lead)  
**Interviewee:** Founder / Managing Broker  
**Subject:**  Initial Operational Discovery  

---

## 1. Interview Summary & Operational State
The Founder described current operations as a lean 4-person team (1 Broker + 3 Field Agents). Key processes rely heavily on mobile communication and cloud storage.

* **Client Data Collection:** KYC documents (Aadhaar, PAN, Bank details) are collected directly via WhatsApp from buyers and sellers.
* **Data Storage:** Files are kept on field agents, personal mobile devices and uploaded to a shared Google Drive.
* **Access Control:** The team shares a single, common login password to access the company Google Drive.

---

## 2. Identifiing Gaps Assement

| # | Operational Practice | Security / Compliance Gap | ISO 27001 Control Mapping |
| :---: | :--- | :--- | :--- |
| **1** | Storing unmasked PII on personal phones via WhatsApp | Risk of data leak via unmanaged BYOD endpoints; violation of DPDP Act regulations. 
| **2** | Single shared Google Drive account for all staff | Failure of individual accountability and access governance; impossible to track audit logs.

---

## 3. Preliminary ISMS Scope Boundaries
Based on this interview, the following assets and platforms are formally designated as **In-Scope** for the RealtySec ISMS:

* **SaaS / Cloud Platforms:** Google Workspace Tenant (Google Drive, Gmail).
* **Communication Channels:** WhatsApp / Mobile Messaging channels used for business.
* **Hardware Endpoints:** Mobile devices (BYOD) and personal laptops used by the 4 team members.
* **Information Assets:** Customer PII (Aadhaar, PAN, bank accounts) and Property Agreement records.

---

## 1. Context & Overview
ISO 27001:2022 Clause 4.2 requires the organization to determine the interested parties that are relevant to the Information Security Management System (ISMS) and their legal, regulatory, or contractual security requirements.

---

## 2. Interested Parties Matrix

| Interested Party | Category | Security & Compliance Expectation / Need | ISMS Control Mapping |
| :--- | :--- | :--- | :--- |
| **Clients (Buyers & Sellers)** | External | Confidentiality of KYC identity proofs (Aadhaar, PAN), land ownership records, and enforcement of signed NDAs. | |
| **Data Protection Board / Regulators (DPDP Act)** | Statutory / Legal | Prevention of PII data breaches, explicit consent logging, and legal compliance under India's DPDP Act. |  |
| **Legal & Advisory Consultants** | External Advisory | Standardized contractual language, NDA enforcement, and guidance on liability mitigation. |   |
| **Field Agents & Staff** | Internal | Clear guidelines on acceptable device usage, remote communication safety, and data handling rules. | |

---

## 3. Lead Auditor Summary & Action Items
* **Contractual Mandate:** Client NDAs must be stored in a centralized, access-controlled directory rather than on individual agent phones.
* **Legal Mandate:** A formal **Candidate & Client Privacy Policy** must be drafted to align with the DPDP Act requirements identified during discovery.
