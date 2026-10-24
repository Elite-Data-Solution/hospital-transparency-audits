# Elite Data Solution - Hospital Price Transparency Public Diagnostic Index

**Governing Federal Standard:** CMS Hospital Price Transparency Mandate (45 CFR Part 180)  
**Publication Cadence:** Weekly Nationwide Expansion (25 Newly Audited Healthcare Facilities Released Every Sunday)  
**Last Index Compilation:** `2026-10-24T10:42:34.274258+00:00`  
**Independent Workpaper Custody:** Elite Data Solution (`audit@elitedatasolution.net`)  
**Advisory Portal:** [https://elitedatasolution.net](https://elitedatasolution.net)

---

## Executive Overview & Aggregate Statistics

| Regulatory Inspection Metric | Aggregate Volume | Statutory Audit Context |
| :--- | :--- | :--- |
| **Total Facilities Audited** | **50** | Total hospital Machine-Readable File (MRF) endpoints ingested |
| **100% Compliant Facilities** | **0** | Standard charge files verifying 100% data completeness with zero detected defects |
| **Non-Compliant Facilities** | **50** | Files exhibiting structural syntax, schema, pricing, or CMS rule non-compliance |
| **Statutorily Obstructed Facilities** | **0** | Facilities deploying automated bot blockers / WAF walls in violation of 45 CFR § 180.50 |
| **Total Chargemaster Rows Scanned** | **3,164,483** | Total individual standard charge records algorithmically inspected |
| **Total Compliance Defects Cataloged** | **4,158,688** | Total statutory infractions isolated and documented across workpapers |

---

## Auditing Methodology & Scoring Architecture

### Statutory Compliance Standing (Binary Invariant)
Under federal administrative law (45 CFR Part 180), hospital price transparency compliance is strictly binary. The Centers for Medicare & Medicaid Services (CMS) does not grant partial credit. Even if a hospital maintains 99% data completeness across 100,000 chargemaster rows, omitting mandatory clinical billing codes (CPT/HCPCS/DRG/NDC), missing root metadata headers, or publishing in unauthorized proprietary formats (.xlsx, .zip) constitutes a formal statutory non-compliance defect subject to CMS Warning Notices and daily Civil Monetary Penalties (45 CFR § 180.90).

### Data Completeness Rate (0.0% – 100.0%)
The Data Completeness Rate (and associated letter grade) is an algorithmic diagnostic metric evaluating the proportion of fully populated, uncorrupted, and validated standard charge records. A facility achieving a high score (e.g., Grade A+ / 98.8%) demonstrates strong structural chargemaster density, but isolated non-compliant coordinates still legally expose the facility until fully remediated.

---

## ⚠️ Non-Compliant Facilities (Pricing, Schema & CMS Rule Defects)

The following facilities publish accessible MRFs, but independent diagnostic inspection detected structural syntax,
missing payer contract data, zero-dollar pricing placeholders, or schema non-compliance defects:

| Hospital Facility Name | State | Data Completeness Rate | Grade | Scanned Rows | Cataloged Defects | Public Diagnostic Audit Report |
| :--- | :--- | :---: | :---: | :---: | :---: | :--- |
| **Atmore Community Hospital** | Alabama | 0.0% | **F** | 0 | 1 | [Atmore Community Hospital Diagnostic Report](Alabama/Atmore_Community_Hospital/Atmore_Community_Hospital_Public_Audit_Report.pdf) |
| **Baptist Medical Center South** | Alabama | 59.0% | **F** | 18,430 | 35,309 | [Baptist Medical Center South Diagnostic Report](Alabama/Baptist_Medical_Center_South/Baptist_Medical_Center_South_Public_Audit_Report.pdf) |
| **Beacon Childrens Hospital** | Alabama | 0.0% | **F** | 0 | 1 | [Beacon Childrens Hospital Diagnostic Report](Alabama/Beacon_Childrens_Hospital/Beacon_Childrens_Hospital_Public_Audit_Report.pdf) |
| **Bibb Medical Center** | Alabama | 0.0% | **F** | 0 | 1 | [Bibb Medical Center Diagnostic Report](Alabama/Bibb_Medical_Center/Bibb_Medical_Center_Public_Audit_Report.pdf) |
| **Children's Hospital Of Alabama** | Alabama | 98.8% | **A+** | 5,653 | 48 | [Children's Hospital Of Alabama Diagnostic Report](Alabama/Childrens_Hospital_Of_Alabama/Childrens_Hospital_Of_Alabama_Public_Audit_Report.pdf) |
| **Community Hospital Inc** | Alabama | 52.7% | **F** | 4,514 | 3,076 | [Community Hospital Inc Diagnostic Report](Alabama/Community_Hospital_Inc/Community_Hospital_Inc_Public_Audit_Report.pdf) |
| **D W Mcmillan Memorial Hospital** | Alabama | 0.0% | **F** | 0 | 1 | [D W Mcmillan Memorial Hospital Diagnostic Report](Alabama/D_W_Mcmillan_Memorial_Hospital/D_W_Mcmillan_Memorial_Hospital_Public_Audit_Report.pdf) |
| **East Alabama Medical Center** | Alabama | 0.0% | **F** | 0 | 1 | [East Alabama Medical Center Diagnostic Report](Alabama/East_Alabama_Medical_Center/East_Alabama_Medical_Center_Public_Audit_Report.pdf) |
| **Jackson Medical Center** | Alabama | 68.9% | **D** | 3,841 | 1,349 | [Jackson Medical Center Diagnostic Report](Alabama/Jackson_Medical_Center/Jackson_Medical_Center_Public_Audit_Report.pdf) |
| **Wiregrass Medical Center** | Alabama | 99.9% | **A+** | 54,566 | 69 | [Wiregrass Medical Center Diagnostic Report](Alabama/Wiregrass_Medical_Center/Wiregrass_Medical_Center_Public_Audit_Report.pdf) |
| **Alaska Regional Hospital** | Alaska | 59.0% | **F** | 98,061 | 94,129 | [Alaska Regional Hospital Diagnostic Report](Alaska/Alaska_Regional_Hospital/Alaska_Regional_Hospital_Public_Audit_Report.pdf) |
| **Bartlett Regional Hospital** | Alaska | 97.8% | **A+** | 9,193 | 171 | [Bartlett Regional Hospital Diagnostic Report](Alaska/Bartlett_Regional_Hospital/Bartlett_Regional_Hospital_Public_Audit_Report.pdf) |
| **Fairbanks Memorial Hospital** | Alaska | 98.0% | **A+** | 135,179 | 2,539 | [Fairbanks Memorial Hospital Diagnostic Report](Alaska/Fairbanks_Memorial_Hospital/Fairbanks_Memorial_Hospital_Public_Audit_Report.pdf) |
| **Aurora Behavioral Health System** | Arizona | 53.9% | **F** | 30 | 29 | [Aurora Behavioral Health System Diagnostic Report](Arizona/Aurora_Behavioral_Health_System/Aurora_Behavioral_Health_System_Public_Audit_Report.pdf) |
| **Copper Queen Community Hospital** | Arizona | 92.5% | **A-** | 77,845 | 6,472 | [Copper Queen Community Hospital Diagnostic Report](Arizona/Copper_Queen_Community_Hospital/Copper_Queen_Community_Hospital_Public_Audit_Report.pdf) |
| **Honor Health Deer Valley Medical Center** | Arizona | 97.9% | **A+** | 312,795 | 5,898 | [Honor Health Deer Valley Medical Center Diagnostic Report](Arizona/Honor_Health_Deer_Valley_Medical_Center/Honor_Health_Deer_Valley_Medical_Center_Public_Audit_Report.pdf) |
| **Honorhealth Scottsdale Osborn Medical Center** | Arizona | 0.0% | **F** | 0 | 1 | [Honorhealth Scottsdale Osborn Medical Center Diagnostic Report](Arizona/Honorhealth_Scottsdale_Osborn_Medical_Center/Honorhealth_Scottsdale_Osborn_Medical_Center_Public_Audit_Report.pdf) |
| **Honorhealth Sonoran Crossing Medical Center** | Arizona | 59.0% | **F** | 290,636 | 195,209 | [Honorhealth Sonoran Crossing Medical Center Diagnostic Report](Arizona/Honorhealth_Sonoran_Crossing_Medical_Center/Honorhealth_Sonoran_Crossing_Medical_Center_Public_Audit_Report.pdf) |
| **Baptist Health - Fort Smith** | Arkansas | 0.0% | **F** | 0 | 1 | [Baptist Health - Fort Smith Diagnostic Report](Arkansas/Baptist_Health_-_Fort_Smith/Baptist_Health_-_Fort_Smith_Public_Audit_Report.pdf) |
| **Baptist Health - Van Buren** | Arkansas | 0.0% | **F** | 0 | 1 | [Baptist Health - Van Buren Diagnostic Report](Arkansas/Baptist_Health_-_Van_Buren/Baptist_Health_-_Van_Buren_Public_Audit_Report.pdf) |
| **Baptist Health Extended Care Hospital-lr Inc** | Arkansas | 0.0% | **F** | 0 | 1 | [Baptist Health Extended Care Hospital-lr Inc Diagnostic Report](Arkansas/Baptist_Health_Extended_Care_Hospital-lr_Inc/Baptist_Health_Extended_Care_Hospital-lr_Inc_Public_Audit_Report.pdf) |
| **Baptist Health Medical Center - Arkadelphia** | Arkansas | 0.0% | **F** | 0 | 1 | [Baptist Health Medical Center - Arkadelphia Diagnostic Report](Arkansas/Baptist_Health_Medical_Center_-_Arkadelphia/Baptist_Health_Medical_Center_-_Arkadelphia_Public_Audit_Report.pdf) |
| **Baptist Health Medical Center - Conway** | Arkansas | 0.0% | **F** | 0 | 1 | [Baptist Health Medical Center - Conway Diagnostic Report](Arkansas/Baptist_Health_Medical_Center_-_Conway/Baptist_Health_Medical_Center_-_Conway_Public_Audit_Report.pdf) |
| **Baptist Health Medical Center - Hot Springs County** | Arkansas | 0.0% | **F** | 0 | 1 | [Baptist Health Medical Center - Hot Springs County Diagnostic Report](Arkansas/Baptist_Health_Medical_Center_-_Hot_Springs_County/Baptist_Health_Medical_Center_-_Hot_Springs_County_Public_Audit_Report.pdf) |
| **Baptist Health Medical Center - Little Rock** | Arkansas | 0.0% | **F** | 0 | 1 | [Baptist Health Medical Center - Little Rock Diagnostic Report](Arkansas/Baptist_Health_Medical_Center_-_Little_Rock/Baptist_Health_Medical_Center_-_Little_Rock_Public_Audit_Report.pdf) |
| **Baptist Health Medical Center - Stuttgart** | Arkansas | 0.0% | **F** | 0 | 1 | [Baptist Health Medical Center - Stuttgart Diagnostic Report](Arkansas/Baptist_Health_Medical_Center_-_Stuttgart/Baptist_Health_Medical_Center_-_Stuttgart_Public_Audit_Report.pdf) |
| **Baptist Health Medical Center Heber Springs** | Arkansas | 0.0% | **F** | 0 | 1 | [Baptist Health Medical Center Heber Springs Diagnostic Report](Arkansas/Baptist_Health_Medical_Center_Heber_Springs/Baptist_Health_Medical_Center_Heber_Springs_Public_Audit_Report.pdf) |
| **Baptist Health Medical Center North Little Rock** | Arkansas | 0.0% | **F** | 0 | 1 | [Baptist Health Medical Center North Little Rock Diagnostic Report](Arkansas/Baptist_Health_Medical_Center_North_Little_Rock/Baptist_Health_Medical_Center_North_Little_Rock_Public_Audit_Report.pdf) |
| **Baptist Health Rehabilitation Institute** | Arkansas | 0.0% | **F** | 0 | 1 | [Baptist Health Rehabilitation Institute Diagnostic Report](Arkansas/Baptist_Health_Rehabilitation_Institute/Baptist_Health_Rehabilitation_Institute_Public_Audit_Report.pdf) |
| **Bradley County Medical Center** | Arkansas | 0.0% | **F** | 0 | 1 | [Bradley County Medical Center Diagnostic Report](Arkansas/Bradley_County_Medical_Center/Bradley_County_Medical_Center_Public_Audit_Report.pdf) |
| **Forrest City Medical Center** | Arkansas | 44.1% | **F** | 3,339 | 3,555 | [Forrest City Medical Center Diagnostic Report](Arkansas/Forrest_City_Medical_Center/Forrest_City_Medical_Center_Public_Audit_Report.pdf) |
| **Fulton County Hospital** | Arkansas | 0.0% | **F** | 0 | 1 | [Fulton County Hospital Diagnostic Report](Arkansas/Fulton_County_Hospital/Fulton_County_Hospital_Public_Audit_Report.pdf) |
| **Howard County General Hospital** | Maryland | 84.7% | **B** | 13,376 | 2,119 | [Howard County General Hospital Diagnostic Report](Maryland/Howard_County_General_Hospital/Howard_County_General_Hospital_Public_Audit_Report.pdf) |
| **Brooke Glen Behavioral Hospital** | New York | 99.0% | **A+** | 561 | 5 | [Brooke Glen Behavioral Hospital Diagnostic Report](New York/Brooke_Glen_Behavioral_Hospital/Brooke_Glen_Behavioral_Hospital_Public_Audit_Report.pdf) |
| **Albert Einstein Medical Center** | Pennsylvania | 0.0% | **F** | 0 | 1 | [Albert Einstein Medical Center Diagnostic Report](Pennsylvania/Albert_Einstein_Medical_Center/Albert_Einstein_Medical_Center_Public_Audit_Report.pdf) |
| **Armstrong Center for Medicine and Health** | Pennsylvania | 84.6% | **B** | 6,693 | 943 | [Armstrong Center for Medicine and Health Diagnostic Report](Pennsylvania/Armstrong_Center_for_Medicine_and_Health/Armstrong_Center_for_Medicine_and_Health_Public_Audit_Report.pdf) |
| **Belmont Behavioral Health System** | Pennsylvania | 59.0% | **F** | 58 | 33 | [Belmont Behavioral Health System Diagnostic Report](Pennsylvania/Belmont_Behavioral_Health_System/Belmont_Behavioral_Health_System_Public_Audit_Report.pdf) |
| **Berwick Hospital Center** | Pennsylvania | 0.0% | **F** | 0 | 1 | [Berwick Hospital Center Diagnostic Report](Pennsylvania/Berwick_Hospital_Center/Berwick_Hospital_Center_Public_Audit_Report.pdf) |
| **Canonsburg Hospital** | Pennsylvania | 0.0% | **F** | 0 | 1 | [Canonsburg Hospital Diagnostic Report](Pennsylvania/Canonsburg_Hospital/Canonsburg_Hospital_Public_Audit_Report.pdf) |
| **Chan Soon-Shiong Medical Center at Windber** | Pennsylvania | 57.9% | **F** | 373,739 | 833,030 | [Chan Soon-Shiong Medical Center at Windber Diagnostic Report](Pennsylvania/Chan_Soon-Shiong_Medical_Center_at_Windber/Chan_Soon-Shiong_Medical_Center_at_Windber_Public_Audit_Report.pdf) |
| **Children's Home of Pittsburgh** | Pennsylvania | 0.0% | **F** | 0 | 1 | [Children's Home of Pittsburgh Diagnostic Report](Pennsylvania/Childrens_Home_of_Pittsburgh/Childrens_Home_of_Pittsburgh_Public_Audit_Report.pdf) |
| **Children's Hospital of Philadelphia** | Pennsylvania | 88.7% | **B+** | 300,782 | 29,386 | [Children's Hospital of Philadelphia Diagnostic Report](Pennsylvania/Childrens_Hospital_of_Philadelphia/Childrens_Hospital_of_Philadelphia_Public_Audit_Report.pdf) |
| **Clarion Psychiatric Center** | Pennsylvania | 40.8% | **F** | 11 | 19 | [Clarion Psychiatric Center Diagnostic Report](Pennsylvania/Clarion_Psychiatric_Center/Clarion_Psychiatric_Center_Public_Audit_Report.pdf) |
| **Cooper University Hospital** | Pennsylvania | 56.5% | **F** | 1,455,181 | 2,945,271 | [Cooper University Hospital Diagnostic Report](Pennsylvania/Cooper_University_Hospital/Cooper_University_Hospital_Public_Audit_Report.pdf) |
| **Crozer-Chester Medical Center** | Pennsylvania | 0.0% | **F** | 0 | 1 | [Crozer-Chester Medical Center Diagnostic Report](Pennsylvania/Crozer-Chester_Medical_Center/Crozer-Chester_Medical_Center_Public_Audit_Report.pdf) |
| **Delaware County Memorial Hospital** | Pennsylvania | 0.0% | **F** | 0 | 1 | [Delaware County Memorial Hospital Diagnostic Report](Pennsylvania/Delaware_County_Memorial_Hospital/Delaware_County_Memorial_Hospital_Public_Audit_Report.pdf) |
| **Einstein Medical Center Montgomery** | Pennsylvania | 0.0% | **F** | 0 | 1 | [Einstein Medical Center Montgomery Diagnostic Report](Pennsylvania/Einstein_Medical_Center_Montgomery/Einstein_Medical_Center_Montgomery_Public_Audit_Report.pdf) |
| **Forbes Hospital** | Pennsylvania | 0.0% | **F** | 0 | 1 | [Forbes Hospital Diagnostic Report](Pennsylvania/Forbes_Hospital/Forbes_Hospital_Public_Audit_Report.pdf) |
| **Grand View Hospital** | Pennsylvania | 0.0% | **F** | 0 | 1 | [Grand View Hospital Diagnostic Report](Pennsylvania/Grand_View_Hospital/Grand_View_Hospital_Public_Audit_Report.pdf) |
| **Holy Redeemer Hospital** | Pennsylvania | 0.0% | **F** | 0 | 1 | [Holy Redeemer Hospital Diagnostic Report](Pennsylvania/Holy_Redeemer_Hospital/Holy_Redeemer_Hospital_Public_Audit_Report.pdf) |

---

## ✅ 100% Compliant Facilities (Zero Detected Defects)

The following facilities maintain published machine-readable datasets that verify 100% structural conformity
and complete data integrity with zero detected compliance anomalies:

| Hospital Facility Name | State | Data Completeness Rate | Grade | Scanned Records | Compliance Verification Report |
| :--- | :--- | :---: | :---: | :---: | :--- |
| *No 100% compliant facilities cataloged in current batch.* | - | - | - | - | - |

---

## Regulatory Defensibility & Workpaper Requisition

Elite Data Solution produces mathematically defensible diagnostic workpapers for hospital financial executives,
revenue cycle leadership, and healthcare advisory practice leaders. Facilities seeking line-by-line
remediation error ledgers, root-cause schema diagnostics, or barrier elimination guidance can request complete workpaper packages:

- **Official Audit Inquiries:** `audit@elitedatasolution.net`
- **Advisory Practice Portal:** [https://elitedatasolution.net](https://elitedatasolution.net)
- **Statutory Standards Reference:** 45 CFR § 180.50 (Accessibility), 45 CFR § 180.70 (CAP), 45 CFR § 180.90 (CMP Penalties)
