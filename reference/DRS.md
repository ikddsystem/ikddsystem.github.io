# IKDDS Data Requirements Specification

Irish Kidney Disease Data System

> **Auto-generated from the `ikdds` package metadata** (`redcap_dictionary` + `field_mapping`) on 2026-06-15. Do not edit by hand -- change the package data and regenerate.


## 1. Purpose

Specifies the data requirements for the IKDDS: field definitions, source
mappings, validation rules, and coded value lists.

## 2. Scope

The IKDDS captures data across **11** REDCap forms containing **209** fields.

## 3. Complete field listing

| Field | Form | Type | Label | Validation |
| --- | --- | --- | --- | --- |
| record_id | registry_enrolment | text | Registry record ID |  |
| idn01 | demographics | text | Patient Surname |  |
| idn02 | demographics | text | Patient Forename |  |
| idn03 | demographics | text | Date of Birth | date_ymd |
| idn04 | demographics | text | Local Hospital Number |  |
| idn05 | demographics | text | Flag for Opted out of sending identifiable data to UKRR |  |
| idn06 | demographics | text | Year of birth | integer |
| idn07 | demographics | text | Unique identifier not attributable to patient. |  |
| idn08 | demographics | text | Patient birth name = name on birth certificate - also 'Maiden name' |  |
| idn09 | demographics | text | Alias - other surname by which patient also known |  |
| pat00 | demographics | text | Sex, Gender on birth certificate |  |
| pat01 | demographics | dropdown | Hospital centre code |  |
| pat11 | demographics | text | CHI number - patients registered in Scotland |  |
| pat13 | demographics | text | NHS number format - without spaces |  |
| pat18 | demographics | text | H & C Number - patients registered in Northern Ireland |  |
| pat20 | demographics | text | Address line 1 |  |
| pat21 | demographics | text | Address line 2 |  |
| pat22 | demographics | text | Address line 3 |  |
| pat19 | demographics | text | Address line 4 |  |
| pat23 | demographics | text | Postcode |  |
| pat25 | demographics | text | Ethnicity |  |
| pat38 | demographics | text | GP Practice code (current) |  |
| pat40 | demographics | text | Date of death | date_ymd |
| pat42 | demographics | dropdown | Main Cause of death 1 EDTA |  |
| pat43 | demographics | dropdown | Cause of death 2 EDTA |  |
| pat44 | demographics | text | Cause of death - free text if no appropriate code available |  |
| dxs01 | diagnoses | text | EDTA primary renal disease code | integer |
| dxs02 | diagnoses | text | SNOMED primary renal disease code |  |
| dxs03 | diagnoses | radio | Was primary renal disease diagnosis confirmed by kidney biopsy? |  |
| dxs04 | diagnoses | text | Secondary renal disease code |  |
| dxs05 | diagnoses | text | Primary disease free text if no suitable code available |  |
| dxs06 | diagnoses | text | Date of diagnosis of primary renal disease | date_ymd |
| dxs07 | diagnoses | text | Diabetes |  |
| dxs08 | diagnoses | text | Date diabetes diagnosed | date_ymd |
| dxs09 | diagnoses | radio | Malignancy Yes / No |  |
| dxs10 | diagnoses | dropdown | Malignancy site, first primary site only |  |
| dxs11 | diagnoses | text | Malignancy  - date first diagnosed | date_ymd |
| txt00 | renal_treatment | text | Date start treatment | date_ymd |
| txt01 | renal_treatment | text | Date end treatment | date_ymd |
| txt02 | renal_treatment | text | Treatment modality code |  |
| txt20 | renal_treatment | dropdown | Treatment site/centre code |  |
| txt21 | renal_treatment | dropdown | Treatment supervision |  |
| txt40 | renal_treatment | dropdown | Transfer in from - site patient originated from |  |
| txt41 | renal_treatment | dropdown | Transfer out to - destination site of patient transferring out |  |
| hdp00 | hd_prescription | text | Date of dialysis prescription | date_ymd |
| hdp01 | hd_prescription | text | Times per week | integer |
| hdp02 | hd_prescription | text | Time dialysed in minutes | integer |
| hdp04 | hd_prescription | dropdown | Vascular access in use |  |
| qhd00 | hd_sessions | text | Date of HD/PEX session | date_ymd |
| qhd40 | hd_sessions | text | Clock time session started |  |
| qhd41 | hd_sessions | text | Haemodialysis or plasma exchange |  |
| qhd20 | hd_sessions | dropdown | Vascular access used for this treatment |  |
| qhd31 | hd_sessions | text | Duration of treatment in minutes | integer |
| med01 | medications | text | Drug start date | date_ymd |
| med02 | medications | text | Drug stop date | date_ymd |
| med03 | medications | text | Generic drug name |  |
| med04 | medications | text | Branded drug name |  |
| med05 | medications | dropdown | Drug unit of measurement |  |
| med06 | medications | text | Drug dose | integer |
| med07 | medications | dropdown | Drug route |  |
| med08 | medications | text | Drug frequency of administration |  |
| med09 | medications | text | Drug comments |  |
| qbla6 | lab_results | text | Serum sodium | integer |
| qbla7 | lab_results | text | Date of sodium | date_ymd |
| qblkn | lab_results | text | Serum sodium - post dialysis | integer |
| qblkp | lab_results | text | Date of post dialysis sodium | date_ymd |
| qbla9 | lab_results | text | Serum potassium | number |
| qblaa | lab_results | text | Date of potassium | date_ymd |
| qblkl | lab_results | text | Serum potassium - post dialysis | number |
| qblkm | lab_results | text | Date of post dialysis potassium | date_ymd |
| qbla3 | lab_results | text | Serum urea | integer |
| qblaj | lab_results | text | Date of serum urea | date_ymd |
| qblkg | lab_results | text | Serum urea - post dialysis | integer |
| qblkh | lab_results | text | Date of post dialysis urea | date_ymd |
| qbla1 | lab_results | text | Serum creatinine | integer |
| qbla2 | lab_results | text | Date of serum creatinine | date_ymd |
| qblke | lab_results | text | Serum creatinine - post dialysis | integer |
| qblkf | lab_results | text | Date of post dialysis creatinine | date_ymd |
| qbla4 | lab_results | text | Serum bicarbonate | integer |
| qbla5 | lab_results | text | Date of bicarbonate | date_ymd |
| qblkq | lab_results | text | Serum bicarbonate  - post dialysis | integer |
| qblkr | lab_results | text | Date of post dialysis bicarbonate | date_ymd |
| qblap | lab_results | text | Glomerular filtration rate (GFR) predicted by creatinine based formula (CKD-EPI) WITHOUT ethnicity | integer |
| qblaq | lab_results | text | Date of CKD-EPI eGFR | date_ymd |
| qblar | lab_results | text | Glomerular filtration rate (GFR) predicted by creatinine based formula (MDRD) WITHOUT ethnicity | integer |
| qblas | lab_results | text | Date of MDRD eGFR | date_ymd |
| qblac | lab_results | text | Serum uric acid (urate) | integer |
| qblad | lab_results | text | Date of serum uric acid (urate) | date_ymd |
| qblb1 | lab_results | text | Serum phosphate | integer |
| qblb2 | lab_results | text | Date of serum phosphate | date_ymd |
| qblb3 | lab_results | text | Serum calcium | integer |
| qblbb | lab_results | text | Date of serum calcium | date_ymd |
| qblb4 | lab_results | text | Corrected/adjusted serum calcium | integer |
| qblbc | lab_results | text | Date of corrected/adjusted serum calcium | date_ymd |
| qblb5 | lab_results | text | Serum alkaline phosphatase | integer |
| qblb6 | lab_results | text | Date of Serum alkaline phosphatase | date_ymd |
| qblpc | lab_results | text | ALT - alanine transaminase | integer |
| qbljb | lab_results | text | Date of ALT | date_ymd |
| qblb7 | lab_results | text | Serum albumin | integer |
| qblb8 | lab_results | text | Date of albumin | date_ymd |
| qblb9 | lab_results | text | Serum parathyroid hormone (PTH) | integer |
| qblba | lab_results | text | Date of PTH | date_ymd |
| qbld1 | lab_results | text | Total serum cholesterol | integer |
| qbld2 | lab_results | text | Date of serum cholesterol | date_ymd |
| qbld3 | lab_results | text | Serum HDL cholesterol | integer |
| qbldb | lab_results | text | Date of serum HDL cholesterol | date_ymd |
| qbld4 | lab_results | text | Serum LDL cholesterol | integer |
| qbldc | lab_results | text | Date of serum LDL cholesterol | date_ymd |
| qbld5 | lab_results | text | Serum triglycerides | integer |
| qbldf | lab_results | text | Date of serum triglycerides | date_ymd |
| qbld6 | lab_results | text | CRP | integer |
| qbld7 | lab_results | text | Date of CRP | date_ymd |
| qbld8 | lab_results | text | HbA1c (%) | integer |
| qblda | lab_results | text | HbA1c (mmol/mol) | integer |
| qbld9 | lab_results | text | Date of HbA1c | date_ymd |
| qble1 | lab_results | text | Haemoglobin (g/dL) | integer |
| qbleb | lab_results | text | Haemoglobin (g/L) | integer |
| qble2 | lab_results | text | Date of haemoglobin | date_ymd |
| qble5 | lab_results | text | White blood count (WBC) | integer |
| qblea | lab_results | text | Date of WBC | date_ymd |
| qble4 | lab_results | text | Platelets | integer |
| qble9 | lab_results | text | Date of platelets | date_ymd |
| qbljj | lab_results | text | Reticulocyte haemoglobin (CHr) | integer |
| qbljk | lab_results | text | Date of reticulocyte haemoglobin | date_ymd |
| qblf1 | lab_results | text | Serum ferritin | integer |
| qblf2 | lab_results | text | Date of serum ferritin | date_ymd |
| qblf3 | lab_results | text | Transferrin saturation | integer |
| qblf4 | lab_results | text | Date of transferrin saturation | date_ymd |
| qblf5 | lab_results | text | Percentage of hypochromic red cells | integer |
| qblf6 | lab_results | text | Date of hypochromic red cells | date_ymd |
| qblf7 | lab_results | text | Serum B12 | integer |
| qblf8 | lab_results | text | Date of serum B12 | date_ymd |
| qblf9 | lab_results | text | Serum folate | integer |
| qblfa | lab_results | text | Date of serum folate | date_ymd |
| qblfb | lab_results | text | Red cell folate | number |
| qblfc | lab_results | text | Date of red cell folate | date_ymd |
| qblgu | lab_results | text | PSA - prostate specific antigen | integer |
| qblgv | lab_results | text | Date of PSA test | date_ymd |
| qblff | lab_results | text | Tacrolimus blood concentration level | integer |
| qblfg | lab_results | text | Date of tacrolimus blood concentration level | date_ymd |
| qblfh | lab_results | text | Sirolimus blood concentration level | integer |
| qblfj | lab_results | text | Date of sirolimus blood concentration level | date_ymd |
| qblfk | lab_results | text | Ciclosporin blood concentration level | integer |
| qblfl | lab_results | text | Date of ciclosporin blood concentration level | date_ymd |
| qblfm | lab_results | text | Mycophenolate blood concentration level | integer |
| qblfn | lab_results | text | Date of mycophenolate blood concentration level | date_ymd |
| qblg9 | lab_results | text | Urea reduction ratio | integer |
| qblga | lab_results | text | Date of urea reduction ratio | date_ymd |
| qblgg | lab_results | text | Kt/V measured by a haemodialysis machine | integer |
| qblgh | lab_results | text | Date of Kt/V | date_ymd |
| qblha | lab_results | text | HBV surface antibody status |  |
| qblhb | lab_results | text | Date of test HBV surface antibody | date_ymd |
| qblhc | lab_results | text | HBV surface antigen status |  |
| qblhd | lab_results | text | Date of test HBV surface antigen | date_ymd |
| qblhe | lab_results | text | HCV antibody status |  |
| qblhf | lab_results | text | Date of test HCV surface antibody | date_ymd |
| qblh1 | lab_results | text | BK Virus status |  |
| qblh2 | lab_results | text | Date of BK Virus status | date_ymd |
| qblhm | lab_results | text | HIV screening test |  |
| qblhl | lab_results | text | Date HIV screening test | date_ymd |
| qblgn | lab_results | text | COVID-19 antigen PCR |  |
| qblgp | lab_results | text | Date of COVID-19 antigen PCR | date_ymd |
| qblgs | lab_results | text | COVID-19 IgG antibody status |  |
| qblgt | lab_results | text | Date of COVID-19 IgG antibody status | date_ymd |
| qblc1 | lab_results | text | Urine protein:creatinine ratio | integer |
| qblc2 | lab_results | text | Date of urine protein:creatinine ratio | date_ymd |
| qblc3 | lab_results | text | Urine albumin:creatinine ratio | integer |
| qblc4 | lab_results | text | Date of urine albumin:creatinine ratio | date_ymd |
| qblhx | lab_results | text | Urine creatinine concentration | integer |
| qblhy | lab_results | text | Date of urine creatinine concentration | date_ymd |
| qbljs | lab_results | text | Urine protein concentration | integer |
| qbljt | lab_results | text | Date of urinary protein concentration | date_ymd |
| qbljl | lab_results | text | Proteinuria dipstick test |  |
| qbljm | lab_results | text | Date of Proteinuria dipstick test | date_ymd |
| qblhv | lab_results | text | Urine volume in 24 hours | integer |
| qblhu | lab_results | text | Date of urine volume in 24 hours | date_ymd |
| qbljn | lab_results | text | PD fluid WCC count |  |
| qbljp | lab_results | text | Date of PD fluid WCC count | date_ymd |
| qbljq | lab_results | text | PD fluid culture organism grown  text |  |
| qbljr | lab_results | text | Date of PD fluid culture test | date_ymd |
| qbljx | lab_results | text | Blood culture organism grown text ** |  |
| qbljy | lab_results | text | Date of blood culture test | date_ymd |
| qblg1 | observations | text | Weight | integer |
| qblg2 | observations | text | Date of weight | date_ymd |
| qblgb | observations | text | Height | integer |
| qblgc | observations | text | Date of Height | date_ymd |
| qblg3 | observations | text | Systolic blood pressure | integer |
| qblg4 | observations | text | Diastolic blood pressure | integer |
| qblg5 | observations | text | Date of blood Pressure | date_ymd |
| qblg6 | observations | text | Post dialysis systolic blood pressure | integer |
| qblg7 | observations | text | Post dialysis diastolic blood pressure | integer |
| qblg8 | observations | text | Date of post dialysis blood pressure | date_ymd |
| qblks | observations | text | Body weight measured post dialysis | integer |
| qblkt | observations | text | Date of body weight measured post dialysis | date_ymd |
| qblku | observations | text | Symptoms of peritonitis |  |
| qblkv | observations | text | Date of peritonitis symptoms | date_ymd |
| cap01 | care_planning | text | Date of assessment | date_ymd |
| cap02 | care_planning | text | Type of assessment |  |
| cap03 | care_planning | text | Outcome of assessment |  |
| tra61 | transplant | text | Date of kidney transplant | date_ymd |
| tra64 | transplant | text | Date of kidney transplant failure | date_ymd |
| tra77 | transplant | text | UKTR donor type of transplant |  |
| tra70 | transplant | text | UKTR recipient ID | integer |
| tra72 | transplant | text | Date registered for transplantation | date_ymd |
| tra73 | transplant | text | Transplant centre | integer |
| tra91 | transplant | text | Cold Ischaemic Time - in minutes | integer |
| tra83 | transplant | text | HLA Mismatch A | integer |
| tra84 | transplant | text | HLA Mismatch B | integer |
| tra85 | transplant | text | HLA Mismatch DR | integer |

## 4. Source mappings (eMed to REDCap)

| REDCap field | Form | eMed table | eMed column | Transform |
| --- | --- | --- | --- | --- |
| record_id | registry_enrolment | Report.PatientDemography | PatientID | as.character |
| idn01 | demographics | Report.PatientDemography | LastName | as.character |
| idn02 | demographics | Report.PatientDemography | FirstName | as.character |
| idn03 | demographics | Report.PatientDemography | DateOfBirth | to_ymd |
| idn04 | demographics | Report.PatientDemography | PrimaryHospitalNo | as.character |
| idn06 | demographics | Derived | substr(idn03, 1, 4) | derived |
| pat00 | demographics | Report.PatientDemography | Gender | as.character |
| pat13 | demographics | Report.PatientDemography | NationalHealthServiceNo | gsub_whitespace |
| pat20 | demographics | Report.PatientDemography | HomeAddress | addr_split_1 |
| pat21 | demographics | Report.PatientDemography | HomeAddress | addr_split_2 |
| pat22 | demographics | Report.PatientDemography | HomeAddress | addr_split_3 |
| pat19 | demographics | Report.PatientDemography | HomeAddress | addr_split_4 |
| pat23 | demographics | Report.PatientDemography | HomePostCode | as.character |
| pat25 | demographics | Report.PatientDemography | Ethnicity | as.character |
| pat38 | demographics | dbo.vw_PatientGPDetails | GPPracticeCode | as.character |
| pat40 | demographics | Report.PatientDemography | DateOfDeath | to_ymd |
| pat42 | demographics | dbo.vw_ADHCauseOfDeath | CauseOfDeath1 | as.character |
| pat43 | demographics | dbo.vw_ADHCauseOfDeath | CauseOfDeath2 | as.character |
| dxs01 | diagnoses | Report.PatientRenalDiagnosis | RenalDiagnosisID | safe_first_p1 |
| dxs02 | diagnoses |  |  | NA_placeholder |
| dxs03 | diagnoses |  |  | NA_placeholder |
| dxs04 | diagnoses | Report.PatientRenalDiagnosis | RenalDiagnosisID | safe_first_p2 |
| dxs05 | diagnoses | Report.PatientRenalDiagnosis | RenalDiagnosis_ReadCode | safe_first_p1 |
| dxs06 | diagnoses | Report.PatientRenalDiagnosis | StartDate | to_ymd_p1 |
| dxs07 | diagnoses | dbo.tbl_EDTA_ERA_Registry_Patient | Diabetes_Mellitus | to_01 |
| dxs08 | diagnoses |  |  | NA_placeholder |
| dxs09 | diagnoses | dbo.tbl_EDTA_ERA_Registry_Patient | Malignancy | to_YN_unknown |
| dxs10 | diagnoses |  |  | NA_placeholder |
| dxs11 | diagnoses |  |  | NA_placeholder |
| txt00 | renal_treatment | Report.PatientRenalTimeLineEvents | StartDate | to_ymd |
| txt01 | renal_treatment | Report.PatientRenalTimeLineEvents | EndDate | to_ymd |
| txt02 | renal_treatment | Report.PatientRenalTimeLineEvents | TreatmentModalityCode | as.character |
| txt20 | renal_treatment | Report.PatientSite | SiteCode | as.character |
| txt21 | renal_treatment | Report.PatientRenalTimeLineEvents | Supervision | as.character |
| txt40 | renal_treatment | Report.PatientRenalTimeLineEvents | TransferInFrom | as.character |
| txt41 | renal_treatment | Report.PatientRenalTimeLineEvents | TransferOutTo | as.character |
| hdp00 | hd_prescription | Report.PatientHDPrescription | PrescriptionDate | to_ymd |
| hdp01 | hd_prescription | Report.PatientHDPrescription | TimesPerWeek | as.character |
| hdp02 | hd_prescription | Report.PatientHDPrescription | TimeDialysedMinutes | as.character |
| hdp04 | hd_prescription | dbo.vw_VascularAccessDetails | VascularAccessCode | as.character |
| qhd00 | hd_sessions | Report.PatientHDTreatments | DxDate | to_ymd |
| qhd40 | hd_sessions | Report.PatientHDTreatments | SessionStartTime | format_time |
| qhd41 | hd_sessions | Report.PatientHDTreatments | TreatmentType | as.character |
| qhd20 | hd_sessions | Report.PatientHDTreatments | VascularAccessUsed | as.character |
| qhd31 | hd_sessions | Report.PatientHDTreatments | DurationMinutes | as.character |
| med01 | medications | Report.PatientDrugList | StartDate | to_ymd |
| med02 | medications | Report.PatientDrugList | StopDate | to_ymd |
| med03 | medications | Report.PatientDrugList | GenericName | as.character |
| med04 | medications | Report.PatientDrugList | BrandName | as.character |
| med05 | medications | Report.PatientDrugList | UnitOfMeasurement | as.character |
| med06 | medications | Report.PatientDrugList | Dose | as.character |
| med07 | medications | Report.PatientDrugList | Route | as.character |
| med08 | medications | Report.PatientDrugList | Frequency | as.character |
| med09 | medications | Report.PatientDrugList | Comments | as.character |
| qblg1 | observations | Report.vw_ObservationBMI | Weight | as.character |
| qblg2 | observations | Report.vw_ObservationBMI | WeightDate | to_ymd |
| qblgb | observations | Report.vw_ObservationBMI | Height | as.character |
| qblgc | observations | Report.vw_ObservationBMI | HeightDate | to_ymd |
| qblg3 | observations | Report.vw_ObservationBP | SystolicBP | as.character |
| qblg4 | observations | Report.vw_ObservationBP | DiastolicBP | as.character |
| qblg5 | observations | Report.vw_ObservationBP | BPDate | to_ymd |
| qblg6 | observations | Report.PatientHDTreatments | PostSystolicBP | as.character |
| qblg7 | observations | Report.PatientHDTreatments | PostDiastolicBP | as.character |
| qblg8 | observations | Report.PatientHDTreatments | PostBPDate | to_ymd |
| qblks | observations | Report.vw_HDWeight | PostDialysisWeight | as.character |
| qblkt | observations | Report.vw_HDWeight | PostWeightDate | to_ymd |
| qblku | observations | Report.PatientClinicalStatus | PeritonitisSymptoms | as.character |
| qblkv | observations | Report.PatientClinicalStatus | PeritonitisDate | to_ymd |
| tra61 | transplant | Report.PatientTxProcedure | TransplantDate | to_ymd |
| tra64 | transplant | Report.PatientTxProcedure | FailureDate | to_ymd |
| tra77 | transplant | Report.TxRecipientDonor | DonorType | as.character |
| tra70 | transplant | Report.TxRecipientDonor | RecipientID | as.character |
| tra72 | transplant | Report.PatientTxProcedure | RegistrationDate | to_ymd |
| tra73 | transplant | Report.PatientTxProcedure | TransplantCentre | as.character |
| tra91 | transplant | Report.PatientTxProcedure | ColdIschaemicTime | as.character |
| tra83 | transplant | Report.TxRecipientDonor | HLAMismatchA | as.character |
| tra84 | transplant | Report.TxRecipientDonor | HLAMismatchB | as.character |
| tra85 | transplant | Report.TxRecipientDonor | HLAMismatchDR | as.character |
| cap01 | care_planning | Report.PatientClinicalStatus | AssessmentDate | to_ymd |
| cap02 | care_planning | Report.PatientClinicalStatus | AssessmentType | as.character |
| cap03 | care_planning | Report.PatientClinicalStatus | AssessmentOutcome | as.character |
