# P5.1 — Data Quality & Data Governance Evidence Analysis

## Status
COMPLETE

## Scope
This sub-process analyses CAG Report No. 20 of 2025, primarily Para 2.4 (Data management and IT control framework for PMKVY), covering PMKVY 1.0–3.0 audit evidence and the later PMKVY 4.0 observations reported by CAG.

## Evidence Matrix

| Evidence | Period / Scope | Governance dimension | What the evidence establishes | What it does NOT establish |
|---|---|---|---|---|
| No Ministry policy for retention of PMKVY electronic records; PMKVY 1.0 attendance, trainer/assessor ID/contact and training-location/assessment information was not retained. | PMKVY 1.0; audit of first three phases | Data retention / evidence traceability | Records required for reconstructing parts of the implementation trail were not consistently retained. | It does not by itself prove that the underlying training did not occur. |
| RPL photographs/videos were not retained at NSDC and were available only with SSCs/TPs/TCs; some evidence was incomplete or not linked to candidate attendance. | RPL; audit evidence | Evidence traceability | Central auditability and linkage between evidence and candidate/batch records were weak. | It does not prove that every RPL activity lacked supporting evidence. |
| Data retention policy was absent; CAG said inadequate retention prevented evidence production and disrupted the transaction trail. | PMKVY 1.0–3.0 audit | Internal control / traceability | Retention is a control requirement, not merely a storage issue, because it affects later verification and auditability. | It does not establish intentional concealment. |
| Data Governance Framework was issued in April 2022, after completion of all three phases, and CAG found that it did not adequately address key ownership, security and management issues in line with IT Act requirements. | April 2022; PMKVY 1.0–3.0 ended March 2022 | Governance framework | Formalisation of governance occurred late relative to the audited phases and was assessed by CAG as incomplete. | It does not mean no data governance activity existed before April 2022. |
| Private-sector stakeholders including SSCs, TPs and TCs had access to end-to-end transaction/personal data; NSDC stated it had received no Ministry guidelines/instructions on data security. | PMKVY implementation period; Ministry update June 2025 | Data security / privacy | The audit identified a need for clearer data-security, sharing and privacy controls across a multi-actor ecosystem. | It does not prove that personal data was misused or breached. |
| Trainer ID was null/0 in 2,30,758 of 3.39 lakh analysed PMKVY 2.0/3.0 batches, involving 61,12,030 certified candidates. Assessor contact was null/none in 3,27,220 batches, involving 93,01,810 certified candidates. | PMKVY 2.0–3.0; 3.39 lakh batches | Record completeness / identity traceability | Mandatory system fields did not reliably result in complete, usable trainer/assessor identity/contact records. | It does not prove that those candidates were trained by unauthorised persons. |
| CAG noted that an initially required IT control was later revoked and concluded that non-recording of trainer/assessor identification and contact details did not provide assurance regarding completion of essential steps leading to certification. | PMKVY 2.0–3.0 | IT control design and enforcement | Control existence and control continuity matter; weakening a control during implementation can reduce assurance. | It does not establish that all affected certifications were invalid. |
| Bank-account field was zero/null/N/A/blank for 90,66,264 of 95,90,801 PMKVY 2.0/3.0 participants (94.53%). 12,122 unique bank accounts were repeated for 52,381 participants. Apparent invalid account values were also found. | PMKVY 2.0–3.0 | Data quality / beneficiary identity / payment traceability | The account-data field had substantial completeness and validity problems, limiting assurance from that field about participant identity and payment traceability. | It does not prove duplicate beneficiaries or fraud. |
| Ministry reported 61.14 lakh of 95.91 lakh candidates had received DBT by October 2024; CAG noted payments to more than 34 lakh certified candidates had not been made and that information on efforts to ensure payment was insufficient. | Data updated Oct 2024 | Payment/outcome traceability | Incomplete information was associated with a substantial unresolved payment-tracking issue at the date reported. | Non-payment does not by itself establish ineligibility or fraud. |
| 179,407 unique emails were used for 7,120,995 candidates; 390,508 unique mobile numbers were used for 1,056,475 candidates in repeated-entry patterns. ‘Migrated data’ appeared for Candidate_Email for 36,49,344 candidates. About 87,000 mobile numbers had invalid/dummy-like patterns. | PMKVY 2.0–3.0 | Contact-data quality | Contact fields could not reliably serve as unique, accurate channels for beneficiary communication. | It does not establish that all repeated contacts belonged to unrelated persons. |
| In an audit survey of 4,330 beneficiaries certified during 2019–21, 36.51% of emails failed delivery; only 171 candidates (3.95%) responded; 131 responses (76.61% of responses) came from the same email ID or TP/TC-linked IDs. | Audit beneficiary survey | Feedback-data reliability | Poor contact-data quality materially constrained the audit's ability to obtain beneficiary feedback from the sampled population. | The 171 responses cannot be treated as representative of all PMKVY beneficiaries. |
| Ministry stated PMKVY 4.0 would mandate mobile/email and Aadhaar-based e-KYC. CAG's analysis of 9.45 lakh certified PMKVY 4.0 candidates up to 9 Oct 2024 still found 175 invalid and 2,263 repeated mobile numbers, >2.72 lakh null emails and >3.08 lakh repeated emails. | PMKVY 4.0 data up to 9 Oct 2024 | Control implementation | At that checkpoint, CAG found that the assured IT controls had not fully translated into clean contact data. | It does not establish the status of the system after 9 Oct 2024. Later reforms must be analysed separately. |

## Analytical findings

### Finding 1 — Digital infrastructure did not automatically produce reliable administrative data
PMKVY used the Skill India Portal across the implementation cycle, but CAG found substantial missing, null, repeated, invalid and unretained data. The research implication is that digitisation should be analysed as a governance system requiring validation, retention, identity controls and accountability, rather than as a sufficient condition for reliable administration.

### Finding 2 — Completeness and validity are separate controls
The bank-account, trainer/assessor and contact-data findings show that a field being present in a data model does not guarantee that the value entered is complete, valid, unique or usable. This distinction is central to the study's data-governance argument.

### Finding 3 — Control relaxation creates a governance problem when no alternative control is documented
CAG reported that some contact/bank fields were initially mandatory and later relaxed because of implementation difficulties, but alternative audit-trail controls were not put in place. The defensible research interpretation is that control design must account for ground realities before enforcement, and any relaxation should be paired with a documented compensating control.

### Finding 4 — Data quality affects feedback and oversight, not only record keeping
The beneficiary survey demonstrates a direct governance consequence: unreliable electronic identity/contact information limited the ability to collect beneficiary feedback. Therefore, data quality is connected to monitoring and course correction, not only database cleanliness.

### Finding 5 — Control existence, control operation and control effectiveness must be distinguished
The PMKVY 4.0 observation is useful because CAG examined whether promised controls were reflected in actual data. The presence of a stated e-KYC/contact requirement was not treated as proof of effective operation when invalid/null/repeated data persisted.

## Research-safe interpretation
The strongest defensible statement from P5.1 is:

> CAG evidence indicates that the reliability of PMKVY's digital administrative information was constrained by weaknesses in data retention, record completeness, field validity, identity/contact traceability and continuity of IT controls. These weaknesses affected the ability to verify implementation records and obtain beneficiary feedback. The audit evidence does not, by itself, establish fraud, fabricated beneficiaries or causal effects on employment outcomes.

## Evidence chain
**Digital system → Data capture → Validation → Identity/contact traceability → Retention → Auditability → Feedback**

The chain shows why a digital platform can exist while governance reliability remains incomplete.

## Sources
Primary source: Comptroller and Auditor General of India, Report No. 20 of 2025, Skill Development under Pradhan Mantri Kaushal Vikas Yojana, especially Paras 2.4, 2.4.1 and 2.4.2.

## Next
P5.2 — Beneficiary Verification & Eligibility Evidence Analysis.
