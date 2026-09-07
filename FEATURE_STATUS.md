# Feature status — Healthcare revenue & payer reconciliation

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 591 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 0 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 0 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 0 | 0 | Native records/view |
| Reports & analytics | report | 40 | 0 | Native records/view |
| Activity & audit trail | audit | 39 | 0 | Native records/view |
| Provider connections | integration | 8 | 0 | Provider request records only |
| Dispatch trip ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Patient payer eligibility | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Origin destination modifiers | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Loaded mileage calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Service level determination | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Medical necessity evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Physician certification control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Repetitive transport authorization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Signature evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim generation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Denial classification | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Appeal package generation | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Secondary payer coordination | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Remittance reconciliation | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Base mileage payer analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Plan classification mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Benefit limit comparison | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| NQTL inventory | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Prior authorization comparison | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Concurrent review comparison | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Medical necessity criteria review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Network admission analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reimbursement methodology comparison | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Denial rate analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Out-of-network access analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Comparative analysis workbench | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Member impact calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Corrective action workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Regulator evidence package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Parity governance dashboard | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| PPO contract library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Leased-network mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Provider location registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| CDT procedure catalog | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim EOB ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fee schedule repricing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Alternate benefit analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Downgrade validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Frequency limitation review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bundling analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| COB calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Missing payment detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Appeal generation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Corrected claim submission | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payer procedure analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Patient eligibility registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Treatment ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ESRD base rate library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Wage index adjustment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Low-volume adjustment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rural adjustment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Onset adjustment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Comorbidity adjustment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Training add-on calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| TDAPA treatment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Outlier service calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Missing treatment detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim reconciliation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Facility modality analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Equipment HCPCS registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Patient order tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Coverage necessity rules | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Proof-of-delivery control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Prior authorization | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Capped rental tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Purchase versus rental calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Competitive bidding adjustment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Oxygen supply replenishment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Same-or-similar validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Denial appeal workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Asset return tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product payer profitability | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Stop-loss policy library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Covered census registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Medical claim ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pharmacy claim ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Specific attachment calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Aggregate attachment calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Aggregating-specific deductible | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Run-in and run-out validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contract basis and exclusion analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Paid-claim evidence package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Laser and amendment control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier submission workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier request management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reimbursement reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| High-cost claimant forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Site rate registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Managed-care contract mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Encounter ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Qualifying visit validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Same-day visit rules | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| PPS rate calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| APM rate calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| MCO payment allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Wrap amount calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duplicate encounter control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| State submission file | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Error response remediation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payment receipt matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Aging and appeal workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Site plan analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Member eligibility | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim encounter ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Administrative fee validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Discount guarantee calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rebate guarantee validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Service-level measurement | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Implementation milestones | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Clinical outcome guarantee | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Engagement guarantee | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Data delivery SLA | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Performance credit calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor evidence request | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Settlement negotiation workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit outcome reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Member coverage registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| COB questionnaire workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Medicare eligibility matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Employer plan matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dependent birthday rule | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Working-aged rules | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Disability ESRD rules | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Accident liability detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim payer-order calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Overpayment identification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Provider recovery notice | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Primary payer rebilling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Member appeal evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recovery cash ledger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| COB root-cause analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contract ingestion & versioning | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim and 835 remittance ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contractual claim repricing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| DRG and case-rate validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fee-schedule validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bundling and carve-out analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Stop-loss and outlier calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Denial and adjustment classification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Authorization evidence control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Timely-filing deadline control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Underpayment case workbench | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payer appeal package generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payer response tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash posting reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recovery and root-cause analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Patient episode registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Plan-of-care tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Order and signature control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Face-to-face validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| EVV event ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Scheduled versus delivered visits | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Missing check-in remediation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| OASIS validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| PDGM grouping reconstruction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| LUPA threshold monitoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Comorbidity adjustment validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim generation and scrub | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Episode profitability analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Election benefit registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Beneficiary count calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Service-day ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transfer allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Live-discharge treatment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payment ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Aggregate cap calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Proportional method | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Streamlined method | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Inpatient day ratio | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sequestration treatment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Notice reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Liability forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Settlement payment workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Provider cap analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Implant and device master | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor contract library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| OR case ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Implant-log ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Barcode and UDI reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Preference-card comparison | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor invoice matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Charge capture validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| HCPCS and revenue-code mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim-line reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Missing-charge detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duplicate implant charge detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contract price variance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payer reimbursement comparison | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Corrected-claim workflow | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Procedure vendor and surgeon analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Encounter timeline reconstruction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Admission order validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Observation order validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Two-midnight evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Condition code 44 control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Utilization review queue | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Medical necessity scoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bed-status reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Hours and unit calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Ancillary charge capture | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim status coding | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Denial root-cause analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Appeal packet generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payment reconciliation | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Status revenue analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Hospitals & Files | records | 1 | 0 | Native records/view |
| Rate Integrity | records | 1 | 0 | Native records/view |
| Compliance | records | 2 | 0 | Native records/view |
| Benchmarks | records | 1 | 0 | Native records/view |
| Hospital | records | 1 | 0 | Native records/view |
| MRF File | records | 1 | 0 | Native records/view |
| Rate Entry | records | 1 | 0 | Native records/view |
| Completeness Test | records | 1 | 0 | Native records/view |
| Percentile Check | records | 1 | 0 | Native records/view |
| Code Normalization | records | 1 | 0 | Native records/view |
| Accessibility Check | records | 1 | 0 | Native records/view |
| Attestation | records | 2 | 0 | Native records/view |
| CMS Warning | records | 1 | 0 | Native records/view |
| Corrective Action | records | 1 | 0 | Native records/view |
| Benchmark Report | records | 1 | 0 | Native records/view |
| Validation Run | records | 1 | 0 | Native records/view |
| Draft: MRF Validator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Rate Benchmark Analyst | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Attestation Drafter | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Department eligibility registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Ownership licensure evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Campus-distance validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Public awareness evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Patient notice control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Professional facility claim linking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Place-of-service validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| PO modifier control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| PN modifier control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Site-neutral payment calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Split-billing validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Charge capture review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Department economics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Inpatient claim ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Discharge status validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transfer destination matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Post-acute claim linkage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| DRG transfer-rule library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Geometric mean LOS validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Per-diem payment reconstruction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Same-day readmission analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Interrupted stay review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payer policy versioning | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Underpayment detection | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Corrected claim generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Appeal evidence package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Facility DRG analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Test and panel catalog | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Order specimen ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Medical necessity validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Diagnosis coverage rules | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ABN evidence management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Panel bundling validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| CPT modifier control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reference-lab invoice matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payer fee schedule calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim submission | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Client versus payer billing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Test payer and provider analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Member identity resolution | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Eligibility span ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Interstate coverage matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Medicare overlap detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Marketplace overlap detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Managed-care enrollment reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Capitation overpayment calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fee-for-service claim review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Retro termination validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Provider notification workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Member due-process evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Plan recovery demand | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash recovery tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Eligibility control remediation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Program integrity analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Program authority library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Provider eligibility registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Base claim ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Uncompensated care calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Upper payment limit control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| DSH limit calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Directed payment methodology | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quality pool scoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Provider tax interaction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Intergovernmental transfer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pool allocation calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| State payment file matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Provider dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash reconciliation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Program provider analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contract price library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Distributor customer mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Device SKU registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sales trace ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Eligibility validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contract price calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Chargeback validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duplicate claim detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Volume rebate calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Price-protection calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Return credit coordination | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Distributor deduction matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Settlement reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Device channel analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contract and segment registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Star measure ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cut-point version control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Enrollment month reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| County benchmark mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quality bonus factor calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rebate percentage validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Double-bonus county logic | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| New-plan treatment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Low-enrollment plan treatment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payment report ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Expected revenue calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| CMS variance case workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Revenue true-up ledger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contract quality economics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Provider and filing-year registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Trial-balance import and mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cost-center classification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Overhead step-down allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Medicare utilization statistics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| PS&R reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Medicare bad-debt recovery | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| DSH and uncompensated-care support | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| IME and GME reimbursement | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Wage-index data validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Related-party cost review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cost-report schedule preparation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Desk-review request management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reopening and appeal workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reimbursement outcome analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Members & Diagnoses | records | 1 | 0 | Native records/view |
| Evidence | records | 1 | 0 | Native records/view |
| Submissions & Exposure | records | 1 | 0 | Native records/view |
| Audit Year | records | 1 | 0 | Native records/view |
| Member | records | 1 | 0 | Native records/view |
| Diagnosis | records | 1 | 0 | Native records/view |
| Evidence Document | records | 1 | 0 | Native records/view |
| Chart Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| HCC Gap | records | 1 | 0 | Native records/view |
| RADV Submission | records | 1 | 0 | Native records/view |
| Repayment Estimate | records | 1 | 0 | Native records/view |
| Coding Appeal | records | 1 | 0 | Native records/view |
| Vendor File | records | 1 | 0 | Native records/view |
| Audit Finding | records | 1 | 0 | Native records/view |
| Compliance Task | records | 1 | 0 | Native records/view |
| Draft: HCC Evidence Validator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Repayment Exposure Estimator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Evidence Gap Scanner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Beneficiary eligibility verification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Liability event registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Conditional payment ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim relatedness review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Unrelated claim dispute | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Procurement cost allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Demand amount calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Settlement reporting control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Section 111 evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Final demand tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Appeal waiver workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Release letter evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Settlement reserve forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Case outcome analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payer contract library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Neonatal case registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Acuity level timeline | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Daily census reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Case-rate episode logic | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Included service validation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Implant carve-out calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Drug carve-out calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transport carve-out review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Outlier threshold calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Stop-loss calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim remittance matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payer appeal workflow | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Program payer analytics | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Payer transplant contract library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Patient case registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Evaluation phase tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Organ acquisition cost | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Donor procurement expense | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Case-rate episode definition | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Excluded service validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Outlier stop-loss calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Professional facility reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Travel lodging benefit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim remittance ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contract rate library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Member month ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Risk cell mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Age sex factor calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Retro eligibility reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carve-out validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Encounter completeness | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Stop-loss recovery | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Withhold calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quality pool allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Risk corridor settlement | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payment statement matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Variance dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Group plan analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Case Model | records | 1 | 0 | Native records/view |
| Case Queue | records | 1 | 0 | Native records/view |
| Patient & Provider | records | 1 | 0 | Native records/view |
| Payer & Plan | records | 1 | 0 | Native records/view |
| Codes & Service | records | 1 | 0 | Native records/view |
| Case History | records | 1 | 0 | Native records/view |
| Case Timeline | records | 1 | 0 | Native records/view |
| Lifecycle Progress | records | 1 | 0 | Native records/view |
| Stage Activity | records | 1 | 0 | Native records/view |
| Status Changes | records | 1 | 0 | Native records/view |
| Next Actions | records | 1 | 0 | Native records/view |
| Payer Rule Engine | records | 1 | 0 | Native records/view |
| Policy Matching | records | 1 | 0 | Native records/view |
| Required Criteria | records | 1 | 0 | Native records/view |
| Prior Therapy Checks | records | 1 | 0 | Native records/view |
| Contraindications | records | 1 | 0 | Native records/view |
| Rule Confidence | records | 1 | 0 | Native records/view |
| Evidence Gap Detection | records | 1 | 0 | Native records/view |
| Missing Evidence | records | 1 | 0 | Native records/view |
| Evidence Checklist | records | 1 | 0 | Native records/view |
| Clinical Notes | records | 1 | 0 | Native records/view |
| Labs & Imaging | records | 1 | 0 | Native records/view |
| Medication / Therapy History | records | 1 | 0 | Native records/view |
| Packet Builder | records | 1 | 0 | Native records/view |
| Packet Readiness | records | 1 | 0 | Native records/view |
| Cover Letter | records | 1 | 0 | Native records/view |
| Attached Evidence | records | 1 | 0 | Native records/view |
| Form Validation | records | 1 | 0 | Native records/view |
| Submission Bundle | records | 1 | 0 | Native records/view |
| Submissions + Integrations | integration | 1 | 0 | Provider request records only |
| Submission Queue | records | 1 | 0 | Native records/view |
| Connector Status | integration | 1 | 0 | Provider request records only |
| Status Polling | records | 1 | 0 | Native records/view |
| Fax / Email / SFTP | records | 1 | 0 | Native records/view |
| EHR / FHIR | records | 1 | 0 | Native records/view |
| Appeals Workspace | records | 1 | 0 | Native records/view |
| Denials | records | 2 | 0 | Native records/view |
| Appeal Deadlines | records | 1 | 0 | Native records/view |
| Appeal Drafts | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reviewer Assignment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Resubmissions | records | 1 | 0 | Native records/view |
| SLA Automation | records | 1 | 0 | Native records/view |
| SLA Queue | records | 1 | 0 | Native records/view |
| Overdue Cases | records | 1 | 0 | Native records/view |
| Urgent Cases | records | 1 | 0 | Native records/view |
| Escalations | records | 1 | 0 | Native records/view |
| Notification Triggers | records | 1 | 0 | Native records/view |
| Approval / Denial Rates | records | 1 | 0 | Native records/view |
| Payer Trends | records | 1 | 0 | Native records/view |
| Procedure Trends | records | 1 | 0 | Native records/view |
| Turnaround Time | records | 1 | 0 | Native records/view |
| Evidence Gap Trends | records | 1 | 0 | Native records/view |
| Compliance / Security | records | 1 | 0 | Native records/view |
| Access Controls | records | 1 | 0 | Native records/view |
| PHI Redaction | records | 1 | 0 | Native records/view |
| Sessions | records | 1 | 0 | Native records/view |
| Environment Config | records | 1 | 0 | Native records/view |
| Provider master registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| License credential monitoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sanction exclusion screening | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Ownership disclosure tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Practice location control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reassignment management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payer application workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Revalidation deadline engine | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| PECOS data comparison | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Roster submission tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payer response remediation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim hold detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| At-risk revenue calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Enrollment evidence package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Provider payer analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Golden Records | records | 2 | 0 | Native records/view |
| Rosters & FHIR | records | 1 | 0 | Native records/view |
| Adequacy & Outreach | records | 1 | 0 | Native records/view |
| CMS Filing | records | 1 | 0 | Native records/view |
| Provider | records | 1 | 0 | Native records/view |
| Practice Location | records | 1 | 0 | Native records/view |
| Credential | records | 1 | 0 | Native records/view |
| Roster File | records | 1 | 0 | Native records/view |
| FHIR Validation | records | 1 | 0 | Native records/view |
| Adequacy Measure | records | 1 | 0 | Native records/view |
| Outreach Campaign | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Correction Request | records | 1 | 0 | Native records/view |
| Directory Snapshot | records | 1 | 0 | Native records/view |
| Plan Finder Submission | records | 1 | 0 | Native records/view |
| Network Contract | records | 1 | 0 | Native records/view |
| Draft: Golden Record Matcher | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Network Adequacy Reviewer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Clinic status registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Trial balance ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Visit count validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Provider FTE calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Productivity standard analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Allowable cost classification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Overhead allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vaccine cost carve-out | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Telehealth treatment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bad debt analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Interim rate reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AIR calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cost report schedule generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Settlement forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Clinic cost analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Resident and stay registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| MDS assessment ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ICD-10 category mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| PT component calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| OT component calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| SLP component calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Nursing component calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| NTA component calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Variable per-diem adjustment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Interrupted-stay validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| HIV AIDS adjustment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Consolidated billing control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| VBP adjustment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Facility reimbursement analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Program agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Patient attribution reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Benchmark construction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Historical expenditure validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Trend factor calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Risk adjustment validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim completion factor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quality score calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Minimum savings rate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Risk corridor calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Shared savings calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Shared loss calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payer settlement audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Provider distribution workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Program performance analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Chatbot | records | 1 | 0 | Native records/view |
| Claims Management | records | 1 | 0 | Native records/view |
| Patient Billing | records | 1 | 0 | Native records/view |
| Payment Tracking | records | 1 | 0 | Native records/view |
| Charge Capture | records | 1 | 0 | Native records/view |
| Insurance Verification | records | 1 | 0 | Native records/view |
| Payer Contracts | records | 1 | 0 | Native records/view |
| Aging Reports | records | 1 | 0 | Native records/view |
| Coding Optimization | records | 1 | 0 | Native records/view |
| Audit Trail | records | 1 | 0 | Native records/view |
| AI Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Production Gaps | records | 1 | 0 | Native records/view |
| Production Controls | records | 1 | 0 | Native records/view |
| Denial Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Coding Recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contract Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim Prioritizer | records | 1 | 0 | Native records/view |
| Compliance Risk Checker | records | 1 | 0 | Native records/view |
| Prior Auth Predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| EHR Integration | integration | 1 | 0 | Provider request records only |
| Payer API Integration | integration | 1 | 0 | Provider request records only |
| Appeal Workflow | records | 1 | 0 | Native records/view |
| Provider Credentials | records | 1 | 0 | Native records/view |
| Notification Engine | records | 1 | 0 | Native records/view |
| Webhook Payer Events | integration | 1 | 0 | Provider request records only |
| Clinical Notes Upload | records | 1 | 0 | Native records/view |
| agentic denial management autonomously d | records | 1 | 0 | Native records/view |
| revenue cycle optimization modeling clai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| payer contract intelligence identifying | records | 1 | 0 | Native records/view |
| prior auth automation submitting followi | records | 1 | 0 | Native records/view |
| coding quality compliance auditor flaggi | records | 1 | 0 | Native records/view |
| patient payment intelligence predicting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rules & Jobs | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 591 feature pages were visited in the browser; 589 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 454 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

454 original AI entries are now grouped into **7 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
