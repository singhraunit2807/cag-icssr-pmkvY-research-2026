# P5.2 — Beneficiary Verification & Eligibility Evidence Analysis

## Status
COMPLETE

## Scope
This sub-process analyses CAG Report No. 20 of 2025, Chapter 3, Para 3.2 and sub-paras 3.2.1–3.2.4, covering age, education, technical qualification, work experience and targeted-beneficiary onboarding.

## Evidence Matrix

| CAG evidence | Period / scope | Governance dimension | What it establishes | What it does NOT establish |
|---|---|---|---|---|
| Online PMKVY enrolment did not contain a mechanism to verify age/date of birth against Qualification Pack (QP) requirements. | PMKVY 1.0–3.0 audit evidence | Eligibility validation / system control | Eligibility rules were not fully translated into an automated enrolment control. | It does not mean every enrolled candidate was ineligible. |
| 6.54 lakh certified candidates across 705 job-roles had not attained the minimum entry age as per the QP used for the audit comparison. | PMKVY certified candidates; age analysis | Age verification | A substantial number of certifications were identified where recorded age was below the applicable minimum in the audit comparison. | It does not establish intentional misrepresentation or fraud. |
| Example: 52,214 candidates in Group Farming Practitioner and 40,953 in Self Employed Tailor were below the prescribed minimum age in the QP comparison. | PMKVY audit dataset | Age-rule compliance | The issue was not limited to a single isolated job-role. | Examples cannot be generalised beyond the analysed records. |
| 1,142 candidates below age 18 were trained/certified in Driver/Chauffeur-related job-roles, where the QP required minimum age 18 and a valid licence. | PMKVY audit data | Legally/operationally sensitive eligibility | The audit identified a specific mismatch between recorded age and job-role entry criteria. | The audit evidence quoted here does not establish whether every affected candidate lacked a valid licence. |
| PMKVY 4.0 data up to 9 Oct 2024 still showed 1.18 lakh underage candidates across 365 job-roles. | PMKVY 4.0; 9 Oct 2024 checkpoint | Reform implementation | The planned age-validation corrective mechanism had not fully operated at that audit checkpoint. | It does not describe the system after 9 Oct 2024. |
| Among 60,68,523 candidates certified in job-roles requiring education above Class 9, required information was not recorded in 6,77,807 cases (11.17%); 8,09,046 (13.33%) did not meet the required minimum educational qualification. | PMKVY audit analysis | Education verification / data completeness | Both missing qualification information and recorded qualification mismatches limited assurance that entry criteria were being enforced. | Missing information is not equivalent to failure to meet the qualification. |
| For job-roles requiring prior technical qualification, 1,05,493 of 1,23,533 certified candidates (85.40%) were classified as uneducated/basic literacy/regular education etc.; information was not recorded for 14,122 (11.43%). | PMKVY audit analysis | Technical qualification verification | The audit identified major mismatches between recorded educational status and technical-entry requirements. | The category analysis must not be interpreted as proof that all 1,05,493 were individually fraudulent or improperly trained; the audit compares recorded qualification categories with job-role criteria. |
| Work-experience field existed in the SIP data model but was not being recorded. The audit identified large certifications in job-roles requiring at least one year prior experience, including Food & Beverage Service–Steward (86,447), LED Light Repair Technician (16,990), and Dairy Farmer/Entrepreneur (70,639). | PMKVY audit analysis | Work-experience verification | A data-model provision did not translate into an operating verification mechanism for this eligibility criterion. | It does not prove that none of the candidates had the required experience; the problem is the absence of recorded evidence/control. |
| In PMKVY 4.0, as of October 2024, previous work-experience recording was still not in place; 40,897 candidates in job-roles requiring formal education from Class 9 and above lacked the required minimum qualification, and 4,361 in job-roles requiring prior technical education lacked the requisite qualification. | PMKVY 4.0; Oct 2024 | Reform/control implementation | The audit found that planned eligibility controls had not yet been successfully implemented even in PMKVY 4.0. | These figures are a specific audit checkpoint, not a current 2026 estimate. |
| STT was intended to target unemployed youth or school/college dropouts, but SIP registration did not capture employment status or dropout history. | PMKVY STT | Target-beneficiary verification | The system lacked core administrative fields needed to directly verify whether applicants belonged to the intended target group. | It does not establish that all enrolled candidates were employed or were not dropouts. |
| Ministry stated TPs would check employment and education status during registration/counselling, but Audit noted SIP lacked the information needed to verify adherence to targeting criteria. | PMKVY implementation | Reliance on manual/organisational control | Responsibility assigned to implementing agencies was not equivalent to system-level evidence that the criterion was verified. | It does not establish that TPs never performed such checks. |
| UDISE/UDISE+ was identified as a potential source for dropout information; Ministry reported work toward integration, with partial institution mapping on SIDH by June 2025. | Later reform context | Cross-system verification / interoperability | Cross-system data integration was recognised as a mechanism for improving targeted-beneficiary verification. | Partial mapping is not evidence of complete or effective integration. |

## Important methodological limitation: QP version

CAG noted that minimum qualification requirements could differ across versions of Qualification Packs/job-roles. The version of the QP/job-role under which training was actually imparted was not recorded for PMKVY 1.0 and for about 60.95 lakh certified candidates of PMKVY 2.0/3.0. Therefore, for age/education comparison, Audit used the latest available QP Master File.

This limitation must remain visible in the research. We should describe the findings as **CAG's audit comparison against the available/latest QP Master File**, rather than silently presenting every mismatch as a definitive contemporaneous eligibility violation.

## Analytical findings

### Finding 1 — Eligibility criteria existed, but validation was not embedded sufficiently in enrolment
The strongest governance issue is not simply that some candidates failed eligibility criteria. It is that the enrolment system did not consistently prevent or flag entry where age, education or other QP requirements were not met.

### Finding 2 — Data capture and eligibility verification are different controls
For education and work experience, the audit shows that having a field or an organisational responsibility is not enough. A field must be populated, validated against the relevant rule, and linked to a decision that prevents or flags non-compliant enrolment.

### Finding 3 — Work experience is a particularly clear example
The SIP data model had a provision to record work experience, but it was not being used. Therefore:

**Field exists → Data not recorded → Eligibility cannot be evidenced → Compliance control is not operational.**

This is a strong example of the study's broader argument that digital architecture alone does not guarantee governance effectiveness.

### Finding 4 — Targeting cannot be verified without target-group data
PMKVY STT was intended to target unemployed youth or school/college dropouts, but SIP did not capture employment status or dropout history. This creates a distinction between:

- **programme intention:** target a defined population;
- **registration data:** record the applicant;
- **verification capability:** demonstrate that the applicant belongs to the intended population.

The audit indicates a gap at the third stage.

### Finding 5 — Later controls should be evaluated by operation, not announcement
The Ministry reported planned PMKVY 4.0 controls for age and education. However, CAG's October 2024 examination still found underage candidates and qualification mismatches. Therefore, in later reform analysis, the study should distinguish:

**policy/control announced → system implementation → actual data behaviour → validated effectiveness.**

## Research-safe interpretation

> CAG evidence indicates that PMKVY's beneficiary-eligibility framework was weakened by gaps in system-based verification of age, education, technical qualification and work experience, as well as by limited data capture for identifying intended target groups such as unemployed youth and school/college dropouts. The evidence supports a governance concern about the reliability and enforceability of eligibility controls; it does not, by itself, establish fraudulent enrolment or intentional misuse.

## Connection to the overall framework

P5.2 strengthens this chain:

**Eligibility Rule → Data Capture → Automated/Documented Verification → Eligibility Decision → Reliable Beneficiary Record → Monitoring**

The critical failure point identified by the audit is the transition from **rule** to **operational verification**.

## Evidence boundary

Do not use these findings to claim:
- all underage/underqualified candidates were fraudulent;
- all candidates without recorded work experience lacked actual experience;
- PMKVY as a whole failed to target unemployed youth;
- digital systems caused poor employment outcomes.

Use them to analyse the **reliability, completeness and operational enforcement of eligibility controls**.

## Primary source

Comptroller and Auditor General of India, *Report No. 20 of 2025: Skill Development under Pradhan Mantri Kaushal Vikas Yojana*, Chapter 3, Paras 3.2.1–3.2.4, pp. 33–37/38.

## Next
P5.3 — Monitoring, Evidence Validation & System-Control Analysis.
