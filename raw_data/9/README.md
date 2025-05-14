# **Data from: Safety and efficacy of BCG re-vaccination in relation to COVID-19 morbidity in healthcare workers: A double-blind, randomised, controlled, phase 3 trial**

The TASK008-BCG CORONA SDTM datasets contains all the study data collected under the TASK008-BCG CORONA protocol. The data is in the raw format of information captured onto the electronic Case Report Forms from the source documentation.

**Description of the data and file structure**

The TASK008-BCG CORONA SDTM datasets contain the study data in the CDISC SDTM format. The following CDISC SDTM domains were reported in the datasets:

AE - Adverse Events

CM - Concomitant Medication

DM - Demographics

DS - Disposition

EX - Exposure

IE - Inclusion and Exclusion Criteria

LB - Laboratory Findings

MH - Medical History

SV - Subject Visits

VS - Vital Signs

File Formats: The datasets are in both .CSV and .sas7bdat (include 1 SAS formats. catalogue) Below is the structure of each domain

| **AE (Adverse Events) Domain** |                   |          |         |            |              |                                                                     |
| :----------------------------- | ----------------- | -------- | ------- | ---------- | ------------ | ------------------------------------------------------------------- |
| **#**                          | **Variable**      | **Type** | **Len** | **Format** | **Informat** | **Label**                                                           |
| **1**                          | STUDYID           | Char     | 18      |            |              |  Study ID                                                           |
| **2**                          | TRTGRP            | Char     | 200     | $GROUPS.   |              | Treatment Group                                                     |
| **3**                          | USUBJID           | Char     | 7       | $7.        | $7.          | Unique Participant ID                                               |
| **4**                          | AESPID            | Num      | 8       | BEST12.    | BEST32.      | AE Sponsor ID                                                       |
| **5**                          | AECAT             | Char     | 5       | $5.        | $5.          | AE Category                                                         |
| **6**                          | AEPT              | Char     | 41      | $41.       | $41.         | AE MedDRA Preferred Term                                            |
| **7**                          | AEPTCD            | Num      | 8       | BEST12.    | BEST32.      | AE MedDRA Preferred Term Code                                       |
| **8**                          | AEHLGT            | Char     | 86      | $86.       | $86.         | AE MedDRA High Level Group Term                                     |
| **9**                          | AEHLGTCD          | Num      | 8       | BEST12.    | BEST32.      | AE MedDRA High Level Group Term Code                                |
| **10**                         | AEHLT             | Char     | 70      | $70.       | $70.         | AE MedDRA High Level Term                                           |
| **11**                         | AEHLTCD           | Num      | 8       | BEST12.    | BEST32.      | AE MedDRA High Level Term Code                                      |
| **12**                         | AELLT             | Char     | 79      | $79.       | $79.         | AE MedDRA Lower Level Term                                          |
| **13**                         | AELLTCD           | Num      | 8       | BEST12.    | BEST32.      | AE MedDRA Lower Level Term Code                                     |
| 14                             | AESTDTC           | Num      | 8       | YYMMDD10.  | YYMMDD10.    | Anonymised AE Start Date (Number of Days after Study Day 1)         |
| 15                             | AEENDTC           | Num      | 8       | YYMMDD10.  | YYMMDD10.    | Anonymised AE End Date (Number of Days after Study Day 1)           |
| **16**                         | AEENDTFU          | Num      | 8       | YYMMDD10.  | YYMMDD10.    | Anonymised AE End Follow Up Date (Number of Days after Study Day 1) |
| **17**                         | AEOUT             | Char     | 500     | $9.        | $9.          | AE Outcome                                                          |
| **18**                         | AEOUTFU           | Char     | 500     | $9.        | $9.          | AE Outcome Follow Up                                                |
| **10**                         | AEONGO            | Char     | 3       | $3.        | $3.          | AE Ongoing?                                                         |
| 20                             | AESEV             | Num      | 8       | BEST12.    | BEST32.      | AE Severity                                                         |
| 21                             | AEHS              | Num      | 8       | BEST12.    | BEST32.      | AE Highest Score                                                    |
| 22                             | AEHSFU            | Num      | 8       | BEST12.    | BEST32.      | AE Highest Score Follow Up                                          |
| 23                             | AESER             | Char     | 3       | $3.        | $3.          | AE Seriousness                                                      |
| 24                             | AESERCRIT         | Char     | 28      | $28.       | $28.         | AE Seriousness Criteria                                             |
| 25                             | AEDEATH           | Char     | 29      | $29.       | $29.         | AE Death                                                            |
| 26                             | AEREL             | Char     | 16      | $16.       | $16.         | AE Relationship to IP                                               |
| 27                             | AEREPDT           | Num      | 8       | YYMMDD10.  | YYMMDD10.    | Anonymised AE Report Date (Number of Days after Study Day 1)        |
| 28                             | AEFUDT1           | Num      | 8       | YYMMDD10.  | YYMMDD10.    | Anonymised AE Follow Up Date 1 (Number of Days after Study Day 1)   |
| 29                             | AEFUDT2           | Num      | 8       | YYMMDD10.  | YYMMDD10.    | Anonymised AE Follow Up Date 2 (Number of Days after Study Day 1)   |
| 30                             | AEFUDT3           | Num      | 8       | YYMMDD10.  | YYMMDD10.    | Anonymised AE Follow Up Date 3 (Number of Days after Study Day 1)   |
| 31                             | OnsetHS           | Char     | 3       | $3.        | $3.          | Onset Highest Score                                                 |
| 32                             | AEWK1HS           | Char     | 3       | $3.        | $3.          | AE Week 1 Highest Score                                             |
| 33                             | AEWK2HS           | Char     | 3       | $3.        | $3.          | AE Week 2 Highest Score                                             |
| 34                             | AEWK3HS           | Num      | 8       | BEST12.    | BEST32.      | AE Week 3 Highest Score                                             |
| 35                             | AEWK4HS           | Num      | 8       | BEST12.    | BEST32.      | AE Week 4 Highest Score                                             |
| 36                             | AEWK5HS           | Num      | 8       | BEST12.    | BEST32.      | AE Week 5 Highest Score                                             |
| 37                             | AEWK6HS           | Num      | 8       | BEST12.    | BEST32.      | AE Week 6 Highest Score                                             |
| 38                             | AEWK7HS           | Num      | 8       | BEST12.    | BEST32.      | AE Week 7 Highest Score                                             |
| 39                             | AEWK8HS           | Num      | 8       | BEST12.    | BEST32.      | AE Week 8 Highest Score                                             |
| 40                             | AEWK9HS           | Num      | 8       | BEST12.    | BEST32.      | AE Week 9 Highest Score                                             |
| 41                             | AEWK10HS          | Num      | 8       | BEST12.    | BEST32.      | AE Week 10 Highest Score                                            |
| 42                             | AEWK11HS          | Num      | 8       | BEST12.    | BEST32.      | AE Week 11 Highest Score                                            |
| 43                             | AEWK12HS          | Num      | 8       | BEST12.    | BEST32.      | AE Week 12 Highest Score                                            |
| 44                             | AE\_ISR\_LYMPH    | Char     | 3       | $3.        | $3.          | AE\_ISR\_LYMPH                                                      |
| 45                             | AE\_ISR\_PAIN     | Char     | 3       | $3.        | $3.          | AE Injection Side Reaction Pain                                     |
| 46                             | AE\_ISR\_RED      | Char     | 3       | $3.        | $3.          | AE Injection Side Reaction Redness                                  |
| 47                             | AE\_ISR\_SWELLING | Char     | 3       | $3.        | $3.          | AE Injection Side Reaction Swelling                                 |
| 48                             | AE\_ISR\_CM       | Char     | 3       | $3.        | $3.          | AE Injection Side Reaction Concomitant Medication                   |
| 49                             | AE\_ISR\_ULCER    | Char     | 3       | $3.        | $3.          | AE Injection Side Reaction Ulcer                                    |
| 50                             | AESOC             | Char     | 69      | $69.       | $69.         | AE MedDRA System Organic Class                                      |
| 51                             | AESOCCD           | Num      | 8       | BEST12.    | BEST32.      | AE MedDRA System Organic Class Code                                 |

 

| **CM (Concomitant Medication) Domain** |              |          |         |            |              |                                                                                 |
| :------------------------------------- | ------------ | -------- | ------- | ---------- | ------------ | ------------------------------------------------------------------------------- |
| **#**                                  | **Variable** | **Type** | **Len** | **Format** | **Informat** | **Label**                                                                       |
| **1**                                  | STUDYID      | Char     | 18      |            |              |  Study ID                                                                       |
| **2**                                  | TRTGRP       | Char     | 200     | $GROUPS.   |              | Treatment Group                                                                 |
| **3**                                  | USUBJID      | Char     | 7       | $7.        | $7.          | Unique Participant ID                                                           |
| **4**                                  | VISITNAM     | Char     | 200     |            |              | Visit Name                                                                      |
| **5**                                  | CMSPID       | Char     | 1       |            |              | Concomitant Medication Sponsor ID                                               |
| **6**                                  | CMCAT        | Char     | 200     |            |              | Concomitant Medication Category                                                 |
| **7**                                  | CMTEST       | Char     | 112     |            |              | Concomitant Medication Test Question                                            |
| **8**                                  | CMORRES      | Char     | 1000    |            |              | Concomitant Medication Test Question Response                                   |
| **9**                                  | CMTRT        | Char     | 200     | $200.      | $11.         | Concomitant Medication Treatment                                                |
| **10**                                 | CMSTDT       | Num      | 8       | YYMMDD10.  | YYMMDD10.    | Anonymised Concomitant Medication Start Date (Number of Days after Study Day 1) |
| **11**                                 | CMENDT       | Num      | 8       | YYMMDD10.  |              | Anonymised Concomitant Medication End Date (Number of Days after Study Day 1)   |
| **12**                                 | CMSTATUS     | Char     | 16      | $16.       | $16.         | Concomitant Medication Status                                                   |

 

| **DM (Demography) Domain** |                  |          |         |            |              |                                                                 |
| :------------------------- | ---------------- | -------- | ------- | ---------- | ------------ | --------------------------------------------------------------- |
| **#**                      | **Variable**     | **Type** | **Len** | **Format** | **Informat** | **Label**                                                       |
| **1**                      | STUDYID          | Char     | 18      |            |              |  Study ID                                                       |
| **2**                      | TRTGRP           | Char     | 200     | $GROUPS.   |              | Treatment Group                                                 |
| **3**                      | USUBJID          | Char     | 7       | $7.        | $7.          | Unique Participant ID                                           |
| **4**                      | VISITNAM         | Char     | 21      |            |              | Visit Name                                                      |
| **5**                      | SEX              | Char     | 6       | $6.        | $6.          | Sex for Stratification                                          |
| **6**                      | Age              | Num      | 8       | 5.         |              | Anonymised Age (Categorised per Age Range)                      |
| **7**                      | RACE             | Char     | 9       | $9.        | $9.          | Race for Stratification                                         |
| **8**                      | education        | Char     | 8       | $8.        | $8.          | Highest Level of education?                                     |
| **9**                      | work\_hours      | Char     | 12      | $12.       | $12.         | Working Hours per Week (Including Overtime)                     |
| **10**                     | patients\_seen   | Char     | 13      | $13.       | $13.         | Number of Patients Seen /Interacting With per Day               |
| **11**                     | expect\_interact | Char     | 3       | $3.        | $3.          | Expected to Interact with Known COVID-19 Patients in Your Work? |

 

| **DS (Disposition) Domain** |              |          |         |            |              |                                                                |
| :-------------------------- | ------------ | -------- | ------- | ---------- | ------------ | -------------------------------------------------------------- |
| **#**                       | **Variable** | **Type** | **Len** | **Format** | **Informat** | **Label**                                                      |
| **1**                       | STUDYID      | Char     | 18      |            |              |  Study ID                                                      |
| **2**                       | TRTGRP       | Char     | 200     | $GROUPS.   |              | Treatment Group                                                |
| **3**                       | USUBJID      | Char     | 7       | $7.        | $7.          | Unique Participant ID                                          |
| **4**                       | VISITNAM     | Char     | 200     |            |              | Visit Name                                                     |
| **5**                       | DSSPID       | Char     | 1       |            |              | Disposition Sponsor ID                                         |
| **6**                       | DSTERM       | Char     | 200     |            |              | Disposition Term                                               |
| **7**                       | DSCAT        | Char     | 200     |            |              | Disposition Category                                           |
| **8**                       | DSYN         | Char     | 3       | $3.        | $3.          | Disposition Yes/No                                             |
| **9**                       | DSDT         | Num      | 8       | YYMMDDD10. | YYMMDD10.    | Anonymised Disposition Date (Number of Days after Study Day 1) |
| **10**                      | DSTM         | Num      | 8       | TOD5.      |              | Disposition Time                                               |
| **11**                      | DSREAS       | Char     | 200     | $554.      | $554.        | Disposition Reason                                             |
| **12**                      | DSTEST       | Char     | 200     |            |              | Disposition Test Question                                      |
| **13**                      | DSORRES      | Char     | 1000    |            |              | Disposition Test Response                                      |

 

| **EX (Exposure) Domain** |              |          |         |            |              |                        |
| :----------------------- | ------------ | -------- | ------- | ---------- | ------------ | ---------------------- |
| **#**                    | **Variable** | **Type** | **Len** | **Format** | **Informat** | **Label**              |
| **1**                    | STUDYID      | Char     | 18      |            |              | Study ID               |
| **2**                    | TRTGRP       | Char     | 200     | $GROUPS.   |              | Treatment Group        |
| **3**                    | USUBJID      | Char     | 7       | $7.        | $7.          | Unique Participant ID  |
| **4**                    | VISITNAM     | Char     | 200     |            |              | Visit Name             |
| **5**                    | EXDRUG       | Char     | 200     |            |              | Exposure Drug          |
| **6**                    | EXFORM       | Char     | 17      |            |              | Exposure Form          |
| **7**                    | EXROUTE      | Char     | 13      |            |              | Exposure Route         |
| **8**                    | EXDOSE       | Char     | 3       |            |              | Exposure Dose          |
| **9**                    | EXDOSEU      | Char     | 2       |            |              | Exposure Dose Unit     |
| **10**                   | EXFREQ       | Char     | 4       |            |              | Exposure Frequency     |
| **11**                   | EXTEST       | Char     | 72      |            |              | Exposure Test Question |
| **12**                   | EXORRES      | Char     | 119     |            |              | Exposure Test Response |

 

| **IE (Inclusion/Exclusion Criteria) Domain** |              |          |         |            |              |                                              |
| :------------------------------------------- | ------------ | -------- | ------- | ---------- | ------------ | -------------------------------------------- |
| **#**                                        | **Variable** | **Type** | **Len** | **Format** | **Informat** | **Label**                                    |
| **1**                                        | STUDYID      | Char     | 18      |            |              | Study ID                                     |
| **2**                                        | TRTGRP       | Char     | 200     | $GROUPS.   |              | Treatment Group                              |
| **3**                                        | USUBJID      | Char     | 7       | $7.        | $7.          | Unique Participant ID                        |
| **4**                                        | VISITNAM     | Char     | 21      |            |              | Visit Name                                   |
| **5**                                        | IECAT        | Char     | 200     |            |              | Inclusion/Exclusion Criteria:                |
| **6**                                        | IETESTCD     | Char     | 9       |            |              | Inclusion/Exclusion Criteria Test Code       |
| **7**                                        | IETEST       | Char     | 1000    |            |              | Inclusion/Exclusion Criteria Test Question:  |
| **8**                                        | IEORRES      | Char     | 3       |            |              | Inclusion/Exclusion Criteria Met?            |
| **9**                                        | IESTRESC     | Char     | 3       |            |              | All Inclusion and No Exclusion Criteria Met? |

 

| **LB (Laboratory Findings) Domain** |              |          |         |            |              |                          |
| :---------------------------------- | ------------ | -------- | ------- | ---------- | ------------ | ------------------------ |
| **#**                               | **Variable** | **Type** | **Len** | **Format** | **Informat** | **Label**                |
| **1**                               | STUDYID      | Char     | 18      |            |              | Study ID                 |
| **2**                               | TRTGRP       | Char     | 200     | $GROUPS.   |              | Treatment Group          |
| **3**                               | USUBJID      | Char     | 7       | $7.        | $7.          | Unique Participant ID    |
| **4**                               | VISITNAM     | Char     | 200     |            |              | Visit Name               |
| **5**                               | LBCAT        | Char     | 200     |            |              | Laboratory Category      |
| **6**                               | LBSCAT       | Char     | 200     |            |              | Laboratory Sub Category  |
| **7**                               | LBTEST       | Char     | 200     |            |              | Laboratory Test Question |
| **8**                               | LBYN         | Char     | 3       | $3.        | $3.          | Laboratory Yes/No        |
| **9**                               | LBORRES      | Char     | 200     | $8.        | $8.          | Laboratory Test Response |

 

| **MH (Medical History) Domain** |              |          |         |            |              |                                        |
| :------------------------------ | ------------ | -------- | ------- | ---------- | ------------ | -------------------------------------- |
| **#**                           | **Variable** | **Type** | **Len** | **Format** | **Informat** | **Label**                              |
| **1**                           | STUDYID      | Char     | 18      |            |              | Study ID                               |
| **2**                           | TRTGRP       | Char     | 200     | $GROUPS.   |              | Treatment Group                        |
| **3**                           | USUBJID      | Char     | 7       | $7.        | $7.          | Unique Participant ID                  |
| **4**                           | VISITNAM     | Char     | 200     |            |              | Visit Name                             |
| **5**                           | MHSPID       | Char     | 1       |            |              | Medical History Sponsor ID             |
| **6**                           | MHCAT        | Char     | 15      |            |              | Medical History Category               |
| **7**                           | MHSCAT       | Char     | 200     |            |              | Medical History Sub-Category           |
| **8**                           | MHTEST       | Char     | 200     |            |              | Medical History Test Question          |
| **9**                           | MHORRES      | Char     | 1000    | $200.      | $3.          | Medical History Test Response          |
| **10**                          | MHTERM       | Char     | 200     |            |              | Medical History Term                   |
| **11**                          | MHDECOD      | Char     | 200     | $53.       | $53.         | Medical History Standard Term          |
| **12**                          | MHONGO       | Char     | 3       | $3.        | $3.          | Medical History Ongoing?               |
| **13**                          | MHCM         | Char     | 3       | $3.        | $3.          | Medical History Concomitant Medication |

 

| **SV (Subject Visit) Domain** |              |          |         |            |              |                                                          |
| :---------------------------- | ------------ | -------- | ------- | ---------- | ------------ | -------------------------------------------------------- |
| **#**                         | **Variable** | **Type** | **Len** | **Format** | **Informat** | **Label**                                                |
| **1**                         | STUDYID      | Char     | 18      |            |              | Study ID                                                 |
| **2**                         | TRTGRP       | Char     | 200     | $GROUPS.   |              | Treatment Group                                          |
| **3**                         | USUBJID      | Char     | 7       | $7.        | $7.          | Unique Participant ID                                    |
| **4**                         | VISITNUM     | Num      | 8       | BEST12.    | BEST32.      | Visit Week Number                                        |
| **5**                         | VISITNAM     | Char     | 200     |            |              | Visit Name                                               |
| **6**                         | SVCAT        | Char     | 200     |            |              | Hospital Admission, Study Visit or Follow Up             |
| **7**                         | SVDT         | Num      | 8       | YYMMDDD10. | YYMMDD10.    | Anonymised Visit Date (Number of Days after Study Day 1) |
| **8**                         | HAYN         | Char     | 3       |            |              | Subject Admitted to Hospital                             |

 

| **VS (Vital Signs) Domain** |              |          |         |            |              |                                |
| :-------------------------- | ------------ | -------- | ------- | ---------- | ------------ | ------------------------------ |
| **#**                       | **Variable** | **Type** | **Len** | **Format** | **Informat** | **Label**                      |
| **1**                       | STUDYID      | Char     | 18      |            |              | Study ID                       |
| **2**                       | TRTGRP       | Char     | 200     | $GROUPS.   |              | Treatment Group                |
| **3**                       | USUBJID      | Char     | 7       | $7.        | $7.          | Unique Participant ID          |
| **4**                       | VISITNAM     | Char     | 200     |            |              | Visit Name                     |
| **5**                       | VSTEST       | Char     | 40      |            |              | Vital Signs Test Question      |
| **6**                       | VSORRES      | Char     | 170     |            |              | Vital Signs Test Response      |
| **7**                       | VSORRESU     | Char     | 200     |            |              | Vital Signs Test Response Unit |

 **Sharing/Access information**

More information regarding the TASK008-BCG CORONA study can be found at the following links:

[https://clinicaltrials.gov/study/NCT04379336](https://clinicaltrials.gov/study/NCT04379336)

Published results from the analysis of the TASK008-BCG CORONA SDTM datasets can be found in the following address on the DMJ:

[https://www.thelancet.com/journals/eclinm/article/PIIS2589-5370(22)00144-4/fulltext](https://www.thelancet.com/journals/eclinm/article/PIIS2589-5370\(22\)00144-4/fulltext)

**Code/Software**

The TASK008-BCG CORONA SDTM datasets was generated using SAS 9.4.
