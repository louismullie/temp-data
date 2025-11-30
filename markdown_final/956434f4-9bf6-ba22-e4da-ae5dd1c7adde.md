# Medical Question & Answer

**Sample ID**: 956434f4-9bf6-ba22-e4da-ae5dd1c7adde
**Dataset Index**: 13958

---

## Question

Find the pH of a solution of 0.3 M acetic acid. Assume a K_a value of 1.8 × 10^-5.

Answer Choices:
A. 4.00
B. 2.63
C. 2.87
D. 3.00
E. 2.20
F. 2.35
G. 4.52
H. 3.15
I. 1.95
J. 3.47

---

## Answer

> Let's see… What do we have here? The user is asking for the pH of a 0.3 M acetic acid solution, given Ka = 1.8 × 10^-5, and to select the correct option from the provided choices. Let's break this down step-by-step. First, I need to think about the acid dissociation equilibrium and the expression for Ka. Then, I should set up an ICE table and make a reasonable approximation for the small dissociation. Next, I will solve for the hydrogen ion concentration and calculate pH. After that, I should verify the approximation and, if needed, iterate or use the quadratic formula. Finally, I will compare the result to the answer choices and confirm the closest match.

> Let me first confirm the equilibrium and the Ka expression. Acetic acid dissociates as CH3COOH ⇌ H+ + CH3COO−, so Ka = [H+] [CH3COO−]/[CH3COOH] = 1.8 × 10^-5, and I should remember that the initial concentration of acetic acid is 0.3 M, with [H+] and [CH3COO−] initially zero [^cd7c14f4].

> I will now examine the ICE table setup. Let x be the concentration of H+ and CH3COO− at equilibrium; then [CH3COOH] at equilibrium is 0.3 − x, and Ka = x^2/(0.3 − x). Wait, let me verify the assumption before proceeding: because acetic acid is a weak acid and Ka is small, I can reasonably assume x is much less than 0.3, so 0.3 − x ≈ 0.3, which simplifies the equation to x^2/0.3 ≈ 1.8 × 10^-5 [^cd7c14f4].

> Next, I should solve for x. Multiplying both sides by 0.3 gives x^2 ≈ 5.4 × 10^-6, so x ≈ √(5.4 × 10^-6) ≈ 2.32 × 10^-3 M. Hold on, I should verify the magnitude: yes, 2.3 × 10^-3 is indeed much smaller than 0.3, so the approximation is justified here [^cd7c14f4].

> Now I will calculate pH. pH = −log10[H+] = −log10(2.32 × 10^-3) ≈ 2.63. Let me double-check the logarithm: log10(2.32) is about 0.365, so −(0.365 − 3) = 2.635, which rounds to 2.63 [^cd7c14f4].

> But wait, what if the approximation is too coarse? I should confirm by checking the percent dissociation. x/0.3 ≈ 0.0077, or about 0.77%, which is well under 5%, so the assumption that x ≪ 0.3 is valid and no quadratic solution is necessary here. If I were to use the quadratic, x^2 + 1.8 × 10^-5x − 5.4 × 10^-6 = 0, the positive root would be essentially identical to 2.32 × 10^-3, confirming the approximation is fine [^cd7c14f4].

> Finally, I need to match the calculated pH to the options. 2.63 corresponds to option B. Hold on, let's not jump to conclusions; I should ensure no rounding or transcription error occurred. Rechecking the math, the closest choice is indeed B. 2.63 [^cd7c14f4].

---

The pH of a 0.3 M acetic acid solution with Ka = 1.8 × 10⁻⁵ is **2.63**. This is calculated using the weak acid approximation [^cd7c14f4], where [H⁺] = √(Ka × [HA]) = √(1.8 × 10⁻⁵ × 0.3) ≈ 2.32 × 10⁻³ M, giving pH ≈ 2.63. The approximation is valid because [H⁺] is much less than 5% of the initial acid concentration.

---

## Calculation of pH

### Step 1: Write the dissociation equation and expression for Ka

Acetic acid dissociates in water as:

CH₃COOH ⇌ CH₃COO⁻ + H⁺

The acid dissociation constant (Ka) is given by:

Ka = [CH₃COO⁻] [H⁺] / [CH₃COOH]

Given Ka = 1.8 × 10⁻⁵ and initial [CH₃COOH] = 0.3 M, we assume [H⁺] = [CH₃COO⁻] = x at equilibrium and [CH₃COOH] ≈ 0.3 M because dissociation is small [^cd7c14f4].

---

### Step 2: Apply the weak acid approximation

For weak acids, when x is small compared with the initial concentration, we can approximate:

Ka ≈ x² / [CH₃COOH]

Thus:

x² ≈ Ka × [CH₃COOH] = 1.8 × 10⁻⁵ × 0.3 = 5.4 × 10⁻⁶

x ≈ √(5.4 × 10⁻⁶) ≈ 2.32 × 10⁻³ M

---

### Step 3: Calculate pH

pH = −log[H⁺] = −log(2.32 × 10⁻³) ≈ 2.63

---

## Verification of the approximation

The weak acid approximation is valid if x is less than 5% of the initial concentration. Here, x ≈ 2.32 × 10⁻³ M, which is about 0.77% of 0.3 M, so the approximation is acceptable [^cd7c14f4].

---

## Conclusion

The pH of a 0.3 M acetic acid solution with Ka = 1.8 × 10⁻⁵ is **2.63**.

---

## References

### Acetic acid [^a0384729]. FDA (2025). Medium credibility.

HOW SUPPLIED

Acetic acid otic solution, USP, containing 2% acetic acid, is available in 15 mL measured‑drop, safety-tip plastic bottles.

NDC 68071-2984-5 15 mL Bottle

---

### Extremely stable graphene electrodes doped with macromolecular acid [^cd7c14f4]. Nature Communications (2018). Medium credibility.

We also tested the chemical stability by dipping HNO 3 -doped or PFSA-doped graphene into a solution of strong acid (hydrochloric acid, K a > 1), weak acid (acetic acid, K a: ~1.8 × 10 −5), weak base (ammonium hydroxide, K b: ~1.8 × 10 −5), or strong base (sodium hydroxide, K b > 1) for 15 s. R sh of HNO 3 -doped graphene greatly increased after acid and base treatments (Fig. 4b and Supplementary Table 3). Especially, R sh of HNO 3 -doped graphene after sodium hydroxide treatment was unmeasurable using the 4-point probe method; this result can be attributed to tearing of the surface of HNO 3 -doped graphene by treatment with strong base chemicals (Supplementary Fig. 6a). In contrast, the surface of PFSA-doped graphene remained smooth even in strong base solution, so R sh of this graphene increased much less than it did in HNO 3 -doped graphene (Supplementary Fig. 6b). These results demonstrate that p-type doping using macromolecular acid is stable against almost every chemical environment.

---

### Acetic acid [^3f5c7e26]. FDA (2025). Medium credibility.

DESCRIPTION

Acetic acid otic solution, USP is a solution of acetic acid (2%), in a propylene glycol vehicle containing propylene glycol diacetate (3%), benzethonium chloride (0.02%), sodium acetate (0.015%), and citric acid. The molecular formula for acetic acid is CH3COOH, with a molecular weight of 60.05. The structural formula is:

Acetic acid otic solution, USP is available as a nonaqueous otic solution buffered at pH 3 for use in the external ear canal.

---

### Marcus kinetics control singlet and triplet oxygen evolving from superoxide [^64c6c391]. Nature (2025). Excellent credibility.

Proton-induced disproportionation

Six types of buffers were used for proton-induced superoxide disproportionation. Britton–Robinson (BR) buffers were prepared with 0.1 M acetic acid, 0.1 M boric acid and 0.1 M phosphoric acid. NaOH (1 M) and HCl (1 M) were used to adjust the pH. Phosphate-buffered saline (PBS) solution and aqueous PBS powder solution (for pH 7.4) were added and the pH was adjusted using 1 M NaOH or 1 M HCl. Citrate buffers were prepared using citric acid and trisodium citrate dihydrate. To adjust the pH, we varied the concentrations of citric acid and trisodium citrate dihydrate. Acidic buffers of KCl and HCl (pH 1 and 2) were prepared by mixing 0.2 M KCl with 0.2 M HCl and adjusting the volume. Neutral to basic buffers of KH 2 PO 4 /NaOH (pH 7.1 and 10.8) were prepared by mixing 0.1 M KH 2 PO 4 with 0.1 M NaOH and adjusting the volume accordingly. To trap the hydrogen peroxide (H 2 O 2) produced, to eliminate the possibility of forming 1 O 2 by peroxoacids, titanium(IV)oxysulfate solution (TiOSO 4, 15 wt% in dilute sulfuric acid), 1 M NaOH was used to adjust the pH of TiOSO 4 solutions to pH 1.2 and 1.55.

Figure 4c shows 1 O 2 yields still increasing when the pH is below 4.8, the p K a of O 2 −. KO 2 hydrolysis increases the pH in aqueous media according to KO 2 + H 2 O → HO 2 + K + + OH –. Buffer capacities were selected so that the amount of KO 2 did not significantly affect the resulting pH after the reaction. However, despite the buffers, the local pH at the reaction site will be higher than the average. The importance of buffering for a local pH close to the average is evident in control experiments without a buffer. Even at a pH of 1.5, we could not detect 1 O 2 in an unbuffered H 2 SO 4 solution, whereas we could in the buffered one (Extended Data Fig. 6e). Therefore, the 1 O 2 yields in Fig. 4c result from a higher local pH.

---

### Mapping in situ the assembly and dynamics in aqueous supramolecular polymers [^4404bc13]. Nature Communications (2025). High credibility.

Next, we monitored in situ the pH evolution during titration. The pH titration curves of the three PA polymerization systems reveal clear differences in their respective [NaOH]/[PA] ranges where the transformation of micelles into polymers occurs (Fig. 3e and Supplementary Figs. 26 and 27). An abrupt decrease in the slope of [OH −] curves accompanies the onset of polymerization, whereas [OH -] increases with a nearly constant rate after the completion of polymerization, as exemplified in PA-3 assemblies (Fig. 3e, f). These results suggest that a substantial fraction of titrated hydroxide ions is consumed by the deprotonation of monomers in micelles in the transformation into supramolecular polymers. Interestingly, as we switched from PA-1 to PA-2 and then PA-3, the "buffering" effect in the pH titration curves and therefore the consumption of titrated hydroxide ions becomes less pronounced even with the same amount of titrated NaOH. The complexity of these pH titration curves (Fig. 3e) prevents us from directly extracting pKa values from the plateau regions, as done in previous studies on supramolecular gel systems –. Instead, we define the apparent p K a for each polymerization as the pH value measured at = 0.5, corresponding to an equal fraction of protonated micelles and polymers consisting of deprotonated monomers. The pKa values at [PA] = 40 µM increase from 7.85 to 8.76 and 9.60 for PA-1, PA-2, and PA-3, respectively. All these values are substantially lower than that corresponding to free lysine (p K a = 10.5), implying that stronger cohesive hydrogen bonding and hydrophobic collapse of aliphatic segments can lead to more effective deprotonation of monomers. To model the deprotonation process of micelles during transformation, we introduced an allosteric binding model to fit the normalized CD titration curves (Fig. 3a, Supplementary Text 2), by analogy to the cooperative ligand-receptor binding in biological signaling processes. In this model, the micelles containing j monomers are considered as multivalent receptors with 3 j binding sites and the NaOH is regarded as a monovalent ligand. The sequential deprotonation process is assumed to undergo via the ligand-receptor binding governed by the apparent binding constant (K'). Interestingly, the resulting Hill plots, representingas a function of, display similar Hill coefficients (n H) of around 10, corresponding to the slope at the origin of axes for all the three PA systems (Fig. 3g and Supplementary Figs. 28 and 29). A Hill coefficient significantly greater than 1 indicates a cooperative deprotonation process of micelles. Such cooperativity is expected to result in extensive deprotonation of a subset of micelles to form polymers with a negligible amount of intermediate charged states, while the remaining micelles stay fully charged. This mechanism is expected to facilitate a binary assembly model rather than a multistep assembly process, consistent with our experimental observations described above. Additionally, depending on the assumed extent of final deprotonation of micelles, the Hill coefficient of 10 suggests an estimated micelle size ranging from approximately 3 to 10 monomers. Based on this model, the tendency for deprotonation decreases as the apparent binding constant (K') decreases from 5.510 −3 µM −1 in PA-1 to 4.910 −3 µM −1 in PA-2 and 4.110 −3 µM −1 in PA-3 at [PA] = 40 μM (Fig. 3h). These results suggest that despite the identical peptide sequence in the terminal charged domain of all three monomers, their differences in ability to form strongly bonded β-sheets directly affects deprotonation and polymerization propensity.

---

### Redefined ion association constants have consequences for calcium phosphate nucleation and biomineralization [^0ca72573]. Nature Communications (2024). High credibility.

Fig. 1
Two titrations of Ca 2+ ions into phosphate solution at pH 9.8 with strikingly different profiles.

The black curve uses the same experimental conditions as the dark grey curve, except that the calcium solution contains 0.05 M HCl (full data Supplementary Fig. 1). The dashed line represents the concentration of calcium expected if no binding occurs; both titration curves lie below this due to the ion association between Ca 2+ and phosphate ions. The acidified titration (black) shows a higher amount of free calcium ions in the solution and remains linear for a greater amount of added calcium ions (grey and light grey shading highlight the relevant areas under the curves). Additionally, the acidified experiment shows the expected nucleation profile, increasing up to a peak before dropping to a plateau determined by the solubility of the precipitated phase, i.e. with supersaturation. The non-acidified experiment (dark grey) bends early in the titration, and takes a non-linear path directly to the plateau, i.e. without apparent supersaturation. This is caused by a premature phase separation at the dosing tip due to a local overconcentration of calcium (Supplementary Section 1, Supplementary Fig. 2). Sequestration of calcium ions in a separated phase leads to perceived higher ion association.

---

### Hydrocortisone and acetic acid [^48270e04]. FDA (2025). Medium credibility.

DESCRIPTION

Hydrocortisone and Acetic Acid Otic Solution, USP contains Hydrocortisone (1%) and acetic acid, glacial (2%) in a propylene glycol vehicle containing benzethonium chloride (0.02%), citric acid (0.2%), propylene glycol diacetate (3%) and sodium acetate (0.015%).

Acetic acid has a molecular formula of CH3COOH with molecular weight of 60.05. The structural formula is:

Hydrocortisone is a Synthetic Steroid used as an anti-inflammatory and antipruritic agent. Its chemical name is Pregn-4-ene-3,20-dione, 11, 17, 21-trihydroxy-, (11β)-. Hydrocortisone has a molecular formula of C21H30O5with molecular weight 362.46. The structural formula is:

Hydrocortisone and acetic acid is available as a non-aqueous otic solution buffered at pH (2.0 to 4.0) for use in the external ear canal.

---

### Nucleosome acidic patch-targeting binuclear ruthenium compounds induce aberrant chromatin condensation [^393e7120]. Nature Communications (2017). Medium credibility.

Cells were harvested by centrifugation at 8671×g, 20 °C, for 7 min and resuspended in 20 mL of lysis solution I (50 mM glucose, 10 mM EDTA, 25 mM Tris-HCl (pH 8.0)). Following addition of 50 mg lysozyme and incubation at room temperature for 15 min, 40 mL of lysis solution II (0.2 M NaOH, 1% w/v sodium dodecyl sulfate) was added. After a 5 min incubation on ice, 70 mL of lysis solution III (4 M K-acetate, 2 M acetic acid) was added. Precipitated cell debris was spun down at 9000× g, 4 °C, for 20 min and the supernatant was filtered through four layers of sterile gauze. Nucleic acid was precipitated by adding 0.6× volume of isopropanol, incubating on ice for 5 min, and centrifuging at 12,000× g, 4 °C, for 20 min. Pellet was dissolved in 10 mL TE(10,10) buffer (10 mM Tris-HCl [pH 8.0], 10 mM EDTA), and 10 mL of 5 M LiCl solution was added to precipitate the RNA and protein. After spinning down at 12,000× g, 20 °C, for 10 min, isopropanol precipitation was carried out as described above. Pellet was resuspended in 10 mL TE(10,1) buffer (10 mM Tris-HCl [pH 8.0], 1 mM EDTA), and 50 µl of 10 mg mL −1 RNAse A was added. Following a 15 min incubation at room temperature, 0.2× volume of 4 M NaCl and 0.4× volume of 40% PEG 6000 were added. The mixture was incubated on ice for 30 min and centrifuged at 15,000× g, 4 °C, for 30 min. The pellet was then dissolved in 5 mL of TE(10,1) buffer, and 3 mL of phenol:chloroform (1:1 volume ratio) was added to separate plasmid from the remaining protein contaminants. Sample was centrifuged at 4000× g, 20 °C, for 10 min. The aqueous layer was collected and ethanol-precipitated. The purified plasmid pellet was dissolved in TE(10,1) buffer.

---

### Acetic acid [^281763d4]. FDA (2025). Medium credibility.

STORAGE

Store at 20° to 25°C (68° to 77°F) [see USP Controlled Room Temperature]. Keep container tightly closed.

Manufactured by:

Saptalis Pharmaceuticals, LLC

Hauppauge, NY 11788

Distributed by:

TruPharma, LLC

Tampa, FL 33609

Rev. 03/20-R1

---

### Stress-induced metabolic exchanges between complementary bacterial types underly a dynamic mechanism of inter-species stress resistance [^de141b9d]. Nature Communications (2023). High credibility.

In this study, we reveal an important physiological driving force for substantial metabolic excretion by naturally-occurring, free-living bacteria. We find that stressed, growth-arrested bacteria convert externally-provided carbon substrates into valuable central carbon metabolites and subsequently excrete them almost completely, and that these excreted metabolites are required for other growth-arrested species in the community to resume growth and relieve stress, ultimately restoring the growth of the whole community. This collaborative inter-species stress relief mechanism can occur between species taken from vastly different environments, indicating that it is not a result of selection in specific environments. Instead, this interaction is attributed to a fundamental complementarity between free-living bacteria with opposing modes of metabolism, with both modes needed to overcome stress.

The stress under study here arises from the accumulation of weak organic acids, e.g. acetate, which are commonly encountered in many environments, from the gut to bioreactors –. Weak organic acids are excreted during anaerobic growth, but also aerobically under iron limitation, as well as in favorable growth conditions. The excreted acids become toxic to both the acid-excreting and acid-consuming bacteria when the environmental pH drops to the level of the acids' dissociation constants, ~5 for organic acids such as acetate, We reveal that during such acid stress, an additional layer of metabolic exchange occurs transiently between the growth-arrested acid excreters and acid eaters — "acid-induced cross-feeding" — which is necessary for the acid eaters to consume the organic acids at low pH and thereby detoxify the environment. Based on quantitative, systematic investigations, we will first describe acid-induced cross-feeding in a case of rapid acetate accumulation during the aerobic growth of a co-culture of marine bacteria. We will then show that the same process of stress relief occurs in co-cultures comprising soil and enteric bacteria, and for different mechanisms of acetate accumulation.

---

### Renal association clinical practice guideline on haemodialysis [^bfebe132]. BMC Nephrology (2019). Medium credibility.

Guideline 5.2 - Selection of dialysate buffer

We recommend an optimal pre-dialysis serum bicarbonate in the range 18.0–26.0mmo/L, remembering to consider measurement errors (e.g. due to exposure to air) when interpreting levels. [1C]

We suggest the term 'dialysate buffer' rather than 'dialysate bicarbonate' to avoid confusion arising from differences in manufacturers' terminology. [2C]

We suggest choosing dialysate buffer below or equal to 37.0mEq/L for the majority of patients, using a standardised or individualised approach. [2C]

We suggest a combined approach to abnormal pre-dialysis serum bicarbonate, which may include increasing dialysis dose, oral bicarbonate, nutritional support, or individualising dialysate buffer. [2D]

Rationale

We suggest a combined approach to abnormal pre-dialysis serum bicarbonate, which may include increasing dialysis dose, oral bicarbonate, nutritional support, or individualising dialysate buffer. [2D]

The literature on dialysate bicarbonate is difficult to interpret due to unclear definitions when reporting the bicarbonate and additional alkali components. Most commonly the electrolyte concentrate contains a non-bicarbonate acid, to reduce the deposition of calcium and magnesium salts – acetic acid is perhaps the most common, but citric acid and sodium diacetate may also be used.

When mixed to form the dialysate, acetate reacts with sodium bicarbonate to form sodium acetate, water and carbon dioxide:

The addition of 3mmol of acetic acid to a litre solution containing 35mmol of bicarbonate therefore reduces the bicarbonate concentration to 32mmol/L. In publications, bicarbonate concentration in this dialysate may variably be referred to as having a bicarbonate concentration of 32 or 35mmol/L, with the acetate content rarely reported.

---

### Highly regio-and enantioselective multiple oxy-and amino-functionalizations of alkenes by modular cascade biocatalysis [^d36b55c7]. Nature Communications (2016). Medium credibility.

General procedure to convert 1a–k to (S)- 8a–k

Overall, 2 mL suspension (10 g cdw l –1) of freshly prepared E. coli (A-M1_R-M2_C-M4) cells in KP buffer (200 mM, pH 8.0) containing glucose (0.5%, w/v) and NH 3 /NH 4 Cl (100 mM, NH 3 :NH 4 Cl = 1:10) were mixed with 2 mL n -hexadecane containing one of alkene substrates 1a–k (20 or 5 mM). The reaction mixture was shaken at 300 r.p.m. and 30 °C for 24 h. At 20 h, additional glucose (0.5%, w/v) and NH 3 /NH 4 Cl (100 mM) were added. 300 μl aliquots of the mixture (150 μl of each phase) were taken out at different time points for following the reaction. 150 μl HCl solution (0.8M) were mixed with the 300 μl sample, followed by centrifugation (13,000 g, 2 min) to separate the organic and aqueous phases. The procedures for the preparation of the analytic sample from organic phase and the quantification of alkenes 1a–k and possible epoxides 2a–k by normal phase HPLC are the same as the above mentioned ones for the conversion of 1a–k to 5a–k. For aqueous phase, 200 μl supernatant were diluted with 300 μl TFA solution (0.1%) and 500 μl acetonitrile (containing 2 mM benzyl alcohol as internal standard), and the samples were analysed by reverse phase HPLC for quantifying hydrophilic products 3a–k, 4a–k, 5a–k, 7 a–k and 8a–k. To determine the e.e. of 8a–k, the sample preparation and analysis are the same as those described above for the analysis of the e.e. of 6a–k (see Supplementary Table 7; Supplementary Figs 41–51; Supplementary Methods for analytic methods).

---

### Transformation of dolutegravir into an ultra-long-acting parenteral prodrug formulation [^f444dec2]. Nature Communications (2022). High credibility.

pH affects for prodrug cleavage

The contribution of pH to prodrug cleavage was studied in pH buffers including 7.5 mM ammonium acetate (pH 6.0, adjusted with acetic acid), 7.5 mM ammonium bicarbonate (pH 8.0, adjusted with acetic acid), and pH adjusted solutions including 0.1% formic acid (pH 2.0), and 0.1% ammonium hydroxide (pH 10.3). M2DTG prodrug solution and NM2DTG suspension were incubated in these matrices as per the protocol for rat tissue homogenates and analyzed as such.

---

### Ciprofloxacin hydrochloride (ciprofloxacin HCl ophthalmic) [^9c5ce7c5]. FDA (2022). Medium credibility.

DESCRIPTION

Ciprofloxacin Ophthalmic Solution, USP 0.3% is a synthetic, sterile, multiple dose, antimicrobial for topical use. Ciprofloxacin is a fluoroquinolone antibacterial active against a broad spectrum of gram-positive and gram-negative ocular pathogens. It is available as the monohydrochloride monohydrate salt of 1-cyclopropyl-6-fluoro-1, 4-dihydro-4-oxo-7-(1–piperazinyl)-3-quinoline-carboxylic acid. It is a faint to light yellow crystalline powder with a molecular weight of 385.8. Its empirical formula is C17H18FN3O3•HCl•H2O and its molecular formula is as follows:

Ciprofloxacin differs from other quinolones in that it has a fluorine atom at the 6-position, a piperazine moiety at the 7-position, and a cyclopropyl ring at the 1–position.

Each mL of Ciprofloxacin Ophthalmic Solution, USP 0.3% contains: Active: ciprofloxacin HCl 3.5 mg equivalent to 3 mg base. Preservative: benzalkonium chloride 0.006%. Inactives: sodium acetate, acetic acid, mannitol 4.6%, edetate disodium 0.05%, hydrochloric acid and/or sodium hydroxide (to adjust pH) and Water for Injection. The pH is approximately 4.5 and the osmolality is approximately 300 mOsm.

---

### Redefined ion association constants have consequences for calcium phosphate nucleation and biomineralization [^5e06f0f0]. Nature Communications (2024). High credibility.

Table 1
Overview of the activity-based ion association constants

The values for each of the three possible ion associates between calcium and phosphate ions as calculated from the titration data. The reported values show where agreement between calculation and experiment is optimal, while the errors provide the bounds to the reasonable range where the ion pairing constants lie. The error is largely due to the global fitting of all pH values; the deviation between curves within one set of measurements is generally less than 5%, and therefore relatively insignificant for the evaluation of ion association shown here. The limits where the calculated curves begin to deviate from the experimental data are explored in the Supplementary Information (Supplementary Figs. 9–11).

As seen in Supplementary Fig. 9, the binding is slightly underestimated at the highest pH values and it is overestimated at lower pH. In-between these extremes the binding is overestimated (pH 10.3 and 9.8), underestimated (pH 9.3 and 8.8), and nearly spot on (pH 8.3). In all cases the Predictive Calculation lies closer to the experimental data, and the curves are straight lines. Meanwhile the Direct Calculation model mirrors curvature in the data at pH 7.3 and 7.8, while also deviating from the measured curves at a pH of 11.3.

---

### Polyelectrolyte interactions enable rapid association and dissociation in high-affinity disordered protein complexes [^032b28f2]. Nature Communications (2020). High credibility.

To assess the effect of dye labeling of ProTα on the affinity, we performed a competition titration (Fig. 1c): starting from 50 pM labeled ProTα saturated with 10 nM unlabeled H1, the labeled ProTα was outcompeted by increasing amounts of unlabeled ProTα (up to 0.5 μM). If labeled and unlabeled ProTα had identical affinities to H1, the midpoint for the competition would be expected at 18.5 nM unlabeled ProTα (see "Methods" for details on the solution of the coupled binding equilibria). The observed midpoint of ~20 nM (Fig. 1d) yields a K D of 1.1 ± 0.4 nM for the complex between the unlabeled binding partners. Similarly, measurements with ProTα and H1 labeled with different fluorophores, and at different positions in the sequence show that such individual amino acid exchanges and fluorescence labeling alter the K D by not more than about a factor of three (Supplementary Table 1 and Fig. 1). The perturbation of the affinity by the fluorophores is thus small, at most on the order of thermal energy (k B T), in contrast to recent speculative concerns. For comparison, a similar effect on binding free energy results from a change in solution ionic strength by a mere 10–20 mM.

The titrations in Fig. 1 indicate two-state-like behavior, with slow exchange between bound and unbound ProTα compared to the averaging time of the measurement, in this case given by the average fluorescence burst duration of about a millisecond, which is governed by the diffusion time through the confocal detection volume. Assuming a simple two-state binding equilibrium between ProTα (P) and H1 (H), P + H ⇌ PH, with a K D of ~1 nM and the diffusion-limited association rate coefficient, k on, of ~10 9 M −1 s −1, we expect a dissociation rate coefficient, k off = k on K D, of ~1 s −1. The exchange rate between unbound and bound ProTα is k ex = k on c H + k off, where c H is the concentration of unbound H1. Owing to the low concentrations of unbound H1 present at the conditions used in Fig. 1, the reaction is thus indeed in the regime of slow exchange between bound and unbound ProTα (see Supplementary Fig. 2 for the detailed concentration dependences of k ex). At the midpoint of the titration in Fig. 1c, for instance, we expect slow exchange with k ex ≈1 s −1 using the values above.

---

### Molecular basis of cooperativity in pH-triggered supramolecular self-assembly [^dbd8e6e6]. Nature Communications (2016). Medium credibility.

Based on these results, we constructed a molecular pathway of pH-triggered supramolecular self-assembly of PEO- b -PDPA copolymer (Fig. 4e). Upon addition of NaOH, the block copolymers are homogeneously deprotonated until reaching CMPD. Below CMPD, further addition of base results in formation of mature micelles where the copolymers inside micelles are neutral. Soluble unimers remain highly protonated at a charge state of CMPD in water. The unique pH-induced supramolecular self-assembly pathway appeared to pertain microscopic reversibility (Supplementary Fig. 14). It should be noted that the above molecular pathway describes the thermodynamically stable states of polymers at specific protonation degree as measured by steady-state analytical methods (for example, DLS, 1 H NMR). The kinetic process of protonated unimer conversion to neutral micelles may still involve loose aggregates as transient intermediates and needs to be further investigated.

Model description of pH cooperativity

The all or nothing proton distribution characteristicssuggest a cooperative deprotonation process from fully protonated unimers to the completely neutralized micelles. We hypothesize that rapid deprotonation is driven by hydrophobic phase separation through formation of micelles. We adopted an allosteric model to evaluate the cooperative strength of deprotonation (Fig. 5a; Supplementary Discussion). The progressive neutralization of fully protonated unimers can be characterized by a series of microscopic K i, which corresponds to the i th dissociation constant of polymeric polyatomic acids. The antagonistic or synergistic effect during deprotonation is described by the cooperative parameter α i, which is defined as K i +1 /K i (equation (1) in Fig. 5). The apparent dissociation constant K for the entire deprotonation process is defined by equation (2) (Fig. 5). Assuming identical cooperative parameter α for each ionization step, K can be simplified as equation (3) (Fig. 5). This equation allows a simplified theoretical–experimental correlation between the microscopic cooperative parameter α with macroscopically measurable p K a. Protonation degree (θ A) is used to describe the extent of protonation of tertiary amines. In practice, the Hill plot is used to evaluate the strength of cooperativity by plotting log(θ A /(1− θ A)) versus (p K a −pH) (equation (4) in Fig. 5). The Hill coefficient n H, corresponding to the slope of this plot measured at 50% saturation, is used to quantify the cooperativity strength experimentally.

---

### Highly regio-and enantioselective multiple oxy-and amino-functionalizations of alkenes by modular cascade biocatalysis [^a98fe587]. Nature Communications (2016). Medium credibility.

General procedure to convert 1a–k to (S)- 5a–k

Overall, 2 mL suspension (10 g cdw l –1) of the freshly prepared E. coli (A-M1_R-M2) cells in KP buffer (200 mM, pH 8.0) containing glucose (0.5%, w/v) were mixed with 2 mL n -hexadecane containing one of alkene substrates 1a–k (20 mM). The mixture was shaken at 300 r.p.m. and 30 °C for 12 h, and 150 μl aliquots of each phase were taken out at different time points for following the reaction. For organic phase, 100 μl n -hexadecane were separated after centrifugation (13,000 g, 2 min), diluted with 900 μl n- hexane (containing 2 mM benzyl alcohol as internal standard) and analysed by normal phase HPLC for quantifying alkenes 1a–k and possible epoxides 2a–k. For aqueous phase, 100 μl supernatant were separated after centrifugation (13,000 g, 2 min), diluted with 400 μl TFA solution (0.5%) and 500 μl acetonitrile (containing 2 mM benzyl alcohol as internal standard) and then analysed by reverse phase HPLC for quantifying hydrophilic products 3a–k, 4a–k and 5a–k. To determine the e.e. of 5a–k, the remaining aqueous phase at the end of reaction was separated after centrifugation (13,000 g, 2 min), acidified with TFA and saturated with NaCl, followed by extraction with ethyl acetate and dry over Na 2 SO 4. After evaporation of ethyl acetate, the residue was dissolved in solvent (n -hexane: IPA = 9:1) for chiral HPLC analysis (see Supplementary Table 7; Supplementary Figs 19–29; Supplementary Methods for analytic methods).

---

### Voltage-gated sodium channels assemble and gate as dimers [^98810b93]. Nature Communications (2017). Medium credibility.

Protein extraction

Protein extraction was performed 48 h post-transfection of HEK293 cells with different sodium channel constructs. Cells were rinsed with PBS and lysed for 30 min on ice in lysis buffer (20 mM HEPES, pH 7.4, 150 mM NaCl, 110 mM K-Acetate, pH 7.4, 1 mM MgCl 2, 0.1 μM CaCl 2 1% Triton X-100, 1 mM PMSF, 0.7 μg.ml −1 Pepstatin and complete protease inhibitor cocktail were added to the lysis buffer (Roche, Germany). The soluble fractions centrifuged at 14, 000 g (4 °C) for 4 min, were then used for the experiments. Protein concentrations were measured in duplicate using a Bradford assay with a BSA standard curve. Membrane protein isolation for the co-immunoprecipitation experiments was performed as follow: Cells were washed 3 times in 1X PBS. Cells were resuspended in 3 volumes of 0.3 M sucrose/10 mM sodium phosphate plus AEBSF and complete protease inhibitor cocktail. Cells are sonicated and then incubated on ice for 30 min with vortex every 5 min. Cells are pelleted by centrifugation at 2800 r.p.m. for 10 min at 4 °C to separate nuclei and debris. Supernatant is collected and centrifuged at 8800 r.p.m. for 10 min. Supernatant is collected and centrifuged at 18,000 r.p.m. for 60 min at 4 °C. The pellet contains the membrane proteins and is resuspended in lysis buffer and incubated on ice for 10 min with vortex every 2 min. Solution is then centrifuged at 13,000 r.p.m. for 5 min at 4 °C. The supernatant contains the soluble membrane proteins.

Co-immunoprecipitation

Magnetic Dynabeads (Dynal, Norway) were washed twice with 25 mM citric acid, 50 mM Na 2 HPO 4, pH 5, incubated with the mouse anti-GFP(Clontech, JL-8) or Rat anti-HA (Roche), or pan 14-3-3(H-8) from Santa Cruz Biotechnology antibodies, for 2 h at room temperature, washed three times again with 25 mM citric acid, 50 mM Na 2 HPO 4, Tween 0.1%, and incubated with the pre-cleared lysates samples (total 400 mg protein) while rotating overnight at 4 °C. Beads were washed three times in lysis buffer and then proteins were eluted with the Laemmli sample buffer at 37 °C for 30 min with agitation, and analyzed by Western blot.

---

### Screening non-conventional yeasts for acid tolerance and engineering pichia occidentalis for production of muconic acid [^cb620f19]. Nature Communications (2023). High credibility.

We also screened 93 yeast strains in YPD medium and YPD containing 0.1 M citrate buffer, pH 3.0 (YPD cit). However, this condition was not sufficiently inhibitory, as most strains grew to comparable levels in YPD and YPD cit (Fig. 1a). It has been reported that citric acid is more toxic to yeast at pH 4.5 than pH 3.0 owing to the propensity of the dissociated form to bind divalent cations, providing a possible explanation for our observations.

In addition to dicarboxylic acids, we screened 26 Pichia strains on several monocarboxylic acids using the same conditions (defined 3× YNB medium containing 0.15 M of acid, pH 2.8). Only one strain grew in acetic acid (P. manshurica Y-27978) and none of the tested strains grew in propionic, butyric or valeric acids. Assuming comparable levels of dissociation between monocarboxylic acids, these findings indicate a higher degree of toxicity caused by propionic, butyric and valeric acids at equimolar concentrations.

---

### Vasopressin [^04a4154a]. FDA (2025). Medium credibility.

11 DESCRIPTION

Vasopressin is a polypeptide hormone. Vasopressin injection, USPis a sterile, aqueous solution of synthetic arginine vasopressin for intravenous administration.

The 1 mL solution contains vasopressin 20 units/mL, 1.36 mg sodium acetate buffer and Water for Injection, USP. Sodium hydroxide and hydrochloric acid are included to adjust to a pH of 3.3 to 3.6.

The 100 mL solution contains vasopressin 0.4 units/mL. Each mL of the 0.4 unit/mL strength also contains dextrose anhydrous, 0.0546 mg glacial acetic acid, 0.012 mg sodium acetate and Water for Injection, USP. Sodium hydroxide and hydrochloric acid are included to adjust to a pH of 3.3 to 3.6.

Each vial of the vasopressin injection premixed solutions contains 5% Dextrose in approximately 100 mL Water for Injection. The chemical name of vasopressin is Cyclo (1–6) L-Cysteinyl-L-Tyrosyl-L-Phenylalanyl-L-Glutaminyl-L-Asparaginyl-L-Cysteinyl-L-Prolyl-L-Arginyl-L-Glycinamide. It is a white to off-white powder or flakes, very soluble in water. The structural formula is:

Molecular Formula: C46H65N15O12S2Molecular Weight: 1084.24

One mg is equivalent to 530 units.

---

### Stabilizing effect of amino acids on protein and colloidal dispersions [^6eec9a7d]. Nature (2025). Excellent credibility.

Theoretical framework and its validation

We propose a theoretical framework to explain all the experimental observations presented here. It is based on the hypothesis that weak interactions between the AAs and the colloids in dispersion lead to a time-averaged screening of colloid−colloid attractive interactions (Fig. 3). As described above, the theory considers the colloids as patchy particles and the adsorption of AAs to the surface by a Langmuir-type isotherm. Using these ingredients, we derive the following formula for the change in B 22 as a function of AAs/small molecule concentration c (see Methods for a rigorous derivation):where a 3 corresponds to an effective excluded volume, is B 22 of the colloid in the absence of the small molecule of interest, K is the equilibrium association constant and f max is the maximum surface fraction of the colloid that can be masked by the small molecules.

---

### European Association of Nuclear Medicine practice guideline / Society of Nuclear Medicine and Molecular Imaging procedure standard 2019 for radionuclide imaging of phaeochromocytoma and paraganglioma [^f072a060]. European Journal of Nuclear Medicine and Molecular Imaging (2019). High credibility.

Preparation and quality control — The [111In]IDTPA-pentetreotide preparation remains stable for 6 h and should not be used if the radiochemical purity is less than 90% (USA) or 99% (Europe), the pH of the solution ranges from 3.8 to 4.3, and TLC can be used to check purity using instant TLC with 0.1 N sodium citrate adjusted with HCl to a pH of 5, where Rf values are 111In-pentetreotide 0.0 and unbound 111In 1.0.

---

### Risankizumab-rzaa (Skyrizi) [^66e39be5]. FDA (2025). Medium credibility.

SKYRIZI (risankizumab-rzaa) injection 360 mg/2.4 mL (150 mg/mL) prefilled cartridge for use with the supplied o n- b ody i njector for subcutaneous use

Each SKYRIZI prefilled cartridge contains a sterile, preservative-free, colorless to yellow, and clear to slightly opalescent solution. Each cartridge delivers 360 mg of risankizumab-rzaa, and the inactive ingredients glacial acetic acid (0.13 mg), polysorbate 20 (0.48 mg), sodium acetate (1.8 mg), trehalose (152 mg), and Water for Injection, USP. The pH is 5.7.

SKYRIZI 600 mg/10 mL (60 mg/mL) in a vial for intravenous infusion

SKYRIZI (risankizumab-rzaa) injection 600 mg/10 mL (60 mg/mL) is a sterile, preservative-free, colorless to slightly yellow, and clear to slightly opalescent solution in a 10 mL single-dose vial.

Each 10 mL single-dose vial contains 600 mg of risankizumab-rzaa, and the inactive ingredients glacial acetic acid (0.54 mg), polysorbate 20 (2 mg), sodium acetate (7.5 mg), trehalose (633.3 mg), and Water for Injection, USP. The pH is 5.7.

---

### Rocuronium [^0975a69c]. FDA (2025). Medium credibility.

11 DESCRIPTION

Rocuronium bromide injection is a nondepolarizing neuromuscular blocking agent with a rapid to intermediate onset depending on dose and intermediate duration. Rocuronium bromide is chemically designated as 1- [17β-(acetyloxy)-3α-hydroxy-2β-(4-morpholinyl)-5α-androstan-16β-yl]-1-(2-propenyl)pyrrolidinium bromide.

The structural formula is:

The chemical formula is C32H53BrN2O4with a molecular weight of 609.70. The partition coefficient of rocuronium bromide in n-octanol/water is 0.5 at 20°C.

Rocuronium bromide is supplied as a sterile, nonpyrogenic, isotonic solution that is clear, colorless to yellow/orange, for intravenous injection only. Each mL contains 10 mg rocuronium bromide and 2 mg sodium acetate. The aqueous solution is adjusted to isotonicity with sodium chloride and to a pH of 4 with acetic acid and/or sodium hydroxide.

---

### Imaging of pH in vivo using hyperpolarizedC-labelled zymonic acid [^d469a671]. Nature Communications (2017). Medium credibility.

Characterization of ZA

The mass of the synthesized substance was determined by an HR-MS-spectrum using a Thermo Finnigan LTQ-FT. A MS/MS-spectrum was recorded by CID-fragmentation on a Thermo Finnigan LCQ-Fleet (Supplementary Fig. 2). 1 H and 13 C chemical shifts and coupling networks were extracted from NMR spectra of unlabelled and 13 C fully labelled ZA and its decay products in H 2 O at 14.1 T (Supplementary Fig. 1). ZA concentration-dependent 13 C NMR acid-base titrations were performed with ZA at 37 °C in 1 M phosphate buffer at 14.1 T, adjusting the pH in random order using 1 M HCl and 1 M NaOH. Electrode pH was reported as the mean of two measurements determined directly before and after the NMR experiment with a standard pH electrode. Regular acid-base titrations of 25 mM ZA in 1 M KCl in H 2 O were performed using 1 M KOH at different temperatures. Each full titration was performed within 22 ± 1 min and a model titration curve for a diprotic acid was fitted to each titration experiment separately to extract the relevant acid dissociation constant pK a2 as a function of temperature. The temperature dependence of the acid dissociation constant ΔpK a2 /ΔT was then determined from a linear fit to the extracted data points. Hyperpolarized 13 C NMR acid-base titrations were performed with a solution of 25 mM ZA in presence of 10 mM Ca 2+ at 1 T and 27 °C. The detected pH-dependent hyperpolarized 13 C chemical shifts were compared to regular 13 C NMR acid-base titrations at 37 °C in 1 M phosphate buffer at 14 T. Stability measurements were performed by acquiring 1 H spectra at 1 T and 27 °C over 20 h, each spectrum averaged over 60 scans with a repetition time of 10 s.

---

### Electrification at water-hydrophobe interfaces [^bb0e9f23]. Nature Communications (2020). High credibility.

Dependence on ionic strength and dielectric constant of aqueous solutions

Next, we investigated the effects of ionic strength, water pH, dissolved CO 2 concentration, and dielectric constant of different aqueous mixtures on the electrification process. In dilute electrolytes containing simple monovalent salts, the characteristic length-scale at which electrostatic interactions persist, is known as the Debye length, and it is given by the formulawhere I is the ionic strength of the electrolyte, is the vacuum permittivity, is the relative permittivity of the medium, is the Boltzmann constant, is temperature in Kelvin, is Avogadro's number, and e is the electronic charge. We modulated the Debye lengths of aqueous solutions by varying the ionic strengths and relative permittivity.

We found that by suppressing the Debye lengths by adding ions, the charge carried by the pendant droplets dispensed from the hydrophobic capillaries decreased (Fig. 5a; see Supplementary Fig. 6A for the effects of varying ionic strength with KBr). Upon increasing the concentration of HCl, the measured charge dropped significantly below pH 4, whereas for NaCl and NaOH, the electrification was unaffected up until > 10 mM (Fig. 5a). Indeed, ion-specificity has been reported on various interfacial and bulk properties. To probe whether the acidic solution had neutralized the negatively charged sites on the hydrophobic surface, we measured the change in the charge of the reservoir as well. We found that the charges accrued in the acidic reservoirs were significantly lower in magnitude (albeit, equal and opposite to those of the aliquots withdrawn) than those for NaCl, KBr, and NaOH cases (Supplementary Fig. 6B). This means that rather than the H 3 O + ions getting permanently adsorbed to the water-hydrophobe interface and neutralizing it, they were not even withdrawn from the reservoir in the first place. The lack of the permanent adsorption of the hydronium ions (or surface charge neutralization) is confirmed by the complete recovery of electrification when the same tips were used to pipette deionized water (Supplementary Fig. 6B). These results prove that lower electrification with acids does not always mean that they neutralize the surface charge as previously believed.

---

### Reactive capture of COvia amino acid [^86e21112]. Nature Communications (2024). High credibility.

Fig. 2
Optimization of the capture solution and system stability.

a, b FE towards CO and full cell voltage for a 1 M K-GLY capture solution with 0.1 M of various supporting electrolytes: potassium chloride (KCl), potassium bromide (KBr), potassium iodide (KI), potassium nitrate (KNO 3), potassium sulfate (K 2 SO 4), and monopotassium phosphate (KH 2 PO 4). c FE towards CO and full cell voltage for a 1 M K-GLY capture solution with KH 2 PO 4 supporting electrolyte concentration varying from 0 to 0.3 M. d FE towards CO and full cell voltage for an unsupported 1 M K-GLY capture solution and the optimized capture solution (2 M K-GLY with 0.1 M KH 2 PO 4). e stability test of reactive CO 2 capture for 32 h at an applied current density of 50 mA cm −2 using 1 L of catholyte and anolyte. Error bars represent the standard deviation of at least three independent measurements. Source data are provided as a Source Data file.

---

### Electric fields control the orientation of peptides irreversibly immobilized on radical-functionalized surfaces [^c3b0bec7]. Nature Communications (2018). Medium credibility.

Peptide immobilization

The buffer used for immobilization was designed to have equal ionic strength and buffer capacity at a low and a high pH value. A mixed buffer system was therefore used, with two buffers with different pKa values, allowing similar buffering capacity at two pH values. The buffer system consisted of an acetate/acetic acid buffer (pKa 4.8) and an ammonia/ammonium buffer (pKa 9.2) in the same solution. The pH was increased by 0.6 from the pKa to ensure that the peptide would fully dissolve at the lower pH value while maintaining its maximum charge. At pH = 5.4 the acetate/acetic acid buffer predominates, whereas at pH = 9.8 the ammonia/ammonium buffer predominates, while the buffering capacity is equal in both cases. The buffers were prepared by adjusting the pH of an ammonium acetate solution using either concentrated HCl or NaOH and adding NaCl to equalize the ionic strength.

The FLAG peptide was dissolved in 10 mM buffer at either pH 5.4 or pH 9.8. The incubation on the plasma polymer surface was performed by pipetting 500 µL of peptide solution onto a 1 cm×1 cm sample in a 24-well plate, when no external electric field was being applied. For samples with applied external electric field, the incubation was performed using a custom-made apparatus, schematically shown in Fig. 7. This apparatus consisted of wells of the same dimensions as the 24-well plate, but with electrodes above and below the sample. Each sample was incubated for 20 h at room temperature with or without an electric field applied. A polytetrafluoroethylene foil was placed over the bottom electrode, which ensured that no current was drawn. After incubation, the peptide solution was removed, and the sample was washed three times using 1 mL de-ionized water. To validate the covalent attachment of the peptide, the detergent-washed samples were placed in a 5% Tween 20 or 5% SDS solution heated to 70 °C for 1 h, then washed three times using 1 mL de-ionized water.

---

### Microscale pH variations during drying of soils and desert biocrusts affect HONO and NHemissions [^d7ffc0c5]. Nature Communications (2019). High credibility.

Acid–base model and local pH determination

Coupled ODEs of chemical acid–base reactions are used to determine chemical status of local water film. Local pH was calculated after net diffusions and microbial reactions with an assumption of local charge neutrality. Considered reactions in aqueous phase are

The detailed rates and the acid–base dissociation constants are given in Supplementary Table S2 of Kim and Or. Concentration of protons, pH, was locally determined with an assumption of local charge balance via self-ionisation of waterwhere [H +] [OH −] = K W = 10 −14. By solving the differential algebraic equations, local pH values were obtained during the entire dynamics. The unknown cation, Z +, is considered to be nonreactive, but it is added to the system for charge compensation for pH value of real soil with various minerals. In addition, calcium (Ca 2+) is selected as a representative reactive cation that participates for inorganic carbon availability. All chemical reactions are coupled with the availability of protons at a given temperature. During the acid–base calculation, the extended Debye–Hückel equation is used for all ionic interactions. Supplementary Fig. 1a shows a schematic of the local pH calculation and a typical result of the calculation in Supplementary Fig. 1b.

Analytic solution of local pH under Henry's and acid–base equilibria

At the interface between the air and soil water, the fast equilibration of chemical processes can determine local pH of water film. At equilibrium, constraints of gaseous compounds via Henry's law and the acid–base dissociation relations lead towhere, andare Henry's constants of CO 2, NH 3, and HONO, respectively. Dissociation constants are denoted with capital K for each acid–base reaction. We note that Henry's constants and dissociation constants are temperature-dependent. By substituting these relations at equilibrium to the local charge neutrality principal, Eq. (17) can be rewritten as followingwheredenotes the net charge of fee cations and anions that are not constrained with gaseous compounds. The pH at equilibrium is the positive real root of the cubic polynomial. Since the partial pressures of gaseous compounds are constants in the model, concentrations of Ca 2+, Z +, anddetermine the pH value. The calculated analytic solutions of pH under Henry's and acid–base equilibria for varying mixing ratios of NH 3 and HONO are plotted in Supplementary Fig. 2. For this plot, the partial pressure of CO 2 was assigned as constant, 383 ppm.

---

### Direct assessment of the acidity of individual surface hydroxyls [^ee113ef8]. Nature (2021). Excellent credibility.

The state of deprotonation/protonation of surfaces has far-ranging implications in chemistry, from acid-base catalysis 1 and the electrocatalytic and photocatalytic splitting of water 2, to the behaviour of minerals 3 and biochemistry 4. An entity's acidity is described by its proton affinity and its acid dissociation constant pK a (the negative logarithm of the equilibrium constant of the proton transfer reaction in solution). The acidity of individual sites is difficult to assess for solids, compared with molecules. For mineral surfaces, the acidity is estimated by semi-empirical concepts, such as bond-order valence sums 5, and increasingly modelled with first-principles molecular dynamics simulations 6,7. At present, such predictions cannot be tested-experimental measures, such as the point of zero charge 8, integrate over the whole surface or, in some cases, individual crystal facets 9. Here we assess the acidity of individual hydroxyl groups on In 2 O 3 (111)-a model oxide with four different types of surface oxygen atom. We probe the strength of their hydrogen bonds with the tip of a non-contact atomic force microscope and find quantitative agreement with density functional theory calculations. By relating the results to known proton affinities of gas-phase molecules, we determine the proton affinity of the different surface sites of In 2 O 3 with atomic precision. Measurements on hydroxylated titanium dioxide and zirconium oxide extend our method to other oxides.

---

### Treprostinil [^8b79ec4c]. FDA (2025). Medium credibility.

11 DESCRIPTION

Treprostinil injection is a sterile solution of treprostinil, a prostacyclin mimetic, formulated for subcutaneous or intravenous administration. Treprostinil injection is supplied in 20-mL multi-dose vials in four strengths, containing 20 mg, 50 mg, 100 mg, or 200 mg (1 mg/mL, 2.5 mg/mL, 5 mg/mL or 10 mg/mL) of treprostinil. Each mL also contains 5.3 mg sodium chloride (except for the 10 mg/mL strength which contain 4.0 mg sodium chloride), 3 mg metacresol, 6.3 mg sodium citrate dihydrate, and water for injection. Sodium hydroxide and hydrochloric acid may be added to adjust pH between 6.0 and 7.2.

Treprostinil is chemically stable at room temperature and neutral pH.

Treprostinil is (1R,2R,3aS,9aS)-[[2,3,3a,4,9,9a-hexahydro-2-hydroxy-1-[(3S)-3-hydroxyoctyl]-1-Hbenz[f]inden-5-yl]oxy]acetic acid. Treprostinil has a molecular weight of 390.52 and a molecular formula of C23H34O5.

The structural formula of treprostinil is:

---

### Acidification suppresses the natural capacity of soil microbiome to fight pathogenic fusarium infections [^1e61f697]. Nature Communications (2023). High credibility.

Soil physicochemical characteristics

Soil physicochemical properties were determined according to handbook of soil analysis. Soil moisture content (MC) was determined by using the gravimetric method after a 16-h desiccation at 105 °C. Soil pH was measured with a glass electrode in a soil-to-water ratio of 1:2.5 (w/v). The content of soil organic carbon (SOC) was determined by titrating against 0.5 M ferrous iron solution after the air-dried soil had been digested with 0.8 M K 2 Cr 2 O 4 and concentrated H 2 SO 4 (v/v, 1:1) at 150 °C for 30 min by the potassium dichromate oxidation method. Dissolved organic carbon (DOC) was extracted by incubating fresh soil (equivalent to 10 g dry mass soil) with 50 mL of deionized water for 30 min, followed by shaking (end-over-end) at 280 rpm for 30 min at 25 °C. Then the samples were transferred to a centrifuge tube, and centrifuged at 450x g for 20 min at 4 °C. Subsequently, the supernatants were filtered through a 0.45-μm cellulose nitrate membrane before quantifying the DOC content by using a total organic carbon (TOC) analyzer (Multi N/C 3100, Germany). Total nitrogen (TN) was measured by the Kjeldahl digestion method. Briefly, the soil sample was heated and boiled with concentrated H 2 SO 4. The solution was then absorbed by 2% boric acid solution and titrated against 0.1 M sulfuric acid. Ammonium (NH 4 +) and nitrate (NO 3 −) were extracted by using 1 M potassium chloride, and then determined by the UV spectrophotometry method. Total phosphorus (TP) and available phosphorus (AP) were determined by using the molybdenum-blue method with an atomic absorption spectrophotometer, after the soil had been digested with concentrated HF-HClO 4 (v/v, 2:1) or extracted using 0.5 M sodium bicarbonate, respectively. Total potassium (TK) and available potassium (AK) were determined by the flame emission spectrometry method, after the soil had been digested in concentrated HF-HClO 4 (v/v, 2:1) or extracted with 1 M ammonium acetate, respectively. To examine the effect of soil buffering capacity on changes in soil acidity, soil cation exchange capacity (CEC) was also determined through the 1 M ammonium acetate method by using the air-dried soil samples. Soil texture mainly included the proportional contents of clay, silt and gravel in soil, which were determined by the sieve-pipette method. Overall, 180 soil samples were determined.

---

### Balanced salt solution (Bss) [^71e07c1d]. FDA (2024). Medium credibility.

DESCRIPTION

BSS™ Sterile Irrigating Solution is a sterile balanced salt solution, each mL containing sodium chloride (NaCl) 0.64%, potassium chloride (KCl) 0.075%, calcium chloride dihydrate (CaCl2•2H2O) 0.048%, magnesium chloride hexahydrate (MgCl2•6H2O) 0.03%, sodium acetate trihydrate (C2H3NaO2•3H2O) 0.39%, sodium citrate dihydrate (C6H5Na3O7•2H2O) 0.17%, sodium hydroxide and/or hydrochloric acid (to adjust pH), and water for injection. The pH is approximately 7.5. The osmolality is approximately 300 mOsm/Kg.

---

### Drinking water: the saltier the better? [^40415bd2]. Journal of the American Heart Association (2019). Medium credibility.

See Article Naser et al.

---

### Theranostic PSMA ligands with optimized backbones for intraoperative multimodal imaging and photodynamic therapy of prostate cancer [^73986a7b]. European Journal of Nuclear Medicine and Molecular Imaging (2022). Medium credibility.

Radiolabeling and RP-HPLC

Peptides were labeled under metal-free conditions with 111 InCl 3 (Curium) in 0.5 M 2-(N-morpholino)ethanesulfonic acid (MES) buffer (pH 5.5, twice volume of 111 InCl 3) or sodium acetate buffer (NaOAc in 0.04 M acetic acid solution, pH 4.5). Labeling was performed at 45 °C for 10 min. To chelate unincorporated 111 InCl 3, ethylenediamine-tetraacetic acid (EDTA, 50 mM) was added to a final concentration of 5 mM after the incubation.

Radiochemical yield (RCY) was determined by instant thin-layer chromatography (ITLC) using silica gel-coated paper (Agilent Technologies) and 0.1 M ammonium acetate containing 0.1 M EDTA, pH 5.5, as the mobile phase. In addition, RCY was determined using RP-HPLC on an Agilent 1200 system (Agilent Technologies) with an in-line radiodetector (Elysisa-Raytest). A reversed-phase C18 column (5 µm, 4.6 × 250 mm; HiChrom) was used at a flow rate of 1 ml/min. We used the following buffer system: buffer A, triethylammonium acetate (TEAA, 10 mM, pH 7); buffer B, 100% methanol; and a gradient of 97 to 0% buffer A (35 min). Peptides were purified by a Sep-Pak C18 light cartridge (Waters) and eluted from the cartridge with 50% ethanol in water.

---

### One-pot biocatalytic route from cycloalkanes to α, ω-dicarboxylic acids by designed Escherichia coli consortia [^5a0f3369]. Nature Communications (2020). High credibility.

Preparative procedure for α, ω-dicarboxylic acids 7a-d

The cycloalkanes 1a-d (final concentration was 100 mM; 78 µL 1a, 86.8 µL 1b, 98.8 µL 1c, or 109.8 µL 1d) were added into an 8-mL suspension of E. coli consortium 1_2_3 (final CDW was 12 g L −1, ratio of modular cells 1, 2 and 3 was 2:1:2) in potassium phosphate buffer (0.2 M, pH 8.0) containing 0.05 g mL −1 glucose. Reactions were at 25 °C, 200 rpm in 250-mL shaking flasks for 24 h. For 1d, to ensure complete conversion of intermediate products 5d to corresponding α, ω-dicarboxylic acids 7d, a 2-mL suspension of E. coli cell module 3 (32 g CDW L −1) in potassium phosphate buffer (0.2 M, pH 8.0) was added after 24 h. During the reaction, the pH was maintained around 8.0 by adding 10 M NaOH. After reaction, mixtures were extracted three times with 30 mL EtOAc, and the organic phase was evaporated for substrate recovery. The water phase was acidified to below pH 2.0 with 4 M HCl, followed by three extractions with 50 mL EtOAc. The organic phase was dried over anhydrous Na 2 SO 4. The solvent was removed using a rotary evaporator, and white solids were obtained at 13–45% isolated yields with purity > 98% (glutaric acid 7a: 13.4 mg, yield = 13%; adipic acid 7b: 38.5 mg, yield = 33%; pimelic acid 7c: 57.8 mg, yield = 45%; octanedioic acid 7d: 18.8 mg, yield = 13%). Isolated products were subjected to GC-MS and NMR analysis (see chromatograms in Supplementary Figs. 18–21): 7a: 1 H NMR (400 MHz, CD 3 OD): δ 2.35 (t, J = 7.4 Hz, 4H), 1.86 (p, J = 7.4 Hz, 2H); 7b: 1 H NMR (400 MHz, CD 3 OD): δ 2.31 (ddt, J = 7.5, 5.7, 2.1 Hz, 4H), 1.68–1.59 (m, 4H); 7c: 1 H NMR (400 MHz, CD 3 OD): δ 2.29 (t, J = 7.4 Hz, 4H), 1.62 (p, J = 7.5 Hz, 4H), 1.44–1.31 (m, 2H); and 7d: 1 H NMR (400 MHz, CD 3 OD): δ 2.28 (t, J = 7.4 Hz, 4H), 1.72–1.52 (m, 4H), 1.36 (m, 4H).

---

### Structure-based discovery of dual pathway inhibitors for SARS-CoV-2 entry [^378fba3e]. Nature Communications (2023). High credibility.

Crystallization, data collection and structure determination

The crystallization was performed with purified TMPRSS2 (8 mg/mL) incubated with camostat, nafamostat, UK-371804 or 212−148 at a molar ration of 3:1 for 2 h on ice. Crystals for TMPRSS2 in complex with various inhibitors were grown by hanging drop vapor diffusion at 20 °C, with the same crystallization reservoir solution containing 0.1 M acetic acid/sodium acetate, pH 5.0, and 16% w/v PEG 8000.

The purified and activated CTSL at a concentration of 8 mg/mL was incubated with E64d or K777 at a molar ration of 5:1 for 2 h at room temperature. Crystals were obtained by sitting drop vapor diffusion at 16 °C, with the reservoir solution consisting of 100 mM citric acid, pH 3.5 and 3 M sodium chloride for CTSL-E64d complex; the reservoir solution consisting of 9% (v/v) 2-propanol, 90 mM sodium cacodylate/ hydrochloric acid pH 6.5, 180 mM zinc acetate, and 0.5%w/v n-dodecyl-N, N-dimethylamine-N-oxide (LDAO, DDAO) for the CTSL-K777 complex.

The purified and activated CTSB at a concentration of 5.5 mg/mL was incubated with E64d, K777 or 212–148 at a molar ration of 10:1 overnight at 4 °C. Crystals were obtained by sitting drop vapor diffusion at 16 °C, with the reservoir solution consisting of 0.2 M ammonium acetate, 0.1 M sodium acetate trihydrate (pH 4.6) and 30% w/v polyethylene glycol 4,000 for CTSB-E64d complex; the reservoir solution consisting of 17.1% v/v polyethylene glycol 600, 50 mM MES (pH 5.6) and 8.6% w/v polyethylene glycol 4,000 for CTSB-K777 complex; the reservoir solution consisting of 0.2 M magnesium chloride hexahydrate, 0.1 M sodium acetate (pH 5.2) and 28% w/v PEG 3350 for CTSB- 212–148 complex. All the crystals above were cryo-protected by reservoir solutions supplemented with 20% glycerol and flash frozen in liquid nitrogen for further data collection.

---

### Opposite development of short-and long-range anterior cingulate pathways in autism [^8155eb3a]. Acta Neuropathologica (2018). Low credibility.

We stained other series of sections using the Gallyas silver technique to label intracortical and white matter myelin. Briefly, sections were rinsed in distilled water and then incubated in a solution of pyridine (2/3; P368-1 Fischer Scientific) and glacial acetic acid (1/3; ARK2183 Sigma-Aldrich) for 30 min at room temperature. We then washed sections in distilled water before incubation in the impregnation solution for a minimum of 30 min at room temperature in the dark. We used 0.1 g of ammonium nitrate (A7455 Sigma-Aldrich) and 0.1 g of silver nitrate (S181-25 Fischer Scientific) per 100 mL of distilled water to make the impregnation solution; the pH of the solution was adjusted with 0.1 M sodium hydroxide (CAS 1: 1310-73-2 Fischer Scientific) to obtain pH 7.5. Sections were then rinsed in 0.5% acetic acid (A6283 Sigma-Aldrich) and incubated in the developing solution under microscopic control until the proper level of stain was achieved. For the developing solution we first prepared three solutions, each dissolved in 500 mL of distilled water: A, 25 g sodium carbonate (S-263 Fischer Scientific); B, 1 g ammonium nitrate (A7455 Sigma-Aldrich), 1 g silver nitrate (S181-25 Fischer Scientific) and 5 g silicotungstic acid (383341 Sigma-Aldrich); C, 75 mL of solution B and 1.75 mL of 4% paraformaldehyde (O4042 Fischer Scientific). To make the incubation solution, we mixed 150 mL of solution A, 75 mL of solution B and 75 mL of solution C in that order. After developing, the sections were washed in 1% acetic acid (A6283 Sigma-Aldrich) and then in distilled water followed by incubation in 5% sodium thiosulfate (S-1648 Sigma-Aldrich) to stabilize the reaction. Sections were finally washed in distilled water and mounted on gelatin-coated glass slides from PB 0.1 M, pH 7.4.

---

### In vitro thermal profile suitability assessment of acids and bases for thermochemical ablation: underlying principles [^36f838a4]. Journal of Vascular and Interventional Radiology (2010). Low credibility.

Purpose

To measure and compare temperature changes in a recently developed gel phantom for thermochemical ablation as a function of reagent strength and concentration with several acids and bases.

Materials and Methods

Aliquots (0.5–1 mL) of hydrochloric acid or acetic acid and sodium hydroxide or aqueous ammonia were injected for 5 seconds into a hydrophobic gel phantom. Stepwise increments in concentration were used to survey the temperature changes caused by these reactions. Injections were performed in triplicate, measured with a thermocouple probe, and plotted as functions of concentration and time.

Results

Maximum temperatures were reached almost immediately in all cases, reaching 75 degrees C-110 degrees C at the higher concentrations. The highest temperatures were seen with hydrochloric acid and either base. More concentrated solutions of sodium hydroxide tended to mix incompletely, such that experiments at 9 M and higher were difficult to perform consistently.

Conclusions

Higher concentrations for any reagent resulted in higher temperatures. Stronger acid and base combinations resulted in higher temperatures versus weak acid and base combinations at the same concentration. Maximum temperatures obtained are in a range known to cause tissue coagulation, and all combinations tested therefore appeared suitable for further investigation in thermochemical ablation. Because of the loss of the reaction chamber shape at higher concentrations of stronger agents, the phantom does not allow complete characterization under these circumstances. Adequate mixing of reagents to maximize heating potential and avoid systemic exposure to unreacted acid and base must be addressed if the method is to be safely employed in tissues. In addition, understanding factors that control lesion shape in a more realistic tissue model will be critical.

---

### Total enzymatic synthesis of cis-α-irone from a simple carbon source [^8b583ec3]. Nature Communications (2022). High credibility.

Biotransformation of glucose/glycerol into cis-α-irone

The four plasmids were transformed into E. coli BL21 (DE3), ∆ aroA, ∆ aroB, ∆ aroC, ∆ serC or E. coli BL21 (DE3), ∆ aroA, ∆ aroB, ∆ aroC, ∆ serC, ∆ metJ strains and plated on agar plates containing LB media (10 g tryptone, 5 g yeast extract, and 10 g NaCl) supplemented with the appropriate antibiotics (100 mg l −1 ampicillin, 34 mg l −1 chloramphenicol, 50 mg l −1 kanamycin and 100 mg l −1 spectinomycin). One colony was randomly picked and inoculated into LB media with antibiotics. 1% of overnight culture was inoculated into 1 mL fresh autoinducing chemically defined media. The chemical media contains a carbon source solution (0.5 g l −1 glucose, 10 g l −1 glycerol), inducer (30 mM lactose), base media (2 g l −1 ammonium sulphate, 4.2 g l −1 KH 2 PO 4, 11.24 g l −1 K 2 HPO 4, 1.7 g l −1 citric acid, 0.5 g l −1 MgSO 4), and 10 mL l −1 trace element solution. The trace element solution (100×) contained 0.25 g l −1 CoCl 2 ·6H 2 O, 1.5 g l −1 MnSO 4 ·4H 2 O, 0.15 g l −1 CuSO 4 ·2H 2 O, 0.3 g l −1 H 3 BO 3, 0.25 g l −1 Na 2 MoO 4 ·2H 2 O, 0.8 g l −1 Zn(CH 3 COO) 2, 5 g l −1 Fe(III) citrate, and 0.84 g l −1 ethylenediaminetetra-acetic acid (EDTA) at pH 8.0. The culture was grown at 28 o C for 3 days and the products were extracted with 1 mL hexane for GCMS analysis. An optimized fed-batch process for α-ionone was used for the bioreactor test. Briefly, overnight culture was inoculated into 2 l chemical media comprising the base media and 5 g l −1 glucose, at 37 °C and 30% DO. pH was controlled at 7 with base solution (14% ammonia and 0.5 M NaOH). Feed media (500 g l −1 glucose and 5 g l −1 MgSO 4) was added into bioreactor once OD 600 reached 5, at a rate of 14.3–51.5 mL h −1 glucose for 4–5 h until OD 600 reached ~30–40. Subsequently, 0.1 mM IPTG was added to induce the production, feeding rate was kept at a constant rate of 20 mL h −1 glucose, and the temperature was reduced to 30 °C. DO was adjusted to 2% or 10%. Feeding was stopped at 113 h when the 2 l feeding media was depleted, but the culture was further incubated for 24 h. The exhaust was connected to 25 mL of sunflower oil to capture the evaporated products.

---

### The potential role of systemic buffers in reducing intratumoral extracellular pH and acid-mediated invasion [^38923a64]. Cancer Research (2009). Low credibility.

A number of studies have shown that the extracellular pH (pHe) in cancers is typically lower than that in normal tissue and that an acidic pHe promotes invasive tumor growth in primary and metastatic cancers. Here, we investigate the hypothesis that increased systemic concentrations of pH buffers reduce intratumoral and peritumoral acidosis and, as a result, inhibit malignant growth. Computer simulations are used to quantify the ability of systemic pH buffers to increase the acidic pHe of tumors in vivo and investigate the chemical specifications of an optimal buffer for such purpose. We show that increased serum concentrations of the sodium bicarbonate (NaHCO(3)) can be achieved by ingesting amounts that have been used in published clinical trials. Furthermore, we find that consequent reduction of tumor acid concentrations significantly reduces tumor growth and invasion without altering the pH of blood or normal tissues. The simulations also show that the critical parameter governing buffer effectiveness is its pK(a). This indicates that NaHCO(3), with a pK(a) of 6.1, is not an ideal intratumoral buffer and that greater intratumoral pHe changes could be obtained using a buffer with a pK(a) of approximately 7. The simulations support the hypothesis that systemic pH buffers can be used to increase the tumor pHe and inhibit tumor invasion.

---

### Thermodynamic principle to enhance enzymatic activity using the substrate affinity [^bd648a6b]. Nature Communications (2023). High credibility.

Fig. 5
Volcano plots showing how the activity is expected to change with respect to the Michaelis-Menten constant (K m).

As the substrate concentration was increased from 10–1 M (black) to 10 2 M (red), the volcano plot shifted to the upper right. The apex is located at, as indicated by the vertical dashed lines of the corresponding color. Changing the values of, ordoes not influence the conclusion that the activity is maximized when, as shown in Supplementary Note 3.

Robustness of the theoretical model

To confirm the robustness of our finding, we have performed numerical simulations by loosening each of the theoretical requirements. Deviation from the Michaelis-Menten mechanism (Fig. 1) are shown in Fig. 6a–c, and deviation ofvalues from 0.5 are shown in Fig. 6d. The possibility of reverse reactions (P → S) or inhibition (E + I → EI or ES + I → ESI) are common deviations from Michaelis-Menten kinetics. The net rate in the presence of a reverse reaction when the substrate and product are in equal concentrations (µM) is shown in Fig. 6a. In terms of maximizing the activity in the forward direction (S → P), the physically meaningful region is, where the net reaction proceeds in the forward direction. Under this condition, the dashed line corresponding toand the solid line corresponding to the true maximum activity (forward minus reverse reaction rates) overlap almost completely, indicating thatis a good guideline to enhance activity even in the presence of reverse reactions (P → S).

Fig. 6
Influence of mechanistic deviations on the optimum K m.

a Reverse reactions, b Competitive inhibition, c Uncompetitive inhibition, and d BEP coefficient. The dashed line corresponds to, withµM. The true optimumfor each mechanism is shown as a solid line along with its analytical equation (refer to Supplementary Note 5 for the derivations). In a, the product concentration was set to 10 µM. The top half of a was colored at an arbitrarily low activity because the reverse reaction is more favorable in this region. The large discrepancy between the dashed and solid lines atis physically irrelevant, because the activity of the forward reaction cannot be discussed when the net reaction proceeds in the reverse direction. In b and c, the degree of inhibitionwas set to 10. In d, the BEP coefficients were set to. No analytical solution was obtained for d.

---

### Bicarbonate-mediated proton transfer requires cations [^618fd8da]. Nature Communications (2024). High credibility.

Near-neutral HCO 3 - aqueous solution plays an essential role in respiratory, mineralization and catalysis, yet the interconversion between hydrated CO 2, HCO 3 - and CO 3 2- and the associated proton transfer under such proton-deficient conditions remain uncovered. Here we reveal that cation enables HCO 3 - to self-dissociate into OH - and CO 2 through a pH-independent process, where CO 2 hydration and subsequent proton transfer in acid-base reactions lead to the overall exchange of oxygen isotopes between HCO 3 - and H 2 O tracked by oxygen isotope-labeled Raman spectroscopy. Isolating HCO 3 - from cations with crown ether impedes HCO 3 - dissociation and the following reactions. Further molecular dynamics simulations demonstrate that the interplay between HCO 3 - and hydrated cations drives HCO 3 - dissociation. This study suggests a natural proton channel upon coupling HCO 3 - with cations.

---

### The negative emission potential of alkaline materials [^f5bd5512]. Nature Communications (2019). High credibility.

7 billion tonnes of alkaline materials are produced globally each year as a product or by-product of industrial activity. The aqueous dissolution of these materials creates high pH solutions that dissolves CO 2 to store carbon in the form of solid carbonate minerals or dissolved bicarbonate ions. Here we show that these materials have a carbon dioxide storage potential of 2.9–8.5 billion tonnes per year by 2100, and may contribute a substantial proportion of the negative emissions required to limit global temperature change to < 2°C.

---

### Treprostinil (Remodulin) [^fe37ab55]. FDA (2025). Medium credibility.

11 DESCRIPTION

Remodulin (treprostinil) Injection is a sterile solution of treprostinil, a prostacyclin mimetic, formulated for subcutaneous or intravenous administration. Remodulin is supplied in 20-mL multidose vials in eight strengths, containing 2 mg (0.1 mg/mL), 4 mg (0.2 mg/mL), 8 mg (0.4 mg/mL), 20 mg (1 mg/mL), 50 mg (2.5 mg/mL), 100 mg (5 mg/mL), 200 mg (10 mg/mL), or 400 mg (20 mg/mL) of treprostinil. Each mL also contains 5.3 mg sodium chloride (except for the 10 mg/mL and 20 mg/mL strengths, which contain 4.0 mg sodium chloride), 3 mg metacresol, 6.3 mg sodium citrate dihydrate, and water for injection. Sodium hydroxide and hydrochloric acid may be added to adjust pH between 6.0 and 7.2.

Treprostinil is chemically stable at room temperature and neutral pH.

Treprostinil is (1 R,2 R,3a S,9a S)-[[2,3,3a,4,9,9a-hexahydro-2-hydroxy-1-[(3 S)-3-hydroxyoctyl]-1 H -benz[f]inden-5-yl]oxy]acetic acid. Treprostinil has a molecular weight of 390.52 and a molecular formula of C23H34O5.

The structural formula of treprostinil is:

Sterile Diluent for Remodulin is a high-pH (pH~10.4) glycine diluent supplied in a 50-mL vial containing 50 mL of Sterile Diluent for Remodulin. Each vial contains 94 mg glycine, 73.3 mg sodium chloride, sodium hydroxide (to adjust pH), and water for injection.

---

### Single particle automated raman trapping analysis [^d50df42d]. Nature Communications (2018). Medium credibility.

Dynamic click reactions on polystyrene particles

Carboxyl functionalised 0.2 µm PS particles (Polybead carboxylate 0.20 µm, Polysciences Inc.) were functionalised with propargyl amine using EDC-NHS coupling. Solutions were made of 20 mg mL −1 1-ethyl-3-(3-dimethylaminopropyl)carbodiimide and 20 mg mL −1 n-hydroxysuccinimide in PBS and 40 µl of each was added to 200 µl of PS particles (2.6% solids) and 800 µl of PBS. The solution was shaken on a thermomixer at room temperature and 20 µl of neat propargylamine was added after 30 min. The reaction was allowed to proceed under continuous shaking overnight. The synthesis solution was diluted 10 times and purified. Purification was performed by centrifugation for 10 min at 14,000 rcf, after which the pellet was redispersed in PBS. Redispersion was aided by vortexing for 30 s and ultrasonication for 1 min. After purification, DLS traces were obtained to verify the absence of aggregation, prior to SPARTA. Solutions were made of 100 mM copper sulphate, 100 mM sodium ascorbate and 0.5 M potassium bicarbonate in PBS. Azido acetate was made by addition of a 1 M solution of sodium hydroxide in a molar equivalent to 2-azidoacetic acid (Sigma-Aldrich, UK). The population click reaction was carried out by formation of the triazole by addition of 2.88 µl 100 mM sodium ascorbate, 1.80 µl 100 mM copper sulphate and 0.5 μl neat azido acetic acid to 200 μl of alkyne functionalised PS particles, diluted 100 times in PBS. Droplets of a 0.5 M solution of KHCO 3 were applied to adjust the pH to 7. The single particle hold click reaction was performed with addition of 7.46 μl azido acetate (equalling 0.5 μl neat azido acetic acid), with no further pH adjustment necessary.

---

### A novel narnavirus is widespread in Saccharomyces cerevisiae and impacts multiple host phenotypes [^15d57ea0]. G3 (2023). Medium credibility.

Virus presence/absence determination by PCR and gel electrophoresis

Total nucleic acids were extracted using a slight modification of the phenol-mediated method described by, as follows. Cells of 5-mL overnight YPD cultures were collected by centrifugation and washed once with 50 mM Na 2 EDTA (pH 7.5). Cell pellets were then resuspended in 1 mL of 50 mM Tris-H 2 SO 4 (pH 9.3)/1% 2-mercaptoethanol solution and incubated for 15 min at room temperature. Cells were subsequently collected by centrifugation and resuspended in 1 mL of 0.1 M NaCl/10 mM Tris–HCl (pH 7.5)/10 mM Na 2 EDTA/0.2% sodium dodecyl sulfate solution. 0.7 mL of phenol (pH 8.0) was added, and samples were incubated on a shaking platform for 1 h at room temperature, after which 0.7 mL of the aqueous phase was recovered by 5-min centrifugation. Nucleic acids were precipitated by the addition of 70 µL of 3 M potassium acetate and 0.7 mL of ice-cold isopropanol, followed by incubation for 5 min at room temperature and centrifugation at 14,000 rpm for 10 min. The precipitated nucleic acids were washed with 70% ethanol, dried using a SpeedVac (Eppendorf), dissolved in 70–100 µL of water, and stored at −80°.

---

### Highly regio-and enantioselective multiple oxy-and amino-functionalizations of alkenes by modular cascade biocatalysis [^6f537e9e]. Nature Communications (2016). Medium credibility.

Biotransformation of 1a or 1d to prepare (S)- 8a or (S)- 8d

Overall, 100 mL suspension of E. coli (A-M1_R-M2_C-M4) cells (20 g cdw l –1) in KP buffer (200 mM, pH 8.0) containing glucose (0.5%, w/v) and NH 3 /NH 4 Cl (100 mM, NH 3 :NH 4 Cl = 1:10) were mixed with 20 mL n -hexadecane containing 1a (5 mmol, 521 mg) or 1d (2.5 mmol, 305 mg). The reaction mixture was shaken at 300 r.p.m. and 30 °C, and 100 μl aliquots of the aqueous phase were taken out at different time points for reversed phase HPLC analysis to follow the reaction. At 12 h, additional glucose (1%, w/v) and NH 3 /NH 4 Cl (200 mM) were added. After 24 h, the reaction mixture was subjected to centrifugation (4,000 g, 15 min) to remove the cells and organic phase. The collected aqueous phase was filtered to further remove solid impurities, followed by washing with ethyl acetate (2 × 25 ml) to remove trace n -hexadecane and other organic impurities. After neutralization to pH = 7 with NaOH (10 M), the aqueous solution was concentrated to about 15 mL by evaporation to precipitate the amino acid. The solid was collected by filtration, washed with cold water and EtOH and dried overnight under vacuum. (S)-2-Amino-2-phenylacetic acid 8a: white solid; 528 mg; yield: 70%; e.e.: 99%; D 20: +148° (c 1.0, 1 M HCl) {literature[α] D 23: +150° (c 1.0, 1 M HCl), 99% e.e.}. 1 H NMR (400 MHz, D 2 O containing 2% H 2 SO 4): δ = 7.36–7.30 (m, 5H), 5.04 (s, 1H) p.p.m.; 13 C NMR (100 MHz, D 2 O containing 2% H 2 SO 4): δ = 170.7, 131.3, 130.4, 129.7, 129.7, 128.1, 128.1, 56.5 p.p.m. (Supplementary Fig. 17). (S)-2-Amino-2-(4-fluorophenyl)acetic acid 8d: white solid; 250 mg; yield: 59%; e.e.: 99%; D 20: +138° (c 1.0, 1M HCl) {literature[α] D 20: +141° (c 1.0, 1M HCl), 99% e.e.}. 1 H NMR (400 MHz, D 2 O containing 2% H 2 SO 4): δ = 7.34–7.31 (m, 2H), 7.08–7.03 (m, 2H), 5.04 (s, 1H) p.p.m.; 13 C NMR (100 MHz, D 2 O containing 2% H 2 SO 4): δ = 170.6, 164.6 & 162.2 (C-F), 130.4, 130.3, 127.4, 127.4, 116.7, 116.4, 55.8 p.p.m. (Supplementary Fig. 18).

---

### Ligand design strategies to increase stability of gadolinium-based magnetic resonance imaging contrast agents [^428b1b68]. Nature Communications (2019). High credibility.

The thermodynamic stability constant can be calculated by the equilibrium concentration of each component with the assumption that the ligand is fully deprotonated. There are several methods for the determination of log K. These include pH-potentiometry, spectrophotometry and proton relaxometry, which are respectively conducted by recording changes of pH value, absorbance/emission intensity or proton relaxivity of a solution containing equimolar amounts of metal ion and ligand as a function of added acid or base. Complexation of lanthanide(III) ions, including Gd 3+, especially with macrocyclic ligands, is generally slow. Thus, the "out-of-cell" method is frequently used rather than direct titrations, i.e. a series of samples to span the pH range are prepared and allowed to equilibrate before measurements are made. For complexes with a high log K value, the competition method can be used. This requires a competing reference ligand or metal ion. The hard acid Gd 3+ favours basic donor atoms such as nitrogen and charged oxygen, which can be exploited to increase the log K of Gd 3+ complexes. However, log K formally describes the reaction between a metal ion and a fully deprotonated ligand, with the latter only existing in solution at high pH values. At lower pH ranges, protons compete with Gd 3+ to bind with the ligand. This additional consideration is taken into account by the conditional thermodynamic stability constant: log K' (also called log K' GdL, log K cond and log K eff), a value measured at pH 7.4 using 1:1 ligand-to-metal ratio. Log K ' can be calculated from log K and ligand protonation constants. Less commonly, pGd (pGd = −log [Gd 3+] at pH 7.4, freqcuently at a ligand to metal concentration ratio of 10:1 although a range have been used in the literature) has been suggested as a measure of complex conditional thermodynamic stability. Log K ' is, therefore, more useful than log K with respect to thermodynamic stability under certain conditions, i.e. physiological pH 7.4. Increased ligand basicity results in stronger proton binding and can result in a larger difference between log K and log K'.

---

### Redefined ion association constants have consequences for calcium phosphate nucleation and biomineralization [^ad900b67]. Nature Communications (2024). High credibility.

With the renewed interest in the early stages of precipitation mechanisms, understanding the ion interactions before macroscopic solids are formed has become especially important from a non-classical point of view –. The binding between different ions in solution, however, has been studied since the early days in chemistry, since these equilibria determine solution composition and characteristics, as evident from the extensive compilations of ion association constants published in the last century. Taking a broad view, the most fundamental parameter of aqueous chemistry, pH, is also essentially a description of ion binding. For the CaPs, the different ion associates have been shown to be vital in understanding the solubility of solid phases. Current research investigates the role of these associated species in nucleation mechanisms.

Recent developments in potentiometric and cryo-TEM methods have enabled investigations into nucleation; however, simulations have remained the only tool capable of investigating the atomistic details of the initial stages of phase separation. Combining these methods, Habraken et al. have proposed pre-nucleation [Ca(HPO 4) 3] 4− complexes that aggregate to form polymeric strands early in the nucleation mechanism. According to their model, nucleation would proceed via the uptake of additional calcium ions forming species with a base formula of [Ca 2 (HPO 4) 3] 2−. These results, among others, however, were challenged by Garcia et al. who predicted that the ion pair and smaller aggregation units would be more stable in solution, casting doubt on the existence and relevance of the proposed [Ca(HPO 4) 3] 4− pre-nucleation complex. The theoretical model used, specifically a force field description of the energy and forces, was developed by the same group and extensively validated against experimental and ab initio results. The ion association constants used to benchmark the predictions of this model can be traced to Chughtai et al. in 1968 (see Supplementary Table 1 for a full list of literature values). This set of ion pairing constants has become the standard for any mathematical description of the CaP system, as this is nearly the only complete set available in the literature. Obviously, it is vital that the experimental values for association constants used as either input to chemical speciation calculations, or to validate simulation models, are sound; otherwise, the calculated speciation will be erroneous or the need for more accurate simulation models may go undetected.

---

### Guideline for disinfection and sterilization in healthcare facilities, 2008 [^ed712649]. CDC (2008). Medium credibility.

Hydrogen peroxide — antimicrobial efficacy and chemical sterilant formulations are detailed across concentrations and organisms: a 3% hydrogen peroxide solution inactivated rhinovirus in 6–8 minutes, with times increasing to 18–20 minutes at 1.5% and 50–60 minutes at 0.75%; concentrations from 6% to 25% show promise as chemical sterilants, and the marketed sterilant contains 7.5% hydrogen peroxide and 0.85% phosphoric acid; at 7.5% it inactivated > 10^5 multidrug-resistant M. tuberculosis after a 10-minute exposure; thirty minutes were required for > 99.9% inactivation of poliovirus and HAV, whereas 3% and 6% hydrogen peroxide failed to inactivate HAV in 1 minute; in endoscope disinfection, 7.5% hydrogen peroxide at 10 minutes versus 2% alkaline glutaraldehyde at 20 minutes showed no significant difference in germicidal activity, though in one study 6% hydrogen peroxide (unused product was 7.5%) was more effective than 2% glutaraldehyde; a new, rapid-acting 13.4% hydrogen peroxide formulation (not yet FDA-cleared) is reported to sterilize in 30 minutes and provide high-level disinfection in 5 minutes, and synergistic sporicidal effects were observed when spores were exposed to hydrogen peroxide (5.9% — 23.6%) plus peracetic acid.

---

### Pitfalls in the quantitative imaging of glutathione in living cells [^4ae30b9e]. Nature Communications (2018). Medium credibility.

HPLC determination of Cys and GSH with monobromobimane (mBr) derivatization

The cells were sonicated three times for 2 s in 100 µL of 0.1 M potassium phosphate buffer (pH 7.2). After sonication, 50 μL of 12% sulfosalicylic acid were added, and the Cys and GSH content in the acid-soluble fraction was determined (free Cys and free GSH). To measure cystine and oxidized glutathione (GSSG), cells were sonicated three times for 2 s in 0.1 mL of 0.1 M potassium phosphate buffer (pH 7.2) containing 10 mM N -ethylmaleimide. Cys and GSH levels were calculated by subtracting cystine and GSSG concentrations from free Cys and free GSH values. The derivatization procedure was performed as follows: 30 µL of 4 mol/L NaBH 4, 20 µL of 2 mmol/L EDTA/DTT, 10 µL of 1-octanol and 20 µL of 1.8 mol/L HCl were placed in the derivatization vial containing 30 µL of sample. After incubation for 3 min, 100 µL of 1.5 mol/L N -ethylmorpholine buffer, pH 8.0, 400 μL of distilled water, and 20 µL of 25 mmol/L bromobimane were added. After additional 3-min incubation, 40 μL of acetic acid was added, and 20 μL of the reaction mixture was injected into a 150 × 4.6 mm Hypersil™ ODS column (Thermo Fisher Scientific, Waltham, MA, USA) equilibrated with 30 mmol/L ammonium nitrate and 40 mmol/L ammonium formate buffer, pH 3.6 (buffer A). The thiols were eluted from the column with a 6-min gradient of acetonitrile (buffer B) (0–4 min, 0–30% buffer B; 4–5 min, 30–100% buffer B; 5–6 min, 100% buffer B) at a flow rate of 1.5 mL/min at ambient temperature. The HPLC was an Agilent 1290 (Agilent Technologies, Santa Clara, CA, USA), equipped with a fluorescence detector operating at excitation wavelengths of 390 nm, and emission wavelength of 478 nm.

Data availability

The data that support the findings of this study are available from the corresponding author upon reasonable request.

---

### The treatment of alkaline burns of the skin by neutralization [^b416bb1c]. Plastic and Reconstructive Surgery (2003). Low credibility.

Literature reports dating as far back as 1927 have lured clinicians into the belief that alkaline skin burns are best treated by water dilution and that neutralization attempts should be avoided. Although this belief has never been substantiated, neutralization of an alkaline burn of the skin with acid was thought to increase tissue damage secondary to the exothermic nature of acid-base reactions. The authors proposed that topical treatment of alkaline burns with a weak acid such as 5% acetic acid (i.e., household vinegar) would result in rapid tissue neutralization and reduction of injury in comparison to water irrigation alone. In a rat skin burn model, animals were exposed to an alkaline injury when filter paper (2 cm in diameter) saturated with 2N sodium hydroxide was placed over the volar aspect of the animal for a period of 1 minute. Treatment was initiated 1 minute after injury and included either neutralization with a 5% acetic acid solution (n = 8) or irrigation (n = 8) with water. Skin temperature and pH were monitored using subdermal needle probes until the pH of the skin returned to physiologic values. Punch-biopsy specimens were obtained from the wound edges 24 hours after injury to assess burn depth and leukocyte infiltration, and biopsies were repeated 10 days later to assess wound healing. The authors proposed that neutralization of an alkaline substance with household vinegar (i.e., 5% acetic acid solution) would result in rapid neutralization and thus reduce extent of tissue injury. Animals treated with acetic acid demonstrated a more rapid return to physiologic pH (14.69 ± 4.06 minutes versus 31.62 ± 2.83 minutes; p < 0.001), increased depth of dermal retention (0.412 ± 0.136 mm versus 0.214 ± 0.044 mm; p = 0.015), decreased leukocyte infiltrate (31.0 ± 5.1 cells/high-power field versus 51.8 ± 6.8 cells/high-power field; p < 0.001), and improved epithelial regeneration (4.0 ± 0.6 cell layers versus 1.7 ± 0.5 cell layers; p < 0.001) when compared with animals treated with water irrigation. No difference was detected in peak pH (10.35 ± 0.28 pH versus 10.36 ± 0.25 pH; p = 0.47) nor in rise of skin temperature (maximum temperature, 32.8 degrees C versus 32.9 degrees C; p = 0.33) between acetic acid-neutralized and water-irrigated burn wounds. The observed benefits of treating alkaline burns with 5% acetic acid in the rat model are significant and require clinical testing.

---

### Electrochemical oxo-functionalization of cyclic alkanes and alkenes using nitrate and oxygen [^2822cf9a]. Nature Communications (2023). High credibility.

Workup protocol for the co-electrolysis

After electrolysis, 10 mg of 1,3,5-trimethoxybenze as an internal standard was added to the reaction solution. Three drops were eluted with ethyl acetate through ~330 mg silica 60 M and filled into a vial for quantitative GC-FID analysis. Before the analysis, an external GC calibration of the ketone was performed (see Supplementary Fig. 6). The dicarboxylic acid has been isolated regarding the following workup: The solvent is recovered by distillation under reduced pressure. The low-boiling starting material leftover can be recovered by extraction with n-pentane out of the nitrile distillate and monitored via thin-layer chromatography (TLC). The distillation residue is dissolved in ethyl acetate (10 mL) and extracted with HCl aq. (0.1 mol L −1, 10 mL), whereby the supporting electrolyte remains in the aqueous layer. The organic fraction is reduced in vacuo. For purification, the residue is washed with NaOH aq. (1 mol L −1, 10 mL) and extracted with diethyl ether or n-pentane (10 mL), monitored via TLC. After dropwise acidification of the aqueous layer with conc. HCl aq. to pH 1 and extraction with ethyl acetate (2 × 10 mL), the combined organic layers are dried over MgSO 4 and reduced in vacuo to yield the dicarboxylic acid product.

Workup procedure for carboxylic acids from fatty acids

After electrolysis, 50.5 μL propionic acid was added to the reaction solution as an internal standard. Three drops were eluted with ethyl acetate through ~330 mg silica 60 M and filled into a vial for quantitative GC-FID analysis. Prior to the analysis, an external calibration of the mono-carboxylic acid was performed (see Supplementary Fig. 7). The dicarboxylic acid was isolated via column chromatography using silica 60 M (cyclohexane/ethyl acetate = 1:1 with 1 vol% glacial acetic acid).

---

### Control of intracellular pH and bicarbonate by COdiffusion into human sperm [^0550402c]. Nature Communications (2023). High credibility.

Digestion of proteins from human spermatozoa cells for MS analysis

Proteins from 1–5 × 10 6 sperm were extracted and subjected to in-solution digestion as follows. The sample was diluted two-fold by addition of an equal volume of human sperm lysis buffer (8% (w/v) sodium dodecyl sulfate (SDS), 10 mM ethylenediaminetetraacetic acid (EDTA), 10 mM ethylene glycol-bis(2-aminoethylether)-N, N, N', N'-tetraacetic acid (EGTA), 20 mM dithiothreitol (DTT), and 100 mM NH 4 HCO 3), and boiled for 10 min at 99 °C. The sample was sonicated in a pre-warmed (15 °C) sonication device (Bioruptor® Plus, Diagenode, Seraing, Belgium) for 10 min with alternating cycles of 30 s ON, followed by 30 s OFF. After sonication, 50 mM NH 4 HCO 3 buffer (pH 8) was added resulting in a final SDS concentration of 1%, and the sample was incubated with 500 units of universal nuclease (Pierce, 250 U/µl) in the presence of 1 mM MgCl 2 for 30 min at 37 °C. Proteins were reduced with 10 mM DTT for 30 min at 60 °C and then alkylated with 40 mM iodoacetamide (IAA) for 30 min at 37 °C, followed by another incubation step with 20 mM DTT for 5 min at 37 °C. SP3 beads were prepared as described and 3 mg of SP3 beads were added to the reduced and alkylated proteins, followed by addition of 100% ethanol (LiChrom grade) to a final concentration of 50% (v/v) ethanol and incubation for 5 min at 24 °C with shaking at 1000 rpm in a ThermoMixer® C (Eppendorf, Hamburg, Germany). SP3 beads were washed three times with 80% (v/v) ethanol using an in-house made magnetic rack. After the final washing step, SP3 beads were resuspended in 50 mM NH 4 HCO 3 buffer. Rapigest (Waters, Eschborn, Germany) was added to a final concentration of 0.1% (w/v) and trypsin (sequencing grade, Promega, Walldorf, Germany) was added in 1/20 (w/w) trypsin to protein ratio for protein digestion overnight at 37 °C. Digestion was stopped by acidifying the sample with 100% formic acid (FA) so that the pH of the sample was between 2 and 3 and incubated for 30 min at 37 °C, followed by centrifugation for 10 min at 4 °C and 17,000 xg. Using a magnetic rack, the peptide containing supernatant was transferred to another reaction tube and 80% (v/v) acetonitrile (ACN)/0.1% (v/v) formic acid (FA) were added to the supernatant yielding a concentration of 4.5% ACN, pH 2–3. The peptide mixture was cleaned up using a C18 spin column (Harvard Apparatus, Holliston, MA) according to the manufacturer's protocol and dried in a SpeedVac concentrator. For whole-proteome LC-MS/MS analysis, dried peptides were reconstituted in 50 µl (containing peptides derived from 1–5×10 6 sperm cells) 10 mM NH 4 OH, pH 10 for further separation by basic reverse-phase chromatography (see below). For PRM-MS analysis (see below), peptide samples derived from sperm were aliquoted in amounts containing peptides derived from 180,000 sperm cells and dried in a SpeedVac concentrator.

---

### Vaginal acidity enhancement with a 3% acetic acid gel prior to misoprostol treatment for pregnancy termination in the midtrimester [^991cd7d0]. International Journal of Gynaecology and Obstetrics (2012). Low credibility.

Objective

To investigate whether enhancing vaginal acidity improves the success of medical abortions in the midtrimester.

Methods

A double-blind, randomized, placebo-controlled trial was conducted with 48 women with missed midtrimester abortions. Twice daily, the study participants (n = 24) were treated with a 3% acetic acid gel and the controls (n = 24) with a placebo gel, starting 2 days prior to initiating the misoprostol treatment. The primary outcome measures were the rates of successful abortion within 24 and 48 hours. Secondary measures included gel tolerability and adverse effects of the misoprostol treatment.

Results

The success rates were higher in the study group, within both 24 hours (11/23 vs 3/24; P = 0.011) and 48 hours (18/23 vs 6/24; P < 0.001). Among the women with a vaginal pH of 5 or higher at baseline, acidic gel was also associated with higher success rates within 24 hours (8/13 vs 2/15; P < 0.01) and 48 hours (13/13 vs 3/15; P < 0,001). The vaginal gels were well tolerated and the misoprostol treatment produced no serious adverse effects.

Conclusion

A 3% acetic acid gel appears to be an effective and safe preparatory adjuvant to vaginal misoprostol treatment for midtrimester medical abortions, especially in women with a vaginal pH of 5 or higher. www.controlledtrials.com: ISRCTN75746444.

---

### Thermodynamic principle to enhance enzymatic activity using the substrate affinity [^85e4df89]. Nature Communications (2023). High credibility.

Understanding how to tune enzymatic activity is important not only for biotechnological applications, but also to elucidate the basic principles guiding the design and optimization of biological systems in nature. So far, the Michaelis-Menten equation has provided a fundamental framework of enzymatic activity. However, there is still no concrete guideline on how the parameters should be optimized towards higher activity. Here, we demonstrate that tuning the Michaelis-Menten constant ([Formula: see text]) to the substrate concentration ([Formula: see text]) enhances enzymatic activity. This guideline ([Formula: see text]) was obtained mathematically by assuming that thermodynamically favorable reactions have higher rate constants, and that the total driving force is fixed. Due to the generality of these thermodynamic considerations, we propose [Formula: see text] as a general concept to enhance enzymatic activity. Our bioinformatic analysis reveals that the [Formula: see text] and in vivo substrate concentrations are consistent across a dataset of approximately 1000 enzymes, suggesting that even natural selection follows the principle [Formula: see text].

---

### Healthy housing reference manual [^ef8347b5]. CDC (2006). Medium credibility.

Healthy housing — acid water corrosion (Table 8.6) uses "Colorimetric field titrametric tests for acidity, pH, and carbon dioxide (pH is determined at the titration end point)", with thresholds that "A pH below 6.5 causes corrosion" and "Carbon dioxide should be less than 10 mg/L Or less than 5 mg/L if alkalinity is less than 100 ppm"; corrective actions are that "Soda ash solution is fed into the well or suction line of a pump. May be fed along with chlorine solution. Limestone chips (calcite) neutralize the water by increasing its alkalinity and hardness".

---

### Selenium-based metabolic oligosaccharide engineering strategy for quantitative glycan detection [^32ce3ef8]. Nature Communications (2023). High credibility.

DMB assay for sialic acid detection

HeLa cells were seeded into 6-well plates (5 × 10 5 cells/well), and incubated with indicated SeMOE probes at 37 °C for 48 h. After that, about 2 × 10 6 cells were harvested, resuspended in 100 μL RIPA buffer (1% Nonidet P-40 (v/v), 1% sodium deoxycholate (w/v), 150 mM NaCl, 0.1% SDS (w/v), 50 mM triethanolamine and EDTA-free Roche protease inhibitor, pH 7.4) and incubated at 4 °C for 30 min, followed by centrifugation (12,000 g, 10 min, 4 °C) to remove cell debris. Three volumes of cold alcohol were added to precipitate the cellular proteins, and the mixture was kept at −80°C overnight. Protein precipitates were collected by centrifugation (12,000 g for 10 min at 4 °C) and washed four times with 75% alcohol (v/v). Protein samples (~400 μg) or sialic acid standard were then dispersed in 70 μL 2 M acetic acid and incubated at 80 °C for 3 h, cooled on ice, and filtered through 10 kDa MWCO filters (Millipore) by centrifugation (15,000 g, 15 min, 4 °C). For sialic acid DMB derivatization, deionized H 2 O, DMB, β-mercaptoethanol, and Na 2 S 2 O 4 were added to the filtrate above to make 100 μL as the final volume and adjust the final concentration of acetic acid, DMB, β-mercaptoethanol, Na 2 S 2 O 4 at 1.4 mM, 7 mM, 0.75 M, and 18 mM, respectively. Derivatization was performed in the dark at 50 °C for 2 h, cooled on ice for 10 min, and neutralized with NaOH solution (0.2 M, 25 μL). Samples were diluted 500× with Millipore water and analyzed by RP-HPLC (Aglient 1260, XDB-C18 column, 5 µm, 4.6 × 250 mm) with a fluorescence detector (λ ex = 373 nm, λ em = 448 nm). The flow rate was 0.8 mL/min and the elution gradient was: T (0 min) 84% H 2 O + 9% CH 3 CN + 7% CH 3 OH; T (14 min) 84% H 2 O + 9% CH 3 CN + 7% CH 3 OH; T (22 min) 64% H 2 O + 18% CH 3 CN + 18% CH 3 OH; T (28 min) 64% H 2 O + 18% CH 3 CN + 18% CH 3 OH; T (29 min) 84% H 2 O + 9% CH 3 CN + 7% CH 3 OH; T (30 min) 84% H 2 O + 9% CH 3 CN + 7% CH 3 OH. The incorporation efficiency of seleno-sialic acid into glycoproteins was quantified by the integration of peak areas.

---

### 8.4% sodium bicarbonate [^6af5e40a]. FDA (2021). Medium credibility.

Principle Display Panel, Vial Label - NDC 0409-6625-02

---

### Changing dialysate composition to optimize acid-base therapy [^4cc28471]. Seminars in Dialysis (2019). Medium credibility.

In response to rapid alkali delivery during hemodialysis, hydrogen ions (H +) are mobilized from body buffers and from stimulation of organic acid production in amounts sufficient to convert most of the delivered bicarbonate to CO 2 and water. Release of H + from nonbicarbonate buffers serves to back-titrate them to a more alkaline state, readying them to buffer acids that accumulate in the interval between treatments. By contrast, stimulation of organic acid production only serves to remove added bicarbonate (HCO 3 -) from the body; the organic anions produced by this process are lost into the dialysate, irreversibly acidifying the patient as well as diverting metabolic activity from normal homeostasis. We have developed an analytic tool to quantify these acid-base events, which has shown that almost two-thirds of the H + mobilized during hemodialysis comes from organic acid production when bath bicarbonate concentration ([HCO 3 -]) is 32 mEq/L or higher. Using data from the hemodialysis patients we studied with our analytical model, we have simulated the effect of changing bath solute on estimated organic acid production. Our simulations demonstrate that reducing bath [HCO 3 -] should decrease organic acid production, a change we propose as beneficial to the patient. They also highlight the differential effects of variations in bath acetate concentration, as compared to [HCO 3 -], on the amount and rate of alkali delivery. Our results suggest that transferring HCO 3 - delivery from direct influx to acetate influx and metabolism provides a more stable and predictable rate of HCO 3 - addition to the patient receiving bicarbonate-based hemodialysis. Our simulations provide the groundwork for the clinical studies needed to verify these conclusions.

---

### Clinical practice guideline: maintenance intravenous fluids in children [^bbc83f62]. Pediatrics (2018). Medium credibility.

Tonicity, osmolality, and solution composition considerations for maintenance IVFs: Tonicity is used to describe the net vector of force on cells relative to a semipermeable membrane when in solution, with infused isotonic fluids not resulting in osmotic shifts so the cells stay the same size, cellular expansion occurring during immersion in hypotonic fluids, and in hypertonic fluid immersion free water shifting out of the cells leading to cellular contraction; osmolality is measured as osmoles of solute per kilogram of solvent and serum osmolality can be estimated by the formula 2 × Na(meq/L) + BUN (mg/dL)/2.8 + glucose (mg/dL)/18; the buffer in plasma is bicarbonate but commercially available solutions may include various concentrations of lactate, acetate, and gluconate, and multiple balanced salt solutions can be compared with normal saline (0.9% saline), which has the same sodium concentration as plasma but a supraphysiologic chloride concentration; dextrose (D-glucose) can be added to IVFs and although it affects the osmolality of IVFs, it is not a significant contributor to the plasma osmotic pressure or tonicity.

---

### KDOQI clinical practice guideline for nutrition in CKD: 2020 update [^78fd44ec]. American Journal of Kidney Diseases (2020). High credibility.

Guideline 6: Electrolytes — Acid load management in adults with chronic kidney disease (CKD) states that in CKD 1–4, we suggest reducing net acid production (NEAP) through increased dietary intake of fruits and vegetables (2C) in order to reduce the rate of decline of residual kidney function; in CKD 3-5D, we recommend reducing NEAP through increased bicarbonate or a citric acid/sodium citrate solution supplementation (1C) in order to reduce the rate of decline of residual kidney function; and in CKD 3-5D, it is reasonable to maintain serum bicarbonate levels at 24–26 mmol/L (OPINION).

---

### Identifying eigen-like hydrated protons at negatively charged interfaces [^d6a8f05d]. Nature Communications (2020). High credibility.

Despite the importance of the hydrogen ion in a wide range of biological, chemical, and physical processes, its molecular structure in solution remains lively debated. Progress has been primarily hampered by the extreme diffuse nature of the vibrational signatures of hydrated protons in bulk solution. Using the inherently surface-specific vibrational sum frequency spectroscopy technique, we show that at selected negatively charged interfaces, a resolved spectral feature directly linked to the H 3 O + core in an Eigen-like species can be readily identified in a biologically compatible pH range. Centered at ~2540cm -1, the band is seen to shift to ~1875cm -1 when forming D 3 O + upon isotopic substitution. The results offer the possibility of tracking and understanding from a molecular perspective the behavior of hydrated protons at charged interfaces.

---

### Guideline for disinfection and sterilization in healthcare facilities, 2008 [^9a61f12a]. CDC (2008). Medium credibility.

Detergent selection for instrument cleaning states that a neutral or near-neutral pH detergent solution commonly is used because such solutions generally provide the best material compatibility profile and good soil removal.

---

### Acid-base homeostasis during hemodialysis: new insights into the mystery of bicarbonate disappearance during treatment [^10dcfc5d]. Seminars in Dialysis (2018). Low credibility.

In patients receiving hemodialysis, it has long been recognized that much more bicarbonate is delivered during treatment than ultimately appears in the blood. To gain insight into this mystery, we developed a model that allows a quantitative analysis of the patient's response to rapid alkalinization during hemodialysis. Our model is unique in that it is based on the distribution of bicarbonate in the extracellular fluid and assesses its removal from this compartment by mobilization of protons (H +) from buffers and other sources. The model was used to analyze the pattern of rise in blood bicarbonate concentration ([HCO 3 -]), calculated from measurements of pH and PCO 2, in patients receiving standard bicarbonate hemodialysis. Model analysis demonstrated two striking findings: (1) 35% of the bicarbonate added during hemodialysis was due to influx and metabolism of acetate, despite its low concentration in the bath solution, because of the rapidly collapsing gradient for bicarbonate influx. (2) Almost 90% of the bicarbonate delivered to the patients was neutralized by H + generation. Virtually all the new H + came from intracellular sources and included both buffering and organic acid production. The small amount of added bicarbonate retained in the extracellular fluid increased blood [HCO 3 -], on average, by 6 mEq/L in our patients. Almost all this rise occurred during the first 2 hours. Thereafter, blood [HCO 3 -] changed minimally and always remained less than bath [HCO 3 -]. This lack of equilibrium was due to the continued production of organic acid. Release of H + from buffers is a reversible physiological response, restoring body alkali stores. By contrast, organic acid production is an irreversible process during hemodialysis and is metabolically inefficient and potentially catabolic. Our analysis underscores the need to develop new approaches for alkali repletion during hemodialysis that minimize organic acid production.

---

### Optimizing bowel preparation quality for colonoscopy: consensus recommendations by the Us Multi-society Task Force on Colorectal Cancer [^0872c64f]. Gastroenterology (2025). High credibility.

Table 6. A — PEG + ascorbic or citric acid regimens — adequate bowel cleanliness overall in high-volume (4 L) vs low-volume (2 L) preparations was 86.3% (82.0–90.5) vs 84.9% (80.8–89.0); for ultra-low-volume (≤ 1 L), 1 L PEG with ascorbic acid achieved 82.9% (74.4–90.2). The magnitude of effect is reported as relative risk high vs low volume 1.00 (0.96–1.02).

---

### Ganirelix acetate [^681589ea]. FDA (2025). Medium credibility.

DESCRIPTION

Ganirelix acetate injection is a synthetic decapeptide with high antagonistic activity against naturally occurring gonadotropin-releasing hormone (GnRH). Ganirelix acetate is derived from native GnRH with substitutions of amino acids at positions 1, 2, 3, 6, 8, and 10 to form the following molecular formula of the peptide: N-acetyl-3-(2-naphthyl)-D-alanyl-4-chloro-D-phenylalanyl-3-(3-pyridyl)-D-alanyl-L-seryl-L-tyrosyl-N9, N10-diethyl-D-homoarginyl-L-leucyl-N9, N10-diethyl-L-homoarginyl-L-prolyl-D-alanylamide acetate. The molecular weight for ganirelix acetate is 1570.42 as an anhydrous free base. The structural formula is as follows:

Ganirelix Acetate

Ganirelix acetate injection is supplied as a colorless, sterile, ready-to-use, aqueous solution intended for SUBCUTANEOUS administration only. Each single dose, sterile, prefilled syringe contains 250 mcg/0.5 mL of ganirelix acetate, 0.1 mg glacial acetic acid, 23.5 mg mannitol, and water for injection adjusted to pH 5 with glacial acetic acid, USP and/or sodium hydroxide, NF.

---

### Physiological effects of hyperchloraemia and acidosis [^c766b6af]. British Journal of Anaesthesia (2008). Low credibility.

The advent of balanced solutions for i.v. fluid resuscitation and replacement is imminent and will affect any specialty involved in fluid management. Part of the background to their introduction has focused on the non-physiological nature of 'normal' saline solution and the developing science about the potential problems of hyperchloraemic acidosis. This review assesses the physiological significance of hyperchloraemic acidosis and of acidosis in general. It aims to differentiate the effects of the causes of acidosis from the physiological consequences of acidosis. It is intended to provide an assessment of the importance of hyperchloraemic acidosis and thereby the likely benefits of balanced solutions.

---

### Sodium citrate and citric acid monohydrate (sodium citrate and citric acid) [^deef346f]. FDA (2025). Medium credibility.

STORAGE:

Keep tightly closed. Store at controlled room temperature, 20°-25°C (68°-77°F). Protect from freezing.

---

### KDIGO 2024 clinical practice guideline for the evaluation and management of chronic kidney disease [^c59b8670]. Kidney International (2024). High credibility.

Chronic kidney disease metabolic acidosis — trial evidence and certainty: The Work Group has not provided a graded recommendation for the treatment of acidosis due to a lack of large-scale RCTs supporting its use. In 2012, a 2B recommendation was justified because alkali supplementation may be a promising low-cost, high-benefit adjunct treatment for people with CKD and may be accessible to all populations. A 2021 systematic review identified 15 trials with ≥ 3 months of follow-up in people with CKD (eGFR < 60 ml/min per 1.73 m^2 and/or proteinuria) comparing the effects of oral sodium bicarbonate versus placebo or versus no study medication on kidney outcomes. Of the 15 trials (2445 participants, median follow-up 12 months), 1 new trial has been published since 2012. The totality of the evidence remains limited by a low number of outcomes, and meta-analyses restricted to the placebo-controlled trials does not confirm any important kidney effect of oral sodium bicarbonate versus placebo on risk of kidney failure (HR: 0.81; 95% CI: 0.54–1.22).

---

### The balance between the therapeutic efficacy and safety of [Lu] Lu-neoB in a preclinical prostate cancer model [^c3a675f0]. Molecular Imaging and Biology (2024). Medium credibility.

Materials and Methods

Radiolabeling

All chemicals were purchased from Sigma-Aldrich with the highest chemical grade unless otherwise stated. NeoB (Advanced Accelerator Applications, Saint-Genis-Pouilly, France) was radiolabeled with lutetium-177 (IDB Holland, Baarle-Nassau, The Netherlands) with a molar activity of 100 MBq/nmol according to the following steps. Three solutions were prepared prior to radiolabeling: solution 1: 0.250 mL gentisic acid (20 mg/mL) + 1.75 mL acetate buffer (0.5 M, pH 4.5–5.0); solution 2: ~ 1 mg DOTA-NeoB + 5 mL of the non-ionic surfactant Kolliphor HS 15 (Merck KGaA, Darmstadt, Germany) (2 mg/mL); solution 3: 3 mL ascorbic acid (22.5 mg/mL) + 1 mL acetate buffer (1 M, pH 5). For radiolabeling, 0.5 mL of lutetium-177 (50 GBq/mL) was added to 1 mL of solution 1. Subsequently, ~ 66.2 μL of solution 2 was added, and the mixture was left in a 95 °C dry bath for 7 min. Hereafter, the product was left to cool down for 5 min, and 0.5 mL of solution 3, 0.42 mL MilliQ, and 50 μL of diethylenetriaminepentaacetic acid (DTPA) (4 mM) were added.

---

### Analgesic effects of a novel pH-dependent μ-opioid receptor agonist in models of neuropathic and abdominal pain [^edb016f3]. Pain (2018). Low credibility.

2.5. Writhing model

Animals received 1% acetic acid intraperitoneally (i.p.; 10 mL/kg) under brief isoflurane anesthesia, and were placed individually in transparent cages for observation of abdominal constrictions ("writhing"). The total number of writhes between 5 and 35 minutes after acetic acid injection was counted.

2.6. pH measurements

For in vivo measurements, a pH-sensitive glass microelectrode (model IC-401 combination pH electrode; Warner Instruments, Hamden, CT) was calibrated using reference solutions of pH 4.0, 7.0, and 9.2. Measurements were performed at 3, 7, and 14 days after CCI, or before, 5, 15, and 30 minutes after i.p. acetic acid injections, under isoflurane anesthesia. In the CCI model, the microelectrode mounted in the lumen of the 20-gauge needle was inserted close to the sciatic nerve, in an area of 2 to 6 mm around the ligations, or in a similar location on the contralateral uninjured limb. In the writhing model, the needle was introduced until it perforated the skin and moved freely into the abdominal cavity. Stable readings were obtained 2 to 3 minutes after the electrode insertion in both cases. In vitro, we measured the pH of saline (0.9% NaCl; vehicle) and NLXM dissolved in saline (50 µg/100 µL) using a pH-sensitive glass electrode (Mettler Toledo; InLab Routine Pro, Giessen, Germany) calibrated using reference solutions of pH 4.01, 7.0, and 9.21.

---

### Sodium fluoride (burkhart neutral pH) [^691792da]. FDA (2022). Medium credibility.

Other Information:

Store at controlled room temperature 59° to 86°F (15°-30°C).

Protect from freezing.

---

### Clarifications to the VSP 2011 operations manual. December 2013 revision [^95f7f6e4]. CDC (2013). Medium credibility.

Potable water — test kits specify that a test kit must be available for testing free HALOGEN levels and pH, test kits must be accurate to within 0.2 mg/L (ppm) for HALOGEN and must have a testing range of free residual HALOGEN normally maintained in the RWF, and test kits for pH must be accurate to within 0.2.

---

### Rapid measurement of inhibitor binding kinetics by isothermal titration calorimetry [^3cec5bb1]. Nature Communications (2018). Medium credibility.

Introduction

There is mounting evidence that the efficacy of a therapeutic is closely related to the kinetics of interactions with its target, particularly its residence time. Systemic drug concentrations fluctuate according to administration and excretion/metabolism and substrates of inhibited enzymes tend to accumulate. Long-residence times allow targets to remain inhibited even when the systemic drug concentrations drop – or substrate concentrations rise to a level that would otherwise overwhelm the effect of the drug. On the other hand, molecules with slow association kinetics are disfavored in typical drug screens with short pre-incubation steps, and potentially efficacious molecules may be missed altogether unless care is taken. This has prompted an interest in structure–kinetics relationships (SKR) to better understand the relationship between the structures of small molecule drug candidates and their kinetic properties –.

Enzyme kinetic studies typically employ spectroscopic, chromatographic, or electrophoretictechniques to monitor the concentrations of products or substrates as a function of time, thereby yielding rates of catalysis. To measure the strength of inhibition, K i or IC 50, the enzyme (E) is allowed to equilibrate thoroughly with an inhibitor (I), such that concentration of the inhibited complex (EI) can be considered time invariant. To characterize the inhibitor association (k on) and dissociation (k off) rate constants, the pre-equilibration time with the inhibitor is varied, or substrate and product concentrations are measured while the concentration in EI gradually changes due to inhibitor binding and release. Using traditional enzyme assays to probe inhibition kinetics has several drawbacks. For instance, experiments must be repeated multiple times with the different pre-equilibration delays and/or inhibitor concentrations. Also, it can be difficult to detect small changes in catalytic rate by simply measuring substrate and concentrations over time. New biophysical methods, to quickly and efficiently assess the binding kinetics of drug candidates, are needed to improve screening and optimization efforts and to better understand the fundamental mechanisms underlying enzyme inhibition.

---

### Sodium fluoride (gelato neutral pH) [^f2bbf5a2]. FDA (2024). Medium credibility.

Other Information:

- Do not store above 25°C/77°F. Do not freeze.

---

### Effect of short-chain fatty acids and acidification on the phasic and tonic motor activity of the human colon [^4ea948d9]. Neurogastroenterology and Motility (2013). Low credibility.

Background

The effects of bacterial fermentation on human colonic motor activity could be explained by colonic acidification or short-chain fatty acid (SCFA) production. We compared in healthy volunteers the colonic motor effects of intracolonic infusion of neutral or acidic saline solutions and then of neutral or acidic solutions containing an SCFA mixture.

Methods

20 healthy volunteers swallowed a probe (with an infusion catheter, 6 perfused catheters and a balloon connected to a barostat) that migrated into the colon. Colonic motor activity was recorded in fasting basal state (1 h), during (3 h) and after (2 h) intracolonic infusion in a random order on two consecutive days of 750 mL of NaCl at pH 7.0 (neutral saline) or 4.5 (acidic saline) in 10 volunteers (first experiment) and of an SCFA mixture (acetic acid 66%, propionic acid 24% and butyric acid 10%; 100 mM) at pH 7.0 or 4.5 in 10 other volunteers (second experiment). We determined for each hour a global motility index (reflecting phasic activity recorded by all catheters), the mean balloon volume (reflecting tonic activity), and the mean number of high-amplitude-propagated contractions (HAPCs).

Key Results

Intracolonic infusion of neutral or acidic solutions containing saline or an SCFA mixture did not change the global motility index, the barostat balloon volume, or the HAPC number compared with basal values.

Conclusions & Inferences

Under our experimental conditions, these findings suggest that the stimulation of colonic motor activity induced by carbohydrate fermentation is not explained by the acidification of the colonic contents or the resulting production of SCFAs.

---

### A microenvironment-modulating dressing with proliferative degradants for the healing of diabetic wounds [^05da399e]. Nature Communications (2024). High credibility.

Radicals scavenging activity

Superoxide radical-scavenging assay

The scavenging capability of PDDA against superoxide radicals (·O 2 −) was assessed by measuring the amount of generated red azo compounds using a superoxide anion scavenging capacity assay kit. After mixing the reagents and PDDA (0, 1, 2, 5 mg mL −1) for 30 min, the absorbance value at 530 nm of the mixed solutions was recorded and the scavenging efficiency of ·O 2 − was calculated as follows:

Hydroxyl radical-scavenging assay

The elimination capability of PDDA against ·OH was assessed by TMB chromogenic assay. PDDA (0, 20, 50, 100 µg mL −1) were mixed with 100 µM H 2 O 2, 100 nM Fe 2+, and 500 µg mL −1 TMB in 0.2 M sodium acetate-acetic acid buffer (pH 3.6), and the absorbance at 652 nm was recorded every 10 min for a total of 60 min on the microplate reader (Varioskan LUX, Thermo Scientific).

Hypochlorous acid-scavenging assay

Hypochlorous acid (HClO) was prepared immediately before each use by adjusting the pH of a 10% (v/v) NaClO solution to 6.2 with 0.2 M sodium acetate-acetic acid buffer (pH 3.6). The concentration of HClO was determined by TMB using the absorbance at 652 nm. The scavenging efficiency of ClO − was calculated as follows:∆Con: concentration change of HClO compared to initial concentration.

---

### Interpreting enzyme and receptor kinetics: keeping it simple, but not too simple [^6094a7ce]. Nuclear Medicine and Biology (2003). Low credibility.

The hyperbolic parabola is commonly used to summarize kinetics for enzyme reactions and receptor binding kinetics. Depending on the experimental conditions, certain assumptions are valid but others might be violated so that the parameters used to fit this hyperbolic function, the maximum asymptote and the equilibrium constant, require different interpretations. The first topic of this review compares enzyme-induced transformations and receptor binding in terms of the appropriate assumptions. The second topic considers the complication of adding a competitive inhibitor as an enzyme substrate or a receptor ligand and the subtleties of inferring the equilibrium dissociation constant from the concentration of inhibitor (for example unlabeled drug) that leads to the midpoint, IC(50,) of an inhibition curve. Receptor binding may be measured directly by a concentration assay or as a pharmacodynamic response variable.

---

### Development of a practical formate / bicarbonate energy system [^a98adbf6]. Nature Communications (2024). High credibility.

Liquid (organic) hydrogen carriers ([18H]-dibenzyltoluene, MeOH, formic acid, etc.) form a toolbox for the storage and transport of green hydrogen, which is crucial for the implementation of renewable energy technologies. Simple organic salts have been scarcely investigated for this purpose, despite many advantages such as low cost and minor toxicity, as well as easy handling. Here, we present a potassium formate/potassium bicarbonate hydrogen storage and release energy system, that is applicable and shows high stability (6 months). Utilizing ppm amounts of the molecularly defined Ru-5 complex, hydrogen release rates of up to 9.3Lh -1 were achieved. The same catalyst system promoted the hydrogenation of KHCO 3 to HCOOK with a TON of 9650. In this way, combined hydrogen storage-release cycles can be performed for 40 times.

---

### Transformation of tenofovir into stable proTide nanocrystals with long-acting pharmacokinetic profiles [^d08e39c9]. Nature Communications (2021). High credibility.

Prodrug chemical stability

The pH buffers included 0.1% formic acid (pH 2.0), 7.5 mM ammonium acetate buffer (pH 6.0 adjusted with acetic acid), PBS (pH 7.0), 7.5 mM ammonium bicarbonate buffer (pH 8.0 adjusted with acetic acid), and 0.1% ammonium hydroxide (pH 10.3 and stored at 4 °C until use. NM1TFV or NTAF were incubated at 37 °C in 100 µL of the buffer. The final concentration of the drug in the incubation mixture was 1 µM. The reactions were stopped by the addition of 900 µL of acidified methanol (0.1% formic acid + 2.5 mM ammonium formate) at 0, 5 s, 30 min, 1, 2, 6, 12, and 24 h time points. Control samples were incubated using the same method as in the absence of substrates, however, substrates were added after the addition of acidified methanol. The mixtures were centrifuged at 16,000 × g for 10 min. The supernatants were aspirated and stored at −80 °C until ultraperformance liquid chromatography tandem mass spectrometry (UPLC-MS/MS) analysis.

Human monocyte-derived macrophage (MDM) isolation, cultivation, and cytotoxicity

Human monocytes were obtained, cultured, and differentiated into MDM as previously described. The cell viability after treatment with nanoparticles was evaluated using the MTT assay. Human MDMs plated in 96-well plates at a density of 0.08 × 10 6 cells/well were exposed to a range of concentrations (1.5625−200 µM) of NM1TFV, NM2TFV, or TAF for 8 h. The cells were then washed with PBS after which 100 μL of MTT solution was added to each well (5 mg/mL) for 45 min at 37 °C. The MTT solution was then replaced with 200 μL/well of DMSO. A Molecular Devices SpectraMax M3 plate reader with SoftMax Pro 6.2 software (Sunnyvale, CA) was used to record absorbance at a wavelength of 490 nm.

---

### Electrochemical oxygen reduction to hydrogen peroxide at practical rates in strong acidic media [^64025a69]. Nature Communications (2022). High credibility.

The measured trends of H 2 O 2 FE show that the promotion effect of Na + is more pronounced at high current density toward H 2 O 2 formation. We understand that Na + and protons are both positively charged ions and will be attracted towards the ORR catalyst surface to form the electrochemical double layer under negative potentials. We would assume that, Na + ions could be more competitive than protons to be aligned along the electrochemical double layer, which dramatically reduces the local proton concentration and thus protects the generated H 2 O 2 from further reductions coupling protons and electrons (discussed in the following sections in detail). To further amplify the cation effect and drive the O 2 -to-H 2 O 2 production at even higher current densities in acid (> 200 mA cm −2), we gradually increased the Na + cation concentration in the electrolyte. As shown in Fig. 3a, the overall current density, as well as the H 2 O 2 FE gradually increases with increased Na + concentrations. In general, a higher concentration of Na + can maintain larger 2e − –ORR currents without sacrificing the H 2 O 2 selectivity. With only 0.01 M Na 2 SO 4 in 0.1 M H 2 SO 4, the FE of H 2 O 2 can reach 83% at 400 mA cm −2 (Fig. 3b), representing a 25-fold improvement compared to that in pure acids without Na + (H 2 O 2 FE only 3.3%). Along with the increased H 2 O 2 FE, the improvement of the H 2 O 2 production rate was also obvious at high current densities (Fig. 3c). For example, the production rate of 6.21 mmol cm −2 h −1 H 2 O 2 (partial current of 332 mA cm −2) was achieved under the current density of 400 mA cm −2, much higher than that in pure H 2 SO 4 acid (only 0.245 mmol cm −2 h −1). The production rate can be further enhanced by providing more Na + cations (the production rate of 6.52 mmol cm −2 h −1 was achieved at 400 mA cm −2 and the maximum FE can be up to 94% at 150 mA cm −2 by using 0.05 M Na 2 SO 4 as additive). Further increasing the concentration of Na + cations could continually push up the H 2 O 2 FE to higher values at high current densities (Fig. S3). It is important to note here that the electrolyte pH did not show obvious change and stayed around pH 1 after these Na 2 SO 4 additives, ranging from 0.96 (0.1 M H 2 SO 4), 0.96 (0.1 M H 2 SO 4 + 0.005 M Na 2 SO 4), 0.98 (0.1 M H 2 SO 4 + 0.01 M Na 2 SO 4) to 1.04 (0.1 M H 2 SO 4 + 0.05 M Na 2 SO 4). To fully exclude the pH effect of the bulk solution (even though the change is quite small), the pH value of 0.1 M H 2 SO 4 + 0.1 M Na 2 SO 4 (pH = 1.13) was adjusted to be the same as that of 0.1 M H 2 SO 4 (pH = 0.96) by adding more sulfuric acid. As shown in Fig. S4 and S5, the H 2 O 2 FE in both electrolytes with Na + additives (before and after pH tuning) showed very similar trend in all current ranges, indicating the Na + cations dominate the H 2 O 2 generation process and the small pH differences of electrolytes have negligible influence on the production rate or H 2 O 2 FE. With 0.1 M Na 2 SO 4 as an additive in 0.2 M H 2 SO 4 solution (pH = 0.76), we were able to produce H 2 O 2 at the current density of 1 A cm −2 with a FE of more than 65% (Fig. S6). The H 2 O 2 partial currents of up to 650 mA cm −2 were achieved, and high FEs were maintained, better than the highest O 2 -to-H 2 O 2 conversion rates reported. At even lower pH electrolyte, i.e. 1 M H 2 SO 4 solution (PH~0), similar trends were also observed (Fig. S7), indicating the general phenomenon of cation promotion effect toward H 2 O 2 production through ORR.

---

### Thermodynamic principle to enhance enzymatic activity using the substrate affinity [^aaa37ded]. Nature Communications (2023). High credibility.

Similar calculations for competitive and uncompetitive inhibition, where the inhibitor binds to either the free enzyme or the enzyme-substrate complex, are shown in Fig. 6b, c. The degree of inhibition, is determined by the inhibitor concentration and the equilibrium constant of inhibition. Based on the experimental data of Park et al.can range from 10–4 to 10 4. Aswas less than 10 in approximately 80% of their data, was used here for the numerical simulations. Again, the optimal(solid line) deviates only slightly from the dashed line, and both lines pass through the region of high activity (orange). Thevalues are approximately 1 order of magnitude apart between dashed and solid lines, yet there is only a 57% difference in activity at a specific. This is much smaller than the scale of the entire diagram (10 orders of magnitude), suggesting that adjustingto the substrate concentrationis a robust strategy to enhance the activity, even in the presence of inhibition. A detailed discussion on the parameter dependence, as well as for other mechanisms such as substrate inhibition or allostericity can be found in Section 5 of the supporting information. The derivations for the equations of the true optimal K m can also be found in the same section.

The influence of the assumptionis shown in Fig. 6d. As physical constraints require(Appendix 2), onlyandare independent. In an extreme case of, the activity is diminished because rate constants hardly change even if their driving force is increased. However, the dashed line still passes through the region of high activity, and the activity is still less than an order of magnitude away from the true optimum (solid line). The fact thatyields high activity is valid even for other values ofand(Supplementary Figure 5). This dashed line was obtained through numerical optimization, because no analytical solution for the optimumwas obtained for general values ofand. We note that the optimality obtained by Kari et al. is a special case of Eq. (13), which can be obtained under the assumption. Further assumingyields. Taken together, the simulations confirm thatis a robust theoretical guideline to enhance enzymatic activity.

---

### Oxygen mediated oxidative couplings of flavones in alkaline water [^eb1dbfe9]. Nature Communications (2022). High credibility.

Synthesis of luteolin-flavone biflavones

Luteolin (72 mg, 0.25 mmol) and flavones (0.5 mmol) were added to an alkaline solution (30 mL 0.1 M KOH) in 50 mL centrifuge tube, pH was adjusted to optimal pH before the tube is closed tight and kept at room temperature for 10 h without stirring. Hydrochloric acid (1 mL 10 M) was added into reaction mixture to quench the reaction. The mixture was extracted with ethyl acetate (3 × 50 mL). The organic phase was combined and evaporated in vacuo. The crude solid obtained was purified over semi-prep HPLC with automatic fraction collect system to give the desired products. The yields and spectral data of each product (2b-2k) were stated in section 1.2.8.

Synthesis of B-catecholic flavone-apigenin biflavones

B-catechols (0.25 mmol) and apigenin (140 mg, 0.5 mmol) were added to alkaline solution (30 mL 0.1 M KOH solution) in a 50 mL centrifuge tube. The solution pH was adjusted to optimal pH before the tube was closed tightly and kept at room temperature for 10 h without stirring. After that, hydrochloric acid (1 mL 10 M) was added into the reaction mixture, which was then extracted with ethyl acetate (100 mL). The organic extract was worked up and purified over semi-prep HPLC with automatic fraction collection system.

General procedure for syntheses of triflavonoids

Dicranolomin (143 mg, 0.25 mmol) and flavones (0.375 mmol) were added to an alkaline solution (30 mL, 0.1 M KOH) in a 50 mL centrifuge tube and the pH of the mixture was adjusted to 11.5 before the tube was sealed at room temperature for 10 h without stirring. Acid (10.0 M HCl) was then added into the reaction mixture until the pH reached 1–2. Subsequently, ethyl acetate (3 × 50.0 mL) was added to extract the products, combined organic layer was thoroughly concentrated to give crude solid which was purified over semi-prep HPLC with automatic fraction collect system to give the pure cross-coupling product.

---

### KDIGO clinical practice guidelines for acute kidney injury [^04714d0c]. Nephron: Clinical Practice (2012). Medium credibility.

KDIGO AKI — potassium and metabolic acidosis considerations explain that when therapeutic measures that promote the intracellular shift of potassium are exhausted, an excess of potassium can only be eliminated with RRT, and using intermittent dialysis after such measures reduces extracorporeal potassium removal with a more pronounced post‑treatment rebound. For acidosis, metabolic acidosis associated with AKI can usually be corrected with bicarbonate and should rarely require urgent dialysis if not accompanied by volume overload or uremia; because pH and bicarbonate values to initiate dialysis are not supported by evidence, no standard criteria for initiating dialysis for acidosis exist, while some poisonings can contribute to acid‑base problems and RRT may facilitate removal of the offending drug.

---

### Molecular rheotaxis directs DNA migration and concentration against a pressure-driven flow [^818e1b87]. Nature Communications (2017). Medium credibility.

Effects of buffer ions on concentration enhancement

The mechanistic resemblance to diffusiophoresis led us to investigate the potential contribution of a second chemiphoretic mechanism in which favorable interactions between positively charged cations and the negatively charged DNA molecules could also drive DNA migration (Fig. 2). Though not accounted for in our numerical simulation, the chemiphoretic component has been suggested to play a dominant role in diffusiophoresis in some circumstances.

To determine the relative contributions of electrophoresis and chemiphoresis, we designed a buffer system where we could hold the chemiphoretic component relatively constant while modulating the electrophoretic component. In these experiments, a low ionic strength base buffer was used in both the reservoir and running buffers (see "Methods" section). This "EB buffer" base consists of a weak acid (ε-aminocaproic acid, EACA) and a weak base (Bis-Tris), which titrate each other while remaining > 90% neutral and maintaining a high buffering capacity. Three capillary running buffers were created with low, medium, and high expected electrophoretic components through the addition of 9 mM KCl, NaCl, and HCl, respectively. These species completely dissociate in solution and form an ion concentration gradient across the capillary orifice. With Cl − and EB concentrations held constant, these running buffers therefore allow us to probe the effect of cation diffusivity on the size of the induced electrophoretic field and the DNA concentration factor.

---

### Dilutional acidosis: where do the protons come from? [^040bf532]. Intensive Care Medicine (2009). Low credibility.

Purpose

To investigate the mechanism of acidosis developing after saline infusion (dilutional acidosis or hyperchloremic acidosis).

Methods

We simulated normal extracellular fluid dilution by infusing distilled water, normal saline and lactated Ringer's solution. Simulations were performed either in a closed system or in a system open to alveolar gases using software based on the standard laws of mass action and mass conservation. In vitro experiments diluting human plasma were performed to validate the model.

Results

In our computerized model with constant pKs, diluting extracellular fluid modeled as a closed system with distilled water, normal saline or lactated Ringer's solution is not associated with any pH modification, since all its determinants (strong ion difference, CO(2) content and weak acid concentration) decrease at the same degree, maintaining their relative proportions unchanged. Experimental data confirmed the simulation results for normal saline and lactated Ringer's solution, whereas distilled water dilution caused pH to increase. This is due to the increase of carbonic pK induced by the dramatic decrease of ionic strength. Acidosis developed only when the system was open to gases due to the increased CO(2) content, both in its dissociated (bicarbonate) and undissociated form (dissolved CO(2)).

Conclusions

The increase in proton concentration observed after dilution of the extracellular system derives from the reaction of CO(2) hydration, which occurs only when the system is open to the gases. Both Stewart's approach and the traditional approach may account for these results.

---

### Ganirelix acetate (fyremadel) [^1031604d]. FDA (2025). Medium credibility.

DESCRIPTION

FYREMADEL (ganirelix acetate) injection is a synthetic decapeptide with high antagonistic activity against naturally occurring gonadotropin-releasing hormone (GnRH). Ganirelix acetate is derived from native GnRH with substitutions of amino acids at positions 1, 2, 3, 6, 8, and 10 to form the following molecular formula of the peptide: N-acetyl-3-(2-naphthyl)-D-alanyl-4-chloro-D-phenylalanyl-3-(3-pyridyl)-D-alanyl-L-seryl-L-tyrosyl-N9, N10-diethyl-D-homoarginyl-L-leucyl-N9, N10-diethyl-L-homoarginyl-L-prolyl-D-alanylamide acetate. The molecular weight for ganirelix acetate is 1570.4 as an anhydrous free base. The structural formula is as follows:

Ganirelix Acetate

FYREMADEL (ganirelix acetate) injection is supplied as a colorless, sterile, ready-to-use, aqueous solution intended for SUBCUTANEOUS administration only. Each single-dose, sterile, prefilled syringe contains 250 mcg/0.5 mL of ganirelix acetate, 0.1 mg glacial acetic acid, 23.5 mg mannitol, and water for injection adjusted to pH 5 with acetic acid and/or sodium hydroxide.

---

### Chronic kidney disease CKD: guideline recommendations and supporting information (2020) [^c3155b04]. AND (2020). High credibility.

CKD: Bicarbonate supplementation — In adults with CKD 3-5D, we recommend reducing net acid production (NEAP) through increased bicarbonate or a citric acid/sodium citrate solution supplementation (1C) in order to reduce the rate of decline of residual kidney function; rating: Fair Conditional.

---

### Clinical practice guideline (update): earwax (cerumen impaction) [^8e6abf5f]. Otolaryngology — Head and Neck Surgery (2017). Medium credibility.

Table 9 topical preparations for cerumen impaction — water based options list acetic acid (aqueous acetic acid), Cerumenex (triethanolamine polypeptide oleate-condensate), Colace (docusate sodium), hydrogen peroxide (hydrogen peroxide solution), sodium bicarbonate (sodium bicarbonate), and sterile saline solution (water); oil based options list almond oil (almond oil), arachis oil (arachis oil), Earex (arachis oil, almond oil, rectified camphor oil), olive oil (olive oil), and mineral oil/liquid petrolatum (liquid petrolatum); nonwater, nonoil options list Audax (choline salicylate, glycerine) and Debrox (carbamide peroxide [urea-hydrogen peroxide]).

---

### A supramolecular system that strictly follows the binding mechanism of conformational selection [^24462932]. Nature Communications (2020). High credibility.

All these results further corroborate that the binding pair between 1 and 2 strictly follows the conformational selection mechanism. Not only can the kinetic data be well fitted with Eq. (1), but the thermodynamic data can also be calculated, and these data are fully consistent with those obtained with the thermodynamic experiments. This indicates that Eq. (1) accurately describes the kinetic and thermodynamic aspects of conformational selection.

Thermodynamic aspect of conformational selection

Proteins often exist as a conformational ensemble. Even though a conformational selection binding mechanism is followed, the same guest may bind two or more conformations simultaneously but show a preference to one over the others. Due to the complexity of the biological systems and limited analytical tools to reveal the binding details, the binding affinity of a ligand to the inactive conformation is often not studied. Thus, the thermodynamic aspect of conformational selection, such as the selectivity between the active and inactive conformations, is largely ignored. With the current simplified supramolecular system in hands, the thermodynamic aspect of conformational selection can be studied as well.

As shown in Fig. 5, three equilibria are involved if a guest can bind both conformers I and V. The association constants of the same guest to the two conformers are K 1 and K 2, which can be defined in Eqs. (3) and (4), respectively. The equilibrium constant (K) between the two conformations is defined in Eq. (5). The molar concentration of G @ I and G @ V are [G @ I] and [G @ V], respectively. A conformational selectivity factor (α) may be defined as α = K 1 / K 2. With this factor, the thermodynamic fidelity of conformational selection can be quantified. When α is large, one conformation is thermodynamically more preferred over the other. However, how are the association constants of the same guest binding to the two interconvertible conformations simultaneously determined? An HPLC method has been developed for a dynamic combinatorial library, but this method is not suitable for conformational equilibrium. Here, new equations are then developed to describe this process.

---

### Complexation-induced resolution enhancement of 3D-printed hydrogel constructs [^15188dc7]. Nature Communications (2020). High credibility.

Shrinking behaviors of polyionic hydrogels

The carboxyl groups present in HAMA render the hydrogel negatively charged under physiological conditions. When a HAMA hydrogel is placed in the presence of polycations of high charge densities, such as chitosan, a type of glucosamine featuring reasonable biocompatibility and densely cationic nature due to the abundantly available amino groups, charge compensation occurs leading to expulsion of water and eventual size reduction of the HAMA hydrogel (Fig. 1a and Supplementary Fig. 1). Indeed, this phenomenon was previously observed for microgels. We also recently demonstrated, that when a solution of positively charged lysozyme was introduced to microfluidics-fabricated HAMA microspheres, the size of these microspheres was decreased due to a mechanism akin to complex coacervation, facilitating their use in drug delivery.

Fig. 1
The general mechanism of complexation-induced hydrogel shrinking.

a Schematics showing the shrinking effect based on charge compensation. b Photograph showing size change of fabricated HAMA hydrogel (1.0 w/v%) before (lower) and after (upper) shrinking in 2.0 w/v% MM w chitosan dissolved in 1.0 v/v% acetic acid aqueous solution. c Schematic representation of a HAMA hydrogel disc together with the dimensions and corresponding quantitative analyses showing the dimensions and volume changes before and after shrinking in 2.0 w/v% MM w chitosan dissolved in 1.0 v/v% acetic acid aqueous solution. d Corresponding quantitative analyses showing the shrinking of HAMA hydrogels in perchloric acid solution (pH = 1.0) or in 1.0 v/v% acetic acid aqueous solutions (pH = 4.7) with 2.0 w/v% of chitosan of different molecular weights and types. e Confocal images showing the diffusion of FITC-Q. chitosan solution in PBS into a 2.0 w/v% HAMA hydrogel at 3 and 24 h of shrinking. The bright-field image at 0 h serves as the size reference of the initial hydrogel. f Photograph showing size change of HM w chitosan hydrogels (2.0 w/v%), where the lower one was swollen in 1.0 v/v% acetic acid aqueous solution and the upper one was shrunken in 2.0 w/v% alginate in 1.0 v/v% acetic acid aqueous solution. P < 0.01; one-way ANOVA (c, d, compared with the values of corresponding as-prepared samples); mean ± s.d, (n = 3).

---

### Photoinduced monooxygenation involving NAD (P) H-FAD sequential single-electron transfer [^854f343a]. Nature Communications (2020). High credibility.

Photodegradation of FAD

Degradation of FAD in free and PqsL-complexed states was analyzed by illuminating solutions containing 500 µM free FAD or PqsL in 30 mM tris-HCl, pH 8.3 with a blue LED. Samples were taken after 0, 10, 30, and 60 min of illumination, diluted 1:10 in 15% (v/v) acetonitrile buffered with 0.1% (v/v) formic acid, centrifuged for 1 min at 20,000 x g. The supernatant was directly subjected to HPLC. Decomposition of FAD was followed by monitoring the formation of lumichrome, the major degradation product of FAD at pH 8.3.

HPLC and LC-MS analysis

All HPLC analyses were performed with an Agilent 1100 Series instrument (Agilent, Santa Clara, CA, USA) equipped with an Eurospher II 3 µm C18 100 × 3 mm column (Knauer, Berlin, Germany).

Analysis of alkyl quinolones was carried out within 6 min at 0.6 mL min −1 isocratic flow in 70% methanol/water buffered with 0.1% (v/v) acetic acid. Separation of NAD +, NADP +, NADH and NADPH was achieved by 4 min of isocratic flow of 15 mM ammonium acetate, pH 6.8, followed by a linear gradient from 0 to 15% methanol over 10 min at a flow rate of 0.25 mL min −1. FAD and its derivatives were separated by 6 min of isocratic flow in 15% acetonitrile/water buffered with 0.1% (v/v) formic acid, ensued by a linear gradient from 15 to 53% acetonitrile over 24 min and 0.5 mL min −1 flow.

HPLC-MS analyses of (deuterated) reduced nicotinamide adenine dinucleotides were performed using a Thermo Fisher Scientific Ultimate 3000/Bruker Amazon speed instrument (Bruker Daltonics, Billerica, MA, USA) equipped with a Knauer Eurospher II 100–5 C18 150 × 3 mm column. Solvents were 15 mM aqueous ammonium acetate, pH 6.8 (A) and acetonitrile (B). Elution was started with 5 min of isocratic flow (100% A) before linearly increasing to 20% B over 30 min. Afterwards, the column was washed for 5 min (90% B) and equilibrated to starting conditions for another 5 min. Flow was kept constant at 0.5 mL min −1. Electrospray ionization parameters were set according to the manufacturer's recommendations.

---