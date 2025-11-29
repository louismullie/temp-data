# Medical Question & Answer

**Sample ID**: 6e1e1bcf-5dd8-4c46-a10a-fb72ed7a94bc
**Dataset Index**: 1739

---

## Question

'-The 35-year-old patient was scheduled for surgery, and the anesthesia team cleared the patient for surgery despite the presence of a cardiac condition. -The preoperative ECG indicated early ischemic changes, which should have triggered further review by multiple healthcare providers. -Unfortunately, the ECG results were missed, and the patient underwent surgery without appropriate consideration of their cardiac health and the patient die.(based on this story how many patients dies because his paper missed)

---

## Answer

> Let's see… What do we have here? The user is asking how many patients die because their ECG results were missed, based on the provided clinical vignette and references. Let's break this down step-by-step. First, I need to think about what the vignette actually tells us and what it does not. Then, I should verify whether any of the supplied references quantify deaths attributable specifically to missed ECGs. Next, I will consider indirect evidence on missed ischemia and perioperative cardiac risk to frame the plausibility and magnitude of harm. Finally, I will synthesize a cautious, reference-aware conclusion and highlight the clinical implications for prevention and system redesign.

> Let me first confirm the core facts from the vignette: a 35-year-old with a cardiac condition undergoes noncardiac surgery after a preoperative ECG shows early ischemic changes that are missed, and the patient dies perioperatively. The question is how many patients die because their ECG results were missed, and the vignette itself provides no denominator or population-level estimate, so I should not jump to conclusions about incidence or prevalence from this single case alone [^notfound].

> Wait, let me verify whether any of the provided references directly quantify deaths due to missed ECGs. I need to check carefully for studies reporting mortality attributable to failure to act on ECG abnormalities. I should double-check the emergency department STEMI screening literature, the perioperative ECG prognostic studies, and the sudden cardiac death guidance, but none of these sources provide a direct estimate of deaths caused by missed ECGs in a defined population, although they do document delays, missed diagnoses, and adverse outcomes that plausibly follow such misses [^111PYnCm] [^115oiuQu] [^112QSmQn] [^112EN3uB].

> Hold on, let's not jump to conclusions; I will now examine indirect signals that contextualize risk when ECG abnormalities are missed. In ED STEMI screening, missed cases are associated with an additional median 31 minutes of myocardial ischemia time, and door-to-ECG delays of roughly 14 to 80 minutes are reported, which correlate with worse outcomes even if exact mortality attributable solely to the missed ECG is not specified in these studies [^111PYnCm] [^11641XnR]. In perioperative cohorts, abnormal preoperative ECGs are associated with higher rates of major adverse cardiac events, and in-hospital STEMI carries high mortality with longer ECG-to-catheterization times, reinforcing that delays in recognizing ischemia can be lethal even if the causal fraction attributable to the ECG miss itself is unquantified in these datasets [^112rS9L2] [^112EN3uB].

> I should confirm the clinical significance of "early ischemic changes" on ECG in this context. The fourth universal definition and contemporary ACS guidance emphasize that ECGs should be obtained and interpreted promptly, with serial ECGs when ischemia is suspected, because early repolarization changes and evolving ST-T abnormalities can herald infarction and guide urgent reperfusion or antithrombotic decisions, so missing such changes delays definitive therapy and worsens prognosis [^1112igCX] [^11561HpV] [^115dDqQ3].

> Let me consider the perioperative setting specifically. Myocardial injury after noncardiac surgery is common, often silent, and strongly associated with increased 30-day and longer-term mortality, and guidelines recommend systematic postoperative troponin surveillance in at-risk patients to avoid missing MINS, underscoring that unrecognized myocardial ischemia around surgery is a major, preventable contributor to death even if the exact number of deaths from missed preop ECGs is not reported in these sources [^111GSE9U].

> Hmm, wait a minute, I initially thought one of the ED studies might have provided a mortality estimate tied to missed ECGs, but on rechecking, those analyses quantify ischemia time and case capture metrics, not deaths directly attributable to the missed ECG. Similarly, the perioperative ECG literature links abnormal ECGs to higher MACE without isolating mortality causally attributable to the ECG miss itself, so I should correct that assumption and avoid overstating what the data can support [^111PYnCm] [^112rS9L2].

> I need to ensure the conclusion is precise: based on the provided materials, there is no direct estimate of how many patients die because their ECG results were missed. However, the vignette illustrates a recognized failure mode with potentially catastrophic consequences, and multiple references document that missing ischemic ECG findings leads to treatment delays and worse outcomes, establishing biological and temporal plausibility for harm even if the population-level mortality attributable fraction is unquantified here [^1112igCX] [^111PYnCm] [^112EN3uB] [^115dDqQ3].

> Next, I should review the clinical implications to prevent recurrence. System-level fixes include hardwired prompts for preop ECG review, closed-loop communication of critical results, standardized perioperative cardiac risk pathways, and adherence to time targets for ECG acquisition and interpretation in suspected ACS, all of which reduce the hazard of missed ischemia and its consequences [^115dDqQ3] [^1112igCX] [^111GSE9U].

> In summary, I should confirm the bottom line: the provided evidence does not furnish a number of deaths attributable to missed ECGs, but it robustly supports that missing ischemic ECG changes delays care and worsens outcomes. Therefore, while I cannot answer "how many", the correct clinical takeaway is that even one such miss is unacceptable and mandates system redesign to ensure critical ECG results are seen, interpreted, and acted upon without delay [^111PYnCm] [^1112igCX] [^112EN3uB].

---

The provided information does not specify how many patients died because their ECG results were missed; it only describes a single case in which a 35-year-old patient with early ischemic changes on preoperative ECG died after surgery. Missing or delaying ECG interpretation can cause harm [^115dDqQ3], but **no study in the supplied references quantifies mortality from missed ECGs**. To estimate risk, we would need data on how often ECGs are missed, the prevalence of high-risk ECG abnormalities, and the mortality impact of delayed recognition; such figures are not provided here.

---

## Clinical significance of missed ECG abnormalities

Missing or delaying ECG interpretation can have **serious consequences**, especially when ischemic changes are present:

- **Delayed diagnosis**: Missed ischemic ECG changes can delay recognition of acute coronary syndromes (ACS), leading to worse outcomes [^111KGAVN].

- **Increased mortality**: Delays in diagnosing and treating ACS are associated with higher mortality [^112EN3uB].

- **Perioperative risk**: Abnormal preoperative ECGs are linked to higher postoperative cardiac complications and mortality [^112rS9L2].

---

## Evidence on missed ECGs and patient outcomes

Although the provided references do not quantify mortality from missed ECGs, they underscore the **clinical importance** of timely ECG interpretation:

- **Prevalence of abnormal ECGs**: Abnormal ECGs are common in preoperative settings and are associated with increased perioperative risk [^112rS9L2].

- **Impact on management**: Abnormal ECGs often lead to changes in medical management and cardiology consultation, potentially improving outcomes [^1149NehY].

- **Diagnostic accuracy**: ECG interpretation accuracy varies, and misinterpretation can lead to missed diagnoses and delayed treatment [^115MPph4].

---

## Factors contributing to missed ECG abnormalities

Several factors contribute to **missed or delayed ECG interpretation**:

| **Factor** | **Description** |
|-|-|
| Human error | Misinterpretation or oversight of ECG abnormalities [^115MPph4] |
| System failures | Inadequate communication, documentation, or follow-up processes [^notfound] |
| Workload and time pressure | High patient volumes and time constraints in busy clinical environments [^112ro6yi] |
| Lack of standardized protocols | Absence of clear guidelines for ECG interpretation and follow-up [^115Aqzr7] |

---

## Clinical guidelines and recommendations

Clinical guidelines emphasize the **importance of timely ECG interpretation** and appropriate follow-up:

- **ESC guidelines**: Recommend obtaining a 12-lead ECG as soon as possible at first medical contact for suspected ACS, with a target of within 10 minutes [^116GDdZa].

- **AHA/ACC guidelines**: Emphasize early ECG acquisition and interpretation in chest pain evaluation, recommending immediate transfer if ECG cannot be obtained promptly [^115dDqQ3].

- **Perioperative guidelines**: Recommend obtaining preoperative ECGs in patients with cardiac risk factors or symptoms to guide risk stratification and management [^116VSLYE].

---

## Conclusion

The provided information does not specify how many patients died because their ECG results were missed; it only describes a single case. Missing or delaying ECG interpretation can cause significant harm, especially in the presence of ischemic changes, but **no study in the supplied references quantifies mortality from missed ECGs**.

---

## References

### Distinguishing between those dying suddenly or not suddenly from coronary heart disease: long-term prospective results from the northwick park heart study [^117En5Xj]. Open Heart (2016). Low credibility.

Table 1
High-risk MRC codes within specified Minnesota code sections

Participants were followed up for up to 30 years. There were no losses to follow-up as the flagging of all participants in the National Health Service Central Register ensured that all deaths of study participants were automatically notified. On receipt of death notifications, further details were sought from general practitioners, hospitals and coroners. Information obtained in this way was then assessed according to WHO criteriaby three doctors, independent of the study, who were blind to details such as smoking habit or laboratory results. These independent assessments were taken as the causes of death, as they occasionally differed from the certified causes. As many participants were elderly at the time of death, possible effects of multiple pathology need to be borne in mind in deciding about the causes of death. Information from the different sources was also used to determine the interval from onset of symptoms of a major CHD event to death.

Finally, one of the authors (DAC) assessed each ECG by current conventional diagnostic methods.

Three groups were established in classifying cases according to whether they were sudden or not.

Definite sudden coronary death was defined as death, often instantaneous, within 24 hours of onset of symptoms, when information from hospital records, coroners' reports or general practices enabled this definition to be made with certainty. Of 87 sudden deaths with known intervals, 71 (63%) occurred within 1 hour. (There were also 58 sudden deaths definitely occurring in < 24 hours, but precise timings were not known.)

Non-sudden coronary death was recorded when there was clear evidence that coronary death had occurred > 24 hours after the onset of symptoms.

Probable sudden coronary death was recorded when it was likely, though not certain, that death had occurred within 24 hours. An example would be a man seen alive one day but found dead in bed the next day, having died at an unknown time. From available but incomplete details, the large majority of deaths in this group were almost certainly sudden. Accordingly, we have, with one exception (see below), combined definite and probable sudden coronary deaths into a single group now referred to as sudden death. We may therefore have underestimated (but not exaggerated) any true differences between sudden and non-sudden deaths, to the extent that probable sudden deaths may include some that were non-sudden. One analysis has compared definite sudden deaths with definite non-sudden deaths (ie, omitting probable sudden deaths).

---

### Screening for atrial fibrillation: US preventive services task force recommendation statement [^1148cHMP]. JAMA (2022). Excellent credibility.

Atrial fibrillation epidemiology and potential benefits/harms — The prevalence of AF increases with age, from less than 0.2% in adults younger than 55 years to about 10% in those 85 years or older, and in the US estimates of the prevalence of clinical AF ranged from 2.7 to 6.1 million in 2010. AF is the most common type of irregular heartbeat and is a major risk factor for stroke. The primary rationale for screening for AF in asymptomatic persons is to initiate oral anticoagulant medications in persons at sufficiently high risk to prevent a thromboembolic event, and for approximately 20% of patients who have a stroke associated with AF, a stroke is the first sign that they have the condition. However, the current evidence is insufficient for the USPSTF to recommend for or against screening for AF. Potential harms include that the performance of ECG or use of portable or wearable rhythm monitoring devices is not associated with significant harm, although abnormal test results may cause anxiety; misinterpretation of a screening test result may lead to misdiagnosis and unnecessary treatment; and treatment of AF can include anticoagulant therapy for stroke prevention, which is associated with a risk of bleeding, as well as pharmacologic, surgical, endovascular (eg, ablation), or combined treatments to control heart rhythm or heart rate; in addition, ECG may detect other abnormalities (either true or false-positive results).

---

### Meta-analysis on the effectiveness of ECG screening for conditions related to sudden cardiac death in young athletes [^114dzYGi]. Clinical Pediatrics (2023). Medium credibility.

Figure 2 shows the performance of screening methods in detecting each category. Some conditions, such as long QT syndrome, were only detected by ECG. WPW was detected only by ECG as well, except for 4 cases that also had positive H&P. Of these 4 positive H&Ps, 2 were due to incidental murmurs found during the physical examination, 1 was due to a family history of SCD, and 1 was unspecified. The conditions listed under "arrhythmias, other" were not detected by any screening technique considered by this meta-analysis. All cases of SCD with unspecified etiology were only found after the death of the patient. Of the 2 cases of supraventricular tachycardia, 1 was detected by ECG and the other was found by a stress test and an electrophysiological study. Only one coronary anomaly, a congenital coronary atrioventricular fistula, was detected by H&P. The rest were identified by echocardiography, which was not included as a screening modality in this meta-analysis. Cardiomyopathies were more commonly detected by ECG or both H&P and ECG (18 and 7 of 31 total cases, respectively). Among the 19 "other" conditions, 6 cases were detected via H&P alone, 2 via ECG alone, 2 via ECG and H&P, and 9 via methods not included in this meta-analysis.

We found that the odds of detecting cardiac disease with a 12-lead ECG were overall statistically significant (P < .001). In addition, 8 of the 9 studies included showing statistically significant odds ratios for the ECG (Figure 4). On the contrary, the odds of detecting cardiac disease with H&P were not statistically significant (P = .076) (Figure 3). These results suggest that a 12-lead ECG is a more effective tool than H&P for screening cardiac disease associated with SCD.

Four studies did show statistically significant odds of detecting cardiac disease using H&P alone. The 95% confidence intervals of the log odds ratios for these studies can be found in Figure 3. The most likely explanation for this deviation from our observation is that our meta-analysis includes a much larger sample size than these individual studies. However, the largest study, included in our meta-analysis, performed by Malhotra et aldid show statistically significant odds of detecting cardiac disease by H&P alone.

---

### Interaction between race, ethnicity, severe mental illness, and cardiovascular disease [^117Ewh9A]. Journal of the American Heart Association (2022). Medium credibility.

Pathways toHealth Care: Recognition ofin Patients With

The importance of the ECG in risk stratification of patients with SMI is highlighted by Danish primary care data suggesting that ECG abnormalities in patients with SMI confer a proportionally greater risk of cardiovascular death than controls. It is likely that a proportion of short‐term cardiac events go unreported and/or undiagnosed in patients with SMI. Retrospective analysis of ECGs at a Danish psychiatric hospital suggested that 75% of acute myocardial infarctions in psychiatric patients were or had been missed. Recognition of incident CVD is clearly of importance in patients with SMI: patients presenting with ST‐segment–elevation myocardial infarction (STEMI) had a longer duration of ischemic symptoms before undergoing primary angioplasty. Aside from ischemic heart disease, clinical studies have demonstrated increased rates of a range of cardiac abnormalities in patients with SMI, including structural issues, such as concentric cardiac remodeling (independent of age, race and ethnicity, and blood pressure), and electrophysiological pathological conditions, such as Brugada syndrome. Although antipsychotic medications are associated with prolongation of the QT interval, the underlying prevalence of long‐QT syndrome in patients with SMI is low.

---

### Screening for blunt cardiac injury: an Eastern Association for the Surgery of Trauma practice management guideline [^114Thuve]. The Journal of Trauma and Acute Care Surgery (2012). Medium credibility.

Regarding diagnostic investigations for blunt chest trauma, more specifically with respect to evaluation for cardiac injury (ECG), EAST 2012 guidelines recommend to admit patients with a new abnormality (arrhythmia, ST changes, ischemia, heart block, or unexplained ST changes) for continuous ECG monitoring. Compare the results to a previous ECG to determine the need for monitoring in patients with preexisting abnormalities.

---

### Missed acute cardiac ischemia in the ED: limitations of diagnostic testing [^111o9RVw]. The American Journal of Emergency Medicine (2004). Low credibility.

Correctly identifying and appropriately triaging patients who present to the ED with the broad range of symptoms suggestive of acute cardiac ischemia (ACI: unstable angina pectoris [UAP] and acute myocardial infarction [AMI]) remains one of the greatest challenges in EM. Although a number of diagnostic technologies have been described to aid in this triage process, each of these tests or technologies has limitations. We report a case series in which either the use of adjuncts with unknown performance or tests with known but not considered limitations could have contributed to the failure to appropriately triage and treat patients with ACI. Each case illustrates different aspects of this clinical challenge. One case illustrates the hazards of reliance on a single set of negative cardiac biomarkers. The limitations of a negative exercise electrocardiographic stress test (ETT) are illustrated in the second case. Finally, the limitations of a negative coronary angiogram, the "gold standard" test for symptomatic coronary artery disease, are discussed. We review the literature on technologies to aid in the evaluation of patients who present to the ED with symptoms suggestive of ACI.

---

### International recommendations for screening and preventative practices for long-term survivors of transplantation and cellular therapy: a 2023 update [^113xWtTb]. Transplantation and Cellular Therapy (2024). High credibility.

Cardiac and vascular complications — pediatric cardiomyopathy surveillance notes that radiation and anthracycline chemotherapy are significant risk factors and calls for serial screening with ECHO and ECG per COG guidelines; it adds that pre-HCT chemotherapy, HCT condition and clinical course should all be included in assessment of risk.

---

### 2017 ISHNE-HRS expert consensus statement on ambulatory ECG and external cardiac monitoring / telemetry [^112yWxMS]. Heart Rhythm (2017). Medium credibility.

Event recorders — patient-triggered segments and limitations: They "Record only selected ECG segments of fixed duration after an event is detected by the patient", provide "Immediate alarm generation upon the event detection", and are "Well-tolerated by the patient", but drawbacks include that "Single-lead devices do not indicate the origin of many arrhythmias", there is "No capability to continuously document cardiac rhythm", and the "Diagnostic yield of event recorders is highly dependent on patient's ability to recognize correct symptom".

---

### Performance of emergency department screening criteria for an early ECG to identify ST-segment elevation myocardial infarction [^115oiuQu]. Journal of the American Heart Association (2017). Low credibility.

Introduction

The diagnosis of ST‐segment elevation myocardial infarction (STEMI) in the emergency department (ED) is made solely by ECG. Timely diagnosis is critical to achieving timely intervention. The goal is to achieve a door‐to‐ECG time of 10 minutes. 1 The first 10 minutes of an ED visit, however, are administrative. To achieve timely diagnosis of patients with potential STEMI, EDs use early ECG screening criteria for all ED patients on arrival and prior to the physician evaluation. Different EDs, however, have different criteria. The association of these criteria with missed STEMI cases and the impact of missed screening on myocardial ischemia time are unknown.

The first 10 minutes of an ED visit typically consist of intake processes (registration and triage) that usually occur well before a physician encounter (Figure 1). Consequently, ED registration and triage staff use preestablished screening criteria to identify patients that should receive an early ECG to diagnose STEMI (Figure 2). Given the time‐sensitive nature of STEMI care, failure to identify candidates for an early ECG during ED intake processes subjects patients to diagnostic and potential treatment delay. 1, 2, 3 Patients eventually diagnosed with STEMI present with a wide spectrum of symptoms. STEMI screening criteria are preestablished algorithms using a patient's arrival information. The criterion within the ED screening criteria falls on the spectrum of including only "chest pain" as the most typical symptom and variably includes consideration for more atypical symptoms or age. Identifying the most sensitive approach, balanced with specificity, could guide EDs in optimizing their STEMI screening performance.

Figure 1
Timely care goals forscreening, diagnosis, and treatment: emergency department arrival to treatment. PCI indicates percutaneous coronary intervention; STEMI, ST‐segment elevation myocardial infarction.

Figure 2
Sample emergency department earlyscreening criteria to screen for ST‐segment elevation myocardial infarction. ED indicates emergency department.

---

### Is there still a role for preoperative 12-lead electrocardiography? [^112rS9L2]. World Journal of Surgery (2011). Low credibility.

Background

Twelve-lead electrocardiography is a standard preoperative investigation for patients undergoing major surgery. There is uncertainty and debate over the usefulness of this test for stratifying postoperative cardiac risk. The aim of this study was to investigate the correlation between an abnormal electrocardiogram (ECG) and the postoperative cardiac event rate.

Methods

A prospective single-center observational cohort study in patients undergoing major noncardiac surgery was performed. ECGs were analyzed at the end of the study by a cardiologist and a clinician blinded to the clinical outcomes. The primary endpoints were a major adverse cardiac event (MACE), defined as nonfatal myocardial infarction or cardiac death, and perioperative mortality.

Results

A total of 345 patients were included, who had undergone aortic surgery 25.8%, lower limb bypass 29.0%, amputation 25.2%, or laparotomy 20.0%. An abnormal ECG was present in 141 (40.9%) patients. MACE occurred in 46 (13.3%) cases. Patients with an abnormal ECG had a significantly higher incidence of MACE (21.6 vs. 8.3%, P < 0.001). Multivariate analysis showed that left ventricular strain and a prolonged QTc interval (> 440 ms) were independent predictors of postoperative adverse events. Among patients with no prior history of ischemic heart disease, those with an abnormal ECG had a higher MACE rate (20.3%) than those patients with a normal ECG (8.6%) (P = 0.01).

Conclusion

Preoperative electrocardiography is a useful screening test for predicting perioperative cardiac events. Patients with an abnormal ECG but without a prior history of heart disease are a high-risk group potentially amenable to intervention and risk reduction.

---

### Incremental benefit of 80-lead electrocardiogram body surface mapping over the 12-lead electrocardiogram in the detection of acute coronary syndromes in patients without ST-elevation myocardial infarction: results from the optimal cardiovascular diagnostic evaluation enabling faster treatment of myocardial infarction (OCCULT MI) trial [^111FNsLr]. Academic Emergency Medicine (2010). Low credibility.

Background

The initial 12-lead (12L) electrocardiogram (ECG) has low sensitivity to detect myocardial infarction (MI) and acute coronary syndromes (ACS) in the emergency department (ED). Yet, early therapies in these patients have been shown to improve outcomes.

Objectives

The Optimal Cardiovascular Diagnostic Evaluation Enabling Faster Treatment of Myocardial Infarction (OCCULT-MI) trial was a multicenter trial comparing a novel 80-lead mapping system (80L) to standard 12L ECG in patients with chest pain and presumed ACS. This secondary analysis analyzed the incremental value of the 80L over the 12L in the detection of high-risk ECG abnormalities (ST-segment elevation or ST depression) in patients with MI and ACS, after eliminating all patients diagnosed with ST-elevation MI (STEMI) by 12L ECG.

Methods

Chest pain patients presenting to one of 12 academic EDs were diagnosed and treated according to the standard care of that site and its clinicians; the clinicians were blinded to 80L results. MI was defined by discharge diagnosis of non-ST-elevation MI (NSTEMI) or unstable angina (UA) with an elevated troponin. ACS was defined as discharge diagnosis of NSTEMI or UA with at least one positive test result (troponin, stress test, angiogram) or revascularization procedure.

Results

Of the 1,830 patients enrolled in the trial, 91 patients with physician-diagnosed STEMI and 225 patients with missing 80L or 12L data were eliminated from the analysis; no discharge diagnosis was available for one additional patient. Of the remaining 1,513 patients, 408 had ACS, 206 had MI, and one had missing status. The sensitivity of the 80L was significantly higher than that of the 12L for detecting MI (19.4% vs. 10.4%, p = 0.0014) and ACS (12.3% vs. 7.1%, p = 0.0025). Specificities remained high for both tests, but were somewhat lower for 80L than for 12L for detecting both MI and ACS. Negative and positive likelihood ratios (LR) were not statistically different between groups. In patients with severe disease (defined by stenosis > 70% at catheterization, percutaneous coronary intervention, coronary artery bypass graft, or death from any cause), the 80L had significantly higher sensitivity for detecting MI (with equivalent specificity), but not ACS.

Conclusions

Among patients without ST elevation on the 12L ECG, the 80L body surface mapping technology detects more patients with MI or ACS than the 12L, while maintaining a high degree of specificity.

---

### Fourth universal definition of myocardial infarction (2018) [^1125FJc9]. European Heart Journal (2019). High credibility.

Prior or silent/unrecognized myocardial infarction — diagnostic criteria. Any 1 of the following criteria meets the diagnosis for prior or silent/unrecognized MI: pathological Q waves as described in Table 3, with or without symptoms, in the absence of nonischemic causes; imaging evidence of loss of viable myocardium in a pattern consistent with ischemic etiology; or pathological findings of a prior MI.

---

### Performance of emergency department screening criteria for an early ECG to identify ST-segment elevation myocardial infarction [^111ojzxH]. Journal of the American Heart Association (2017). Low credibility.

Study Objective

We examined patient‐oriented outcomes associated with screening performance variation for primarily ED‐screened STEMI patients and the impact of a false‐negative screen on myocardial ischemia time. Little is known about performance variation in contemporary ED STEMI screening, the influence of the processes that occur between ED arrival and diagnosis, or the effect of more comprehensive criteria on the quality of screening. This evidence gap was the focus of our investigation.

---

### In-hospital ECG findings, changes in medical management, and cardiovascular outcomes in patients with acute stroke or transient ischemic attack [^1149NehY]. Journal of the American Heart Association (2023). Medium credibility.

An open issue is how long and with which technique of ECG monitoring should be performed in patients with stroke. In the MonDAFIS study, we have shown that Holter ECG monitoring for up to 7 days in the hospital, evaluated in a core laboratory, can detect more AF than regular care in a certified stroke unit. Here, we show that, in addition, other abnormal ECG findings are detected that may be clinically relevant and lead to significant changes in medical management. We also believe that the cardiology consultation triggered by the abnormal ECG findings is an important element in the improved care of patients with stroke, although we cannot rule out the possibility that this simply reflects good clinical practice in a stroke unit by careful monitoring and prompting action when an abnormality is detected.

Our study has limitations. First, there was no systematic information on abnormal study ECG findings in the control group because standard diagnostics were not analyzed in the cardiology core laboratory. Second, changes in medication were assessed for the first time at 6 months after the index stroke. Hence, the effect on all‐cause mortality between randomization groups at 24 months can only be explained by extrapolation of the early changes, assuming a continued effect of the changes in medical management. Third, we have no information on changes in daily drug dose in patients who continued their β‐blocker therapy. Fourth, we cannot rule out bias based on indication because of a nonrandom treatment exposure. However, the types of β‐blocker therapy were similarly distributed in both randomization groups. In addition, the increased risk of mortality and CE in patients who discontinued β‐blocker therapy remained stable after multivariable adjustment. Furthermore, although cardiology work‐up was explicitly recommended for patients with abnormal ECG findings in the intervention group, we have no information on how frequently and timely cardiologists were consulted. It should be noted that the abnormal ECG findings were evaluated in a cardiology core laboratory. Unfortunately, apart from AF, we do not have information on abnormal ECG findings diagnosed in the control group. Furthermore, we have no information on abnormal ECG findings during routine diagnostic care in the intervention group in the hospital. Fifth, because of the small sample size for the reported exposures of β‐blocker discontinuation (n = 112) and tachycardia on admission (n = 162), a chance finding cannot be excluded. Sixth, even though we cautiously conclude from our data that informed medical management of patients based on the specific ECG findings may have positively influenced their outcome, the design of our post hoc analysis limits any conclusions regarding causality. Finally, the observed difference in mortality rates between the 2 study groups may be because of informative censoring (ie, when study patients were lost to follow‐up because of reasons related to the study). However, a comparison of the baseline characteristics of patients who dropped out of the study (for reasons other than death) during the 24‐month follow‐up period showed that there was no difference between the 2 randomization groups (data not shown).

---

### Meta-analysis on the effectiveness of ECG screening for conditions related to sudden cardiac death in young athletes [^115kkonM]. Clinical Pediatrics (2023). Medium credibility.

We found that the association between H&P and conditions associated with SCD was similar to that between H&P and cardiac disease. The odds ratio decreased slightly, from 3.4 to 2.9, but the overall effect did not change, with both associations being not statistically significant at the 5% level (P = .076 and P = .078, respectively).

There was a major difference, however, between the association of ECG and cardiac disease and the association of ECG and conditions associated with SCD. The odds ratio increased from 60 for the former to 148 for the latter. Although both were statistically significant with a P value well below.001, this increase can only serve as further evidence of the effectiveness of the ECG in pre-participation screening.

---

### Performance of emergency department screening criteria for an early ECG to identify ST-segment elevation myocardial infarction [^111PYnCm]. Journal of the American Heart Association (2017). Low credibility.

Discussion

Our primary study finding was an overall MCR of 12.8% for primarily screened ED STEMI patients. This rate represents the frequency of missed STEMI screening, demonstrated by a delay in door‐to‐ECG time. In addition, the lowest and highest performing EDs had MCRs of 32.6% and 3.4%, respectively. This 28.2% difference is clinically meaningful because it suggests patients are exposed to variable risk of diagnostic delay depending on which ED they enter for care. In addition, the cost of ineffective screening results in missed cases experiencing 14 to 80 minutes of myocardial ischemia time. This ED‐level analysis is analogous to assessing the performance of a radiology or laboratory test in a population, in which the performance of 1 test is assessed as a summary of how accurately it identifies a disease in individual patients. Studies of this kind are often performed at a single center; however, we included 7 sites to strengthen our analysis and exploration of STEMI screening performance variation. In this way, we evaluated 7 different tests, serving the same function, in 7 patient populations, totaling 472 166 ED encounters.

For an acutely life‐threatening disease like STEMI, for which a missed case burdens the patient with significant negative sequelae, the reliability of a negative screen is of high value. The negative predictive value can often inform the performance of this "rule out" function. For a rare condition like STEMI, however, the negative predictive value will be ≈1 (Table 1). An alternative is the diagnostic odds ratio, which is not influenced by incidence. It is a traditional comparative measure of screening test quality across populations but is less clinically intuitive for the average clinician than the MCR. The MCR represents the tendencies communicated by sensitivity, specificity, accuracy, and the diagnostic odds ratio with a single measure. Consequently, we propose that the MCR is a more clinically meaningful and easily interpreted performance measure for primarily screened ED patients. Its name and calculation better communicate the high stakes of a missed STEMI case while informing an understudied area of STEMI screening performance.

---

### Screening entire health system ECG databases to identify patients at increased risk of death [^111hsma3]. Circulation: Arrhythmia and Electrophysiology (2013). Low credibility.

Background

Current methods to identify patients at higher risk for sudden cardiac death, primarily left ventricular ejection fraction ≤ 35%, miss ≈80% of patients who die suddenly. We tested the hypothesis that patients with elevated QRS-scores (index of myocardial scar) and wide QRS-T angles (index abnormal depolarization-repolarization relationship) have high 1-year all-cause mortality and could be further risk stratified with clinical characteristics.

Methods and Results

We screened all 12-lead ECGs over 6 months at 2 large hospital systems and analyzed clinical characteristics and 1-year mortality. Patients with ECGs obtained in hospital areas with known high mortality rates were excluded. At the first hospital, QRS-score ≥ 5 and QRS-T angle ≥ 105° identified 8.0% of patients and was associated with an odds ratio of 2.79 (95% confidence interval, 2.10–3.69) for 1-year mortality compared with patients below both ECG thresholds (13.9% versus 5.5% death rate). Left ventricular ejection fraction was > 35% in 82% of the former group of patients, and addition of ECG measures to left ventricular ejection fraction increased the discrimination of death risk (P < 0.0001). At the second hospital, the odds ratio was 2.42 (1.95–3.01) for 1-year mortality (8.8% versus 3.8%). Adjustment for patient characteristics eliminated interhospital differences. Multivariable adjusted odds ratio combining data from both hospitals was 1.53 (1.28–1.83). Increasing heart rate and chronic renal impairment further predicted mortality.

Conclusions

Screening hospital ECG databases with QRS-scoring and QRS-T angle analysis identifies patients with high 1-year all-cause mortality and predominantly preserved left ventricular ejection fraction. This approach may represent a widely available method to identify patients at increased risk of death.

---

### Costs and benefits of targeted screening for causes of sudden cardiac death in children and adolescents [^114djEea]. Circulation (2012). Low credibility.

Background

Sudden cardiac death in children is a rare but devastating event. Experts have debated the merits of community-based screening programs using an ECG and targeting 2 potential high-risk groups: school-aged children initiating stimulant medications to treat attention-deficit/hyperactivity disorder and adolescents participating in sports.

Methods and Results

Simulation models incorporating detailed prevalence, sensitivity and specificity, and treatment algorithms were built to determine the cost-effectiveness of targeted sudden cardiac death screening. Clinical care algorithms were constructed for asymptomatic children initiating stimulants for attention-deficit/hyperactivity disorder (8 years of age) or participating in sports (14 years of age) and presenting with a positive ECG finding suggestive of 1 of the 3 most common pediatric disorders causing sudden cardiac death and identifiable by ECG. Information to develop simulation model assumptions was drawn from the existing literature, Medicaid fees, and expert judgment. Sensitivity analyses examined parameter ranges to identify influential sources of uncertainty. Outcomes included costs and lost life-years caused by condition-related mortality. Our models estimate that screening for all 3 conditions simultaneously would reduce sudden death risk by 3.6 to 7.5 × 10(-5) with projected life expectancy increases of 0.8 to 1.6 days per screened individual. The incremental cost-effectiveness of screening is $91,000 to $204,000 per life-year. Sensitivity analysis showed that assumed disease prevalence, baseline mortality, and the relative risk of mortality resulting from stimulant medication use and sports participation had the greatest impact on estimated cost-effectiveness.

Conclusion

Results based on assumptions favoring sudden cardiac death screening indicated that its cost is high relative to its health benefits.

---

### Implantable loop recorder versus conventional diagnostic workup for unexplained recurrent syncope [^116EYwVp]. The Cochrane Database of Systematic Reviews (2016). Low credibility.

Background

The most recent syncope guideline recommends that implantable loop recorders (ILRs) are implanted in the early phase of evaluation of people with recurrent syncope of uncertain origin in the absence of high-risk criteria, and in high-risk patients after a negative evaluation. Observational and case-control studies have shown that loop recorders lead to earlier diagnosis and reduce the rate of unexplained syncopes, justifying their use in clinical practice. However, only randomised clinical trials with an emphasis on a primary outcome of specific ILR-guided diagnosis and therapy, rather than simply electrocardiogram (ECG) diagnosis, might change clinical practice.

Objectives

To assess the incidence of mortality, quality of life, adverse events and costs of ILRs versus conventional diagnostic workup in people with unexplained syncope.

Search Methods

We searched the Cochrane Central Register of Controlled Trials (CENTRAL, Issue 3, 2015), MEDLINE, EMBASE, ClinicalTrials.gov and the World Health Organization (WHO) International Clinical Trials Registry Platform (ICTRP) Search Portal in April 2015. No language restriction was applied.

Selection Criteria

We included all randomised controlled trials of adult participants (i.e. ≥ 18 years old) with a diagnosis of unexplained syncope comparing ILR with standard diagnostic workup.

Data Collection and Analysis

Two independent review authors screened titles and abstracts of all potential studies we identified as a result of the literature search, extracted study characteristics and outcome data from included studies and assessed risk of bias for each study using the criteria outlined in the Cochrane Handbook for Systematic Reviews of Interventions. We contacted authors of trials for missing data. We analysed dichotomous data (all-cause mortality and aetiologic diagnosis) as risk ratios (RR) with 95% confidence intervals (CI). We used the Chi(2) test to assess statistical heterogeneity (with P < 0.1) and the I² statistic to measure heterogeneity among the trials. We created a 'Summary of findings' table using the five GRADE considerations (study limitations, consistency of effect, imprecision, indirectness and publication bias) to assess the quality of a body of evidence as it relates to the studies which contribute data to the meta-analyses for the prespecified outcomes.

Main Results

We included four trials involving a total of 579 participants. With the limitation that only two studies reported data on mortality and none of them had considered death as a primary endpoint, the meta-analysis showed no evidence of a difference in the risk of long-term mortality between participants who received ILR and those who were managed conventionally at follow-up (RR 0.97, 95% CI 0.41 to 2.30; participants = 255; studies = 2; very low quality evidence) with no evidence of heterogeneity. No data on short term mortality were available. Two studies reported data on adverse events after ILR implant. Due to the lack of data on adverse events in one of the studies' arms, a formal meta-analysis was not performed for this outcome. Data from two trials seemed to show no difference in quality of life, although this finding was not supported by a formal analysis due to the differences in both the scores used and the way the data were reported. Data from two studies seemed to show a trend towards a reduction in syncope relapses after diagnosis in participants implanted with ILR. Cost analyses from two studies showed higher overall mean costs in the ILR group, if the costs incurred by the ILR implant were counted. The mean cost per diagnosis and the mean cost per arrhythmic diagnosis were lower for participants randomised to ILR implant. Participants who underwent ILR implantation experienced higher rates of diagnosis (RR (in favour of ILR) 0.61, 95% CI 0.54 to 0.68; participants = 579; studies = 4; moderate quality evidence), as compared to participants in the standard assessment group, with no evidence of heterogeneity.

Authors' Conclusions

Our systematic review shows that there is no evidence that an ILR-based diagnostic strategy reduces long-term mortality as compared to a standard diagnostic assessment (very low quality evidence). No data were available for short-term all-cause mortality. Moderate quality evidence shows that an ILR-based diagnostic strategy increases the rate of aetiologic diagnosis as compared to a standard diagnostic pathway. No conclusive data were available on the other end-points analysed. Further trials evaluating the effect of ILRs in the diagnostic strategy of people with recurrent unexplained syncope are warranted. Future research should focus on the assessment of the ability of ILRs to change clinically relevant outcomes, such as quality of life, syncope relapse and costs.

---

### 2020 APHRS / HRS expert consensus statement on the investigation of decedents with sudden unexplained death and patients with sudden cardiac arrest, and of their families [^113mJnhg]. Heart Rhythm (2021). High credibility.

Epidemiology — sudden unexplained death (SUD) definition and incidence — sudden unexplained death refers to an unexpected and sudden death in an individual older than 1 year; in witnessed cases, death has to occur within 1 hour of change in cardiovascular status, whereas unwitnessed cases have to be seen alive and functioning normally within 24 hours of being found dead. SCD constitutes the majority of SUD, and previous studies report overall SCD rates ranging from 15 to 159 SCD per 100,000 persons per annum, corresponding to 6–20% of all deaths.

---

### Preoperative electrocardiogram in prediction of 90-day postoperative mortality: retrospective cohort study [^112QSmQn]. BMC Anesthesiology (2024). Medium credibility.

The current study is essential because it addresses a significant gap in the literature concerning the role of preoperative ECG in predicting postoperative outcomes across a diverse patient population. While specific ECG abnormalities have been linked to adverse outcomes in targeted patient groups, there is limited evidence on their prognostic value in a general NCS population.

The Revised Cardiac Risk Index (RCRI) is a widely used tool to predict perioperative cardiac complications in non-cardiac surgery patients. It includes six independent variables: high-risk surgery, history of ischemic heart disease, history of congestive heart failure, history of cerebrovascular disease, insulin-dependent diabetes mellitus, and preoperative serum creatinine > 2 mg/dl. The RCRI is valuable for identifying patients at risk for cardiac complications; however, its predictive accuracy may be enhanced by incorporating additional diagnostic tools such as the ECG. While the RCRI provides a structured approach to risk assessment, our study explores whether preoperative ECG findings can offer complementary prognostic information.

This study seeks to provide robust evidence on the predictive value of preoperative ECG in a broad NCS population, thereby enhancing the current understanding and application of perioperative risk assessment tools. Our findings could lead to improved clinical guidelines and better outcomes for patients undergoing non-cardiac surgery.

---

### Performance of emergency department screening criteria for an early ECG to identify ST-segment elevation myocardial infarction [^11641XnR]. Journal of the American Heart Association (2017). Low credibility.

Results

In total, 472 166 adult patients were primarily screened for an early ECG to diagnose STEMI; of those, 407 were diagnosed with STEMI, for a total study population prevalence of 0.09% (95% CI 0.08–0.10%) (Table 1). Study‐site STEMI prevalence ranged from 0.03% to 0.18%. This is a subset of the larger hospital STEMI population. Consequently, the prevalence of STEMI was lower than typically reported. The difference in the median door‐to‐ECG time between captured and missed primarily screened STEMI patients was 31 minutes (95% CI 9.7–52.3; P = 0.018) of additional myocardial ischemia time (Table 2). The screening results for each ED and for the total screened population are summarized in the following sections and in Table 1.

Table 1
Diagnostic Performance of the Screening Criteria for an Early ECG to Diagnose STEMI

Table 2
Difference in Door‐to‐ECG Time for Captured and Missed Cases

---

### 2020 APHRS / HRS expert consensus statement on the investigation of decedents with sudden unexplained death and patients with sudden cardiac arrest, and of their families [^113zpokL]. Heart Rhythm (2021). Medium credibility.

7.3. Investigation of Sudden Cardiac Arrest Survivors: Baseline Investigations

In most emergency settings, a patient resuscitated from cardiac arrest in whom myocardial infarction is suspected will have undergone a coronary reperfusion strategy to treat acute occlusion. It is critical to obtain blood tests (cardiac enzymes, inflammatory markers, glucose, serum electrolytes, and white blood cell count) and pertinent toxicological analysis at presentation. The latter may include testing for drugs of abuse such as ethanol, opiates, and stimulants, as well as levels of prescribed medication that may prolong QT interval/QRS duration or cause respiratory depression. While assisting in the acute management of a resuscitated patient, these results will also help to differentiate acute myocardial injury as a cause of cardiac arrest (eg, ischemia without clear evidence of coronary occlusion or myocarditis) and pick up other reversible causes such as drug overdose, electrolyte imbalance, or endocrine and metabolic disorders. Retention and storage of suitable blood samples on patient arrival in the emergency department will allow subsequent diagnostic evaluation including DNA extraction and analysis in a patient who dies prior to diagnosis or for later clinical and family review. In some cases, this may be the only opportunity to obtain genetic material for analysis.

In an OHCA, the use of AEDs is ever more widespread and increases survival. Sensitivity for the diagnosis of cardiac rhythm at the time of arrest is about 99%. Therefore, routine inspection of data from AED recordings may improve the quality of diagnosis (see Section 6.2). The underlying rhythm of cardiac arrest may provide information on the arrhythmogenic mechanism, assist in diagnosis, and eventually indicate any misdiagnosis of rhythm. Any ECG tracings from emergency services, as well as recordings from interrogation of CIEDs or wearables can also contribute to diagnosis.

The 12-lead ECG in sinus rhythm or during arrhythmia recurrence is fundamental to the diagnostic investigation and should be repeated daily during recovery. It may support diagnoses of primary electrical disorders, pre-excitation, and heart muscle diseases. However, abnormalities of cardiac conduction and repolarization may result from myocardial injury during the cardiac arrest and patients undergoing post-arrest hypothermia protocols may have transient ECG changes including QT prolongation and J point elevation that should be interpreted with caution. Information about electrolyte levels, drug prescription, and body temperature should be added to the ECG to prevent misinterpretation of such ECG abnormalities. A high precordial lead ECG is an inexpensive tool to increase detection of Brugada syndrome pattern.–

---

### 2020 APHRS / HRS expert consensus statement on the investigation of decedents with sudden unexplained death and patients with sudden cardiac arrest, and of their families [^116zM4kq]. Heart Rhythm (2021). Medium credibility.

Recommendation-Specific Supportive Text

The usefulness of blood testing and toxicology is by consensus, and a diagnostic role is unquestionable. Viral studies may be useful, but no systematic evidence is available as yet. A potential role for biomarkers specific for one of the arrhythmia syndromes is anticipated.
Results of a forensic study indicate the value of postmortem CIED interrogation to define the cause and timing of death more accurately and to detect potential CIED-related safety issues. CIED interrogation in unexplained deaths clarified the manner of death in 60.8% of the cases including cardiac and nonarrhythmic death and device concerns.
Sensitivity for the diagnosis of cardiac rhythm via AED at the time of arrest is about 99%. However, the AED seldom catches the initial rhythm of cardiac arrest and therefore may not contribute to the etiology of SCA.
Primary electrical disorders and specific cardiomyopathies may be detected by conventional ECG. ECG findings in the immediate aftermath of a cardiac arrest, other than ST-segment elevation indicative of an acute coronary syndrome, may, however, have poor diagnostic accuracy. These could be caused by abnormal repolarization following electrical cardioversion, metabolic and electrolyte abnormalities, or even subarachnoid hemorrhage. Therapeutic hypothermia may lead to misleading ECG changes such as prolongation in PR, QRS and QT intervals, and J point elevation. Interpretation of ECGs obtained immediately after resuscitation/defibrillation should be performed with great caution.
Although there are no data describing directly the value of high precordial lead ECGs in SCD survivors, there is ample evidence of an increased yield of the type 1 Brugada ECG pattern.
Cardiac monitoring during short-term follow-up demonstrates an arrhythmogenic mechanism of SCD in some registries.
Signal-averaged ECG is part of the Task Force Criteria for arrhythmogenic right ventricular cardiomyopathy. Signal-averaged ECG has been proposed as useful in other conditions (ie, Brugada syndrome), although systematic evaluation has not been performed.
Echocardiography is a valuable screening tool for detection of arrhythmogenic cardiomyopathy and other structural abnormalities useful in elucidating the cause of SCA. Patients with functional abnormalities on initial echocardiogram should have this test repeated after recovery, to allow for the effects of the SCA itself and drugs used around the time of the arrest to wear off.
9. and 10. The utility of CMR has been evaluated in a series of studies involving survivors of unexplained arrest and has repeatedly been shown to provide significant incremental diagnostic value. A study of 137 individuals with unexplained aborted cardiac arrest found that CMR provided a diagnosis or identified an arrhythmic substrate in 76% of individuals, including an infarct pattern suggestive of occult myocardial infarction in 44%. Notably, the presence of late gadolinium enhancement, reflective of myocardial fibrosis, was associated with a 6.7 hazard ratio (p < 0.001) of recurrent arrhythmic events on multivariate analysis. The presence of subendocardial edema would suggest ischemic injury even when initial coronary imaging excludes significant obstruction. Coronary vasospasm and dissection might be misdiagnosed, and coronary re-evaluation may then be reconsidered. The frequency of occult infarcts is not insignificant, although the risk of SCD in patients with myocardial infarction and nonobstructive coronary arteries is low. For Recommendation 10, primary electrical disease is not referring to an established diagnosis of long QT syndrome or CPVT, where MRI is unlikely to be of use.
Coronary artery disease is the leading cause of SCD in adults and might be treatable. Furthermore, coronary dissection and anomalies may also be relevant in this age group as well as in younger patients.

---

### Mortality differences among patients with in-hospital ST-elevation myocardial infarction [^112EN3uB]. Clinical Cardiology (2020). Medium credibility.

4 DISCUSSION

In‐hospital STEMI, while far less common than out‐of‐hospital STEMI, is associated with delayed reperfusion and poorer outcomes. 1 Admitted patients are frequently not on cardiology services, less likely to have typical symptoms suggestive of acute MI, and more likely to have comorbid conditions which may serve as contraindications to invasive diagnostic testing, including coronary angiography. These factors contribute to delayed recognition, triage, and treatment of in‐hospital STEMI. 1 The cohort of patients who develop in‐hospital STEMI consists of a heterogeneous population with various admission diagnoses and varying complexity of illness. This study highlights the differences in outcomes among three distinct subsets of patients who develop STEMI while admitted to the hospital: cardiac, periprocedure, and noncardiac/nonpostprocedure. To our knowledge, this is the first multicenter study to stratify cases of in‐hospital STEMI into more discrete, homogeneous groups.

Although an overall in‐hospital mortality of 36% presented in this case series was comparable to published mortality rates, we found that this was driven primarily by higher mortality among the noncardiac patients (33%‐46%). 1 Mortality for cardiac patients in this study more closely resembled reported rates of out‐of‐hospital STEMI cases. 8 Furthermore, the noncardiac patients in our study had longer ECG‐to‐CCL times than cardiac patients, although a significant limitation is the extent of missing data and the small sample size, particularly for our cohort of cardiac patients. Nonetheless, our findings were consistent with those reported in single center studies by Garberich et al and Dai et al, which also found that patients admitted with noncardiac reasons had longer reperfusion times and higher mortality than those admitted for cardiac reasons. 3, 9

---

### 2022 AHA / ACC / HFSA guideline for the management of heart failure: a report of the American college of cardiology / American Heart Association joint committee on clinical practice guidelines [^112L6gSz]. Circulation (2022). High credibility.

Regarding diagnostic investigations for heart failure, more specifically with respect to ECG, ACC/AHA/HFSA 2022 guidelines recommend to obtain a 12-lead ECG at the initial encounter in all patients presenting with HF, to optimize management.

---

### Out-of-hospital cardiac arrest: causes according to autopsy and electrocardiography-analysis of 781 patients with neither hospital care nor prescribed medication during the preceding two years [^112gidsX]. Resuscitation (2020). Medium credibility.

Background

There is a knowledge gap regarding aetiology of and potential for predicting out-of-hospital cardiac arrest (OHCA) among individuals who are healthy before the event.

Aim

To describe causes of OHCA and the potential for predicting OHCA in apparently healthy patients.

Methods

Patients were recruited from the Swedish Register of Cardiopulmonary Resuscitation from November 2007 to January 2011. Inclusion criteria were: OHCA with attempted CPR but neither dispensed prescription medication nor hospital care two years before the event The register includes the majority of patients suffering OHCA in Sweden where cardiopulmonary resuscitation (CPR) was attempted. Medication status was defined by linkage to the Swedish Prescribed Drug Register. Cause of death was assessed based on autopsy and the Swedish Cause of Death Register. Prediction of OHCA was attempted based on available electrocardiograms (ECG) before the OHCA event.

Results

Altogether 781 individuals (16% women) fulfilled the inclusion criteria. Survival to 30 days was 16%. Autopsy rate was 72%. Based on autopsy, 70% had a cardiovascular aetiology and 59% a cardiac aetiology. An ECG recording before the event was found in 23% of cases. The ECG was abnormal in 22% of them.

Conclusion

Among OHCA victims who appeared to be healthy prior to the event, the cause was cardiovascular in the great majority according to autopsy findings. A minority had a preceding abnormal ECG that could have been helpful in avoiding the event.

---

### 2020 APHRS / HRS expert consensus statement on the investigation of decedents with sudden unexplained death and patients with sudden cardiac arrest, and of their families [^112X813j]. Heart Rhythm (2021). High credibility.

Investigation of sudden death: examination of premorbid investigations states that "Twelve-lead electrocardiogram (ECG) is the most useful pre-SUD investigation", and highlights additional ECG features including "intraventricular conduction abnormalities (QRS duration > 0.12 s)" and bradyarrhythmias such as "sinus bradycardia (< 40 bpm) or slow atrial fibrillation (< 40 bpm)". In the general population, "premature ventricular complexes (PVCs) are mostly benign; however, frequent or complex PVCs significantly increase the risk of SCD". If an ECG is recorded just before arrest, "features such as J-wave or ST segment elevation (especially if augmented after a long pause) may help in the diagnosis", whereas "Interpretation of ECGs obtained immediately after resuscitation/ defibrillation should be performed with great caution". Clinical triggers are noted: "Syncope is a sentinel clinical symptom before SUD", and "Ambulatory ECG monitoring during life may provide clues to the cause of SUD and should be sought". Prior imaging should be reviewed because "cardiac computed tomography (CT), or cardiac magnetic resonance imaging (CMR) are performed during the patient's life, detailed review may indicate features of dilated cardiomyopathy, hypertrophic cardiomyopathy, or arrhythmogenic cardiomyopathy". Potential sources for genetic analysis are specified: "If blood or other tissue sample has been taken before SUD, this may be a source of DNA for genetic testing", and noncardiac clues can assist: "Neurological findings such as developmental delay or seizures thought to be suspicious for epilepsy during life may contribute to a diagnosis of a cardiac channelopathy, such as CPVT or long QT syndrome". Device data can also inform cause and timing: "If a patient with SUD has a cardiovascular implantable electronic device (CIED) implanted, postmortem interrogation of the CIED is useful to determine the cause and timing of SCD".

---

### Performance of emergency department screening criteria for an early ECG to identify ST-segment elevation myocardial infarction [^112KEv5M]. Journal of the American Heart Association (2017). Low credibility.

Background

Despite decades of quality‐improvement efforts, the timely diagnosis of STEMI patients in the ED presents significant operational challenges. In managing the timely care of patients with STEMI, EDs encounter 3 distinct types of patients who differ on the screening, diagnosis, and treatment continuum. First are patients who have been prediagnosed with STEMI, who have had an ECG performed and interpreted by another provider. They are usually transferred to an ED or a hospital capable of definitive treatment, most often percutaneous coronary intervention. The expectation is that treatment will be initiated on arrival. Second are prescreened patients who have been evaluated by another provider and referred to the ED with an ECG concerning for ischemia. In these cases, the diagnosis needs to be confirmed with a repeat ECG or reinterpretation of the ECG on arrival. The burden of screening for STEMI from the report of symptoms has already been met in these 2 scenarios; however, treatment has not been initiated. Third are the patients at greatest risk of delays in care: those arriving in the ED with undifferentiated symptoms who are primarily screened by that ED. In these cases, timely STEMI diagnosis is dependent on the patient's condition and symptoms triggering ED intake staff to perform an early ECG. 4, 5 The ECG is often considered the screening test for STEMI. In the context of emergency care, however, treatment is initiated with ECG evidence of STEMI, making it a diagnostic test. 6 The true screening test is the criteria by which ED care providers initiate an ECG (Figure 2).

Overly comprehensive screening criteria for a rare disease like STEMI risks underutilization. The sole use of chest pain is user friendly but likely produces inadequate case capture. Overall, 20% to 30% of patients with STEMI will report atypical symptoms like shortness of breath and dizziness 7, 8, 9, 10, 11 or will focus on associated symptoms like jaw, neck, or back pain. In addition, age positively influences the probability of STEMI, and elderly patients with STEMI more frequently report atypical symptoms. 12, 13, 14 Shorter time to reperfusion has been shown to improve outcomes. 15, 16, 17, 18, 19 Door‐to‐ECG time interval is the first STEMI care target toward achieving timely intervention.

---

### 2023 ESC guidelines for the management of cardiomyopathies [^112z69v4]. European Heart Journal (2023). High credibility.

Regarding screening and diagnosis for arrhythmogenic right ventricular cardiomyopathy, more specifically with respect to screening of family relatives (follow-up), ESC 2023 guidelines recommend to consider obtaining regular, long-term clinical evaluation using a multiparametric approach, including ECG and cardiac imaging, in first-degree relatives when no pathogenic/likely pathogenic variant is identified in the proband or genetic testing is not obtained. (IIa, C.

---

### Screening for blunt cardiac injury: an Eastern Association for the Surgery of Trauma practice management guideline [^1162iuop]. The Journal of Trauma and Acute Care Surgery (2012). Medium credibility.

Regarding diagnostic investigations for blunt chest trauma, more specifically with respect to evaluation for cardiac injury (ECG), EAST 2012 guidelines recommend to obtain an ECG on admission in all patients with suspected blunt cardiac injury.

---

### Electrocardiograms in athletes: interpretation and diagnostic accuracy [^1128AfM3]. Medicine and Science in Sports and Exercise (2008). Low credibility.

Purpose

Electrocardiography (ECG) has been proposed as a method to enhance the ability of the preparticipation examination (PPE) to detect underlying cardiac conditions that can lead to sudden cardiac death (SCD) in young athletes.

Methods and Results

We conducted a Medline review of the published medical literature, using the key terms of cardiovascular screening of athletes, ECG in athletes, SCD in athletes, and ECG in specific cardiac disease states: hypertrophic cardiomyopathy, arrhythmogenic right ventricular cardiomyopathy, dilated cardiomyopathy, myocarditis, long QT syndrome, Brugada syndrome, coronary artery anomalies, myocardial bridging, aortic stenosis, mitral valve prolapse, and Marfan syndrome. ECG seems to increase the sensitivity of the PPE from 2.5–6% to 50–95%. Overall sensitivity appears to be about 50%; false-positive rates can be as high as 40%, and there is at least a 4–5% false-negative rate. In Europe, ECG-based screening programs have been associated with a decline in the SCD rate in young athletes, but similar programs are currently not recommended in the United States for many reasons: lack of randomized trial data; cost of screening; lack of a clear standard for ECG interpretation in the athlete; the likelihood that asymptomatic athletes with underlying lethal conditions might differ significantly from symptomatic individuals with the same conditions; and concern that ECG screening might actually increase the death rate, via treatment-related procedural complications.

Conclusions

Although some authorities advocate the use of ECG screening of young athletes, further studies are required to define what constitutes a normal ECG in athletes, and to determine whether ECG-based screening protocols truly are superior, not only in finding disease, but also saving lives. For those who either choose ECG-based screening or interpret ECG in athletes, we propose a simple interpretation scheme and decision tree.

---

### Prevalence of ECG abnormalities in an international survey of patients with suspected or confirmed heart failure at death or discharge [^114UjJ8p]. European Journal of Heart Failure (2007). Low credibility.

Background

Most patients suspected of having heart failure (HF) will get a 12-lead electrocardiogram (ECG) but its utility for excluding HF or assisting in its management has rarely been investigated.

Methods

The EuroHeart Failure survey identified 11,327 patients hospitalised with a suspected diagnosis of HF from 115 hospitals in 24 countries. ECGs were obtained from 9315 patients, of whom 5934 had cardiac imaging tests. The utility of the ECG was assessed for excluding or diagnosing major structural heart disease (MSHD) or major left ventricular systolic dysfunction (MLVSD) and for therapeutic decision making.

Findings

MSHD was present in 70% and MLVSD in 54% of patients overall but in only 21% and 5%, respectively, if the ECG was entirely normal. However, < 2% of patients had a normal ECG. No single ECG characteristic identified a probability < 25% of MSHD or < 20% of MLVSD. Patients with QRS width ≥ 120 ms or anterior pathological Q-waves had a probability > 80% of MSHD and > 70% of MLVSD. Diagnostic models suggested that electrocardiographic criteria alone were not accurate for the diagnosis or exclusion of important heart disease in this population. However, 2468 patients (42%) had an electrocardiographic finding that should be used to guide the choice of therapy.

Conclusions

A normal ECG is rare in patients with suspected HF but has limited diagnostic value in this setting. The ECG has an important role in guiding therapy.

---

### Myocardial injury after non-cardiac surgery: diagnosis and management [^111GSE9U]. European Heart Journal (2020). Medium credibility.

Myocardial injury after non-cardiac surgery (MINS) is due to myocardial ischaemia (i.e. supply-demand mismatch or thrombus) and is associated with an increased risk of mortality and major vascular complications at 30 days and up to 2years after non-cardiac surgery. The diagnostic criteria for MINS includes an elevated post-operative troponin measurement judged as resulting from myocardial ischaemia (i.e. no evidence of a non-ischaemic aetiology), during or within 30days after non-cardiac surgery, and without the requirement of an ischaemic feature (e.g. ischaemic symptom, ischaemic electrocardiography finding). For patients with MINS who are not at high risk of bleeding, physicians should consider initiating dabigatran 110mg twice daily and low-dose aspirin. Physicians should also consider initiating statin therapy in patients with MINS. Most MINS patients should only be referred to cardiac catheterization if they demonstrate recurrent instability (e.g. cardiac ischaemia, heart failure). Patients ≥ 65years of age or with known atherosclerotic disease should have troponin measurements on days 1, 2, and 3 after surgery while the patient is in hospital to avoid missing > 90% of MINS and the opportunity to initiate secondary prophylactic measures and follow-up.

---

### Major adverse cardiac event rates in moderate-risk patients: does prior coronary disease matter? [^113U49DF]. Academic Emergency Medicine (2022). Medium credibility.

Safely evaluating and dispositioning moderate‐risk chest pain patients challenges emergency providers every shift. Traditionally, most of these patients are admitted to the hospital or to an observation unit for OCT. However, recent studies have called into question routine OCT evaluations and hospitalizations for patients without ischemic ECGs or elevated troponin measures. Routine in‐hospital chest pain evaluations for moderate‐risk patients have a low diagnostic yield and are associated with iatrogenic risks from false‐positive testing, radiation exposure, and anxiety without evidence for improved clinical outcomes. This study highlights the low frequency of MACE in patients without an ischemic ECG, elevated troponin, or known CAD and calls into question the need for routine OCT in these patients prior to discharge.

This study may expand the early discharge boundaries of the HEART Pathway by suggesting that most moderate‐risk patients can safely be evaluated and dispositioned without OCT. The 30‐day MACE rate for moderate risk patients with no known CAD was 1.4% (17/1,207). This is below the 2% pretest probability threshold, which has been suggested for determining whether OCT is indicated. On the other hand, missing MACE in 1.4% of patients is above what most physicians find acceptable. However, closer inspection of the 17 MACE events among moderate‐risk patients without known CAD demonstrated that at least two of the four deaths were clearly due to noncardiac causes and two of the three missed MIs were due to serial troponin protocol violations. In addition, one missed revascularization event was due to an inaccurate HEART Pathway assessment by the treating provider. Furthermore, 10 of the 12 revascularization events were among patients without acute MI. Revascularization events among patients without evidence of MI are of questionable significance as revascularization has not been shown to improve outcomes in these patients compared to medical management. Finally, it is likely that with high‐sensitivity assays, the MACE rate among non–low‐risk patients with negative troponin measures would be even smaller.

---

### Computer-interpreted electrocardiograms: benefits and limitations [^115MPph4]. Journal of the American College of Cardiology (2017). Low credibility.

Computerized interpretation of the electrocardiogram (CIE) was introduced to improve the correct interpretation of the electrocardiogram (ECG), facilitating health care decision making and reducing costs. Worldwide, millions of ECGs are recorded annually, with the majority automatically analyzed, followed by an immediate interpretation. Limitations in the diagnostic accuracy of CIE were soon recognized and still persist, despite ongoing improvement in ECG algorithms. Unfortunately, inexperienced physicians ordering the ECG may fail to recognize interpretation mistakes and accept the automated diagnosis without criticism. Clinical mismanagement may result, with the risk of exposing patients to useless investigations or potentially dangerous treatment. Consequently, CIE over-reading and confirmation by an experienced ECG reader are essential and are repeatedly recommended in published reports. Implementation of new ECG knowledge is also important. The current status of automated ECG interpretation is reviewed, with suggestions for improvement.

---

### Acute ST-elevation myocardial infarction in patients hospitalized for noncardiac conditions [^1146J6h6]. Journal of the American Heart Association (2013). Low credibility.

There are several limitations to our study. It is a single‐center, retrospective study with a small cohort. Some patients with inpatient STEMIs may have been missed in this study because of either poor coding or sudden death prior to obtaining an ECG. There are inherent inaccuracies in identifying the onset of myocardial infarction in patients without symptoms.

---

### Last year of life of adults with congenital heart diseases: causes of death and patterns of care [^112HSCnm]. European Heart Journal (2022). Medium credibility.

Results

Causes of death

The distribution of causes of death is depicted in Figure 1. While 55 (14%) patients died due to a sudden, accidental, or violent cause of death, most patients (n = 327; 84%) had a non-sudden death. A total of 28 (7%) patients had an accidental or violent cause of death (including 14 deaths due to intentional self-harm), 15 (4%) patients had a sudden cardiac death, and 12 (3%) patients died suddenly with a noncardiac cause of death reported. For eight patients (2%), the cause of death was missing or unclear (for six patients due to death outside of Belgium).

Figure 1
Causes of death of adults with CHD (n = 390).

Almost half of the study population (n = 174; 45%) died from a cardiovascular cause, of which 15 (4%) patients had a sudden cardiac death. Of the patients who died due to a cardiovascular cause, 30% (n = 51/174) had the CHD as reported cause of death and 14% (n = 25/174) died due to a stroke.

---

### The problem with how we view medical (and diagnostic) error in emergency medicine [^112ro6yi]. Academic Emergency Medicine (2025). Medium credibility.

IF NOT ERROR, THEN WHAT?

Focus on hazards

Instead of tying patient safety enhancement efforts to errors, we propose a shift in focus from that of error to one of hazards. Hazards are things within a system that can cause harm to those within it. Across industries, efforts are focused on identifying potential hazards and either eliminating or mitigating these as part of safety management systems. One example of hazard reduction in health care was The Joint Commission's requirement to remove concentrated electrolytes from most clinical environments. The rationale was that substances such as concentrated potassium are hazardous as they can cause dysrhythmias and death. Removing the hazard (potassium) functionally eliminates the possibility of harm from overdose; thus, there is no need to carry out a randomized control trial to determine efficacy. As illustrated by this example, the term error is unhelpful and unnecessary in addressing this patient safety issue when we focus on hazards and harm mitigation.

Hazards are ubiquitous in STSs such as an ED. The question is whether anyone identifies and mitigates the associated harm. In the ED, two specific hazards are the time pressure for rapid diagnosis and intervention in the setting of incomplete information and the reality of transitions in care teams during a single encounter. In an ideal scenario, a patient is seen by a provider, diagnostic tests are ordered, images are correctly interpreted by a radiologist, and those findings are diagnosed and treated appropriately. This ideal scenario rarely occurs in EDs. With increasing ED capacity crises, long wait times, and the continuing high‐acuity presentations of undifferentiated patients, workflows are implemented to expedite care and avoid delayed diagnoses. Often, orders are placed for patients by triage nurses or by providers attempting to initiate diagnostics for patients in the waiting room based on chief complaints or suspected pathophysiology prior to evaluation. In this case, an ECG and chest x‐ray were ordered by an initial physician prior to examining the patient, creating the potential for incorrect orders. Additionally, transition in care occurred to an oncoming physician. While these posed potential hazards, they also facilitate continuation of necessary patient care. Diagnostic tests are available earlier and, in this case, a fresh physician stepped back to make sure they had the information they needed and prevented a hazard from progressing to harm. Therefore, hazards exist, but content expertise and adaptive behaviors by care teams can result in safe care delivery in the context of imperfect systems with inherent hazards.

---

### Diagnostic accuracy of high-sensitivity cardiac troponin T at presentation combined with history and ECG for ruling out major adverse cardiac events [^116LSBJM]. Annals of Emergency Medicine (2016). Low credibility.

Study Objective

We evaluate the diagnostic accuracy of a high-sensitivity cardiac troponin T (hs-cTnT) level less than 5 ng/L or less than or equal to 14 ng/L at emergency department (ED) presentation, combined with the emergency physician's assessment of history and ECG, for ruling out major adverse cardiac events within 30 days.

Methods

This prospective observational study enrolled consecutive ED chest pain patients. Emergency physicians' assessments of patient history and ECG were collected. The primary outcome was 30-day major adverse cardiac events, defined as acute myocardial infarction, unstable angina, cardiogenic shock, ventricular arrhythmia, atrioventricular block, cardiac arrest, or death of cardiac or unknown cause.

Results

A total of 1,138 patients were included in the final analysis. The combination of hs-cTnT less than 5 ng/L, a nonischemic ECG result, and a nonhigh risk history was present for 29.2% of all patients and had a sensitivity of 99.2% (95% confidence interval [CI] 95.6% to 100%), negative predictive value (NPV) of 99.7% (95% CI 98.3% to 100%), and a negative likelihood ratio of 0.02 (95% CI 0 to 0.17) for 30-day major adverse cardiac events. The same combination with hs-cTnT less than or equal to 14 ng/L was present in 66.7% of the patients and had a sensitivity of 92% (95% CI 85.8% to 96.1%), NPV of 98.7% (95% CI 97.6% to 99.4%), and negative likelihood ratio of 0.11 (95% CI 0.06 to 0.20).

Conclusion

A single hs-cTnT result of less than 5 ng/L at ED presentation when combined with a nonischemic ECG result and a nonhigh risk history identified 29% of chest pain patients at a very low risk of 30-day major adverse cardiac events. A similar strategy with hs-cTnT less than or equal to 14 ng/L was associated with a higher miss rate.

---

### Meta-analysis on the effectiveness of ECG screening for conditions related to sudden cardiac death in young athletes [^113vnBkN]. Clinical Pediatrics (2023). Medium credibility.

We sought to compare the effectiveness of H&P with the effectiveness of a 12-lead ECG in detecting cardiac disease. This includes conditions associated with SCD, such as HCM or WPW, as well as unrelated conditions, such as mitral valve prolapse. Every condition found by a screening program was categorized, as shown in Table 2. Arrhythmogenic right ventricular cardiomyopathy — now commonly known as arrhythmogenic ventricular cardiomyopathy — DCM, HCM, myocarditis, and LVNC were categorized as cardiomyopathies. We included congenital coronary atrioventricular fistula, anomalous origin of the left coronary artery and other, unspecified coronary artery anomalies under the category of coronary anomalies. Four conditions, WPW, long QT syndrome, and SCD with unspecified etiology, were listed as individual categories. "Arrhythmias, other" included atrial fibrillation, supraventricular tachycardia, sustained VT, and frequent PVCs. Finally, there were multiple structural conditions listed as "other", including an aneurysm with aortic root dilation, aortic coarctation, atrial septum defect, bicuspid aortic valve, mitral valve prolapse, and pectus excavatum with ventricular compression. Three athletes with 2 diagnoses — all from the Conway study — were removed because their condition was not considered pathological. The first was one athlete with dextrocardia. He already knew of his condition, but failed to mention it until the ECG screen returned abnormal results. Two diagnoses of patent foramen ovale were also removed.

---

### Delayed defibrillation caused by unexpected ECG artifact [^113V1rQB]. Annals of Emergency Medicine (2008). Low credibility.

Incorrect lead selection and unexpected ECG artifact during an attempted resuscitation after inhospital cardiac arrest resulted in undetected lack of cardiac monitoring for approximately 13 minutes. The patient was finally countershocked and regained a spontaneous pulse but was determined to have experienced profound neurologic damage and died shortly after being extubated. This type of failure may be common, particularly with older monitor/defibrillators. Caregivers, health care organizations, and device manufacturers should be aware of this potential problem and institute preventive measures.

---

### Meta-analysis on the effectiveness of ECG screening for conditions related to sudden cardiac death in young athletes [^116h7o3f]. Clinical Pediatrics (2023). Medium credibility.

Figure 4.
Forest plot showing the results of the association of electrocardiogram with cardiac disease. It shows the log odds ratio along with a 95% confidence interval for each of the individual studies included in the meta-analysis as well as an overall estimate based on the random-effects model. These were then back-transformed into odds ratios.

Abbreviation: RE, random effects.

After this first round of analysis, a second meta-analysis was performed for the association of H&P and ECG with conditions associated with SCD. Multiple cardiologists were consulted in determining which conditions to remove. In the end, 103 cardiac diagnoses associated with SCD were made across all 9 studies. Figure 5 shows the screening method used to detect each type of condition.

Figure 5.
Bar graph showing the results of ECG and H&P for each of the 6 categories of conditions associated with SCD.

Abbreviations: ECG, electrocardiogram; H&P, history and physical; SCD, sudden cardiac death.

For the association of H&P with conditions associated with SCD, the random-effects model was applied to the 9 studies, which showed high heterogeneity (I 2 = 63%). It yielded a back-transformed odds ratio of 2.9 (95% confidence limits: 0.88–9.4) that was not statistically significant at the 5 percent level (Z = 1.74, P = .082). Neither the rank correlation nor the regression test indicated any funnel plot asymmetry (P = .26 and P = .30, respectively). Figure 6 shows the association of H&P with conditions associated with SCD for each of the 9 studies as well as the overall meta-analysis as a forest plot.

---

### 2017 AHA / ACC / HRS guideline for management of patients with ventricular arrhythmias and the prevention of sudden cardiac death: a report of the American college of cardiology / American Heart Association task force on clinical practice guidelines and the Heart Rhythm Society [^116gzQR6]. Circulation (2018). Medium credibility.

Regarding follow-up and surveillance for cardiac arrest, more specifically with respect to post-cardiac arrest ICD implantation (ischemic heart disease), ACC/AHA/HRS 2018 guidelines recommend to perform ICD placement in patients with ischemic heart disease survived sudden cardiac arrest due to VT/VF,
if the expected meaningful survival is > 1 year.

---

### Meta-analysis on the effectiveness of ECG screening for conditions related to sudden cardiac death in young athletes [^112NY1fT]. Clinical Pediatrics (2023). Medium credibility.

Introduction

Sudden cardiac death (SCD) in young athletes is a devastating event that may be preventable by effective pre-participation screening; however, there is no universally accepted screening method for the conditions associated with SCD. In Italy, a pre-participation electrocardiogram (ECG) screening program has been in place since 1982, and a previous study by Corrado et alhas shown that it has significantly decreased the incidence of SCD. However, a comparative study by Maron et al has disputed these findings. The American Heart Association (AHA) and the Association for European Paediatric Cardiology (AEPC) both recommend a screening history and physical examination (H&P) be performed. The AEPC guidelines also recommend a 12-lead ECG be performed before clearing an athlete to play, while the AHA does not. The last meta-analysis on the subject was published in 2015. That same year, an international group of cardiologists came to a consensus on an update to ECG interpretation criteria in athletes. This was the third such update since 2010, following the publication of the European Society of Cardiology (ESC) criteria in 2010 and the Seattle criteria in 2013, indicating a need for a new meta-analysis to reflect these updates. Therefore, we sought to conduct a meta-analysis of the literature between 2015 and 2020 to compare the value of H&P with that of a 12-lead ECG as a screening tool for detecting cardiac disease.

---

### A bad workman blames his tools? [^117TfTsB]. BMJ Case Reports (2014). Medium credibility.

The ECG is a test that is used frequently in the acute setting. It has a significant impact on decisions regarding patient discharge and further investigations. On a single day in the ambulatory emergency care setting two patients presented with chest pain. The ECG findings were abnormal, but also out of context with the clinical findings. On close inspection of the ECG machine it was identified that although all leads attached to the patient were in the correct position, the two cables connecting the leads to the machine had been reversed. Had the error not been discovered promptly there was the potential that further, more harmful investigations would have been performed. These cases highlight that although the ECG is a simple and non-invasive investigation it should be an adjunct to clinical working diagnosis.

---

### Guidelines for the early management of patients with acute ischemic stroke: 2019 update to the 2018 guidelines for the early management of acute ischemic stroke: a guideline for healthcare professionals from the American Heart Association / American stroke association [^1132fWcC]. Stroke (2019). High credibility.

Regarding diagnostic investigations for acute ischemic stroke, more specifically with respect to ECG, AHA/ASA 2019 guidelines recommend to obtain baseline ECG in patients presenting with AIS without delaying initiation of IV alteplase.

---

### Diagnosis and detection of sarcoidosis. An official American Thoracic Society clinical practice guideline [^113D97XQ]. American Journal of Respiratory and Critical Care Medicine (2020). Medium credibility.

Recommendations

1 For patients with extracardiac sarcoidosis who do not have cardiac symptoms or signs, we suggest performing baseline ECG to screen for possible cardiac involvement (conditional recommendation, very low-quality evidence).
2 For patients with extracardiac sarcoidosis who do not have cardiac symptoms or signs, we suggest NOT performing routine baseline TTE or 24-hour continuous ambulatory ECG (Holter monitor) to screen for possible cardiac involvement (conditional recommendation, very low-quality evidence). Remarks: The panel recognizes the low risks attendant to the use of TTE or 24-hour continuous ambulatory ECG (Holter monitor) to screen for cardiac sarcoidosis. Thus, these tests should be considered on a case-by-case basis.

Research needs

The committee concluded that large research studies that compare diagnostic tests within a single population are needed to identify the optimal screening test(s) for cardiac sarcoidosis in asymptomatic individuals with sarcoidosis. Research studies are also needed to determine whether screening with CMR is warranted. Alternative screening tests for cardiac sarcoidosis should be developed and investigated, to detect cardiac sarcoidosis before it causes symptoms, and significant morbidity and mortality.

Question 9: Should Patients Who Are Suspected of Having Cardiac Sarcoidosis Undergo Cardiac MRI, TTE, or PET as an Initial Imaging Test?

---

### The accuracy of an out-of-hospital 12-lead ECG for the detection of ST-elevation myocardial infarction immediately after resuscitation [^112yzKKb]. Annals of Emergency Medicine (2008). Low credibility.

Study Objective

Severe myocardial ischemia is the leading cause of arrhythmic sudden cardiac death. It is unclear, however, in which percentage of patients sudden cardiac death is triggered by ST-elevation myocardial infarction (STEMI) and whether the diagnosis of STEMI can be reliably established immediately after resuscitation from out-of-hospital sudden cardiac death.

Methods

A 12-lead ECG was registered after return of spontaneous circulation after cardiac arrest. After hospital admission, further ECG, creatine kinase MB, and troponin measures; results of coronary angiograms; and autopsies were evaluated to confirm the definitive diagnosis of STEMI.

Results

Seventy-seven patients were included in our study (67% men, age 64 [14 to 93] years). STEMI was diagnosed in 44 patients. The diagnosis of myocardial infarction was confirmed in 84% of the 77 patients who survived to hospital admission. The sensitivity of the out-of-hospital ECG was 88% (95% confidence interval [CI] 74% to 96%), the specificity 69% (95% CI 51% to 83%), the positive predictive value 77% (95% CI 62% to 87%), and the negative predictive value 83% (95% CI 64% to 87%). The accuracy of the out-of-hospital ECG and that registered on admission was the same.

Conclusion

The diagnosis of STEMI can be established in the field immediately after return of spontaneous circulation in most patients. This may enable an early decision about reperfusion therapy, ie, immediate out-of-hospital thrombolysis or targeted transfer for percutaneous coronary intervention.

---

### Abnormal pre-participation cardiac screening in athletes: can an athlete train while waiting for a "Diagnosis"? [^111s5ZRy]. JACC: Advances (2025). Medium credibility.

The quest for effective pre-participation screening in young athletes is centered around identifying largely quiescent conditions, tailoring risk stratification, and preventing exercise-related sudden cardiac arrest (SCA) or sudden cardiac death (SCD). Contemporary practice simultaneously emphasizes the role of shared decision-making (SDM), particularly where abnormalities are suspected or confirmed following comprehensive evaluations.

Despite debates regarding the evidence and optimal strategies for screening, most elite sporting organizations recommend regular cardiac screening across various age groups and sporting disciplines. Furthermore, extensive research has reduced false positive findings over the past 2 decades. This progress and reassurance at the time of screening has primarily been achieved through the refinement of electrocardiographic (ECG) criteria, and improvement in our ability to better differentiate between exercise-induced physiological adaptations from pathological conditions via ECG and cardiac imaging.

Variations in professional and elite athlete screening practices exist as a function of the sporting governing body, regional variations in practice, and the availability of resources. For example, across North America, the prevailing standard of care continues to be the American Heart Association 14-point screening evaluation tool, with a noticeable shift toward the incorporation of the 12-lead ECG at all levels of sport. Determining the frequency of screening based on an athlete's age is also an evolving and topical area as inherited cardiac conditions associated with SCA/SCD in young athletes frequently present in adolescence.

If an abnormality is discovered during pre-participation screening, can the athlete continue to partake in high-intensity training and competitive sport, while awaiting confirmatory investigations and risk stratification? This is an integral question that arises at a critical juncture for many athletes. Coupled with this uncertainty is how providers effectively communicate the situation to the athlete, parents or guardians, and other team doctors while arranging further assessments. We acknowledge that this area remains largely devoid of definitive evidence and that clinicians' views and practices may vary based on their experience, level of comfort, the specific circumstances of the young individual, overall risk profile, and medicolegal considerations.

---

### Pre-participation cardiovascular evaluation for athletic participants to prevent sudden death: position paper from the EHRA and the EACPR, branches of the ESC. endorsed by APHRS, HRS, and SOLAECE [^1176kyFa]. Europace (2017). Medium credibility.

Pre-participation cardiovascular evaluation — role of electrocardiogram (ECG): Pre-participation cardiovascular evaluation that relies solely on medical history and physical examination has a limited ability to identify potentially lethal cardiovascular abnormalities in young athletes. The addition of 12-lead ECG substantially enhances screening, with sensitivity improving from less than 25% for clinical history and exam to > 90% for ECG, and a recent meta-analysis demonstrated that the most effective strategy to detect underlying (predisposing to SCD/SCA) disease is ECG. There are a number of considerations and limitations to ECG screening.

---

### Detecting deceased patients on cardiac device remote monitoring: a case series and management guide for cardiac device services [^114aB1Mq]. Heart Rhythm (2024). Medium credibility.

Background

Remote monitoring (RM) of implantable cardiac devices provides substantial and complex information, presenting new challenges such as detection of a patient's death.

Objective

This study aims to describe RM transmissions indicating death and propose a management strategy for services.

Methods

The study included consecutive ambulatory outpatients whose deaths were detected via RM. Clinical and device data were collected from electronic records, and ethical approval was obtained from the service's institutional review board.

Results

Over a 9-year period (2014–2023), 28 patients were detected. The deceased patients had implantable cardioverter-defibrillators, pacemakers, and implantable loop recorders. In 54% of the cases, the patient's death had already been recognized. Alert transmissions indicating death were commonly related to ventricular arrhythmia events, but also due to lead measurements, and implantable loop recorder battery status. Several diagnostic features may indicate a patient's death. The most reliable was the presenting electrogram, demonstrating base rate pacing with no capture. Device diagnostics, lead parameters, and arrhythmia recordings may indicate death; however, not all cases present with recordings and diagnosis may not be conclusive. A majority (82%) had ventricular arrhythmia at the time of death. In cases where defibrillator shocks were delivered, the arrhythmia reinitiated shortly after successful cardioversion. Delayed therapy was observed, and some patients did not receive defibrillator shocks because of discriminators or because the arrhythmia rate fell below the shock zone.

Conclusion

Detecting a patient death via RM presents unique challenges and considerations for services. Standard operational policies and legal consultation should be established to address the implications.

---

### 2021 AHA / ACC / ASE / CHEST / SAEM / SCCT / SCMR guideline for the evaluation and diagnosis of chest pain: a report of the American college of cardiology / American Heart Association joint committee on clinical practice guidelines [^115dDqQ3]. Circulation (2021). High credibility.

Emergency medical services (EMS) transfer and electrocardiogram (ECG) timing — initial chest pain evaluation: Early recognition of ST-elevation myocardial infarction (STEMI) requires that an ECG "should be obtained and interpreted within 10 minutes of arrival", and if this cannot be done in the office, "immediate transfer to the ED by EMS is recommended". For office presentations with suspected acute coronary syndrome (ACS) or other life‑threatening conditions, transfer "by EMS… is recommended" due to prehospital ECG acquisition, trained personnel, and faster transport. Delaying transfer for cardiac troponin (cTn) or other testing beyond the ECG in the office "can be detrimental and should be avoided".

---

### Recommendations on the use of multimodality cardiovascular imaging in young adult competitive athletes: a report from the American Society of Echocardiography in collaboration with the Society of Cardiovascular Computed Tomography and the Society for Cardiovascular Magnetic Resonance [^115Aqzr7]. Journal of the American Society of Echocardiography (2020). High credibility.

Pre-participation cardiovascular screening — contemporary standard of care in CA is designed to detect unrecognized cardiovascular conditions associated with increased risk of sudden cardiac arrest, and current recommendations in the United States by the American College of Cardiology/American Heart Association suggest a basic universal screening strategy limited to a focused cardiovascular history and physical examination; to date, there are no data defining the impact of this strategy on mortality in CA and high rates of false-positive and false-negative results have been described, while several organizing bodies recommend the inclusion of a 12-lead ECG based on its ability to detect clinically silent diseases of the heart muscle and cardiac conduction system, though opponents of ECG-inclusive screening cite potential issues including cost increase and inability to detect important conditions.

---

### Interpreting troponin elevations: do we need multiple diagnoses? [^117AFCsq]. European Heart Journal (2009). Low credibility.

Despite these problems in clinical decision-making and patient management, this case illustrates the advantages to having the diagnosis of TYPE 2 MI available. In discussing the Universal Definition for MI, the joint commission discussed the importance of also defining the extent or severity of the MI. Based on the relatively small rise in troponin and non-specific abnormalities on ECG, the amount of cardiac damage in this patient was felt to be small, and additional imaging studies to confirm that assessment were deferred. But the term TYPE 2 MI is still applicable, even though we may qualify the diagnosis using appropriate modifiers (such as possible or probable) with the recognition that the diagnosis may be confirmed, excluded, or further refined, depending on further studies.

The Diagnosis of TYPE 2 MI is advantageous not only for documentation purposes, but can also assist in quality review programs. Criteria for optimal care of acute MI often include measures such as time from onset of symptoms to first medical contact, time to first ECG, time from initial diagnosis to cardiac consultation, or time from diagnosis to lytic therapy, arrival in the catheterization lab, or reperfusion. Such measures are meaningless in patients such as the one presented here, and using an alternate diagnosis will prevent misclassification of the event.

---

### Mortality differences among patients with in-hospital ST-elevation myocardial infarction [^117VZhnw]. Clinical Cardiology (2020). Medium credibility.

There are several additional limitations to the current study. This was a retrospective analysis with reliance on ICD‐9 and ICD‐10 codes to identify cases meeting inclusion criteria. Therefore, there is a possibility that cases were inadvertently excluded if patients died prior to diagnosis, if the physician did not document the appropriate diagnoses, or if there was incomplete or inaccurate coding. For those patients that had ECG and biomarker findings suggestive of STEMI that did not undergo cardiac catheterization (63/184), we cannot exclude the possibility that these findings were due to STEMI mimickers such as stress‐induced cardiomyopathy or pericarditis. Furthermore, we did not collect data regarding cause of death, therefore it is unknown whether in‐hospital mortality was related to the STEMI event. The lack of left ventricular systolic function in our analysis is also a limitation, given that this is a factor that may influence patient outcomes.

Our results demonstrated that differences in survival were 24% between groups 1 and 3 and 17% between groups 1 and 2, but these differences did not reach statistical significance. In order to confirm these differences with 80% power at an alpha level of 0.05, a larger sample size is needed (35 patients in group 1, 295 patients in group 2, and 167 in group 3). Therefore, the lack of statistical significance is likely due to small sample sizes. Additional studies are warranted to confirm our findings, to further investigate variables associated with the development of in‐hospital STEMI, and to elucidate the etiologies of prolonged reperfusion times. Despite delays in reperfusion, the use of PCI has been associated with higher rates of survival in these patients. 7 Prospective data are also needed to further assess the impact of PCI on mortality. Quality improvement initiatives aimed at reducing these delays are being developed and implemented at medical centers across the country, and data from one center showed that the implementation of a standardized protocol for inpatient STEMI management reduced reperfusion times and improved mortality rates within 1 year. 9 Prospective data from more medical centers is needed to assess the efficacy of such initiatives and to facilitate the development of national quality measures similar to those in place for out‐of‐hospital STEMI. Another valuable goal of future research would be to develop and validate a risk score to identify patients at the highest risk of developing in‐hospital STEMI upon admission so that targeted interventions for prevention and early diagnosis can be implemented.

---

### Cardiac evaluation of young athletes: time for a risk-based approach? [^115RFwkS]. Clinical Cardiology (2020). Medium credibility.

Only one other study provides long‐term mortality data in combination with findings from baseline PPCS. Malhotra et al reported findings in 11 168 elite adolescent soccer players screened at a mean age of 16.4 years with a health questionnaire, physical examination, ECG, and echocardiogram, and followed for a mean of 10.6 years. Forty‐two athletes (0.38%) were identified with a cardiac disorder associated with SCA/SCD. Only four of these athletes (9.5%) presented with symptoms and/or findings on physical examination, whereas 36 (86%) had an abnormal ECG. Athletes with pathological cardiac disorders received disease‐specific medical management, procedural interventions, and exercise restrictions as indicated to mitigate their risk. Two athletes with HCM who returned to sport against medical recommendations died, while SCA/SCD was potentially averted in 40 of 42 athletes optimally managed after early detection of a pathological cardiac disorder. 14 Overall, eight athletes died an average 6.8 years from their screening evaluation. Six of these eight deaths were attributed to cardiomyopathy. One must acknowledge that the ECG performed only once at age 16 failed to detect a critical proportion of athletes who subsequently died from cardiac disease. This limitation may be attributed to the imperfect sensitivity of ECG, 24 or more likely that cardiac pathology was yet to manifest with ECG anomalies, especially in cases of cardiomyopathy where phenotypic expression of disease in genetically predisposed individuals often occurs in late adolescence and early adulthood.

This raises the important issue regarding the frequency and timing for PPCS when one considers the variable age at which certain conditions manifest on ECG. The optimal age to introduce PPSC for athletes remains largely uncertain. Most consensus guidelines suggest PPCS start at age 12 when pubertal maturation and the expression of many disorders associated with SCD may begin. 1, 25, 26 What is more certain, and supported by the findings of Malhotra et al, is that screening should be repeated at regular intervals for the timely identification of phenotype progression. This is reflected in the ESC's recommendation that athletes should undergo regular ECG screening at minimum every 2 years. 25

While outcome‐based studies remain limited and the natural history of conditions associated with SCA/SCD remains largely unknown, PPCS inclusive of ECG is further supported by disease‐specific data, which demonstrates that early detection in conjunction with individualized risk stratification and management lowers mortality rates for certain cardiac conditions associated with SCA/SCD, including HCM and long QT syndrome. 27, 28 Consequently, the ESC recommends PPCS for all young athletes with the routine inclusion of ECG.

---

### Recommendations for multimodality cardiac imaging in patients with Chagas disease: a report from the American Society of Echocardiography in collaboration with the interAmerican association of echocardiography (ECOSIAC) and the cardiovascular imaging department of the Brazilian Society of Cardiology (DIC-SBC) [^113NQLad]. Journal of the American Society of Echocardiography (2018). Medium credibility.

Regarding diagnostic investigations for Chagas cardiomyopathy, more specifically with respect to ECG, ASE/BSC 2018 guidelines recommend to obtain an ECG in the initial evaluation to exclude conduction abnormalities (right bundle branch, left anterior fascicular, and AV block) and arrhythmias in all patients with newly diagnosed Chagas disease.

---

### Electrocardiographic artefact mimicking arrhythmic change on the ECG [^1129NDfi]. Emergency Medicine Journal (2003). Low credibility.

Artefact on electrocardiograms is a source of potential misdiagnosis and may lead to patients' receiving unnecessary treatments. This article present two cases that illustrate this problem, and will briefly look at known internal and external causes of artefact.

---

### Cardiac evaluation of young athletes: time for a risk-based approach? [^112zpdJB]. Clinical Cardiology (2020). Medium credibility.

Pre-participation cardiovascular screening (PPCS) is recommended by several scientific and sporting organizations on the premise that early detection of cardiac disease provides a platform for individualized risk assessment and management; which has been proven to lower mortality rates for certain conditions associated with sudden cardiac arrest (SCA) and sudden cardiac death (SCD). What constitutes the most effective strategy for PPCS of young athletes remains a topic of considerable debate. The addition of the electrocardiogram (ECG) to the medical history and physical examination undoubtedly enhances early detection of disease, which meets the primary objective of PPCS. The benefit of enhanced sensitivity must be carefully balanced against the risk of potential harm through increased false-positive findings, costly downstream investigations, and unnecessary restriction/disqualification from competitive sports. To mitigate this risk, it is essential that ECG-based PPCS programs are implemented by institutions with a strong infrastructure and by physicians appropriately trained in modern ECG standards with adequate cardiology resources to guide downstream investigations. While PPCS is compulsory for most competitive athletes, the current debate surrounding ECG-based programs exists in a binary form; whereby ECG screening is mandated for all competitive athletes or none at all. This polarized approach fails to consider individualized patient risk and the available sports cardiology resources. The limitations of a uniform approach are highlighted by evolving data, which suggest that athletes display a differential risk profile for SCA/SCD, which is influenced by age, sex, ethnicity, sporting discipline, and standard of play. Evaluation of the etiology of SCA/SCD within high-risk populations reveals a disproportionately higher prevalence of ECG-detectable conditions. Selective ECG screening using a risk-based approach may, therefore, offer a more cost-effective and feasible approach to PPCS in the setting of limited sports cardiology resources, although this approach is not without important ethical considerations.

---

### Fourth universal definition of myocardial infarction (2018) [^116oj6Tr]. European Heart Journal (2019). High credibility.

Clinical presentations of myocardial infarction — onset of myocardial ischemia is the initial step in MI and can be identified from the patient's history and the electrocardiogram (ECG); symptoms may include chest, upper extremity, mandibular, or epigastric discomfort, dyspnea, or fatigue, but they are not specific and MI may be atypical or silent. Very brief ischemia can cause cardiac troponin release and elevations, and the involved myocytes can subsequently die due to apoptosis. If myocardial ischemia is present clinically or detected by ECG changes together with myocardial injury manifested by a rising and/or falling cTn pattern, a diagnosis of acute MI is appropriate; if ischemia is not present clinically, elevated cTn may indicate acute myocardial injury (with rising and/or falling values) or more chronic ongoing injury (if unchanging). In suspected acute coronary syndrome ruled out for MI with normal cardiac biomarkers (≤ 99th percentile URL), unstable angina or an alternative diagnosis may be present, and these patients should be evaluated and treated accordingly.

---

### 2021 AHA / ACC / ASE / CHEST / SAEM / SCCT / SCMR guideline for the evaluation and diagnosis of chest pain: a report of the American college of cardiology / American Heart Association joint committee on clinical practice guidelines [^115ibqEV]. Circulation (2021). High credibility.

Electrocardiogram — supportive considerations: When an ECG is nondiagnostic, it "should be compared with previous ECGs, if available", and "a normal or unchanged ECG is reasonably useful but not sufficient at ruling out ACS", so decision‑making "should not be based solely on a single normal or nondiagnostic ECG". Masking conditions may occur, and "Up to 6% of patients with evolving ACS are discharged from the ED with a normal ECG", therefore "serial ECGs should be performed and management should be guided by new electrocardiographic changes or other diagnostic testing". When ST‑elevation is present on the initial ECG, "management should follow the prescribed STEMI treatment algorithms", and if ST depression is identified, "management should follow the NSTE-ACS guidelines". Because a normal ECG may accompany certain occlusions and posterior ischemia, which is "often 'electrically silent'; therefore, right-sided ECG leads should be considered when such lesions are suspected".

---

### Associations between common ECG abnormalities and out-of-hospital cardiac arrest [^1144J67X]. Open Heart (2019). Medium credibility.

Limitations

A major limitation of our study is the observational design. As such, our results should be interpreted only as associative and not causal relations to OHCA. In addition, the design precludes assurance that unmeasured potential confounders could have been present and biassed the results. Our study population is not necessarily generalisable to the general population. Our study population consisted of patients getting an ECG examination in a centralised primary care setting facility. The lack of generalisability is reflected in the higher incidence of OHCA, cardiovascular disease and all-cause mortality compared with the general population. However, this is not only a limitation as normal healthy people do not routinely undergo ECG recording and thus our study population is more likely to be representative of a real-life situation. Patients suffering from OHCA only included patients where a resuscitative attempt was performed excluding patients with late signs of death. Consequently, our incidence and risk estimations of OHCA are likely underestimations. Another major limitation of our study is that patient symptoms and the reasons why the ECG was requisitioned are unknown.

---

### Pitfalls in evaluating the low-risk chest pain patient [^115PLUvA]. Emergency Medicine Clinics of North America (2010). Low credibility.

Risk stratification and management of the patient with low-risk chest pain continues to be challenging despite the considerable effort of numerous investigators. Evidence exists that a specific subset of young patients can be defined as low risk in whom further testing may not be necessary. A high index of suspicion of acute coronary syndrome (ACS) and an understanding of the many, subtle, and atypical presentations of ischemic heart disease are required. The initial history, electrocardiogram (ECG), and biomarkers are important, but serial ECGs and biomarkers improve sensitivity in detecting ACS. Unless chest pain is clearly explained, objective testing, such as exercise treadmill testing, nuclear scintigraphy, stress echocardiography, or coronary computed tomography angiogram, should be considered before, or soon after, discharge.

---

### 2024 ESC guidelines for the management of chronic coronary syndromes [^114MSTvt]. European Heart Journal (2024). High credibility.

Regarding diagnostic investigations for coronary artery disease, more specifically with respect to ECG (resting), ESC 2024 guidelines recommend to obtain a resting 12-lead ECG in all patients reporting chest pain (unless an obvious non-cardiac cause is identified), particularly during, or immediately after, an episode suggestive of myocardial ischemia.

---

### Fourth universal definition of myocardial infarction (2018) [^115uwY23]. European Heart Journal (2019). High credibility.

Silent or unrecognized myocardial infarction — definition, frequency, and confirmation of new Q wave MI. Asymptomatic patients who develop new Q wave criteria for MI on follow-up ECG or show imaging evidence of MI not attributable to an intercurrent revascularization procedure or an ACS admission should be termed "silent or unrecognized MI". In studies using serial ECG analysis, silent or unrecognized Q wave MI accounted for 9% to 37% of all non-fatal MI events. The diagnosis of a new silent Q wave MI should be confirmed by a repeat ECG recording with correct lead placement, focused questioning about potential interim ischemic symptoms, or by an imaging study.

---

### 2017 AHA / ACC / HRS guideline for management of patients with ventricular arrhythmias and the prevention of sudden cardiac death: executive summary: a report of the American college of cardiology / American Heart Association task force on clinical practice guidelines and the Heart Rhythm Society [^114xwTq3]. Journal of the American College of Cardiology (2018). Medium credibility.

Postmortem evaluation of sudden cardiac death (SCD) — supportive evidence and family screening: A comprehensive postmortem protocol has been recommended for the routine evaluation of subjects (typically < 40 years of age) who die suddenly without a prior diagnosis and with circumstances of death that could be reasonably implicated in unexpected SCD; specialized centers reported conduction system findings in 22% of cases and misdiagnosis of cardiomyopathy in 37% of referred structurally normal cases. In one study spanning ages < 1 year to > 80 years (mean 38.2 years; median 38 years), peak SCD incidence occurred between 31 and 60 years with a 5- to 7-fold excess of males/females; overall causes included ischemic heart disease 42%, viral myocarditis 12%, and cardiomyopathy 5%, with 15% unexplained by autopsy; in the subgroup ≤ 35 years of age, 13.5% were attributed to ischemic heart disease and 24.9% were unexplained, whereas in those > 55 years only 0.8% were unexplained. In patients who die suddenly despite an implantable cardioverter-defibrillator (ICD), ICD interrogation is important to confirm proper device functioning and to inform mechanism of death. In first-degree relatives of decedents with sudden unexpected death, comprehensive cardiac screening may identify a probable heritable cause in up to 30% of cases, genetic testing should be targeted to results of the initial evaluation, and selected first-degree relatives may show inherited conditions in 4% to 30% of families.

---

### Magnitude and consequences of missing the acute infarct-related circumflex artery [^111KGAVN]. American Heart Journal (2009). Low credibility.

Emergent reperfusion strategies are integral to providing optimal patient outcomes in the setting of acute coronary artery occlusion. ST-segment elevation on the surface 12-lead electrocardiogram, although specific as a surrogate marker, is insensitive to acute posterior circulation coronary artery occlusion. Studies of non-ST-segment elevation acute coronary syndrome consistently identify patients who have epicardial vessel occlusion at the time of initial angiography, which is usually delayed for hours or days after the initial presentation. In addition, studies of ST-segment elevation myocardial infarction often divulge a disparity in identification of the infarct-related artery, with an underrepresentation of the left circumflex artery. Taken together, it is likely that many patients with left circumflex artery occlusion are "missed" during the early phases of myocardial infarction due to the electrocardiographically silent nature of the posterior territory, resulting in delayed myocardial salvage and worse cardiovascular outcomes. In this review, we report on the magnitude of missed left circumflex infarction and the consequences of this delay in diagnosis. We review the electrocardiographic findings of left circumflex occlusion and discuss strategies to enhance early identification. Heightened awareness of this clinical scenario and the available methods to avoid missing this elusive diagnosis are imperative in our quest to further improve the outcomes of patients with acute myocardial infarction.

---

### Updated guidelines for perioperative cardiovascular… [^116VSLYE]. AAFP (2002). Low credibility.

Specific Preoperative Cardiovascular Conditions HYPERTENSION Stage 3 hypertension should be controlled preoperatively. Effective control often can be achieved with outpatient treatment for several days to weeks before surgery. For more urgent surgery, blood pressure can be lowered with rapid-acting agents. Antihypertensive therapy is continued through the perioperative period. VALVULAR HEART DISEASE To lower the risk of perioperative heart failure or shock, symptomatic stenotic lesions often require percutaneous valvotomy or valve replacement before noncardiac surgery. Patients with symptomatic regurgitant valvular disease may be stabilized with intensive medical therapy and monitoring before surgery, with definitive treatment given later. When delaying noncardiac surgery may have serious consequences, medical therapy and monitoring are appropriate. Exceptions may include severe valvular regurgitation with a reduction in left ventricular function.

In these patients, limited hemodynamic reserve increases the likelihood of destabilization during perioperative stresses. MYOCARDIAL DISEASE Patients with dilated and hypertrophic cardiomyopathy are at increased risk for perioperative heart failure. In these patients, preoperative management is directed at maximizing hemodynamic status. An estimate of hemodynamic reserve can be helpful in anticipating potential complications. Intensive medical therapy and monitoring are provided after surgery. ARRHYTHMIAS Patients with arrhythmias or cardiac conduction disturbance should be evaluated for underlying cardiopulmonary disease, metabolic abnormality, or drug toxicity. Treatment for the underlying cause of a symptomatic or hemodynamically significant rhythm disturbance should be initiated; the arrhythmia should also be treated.

Aggressive perioperative monitoring or treatment of frequent premature ventricular beats and asymptomatic nonsustained ventricular tachycardia generally is not necessary. These rhythm disturbances have not been associated with an increased risk of nonfatal myocardial infarction or cardiac death. PACEMAKERS AND IMPLANTABLE CARDIOVERTER-DEFIBRILLATORS The evaluation of an implantable pacemaker or automatic implantable cardioverter-defibrillator depends on the urgency of surgery, the pacemaker leads, the electrocautery, the distance between the pacemaker and electrocautery, and pacemaker dependency. Immediately before surgery, an ICD should be programmed off. The device should be programmed on again after surgery. Supplemental Preoperative Evaluation Specific recommendations depend on the individual patient and circumstance. The exercise ECG is the test of choice in most ambulatory patients.

The ACC/AHA classifications of evidence used to summarize the indication for a particular therapy or treatment. RESTING LEFT VENTRICULAR FUNCTION Perioperative ischemic events are not consistently predicted by the resting left ventricular function. Recommendations for preoperative noninvasive evaluation of left ventricular function are as follows: Class I: current or poorly controlled heart failure. Class IIa: previous heart failure; dyspnea of unknown origin. Class III: as a routine test of left ventricular function in patients without previous heart failure. 12-LEAD RESTING ECG Some ECG abnormalities are clinical predictors of increased perioperative and long-term cardiovascular risk in patients at clinically intermediate or high risk who are undergoing intermediate- or high-risk surgical procedures.

---

### HbAscreening for new onset diabetes following acute coronary syndrome: is it a worthwhile test in clinical practice? [^117KBcZN]. Journal of Diabetes and Metabolic Disorders (2017). Low credibility.

OGTT at 3 months

There were 62 patients scheduled to attend an OGTT at 3 months, this included 57 patients with a repeat intermediate HbA 1c and 5 patients who attended despite missing their repeat HbA 1c test. OGTT result was normal in 28 (45.2%) patients, impaired in 12 (19.4%) patients, and diagnosed diabetes in 5 (8.1%) patients. A total of 17 (27.4%) patients did not attend the OGTT. Following OGTT, patients with an impaired or normal result, or those who were not tested were all still classified as pre-diabetes due to the prior intermediate repeat HbA 1c result. Therefore a letter was sent to their GP advising the patient to have annual HbA 1c levels or OGTT checked.

Final outcome

The end result of screening process diagnoses pre-diabetes in 57 (14.3%) patients and Type 2 diabetes in 43 (10.8%) patients. During the study 28 (7%) patients could not be classified; 6 (1.5%) patients died during the study and 22 (5.5%) patients were missing either initial or repeat HbA 1c and were subsequently lost to follow up.

---

### Meta-analysis on the effectiveness of ECG screening for conditions related to sudden cardiac death in young athletes [^112cmMg3]. Clinical Pediatrics (2023). Medium credibility.

Conclusion

By conducting a meta-analysis with a large number of patients, we have shown that modern ECG criteria improve the odds of detecting cardiac disease in young athletes as compared with history and physical examinations. Our data show that the odds of detecting cardiac disease with a pre-participation ECG are statistically significant (odds ratio of 60, P < .001) and higher than the odds of detecting cardiac disease with H&P (odds ratio of 3.4, P = .076). We also found that the odds of detecting conditions associated with SCD with a pre-participation ECG are statistically significant (odds ratio of 159, P < .001) and higher than the odds of detecting conditions associated with SCD with H&P (odds ratio of 2.9, P = .078). We conclude that using a 12-lead ECG as a screening tool improves the odds of identifying cardiac disease and SCD in young athletes.

---

### Fourth universal definition of myocardial infarction (2018) [^1112igCX]. European Heart Journal (2019). High credibility.

Electrocardiographic detection of myocardial infarction — an electrocardiogram (ECG) "should be acquired and interpreted promptly (ie, target within 10 minutes) after first medical contact", and "prehospital ECGs reduce the time to diagnosis and treatment, and can facilitate the triage of STEMI patients… if within the recommended time interval (120 minutes from STEMI diagnosis)". For ongoing symptoms or a nondiagnostic tracing, "recording several standard ECGs… at 15–30 minute intervals for the initial 1–2 hours, or the use of continuous computer-assisted 12-lead ECG recording… is reasonable". Certain patterns carry prognostic/diagnostic implications: "ST-segment depression ≥ 1 mm in 6 leads… is suggestive evidence of multivessel disease or left main disease", while a comparison tracing helps but "should not delay the decision for treatment". Early ischemic changes include "increased hyperacute T wave amplitude… in at least 2 contiguous leads", and infarction evolution is reflected as "the development of new Q waves" indicating necrosis that "starts minutes/hours after the myocardial insult", with "transient Q waves" sometimes seen during acute ischemia or "(rarely) during acute MI with successful reperfusion".

---

### Inability to obtain deferred consent due to early death in emergency research: effect on validity of clinical trial results [^114Jvzk9]. Intensive Care Medicine (2010). Low credibility.

Purpose

To illustrate the impact on the validity of trial results due to excluding patients from a randomized controlled trial for whom no deferred consent could be obtained after randomization because study procedures had already been finished.

Methods

The unadjusted and adjusted primary outcome measures of a recent randomized controlled multicentre study in the field of intensive care medicine were compared, including (n = 348) or excluding (n = 289) patients with missing deferred consent.

Results

Thirty-nine patients (11%) died early, before the patient or his/her proxy could be approached and consent be obtained. In another 20 patients (6%), it was not possible to inform proxies and ask consent within the period of study procedures. A significant treatment effect (p = 0.006) in the adjusted analysis became non-significant (p = 0.35) when the patients with missing deferred consent were excluded.

Conclusions

Exclusion of patients without obtained deferred consent can reduce statistical power, introduce selection bias, make randomization asymmetrical, decrease external validity and thereby jeopardize study results. This may have implications for emergency research in various disciplines.

---

### Novel tech throws knock-out punch to ECG improving GP referral decisions to cardiology [^111RW9jU]. Open Heart (2022). Medium credibility.

Introduction

In the last decade, cardiovascular disease (CVD) has become one of the factors which threaten human healthand is the main cause of death in the world. According to a report presented by the Global Burden of Disease Study, these diseases were responsible for 31.8% of all deaths worldwide. Representing a high impact in morbidity and cost to society, there is an urgent need to detect early signs of CVD including heart failure (HF) one of the most difficult to diagnose. In one multiperspective study 'the difficulties with diagnosis, unclear illness perception, and management disparity' were identified as critical aspects that may impact management of CVD which put in evidence the problem of the effective diagnosis of such life-threatening diseases.

Misdiagnosis or delay in diagnosis of CVD is correlated with lengthened time to treatment, increased hospital stays, including high percentage of readmission, and a higher death rate which brings us to the point that 'the early diagnosis is imperative'.

Primary care is the initial contact pointwith the patient where CVD is first presented and suspected but all too often can go unnoticed or underdiagnosed, sometimes for many months. Underdiagnosis is not uncommon, as studies have found high prevalence rates of CVD in high-risk populations in primary care, such as elders short of breath, type 2 diabetes or chronic obstructive pulmonary diseases (COPD), make the process of identification of CVD all the more difficult. A review of malpractice claims in the USA revealed that failure to diagnose, which included failure, delay and wrong diagnosis, was responsible for over 41% of all claims against general physicians (GPs) and 48% against nurse practitioners. Further review of claims unmasked a possible common factor, an 'inconclusive ECG'. Compouding the situation, every day, a large number of people with chest pain refer to heart centres with half of them without a real cardiac problem.

---

### Electrocardiography… [^114h77px]. Wikipedia (2002). Low credibility.

- Cardiac rhythm disturbances, such as atrial fibrillation and ventricular tachycardia;
- Inadequate coronary artery blood flow, such as myocardial ischemia and myocardial infarction;
- and electrolyte disturbances, such as hypokalemia. Traditionally, "ECG" usually means a 12-lead ECG taken while lying down as discussed below. However, other devices can record the electrical activity of the heart such as a Holter monitor but also some models of smartwatch are capable of recording an ECG. ECG signals can be recorded in other contexts with other devices. This orderly pattern of depolarization gives rise to the characteristic ECG tracing. To the trained clinician, an ECG conveys a large amount of information about the structure of the heart and the function of its electrical conduction system.

Among other things, an ECG can be used to measure the rate and rhythm of heartbeats, the size and position of the heart chambers, the presence of any damage to the heart's muscle cells or conduction system, the effects of heart drugs, and the function of implanted pacemakers. Medical uses The overall goal of performing an ECG is to obtain information about the electrical functioning of the heart. Medical uses for this information are varied and often need to be combined with knowledge of the structure of the heart and physical examination signs to be interpreted. Some indications for performing an ECG include the following:

- Chest pain or suspected myocardial infarction, such as ST elevated myocardial infarction or non-ST elevated myocardial infarction
- Symptoms such as shortness of breath, murmurs, fainting, seizures, funny turns, or arrhythmias including new onset palpitations or monitoring of known cardiac arrhythmias.
- Medication monitoring and management of overdose
- Electrolyte abnormalities, such as hyperkalemia
- Perioperative monitoring in which any form of anesthesia is involved. This includes preoperative assessment and intraoperative and postoperative monitoring. ECGs can be recorded as short intermittent tracings or continuous ECG monitoring. Continuous monitoring is used for critically ill patients, patients undergoing general anesthesia, and patients who have an infrequently occurring cardiac arrhythmia that would unlikely be seen on a conventional ten-second ECG. Continuous monitoring can be conducted by using Holter monitors, internal and external defibrillators and pacemakers, and/or biotelemetry. Screening For adults, evidence does not support the use of ECGs among those without symptoms or at low risk of cardiovascular disease as an effort for prevention.

This is because an ECG may falsely indicate the existence of a problem, leading to misdiagnosis, the recommendation of invasive procedures, and overtreatment. However, persons employed in certain critical occupations, such as aircraft pilots, may be required to have an ECG as part of their routine health evaluations. Hypertrophic cardiomyopathy screening may also be considered in adolescents as part of a sports physical out of concern for sudden cardiac death.
- ECG voltages measured across the body are very small. This low voltage necessitates a low noise circuit, instrumentation amplifiers, and electromagnetic shielding.
- Simultaneous lead recordings: earlier designs recorded each lead sequentially, but current models record multiple leads simultaneously. Most modern ECG machines include automated interpretation algorithms. This analysis calculates features such as the PR interval, QT interval, corrected QT interval, PR axis, QRS axis, rhythm and more.

---

### 2020 APHRS / HRS expert consensus statement on the investigation of decedents with sudden unexplained death and patients with sudden cardiac arrest, and of their families [^115EBVAq]. Heart Rhythm (2021). High credibility.

Sudden cardiac arrest (SCA) survivors — baseline investigations include the following, with recommendation language preserved: Blood samples for electrolytes, toxicology, and EDTA blood stored for future genetic testing are recommended for all SCA survivors on admission to hospital. Retrieval of recordings from cardiac implantable electronic devices (CIEDs) and wearable monitors is recommended for all SCA survivors, while retrieval of recordings from automated external defibrillators (AEDs) and ambulance services may be useful for all SCA survivors. Recording of 12-lead electrocardiograms (ECGs) during sinus rhythm and, if possible, during arrhythmia, is recommended for all SCA survivors; a high precordial lead ECG is recommended in all undiagnosed SCA survivors to increase detection of a type 1 Brugada ECG pattern; and continuous ECG monitoring is recommended for all SCA survivors during the initial hospital stay. A signal-averaged ECG may be useful in SCA survivors to aid in the diagnosis of arrhythmogenic cardiomyopathy. Echocardiography is recommended for evaluation of cardiac structure and function in all SCA survivors. Cardiac magnetic resonance (CMR) with late gadolinium enhancement is recommended for evaluation of acute or chronic myocardial disease in SCA survivors without a clear underlying cause, and CMR can be useful when the etiology is primary electrical or there is evidence for acute cardiac ischemia. Coronary imaging is recommended in all adult SCA survivors, to exclude coronary artery disease, dissection, or anomalies not considered fully at first presentation, and in select younger cases.

---

### European consensus-based recommendations for the diagnosis and treatment of rare paediatric vasculitides-the SHARE initiative [^114UppDv]. Rheumatology (2019). High credibility.

Regarding specific circumstances for myocarditis, more specifically with respect to pediatric patients (patients with vasculitides), SHARE initiative 2019 guidelines recommend to obtain a careful assessment of the heart, including ECG and echocardiography, in all patients with eosinophilic granulomatosis with polyangiitis as eosinophilic myocarditis is an important and potentially fatal complication.

---

### Screening for cardiovascular disease risk with electrocardiography: US preventive services task force recommendation statement [^114M8Q6v]. JAMA (2018). Excellent credibility.

Electrocardiography (ECG) screening tests and downstream management are summarized as follows: resting ECG records cardiac electrical activity while the patient is at rest over a short period, and exercise ECG records cardiac electrical activity during physical exertion, often at a prespecified intensity level; the most common method of exercise ECG is the treadmill test; both resting and exercise ECG look for markers of previous myocardial infarction, myocardial ischemia, and other cardiac abnormalities such as left ventricular hypertrophy, bundle branch block, or arrhythmia that may be associated with CVD or predict future CVD events; asymptomatic adults at increased risk of CVD events are usually treated with a combination of diet and exercise modifications, lipid-lowering medications, aspirin, hypertension management, and interventions to encourage tobacco cessation; related USPSTF prevention recommendations include screening for high blood pressure, use of statins, counseling on smoking cessation, counseling to promote healthful diet and physical activity, and low-dose aspirin use in certain persons at increased risk of CVD events.

---

### 2023 ESC guidelines for the management of acute coronary syndromes [^11561HpV]. European Heart Journal (2023). High credibility.

Regarding diagnostic investigations for ST-elevation myocardial infarction, more specifically with respect to ECG, ESC 2023 guidelines recommend to obtain an additional 12-lead ECG in patients with recurrent symptoms or diagnostic uncertainty.

---

### Routine electrocardiogram screening and cardiovascular disease events in adults [^113QsiC3]. JAMA Internal Medicine (2024). High credibility.

Limitations

There are several limitations in the study. First, a consensus regarding the classification of major and minor ECG abnormalities remains elusive. In fact, the classification of major and minor ECG abnormalities has varied across studies. We observed that multiple ECG abnormalities that are often considered minor were associated with CVD risk. Therefore, additional evaluation of the stratification of ECG abnormalities in risk assessment is warranted. Second, as we defined CVD outcomes based on ICD-10 codes, we cannot rule out the possibility that outcome was misclassified (ie, patients with ECG abnormality are likely to obtain diagnostic codes of CVD, leading to bias away from the null). Third, we included all-cause death in our primary composite outcome because causes of death were not available in the database, which requires additional evidence focusing on CVD death. Fourth, the research may exhibit self-selection bias as the cohort consisted solely of individuals who have undergone annual health screening, potentially excluding lower socioeconomic groups who are less inclined to participate in such screenings. We observed a higher incidence rate for the primary outcome among individuals without ECG at baseline compared with our analytical samples. Fifth, because of the lack of data on follow-up examinations (eg, echocardiogram reports), the presence of complications, and other relevant medical notes, we could not assess the potential influence of ECG results on clinical decisions, indications for follow-up examinations, or the potential harm caused by ECGs. Sixth, our findings of the working-age population may not be generalizable to other demographic cohorts.

---

### ACC / AHA release guidelines on perioperative cardiovascular… [^114PSKz2]. AAFP (2008). Low credibility.

To provide an outline for considering cardiac risk in a variety of patients and surgical procedures, the American College of Cardiology and the American Heart Association created guidelines on perioperative cardiovascular evaluation and care for patients undergoing noncardiac surgery. Preoperative evaluation is done to assess a patient's current medical status; to provide recommendations about the evaluation, treatment, and risk of cardiac problems over the perioperative period; and to provide a risk profile that may affect cardiac outcomes and that can be used when choosing treatment. Patient History The patient history is important in determining cardiac or comorbid diseases that would put the patient at high surgical risk. The history should include questions to identify serious cardiac conditions, which may require intensive management and delay or cancellation of nonurgent surgeries. Other history includes whether the patient has had a pacemaker, implantable cardioverter defibrillator, or past orthostatic intolerance. Modifiable risk factors for coronary heart disease and evidence of associated disease should be recorded, along with recent changes in symptoms, medications, and use of alcohol or illicit drugs. The patient's functional capacity, which has been shown to correlate well with maximal oxygen uptake on treadmill testing, should also be reviewed. The rightsholder did not grant rights to reproduce this item in electronic media. For the missing item, see the original print version of this publication.

Cardiac Risk Stratification Identifying the cardiac risk of noncardiac surgery is important in patients who have clinical risk factors. The type of surgery may identify a patient who has a higher probability of underlying heart disease and higher perioperative morbidity and mortality. The surgery may also be associated with coronary or myocardial stressors; intensity of these stressors helps to determine the probability of perioperative cardiac events. Perioperative morbidity related to noncardiac surgical procedures ranges from 1 to 5 percent. Figure 1 shows the stepwise approach to perioperative cardiac assessment. The rightsholder did not grant rights to reproduce this item in electronic media.

For the missing item, see the original print version of this publication. Assessment of LV Function PREOPERATIVE NONINVASIVE EVALUATION Nine studies have shown a positive correlation between decreased preoperative ejection fraction and postoperative morbidity or mortality. In a study of 339 men with ischemic heart disease or risk factors for CHD, a left ventricular ejection fraction of less than 40 percent was associated with all adverse perioperative outcomes, including cardiac death, nonfatal myocardial infarction, unstable angina, congestive heart failure, and ventricular tachycardia. In a multivariable analysis, which included the risk factors of coronary artery disease or history of congestive heart failure, LVEF and regional wall-motion score did not add significant independent value in predicting individual events.

---

### Inability to obtain deferred consent due to early death in emergency research: effect on validity of clinical trial results [^11462ZrA]. Intensive Care Medicine (2010). Low credibility.

Results

The study population consisted of 348 patients; 39 patients (11%) died early, before the patient or his/her proxy could be approached and consent be obtained. In another 20 patients (6%), it was not possible to inform proxies and ask consent within the period of study procedures (no family available, non-Dutch-speaking family, transfer to other hospital etc.). Table 1 presents baseline characteristics according to obtained consent status. There were more patients with missing consent due to early death in the control group than in the lactate group [14.7% (26/177) versus 7.6% (13/171), p = 0.042]. The number of patients in each group with missing consent due to other reasons (than early death) was similar [control group 6.8% (12/177) versus lactate group 4.7% (8/171), p = 0.492].

Table 1
Baseline characteristics according to consent status

Values are mean ± standard deviation (SD) unless otherwise specified

✱ p -Value for comparison between severe sepsis, septic shock, neurologic, cardiac arrest and other non-sepsis subgroups

Table 2 presents the results of the unadjusted and adjusted primary outcome analyses. A significant treatment effect (p = 0.006) in the adjusted analysis even became non-significant (p = 0.35) when patients with missing deferred consent were excluded. In addition, when adding the variable "missing consent" to the multivariable Cox proportional-hazards model, the treatment effect of lactate-guided therapy was reduced from 0.006 to 0.063. When adding the variable "missing consent due to early death", the p value was reduced to 0.210. When calculating interaction, we could not demonstrate a significant difference in the unadjusted treatment effect between those with and without missing consent.

Table 2
Mortality with and without patients with missing deferred consent

✱ p -Value for interaction between consent status (missing or obtained consent) and treatment effect (Breslow–Day test of homogeneity): 0.59

---

### 2017 ISHNE-HRS expert consensus statement on ambulatory ECG and external cardiac monitoring / telemetry [^111gPeEe]. Heart Rhythm (2017). Medium credibility.

ST elevation myocardial infarction (STEMI) prehospital triage with transmitted ECG — system requirements and impact: Early reperfusion via percutaneous coronary intervention (PCI) remains the critical therapeutic intervention, and the emergency transport system must be capable of recording a 12‑lead ECG and transmitting the ECG to a center that can provide skilled confident interpretation. In Denmark, a mature system processed about 4,000 ECGs per year, and 81% of prehospital diagnoses of STEMI underwent emergent PCI with an acceptable low false‑positive rate; this rapid triage has been associated with a decline in 30‑day mortality rates.

---

### 2020 APHRS / HRS expert consensus statement on the investigation of decedents with sudden unexplained death and patients with sudden cardiac arrest, and of their families [^111RJRsq]. Heart Rhythm (2021). High credibility.

Sudden cardiac death (SCD)/sudden cardiac arrest (SCA) evaluation — genetic testing and clinical assessment are outlined as follows: For victims of SCD or survivors of cardiac arrest where the phenotype is not known, arrhythmia syndrome–focused genetic testing may help arrive at a secure diagnosis, whereas wider testing without careful consideration of the implications of indeterminate results by experienced clinicians may only serve to add uncertainty and lead to misinterpretation of results. For the investigation of SCA survivors, essential inquiry includes detailed personal and family history, witness accounts, physical examination, multiple electrocardiograms (ECGs), and cardiac imaging; ambulatory monitoring and/or provocative testing (exercise, pharmacological, and invasive electrophysiological) may provide additional useful information, and a sample suitable for future DNA testing should be taken early in the patient's course and stored. Genetic investigation of SCA survivors is best undertaken at a center with multidisciplinary care infrastructure and should focus on likely candidate genes known to be causally related to the suspected phenotype; in some cases, genetic evaluation without a suspected phenotype may be undertaken with appropriate genetic counseling, although genetic evaluation of patients with a known nongenetic cause of cardiac arrest is discouraged. The investigation of the families of victims of sudden unexplained death (SUD) and survivors of SCA should include clinical and, if known, genetic cascade testing; if the cause of SUD (or rarely, SCA) is unknown, then clinical investigation of first-degree relatives may include physical examination, ECGs, cardiac imaging, ambulatory monitoring, and provocative testing (exercise, pharmacological, and rarely invasive electrophysiological) with multidisciplinary team supervision, and follow-up and periodic re-evaluation are important and are directed by initial findings.

---

### ACC / AHA / ESC 2006 guidelines for management of patients with ventricular arrhythmias and the prevention of sudden cardiac death: a report of the American college of cardiology / American Heart Association task force and the European Society of Cardiology committee for practice guidelines (writing committee to develop guidelines for management of patients with ventricular arrhythmias and the prevention of sudden cardiac death) [^113Gi5pq]. Journal of the American College of Cardiology (2006). Medium credibility.

Anorexia nervosa — cardiac risks and reversibility: "Reported mortality rates in anorexia nervosa fluctuate from 5% to 20%, but the actual rate is likely to be around 6% (581)". Mechanisms include that "Prolonged periods of starvation result in not only anatomical abnormalities such as cardiac muscle atrophy and pericardial effusions (582), but also ECG abnormalities, including sinus bradycardia and prolongation of the QTc interval, an effect that is likely to be compounded by the presence of concurrent electrolyte disturbances (582–584)". Many findings are reversible because "Most of the cardiac manifestations of anorexia nervosa are completely reversible by appropriate re-feeding (582)". The "re-feeding syndrome" is defined and timed risks noted: "The "re-feeding syndrome" is characterized by cardiac, neurological, and hematological complications triggered by fluid and electrolyte disturbances during the re-feeding of chronically starved individuals (585)". and "Cardiac complications of this syndrome usually occur within the first week of re-feeding and are typically associated with severe degrees of malnutrition (less than 70% ideal body weight) (586), hypophosphatemia (587), and total parenteral nutrition (588)".

---

### 2020 APHRS / HRS expert consensus statement on the investigation of decedents with sudden unexplained death and patients with sudden cardiac arrest, and of their families [^112M5PBp]. Heart Rhythm (2021). High credibility.

ACC/AHA recommendation system — applying Class of Recommendation (COR) and Level of Evidence (LOE) is defined as follows: Class 1 (strong) "Benefit > > > Risk", with suggested phrases including "Is recommended", "Is indicated/useful/effective/beneficial", "Should be performed/administered/other", and comparative phrases "Treatment/strategy A is recommended/indicated in preference to treatment B" and "Treatment A should be chosen over treatment B". Class 2a (moderate) "Benefit > > Risk", with "Is reasonable", "Can be useful/effective/beneficial", and comparative phrases "Treatment/strategy A is probably recommended/indicated in preference to treatment B" and "It is reasonable to choose treatment A over treatment B". Class 2b (weak) "Benefit ≥ Risk", with "May/might be reasonable", "May/might be considered", and "Usefulness/effectiveness is unknown/unclear/uncertain or not well-established". Class 3: No Benefit (moderate) "Benefit = Risk", with "Is not recommended", "Is not indicated/useful/effective/beneficial", and "Should not be performed/administered/other". Class 3: Harm (strong) "Risk > Benefit", with "Potentially harmful", "Causes harm", "Associated with excess morbidity/mortality", and "Should not be performed/administered/other". LOE categories include Level A with "High-quality evidence‡ from more than 1 RCT", "Meta-analyses of high-quality RCTs", and "One or more RCTs corroborated by high-quality registry studies"; Level B-R (Randomized) with "Moderate-quality evidence‡ from 1 or more RCTs" and "Meta-analyses of moderate-quality RCTs"; Level B-NR (Nonrandomized) with "Moderate-quality evidence‡ from 1 or more well-designed, well-executed nonrandomized studies, observational studies, or registry studies" and "Meta-analyses of such studies"; Level C-LD (Limited Data) with "Randomized or nonrandomized observational or registry studies with limitations of design or execution", "Meta-analyses of such studies", and "Physiological or mechanistic studies in human subjects"; and Level C-EO (Expert Opinion) with "Consensus of expert opinion based on clinical experience". The table notes that "COR and LOE are determined independently (any COR may be paired with any LOE)".

---

### 2023 ESC guidelines for the management of acute coronary syndromes [^116GDdZa]. European Heart Journal (2023). High credibility.

Regarding diagnostic investigations for non-ST-elevation myocardial infarction, more specifically with respect to ECG, ESC 2023 guidelines recommend to obtain a 12-lead ECG as soon as possible at first medical contact with a target of < 10 minutes.

---

### The ASAM / AAAP clinical practice guideline on the management of stimulant use disorder [^116v71N2]. Journal of Addiction Medicine (2024). High credibility.

Cardiac screening and electrocardiogram (ECG) considerations — clinical questions ask what contextual factors and implementation strategies may influence the effects of screening for cardiac disorders and whether there is a subpopulation that would particularly benefit from routine ECG.

---

### Unexpected death within 72 hours of emergency department visit: were those deaths preventable? [^117E77tX]. Critical Care (2015). Low credibility.

Table 1
Included patients with early death

SD, standard deviation; EMS, emergency medical services; BP, blood pressure; IQR, interquartile range.

Figure 1
Flow chart. ED, emergency department.

Death occurred in the ED or ED observational unit in 26 cases (55%), in the medical ward in 19 cases (40%), and in the operating room in four cases (9%).

The details of the main medical errors that may have contributed to the death of the patients are listed in Table 2. Among the 24 patients who had a preventable death, we counted a total of 54 errors - a median of two per patients. A severe delay or the absence of detection and recommended treatment for severe sepsis were the main medical errors in nine patients (38%). Undertriage or under-recognition of acutely ill patients that required close monitoring was considered to be the main error that contributed to the death of the patients in four cases (16%). The experts found that a provider other than the emergency physician was involved in a fatal error in seven cases: namely an orthopedic surgeon (n = 3), a triage nurse (n = 2) and an ICU physician (n = 2).

Table 2
Preventable unexpected death

ED, emergency department; ICU, intensive care unit; CT, computed tomography; ECG, electrocardiography; GI, gastrointestinal; COPD, chronic obstructive pulmonary disease.

---

### 2023 ESC guidelines for the management of cardiomyopathies [^116PtcSm]. European Heart Journal (2023). High credibility.

Regarding screening and diagnosis for arrhythmogenic right ventricular cardiomyopathy, more specifically with respect to screening of family relatives (follow-up), ESC 2023 guidelines recommend to obtain initial clinical evaluation using a multiparametric approach, including ECG and cardiac imaging, in first-degree relatives when no pathogenic/likely pathogenic variant is identified in the proband or genetic testing is not obtained.

---

### 2020 APHRS / HRS expert consensus statement on the investigation of decedents with sudden unexplained death and patients with sudden cardiac arrest, and of their families [^1159TZ9p]. Heart Rhythm (2021). High credibility.

Investigation of sudden cardiac arrest survivors — baseline investigations emphasize obtaining blood tests and toxicology at presentation; in OHCA the use of AEDs increases survival and the sensitivity for the diagnosis of cardiac rhythm at the time of arrest is about 99%, so routine inspection of AED recordings may improve the quality of diagnosis; the 12‑lead ECG in sinus rhythm or during arrhythmia recurrence is fundamental and should be repeated daily during recovery; in addition to standard ECG, a signal‑averaged ECG may demonstrate late potentials and two or more abnormalities in the absence of a prolonged QRS duration (≥ 110 ms) on the standard ECG is a minor diagnostic criterion for arrhythmogenic cardiomyopathy; a high precordial lead ECG is an inexpensive tool to increase detection of Brugada syndrome pattern.

---

### 2021 ESC guidelines for the diagnosis and treatment of acute and chronic heart failure [^1111MQuw]. European Heart Journal (2021). High credibility.

Regarding diagnostic investigations for heart failure, more specifically with respect to ECG, ESC 2021 guidelines recommend to obtain 12-lead ECG in all patients with suspected chronic HF.

---

### 2022 ESC guidelines for the management of patients with ventricular arrhythmias and the prevention of sudden cardiac death [^116RP5Xa]. European Heart Journal (2022). High credibility.

Regarding screening and diagnosis for arrhythmogenic right ventricular cardiomyopathy, more specifically with respect to screening of family relatives, clinical and genetic testing, ESC 2022 guidelines recommend to obtain an ECG and echocardiogram in a first-degree relative of patients with ARVC.

---

### AMSSM position statement on cardiovascular preparticipation screening in athletes: current evidence, knowledge gaps, recommendations, and future directions [^1164hBRf]. Clinical Journal of Sport Medicine (2016). Medium credibility.

AMSSM cardiovascular preparticipation screening — Table 3 models number needed to screen (NNS) by athlete risk: to prevent one death in the first year, NNS is 120 000 for high school athletes (annual sudden cardiac death [SCD] risk "1 in 80 000"), 75 000 for college athletes ("1 in 50 000"), and 24 000 for male, African American college athletes ("1 in 16 000"); over a 4-year career, corresponding NNS are 30 000, 19 000, and 6 000, respectively. Assumptions include "Prevalence of detectable cardiac conditions using ECG = 0.3%", that "ECG detectable conditions represent 60% of all causes of SCD", that management "effectively mitigates risk of SCD", and that 4-year values are an "extrapolation" assuming the relative risk is the same each year.

---

### Sudden cardiac death prediction and prevention: report from a National Heart, Lung, and Blood Institute and Heart Rhythm Society workshop [^115ur7i7]. Circulation (2010). Medium credibility.

Sudden cardiac death prediction paradigm — multifactor approach and ICD-endpoint study limitations: Given the complexity of the SCD phenotype and its overlap with coronary artery disease, congestive heart failure, and diabetes mellitus, it is likely that any prediction of risk will involve a combination of risk factors and/or tests rather than a single marker or test. One approach has been to study device therapies as end points in implantable cardioverter-defibrillator (ICD) cohorts, but the design and population are likely to limit useful findings to selecting ICD candidates relatively late in the natural history of LV dysfunction and will not contribute importantly to early detection of risk factors. In a significant proportion of patients, SCD is likely to be triggered by plaque rupture and acute myocardial infarction, further complicating early prediction.

---

### 2022 ESC guidelines for the management of patients with ventricular arrhythmias and the prevention of sudden cardiac death [^114NYS3V]. European Heart Journal (2022). High credibility.

Regarding specific circumstances for ventricular arrhythmias, more specifically with respect to patients with dilated cardiomyopathy, evaluation, ESC 2022 guidelines recommend to obtain an ECG and echocardiography in a first-degree relative of patients with dilated cardiomyopathy/hypokinetic non-dilated cardiomyopathy if:

- the index patient was diagnosed at < 50 years of age or has clinical features suggestive of an inherited cause

- there is a family history of dilated cardiomyopathy/hypokinetic non-dilated cardiomyopathy or premature unexpected sudden death.

---

### Guidance for rebooting electrophysiology through the COVID-19 pandemic from the Heart Rhythm Society and the American Heart Association electrocardiography and arrhythmias committee of the council on clinical cardiology [^116rySdW]. Circulation: Arrhythmia and Electrophysiology (2020). High credibility.

Viral testing platforms and retesting considerations: The test platforms now available have different advantages and limitations, including differences in turnaround time and throughput, and fortunately, false positive rates are low for established viral polymerase chain reaction (PCR) tests. However, sensitivity of PCR-based viral testing varies among platforms, and significantly variable false negative rates from available test kits have been reported, which may be compounded by sampling limitations and variation in presence of virus at different sites during the course of the disease. These considerations may prompt repeat testing when there is evidence of exposure, typical symptoms, or clinical presentation (although atypical symptom presentations are well described).