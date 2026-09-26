# Process 7 — Evidence-Backed Data Analysis & Results Architecture

## Status
Complete.

## Purpose

This process converts verified CAG observations into a results architecture suitable for the eventual research article. It does not draft the final article. The objective is to establish:

- which numerical findings are safe to report;
- what denominator/population/period belongs with each number;
- which calculations are descriptive only;
- how findings should be grouped into analytical dimensions;
- what belongs in Results versus Discussion;
- which previously identified numbers require re-verification before use.

Primary source: Comptroller and Auditor General of India, Report No. 20 of 2025, *Skill Development under Pradhan Mantri Kaushal Vikas Yojana*. The report was tabled on 18 December 2025. The audit mainly covers PMKVY 1.0–3.0 and distinguishes later PMKVY 4.0 developments. 

## 1. Evidence discipline

Every result should follow:

**Claim → exact figure → denominator/population → period → source → analytical interpretation**

The following rules apply:

1. Do not report a percentage without its denominator.
2. Do not combine PMKVY 1.0–3.0 audit evidence with PMKVY 4.0 evidence without explicitly separating periods.
3. Do not generalise findings from the eight selected States to all States unless the source itself provides an all-India figure.
4. Do not convert a data anomaly into a fraud finding.
5. Do not interpret a placement percentage as evidence of a causal effect of digital governance.
6. Do not treat government-reported later reforms as independent proof of effectiveness.
7. Do not silently replace a CAG denominator with a broader programme denominator.

## 2. Verified results suitable for the Results section

### Table 1. Electronic identity and participant-data reliability

| Indicator | Verified audit evidence | Scope / denominator | Analytical meaning |
|---|---:|---|---|
| Missing/invalid bankAccountdetails | 90,66,264 | 95,90,801 PMKVY 2.0/3.0 participants | 94.53% of records had zero, Null, N/A or blank values in the field |
| Repeated bank accounts | 12,122 unique accounts | Used for 52,381 participants | Repeated account identifiers weakened assurance about participant identity |
| Trainer ID null/0 | 2,30,758 batches | 61,12,030 certified candidates | Weak traceability of trainer identity in a substantial certified-candidate population |
| Assessor contact null/none | 3,27,220 batches | 93,01,810 certified candidates | Weak traceability of assessor contact information |
| Assessor ID 0.00 | 46 batches | 874 candidates | Specific system-data anomaly |

CAG states that the bank-account field analysis did not provide adequate assurance about participant identity. It also states that non-recording of trainer/assessor identification and contact details did not provide assurance regarding completion of essential steps leading to certification. citeturn0search25turn2search0

### Table 2. Beneficiary feedback and identity/contact reliability

| Indicator | Verified evidence | Interpretation |
|---|---:|---|
| Trainees submitting feedback | 73,100 | Less than 1% of certified candidates as of September 2022 |
| Beneficiary survey contacted | 4,330 | CAG's survey population |
| Survey email failures | 36.51% | Evidence of weak electronic contact reliability |
| Survey response rate | 3.95% | Very limited response coverage |
| Responses linked to same email/TP/TC email IDs | 76.61% | Further limitation on independent beneficiary feedback |

The official CAG report states that only 73,100 trainees, less than one per cent of certified candidates, had submitted feedback across the three phases as of September 2022. It also records problems in the beneficiary survey linked to incorrect electronic identity information. citeturn1search0

### Table 3. Beneficiary eligibility and verification

The CAG report identified:

- 6.54 lakh certified candidates across 705 job roles who had not attained the minimum entry age identified through the audit's comparison;
- 1,142 under-18 candidates in Driver/Chauffeur roles requiring age 18;
- 40,897 candidates certified in roles requiring formal education from Class 9 onward without the required qualification;
- 4,361 candidates in roles requiring prior technical education without the requisite qualifications.

**Interpretation rule:** these findings must be described as CAG audit findings based on the available data and qualification-pack comparison. The report notes limitations because the version of the Qualification Pack/job-role requirement under which training was actually imparted was not recorded for PMKVY 1.0 and for a large PMKVY 2.0/3.0 population. Therefore, the final article must not describe every identified record as a definitive contemporaneous eligibility violation without this qualification.

### Table 4. Monitoring and evidence-validation findings

Verified findings include:

- 1,463 inspection reports were examined.
- 45 inspection reports used the same photograph as evidence for different trainings.
- 80 instances involved the same NSDC inspector reporting at multiple locations in different States on the same day.
- 24 Training Centres had AEBAS biometric devices not installed or not working.
- CAG identified substantial deficiencies in geo-tagged inspection evidence and recommended stricter system-validation checks.

The report links these findings to weaknesses in the reliability and validation of monitoring evidence rather than automatically characterising every case as deliberate fabrication. citeturn0search26

### Table 5. Centre-State monitoring and integration

Verified findings:

- In six of the eight audited States — Assam, Bihar, Jharkhand, Kerala, Maharashtra and Odisha — State Skill Development Missions lacked access to central-component training data from NSDC.
- This limited their monitoring ability.
- Three States — Assam, Jharkhand and Odisha — reported that State/District Skill Monitoring Committees had never been formed.
- As of September 2022, only 73,100 trainees had submitted feedback across all three phases.

These findings are especially relevant to the research dimension of **information usability for oversight**, because the issue is not merely whether data exist centrally, but whether the relevant sub-national authority can access and use them for monitoring. citeturn1search0

### Table 6. Placement outcomes

CAG reports that, among candidates certified under STT/SP components:

| Phase | Certified | Placed | Placement rate |
|---|---:|---:|---:|
| PMKVY 1.0 | 13.32 lakh | 2.23 lakh | 16.74% |
| PMKVY 2.0 | 40.37 lakh | 20.62 lakh | 51.08% |
| PMKVY 3.0 | 2.45 lakh | 0.33 lakh | 13.47% |
| Total | 56.14 lakh | 23.18 lakh | 41.29% |

CAG also reported concerns regarding placement evidence in Kerala.

**Interpretation boundary:** these figures describe reported certification and placement outcomes. They do not establish that data-quality or digital-governance weaknesses caused the observed placement rates. citeturn0search26

## 3. Descriptive calculations to use

The study should use only transparent descriptive calculations.

### A. Missing bank-account field

90,66,264 / 95,90,801 × 100 = **94.53%**

This percentage is directly reported by CAG and should be reproduced without changing the denominator. citeturn0search25

### B. Repeated bank accounts

52,381 participants / 95,90,801 total participants × 100 ≈ **0.55%**

This is a researcher-calculated descriptive ratio. It should be presented only if the article needs the relationship to the full dataset; otherwise, the CAG's raw figure is sufficient.

### C. Feedback participation

CAG describes 73,100 feedback submissions as **less than one per cent of certified candidates** as of September 2022. The article should retain CAG's formulation unless the exact denominator used by the report is reproduced. citeturn1search0

### D. Placement

Placement rates are already reported by CAG. No recalculation is necessary unless a table requires consistency checking. The article should use CAG's phase-specific denominators.

## 4. Results architecture

The Results section should contain five empirical subsections:

### Result 1 — Data reliability

Evidence:
- missing/invalid bank-account field;
- repeated account identifiers;
- trainer/assessor identification gaps;
- contact-data problems;
- retained/missing electronic evidence.

Research meaning:
The audit reveals weaknesses in the reliability and traceability of programme information.

### Result 2 — Beneficiary verification

Evidence:
- age/entry-criteria findings;
- education/qualification findings;
- lack of adequate verification mechanisms;
- limitations concerning Qualification Pack versions.

Research meaning:
The digital registration process did not always ensure that recorded beneficiary information was sufficient for reliable eligibility verification.

### Result 3 — Monitoring and validation

Evidence:
- inspection reports;
- repeated photographs;
- same-day multi-location reporting;
- AEBAS device problems;
- geo-location/system-validation weaknesses.

Research meaning:
Monitoring reliability depends on validation controls surrounding the evidence generated by the digital system.

### Result 4 — Information integration, access and feedback

Evidence:
- six of eight audited States lacked access to central-component data;
- monitoring committees not functioning/formed in some States;
- low feedback participation;
- beneficiary survey response/contact limitations.

Research meaning:
The governance problem extends from data generation to administrative usability.

### Result 5 — Outcome tracking

Evidence:
- phase-wise certification and placement figures;
- CAG observations concerning placement evidence;
- limited feedback/outcome information;
- later PMKVY 4.0 post-certification tracking as a separate reform layer.

Research meaning:
Programme outcome information should be interpreted as an administrative monitoring issue as well as a performance indicator. No causal digital-governance claim should be made.

## 5. Results versus Discussion

### Results should answer:
**What did the evidence show?**

Examples:
- 94.53% of PMKVY 2.0/3.0 records had zero, Null, N/A or blank bank-account details.
- Six of eight audited States lacked access to central-component training data.
- Only 73,100 trainees had submitted feedback by September 2022.

### Discussion should answer:
**What do those findings mean for governance?**

Examples:
- A digital platform can generate large administrative datasets without automatically producing reliable information for verification.
- Central data availability is not equivalent to effective Centre-State information usability.
- Feedback systems need both valid contact data and mechanisms ensuring that collected feedback can be used for course correction.

## 6. Results-to-research-question mapping

| Research question | Main evidence block |
|---|---|
| RQ1: data-quality, retention and IT-control weaknesses | Tables 1 and electronic-evidence findings |
| RQ2: identity, age, education and eligibility verification | Table 3 |
| RQ3: monitoring, validation and Centre-State integration | Tables 4 and 5 |
| RQ4: PMKVY 4.0/SIDH response | P6 comparative reform analysis |
| Main RQ: governance implications and strengthening measures | P5 integrated framework + P6 + P7 results |

## 7. Evidence not yet safe for final numerical use

The following figures were previously identified through secondary/non-primary material and must be reverified against the official CAG PDF before entering the final article:

- 6,77,807 candidates missing required qualification information;
- 8,09,046 candidates not meeting minimum education in the specified dataset;
- detailed technical-qualification subgroup percentages;
- exact certification-delay denominators and percentages;
- exact AEBAS-compliance percentage based on the 98,488-batch dataset;
- exact 84.21% geo-tagging denominator if the table is used;
- any additional detailed numbers sourced only from non-primary mirrors.

Until verified:

**Status = Evidence insufficient — do not include in final Results.**

## 8. Three-level analytical reading of results

### Level 1 — Data reliability
Can the record be trusted as complete, valid and traceable?

### Level 2 — Control reliability
Do verification, monitoring and validation mechanisms operate sufficiently to detect and correct errors?

### Level 3 — Governance usefulness
Can authorised programme managers use the resulting information for monitoring, feedback and course correction?

The central analytical insight is that failure at Level 1 can weaken Level 2, while failure at Level 2 can reduce the usefulness of information at Level 3. This is a researcher-developed analytical interpretation, not a CAG quotation.

## 9. Proposed Results tables for final article

The final article should not reproduce every audit number. A concise set of high-value tables is preferable:

1. **Table 1 — Selected CAG findings on data reliability and verification**
2. **Table 2 — Monitoring, validation and Centre-State information-access findings**
3. **Table 3 — Phase-wise certification and placement outcomes**
4. **Table 4 — CAG weakness → governance requirement → PMKVY 4.0/SIDH response → evidence maturity**

The narrative should explain the analytical significance of each table instead of repeating every cell.

## 10. P7 conclusion

The verified evidence supports a coherent empirical chain:

**Data reliability weaknesses → weaker beneficiary/transaction traceability → verification limitations → monitoring-validation weaknesses → restricted information usability → limited feedback/course-correction capacity**

This should be presented as an analytical chain supported by multiple CAG findings, not as a statistically proven causal pathway.

The evidence also supports a second, separate chain:

**CAG-identified weakness → subsequent governance response → evidence maturity assessment**

This allows the final study to examine reform without claiming reform effectiveness beyond the evidence.

## Sources

- CAG, *Report No. 20 of 2025: Skill Development under Pradhan Mantri Kaushal Vikas Yojana*, official report.
- CAG official audit-report page for Report No. 20 of 2025.
- Official PMKVY 4.0/SIDH material used in P6 for the reform comparison.

## Process conclusion

P7 is complete. Verified numerical evidence has been separated from evidence requiring re-verification. The Results architecture is now fixed enough for the next process.

Next formal process: **P8 Evidence-Based Discussion, Governance Framework & Policy Implications**.
