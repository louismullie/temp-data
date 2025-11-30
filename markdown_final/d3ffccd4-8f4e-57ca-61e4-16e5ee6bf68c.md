# Medical Question & Answer

**Sample ID**: d3ffccd4-8f4e-57ca-61e4-16e5ee6bf68c
**Dataset Index**: 192301

---

## Question

15. A flag is in the shape of a right-angled triangle, as shown, with the horizontal and vertical sides being of length $72 \mathrm{~cm}$ and $24 \mathrm{~cm}$ respectively. The flag is divided into 6 vertical stripes of equal width.
What, in $\mathrm{cm}^{2}$, is the difference between the areas of any two adjacent stripes?

A 96
B 72
C 48
D 32
E 24

---

## Answer

> Let's see… What do we have here? The user is asking for the difference in area between any two adjacent vertical stripes in a right-angled triangle flag with a 72 cm horizontal side and a 24 cm vertical side, divided into 6 vertical stripes of equal width. Let's break this down step-by-step. First, I need to think about the geometry and how the stripes are defined. Then, I should calculate the width of each stripe. Next, I will determine the heights of the stripes at their left and right edges using similar triangles. After that, I will compute the area of each stripe as a trapezoid. Finally, I will find the difference between adjacent stripes and verify the pattern is consistent across all pairs.

> Let me first confirm the setup: the flag is a right triangle with base 72 cm and height 24 cm, and it is divided into 6 vertical stripes of equal width, so each stripe has width 72 cm divided by 6, which is 12 cm. Wait, let me verify that division: 72 ÷ 6 = 12, yes, each stripe is 12 cm wide horizontally.

> Now, I need to think about the heights of the stripes. Because the triangle tapers linearly from bottom to top, the height at any horizontal position x from the left is given by similar triangles: height(x) = 24 cm × (1 − x/72). Hold on, I should verify that formula: at x = 0, height is 24 cm, and at x = 72 cm, height is 0 cm, which matches the triangle, so the linear scaling is correct.

> Next, I will calculate the left and right heights for each stripe. Stripe 1 spans x = 0 to 12 cm, so its left height is 24 cm and its right height is 24 × (1 − 12/72) = 24 × 5/6 = 20 cm. Stripe 2 spans x = 12 to 24 cm, so its left height is 20 cm and its right height is 24 × (1 − 24/72) = 24 × 2/3 = 16 cm. I should double-check the pattern: each step rightward decreases the height by 4 cm, so the heights at the right edges are 20, 16, 12, 8, 4, and 0 cm respectively, which aligns with the linear taper.

> I will now compute the area of each stripe as a trapezoid: area = width × (left height + right height)/2. For stripe 1: 12 × (24 + 20)/2 = 12 × 22 = 264 cm². For stripe 2: 12 × (20 + 16)/2 = 12 × 18 = 216 cm². For stripe 3: 12 × (16 + 12)/2 = 12 × 14 = 168 cm². For stripe 4: 12 × (12 + 8)/2 = 12 × 10 = 120 cm². For stripe 5: 12 × (8 + 4)/2 = 12 × 6 = 72 cm². For stripe 6: 12 × (4 + 0)/2 = 12 × 2 = 24 cm². Wait, let me verify one of these: stripe 3 should indeed be 168 cm², and 12 × 14 is 168, so the arithmetic checks out.

> Next, I should find the difference between adjacent stripes. The differences are: 264 − 216 = 48 cm², 216 − 168 = 48 cm², 168 − 120 = 48 cm², 120 − 72 = 48 cm², and 72 − 24 = 48 cm². Hold on, I should verify that last subtraction: 72 − 24 is 48, yes, so every adjacent pair differs by exactly 48 cm².

> Therefore, the difference between the areas of any two adjacent stripes is 48 cm², which corresponds to option C. I should confirm there isn't a trick I'm missing about orientation or counting; the problem is symmetric in the sense that moving from left to right or right to left yields the same absolute difference, and the linear taper ensures a constant area decrement between neighbors, so the answer is consistent across all adjacent pairs.

---

The difference between the areas of any two adjacent vertical stripes is **48 cm²**. This arises because each stripe is a trapezoid whose height decreases linearly from the base to the apex; the area difference between adjacent trapezoids is constant and equals the product of the stripe width (12 cm) and the height difference per stripe (4 cm), giving 48 cm².

---

## Step-by-step solution

### 1. Calculate the total area of the triangle

The area of a right-angled triangle is given by:

[
\\text{Area} = \\frac{1}{2} \\times \\text{base} \\times \\text{height}
]

Substituting the given dimensions:

[
\\text{Total area} = \\frac{1}{2} \\times 72, \\text{cm} \\times 24, \\text{cm} = 864, \\text{cm}^2
]

---

### 2. Determine the width of each stripe

The flag is divided into 6 vertical stripes of equal width, so:

[
\\text{Stripe width} = \\frac{72, \\text{cm}}{6} = 12, \\text{cm}
]

---

### 3. Analyze the geometry of the stripes

Each stripe is a trapezoid with:

- **Base**: 12 cm (width of the stripe)
- **Height**: varies linearly from the bottom to the top of the triangle

The height of the triangle decreases linearly from 24 cm at the base to 0 cm at the apex. Therefore, the height difference between adjacent stripes is constant.

---

### 4. Calculate the height difference between adjacent stripes

The total height of the triangle is 24 cm, and there are 6 stripes. The height difference between adjacent stripes is:

[
\\text{Height difference} = \\frac{24, \\text{cm}}{6} = 4, \\text{cm}
]

---

### 5. Calculate the area difference between adjacent stripes

The area of a trapezoid is given by:

[
\\text{Area} = \\frac{1}{2} \\times (\\text{sum of parallel sides}) \\times \\text{height}
]

For adjacent stripes, the difference in area arises from the difference in the heights of the trapezoids. The difference in area between any two adjacent stripes is:

[
\\text{Area difference} = \\text{stripe width} \\times \\text{height difference} = 12, \\text{cm} \\times 4, \\text{cm} = 48, \\text{cm}^2
]

---

## Verification

To verify, consider the areas of the first two stripes:

- **First stripe**: trapezoid with heights 24 cm and 20 cm

[
\\text{Area}_1 = \\frac{1}{2} \\times (24 + 20) \\times 12 = 264, \\text{cm}^2
]

- **Second stripe**: trapezoid with heights 20 cm and 16 cm

[
\\text{Area}_2 = \\frac{1}{2} \\times (20 + 16) \\times 12 = 216, \\text{cm}^2
]

- **Difference**: (264–216 = 48, \\text{cm}^2)

This confirms the earlier result.

---

The difference between the areas of any two adjacent stripes is **48 cm²**.

---

## References

### Gustatory thalamic neurons mediate aversive behaviors [^6ba208aa]. Nature Communications (2025). High credibility.

Conditioned place preference (CPP)

Mice underwent a 4-day conditioned place preference paradigm protocol in a rectangular CPP box. The CPP box is divided equally into two 20 × 20 × 30 cm square boxes with a 6.5 × 30 cm slide door connected in the middle. These two square boxes differ in wall decoration with vertical stripes one side and spots on the other side. The vertical striping chamber also contains two triangular blocks in the corner. On day 1, Mice were placed in the middle of the CPP chamber and allowed free exploration for 30 min with open access to both striped and dotted chambers. On day 2 and day 3, mice were i.p. injected with Saline (10 ml/kg) and immediately moved to the saline-paired chamber (either the vertical stripe or circled dot chamber) with the door closed. Mice were allowed free exploration in the saline-paired chamber for 30 min. Five hours later, mice received the same volume of U50 (5 mg/kg) through i.p. injection and were moved immediately to the other chamber paired with U50. Mice were allowed free exploration in the U50-paired chamber for 30 min and returned to their home cage after. On day 4, mice were placed in the middle of two chambers and allowed to freely explore both sides for 10 min. The time spent on each side was measured and averaged using the video-tracking software, EthoVision XT 15 (Noldus, Virginia, USA), to calculate the conditioned preference.

---

### Footprint-C reveals transcription factor modes in local clusters and long-range chromatin interactions [^6b316214]. Nature Communications (2024). High credibility.

Loop classification

Loops were annotated and categorized into promoter-promoter (Pro-Pro), promoter-enhancer (Pro-Enh), enhancer-enhancer (Enh-Enh), structural between A compartments (A-A structural), structural between B compartments (B-B structural), or other loops based on the annotation of active TSS, H3K27ac ChIP-seq peaksand PC1 values from Footprint-C data. H3K27ac peaks were called from K562 H3K27ac ChIP-seq dataset using MACS2. RNA-seq data was used to annotate active TSS. Firstly, we extended anchors ± 10 kb. Anchors containing active TSS were defined as Pro. Secondly, remaining anchors containing H3K27ac peaks were defined as Enh. Thirdly, remaining anchors were further defined as structural A or B anchors based on the PC1 value of anchors. Pro-Pro, Pro-Enh, Enh-Enh, A-A structural, and B-B structural loops were defined by the respective annotation of the two anchors.

Stripe calling

Stripes were called from contact matrices using Stripennor StripeCaller. The stripes were called by Stripenn at 5-kb resolution with the following settings: -m 0.95,0.96,0.97,0.98,0.99 -p 0.1. Stripes were called by StripeCaller with the following settings: — local-num 2 — fold-enrichment 1.1 — min-seed-len 6. Pile-up plots of stripes were obtained using coolpup.py, with the following settings: — local — rescale. The loop domains in Supplementary Fig. 4k were annotated by horizontal and vertical stripes obtained by Stripenn, and were divided into four types of left-, right-, both-sided, and no stripe loops. The loop domains were divided into 50 equally distanced intervals. The left or right anchors were extended 10 intervals forward or backward respectively. The percentage of loops overlapping with 1 V sites in each interval were calculated.

Insulation score analysis

The insulation scoreswere calculated at 40-kb resolution using the cooltools package.

Compartment analysis

The compartments were identified at 100-kb resolution using cooltools package. The eigenvector of the first principal component represents the compartment profile, with positive and negative values representing A and B compartments respectively.

---

### Rapid active zone remodeling consolidates presynaptic potentiation [^13e85582]. Nature Communications (2019). High credibility.

To investigate the AZ structure in an approach independent of the cluster-distance minimization procedure described above, we repeated the averaging in a different way as follows. We developed a MATLAB code for AZ centering and alignment by rotation of the highest intensity pixel to identical angles and therefore similar positions, which yielded qualitatively similar results (Supplementary Fig. 3a). Again, high-intensity clusters were detected in AZ images cleaned from clusters belonging to bordering AZs, and all translations and rotations were then performed on unretouched images. The center of mass of the found cluster coordinates was calculated and the image shifted so that the center of mass of the coordinates was in the center of the 51 by 51 pixel space (x = y = 26; see Eqs. (1) to (6)). Only the position of the brightest pixel was then considered for rotation. To determine the angle by which to rotate each image to place this highest intensity pixel to the same fixed position (on the vertical midline between the two top image quadrants — the "twelve o'clock" position), the x and y distances to the center of rotation (equal to the center pixel of the image x = y = 26) were calculated to find the length (l) of the hypotenuse and the opposite side of the right triangle using pdist. The angle α in degrees was then calculated by taking the inverse sine in degrees of this value (MATLAB function asind), as shown in Eq. (9). In cases where the brightest peak was located above the horizontal midline, the adjacent side of the triangle was the vertical midline. In cases where the brightest peak was located below the horizontal midline, the angle was calculated with the horizontal midline being the adjacent side, and 90° were added to the final angle value. Additionally, in cases where the brightest peak was located to the right of the vertical midline, the angle was multiplied with −1. To generate the results shown in Supplementary Fig. 3b, which shows the averaging of AZ images within randomly assigned categories, we generated a number of random category values and then proceeded with the averaging procedure described above. For this, we reproduced the distribution of category values from the AZ dataset according to the histogram values of the category vector as follows. A histogram of the category vector was generated (MATLAB function histogram) with a bin width of 1, yielding the absolute amount of AZs per category. A cumulative sum vector was calculated from these histogram values (MATLAB function cumsum). For each position in the category vector, we then chose a random number between 0 and 1 and multiplied it by the number of images. We then found the first position in the cumulative sum vector that was larger than this random value. The position found was equal to the assigned category. This resulted in a randomly assigned category vector with a similar distribution of categories as the original vector.

---

### Boundary-directed epitaxy of block copolymers [^eef4826e]. Nature Communications (2020). High credibility.

Directed self-assembly of block copolymers (BCPs) enables nanofabrication at sub-10 nm dimensions, beyond the resolution of conventional lithography. However, directing the position, orientation, and long-range lateral order of BCP domains to produce technologically-useful patterns is a challenge. Here, we present a promising approach to direct assembly using spatial boundaries between planar, low-resolution regions on a surface with different composition. Pairs of boundaries are formed at the edges of isolated stripes on a background substrate. Vertical lamellae nucleate at and are pinned by chemical contrast at each stripe/substrate boundary, align parallel to boundaries, selectively propagate from boundaries into stripe interiors (whereas horizontal lamellae form on the background), and register to wide stripes to multiply the feature density. Ordered BCP line arrays with half-pitch of 6.4nm are demonstrated on stripes > 80nm wide. Boundary-directed epitaxy provides an attractive path towards assembling, creating, and lithographically defining materials on sub-10nm scales.

---

### Trajectory discrimination and peripersonal space perception in newborns [^9e5fc277]. Infancy (2017). Low credibility.

During the experiment, the monitor (24″) showed a gray background containing two peripheral black areas, where the stimuli appeared. Both were 24.4 cm wide and 20.4 cm high; they were both 0.85 cm apart from the nearest edge of the screen and 1.6 cm apart from one another; they were both 6 cm apart from the top and the bottom of the screen. At the beginning of AC and ANC stimuli and at the end of the R one the ball subtended a visual angle of 23.54° × 23.54°; on average, the width of the stripes subtended a visual angle of 2.94°. The ball was 3.2 cm apart from the nearest edge of the frame and 14 cm apart from the farthest and was 6.6 cm apart from the top and the bottom of the frame. At the end of the AC stimulus and at the beginning of the R one, the ball subtended a visual angle of 37.70° × 37.70°; on average, the width of the stripes subtended a visual angle of 4.71°. The ball was 5.3 cm apart from both edges of the frame and was 3.3 cm apart from the top and the bottom of the frame. At the end of the ANC stimulus, the ball subtended a visual angle of 34.70° × 34.70°; on average, the width of the stripes subtended a visual angle of 4.33°. The ball was 3.2 cm apart from the nearest edge of the frame and 11.2 cm apart from the farthest and was 5.2 cm apart from the top and the bottom of the frame. The luminance of the display was 0.5 cd/m 2 for the black frames and 54 cd/m 2 for the gray background; it was instead 78 cd/m 2 for the white stripes of the moving ball and 108 cd/m 2 for the lightest part of it (highlight). We provided the infants with high contrast stimuli in order to enhance their attention toward them; in fact, Michelson contrast between the black frames and the gray background was −0.982, between the white stripes of the ball and the black frames it was 0.987, and between the highlight of the ball and the black frames it was 0.991. The black curtain surrounding the monitor had a luminance of 0.2 cd/m 2 and the room was poorly lit in order to ensure that the newborns' attention was focused toward the screen (average walls luminance was 30 cd/m 2; average ceiling luminance was 15 cd/m 2). All measures were taken from the infant's position during the experiments, and the ambient lighting while measuring was the same as the average lighting of the room while testing was conducted. The speed of our stimuli resulted from the combination of the length of the path that the recorded ball had to travel (35.51 cm for AC and R; 30 cm for ANC) and a display time long enough to ensure that the newborns' attention could be engaged. The resulting speed of the ball in the AC and R stimuli was 10.6 cm/sec, whereas in the ANC stimulus, it was 9 cm/sec. We were not concerned about the effect that the speed of the moving stimulus could have on the discrimination of the different trajectories. In fact, previous studies did not use stimuli moving with a consistent speed and their results indicated that even wide variations in the looming speed (i.e. from 6 to 48 cm/sec) did not have any impact on infants' reactions (Náñez, 1988). Each stimulus moved for 3,333 msec, preceded and followed by 10 frames (333 msec) where the ball stood still (during the last one contrast was reduced, favoring a fading effect), for an overall stimulus duration of 4,000 msec. Each stimulus was presented eight times, with a 1‐sec interval between two subsequent presentations and 4,000 msec of blank screen before the first presentation, for an overall trial duration of 44 sec.

---

### Anisotropic encoding of three-dimensional space by place cells and grid cells [^a8aebe5f]. Nature Neuroscience (2011). Medium credibility.

The subjective sense of space may result in part from the combined activity of place cells in the hippocampus and grid cells in posterior cortical regions such as the entorhinal cortex and pre- and parasubiculum. In horizontal planar environments, place cells provide focal positional information, whereas grid cells supply odometric (distance measuring) information. How these cells operate in three dimensions is unknown, even though the real world is three-dimensional. We investigated this issue in rats exploring two different kinds of apparatus: a climbing wall (the 'pegboard') and a helix. Place and grid cell firing fields had normal horizontal characteristics but were elongated vertically, with grid fields forming stripes. It seems that grid cell odometry (and by implication path integration) is impaired or absent in the vertical domain, at least when the rat itself remains horizontal. These findings suggest that the mammalian encoding of three-dimensional space is anisotropic.

---

### Model mimicry limits conclusions about neural tuning and can mistakenly imply unlikely priors [^f18dc9ec]. Nature Communications (2025). High credibility.

Fig. 2
Cardinal anisotropies for orientation decoding are specific to central stimuli in EEG. Stimulus positions and sizes (top) are shown to scale.

Dashed lines depict the vertical and horizontal meridians. Black horizontal line illustrates 10° visual angle from fixation. A Re-analyzes of experiments reported by Harrison and colleagues(left: n = 36) and Wolff and colleagues(right: n = 24) where central orientations were shown to participants. Line plots show mean-centered Mahalanobis distance-based decoding metrics as a function of orientation, with shaded areas indicating the cardinal orientation bins used to compute differences between horizontal (green) and vertical (purple) orientations. Blue error areas are 95% confidence intervals (C. I.). The box plots show decoding metric differences for horizontal minus vertical orientations, with box limits indicating the upper and lower quartiles of the data, whiskers indicating 1.5 times the inter-quartile range, and blue dots representing individual subjects. The superimposed black circle and error-bars indicate the mean and 95% C. I. Top: Mean-centered accuracy (mean-centered cosine vector mean of pattern similarity curve), Middle: Mean-centered precision (1 minus the circular standard deviation of decoded orientation across trials), Bottom: Bias of pattern similarity curves, in degrees. Both data-sets show statistically significant differences between horizontal and vertical orientations), with higher decoding for horizontal orientations (both p < 0.001), higher precision for horizontal orientations (left: p < 0.001, right: p = 0.003), and a stronger attraction toward vertical orientations (both: p < 0.001). Tests were two-sided permutation t-tests (10.000 permutations). No adjustments for multiple comparisons were made. B Re-analyzes of experiments with orientations presented laterally, (left: n = 30; right: n = 26) to the left and right of fixation, at an eccentricity of 6.69° or 6.08° (for data fromand, respectively). Same conventions as in A. No consistent differences between horizontal and vertical orientations. (Decoding accuracy difference, left: p = 0.315, right: p = 0.232; precision difference, left: p = 0.837, right: p = 0.895; attraction difference, left: p 0.43, right: p = 0.236; two-sided, not corrected for multiple comparisons). Source data are provided as a Source Data file.

---

### Boundary-directed epitaxy of block copolymers [^bee52b79]. Nature Communications (2020). High credibility.

Fig. 5
Monte Carlo simulations.

Simulated BCP morphology at the free (top) surface (top left), at the substrate (bottom) surface (top right), and along a cross-section perpendicular to the stripe width (bottom) after 10 2 (a), 6. 5 × 10 4 (b), 1.25 × 10 5 (c), 1.8 × 10 5 (d), 3.0 × 10 5 (e), and 2.15 × 10 6 (f) MC cycles. The stripe, substrate, B block, and A block are green, gray, blue, and red, respectively. White dashed lines indicate the positions of the stripe/substrate boundaries. White dotted lines in b, e, f highlight an antiphase transition between horizontal lamellae, a set of slanted lamellae, and an L-junction, respectively. Since vertical B lamellae and horizontal B lamellae connect via L-junctions along the stripe edge at the free surface, it is difficult to differentiate these two domains in the top view in f. In contrast, in SEM images of the free surface (e.g. Figs. 1–3), vertical PS lamellae on the stripe display different contrast than horizontal PS lamellae on the substrate because the former domains are through-film while the latter domains are on top of at least one horizontal PPC domain.

The slanted lamellae act as a template to convert the lamellar domains on the stripes from horizontal to vertical. Specifically, the bottommost A lamella on the substrate curves upward to form a through-film domain directly bordering the stripe edge. This slanted A lamella nucleates the formation of a vertical B lamella on the stripe at the stripe/substrate boundary, which subsequently induces the formation of a vertical A lamella at the stripe center. Similar evolution is observed when the stripe width is increased to 2.5 L 0 and 3.5 L 0, accompanied by the formation of additional vertical A and B lamellae in the stripe interior (Supplementary Fig. 23). Slanted lamellae therefore drive the nucleation of and pin vertical lamellae along the stripe edges, mimicking sidewalls in graphoepitaxy; here, however, the first vertical lamellae nucleate spontaneously to form at stripe/substrate boundaries without predefined topographic features.

---

### Prominent effects and neural correlates of visual crowding in a neurodegenerative disease population [^527ea900]. Brain (2014). Low credibility.

Task 3: Shape flankers

Target letters (n = 24) were flanked on each side by a triangle presented at different orientations. Triangles were of equal height and line thickness to target letters.

Task 4: Number flankers

Target letters (n = 24) were flanked on each side by an Arabic numeral, chosen from a range between 2 and 9.

Task 5: Same-polarity flankers

Target letters (n = 24) were flanked on each side by black letters; presentation was as Task 2 except that items were presented on a grey background to match Task 6 (see below).

Task 6: Reverse-polarity flankers

Target black letters (n = 24) were flanked on each side by white letters, all presented on a grey background.

The edge-to-edge distance between the target letter and flankers was 0.1° of visual angle in the condensed condition and 1.0° in the spaced condition at a viewing distance of 50 cm; the height of stimuli (10.5 mm) corresponded to a visual angle of 1.20°. Participants were given one prompt for each trial where they named the flanker ('Is that the letter in the middle?'); this prompt was intended to limit errors resulting from visual disorientation. The same combination of flankers was used for each target letter under both spatial conditions within each flanker condition. Alphabetic items occurred with equal frequency within each task. The stimuli were presented in blocks of six items, with blocks being administered in an ABBA design. All flanked stimuli were presented in the centre of the screen within a fixation box (6.4° in width, 2.9° in height). All 26 patients with PCA completed Tasks 1, 2 and 4; 24 completed Task 3; and 22 completed Tasks 5 and 6. Naming latencies were manually determined from the onset of each letter using Audacity.

Data analysis

---

### Twisted moiréconductive thermal metasurface [^f8d6fd6d]. Nature Communications (2024). High credibility.

Theoretical verification of thermal magic angle in twisted metadevices

To verify our twisted model designed above, the finite-element simulations have been performed with the software COMSOL MULTIPHYSICS. Firstly, for the background with arbitrary thermal conductivity, the corresponding thermal conductivityof region II can be derived based on the corresponding matching function. Then, this metadevice still works with the change ofdetermined by Eq. (S19) via twisted manipulations owing to the satisfaction of the matching function.

To start, the temperature profiles of the theoretical twisted model are presented in Fig. 2a, b. Obviously, it is easy to understand that the heat flux bending angle disappears by twisting an equal angleandin opposite directions based on the heat flux direction, respectively. It can be observed from the simulation results (Fig. 2a) that when the twist angles are both zero degrees, the isotherms of the background are almost without distortion and those in region IV almost vanish, exhibiting the realization of a thermal cloak. However, since the effective thermal conductivity in Region IV changes dramatically with a tiny increase of twisted angles, the isotherms of the background are almost still without distortion while the interval of the isotherms in Region IV turns out to be narrower compared with those of the background, indicating the realization of a cloak-to-concentrator. Moreover, for the central region, the effective thermal conductivity and temperature gradient along the measured line of y = 0 cm with corresponding simulated results as a function of twisted angle difference are presented in Fig. 2c, d, respectively. Interestingly, it is easy to observe that the positions of peak value of numerical curves (Fig. 2d) with the decrease of the stripe width w are governed by Eq. (6). Meanwhile, the width w of stripe and radius R 1 could theoretically elicit the maximum value of temperature gradient related to the twisted angle, indicating the possibility to imitate a thermal magic angle. In short, when the thermal analog of the magic angle governed by Eq. (6) is achieved and the effective thermal conductivity in region IV can be approximately calculated by Eq. (S19), the switchable effect emerges.

Fig. 2
Theoretical and simulated twisted thermotics.

a, b Results of the temperature profiles for the twisted angleswith a and b. c, d The dependences of c the effective thermal conductivityand d temperature gradient on the angle difference.

---

### Discretized representations in V1 predict suboptimal orientation discrimination [^32b9edfb]. Nature Communications (2025). High credibility.

Fig. 6
Cosine similarity between the representations of the task and tuning block stimuli.

a Trial-averaged APrE activity of 206 neurons simultaneously recorded in an example session (Go/NoGo angle = 90°), during the presentation of the Go (top panel) and NoGo cues (bottom panel). In both panels, neurons are ordered as a function of their response intensity to the Go stimulus presentation. b Cosine similarity between the neuronal activity patterns evoked by the Go and NoGo cues that are shown in (a). c Same representation as in (b) for all the Go/NoGo angles of all the mice (thin grey lines: individual mice; colored lines: averages across mice). d Mouse behavioral performance (D') as a function of the average cosine similarity between the Go and NoGo neuronal responses during the first 2 s of the visual stimulus presentation. The color code for individual sessions corresponds to the one used in (c). Black shapes indicate the mean across mice for the different Go/NoGo angles. Vertical colored lines indicate the cosine similarity measured during the baseline activity immediately preceding the visual stimulus (duration: 1 s, see colored horizontal lines in (c)). The horizontal dotted line indicates the maximum D' that can be obtained with random performance. e Self-similarity computed using 1000 random 2-half splits of the Go (left) or NoGo (right) trials for the 90° and 15° Go/NoGo angles. Same color code as in (c). f Self-similarity and Go/NoGo similarity for all sessions (n = 10) and Go/NoGo angles. Paired Wilcoxon test, ✱✱ p < 0.001, ✱✱ p < 0.01. g Activity evoked in the orientation space by the 30° and 60° stimuli of the tuning curve block in trained (top) and naïve (bottom) animals h. Average cosine similarity between all pairs of tuning block stimuli in trained (upper triangle) and naive (lower triangle) animals. i Average difference between trained and naive mice of the z -scored similarity measured for each pair of adjacent stimuli. The shaded area indicates the bootstrapped 95% confidence interval.

---

### Theory of branching morphogenesis by local interactions and global guidance [^34973bae]. Nature Communications (2021). High credibility.

Comparison between analytical model and simulations

Importantly, Eq. (1) describing the probability of branch orientation attains a steady-state solution (∂ t P st (ψ, t) = 0) that is largely independent of the form of the external field, i.e. it applies generically to different geometries after defining the relative branch alignment with respect to the external field. This solution predicts that the alignment of angles with respect to the polarity of the external field will be determined by the von Mises distribution (circular normal distribution):with a concentration parameter given by ν ≡ μ f c / D, and I 0 (ν) is the modified Bessel function of the first kind of order zero. The fluctuations in the angular alignment as determined by the variance will thus follow a universal scaling approximately given by σ 2 ∝ D / μ f c that underlines the relative contribution of the local noise to the external guidance. For an axial (linear) field parallel to the horizontal axis, for instance, the above solution applies to the distribution of the local angles φ of the branch segments (Fig. 1 d). In a radial external field emerging from a central point of origin, however, the alignment of a branch is determined by the angle difference ψ ≡ φ − θ between its local angle φ and its angle θ with respect to the origin of the external field, and thus ψ, rather than φ, is predicted to follow the von Mises distribution (see Supplementary Figs. 4–9 for the alignment angles for different model assumptions). Comparing these analytical criteria with the numerical simulations led to excellent agreement without using any fit parameter (Fig. 1 d–f).

To summarize, the combination of analytical modelling and numerical simulations allows us to make a number of predictions for different topological and geometrical properties of branched structures: A key signature of external guidance is that branching angles should conform to a von Mises distribution while the overall branching structure in an axial field can adopt a well-defined conical domain in the absence of defined boundaries. Furthermore, a signature of the stochastic nature of branching and annihilating random walks is that even with external guidance, the local branch length or overall network size and shape should be highly variable to random branching events and local density-driven termination of tip growth.

---

### Is the middle between both halves? midpoint location and segment size estimation in neglect [^b7e5475a]. Neurology (2002). Low credibility.

Background

Line bisection errors in neglect are attributed to perceptual size distortions. In order to compare the two segments of the line to determine if they are equal, one might first estimate the location of a midpoint that defines the two line segments to be compared.

Objectives

The authors attempted to determine whether estimating a line's midpoint can be dissociated from comparing the two segments of this line, and if so, what the relative contribution of each of these tasks is to the perceptual bias in neglect.

Methods

The authors studied two patients with hemispatial neglect from right hemisphere lesions by asking them where bisection marks were placed on prebisected lines and whether the two adjacent line segments were equal.

Results

There was a stronger bias judging the position of the bisecting marks ("where" determination) than comparing the size of two adjacent line segments.

Conclusions

These results suggest that perceptual size distortion of line segments alone cannot explain the subjects' line bisection bias, but postperceptual deficits in "where" computations may better account for their errors locating the midpoint. "Where" determinations might require more attentional capacity, depend more heavily on viewer-centered allocation of attention, and be mediated by the right hemisphere's "where" dorsal stream. In contrast, comparing the length of two segments might be mediated by the left hemisphere's "what" ventral stream.

---

### The 30-degree angle revisited [^eec48357]. Journal of the American Academy of Dermatology (2005). Low credibility.

The standard surgical ellipse, with 30 degrees apical angles and a length-to-width ratio of 2 or 3 to 1, works optimally on a flat surface. The same pattern, when used for excisions on strongly convex or concave surfaces, leads to distortions which may require significant revisions. The reason for these discrepancies is explainable by the mathematical differences between flat Euclidian geometry and curved non-Euclidian geometry. Understanding these basic mathematical principles as applied to cutaneous surgery should lead to better preoperative planning, fewer intraoperative surprises, and more pleasing results.

---

### Homeostatic plasticity of eye movement performance in xenopus tadpoles following prolonged visual image motion stimulation [^c3ad733c]. Journal of Neurology (2023). Medium credibility.

Visual motion stimuli, optokinetic training, and eye motion recording

For eye motion recordings, semi-intact preparations were mechanically secured dorsal side-up in the center of a Sylgard-lined circular dish (Ø 5 cm), surrounded by a visual virtual reality environment as described previously (Fig. 1 a;). The visual environment consisted of equally spaced, vertical black and white stripes subtending a visual angle of 16° per stripe. This pattern was projected onto a cylindrical screen (275° coverage, Ø 8 cm, 5 cm height; Fig. 1 a) at 60 Hz by three digital light processing video projectors (Aiptek V60), affixed in 90° angles to each other on the experimental table. For the optokinetic training, the visual image motion pattern was continuously oscillated horizontally to the left and right for 30 min (Fig. 1 b). Stimulus motion consisted of alternating bidirectional movements at two velocities: 4°/s or 8°/s, presented at different stimulus cycle durations — for 10 s or for 20 s — to generate visual image motion with different peak-to-peak position amplitudes. Accordingly, these stimulus parameter combinations produced four different profiles (Fig. 1 c), and correspondingly elicited OKR responses with different eye motion amplitudes. Each animal was tested for only one stimulus profile to avoid transferring a possible training effect from an initial training stimulus onto a subsequent one. Accordingly, each stimulus profile was separately tested on a group of animals naïve to any training stimulus.

Fig. 1
Stimulation and recording of the optokinetic reflex in semi-intact preparations of Xenopus laevis tadpoles. a Schematic illustrating the experimental setting with a Ringer-filled circular recording chamber hosting the preparation; horizontal motion of vertical black and white stripes across the surrounding cylindrical screen serves as large-field visual motion stimulus and elicits eye movements (double arrows). b Representative example of horizontal positional oscillations of the eyes (lower trace) during prolonged (30 min) visual motion stimulation (upper traces), at the onset (left) and the end of the training period (right). c Single cycles of visual image motion profiles depicting the different combinations of stimulus velocities of either 4°/s (1, 4) or 8°/s (2, 3), presented in bidirectional alternation with a cycle duration of either 20 s (1, 2) or 10 s (3, 4)

---

### How to evaluate agreement between quantitative measurements [^7316afc8]. Radiotherapy and Oncology (2019). Medium credibility.

When a method comparison study is performed, the aim is to evaluate the agreement of measurements of different methods. We present the Bland-Altman plot with limits of agreement as the correct analysis methodology. We also discuss other scaled and unscaled indices of agreement and commonly used inappropriate approaches.

---

### Semantic priming modulates the strength and direction of the kanizsa illusion [^abb1ff18]. Communications Psychology (2025). Medium credibility.

Based on the pilot experiments, the illusory triangle's sides were set to be 3.9 × 3.4 × 3.4 cm (4.53.9visual angles). It was positioned a bit over the vertical center of the screen (8.6° from the bottom of the screen, 7.2° from the top) and in the left of the horizontal center (11.1° from the left screen border, 17.2° from the right). Other sliced circles were at least 1 cm (1.1° visual angles) distant from the three Kanizsa inducing circles. The background of the pictures and instructions was black. The instructions were written in white Hebrew letters, in David font.

The Pac-Man prime in Experiment 1 was a screenshot taken from the "Pac-Man" video game, presenting a Pac-Man gameboard maze (see again Fig. 1 for illustration). The Pac-Man character itself was removed from the picture to prime only the general context of the game and not the character itself. The non-semantic "scrambled" prime was a scrambled version of the Pac-Man display picture, created using Adobe Photoshop CC2018's "Scramble" filter. Tile parameters were 0.52 cm height and 0.52 cm width (20 px × 20 px or 0.6° × 0.6° visual angles).

---

### Agreement between methods [^ce77f1f2]. Kidney International (2008). Low credibility.

Before new tests are implemented, it is important to compare their results with those of other measurement methods that are already in use. In the determination of this so-called agreement between methods, one may choose between several statistical approaches. The correlation coefficient is a popular approach to determine the agreement between measurement methods. It is easy to calculate, but has important limitations: it does not provide any information on the type of association and it is extremely sensitive to the range of values within the study. Finally, a correlation coefficient does not reveal whether any difference between two measurements is systematic or random. Therefore, it is highly preferable to use Bland-Altman plots instead, as these reveal both systematic and random errors. Bland-Altman plots are also preferable in case of repeated measurements and calibrations.

---

### Direct nanopatterning of complex 3D surfaces and self-aligned superlattices via molecular-beam holographic lithography [^1e3caf64]. Nature Communications (2025). High credibility.

Discussion

Beyond the ultra-fine resolution, the power of MBHL lies in its vast design space for beam trajectories. Theoretically, MBHL is capable of approximating any 2D periodic designby solving the optimal trajectory function F (x) from the deconvolution of Eq. (1). Although the exact inverse design poses challenges due to practical constraints from deposition systems, here we demonstrate a few examples of advanced patterns formed using few-beam MBHL interference. In the simplest = 2 interference illustrated in Fig. 2, where the azimuthal angles for the beam trajectory are, the angle displacementstrongly influences the interaction between neighboring deposits. Figure 6a–e show the spectrum of pattern morphologies achievable by adjustingon a square lattice nanoaperture with pore radius, center-to-center spacingand beam offset. Inspired by the ranking of periodic nanomaterials' dimensionality(see "Methods"), we created a comprehensive phase diagram of the pattern morphology as a function of the parameters, and, ranging from 0D (isolated particles) to 1D (stripes) and 2D (planar) geometries. Supplementary Fig. 11 demonstrates a similar phase diagram for hexagonal nanoapertures under such conditions. We also anticipate that a misalignment between the axis of mirror symmetry of the trajectory function and that of the nanostencil will lead to the formation of a geometrically chiral pattern. Figure 6f, g demonstrate the evolution of the geometric chirality in the MBHL deposition patterns forinterference on honeycomb nanoapertures (, top row) andinterference on square nanoapertures (, bottom row). By leveraging the concept of geometric overlap measure for planar chiral surfaces, we employ a chirality indexto evaluate the chirality of the formed surface patterns (see "Methods"):whereandare the mirror images of the deposition patterns on domain, anddenotes the translation by vectorfollowed by rotation of. For an achiral surface, whereasindicates a perfectly chiral surface. As shown in Supplementary Figs. 12 and 13, the continuous modulation of the geometric chirality of nanosurfaces can be achieved by simply tuning the angle displacement of the beam trajectory, which is otherwise a non-trivial task in other fabrication processes. Our numerical optimization via the CL model indicates that the maximumvalues for the honeycomb (Fig. 6f) and square (Fig. 6g) nanoapertures are 0.46 and 0.57, respectively, manifesting as propeller and gammadion, respectively. The capacity of the MBHL process for precise manipulation of overlap, dimensionality, and chirality offers vast potential for applications in nanophotonic and plasmonic devices. We foresee further innovative trajectory designs emerging from future research, expanding the functional scope of MBHL.

---

### Sources of confidence in value-based choice [^4f84ca43]. Nature Communications (2021). High credibility.

Fig. 5
The efficient coding model.

a The decision process with three distinct process stages, color-coded to match the graphs. The prior matches the distribution of subjective values v of supermarket products. When choosing between two items, subjects look repeatedly at them, spending unequal time on the two options. The subjective values are internally encoded, the corresponding likelihood functionis constrained by the prior p (v) via efficient coding. Lastly, noise that occurs after the decoding is taken into account. b Standardized posterior estimates of the relationship between confidence and variance in the encoding process, the variance in the comparison process, and attentional factors (β θ). is not significantly different from 0 (P = 0.39), both and (β θ) are significantly bigger than zero with P < 0.001. The effect size of is not significantly different from 0. Both the effect sizes of and (β θ) are significantly bigger than zero with P < 0.001. Error bars indicate the mean posterior estimate of the standard deviation. P -values are based on the highest density interval of the posterior estimates. c Left column: the empirical probabilities of choosing the upper item; up: as a function of value difference; down: as a function of the difference in dwell time. Right column: the same as left but for the predicted probabilities by the efficient coding model. The trials are median split in high/low confidence. Value difference and dwell time difference are split into eight groups of equal size. Data are presented as mean values ± SEM. Source data are provided as a Source Data file. d Comparison of parameter estimates of two alternative efficient coding models: a model with agent-specific estimates of σ enc and a model that allows for trial-to-trial fluctuations of σ enc. The median of the posterior estimate of σ enc of the agent-specific model is indicated by the horizontal green line, the shaded grey area indicates the 95% confidence interval. The diagonal green lines represent 100 random samples of the posterior distribution of how σ enc changes with confidence in the model allowing for trial-to-trial fluctuations. e, f Same as (e) but for σ comp and θ. g Comparison of the effect sizes of the posterior estimates of σ enc and σ comp. Vertical red dashed line indicates the median, black lines indicate the 95% confidence interval. h Comparison of the posterior estimates of the intercept of θ in the efficient coding model and the RUM. i Comparison of the posterior estimates of the slope of θ in the efficient coding model and the RUM. For the whole figure n = 33 independent participants.

---

### History… [^57e99693]. FDA (2025). Medium credibility.

2-B 57 More on Office of Generic Drugs 60 Office of New Drug Chemistry 60 Gleevec 66 Mylotarg – First Major Combination Product 68 Cypher Drug-Eluting Stent 70 Chloramphenicol 71 COX-2 Inhibitors. 72 Off-Label Drugs 72 Aspirin 72 Minoxidil 72 Viagra 3-A 73 Approval Process – Signatures 74 More on Mylotarg and Cypher Drug-Eluting Stent 74 Office of Combination Products 75 Working with Center for Devices. JES: The old Federal Building down there at 2nd and C. It's right behind where the Commissioner sits and right across the street from the Sam Rayburn Office Building and Independence Mall. As a matter of fact — this is a true story — I was walking from C Street to train. shorts and sneakers, because it was hot. At any rate, I'm walking towards the train station, and lo and behold, I see Senator Nancy Kassebaum, who is my representative from Kansas, walking across the street to the Dirksen Office Building.

So I walked up to her — she was wearing a purple. circulating in the blood. In order to get a drug in there to affect enough of the molecules requires a Herculean amount of material, and we never could get across that barrier where we could deliver enough drug to suppress the gelation to the point where it wouldn't causes crises. They've tried lots of things that will interrupt that process,… United States, in the various European countries and Canada, in Asia, and what one of the interesting things was, was the science of the formulation. Why did we approve the formulation we approved here, and how did it compare to some of the others. So we did an awful lot of formulation comparison. The requirements for dissolution testing of. JS: One of the great concerns when the 1962 amendments were passed, of course, is that the industry was promised that this would not involve comparative studies, particularly of drug effectiveness. JES: That's right.

JS: And so that movement that you just described kind of flies in the face of that.

---

### Diagnostic accuracy of the tsiogkaSpaeth grid test for detecting visual field defects in patients with glaucoma [^7eea2fc1]. BMJ Open Ophthalmology (2025). High credibility.

The TS grid

As it has been previously described, the TS grid is a new optotype, designed to detect defects in both the central and mid-peripheral VFs. It is designed to be printed on a typical A4 non-glossy paper sheet in a horizontal orientation (22.5 cm width and 17.8 cm height). The grid consists of 54 rectangles of a side length of 2.4 cm, 32 rectangles of side length of 1.2 cm and 16 rectangles of side length of 0.6 cm, arranged to fit precisely on the A4 paper. The smaller rectangles are placed at the centre of the grid, surrounded by the medium-sized rectangles, and then by the larger ones. This gradual increase in the size of the rectangles was employed in order to compensate for the decreased sensitivity when detecting defects in the periphery. In this way, a table is formed, in the shape of a rectangle. These rectangles alternately contain arrows of 3.15:1 (grey:white) contrast ratio, pointing in horizontal or vertical directions separated by empty rectangles in order to facilitate the patient and communication with the examiner. The direction of each arrow varies. Recognition of the direction in which each arrow is pointing does not require literacy in any language, does not require recognition of an object and has only one right answer. It is, also, easily incorporated into a forced-choice paradigm. In addition, the direction of each arrow does not follow a pattern in order to avoid memorisation. A small black circle is positioned at the centre of the optotype and uses the fixation point. Following the Amsler's grid configuration and design, each 5 mm rectangle on the TS grid subtends a visual angle of 1°e when the chart is held at 30 cm. Therefore, the central area of the TS grid subtends 4.8° horizontally and vertically, the paracentral area 15.4° horizontally and vertically and the entire TS grid 43.2° horizontally and 33.6° vertically. The TS grid is printed in two different forms. One has the arrows occupying one half of the sites, while the other has the arrows in the other half on the test's sites. Each eye is tested using both versions of the TS grid: the first TS grid is complementary to the second grid as shown in online supplemental figure 1a, b. So a total of four rounds is examined per patient. After correcting for near refractive error and leaning on a desk, each participant is asked to view the TS grid monocularly at a distance of 30 cm. To ensure the TS Grid is held face-on during testing, the person administering the test should place the test paper on a rigid, flat surface to keep the grid straight and prevent any bends or folds. The test should be conducted so that reflections from surrounding light are minimised, and patients are positioned so as to avoid glare. To maintain a consistent 30 cm distance from the patient's face, a ruler or a marked reference on the clinician's arm or desk is used. The patient may hold the grid themselves, but if the patient struggles, the clinician should help in holding the grid at the proper distance and position. The fellow eye is occluded with an eye patch. The examinee is instructed to fixate on the central black spot and to try to perceive the direction of the arrows with his/her peripheral vision. If the patient turns his/her eyes to the arrow, he/she is advised to return to the central area and to try to perceive if he/she finally can recognise it or not. During the first examination, the arrows are presented by the examiner to the patient so that the patient learns to recognise them. Patients are instructed to fixate at the central point of the grid at all times and asked to answer if she/he can see the direction of each arrow that is pointed to by the examiner with a pen or a laser pointer for improving focus and minimising distractions, in settings where such equipment is accessible, starting from the central area to the periphery. It is necessary for the person administering the test to return to each tested area once if he believes that the response was not accurate, in order to verify the first answer. Correct and incorrect responses are recorded by circling (indicating a correct response) or deleting (indicating a false response) on the main reference chart (online supplemental figure c) held by the examiner. If the patient cannot see an arrow, the procedure is repeated, and if she/he is still not able to see the arrow, the arrow is deleted from the chart. Ideally, testing with the TS grid test should be done at the beginning of the examination in order to avoid potential fatigue that could affect performance. A total TS score is summated from correctly answered rectangles, with 102 the perfect summed score from all rectangles.

---

### Overestimation of numerical distances in the left side of space [^fe092e52]. Neurology (2004). Low credibility.

Normal subjects presented with a middle number and two left- and right-sided outer numbers overestimate the numerical distance between the middle number and that positioned at its left side. Repetitive transcranial magnetic stimulation (rTMS) of the right posterior parietal cortex specifically counteracts this bias, suggesting that the mental representation of space defined by numbers is shifted toward the left side depending on a greater activity of the right hemisphere.

---

### Quantitative imaging metrics for the assessment of pulmonary pathophysiology: an official American Thoracic Society and Fleischner society joint workshop report [^6517cbfd]. Annals of the American Thoracic Society (2023). High credibility.

Basic stereological measurements — first-order parameters and probes identify that "First-order parameters are volume (three-dimensional [3D]), surface (two-dimensional [2D]), length (one-dimensional [1D]), and number (zero-dimensional [0D])". Measurements "are performed using geometric test probes, such as points (0D), lines (1D), planes (2D), or volumes (3D)". These probes create countable events in the image, and "Raw counts provide ratios… that are multiplied by the reference space volume to obtain absolute measures for the lung or subcompartment".

---

### Invariance properties of bacterial random walks in complex structures [^031312fd]. Nature Communications (2019). High credibility.

The effect of size and shape

We have demonstrated that, for a fixed shape, the density of obstacles has a strong effect on the distribution of path lengths while leaving the mean value unchanged as long as the total internal accessible area remains the same.

We will now investigate the effects of shape and size on the path length distributions and again conclude that, although path distributions are very sensitive to the detailed geometry of the domain, mean path lengths and residence times can be accurately predicted using only the surface to perimeter ratio. We fabricate microstructures of circular, squared and triangular shapes all in four different sizes as shown in Fig. 2a. In all structures the obstacle density is fixed to N / S = 0.016 μm −2. All recorded trajectories are also plotted in Fig. 2a with a color map encoding the scaled path length L /. In Fig. 2b we plot for each structure the histogram of path lengths normalized by the expected valuein Eq. 4. As we move from circles to squares and then to triangles we observe that the corresponding histograms are characterized by larger frequencies for both short and long path lengths. The probability of short paths increases as we introduce convex corners and reduce their angle, as evidenced by the blue-violet color of the corners in squared and triangular structures. The presence of longer paths in triangles can be also understood noting that the normalized maximum straight paths for circles, square and triangles are respectively 4/ π,/ π and/ π (see Supplementary Fig. 2). Despite these qualitative and quantitative differences between histograms, mean path lengths are always close to 1 when normalized by the predicted valueas shown in Fig. 2b. The observed path length distributions can be very well reproduced by a Lorentz gas model where collisions with obstacles are described as instantaneous reorientation events. These events are assumed to occur with a constant probability per unit path length given by, where/ π is the rotational average cross section of line obstacles with length b (see Methods). For perfectly straight trajectories, circles and squares have path length distributions with a vertical asymptote. A strong peak is found at the location of this divergence and is progressively smeared as the linear size of the domain becomes larger than the mean free path. Upon increasing the size of the region a peak aroundappears due to bacteria that scatter close to the boundary, reorient and exit. The mix of these two types of trajectories gives rise to the observed double-peak structure. Differently for the triangle no asymptote is present in the P (L) for large λ, therefore only a peak atprogressively appears. These results show that P (L) depends strongly on the random walk properties (as the mean free path), and on the domain features (shape and size). Differently the mean valuesanddepend only on the surface to perimeter ratio of the domain as expressed by Eq. 4. Experimental values ofare shown Fig. 3a for all shapes and sizes. We find an excellent agreement with theory using the same value s = 6.3 μm 2 that was used previously to predict the experimental values ofas a function of the number of obstacles (see Fig. 1c). This value of s has also been used to calculateaccording to Eq. 5 which captures quantitatively well the experimental data as shown in Fig. 3b.

---

### Temporal dynamics of the neural representation of hue and luminance polarity [^cadce983]. Nature Communications (2022). High credibility.

The 95% CI around the time to peak was determined from the times to peak for each of the 1000 bootstrapped time courses. Statistical tests on the difference in time to peak between two problems were performed using the bootstrap distributions of the differences in time to peak values. If the 95% confidence interval did not include 0, we rejected the null hypothesis, and p values were calculated based on the proportion of values that did fall below 0. To determine at which time points decoding accuracy was significantly above chance, a permutation test was used to calculate p values. This was done by permuting the sign of the decoding accuracy data on a participant basis 1000 times. For each permutation sample, the mean accuracy was recomputed, resulting in an empirical distribution of 1000 mean accuracies. This distribution was used to convert the real mean accuracies across subjects over time to p -value maps over time. The significance threshold was p < 0.05, and significant regions were determined using a cluster-based approach (cluster defining threshold p < 0.01). Onset of significance was calculated as the first time point where accuracy was significant for four continuous 5 ms time bins — the requirement that the accuracy be significant for four consecutive bins was adopted to minimize false positives. Reported p values for paired comparisons of the timing and magnitude of the decoding accuracy are uncorrected.

For the control experiment, classifiers were trained and tested for each session individually to yield eight decoding time courses; the five cross validation splits consisted of 15 trials. The 95% confidence intervals on the times to peak and the statistical tests used to compare the peak times were produced similarly to those of the main experiment, by sampling from the eight decoding curves to produce 1000 bootstrapped time courses (shading in Fig. 5 shows the 95% CI at each time point). To estimate the significance of decoding at each time point, shown as the horizontal line of data points above the x -axis in the curves in Fig. 5, we used a within-subjects approach instead of the across-subjects approach used in the main experiment. A null distribution was produced to test whether the decoding at each time point was greater than what one would expect by chance. In each null decoding run, the stimuli identities were shuffled, and the classifier was trained and tested on the shuffled data. There were 1000 null decoding runs, and p values at each time point were calculated based on the proportion of null decoding accuracies that exceeded the real decoding accuracy. These p values were then FDR corrected.

---

### High-dimensional one-shot optical field compressive sensing of structured light [^818ca56a]. Nature Communications (2025). High credibility.

Detailed studies show that the measured polarization phase differencechanges from 190° for the 2.26 rad/fs frequency component (834 nm wavelength) to 172° for the 2.48 rad/fs one (760 nm wavelength) (Fig. 2c red), consistent with calculations based on the half-wave plate refractive index provided by the supplier (Fig. 2c blue). Thus, the chromatic dispersion of the incident half-wave plate introduces wavelength–polarization coupling of a supposed linearly polarized light, illustrating the high-dimensional resolving power of the proposed scheme. In the time domain, the polarization state at each time slice is averaged over the entire spectral bandwidth, showing little variation.

We then use quarter-wave plates to generate light fields with right-rotating circular and left-rotating elliptical polarization, and Fig. 2d and e show their 3D spatiotemporal polarization states (white arrows) and intensities (color maps). For the elliptical polarization case, the white arrows form ellipses rotating along the left-hand direction, and their long axes are 20° to the-direction, consistent with the design. Moreover, the light chirality in each case is unambiguously determined, justifying the genuine 3D one-shot polarization resolving capability for arbitrary light, instead of simple specialized cases such as linear polarization –.

---

### Quantification of network structural dissimilarities [^3cf663e0]. Nature Communications (2017). Medium credibility.

Identifying and quantifying dissimilarities among graphs is a fundamental and challenging problem of practical importance in many fields of science. Current methods of network comparison are limited to extract only partial information or are computationally very demanding. Here we propose an efficient and precise measure for network comparison, which is based on quantifying differences among distance probability distributions extracted from the networks. Extensive experiments on synthetic and real-world networks show that this measure returns non-zero values only when the graphs are non-isomorphic. Most importantly, the measure proposed here can identify and quantify structural topological differences that have a practical impact on the information flow through the network, such as the presence or absence of critical links that connect or disconnect connected components.

---

### Shape morphing of plastic films [^835f8daf]. Nature Communications (2022). High credibility.

Through discrete peeling of the film belt, local curvature can be programmed and thus different polygonal shapes such as triangle, quadrangle, pentagon and hexagon were also obtained by simply arranging the adhesive layers with predetermined widths and intervals according to the interior angles and side lengths of the targeted shape and peeling the film under the according parameters (Fig. 3e and Supplementary Movie 7). Taking right triangle with an interior angle of 60° and shortest side of 10 mm and the 80 μm thick PTFE film at a peeling angle of 180° as an example, the diameter of the peeled film, d is ~2 mm and thus the widths of adhesive tapes (w a = (180 - θ)π d /360, θ is the interior angle) are 2.62 mm, 1.57 mm and 2.09 mm for interior angles of 30°, 90°, and 60°, respectively and intervals are 17.3, 10 and 20 mm, respectively (Fig. 3e, left). When peeling the film at peeling angle of 180°, the default right triangle was obtained (Supplementary Movie 7). Furthermore, complex 3D structures can be designed and fabricated through a multistep peeling process. For example, a two-step peeling process with orthogonal peeling directions and opposite curling directions can form hyperboloids (Fig. 3f and Supplementary Movie 8). In step I, a PTFE film (4 cm × 2 cm) was attached on two separated adhesive tapes (1 cm × 2 cm with an interval of 2 cm) and peeled off along the red line (Fig. 3f, left); in step II, the other side of the PTFE film was adhered on the adhesive tape (2 cm × 2 cm) and peeled off along the blue line with different peeling angles for the hyperboloids and semi-hyperboloids, before which the parts adhered in the first step were cut into parallel strips along their curling direction. More complex final 3D geometries can also be programmed by designing the layout of the 2D precursors and peeling them along the default routes (adhered regions, peeling direction, and peeling angle). Using this method, we obtained seventeen highly complex 3D geometries from ten 2D precursors and remarkably good agreement between experimental results and FEA predictions further verified the versatility of this shape-morphing strategy and the accuracy of the models (Fig. 4). Apart from the polymer films, the peeling-induced shape morphing strategy is also applicable to other materials capable of plastic deformation, such as metals (copper, silver, aluminum, nickel, titanium, and iron), semiconductor polymer films (poly(3-hexylthiophene-2,5-diyl), P3HT), filter paper, and composite films ranging from centimeter to micrometer (Supplementary Fig. 18).

---

### Emergence of symmetry selectivity in the visual areas of the human brain: fMRI responses to symmetry presented in both frontoparallel and slanted planes [^98d5ee23]. Human Brain Mapping (2018). Low credibility.

2.4.1 Stimuli to explore symmetry coherence and folds of symmetry on frontoparallel planes

Sparse symmetrical patterns (1.8% density as defined by the percentage of red dot pixels in the entire stimulus, giving 0.7 dots per deg 2) were generated by distributing red dots on a mid‐grey background after Sasaki et al. (2005). Here we restricted the dots to a single‐color channel (red) to reduce chromatic aberrations at the projector screen and render high fidelity stimuli. Stimuli were a square, 16° on a side and each dot was 0.16° wide. We generated stimuli to examine symmetry coherence, folds of symmetry, symmetry from slanted planes, and the contribution of attention to symmetry processing. To examine symmetry coherence we chose a fourfold stimulus to maximize the neural response. Four conditions were used: 100% symmetry; 75% symmetry; 50% symmetry, and 0% symmetry (100% noise) (Figure 3). Dot patterns were first generated with 100% symmetry, a proportion of dots corresponding to the appropriate noise level were then removed and randomly replaced at previously unoccupied locations across the stimulus. To probe folds of symmetry, four conditions were used: fourfold stimuli containing horizontal, vertical, and diagonal symmetry; twofold stimuli containing horizontal and vertical symmetry; onefold stimuli containing vertical symmetry, and 100% noise stimuli containing no symmetry (Figure 4). In separate experiments, the role of attention was probed by replacing passive viewing with a symmetry detection task. During these sessions, catch trials were included in which a motif was embedded within the stimulus and participants were asked to count the total number of motifs presented within each scan. We used a counting task for simplicity and to avoid potential confounds introduced by button presses. For fourfold and twofold patterns, a diamond motif whose points touched the center, top, bottom, and sides of the stimulus was embedded (Figure 2). For onefold patterns, a V‐shape that ran from the top edges to the bottom center of the stimulus was embedded (Figure 2). Importantly, by choosing motifs that were themselves symmetrical, we ensured that attention was maintained on a symmetry relevant, rather than symmetry irrelevant feature. To make the motif stimuli, we first positioned the dots constituting the symmetry stimulus (80% of total dots), while masking the area in which the motif could fall. The remaining 20% of dots were then randomly distributed along the motif line in a fashion that preserved the folds of symmetry present in the stimulus (Figure 2).

---

### Combined petrosal intertentorial approach: a cadaveric study of comparison with the standard combined petrosectomy [^95cede2f]. Operative Neurosurgery (2025). Medium credibility.

Areas of Surgical Exposure

Two areas of exposure (petroclival skull base and brainstem) were calculated by obtaining the sum of areas formed by juxtaposed triangles. For the petroclival area, we identified 4 fixed anatomic landmarks (posterior clinoid process, MC, internal acoustic canal, and jugular foramen) and 2 variables (uppermost and lowest medial clivus). Measuring the coordinates of these 6 points created a hexagonal shape. For the brainstem area, we identified 2 fixed points (trigeminal and facial nerve root entry zone [REZ]) and 3 variables (the lowest medial, the uppermost medial, and uppermost lateral brainstem), obtaining a pentagon-shaped area (Figure 5 A and 5 B drawing). Each polygon was divided along diagonals to create triangles whose area was calculated by the length of each side using Heron's formula. The areas of the 4 triangles of the petroclival skull base and the 3 triangles of the brainstem were then summed to calculate the total area of surgical exposure.

FIGURE 5.
These figures demonstrate the methodology of the study. A, Schematic representation of the bony skull base indicating the petroclival area of exposure. B, Schematic representation of the brainstem area of exposure. C, A, B, C, D, E, and F represent the 6 limits of the surface measurements that form a hexagon (black), bordered by dural and bony structures, whose area describes the surgical freedom. D, Illustration of the methodology to calculate the angles of attack. The distal point is fixed on the target (ie, right VII REZ), and the dissector is moved in the vertical (cranio-caudal, red dotted lines) and horizontal planes (antero-posterior, green dotted lines) until the limits of the osteo-dural points are encountered (red and green stars). ACP, anterior clinoid process; CN, cranial nerve; FL, foramen lacerum; FO, foramen ovale; FR, foramen rotundum; FS, foramen spinosum; HC, hypoglossal canal; IAC, internal acoustic canal; JF, Jugular foramen; LCNs, lower cranial nerves; PA, petrous apex; PCJ petroclival junction; PCP, posterior clinoid process; REZ, root entry zone.

---

### Statistics review 10: further nonparametric methods [^7a912fe5]. Critical Care (2004). Low credibility.

This review introduces nonparametric methods for testing differences between more than two groups or treatments. Three of the more common tests are described in detail, together with multiple comparison procedures for identifying specific differences between pairs of groups.

---

### High-dimensional one-shot optical field compressive sensing of structured light [^50191428]. Nature Communications (2025). High credibility.

Fig. 4
High-dimensional one-shot optical sensing of radially and azimuthally polarized beams.

a The 3D spatiotemporal polarization direction (white arrows) and intensity (color map) profiles of the radially polarized beam. b The polarization parameterdescribing the amplitude ratio angle between- and-polarized light components of the radially polarized beam. c The polarization parameterdescribing the phase difference between- and-polarized light components of the radially polarized beam. d–f The same as a–c, but for the azimuthally polarized beam.

To generate an azimuthally polarized beam, we rotate the half-wave plate with its optical axis along the-direction. The 3D spatiotemporal intensity and polarization profile are illustrated in Fig. 4d, showing polarization vectors pointing azimuthally. This observation is further corroborated by the detailed polarization angle mapand the phase difference mapat the time slice of0 fs (Fig. 4e, f), consistent with the designed azimuthal polarization state.

High-dimensional one-shot sensing of structured light fields beyond 2D

Control of structured light beyond 2D involves the manipulation of optical fields along the longitudinal temporal dimension. One typical example of such longitudinally structured light is the so-called polarization-gating field, which has counter-rotating circular polarization states at the leading and trailing edges of the pulsed light field, but is linearly polarized in the narrow central temporal region. Polarization-gating fields have been applied for isolated attosecond electron and light pulse generation, and chiral detection of biological molecules. As shown in Fig. 5a, we generate the polarization-gating field by transmitting an-polarized 40 fs incident laser pulse through a birefringent crystal (~0.6 mm quartz with its optical axis at 45° to), introducing a 16 fs time delay between ordinary and extraordinary fields. Then a quarter-wave plate converts ordinary and extraordinary fields into left- and right-circularly polarized ones respectively, but in their temporally overlapping area, left- and right-circularly polarized fields coherently add up to form linear polarization.

---

### Mavorixafor (Xolremdi) [^ab62ceb7]. FDA (2024). Medium credibility.

7.2 Effect of XOLREMDI on Other Drugs

CYP2D6 Substrates

The use of XOLREMDI with drugs that are another drug highly dependent on CYP2D6 for clearance is contraindicated [see Contraindications (4)].

Mavorixafor is a CYP2D6 inhibitor. Mavorixafor increases exposure of CYP2D6 substrates [see Clinical Pharmacology (12.3)], which may increase the risk of adverse reactions related to these substrates.

CYP3A4 Substrates

Monitor for CYP3A4 substrate related adverse reactions more frequently, unless otherwise recommended in the substrate's Prescribing Information, when XOLREMDI is used concomitantly with CYP3A4 substrates where minimal substrate concentration changes may lead to serious adverse reactions.

Mavorixafor is an inhibitor of CYP3A4. Mavorixafor may increase the Cmaxand AUC of CYP3A4 substrates [see Clinical Pharmacology (12.3)], which may increase the risk of adverse reactions from the CYP3A4 substrate.

P-gp Substrates

Monitor for P-gp substrate related adverse reactions more frequently, unless otherwise recommended in the substrate's Prescribing Information, when XOLREMDI is used concomitantly with P-gp substrates where minimal substrate concentration changes may lead to serious adverse reactions.

Digoxin: Measure serum digoxin concentrations before initiating concomitant use with XOLREMDI, and continue monitoring serum digoxin concentrations as recommended in the Prescribing Information for digoxin [see Clinical Pharmacology (12.3)].

Mavorixafor is an inhibitor of P-gp. Mavorixafor may increase the Cmaxand AUC of P-gp substrates [see Clinical Pharmacology (12.3)], which may increase the risk of adverse reactions from the P-gp substrate.

Metformin: Monitor for glycemic control and adjust the dose of metformin as necessary. Mavorixafor may decrease the mean Cmaxand AUC of metformin, which may reduce metformin's effectiveness. The mechanism of this interaction is unknown.

7.3 Drugs that Prolong the QTc Interval

Obtain an electrocardiogram when initiating, during concomitant use, and as clinically indicated in patients receiving concomitant medications with a known potential to prolong the QTc interval [see Warnings and Precautions (5.2)].

XOLREMDI causes QTc interval prolongation [see Clinical Pharmacology (12.2)]. Concomitant use of XOLREMDI with other products that prolong QTc interval may result in a greater increase in QTc interval and adverse reactions associated with QTc interval prolongation, including torsade de pointes, other serious arrythmias, and sudden death [see Warnings and Precautions (5.2)].

---

### Recommendations for cardiac chamber quantification by echocardiography in adults: an update from the American Society of Echocardiography and the European association of cardiovascular imaging [^79b1194c]. Journal of the American Society of Echocardiography (2015). Medium credibility.

Echocardiographic assessment of right atrial (RA) size — volume by 2D describes that "2D volumetric measurements are usually based on tracings of the blood-tissue interface on the apical four-chamber view" and that "At the tricuspid valve level, the contour is closed by connecting the two opposite sections of the tricuspid ring with a straight line". It adds, "Volumes can be computed by using either the single plane area-length" or "the disks summation technique", performed in a "2D view". The listed advantage is "More representative of actual RA size than linear dimensions", while limitations include "Assumes a symmetrical shape of the cavity", "Single plane volume calculation may be inaccurate since it assumes that RA enlargement is symmetrical", and "Normal values not well established".

---

### Guidelines for performing a comprehensive transthoracic echocardiographic examination in adults: recommendations from the American Society of Echocardiography [^24e92f6b]. Journal of the American Society of Echocardiography (2019). High credibility.

Transthoracic echocardiography sector size and depth — Depth is measured in units of length and should be set to maximize the size of the display for the structures or flow of interest, and because the heart is a moving structure, higher frame rates are desirable to increase temporal resolution; unnecessarily large sector depths can reduce image quality, and a narrower sector angle may be appropriate in some circumstances to enhance image quality.

---

### Standards of care in diabetes – 2025 [^ef149bc3]. Diabetes Care (2025). High credibility.

Regarding specific circumstances for diabetic nephropathy, more specifically with respect to pediatric patients, ADA 2025 guidelines recommend to determine the eGFR at the time of diagnosis and annually thereafter.

---

### Standards of care in diabetes – 2025 [^5eb43e21]. Diabetes Care (2025). High credibility.

Regarding follow-up and surveillance for diabetes mellitus type 1, more specifically with respect to continuous glucose monitoring, ADA 2025 guidelines recommend to implement early continuous glucose monitoring in adult patients with T1DM to improve glycemic outcomes and QoL and minimize hypoglycemia.

---

### Colorectal cancer screening and prevention [^390b568a]. American Family Physician (2025). High credibility.

Regarding screening and diagnosis for colon cancer, more specifically with respect to indications for screening, high-risk individuals, family history, AAFP 2025 guidelines recommend to obtain CRC screening in patients with ≥ 1 first-degree relatives with CRC or adenomatous polyps, starting at 40 years of age or 10 years before the age of the youngest relative at the time of their diagnosis.

---

### Clotrimazole [^b5a7188a]. FDA. Low credibility.

The dosage of clotrimazole OTIC for treatment of otomycosis in adults is 1 vial OTIC BID for 14 days (1%/0.17 mL)

---

### Functional differentiation in the human ventromedial frontal lobe: a data-driven parcellation [^0207cfd2]. Human Brain Mapping (2020). Medium credibility.

We tested for differences in co‐occurrence patterns between all pairs of clusters by performing MACM separately on the experiments associated with either cluster, and then computing the voxel‐wise difference between the ensuing ALE maps. All experiments contributing to the two contrasted clusters were pooled and randomly divided into two groups of the same size as the two original sets of experiments defined by activation in the first or second cluster (Eickhoff et al. 2011). ALE‐scores for these two randomly assembled groups were calculated and the difference between these ALE‐scores was recorded for each voxel in the brain. Repeating this process 10,000 times then yielded a null distribution of differences in ALE‐scores between the MACM analyses of the two clusters. The "true" difference in ALE scores was then tested against this null distribution yielding a posterior probability that the true difference was not due to random noise in an exchangeable set of labels based on the proportion of lower differences in the random exchange. The resulting probability values were then thresholded at p > .95 (95% chance for true difference) and inclusively masked by the respective main effects, that is, the significant effects in the MACM for the particular cluster. To simplify the analysis and reduce the number of comparisons, we computed a conjunction map of the contrasts of a given subregion with all others (e.g. Clusters 1 vs. 2–6). This would identify regions which were preferentially connected to the subregion compared to all other subregions.

---

### The limit of droplet rebound angle [^84959657]. Nature Communications (2025). High credibility.

Fig. 2
Mechanism of droplet horizontal rebound.

a Schematic illustration of droplet retraction on the PW surface. b Measured impact and retraction force of z -direction F on the PW surface F PW and SHB surface F SHB. t = 0 is set when the droplet reaches its maximum spreading radius. c The force F z in the vertical direction during the retraction process of the droplet on the PW surface and the SHB surface. Here, the force is expressed asand plotted by data of. d The force F x in the vertical direction during the retraction process of the droplet on the PW surface and the SHB surface. The "+" and "−" denote the force is to the right and left, respectively, as distinguished by different colors. Here, the force is expressed asand plotted by data of.

Horizontal adhesion of the droplet

On the other hand, in the x- direction, the contact angles of the left and right sides are different during the retraction process of the droplet. Therefore, like theof the spring system, the droplet will experience an asymmetric x -direction adhesion force, whereis the action length of the x -direction force (see details in Supplementary Note 6). The accumulation ofover time t converts to the lateral rebound velocity of the droplet. Similar to Fig. 2c, since it is hard to accurately obtain the real-time contact angle of the left endsand right endsof the droplet, is used to characterize the adhesion force received by the droplet in the horizontal direction, whereis the weighted arithmetic mean of, as shown in Fig. 2d. According to the relative size of the left and right contact angles, the variation process ofcan be divided into three stages according to the side view of the droplet rebounding process shown in Supplementary Fig. 6c – f, namely >, and <. When >, the x -direction force on the droplet is to the right, which is denoted by "+" in Fig. 2d; and when <, the x -direction force on the droplet is to the left, which is denoted by "−". Here, the value of the lateral adhesion force can be calculated if we assume that the left and right contact angles observed from the side view are equivalent to the actual left and right contact angles, respectively (see Supplementary Fig. 6g – i). The calculated droplet lateral velocity is close to that measured by high-speed photography, which indicates that the lateral force analysis above is reliable.

---

### A problem of persistence: still more questions than answers? [^1078e4fd]. Nature Reviews: Microbiology (2013). Medium credibility.

The current antibiotic resistance crisis has led to increased pressure to prioritize strategies to tackle the issue, with a strong focus being placed on the development of novel antimicrobials. However, one major obstacle that is often overlooked is persister cells, which are refractory to antibiotic treatment. Tackling persistence is a challenge because these cell types are extremely difficult to study and, consequently, little is known about their physiology and the factors that lead to their emergence. Here, four experts contemplate the main physiological features that define persistence and the implications of persistence for antibiotic treatment regimens, and consider what the study of bacterial persistence has taught us about the heterogeneity of bacterial populations.

---

### The timescale and direction of influence of a third inferior alternative in human value-learning [^eb7260f5]. Communications Psychology (2025). Medium credibility.

Basic performance

During the learning phase (Fig. 2B), participants were sequentially exposed to the value associated with each alternative. The value was shown by a cloud of moving dots, with the number of dots representing the reward magnitude (i.e. number of points) associated with the coin (see "Methods" section). Participants completed 99.91% (95% CI = [99.84%, 99.97%]) of all learning trials with an average reaction time of 623.66 milliseconds (ms) (95% CI = [593.56 ms, 653.76 ms]) in Experiment 1, and 99.3% (95% CI = [98.94%, 99.66%]) of all learning trials with an average reaction time of 411.92 ms (95% CI = [386.66 ms, 437.18 ms]) in Experiment 2, indicating that they properly engaged with the learning phase. We found no statistically significant evidence for differences between the reaction times across learning trials that involved the higher-value (HV), lower-value (LV), and distractor value (DV) alternatives across different contexts in either experiment (2-way ANOVA on log (RT) in Experiment 1: alternatives: F (2, 174) = 0.004, p = 0.99, partial η² < 0.01, 95% CI = [0.00, 0.02], contexts: F (1, 174) = 0.15, p = 0.69, partial η² < 0.01, 95% CI = [0.00, 0.03], interaction: F (2, 174) = 0.02, p = 0.98, partial η² = 0.00, 95% CI = [0.00, 0.02]; and in Experiment 2: alternatives: F (2, 402) = 0.03, p = 0.97, partial η² = 0.00, 95% CI = [0.00, 0.01], contexts: F (1, 402) = 0.06, p = 0.81, partial η² < 0.01, 95% CI = [0.00, 0.01], interaction: F (2, 402) = 0.04, p = 0.97, partial η² < 0.01, 95% CI = [0.00, 0.01]).

---

### Cladribine (Mavenclad) [^adfd0eb6]. FDA (2025). Medium credibility.

2.2 Recommended Dosage

The recommended cumulative dosage of MAVENCLAD is 3.5 mg per kg body weight administered orally and divided into 2 yearly treatment courses (1.75 mg per kg per treatment course) (see Table 1). Each treatment course is divided into 2 treatment cycles:

Administration of First Treatment Course

First Course/First Cycle: start any time.
First Course/Second Cycle: administer 23 to 27 days after the last dose of First Course/First Cycle.

Administration of Second Treatment Course

Second Course/First Cycle: administer at least 43 weeks after the last dose of First Course/Second Cycle.
Second Course/Second Cycle: administer 23 to 27 days after the last dose of Second Course/First Cycle.

Administer the cycle dosage as 1 or 2 tablets once daily over 4 or 5 consecutive days [see How Supplied/Storage and Handling (16.1)]. Do not administer more than 2 tablets daily.

Following the administration of 2 treatment courses, do not administer additional MAVENCLAD treatment during the next 2 years. Treatment during these 2 years may further increase the risk of malignancy [see Warnings and Precautions (5.1)]. The safety and efficacy of reinitiating MAVENCLAD more than 2 years after completing 2 treatment courses has not been studied.

2.3 Missed Dose

If a dose is missed, patients should not take double or extra doses.

If a dose is not taken on the scheduled day, then the patient must take the missed dose on the following day and extend the number of days in that treatment cycle. If two consecutive doses are missed, the treatment cycle is extended by 2 days.

2.4 Administration

MAVENCLAD tablets are taken orally, with water, and swallowed whole without chewing. MAVENCLAD can be taken with or without food.

Separate administration of MAVENCLAD and any other oral drugs by at least 3 hours during the 4 to 5 day MAVENCLAD treatment cycles [see Clinical Pharmacology (12.6)].

MAVENCLAD is a cytotoxic drug. Follow applicable special handling and disposal procedures [see References (15)]. MAVENCLAD is an uncoated tablet and must be swallowed immediately once removed from the blister. If a tablet is left on a surface, or if a broken or fragmented tablet is released from the blister, the area must be thoroughly washed with water.

The patient's hands must be dry when handling the tablets and washed thoroughly afterwards. Avoid prolonged contact with skin.

---

### Technical update on HIV-1 / 2 differentiation assays [^50eb7933]. CDC (2016). Medium credibility.

HIV-1/HIV-2 differentiation testing — alternatives when the FDA-approved antibody differentiation immunoassay cannot be used states that there may be circumstances under which a laboratory is unable to adopt the FDA-approved HIV-1/HIV-2 antibody differentiation immunoassay, and in this situation a laboratory has alternatives for that step in the algorithm, some of which could delay turnaround time for test results. Send specimens to another laboratory that offers the FDA-approved supplemental HIV antibody differentiation assay. Refer to CDC/APHL laboratory testing guidance section I, "Alternative Testing Sequences When Tests in the Recommended Algorithm Cannot be Used".

---

### The timescale and direction of influence of a third inferior alternative in human value-learning [^a6be0a25]. Communications Psychology (2025). Medium credibility.

Fig. 6
Model comparison.

A Distractor effect comparison between the actual data and simulated data using the best-fitted parameters, the RB model has a closer fit to the actual distractor effect in the choice data. B Fixed-effect Bayesian model comparison, Black asterisks: significant ΔBIC against 10, one-sided one-sample t -tests. C Random-effect Bayesian model comparison. D The difference of " HV + LV " between two contexts, simulated by the best-fitted parameters of the RB model. E Number of binary comparisons (best-fitted k parameters in RB model) for two groups of participants with negative and positive distractor effects. In all panels, the data here is pooled across both experiments (N = 98) (Fig. S3 in Supplemental Information for each Experiment), the error bars are standard errors of the mean across participants, and the colored dots indicate the individual participant.

---

### Guidelines for the standardization of adult echocardiography reporting: recommendations from the American Society of Echocardiography [^5fd207c0]. Journal of the American Society of Echocardiography (2025). High credibility.

Echocardiography report comparisons to prior studies — comparative statements should address technical differences of the comparison study, include the date of the study being compared and whether findings are new, unchanged, resolved, improved, or worsened, and conclude with a summary statement on the clinical significance of the comparison.

---

### Colorectal cancer screening and prevention [^c270f773]. American Family Physician (2025). High credibility.

Regarding screening and diagnosis for colon cancer, more specifically with respect to indications for screening, general population, aged 76–85 years, AAFP 2025 guidelines recommend to consider obtaining screening for CRC in adults aged 76–85 years at average risk based on overall health status, prior screening history, and patient preferences.

---

### ESICM / ESCMID task force on practical management of invasive candidiasis in critically ill patients [^551f3d5b]. Intensive Care Medicine (2019). High credibility.

Regarding medical management for invasive candidiasis, more specifically with respect to step-down therapy, ESCMID/ESICM 2019 guidelines recommend to discontinue antifungal therapy in patients with suspected (but not proven) invasive candidiasis with negative blood cultures and/or other negative culture specimens taken from suspected infectious foci before starting antifungal therapy.

---

### Shearing-induced asymmetry in entorhinal grid cells [^57d11eea]. Nature (2015). Excellent credibility.

Grid cells are neurons with periodic spatial receptive fields (grids) that tile two-dimensional space in a hexagonal pattern. To provide useful information about location, grids must be stably anchored to an external reference frame. The mechanisms underlying this anchoring process have remained elusive. Here we show in differently sized familiar square enclosures that the axes of the grids are offset from the walls by an angle that minimizes symmetry with the borders of the environment. This rotational offset is invariably accompanied by an elliptic distortion of the grid pattern. Reversing the ellipticity analytically by a shearing transformation removes the angular offset. This, together with the near-absence of rotation in novel environments, suggests that the rotation emerges through non-coaxial strain as a function of experience. The systematic relationship between rotation and distortion of the grid pattern points to shear forces arising from anchoring to specific geometric reference points as key elements of the mechanism for alignment of grid patterns to the external world.

---

### As-3 [^f4572ab3]. FDA (2025). Medium credibility.

Storage and handling

Store at room temperature (25 °C/77 °F). Avoid excessive heat.

Protect from freezing

---

### Standards of care in diabetes – 2025 [^cb4a5970]. Diabetes Care (2025). High credibility.

Regarding diagnostic investigations for diabetes mellitus type 1, more specifically with respect to general principles, ADA 2025 guidelines recommend to obtain a complete medical evaluation at the initial visit and follow-up, as appropriate, to:

- confirm the diagnosis and classify diabetes

- ssess glycemic status and previous treatment

- evaluate for diabetes complications, potential comorbid conditions, and overall health status

- identify care partners and support system

- assess social determinants of health and structural barriers to optimal health and health care

- review risk factor management in the patient with diabetes

- begin engagement with the patient with diabetes in the formulation of a care management plan including initial goals of care

- develop a plan for continuing care.

---

### A comparison of phase II study strategies [^ebb760ae]. Clinical Cancer Research (2009). Low credibility.

The traditional oncology drug development paradigm of single arm phase II studies followed by a randomized phase III study has limitations for modern oncology drug development. Interpretation of single arm phase II study results is difficult when a new drug is used in combination with other agents or when progression-free survival is used as the endpoint rather than tumor shrinkage. Randomized phase II studies are more informative for these objectives but increase both the number of patients and time required to determine the value of a new experimental agent. In this article, we compare different phase II study strategies to determine the most efficient drug development path in terms of number of patients and length of time to conclusion of drug efficacy on overall survival.

---

### Addressing early childhood emotional and behavioral problems [^0988ef83]. Pediatrics (2016). Medium credibility.

Examples of evidence-based treatments for existing diagnoses in young children — This report focuses on programs that target current diagnoses or clear clinical problems (rather than risk) in infants and toddlers.

---

### Semaglutide improves cardiometabolic risk factors in adults with overweight or obesity: STEP 1 and 4 exploratory analyses [^8785ac70]. Diabetes, Obesity & Metabolism (2023). Medium credibility.

2 MATERIALS AND METHODS

The methodology of STEP 1 and 4 has been described previously.

2.1 Study designs

STEP 1 (NCT03548935) was a double‐blind, placebo‐controlled trial (Figure S1). Participants were randomized 2:1 to once‐weekly s.c. semaglutide 2.4 mg or placebo, with lifestyle intervention for 68 weeks. STEP 4 (NCT03548987) was a randomized withdrawal trial in which all participants received semaglutide during a 20‐week run‐in period (Figure S2). Participants reaching the once‐weekly s.c. semaglutide 2.4 mg target maintenance dose at week 20 were randomized 2:1 to continue semaglutide or switch to placebo for 48 weeks. All participants received lifestyle intervention throughout the 68 weeks.

Both trials were conducted in accordance with the Declaration of Helsinki and Good Clinical Practice guidelines. Protocols were approved by independent ethics committees or institutional review boards at each study site. All participants provided written informed consent.

2.2 Study population

Participants in both trials were aged ≥ 18 years with one or more self‐reported unsuccessful dietary effort to lose weight and body mass index ≥ 30 kg/m 2 or ≥ 27 kg/m 2 with one or more weight‐related comorbidity without diabetes.

2.3 Outcomes and assessments

The endpoints assessed are detailed below, with information on how they were measured in the Supporting Information.

---

### Semaglutide 2.4 mg for the treatment of obesity: key elements of the STEP trials 1 to 5 [^ebad60f3]. Obesity (2020). Medium credibility.

In the sustained WM trial (STEP 4, NCT03548987), 902 participants with obesity or overweight, without T2D, are being treated with semaglutide 2.4 mg once weekly. Those completing a 20‐week run‐in period are being randomly assigned in a 2:1 manner to receive continued semaglutide 2.4 mg or placebo for an additional 48 weeks to assess WL (Figure 4, Table 1). Approximately 750 eligible participants will be randomly assigned. In addition, it has a withdrawal trial design to assess the change in weight after switching from semaglutide to placebo.

Figure 4
Sustained weight management trial design (Semaglutide Treatment Effect in People with obesity 4). This is a 68‐week, randomized, double‐blind, placebo‐controlled, two‐armed, multicenter, multinational withdrawal clinical trial, with 7 weeks of follow‐up without treatment for safety assessments, comparing semaglutide 2.4 mg (subcutaneously, once weekly) with placebo, as an adjunct to lifestyle intervention, in people with obesity or overweight. *During the 20‐week run‐in period, participants start a dose escalation (visit 2 [week 0]) with semaglutide 2.4 mg (subcutaneously, once weekly) as an adjunct to a reduced‐calorie diet and increased physical activity for 20 weeks. The run‐in period includes 4 weeks at the target dose (semaglutide subcutaneously, 2.4 mg once weekly).

In the long‐term WM trial (STEP 5, NCT03693430), 304 participants with obesity or overweight, without T2D, are being randomly assigned in a 1:1 manner to receive semaglutide 2.4 mg or placebo to assess WL (Figure 5, Table 1) over a 2‐year period.

Figure 5
Long‐term weight management trial design (Semaglutide Treatment Effect in People with obesity 5). This is a 104‐week, randomized, double‐blind, placebo‐controlled, two‐armed, parallel‐group, multicenter, multinational clinical trial, with 7 weeks of follow‐up without treatment for safety assessments, comparing semaglutide 2.4 mg (subcutaneously, once weekly) with placebo, as an adjunct to lifestyle intervention in people with obesity or overweight.

---

### 2023 ESC guidelines for the management of cardiovascular disease in patients with diabetes [^24784e3d]. European Heart Journal (2023). High credibility.

Regarding medical management for diabetes mellitus type 2, more specifically with respect to prevention of CVD, glucose-lowering medications, ESC 2023 guidelines recommend to consider initiating metformin to reduce cardiovascular risk in patients with T2DM without ASCVD or severe target-organ damage at low, moderate,
high, or very high risk.

---

### Diagnosis, management and treatment of the Alport syndrome-2024 guideline on behalf of ERKNet, ERA and ESPN [^45eede36]. Nephrology, Dialysis, Transplantation (2025). High credibility.

Regarding diagnostic investigations for Alport syndrome, more specifically with respect to hearing assessment, ERA/ERN ERKNet/ESPN 2025 guidelines recommend to consider obtaining a hearing evaluation at diagnosis or upon reaching adulthood in female patients with X-linked alport syndrome, and then every 5 years in the absence of hearing loss symptoms.

---

### Guidelines for the echocardiographic assessment of the right heart in adults and special considerations in pulmonary hypertension: recommendations from the American Society of Echocardiography [^29d32346]. Journal of the American Society of Echocardiography (2025). High credibility.

American Society of Echocardiography right atrial size — reference limits and abnormality grading for chamber dimension and volume are as follows: Right atrium (RA) major dimension, cm, is normal when < 5.4, mild enlargement when ≥ 5.4 to ≤ 5.8, moderate when > 5.8 to ≤ 6.3, and severe when > 6.3; RA minor dimension, cm, is normal when < 4.2, mild when ≥ 4.2 to ≤ 4.7, moderate when > 4.7 to ≤ 5.1, and severe when > 5.1; RA area, cm2, is normal when < 19, mild when ≥ 19 to ≤ 22, moderate when > 22 to ≤ 24, and severe when > 24; Right atrial volume (RAV) index (method of disks), mL/m2, is normal when < 30, mild when ≥ 30 to ≤ 36, moderate when > 36 to ≤ 41, and severe when > 41; RAV index (area-length method), mL/m2, is normal when < 33, mild when ≥ 33 to ≤ 38, moderate when > 38 to ≤ 44, and severe when > 44; RA end-systolic volume index (3D method), mL/m2, is normal when < 42, mild when ≥ 42 to ≤ 49, moderate when > 49 to ≤ 57, and severe when > 57; RA end-diastolic volume index (3D method), mL/m2, is normal when < 60, mild when ≥ 60 to ≤ 73, moderate when > 73 to ≤ 87, and severe when > 87.

---

### Use of endocrine therapy for breast cancer risk reduction: ASCO clinical practice guideline update [^247375b3]. Journal of Clinical Oncology (2019). High credibility.

Regarding preventative measures for breast cancer, more specifically with respect to chemoprophylaxis, ASCO 2019 guidelines recommend to offer exemestane as an alternative to tamoxifen and/or raloxifene to reduce the risk of invasive breast cancer, specifically ER+ breast cancer, in postmenopausal women ≥ 35 years of age with a 5-year projected absolute breast cancer risk ≥ 1.66% or with lobular carcinoma in situ or atypical hyperplasia.

---

### Phase 0 / microdosing approaches: time for mainstream application in drug development? [^98d5620b]. Nature Reviews: Drug Discovery (2020). High credibility.

Phase 0 approaches - which include microdosing - evaluate subtherapeutic exposures of new drugs in first-in-human studies known as exploratory clinical trials. Recent progress extends phase 0 benefits beyond assessment of pharmacokinetics to include understanding of mechanism of action and pharmacodynamics. Phase 0 approaches have the potential to improve preclinical candidate selection and enable safer, cheaper, quicker and more informed developmental decisions. Here, we discuss phase 0 methods and applications, highlight their advantages over traditional strategies and address concerns related to extrapolation and developmental timelines. Although challenges remain, we propose that phase 0 approaches be at least considered for application in most drug development scenarios.

---

### Recommendations for noninvasive evaluation of native valvular regurgitation: a report from the American Society of Echocardiography developed in collaboration with the Society for Cardiovascular Magnetic Resonance [^72901fb9]. Journal of the American Society of Echocardiography (2017). Medium credibility.

Color Doppler determinants of regurgitant jet size and acquisition settings — jet momentum (Av^2) is a major overall determinant of jet size, and eccentric wall-hugging jets lose momentum rapidly, thus appearing smaller than nonconstrained jets of the same RVol; reducing the Nyquist limit (velocity scale) makes the jet appear larger; slit-like orifices (particularly imaged along the long axis of the orifice) and multiple separate orifices lead to larger jets than single, relatively round orifices; pulse repetition frequency affects jet area inversely and jet size is quite sensitive to and proportional to gain; attenuation in the far field or from interposing highly echoreflectant structures will decrease jet size; higher transducer frequency increases Doppler shift and can make jets larger (as in transesophageal echocardiography [TEE]) but higher frequency beams may suffer excessive attenuation and jets may appear smaller in the far field during transthoracic echocardiography (TTE); angle of interrogation can make jets interrogated orthogonally appear smaller than the same jet imaged axially, and if the tissue priority is set too high, structures may encroach on the color Doppler signal; Standard technique is to use a Nyquist limit (aliasing velocity) Val of 50–70 cm/sec and a high color gain that just eliminates random color speckle from nonmoving regions, and the minimum detectable velocity typically is a fraction (around 10%) of the full Nyquist velocity; illustrating momentum dependence, a 5 m/sec mitral regurgitant jet with a flow rate of 100 mL/sec should appear the same by Color Doppler as a 2.5 m/sec tricuspid regurgitation jet with a flow rate of 200 mL/sec.

---

### Moving beyond the hazard ratio in quantifying the between-group difference in survival analysis [^84aa7ba7]. Journal of Clinical Oncology (2014). Low credibility.

In a longitudinal clinical study to compare two groups, the primary end point is often the time to a specific event (eg, disease progression, death). The hazard ratio estimate is routinely used to empirically quantify the between-group difference under the assumption that the ratio of the two hazard functions is approximately constant over time. When this assumption is plausible, such a ratio estimate may capture the relative difference between two survival curves. However, the clinical meaning of such a ratio estimate is difficult, if not impossible, to interpret when the underlying proportional hazards assumption is violated (ie, the hazard ratio is not constant over time). Although this issue has been studied extensively and various alternatives to the hazard ratio estimator have been discussed in the statistical literature, such crucial information does not seem to have reached the broader community of health science researchers. In this article, we summarize several critical concerns regarding this conventional practice and discuss various well-known alternatives for quantifying the underlying differences between groups with respect to a time-to-event end point. The data from three recent cancer clinical trials, which reflect a variety of scenarios, are used throughout to illustrate our discussions. When there is not sufficient information about the profile of the between-group difference at the design stage of the study, we encourage practitioners to consider a prespecified, clinically meaningful, model-free measure for quantifying the difference and to use robust estimation procedures to draw primary inferences.

---

### Pharmacological management of osteoporosis in postmenopausal women: an endocrine society guideline update [^8e1830e4]. The Journal of Clinical Endocrinology and Metabolism (2020). High credibility.

Regarding medical management for postmenopausal osteoporosis, more specifically with respect to antiresorptive and anabolic therapy, PTH analogs, ES 2020 guidelines recommend to initiate teriparatide or abaloparatide for up to 2 years to reduce the risk of vertebral and non-vertebral fractures in postmenopausal patients with osteoporosis at very high risk of fractures, such as severe or multiple vertebral fractures. (1, Moderate) Switch to an antiresorptive therapy to maintain bone density gains in postmenopausal patients with osteoporosis completing a course of teriparatide or abaloparatide.

---

### Rigorous location of phase transitions in hard optimization problems [^d98ebea5]. Nature (2005). Excellent credibility.

It is widely believed that for many optimization problems, no algorithm is substantially more efficient than exhaustive search. This means that finding optimal solutions for many practical problems is completely beyond any current or projected computational capacity. To understand the origin of this extreme 'hardness', computer scientists, mathematicians and physicists have been investigating for two decades a connection between computational complexity and phase transitions in random instances of constraint satisfaction problems. Here we present a mathematically rigorous method for locating such phase transitions. Our method works by analysing the distribution of distances between pairs of solutions as constraints are added. By identifying critical behaviour in the evolution of this distribution, we can pinpoint the threshold location for a number of problems, including the two most-studied ones: random k-SAT and random graph colouring. Our results prove that the heuristic predictions of statistical physics in this context are essentially correct. Moreover, we establish that random instances of constraint satisfaction problems have solutions well beyond the reach of any analysed algorithm.

---

### Validation of monte carlo estimates of three-class ideal observer operating points for normal data [^26b6e5d9]. Academic Radiology (2013). Low credibility.

Rationale and Objectives

Traditional two-class receiver operating characteristic (ROC) analysis is inadequate for the complete evaluation of observer performance in tasks with more than two classes.

Materials and Methods

Here, a Monte Carlo estimation method for operating point coordinates on a three-class ROC surface is developed and compared with analytically calculated coordinates in two special cases: (1) univariate and (2) restricted bivariate trinormal underlying data.

Results

In both cases, the statistical estimates were found to be good in the sense that the analytical values lay within the 95% confidence interval of the estimated values about 95% of the time.

Conclusions

The statistical estimation method should be key in the development of a pragmatic performance metric for evaluation of observers in classification tasks with three or more classes.

---

### Elacestrant (Orserdu) [^25e5bc7d]. FDA (2024). Medium credibility.

The dosage of elacestrant PO for treatment of breast cancer in postmenopausal female adults with ESR1 mutation (advanced or metastatic, ER-positive, HER2-negative, progression after ≥ 1 line of endocrine therapy) is 345 mg PO daily until disease progression or unacceptable toxicity

---

### Standards of care in diabetes – 2025 [^14753c0e]. Diabetes Care (2025). High credibility.

Regarding specific circumstances for chronic kidney disease, more specifically with respect to patients with diabetes mellitus (monitoring of renal function), ADA 2025 guidelines recommend to monitor urinary albumin (such as spot urinary albumin-to-creatinine ratio) and eGFR 1–4 times per year, depending on the stage of the disease, in patients with established diabetic kidney disease.

---

### Weight regain and cardiometabolic effects after withdrawal of semaglutide: the STEP 1 trial extension [^cbf53ee8]. Diabetes, Obesity & Metabolism (2022). Medium credibility.

3.2 Change in body weight and

During the main treatment phase (from baseline [week 0] to week 68), semaglutide reduced body weight more than placebo (Figure 1A and Tables 2 and S1); observed mean weight loss was 17.3% (standard deviation [SD]: 9.3%) with semaglutide versus 2.0% (SD: 6.1%) with placebo (Table S1). After treatment withdrawal, body weight regain was observed in both the semaglutide and placebo arms (Figure 1A and Tables 2 and S1). Participants regained a mean of 11.6 percentage points (SD: 7.7) of body weight in the semaglutide arm versus 1.9 percentage points (SD: 4.8) in the placebo arm (Table S1). The net mean body weight loss over the full duration of the main treatment phase and off‐treatment extension phase (from week 0 to week 120) was 5.6% (SD: 8.9%) in the semaglutide arm versus 0.1% (SD: 5.8%) in the placebo arm (Figure 1A). At week 120, 5% or higher weight loss from baseline was observed in 48.2% of participants (95 of 197) in the semaglutide arm and in 22.6% (21 of 93) in the placebo arm.

---

### EASL-EASD-EASO clinical practice guidelines on the management of metabolic dysfunction-associated steatotic liver disease (MASLD) [^e30d71d8]. Journal of Hepatology (2024). High credibility.

Regarding classification and risk stratification for metabolic dysfunction-associated steatotic liver disease, more specifically with respect to noninvasive assessment of fibrosis, EASD/EASL/EASO 2024 guidelines recommend to use a multi-step approach in adult patients with MASLD:

- obtain an established non-patented blood-based score, such as the fibrosis-4 index, as the first step

- obtain established imaging techniques, such as liver elastography, as the second step to further clarify the fibrosis stage if fibrosis is still suspected or in high-risk groups.

---

### Evaluation of the visual system by the primary care provider following concussion [^f02d8b33]. Pediatrics (2022). High credibility.

Concussion visual evaluation — versions (horizontal and vertical movements under binocular conditions) and ductions (movements of each eye under monocular conditions) are assessed by holding the stimulus about 2 feet in front of the patient and moving it in an "H" pattern to the right, left, up-right, up-left, down-right, and down-left, first under binocular conditions then with each eye covered; the eyes should move equally symmetrically to the extreme positions of gaze.

---

### Guidelines for performing a comprehensive transthoracic echocardiographic examination in adults: recommendations from the American Society of Echocardiography [^81dffce8]. Journal of the American Society of Echocardiography (2019). High credibility.

Spectral Doppler parameter — velocity scale: in a pulsed‑wave (PW) Doppler sample from the left ventricular outflow tract (LVOT), the velocity scale specifies the range of velocities that can be displayed; in the example, the velocity scale is adjusted from a maximum velocity range of −80.0 to −120 cm/sec, and the right image has no aliasing.

---

### Lateral intercalation-assisted ionic transport towards high-performance organic electrochemical transistor [^4f7220e1]. Nature Communications (2024). High credibility.

Following this concept, we fabricated OECTs decorated with striped films as shown in Fig. 1a, using the P3HT polymer as channel material. While applying a gate bias (V GS), the anion in electrolyte (1-ethyl-3-methylimidazolium bis(trifluoromethylsulfonyl)imide, EMIM + TFSI −) is driven to transport vertically into the active layer and induce with hole carrier. Compared with conventional ion transport, the LI-assisted ionic transport based on lateral channels delivered by the striped films, which not only allows ions to penetrate vertically but also laterally. Figure 1b exhibits the AFM images of P3HT thin films with different stripe structures obtained after photolithography, with stripe widths precisely controlled to 2 μm. The device geometry and the stripped structure in the channel were shown in Supplementary Fig. 2. Notably, for the 100 µm-patterned film, the stripe width equals the device width, resulting in ion penetration from both edges; while other patterned are within the device channel. In this research, the stripe spacing is fixed at 2 μm and the thickness of the films is set at approximately 1 μm for P3HT. A thick OSC layer is adopted first to reveal the volume-dominated trade-off between transconductance and response time. This is achieved by modulating ionic transport directions to emphasize the effect of lateral injection.

---

### The timescale and direction of influence of a third inferior alternative in human value-learning [^b06a7d7f]. Communications Psychology (2025). Medium credibility.

In the choice phase (Fig. 2D), participants made 12 ternary and 12 binary choices (four trials per each possible binary pair) by reporting their preferred alternative within a maximum of two seconds. We included all three possible binary pairs (HV vs. LV, HV vs. DV, LV vs. DV) to keep the presentation rate of all alternatives equal and to avoid introducing any implicit bias toward the two high-value alternatives. Participants completed 99.73% (95% CI = [99.62%, 99.84%]) of all choice trials with an average reaction time of 729.89 ms (95% CI = [695.14 ms, 764.65 ms]) in Experiment 1, and 99.34% (95% CI = [99.08%, 99.60%]) of choice trials with an average reaction time of 614.50 ms (95% CI = [581.55 ms, 647.45 ms]) in Experiment 2. Participants chose the best alternative significantly higher than the chance level in both ternary and binary trials (Experiment 1: accuracy in ternary = 81.63% (95% CI = [78.49%, 84.77%]), t (29) = 30.17, p < 0.001, d = 5.51, 95% CI = [5.13, 5.88]), and in binary = 90.27% (95% CI = [88.29%, 92.25%]), t (29) = 39.86, p < 0.001, d = 7.28, 95% CI = [6.90, 7.65]; Experiment 2: accuracy in ternary = 70.08% (95% CI = [66.81%, 73.35%]), t (67) = 22.03, p < 0.001, d = 2.67, 95% CI = [2.43, 2.91], and in binary = 81.23% (95% CI = [78.66%, 83.81%], t (67) = 23.80, p < 0.001, d = 2.89, 95% CI = [2.64, 3.13]; Fig. S1 in Supplemental Information). The average reaction time in binary trials was significantly higher than in ternary trials only in Experiment 1, with no statistically significant evidence for change across different contexts in both experiments (2-way ANOVA on log (RT) in Experiment 1: choice type: F (1, 116) = 11.40, p < 0.001, partial η² = 0.09, 95% CI = [0.02, 0.21], contexts: F (1, 116) = 0.20, p = 0.65, partial η² < 0.01, 95% CI = [0.00, 0.05], interaction: F (1, 116) = 0.03, p = 0.87, partial η² < 0.01, 95% CI = [0.00, 0.04]; and in Experiment 2: choice type: F (1, 268) = 2.97, p = 0.09, partial η² = 0.01, 95% CI = [0.00, 0.05], contexts: F (1, 268) = 0.93, p = 0.34, partial η² < 0.01, 95% CI = [0.00, 0.03], interaction: F (1, 268) = 0.01, p = 0.92, partial η² < 0.01, 95% CI = [0.00, 0.02]; Fig. S1 in Supplemental Information). This seemingly counterintuitive finding might be attributed to the greater uncertainty linked with the identities of the alternatives in binary trials.

---

### AGA clinical practice guideline on management of gastroparesis [^9e865be1]. Gastroenterology (2025). High credibility.

Regarding diagnostic investigations for gastroparesis, more specifically with respect to gastric emptying studies, methodology, AGA 2025 guidelines recommend to perform a 4-hour study in all cases, as some patients with normal emptying at 2 hours may be reclassified as delayed at 4 hours.

---

### New designs for phase 2 clinical trials [^a90544dc]. Blood (2003). Low credibility.

Conventional phase 2 clinical trials are typically single-arm experiments, with outcome characterized by one binary "response" variable. Clinical investigators are poorly served by such conventional methodology. We contend that phase 2 trials are inherently comparative, with the results of the comparison determining whether to conduct a subsequent phase 3 trial. When different treatments are studied in separate single-arm trials, actual differences between response rates associated with the treatments, "treatment effects", are confounded with differences between the trials, "trial effects". Thus, it is impossible to estimate either effect separately. Consequently, when the results of separate single-arm trials of different treatments are compared, an apparent treatment difference may be due to a trial effect. Conversely, the apparent absence of a treatment effect may be due to an actual treatment effect being cancelled out by a trial effect. Because selection involves comparison, single-arm phase 2 trials thus fail to provide a reliable means for selecting which therapies to investigate in phase 3. Moreover, reducing complex clinical phenomena, including both adverse and desirable events, to a single outcome wastes important information. Consequently, conventional phase 2 designs are inefficient and unreliable. Given the limited number of patients available for phase 2 trials and the increasing number of new therapies that must be evaluated, it is critically important to conduct these trials efficiently. These concerns motivated the development of a general paradigm for randomized selection trials evaluating several therapies based on multiple outcomes. Three illustrative applications of trials using this approach are presented.

---

### Global strategy for asthma management and prevention [^2d5a224e]. GINA (2024). High credibility.

Asthma medications — controller denotes medication targeting both domains of asthma control (symptom control and future risk), and in the past 'controller' was largely used for ICS-containing medications prescribed for regular daily treatment so 'controller' and 'maintenance' became almost synonymous; to avoid confusion, 'ICS-containing treatment' and 'maintenance treatment' have been substituted as appropriate where the intended meaning was unclear.

---

### Guidelines for performing a comprehensive transthoracic echocardiographic examination in adults: recommendations from the American Society of Echocardiography [^5aa9dd7e]. Journal of the American Society of Echocardiography (2019). High credibility.

M-mode parameter and function — sweep speed changes the number of cardiac cycles displayed along the horizontal axis of the M-mode display, with example images at a sweep speed of 25 mm/sec and 50 mm/sec.

---

### Adaptation to feedback representation of illusory orientation produced from flash grab effect [^98b550d9]. Nature Communications (2020). High credibility.

The disks rotated 250° (degrees of rotation) every second and reversed direction every 240 ms (covering 60°, 1 sector, in that time). On each reversal a light–dark edge would be at the vertical orientation, and for every other rotation reversal (480 ms/cycle) two red vertical bars (0.3 dva width) were flashed on for 33 ms, aligned with the light–dark edges.

In the first experiment, we tested the TAE to perceived tilted but retinally vertical condition. We first measured the size of the FGE. Subjects were presented with a pair of rotating sectored disks and two vertical bars were flashed briefly at the direction reversals. A pair of green pointers (0.3 dva) was presented around each of the two disks. Using the keyboard, the subjects adjusted the angles between the pointers until the pointers and bars appeared to be aligned. They had unlimited time to adjust the angles, and were asked to press the spacebar when they were satisfied with the angle alignment to record the setting and to start the next trial. The two rotation directions (left clockwise and right counter-clockwise, vice versa) were tested 5 times each for each subject. The mean perceived tilt (away from vertical) across subjects was 15.55° (n = 8, SD = 7.54).

The adaptation trial sequence is depicted in Fig. 1a. On each trial, subjects were presented with the same patterned disks as in the flash-grab measurement part of the experiment and adapted to the two flash bars. The bars were perceived to be tilted due to the FGE. The adaptation period included 11 flashes (5.3 s) in each trial, followed by a 33.3 ms blank period. Then a pair of test bars were presented for 33.3 ms. The test bars were the same as the pair of red bars presented during the adaptation period except that the angle between two bars was varied ranging from −6.9° to +6.9° (seven variations, −6.9°, −2.3°, −1.1°, 0°, +1.1°, +2.3°, +6.9°, positive degree represents the two bars converging upward). Subjects were asked to judge whether the two test bars were converging upward or downward using a 2AFC method. The seven different angular conditions of bars were tested 20 times each (selected in random order across trials).

---

### Guidelines for the use of echocardiography as a monitor for therapeutic intervention in adults: a report from the American Society of Echocardiography [^0bd98e75]. Journal of the American Society of Echocardiography (2015). Medium credibility.

Prosthetic valve thrombolysis monitoring — echocardiographic thresholds and response assessment: "Both TTE and TEE have been used to detect prosthetic valve thrombosis and monitor therapy effectiveness", and "Fibrinolytic therapy is recommended if left-sided prosthetic valve thrombus area (planimetered on a 2D image) is < 0.8 cm^2, with serial Doppler echocardiographic monitoring of mean gradients across the valve to assess effectiveness of either fibrinolytic or unfractionated heparin treatment". "A significant reduction in the transvalvular gradient at 24 hours is indicative of effective therapy", and "both are equally effective at monitoring for reductions in transvalvular gradients".

---

### ESTES guidelines: acute mesenteric ischaemia [^f0f5bc7b]. European Journal of Trauma and Emergency Surgery (2016). Medium credibility.

Regarding follow-up and surveillance for acute mesenteric ischemia, more specifically with respect to second-look procedures, ESTES 2016 guidelines recommend to reassess ischemic bowel after adequate fluid resuscitation and revascularization. Perform a second-look procedure to assess the viability of the bowel if any doubt remains.

---

### Aperiodic nanoplasmonic devices for directional colour filtering and sensing [^fc6983eb]. Nature Communications (2017). Medium credibility.

Anti-symmetric spatial spectrum splitting

Spectrum splitting using diffractive optics has been utilized in recent years to enhance the photovoltaic output power in solar cellsas well as for hyperspectral imaging applications. Periodic plasmonic antennas have also been utilized to achieve symmetric, angularly continuous, directional spectral sorting of white-lightor emission from quantum dots and fluorophores. The angle-resolved colour sorter described above, on the other hand, can be exploited to achieve anti-symmetric spatial spectrum-splitting, in other words, spectrally resolving transmitted light into different angles all belonging to a single angular half-space with respect to the normal. This functionality results upon illumination of the un-patterned side of the structure with white light, i.e. "reverse illumination", leading to emergence of a discrete set of colour-sorted beams from the patterned side, each traveling along a different, pre-defined angle to one side of the normal only (Fig. 3, top panel). For experimental characterization of this effect, the fabricated device was illuminated at normal incidence on its groove-free side using a TM-polarized supercontinuum white-light laser light with H -field parallel to the slit-length (oriented along the y -direction at x = 0, Fig. 3). The colour and intensity distribution of the transmitted light in a far-field plane located at a distance Δ z = 17.5 μm from the device exit surface was imaged using an inverted optical microscope (×100, NA = 0.75 microscope objective) and a colour-CCD camera (where the x -position of the transmitted light field relative to the center of the slit is calibrated by imaging the exit surface of a reference single-slit illuminated under identical conditions). By directly measuring the distance of the local intensity maximum of the red, green, and blue streaks relative to the center of the slit, Δ x, the diffraction angles for the red, blue, and green light are determined to be 0° ± 0.49°, 9.72° ± 0.47°, and 18.92° ± 0.44° respectively. The uncertainty in measurement of angles is one standard deviation, and calculated from the uncertainty in measuring the distances of the red, green, and blue streaks relative to the normal to the slit due to the finite pixel-spacing of the CCD camera. The measured angles are close to the angles specified for angle-selective colour-filter operation under "forward illumination" (0°, 10°, and 20° respectively), verifying the time-reversal symmetric behavior expected for any linear device. Note that the same spectrally resolved angular output response can be achieved for any angle of "reverse illumination" on the un-patterned side, the slit acting as a spatial filter. This approach to map the wavelength of incident radiation to a given angle can also be readily extended to more than three input wavelengths (e.g. five, by applying reciprocity to the result of Supplementary Fig. 7) allowing hyperspectral imaging where a spectral image cube can be directly acquired in a single exposure using a two-dimensional array of such devices coupled to an imaging chip. In contrast to other spectral imaging techniques, the colour-sorting approach presented here does not rely on filters or scanning interferometers that require long acquisition times for spectral-cube measurements. The multi-colour functionality achieved here with a single-device stands in contrast to the mono-colour functionality, characteristic of periodic plasmonic structures that require physically separate structures to achieve a full set of discrete colour responses.

---

### Digoxin [^f3d4e389]. FDA (2025). Medium credibility.

3 DOSAGE FORMS AND STRENGTHS

Scored Tablets: 125 mcg are white to off-white, round shaped, flat faced, beveled edge, scored, uncoated tablets debossed with "D" "125" ("D" above the score and "125" below the score) on one side and plain on the other side.

Scored Tablets: 125 mcg (3)

---

### Promoting optimal development: screening for mental health, emotional, and behavioral problems: clinical report [^d13b5812]. Pediatrics (2025). High credibility.

Follow-up planning — once a decision on next steps has been reached in partnership with a family, it is important to ensure an appropriate follow-up plan, which will depend on the nature and severity of the problem, management plan implemented, and patient and family response to the plan.

---

### Roflumilast (Zoryve) [^e2de6cd7]. FDA (2024). Medium credibility.

The dosage of roflumilast TOP for treatment of plaque psoriasis in adults is 1 application(s) TOP daily (0.3% cream or foam)

---

### Viability and cosmesis of right angle and vertical paramedian forehead flaps are equivalent: a retrospective quantitative study [^06a4fb13]. Dermatologic Surgery (2022). Medium credibility.

Background

Paramedian forehead flaps (PMFFs) are commonly used for reconstruction of nasal defects. The classic PMFF is vertically oriented while the modified PMFF is designed with a 90-degree angle. No study has compared outcomes between these PMFF designs.

Objective

To compare and quantify viability and cosmesis of 90-degree and vertical PMFF.

Methods

Retrospective chart review of 70 consecutive patients with a vertical or 90-degree PMFF design for nasal repairs after Mohs micrographic surgery (MMS). Cosmetic outcome was assessed on a 10-cm, 100-point, visual analog scale (VAS) by an independent observer using standardized 3-month postoperative photographs. Flap viability was assessed using standardized 3-week postoperative photographs. Descriptive statistics, t -test, and Mann-Whitney test were used for statistical analysis.

Results

Forty-eight patients were repaired with a vertical PMFF and 22 using the 90-degree PMFF. The mean defect area of vertical and 90-degree designs was equivalent (7.7 ± 4.0 cm 2 vs 8.1 ± 4.0 cm 2, p = .70). There was no significant difference in cosmetic outcome (75.9 ± 9.4 vs 72.9 ± 6.8, p = .19) or flap viability (3.8% ± 11.6 vs 2.6% ± 7.9, p = .67) between vertical and 90-degree designs.

Conclusion

Vertical and 90-degree PMFF designs for nasal repairs after MMS are equivalent in cosmetic outcome and viability.

---

### Recommendations for cardiac chamber quantification by echocardiography in adults: an update from the American Society of Echocardiography and the European association of cardiovascular imaging [^7f030a8b]. Journal of the American Society of Echocardiography (2015). Medium credibility.

Right ventricular apical views — image acquisition guidance (Figure 7) explains that three apical images demonstrate different views of the right ventricle, with the middle image showing the right ventricular–focused view, and that minor variations in the four-chamber plane position relative to the right ventricular crescent shape may result in variability of right ventricular size when measured linearly.

---

### Diagnosis and classification of diabetes: standards of care in diabetes – 2025 [^568cafd9]. Diabetes Care (2025). High credibility.

Type 1 diabetes natural history and progression risk indicate that stage 1, defined by the presence of two or more autoantibodies and normoglycemia, carries a 5-year risk of developing symptomatic type 1 diabetes of ~44%. In stage 2, risk is ~60% by 2 years and ~75% within 5 years of developing a clinical diagnosis of type 1 diabetes. A consensus group provides expert recommendations on what should be monitored and how often these factors should be monitored in individuals with presymptomatic type 1 diabetes.

---

### Shape morphing of plastic films [^a96c261a]. Nature Communications (2022). High credibility.

Polygons

The adhesive layer was parallelly aligned with certain intervals. The width of the adhesive layer (w a) was calculated from the interior angles ɵ and the diameter of the peeled-off film, d, where w a = (180− ɵ) π d /360. The intervals are equal to the corresponding side length. Taking right triangle with interior angles of 60° and the shortest side length of 10 mm as an example, the diameter of peeled-off PTFE film (thickness of 80 μm, width of 4 mm) with Kapton tape as the adhesive layer and a peeling angle of 180° is 2 mm; thus, the widths of adhesive layers should be 2.62, 1.57, 2.09 and 2.62 mm, respectively, and the corresponding intervals should be 17.3, 10 and 20 mm, respectively (Fig. 3e). The PTFE film (thickness of 80 μm, width of 4 mm) was adhered vertical to the adhesive layer and peeled off at peeling angle of 180°. For an isosceles right triangle with a short side length of 10 mm, the widths of adhesive layers should be 2.36, 1.57, 2.36, and 2.36 mm, respectively, and the corresponding intervals should be 10, 10, and 14.1 mm, respectively. For an equilateral triangle with a side length of 10 mm, the widths of adhesive layers should be 2.09, 2.09, 2.09, and 2.09 mm, respectively, and the corresponding intervals should be 10, 10 and 10 mm, respectively. For the equilateral polygon with a side length of 10 mm, the widths of adhesive layers are 1.57, 1.26, and 1.05 mm with intervals of 10 mm for quadrangle, pentagon and hexagon, respectively.

---

### A modified reverse right-angled triangle osteotomy using the lateral approach for the treatment of posttraumatic cubitus varus deformity in children [^bbbb2306]. Journal of Pediatric Orthopedics (2023). Medium credibility.

METHODS

During the time between October 2017 and May 2020, 22 elbows with posttraumatic cubitus varus deformity were treated by means of a modified reverse right-angled triangle osteotomy at the Department of Pediatric Orthopaedics of our hospital. All procedures were carried out by a single senior surgeon. The surgical indication was that the difference between the affected side and the healthy contralateral side was at least 20 degrees and the parents requested surgical treatment. The 22 patients involved included 6 female and 16 male patients with an average age of 10.3 years (range, 8 to 13 years) at the time of the osteotomy. The average time from injury to the osteotomy was 2.2 years (range, 1.1 to 3.2 years). Thirteen patients had a right-sided deformity and 9 had a left-sided deformity. All patients presented with an extension type of supracondylar fracture at the time of injury. The procedures were performed after the approval of the Institutional Ethics Committee and informed consent was obtained from the patients and their families.

Preoperative Planning and Operative Technique

Design drawing of paper simulated osteotomy was performed before surgery. The initial osteotomy was performed 0.5 to 1 cm superior to the olecranon fossa and perpendicular to the lateral rim of the distal humerus (line AB) (Fig. 1 A). The proximal end of the humerus osteotomy was resected with a reverse right-angled triangle so that the DAE angle was equal to the intended angle of correction (Fig. 1 B). The intended angle of correction was equal to the sum of the carrying angle of the normal side plus the varus angle of the affected side and the expectation of 5 degrees of correction loss after surgery. According to the relevant knowledge of the right triangle, the angle DBA was equal to the angle DAE, which was the expected correction angle. After the inverted right triangle, ADB was cut off at the proximal end of the humerus osteotomy, and the apex A of the distal humeral osteotomy segment was rotated inward and overlapped with the apex D to complete the distal humeral valgus osteotomy (Fig. 1 C).

---

### American College of Gastroenterology guidelines update: diagnosis and management of celiac disease [^2f907187]. The American Journal of Gastroenterology (2023). High credibility.

Celiac disease gluten challenge steps within the diagnostic algorithm include specific dosing and timing: The algorithm specifies 3 g gluten daily for 2 weeks, then 3 g gluten daily for up to 6 additional weeks, with repeat serology at end of challenge and repeat serology 2 to 6 weeks after end of challenge.

---

### Standards of care in diabetes – 2025 [^d4969f8c]. Diabetes Care (2025). High credibility.

Regarding diagnostic investigations for diabetes mellitus type 1, more specifically with respect to screening for PAD, ADA 2025 guidelines recommend to assess lower extremity pulses, capillary refill time, rubor on dependency, pallor on elevation, and venous filling time for initial screening of PAD. Obtain ankle-brachial index with toe pressures and further vascular assessment as appropriate in patients with symptoms of claudication or decreased or absent pedal pulses.

---

### The management of newly diagnosed large B-cell lymphoma: a British Society for Haematology guideline [^0b5325ec]. British Journal of Haematology (2024). High credibility.

Regarding diagnostic investigations for diffuse large B-cell lymphoma, more specifically with respect to imaging for staging, BSH 2024 guidelines recommend to consider obtaining contrast-enhanced CT of the neck, chest, abdomen, and pelvis as an alternative if PET-CT is impractical or as an additional imaging modality in selected cases.

---

### The importance of purkinje activation in long duration ventricular fibrillation [^eea7b774]. Journal of the American Heart Association (2014). Low credibility.

Animal preparation

Six pigs (41 ± 8 kg, mean ± SD) and 6 dogs (32 ± 5 kg) were injected intramuscularly with Telazol (4.4 mg/kg), xylazine (2.2 mg/kg), and atropine (0.04 mg/kg) for anesthetic induction. Anesthesia was maintained with isoflurane in 100% oxygen by inhalation. Core body temperature, arterial blood pressure, arterial blood gases, and serum electrolytes were monitored and maintained within normal ranges throughout the study. ECG lead II was continuously displayed. The heart was exposed through a median sternotomy and supported in a pericardial sling. A plaque containing 504 electrodes (24×21) with 2 mm spacing between each electrode (Figure 1 A) was sutured to the anterior lateral LV, with one edge of the plaque adjacent to the LAD (Figure 1 D). Two rows of plunge needles, each with 12 electrodes 2 mm apart (Figure 1 B), were inserted across one another over the midlines of the plaque, so that, together with the epicardial array, the electrodes formed 3 orthogonal planes (Figure 1 C). The vertical array was a row of 24 plunge needles 2 mm apart extending from the base to the apex of the anterior LV. The horizontal array was a row of 21 plunge needles 2 mm apart placed at a right angle to the vertical array (Figure 1 D). The needles were fabricated from glass‐reinforced epoxy according to a new design. The needle shafts were 0.5 mm in diameter, which is about half the diameter of traditional steel needle electrodes and minimizes damage to the myocardium. We showed in our previous publication and in the first 3 animals in this study that such a needle array does not affect VF activation patterns. A stainless steel wire was attached to the right leg as the reference electrode for the unipolar mapping electrodes. A catheter (SPRINT™ 6942 to 65 cm, Medtronic, Inc) containing a 5‐cm‐long right ventricle (RV) coil (479 mm 2 surface area) and an 8‐cm‐long SVC coil (766 mm 2 surface area) defibrillation electrodes were inserted into the right jugular vein. One electrode was in the right ventricular apex and the other was near the junction of the superior vena cava and the right atrium. To pace the heart, pairs of barbed silver wire electrodes insulated, except at the tips, were inserted into the LV epicardium via 21G needles. The pacing electrodes were 2 to 5 mm away from the edges of the mapping plaque (Figure 1 A). After needle insertion, we waited 20 minutes to allow injury currents to subside.

---

### Standards of care in diabetes – 2025 [^9fec4de9]. Diabetes Care (2025). High credibility.

Regarding follow-up and surveillance for diabetes mellitus type 1, more specifically with respect to continuous glucose monitoring, ADA 2025 guidelines recommend to assess skin reactions, either due to irritation or allergy, and address to aid in successful use of devices.

---