# Medical Question & Answer

**Sample ID**: b41bba99-1bfa-624d-faa7-cfebf92ecb72
**Dataset Index**: 158188

---

## Question

2. Write down and read all seven-digit numbers, the sum of the digits in each of which is equal to 2. How many such numbers are there?

---

## Answer

> Let's see… What do we have here? The user is asking how many seven-digit numbers have digits that sum to 2. Let's break this down step-by-step. First, I need to think about the constraints that define a seven-digit number and what "sum of digits equals 2" implies. Then, I should verify the combinatorial approach for distributing the digit sum across seven positions. Next, I will enumerate the distinct cases that satisfy the constraints and count each case. Finally, I will double-check the arithmetic and state the total clearly.

> Let me first confirm the problem setup. A seven-digit number ranges from 1,000,000 to 9,999,999, so the first digit cannot be zero, and the sum of all seven digits must equal 2. I need to ensure that any solution respects the non-zero constraint on the leading digit while allowing the remaining digits to be zero or positive integers that keep the total sum at 2.

> Now, I will think about the combinatorial framing. The problem reduces to finding the number of integer solutions to d₁ + d₂ + d₃ + d₄ + d₅ + d₆ + d₇ = 2, with d₁ ≥ 1 and 0 ≤ dᵢ ≤ 9 for i = 2, …,7. Wait, let me verify the upper bounds; since the total sum is only 2, no individual digit can exceed 2, so the dᵢ ≤ 9 constraint is automatically satisfied and I can ignore it for counting purposes, which simplifies the analysis to a stars-and-bars problem with a lower bound on d₁.

> I will now examine the feasible cases. Because the total digit sum is 2 and d₁ ≥ 1, the only possible distributions are: (1) d₁ = 2 and all other digits are 0, or (2) d₁ = 1 and exactly one of the remaining six digits is 1 while the rest are 0. Hold on, I should verify that these are indeed the only possibilities; yes, any other combination would either violate the leading-digit constraint or exceed the total sum of 2.

> Let me count Case 1 precisely. If d₁ = 2 and d₂ through d₇ are all 0, there is exactly one such number: 2,000,000. I should confirm that this is the only arrangement in this case; indeed, fixing the first digit to 2 forces all other digits to be 0 to meet the sum constraint, so the count is 1.

> Next, I should count Case 2. If d₁ = 1, then I need exactly one of the remaining six digits to be 1 and the other five to be 0. The number of ways to choose which of the six positions gets the 1 is C(6,1) = 6. Wait, let me double-check that calculation; yes, choosing 1 position out of 6 gives 6 distinct numbers, such as 1,100,000 and 1,010,000, and so on.

> I will now sum the cases to get the total. Case 1 contributes 1 number and Case 2 contributes 6 numbers, so the total is 1 + 6 = 7. Hold on, I should verify that I'm not missing any other valid configurations; given the constraints and the small total sum, these are the only possibilities, so the final answer is 7.

---

There are **7** seven-digit numbers whose digits sum to 2. These are: 1000001, 1000010, 1000100, 1001000, 1010000, 1100000, and 2000000. The solution follows from the constraint that the first digit must be at least 1, so the only ways to achieve a digit sum of 2 are either a 2 in the first position with six 0s, or a 1 in the first position with a single 1 in one of the remaining six positions.

---

## Mathematical approach

We need to find the number of seven-digit numbers d₁d₂d₃d₄d₅d₆d₇ such that:

- d₁ ≥ 1 (since it is a seven-digit number)
- dᵢ ≥ 0 for i = 2, 3, …, 7
- d₁ + d₂ + d₃ + d₄ + d₅ + d₆ + d₇ = 2

This is a classic **stars and bars** problem with constraints [^notfound]. We consider two cases:

---

### Case 1: d₁ = 2

If d₁ = 2, then the remaining six digits must sum to 0. The only way this can happen is if d₂ = d₃ = d₄ = d₅ = d₆ = d₇ = 0. Thus, there is **only 1 number** in this case: 2000000.

---

### Case 2: d₁ = 1

If d₁ = 1, then the remaining six digits must sum to 1. This means exactly one of d₂, d₃, …, d₇ must be 1, and the rest must be 0. There are **6 positions** where the digit 1 can appear, so there are 6 numbers in this case: 1000001, 1000010, 1000100, 1001000, 1010000, and 1100000.

---

## Total number of seven-digit numbers

Adding the numbers from both cases, we get a total of 1 + 6 = 7 seven-digit numbers whose digits sum to 2.

---

## List of seven-digit numbers with digit sum equal to 2

Here is the **complete list** of seven-digit numbers whose digits sum to 2:

| **Number** | **Digit sum** |
|-|-|
| 1000001 | 2 |
| 1000010 | 2 |
| 1000100 | 2 |
| 1001000 | 2 |
| 1010000 | 2 |
| 1100000 | 2 |
| 2000000 | 2 |

---

## Conclusion

There are **7** seven-digit numbers whose digits sum to 2. These numbers are 1000001, 1000010, 1000100, 1001000, 1010000, 1100000, and 2000000.

---

## References

### Making sense of number words and Arabic digits: does order count more? [^111RupdB]. Child Development (2020). Medium credibility.

The ability to choose the larger between two numbers reflects a mature understanding of the magnitude associated with numerical symbols. The present study explores how the knowledge of the number sequence and memory capacity (verbal and visuospatial) relate to number comparison skills while controlling for cardinal knowledge. Preschool children's (N = 140, M age-in-months = 58.9, range = 41–75) knowledge of the directional property of the counting list as well as the spatial mapping of digits on the visual line were assessed. The ability to order digits on the visual line mediated the relation between memory capacity and number comparison skills while controlling for cardinal knowledge. Beyond cardinality, the knowledge of the (spatial) order of numbers marks the understanding of the magnitude associated with numbers.

---

### Number processing induces spatial performance biases [^111bo32A]. Neurology (2001). Low credibility.

Background

Response speed in parity judgments is faster with the left hand for small numbers (e.g., 1 or 2) and faster with the right hand for larger numbers (e.g., 8 or 9). This effect suggests that number processing can induce systematic spatial biases in bisection tasks.

Method

Neurologically healthy participants bisected visually presented stimuli with a pencil. Stimuli were long strings of uniform digits (experiment 1) or lines with single digit flankers (experiment 2).

Results

Bisection performance was biased to the left of center for strings made of digits 1 or 2 and to the right of center for strings made of digits 8 or 9. Line bisection was biased toward the flanker representing the larger magnitude, regardless of its position.

Conclusions

These results extend previous findings and support the notion of an automatic association of number magnitudes with spatial response codes. The effect may be useful for an assessment of semantic number processing in special populations.

---

### Too many digits: the presentation of numerical data [^115CFoHw]. Archives of Disease in Childhood (2015). Low credibility.

Thus a decimal places rule that ignores significant digits does not work. But equally, and perhaps surprisingly, a significant digits rule that ignores decimal places does not always work either. Reporting risk ratios to three significant digits for example leads to the largest ratio below 1 being reported as 0.999 and the smallest above 1 as 1.01, with three and two decimal places, respectively. This is clearly unsatisfactory as they differ in precision by a factor of ten. In this instance a combination of significant digits and decimal places, the rule of four, works best: round the risk ratio to two significant digits if the leading non-zero digit is four or more, otherwise round to three.

The rule of four gives three decimal places for risk ratios from 0.040 to 0.399, two from 0.40 to 3.99 and one from 4.0 to 39.9. Applying it to the example of 22.68 above gives 22.7 (95% CI 7.5 to 74). Alternatively one can apply the rule with one less significant digit, giving 23 with CI 8 to 70.

Another example is the reporting of test statistics such as t or F. Specifying one decimal place would permit say t = 30.1, where 30 is clearly sufficient as it is so highly significant. Conversely specifying two significant digits would permit t = −0.13, where again the extra precision is irrelevant as it is far from significant. A suitable rule specifies up to one decimal place and up to two significant digits.

When comparing group means or percentages in tables, rounding should not blur the differences between them. This is the basis for the Hopkins two digits rule, whereby the mean has enough decimal places to ensure two significant digits for the SD. An analogous rule for percentages might be to use enough decimal places to ensure two significant digits for the range of values across groups, eg, if the range is 10% or more use whole numbers, if less than 1% use two decimal places, and otherwise one. In practice percentages are usually given along with their corresponding frequencies, so precision is less critical as the exact values can be calculated.

---

### A DNA-based system for selecting and displaying the combined result of two input variables [^114uJouM]. Nature Communications (2015). Medium credibility.

If the method should be used to process the input of two biological sequences it would require that X and Y be decoupled to allow input of arbitrary sequences. For this purpose we have introduced a third capture–linker strand as shown in Fig. 3a. This sequence contains two 8-nt domains that are each complementary to the two inputs, and furthermore it contains the capture sequence that allows binding to the MBs. This forms an incomplete four-way junction that is completed by selecting the fully complementary result sequence on the two 8-nt domains on X and Y to form a stable four-way junction. To demonstrate the principle we have used two short synthetic input strands. As shown with native PAGE in Fig. 3b, lane 4, inputs X and Y are independent. In lane 7, inputs X, Y and the capture–linker form a stable complex. In the native PAGE result shown in Fig. 3c, lanes 3 and 4, neither X nor Y alone binds with the result strand. In lane 5, where both X and Y are present, the input complex can bind to the correct result. This means that the correct result is only selected in the presence of both inputs X and Y. In lane 6 it is demonstrated, using three results where only one of the domains is correct, that wrong results do not bind to the input complex. Finally, in lane 7 the correct result is selected in the mixture with three wrong result sequences.

Translation of the results to a seven-segmented display

The mechanism of the output generation proceeds by selection of translator strands that guide the assembled complex to the lines of the digital number that displays the result in a seven-segmented display. As illustrated in Fig. 4 for the simple calculation of 1 × 2 = 2, the result two strands can hybridize with each of the five translator strands that are required to display the number 2. After MB-mediated separation from the solution of translator strands, the result–translator complex is (in most cases) liberated from the MBs and applied to a surface containing a pattern of one or more digital numbers. Each of the lines in the digit is functionalized with a unique host sequence that is complementary to the translator stands a–g. This means that contingent on the selected set of translator strands the digit has the capacity to display all numbers from 0 to 9. The encoding required for displaying the numbers 0–9 is shown in Table 1. A total of 49 translator sequences are required for displaying the 10 numbers in a one-digit display.

---

### A DNA-based system for selecting and displaying the combined result of two input variables [^116Dh4Gb]. Nature Communications (2015). Medium credibility.

Results

The design principle

The mechanism of the DNA-based system is outlined in more detail in Fig. 1. The two input strands X and Y each represent a number. The red and green parts of the input sequences contain the information that is specific for the number they represent. These domains are each 8-nt long. The black part of the sequences (16 nt) is universal so that all input X sequences can form a hybrid with all Y sequences. The yellow part of input X is a capture sequence that is used for separation. When the input strands are mixed with a library of result strands the input strands will form a stable three-way junction result with, and only with, the fully complementary result strand containing two domains that are complementary to the red and green parts of the input strands. The system may be viewed as a type of AND gate since both X and Y have to be present to select the result; however, it is not binary since X and Y may in principle each represent up to 2⁸ different values. The selective binding of the combined input to one specific result strand in the result library is the key element of the method. The result strand contains a blue extension with a unique sequence representing the value that corresponds to the multiplication of X and Y. Next, the value is translated into a mixture of result–translator complexes by incubation with a library of translator strands. If, for example, the result of the calculation is 2 then the translator strands that represent 2 will be selected. For the presentation of the number 2 in a seven-segmented display, five out of seven lines must be addressed and, that is, five different translator sequences are employed to display the digit 2. Hence, the result strand representing the number 2 will hybridize with a mixture of the translator strands representing 2. In the final readout generation the result–translator complexes are separated from the translator library and subjected to a universal display platform on a surface where the translator strands bind to the domains of the digit that corresponds to the result as illustrated for the result 2 in Fig. 1. We demonstrated the readout on three different platforms: two macroscopic displays that provide a fluorescent and a visual readout, and on the nanoscale on a DNA origami platform where the readout is imaged using AFM.

---

### Measuring global functioning in older adults with cognitive impairments using the rasch model [^1125bHpF]. BMC Geriatrics (2020). Medium credibility.

Methods

Participants

This study is based on a retrospective analysis on clinical data from patients that received clinical care at the ASL of Bassano, Italy, between 2013 and 2018. Only patients with clinical diagnosis of MCI, or dementia, and without functional impairment due to physical inability, were included in this study. We excluded individuals that did not complete the neuropsychological assessment which comprises a very common battery of tests used in Italy: the Esame Neuropsicologico Breve (ENB, Short Neuropsychological Examination ;, as well as the Activity of Daily Living (ADL ;, the Instrumental Activities of Daily Living (IADL; questionnaires, and the Mini-Mental State Examination (MMSE ;.

A total of 265 medical records were included in the following analyses. All individuals were outpatients in the age range of 62 to 95 (M = 78.25, SD = 5.80) with education between 0 and 18 years (M = 7.09, SD = 3.60). All patients were able to read and write at the time of the testing.

Measures

The MMSE comprises items that test temporal and spatial orientation, immediate and delayed verbal memory, language, attention, and praxis. The dependent variable was the sum of the items' scores (max. 30), corrected for age and education.

Esame Neuropsicologico Breve (ENB, Short Neuropsychological Examination ;).

The ENB encompasses 16 tasks. The following description of each test reflects the order of the administration.
1) Digit span: it consists of seven pairs of random number sequences of digits (from 2 to 8). The examiner reads each sequence, one at a time, and the participant has to repeat it in the same order (forward digit span). The test continues until the participant is unable to repeat the sequence correctly. The test assesses short-term memory storage capacity to passively retain verbal information for a few seconds. Only sequences containing between 3 and 8 digits were administered in this study.

---

### Calculation impairment in neurodegenerative diseases [^113ApFzM]. Journal of the Neurological Sciences (2003). Low credibility.

We examined oral calculation in patients with corticobasal degeneration (CBD; N = 17), frontotemporal dementia (FTD; N = 17), and Alzheimer's disease (AD; N = 20), as well as 17 healthy seniors matched for age and education. Our calculation model involves at least three components: numerosity, combinatorial processes, and executive resources such as working memory. We assessed addition, subtraction, multiplication, and division involving small numbers (small, single-digit answers) and large numbers (larger, single- and double-digit answers). We also assessed dot counting for small numbers (2–5) and large numbers (6–9), as well as a measure of working memory. All patient groups differed from healthy seniors in oral calculation. CBD (36% correct) and FTD (65% correct) demonstrated a significant overall impairment in oral calculation relative to AD (76% correct). CBD (66% correct) had more difficulty counting dots overall relative to AD (94% correct) and FTD (86% correct), consistent with our hypothesis that the calculation deficit in CBD is due in large part to a numerosity deficit. FTD had more difficulty relative to AD in their performance of reverse digit span, consistent with our hypothesis that FTD patients' executive resource limitation contributes to their pattern of calculation impairment.

---

### Sex-differences in network level brain dynamics associated with pain sensitivity and pain interference [^112kPWcx]. Human Brain Mapping (2021). Medium credibility.

2.3 Effect of pain on a cognitive test

To define the effect of pain on a cognitive task, we performed a task which was previously described and used (Cheng et al. 2017; Erpelding & Davis, 2013; Kucyi et al. 2013; Seminowicz & Davis, 2006, 2007; Seminowicz, Mikulis, & Davis, 2004). The cognitive task is a modified version of the numerical task (Eccleston & Crombez, 1999; Windes, 1968) that has been utilized instead of the Stroop task because it has been shown to produce robust differences in reaction time (RT) between task conditions (Erpelding & Davis, 2013). Briefly, participants viewed a computer screen that displayed three boxes, each containing multiple copies of a digit from 1 to 9. Each of the three boxes contained a different number of copies of digits and unique value of digits in each box. For example, box one might have three 2 s, box two might have seven 5 s, and box three might have nine 1 s. The participant is instructed to use a numerical keypad to report the number of digits in the box that contains the most number of digits. The instructions are to respond as quickly and as accurately as possible. The outcome measure of the task was the RT for each correct trial. The value of the number and the number of digits inside each box was different across each trial. Each participant underwent 6 blocks of the task which alternated between pain and no pain blocks (3 pain blocks and 3 no pain blocks) with the no pain block always being the first block. Every block contained 24 trials with each trial lasting for 2.5 s. Between each block, there was a short interval of 20 s and a 5 s countdown was provided to indicate the start of the next block.

---

### A DNA-based system for selecting and displaying the combined result of two input variables [^114E4TCT]. Nature Communications (2015). Medium credibility.

The system we have devised, furthermore, converts the selected result to Arabic numerals with one or two digits that are displayed on different templates, from the nanoscale to the macroscale. With few exceptions, other DNA-computing networks provide the output in the form of optical signals such as absorption or emission, which significantly limits the number of outputs that can be differentiated in the same solution. In other examples the readout has been observed by mobility shifts in gels or by sequencing, which are slow and laborious methods. On other occasions the result of DNA logic operations has been readout using atomic force microscopy (AFM), showing single-nucleotide polymorphisms as a letter symbol on DNA origami. In other work electrochemical readout has been applied for detection of the output of logic operations. In our system the digit is formed by segregating the output value from the first selection in a set of sequences that will address the lines in a seven-segmented display that are required to write the result number. Recently, Poje et al. reported on a system that also provides the output of a DNA-based system in a macroscopic fluorescence-based seven-segmented display; however, in this system the input was based on Boolean logic gates. In our work we also show the readout of the seven-segmented display at the nanoscale on DNA origami and a display that can be read by the naked eye.

---

### An iterative approach for estimating domain-specific cognitive abilities from large scale online cognitive data [^111BXB2u]. NPJ Digital Medicine (2024). Medium credibility.

Digits Span is a cognitive task designed to measure working memory capacity. Participants are presented with a sequence of numbers that they must recall. The first sequence is always 2 numbers long, and at each trial, if the participant replies correctly, the length of the next sequence increases by one. If the participant incorrectly recalls the sequence of numbers, then another string of the same length is presented. This is repeated until the participant replies incorrectly 3 times consecutively, when the task terminates. Spatial Span has a similar design to Digits Span, but instead of digits participants recall the location of sequences of flashes on a 4 × 4 grid of squares, testing their spatial working memory capacity. As shown in Fig. 3c for Digits Span, the derived DS measure suggested that the more numbers participants must remember, the harder is the trial (correlation between sequence length and DS is r = 0.92). Similarly for Spatial Span, the more squares participants have to remember, the harder is the trial (correlation between sequence length and DS is r = 0.84) (Fig. 3d).

Words Definitions is designed to measure crystallised intelligence. Participants are presented with a word and four alternative definitions. They must select the definition that corresponds to the meaning of the word as quickly as possible. The task has multiple trials and at each trial a different word is shown. The words are characterised by different frequency of occurrence in the English language. To assess the word difficulty scale predicted by IDoCT for the Words Definitions task, the correlation between the obtained measure of difficulty DS and the frequency of occurrence in the English language of the words included in the cognitive assessment was calculated. As shown in Fig. 3a, the most frequently used words in English were assigned a lower D and DS compared to the least frequently used ones. A Spearman correlation of −0.66 and −0.64 between respectively DS and D with the log frequency measures of the words was found.

Motor Control is designed to measure motor abilities. Participants are shown a moving target, which is represented as a circular red button, and are expected to press on the target as quickly as possible, as soon as it appears, and before it changes location in the screen. According to IDoCT, the further the location of the current target from the previous location, the higher the difficulty estimate DS (Spearman correlation between the distance and D and DS was 0.91 and 0.87, respectively — Fig. 3b).

---

### Spontaneous sparse learning for PCM-based memristor neural networks [^116cCCQr]. Nature Communications (2021). High credibility.

To identify the improvement in accuracy, we examined the confusion matrix as shown in Fig. 3b and e. The confusion matrix indicated how many times the neural network classified each input digit image into each class. The diagonal number indicates correct classifications for each digit while the off-diagonal number means the total occurrence of the confusion (i.e. the discrepancy between the prediction and the truth). The numbers at the top and right (single row and column, respectively) are the sum of each row and column except diagonal value. For example, the highest value '205' (sum of values surrounded by black lines in the confusion matrix) at the top means that the neural network mispredicted the input digit images as '3' mostly (denoted by 'misprediction as '3"), and the highest value '222' (sum of values surrounded by red lines in confusion matrix) at the right means that the class '8' is mostly mispredicted by the neural network (denoted by 'misprediction of '8"). Because some specific digits like '3' and '8' showed distinctive results in confusion matrix, we compared a digit-wise accuracy during the training. The digit-wise accuracy is defined as the number of correct predictions divided by the number of actual images for each digit. Digit '0' and '1' outperform in accuracy while digit '8' shows low accuracy overall in Fig. 3c. Although '3' and '8' show the top-2 highest attempt/success ratio (shown in Fig. 3d), the accuracy of '3' is much higher than the accuracy of '8'. The improved result (denoted by 'Drift') shows that the number of misprediction as '3' is reduced from 205 to 109 and the number of misprediction of '8' is reduced from 222 to 76 significantly. The SSL shows accuracy improvement for most of the digits, especially better for '8' as found in Fig. 3f.

---

### The impact of learning multiple real-world skills on cognitive abilities and functional independence in healthy older adults [^115z1Erw]. The Journals of Gerontology: Series B, Psychological Sciences and Social Sciences (2023). Medium credibility.

Measures

A baseline assessment (Week 0) was added in Study 2, so that the participants could serve as their own control. We also included pre-test (Week 6), midpoint (Week 12), and post-test (Week 18) assessments, following Study 1. The measurement battery for Study 2 was identical to the battery in Study 1, with the exception of two additional working memory measures: the 2-back from the EXAMINER battery, and the forward and backward digit span task (Table 2). The 2-back task required participants to remember the location of a square on two trials prior to the current trial (compared with only one trial prior in the 1-back task). The forward and backward digit span task required participants to memorize 16 sequences for the forward task and 14 sequences for the backward task. There were two sequences per trial, with eight trials for the forward task and seven trials for the backward task. The number of digits in each sequence increased after each trial, starting with two digits in the sequences for the first trial and ending with eight to nine digits in the last trial. The total score was divided by 15, the total number of trials.

---

### Perceived stress and cognitive decline: the moderating role of emotion regulation [^1163CXYd]. Innovation in Aging (2025). Medium credibility.

Emotion regulation

At the MIDUS 2 Biomarkers Project, a shortened version of the Emotion Regulation Questionnaire (ERQ;) was administered. Participants responded to four items assessing how frequently they engaged in cognitive reappraisal (" I control my emotions by changing the way I think about the situation I'm in "; " When I'm faced with a stressful situation, I make myself think about it in a way that helps me stay calm ") and expressive suppression (" When I am feeling negative emotions, I make sure not to express them "; " I keep my emotions to myself "). Items were rated on a 7-point Likert scale (1 = strongly disagree, 7 = strongly agree), with higher scores reflecting more frequent use of either strategy. In the current study, responses on both sets of items were summed to represent how frequently participants reported engaging in reappraisal and suppression, respectively. Scores for each emotion regulation strategy ranged from 2 to14.

Cognition

At the MIDUS 2 and 3 Cognitive Projects, participants completed the Brief Test of Adult Cognition by Telephone (BTACT;). The BTACT is a telephone-administered cognitive battery that includes seven subtests assessing immediate and delayed recall, working memory span, verbal fluency, inductive reasoning, processing speed, and attention-switching. Composite measures representing executive functions and episodic memory were provided through MIDUS. The Word List Immediate and Word List Delayed tasks were used to obtain the episodic memory composite score, and the Digits Backward, Category Fluency, Number Series, and Backward Counting tasks were included in the executive functions composite score.

Covariates

Participants self-reported their status on sociodemographic variables as part of the MIDUS 2 Survey. Analyses statistically adjusted for baseline age, sex (0 = male; 1 = female), years of education, household income, and number of medications. Educational attainment was indexed on a 12-point scale, ranging from "some grade school" to "professional degree". Household income was represented as the summed value of estimated earnings from wages, pensions, social security, and other sources. Number of medications was included as a continuous variable to account for comorbid conditions. These demographic and health factors have shown independent associations with both perceived stress and cognition and thus were covaried for to adjust for confounding influences. Additionally, baseline cognitive performance was covaried for to allow for quantification of cognitive decline over time.

---

### Predictors of hand function following digit replantation: quantitative review and meta-analysis [^1115j5Xc]. Hand (2021). Medium credibility.

Background: Digit replantation affords the opportunity to restore hand function following amputation. To date, however, few studies have evaluated functional outcomes following replantation. Therefore, it was the objective of this study to perform a meta-analysis to better characterize the predictors of hand function. Methods: A literature search was performed using the PubMed database to identify studies that focused on digit amputation/replantation and functional outcomes. Studies were evaluated for patient- and injury-related factors and their respective effects on clinical outcomes of sensation, grip strength, and Disabilities of the Arm, Shoulder, and Hand (DASH) scores. Statistical analysis was conducted across the pooled data set to identify significant trends. Results: Twenty-eight studies representing 618 replanted digits were included in this study. We found the average grip strength was 78.7% (relative to contralateral), the average 2-point discrimination (2PD) was 7.8 mm, and the average DASH score was 12.81. After conducting statistical analysis, we found patients with more proximal injuries had lower grip strength scores (P < .05). We found 2PD scores were influenced by age, mechanism of injury, and amputation level (P < .05). Finally, we found DASH scores after replantation were predicted by mechanism of injury and level of amputation (P < .05). The following variables did not influence outcomes: gender, tobacco use, ischemia time, and digit number. Conclusions: Digit replant does not restore premorbid hand function but does result in adequate hand function. Expected functional outcomes following replant should be considered in the decision-making process. These data can help risk-stratify patients, guide postreplant expectations, and influence the decision for replantation.

---

### A randomised controlled intervention trial evaluating the efficacy of a mediterranean dietary pattern on cognitive function and psychological wellbeing in healthy older adults: the medLey study [^115YozHM]. BMC Geriatrics (2015). Low credibility.

Short-term memory and working memory

The Digit Span Forward (DSF), Digit Span Backward (DSB) and the Letter-Number sequencing (LNS) subtest tasks from the latest version of the Wechsler Adult Intelligence Scale (WAIS-IV), are used to measure short term memory (DSF) and working memory (DSB and LNS). For DSF, participants are read a consecutive string of numbers (from 1–9) at a rate of one per second, and asked to repeat them back in the exact order they are presented. For the DSB task, participants are asked to repeat the sequence of numbers back in the exact reverse order that they were presented. String lengths range from two to eight digits and each trial presented two lists of the same string length. For each one of the eight trails over the two Digit Span tasks, a score of zero is given if a participant makes an incorrect response, and a score of 1 was given for a correct response. Individual total raw scores for the DSF and DSB tasks is calculated by summing the accumulated scores for the eight trials administered to each separate task. The maximum total raw score for both the DSF and the DSB was 16.

For the LNS task, participants are presented with strings of numbers and letters at a rate of one item per second, and afterwards asked to repeat back the numbers in numerical order followed by the letters in alphabetical order. String lengths ranged from two to eight digits and letters, and each trial presented three lists of the same string length. Following standard scoring procedures as outlined in the test manual, all seven trials (with three test items per trial) (not including sample items) were given a score of 0, 1, 2 or 3 (0 = fails all three trials, 1 = passes one trial, 2 = passes two trials, 3 = passes all three trials). For trials one and two, a score of 0 is given if a participant provides an incorrect response, suggesting they did not know the answer, or did not provide an answer within the allocated time limit of 30 seconds. For trials three to ten, credit is given for providing the correct letters in sequence followed by the correct letters in sequence.

---

### Depression, anxiety and cognitive function in persons with inflammatory rheumatic diseases: cross-sectional results from the German national cohort (NAKO) [^115vsnHE]. RMD Open (2024). Medium credibility.

Generalised Anxiety Disorder Questionnaire (GAD-7)

The Generalised Anxiety Disorder seven-item scale (GAD-7) is part of the NAKO questionnaire implemented via touch screen. It was developed and validated as a measure for evaluating the presence and severity of generalised anxiety disorders. It is a self-reported questionnaire measuring general anxiety symptoms related to the past 2 weeks, however, in the NAKO version the time frame was extended to 4 weeks. Response options are scored from 0 (not at all) to 3 (almost every day) for each question (possible range 0–21). A cut-off score of ≥ 10 is used to indicate the presence of GAD. The GAD-7 has been validated to measure GAD in persons with RA with a sensitivity of 0.64 (95% CI 0.31, 0.89) and a specificity of 0.86 (95% CI 0.78, 0.91).

Neuropsychological tests

A set of questions assessed subjective memory complaints and yielded case classifications of no memory complaints and those with complaints with and without worry.

The neuropsychological test battery included different tests to address the domains of memory and executive functions, tests for fine motor movements and attention as well as numerical reasoning. The Level 1 examination included a word list with immediate and delayed recall to test verbal episodic memory (12 nouns), a verbal fluency test (animal names), a digit span backwards test of working memory and the Stroop interference task of selective attention. A number series task was included in the extended Level 2 examination.

In the word list recall tests 1–3, participants were asked three times, one delayed at the end of testing, to recall as many words as possible from a digitally recorded list of words (possible range 1–12). In the semantic fluency task, participants were asked to enumerate as many animal names as possible within 1 min (possible range 1–79). In the Stroop colour-word task, participants were first asked to name the colour of 36 differently coloured boxes (Stroop table 2) and second to name the colour of incongruent colour names (Stroop table 3). For the digit span backwards, participants were acoustically presented digitally recorded number sequences of increasing length, containing three to nine random single digits spoken at a rate of 1 s per number. Participants were instructed to recall each sequence in reverse order. Scores from participants who experienced documented disturbances during the neuropsychological tests, for example, sudden noise or interruption, were not considered in the analyses.

---

### Testing bidirectionality in associations of awareness of age-related gains and losses with physical, mental, and cognitive functioning across 1 year: the role of age [^112pAuaD]. The Journals of Gerontology: Series B, Psychological Sciences and Social Sciences (2023). Medium credibility.

Mental Health

Depression was assessed with the nine-item Patient Health Questionnaire. For each item, respondents indicated how frequently they experienced the selected symptom over the previous 2 weeks (1 = not at all; 2 = several days; 3 = more than half the days; 4 = nearly every day). Higher scores (range: 9–36) indicate greater depression. Scores ≥ 19 indicate clinical depression. Cronbach's α in this sample was 0.76.

Anxiety was assessed with the seven-item Generalized Anxiety Disorder scale. For each item, respondents indicated how frequently they experienced the selected symptom over the previous 2 weeks (1 = not at all; 2 = several days; 3 = more than half the days; 4 = nearly every day). Higher scores (range: 7–28) indicated greater presence of anxiety. Scores ≥ 12 indicate clinical anxiety. Cronbach's α in this sample was 0.87.

Cognitive Functioning

Cognitive functioning was measured with the PROTECT Cognitive Test Battery, which is self-administered online and comprises four tasks: Verbal Reasoning, Paired Associate Learning, Self-Ordered Search, and Digit Span. For each task, a score was obtained by subtracting the number of errors from the number of correct answers; higher scores indicate better performance. For Verbal Reasoning the score has no upper or lower limit because respondents can make attempts on as many trials as they can within 3 min. For Paired Associate Learning, the score can range from 0 to 16. The score for the Self-Ordered Search Task can range from 0 to 20. For Digit Span, the score can range from 0 to 20. A composite score for Working Memory was obtained by summing participants' scores on Paired Associate Learning, Self-Ordered Search, and Digit Span. This was deemed possible as intercorrelations among these variables were > .70. Higher scores on this linear composite indicate better Working Memory.

---

### Melanoma staging: varying precision and terminal digit clustering in breslow thickness data is evident in a population-based study [^114Zjrot]. Journal of the American Academy of Dermatology (2018). Low credibility.

Background

Errors in Breslow thickness reporting can give misclassification of T category, an important classifier in melanoma staging.

Objective

We sought to investigate precision (number of digits) and terminal digit clustering in Breslow thickness and potential consequences for T category.

Methods

All first primary and morphologically verified invasive melanomas in Norway between 2008 and 2015 were included. A smoothing model was fitted to estimate the underlying Breslow thickness distribution without digit clustering.

Results

Thickness was reported for 13,057 (97.5%) patients; the median was 1.0 mm (range, 0.09–85). It was reported as whole numbers (15.6%), to 1 decimal (78.2%) and 2 decimal places (6.2%)-thin tumors with more precision than thick tumors. Terminal digit clustering was found with marked peaks in the observed frequency distribution for terminal digits 0 and 5, and with drops around these peaks. Terminal digit clustering increased proportions of patients classified with T1 and T4 tumors and decreased proportions classified with T2 and T3.

Limitations

Breslow thickness was not reported in 2.5% of cases.

Conclusions

The Norwegian recommendation of measurement to the nearest 0.1 mm was not followed. Terminal digit clustering was marked, with consequences for T category. Pathologists, clinicians, and epidemiologists should know that clustering of thickness data around T category cut points can impact melanoma staging with consequent effect on patient management and prognosis.

---

### A soft photopolymer cuboid that computes with binary strings of white light [^112ZnQ2a]. Nature Communications (2019). High credibility.

Fig. 5
Binary arithmetic. Schemes of addition of a 01 + 10 and b 01 + 01. Addends are input as binary strings through Beams Y and Z; place values are indicated. The result is contained in the antidiagonal of the output (yz plane). Carrier configurations 0D (red spots) = 0, 1DV (green spots), 1DH (blue spots) = 1, 2D (gray spots) = 0C1. c Addition is commutative and different addend pairs generate different output patterns but the same sum; examples from the 2² × 2² system are tabulated. Any addend may be added on the grid, provided that the sum does not exceed N digits for a 2ᴺ × 2ᴺ grid. Shorter binary strings are accommodated by appending leading zeroes as shown in d for the sum of 10010 and 1010 performed on a 2⁵ × 2⁵ system. Subtraction is accomplished by adding the two's complement of the minuend. We determine e the difference between 10010 and 1010 by adding 10110 and dropping the leftmost digit. This occurs naturally as the bottom–left voxel signifies a carried digit that cannot be contained within the grid. f A flowchart summarizing the steps of an addition algorithm including the treatment of carried over digits as exemplified in the accompanying output pattern corresponding to the sum of 01011 and 00110. (c – f scale bar = 500 μm)

The system is scalable. For a 2ᴺ × 2ᴺ system, the maximum computable sum = 2ᴺ − 1. For example, in the 2⁵ × 2⁵ system shown in Fig. 5d, the largest possible sum is 31. We use this system to demonstrate the addition of 10010 and 01010 to yield a sum of 11100. Using the same system, we also demonstrate the subtraction of the same numbers (Fig. 5e). In the case of the latter, we employ the radix complement method employed in digital computing (Supplementary Note 2). The addition of 00110 + 01011 to yield 10001 in Fig. 5f illustrates the treatment of carried over digits, which is summarized in the accompanying flowchart. Specifically, a carried over digit can only be deposited at the nearest element of increased place value that possesses a value of 0 or 0C1. When carried over an element possessing a value of 1, a result of 0 is deposited at that place value (further details and additional examples are provided in Supplementary Fig. 6).

---

### Cognitive performance in dialysis patients-"when is the right time to test? " [^115vY4a1]. BMC Nephrology (2021). Medium credibility.

RBANS

The RBANS is a brief, individually-administered test measuring cognitive function across five domains: attention, language, visuospatial/constructional abilities, and immediate and delayed memory. Performance in each domain is measured by the subtests (12 in total) described below, which are combined to yield five scaled "index scores" gauging function in the respective domains. These five index scores are in turn combined to yield a composite score referred to as the "total scale score". Stimuli are contained in a wire-bound, easel-type booklet, making the test easily portable and allowing for bedside administration. Total administration time is 20–30 min. Normative information from the manual for the index and total scores is based on 540 healthy adults who ranged in age from 20 to 89 years.

The battery was designed to be amenable to the construction of multiple equivalent forms, and there are different, equivalent versions of the RBANS available for test-retest use.

The domains comprise the following subtests:
Immediate Memory

List Learning: immediate recall of a 10-item list of words.
Story Memory: a 12 item story, read aloud for immediate recall over two trials.

2 Visuospatial/Constructional

Figure Copy: copying a geometric figure of 10 parts.
Line Orientation: a 10 item line orientation test.

3 Language

Picture Naming: 10-line drawings which the subject must name
Semantic Fluency: the total number of examples generated for a given semantic category within 60 s.

4 Attention

Digit Span: analogous to digits forward on the WAIS. There are two strings of digits in each item, each pair increasing in length from 2 to 9 digits. The second string of a given length is only read if the first string is failed.
Coding: numbers rather than symbols were chosen for the response in order to avoid the possible detrimental effect of a constructional apraxia on performance.

5 Delayed Memory

List Recall: free recall of the words from the List Learning task.
List Recognition: yes/no recognition testing for memory of the words from the List Learning task.
Story Recall: free recall of the story from the story memory test.
Figure Recall: free recall of the figure from the figure copy subtest.

All subtests of the RBANS were scored according to standardized age-adjusted criteria. Raw scores from the 12 subtests were converted to age- adjusted scaled scores before calculating an index score for each domain. The sum of the index scores was then converted to a total scale score.

---

### Impact of left-digit age bias in the treatment of localized prostate cancer [^115EcbyD]. The Journal of Urology (2022). Medium credibility.

Purpose

Left-digit bias is a phenomenon in which the leftmost digit of a number disproportionately influences decision making. We measured the effect of left-digit age bias on treatment recommendations for localized prostate cancer.

Materials and Methods

We included men with clinically localized prostate adenocarcinoma in Surveillance, Epidemiology, and End Results from 2004 to 2018 and the National Cancer Database from 2004 to 2016. Primary outcomes were recommendations for radiation therapy and radical prostatectomy. Regression discontinuity was used to assess whether age increase from 69 to 70 years was associated with disproportionate changes in treatment recommendations.

Results

In Surveillance, Epidemiology, and End Results, discontinuities were found in the proportion of patients recommended for radiation among the entire cohort (effect size 2.2%, P < .01) and among patients with Gleason 6 (1.6%, P < .01), Gleason 7 (2.5%, P < .01), and Gleason ≥ 8 (2.1%, P < .01) cancer, while the proportion recommended for prostatectomy decreased in the entire cohort (-1.4%, P < .01) and in patients with Gleason 7 cancer (-2.4%, P < .01). In the National Cancer Database, discontinuity from age 69 to 70 was found in recommendations for radiation in the entire cohort (effect size: 3.1%, P < .01) and in patients with Gleason 6 (2.2%, P < .01), Gleason 7 (4.0%, P < .01), and Gleason ≥ 8 (2.3%, P < .02) cancer, while the proportion recommended for prostatectomy decreased at this cutoff in the entire cohort (effect size: -2.7%, P < .01) and patients with Gleason 6 (-2.2%, P < .01) and Gleason 7 (-3.7%, P < .01) cancer.

Conclusions

In patients with localized prostate cancer, left-digit age change from 69 to 70 was associated with disproportionately increased recommendations for radiation and decreased recommendations for prostatectomy.

---

### Pediatric application of coding and valuation systems [^11752UMr]. Pediatrics (2019). High credibility.

Pediatric coding — CPT within HCPCS and National Drug Code (NDC) usage explains that the American Medical Association (AMA) maintains and annually publishes CPT, CPT is level I of HCPCS, and HCPCS level II identifies products/services not in CPT and is produced and maintained by CMS; CMS often creates G codes within level II. For medications, drug products are reported by an NDC, a "10-digit, 3-segment number"; the first segment has "4 to 5 numbers" for the labeler, the second has "3 to 4 numbers" for strength and form, and the third is a "1- to 2-digit number" for package size/types; Medicare and many payers require NDC code reporting on medication claims.

---

### Use of ICD-10 diagnoses in Danish psychiatric hospital-based services in 2001–2007 [^112LGPA8]. World Psychiatry (2010). Low credibility.

The Danish version of the ICD-10 chapter on mental and behavioural disorders has 380 different diagnoses when three digits are used. This study examines how many of the available diagnoses were used and to what extent in Danish psychiatric hospital-based services in the period from 2001 to 2007, through an analysis of the total number of diagnoses reported to the Danish Psychiatric Central Research Register (n = 1,260,097). The 50th percentile (50.1%) was reached by using 16 diagnoses (4.2% of 380 available). The three most frequently registered diagnoses were paranoid schizophrenia, alcohol dependence and adjustment disorder, used 10.2%, 8.3% and 5.9% of the times, respectively. Seven diagnoses (1.8%) were used between 1 and 4 times during the 7-year period. One hundred nine (28.7% of available diagnoses) were used less than 100 times each. These data suggest that it may be sensible to reconsider the number of diagnoses needed in the revision of the ICD-10 chapter on mental and behavioural disorders.

---

### Working memory training restores aberrant brain activity in adult attention-deficit hyperactivity disorder [^116LTUgE]. Human Brain Mapping (2020). Medium credibility.

2.3.3 Digit and visuospatial running memory

Participants were presented with sequences of digits or visuospatial stimuli of varying length (Pollack, Johnson, & Knaff, 1959). In the verbal version, the sequences consisted of digits (1–9), and in the visuospatial version, the stimuli consisted of squares appearing at eight different locations. Each cross was visible in the matrix for 1,500 ms. The inter‐stimulus‐interval was 500 ms, during which the matrix was empty. The stimuli were pseudo‐randomized into 28 sequences. The sequence length varied from seven to fourteen, with the exception of two four‐unit catch sequences. Each time a sequence ended, the participants repeated the digits or squares by clicking on corresponding numbers in the screen in the correct order, or by clicking on the correct locations with the mouse. In both tasks, the participants did not know the sequence length beforehand. The dependent variables were the total number of correctly recalled location/digit sequences.

2.3.4 Digit span

In the digit span task, participants were instructed to repeat sequences of digits in the same (forward) or reversed (backward) order (Blankenship, 1938). Sequence length varied between 2 and 9 digits in the forward tasks, and 2 to 8 digits in the backward tasks. Digits were presented with the interval of one per second. Two sequences of each length were administered. When the participant answered correctly to one of the sequences, the sequence length was increased by one digit. The task ended once the participant made two errors in a row. The dependent variable was the total number of correctly reported sequences (averaged across the forward and backward versions).

2.3.5 Continuous performance test

In the continuous performance test (CPT) task, participants were presented with a sequence of letters with fixed alternating intervals (1,000, 2000, and 3,000 ms) (Rosvold, Mirsky, Sarason, Bransome, & Beck, 1956). They were required to press the space bar for each letter, except for the letter X (probability 9.7%). There were 360 trials, and the duration of the task was approximately 14 min. Two dependent variables were used, omission errors as a proxy for inattention, and commission errors, as a proxy for impulsivity.

---

### Distributed functional connectivity predicts neuropsychological test performance among older adults [^1147hGRt]. Human Brain Mapping (2021). Medium credibility.

2.2.2 KSHAP neuropsychological test

To test the generalizability of the predictive model, we identified eight homologous neuropsychological tests included in the KSHAP dataset. Similarity and correspondence of administration procedures and contents were scrutinized. For the attention and working memory, Digit Span Forward, and Digit Span Backward tests included in the Elderly Memory disorder Scale (Chey, 2007) were available. The score was the sum of all correct trials were counted from 2 to 8 lengths of digits. The category fluency test asked participants to generate words from the two semantic categories (i.e. animal and supermarket) each within a minute (Kang, Chin, Na, Lee, & Park, 2000; Kang, Jang, & Na, 2012). While interference condition of the original Trail Making Test in UDSNB asks to alternate between numbers and alphabets (Reitan & Wolfson, 1993), modified Trail Making Test (mTMT) asked to alternate between numbers and symbols (triangle and rectangle) to minimize the floor effect of illiterate elderly (M. Park & Chey, 2003; Seo et al. 2006). The mTMT Part A (Trail A) consisted of 15 consecutively numbered circles arranged randomly on a sheet of paper. Participants were asked to draw a line between the circles in ascending order as quickly as possible. In mTMT Part B, they were asked to draw between triangles and squares alternately. In mTMT Part C (Trail C), participants consecutively connected lines between 8 numbers (ascending order) and 7 shapes (triangle and square) in an alternating way (1 – △ – 2 – □ – 3 – △…). Total time consumed to complete the mTMT‐A and mTMT‐C were used in the analysis, and mTMT‐B was not used in the analysis due to the variability in the possible trail options. A few participants exceeded the typical time limit of mTMT‐A (150 s, n = 1) and mTMT‐C (300 s, n = 7), but a maximum of 300 and 600 s, respectively, were allowed to finish the task due to the participants' unskilled usage of pencil. Total time (s) to complete the lines were log‐transformed and inversed. The Story Recall Test included in the Elderly Memory disorder Scale was used to assess episodic memory function. The Story Recall Test consisted of one story modified from the Logical Memory subtest in WMS‐III into a more culturally familiar content (An & Chey, 2004). The SRT required subjects to recall a paragraph containing 24 semantic units and the delayed recall subtests were administered 15–30 min after the immediate recall session.

---

### Giving science the finger-is the second-to-fourth digit ratio (2D: 4D) a biomarker of good luck? A cross sectional study [^112Yr3P2]. BMJ (2021). Excellent credibility.

Statistical analysis

Statistical analysis was performed by using the average 2D:4D from at least two raters for each hand and each procedure (photocopy and radiography). Significant relations have been reported between 2D:4D and various outcomes when male and female individuals are combined into one group. In other instances, the relation between 2D:4D and an outcome is only statistically significant when men and women are analyzed separately. Therefore, we performed all analyses both ways — with sexes combined and separated.

In our (facetious) effort to persuade less statistically savvy readers of the validity of our statistical analyses, we report as many P values as possible, even where they are not necessary (eg, descriptive statistics). All statistical analyses were performed in SPSS version 27.0 and a priori statistical significance was set at P ≤ 0.05.

Inter-rater agreement

To determine reliability of the most consistent raters for a given 2D:4D, a one-way random intraclass correlation coefficient was computed for each hand using each technique. Additionally, the mean inter-rater percentage differences were computed for each measurement technique for each hand.

To determine the relation between 2D:4D and sex, hand, and measurement technique, linear mixed effects models were computed by use of a scaled identity as the repeated measures covariance structure. Sex (male v female), hand (left v right), measurement technique (photocopy v radiograph), and all two way interactions between the three factors served as categorical predictors, and 2D:4D served as the dependent variable. A similar linear mixed effects model was also used to compare age, height, and body mass between sexes.

For correlations between 2D:4D and body composition parameters and good luck, preliminary analysis showed that the continuous body composition outcome variables were not normally distributed. Therefore, Spearman's r s was computed for all correlations.

Patient and public involvement

Conversations with members of the public inspired this study, because many indicated that they had seen 2D:4D mentioned in social media; some believed that scientific research had confirmed that 2D:4D had real life applications, while others expressed doubt that 2D:4D could predict anything. However, patients or the public were not directly involved in this study because of limited resources. A member of the public read this manuscript after submission.

---

### Association between recent real-life exposure to hypoglycaemia and cognitive function during hypoglycaemia in people with type 1 diabetes: findings from the hypo-RESOLVE clamp study [^115t8ibU]. Diabetes, Obesity & Metabolism (2025). Medium credibility.

2.4 Cognitive tests

At baseline (before onset of insulin infusion) and during hypoglycaemia, cognitive function was examined using a test battery of four validated cognitive function tests with a total duration of approximately 20 min. Primary endpoints were delta scores from baseline to hypoglycaemia for each test. We applied the Paced Auditory Serial Addition Test (PASAT)and three subtasks (Alertness, Verbal Flexibility and Working Memory) of the Test of Attentional Performance (TAP). The TAP Alertness subtask evaluated processing speed with the mean reaction time in milliseconds as the outcome. It examined how quickly participants pressed a button when an 'X' was presented on the laptop screen with or without an auditory warning signal beforehand. In the TAP Working Memory subtask, working memory was examined with the sum of omissions and errors as the outcome. A total of 100 single‐digit numbers were displayed on a laptop screen at 3‐s intervals, and the participants were instructed to press a button whenever the displayed digit matched the one shown two digits prior. The TAP Verbal Flexibility subtask evaluated attention and executive function with a ratio between the mean reaction time of the two simple tests and the complex test as the outcome. When numbers (on the left side of the laptop screen) and letters (on the right side) were displayed on the laptop screen, the participants should press the left or right button, respectively. The simple tasks encountered either numbers (first round) or letters (second round), while the complex task encountered both numbers and letters. Lastly, the PASAT, which evaluated different cognitive aspects, including processing speed and working memory, had a mean percentage of correct answers as an outcome. An audio clip presented 60 single digits with either 2.8‐ or 2.0‐s intervals. Throughout the read‐out of the digits, the participants were instructed to verbally state the sum of two consecutive digits in the digit row rather than a cumulative total.

On the procedure day, 11 of the included participants did not complete the TAP Verbal Flexibility subtask due to logistical errors.

---

### Giving science the finger-is the second-to-fourth digit ratio (2D: 4D) a biomarker of good luck? A cross sectional study [^115nANgB]. BMJ (2021). Excellent credibility.

Results

The analysis included 176 individuals (102 men and 74 women). Men were significantly older (age +1.5 years (95% confidence interval 0.2 to 2.9), P = 0.03), heavier (body mass +16.0 kg (12.9 to 19.1), P < 0.001), and taller (height +0.16 m (0.10 to 0.22), P < 0.001) than women. A total of 690 hand images (346 photocopy, 344 radiograph) were included in the analysis. The left hands from one female and one male participant were excluded from analysis, because of a history of broken digits on those hands. Four photocopies (two left hands for men, one left and right for a woman) and six radiographs (three left and three right for men) were not analyzed for technical reasons (that is, missing scan, digits landmarks not clearly visible).

Reliability and rater agreement

All intraclass correlation values were more than 0.90 and the mean percentage difference between raters was less than 1.0% for all 2D:4D measurements, indicating excellent agreement between raters (table 1).

Table 1
Reliability of rater measurement of the second-to-fourth digit ratio, by measurement technique and participant hand measured. Data are mean (95% confidence interval)

---

### Giving science the finger-is the second-to-fourth digit ratio (2D: 4D) a biomarker of good luck? A cross sectional study [^115ztAmt]. BMJ (2021). Excellent credibility.

Digit ratio data collection

Digit ratios were measured by two different procedures in accordance with best practice recommendations (appendix 1). Figure 2 shows example images. Participants were instructed to lightly place their hand on a standard photocopier (MX-3570N, Sharp Electronics, Montvale, NJ), and the researcher then scanned one hand at a time. Digital images were captured and delivered electronically to the research team. To minimize radiation exposure and optimize time efficiency, we also used DXA to obtain images of the phalangeal bones. We used the scanner's lumbar spine analysis software to capture an image with sufficient detail to identify details of the phalangeal bones.

Fig 2
Example hand images used to measure the second-to-fourth digit ratio (2D:4D). Both images are the right hand of the same participant; yellow lines represent second and fourth digit measurements. (A) Photocopy image: 2D:4D = 0.966. (B) Radiographic image: 2D:4D = 0.943 (radiographic image has been horizontally flipped to be in the same orientation as the photocopy)

Good luck measurement

Participants were asked to select five cards from a deck of playing cards (United States Playing Card Company, Erlanger, KY). Cards were thoroughly shuffled by an investigator and then fanned out, face down, onto a smooth, flat surface. The participant was then requested to select any five of the face down cards and flip them over. The value and suit of the cards were recorded. This procedure was repeated a second time with a separate, shuffled deck of playing cards, which resulted in each participant having two separate, randomly selected, five card poker hands, drawn from two separate decks of cards.

Poker hands were classified and ranked according to standard poker rules (that is, royal flush as the highest hand, single high card as lowest hand). Each individual's highest ranking hand was then selected, and ranked in relation to all other participants at the completion of the study. For instance, the best poker hand in the study's dataset (a nine high straight) was given the top rank of 1. In the event of a tie, both hands were given the same rank, and the ranking below was given a rank two units below those (eg, if two participants had identical hands, and both were ranked 37th, the next hand below them would be ranked 39th).

---

### Review of the molecular development of the thumb: digit primera [^115ZJNZg]. Clinical Orthopaedics and Related Research (2014). Low credibility.

Background

The thumb, or digit 1, is not a typical digit. In addition to its unusual mobility and function, its formation is also unusual. It is the last digit to form and the most commonly targeted when limb development is disrupted. The thumb domain is defined by the overlapping expression of HOXA13, TBX5, GLI3R, and HOXD13 and, importantly, by an absence of other distal HOXD transcription factors. This brief review, combining developmental biology and clinical genetics, discusses the current understanding of how the thumb domain is established.

---

### Prevalence of tuberculosis in children after natural disasters, bohol, Philippines [^11352Cpz]. Emerging Infectious Diseases (2019). Medium credibility.

Using 7 households per cluster and an estimated minimum average of 3 children per household, we determined we needed 200 clusters to obtain our sample size. The 200 clusters comprised 100 clusters chosen from the municipalities that suffered the greatest effects of the natural disasters (heavily affected areas) and 100 clusters from municipalities that suffered fewer effects (less affected areas) based on data from the Provincial Health Office (Reymoses Cabagnot, Provincial Health Officer, pers. comm. 2015 Aug 17). We randomly selected 7 municipalities each from heavily affected and less affected areas, providing 14 municipalities total for sampling.

To select the 200 clusters, we alphabetically arranged the names of all villages and their population sizes (based on the 2010 census), stratified by heavily affected area and less affected area designation. We determined the sampling interval by dividing the total population of each area (224,212 in heavily affected areas and 214,072 in less affected areas) by the number of clusters needed. We identified the first cluster (village) by using a randomly generated 5-digit number and matching it to the first village in our list with a cumulative population greater than or equal to the random number. We identified the second cluster by adding the sampling interval to the random number and selected subsequent clusters by adding the sampling interval to the previously generated number until we identified 100 clusters in each area (Appendix Tables 1, 2).

---

### Clinical decision support and cardiometabolic medication adherence: a randomized clinical trial [^113W1gVg]. JAMA Network Open (2025). High credibility.

The diabetes cohort included individuals with hemoglobin A 1c (HbA 1c) greater than or equal to 8% (to convert to proportion of total hemoglobin, multiply by 0.01) and PDC less than 80% for all medications in at least 1 of the noninsulin glucose-lowering medication classes (metformin, sulfonylurea, meglitinide, glucagonlike peptide-1 receptor agonist, sodium-glucose cotransporter 2 inhibitor, dipeptidyl peptidase-4 inhibitor, or thiazolidinedione).

Participants in the dyslipidemia cohort met American College of Cardiology/American Heart Association (ACC/AHA) criteria for statin use and receiving a statin with PDC less than 80%. Patients with their most recent low-density lipoprotein cholesterol (LDL-C) less than 100 mg/dL (to convert to millimoles per liter, multiply by 0.0259) within 24 months before the index encounter were excluded. The ACC/AHA criteria for statin use included the following. First, age greater than 21 years and either (1) LDL-C greater than or equal to 190 mg/dL, (2) atherosclerotic cardiovascular disease (ASCVD) diagnosis on the problem list; or (3) 2 or more International Statistical Classification of Diseases and Related Health Problems, 10th Revision (IDC-10)ASCVD encounter codes in the previous 2 years. Second, age 40 to 75 years and either (1) diagnosis of diabetes based the problem list or 2 or more IDC-10 encounter codes in the previous 2 years or (2) a 10-year ASCVD risk score of 7.5% or more based on the ACC/AHA 10-year pooled cohort equations.

Pregnant patients and those living in long-term care facilities or receiving parenteral cancer chemotherapy or hospice care were excluded from the study. Patients opting out of research were excluded from the analysis.

Randomization

Patient-level randomization of study-eligible patients was done at the time of an index primary care encounter at a study clinic during a 6-month accrual period. All patients meeting study eligibility criteria at an index visit were assigned a random 7-digit study identification number by a web-based computerized allocation system. Patients were allocated to either clinical decision support or usual care based on the random even or odd terminal digit of the study identification number.

---

### The genetic relationship between educational attainment and cognitive performance in major psychiatric disorders [^117TALXB]. Translational Psychiatry (2019). Medium credibility.

Trail-Making-Test (TMT)

The TMT is a measure of visual attention and task switching and is one of several executive functioning measures. The test consists of two parts, part A assesses psychomotor speed of the participant, and part B assesses switching between two automated tasks (counting and reciting the alphabet). The time taken to complete each part of the test was measured and the difference in time needed (part B-part A) was used, as it is considered a more accurate measure of the divided attention and alternating sequencing tasks tested in part B –. In this case, a higher score meant worse cognitive performance.

Verbal digit span

The verbal digit span, from the Wechsler Adult Intelligence Scale, assesses short-term (forward digit-span) and working memory capacity (backward digit-span). Briefly, participants were asked to recall verbally a sequence of digits, with increasingly longer sequences in each trial. For each correctly recalled string of digits, one point was given. The test was ended when the participant was unable to correctly repeat two presented strings of the same length. The difference between the forward and backward task is that the latter involves mental manipulation as the participant is required to repeat the digits in backward order. A score for each task was considered.

Digit-Symbol-Test (DST)

The DST is a subset of the Wechsler Adult Intelligence Scaleand measures processing speed, working memory, visuospatial processing and attention. In this test, the participant was asked to use a key of numbers 1–9 with coinciding symbols to draw the appropriate symbol that matched the number given. The participant was given 120 s to fill in as many corresponding symbols as possible. In the end, the correct number of symbols drawn was totaled to get an overall score.

Verbal Learning and Memory Test (VLMT)

The VLMT is the German version of the Auditory Verbal Learning Test. This word-list learning paradigm assesses several memory parameters through serial list learning with subsequent distraction, retrieval after distraction and half-hour time delay, and through a recognition task. The test consists of two different word lists which are each 15 independent words and a recognition list which includes 30 words from the two lists and 20 similar distractor words. Four VLMT scores were rated, the first for the number of correctly recalled words from the first list, a second score for the number of words lost after distraction, a third score of words lost after a time interval, and a fourth score of correctly recalled words from the recognition list.

---

### Second to fourth digit ratio (2D: 4D), breast cancer risk factors, and breast cancer risk: a prospective cohort study [^113kVRGC]. British Journal of Cancer (2012). Low credibility.

Results

Inter and intraobserver reliability was high for raw digit measurements, with ICC's for left and right, index and ring fingers all being greater than 0.95. Intraclass correlation coefficients for 2D: 4D ratio were slightly lower than those for raw digit measurements (0.80 for right and 0.73 for left 2D: 4D), but still suggest that the observed variability in digit ratio is largely due to between individual differences rather than measurement error.

Of the 9044 women available for this study, we identified 573 incident breast cancer cases during a median follow-up of 16 years 4 months per participant (a total of 145 328 person-years at risk were observed). Characteristics of the study population are shown in Table 1. Cases were slightly older than non-cases on average, with median age at baseline of 55 years compared with 53. Seventy-five percent of the participants were born in Australia, New Zealand, or the United Kingdom.

---

### Distinct and convergent beneficial effects of estrogen and insulin on cognitive function in healthy young men [^111hjgCM]. The Journal of Clinical Endocrinology and Metabolism (2022). Medium credibility.

Short-term memory and recognition

The Verbal Learning and Memory Test (VLMT) was used to assess short-term verbal memory and recognition discriminability. In this task, a list of 15 unrelated nouns (list A) was aurally presented (1 word per 2 seconds) and the participant was asked to immediately recall as many items as possible without feedback on the accuracy of the answer. This procedure was repeated 2 times. An additional list of 15 different nouns (list B) was presented after the third run to induce interference, and the participant again recalled as many items as possible from list A. Subsequently, list A was once again presented and recalled. After a 30-minute delay, recognition discriminability was tested via cued recall, that is, the 15 nouns of list A were aurally presented intermixed with items of list B and with semantically and phonologically similar items (50 nouns in total); the participant was asked to indicate whether or not an item belonged to list A. Corrected performance (the numbers of correctly remembered words minus false alarms; 15 points maximum) was calculated.

Working memory

Participants performed the digit span subtest of the Hamburg-Wechsler Adult Intelligence Scale — Revised 1991 twice to investigate the influence of estrogen and insulin on verbal working memory. In this test, up to 9 digits were read to the subject at a rate of 1 digit per second, for example, "5-8-2". The subject was to repeat the digits chronologically (forward test) or in reverse order (backward test). Starting with 3 digits, the number gradually increased until the participant failed to correctly repeat the digits twice in a row. Correct responses after 1 presentation equaled 2 points, and correct answers after 2 presentations equaled one point. Total performance score (28 points maximum) was the sum of the forward and backward components.

---

### The neural basis of metacognitive monitoring during arithmetic in the developing brain [^1113pYNu]. Human Brain Mapping (2020). Medium credibility.

FIGURE 1
Schematic overview of the arithmetic task. Overview of (a) run, (b) block, and (c) trial

FIGURE 2
Screen presented for the experimental condition: metacognitive question (left); screen presented for the control condition: color question (right)

FIGURE 3
Overview of a block in the experimental (a) and control (b) conditions

Each participant was presented with a set of 150 multiplication items. A list of the items is included in the Appendix S1, Supplementary Information and on the Open Science Framework page of this project. Multiplication was chosen as arithmetic operation of interest to ensure considerable inter‐ and intra‐individual variability in performance by using items of different difficulty levels, while still using a task with which children were very familiar, and which was as ecologically valid as possible. To maximize variability in both arithmetic performance and metacognition processes (experimental condition, see below) a wide range of multiplication items was included, ranging from easy items (n = 50; i.e. single‐digit multiplications items with 0–1 and 2–9 as operands, and single times double digit items with 0–1 or 10–11 and 12–19 or 2–9, respectively, as operands) over standard multiplication tables (n = 50; i.e. single‐digit multiplications with 2–9 as operands) to hard items (n = 50; i.e. single‐ times double‐digit multiplications with 2–9 and 12–19 as operands). We did not include ties, standard single‐digit items that were considered "too easy" (i.e. 2 × 3, 2 × 4, 3 × 4 and their commutative pairs), and hard items that were considered "too difficult" (i.e. operands 17–19 combined with operands 7–9). In each run, the same number of single‐digit items as well as single‐times double‐digit items was presented. The number of times a specific operand was presented in one run was equally distributed across runs. Commutative pairs were never presented within the same run.

---

### Giving science the finger-is the second-to-fourth digit ratio (2D: 4D) a biomarker of good luck? A cross sectional study [^116owHoy]. BMJ (2021). Excellent credibility.

Comparison of 2D:4D by sex, hand, and measurement technique

A summary of 2D:4D data are provided in table 2. Some significant differences were seen: men had a lower 2D:4D than women (P < 0.001), the left hand had a lower 2D:4D than the right hand for the photocopy technique (P = 0.004; but a two way interaction showed this association was significant for photocopy only), and the radiograph technique produced lower 2D:4D measurements than the photocopy technique (P < 0.001). A significant interaction between measurement technique and hand measured (P = 0.006) was noted, but the interactions between sex and measurement technique (P = 0.70) and between sex and hand measured (P = 0.92) were not significant. Despite significant differences in mean 2D:4D, the distribution of 2D:4D between sexes, hands, and techniques showed considerable overlap (fig 3).

Table 2
Summary of second-to-fourth digit ratios (2D:4D) by sex, measurement technique, and participant hand measured. Data are mean (95% confidence interval). 95% confidence intervals for radiograph ratios for men are equal to three decimal places

Fig 3
Histograms of second-to-fourth digit ratios (2D:4D) by participant hand measured, sex, and measurement technique. Despite statistically significant mean differences between men and women for each hand and each technique, the histograms had considerable overlap. (A) Left hand, photocopy technique; (B) right hand, photocopy; (C) left hand, radiograph; (D) right hand, radiograph

---

### Long-term effects of compulsory schooling on physical, mental and cognitive ageing: a natural experiment [^114gsbZu]. Journal of Epidemiology and Community Health (2019). Medium credibility.

Outcomes

In Constances, mental health was measured using the 20-item version of the Centre for Epidemiologic Studies Depression scale (CES-D), a validated depressive symptoms scale. Higher scores indicate higher levels of depressive symptoms and a cut-off of 16 for men and 20 for women was used to define elevated levels of depressive symptoms.

Cognitive function was assessed by trained neuropsychologists using five tests. The Mini-Mental State Examination (MMSE) is a general test of cognitive function consisting of 30 questions assessing five areas of cognition: orientation, registration, attention and calculation, recall and language. The Digit-Symbol Substitution Task of the Wechsler adult intelligence scale IV assesses psychomotor speed. The respondents were presented with nine digit-symbol pairs, followed by a list of numerical digits. They were asked to write the corresponding symbol under each digit as fast as possible. We retain the number of symbols correctly associated in 90 s. The Free and Cued Selective Reminding Test (FCSRT) measures verbal episodic memory. Respondents were first asked to read and memorise 16 words, then asked to recall as many words as possible in 2 min. The neuropsychologist provided a cue for each word that has not been retrieved. For this study, we include the FCSRT free immediate recall score. Finally, two verbal fluency tasks were included to assess language abilities: number of words related to the 'animals' category named in 1 min for the semantic fluency task and number of words starting with the letter 'R' named in 1 min for the phonemic fluency task. As the scale of each individual cognitive test differs, each score is converted to a z-score by subtracting the mean and dividing by the SD. A global cognitive score is obtained by summing the standardised tests. High cognitive performance is defined as the top quartile of the global score's distribution.

Physical functioning is assessed based on three objective health measures. Hand grip strength was assessed using a handheld dynamometer. Participants were asked to sit and squeeze the dynamometer for a few seconds with their dominant hand. The exercise was repeated three times and grip strength was determined as the average of the three results. Finger tapping, a measure of motor performance, was assessed by the number of taps respondents could do with the index finger of their dominant hand for 15 s. Walking speed was measured as the time taken by respondents to walk 3 m at a rapid pace. For each physical health outcome, high levels of physical functioning are defined based on the top quartile of the distribution.

---

### Giving science the finger-is the second-to-fourth digit ratio (2D: 4D) a biomarker of good luck? A cross sectional study [^116NRAwH]. BMJ (2021). Excellent credibility.

Discussion

This study intended to explore whether researchers can get lucky in finding statistically significant associations between a biomarker and various outcomes of interest, and whether these relations might reflect random chance rather than biological cause and effect. Failure to recognize these common research pitfalls (eg, scientifically unjustified hypotheses, weak experimental and statistical methodology, and improper reporting; box 1) can allow false positive findings to masquerade as evidence to support unsound theories. We focus on the 2D:4D example, but we urge researchers and clinicians to be especially vigilant when interpreting data from biomarker association studies.

Box 1
So-called "pitfalls" to avoid in research on second-to-fourth digit ratios (satirical)

Readers unaware of our study's intent could interpret our results as showing that prenatal testosterone influences body composition in men (maximum rₛ = 0.26), but not as much as it influences good luck (rₛ = 0.28). These results accord with much of what is reported in the 2D:4D literature, including similar magnitude correlations (that is, rₛ = 0.15 to 0.35), lower 2D:4D associated with desirable metrics of performance (that is, better body composition and poker hand), a sex specific effect, and greater association for the right hand than for the left. If study's reported findings are similar to an existing body of research, it might be easy to overlook multiple fallacies and assume that statistically significant findings represent real effects. Thus, our findings could be used (inappropriately) to support theories claiming that prenatal testosterone exposure influences adulthood traits, and they could validate an unfounded hypothesis that 2D:4D might be predictive of future luck.

---

### Effect of age on the protein profile of healthy malay adults and its association with cognitive function competency [^1177ajrv]. Journal of Alzheimer's Disease (2019). Medium credibility.

Forward Digit Span (FDS)

Subjects listened to a string of digits and repeated them in forward order verbally. The first sequence consisted of three digits. An additional digit was added until a maximum span of nine digits was achieved if subjects were able to express each digit correctly. The subjects had two trials for each span. If subjects repeated wrong digits in two of the trials, the test was halted. Scoring was based on the maximum digits repeated without error in one of the two trials.

Backward Digit Span (BDS)

Execution of this test was similar to the FDS. Subjects repeated the span in reverse order with the last digit in the span repeated first. The first span included two digits, and the last one was eight digits. The test was stopped if an error was made in two consecutive trials. Like the FDS, each subject's score was the maximum digits repeated without error in one of the two trials.

Digit Symbol

Subjects were required to redraw symbols that were matched with a particular number within 120 min. A list of numbers was shown in parallel to the assigned symbols for reference during the task. Subjects were allowed to practice drawing the symbols before beginning the actual test. Scoring was based on the total number of symbols drawn regardless of sequence.

Visual Reproduction (VR)

There were two parts of this task, VRI and VRII. In VRI, four different cards were presented to the subjects. Each card was shown within five seconds, and subjects were asked to redraw the shape on each card. In VRII, subjects were given a glimpse of the drawn shapes and required to memorize them. The subjects were then asked to redraw the shapes without the presence of any visual stimuli.

---

### Neural association between non-verbal number sense and arithmetic fluency [^112XM85Z]. Human Brain Mapping (2020). Medium credibility.

2.3.2 Numerosity comparison

Three dot arrays were presented simultaneously on the screen. The target array was presented in upper part of the screen, and two candidate arrays were presented in the lower half of the screen. Participants were asked to judge which candidate array contained the same number of dots as the target array. However, as this was not a matching task, the layout of the dots differed even when the number of dots was the same. For half of the trials, the total area taken up by the dots was the same for all three arrays. For the other half, the average area for a single dot (total area/number of dots) was the same for all three arrays. Dot size varied and dots were randomly distributed within a circle. Choices were made by pressing the "Q" (left candidate) and "P" (right candidate) keys on the keyboard. The task comprised 120 trials that were divided into two 60‐trials blocks.

2.3.3 Simple addition

We used a simple single‐digit addition task. For each trial, an addition problem was presented in the middle of the upper part of the screen and two candidate answers, one of which was correct, were presented side by side in the lower part of the screen. Participants were asked to choose the correct answer by pressing the "Q" (left candidate) and "P" (right candidate) keys on the keyboard. There are 81 possible single‐digit addition problems starting from 1 + 1 and ending at 9 + 9. To avoid repeating the same problem more than once, this test only had 81 trials.

2.3.4 Simple subtraction

The subtraction problems were the reversed calculations from the single‐digit addition. Thus, there are 81 possible problems starting from 2 to 1 and ending at 18 to 9. Again, to avoid repeating problems, this test only had 81 trials. All other aspects of the task were the same as the simple addition task.

2.3.5 Character rhyming

Two Chinese characters were presented simultaneously on the screen. Participants were asked to judge whether they rhymed or not. This test had 120 trials.

---

### Cognitive-motor multitasking in older adults: a randomized controlled study on the effects of individual differences on training success [^1171rK89]. BMC Geriatrics (2022). Medium credibility.

Global cognition is assessed using the Digit-Symbol-Substitution test (DSST). This test is part of the Wechsler Adult Intelligence Scale and is performed as paper-and-pencil tests. It consists of nine digit-symbol pairs followed by a list of digits with blank cells below. Participants are required to write the corresponding symbol in each blank cell below the digits as quickly as possible. The number of correct symbols within 90 sec is analyzed.

Tests of motor fitness

A battery of four established motor tests is used to determine different aspects of motor fitness following standardized procedures and instructions. Time is kept using a regular stop watch. Short practice trials with two to five repetitions are performed before each test.

Leg strength and endurance is assessed using the Chair stand test of the senior fitness test for older adults. Participants sit on a height-adjustable chair without armrests. Arms are crossed with hands on opposite shoulders. Participants continuously rise up to a straight standing position and sit down to a fully seated position with a straight back as often as possible within 30 s. They are asked to keep their arms crossed and both feet on the floor during the whole test. Correctly executed chair stands are registered.

Bimanual dexterity is measured with the Purdue Pegboard test. The Pegboard consists of two rows of 25 small holes from top to bottom. Small metal pins (pegs) are located at the upper left and right of the board. Participants are instructed to simultaneously pick up a peg from the right side with the right hand and a peg from the left side with the left hand, to place both pegs into the top empty holes in the left and right row, and to repeat this procedure as often as possible within 30 s. Three trials are performed. The number of rows with two correctly placed pegs is assessed for each trial.

---

### Transcriptomic analysis of avian digits reveals conserved and derived digit identities in birds [^114xREeY]. Nature (2011). Excellent credibility.

Morphological characters are the result of developmental gene expression. The identity of a character is ultimately grounded in the gene regulatory network directing development and thus whole-genome gene expression data can provide evidence about character identity. This approach has been successfully used to assess cell-type identity. Here we use transcriptomic data to address a long-standing uncertainty in evolutionary biology, the identity of avian wing digits. Embryological evidence clearly identifies the three wing digits as developing from digit positions 2, 3 and 4 (ref. 6), whereas palaeontological data suggest that they are digits I, II and III. We compare the transcriptomes of the wing and foot digits and find a strong signal that unites the first wing digit with the first foot digit, even though the first wing digit develops from embryological position 2. Interestingly, our transcriptomic data of the posterior digits show a higher degree of differentiation among forelimb digits compared with hindlimb digits. These data show that in the stem lineage of birds the first digit underwent a translocation from digit position 1 to position 2, and further indicate that the posterior wing digits have unique identities contrary to any model of avian digit identity proposed so far.

---

### Giving science the finger-is the second-to-fourth digit ratio (2D: 4D) a biomarker of good luck? A cross sectional study [^112ujbS1]. BMJ (2021). Excellent credibility.

Abstract

Objectives

To explore whether random chance, weak research methodology, or inappropriate reporting can lead to claims of statistically significant (yet, biologically meaningless) biomarker associations, using as a model the relation between a common surrogate of prenatal testosterone exposure, second-to-fourth digit ratio (2D:4D), and a random indicator of good luck.

Design

Cross sectional study.

Setting

University sports performance laboratory in the United States. Data were collected from May 2015 to February 2017.

Participants

176 adults (74 women, 102 men), including university students, faculty, and staff with no history of injuries, disease, or medical conditions that would affect digit length.

Main outcome measures

2D:4D, body composition parameters potentially influenced by androgens (bone mineral content, bone mineral density, body fat percentage), and good luck (using poker hands from randomly selected playing cards as a surrogate).

Results

2D:4D significantly correlated with select body composition parameters (Spearman's rₛ range −0.26 to 0.23; P < 0.05), but the correlations varied by sex, participant hand measured, and the method of measuring 2D:4D (by photocopy or radiography). However, the strongest correlation observed was between right hand 2D:4D in men measured by radiograph and poker hand rank (rₛ = 0.28, P = 0.004).

Conclusions

Greater prenatal exposure to testosterone, as estimated by a lower 2D:4D, significantly increases good luck in adulthood, and also modulates body composition (albeit to a lesser degree). While these findings are consistent with a wealth of research reporting that 2D:4D is related to many seemingly disparate outcomes, they are not meant to provide confirmatory evidence that 2D:4D is a universal biomarker of nearly everything. Instead, the associations between 2D:4D and good luck are simply due to chance, and provide a "handy" example of the reproducibility crisis within medical and scientific research. Biologically sound hypotheses, pre-registration of trials, strong methodological and statistical analyses, transparent reporting of negative results, and unbiased interpretation of data are all necessary for biomarker studies and other areas of clinical research.

---

### United States medical licensing examination step 1 two-digit score: a correlation with the American board of pathology first-time test taker pass / fail rate at the university of Pittsburgh medical center [^116pqESU]. Archives of Pathology & Laboratory Medicine (2011). Low credibility.

Context

Factors that correlate with success or failure on the American Board of Pathology (ABP) examination are not known. Other medical residency programs have shown that standardized test scores correlate with specialty board examination scores; however, data from pathology programs are lacking.

Objective

To investigate whether the 2-digit score on step 1 of the United States Medical Licensing Examination (USMLE) was correlated with ABP examination performance at a large university pathology program.

Design

Nine years of data (2001–2009) from pathology residents (n = 72) at the University of Pittsburgh Medical Center (UPMC, Pittsburgh, Pennsylvania) was collected from existing files and deidentified. Step 1 USMLE 2-digit scores and ABP failure rates for first-time test takers were compared. Results are reported as the percentage of residents who failed either the anatomic pathology or clinical pathology part of the ABP examination in cohorts by their USMLE 2-digit score (≤ 80, 81–85, 86–89, ≥ 90).

Results

The rolling 5-year (2005–2009) ABP average failure rate for first-time test takers of the anatomic pathology examination was 3.1% (UPMC) and 14.1% (nationally); in clinical pathology, it was 13.8% (UPMC) and 23.6% (nationally). At UPMC, no resident failed the anatomic pathology or clinical pathology parts of the ABP examination if his or her 2-digit USMLE step 1 score was 90 or more across 9 years of training (2001–2009).

Conclusions

In the UPMC pathology program, 2-digit scores on USMLE step 1 of 90 or more and 80 or less were strong measures of ABP first-time pass/failure rates, whereas scores of 81 to 89 were less-accurate measures. The USMLE step 1 score is one of many criteria that can be used for screening applicants for a pathology residency program.

---

### Vortioxetine (Trintellix) [^1167Dx9B]. FDA (2025). Medium credibility.

Time Course of Treatment Response

In the 6 to 8 week placebo-controlled studies, an effect of TRINTELLIX based on the primary efficacy measure was generally observed starting at Week 2 and increased in subsequent weeks with the full antidepressant effect of TRINTELLIX generally not seen until Study Week 4 or later. Figure 4 depicts time course of response in U.S. based on the primary efficacy measure (MADRS) in Study 5.

Figure 4. Change from Baseline in MADRS Total Score by Study Visit (Week) in Study 5

Figure 5. Difference from Placebo in Mean Change from Baseline in MADRS Total Score at Week 6 or Week 8

Digit Symbol Substitution Test in Major Depressive Disorder

Two, eight week, randomized, double-blind, placebo-controlled studies were conducted to evaluate the effect of TRINTELLIX on the Digit Symbol Substitution Test (DSST) during the treatment of acute MDD. The DSST is a neuropsychological test that most specifically measures processing speed, an aspect of cognitive function that may be impaired in MDD. Patients are asked to match nine symbols with their corresponding number (1 to 9) according to a key; the score is the correct number of matches achieved in 90 seconds. For reference, the mean score for healthy 45 to 54 year-old subjects is 50 (SD = 15).

Study 7 randomized adult patients meeting the diagnostic criteria for recurrent MDD to receive TRINTELLIX 10 mg, TRINTELLIX 20 mg, or placebo once daily. Study 8 randomized adult patients meeting the diagnostic criteria for recurrent MDD and reporting subjective difficulty concentrating or slow thinking to receive a flexible dose of TRINTELLIX (10 or 20 mg) or placebo once daily. Neither study included patients whose MDD was in remission yet who continued to experience difficulty concentrating or slow thinking. Patients' mean age was 46 (SD = 12) and 45 (SD = 12) in Study 7 and 8, respectively. In both studies, patients in the TRINTELLIX group had a statistically significantly greater improvement in number of correct responses on the DSST (Table 6); depressed mood as assessed by change from baseline in MADRS total score also improved in both studies.

The effects observed on DSST may reflect improvement in depression. Comparative studies have not been conducted to demonstrate a therapeutic advantage over other antidepressants on the DSST.

---

### Giving science the finger-is the second-to-fourth digit ratio (2D: 4D) a biomarker of good luck? A cross sectional study [^114bo28z]. BMJ (2021). Excellent credibility.

Relation between 2D:4D and outcome measures

Correlations between 2D:4D and body composition parameters and good luck ranking are presented in table 3, figure 4, and figure 5. Many statistically significant correlations were seen, with rₛ ranging in magnitude from 0.16 to 0.28; the strongest correlation was between the right hand 2D:4D measured by the radiograph technique and poker hand rank in men. However, results were not always consistent between measurement technique. For instance, the correlation between right hand 2D:4D and bone mineral content in women was significant for the photocopy technique (rₛ = 0.23, P = 0.05), but not for the radiograph technique (rₛ = 0.08, P = 0.5). In some instances, only men showed a significant correlation (eg, between left and right hand 2D:4D measured using the radiograph technique with bone mineral density), while in others, correlations were only significant when sexes were combined (that is, left and right hand 2D:4D measured using the radiograph technique with body fat percentage).

Table 3
Relations between second-to-fourth digit ratios (2D:4D) and age, body composition parameters, and good luck (using poker hand rank as a surrogate)

Fig 4
Scatter plots of second-to-fourth digit ratios (2D:4D) versus bone mineral density by participant sex and hand measured. Only 2D:4D measured by radiographic technique are presented, because the ratios measured by photocopy did not show significant results. (A) left hand, women; (B) right hand, women; (C) left hand, men; (D) right hand, men

Fig 5
Scatter plots of second-to-fourth digit ratios (2D:4D) versus poker hand rank by participant hand measured and sex. Only 2D:4D measured by radiographic technique are presented, because the ratios measured by photocopy did not show significant correlations. (A) Left hand, women; (B) right hand, women; (C) left hand, men; (D) right hand, men

---

### Smartphone-based symbol-digit modalities test reliably captures brain damage in multiple sclerosis [^116pPExP]. NPJ Digital Medicine (2021). Medium credibility.

As the burden of neurodegenerative diseases increases, time-limited clinic encounters do not allow quantification of complex neurological functions. Patient-collected digital biomarkers may remedy this, if they provide reliable information. However, psychometric properties of digital tools remain largely un-assessed. We developed a smartphone adaptation of the cognitive test, the Symbol-Digit Modalities Test (SDMT) by randomizing the test's symbol-number codes and testing sequences. The smartphone SDMT showed comparable psychometric properties in 154 multiple sclerosis (MS) patients and 39 healthy volunteers (HV). E.g., smartphone SDMT achieved slightly higher correlations with cognitive subscores of neurological examinations and with brain injury measured by MRI (R² = 0.75, Rho = 0.83, p < 0.0001) than traditional SDMT. Mathematical adjustment for motoric disability of the dominant hand, measured by another smartphone test, compensates for the disadvantage of touch-based test. Averaging granular home measurements of the digital biomarker also increases accuracy of identifying true neurological decline.

---

### 1q21.1 distal copy number variants are associated with cerebral and cognitive alterations in humans [^113ez5wx]. Translational Psychiatry (2021). Medium credibility.

For the copy number dosage effect analysis (i.e. the effect on brain structure of 1q21.1 distal copy number variation), a linear regression on the copy number status of the individuals (deletion = 1, normal = 2, duplication = 3) was performed using the following model: covariance-corrected, normalized brain measure ~ copy number (deletion = 1, non-carrier = 2, duplication = 3). For comparison between groups, a two-sample, two-sided t test assuming equal variance in all carrier/non-carrier groups was employed (R v3.3.2) where deletion or duplication carriers were compared either to each other or to non-carriers. To correct for the multiple comparisons, we calculated the number of independent outcome measures through the spectral decomposition of a correlation matrix using MatSpDlite of the three global, seven subcortical and 68 regional cortical measures. Based on the ratio of observed eigenvalue variance to its theoretical maximum, the estimated equivalent of independent measures was 36. Thus, we set the significance threshold at α = 0.05/36 = 0.0014. We report the uncorrected P values throughout the manuscript.

Effect size is calculated as the absolute effect size (the difference in mean between the two copy number groups in the t test — which, in this case, equals Cohen's D as the standard deviation of the normalized brain measures is one) and the estimate of beta in the linear regression. Plots were generated using R library ggplot2 v2.2.1. Regional cortical visualization was done with the R package ggseg v1.5.1.

In a novel analysis, the independent Icelandic data were processed and analysed as the main dataset. We meta-analysed the results using the R package metafor v2.0.0, as previously.

Cognitive task performance data

We downloaded behavioural performance measures on seven cognitive tests (the pairs matching task, the reaction time task, reasoning and problem-solving tests, the digit span test, the symbol digit substitution test and the trail making A and B tests) from the UK Biobank repository, performed by at least 10% of the participants. The results were processed following the general approach by Kendall et al. For more details, see Supplementary Note 6. For the analysis of the seven cognitive measures, we set the significance threshold to α = 0.05/7 = 0.007.

---

### Determinants of cognitive dysfunction in adults with sickle cell-related stroke or suspected neurological morbidity [^115Bs8iB]. Blood Advances (2024). Medium credibility.

Executive functioning

The Digit-Symbol Coding subtest (DSST)was used to assess processing speed. It consists of 9 digit-symbol pairs followed by a list of digits. Under each digit, patients were asked to write down as many of the corresponding symbols as possible over the course of 120 seconds. Raw scores were transformed into standard scores and classified as normal (> 7), weak (6–7), or pathological (< 6). Mental flexibility was assessed using the switching fluency test of the district of Seine-Saint-Denis(le test des fluences alternées du 93 or TFA-93). After simple fluency tasks, patients were asked to say as many words as possible in 1 minute by alternating between animals and fruit. The switching cost index as a measure of flexibility was calculated by dividing the number of correct responses given in the switching condition by the sum of correct responses given in the 2 semantic fluency tasks. The higher the calculated index, the lower the switching cost. This index was interpreted based on data from 279 native French speaking healthy controls aged 21 to 84 years (mean age: 60.9 ± 13.6), 43% (EL1: 39%; EL2: 27%; and EL3: 34%). The switching index was considered as weak if < 70%, and pathological if < 65%, corresponding respectively to a risk of drawing a wrong inference, < 10% (percentile 10) vs < 5% (percentile 5).

Mood

The Hospital Anxiety and Depression Scalewas used to assess the patient's current emotional state. Scores were classified separately for anxious and depressive symptoms as follows: absence of symptoms (≤ 7), suspected presence or presence of symptoms (> 7).

---

### Neuropsychological test performance of cognitively healthy centenarians: normative data from the Dutch 100-plus study [^111peD7N]. Journal of the American Geriatrics Society (2019). Medium credibility.

Neuropsychological Tests

The neuropsychological test battery consisted of 15 tests measuring global cognition, premorbid intelligence, attention and/or concentration, language, memory, executive function, and visuospatial function. See supplementary data for more detailed information on properties of these tests. At the start of the study, the test battery was limited to the MMSE and CDT but expanded gradually over the course of the study with tests that allow the evaluation of specific cognitive domains. For this reason, not all centenarians were presented with the same battery or the same number of tests.

The MMSE was used to evaluate global cognition. 21 We addressed premorbid intelligence using the DART, 22, 23, 24 in which subjects are asked to read out loud 50 words with atypical phonemic pronunciation. These words were presented in an enlarged font size to take into account possible visual difficulties. The Digit Span was used to evaluate attention/concentration (forward condition) and working memory (backward condition). 25 The forward condition requires subjects to repeat sequences of digits that increase in length, whereas in the backward condition, sequences of digits have to be repeated in reverse order. We evaluated processing speed and attention using the TMT A, and mental flexibility using the TMT B, which respectively requires subjects to connect dots of numbers in numerical order and alternate between numbers and letters in numerical and alphabetical sequence. 26 If the centenarians were not determined to proceed after 180 seconds (TMT A) and 300 seconds (TMT B), the test was aborted and scores were extrapolated based on the last finished item (number or letter) and the time spent on the test. The Dutch version of the Controlled Oral Word Association Test (naming words from initial letters) and Category fluency (naming animals) were administered to evaluate executive functioning and language, the latter also assessing semantic memory. 27, 28 To evaluate executive functioning, we administered the Key Search subtest of the Behavioral Assessment of the Dysexecutive Syndrome Test Battery 29 involving a problem‐solving task instructing subjects to think of a strategy to find a lost key. Memory was measured with the story recall subtest of the Dutch version of the RBMT and the VAT. 30, 31, 32 The RBMT requires subjects to immediately repeat all items they remember from two stories read out loud, and again after a 15‐minute interval. When necessary, a cue was given for helping them recall the story line, which was considered when calculating the total score. We made two adaptations to the test procedure: (1) two stories were read instead of one to improve reliability; (2) during recall, all remembered items were scored, whether they belonged to the appropriate story line or not. The VAT involves subjects to name two visual items shown in one picture (eg, a hedgehog on a chair), of which one item (hedgehog) needs to be recalled afterwards while the other (the chair without the hedgehog) is used as a cue. We used naming of the items as an additional measure of language functioning. Visuospatial orientation was assessed with the Number Location subtest of the Visual Object and Space Perception Battery, 33 which required subjects to indicate a specific number that corresponded with the exact location of a dot. For evaluating visuospatial construction, subjects were instructed to draw a clock with the hands at 10 past 11 (CDT). Because of common tremors in centenarians, the CDT was offered with a predrawn circle and was scored according to a method that does not consider the drawing of the circle. 34, 35

---

### 20140714.NGHP. ErrorCodes.txt-cob.cms.hhs.gov… [^114A1Tnm]. cob.cms.hhs.gov (2025). Medium credibility.

CC07 Claimant 1 Mailing Address Line 2 "Optional. If field greater than spaces, field must contain at least 2 alphanumeric characters". CC30 Claimant 2 Zip "If Claimant 2 Relationship is not equal to spaces, field must contain a valid 5-digit numeric US Zip Code. If Claimant 2 Relationship equal to spaces, field must be equal to zeroes. If Claimant 2 State = "FC", field must be equal to all zeroes". CC32 Claimant 2 Phone "If Claimant 2 Relationship is not equal to spaces, field must contain a non-zero 10-digit numeric value. If Claimant 2 Relationship equal to spaces, field must be equal to zeroes. If Claimant 2 State = "FC", field must be equal to all zeroes". CC34 Claimant 2 Entity/Organization Name "If Claimant 2 Relationship equal to space, field must contain spaces. If Claimant 2 Relationship = "X", "Y", or "Z", field must contain alpha and/or numeric characters, spaces, commas, &
- '. @ /: ;. and field must contain at least 2 non-space alphanumeric characters".

CC52 Claimant 3 Phone "If Claimant 3 Relationship is not equal to spaces, field must contain a non-zero 10-digit numeric value. If Claimant 3 Relationship equal to spaces, field must be equal to zeroes. If Claimant 3 State = "FC", field must be equal to all zeroes". CC72 Claimant 4 Phone "If Claimant 4 Relationship is not equal to spaces, field must contain a non-zero 10-digit numeric value. If Claimant 4 Relationship equal to spaces, field must be equal to zeroes. If Claimant 4 State = "FC", field must be equal to all zeroes". CI11 ICD-9 Diagnosis Code 7 "Optional. Must contain spaces or must match a value in the first 5 bytes of a record on one of the 3 most current lists of valid ICD-9 diagnosis codes at www. cms. gov/ICD9ProviderDiagnosticCodes/06_codes. asp. Must not be on the list of. Excluded Codes. in Appendix H. Must not begin with "E". Must not begin with "V". Must not include decimal point".

---

### The association of APOE genotype and cognitive decline in interaction with risk factors in a 65–69 year old community sample [^1175431D]. BMC Geriatrics (2008). Low credibility.

Cognitive tests

Speed

Mental speed was measured with the Symbol-Digit Modalities Test, which asks the participant to substitute as many digits for symbols as possible in 90 seconds.

Reaction time (RT)

Reaction time (RT) was tested using a small box held with both hands, with left and right buttons at the top to be depressed by the index fingers. There were four blocks of 20 trials measuring simple reaction time (SRT), followed by two blocks of 20 trials measuring choice reaction time (CRT). Means were calculated after removing outliers. This was done by first eliminating any values under 100 ms or over 3,000 ms. Next, means and standard deviations were calculated for each individual for each block, and values outside three standard deviations from the individual's block mean were eliminated.

Memory

Immediate and delayed recall were assessed with the first trial of the California Verbal Learning Test, which involves recalling a list of 16 nouns. The interval between immediate and delayed recall was occupied by a test of grip strength.

Working memory

Working memory was assessed with the Digits Backwards subtest of the Wechsler Memory Scale, which presents participants with series of digits at the rate of one per second and asks them to repeat the digits backwards.

General cognitive impairment

The 11 item Mini-Mental State Examination (MMSE) was administered primarily for screening purposes. However, the MMSE provides a reliable measure of mental status, covering aspects of cognition (in particular, orientation to time and place) that were not measured by the other cognitive tests.

Cognitive change scores were calculated for each test by subtracting Wave 1 scores from Wave 2 scores.

---

### NHANES 2011–2012: cognitive functioning data documentation, codebook, and frequencies… [^117Rc8Fu]. wwwn.cdc.gov (2011). Low credibility.

Each assessment is described, in brief: The CERAD Word Learning subtest assesses immediate and delayed learning ability for new verbal information. It has been used in major epidemiologic studies with diverse racial and cultural communities. The test consists of three consecutive learning trials, and a delayed recall. For the learning trials, participants are instructed to read aloud 10 unrelated words, one at a time, as they are presented. Immediately following the presentation of the words, participants recall as many words as possible. In each of the three learning trials, the order of the 10 words is changed. The maximum score possible on each trial is 10. In NHANES, the words for the learning trials were presented in large bolded letters on a computer monitor. Participants who were unable to read, due to literacy or visual impairment, were asked to repeat each word after it was read by the interviewer.

The delayed word recall occurred after the other two cognitive exercises were completed. In addition to scores for each word learning trial and the delayed word recall, a score for the number of intrusions is included in the data file. The Digit Symbol Substitution test, a performance module from the Wechsler Adult Intelligence Scale, relies on processing speed, sustained attention, and working memory. The DSST has been used in large screenings, epidemiological and clinical studies, and was administered during the household interview to participants 60 years and over during NHANES 1999–2002. The exercise is conducted using a paper form that has a key at the top containing 9 numbers paired with symbols. Participants have 2 minutes to copy the corresponding symbols in the 133 boxes that adjoin the numbers.

The score is the total number of correct matches. A sample practice test is administered before the participants begin the main test. In NHANES, participants who could not correctly match the symbols with the numbers on their own during the pretest practice did not continue. Details on scoring can be found in the 1999–2000 NHANES CFQ questionnaire data file documentation https: //wwwn. cdc. gov/Nchs/Nhanes/1999–2000/CFQ. htm.

---

### Alternatives for measuring sitting accumulation in workplace surveys [^113B5PAD]. Journal of Occupational and Environmental Medicine (2021). Medium credibility.

The final questionnaire can be found in Supplemental Digital Content (Text, Supplemental Digital Content 1, copy of questionnaire). Briefly it contained seven candidate measures of sitting accumulation, some that enquire directly regarding accumulation (1 to 3) and some (4 to 7) that may capture accumulation indirectly while enquiring about other facets of sedentary behavior. These were:

1% sitting in long bouts — This question asked about the percentage of sitting time at work that occurs in bouts of 30 minutes or longer (numeric response). It was designed to immediately follow the OSPAQ.
2 Longest sitting bout–What is the longest period of time you spent sitting down without leaving your seat during the average workday in the last 7 days? (response options: less than 30 min/30 to less than 60 min/60 to less than 90 min/90 to less than 150 min/more than or equal to 150 min).
3 Interruption rate — How many times did you interrupt (by standing or moving) your sitting each hour during an average working day over the last 7 days? (0/1/2/3/4/5 or more). The wording used was aimed to reduce confusion from the term "break" in the previously published version.
4 Conscious effort — Did you make conscious efforts to reduce the time you spend sitting behind your desk during the day? (Yes/No).
5 Typical day — How would you describe your typical day at work over the last 7 days? (Mostly sitting with very little standing and moving/mostly standing/changing from sitting to standing throughout the day/constantly moving). Categorical descriptions of usual day occupational and domestic activity have been used previously in the National Health and Nutrition Examination Survey, although with different wording and focus.
6 Sitting strategy variety, and 7. Sitting strategy frequency. These two measures were constructed from a 10-item array in which participants were asked how many times (interval choice of 0 to 10 or more times per day) they used each of a list of 10 strategies to reduce and break up sitting time. The strategies selected for the list were those that were commonly used by workers in previous interventions. Sitting strategy variety was calculated as the number of strategies participants indicated they undertook at least once per day (0 to 10 strategies). Sitting strategy frequency was the sum total of the number of times per day each of the 10 strategies was used (0 to 100 times per day).

---

### Index finger pollicization [^11531Ys5]. The Journal of Hand Surgery (2011). Low credibility.

The thumb is a specialized organ with unique functions that cannot be replicated by any other digit. The most powerful technique for construction of a missing thumb is index finger pollicization. In this article, we outline our technique for index finger pollicization. Over a 30-year period, certain technical refinements have improved the function and appearance of these transposed digits.

---

### Broadband generation of perfect poincarébeams via dielectric spin-multiplexed metasurface [^111TQkuj]. Nature Communications (2021). High credibility.

Optical information encryption

In the previous section, using a dielectric metasurface we have demonstrated the generation of PPBs that are independent of the topological charge number and polarization order. In principle, this approach encoding SAM and OAM states of light into PPBs in parallel channels can be employed for all-optical information encryption. For instance, various distinguishable PPBs with different polarization orders and ellipticities can be used to encode different double-digit hexadecimal numbers. For e.g. if the absolute value of polarization order | p | and ellipticity factor γ of the intensity pattern respectively denote the first and second digit of a double-digit hexadecimal number, and then a PPB represents a byte of data. As a result, the combination of 16 different values of | p | and γ for the PPBs can represent 256 hexadecimal numbers from 00 to FF. In our design, polarization order | p | ranging from 0 to 7.5 with an interval of 0.5 corresponds to the first hexadecimal digit from 0 to F, while ellipticity factor γ ranging from 0.5 to 2.0 with an interval of 0.1 represents the second hexadecimal digit from 0 to F. This code chart is given in Supplementary Table 3 and can be used to denote the characters of various encoding schemes.

---

### Meta-analysis shows associations of digit ratio (2d: 4d) and transgender identity are small at best [^115RiVui]. Endocrine Practice (2018). Low credibility.

Abbreviations

2D:4D = digit ratio; CI = confidence interval; F = female; FtM = female-to-male transgender; M = male; MtF = male-to-female transgender; TGI = transgender identity.

---

### Augmented manipulation ability in humans with six-fingered hands [^112LwFkM]. Nature Communications (2019). High credibility.

Fig. 3
Hands with supernumerary fingers perform more complex movements. Subplots (a – f) report on analyses of hand movements recorded during manipulation of objects of various shapes. The movement task was carried out by two six- and 13 five-fingered subjects. a Dependency between individual fingers quantified by the mutual information between the movements of pairs of fingers, with a value of 0 indicating complete independence between fingers and positive values an increasing dependency. Note that the mutual information is symmetric, i.e. b The cumulative amount of explained variance of hand movements as a function of an increasing number of principal components. Error bars depict SDs across subjects. c The number of effective dof (computed using the principle components, see Methods) was higher in six-fingered than in five-fingered subjects. d Information entropy of the discretized movements where each finger is either resting, flexing or extending. Entropy is shown for an increasing number of fingers, starting with thumb only ("T") and successively adding one finger (index "I", middle "M", ring "R", little "L" and supernumerary "S"). Dotted lines indicate the theoretically maximum possible entropy for five- and six-fingered hands. e Percentage of times thumb and index finger ("T + I"), thumb only ("T"), index only ("I") were moving when the supernumerary finger moved. From left to right: different percentiles of the speed distribution were used as thresholds to separate rest from movement. f Median movement speed of individual fingers for five- and six-fingered subjects. Subplots (g, h) show results from the video game experiment. g Schematic of the task, subjects were required to press a button corresponding to the bottom white targets every time an oscillating cursor (green or red) entered the box. The target boxes flashed blue if a correctly timed press occurred and displayed as red if an incorrectly timed press occurred. Horizontal bars at the bottom of the screen displayed the fraction of correct key presses (top) and one minus the fraction of missed (bottom) key presses. h Subjects' learning curve for the 5 + 1 (dotted) and 6 finger (solid) control. Digits used shown in the inset in dark gray

---

### Similar somatotopy for active and passive digit representation in primary somatosensory cortex [^1178CRWH]. Human Brain Mapping (2023). Medium credibility.

2.6 Key analyses

Data from the active and the passive task were analysed in three different ways to probe different hallmark aspects of digit representation. First, we investigated correspondence in spatial location between digit maps obtained in the active and passive tasks (Section 3.1). Second, we examined somatotopic organisation with the somatotopic index analysis (Section 3.2.1). Within each digit specific cluster (as identified by the functional localiser) we also examined the somatotopic neighbourhood activity for each digit using traditional univariate analysis (Section 3.2.2). Finally, we examined the multivariate representational structure of the hand using (unthresholded) activity patterns across the SI hand area using RSA (Section 3.3). All data used for final analysis will be made available online at the Open Science Framework upon publication of this manuscript.

2.6.1 Spatial correspondence

To assess the spatial correspondence between digit representations in the active and passive tasks (Section 3.1), a Dice coefficient (Dice,) was calculated on activity maps projected onto the cortical surface (as in Kikkert et al.) for each individual participant. Traditionally, the amount of spatial overlap between, in this case, two digit representations, is calculated in reference to the total spatial area of these two digits. However, cases may occur when one digit's representation is completely within another's (i.e. completely overlapping), but the area of the second digit may be much larger than the first, leading to a small Dice coefficient. To account for these differences, the Dice coefficient was normalised to the smallest area of the pair of digits (see Formula 1). This constrains the maximum overlap to be equal to the smallest digit representation area. Note: the same analysis was run with the traditional Dice coefficient with comparable results. This analysis can be found in the Supplementary Materials, Section 1, and Figure S2.

---

### Peripheral microangiopathy in precapillary pulmonary hypertension: a nailfold video capillaroscopy prospective study [^113Ukeh5]. Respiratory Research (2021). Medium credibility.

As irregularly enlarged were characterized capillaries with apical limb width > 20 μm and < 50 μm and as giant, homogeneously enlarged capillaries with apical limb width ≥ 50 μm. The mean of each capillaroscopic feature was calculated from the sum of consecutive images for each digit. Subsequently, the average values from eight fingers were added together and divided by the number of studied digits. The resulting value indicated the number of this capillaroscopic feature adjusted by each millimeter of the nailfold.

The "overall pattern recognition" was qualitatively assessed based on capillary density, the presence of irregularly enlarged capillaries, hemorrhages and shape abnormalities using a fast-track algorithm proposed by Smith et al. Images were classified as "normal pattern", "non-specific pattern" and "scleroderma pattern". Furthermore, a semi-quantitative rating scale was adopted (score:0–3) based on these four capillaroscopic parameters in order to classify patients according to the severity of systemic microvascular disease. Capillary density was rated as follows: 0 for > 9 capillaries/mm, 1 for 7–9 capillaries/mm, 2 for 4–6 capillaries/mm and 3 for 1–3 capillaries per mm. Irregularly enlarged capillaries, hemorrhages and shape abnormalities were scored accordingly: 0 equals to no changes, 1 to changes less than 33% of the total number of capillaries/mm, 2 to changes between 33 and 66% of the total number of capillaries/mm, and 3 to changes more than 66% of the total number of capillaries/mm. Total score was calculated by the sum of scores for each finger divided by the total number of fingers evaluated and was rounded to the next integer to define the risk group.

---

### A phase 1c trial comparing the efficacy and safety of a new aqueous formulation of alphaxalone with propofol [^115tmu1R]. Anesthesia and Analgesia (2015). Low credibility.

Digit Symbol Substitution Test

A DSST, was completed 4 times at 15-minute intervals before anesthetic drug injection and again 4 more times at 15-minute intervals in the PACU from 35 to 80 minutes after anesthetic drug injection. The 4 tests before PHAX and propofol injection were administered by the caring anesthetist and the 4 tests in PACU were administered by the PACU nurse.

The DSST is a paper-based test. At the top of the page are printed 9 digits, 1 to 9 each paired with a different symbol (e.g. 1/-,2/┴. 7/Λ,8/X,9/ =). The rest of the page is covered with a list of digits in a random order (e.g. [7] [3] [4].) with a blank space under each digit. The subject is asked to write down the corresponding symbol in each blank space, as fast as possible in 90 seconds. The number of correct symbols within the allowed time is measured. The pairing of digit and symbol was kept constant during the study, but the order in which the digits were presented in the list to be completed with symbols was different from one testing time to the next. However, the same list was used for all subjects at a particular test time. The test was repeated on 4 occasions separated by 15 minutes, because it is well known that repeat testing causes improved scores because of learning. This produced a "best" prestudy score on the fourth test. The aim of this design was to compare the postsedation scores in each subject with his last best predrug score to assess the time taken to recover from subtle sedating effects of PHAX and propofol.

The times after anesthetic injection for the subjects who received the near equivalent doses of PHAX (n = 9) and propofol (n = 8) to achieve DSST scores in the PACU equal to or greater than the last predrug score were combined to produce medians (IQR) for comparison of the PHAX and propofol in achieving early recovery.

Biochemistry and Hematology

Venous blood was taken for the measurement of total blood count, liver function test, and renal function test before drug administration and once on the morning of discharge. Venous blood was also taken for the measurement of complement fractions (C3 and C4) at 1 and 10 minutes after anesthetic drug injection. Arterial blood was withdrawn for blood gas measurements at 2 and 5 minutes after drug administration.

---

### Impaired digit span can predict further cognitive decline in older people with subjective memory complaint: a preliminary result [^111c724s]. Aging & Mental Health (2011). Low credibility.

Subjective memory complaint (SMC) is common among elderly people, and is thought to be part of mild cognitive impairment (MCI). We evaluated whether impaired digit span (IDS) in older people with SMC can predict wider impairment in future neuropsychological tests that correspond to MCI. After a mean of 6.6 years from the initial assessment, we reevaluated 16 subjects with SMC and normal digit span (NDS) scores (mean age 57.6 ± 8.1 years) and 28 subjects with SMC and IDS scores (mean age 59.7 ± 9.9 years). The IDS group showed wider cognitive decline in tests of short-term verbal memory and category verbal fluency compared to the NDS group. IDS scores indicate an earlier step for conversion of SMC to MCI.

---

### The Montreal cognitive assessment: normative data from a large Swedish population-based cohort [^111zMidj]. Journal of Alzheimer's Disease (2017). Low credibility.

MoCA administration and scoring

The MoCA assesses global cognitive function and contains of 10 subtests. Visuospatial abilities are assessed using a clock-drawing task and a three-dimensional cube copy, short-term memory is tested with two learning trials of five nouns followed by a delayed recall task. Executive functions are assessed using a task adapted from the Trail Making B test, a phonemic fluency task, and a two-item verbal abstraction task. Attention, concentration, and working memory are evaluated using an attention task, a serial subtraction task and digits forward and backward. Language is tested with a naming task with low-familiarity animals (lion, camel, rhinoceros), repetition of two syntactically complex sentences, and the fluency task. Orientation is evaluated by time and place. The participants in our study were evaluated with the Swedish MoCA, version 7.0. Nurses and biomedical scientists experienced in cognitive testing, administered the MoCA. In the original validation study, it was suggested that people being evaluated with the MoCA received an extra point to the total score if they had ≤ 12 years of education. We calculated mean MoCA scores without adding an extra point for low education. To increase the sample sizes of age groups, larger age intervals were created with overlapping age groups according to a previously described method, which has been used in other normativestudies.

Screening and assessment of cognitive impairment

We screened for cognitive impairment with the MMSE and AQT. The MMSE assesses global cognition with a well-established cut-off for cognitive impairment at < 24 points that provides a high specificity. AQT, on the other hand, provides a high sensitivity for impaired attention and executive function. The test score constitutes the number of seconds it takes to fulfil each test plate where the subject should name the color and form of 40 figures. The cut-off for AQT was set at > 90 s for cognitive impairment (higher score equals poorer performance). This approximately corresponds to +1 standard deviation (SD) based on a previous normative sample where the mean score was 71.2 s (SD 21.5 s). The MMSE and AQT administered together improve sensitivity, and have a higher sensitivity than MMSE in combination with Clock Drawing Test. They are thus a suitable complement to each other when evaluating cognitive function.

---

### Second to fourth digit ratio and prostate cancer severity [^11222bZH]. Prostate Cancer and Prostatic Diseases (2013). Low credibility.

Background

The ratio of the second to the fourth digit (2D:4D ratio) is a sexually dimorphic trait established in utero that differs between ethnic groups. It is associated with prenatal androgen exposure, and studies have evaluated the ratio as a marker for certain traits and disease states known to be associated with higher levels of in utero androgens, such as prostate cancer. There are currently no screening tools that stratify men with prostate cancer according to the severity of their disease. This study aims to investigate the 2D:4D ratio as a potential marker for prostate cancer severity. Our hypothesis was that lower digit ratios, representing higher in utero androgen exposure, would be associated with more severe disease.

Methods

Measurements were taken of the second and fourth digits of the right hand of male patients diagnosed with prostate cancer. Gleason score, presence of metastasis, family history, age at diagnosis and race were recorded. The distribution of demographic and other patient characteristics were compared with digit ratios to determine relationships.

Results

African-American men with prostate cancer are 3.70 times more likely to have a low 2D:4D digit ratio than Caucasian men with prostate cancer (95% confidence interval: 1.98, 6.92; P < 0.0001). There were no statistically significant differences in the presence of metastasis, Gleason score, family history or age at diagnosis by digit ratio.

Conclusion

2D:4D ratio shows strong differences between African-Americans and Caucasians; however, it does not correlate with disease severity in men already diagnosed with prostate cancer. Although this is a small population sample with possible confounding factors, it does not provide evidence to support the hypothesis that prenatal androgens affect prostate cancer grade or progression.

---

### Neuropsychological functioning and jumping to conclusions in delusions [^113a6E28]. Schizophrenia Research (2013). Low credibility.

There were no differences in premorbid IQ between those who jumped to conclusions and those who did not. When the JTC group was defined by the more difficult (60:40) version of the task, those who jumped to conclusions performed significantly worse (p values < 0.05) on tests of working memory (Digit Span total and forwards, and Letter–Number Sequencing) and also at trend level (p = 0.09) on Digit Span backwards. Those with the JTC bias on the easy (85:15) version likewise performed more poorly on the tests of working memory (Digit Span total and backwards, and Letter–Number Sequencing), but at trend level (0.05 < p values < 0.1). Both JTC (easy and hard) groups showed poorer performance on the Rey test of verbal learning and memory (RAVLT), but this failed to reach significance (0.05 < p values < 0.1). In order to explore whether working memory contributed to the (non-significant) difference between the groups in performance on this test, we ran a further analysis, in which we controlled for digit span forwards and letter–number sequencing. While there was no evidence for a contribution from digit span forwards, there was an effect of letter–number sequencing. The mean differences were very little changed by adding in digit span forwards as a covariate, and digit span itself was not a significant predictor of RAVLT. However, letter–number sequencing had an impact, reducing the effect of JTC on the mean differences and significantly predicting RAVLT (see Tables 1 and 2). A check on whether JTC performance differed by current level of medication (none, low, medium or high dosage) found no differences on either version of the task. Finally, whatever the version of the task, there were no differences between those who jumped to conclusions and those who did not in total positive and negative psychotic symptom scores (SAPS and SANS), in the SAPS global severity of delusions rating or in depression or anxiety (BDI and BAI) (see Tables 1 and 2). However, those who jumped to conclusions on the 85:15 version, but not the 60:40 version, scored significantly more highly than those who did not on a sum of all SAPS delusions items (see Tables 1 and 2).

---

### Guidance on community viral load: a family of measures, definitions, and method for calculation [^113SXd3E]. CDC (2011). Medium credibility.

Table 2 — additional community viral load (VL) measures — includes a cumulative measure defined as "Sum of VLs for all cases" that reflects "The number of virus particles in the population who have a VL; affected by the number of cases; reflects both prevalence of HIV cases and burden of viremia". A suppression proportion is defined by "The numerator is the number of cases whose most recent VL was suppressed; the denominator is the number of cases with a VL" and interpreted as "Maximal Virologic Suppression, or the percent virologically suppressed reflects ART uptake, adherence, and effectiveness in clinical settings; a quality of HIV care measure; in jurisdictions offering universal treatment, an important marker of uptake of universal ART guidelines". Calculation timing guidance notes "Time needs to be defined for each calculation, usually a 12-month period. Pooling over a few years can increase VL completeness but is harder to interpret". The abbreviation is specified as "ART, antiretroviral treatment".

---

### The relationship between IQ, memory, executive function, and processing speed in recent-onset psychosis: 1-year stability and clinical outcome [^111TakSQ]. Schizophrenia Bulletin (2010). Low credibility.

Predictors of 1-Year Clinical Outcome From Baseline WAIS-III Subscale Scores

We used the significant (P < .05) correlations between baseline clinical and WAIS-III scores to determine the analysis of 1-year clinical outcome in those pairs that had been successfully followed up. In each case, a linear regression was used to determine whether the relevant baseline cognitive score was a significant predictor of the 1-year clinical measure, once the equivalent baseline clinical measure was already entered as a predictor in the model. Thus, controlling for baseline symptoms, we found no effects of block design on disorganization (first step: baseline syndrome score r² = 0.02, F 1,27 = 0.37, P = 0.550; second step: baseline block design–scaled score r² = 0.02, F 1,26 = 0.70, P = 0.409), arithmetic on disorganization (first step: baseline syndrome score r² = 0.01, F 1,27 = 0.37, P = 0.550; second step: baseline block design–scaled score r² = 0.05, F 1,26 = 1.17, P = 0.290), arithmetic on mania (first step: baseline mania score r² = 0.01, F 1,27 = 0.28, P = 0.602; second step: baseline arithmetic-standardized residual score r² = 0.03, F 1,26 = 0.70, P = 0.409), or block design on mania (first step: baseline mania score r 2 = 0.01, F 1,27 = 0.28, P = 0.602; second step: baseline block design–standardized residual score r² = 0.04, F 1,26 = 1.106, P = 0.312). Regarding the negative syndrome, digit symbol–scaled score had no effect (first step: baseline syndrome score r² = 0.11, F 1,27 = 3.45, P = 0.074; second step: baseline digit symbol–scaled score r² = 0.01, F 1,26 = 0.35, P = 0.559), but digit symbol–standardized residual score accounted for a significant amount of the variance in the negative syndrome score once the baseline negative syndrome had been taken into account (second step: baseline digit symbol–standardized residual score r² = 0.16, F 1,26 = 5.83, P = 0.023).

---

### Hand pattern indicates prostate cancer risk [^111etda4]. British Journal of Cancer (2011). Low credibility.

Background

The ratio of digit lengths is fixed in utero, and may be a proxy indicator for prenatal testosterone levels.

Methods

We analysed the right-hand pattern and prostate cancer risk in 1524 prostate cancer cases and 3044 population-based controls.

Results

Compared with index finger shorter than ring finger (low 2D:4D), men with index finger longer than ring finger (high 2D:4D) showed a negative association, suggesting a protective effect with a 33% risk reduction (odds ratio (OR) 0.67, 95% confidence interval (CI) 0.57–0.80). Risk reduction was even greater (87%) in age group < 60 (OR 0.13, 95% CI 0.09–0.21).

Conclusion

Pattern of finger lengths may be a simple marker of prostate cancer risk, with length of 2D greater than 4D suggestive of lower risk.

---

### Second to fourth digit ratio (2D: 4D) and prostate cancer risk in the melbourne collaborative cohort study [^111Nc4Qe]. British Journal of Cancer (2011). Low credibility.

Background

The ratio of the lengths of index and ring fingers (2D:4D) is a marker of prenatal exposure to sex hormones, with low 2D:4D being indicative of high prenatal androgen action. Recent studies have reported a strong association between 2D:4D and risk of prostate cancer.

Methods

A total of 6258 men participating in the Melbourne Collaborative Cohort Study had 2D:4D assessed. Of these men, we identified 686 incident prostate cancer cases. Hazard ratios (HRs) and confidence intervals (CIs) were estimated for a standard deviation increase in 2D:4D.

Results

No association was observed between 2D:4D and prostate cancer risk overall (HRs 1.00; 95% CIs, 0.92–1.08 for right, 0.93–1.08 for left). We observed a weak inverse association between 2D:4D and risk of prostate cancer for age < 60, however 95% CIs included unity for all observed ages.

Conclusion

Our results are not consistent with an association between 2D:4D and overall prostate cancer risk, but we cannot exclude a weak inverse association between 2D:4D and early onset prostate cancer risk.

---

### Hand burns surface area: a rule of thumb [^114ugfPb]. Burns (2018). Low credibility.

Introduction

Rapid estimation of acute hand burns is important for communication, standardisation of assessment, rehabilitation and research. Use of an individual's own thumbprint area as a fraction of their total hand surface area was evaluated to assess potential utility in hand burn evaluation.

Materials and Methods

Ten health professionals used an ink-covered dominant thumb pulp to cover the surfaces of their own non-dominant hand using the contralateral thumb. Thumbprints were assessed on the web spaces, sides of digits and dorsum and palm beyond the distal wrist crease. Hand surface area was estimated using the Banerjee and Sen method, and thumbprint ellipse area calculated to assess correlation.

Results

Mean estimated total hand surface area was 390.0cm 2 ± SD 51.5 (328.3–469.0), mean thumbprint ellipse area was 5.5cm 2 ± SD 1.3 (3.7–8.4), and mean estimated print number was 73.5 ± SD 11.0 (range 53.1–87.8, 95% CI 6.8). The mean observed number of thumbprints on one hand was 80.1 ± SD 5.9 (range 70.0–88.0, 95% CI 3.7), χ² = 0.009. The combined mean of digital prints was 42, comprising a mean of two prints each on volar, dorsal, radial and ulnar digit surfaces, except volar middle and ring (3 prints each). Palmar prints were 15 (11–19), dorsal 15 (11–19), ulnar palm border 3, first web space 2, and second, third and fourth web spaces one each. Using the surface of the palm alone, excluding digits, as 0.5% of total body surface area, the area of one thumbprint was approximated as 1/30th of 1%.

Conclusions

We have demonstrated how thumbprint area serves as a simple method for evaluating hand burn surface area.

---

### The Montreal cognitive assessment: normative data from a large Swedish population-based cohort [^112NAvJC]. Journal of Alzheimer's Disease (2017). Low credibility.

MOCA scores

The mean MoCA score was 26.0 (SD 2.3) for the entire normative population (ages 65–85). The mean (SD) scores stratified on age group and education level are shown in Table 2. The participants scored on average 82% on visuospatial function, 98% on naming, 98% on attention letters, 97% on attention subtraction, 89% on attention digits, 93% on language repeat, 69% on language fluency, 85% on abstraction, 62% on delayed recall, and 99% on orientation. Normative scores for the different parts of MoCA stratified according to age and education are provided in Supplementary Table 1. The mean MoCA score for women was 26.1 (SD 2.3) and for men 25.7 (SD 2.4) (p = 0.006). In Table 3, we present data of calculated cut-off scores ≤ 1, ≤ 1.5 and ≤ 2 SD below the mean score.

Table 2
MoCA scores by age and education level

Scores are in mean (standard deviation). * Elementary school or lower, up to 10 years of education. ** Graduation from high school/Advanced level including any additional courses. ** University degree.

Table 3
Cut-off scores by age and education level

Raw MoCA-scores not including an extra point for low education. Arrows show cut-offs at –1 SD (yellow), –1.5 SD (orange), and –2 SD (red) below the mean MoCA score. The cut-offs correspond to the DSM-5 criteria where major neurocognitive disorders s typically perform ≥ 2 SD below appropriate norms, and mild neurocognitive disorders typically perform in the 1–2 SD range. Cut-offs are preferably chosen in the age group where age is centered midmost in the age interval. * Elementary school or lower, up to 10 years of education. ** Graduation from high school/Advanced level including any additional courses. ** University degree. SD, standard deviation.

---

### Sensory recovery 1 year after bridging digital nerve defects with collagen tubes [^113tjQUU]. The Journal of Hand Surgery (2013). Low credibility.

Purpose

To investigate digital nerve regeneration following implantation of collagen tubes in a prospective study.

Methods

Forty-five digital nerve defects (≤ 2.6 cm) in the hand were reconstructed in 35 patients (6 female, 29 male; mean age, 47 y). Nerve regeneration was evaluated at 3, 6, and 12 months after surgery by applying a sum score comprising static 2-point discrimination, sensory threshold with Semmes-Weinstein monofilament mechanical stimuli, warm/cold sensation, vibration sense, sharp/dull recognition, recognition of numbers, and subjective estimation of the patient. Electroneurography and ultrasound were also performed.

Results

In the distribution of 60% of the operated nerves, very good or good recovery was found. In contrast to basic sensory function, the more complex static 2-point discrimination was more frequently impaired after 1 year. After 6 months, the sum score correlated with electroneurography. The type of injury altered the final sensory nerve function. Circular saw and iatrogenic injuries showed a negative correlation with final sensory nerve function. Complications (infection) were observed in 2 patients.

Conclusions

Owing to the good functional outcome in the majority of cases, the use of collagen tubes is useful to span digital nerve defects up to 2.6 cm.

Type Of Study/Level Of Evidence

Therapeutic IV.

---

### ASGE guideline on the management of achalasia [^114La9sC]. Gastrointestinal Endoscopy (2020). High credibility.

Wiley Cochrane Library search strategy for achalasia — numbered queries and yields are listed. MeSH descriptor "[Esophageal Achalasia] explode all trees" (#1) had 111, a text-word search "(cardiospasm or achalasia or megaesophagus or mega-esophagus or megaesophagus or mega-oesophagus); ti, ab" (#2) had 226, and "#1 or #2" (#3) had 231. With surgical qualifiers, "MeSH descriptor: [Esophageal Achalasia] explode all trees and with qualifier(s): [Surgery - SU]" (#4) had 38 and "MeSH descriptor: [Esophageal Sphincter, Lower] explode all trees and with qualifier(s): [Surgery - SU]" (#5) had 7. The procedure-term query "(myotomy or heller or peroral or per oral or poem or lhm); ti, ab" (#6) had 8540; combining these as "#4 or #5 or #6" (#7) had 8553; and the final combination "#3 and #7" (#8) had 114.

---

### Finger counting training enhances addition performance in kindergarteners [^1127zM7A]. Child Development (2024). Medium credibility.

This interaction was further modulated by Finger use group (i.e. Group × Finger use group × Testing point, F (1, 324) = 16.4, = .05, p < .001). Indeed, the experimental effect just described was higher in the group of 86 non‐finger users than in the group of 105 finger users. In fact, the positive effect of the training was significant only for non‐finger users (as seen above, from 37.3% at pre‐test to 77.1% at immediate post‐test, +39.8%, t (129) = 4.83, d = 0.89, p < .001) and not for finger users (from 81.8% at pre‐test to 92.4% at immediate post‐test, +10.6%, t (195) = 1.71, d = 0.24, p = .089).

Finally, analyses in the sub‐samples of non‐finger users from the experimental group who responded to our intervention (i.e. who shifted to finger use at post‐test) or not were conducted. Concerning the 74% of children (N = 64) who shifted to a finger counting strategy at immediate post‐test, the percentages of correctly solved additions went from 32.5% at pre‐test to 86.6% at immediate post‐test (i.e. +54.1%), t (63) = 12.70, d = 1.59, p < .001. In contrast, the remaining 26% of children (N = 22), who still did not use their fingers to solve the additions at immediate post‐test, did not show accuracy improvement (from 51.4% at pre‐test to 49.5% at immediate post‐test, −1.9%), t (21) = 0.59, d = 0.13, p = .559.

---

### Diagnosis of learning disabilities but not academic difficulties alone is associated with neurocognitive impairment in people living with HIV: evidence from clinical research to support and refine the current HAND diagnostic guidelines [^114Rj926]. AIDS and Behavior (2025). Medium credibility.

No participant had a severe LD. It is probable that patients with severe LD would have received care in a different facility. In addition, all participants were able to complete the test battery further corroborating that none had a severe LD.

Neuropsychological test performance was evaluated using a standard battery which assessed seven cognitive domains (specific tests for each listed): Speed of Information Processing: WAIS-III Digit Symbol, Trail Making Test Part A; Attention/Working Memory: WAIS-III Digit Span, WMS-III Spatial Span, and WMS-III Letter Number Sequencing; Motor Functions: Grooved Pegboard test; Executive Functions: Trail Making Test Part B, Wisconsin Card Sorting Test (64); Learning and Memory: California Verbal Learning Test, Wechsler Adult Memory Scale-III (WMS-III) Story Learning and Story Recall, and WMS-III Figure Learning and Figure Memory; and Language: Boston Naming Test and Verbal Fluency.

Individual raw neuropsychological test scores were converted into demographically corrected T-scores using published norms and thus correcting for age, education, gender, and ethnicity when relevant. T-scores were averaged into domains T-scores following conventional nomenclature and a global mean T-scores. T-scores were then converted into deficit scores according to the following criteria: ≥ 40T = 0 (Normal); 39T-35T = 1 (Mildly impaired); 34T–30T = 2 (Mildly to moderately impaired); 29T–25T = 3 (Moderately impaired); 24T–20T = 4 (Moderately to severely impaired); and ≤ 19T = 5 (Severely impaired). The deficit scores were then averaged into a Global Deficit Score (GDS) where the conventional cut-off of GDS ≥ 0.5 indicates neurocognitive impairment (NCI). T-scores and dichotomized GDS were both used in the present study.

---

### Augmented manipulation ability in humans with six-fingered hands [^114yUBCM]. Nature Communications (2019). High credibility.

Next, we investigated the functional organization of the motor cortex in P1 using an individual finger tapping task and functional MRI at 7T high resolution. In order to highlight the specific representations of each finger, we compared the activity patterns generated by individual finger movements (Supplementary Fig. 3). The results show that the representation of the SF in the primary sensorimotor cortices was distinct from the representations of all other fingers, including the thumb (Fig. 2e, Supplementary Fig. 4). This demonstrates that separate neural resources are used to control movements of the SF in this six-fingered subject.

Mental representation of polydactyly hands

To infer the mental representation of the hand in our polydactyly subjects, we asked them to indicate their perceived location of landmarks on the hand (fingertip, first and second knuckles, for each finger) by pointing with the other hand to the corresponding target on a two-dimensional graded grid placed above the hidden hand, following a tactile cue on the target. As we see in Fig. 2f, the hand representation corresponds to its anatomy, with the SF perceived correctly between the thumb and index. We found similar localization errors in the six-fingered and five-fingered subjects (two-sided Wilcoxon rank sum test, p = 0.33, W = 7, 95% CIs [−0.89 cm,0.47 cm], average across fingers six- vs. five-fingered subjects, N 1,2 = 2,9, cf. ref.). This morphologically correct representation of the fingers may support six-fingered manipulation.

---

### AASLD practice guidance on prevention, diagnosis, and treatment of hepatocellular carcinoma [^112wHKKv]. Hepatology (2023). High credibility.

AASLD hepatocellular carcinoma — proposed expanded criteria for liver transplantation and associated outcomes include the following examples: UCSF criteria define "One tumor < 6.5 cm or 2–3 tumors, each < 4.5 cm, with total tumor volume ≤ 8 cm" with "81% 5-year survival"; a total tumor volume approach specifies "Sum of volume for each tumor ≤ 115 cm³" with "75% 4-year survival"; the up-to-seven criteria require "Diameter or largest tumor (cm) + number of tumors ≤ 7" with "71% 5-year survival"; the extended Toronto criteria state "Biopsy demonstrating well-to-moderate differentiation for patients beyond Milan criteria and ECOG performance status 0–1" with "68% 5-year survival"; and the Kyoto criteria use "Number of tumors ≤ 10, maximum diameter of each tumor ≤ 5 cm, and serum DCP ≤ 400 mAU/ml" with "65% 5-year survival".

---

### Initial diagnostic workup of acute leukemia: guideline from the college of American pathologists and the American Society of Hematology [^117TnbsN]. Archives of Pathology & Laboratory Medicine (2017). Medium credibility.

Supplemental Table 12: Quality assessment for Statement 13 — prospective cohort studies summarizes six studies and evaluates domains including balance between treatment/assessment groups, reporting of baseline characteristics and of any adjustment when differences were present, funding source, and overall risk of bias assessment; the header specifies "Prospective Cohort Studies (N = 6)", and an example row documents responses such as "No (N)", "Yes (Y)", and "Not reported".

---

### Norethindrone (Errin) [^112ogKjW]. FDA (2024). Medium credibility.

INSTRUCTIONS TO PATIENTS

How to Use the Errin® Tablets Blister Card

The first time you use these pills, take your first pill on the first day of your menstrual period. Pick the Days of the Week Sticker that starts the first day of your period. When you have picked the right sticker, throw away the others and place the sticker on the blister card over the pre-printed days of the week and make sure it lines up with the pills.
Your blister package consists of three parts, the foil pouch, wallet, and a blister card containing 28 individually sealed pills. Note that the pills are arranged in four numbered rows of 7 pills, with the preprinted days of the week printed above them. All 28 pills are "active" birth control pills. Refer to the sample of the blister card below:
To remove a pill, push down on the pill with your thumb and forefinger so that the pill releases through the back of the blister card. Each day, take one pill. Always go from left to right along the row. Each new row will begin on the same day of the week.
Take one pill every day for 28 days, whether bleeding or not, until you have taken all the pills. It is important that you take your pill at the same time every day.
After you have taken all 28 pills, begin taking your pills again the next day. Be sure that the calendar day on your new package corresponds with the actual day.

All brand names listed are the registered trademarks of their respective owners and are not Dr. Reddy's Laboratories.

Distributed by:

 Dr. Reddy's Laboratories Inc.

princeton, NJ08540

Rev. 10/2023

---

### Process and treatment of pedometer data collection for youth: the Canadian physical activity levels among youth study [^115A8fkT]. Medicine and Science in Sports and Exercise (2010). Low credibility.

Background

Pedometry methods for collecting data in young populations are advancing, but it is unclear how many days of data are enough for population monitoring.

Methods

Using random-digit dialing, 11,669 5- to 19-yr-olds were recruited into the Canadian Physical Activity Levels among Youth study and mailed a data collection package. Pedometers were worn for 7 d, and steps counts were logged daily. Reactivity was assessed by examining estimates from the pattern of pedometer data across days (arranged from first day of collection to last) using a repeated-measures ANOVA. Intraclass correlations (ICC) were computed for the first day and consecutive additional days (compared with the criterion estimate based on the whole week) to determine the minimal number of days required to achieve a reliability ICC of 0.70, 0.80, and 0.90.

Results

Most children (990%) wore the pedometer for 7 d. Mean steps per day differed across consecutive days (F = 52.7, P = 0.000); however, no difference occurred between the first and the second day of monitoring. Furthermore, no difference was observed between the first and either the third or the fourth day when monitoring commenced on a Monday or a Tuesday. Therefore, there was no clear evidence of reactivity. The first day provided a good representation of steps per day relative to the whole week in terms of both reliability (ICC = 0.79) and validity (relative absolute percent error [APE] = 2.5%), and these improved with additional days (2 d, ICC > 0.85; ≥ 3 d, ICC > 0.90; and ≥ 3 d, APE < 1%).

Conclusions

The Canadian Physical Activity Levels among Youth demonstrates the feasibility of national surveillance of physical activity using pedometers. Two days are sufficient to determine steps per day, and a single day appears defensible in terms of population monitoring if minimal standards for reliability are acceptable.

---

### Lateralized neural responses to letters and digits in first graders [^113VPP8C]. Child Development (2019). Medium credibility.

The emergence of visual cortex specialization for culturally acquired characters like letters and digits, both arbitrary shapes related to specific cognitive domains, is yet unclear. Here, 20 young children (6.12 years old) were tested with a frequency-tagging paradigm coupled with electroencephalogram recordings to assess discrimination responses of letters from digits and vice-versa. One category of stimuli (e.g., letters) was periodically inserted (1/5) in streams of the other category (e.g., digits) presented at a fast rate (6 Hz). Results show clear right-lateralized discrimination responses at 6 Hz/5 for digits within letters, and a trend for left-lateralization for letters. These results support an early developmental emergence of ventral occipito-temporal cortex specialization for visual recognition of digits and letters, potentially in relation with relevant coactivated brain networks.

---

### A randomized, controlled pilot trial of the emotional faces memory task: a digital therapeutic for depression [^116a3Udi]. NPJ Digital Medicine (2018). Low credibility.

Procedure

The study intervention was administered over 20 visits. At the first visit, the SCID and Ham-D were administered to confirm MDD diagnosis and determine symptom severity. A subsequent baseline evaluation assessed reading level, attention and working memory, MDD symptom severity, and participants' perceived acceptability of a cognitive training exercise as an intervention for MDD. To measure reading ability, a Wide Range Achievement Test Reading test was administered. To assess attention span and working memory, a composite score was calculated as the mean scaled score from the Digit-Span Forward (DSF), Digit-Span Backward (DSB) and Letter-Number Sequencing (LNS) subtests of the Wechsler Adult Intelligence Scale-3rd Edition.MDD symptoms were evaluated using the clinician-rated Ham-D, and the self-report measure Beck Depression Inventory (BDI-II). Acceptability of a cognitive training intervention as a treatment for MDD was assessed using a 5-point Likert-scale ("Using the scale below, please circle the number corresponding to how acceptable cognitive training would be to you, for the treatment of your depression symptoms, if cognitive training were a treatment option in the future". 1: not at all acceptable; 3: somewhat acceptable; 5: very acceptable).

Participants were randomly assigned to the EFMT or CT groups by a research coordinator using a pre-determined randomization sequence for group assignment, with balancing in blocks of six participants in the sequence. Investigators and blinded study raters were kept blind to group assignment throughout the study. Participants were assigned to complete 18 training sessions over 6 weeks (approximately 20–35 min each, three times per week). Participants that failed to complete at least two sessions in any week, or that missed greater than three sessions during the course of the study, were discontinued as per the study protocol. Weekly Ham-D assessments were conducted by PhD or MD-level clinicians who were blind to group assignment. Ham-D raters were extensively trained to administer the assessment and demonstrated an ICC > 0.8 on two separate training interviews. An outcome evaluation was conducted within 1 week of completing the training sessions, at which time the baseline assessments were repeated. At the outcome evaluation, assessments of participants' perceived acceptability of a cognitive-training intervention were again obtained, as were assessments of perceived helpfulness with improving memory, improving attention and concentration, improving control over thoughts, and improving mood. Assessments were obtained using a 5-point Likert-scale (1: not acceptable; 3: somewhat acceptable; 5: very acceptable).

---

### Neurocognitive deficits in survivors of childhood acute myeloid leukemia [^112gX7Qi]. BMC Pediatrics (2022). Medium credibility.

Fig. 2
Wechsler Intelligence Scale for Children-Fourth Edition (WISC-IV) and Wechsler Adult Intelligence Scale-Fourth Edition (WAIS-IV) subtest scores. In the WISC-IV cases, the Letter-Number Sequencing subtest score was the lowest (mean [M] = 6.9, standard deviation [SD] = 3.2), and the Coding subtest score was the highest (M = 12.0, SD = 2.9). In the WAIS-IV cases, the Digit Span subtest score was the lowest (M = 9.5, SD = 2.3), and the Arithmetic subtest score was the highest (M = 12.0, SD = 3.7)

The associations between FSIQ and all demographic and clinical variables listed in Table 2 were examined by univariate analysis. The t -test revealed no significant difference in the FSIQ between the WISC-IV and WAIS-IV cases (M = 93.7, SD = 9.3 and M = 105.0, SD = 15.8, respectively, p = 0.16). Among WISC-IV cases, participants aged 10 years and older showed higher FSIQ score than participants under 10 years of age (M = 100.0, SD = 6.1 and M = 85.3, SD = 4.5, respectively, p = 0.017). As presented in Fig. 3, FSIQ was moderately related to the time since diagnosis (rs = 0.59, p = 0.049) and strongly related to age at assessment (r = 0.69, p = 0.013). A longer time since diagnosis and older age at assessment were associated with high FSIQ. Multiple linear regression was performed to predict FSIQ based on the time since diagnosis and age at assessment. A significant regression equation was found (F (2, 9) = 11.74, R² = 0.66, p = 0.003). The participants' predicted FSIQ was equal to 76.01 + 2.05 (time since diagnosis) + 0.88 (age at assessment), where time since diagnosis and age at assessment were measured in years. Both time since diagnosis and age at assessment were significant predictors of FSIQ.

---

### Intact finger representation within primary sensorimotor cortex of musician's dystonia [^116qXWG4]. Brain (2023). Medium credibility.

We then investigated whether there were any changes in the relative structure of the dissimilarities between controls and patients, which can be visualized by plotting the normalized dissimilarities across all digit pairs (Fig. 5A and B), or in two dimensions using multidimensional scaling (Fig. 5C). Replicating earlier studies, we found that this structure was highly invariant across subjects, with the largest dissimilarities for thumb and ring fingers and smallest for the middle and ring fingers. Importantly, we did not find any group difference in the pattern of dissimilarities [S1: F (9,135) = 0.26, P = 0.9831, M1: F (9,135) = 0.03, P = 0.999]. We also tested for a difference between the distances involving the affected fingers compared to the non-affected fingers in the dystonic group. We did not find a significant difference, [S1: t (8) = −1.672, P = 0.133, M1: t (8) = −0.504, P = 0.627], and if anything, the distances involving affected fingers were larger than those only involving unaffected fingers, contrary to the idea dystonia is associated with a loss of separation between cortical digit representation.

---

### The measure of a man: associations between digit ratio and disordered eating in males [^1158uz7C]. The International Journal of Eating Disorders (2010). Low credibility.

Objective

The current study sought to determine whether there is a relationship between prenatal testosterone exposure, as indicated by the digit ratios of the second to fourth fingers (2D:4D ratio), and disordered eating and drive for muscularity in men.

Method

Digit ratios were calculated by measuring photocopies of participants' finger lengths. Self-reported body image and eating attitudes and behaviors were assessed.

Results

There were significant correlations between 2D:4D ratio and disordered eating and drive for leanness, indicating that greater prenatal testosterone exposure was associated with less disordered eating and increased drive for muscularity.

Discussion

This suggests that greater prenatal testosterone exposure may be protective factor against the development of eating disorders in men. Potential mechanisms are discussed.

---

### Serum sodium, cognition and incident dementia in the general population [^1175mWYM]. Age and Ageing (2023). Medium credibility.

Assessment of cognitive function

Cognitive function was assessed using a neuropsychological test battery administered at the research centre both at baseline and during follow-up visits. Assessment methods of cognitive function have been reported in detail previously. In short, the neuropsychological test battery comprised the Mini-Mental State Examination (MMSE), the Letter Digit Substitution Test (LDST), the Stroop Test (Reading, Colour naming and Interference), the Word Fluency Test (WFT), the 15-Word Learning Test (WLT; Immediate recall, Delayed recall and Recognition) and the Purdue Pegboard Test (PPB; right, left and both hands, and the sum of all three). The MMSE is a widely used 30-item test to measure global cognitive function both in research and in clinical settings. MMSE scores < 25 points may indicate cognitive impairment. The LDST (recording digits next to corresponding letters) assesses information processing speed. The Stroop Reading subtask (reading colour names) measures reading speed; the Colour naming subtask (naming observed colours) measures colour naming speed; and the Interference subtask (naming the observed colours of colour names displayed in incongruous ink colour) assesses the cognitive ability to inhibit stimuli interference and captures the well-known Stroop effect. The WFT (naming as many words as possible from a certain category in 1 min) is an assessment of verbal fluency. The 15-WLT Immediate recall subtask (recollection of words immediately after presentation) assesses verbal learning; the Delayed recall subtask (retrieval of words 10 min after presentation) assesses retrieval abilities from verbal memory; and the Recognition subtask (recognition of words presented 10 min earlier) assesses verbal memory recognition. The PPB test (placing pins in holes in 30 s with the left hand, the right hand and both hands) is a measure of dexterity and (psycho)motor skill. For each cognitive test, higher scores indicate better performance, except for the Stroop test for which higher scores indicate worse performance. Therefore, the inverse of the Stroop test is included in the current study to facilitate comparison to the other cognitive tests. As a measure of global cognitive function, we calculated a general cognitive factor (G-factor) by performing a principal component analysis incorporating the LDST, the Interference subtask of the Stroop Test, the WFT, the sum-score of the PPB subtasks and the delayed recall subtask of the 15-WLT. To avoid distortion of factor weights because of strongly correlated subtasks, we selected the most informative and relevant subtasks from the multi-subtask cognitive tests. The G-factor was only calculated when information on all five individual cognitive tests was available.

---

### Is prolonged use of antibiotic prophylaxis and postoperative antithrombotic and antispasmodic treatments necessary after digit replantation or revascularization? [^112zNDBX]. Clinical Orthopaedics and Related Research (2023). Medium credibility.

Background

Ensuring the patency of repaired vessels is pivotal in improving the success rate of digit replantation. There is no consensus on how to best approach postoperative treatment for digit replantation. The influence of postoperative treatment on the risk of failure of revascularization or replantation remains unclear.

Questions/Purposes

(1) Is there an increased risk of postoperative infection with early discontinuation of antibiotic prophylaxis? (2) How are anxiety and depression affected by a treatment protocol consisting of prolonged antibiotic prophylaxis and administration of antithrombotic and antispasmodic drugs and by the failure of a revascularization or replantation procedure? (3) Are there differences in the risk of revascularization or replantation failure based on the number of anastomosed arteries and veins? (4) What factors are associated with failure of revascularization or replantation?

Methods

This retrospective study was conducted between July 1, 2018, and March 31, 2022. Initially, 1045 patients were identified. One hundred two patients chose revision of amputation. In all, 556 were excluded because of contraindications. We included all patients in whom the anatomic structures of the amputated part of the digit were well preserved, and those with an ischemia time for the amputated part that did not exceed 6 hours. Patients in good health without any other serious associated injuries or systemic diseases and those without a history of smoking were eligible for inclusion. The patients underwent procedures that were performed or supervised by one of four study surgeons. Patients were treated with antibiotic prophylaxis (1 week); patients treated with antithrombotic and antispasmodic drugs were categorized into the prolonged antibiotic prophylaxis group. The remaining patients treated with antibiotic prophylaxis for less than 48 hours and no antithrombotic and no antispasmodic drugs were categorized into the nonprolonged antibiotic prophylaxis group. Postoperative follow-up was for a minimum of 1 month. Based on the inclusion criteria, 387 participants with 465 digits were selected for an analysis of postoperative infection. Twenty-five participants with a postoperative infection (six digits) and other complications (19 digits) were excluded from the next stage of the study, in which we assessed factors associated with the risk of failure of revascularization or replantation. A total of 362 participants with 440 digits were examined, including the postoperative survival rate, variation in Hospital Anxiety and Depression Scale scores, the association between the survival rate and Hospital Anxiety and Depression Scale scores, and the survival rate based on the number of anastomosed vessels. Postoperative infection was defined as swelling, erythema, pain, purulent discharge, or a positive bacterial culture result. Patients were followed for 1 month. The differences in anxiety and depression scores between the two treatment groups and the differences in anxiety and depression scores based on failure of revascularization or replantation were determined. The difference in the risk of revascularization or replantation failure based on the number of anastomosed arteries and veins was assessed. Except for statistically significant variables (injury type and procedure), we thought that the number of arteries, number of veins, Tamai level, treatment protocol, and surgeons would be important. A multivariable logistic regression analysis was used to perform an adjusted analysis of risk factors such as postoperative protocol, injury type, procedure, number of arteries, number of veins, Tamai level, and surgeon.

Results

Postoperative infection did not appear to increase without prolonged use of antibiotic prophylaxis beyond 48 hours (1% [3 of 327] versus 2% [3 of 138]; OR 2.4 [95% confidence interval (CI) 0.5 to 12.0]; p = 0.37). Intervention with antithrombotic and antispasmodic therapy increased the Hospital Anxiety and Depression Scale scores for anxiety (11.2 ± 3.0 versus 6.7 ± 2.9, mean difference 4.5 [95% CI 4.0 to 5.2]; p < 0.01) and depression (7.9 ± 3.2 versus 5.2 ± 2.7, mean difference 2.7 [95% CI 2.1 to 3.4]; p < 0.01). In the analysis based on the failure of revascularization or replantation, the Hospital Anxiety and Depression Scale scores for anxiety (11.4 ± 4.4 versus 9.7 ± 3.5, mean difference 1.7 [95% CI 0.6 to 2.8]; p < 0.01) and depression (8.5 ± 4.6 versus 7.0 ± 3.1, mean difference 1.5 [95% CI 0.5 to 2.5]; p < 0.01) were higher in the failed revascularization or replantation group than in the successful revascularization or replantation group. There was no increase in the artery-related risk of failure (one versus two anastomosed arteries: 91% versus 89%, OR 1.3 [95% CI 0.6 to 2.6]; p = 0.53). For patients with anastomosed veins, a similar outcome was observed for the two vein-related risk of failure (two versus one anastomosed vein: 90% versus 89%, OR 1.0 [95% CI 0.2 to 3.8]; p = 0.95) and three vein-related risk of failure (three versus one vein anastomosed: 96% versus 89%, OR 0.4 [95% CI 0.1 to 2.4]; p = 0.29). Factors associated with failure of revascularization or replantation included the mechanism of injury (crush: OR 4.2 [95% CI 1.6 to 11.2]; p < 0.01, avulsion: OR 10.2 [95% CI 3.4 to 30.7]; p < 0.01). Revascularization had a lower risk of failure than replantation (OR 0.4 [95% CI 0.2 to 1.0]; p = 0.04). Treatment with a protocol of prolonged antibiotics, antithrombotics, and antispasmodics was not associated with a lower risk of failure (OR 1.2 [95% CI 0.6 to 2.3]; p = 0.63).

Conclusion

With proper wound debridement and patency of repaired vessels, prolonged use of antibiotic prophylaxis and regular antithrombotic and antispasmodic treatment may not be necessary for successful digit replantation. However, it may be associated with higher Hospital Anxiety and Depression Scale scores. Postoperative mental status is associated with digit survival. Well-repaired vessels, instead of the number of anastomosed vessels, could be critical to survival and decrease the influence of risk factors. Further research on consensus guidelines that compare postoperative treatment and the surgeon's level of expertise after digit replantation should be conducted at multiple institutions.

Level Of Evidence

Level III, therapeutic study.

---

### Geriatric emergency department guidelines [^115BUUVb]. Annals of Emergency Medicine (2014). Medium credibility.

Geriatric emergency department guidelines — cognitive screening instructions state: "Now I would like to ask you some questions to check your memory and concentration. Some of them may be easy and some of them may be hard". Items include "1) What year is it now?" and "2) What month is this?" with scoring "(0) (1)". The patient repeats "John Brown, 42 Market Street, Chicago" with "Trials to learning ______ (if unable to do in 3 trials = C)". For time, "Without looking at your watch or the clock, tell me what time it is", with "(within 1-hour) ______ Correct Incorrect (0) (1)" and "Actual time: ________". "4) Count aloud backwards from 20 to 1" is scored "0 1 2 Errors", with the note "If subject starts counting forward or forgets the task, repeat instructions and score one error", and the sequence "20 19 18 17 16 15 14 13 12 11 10 9 8 7 6 5 4 3 2 1". "5) Say the months of the year in reverse order", showing "D N O S A JL JN MY AP MR F J" and "0 1 2 Errors", with the rule "If the tester needs to prompt with the last name of the month of the year, one error should be scored". "6) Repeat the name and address you were asked to remember" shows "(John Brown, 42 Market Street, Chicago) 0 1 2 3 4 5 Errors".

---

### Can user testing of a clinical trial patient information sheet make it fit-for-purpose? – a randomized controlled trial [^111ZRwnr]. BMC Medicine (2011). Low credibility.

Procedure

This phase comprised 3 stages:

1. Testing of the original information sheet. The information was tested using participants who were instructed to imagine receiving treatment for leukemia and being asked to take part in a trial to test different drug treatments. They were posted the sheet so that they received it at least 24 hours before testing and were asked to read it carefully (and note how many minutes it took them to read it). When they attended for testing they were given a chance to read it once more (with the reading time recorded) and were left alone to do so. Then each of the 21 user test questions was put in turn and the participant was asked, first, to find the answer in the sheet and, second, to give their answer and, where required, to explain what the information meant. The interviewer judged if the participant had demonstrated understanding by their answer to each question; any uncertainties in scoring were resolved through later discussion among the interviewers and PK, by using the interview transcript. No upper time limit was placed on answering each question and the interviewer moved on to the next question when the participant provided an answer, or if the participant gave up and requested to move on, or when it became clear that they could not find the answer. After the 21 structured questions participants were asked for their general impressions of the sheet, with particular focus on the appearance, wording, print size, headings and organization of information. Interviews were audio recorded and transcribed.

2. Re-wording and re-design of the Information Sheet. Revision of the information was based on three sources: participants' user test questionnaire data and their opinions; good practice in information wording and design; the authors' experience and expertise in information writing and design. Care was taken to retain the original meaning of the information, and no information was removed, except in the case of repetition.

3. Testing of the revised Information Sheet (as per stage (1), followed again by participants' evaluative comments.

Data analysis

Data analysis looked at: the scores for each of the 21 questions to determine how many participants could find and then understand the answer to each question and could at least eight of ten participants do so, to match European Commission legislative thresholds for licensed medicine leaflets; how many participants could answer all of the 21 questions correctly (that is, score a clear round); and participants' evaluative comments after the formal questioning.

---

### Comparing cognitive tests and smartphone-based assessment in 2 US community-based cohorts [^115drDJi]. Journal of the American Heart Association (2024). Medium credibility.

In the BHS, like the FHS protocol, the neuropsychological test evaluation requires trained personnel and takes ≈45 minutes to complete. The BHS examinations are conducted every 4 to 5 years and evaluate executive control, attention/information processing speed, and verbal episodic memory domains. The specific neuropsychological tests analyzed for the current research included the most recent examination, including the Digit Span Forward and Digit Span Backward tests (WAIS‐IV), TMT‐A and TMT‐B, WAIS‐IV Logical Memory Immediate and Delayed Free Recall, Delayed Recognition (Wechsler Memory Scale‐IV), and WAIS‐IV Digit Symbol Coding tests.

A Global Cognitive Score (GCS) was computed using the same approach for FHS and BHS data to ensure the comparability of results. The TMT‐A and TMT‐B were reverse‐scored so that higher scores indicated better performance. Because neuropsychological performance is highly influenced by cultural constructs and may result in the overrepresentation of lower and higher scores, we demographically corrected neuropsychological scores to yield more comparable indicators of cognitive function. Neuropsychological test raw scores were standardized into Z scores corrected for age, sex, and race, then averaged to compute a GCS. For descriptive purposes, the GCS was divided into quartiles. The 2 middle quartiles were merged into 1 single group to allow for lower and upper tail descriptions resembling better and worse cognitive performance, given that all individuals were cognitively normal.

As a secondary analysis, domain‐specific Z scores were created separately in both cohorts to examine the association between DANA task digital outcome measures and executive function abilities (Digit Span Backward and TMT‐B), attention and processing speed (Digit Span Forward and TMT‐A), and verbal/visual episodic memory (Immediate and Delayed Free Recall).

Sociodemographic Characteristics

Sociodemographic data were collected in accordance with established FHS and BHS protocols, respectively. Variables included age (years) at neuropsychological exam, sex (women, men), and education (less than high school, high school, some college, and college graduate). Information on the educational level was obtained from self‐reported questionnaires. Given that race, income, geography, and other social determinants affect the quality of education and are not fully captured by education years alone, educational attainment was gauged using a proxy of premorbid cognitive abilities. Specifically, a word reading test (Wide Range Achievement Test‐3 for FHS participants and Wide Range Achievement‐4 for BHS participants) was used, and the index score was converted into a Z score.

---

### Cognitive executive function in dystonia [^113pBb2N]. Movement Disorders (2003). Low credibility.

Dystonia is a movement disorder considered to result from basal ganglia dysfunction. The aim of this study was to investigate the functional significance of frontal hyperactivity demonstrated in dystonia in imaging studies by examining executive function and working memory, in which the prefrontal cortex is known to be involved. We assessed 10 patients with idiopathic dystonia and 12 age- and IQ-matched normal controls. All subjects completed tests of first letter, category, and alternating category word fluency, the Wisconsin Card Sorting Test, the Stroop Colour Word Naming Test, the Missing Digit Test of working memory, a test of random number generation, a test requiring generation of self-ordered random number sequences, the Paced Serial Addition Test, a test of conditional associative learning, and finger tapping and peg insertion under unimanual, bimanual, and dual task conditions. The patients with dystonia did not differ significantly from controls on any measures of executive function or working memory used other than category word fluency and the extent of decline in tapping with one hand under dual task conditions when simultaneously inserting pegs with the other hand. For this small sample, the results suggest that unlike other movement disorders associated with fronto-striatal dysfunction such as Parkinson's disease or Huntington's disease, dystonia was not associated with deficits on the tests of executive function or working memory used. A more detailed investigation of cognitive function in a larger sample of patients is required.

---

### Quantitative sensory testing: report of the therapeutics and technology assessment subcommittee of the American Academy of Neurology [^1177R4p4]. Neurology (2003). Medium credibility.

Strength of recommendations — For rating A, the page defines "Established as useful/predictive or not useful/predictive for the given condition in the specified population" and states that "Level A rating requires at least one convincing Class I study or at least two consistent, convincing Class II studies"; for rating B, it defines "Probably useful/predictive or not useful/predictive for the given condition in the specified population" and that "Level B rating requires at least one convincing Class II study or at least three consistent Class III studies"; for rating C, it defines "Possibly useful/predictive or not useful/predictive for the given condition in the specified population" with "Level C rating requires at least two convincing and consistent Class III studies"; rating U indicates "Data inadequate or conflicting. Given current knowledge, test/predictor is unproven".

---

### Digit distribution of proper digital nerve action potential [^114xtxjf]. Muscle & Nerve (2001). Low credibility.

Antidromic sensory nerve action potential testing is well characterized and commonly used to assess the sensory component of the upper limb median and ulnar nerves. The final terminal segments of these nerves are the proper digital nerves. Ring recording electrodes are commonly used to detect the proper digital nerves' antidromic responses. Attempts to record the separate contributions of individual digital nerves along the lateral aspects of each finger, using small surface electrodes, is shown to be unreliable for determining the integrity of a single terminal digital branch. We found between 50% to 77% of the stimulated terminal branch's response amplitude when recorded at electrodes positioned over the nonstimulated branch located 180 degrees from the activated terminal branch. Detecting a single terminal nerve response was achieved by using the fourth digit and the second digit with one of the second digit's branches neurophysiologically blocked by local anesthetic. The volume-conducted response from the opposite side of the finger resulted in this relatively large recorded response, which remains within the range of reference values precluding the simple use of antidromic techniques to assess injury to a single proper digital nerve. Techniques are proposed to avoid such pitfalls and to assess most accurately the desired response.

---

### Association of prenatal depression with second to fourth digit ratio in children aged 4 and 6 years [^115v7dsv]. Depression and Anxiety (2025). Medium credibility.

3.3. Association Between Prenatal Depressive Symptoms and 2D:4D Ratios in Children

Table 2 demonstrates a general pattern that prenatal depressive symptoms were associated with higher 2D:4D ratios in the offspring. Specifically, for depressive symptoms in the second trimester, a statistically significant increase in digit ratios was observed in the left hand of the offspring (2D:4DL) at 4 years of age, with increments of 0.007 (95% CI: 0.000, 0.015) for the subthreshold depressive group and 0.010 (95% CI: 0.001, 0.019) for the screen-positive depressive group. In relation to the depressive symptoms in the third trimester, associations were observed on 2D:4DL of offspring at both 4 and 6 years of age, although statistically significant increases were only found in the screen-positive depressive group (4-years: β: 0.012, 95% CI: 0.001, 0.023 and 6-years: β: 0.014, 95% CI: 0.003, 0.024). A dose–response effect was observed across different levels of the depressive group in all the above associations. Stratification by sex showed a similar pattern, with an additional association with an increased 2D:4DR ratio among girls aged 6 years in the third trimester (Table 2).

---

### Codesigned standardised referral form: simplifying the complexity [^112iEZFR]. BMJ Health & Care Informatics (2024). High credibility.

Table 3
Categories of unique referral data on referral forms and in referral guidelines

The average number of referral data fields per digital referral was significantly higher than paper referrals (55.0 ± 10.6 vs 30.5 ± 8.1; 95% CI p < 0.01; figure 1). Subgroup analysis (figure 2) demonstrated that digital referrals have significantly higher average number of informational data (13.7 ± 1.7 vs 8.6 ± 2.9; 95% CI p < 0.01), checkboxes (13.7 ± 1.7 vs 4.8 ± 3.4; 95% CI p < 0.01) and free-text entry (31.1 ± 5.0 vs 16.1 ± 6.0; 95% CI p < 0.01) requests. The average number of attachment requests was not significantly different between digital and paper referrals (1.1 ± 1.4 vs 1.0 ± 1.0; 95% CI p = 0.38).

Figure 1
Mean number of referral data types requested per paper and digital referral form (✱ p ≤ 0.01).

Figure 2
Mean number of referral data types requested within each category for paper and digital referral forms (✱ p ≤ 0.001).

---

### Differences in spatial acuity between digits [^114SafBk]. Neurology (2001). Low credibility.

The spatial acuity of the index, middle, and ring distal finger pads of eight right-handed men, aged 22 to 57 years, was measured by using gratings and raised letters. Acuity declined significantly from the index to the middle finger and from the middle to the ring finger. There were no significant differences between homologous fingers of the two hands. Letter recognition and grating orientation threshold measures were highly correlated.