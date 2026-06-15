# IKDDS Case Report Form Specification

Irish Kidney Disease Data System

> **Auto-generated from the `ikdds` package metadata** (`redcap_dictionary` + `field_mapping`) on 2026-06-15. Do not edit by hand -- change the package data and regenerate.


## Forms


### Registry enrolment

| Field | Label | Type | Validation |
| --- | --- | --- | --- |
| record_id | Registry record ID | text |  |

### Demographics

| Field | Label | Type | Validation |
| --- | --- | --- | --- |
| idn01 | Patient Surname | text |  |
| idn02 | Patient Forename | text |  |
| idn03 | Date of Birth | text | date_ymd |
| idn04 | Local Hospital Number | text |  |
| idn05 | Flag for Opted out of sending identifiable data to UKRR | text |  |
| idn06 | Year of birth | text | integer |
| idn07 | Unique identifier not attributable to patient. | text |  |
| idn08 | Patient birth name = name on birth certificate - also 'Maiden name' | text |  |
| idn09 | Alias - other surname by which patient also known | text |  |
| pat00 | Sex, Gender on birth certificate | text |  |
| pat01 | Hospital centre code | dropdown |  |
| pat11 | CHI number - patients registered in Scotland | text |  |
| pat13 | NHS number format - without spaces | text |  |
| pat18 | H & C Number - patients registered in Northern Ireland | text |  |
| pat20 | Address line 1 | text |  |
| pat21 | Address line 2 | text |  |
| pat22 | Address line 3 | text |  |
| pat19 | Address line 4 | text |  |
| pat23 | Postcode | text |  |
| pat25 | Ethnicity | text |  |
| pat38 | GP Practice code (current) | text |  |
| pat40 | Date of death | text | date_ymd |
| pat42 | Main Cause of death 1 EDTA | dropdown |  |
| pat43 | Cause of death 2 EDTA | dropdown |  |
| pat44 | Cause of death - free text if no appropriate code available | text |  |

### Diagnoses

| Field | Label | Type | Validation |
| --- | --- | --- | --- |
| dxs01 | EDTA primary renal disease code | text | integer |
| dxs02 | SNOMED primary renal disease code | text |  |
| dxs03 | Was primary renal disease diagnosis confirmed by kidney biopsy? | radio |  |
| dxs04 | Secondary renal disease code | text |  |
| dxs05 | Primary disease free text if no suitable code available | text |  |
| dxs06 | Date of diagnosis of primary renal disease | text | date_ymd |
| dxs07 | Diabetes | text |  |
| dxs08 | Date diabetes diagnosed | text | date_ymd |
| dxs09 | Malignancy Yes / No | radio |  |
| dxs10 | Malignancy site, first primary site only | dropdown |  |
| dxs11 | Malignancy  - date first diagnosed | text | date_ymd |

### Renal treatment

| Field | Label | Type | Validation |
| --- | --- | --- | --- |
| txt00 | Date start treatment | text | date_ymd |
| txt01 | Date end treatment | text | date_ymd |
| txt02 | Treatment modality code | text |  |
| txt20 | Treatment site/centre code | dropdown |  |
| txt21 | Treatment supervision | dropdown |  |
| txt40 | Transfer in from - site patient originated from | dropdown |  |
| txt41 | Transfer out to - destination site of patient transferring out | dropdown |  |

### Hd prescription

| Field | Label | Type | Validation |
| --- | --- | --- | --- |
| hdp00 | Date of dialysis prescription | text | date_ymd |
| hdp01 | Times per week | text | integer |
| hdp02 | Time dialysed in minutes | text | integer |
| hdp04 | Vascular access in use | dropdown |  |

### Hd sessions

| Field | Label | Type | Validation |
| --- | --- | --- | --- |
| qhd00 | Date of HD/PEX session | text | date_ymd |
| qhd40 | Clock time session started | text |  |
| qhd41 | Haemodialysis or plasma exchange | text |  |
| qhd20 | Vascular access used for this treatment | dropdown |  |
| qhd31 | Duration of treatment in minutes | text | integer |

### Medications

| Field | Label | Type | Validation |
| --- | --- | --- | --- |
| med01 | Drug start date | text | date_ymd |
| med02 | Drug stop date | text | date_ymd |
| med03 | Generic drug name | text |  |
| med04 | Branded drug name | text |  |
| med05 | Drug unit of measurement | dropdown |  |
| med06 | Drug dose | text | integer |
| med07 | Drug route | dropdown |  |
| med08 | Drug frequency of administration | text |  |
| med09 | Drug comments | text |  |

### Lab results

| Field | Label | Type | Validation |
| --- | --- | --- | --- |
| qbla6 | Serum sodium | text | integer |
| qbla7 | Date of sodium | text | date_ymd |
| qblkn | Serum sodium - post dialysis | text | integer |
| qblkp | Date of post dialysis sodium | text | date_ymd |
| qbla9 | Serum potassium | text | number |
| qblaa | Date of potassium | text | date_ymd |
| qblkl | Serum potassium - post dialysis | text | number |
| qblkm | Date of post dialysis potassium | text | date_ymd |
| qbla3 | Serum urea | text | integer |
| qblaj | Date of serum urea | text | date_ymd |
| qblkg | Serum urea - post dialysis | text | integer |
| qblkh | Date of post dialysis urea | text | date_ymd |
| qbla1 | Serum creatinine | text | integer |
| qbla2 | Date of serum creatinine | text | date_ymd |
| qblke | Serum creatinine - post dialysis | text | integer |
| qblkf | Date of post dialysis creatinine | text | date_ymd |
| qbla4 | Serum bicarbonate | text | integer |
| qbla5 | Date of bicarbonate | text | date_ymd |
| qblkq | Serum bicarbonate  - post dialysis | text | integer |
| qblkr | Date of post dialysis bicarbonate | text | date_ymd |
| qblap | Glomerular filtration rate (GFR) predicted by creatinine based formula (CKD-EPI) WITHOUT ethnicity | text | integer |
| qblaq | Date of CKD-EPI eGFR | text | date_ymd |
| qblar | Glomerular filtration rate (GFR) predicted by creatinine based formula (MDRD) WITHOUT ethnicity | text | integer |
| qblas | Date of MDRD eGFR | text | date_ymd |
| qblac | Serum uric acid (urate) | text | integer |
| qblad | Date of serum uric acid (urate) | text | date_ymd |
| qblb1 | Serum phosphate | text | integer |
| qblb2 | Date of serum phosphate | text | date_ymd |
| qblb3 | Serum calcium | text | integer |
| qblbb | Date of serum calcium | text | date_ymd |
| qblb4 | Corrected/adjusted serum calcium | text | integer |
| qblbc | Date of corrected/adjusted serum calcium | text | date_ymd |
| qblb5 | Serum alkaline phosphatase | text | integer |
| qblb6 | Date of Serum alkaline phosphatase | text | date_ymd |
| qblpc | ALT - alanine transaminase | text | integer |
| qbljb | Date of ALT | text | date_ymd |
| qblb7 | Serum albumin | text | integer |
| qblb8 | Date of albumin | text | date_ymd |
| qblb9 | Serum parathyroid hormone (PTH) | text | integer |
| qblba | Date of PTH | text | date_ymd |
| qbld1 | Total serum cholesterol | text | integer |
| qbld2 | Date of serum cholesterol | text | date_ymd |
| qbld3 | Serum HDL cholesterol | text | integer |
| qbldb | Date of serum HDL cholesterol | text | date_ymd |
| qbld4 | Serum LDL cholesterol | text | integer |
| qbldc | Date of serum LDL cholesterol | text | date_ymd |
| qbld5 | Serum triglycerides | text | integer |
| qbldf | Date of serum triglycerides | text | date_ymd |
| qbld6 | CRP | text | integer |
| qbld7 | Date of CRP | text | date_ymd |
| qbld8 | HbA1c (%) | text | integer |
| qblda | HbA1c (mmol/mol) | text | integer |
| qbld9 | Date of HbA1c | text | date_ymd |
| qble1 | Haemoglobin (g/dL) | text | integer |
| qbleb | Haemoglobin (g/L) | text | integer |
| qble2 | Date of haemoglobin | text | date_ymd |
| qble5 | White blood count (WBC) | text | integer |
| qblea | Date of WBC | text | date_ymd |
| qble4 | Platelets | text | integer |
| qble9 | Date of platelets | text | date_ymd |
| qbljj | Reticulocyte haemoglobin (CHr) | text | integer |
| qbljk | Date of reticulocyte haemoglobin | text | date_ymd |
| qblf1 | Serum ferritin | text | integer |
| qblf2 | Date of serum ferritin | text | date_ymd |
| qblf3 | Transferrin saturation | text | integer |
| qblf4 | Date of transferrin saturation | text | date_ymd |
| qblf5 | Percentage of hypochromic red cells | text | integer |
| qblf6 | Date of hypochromic red cells | text | date_ymd |
| qblf7 | Serum B12 | text | integer |
| qblf8 | Date of serum B12 | text | date_ymd |
| qblf9 | Serum folate | text | integer |
| qblfa | Date of serum folate | text | date_ymd |
| qblfb | Red cell folate | text | number |
| qblfc | Date of red cell folate | text | date_ymd |
| qblgu | PSA - prostate specific antigen | text | integer |
| qblgv | Date of PSA test | text | date_ymd |
| qblff | Tacrolimus blood concentration level | text | integer |
| qblfg | Date of tacrolimus blood concentration level | text | date_ymd |
| qblfh | Sirolimus blood concentration level | text | integer |
| qblfj | Date of sirolimus blood concentration level | text | date_ymd |
| qblfk | Ciclosporin blood concentration level | text | integer |
| qblfl | Date of ciclosporin blood concentration level | text | date_ymd |
| qblfm | Mycophenolate blood concentration level | text | integer |
| qblfn | Date of mycophenolate blood concentration level | text | date_ymd |
| qblg9 | Urea reduction ratio | text | integer |
| qblga | Date of urea reduction ratio | text | date_ymd |
| qblgg | Kt/V measured by a haemodialysis machine | text | integer |
| qblgh | Date of Kt/V | text | date_ymd |
| qblha | HBV surface antibody status | text |  |
| qblhb | Date of test HBV surface antibody | text | date_ymd |
| qblhc | HBV surface antigen status | text |  |
| qblhd | Date of test HBV surface antigen | text | date_ymd |
| qblhe | HCV antibody status | text |  |
| qblhf | Date of test HCV surface antibody | text | date_ymd |
| qblh1 | BK Virus status | text |  |
| qblh2 | Date of BK Virus status | text | date_ymd |
| qblhm | HIV screening test | text |  |
| qblhl | Date HIV screening test | text | date_ymd |
| qblgn | COVID-19 antigen PCR | text |  |
| qblgp | Date of COVID-19 antigen PCR | text | date_ymd |
| qblgs | COVID-19 IgG antibody status | text |  |
| qblgt | Date of COVID-19 IgG antibody status | text | date_ymd |
| qblc1 | Urine protein:creatinine ratio | text | integer |
| qblc2 | Date of urine protein:creatinine ratio | text | date_ymd |
| qblc3 | Urine albumin:creatinine ratio | text | integer |
| qblc4 | Date of urine albumin:creatinine ratio | text | date_ymd |
| qblhx | Urine creatinine concentration | text | integer |
| qblhy | Date of urine creatinine concentration | text | date_ymd |
| qbljs | Urine protein concentration | text | integer |
| qbljt | Date of urinary protein concentration | text | date_ymd |
| qbljl | Proteinuria dipstick test | text |  |
| qbljm | Date of Proteinuria dipstick test | text | date_ymd |
| qblhv | Urine volume in 24 hours | text | integer |
| qblhu | Date of urine volume in 24 hours | text | date_ymd |
| qbljn | PD fluid WCC count | text |  |
| qbljp | Date of PD fluid WCC count | text | date_ymd |
| qbljq | PD fluid culture organism grown  text | text |  |
| qbljr | Date of PD fluid culture test | text | date_ymd |
| qbljx | Blood culture organism grown text ** | text |  |
| qbljy | Date of blood culture test | text | date_ymd |

### Observations

| Field | Label | Type | Validation |
| --- | --- | --- | --- |
| qblg1 | Weight | text | integer |
| qblg2 | Date of weight | text | date_ymd |
| qblgb | Height | text | integer |
| qblgc | Date of Height | text | date_ymd |
| qblg3 | Systolic blood pressure | text | integer |
| qblg4 | Diastolic blood pressure | text | integer |
| qblg5 | Date of blood Pressure | text | date_ymd |
| qblg6 | Post dialysis systolic blood pressure | text | integer |
| qblg7 | Post dialysis diastolic blood pressure | text | integer |
| qblg8 | Date of post dialysis blood pressure | text | date_ymd |
| qblks | Body weight measured post dialysis | text | integer |
| qblkt | Date of body weight measured post dialysis | text | date_ymd |
| qblku | Symptoms of peritonitis | text |  |
| qblkv | Date of peritonitis symptoms | text | date_ymd |

### Care planning

| Field | Label | Type | Validation |
| --- | --- | --- | --- |
| cap01 | Date of assessment | text | date_ymd |
| cap02 | Type of assessment | text |  |
| cap03 | Outcome of assessment | text |  |

### Transplant

| Field | Label | Type | Validation |
| --- | --- | --- | --- |
| tra61 | Date of kidney transplant | text | date_ymd |
| tra64 | Date of kidney transplant failure | text | date_ymd |
| tra77 | UKTR donor type of transplant | text |  |
| tra70 | UKTR recipient ID | text | integer |
| tra72 | Date registered for transplantation | text | date_ymd |
| tra73 | Transplant centre | text | integer |
| tra91 | Cold Ischaemic Time - in minutes | text | integer |
| tra83 | HLA Mismatch A | text | integer |
| tra84 | HLA Mismatch B | text | integer |
| tra85 | HLA Mismatch DR | text | integer |
