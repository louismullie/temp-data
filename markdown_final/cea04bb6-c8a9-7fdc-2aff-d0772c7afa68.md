# Medical Question & Answer

**Sample ID**: cea04bb6-c8a9-7fdc-2aff-d0772c7afa68
**Dataset Index**: 231353

---

## Question

What is the maximum area of an isosceles trapezoid that has legs of length 1 and one base twice as long as the other?
(A) [5/4] (B) [8/7] (C) [5√2/4] (D) [3/2] (E) [3√3/4]

---

## Answer

> Let's see… What do we have here? The user is asking for the maximum area of an isosceles trapezoid with legs of length 1 and one base twice as long as the other. Let's break this down step-by-step. First, I need to think about setting up the geometry and labeling variables. Then, I should express the area in terms of a single variable and find the critical points. Next, I will verify the second derivative to confirm a maximum. Finally, I will compute the maximum area and match it to the answer choices, making sure I haven't missed any constraints or made algebraic errors along the way.

> Let me first set up the trapezoid. I will call the shorter base b and the longer base 2b, with legs of length 1. Because it is isosceles, the legs are congruent and the base angles are equal, so I can drop altitudes from the ends of the shorter base to the longer base to form two right triangles and a rectangle in the middle, which will help me relate height and bases to the leg length [^notfound].

> Wait, let me verify the height expression. In each right triangle, the horizontal projection of the leg is (2b − b)/2 = b/2, and the vertical side is the height h, so by the Pythagorean theorem, h² + (b/2)² = 1², which gives h = √(1 − b²/4). I should confirm that this is valid only when 1 − b²/4 ≥ 0, so b ≤ 2, which makes geometric sense because the leg length is 1 and the horizontal offset cannot exceed the leg length [^notfound].

> Next, I should write the area formula. The area A of a trapezoid is the average of the bases times the height, so A = (b + 2b)/2 × h = 3b/2 × √(1 − b²/4). I need to ensure I substitute the correct height expression, which I just derived, so A(b) = (3b/2)√(1 − b²/4) for 0 < b ≤ 2 [^notfound].

> I will now examine how to maximize this function. Let me consider squaring the area to simplify differentiation, since the square of a positive function attains its maximum at the same point. So I define f(b) = A² = (9b²/4)(1 − b²/4) = (9/4)(b² − b⁴/4). Taking the derivative, f′(b) = (9/4)(2b − b³) = (9/4)b(2 − b²). Setting f′(b) = 0 gives b = 0 or b² = 2, so b = √2, and I should discard b = 0 because it corresponds to a degenerate trapezoid with zero area [^notfound].

> Hold on, I should verify that this critical point is a maximum. The second derivative is f″(b) = (9/4)(2 − 3b²). At b = √2, f″(√2) = (9/4)(2 − 6) = −9, which is negative, confirming a local maximum. Since the function is continuous on (0, 2] and tends to 0 as b approaches 0 or 2, this local maximum is indeed the global maximum on the domain [^notfound].

> Now I will compute the maximum area. Substituting b = √2 into the area formula, A = (3√2/2)√(1 − (√2)²/4) = (3√2/2)√(1 − 2/4) = (3√2/2)√(1/2) = (3√2/2)(1/√2) = 3/2. Wait, let me double-check that simplification: √2 × 1/√2 = 1, so yes, the maximum area is 3/2 [^notfound].

> I should confirm the answer choice mapping. The options include 3/2 as choice D, so the correct selection is D. Let me reconsider whether any of the other choices could arise from a different interpretation or a calculation error; none of the other options match 3/2, and my derivation consistently leads to this result, so I am confident in D as the answer [^notfound].

---

The maximum area of an isosceles trapezoid with legs of length 1 and one base twice the other is **3/2**, achieved when the shorter base is √2 and the height is √2/2. This result is obtained by expressing the area as a function of the shorter base, then maximizing it using calculus. The maximum area corresponds to option **D**.

---

## Geometric setup

Let the isosceles trapezoid have:

- Legs of length 1.
- Shorter base of length (b).
- Longer base of length (2b).
- Height (h).

By dropping altitudes from the ends of the shorter base to the longer base, we form two right triangles and a rectangle. The horizontal projection of each leg is ([(2b − b)/2] = [b/2]), so by the Pythagorean theorem:

h² + ([b/2])² = 1² ⇒ h = √(1 − [b²/4])

---

## Area expression

The area (A) of a trapezoid is the average of the bases times the height:

A = [(b + 2b)/2] × h = [3b/2] × √(1 − [b²/4])

---

## Maximizing the area

To maximize (A), we maximize (A²) (since (A > 0)):

A² = ([3b/2])² (1 − [b²/4]) = [9b²/4] (1 − [b²/4]) = [9/4] (b² − [b⁴/4])

Let f(b) = b² − [b⁴/4]. Then:

f′(b) = 2b − b³ = b(2 − b²)

Setting f′(b) = 0 gives b = 0 or b² = 2. Since b > 0, we have b = √2. The second derivative:

f″(b) = 2 − 3b² ⇒ f″(√2) = 2 − 6 = −4 < 0

confirms a maximum at (b = √2).

---

## Maximum area calculation

Substitute (b = √2) into the area formula:

h = √[1 − [(√2)²/4]] = √[1 − [2/4]] = √[1/2] = [√2/2]

A = [3√2/2] × [√2/2] = [3 × 2/4] = [3/2]

---

## Conclusion

The maximum area is **3/2**, which corresponds to option **D**.

---

## References

### Coarse-grained fundamental forms for characterizing isometries of trapezoid-based origami metamaterials [^cecbb2e6]. Nature Communications (2025). High credibility.

Analysis of Arc-Morph origami

We introduce the family of Arc-Morph origami, such as the example shown in Fig. 3 A. This family generalizes the Arc-Miura crease patterns presented in refs. to include the non-developable vertex geometry from the family of Morph parallelogram-based origami introduced in ref. The unit cell of these periodic crease patterns is constructed from copies of a base vertex that is parameterized by the two independently chosen sector angles α and β. The three remaining vertices of the cell have identical or supplementary sector angles and the distinction in the present work is that the vertices are arranged to form trapezoid faces rather than parallelograms. We exclusively consider isosceles trapezoids to simplify analytic expressions, but our model applies to tessellations composed of more general trapezoids and with larger unit cells such as those shown in Fig. 1 B–D which contain increased numbers of faces. Thus, each of the trapezoids has two legs of length q, one base of length p, and one base of eitheror(see Fig. 3 B). This yields the three-dimensional design space (α, β, q / p) for Arc-Morph, where the magnitude of p dictates the scale of the system which has no role in our kinematic analysis.

---

### Coarse-grained fundamental forms for characterizing isometries of trapezoid-based origami metamaterials [^5b430ca6]. Nature Communications (2025). High credibility.

We repeat this analysis for the nonrigid isometry which we cannot describe in terms of changes to the dihedral angles exclusively. Since this crease pattern falls within the broader set of TBO that our theory applies to, the nonrigid isometry is represented by the vertex amplitudesand the face amplitudes. We again integrate the changes in the lattice vectors and the lattice rotation matrices, then average according to our coarse-graining procedure to find:where we determine σ 1 and σ 2 directly fromandand find that the diagonal components of the strain vanish: ε φ φ = ε z z = 0. We confirm these quantities are self consistent with δ I φ z = δ I z φ = R 2 σ 1 + σ 2, δ I I φ z = δ I I z φ = R σ 1 without any adjustment to the averaging step of our coarse-graining procedure. Here, there is an apparent discrepancy regarding the units of σ 1 and σ 2: from dimensional analysis of Eqn. (7), σ 1 must have units of inverse area and σ 2 must be dimensionless. However, our calculations leading to Eqns. ((15), (16)) use a dimensionless face amplitude to simplify our calculations while the integration framework assumes the face amplitude has units of inverse length. This is in contrast to the vertex amplitudes which are always dimensionless. Introducing such a length scale, for example from the square root of the cell area, resolves the apparent discrepancy. The self consistency of our results relies on both the averaging process in our coarse-graining method and the inclusion of the Jacobian to transform from the discrete lattice coordinates to the continuous surface coordinates. While for the nonrigid isometries of parallelogram-based origami the averaging is also important, the Jacobian may be neglected because the ground states are quasi-planar.

---

### Climbing favours the tripod gait over alternative faster insect gaits [^cd5d58cb]. Nature Communications (2017). Medium credibility.

We did not model air drag in our simulations. Although drag is an important factor for insect flight, we found that it is not nearly as relevant as frictional forces for walking. We computed drag forces for a single leg according to equation (3):

where ρ = 1.225 kg m −3 (density of air), c D = 1.05 (drag coefficient for a cube). The velocity ν was computed based on the frequency of leg motion and length of each leg: ν = 2 πfL = 0.0628, m s −1, where f = 20 Hz and L = 0.0005, m. We considered the area of a leg as the drag area A where A = d. L = 5.10 −8 m 2, where d = 100 μm. Frictional forces are therefore three orders of magnitude larger and dominate drag forces. Similarly, if drag forces are calculated for the whole body, the velocity ν c = 0.02 m s −1 (the approximate maximum walking speed of a fly) and the drag area A = 0.0025 2 m 2 (the cross-sectional area approximated by the square of a fly's length). In this case F D = 1.6.10 −9 N and is still several orders of magnitude smaller than frictional forces.

Gait optimization

We used PSO, a stochastic optimization algorithm, to discover gaits that optimize forward velocity under different adhesion and travel orientation conditions. We implemented PSO using the inspyred (inspyred.github.com) Python framework. Briefly, 50 candidate gaits (particles) were randomly initialized within a 5-dimensional search space of possible solutions. Each dimension represents one leg's phase of motion relative to the front left leg, which was fixed at 0° phase. During PSO, the phases of the five remaining legs could vary between 0° and 360°. For example, in this formulation a phase vector [L1 = 0°; R1 = 180°; L2 = 180°; R2 = 0°; L3 = 0°; R3 = 180°] defines the classic tripod gait, which we call tripod-A to distinguish it from alternative three-legged gaits.

---

### Coarse-grained fundamental forms for characterizing isometries of trapezoid-based origami metamaterials [^a2ff9e7d]. Nature Communications (2025). High credibility.

Investigations of origami tessellations as effective media reveal the ability to program the components of their elasticity tensor, and thus control the mechanical behavior of thin sheets. However, existing efforts focus on crease patterns that are composed of parallelogram faces where the parallel lines constrain the quasi-static elastic response. In this work, crease patterns composed of more general trapezoid faces are considered and their low-energy linear response is explored. Deformations of such origami tessellations are modeled as linear isometries that do not stretch individual panels at the small scale yet map to non-isometric changes of coarse-grained fundamental forms that quantify how the effective medium strains and curves at the large scale. Two distinct mode shapes, a rigid breathing mode and a nonrigid shearing mode, are identified in the continuum model. A specific example, which we refer to as Arc-Morph origami, is presented with analytical expressions for its deformations in both the discrete and continuous models. A developable specimen is fabricated and tested to validate the analytical predictions. This work advances the continuum modeling of origami tessellations as effective media with the incorporation of more generic faces and ground states, thereby enabling the investigation of novel designs and applications.

---

### Dynamic similarity and the peculiar allometry of maximum running speed [^db3920dd]. Nature Communications (2024). High credibility.

From these parameters, we derived first order predictions for the Hill- and Borelli-limit, and, the physiological similarity index, the reduced parasitic energy, and the work density of muscle, W ρ = σ m a x ε m a x ρ −1. Estimates for l m and m f were obtained as arithmetic averages or via log-log regression from data on 31 mammalian and reptile species that varied across four orders of magnitude in body mass; the fascicle length here is the fascicle length of a hypothetical muscle which has a volume and physiological cross-sectional area equal to the sum of all relevant limb muscles. All estimates assume that half of the total limb muscle mass contributes to the acceleration during stance.

First, and in general, the exact geometric similarity was assumed wherever available scaling exponents were consistent with or very close to this hypothesis (but see point three on the gear ratio). Geometric similarity is a parsimonious and plausible null hypothesis, and thus the obvious starting point. Second, we note that the fascicle length, l m is an equivalent fascicle length, equal to the fascicle length of a hypothetical muscle which has a volume and physiological cross-sectional area equal to the sum of that of all relevant limb muscles, averaged across all limbs [for further detail, see ref.]. In practice, this definition reflects the physical reality that the speed of individual contractile elements linked in series is additive. The physiological cross-sectional area then follows in analogy, as the ratio between total limb muscle volume and equivalent fascicle length. Third, we estimate an average gear ratio G = 0.3 ± 0.2 from published data on 42 vertebrate species covering about five orders of magnitude in body mass [Fig. 2; data from –,]. As is well established, the gear ratio increases significantly with size within quadrupedal mammals, G ∝ m 0.16 [, We note that this slope differs from the estimate reported in the original papers, as we included additional data.]. G is however approximately size-invariant within the bipedal, hopping Macropodoidea [G ∝ m 0.004 ;]. We used a size-invariant gear ratio as the initial guess for our across-clade analysis to adhere to the parsimonious assumption of geometric similarity, and because the allometry of the gear ratio appears to be clearly confounded by evolutionary history, so that extrapolation to groups not represented in the available data is likely unreliable [Fig. 2 and]. Further quantitative interpretation and in particular extrapolation to animals outside the size range for which data is available can be conducted once a larger and more phylogenetically diverse dataset is available. The functional significance of a systematic variation of G with size, and its effect on maximum running speed, is critically evaluated in more detail in the results. Fourth and last, our analysis required estimation of an effective 'coefficient of restitution', η, which quantifies the speed loss from collisions and unavoidable fluctuations in the vertical centre-of-mass velocity that accompany each step. We first briefly derive the relation between the speed increment per step (v i), the effective coefficient of restitution (η), and the maximum possible speed (v peak), and then estimate η directly from empirical data. All statistical analysis below or elsewhere in the manuscript was conducted in R v. 4.3.2 pr Python 3.

---

### Miniaturized MgBi-based thermoelectric cooler for localized electronic thermal management [^8ecc9c5a]. Nature Communications (2025). High credibility.

Results

Principles for the design of a miniscale thermoelectric cooling device

The performance of thermoelectric coolers, e.g. the maximum cooling temperature difference (Δ T max) and cooling power (Q c), is jointly determined by the material properties and the device design. In this study, the performance of Mg 3 Bi 2 -based thermoelectric coolers is investigated by examining the effects of varying leg lengths, different ceramic materials, and varied electrical contact resistivities. The material properties used for the calculation are shown in Supplementary Fig. 1.

When the cooler operates at the optimal electrical current and reaches a steady state, the cooling power at the cold side is determined by Eq. (1), where T c is the cold-side temperature, T h is the hot-side temperature, N is the number of thermoelectric pairs, and I is the electrical current. In addition, S, R, and K are the Seebeck coefficient, the electrical resistance, and the thermal conductance of a thermoelectric pair consisting of an n-type leg and a p-type leg.

The maximum temperature difference of the thermoelectric cooler is expressed by Eq. (2), where the figure of merit of a thermoelectric pair (Z) is given by Eq. (3), When the temperature difference becomes zero, the cooling power reaches its maximum value (Q c, max), which is shown by Eq. (4), Considering the impact of electrical contact resistance (R e) and substrate thermal resistance (R t) on the cooling performance, Eq. (2) can be rewritten as, where the updated figure of merit (Z d) is given by Eq. (6), where ρ e is the electrical contact resistivity. In Eq. (6), it is assumed that the leg lengths (L) and cross-sectional areas of the n-type and p-type are identical.

---

### Guidelines for performing a comprehensive transthoracic echocardiographic examination in adults: recommendations from the American Society of Echocardiography [^dda85ed8]. Journal of the American Society of Echocardiography (2019). High credibility.

Left atrial (LA) volume — Two-dimensional LA images should be independently obtained and optimized; maximum volume at end-systole is identified, A4C and A2C endocardial borders are traced excluding atrial appendage and pulmonary veins, LA length is measured in both views from the center of the mitral annulus to the inner edge of the furthest traced superior wall, the long-axis lengths should be within 5 mm of each other (otherwise the apical images should be reevaluated), and most systems calculate biplane volume using area-length and biplane disk summation where the shorter length is used for area-length and the longer length for method of disks, which is the preferred method, with laboratories advised to consistently use the same technique.

---

### Exact, time-dependent analytical equations for spiral trajectories and matching gradient and density-correction waveforms [^a4c9208e]. Magnetic Resonance in Medicine (2026). Medium credibility.

2.7 Moment nulling trapezoids

Designing a pair of trapezoids to null zeroth and first moments of a single gradient waveform is common; for spiral imaging, the design of "vector" trapezoid pairs that are played out in both in‐plane directions and are freely rotatable under gradient constraints has not been shown to our knowledge. We have developed a fast algorithm for joint design of this trapezoid pair, which reduces their total duration compared with those made using separate, single‐channel designs. Joint design ensures simultaneous nulling across both axes while maximizing gradient usage without exceeding system limits, resulting in more efficient and symmetric gradient waveforms. Using the notation illustrated in Figure 2, we define variables t a and t b to be the effective total duration (area divided by amplitude) of two trapezoids A and B, respectively, and the effective ramp time t r to be one‐half the actual ramp time. Defining M0 and M1 as the relative gradient moments at the end of spiral waveforms, we write matrix equations for the desired moments of the gradient waveforms and invert them, givingWe enforce these equations in the following iterative solution:

FIGURE 2
Illustration of trapezoids used for pair‐wise design of M1 and M0 nulling with full rotational compatibility.

Step 0: Initialize with t ra = t rb = 0.5*Gmax/Smax, t a = 2 t ra, t b = t rb.

Step 1: Solve for gradient amplitudes, using Equations (19) and (20).

Step 2: Normalize A and B vector gradient amplitudes separately by factorsand, respectively.

Step 3: Solve for new trapezoid durations, using Equation (21).

Iterating these 3 steps converges on a solution quickly. One can modify this approach routine (see code) to account for nontrapezoid (triangular) waveforms.

---

### A bioinspired multilegged soft millirobot that functions in both dry and wet conditions [^4a199c93]. Nature Communications (2018). Medium credibility.

Fig. 4
Demonstration of robot locomotion at harsh environment. a Locomotion on wet surface with liquid film. The robot can move with an average speed of 0.5 mm/s on wet surface under a drive frequency of 1 Hz owing to its small contact area to underlying substrate and hydrophobic tapered feet. b Robot locomotion with a loading 100 times of its own weight. In this condition, the robot can move 8 mm in 45 s. c Cross a steep obstacle with height ∼10 times higher of its own leg. The robot's posture can be easily adjusted to climb obstacles as a result of the discontinuous flap-wave mode and continuous inverted-pendulum motion locomotion mode. d Comparison of the normalized speed between the soft robot and other animals. A dimensionless number V l, i.e. the locomotion distance in one second relative to the lower limb (leg or foot) length, is defined to quantify the locomotion efficiency of various living organisms. The maximum velocities of human and cheetah are 10.4 m/s and 33.3 m/s, respectively, corresponding to V l 7.4 and 33.3, respectively. In contrast, the soft robot can easily reach the maximum speed of human and cheetah at a swing frequency 3 Hz and 13 Hz, respectively. e Demonstration of drug transport in a stomach model under wet environment. The complex stomach internal structure is 1.5–6.8 mm in depth and 2.4–6.2 mm in width (2–10 orders of magnitude lager than the leg length). The robot can move 32 mm in 50 s at such a harsh in vivo simulated environment, meanwhile carrying a medical tablet (~91.4 mg) that is twice heavier than itself

---

### Mechanical dyssynchrony precedes QRS widening in ATP-sensitive K ⁺ channel-deficient dilated cardiomyopathy [^38c1408b]. Journal of the American Heart Association (2013). Low credibility.

Deconvolution of Mechanical Dyssynchrony

To dissect wall motion pathodynamics, high‐resolution speckle‐tracking echocardiography was performed prospectively post‐TAC. Specifically, disease progression was tracked within K ATP channel–knockout cohorts that survived > 1 month post‐TAC and whose speckle‐based strain was successfully analyzed in all 24 segments of the cardiomyopathic ventricles throughout follow‐up (n = 15 at 2 weeks, n = 8 at 1.5 months, and n = 5 at 3 months post‐TAC). Temporal and spatial disparity were 2‐dimensionally deconvoluted in strain/R‐R interval maps (6 segments in Figure 3, 48 points in Figure 4 A), and peak strain/anatomical maps (Figure 4 B through 4 D), respectively. Additionally, 3‐dimensional plots provided a comprehensive dataset of all sampling points throughout cardiac cycles (Figure 4 E through 4 G). Before stress imposition, the strain/R‐R interval map revealed a singular isosceles triangle–shaped peak, representing synchronous wall motion (Figure 3 A). Poststress, K ATP channel–deficient cardiomyopathic hearts were characterized by reduced shortening and varying amplitude, timing, and direction of wall motion, resulting in anisotropy underlying irregular ventricular contraction (Figure 3 B through 3 D). Intraventricular delay (yellow arrows in Figure 4 A) and conflicting motion (blues areas in Figure 4 A) were progressively exaggerated during follow‐up. In mid‐ventricular short‐axis view, peak strain was > 30% in all sampling points prestress and decreased to < 15% in 3 of 6 segments at 3 months poststress (Figure 4 B through 4 G). Peak radial strains progressively decreased (Figures 3 and 4). Similarly, longitudinal systolic strain declined as cardiomyopathy advanced, demonstrating a correlation with established parameters of cardiac dilatation (ie, LV end‐diastolic dimension, r = 0.79; Figure 5 A) and reduced ejection fraction (r = 0.89; Figure 5 B). At 3 months poststress, peak systolic strain persistently declined in longitudinal (P < 0.0001; Figure 5 C), circumferential (P < 0.0001; Figure 5 C), and long‐axis or short‐axis radial (P < 0.0001; Figure 5 D) directions. Beyond overall changes (Figure 5), the strain map revealed that myocardial dysfunction occurred inhomogeneously within the K ATP channel–deficient ventricle (Figure 4 D and 4 G), not manifested in 2‐dimensional or M‐mode echocardiography. The interventricular septal wall was resilient (Figure 6), maintaining prestress values in peak systole (pre‐TAC 30.3 ± 2.7%, 3 months post‐TAC 22.1 ± 2.2%; P = 0.07; Figure 6 A and 6 B) and in time‐to‐peak strain (pre‐TAC 67.8 ± 3.7 ms, 3 months post‐TAC 63.7 ± 6.1 ms; P = 0.58; Figure 6 C and 6 D). Conversely, the lateral wall developed severe hypokinesis with maximum delay, demonstrating vulnerability to mechanical malfunction and significant conduction abnormality (peak strain: pre‐TAC 45.8 ± 4.8%, 3 months post‐TAC 14.0 ± 1.4%; P < 0.01; Figure 6 A and 6 B; time‐to‐peak strain: pre‐TAC 63.4 ± 3.1 ms, 3 months post‐TAC 87.5 ± 6.5 ms P < 0.01; Figure 6 C and 6 D). Speckle‐based strain analysis thus unmasked vulnerable areas of contractile defect that generate mechanical dyssynchrony in K ATP channel–deficient stress‐vulnerable hearts.

---

### Quantitative imaging metrics for the assessment of pulmonary pathophysiology: an official American Thoracic Society and Fleischner society joint workshop report [^6517cbfd]. Annals of the American Thoracic Society (2023). High credibility.

Basic stereological measurements — first-order parameters and probes identify that "First-order parameters are volume (three-dimensional [3D]), surface (two-dimensional [2D]), length (one-dimensional [1D]), and number (zero-dimensional [0D])". Measurements "are performed using geometric test probes, such as points (0D), lines (1D), planes (2D), or volumes (3D)". These probes create countable events in the image, and "Raw counts provide ratios… that are multiplied by the reference space volume to obtain absolute measures for the lung or subcompartment".

---

### A non-spatial account of place and grid cells based on clustering models of concept learning [^7c3febb5]. Nature Communications (2019). High credibility.

Due to the asymmetrical shape of the trapezoid environment, the procedure for generating a movement trajectory above leads to a slightly biased sampling of the wide part of the trapezoid, and less exploration of the middle and top parts of the shape. To deal with this, we made a slight change to the possible steps after generating a step that brings the agent out of the environment, described below. For each trial, the step was generated as before. If the generated step was out of the environment, the step was cancelled, and the next step was determined as follows. If the step generated would have brought the agent out of the bottom of the trapezoid, the next step was sampled from [0, 0, 1, 1] (stay or up). If the step brings the agent out to the top, the next step was sampled from [−1, −1, 0, 0] (down or stay). When the step takes the agent out of the left of the trapezoid, then the next step to be sampled on the horizontal axis were [0, 1, 1, 2, 4], towards the inner portion of the environment. If the step took the agent out of the right side of the trapezoid, the next step was generated as before, from [−4, −2, −1, −1, 0, 1, 1, 2, 4]. This is because when the agent is out of the trapezoid on the horizontal (left-right) axis, the agent could still be in the middle of the shape on the vertical axis, since the shape becomes more narrow as it reaches the right. Finally, when it lands exactly in the middle of the horizontal axis, but is out of the shape (on the horizontal axis), the next step to be sampled from on the vertical axis is [−1, 0, 1].

Reporting summary

Further information on research design is available in the Nature Research Reporting Summary linked to this article.

---

### High performance magnesium-based plastic semiconductors for flexible thermoelectrics [^91d5d607]. Nature Communications (2024). High credibility.

Fig. 4
The in-plane and out-of-plane TE modules of Mg 3 Sb 2- x Bi x.

The fabricated (a) in-plane and (b) out-of-plane TE module based on Mg 3 Sb 0.5 Bi 1.498 Te 0.002 with its schematics on the left; the output voltage V and power density P / A of (c) in-plane and (d) out-of-plane TE modules. The temperature value is the temperature difference of the module Δ T module.

The in-plane TE module consists of nine n-type Mg 3 Sb 0.5 Bi 1.498 Te 0.002 legs, exhibiting a maximum output voltage V of ~6.2 mV and a maximum power density P / A of ~0.24 μW·cm −2 when the measured temperature difference of the module Δ T module is ~5.6 K (Fig. 4c), where the P is the output power, A is the area of the TE module. Considering the length of the TE legs L, the obtained normalized power density P × L / A of this in-plane TE module reaches 14.4 μW·m −1, significantly surpassing that of PEDOT and Poly[A x (M-ett)]-based organic flexible TE modules. However, compared to the state-of-art in-plane flexible TE modules based on Ag 2 S 0.5 Se 0.5, the performance of this Mg 3 Sb 0.5 Bi 1.498 Te 0.002 flexible TE module is relatively inferior, primarily due to the substantial internal resistance, about 27 Ω in Mg 3 Sb 2- x Bi x against 9 Ω in Ag 2 S 0.5 Se 0.5. The high internal resistance in Mg 3 Sb 0.5 Bi 1.498 Te 0.002 flexible TE module arises from the significant contact resistance between Mg 3 Sb 0.5 Bi 1.498 Te 0.002 and electrodes. As shown in Supplementary Fig. 15, the contact resistance between Mg 3 Sb 0.5 Bi 1.498 Te 0.002 and Cu electrode is very high, of about 3500 μΩ·cm 2. Given the excellent room-temperature zT of plastic Mg 3 Sb 0.5 Bi 1.498 Te 0.002, the reduction of the interfacial resistance of the flexible TE module holds the promise of substantially enhanced performance and fosters future applications in flexible electronics.

---

### Diagnosis and management of Barrett esophagus: European Society of Gastrointestinal Endoscopy (ESGE) guideline [^579dc464]. Endoscopy (2023). High credibility.

Regarding follow-up and surveillance for Barrett's esophagus, more specifically with respect to surveillance endoscopy, intervals, ESGE 2023 guidelines recommend to consider using varying surveillance intervals for different BE lengths:

| **Situation** | **Guidance** |
|-|-|
|Maximum extent of ≥ 1 cm and < 3 cm|- Every 5 years|
|Maximum extent of ≥ 3 cm and < 10 cm|- Every 3 years|
|Maximum extent of ≥ 10 cm|- Refer patients to an expert center|
|Irregular Z-line/columnar-lined esophagus of < 1 cm|- Do not obtain endoscopic surveillance or routine biopsies.|

---

### AIUM practice parameter for the performance of detailed diagnostic obstetric ultrasound examinations between 12 Weeks 0 Days and 13 Weeks 6 Days [^cd3ffc0d]. Journal of Ultrasound in Medicine (2021). High credibility.

Method of measuring CRL between 12 Weeks 0 Days and 13 Weeks 6 Days — key technique steps: "Fetus fills at least two-thirds of the image space available", and "The long axis of the fetus should be perpendicular to the ultrasound beam". The fetus "should be in the midsagittal position with the profile, spine, and rump visible. The entire CRL should be visible". It "should be in a neutral position with fluid between the chin and anterior neck. The fetus should not be hyperextended (the angle between the chin and anterior neck should not be > 90°)". Calipers: "The caliper crossbars should be placed on the outer border of the skin on the fetal head and rump. The caudal caliper should not be on the distal spine or posterior thigh or include the limbs". Measurement and reporting: "The maximum length of the fetus from the cranial to caudal calipers should be measured in a straight line, parallel to the long axis of the fetus", and "The numeric value is reported as the mean of 3 acceptable measurements".

---

### A non-spatial account of place and grid cells based on clustering models of concept learning [^59af4302]. Nature Communications (2019). High credibility.

Gridness in trapezoid environments

To simulate the effect of asymmetric boundaries in a trapezoid enclosure on gridness, we took cluster positions from simulations after learning in square environments, and ran an additional learning phase for 250,000 trials. In this new learning phase, the shape of the environment was now a trapezoid (the agent could only move to those locations), and the annealed learning rate schedule continued (starting at 0.0025, reducing to 0.002 at the end). The trapezoid dimensions were 5 × 24 × 50 pixels, closely matching the proportions in(0.2 × 0.9 × 1.9 meters; multiplied by (50/1.9) equals to 5.26, 23.7, and 50).

In order to test whether the asymmetric boundaries of the trapezoid affected gridness, the trapezoid was split into two halves and we computed the grid score for the spatial autocorrelogram on the left (wide) and right (narrow) side of the shape. Due to discretization, we split it as close to equal as possible. The wide half extended from the leftmost pixels to the 17th pixel (338 pixels), and the narrow side extended from the 18th pixel to the 50th pixel (339 pixels).

---

### Long-term passive leg stretch improves systemic vascular responsiveness as much as single-leg exercise training [^ce047d09]. Medicine and Science in Sports and Exercise (2022). Medium credibility.

Single passive limb movement

Single passive limb movement was performed by the recommended procedures. Sitting on a chair, subjects rested in the upright-seated position for 10 min before starting the data collection and remained in this position until the end of the test. The sPLM protocol consisted of 60 s of baseline peripheral hemodynamic data collection, followed by single passive knee flexion and extension of 1 s, after which the leg was kept fully extended for the remaining 59 s for the postmovement data collection. sPLM was performed by a member of the research team, who moved the subject's lower leg through a 90° ROM at 1 Hz. Throughout the test, measurements of arterial blood velocity and vessel diameter were performed in the common femoral artery of the passively moved leg, distal to the inguinal ligament and proximal to the deep and superficial femoral bifurcation by Doppler ultrasound (mod. Logiq-7; General Electric Medical Systems). After being positioned to an insonation angle of 60° or less, a 9-MHz linear array transducer was used to measure the mean blood velocity. The sample volume was centered and size-maximized according to the vessel's diameter. Femoral artery Q ˙ (Q ˙ fem) was calculated by using data of arterial diameter and mean blood velocity as:

Q ˙ (mL·min −1) = mean blood velocity × π × (diameter / 2)² × 60

The cumulative Q ˙ fem was integrated (area under the curve [AUC]) using the trapezoidal rule and then calculated. Reliability analysis for sPLM was previously reported.

Before the sPLM, the systolic and diastolic arterial pressure was measured at rest by a digital sphygmomanometer (mod. HEM-907; Omron, Hoofddorp, The Netherlands). The mean arterial pressure (MAP) was therefore calculated.

---

### Area available for atrial fibrillation to propagate is an important determinant of recurrence after ablation [^6a58f173]. JACC: Clinical Electrophysiology (2021). Medium credibility.

Objectives

This study sought to evaluate atrial fibrillation (AF) ablation outcomes based on scar patterns and contiguous area available for AF wavefronts to propagate.

Background

The relevance of ablation scar pattern acting as a barrier for electrical propagation in recurrence after catheter ablation for persistent AF is unknown.

Methods

Three-month post-ablation atrial cardiac magnetic resonance was used to determine post-ablation scar. The left atrium (LA) was divided into 5 areas based on anatomical landmarks and scar patterns. The length of gaps in scar on the area boundaries was used to calculate fibrillatory areas (FAs) by adding the weighted contribution of adjacent areas. Cylindrical as well as patient-specific computational models were used to further confirm findings.

Results

A total of 75 patients that underwent an initial ablation for AF with 2 years of follow-up were included. The average maximum FA was 7,896 ± 1,988 mm 2 in patients with recurrence (n = 40) and 6,559 ± 1,784 mm 2 in patients without recurrence (n = 35) (p < 0.008). After redo ablation in 19 patients with recurrence, average maximum FA was 7,807 ± 1,392 mm 2 in 9 patients with recurrence and 5,030 ± 1,765 mm 2 in 10 without recurrence (p < 0.007). LA volume and total scar were not significant predictors of recurrence after the first ablation. In the cylindrical model, AF self-terminated after reducing the FAs. In the patient-specific models, simulation matched the clinical outcomes with larger FAs associated with post-ablation arrhythmia recurrences.

Conclusions

This data provides mechanistic insights into AF recurrence, suggesting that post-ablation scar pattern dividing the atria into smaller regions is an important and better predictor than LA volume and total scar, with improved long-term outcomes in persistent AF.

---

### Quantitative imaging metrics for the assessment of pulmonary pathophysiology: an official American Thoracic Society and Fleischner society joint workshop report [^7e0b2d1d]. Annals of the American Thoracic Society (2023). High credibility.

Basic stereological measurements for lung imaging — first-order parameters, probes, and reference space are specified. First-order parameters are volume (three-dimensional [3D]), surface (two-dimensional [2D]), length (one-dimensional [1D]), and number (zero-dimensional [0D]). Measurements are performed using geometric test probes, such as points (0D), lines (1D), planes (2D), or volumes (3D), with probe–voxel interactions generating countable events; raw counts yield ratios that are multiplied by the reference space volume to obtain absolute lung or subcompartment measures. It is crucial to define and measure a biologically meaningful reference space for analysis and reporting, because measurements expressed only as ratios are subject to "the reference trap", where changes can arise from the numerator, denominator, or both; an efficient volume measurement method, point counting, is used for acinar components by micro-CT and for extrapulmonary organ volume by CT.

---

### Recommendations for quantification methods during the performance of a pediatric echocardiogram: a report from the pediatric measurements writing group of the American Society of Echocardiography pediatric and congenital heart disease council [^75701799]. Journal of the American Society of Echocardiography (2010). Medium credibility.

Pediatric quantification protocols — pulmonary veins, systemic veins, and atria — advise that the pulmonary veins are usually best evaluated in a high left parasternal or suprasternal short‑axis view ("crab" view) and that the left atrial (LA) appendage should not be mistakenly identified as the left upper pulmonary vein and the right middle pulmonary vein should not be mistakenly identified as the right upper pulmonary vein; subxiphoid short‑axis or right parasternal views are usually better at displaying the right upper pulmonary vein. The superior vena cava is not routinely measured in clinical practice, and normative data have not been established, whereas inferior vena cava (IVC) size can be measured above its junction with the hepatic veins just below the diaphragm in subxiphoid short‑axis views (displaying the IVC long axis), and this may help assess hydration status. The IVC diameter varies with respiration, and the collapsibility index (the percentage decrease in IVC diameter with inspiration) appears to correlate with right atrial (RA) pressures in adults, but neither the IVC diameter nor the collapsibility index appears to correlate with age or BSA in adult patients, and the utility of the collapsibility index in children has not been evaluated. Left atrial size can be assessed by M‑mode and 2D measurements of the distance from the posterior aortic wall to the posterior LA wall, though this anteroposterior distance correlates poorly with angiographically derived LA volumes; recent recommendations involve calculation of LA volumes from apical views at end‑systole just before the MV opens using major‑axis and minor‑axis dimensions and planimetered areas in orthogonal views. Among LA volume calculations, the biplane area‑length and the biplane Simpson (summation of disks) methods using apical 4‑chamber and 2‑chamber views appear to provide the most consistent results with published reference values for normal adults; the biplane area‑length method has also been used in children, and LA volumes indexed to BSA appear to correlate with diastolic function and mitral regurgitation grade. Real‑time three‑dimensional echocardiography with a rotation/polyhedral‑based algorithm has correlated well with LA volumes measured by magnetic resonance imaging, and right atrial size is usually assessed in an apical 4‑chamber view at end‑systole just before the TV opens.

---

### Two-edge-resolved three-dimensional non-line-of-sight imaging with an ordinary camera [^4fae72db]. Nature Communications (2024). High credibility.

Through simple geometric calculations, the azimuth and elevation angles of a hidden scene point can be estimated from the slope and height of the illuminated right trapezoidal region of the observation. However, spatially extended hidden scenes do not create sharp shadows. They instead produce a superposition thereof, that is dependent on the geometry of the scene from the vantage of the observed ceiling portion, appearing as a region of highly informative penumbra(see Fig. 2 a for an example photograph of penumbra). The penumbra region encodes information about the geometry of the hidden scene from the perspective of the ceiling, along two dimensions (i.e. in azimuth and elevation angles). Efficiently extracting this information for reconstructing a general spatially extended scene is achievable through a computational algorithm presented later on.

Fig. 2
Two-step reconstruction procedure.

a Measured penumbra photograph. b A linear inverse problem (LIP) is solved, per colour channel, to recover the azimuth and projected-elevation representation (i.e. the shapes) of hidden scene objects, with the entire hidden scene assumed to be confined to a single fixed range. c Colour visualisation of the initial angular reconstruction. d The reconstruction is analysed for connected surface elements which most likely belong to the same cluster. Four such clusters were identified, one for each of the three objects and a fourth (bottom right) for spurious elements. e A non-linear inverse problem (NLIP) is solved to estimate four ranges and four global radiosities, one for each cluster identified in (d). f Multiple views of the 3D colour reconstruction produced by incorporating the estimated ranges and solving a resulting total-variation-regularised LIP to obtain smoother estimates; a 3D view (second column), plan view (first column, top) and side view (first column, bottom) of the final reconstruction. (Best viewed in colour. The reconstruction procedure is also explained in Supplementary Movie 1).

---

### The force-velocity profile for jumping: what It is and what It is not [^4e662000]. Medicine and Science in Sports and Exercise (2023). Medium credibility.

Model C: four segments actuated by six Hill-type muscle–tendon complexes

Model C (Fig. 7 A) comprised four body segments, actuated by six lumped muscle–tendon complexes of the human lower extremity. Each muscle–tendon complex was represented by a Hill-type unit, comprising a contractile element, a series elastic element, and a parallel elastic element. Forces of the elastic elements quadratically increased with elongation, whereas force of the contractile element depended on length and velocity of the contractile element, and active state. Active state, in turn, dynamically depended on muscle stimulation over time (STIM(t)). Initial STIM levels were set such that the model was in equilibrium in the starting position. During the jump, STIM of each muscle–tendon complex was allowed to change from the initial level to the maximum level of 1 at a rate of 5·s −1, and this increase started at a STIM onset time. For a vertical jump, the combination of STIM onset times that maximized the height achieved by the center of mass was found using a genetic algorithm. For an isokinetic lower extremity extension, the toes were moved away from the hip at a constant velocity, and the combination of STIM onset times that maximized the work done on the toes was found.

FIGURE 2
Model A1 and its force–velocity profile. A, Model A1 consists of a mass projected by a linearly damped force (inset). m, total mass (82 kg); b, coefficient of linear damping; h, height of the center of mass; F, force of the actuator; v, velocity of the actuator. The intrinsic force–velocity relationship of the actuator was F = F 0 − b v, where isometric force F 0 was 3400 N and b was 700 N·s·m −1. B, Force–velocity profile of the model obtained by plotting effective work per unit push-off distance as a function of half the takeoff velocity (see Fig. 1). The force–velocity profile differs from the intrinsic relationship of the model. The latter is obtained by having the model extend isokinetically at different velocities. During the unloaded jump, less effective work is produced than during an isokinetic extension at the same average velocity (vertical dashed line). The same effective work as during the unloaded jump can be produced during an isokinetic extension at a higher velocity (solid arrow).

RESULTS

---

### Simultaneous multiple resonance frequency imaging (SMURF): fat-water imaging using multi-band principles [^15ac8589]. Magnetic Resonance in Medicine (2021). Medium credibility.

2.1 SMURF excitation

In 2D and slab‐selective 3D acquisitions, in which a gradient is applied during the radiofrequency (RF) excitation to achieve slice/slab selection, spatial‐spectral pulses 25 are required for SMURF imaging. Using the small tip‐angle approximation and the concept of excitation k‐space outlined by Pauly, 31 the transversal magnetization M xy excited by a spatial‐spectral pulse B SS (t) of duration T is defined as

where M 0 is the initial magnetization,

where G z is the slice‐selective gradient, and

Spatial‐spectral pulses comprise a train of short subpulses modulated by a temporal weighting function (Figure 2A). The concurrently applied G z typically consists of a series of short trapezoids of alternating polarity (Figure 2B), the duration of which (T z) determines the separation between the excited and suppressed frequencies (f s) (Figure 2E), as well as the frequencies of inherent periodic replicates. 25 The spatial excitation profile is thus determined by the Fourier transform of the subpulses and the spectral excitation profile is determined by the Fourier transform of the temporal weighting function. To use the acquisition time and applied gradients most efficiently, the subpulses can be applied during both positive and negative phases of the G z (true null design), and also during gradient ramping. The duration of the gradient sublobes has to be chosen such that the frequencies of periodic replicates and the suppressed frequencies, for the true null design given by

FIGURE 2
Dual‐band spatial‐spectral pulse used for 90° excitation in 2D TSE‐SMURF imaging. A, RF waveform created by a train of sinc subpulses modulated by a dual‐band envelope. B, Waveform of the oscillating trapezoidal z‐gradient played concurrently with the RF pulse for slice‐selection. Excitation profile of the RF pulse, comprising two frequency bands offset by 440 Hz, shown as a function of the position along the slice‐selection direction (C), the Larmor frequency (D), and the Larmor frequency and position along the slice‐selection direction (E).

do not impair the desired spectral excitation profile. To allow the longest T z (maximal G z area) and hence, the minimum slice thickness, f s, should be equal to the chemical shift difference. In SMURF fat‐water imaging at 3 T, this requires a sublobe duration of about 0.56 ms.

---

### Standards of care in diabetes – 2025 [^31be65a6]. Diabetes Care (2025). High credibility.

Regarding diagnostic investigations for hypoglycemia, more specifically with respect to screening for cognitive impairment, ADA 2025 guidelines recommend to simplify diabetes treatment plans as much as possible for patients with cognitive impairment and tailor to minimize the risk of hypoglycemia.

---

### Miniaturized MgBi-based thermoelectric cooler for localized electronic thermal management [^6dfd927e]. Nature Communications (2025). High credibility.

Experimentally, a Mg 2 Ni layer was fabricated on Mg 3 Bi 2- x Sb x through a sintering process, followed by the deposition of a Cu thin film onto the Mg 2 Ni layer using the sputtering technique, i.e. Mg 3.2 Bi 1.497 Sb 0.5 Te 0.003 /Mg 2 Ni/Cu film. The contact layer structure is shown in Fig. 2a. The impact of contact layer thickness on the cooling performance has been investigated through finite element simulations. The results indicate that a thinner contact layer favors the optimal leg cross-sectional ratio between the n-type and p-type thermoelectric legs (A n / A p) approaching unity (Fig. 2b). This not only benefits the processing of the thermoelectric legs but also contributes to obtaining a higher cooling power density. On the other hand, based on the optimal leg cross-sectional area ratio, the disparities in Δ T max due to different contact layer designs are compared in Fig. 2c. As the leg length decreases, a thinner contact layer can result in an improved Δ T max, and a similar trend is also reflected in maximum cooling power (Supplementary Fig. 3). Considering the significant impact of contact layer thickness on the performance of miniaturized coolers, sputtering is employed to fabricate the metallization layer.

Fig. 2
The design of n-type Mg 3.2 Bi 1.497 Sb 0.5 Te 0.003 thermoelectric leg.

a Schematic view of the leg structure, including pre-circuited AlN ceramic plate, Cu electrode, Sn 42 Bi 58 solder, sputtered Cu layer, Mg 2 Ni contact layer, and Mg 3 Bi 2 -based materials. b Simulated maximum temperature difference as a function of the cross-section area ratio of the n- and p-type legs (A n / A p) with different contact layer thicknesses. c Simulated maximum temperature difference as a function of the leg lengths with different contact layer thicknesses. d Scanning electron microscopy image of the Mg 3.2 Bi 1.497 Sb 0.5 Te 0.003 /Mg 2 Ni/Cu film/Sn-Bi solder/Cu electrode junction, the corresponding EDX mapping, and the interfacial electrical contact resistance.

---

### Elacestrant (Orserdu) [^25e5bc7d]. FDA (2024). Medium credibility.

The dosage of elacestrant PO for treatment of breast cancer in postmenopausal female adults with ESR1 mutation (advanced or metastatic, ER-positive, HER2-negative, progression after ≥ 1 line of endocrine therapy) is 345 mg PO daily until disease progression or unacceptable toxicity

---

### Retrospective measurement of different size parameters of non-radiated rectal cancer on MR images and pathology slides and their comparison [^b0df7a62]. European Radiology (2003). Low credibility.

There are no non-invasive methods to assess the real tumor size in rectal cancer prior to surgery, especially following radio/chemotherapy. Magnetic resonance imaging is gaining increasing acceptance as the primary modality at many centers for evaluation of pelvic malignancies including rectal cancers. The aim of this study was to evaluate if the tumor size as assessed by stereological or metric means on MRI correlates to the corresponding pathologic findings. To our knowledge, no such previous work has been reported in the literature. From the Cancer Register Center, 18 patients in the age range of 39–90 years with rectal cancer who had complete preoperative MR with subsequent giant section pathological examinations of the resected bowel were included. The tumor size was measured on MR and histopathologic specimen using both a stereologic and a metric mode. The measured parameters included the maximum transverse area occupied by the tumor, thickness, width, and the length of tumor and the volume of the tumor measured in two different fashions by the product of area and length (al) or the product of thickness, width, and length (twl). The depth of tumor infiltration (T) and presence of local lymph node metastases (N) were also separately evaluated on the histopathologic specimen. There were 1, 4, 12, and 1 patients with tumor stages T1, T2, T3, and T4, respectively. The mean thickness, width, length, area, and volumes, al and twl, were 1.62, 2.8, and 4.78 cm, and 4.72 cm2, 26.29 cm3, and 20.07 cm3, respectively. Regression curves were drawn for above-mentioned parameters. They showed some correlation with square correlation coefficient measuring between 0.38 and 0.82. The best correlation was seen for area (0.75) and volume measured by the product of area and length of the tumor (0.82). With the formula proposed from this material, we assume that rectal tumors can be measured on MR images using a metric model, especially area and the volume (the product of area and length), and then extrapolated to what we would expect from pathology, hence providing us with a tool where we could measure tumor response after neoadjuvant therapy.

---

### Halobetasol propionate [^a8fb7e2a]. FDA (2024). Medium credibility.

The dosage of halobetasol propionate TOP for treatment of plaque psoriasis in adults is 1 thin layer TOP BID for up to 2 weeks (0.05% foam)

---

### Miniaturized MgBi-based thermoelectric cooler for localized electronic thermal management [^59a50398]. Nature Communications (2025). High credibility.

Discussion

To sum up, we report the miniaturization of the Mg 3 Bi 2 -based thermoelectric coolers, including optimization of the thermoelectric leg length, interfacial electrical contact resistance, the thermal conductivity of the ceramic substrate, and contact layer design. The n-type thermoelectric legs with a copper layer (< 3 μm), a Mg 2 Ni layer (50 μm), and an Mg 3 (Bi, Sb) 2 layer (900 μm), with a cross-sectional area of 1.0 × 1.0 mm 2 were prepared. The contact resistivity of the n-type thermoelectric joint was only 1 μΩ cm 2, and AlN was selected as the substrate material to minimize the thermal resistance. At a hot-side temperature of 300 K, this miniscale cooler achieved a maximum cooling temperature difference of ~ 59.0 K and a cooling power density of ~ 5.7 W cm −2. At 350 K, these values increased to ~ 81.2 K and ~ 7.4 W cm −2, outperforming the state-of-the-art Mg 3 Bi 2 -based coolers. The Mg 3.2 Bi 1.497 Sb 0.5 Te 0.003 /Bi 0.4 Sb 1.6 Te 3 miniscale cooler achieved the time constants of ~ 1.8 s, ~ 12 s, and ~ 30 s and maximum cooling speeds of ~ 65 K s −1, ~30 K s −1, and ~20 K s −1 under the thermal capacitances of 0.0 J K −1, 0.27 J K −1, and 0.80 J K −1, respectively. After 270 h of continuous operation (approximately 3000 cycles), the cooler maintains its original cooling performance. In addition, this miniscale cooler was used to successfully achieve the localized cooling of the CPU in the microcontroller. Our results demonstrate that the miniaturized Mg 3 Bi 2 -based coolers are promising for localized electronic thermal management.

---

### 2024 American College of Rheumatology (ACR) guideline for the screening, treatment, and management of lupus nephritis [^676d755a]. Arthritis Care & Research (2025). High credibility.

Regarding diagnostic investigations for lupus nephritis, more specifically with respect to initial evaluation, ACR 2025 guidelines recommend to obtain a thorough evaluation to exclude alternative etiologies of kidney dysfunction in patients with SLE, including non-inflammatory causes such as hypertensive, diabetic, and medication-induced nephropathy.

---

### Clobetasol propionate (Clobex) [^896f1644]. FDA (2024). Medium credibility.

The dosage of clobetasol propionate TOP for treatment of plaque psoriasis in adults (mild-to-moderate) is:

- **Maintenance**: 1 application(s) TOP BID for up to 2 weeks (foam)
- **Maximum**: for 50 g per week of cumulative use

---

### 2018 ESC guidelines for the diagnosis and management of syncope [^d327125d]. European Heart Journal (2018). Medium credibility.

Regarding screening and diagnosis for syncope, more specifically with respect to diagnostic criteria (situational syncope), ESC 2018 guidelines recommend to suspect situational reflex syncope with high probability in patients with syncope occurring during or immediately after specific triggers.

---

### Recommendations for cardiac chamber quantification by echocardiography in adults: an update from the American Society of Echocardiography and the European association of cardiovascular imaging [^79b1194c]. Journal of the American Society of Echocardiography (2015). Medium credibility.

Echocardiographic assessment of right atrial (RA) size — volume by 2D describes that "2D volumetric measurements are usually based on tracings of the blood-tissue interface on the apical four-chamber view" and that "At the tricuspid valve level, the contour is closed by connecting the two opposite sections of the tricuspid ring with a straight line". It adds, "Volumes can be computed by using either the single plane area-length" or "the disks summation technique", performed in a "2D view". The listed advantage is "More representative of actual RA size than linear dimensions", while limitations include "Assumes a symmetrical shape of the cavity", "Single plane volume calculation may be inaccurate since it assumes that RA enlargement is symmetrical", and "Normal values not well established".

---

### Age-and step-length-dependent alterations in muscle synergies and joint coordination during unexpected gait termination [^2e7053dc]. BMC Geriatrics (2025). Medium credibility.

CoP & com metrics

All CoP data were analyzed over the 1-s stopping phase (foot-strike to 1 s) at 1,000 Hz.

CoP path length

(xi, yi) is the CoP coordinates at sample i, i = 1, …, N (N = 1000).

CoP mean velocity

was calculated by:

CoP 95% confidence ellipse area

The 2 × 2 covariance matrix Σ was computed from the CoP data set of stepping leg. The area of the 95% confidence ellipse was given by:

CoM acceleration SD

Whole-body CoM anterior-posterior x (t), medio-lateral y (t), and vertical displacement z (t) was reconstructed via a linked-segment model from marker data (Plug-in Gait model in Nexus software). CoM acceleration a x (t), a y (t), a z (t) were obtained by twice differentiating time (displacement-velocity-acceleration) (filtered at 6 Hz). Its standard deviation over the 1 s phase quantifies postural sway variability:

Joint coordination metrics during the stopping phase

To evaluate inter-joint coordination during the 1-second stopping phase, we computed both temporal coupling and timing variability metrics across three joint pairs: ankle–knee, knee–hip, and ankle–hip. Analyses were based on X-axis (anterior-posterior, Flexion-Extension) joint angles.

Cross-correlation and full width at half maximum (FWHM)

To assess temporal synchrony between joints, normalized cross-correlation functions were computed between each joint-pair angle time series:

Where x t and y t ​ are joint angle signals, and are their means, σ x and σ y​ their standard deviations, and τ the lag in milliseconds (within ± 500ms).

To quantify the duration of strong coupling, we computed the Full Width at Half Maximum (FWHM) of the cross-correlation curve:

where "I" is the indicator function and "fs" is the sampling frequency (Hz).

For each joint-pair moment (ankle–knee, knee–hip, ankle–hip), FWHM was defined as the duration, within the 1-second stopping phase, during which the moment magnitude remained greater than or equal to 50% of its peak value. A smaller FWHM indicates sharper synchrony ("tight V-shape") whereas larger values suggest broader, less precise coordination.

---

### Polyply; a python suite for facilitating simulations of macromolecules and nanomaterials [^a4f86113]. Nature Communications (2022). High credibility.

Step 4: Constrained random walk

To generate coordinates for the one bead per residue molecules in our target system, we perform a self-excluding random walk. An attempt to place a bead (step) in the random walk is rejected, if a maximum force on the placed bead is exceeded. The self-excluding random walk is by default performed along a breadth-first traversal of the molecular graph. This means nodes (i.e. residues) that are close to each other are placed first and then the algorithm proceeds further along the chain. Molecules are placed separately after each other, where the starting point is randomly chosen from a grid.

This grid can either be user-specified or is considered to be rectangular across the box. When the random-walk algorithm exceeds a certain number of steps, it goes backward in the breadth-first path by default by ten residues and tries to replace these ten residues. In addition to the force-acceptance criterion, the random-walk can also be supplemented with three additional conditions which help steer overall conformations: (1) geometrical constraints can be set to define regions of space that are excluded from sampling; (2) dimension constraints can be specified to limit the random walk dimension along specific vectors to for example create brushes on surfaces; (3) distance restraints can be set to define target distances between specific nodes within a molecule. To meet the distance restraints, polyply implements a graph-based algorithm that puts upper and lower bounds on each step taken. Details and benchmarking are provided in Supplementary Fig. 2 and Supplementary Note 4, subsection 2. All additional conditions have to be specified in a build file. The file syntax for the build file is available online. Furthermore, to generate starting structures for polymers with high persistence lengths, polyply implements a feature that lets the user set a persistence length. Subsequently, the program samples from the end-to-end distance distribution of the worm-like chain model and use the distance restraint algorithm to set the end-to-end distance (see Supplementary Note 3 for more details). All interactions are computed considering rectangular periodic boundary conditions using the scipy c-implementation of the KD-tree. Using a KD-tree makes it possible to compute a large number of distances within a cut-off efficiently within python.

---

### The anatomic rationale for transforaminal endoscopic interbody fusion: a cadaveric analysis [^ee8a102f]. Neurosurgical Focus (2016). Low credibility.

OBJECTIVE The authors describe a cadaveric analysis to determine the ideal dimensions and trajectory for considering endoscopic transforaminal interbody implantation. METHODS The soft tissues of 8 human cadavers were removed from L-1 to the sacrum, exposing the posterior bony elements. Facetectomies were performed bilaterally at each lumbar level with resection of the pars interarticularis, revealing the pedicles, nerve roots, and interbody disc space. Each level was digitally photographed with a marker for scale and evaluated with digital analysis software. The traversing and exiting nerve roots and pedicle margins were identified, and the distances between these structures and their relationships to the surrounding structures were documented. RESULTS The dimensions of 2 areas were measured: the working triangle and safe zone. The working triangle is the triangle between the exiting and traversing nerve roots above the superior margin of the inferior pedicle. The safe zone is the trapezoid bounded by the widths of the superior and inferior pedicles between the exiting and traversing nerve roots. The mean surface area for the working triangle was 1.83 cm(2), with L5-S1 having the largest area at 2.19 cm(2). The mean surface area of the safe zone was 1.19 cm(2), with L5-S1 having the largest area at 1.26 cm(2). At the medial border of the pedicle extending superiorly, there were no nerve structures within 1.19 cm at any level. On the lateral border of the pedicle, the exiting nerve root was closer superiorly, with the closest being 0.3 cm. CONCLUSIONS The working triangle is a relatively large area. The safe zone, just superior to the pedicle, is free of nerve structures. By utilizing the superior border of the pedicle, the disc space can be accessed within this safe zone without risk of injury to the nerves. A thorough understanding of foraminal anatomy is fundamental for considering how to safely access the disc space, thereby utilizing less invasive endoscopic techniques, and is an important first step in considering what shapes and sizes of interbody implants and retractors are feasible for use in the foramen.

---

### Prostate volume contouring: a 3D analysis of segmentation using 3DTRUS, CT, and MR [^7bb80e4d]. International Journal of Radiation Oncology, Biology, Physics (2007). Low credibility.

Purpose

This study evaluated the reproducibility and modality differences of prostate contouring after brachytherapy implant using three-dimensional (3D) transrectal ultrasound (3DTRUS), T2-weighted magnetic resonance (MR), and computed tomography (CT) imaging.

Methods and Materials

Seven blinded observers contoured 10 patients' prostates, 30 day postimplant, on 3DTRUS, MR, and CT images to assess interobserver variability. Randomized images were contoured twice by each observer. We analyzed length and volume measurements and performed a 3D analysis of intra- and intermodality variation.

Results

Average volume ratios were 1.16 for CT/MR, 0.90 for 3DTRUS/MR, and 1.30 for CT/3DTRUS. Overall contouring variability was largest for CT and similar for MR and 3DTRUS. The greatest variability of CT contours occurred at the posterior and anterior portions of the midgland. On MR, overall variability was smaller, with a maximum in the anterior region. On 3DTRUS, high variability occurred in anterior regions of the apex and base, whereas the prostate-rectum interface had the smallest variability. The shape of the prostate on MR was rounder, with the base and apex of similar size, whereas CT contours had broad, flat bases narrowing toward the apex. The average percent of surface area that was significantly different (95% confidence interval) for CT/MR was 4.1%; 3DTRUS/MR, 10.7%; and CT/3DTRUS, 6.3%. The larger variability of CT measurements made significant differences more difficult to detect.

Conclusions

The contouring of prostates on CT, MR, and 3DTRUS results in systematic differences in the locations of and variability in prostate boundary definition between modalities. MR and 3DTRUS display the smallest variability and the closest correspondence.

---

### Standards of care in diabetes – 2025 [^1f4eb314]. Diabetes Care (2025). High credibility.

Regarding diagnostic investigations for diabetes mellitus type 1, more specifically with respect to assessment for hyperglycemic crises, ADA 2025 guidelines recommend to provide structured education on the recognition, prevention, and management of hyperglycemic crisis to patients with T2DM having experienced these events and patients at high risk for these events.

---

### Colorectal cancer screening and prevention [^c270f773]. American Family Physician (2025). High credibility.

Regarding screening and diagnosis for colon cancer, more specifically with respect to indications for screening, general population, aged 76–85 years, AAFP 2025 guidelines recommend to consider obtaining screening for CRC in adults aged 76–85 years at average risk based on overall health status, prior screening history, and patient preferences.

---

### Half-heusler alloys as emerging high power density thermoelectric cooling materials [^a8ac7e9c]. Nature Communications (2023). High credibility.

Benefiting from the ultra-high PF and the decent z value near room temperature, Nb 0.55 Ta 0.40 Ti 0.05 FeSb exhibits enhanced performance compared to that of Bi 2 Te 3 -based TE materials in terms of low Δ T heat pumping. The YbAl 3 alloy with an extremely high PF of ~110 µW cm −1 K − 2 at room temperature (Fig. S 9), which is compatible with p-type Nb 0.55 Ta 0.40 Ti 0.05 FeSb, was used as the n-type counterpart to construct the uni-couple cooling device (hH-YbAl 3). Figure 4b shows the simulated cooling performance of hH-YbAl 3 device. Considering the extremely high electrical and thermal conductivity of YbAl 3, the cross-section of the YbAl 3 leg should be four times smaller than that of p-type hH to optimize the performance of the device, which makes the construction and measurement of the device extremely difficult. Thus, the cross-section ratio (A p /A n) was reduced to 1.4, leading to slightly lower performance than that of the device with optimized geometry. The measuredof the hH-YbAl 3 device at Δ T of 5 K was found to be 3.6 W cm −2 (with a leg length of 7.7 mm), which is twice that of the Bi 2 Te 3 -based device, 1.7 W cm −2, with the same leg length and Δ T (Fig. 4b, c and Fig. S 10). The maximum cooling power density of the hH-YbAl 3 device remains competitive with that of Bi 2 Te 3 -based devices up to Δ T of 20 K. Improved n-type material would be able to provide even higher performance at high Δ T. For example, a hypothetical device made using both legs with similar properties to Nb 0.55 Ta 0.40 Ti 0.05 FeSb (which has a negative Seebeck coefficient for the n-type leg) would result in a higher cooling capacity across a wider Δ T range of 46 K (Fig. 4b).

---

### Colorectal cancer screening and prevention [^390b568a]. American Family Physician (2025). High credibility.

Regarding screening and diagnosis for colon cancer, more specifically with respect to indications for screening, high-risk individuals, family history, AAFP 2025 guidelines recommend to obtain CRC screening in patients with ≥ 1 first-degree relatives with CRC or adenomatous polyps, starting at 40 years of age or 10 years before the age of the youngest relative at the time of their diagnosis.

---

### Recommendations for cardiac chamber quantification by echocardiography in adults: an update from the American Society of Echocardiography and the European association of cardiovascular imaging [^194fdbe5]. Journal of the American Society of Echocardiography (2015). Medium credibility.

Left atrial (LA) volume quantification by echocardiography is described using two-dimensional echocardiography (2DE) and three-dimensional (3D) approaches, with 2D volumetric measurements based on tracings from apical four- and two-chamber views; at the mitral valve level the contour is closed by a straight line, endocardial tracing excludes the atrial appendage and pulmonary veins, LA length L is the shortest long axis from apical two- and four-chamber views, and the two lengths should not differ more than 5 mm; volumes can be computed by an area-length approximation or by a disk summation technique, and 3D data sets are usually acquired from the apical approach using a multibeat full-volume acquisition. For the 2DE area-length technique, advantages include accurate assessment of asymmetric remodeling of the left atrium and being a more robust predictor of cardiovascular events than linear or area measurements, whereas limitations include geometric assumptions about LA shape, few accumulated data on normal population, and that single plane volume calculations are inaccurate because they assume A1 = A2. For 3D data sets, advantages are no geometrical assumption about LA shape and greater accuracy compared with 2D measurements, while limitations include dependence on adequate image quality, lower temporal resolution, limited data on normal values, and that patient's cooperation is required.

---

### Hypromellose 2906 (4000 mpa.s) (goniotaire) [^6ffaafe0]. FDA (2022). Medium credibility.

Active:

Hypromellose 25mg (2.5%):

---

### Restoration of the tibial ACL footprint area and geometry using the modified insertion site table [^fb317262]. Knee Surgery, Sports Traumatology, Arthroscopy (2012). Low credibility.

Purpose

This article is based on the concept of complete footprint restoration. It introduces a "Modified Insertion Site Table" for individual size-matched single- (SB) and double-bundle (DB) ACL reconstruction, which gives surgical guidelines for graft diameters and drill angles according to the restored tibial insertion site area and geometry.

Methods

Potential graft diameters and drill angles were matched for all individual tibial insertion site lengths between 8 and 21 mm. A "Modified Insertion Site Table" was calculated to achieve a maximum of area restoration of the tibial ACL footprint for each of these insertion site lengths. The geometry of the restored footprint was considered.

Results

A wide ACL footprint up to a 16-mm-long insertion site might be best restored with a SB-, a narrow one with a DB-ACL reconstruction. In a 17-mm-long insertion site, SB- and DB-ACL reconstructions restore a similar amount of footprint area, so geometry considerations of the footprint may decide which surgical technique may be favourized. SB can restore a maximum length of 13.1 mm and DB up to 21 mm. The width of the restored area depends on the drill bit diameter(s) and is larger for SB in most cases. In larger footprints, DB can replicate up to 63% more area and 37% more length than SB-ACL reconstruction.

Conclusions

Anatomical footprint restoration requires assessment of the length, width, and the orientation of the tibial ACL insertion site. Both SB- and DB-ACL reconstruction may achieve a wide range of area and geometric restoration of the individual ACL footprint. While SB-ACL reconstruction may be best used for wide insertion sites with up to 16 mm in length, DB-ACL reconstruction has the potential to restore narrow and larger footprints up to 21 mm in length. The "Modified Insertion Site Table" resumes the concept for orientation during surgery

---

### Two-edge-resolved three-dimensional non-line-of-sight imaging with an ordinary camera [^9cd4cd29]. Nature Communications (2024). High credibility.

In addition, variations in the range or radiosity of the object have no impact on the obstructed non-illuminated portion of the observation; it only affects the brightness of the illuminated portion. An overall brightness change in the illuminated portion of the observation plane, with no change to the slope and height of the right trapezoidal region, is explainable by a corresponding change in the range and/or radiosity of the hidden scene point. This suggests that, although highly coupled themselves, the radiosity and range parameters have no coupling with the pair of angular parameters. Thus, errors in range or radiosity have a negligible impact on the angular estimates. No convenient (re-)parameterisations exist that make the range and radiosity parameters similarly information orthogonal. However, we alleviate the effect of their coupling through a two-step computation that first estimates the radiosities and scene shape (2D angular) components while assuming that the entire scene is confined to a fixed range, and subsequently computes ranges of the recovered hidden scene objects. Central to this approach is the assumption that neighbouring clusters of surface elements belong to the same object and thus have approximately equal ranges. This results in the significantly more feasible problem of recovering a single range for clusters of estimated surface elements, in place of the possibly intractable one that estimates a range per recovered surface element.

The existence of information orthogonality among the range, azimuth, and project-elevation coordinates is crucial to the success of our two-step reconstruction procedure. Notably, it ensures that accurate angle estimation (i.e. shape) is achievable without knowing the ranges of objects within the hidden scene because errors in one do not prevent reliable reconstruction of the other. Additionally, the proposed coordinate system also simplifies the forward modelling by enabling closed-form expressions for incorporating occlusion. Consequently, we could accurately compute the forward model matrix without performing computationally intensive numerical integrations. We formalise these claims and elucidate the information orthogonality phenomenon through Fisher information analyses, and experimental demonstrations in Supplementary Notes 2 and 3.

---

### Roflumilast (Zoryve) [^e2de6cd7]. FDA (2024). Medium credibility.

The dosage of roflumilast TOP for treatment of plaque psoriasis in adults is 1 application(s) TOP daily (0.3% cream or foam)

---

### 2025 ESC guidelines for the management of myocarditis and pericarditis [^230fe03b]. European Heart Journal (2025). High credibility.

Regarding specific circumstances for acute pericarditis, more specifically with respect to patients with post-cardiac injury syndromes, ESC 2025 guidelines recommend to initiate IL-1 antagonists in patients with refractory post-cardiotomy inflammatory syndrome to prevent recurrences and progression to constriction.

---

### The effect of muscles in the treatment of lower limb lymphedema: respiratory muscles or leg muscles? [^764880aa]. Supportive Care in Cancer (2025). Medium credibility.

Outcome measurements

Participants'demographic and disease information (age, gender, height, body weight, stage and duration of lymphedema) was recorded.

---

### Sodium bicarbonate [^cce80997]. FDA. Low credibility.

Warning or precaution regarding the use of sodium bicarbonate PO and fluid retention: use caution in patients with hypertension or conditions that predispose them to fluid retention.

---

### Prediction of spontaneous ureteral stone passage: automated 3D-measurements perform equal to radiologists, and linear measurements equal to volumetric [^58acc504]. European Radiology (2018). Low credibility.

(aut) = Automated 3D segmentation based measurement. (manual) = Mean of three readers manual estimations of stone size

Table 2
Area under the curve (AUC) for the prediction of spontaneous passage of a ureteral stone with different measurements — Subgrouped according to position in the ureter

Length = Longest stone axis, width = largest diameter perpendicular to the long axis, area = cross-sectional area perpendicular to the long axis, circumference = circumference perpendicular to the long axis, volume = stone volume, surface = total surface area

(aut) = Automated 3D segmentation based measurement. (manual) = Mean of three readers manual estimations of stone size

Fig. 4
Receiver-operating characteristic (ROC) curves for the prediction of the outcome of spontaneous passage in 20 weeks with eight different measurements. Length = Longest stone axis, width = largest diameter perpendicular to the long axis, area = cross-sectional area perpendicular to the long axis, circumference = circumference perpendicular to the long axis, volume = stone volume, surface = total surface area. (aut) = Automated 3D segmentation-based measurement. (manual) = Mean of three readers' manual estimations of stone size (bone window)

The Bland-Altman 95% limits of agreement between the automated 3D algorithm and the manual measurements (average of three readers) were 0.2 ± 1.1 mm for the stone length and 0.2 ± 1.4 mm for the stone width (Fig. 5). There is a strong tendency towards smaller automatic than manual measurements for larger stones as demonstrated by Fig. 5. This finding is expected since the automatic measurements used a variable threshold defined as one half of the maximum attenuation, whereas the readers used a fixed bone window for measurements. Larger stones have higher peak attenuation resulting in a higher segmentation threshold compared to the smaller stones.

Fig. 5
Bland-Altman plots. a) Automated length vs. manual length (mean of three readers, bone window). Bland-Altman 95% limits of agreement 0.2 ± 1.1 mm, n = 391. b) Automated width vs. manual width (mean of three readers, bone window). Bland-Altman 95% limits of agreement 0.2 ± 1.4 mm, n = 391

Impact of inter-reader variability on the predicted outcome of ureteral stones

---

### Guidelines for performing a comprehensive pediatric transthoracic echocardiogram: recommendations from the American Society of Echocardiography [^8ec10f9f]. Journal of the American Society of Echocardiography (2024). High credibility.

Pediatric transthoracic echocardiography — area and length-based LV measurements include end-diastolic area (EDA) obtained in 2DE: parasternal short-axis or subcostal sagittal (short-axis) view at maximum area at end-diastole for LV size; EDA is used for LV volume and mass calculation and is appropriate for abnormal LV shape but depends on good blood-endocardium border. End-systolic area (ESA) uses minimum area at end-systole and is used for LV volume calculation and is appropriate for abnormal LV shape. End-diastolic length (EDL) uses 2DE: apical four-chamber or subcostal coronal (long-axis) view and is measured just after MV closure at end-diastole; it is used for LV volume and mass calculation and is appropriate for abnormal LV shape, but depends on good blood-endocardium border, especially at apex, and foreshortening can limit accuracy.

---

### 2023 ESC guidelines for the management of cardiovascular disease in patients with diabetes [^24784e3d]. European Heart Journal (2023). High credibility.

Regarding medical management for diabetes mellitus type 2, more specifically with respect to prevention of CVD, glucose-lowering medications, ESC 2023 guidelines recommend to consider initiating metformin to reduce cardiovascular risk in patients with T2DM without ASCVD or severe target-organ damage at low, moderate,
high, or very high risk.

---

### KDIGO 2024 clinical practice guideline for the management of LUPUS NEPHRITIS [^e4483443]. Kidney International (2024). High credibility.

Steroid-sensitive nephrotic syndrome in children (first episode) — glucocorticoid duration comparisons include 1-month versus 2-month, 12-month versus 5-month, and 5- or 6-month (4–6 months in 1 study) versus 3-month courses; dosing strategy comparisons include weight-based prednisolone 1.5 mg/kg [maximum 40 mg] versus body surface area–based prednisolone 40 mg/m2.

---

### Endoscopic management of Barrett's esophagus: European Society of Gastrointestinal Endoscopy (ESGE) position statement [^c63a7687]. Endoscopy (2017). Medium credibility.

Regarding screening and diagnosis for esophageal cancer, more specifically with respect to indications for screening, Barrett's esophagus, general principles, ESGE 2017 guidelines recommend to stratify surveillance intervals for nondysplastic Barrett's esophagus according to the length of the Barrett's segment:

| **Situation** | **Guidance** |
|-|-|
|Irregular Z-line/columnar-lined esophagus < 1 cm|- No endoscopic surveillance|
|Maximum extent of Barrett's esophagus ≥ 1 cm and < 3 cm|- 5 years|
|Maximum extent of Barrett's esophagus ≥ 3 cm and < 10 cm|- 3 years.|

---

### Filgrastim-txid (Nypozi) [^3c3c8e7c]. FDA (2024). Medium credibility.

G Check the syringe for an air bubble. Point the needle up and gently tap the syringe with your fingers until the air bubble rises to the top of the syringe.

H Hold the syringe as shown below and press slowly on the plunger to push out the excess medicine until the top edge of the conical base of the plunger stopper lines up with the syringe marking for your prescribed dose. As you push the plunger rod up, air and extra medication is removed. Check to make sure the plunger lines up with the syringe markings for your prescribed dose. If you remove too much medicine, get a new prefilled syringe and start again at Step 1.

See the figure below (Step 2) for an example of a dose of 0.4 mL. Your dose may be different than the example shown.
Call your healthcare provider if you have problems measuring your prescribed dose.

Step 3: Subcutaneous (under the skin) injection

I With one hand gently pinch the skin at the injection site to create a firm surface.

Important: Keep the skin pinched while injecting.

J Hold the pinch. With your other hand insert the needle into the skin at a 45 to 90 degree angle as shown.

K Using slow and constant pressure, slowly press down on the plunger rod as far as it will go so that the plunger head is completely between the needle guard wings.

---

### 2021 ESC / EACTS guidelines for the management of valvular heart disease [^95148bb1]. European Heart Journal (2022). High credibility.

Regarding surgical interventions for tricuspid regurgitation, more specifically with respect to indications for surgery, symptomatic patients, EACTS/ESC 2022 guidelines recommend to consider performing surgery in patients with mild or moderate secondary TR with annular dilation (≥ 40 mm or > 21 mm/m² by 2D echocardiography) undergoing left-sided valve surgery.

---

### Standards of care in diabetes – 2025 [^1e105a7e]. Diabetes Care (2025). High credibility.

Regarding specific circumstances for hypertension, more specifically with respect to patients with diabetes mellitus, pharmacotherapy, ADA 2025 guidelines recommend to include drug classes demonstrated to reduce cardiovascular events in patients with diabetes. Initiate ACEis or ARBs as first-line therapy for HTN in patients with diabetes and coronary artery disease.

---

### Miniaturized MgBi-based thermoelectric cooler for localized electronic thermal management [^11043f31]. Nature Communications (2025). High credibility.

The impact of substrate thermal resistance on the hot-side temperature is shown by Eq. (7), where Q h is the heat dissipation of the cooler, and T s is the heat sink temperature. The electrical contact resistance also affects the maximum cooling power, and Eq. (4) can be rewritten as,

Calculations on the performance of the Mg 3 Bi 2 -based cooler were conducted. Based on Eq. (5), the relationship between Δ T max and leg length under different contact resistivities was calculated (Fig. 1a). As the length of the thermoelectric leg decreases, the Δ T max diminishes, primarily due to the increased influence of irreversible losses associated with contact resistances at the interfaces. These losses become more pronounced as the leg length is reduced, leading to a significant reduction in cooling performance. This reduction becomes more pronounced as the interfacial electrical contact resistivity increases, and the disparity in Δ T max is noticeable when the leg length is less than 1.0 mm. For a Mg 3 Bi 2 -based leg with dimensions of 1 × 1 × 1 mm 3, the contact resistivity of 10 μΩ cm 2 accounts for approximately 6.7% of the total internal resistance, further highlighting the critical role of minimizing contact losses in optimizing the performance of miniaturized thermoelectric coolers. According to Eq. (8), the large electrical contact resistance is also deleterious to maximum cooling power since the Joule heating caused by contact resistance becomes more significant at shorter leg lengths (Fig. 1b). The relationship between Δ T max and leg length for different substrate materials, e.g. Al 2 O 3, AlN, and diamond, is depicted in Fig. 1c. It is assumed that the thickness of ceramic materials is 500 μm and the electrical contact resistivity is zero. The results demonstrate that the choice of substrate material significantly impacts the thermal resistance, thereby influencing the Δ T max of the thermoelectric cooler. Specifically, substrates with higher thermal conductivity exhibit mitigated degradation of Δ T max, highlighting the critical role of substrate material selection for optimizing cooling performance.

---

### Effective discipline to raise healthy children [^94ceab7c]. Pediatrics (2018). Medium credibility.

Cycle of corporal punishment and aggressive child behavior — Longitudinal cohort evidence linked spanking to later aggression and externalizing problems: the Fragile Families and Child Wellbeing Study was a population-based birth cohort of approximately 5000 children from 20 large US cities between 1998 and 2000 with data at birth and 1, 3, 5, and 9 years; children spanked more than twice per month at age 3 years were more aggressive at age 5, a follow-up at 9 years found correlations between spanking at age 5 and higher externalizing behavior and lower receptive vocabulary scores, and subsequent analyses concluded that increased frequency of spanking was associated with increased externalizing behaviors and more spanking in response, creating a complex negative spiral over time.

---

### Evidence-based guidelines for the pharmacological treatment of schizophrenia: updated recommendations from the British Association for Psychopharmacology [^3462202c]. Journal of Psychopharmacology (2020). High credibility.

Regarding diagnostic investigations for schizophrenia, more specifically with respect to initial assessment, BAP 2020 guidelines recommend to elicit a personal and family history of CVDs in all patients. Identify and modify risk factors for CVD/sudden death, including increased BMI, smoking, diabetes, elevated HR, BP, cholesterol, liver disease, and poor nutrition, recognizing that many of these factors may be exacerbated by antipsychotic medications.

---

### Yoked surface codes [^9e0c45c6]. Nature Communications (2025). High credibility.

Yoked surface code patches change the length and number of shortest error paths. In 1D yoked surface codes, shortest error paths correspond to two shortest error paths in different surface code patches. This doubles the code distance, but introduces quadratic scaling in r, the number of rounds between yoke checks. Furthermore, since a logical failure can occur over any two patches in the code, the number of shortest error paths also scales quadratically in n. Based on this, we expect the scaling of the 1D yoked logical error rate to be, where λ 1 denotes the increased error suppression factor obtained from doubling the code distance, which we would expect to be at most. Note that the quadratic scaling versus r is only for numbers of rounds up to the yoke check period. Shortest paths from patches in different check periods don't combine to form a shortest error path in the concatenated code (although they can form an effective measurement error). Consequently, we expect the scaling versus rounds to be quadratic up to the check period, and then linear afterwards.

A similar argument holds for 2D yoked surface codes, for which the distance quadruples, but now the error scaling becomes quartic versus the number of rounds r between yoke checks, while remaining quadratic in the number of patches n. The quartic scaling versus r is similar: within the support of a weight four logical error, any combination of error paths within those patches can cause the error. The quadratic scaling versus n is because weight four logical errors correspond to four logical errors landing on the corners of a rectangle within the grid. There are Θ (n 2) of these rectangles specified by their endpoints across a diagonal. Based on this, we expect the scaling of the 2D yoked logical error rate to be, where λ 2 denotes the increased error suppression factor obtained from quadrupling the code distance, which we would expect to be at most.

We emphasize that these are simple path-counting heuristics, where we can empirically fit the different λ factors and coefficients. However, these can of course break down. For example in 2D, the set of higher-weight inner logical errors leading to failure could scale as o (r 4). Despite this, we observe good agreement between simulation and these heuristic scaling laws.

---

### Electrohydraulic musculoskeletal robotic leg for agile, adaptive, yet energy-efficient locomotion [^8f766a16]. Nature Communications (2024). High credibility.

Fig. 3
The leg performs agile locomotion.

a High jump. The leg jumped 128 mm high from the ground and reached the highest point in 172 ms. b Agile vertical hopping. Top: the leg was driven by an open-loop force controller with the periodic input signal. The partial overlap of the activation of the extensor and flexor muscles during the stance phase was used to compensate for dead zones of the muscle (from 0 kV to 3 kV, depending on external loads, the actuators do not respond to voltage signals), and for inertial delay of the leg motion. Bottom: the leg hopped at 3 Hz on the rubber surface (left) and the slippery surface (right). c Limit cycles for hopping on a slippery surface. The dashed line showed the mean value of the 15 cycles. d Rapid gait motion. Top: the leg was driven by the open-loop force controller with the periodic input signal. Bottom: The leg achieved 5 Hz gait motion and 10 Hz linear motion. e Size comparison of the area enclosed by the leg's foot trajectory at each frequency. The mean and standard deviation were calculated from multiple motion cycles after reaching a steady limit cycle (details in the Methods section).

Given the short stance time, we were encouraged to explore the leg's capabilities of rapid hopping, that is, high-frequency repetitive jumps (Fig. 3b). The gravitational acceleration alone was not high enough to bring the leg back down to the ground fast enough, thus limiting the achievable maximum motion frequency. To account for this in our experiments, we used the antagonistic pairs of muscles in the leg to reach even higher frequency motions. Using an open-loop force controller (Fig. 3b; top), we successfully achieved a hopping frequency of 3 Hz on various terrains (Fig. 3b; bottom), showcasing the leg's agility and versatility. The hopping motion displayed stable limit cycles (Fig. 3c), further emphasizing the leg's ability to perform robust and agile hopping maneuvers. For 3 Hz, the leg achieved a jump height of 80 mm and was dynamically stable in vertical hopping.

---

### Norvir [^cd1699c3]. FDA (2020). Medium credibility.

0.25 0.8 mL (62.5 mg) 0.9 mL (75 mg) 1.1 mL (87.5 mg) 1.25 mL (100 mg)

0.50 1.6 mL (125 mg) 1.9 mL (150 mg) 2.2 mL (175 mg) 2.5 mL (200 mg)

0.75 2.3 mL (187.5 mg) 2.8 mL (225 mg) 3.3 mL (262.5 mg) 3.75 mL (300 mg)

1.00 3.1 mL (250 mg) 3.75 mL (300 mg) 4.4 mL (350 mg) 5 mL (400 mg)

1.25 3.9 mL (312.5 mg) 4.7 mL (375 mg) 5.5 mL (437.5 mg) 6.25 mL (500 mg)

1.50 4.7 mL (375 mg) 5.6 mL (450 mg) 6.6 mL (525 mg) 7.5 mL (600 mg)

Body surface area (BSA) can be calculated as follows1:

[norvir equation]

---

### Standards of care in diabetes – 2025 [^5c059b62]. Diabetes Care (2025). High credibility.

Regarding specific circumstances for hypertension, more specifically with respect to patients with diabetes mellitus, lifestyle modifications, ADA 2025 guidelines recommend to advise lifestyle interventions in patients with BP > 120/80 mmHg, consisting of weight loss when indicated, a DASH-style eating pattern (including reducing sodium and increasing potassium intake), moderation of alcohol intake, smoking cessation, and increased physical activity.

---

### Identifying the barriers to quality [^b6369d1a]. The Journal of Clinical Psychiatry (2015). Low credibility.

The Mental Health Quality Forum, a 2-meeting multidisciplinary panel, was held in March and June 2013 to identify problems and opportunities in the management of serious mental illness. In the first meeting, participants from a range of mental health care-related backgrounds identified components of quality care and the key issues that cause delivery of that care to be suboptimal.

---

### Standards of care in diabetes – 2025 [^ed74d997]. Diabetes Care (2025). High credibility.

Regarding specific circumstances for obesity, more specifically with respect to patients with diabetes mellitus, bariatric surgery, ADA 2025 guidelines recommend to evaluate patients being considered for metabolic surgery for comorbid psychological conditions and social and situational circumstances with the potential to interfere with surgery outcomes.

---

### AGA clinical practice update on the management of ascites, volume overload, and hyponatremia in cirrhosis: expert review [^35bd9056]. Gastroenterology (2025). High credibility.

Regarding therapeutic procedures for ascites, more specifically with respect to therapeutic paracentesis, AGA 2025 guidelines recommend to perform therapeutic paracentesis for refractory ascites, with the frequency guided by recurrence.

---

### 2025 ESC guidelines for the management of myocarditis and pericarditis [^b050a21b]. European Heart Journal (2025). High credibility.

Regarding nonpharmacologic interventions for myocarditis, more specifically with respect to physical activity restrictions, ESC 2025 guidelines recommend to restrict physical exercise until remission for at least 1 month in athletes and non-athletes after inflammatory myopericardial syndrome, using an individualized approach to accelerate recovery.

---

### Diagnosis, evaluation, and management of ascites, spontaneous bacterial peritonitis and hepatorenal syndrome: 2021 practice guidance by the American Association for the Study of Liver Diseases [^0ecc018a]. Hepatology (2021). High credibility.

Regarding therapeutic procedures for ascites, more specifically with respect to therapeutic paracentesis, AASLD 2021 guidelines recommend to perform large-volume paracentesis as first-line therapy in patients with grade 3 ascites. Advise sodium restriction and initiate diuretics after paracentesis.

---

### Diagnosis, management and treatment of the Alport syndrome-2024 guideline on behalf of ERKNet, ERA and ESPN [^45eede36]. Nephrology, Dialysis, Transplantation (2025). High credibility.

Regarding diagnostic investigations for Alport syndrome, more specifically with respect to hearing assessment, ERA/ERN ERKNet/ESPN 2025 guidelines recommend to consider obtaining a hearing evaluation at diagnosis or upon reaching adulthood in female patients with X-linked alport syndrome, and then every 5 years in the absence of hearing loss symptoms.

---

### Standards of care in diabetes – 2025 [^14753c0e]. Diabetes Care (2025). High credibility.

Regarding specific circumstances for chronic kidney disease, more specifically with respect to patients with diabetes mellitus (monitoring of renal function), ADA 2025 guidelines recommend to monitor urinary albumin (such as spot urinary albumin-to-creatinine ratio) and eGFR 1–4 times per year, depending on the stage of the disease, in patients with established diabetic kidney disease.

---

### 2022 ESC guidelines for the management of patients with ventricular arrhythmias and the prevention of sudden cardiac death [^9a594a67]. European Heart Journal (2022). High credibility.

Regarding medical management for myocarditis, more specifically with respect to management of cardiac arrhythmias, catheter ablation, ESC 2022 guidelines recommend to consider performing catheter ablation as an alternative to ICD therapy, after discussion with the patient and provided that established endpoints have been reached, in patients with hemodynamically well-tolerated sustained monomorphic VT occurring in the chronic phase of myocarditis, preserved LV function, and a limited scar amenable to ablation.

---

### Degenerate boundaries for multiple-alternative decisions [^55f4a482]. Nature Communications (2022). High credibility.

Sequential Bayesian inference can be rewritten in a form that more closely resembles a sum of evidence by taking the logarithm of equation (8):For each of the n -choices, the accumulated evidence is the log posterior, with n distinct evidence incrementsand a common subtractive log-marginal term. Calculation of this log-marginal is necessary for multiple (n > 3) choice optimal decision-making, but can be avoided for n = 2 by using the SPRT as mentioned above. A similarterm in a theory of basal ganglia function has been interpreted as suppressing evidence accumulation when choices are ambiguous –.

Within this framework, using that probabilities sum to unity ∑ i P i (t) = 1, the evidence accumulation takes place within an (n − 1)-dimensional linear subspace spanning n vertices { P i = 1, P j ≠ i = 0} of an N -dimensional unit hypercube. This is most easily seen for N = 3 choices, where the decision variables P = (P 1, P 2, P 3) vary within a triangle passing through three vertices {(1, 0, 0), (0, 1, 0), (0, 0, 1)} of the unit cube (Fig. 1, top right panel). So rather than representing evidence accumulation trajectories as a random walk constrained to two dimensions, for multiple alternatives the random walk moves in higher dimensions (a line for two alternatives, a plane/triangle for three, and so on). For simplicity, this vector is initialized with equal prior probabilities 1/ n and updated sequentially until one of the elements reaches a boundary, P i > θ.

Both the SPRT and two-choice sequential Bayesian inference give optimal decisions in that they give the fastest decisions for a given level of accuracy on single trials of known difficulty. Formally, they optimize a cost function, the Bayes risk, that is linear in the mean error rate e and mean decision time T over many trialswith error costs W i > 0 and cost of time c, scaling the expected error and decision time,… This cost function represents the trade-off between speed and accuracy of decision-making: slow but accurate or fast but inaccurate decisions are both costly, and so a balance must be found. For equal decision costs, W 0 = W 1, there is a single threshold that is free parameter, which for optimal decision-making is tuned according to the relative cost c / W of accuracy and time.

---

### European Stroke Organisation (ESO) and European Association of Neurosurgical Societies (EANS) guideline on stroke due to spontaneous intracerebral haemorrhage [^a24b784e]. European Stroke Journal (2025). High credibility.

Regarding diagnostic investigations for intracerebral hemorrhage, more specifically with respect to initial evaluation, EANS/ESO 2025 guidelines recommend to consider using algorithms such as the DIAGRAM for targeted investigation of the cause of spontaneous ICH to improve the performance of prediction regarding the underlying cause, compared to standard care.

---

### The natural history of the growth of the hand: I. hand area as a percentage of body surface area [^61d2446b]. Plastic and Reconstructive Surgery (2001). Low credibility.

The use of a patient's own hand as a tool to estimate the area of burn injury is well documented. The area of the palmar surface of one hand has been estimated to be 1 percent of the body surface area. The area of the palmar surface of the hand was measured to test the accuracy of this estimate and then compared with the body surface area as calculated by formulas in common use. This study also sought to determine the natural history of the growth of the hand to permit development of a readily available, bedside means of estimating hand area and body surface area. Bilateral hand tracings were obtained from 800 volunteers ranging in age from 2 to 89 years. The area of each tracing was determined using an integrating planimeter. The height and weight of each individual were measured, and his/her body surface area was calculated. The palmar hand's percentage of body surface area was determined by calculating the quotient for hand area divided by body surface area. Additionally, the width of the hand was measured from the ulnar aspect at the palmar digital crease of the small finger to the point where the thumb rested against the base of the index finger. The length of the hand was measured from the middle of the interstylon to the tip of the middle finger. These two figures were multiplied together to obtain a product which approximated the area of the hand. Based on the most commonly used DuBois formula for calculating body surface area, the area of palmar surface of the hand corresponds to 0.78 ± 0.08 percent of the body surface area in adults. The percentage varies somewhat with age and reaches a maximum of 0.87 ± 0.06 percent in young children. Multiplying the length of the hand by its width overestimates the area of the hand as determined by planimetry by only 2 percent. A patient's own hand may be used as a complementary, readily available template for estimation of burn area or other areas of disease or injury. In adults, the area of tracing of the outline of the hand is 0.78 percent of the body surface area, whereas in children, this number tends to be slightly higher. In the emergency room or on the wards, a simple product of length multiplied by width of the hand will closely approximate the area as determined by planimetry. This method allows a more accurate determination of the area of the palmar surface of the hand than the 1 percent estimate, which may lead to an overestimation of the size of a burn wound in adults.

---

### Erythromycin (Ery-tab) [^379f7f44]. FDA (2024). Medium credibility.

Carcinogenesis, Mutagenesis, Impairment of Fertility

Long-term oral dietary studies conducted with erythromycin stearate in rats up to 400 mg/kg/day and in mice up to about 500 mg/kg/day (approximately 1–2 fold of the maximum human dose on a body surface area basis) did not provide evidence of tumorigenicity. Erythromycin stearate did not show genotoxic potential in the Ames, and mouse lymphoma assays or induce chromosomal aberrations in CHO cells. There was no apparent effect on male or female fertility in rats treated with erythromycin base by oral gavage at 700 mg/kg/day (approximately 3 times the maximum human dose on a body surface area basis).

Pregnancy

Teratogenic Effects

There is no evidence of teratogenicity or any other adverse effect on reproduction in female rats fed erythromycin base by oral gavage at 350 mg/kg/day (approximately twice the maximum recommended human dose on a body surface area) prior to and during mating, during gestation, and through weaning. No evidence of teratogenicity or embryotoxicity was observed when erythromycin base was given by oral gavage to pregnant rats and mice at 700 mg/kg/day and to pregnant rabbits at 125 mg/kg/day (approximately 1–3 times the maximum recommended human dose).

Labor and Delivery

The effect of erythromycin on labor and delivery is unknown.

Nursing Mothers

Erythromycin is excreted in human milk. Caution should be exercised when erythromycin is administered to a nursing woman.

Pediatric Use

See INDICATIONS AND USAGE and DOSAGE AND ADMINISTRATION.

---

### Quantifying entanglement in a 68-billion-dimensional quantum state space [^b339b52f]. Nature Communications (2019). High credibility.

Adaptive sampling algorithm

For each configuration, experimental data are stored in nodes in a quad-tree decomposition of P whose levels describe increasingly fine detail. The i th node corresponds to a square area ofat locationwith span. Nodes are sampled by placing the corresponding, one-dimensional local patterns on the DMDs and generating a coincidence histogram during acquisition time T a = 0.5 s. Coincidences C i are counted within a 1-ns coincidence window centered on the coincidence peak; accidental coincidences A i are counted in a 1-ns window displaced 2 ns from the coincidence window. Coincidence and accidental values are appended to a list each time the node is sampled. The estimated count rate, whereis a calibrated, relative fiber coupling efficiency. Optionally, A i can be subtracted from C i for accidental removal. Uncertainty is computed by assuming Poissonian counting statistics for C i and A i and applying standard, algebraic propagation of error through the calculation of the entanglement quantity (Eq. (3)).

The data collection algorithm consists of a partitioning phase followed by an iterative phase. During partitioning, the algorithm repeatedly iterates through a scan-list of leaves of the tree. Node i is considered stable when sgn(αR T − R i) is known to at least β standard deviations of certainty, where splitting threshold α (0 ≤ α ≤ 1) and stability criterion β are user-chosen heuristics. Stable nodes are no longer measured. If a node is stable and R i ≥ αR T, the node is split into four equal-sized sub-quadrants, which are initially unstable and added to the scan-list. Optionally, a maximum resolution (maximum tree depth) may be set.

The transition to the iterative phase occurs when the percentage of unstable leaves is < Γ, a user-chosen parameter. At this point, stability is ignored and all leaf nodes are scanned repeatedly and guaranteed to have the same total acquisition time. Various final stopping criteria can be used; we chose a fixed total run time. Note that heuristic parameters α, β, and γ may be changed during operation if desired. For the data shown in this manuscript, α = 0.002, β = 2, and Γ = 0.15 with a 30-h runtime.

The probability distributionis computed by uniformly distributing the estimated count rate (with or without accidental subtraction) from each leaf node across its constituent elements in, followed by normalization.

---

### Promoting optimal development: screening for mental health, emotional, and behavioral problems: clinical report [^d13b5812]. Pediatrics (2025). High credibility.

Follow-up planning — once a decision on next steps has been reached in partnership with a family, it is important to ensure an appropriate follow-up plan, which will depend on the nature and severity of the problem, management plan implemented, and patient and family response to the plan.

---

### Evaluation after a first seizure in adults [^b94f7748]. American Family Physician (2022). High credibility.

Regarding diagnostic investigations for first seizure in adults, more specifically with respect to initial assessment, AAFP 2022 guidelines recommend to evaluate for provoking factors after a first seizure, such as inflammatory, infectious, structural, toxic, or metabolic causes.

---

### Clobetasol propionate (Clobex) [^231f7ff0]. FDA (2024). Medium credibility.

The dosage of clobetasol propionate TOP for treatment of bullous pemphigoid in adults (extensive) is 1 application(s) TOP BID, 30–40 g per day, tapered after 15 days in case of response and continued for 4–12 months (0.05% cream or ointment)

---

### Clobetasol propionate (Clobex) [^1104c046]. FDA (2024). Medium credibility.

The dosage of clobetasol propionate TOP for treatment of bullous pemphigoid in adults (localized) is 1 application(s) TOP BID, 10–20 g per day, tapered after 15 days in case of response and continued for 4–12 months (0.05% cream or ointment)

---

### Chemical shift encoding using asymmetric readout waveforms [^8935a941]. Magnetic Resonance in Medicine (2021). Medium credibility.

2.2 Matching the in‐phase echo

A property of the asymmetric readouts, resulting from the dynamic bandwidth, is the non‐uniform k‐space sampling density. We propose to counterbalance this with a matched in‐phase readout to achieve a more balanced total k‐space sampling density in a two‐point RARE sequence. Ideally, the combined fat/water estimates will have an improved SNR transfer function with this approach (described below).

Although constrained to be symmetrical about the k‐space origin, the sampling density of the matched readout can be varied. Instead of a conventional trapezoidal readout with fixed amplitude λ, we investigated a symmetric quadratic readout waveform which matches the CSE readout, illustrated in Figure 2. The constantmatches the asymmetric spline such that the combined effective dwell time at the k‐space center equals that of two trapezoidal in‐phase readouts. That is, the total time spent sampling the k‐space center is the same: The quadratic coefficientis defined by the gradient moment M, the center pointcoinciding with the spin echo, and the constant:

FIGURE 2
Symmetric readout waveforms for in‐phase CSE. A trapezoid and the proposed matched quadratic waveform is shown in (A). The k‐space trajectory over time is shown in (B). The time axis (x) is shared between the plots

A comparison between the sampling densities for trapezoidal and quadratic in‐phase readouts is shown in Figure 3. It is clear that while the density is non‐uniform, the area is consistent between the spline, quadratic, and trapezoidal waveforms because the total readout durations are equal. In contrast, the shifted trapezoidal case shows a uniform distribution but with a smaller area. This is a consequence of less time spent sampling the signal. In Figure 4 D, it is evident that the combined sampling time at the k‐space center is increased and a more uniform density is achieved with the quadratic in‐phase waveform. We hypothesize that the asymmetry of the sampling density can be counterbalanced by using real‐valued k‐space fat/water separation, described below.

---

### Digital leg volume quantification: precision assessment of a novel workflow based on single capture three-dimensional whole-body surface imaging [^5221b9a3]. Journal of Digital Imaging (2021). Medium credibility.

A strength of this study lies in the relatively large sample size and morphologic variety of the examined subjects. While some studies assessing the precision of a workflow have examined rather small and homogenous cohorts or make use of an imaging phantom, this study included over 80 subjects in its analysis. A high number of subjects were subsequently available for each of the subgroups that were further analyzed as part of this study. Also, this study specifically examined subjects in the target population for clinical leg volume documentation. As such, it included patients with varying degrees of uni- or bilaterally high values of leg volume, and with a range of BMI values from 18.7 to 55.8 kg/m 2. While the study investigates measurement reproducibility between two separate scans in a single session, it does not provide information regarding the precision when more than two scans are conducted in one session, or when the scans are spread out over an extended period of time. Also, this study did not include multiple assessments of the same subjects by different assessors, and thus, inter-rater reliability was not examined. Future studies ought to evaluate reproducibility by repeatedly examining the same cohort without the subjects undergoing pronounced morphologic changes in the meantime. The influence of varying imaging operators should also be investigated. Finally, future efforts should be made to automate the data-processing part of the workflow.

---

### 2021 guideline for the prevention of stroke in patients with stroke and transient ischemic attack: a guideline from the American Heart Association / American stroke association [^2bda0db7]. Stroke (2021). High credibility.

Regarding specific circumstances for acute ischemic stroke, more specifically with respect to patients with patent foramen ovale (choice of closure method), AHA/ASA 2021 guidelines recommend to insufficient evidence regarding the benefit of closure with a transcatheter device and long-term antiplatelet therapy over antiplatelet therapy alone for the prevention of recurrent stroke in patients aged 18–60 years with a non-lacunar ischemic stroke of undetermined cause despite a thorough evaluation and a patent foramen ovale without high-risk anatomic features.

---

### AIUM practice parameter for the performance of detailed diagnostic obstetric ultrasound examinations between 12 Weeks 0 Days and 13 Weeks 6 Days [^0ea34f29]. Journal of Ultrasound in Medicine (2021). High credibility.

Abdominal circumference — this measurement may be helpful in certain clinical situations such as early asymmetric growth restriction (triploidy) and skeletal dysplasia; technique specifies obtaining an axial scan optimized to fill the majority of the image space, ensuring the fetal stomach and, if possible, the intrahepatic portion of the portal vein are seen while the kidneys and umbilical cord insertion are excluded, confirming a true axial plane with one vertebral body and a single rib on each side with the spine optimally at 3 or 9 o'clock, and measuring along the outer skin edge by an ellipse or 2 perpendicular diameters.

---

### Standards of care in diabetes – 2025 [^2a4976a0]. Diabetes Care (2025). High credibility.

Regarding specific circumstances for chronic kidney disease, more specifically with respect to patients with diabetes mellitus, renin-angiotensin system inhibitors, ADA 2025 guidelines recommend to monitor for increased serum creatinine and for increased serum potassium levels when ACEis, ARBs, or mineralocorticoid receptor antagonists are used, or for hypokalemia when diuretics are used at routine visits and 7–14 days after initiation or after a dose change.

---

### Promoting optimal development: screening for behavioral and emotional problems [^9b391825]. Pediatrics (2015). Medium credibility.

Lessons learned from implementing a screening program (Table 1) — promoters and challenges: Promoted implementation included "Creating an office-wide implementation system", "Dividing responsibility among staff", "Actively monitoring implementation and continuing to make changes", "Choosing screens perceived to least disrupt clinic flow", and "Aligning screening measures with those used in community based programs". Challenges remained including "Consistent referral of children with failed screens", "Distributing screens to children at screening ages but not to others", "Maintaining consistent screening practice during busy times", "Coping with screening gaps due to staff turnover", "Tracking referrals through a distinct implementation system from screening", and "Not screening when surveillance raised concerns".

---

### Erythromycin ethylsuccinate (ery-ped) [^8b2b1835]. FDA (2024). Medium credibility.

Carcinogenesis, Mutagenesis, Impairment of Fertility: Long-term oral dietary studies conducted with erythromycin stearate in rats up to 400 mg/kg/day and in mice up to 500 mg/kg/day (approximately 1–2 fold of the maximum human dose on a body surface area basis) did not provide evidence of tumorigenicity. Erythromycin stearate did not show genotoxic potential in the Ames, and mouse lymphoma assays or induce chromosomal aberrations in CHO cells. There was no apparent effect on male or female fertility in rats treated with erythromycin base by oral gavage at 700 mg/kg/day (approximately 3 times the maximum human dose on a body surface area basis).

Pregnancy: Teratogenic Effects. There is no evidence of teratogenicity or any other adverse effect on reproduction in female rats fed erythromycin base by oral gavage at 350 mg/kg/day (approximately twice the maximum recommended human dose on a body surface area) prior to and during mating, during gestation, and through weaning. No evidence of teratogenicity or embryotoxicity was observed when erythromycin base was given by oral gavage to pregnant rats and mice at 700 mg/kg/day and to pregnant rabbits at 125 mg/kg/day (approximately 1–3 times the maximum recommended human dose).

Labor and Delivery: The effect of erythromycin on labor and delivery is unknown.

Nursing Mothers: Erythromycin is excreted in human milk. Caution should be exercised when erythromycin is administered to a nursing woman.

Pediatric Use: See INDICATIONS AND USAGE and DOSAGE AND ADMINISTRATION sections.

---

### 2023 U.S. department of veterans affairs and U.S. department of defense clinical practice guideline for the management of headache [^7d673313]. Annals of Internal Medicine (2024). High credibility.

Algorithm — this clinical practice guideline (CPG) algorithm is designed to facilitate understanding of the clinical pathway and decision-making process used in managing patients with Headache, and the format represents a simplified flow that helps foster efficient decision making by providers; it includes steps of care in an ordered sequence, decisions to be considered, decision criteria recommended, and actions to be taken; the algorithm is a step-by-step decision tree, with standardized symbols to display each step and arrows connecting numbered boxes indicating the order in which the steps should be followed; shape meanings are specified: rounded rectangles represent a clinical state or condition, hexagons represent a decision point in the process of care formulated as a question that can be answered "Yes" or "No", rectangles represent an action in the process of care, and ovals represent a link to another section within the algorithm; Sidebars 1–7 provide more detailed information, and Appendix K contains alternative text descriptions of the algorithms.

---

### Leg length discrepancy: the natural history (and what Do we really know) [^888d8934]. Journal of Pediatric Orthopedics (2019). Medium credibility.

Background

The long-term effects of small limb length discrepancies have been poorly documented in the literature. References to low back pain, hip pathology, knee pathology, and foot problems abound in the popular literature. Health care providers frequently recommend the use of lifts for structural and functional limb length discrepancies, yet the natural history of limb length inequality as well as the effectiveness of treatments that may be recommended are obscure. The purpose of this paper is to document and evaluate the literature associated with small limb length discrepancies.

Methods

A search of the English literature was carried out using PubMed to identify papers dealing with the effects of limb length discrepancies. Papers reporting only expert opinion or case reports were excluded.

Results

Papers dealing with the natural history of limb length discrepancy as well as studies in which gait analysis was performed in patients with limb length discrepancy were identified. Only 10% of the population has exactly equal lower limb lengths. Approximately 90% of the population has a limb length discrepancy < 1.0cm. Hip and knee pathology is present in an increased number of patients with limb length discrepancies over 5mm. Hip pathology is more often present in the long leg, knee pathology has been reported in various studies to be more common in either the long or short leg. Low back problems seem to be more common on the short side in patients with limb length discrepancies. A number of different compensatory mechanisms for limb length discrepancy have been identified during gait analysis.

Conclusions

There seems to be a consensus that limb length discrepancies > 2.0cm are frequently a problem. There is some evidence that limb length discrepancies as little as 5mm can lead to long-term pathology.

---

### Long-term outcomes of muscle volume and achilles tendon length after achilles tendon ruptures [^4336a574]. Knee Surgery, Sports Traumatology, Arthroscopy (2013). Low credibility.

Purpose

The best treatment for Achilles tendon (AT) ruptures remains controversial. Long-term follow-up with radiological and clinical measurements is needed.

Methods

In this retrospective multicentre cohort study, patients (n = 52) were assessed at a mean of 91 months follow-up after unilateral AT rupture treated by open, percutaneous or conservative (non-surgical) treatment. Demographic parameters, time off work, maximum calf circumference and clinical scores (ATRS, Hannover, AOFAS) were evaluated. Muscle volume and cross-sectional area of the calf and AT length were measured on MR images and were compared between groups and to each patient's healthy contralateral leg.

Results

Reduced muscle volume was found across all groups with a higher muscle volume in the conservative (729.9 ± 130.3 cm(3)) compared to the percutaneous group (675.9 ± 207.4 cm(3), p = 0.04). AT length was longer in the affected leg (198.4 ± 24.1 vs. 180.6 ± 25.0 mm, p < 0.0001) without difference in subgroup analysis. Clinically measured ankle dorsiflexion showed poor correlation with AT length (R² = 0.07, p = 0.008). Muscle volume strongly correlated with the cross-sectional area (R² = 0.6, p < 0.0001) but showed a weak correlation with the Hannover score (R² = 0.08, p = 0.048). Maximum calf circumference correlated with muscle volume (R² = 0.42, p < 0.0001).

Conclusions

No significant difference between the treatment groups was found in muscle volume, AT length, clinical measures or days off work. Cross-sectional area and maximum calf circumference are cost-effective measurements and a good approximation of muscle volume and can thus be used in a clinical setting while clinical dorsiflexion should not be used.

---

### Standards of care in diabetes – 2025 [^fc74dd5c]. Diabetes Care (2025). High credibility.

Regarding specific circumstances for chronic kidney disease, more specifically with respect to patients with diabetes mellitus, protein intake, ADA 2025 guidelines recommend to aim to a target level of 0.8 g/kg body weight/day of dietary protein intake in patients with nondialysis-dependent stage ≥ G3 CKD.
Consider targeting 1.0–1.2 g/kg/day of dietary protein intake in patients on dialysis since protein energy wasting is a major problem in some patients on dialysis.

---

### Rehabilitation interventions need more than methodological standardisation: an individualised approach [^b61801f8]. BMJ Open Sport & Exercise Medicine (2020). High credibility.

Statistics

The non-injured group was used to create a 'performance database' to compare the injured individuals to. All of the trials were used from all the participants with the minimum value subtracted from the maximum value to create the range of values. This range of each physical performance characteristic was then normalised to 100 data points. Each of the best physical performance characteristics from the injured group, regardless of leg for the unilateral tests, was then compared to the normalised range to provide a score of performance with a score of 100 being the highest performing score. Shorter times (completion times, ground contact times, time to stabilisation and jump time) were judged as higher performing, all other physical performance characteristics as the larger the value, the higher the performance.

A decision was made to select five injured participants for analysis due to the difficulty in displaying individual data from all participants. An objective selection criterion was set by using the five participants with the largest Mahalanobis Distance to the non-injured performance database. The Mahalanobis distance (MD) was calculated for every subject within the injured group using the physical performance characteristics (x i, n) to the average of the corresponding physical performance characteristics from the non-injured group (μ n) and was defined as:

Where n is the row of the physical performance characteristic within the database, i the subject, and S is the covariance matrix of the physical performance characteristics. All data used in this calculation are raw.

The authors recognise that the MD will be a novel measure for many readers. The MD is a measure of the distance from the centroid, which can be thought of as the overall mean for multiple variables. For example in the 110° cut, it can be thought of as the overall mean of the completion time, the ground contact time and the horizontal to vertical ratio. The MDs for each injured individual are, using the example above, the distance of that individual's 110° cut overall mean from the overall mean of the non-injured performance database of 110° cuts. The MD was calculated for each of the tests which generated 6 MD scores for each injured participant, one for each of the physical performance tests. A mean of the MDs was then calculated for each participant with the five largest mean MDs selected to be displayed within the results as the five participants that most differed from the performance database. These five participants will be hitherto referred to as the 'analysed' participants.

---

### Guidelines for the prevention and treatment of opportunistic infections in children with and exposed to HIV [^beefde85]. HIV.gov (2025). High credibility.

Isosporiasis (Cystoisosporiasis) — treatment in children with or exposed to HIV: First-choice therapy is trimethoprim-sulfamethoxazole (TMP-SMX) 5 mg/kg body weight of the TMP component (maximum 160 mg TMP) twice daily by mouth for 10 days. An alternative is pyrimethamine 1 mg/kg body weight (maximum 25 mg) plus folinic acid 5–15 mg by mouth once daily for 14 days. Second-line alternatives include ciprofloxacin 10–20 mg/kg body weight (maximum 500 mg) by mouth twice daily for 7 days or nitazoxanide for 3 consecutive days with age-based dosing: 1–3 years, 100 mg by mouth every 12 hours; 4–11 years, 200 mg by mouth every 12 hours; adolescents aged ≥ 12 years and adults, 500 mg by mouth every 12 hours. If symptoms worsen or persist, the TMP-SMX dose (5 mg/kg/dose of the TMP component) may be given more frequently (e.g., 3–4 times daily by mouth for 10 days) and/or duration may be increased to 3–4 weeks; the optimal duration of retreatment with pyrimethamine has not been established. Ciprofloxacin is not a drug of choice in children because of increased incidence of adverse events, including events related to joints and/or surrounding tissues.

---

### EASL clinical practice guidelines for the management of patients with decompensated cirrhosis [^38f5fcd0]. Journal of Hepatology (2018). Medium credibility.

Regarding therapeutic procedures for ascites, more specifically with respect to therapeutic paracentesis, EASL 2018 guidelines recommend to administer albumin (8 g/L of ascites removed) for plasma volume expansion in patients undergoing large-volume paracentesis of > 5 L of ascites.