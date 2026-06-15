# IKDDS Data Dictionary

> **Auto-generated from the `ikdds` package metadata** (`redcap_dictionary` + `field_mapping`) on 2026-06-15. Do not edit by hand -- change the package data and regenerate.


**209 fields across 11 forms.**

## Summary by form

| Form | Fields | Field types |
| --- | --- | --- |
| registry_enrolment | 1 | text |
| demographics | 25 | text, dropdown |
| diagnoses | 11 | text, radio, dropdown |
| renal_treatment | 7 | text, dropdown |
| hd_prescription | 4 | text, dropdown |
| hd_sessions | 5 | text, dropdown |
| medications | 9 | text, dropdown |
| lab_results | 120 | text |
| observations | 14 | text |
| care_planning | 3 | text |
| transplant | 10 | text |


## Registry enrolment

| Field | Label | Type | Validation | Choices |
| --- | --- | --- | --- | --- |
| record_id | Registry record ID | text |  |  |

## Demographics

| Field | Label | Type | Validation | Choices |
| --- | --- | --- | --- | --- |
| idn01 | Patient Surname | text |  |  |
| idn02 | Patient Forename | text |  |  |
| idn03 | Date of Birth | text | date_ymd |  |
| idn04 | Local Hospital Number | text |  |  |
| idn05 | Flag for Opted out of sending identifiable data to UKRR | text |  |  |
| idn06 | Year of birth | text | integer |  |
| idn07 | Unique identifier not attributable to patient. | text |  |  |
| idn08 | Patient birth name = name on birth certificate - also 'Maiden name' | text |  |  |
| idn09 | Alias - other surname by which patient also known | text |  |  |
| pat00 | Sex, Gender on birth certificate | text |  |  |
| pat01 | Hospital centre code | dropdown |  | ABROAD, ABROAD \| SNC01, Aberdeen Royal Infirmary \| SLC01, Monklands Hospital \| 24027, Antrim Hospital \| RQBAU, Ysbyty Gwynedd \| RDDH0, Basildon Hospital \| 2020, Belfast City Hospital \| 11023, Royal Belfast Hospital for Sick Children \| 7021, Ulster Hospital \| RQ3, Birmingham Childrens Hospital \| RL7, Heartlands Hospital \| RRK02, Queen Elizabeth Hospital \| RAE05, St Lukes Hospital \| RGU01, Royal Sussex County Hospital \| RA723, Bristol Royal Hospital for Children \| REE01, Southmead Hospital \| RGT01, Addenbrookes Hospital \| RVVKC, Kent & Canterbury Hospital \| RWM51, Children's Kidney Centre - UHW \| RRBBV, University Hospital of Wales \| RLGAY, Cumberland Infirmary \| RAZ, St Helier Hospital \| RQ8L0, Broomfield Hospital \| RDEE4, Colchester General Hospital \| RKB01, University Hospital Coventry & Warwick \| RFPFG, Royal Derby Hospital \| RP5, Doncaster Royal Infirmary \| RBD01, Dorset County Hospital \| RNA03, Russells Hall Hospital \| SYC02, Dumfries & Galloway Royal Infirmary \| STC01, Ninewells Hospital \| SSC02, Royal Infirmary of Edinburgh \| RH8, Royal Devon and Exeter Hospital \| SGC04, Queen Elizabeth University Hospital \| SGC02, Royal Hospital for Sick Children \| RH641, Gloucestershire Royal Hospital \| RF201, Hull Royal Infirmary \| SHC01, Raigmore Hospital \| RGQ02, Ipswich Hospital \| SAC02, University Hospital Crosshouse \| SFC01, Victoria Hospital \| 99RQR13, Leeds Children's Hospital \| RQR13, St James's University Hospital \| RFBAK, Leicester General Hospital \| RW402, Aintree University Hospital \| RBS25, Alder Hey Childrens Hospital \| RQ617, Royal Liverpool University Hospital \| RNJ00, Barts and The London Hospital \| RJ122, Evelina Children's Hospital (Guys & St Thomas') \| RP4, Great Ormond Street Hospital for Children \| RJ121, Guy's and St Thomas's Hospital \| RJZ, King's College Hospital \| RAL01, Royal Free Hospital \| RJ701, St George's Hospital \| RQN02, West London Transplant & Renal Centre (Imperial) \| RM574, Manchester Royal Infirmary \| RW3RM, Royal Manchester Children's Hospital \| RCJAT, James Cook University Hospital \| RTD01, Freeman Hospital & Royal Victoria Infirmary \| RTD02, The Great North Childrens Hospital \| 33020, Daisy Hill Hospital  (Southern Trust) \| RM102, Norfolk & Norwich University Hospital \| 99RCSLB, Nottingham Childrens Hospital  (Queens Medical Centre) \| RCSLB, Nottingham City Hospital \| 45021, Tyrone County Hospital  (Western Trust) \| RNX02, Oxford Radcliffe Hospital \| RK950, Derriford Hospital \| RHU02, Queen Alexandra Hospital \| RMF01, Royal Preston Hospital \| RHW01, Royal Berkshire Hospital \| RKGA1, Ysbyty Glan Clwyd \| RM301, Salford Royal Hospital \| RK7CC, Northern General Hospital \| RLZ01, Royal Shrewsbury Hospital \| RHM02, Southampton Childrens Hospital \| RAJ01, Southend Hospital \| RAQ01, Lister Hospital \| RJE01, Royal Stoke University hospital \| RLNGH, Sunderland Royal Hospital \| RQHC7, Morriston Hospital \| REF12, Royal Cornwall Hospital (Treliske) \| RBL14, Arrowe Park Hospital \| RL403, New Cross Hospital \| RKHA4, Wrexham Maelor Hospital \| RCB55, York District General Hospital |
| pat11 | CHI number - patients registered in Scotland | text |  |  |
| pat13 | NHS number format - without spaces | text |  |  |
| pat18 | H & C Number - patients registered in Northern Ireland | text |  |  |
| pat20 | Address line 1 | text |  |  |
| pat21 | Address line 2 | text |  |  |
| pat22 | Address line 3 | text |  |  |
| pat19 | Address line 4 | text |  |  |
| pat23 | Postcode | text |  |  |
| pat25 | Ethnicity | text |  |  |
| pat38 | GP Practice code (current) | text |  |  |
| pat40 | Date of death | text | date_ymd |  |
| pat42 | Main Cause of death 1 EDTA | dropdown |  | 0, Cause of death uncertain / not determined \| 11, Myocardial ischaemia and infarction \| 12, Hyperkalaemia \| 13, Haemorrhagic pericarditis \| 14, Other causes of cardiac failure \| 15, Cardiac arrest/sudden death; other cause or unknown \| 16, Hypertensive cardiac failure \| 17, Hypokalaemia \| 18, Fluid overload/pulmonary oedema \| 19, Elevated PVR/Pulmonary hypertension \| 21, Pulmonary embolus \| 22, Cerebro-vascular accident, other cause or unspecified \| 23, Gastro-intestinal haemorrhage (digestive) \| 24, Haemorrhage from graft site \| 25, Haemorrhage from vascular access or dialysis circuit \| 26, Cerebral haemorrhage from ruptured vascular aneurysm (not code 22 or 23) \| 27, Haemorrhage from surgery (except digestive haemorrhage) \| 28, Other haemorrhage, other site and/or other cause \| 29, Mesenteric infarction \| 31, Pulmonary infection (bacterial) \| 32, Pulmonary infection (viral) \| 33, Pulmonary infection (fungal or protozoal; parasitic) \| 34, Infections elsewhere except viral hepatitis \| 35, Septicaemia \| 36, Tuberculosis (lung) \| 37, Tuberculosis (elsewhere) \| 38, Generalized viral infection \| 39, Peritonitis (all causes except for Peritoneal Dialysis) \| 41, Liver disease due to hepatitis B virus \| 42, Liver disease due to other viral hepatitis \| 43, Liver disease due to drug toxicity \| 44, Cirrhosis - not viral (alcoholic or other cause) \| 45, Cystic liver disease \| 46, Liver failure - cause unknown \| 51, Patient refused further treatment for ERF \| 52, Suicide \| 53, ERF treatment ceased for any other reason \| 54, ERF treatment withdrawn for medical reasons \| 61, Ureamia caused by graft failure \| 62, Pancreatitis \| 63, Bone marrow depression (Aplosia) \| 64, Cachexia \| 66, Malignant disease in patient treated by immunosuppressive therapy \| 67, Malignant disease: solid tumors (except those of 66) \| 68, Malignant disease: lymphoproliferative disorders (except 66) \| 69, Dementia \| 70, Peritonitis (sclerosing, with peritoneal dialysis) \| 71, Perforation of peptic ulcer \| 72, Perforation of colon \| 73, COPD \| 79, Multi-system failure \| 81, Accident related to ESRF treatment (not 25) \| 82, Accident unrelated to ERF treatment \| 99, Other identified cause of death \| 100, Peritonitis (bacterial, with peritoneal dialysis) \| 101, Peritonitis (fungal, with peritoneal dialysis) \| 102, Peritonitis (due to other cause, with peritoneal dialysis) \| 103, Peripheral vascular disease \| 104, Calciphylaxis \| 105, Ischaemic bowel \| 106, Ruptured AAA \| 107, Advanced CKD not on dialysis(conservative management) \| 108, Acute kidney injury \| 109, C Diff colitis \| 110, Line related sepsis \| 111, COVID 19 |
| pat43 | Cause of death 2 EDTA | dropdown |  | 0, Cause of death uncertain / not determined \| 11, Myocardial ischaemia and infarction \| 12, Hyperkalaemia \| 13, Haemorrhagic pericarditis \| 14, Other causes of cardiac failure \| 15, Cardiac arrest/sudden death; other cause or unknown \| 16, Hypertensive cardiac failure \| 17, Hypokalaemia \| 18, Fluid overload/pulmonary oedema \| 19, Elevated PVR/Pulmonary hypertension \| 21, Pulmonary embolus \| 22, Cerebro-vascular accident, other cause or unspecified \| 23, Gastro-intestinal haemorrhage (digestive) \| 24, Haemorrhage from graft site \| 25, Haemorrhage from vascular access or dialysis circuit \| 26, Cerebral haemorrhage from ruptured vascular aneurysm (not code 22 or 23) \| 27, Haemorrhage from surgery (except digestive haemorrhage) \| 28, Other haemorrhage, other site and/or other cause \| 29, Mesenteric infarction \| 31, Pulmonary infection (bacterial) \| 32, Pulmonary infection (viral) \| 33, Pulmonary infection (fungal or protozoal; parasitic) \| 34, Infections elsewhere except viral hepatitis \| 35, Septicaemia \| 36, Tuberculosis (lung) \| 37, Tuberculosis (elsewhere) \| 38, Generalized viral infection \| 39, Peritonitis (all causes except for Peritoneal Dialysis) \| 41, Liver disease due to hepatitis B virus \| 42, Liver disease due to other viral hepatitis \| 43, Liver disease due to drug toxicity \| 44, Cirrhosis - not viral (alcoholic or other cause) \| 45, Cystic liver disease \| 46, Liver failure - cause unknown \| 51, Patient refused further treatment for ERF \| 52, Suicide \| 53, ERF treatment ceased for any other reason \| 54, ERF treatment withdrawn for medical reasons \| 61, Ureamia caused by graft failure \| 62, Pancreatitis \| 63, Bone marrow depression (Aplosia) \| 64, Cachexia \| 66, Malignant disease in patient treated by immunosuppressive therapy \| 67, Malignant disease: solid tumors (except those of 66) \| 68, Malignant disease: lymphoproliferative disorders (except 66) \| 69, Dementia \| 70, Peritonitis (sclerosing, with peritoneal dialysis) \| 71, Perforation of peptic ulcer \| 72, Perforation of colon \| 73, COPD \| 79, Multi-system failure \| 81, Accident related to ESRF treatment (not 25) \| 82, Accident unrelated to ERF treatment \| 99, Other identified cause of death \| 100, Peritonitis (bacterial, with peritoneal dialysis) \| 101, Peritonitis (fungal, with peritoneal dialysis) \| 102, Peritonitis (due to other cause, with peritoneal dialysis) \| 103, Peripheral vascular disease \| 104, Calciphylaxis \| 105, Ischaemic bowel \| 106, Ruptured AAA \| 107, Advanced CKD not on dialysis(conservative management) \| 108, Acute kidney injury \| 109, C Diff colitis \| 110, Line related sepsis \| 111, COVID 19 |
| pat44 | Cause of death - free text if no appropriate code available | text |  |  |

## Diagnoses

| Field | Label | Type | Validation | Choices |
| --- | --- | --- | --- | --- |
| dxs01 | EDTA primary renal disease code | text | integer |  |
| dxs02 | SNOMED primary renal disease code | text |  |  |
| dxs03 | Was primary renal disease diagnosis confirmed by kidney biopsy? | radio |  | Y, Yes \| N, No \| UNKNOWN, Unknown |
| dxs04 | Secondary renal disease code | text |  |  |
| dxs05 | Primary disease free text if no suitable code available | text |  |  |
| dxs06 | Date of diagnosis of primary renal disease | text | date_ymd |  |
| dxs07 | Diabetes | text |  |  |
| dxs08 | Date diabetes diagnosed | text | date_ymd |  |
| dxs09 | Malignancy Yes / No | radio |  | Y, Yes \| N, No \| UNKNOWN, Unknown |
| dxs10 | Malignancy site, first primary site only | dropdown |  | 101, Non-melanoma skin cancer, BCC, SCC \| 102, Melanoma \| 103, Breast \| 104, Upper GI (oesophagus/stomach) \| 105, Lower GI (small/large bowel) \| 106, Lung \| 107, Urological NOT prostate \| 108, Prostate \| 109, Testicular \| 110, Leukaemia \| 111, Lymphoma \| 112, Myeloma \| 113, CNS Tumour \| 114, Musculo-skeletal \| 115, Other |
| dxs11 | Malignancy  - date first diagnosed | text | date_ymd |  |

## Renal treatment

| Field | Label | Type | Validation | Choices |
| --- | --- | --- | --- | --- |
| txt00 | Date start treatment | text | date_ymd |  |
| txt01 | Date end treatment | text | date_ymd |  |
| txt02 | Treatment modality code | text |  |  |
| txt20 | Treatment site/centre code | dropdown |  | ABROAD, ABROAD \| SNC01, Aberdeen Royal Infirmary \| SLC01, Monklands Hospital \| 24027, Antrim Hospital \| RQBAU, Ysbyty Gwynedd \| RDDH0, Basildon Hospital \| 2020, Belfast City Hospital \| 11023, Royal Belfast Hospital for Sick Children \| 7021, Ulster Hospital \| RQ3, Birmingham Childrens Hospital \| RL7, Heartlands Hospital \| RRK02, Queen Elizabeth Hospital \| RAE05, St Lukes Hospital \| RGU01, Royal Sussex County Hospital \| RA723, Bristol Royal Hospital for Children \| REE01, Southmead Hospital \| RGT01, Addenbrookes Hospital \| RVVKC, Kent & Canterbury Hospital \| RWM51, Children's Kidney Centre - UHW \| RRBBV, University Hospital of Wales \| RLGAY, Cumberland Infirmary \| RAZ, St Helier Hospital \| RQ8L0, Broomfield Hospital \| RDEE4, Colchester General Hospital \| RKB01, University Hospital Coventry & Warwick \| RFPFG, Royal Derby Hospital \| RP5, Doncaster Royal Infirmary \| RBD01, Dorset County Hospital \| RNA03, Russells Hall Hospital \| SYC02, Dumfries & Galloway Royal Infirmary \| STC01, Ninewells Hospital \| SSC02, Royal Infirmary of Edinburgh \| RH8, Royal Devon and Exeter Hospital \| SGC04, Queen Elizabeth University Hospital \| SGC02, Royal Hospital for Sick Children \| RH641, Gloucestershire Royal Hospital \| RF201, Hull Royal Infirmary \| SHC01, Raigmore Hospital \| RGQ02, Ipswich Hospital \| SAC02, University Hospital Crosshouse \| SFC01, Victoria Hospital \| 99RQR13, Leeds Children's Hospital \| RQR13, St James's University Hospital \| RFBAK, Leicester General Hospital \| RW402, Aintree University Hospital \| RBS25, Alder Hey Childrens Hospital \| RQ617, Royal Liverpool University Hospital \| RNJ00, Barts and The London Hospital \| RJ122, Evelina Children's Hospital (Guys & St Thomas') \| RP4, Great Ormond Street Hospital for Children \| RJ121, Guy's and St Thomas's Hospital \| RJZ, King's College Hospital \| RAL01, Royal Free Hospital \| RJ701, St George's Hospital \| RQN02, West London Transplant & Renal Centre (Imperial) \| RM574, Manchester Royal Infirmary \| RW3RM, Royal Manchester Children's Hospital \| RCJAT, James Cook University Hospital \| RTD01, Freeman Hospital & Royal Victoria Infirmary \| RTD02, The Great North Childrens Hospital \| 33020, Daisy Hill Hospital  (Southern Trust) \| RM102, Norfolk & Norwich University Hospital \| 99RCSLB, Nottingham Childrens Hospital  (Queens Medical Centre) \| RCSLB, Nottingham City Hospital \| 45021, Tyrone County Hospital  (Western Trust) \| RNX02, Oxford Radcliffe Hospital \| RK950, Derriford Hospital \| RHU02, Queen Alexandra Hospital \| RMF01, Royal Preston Hospital \| RHW01, Royal Berkshire Hospital \| RKGA1, Ysbyty Glan Clwyd \| RM301, Salford Royal Hospital \| RK7CC, Northern General Hospital \| RLZ01, Royal Shrewsbury Hospital \| RHM02, Southampton Childrens Hospital \| RAJ01, Southend Hospital \| RAQ01, Lister Hospital \| RJE01, Royal Stoke University hospital \| RLNGH, Sunderland Royal Hospital \| RQHC7, Morriston Hospital \| REF12, Royal Cornwall Hospital (Treliske) \| RBL14, Arrowe Park Hospital \| RL403, New Cross Hospital \| RKHA4, Wrexham Maelor Hospital \| RCB55, York District General Hospital |
| txt21 | Treatment supervision | dropdown |  | HOME, Home (Haemodialysis).  Already implied for PD \| INCENTRE, Treatment occurs In-centre \| ASSISTED, Treatment is assisted by a paid carer |
| txt40 | Transfer in from - site patient originated from | dropdown |  | ABROAD, ABROAD \| SNC01, Aberdeen Royal Infirmary \| SLC01, Monklands Hospital \| 24027, Antrim Hospital \| RQBAU, Ysbyty Gwynedd \| RDDH0, Basildon Hospital \| 2020, Belfast City Hospital \| 11023, Royal Belfast Hospital for Sick Children \| 7021, Ulster Hospital \| RQ3, Birmingham Childrens Hospital \| RL7, Heartlands Hospital \| RRK02, Queen Elizabeth Hospital \| RAE05, St Lukes Hospital \| RGU01, Royal Sussex County Hospital \| RA723, Bristol Royal Hospital for Children \| REE01, Southmead Hospital \| RGT01, Addenbrookes Hospital \| RVVKC, Kent & Canterbury Hospital \| RWM51, Children's Kidney Centre - UHW \| RRBBV, University Hospital of Wales \| RLGAY, Cumberland Infirmary \| RAZ, St Helier Hospital \| RQ8L0, Broomfield Hospital \| RDEE4, Colchester General Hospital \| RKB01, University Hospital Coventry & Warwick \| RFPFG, Royal Derby Hospital \| RP5, Doncaster Royal Infirmary \| RBD01, Dorset County Hospital \| RNA03, Russells Hall Hospital \| SYC02, Dumfries & Galloway Royal Infirmary \| STC01, Ninewells Hospital \| SSC02, Royal Infirmary of Edinburgh \| RH8, Royal Devon and Exeter Hospital \| SGC04, Queen Elizabeth University Hospital \| SGC02, Royal Hospital for Sick Children \| RH641, Gloucestershire Royal Hospital \| RF201, Hull Royal Infirmary \| SHC01, Raigmore Hospital \| RGQ02, Ipswich Hospital \| SAC02, University Hospital Crosshouse \| SFC01, Victoria Hospital \| 99RQR13, Leeds Children's Hospital \| RQR13, St James's University Hospital \| RFBAK, Leicester General Hospital \| RW402, Aintree University Hospital \| RBS25, Alder Hey Childrens Hospital \| RQ617, Royal Liverpool University Hospital \| RNJ00, Barts and The London Hospital \| RJ122, Evelina Children's Hospital (Guys & St Thomas') \| RP4, Great Ormond Street Hospital for Children \| RJ121, Guy's and St Thomas's Hospital \| RJZ, King's College Hospital \| RAL01, Royal Free Hospital \| RJ701, St George's Hospital \| RQN02, West London Transplant & Renal Centre (Imperial) \| RM574, Manchester Royal Infirmary \| RW3RM, Royal Manchester Children's Hospital \| RCJAT, James Cook University Hospital \| RTD01, Freeman Hospital & Royal Victoria Infirmary \| RTD02, The Great North Childrens Hospital \| 33020, Daisy Hill Hospital  (Southern Trust) \| RM102, Norfolk & Norwich University Hospital \| 99RCSLB, Nottingham Childrens Hospital  (Queens Medical Centre) \| RCSLB, Nottingham City Hospital \| 45021, Tyrone County Hospital  (Western Trust) \| RNX02, Oxford Radcliffe Hospital \| RK950, Derriford Hospital \| RHU02, Queen Alexandra Hospital \| RMF01, Royal Preston Hospital \| RHW01, Royal Berkshire Hospital \| RKGA1, Ysbyty Glan Clwyd \| RM301, Salford Royal Hospital \| RK7CC, Northern General Hospital \| RLZ01, Royal Shrewsbury Hospital \| RHM02, Southampton Childrens Hospital \| RAJ01, Southend Hospital \| RAQ01, Lister Hospital \| RJE01, Royal Stoke University hospital \| RLNGH, Sunderland Royal Hospital \| RQHC7, Morriston Hospital \| REF12, Royal Cornwall Hospital (Treliske) \| RBL14, Arrowe Park Hospital \| RL403, New Cross Hospital \| RKHA4, Wrexham Maelor Hospital \| RCB55, York District General Hospital |
| txt41 | Transfer out to - destination site of patient transferring out | dropdown |  | ABROAD, ABROAD \| SNC01, Aberdeen Royal Infirmary \| SLC01, Monklands Hospital \| 24027, Antrim Hospital \| RQBAU, Ysbyty Gwynedd \| RDDH0, Basildon Hospital \| 2020, Belfast City Hospital \| 11023, Royal Belfast Hospital for Sick Children \| 7021, Ulster Hospital \| RQ3, Birmingham Childrens Hospital \| RL7, Heartlands Hospital \| RRK02, Queen Elizabeth Hospital \| RAE05, St Lukes Hospital \| RGU01, Royal Sussex County Hospital \| RA723, Bristol Royal Hospital for Children \| REE01, Southmead Hospital \| RGT01, Addenbrookes Hospital \| RVVKC, Kent & Canterbury Hospital \| RWM51, Children's Kidney Centre - UHW \| RRBBV, University Hospital of Wales \| RLGAY, Cumberland Infirmary \| RAZ, St Helier Hospital \| RQ8L0, Broomfield Hospital \| RDEE4, Colchester General Hospital \| RKB01, University Hospital Coventry & Warwick \| RFPFG, Royal Derby Hospital \| RP5, Doncaster Royal Infirmary \| RBD01, Dorset County Hospital \| RNA03, Russells Hall Hospital \| SYC02, Dumfries & Galloway Royal Infirmary \| STC01, Ninewells Hospital \| SSC02, Royal Infirmary of Edinburgh \| RH8, Royal Devon and Exeter Hospital \| SGC04, Queen Elizabeth University Hospital \| SGC02, Royal Hospital for Sick Children \| RH641, Gloucestershire Royal Hospital \| RF201, Hull Royal Infirmary \| SHC01, Raigmore Hospital \| RGQ02, Ipswich Hospital \| SAC02, University Hospital Crosshouse \| SFC01, Victoria Hospital \| 99RQR13, Leeds Children's Hospital \| RQR13, St James's University Hospital \| RFBAK, Leicester General Hospital \| RW402, Aintree University Hospital \| RBS25, Alder Hey Childrens Hospital \| RQ617, Royal Liverpool University Hospital \| RNJ00, Barts and The London Hospital \| RJ122, Evelina Children's Hospital (Guys & St Thomas') \| RP4, Great Ormond Street Hospital for Children \| RJ121, Guy's and St Thomas's Hospital \| RJZ, King's College Hospital \| RAL01, Royal Free Hospital \| RJ701, St George's Hospital \| RQN02, West London Transplant & Renal Centre (Imperial) \| RM574, Manchester Royal Infirmary \| RW3RM, Royal Manchester Children's Hospital \| RCJAT, James Cook University Hospital \| RTD01, Freeman Hospital & Royal Victoria Infirmary \| RTD02, The Great North Childrens Hospital \| 33020, Daisy Hill Hospital  (Southern Trust) \| RM102, Norfolk & Norwich University Hospital \| 99RCSLB, Nottingham Childrens Hospital  (Queens Medical Centre) \| RCSLB, Nottingham City Hospital \| 45021, Tyrone County Hospital  (Western Trust) \| RNX02, Oxford Radcliffe Hospital \| RK950, Derriford Hospital \| RHU02, Queen Alexandra Hospital \| RMF01, Royal Preston Hospital \| RHW01, Royal Berkshire Hospital \| RKGA1, Ysbyty Glan Clwyd \| RM301, Salford Royal Hospital \| RK7CC, Northern General Hospital \| RLZ01, Royal Shrewsbury Hospital \| RHM02, Southampton Childrens Hospital \| RAJ01, Southend Hospital \| RAQ01, Lister Hospital \| RJE01, Royal Stoke University hospital \| RLNGH, Sunderland Royal Hospital \| RQHC7, Morriston Hospital \| REF12, Royal Cornwall Hospital (Treliske) \| RBL14, Arrowe Park Hospital \| RL403, New Cross Hospital \| RKHA4, Wrexham Maelor Hospital \| RCB55, York District General Hospital |

## Hd prescription

| Field | Label | Type | Validation | Choices |
| --- | --- | --- | --- | --- |
| hdp00 | Date of dialysis prescription | text | date_ymd |  |
| hdp01 | Times per week | text | integer |  |
| hdp02 | Time dialysed in minutes | text | integer |  |
| hdp04 | Vascular access in use | dropdown |  | NLN, Non-tunnelled line \| TLN, Tunnelled Line \| AVF, Arteriovenous fistula \| AVG, Arteriovenous graft \| VLP, Vein loop \| PDC, PD catheter \| PDE, PD Embedded Catheter \| PDT, PD catheter temp |

## Hd sessions

| Field | Label | Type | Validation | Choices |
| --- | --- | --- | --- | --- |
| qhd00 | Date of HD/PEX session | text | date_ymd |  |
| qhd40 | Clock time session started | text |  |  |
| qhd41 | Haemodialysis or plasma exchange | text |  |  |
| qhd20 | Vascular access used for this treatment | dropdown |  | NLN, Non-tunnelled line \| TLN, Tunnelled Line \| AVF, Arteriovenous fistula \| AVG, Arteriovenous graft \| VLP, Vein loop \| PDC, PD catheter \| PDE, PD Embedded Catheter \| PDT, PD catheter temp |
| qhd31 | Duration of treatment in minutes | text | integer |  |

## Medications

| Field | Label | Type | Validation | Choices |
| --- | --- | --- | --- | --- |
| med01 | Drug start date | text | date_ymd |  |
| med02 | Drug stop date | text | date_ymd |  |
| med03 | Generic drug name | text |  |  |
| med04 | Branded drug name | text |  |  |
| med05 | Drug unit of measurement | dropdown |  | L, litres \| dl, decilitres \| ml, millilitres \| g, grams \| mg, milligrams \| ug, micrograms \| ng, nanograms \| tab, tablets \| units, units (i.e. for Epoetins) \| mmol, millimols \| other, Other - please specify in comments |
| med06 | Drug dose | text | integer |  |
| med07 | Drug route | dropdown |  | 1, Oral \| 2, Topical \| 3, Inhalation \| 4, Injection \| 5, Intra peritoneal \| 9, Other - please specify in comments |
| med08 | Drug frequency of administration | text |  |  |
| med09 | Drug comments | text |  |  |

## Lab results

| Field | Label | Type | Validation | Choices |
| --- | --- | --- | --- | --- |
| qbla6 | Serum sodium | text | integer |  |
| qbla7 | Date of sodium | text | date_ymd |  |
| qblkn | Serum sodium - post dialysis | text | integer |  |
| qblkp | Date of post dialysis sodium | text | date_ymd |  |
| qbla9 | Serum potassium | text | number |  |
| qblaa | Date of potassium | text | date_ymd |  |
| qblkl | Serum potassium - post dialysis | text | number |  |
| qblkm | Date of post dialysis potassium | text | date_ymd |  |
| qbla3 | Serum urea | text | integer |  |
| qblaj | Date of serum urea | text | date_ymd |  |
| qblkg | Serum urea - post dialysis | text | integer |  |
| qblkh | Date of post dialysis urea | text | date_ymd |  |
| qbla1 | Serum creatinine | text | integer |  |
| qbla2 | Date of serum creatinine | text | date_ymd |  |
| qblke | Serum creatinine - post dialysis | text | integer |  |
| qblkf | Date of post dialysis creatinine | text | date_ymd |  |
| qbla4 | Serum bicarbonate | text | integer |  |
| qbla5 | Date of bicarbonate | text | date_ymd |  |
| qblkq | Serum bicarbonate  - post dialysis | text | integer |  |
| qblkr | Date of post dialysis bicarbonate | text | date_ymd |  |
| qblap | Glomerular filtration rate (GFR) predicted by creatinine based formula (CKD-EPI) WITHOUT ethnicity | text | integer |  |
| qblaq | Date of CKD-EPI eGFR | text | date_ymd |  |
| qblar | Glomerular filtration rate (GFR) predicted by creatinine based formula (MDRD) WITHOUT ethnicity | text | integer |  |
| qblas | Date of MDRD eGFR | text | date_ymd |  |
| qblac | Serum uric acid (urate) | text | integer |  |
| qblad | Date of serum uric acid (urate) | text | date_ymd |  |
| qblb1 | Serum phosphate | text | integer |  |
| qblb2 | Date of serum phosphate | text | date_ymd |  |
| qblb3 | Serum calcium | text | integer |  |
| qblbb | Date of serum calcium | text | date_ymd |  |
| qblb4 | Corrected/adjusted serum calcium | text | integer |  |
| qblbc | Date of corrected/adjusted serum calcium | text | date_ymd |  |
| qblb5 | Serum alkaline phosphatase | text | integer |  |
| qblb6 | Date of Serum alkaline phosphatase | text | date_ymd |  |
| qblpc | ALT - alanine transaminase | text | integer |  |
| qbljb | Date of ALT | text | date_ymd |  |
| qblb7 | Serum albumin | text | integer |  |
| qblb8 | Date of albumin | text | date_ymd |  |
| qblb9 | Serum parathyroid hormone (PTH) | text | integer |  |
| qblba | Date of PTH | text | date_ymd |  |
| qbld1 | Total serum cholesterol | text | integer |  |
| qbld2 | Date of serum cholesterol | text | date_ymd |  |
| qbld3 | Serum HDL cholesterol | text | integer |  |
| qbldb | Date of serum HDL cholesterol | text | date_ymd |  |
| qbld4 | Serum LDL cholesterol | text | integer |  |
| qbldc | Date of serum LDL cholesterol | text | date_ymd |  |
| qbld5 | Serum triglycerides | text | integer |  |
| qbldf | Date of serum triglycerides | text | date_ymd |  |
| qbld6 | CRP | text | integer |  |
| qbld7 | Date of CRP | text | date_ymd |  |
| qbld8 | HbA1c (%) | text | integer |  |
| qblda | HbA1c (mmol/mol) | text | integer |  |
| qbld9 | Date of HbA1c | text | date_ymd |  |
| qble1 | Haemoglobin (g/dL) | text | integer |  |
| qbleb | Haemoglobin (g/L) | text | integer |  |
| qble2 | Date of haemoglobin | text | date_ymd |  |
| qble5 | White blood count (WBC) | text | integer |  |
| qblea | Date of WBC | text | date_ymd |  |
| qble4 | Platelets | text | integer |  |
| qble9 | Date of platelets | text | date_ymd |  |
| qbljj | Reticulocyte haemoglobin (CHr) | text | integer |  |
| qbljk | Date of reticulocyte haemoglobin | text | date_ymd |  |
| qblf1 | Serum ferritin | text | integer |  |
| qblf2 | Date of serum ferritin | text | date_ymd |  |
| qblf3 | Transferrin saturation | text | integer |  |
| qblf4 | Date of transferrin saturation | text | date_ymd |  |
| qblf5 | Percentage of hypochromic red cells | text | integer |  |
| qblf6 | Date of hypochromic red cells | text | date_ymd |  |
| qblf7 | Serum B12 | text | integer |  |
| qblf8 | Date of serum B12 | text | date_ymd |  |
| qblf9 | Serum folate | text | integer |  |
| qblfa | Date of serum folate | text | date_ymd |  |
| qblfb | Red cell folate | text | number |  |
| qblfc | Date of red cell folate | text | date_ymd |  |
| qblgu | PSA - prostate specific antigen | text | integer |  |
| qblgv | Date of PSA test | text | date_ymd |  |
| qblff | Tacrolimus blood concentration level | text | integer |  |
| qblfg | Date of tacrolimus blood concentration level | text | date_ymd |  |
| qblfh | Sirolimus blood concentration level | text | integer |  |
| qblfj | Date of sirolimus blood concentration level | text | date_ymd |  |
| qblfk | Ciclosporin blood concentration level | text | integer |  |
| qblfl | Date of ciclosporin blood concentration level | text | date_ymd |  |
| qblfm | Mycophenolate blood concentration level | text | integer |  |
| qblfn | Date of mycophenolate blood concentration level | text | date_ymd |  |
| qblg9 | Urea reduction ratio | text | integer |  |
| qblga | Date of urea reduction ratio | text | date_ymd |  |
| qblgg | Kt/V measured by a haemodialysis machine | text | integer |  |
| qblgh | Date of Kt/V | text | date_ymd |  |
| qblha | HBV surface antibody status | text |  |  |
| qblhb | Date of test HBV surface antibody | text | date_ymd |  |
| qblhc | HBV surface antigen status | text |  |  |
| qblhd | Date of test HBV surface antigen | text | date_ymd |  |
| qblhe | HCV antibody status | text |  |  |
| qblhf | Date of test HCV surface antibody | text | date_ymd |  |
| qblh1 | BK Virus status | text |  |  |
| qblh2 | Date of BK Virus status | text | date_ymd |  |
| qblhm | HIV screening test | text |  |  |
| qblhl | Date HIV screening test | text | date_ymd |  |
| qblgn | COVID-19 antigen PCR | text |  |  |
| qblgp | Date of COVID-19 antigen PCR | text | date_ymd |  |
| qblgs | COVID-19 IgG antibody status | text |  |  |
| qblgt | Date of COVID-19 IgG antibody status | text | date_ymd |  |
| qblc1 | Urine protein:creatinine ratio | text | integer |  |
| qblc2 | Date of urine protein:creatinine ratio | text | date_ymd |  |
| qblc3 | Urine albumin:creatinine ratio | text | integer |  |
| qblc4 | Date of urine albumin:creatinine ratio | text | date_ymd |  |
| qblhx | Urine creatinine concentration | text | integer |  |
| qblhy | Date of urine creatinine concentration | text | date_ymd |  |
| qbljs | Urine protein concentration | text | integer |  |
| qbljt | Date of urinary protein concentration | text | date_ymd |  |
| qbljl | Proteinuria dipstick test | text |  |  |
| qbljm | Date of Proteinuria dipstick test | text | date_ymd |  |
| qblhv | Urine volume in 24 hours | text | integer |  |
| qblhu | Date of urine volume in 24 hours | text | date_ymd |  |
| qbljn | PD fluid WCC count | text |  |  |
| qbljp | Date of PD fluid WCC count | text | date_ymd |  |
| qbljq | PD fluid culture organism grown  text | text |  |  |
| qbljr | Date of PD fluid culture test | text | date_ymd |  |
| qbljx | Blood culture organism grown text ** | text |  |  |
| qbljy | Date of blood culture test | text | date_ymd |  |

## Observations

| Field | Label | Type | Validation | Choices |
| --- | --- | --- | --- | --- |
| qblg1 | Weight | text | integer |  |
| qblg2 | Date of weight | text | date_ymd |  |
| qblgb | Height | text | integer |  |
| qblgc | Date of Height | text | date_ymd |  |
| qblg3 | Systolic blood pressure | text | integer |  |
| qblg4 | Diastolic blood pressure | text | integer |  |
| qblg5 | Date of blood Pressure | text | date_ymd |  |
| qblg6 | Post dialysis systolic blood pressure | text | integer |  |
| qblg7 | Post dialysis diastolic blood pressure | text | integer |  |
| qblg8 | Date of post dialysis blood pressure | text | date_ymd |  |
| qblks | Body weight measured post dialysis | text | integer |  |
| qblkt | Date of body weight measured post dialysis | text | date_ymd |  |
| qblku | Symptoms of peritonitis | text |  |  |
| qblkv | Date of peritonitis symptoms | text | date_ymd |  |

## Care planning

| Field | Label | Type | Validation | Choices |
| --- | --- | --- | --- | --- |
| cap01 | Date of assessment | text | date_ymd |  |
| cap02 | Type of assessment | text |  |  |
| cap03 | Outcome of assessment | text |  |  |

## Transplant

| Field | Label | Type | Validation | Choices |
| --- | --- | --- | --- | --- |
| tra61 | Date of kidney transplant | text | date_ymd |  |
| tra64 | Date of kidney transplant failure | text | date_ymd |  |
| tra77 | UKTR donor type of transplant | text |  |  |
| tra70 | UKTR recipient ID | text | integer |  |
| tra72 | Date registered for transplantation | text | date_ymd |  |
| tra73 | Transplant centre | text | integer |  |
| tra91 | Cold Ischaemic Time - in minutes | text | integer |  |
| tra83 | HLA Mismatch A | text | integer |  |
| tra84 | HLA Mismatch B | text | integer |  |
| tra85 | HLA Mismatch DR | text | integer |  |
