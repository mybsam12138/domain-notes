# PAS Example Backlog: 120 Features Under User Requirements

This document is an example **requirement → feature** backlog for a **Policy Administration System (PAS)** for a five-person team over one year.

It is intentionally kept at:
- **Requirement level** = business objective requested by users or stakeholders
- **Feature level** = business capability under that requirement

It does **not** go down to task / API / table / validation / technical implementation level.

---

## Requirement RQ-001: Customer and Party Profile Management
**Business goal:** Allow business users to create, maintain, and search customer and related party information used across quotation, policy, billing, and claims processes.

### Features
1. **Individual Customer Profile Maintenance** — maintain personal details for retail customers.
2. **Corporate Customer Profile Maintenance** — maintain legal entity details for company customers.
3. **Related Party Relationship Management** — link policyholder, insured, payer, beneficiary, and intermediary parties.
4. **Contact Information Management** — maintain phone, email, and communication preferences.
5. **Address Management** — maintain residential, mailing, and business addresses.
6. **Customer Search and Duplicate Check** — search existing parties and reduce duplicate profile creation.

---

## Requirement RQ-002: Producer, Agent, and Broker Administration
**Business goal:** Support distribution channels by maintaining agent, broker, and intermediary information used in quotations, policies, commissions, and reporting.

### Features
7. **Agent Master Maintenance** — maintain agent basic profile and status.
8. **Broker Master Maintenance** — maintain broker company profile and registration details.
9. **Agency Hierarchy Management** — maintain branch, team, and reporting structure.
10. **Producer Assignment to Policy Transactions** — associate agent or broker with quotation and policy records.
11. **Channel Status Control** — activate, suspend, or terminate intermediary accounts.
12. **Channel Search and Directory View** — search and browse available producers and intermediaries.

---

## Requirement RQ-003: Product Catalog and Product Setup
**Business goal:** Allow product teams to configure and maintain insurance products for quotation and policy issuance.

### Features
13. **Product Master Setup** — create and maintain product code, name, and business line.
14. **Plan Configuration** — define one or more plans under a product.
15. **Section Configuration** — define coverage sections within a product or plan.
16. **Benefit Catalog Association** — associate benefits available for the product structure.
17. **Product Versioning** — maintain effective versions of a product over time.
18. **Product Activation Control** — activate or deactivate products for business usage.

---

## Requirement RQ-004: Coverage and Clause Definition
**Business goal:** Allow product users to define what is covered, excluded, and conditioned under each product offering.

### Features
19. **Coverage Item Definition** — define core coverages available for sale.
20. **Coverage Limit Configuration** — configure insured limits and sum insured options.
21. **Deductible Configuration** — configure deductible and excess options.
22. **Clause Library Management** — maintain standard policy clauses.
23. **Coverage-Clause Association** — attach clauses to products, plans, or sections.
24. **Optional Coverage Selection Setup** — configure optional add-on coverages.

---

## Requirement RQ-005: Rating and Pricing Configuration
**Business goal:** Allow pricing users to maintain the business rating rules needed for premium calculation.

### Features
25. **Base Rate Table Maintenance** — maintain base premium rates.
26. **Rating Factor Configuration** — define factors such as age, occupation, territory, or asset type.
27. **Loading and Discount Configuration** — define business loading and discount rules.
28. **Minimum Premium Setup** — maintain minimum premium thresholds.
29. **Short-Term / Pro-Rata Factor Setup** — maintain period-based premium adjustment factors.
30. **Pricing Effective Date Management** — control pricing validity periods.

---

## Requirement RQ-006: Quotation Intake and Data Capture
**Business goal:** Allow users to capture quotation details efficiently for new business and renewals.

### Features
31. **Quotation Header Capture** — capture quotation-level basic information.
32. **Insured Risk Detail Capture** — capture item, member, vehicle, property, or location details.
33. **Coverage Selection During Quotation** — choose plans, sections, and benefits for the quote.
34. **Quotation Party Assignment** — assign policyholder, insured, payer, and intermediary.
35. **Quotation Effective Date Selection** — capture inception and expiry dates.
36. **Quotation Save as Draft** — save incomplete quotation for later continuation.

---

## Requirement RQ-007: Premium Calculation and Pricing Application
**Business goal:** Allow the system to calculate premium accurately based on configured business rules and selected quotation data.

### Features
37. **Quotation Premium Calculation** — calculate premium for selected risk and coverage data.
38. **Premium Recalculation on Change** — recalculate premium when quote data changes.
39. **Coverage-Level Premium Breakdown** — show premium by coverage or section.
40. **Tax and Fee Application** — apply taxes, fees, levies, or stamp duty.
41. **Manual Premium Override with Reason** — allow authorized business override of calculated premium.
42. **Premium Result Display** — present premium summary and breakdown to users.

---

## Requirement RQ-008: Underwriting Rules and Referral Handling
**Business goal:** Allow underwriting controls to be applied during quotation and policy processing.

### Features
43. **Eligibility Rule Check** — check whether a risk is eligible for the product.
44. **Referral Trigger Management** — trigger underwriting referral based on business conditions.
45. **Referral Work Item Creation** — create referral records for review.
46. **Underwriter Decision Recording** — record approve, reject, or conditional decisions.
47. **Underwriting Note Capture** — maintain notes and comments for underwriting review.
48. **Referral Status Tracking** — track referral progress from pending to resolved.

---

## Requirement RQ-009: Quotation Output and Proposal Management
**Business goal:** Allow business users to formalize quotations and share them with customers or intermediaries.

### Features
49. **Quotation Summary View** — display a complete summary of the quotation.
50. **Quotation Version Management** — maintain multiple quote versions or revisions.
51. **Proposal Document Generation** — generate proposal or quotation document output.
52. **Quotation Validity Period Control** — manage quote expiry and validity dates.
53. **Quotation Acceptance Recording** — record whether the customer accepted the quote.
54. **Quotation Conversion to Policy** — convert an accepted quote into a policy transaction.

---

## Requirement RQ-010: New Business Policy Issuance
**Business goal:** Allow accepted quotations to be issued as active policies.

### Features
55. **Policy Number Generation** — generate policy identifiers.
56. **Policy Schedule Generation** — produce policy schedule content.
57. **Policy Issue Confirmation** — confirm issuance and create active policy record.
58. **Policy Inception Control** — manage start and end date application on issue.
59. **Issuance Checklist Review** — ensure required business conditions are satisfied before issue.
60. **Issued Policy View** — allow users to view completed policy records.

---

## Requirement RQ-011: Policy Endorsement Processing
**Business goal:** Allow business users to process mid-term changes to active policies.

### Features
61. **Policy Amendment Initiation** — initiate an endorsement transaction on an active policy.
62. **Coverage Change Endorsement** — change coverage, limits, or deductibles mid-term.
63. **Party Detail Change Endorsement** — change party or contact details affecting the policy.
64. **Risk Addition / Deletion Endorsement** — add or remove insured items or members.
65. **Additional / Return Premium Calculation** — calculate financial impact of the endorsement.
66. **Endorsement Document Output** — generate endorsement schedule or confirmation.

---

## Requirement RQ-012: Renewal Management
**Business goal:** Allow expiring policies to be renewed efficiently with proper review and repricing.

### Features
67. **Renewal Candidate Identification** — identify policies approaching expiry.
68. **Renewal Offer Generation** — create renewal quotation or offer.
69. **Renewal Repricing** — recalculate premium for the renewal term.
70. **Renewal Change Review** — review policy changes needed at renewal.
71. **Renewal Acceptance Recording** — record customer acceptance or decline.
72. **Renewal Policy Issuance** — issue renewed policy term.

---

## Requirement RQ-013: Cancellation and Termination Handling
**Business goal:** Allow users to cancel or terminate policies according to business rules and timing.

### Features
73. **Policy Cancellation Request Capture** — record cancellation request details.
74. **Cancellation Effective Date Control** — define effective date of cancellation.
75. **Cancellation Refund Calculation** — calculate refund or retained premium.
76. **Flat Cancellation Handling** — process cancellations with no earned premium.
77. **Cancellation Reason Tracking** — maintain business reason for cancellation.
78. **Cancellation Confirmation Output** — generate cancellation advice or notice.

---

## Requirement RQ-014: Billing, Invoice, and Receivable Management
**Business goal:** Allow billing teams to manage policy charges and customer receivables.

### Features
79. **Invoice Generation** — generate invoice for premium, fees, and taxes.
80. **Installment Plan Setup** — define installment billing schedules.
81. **Receivable Balance View** — show outstanding amounts per policy or customer.
82. **Billing Adjustment Handling** — reflect endorsement and cancellation billing changes.
83. **Due Date Management** — manage billing due dates and grace periods.
84. **Billing Status Tracking** — track billed, paid, overdue, and adjusted statuses.

---

## Requirement RQ-015: Payment Recording and Allocation
**Business goal:** Allow finance or operations teams to record and apply payments against policy billing records.

### Features
85. **Payment Receipt Recording** — record received payments.
86. **Payment Allocation to Invoice** — allocate payment to one or more invoices.
87. **Partial Payment Handling** — support partially paid balances.
88. **Overpayment and Credit Balance Handling** — manage excess collected amounts.
89. **Payment Reversal Recording** — reverse incorrect payment postings.
90. **Payment History View** — display payment transaction history.

---

## Requirement RQ-016: Document and Attachment Management
**Business goal:** Allow policy-related documents and supporting files to be generated, stored, and retrieved.

### Features
91. **Document Template Management** — maintain business document templates.
92. **Policy Document Generation** — generate schedule, certificate, invoice, or endorsement documents.
93. **Quotation Document Generation** — generate quotation and proposal output.
94. **Attachment Upload** — upload supporting files to quote or policy records.
95. **Attachment Retrieval** — view and download uploaded files.
96. **Document Version Tracking** — track generated document versions.

---

## Requirement RQ-017: Claims and Loss Notification Linkage
**Business goal:** Allow policy users to record and reference claim-related information against policies.

### Features
97. **Loss Notification Capture** — record first notice of loss information.
98. **Policy Coverage Verification for Claim Reference** — verify whether policy details support claim registration.
99. **Claim Reference Association** — associate claim number with the policy.
100. **Loss Event History View** — view claim-related events associated with a policy.
101. **Claim Document Linkage** — link claim-related documents to policy records.
102. **Claim Status Reference View** — view high-level claim status from policy context.

---

## Requirement RQ-018: Partner, Reinsurer, and External Party Reference Management
**Business goal:** Allow external business parties used in policy operations to be maintained consistently.

### Features
103. **Reinsurer Master Maintenance** — maintain reinsurer party records.
104. **Surveyor / Assessor Directory Maintenance** — maintain service provider records.
105. **Bank / Payment Partner Reference Maintenance** — maintain banking and payment counterparties.
106. **External Contact Directory** — maintain key external contact information.
107. **Partner Status Control** — activate, suspend, or close external party records.
108. **Partner Search and Selection** — search and select external parties in transactions.

---

## Requirement RQ-019: User, Role, and Operational Access Administration
**Business goal:** Allow organizations to control who can access PAS functions and business data.

### Features
109. **User Account Maintenance** — create and maintain system user accounts.
110. **Role Definition** — define operational roles for PAS usage.
111. **User-Role Assignment** — assign users to one or more roles.
112. **Branch / Department Access Scoping** — restrict access by organization scope.
113. **Approval Authority Setup** — configure approval authority for overrides and referrals.
114. **User Status Management** — activate, lock, or deactivate users.

---

## Requirement RQ-020: Operational Reporting and Inquiry
**Business goal:** Allow business users and managers to inquire on PAS data and monitor operational performance.

### Features
115. **Quotation Inquiry** — search and review quotation records.
116. **Policy Inquiry** — search and review active, expired, and cancelled policies.
117. **Renewal Pipeline Report** — view upcoming renewal workload.
118. **Billing and Outstanding Report** — view unpaid balances and overdue billing.
119. **Production Report by Channel** — view business volume by agent, broker, or branch.
120. **Policy Transaction History View** — review lifecycle events for each policy.

---

## Notes on Layering

### Requirement layer represents
- A **business objective** or **user-requested outcome**
- Something stakeholders can understand and approve
- A scope container for a group of related business capabilities

### Feature layer represents
- A **business capability** under a requirement
- Something product, BA, QA, and developers can all discuss
- The normal bridge between requirement and lower-level tasks

### What is intentionally not included here
- API endpoints
- database tables
- validation rules
- error handling flows
- developer task breakdown
- effort estimation
- assignee mapping

Those belong to later layers such as **story / task / technical design**.
