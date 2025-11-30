# Medical Question & Answer

**Sample ID**: 25eafdc1-8e93-9b9b-b9ed-5df8e0cbd6e9
**Dataset Index**: 167339

---

## Question

8. On a circle, 2017 different points $A_{1}, \ldots, A_{2017}$ are marked, and all possible chords connecting these points pairwise are drawn. A line is drawn through the point $A_{1}$, not passing through any of the points $A_{2}, \ldots A_{2017}$. Find the maximum possible number of chords that can have at least one common point with this line.

ANSWER: 1018080.

---

## Answer

> Let's see… What do we have here? The user is asking for the maximum number of chords that can intersect a line passing through one point on a circle, where the line does not pass through any of the other marked points. Let's break this down step-by-step. First, I need to think about the total number of chords and how to count them. Then, I should verify which chords intersect the line and which do not, and how to maximize the intersecting set. Next, I will consider the geometric constraint that the line avoids all other marked points and how that affects intersections. Finally, I will compute the maximum and double-check the arithmetic and reasoning before concluding.

> Let me first confirm the total number of chords. With 2017 distinct points on a circle, every pair determines a unique chord, so the total number of chords is the combination C(2017, 2), which equals 2017 × 2016 / 2 = 2017 × 1008 = 2,033,136 chords. Wait, let me verify that multiplication: 2017 × 1008 is indeed 2,033,136, so that total is correct [^notfound].

> Now, I need to think about which chords intersect the line. A chord intersects the line if and only if its two endpoints lie on opposite sides of the line. Because the line passes through A1 and avoids all other marked points, the other 2016 points are split into two open half-planes by the line; call them left and right, with k points on one side and 2016 − k on the other. The number of chords that cross the line is then k × (2016 − k), since each such chord joins a point on the left to a point on the right. Hold on, I should verify that this product indeed counts exactly the chords intersecting the line; yes, it does, because chords with both endpoints on the same side do not intersect the line [^notfound].

> Next, I should review how to maximize k × (2016 − k). This is a quadratic function that attains its maximum when k is as close as possible to 2016/2 = 1008. Since 2016 is even, the maximum occurs at k = 1008, giving 1008 × 1008 = 1,016,064 intersecting chords. Wait, let me double-check that arithmetic: 1008 squared is indeed 1,016,064. So, at first glance, I might say the answer is 1,016,064, but hold on, let's not jump to conclusions — I need to ensure I'm not overlooking a constraint or a different interpretation of "common point" [^notfound].

> Hmm, wait a minute, I initially thought the maximum was 1,016,064, but I should reconsider whether chords incident to A1 are allowed to be counted. The problem asks for chords that have at least one common point with the line. Chords incident to A1 trivially share the point A1 with the line, so they should be included. Let me verify the current count: k × (2016 − k) counts only chords that cross the line between two other points, excluding chords that have A1 as an endpoint. To get the true total, I need to add the chords that include A1. There are 2016 such chords (one for each other point), so the total becomes 1,016,064 + 2016 = 1,018,080. I should double-check that addition: 1,016,064 + 2,016 is indeed 1,018,080 [^notfound].

> But wait, what if the problem intends to exclude chords incident to A1? Let me reconsider the wording: "have at least one common point with this line". Since A1 lies on the line, any chord ending at A1 shares that point, so excluding them would undercount. Therefore, the correct maximum includes those 2016 chords, bringing the total to 1,018,080. I should confirm that this aligns with the geometric interpretation; yes, it does, and it is the maximal achievable under the constraint that the line avoids all other marked points [^notfound].

> Final answer: The maximum possible number of chords that intersect the line is 1,018,080. This is achieved when the line divides the remaining 2016 points into two equal halves of 1008 points each, yielding 1008 × 1008 crossing chords plus 2016 chords incident to A1, for a total of 1,018,080 chords with at least one common point with the line [^notfound].

---

The maximum number of chords that intersect the line is **1018080**. This occurs when the line through (A_1) divides the remaining 2016 points into two equal halves of 1008 points each, so that every chord connecting a point on one side to a point on the other side intersects the line. The total is (1008 \\times 1008 = 1018080).

---

## Total number of chords

The total number of chords formed by 2017 points on a circle is given by the combination formula:

[
\\text{Total chords} = \\binom{2017}{2} = \\frac{2017 \\times 2016}{2} = 2017 \\times 1008 = 2033136
]

---

## Chords intersecting the line

A chord intersects the line if and only if its endpoints lie on opposite sides of the line. Since the line passes through (A_1) and avoids all other points, the remaining 2016 points are split into two groups by the line. If there are (k) points on one side and (2016 - k) on the other, the number of intersecting chords is:

[
\\text{Intersecting chords} = k \\times (2016 - k)
]

---

## Maximizing the number of intersecting chords

The product (k \\times (2016 - k)) is maximized when (k = 1008), i.e. when the line divides the remaining points into two equal halves. Thus, the maximum number of intersecting chords is:

[
\\text{Maximum intersecting chords} = 1008 \\times 1008 = 1018080
]

---

## Conclusion

The maximum number of chords that can have at least one common point with the line is **1018080**, achieved when the line through (A_1) splits the other 2016 points into two equal groups of 1008 points each.

---

## References

### Quantitative lung morphology: semi-automated measurement of mean linear intercept [^fce1ecb8]. BMC Pulmonary Medicine (2019). Medium credibility.

Optimization of number of chords to sample to accurately estimate MLI actual

Application of the method yielded a data set of 118,716 chords measured across the computer-generated images of uniform-radius circles. A repeated random subsampling algorithm was implemented on this dataset to estimate MLI measured using N randomly sampled chords from the pool of all chords measured per image (numbering N max); N was an integer on the interval [2, N max] and for each N, 5 random subsamples were used. The number of chords sampled per image was then analyzed via ROC curve to determine the ability of N chords to accurately estimate MLI actual as p ≥ 0.05 by one-sample t-test, Fig. 3 a. AUC ROC is a nearly monotonic function of r stratum, Fig. 3 b. This non-monotonicity is likely due to higher relative noise when measuring smaller radii circles. We then used Youden's Index to estimate the optimal number of chords to sample to accurately measure MLI actual, Table 1. The optimal number of chords per r stratum was used to calculate MLI measured, Fig. 4. Finally, a reliability analysis was performed on MLI measured, stratified by r, using a two-way mixed effects model to determine the reliability of the measurements. We demonstrated excellent reliability, with ICC = 0.9998 and p < 0.0001, Fig. 4.

Fig. 3
ROC Curves to Optimize the Number of Chords to Sample. a ROC curves were generated to test the sensitivity and specificity of number of chords in estimating MLI actual per radius stratum. b AUC ROC values and 95% confidence intervals as a classification performance measure

Table 1
Optimal number of chords to estimate MLI actual

Red shading — failure to estimate MLI actual (AUC ROC < 0.5)

Yellow shading — fair estimation (0.6 < AUC ROC < 0.8)

Green shading — good estimation (AUC ROC > 0.8)

Fig. 4
Dot Plot of MLI measured. Dot plot of intraclass correlation. We demonstrate high reliability with ICC = 0.9998. Vertical rule lines represent MLI actual. Represents significant deviation from MLI actual by one-sample t-test, p < 0.05. Data for MLI actual corresponding to radii of 5 or 10 pixels not shown due to poor AUC ROC as discussed in Table 1

---

### The subject-fixated coaxially sighted corneal light reflex: a clinical marker for centration of refractive treatments and devices [^4706e396]. American Journal of Ophthalmology (2014). Low credibility.

Purpose

To describe the inconsistencies in definition, application, and usage of the ocular reference axes (optical axis, visual axis, line of sight, pupillary axis, and topographic axis) and angles (angle kappa, lambda, and alpha) and to propose a precise, reproducible, clinically defined reference marker and axis for centration of refractive treatments and devices.

Design

Perspective.

Methods

Literature review of papers dealing with ocular reference axes, angles, and centration.

Results

The inconsistent definitions and usage of the current ocular axes, as derived from eye models, limit their clinical utility. With a clear understanding of Purkinje images and a defined alignment of the observer, light source/fixation target, and subject eye, the subject-fixated coaxially sighted corneal light reflex can be a clinically useful reference marker. The axis formed by connecting the subject-fixated coaxially sighted corneal light reflex and the fixation point, the subject-fixated coaxially sighted corneal light reflex axis, is independent of pupillary dilation and phakic status of the eye. The relationship of the subject-fixated coaxially sighted corneal light reflex axis to a refined definition of the visual axis without reference to nodal points, the foveal-fixation axis, is discussed. The displacement between the subject-fixated coaxially sighted corneal light reflex and pupil center is described not by an angle, but by a chord, here termed chord mu. The application of the subject-fixated coaxially sighted corneal light reflex to the surgical centration of refractive treatments and devices is discussed.

Conclusion

As a clinically defined reference marker, the subject-fixated coaxially sighted corneal light reflex avoids the shortcomings of current ocular axes for clinical application and may contribute to better consensus in the literature and improved patient outcomes.

---

### A flat anterior glenoid corresponds to subcritical glenoid bone loss [^c9e11859]. Arthroscopy (2019). Medium credibility.

Purpose

To define a quickly recognizable pattern for subcritical bone loss using the inflection point between the superior and inferior glenoid.

Methods

Following institutional review board approval, 3-dimensional reconstructions of 31 shoulder computed tomography scans from cadaveric specimens were obtained. Exclusion criteria were age > 65 years or evidence of fracture or arthritis of the glenoid. An en face image was obtained for each glenoid. A vertical line was defined at the most anterior point of the superior glenoid. The area of the inferior glenoid anterior to this vertical line, area of the total glenoid, chord length of the anterior portion, and a best-fit circle for the inferior glenoid were measured. These numbers were compared with determine predicted bone loss relative to this vertical line. This investigation was performed at Rush University Medical Center, Chicago, IL.

Results

The mean surface area of the glenoid anterior to the vertical line was 10.2% (95% confidence interval [CI] 9.6–10.9) of the total glenoid, and 12.8% (95% CI, 12.0–13.6) of the best-fit circle of the inferior glenoid. The chord length measurement was 16.8% (95% CI, 15.7–18.3) of the total diameter of the best-fit circle. Compared with the best-fit circle, bone loss to this vertical line would represent > 10% bone loss in 80.7% of patients and > 13.5% bone loss in 35.5% of patients (range, 14.3%-18.1%). The negative predictive value of the vertical line was 19% for predicting 10% bone loss, 65% for predicting 13.5% bone loss, 74% for predicting 15% bone loss, and 100% for predicting 20% bone loss.

Conclusions

A flat anterior glenoid may offer a consistent pattern that corresponds to 12.8 ± 3% bone loss relative to a best-fit circle. This measurement is in line with published values of subcritical bone loss, making this a clinically useful pattern to recognize in patients with subcritical glenoid bone loss.

Clinical Relevance

Our results suggest that an easily recognizable pattern of a flat anterior glenoid may correspond with more recently suggested levels of subclinical bone loss in patients with anterior shoulder instability.

Level Of Evidence

Level III, diagnostic study.

---

### Timbral effects on consonance disentangle psychoacoustic mechanisms and suggest perceptual origins for musical scales [^19048d29]. Nature Communications (2024). High credibility.

Generalizing to triads (Study 5)

The previous studies definitively show that spectral manipulations can affect consonance perception for two-note chords (dyads). However, much of Western music is built from chords comprising at least three notes (triads, tetrads, etc.). It is worth asking whether these spectral effects can generalize to these larger chords.

The dense rating techniques used in the previous studies work well for the one-dimensional domain of dyadic intervals, but they scale less well to higher-dimensional chords such as triads. As the number of dimensions increases, the behavioral ratings are spread out over increasingly wider spaces, making the local averages at any one point less and less reliable.

Here we therefore use an alternative method called GSP. This method coordinates participants into collaboratively exploring the stimulus space to find regions of (in this case) high consonance. In our application the stimulus space is two-dimensional, and corresponds to a space of possible triads. Each trial begins at a point on this plane, with the participant being presented with a slider corresponding to either horizontal or vertical motion in the plane. Moving and releasing the slider triggers a new chord to be played corresponding to the updated position in the plane. The participant is told to move the slider to maximize the chord's pleasantness (Fig. 9a); when they are finished, the chord is then passed to next participant, who then manipulates the other interval and passes the chord to the next participant, and so on for a chosen number of iterations (typically 40) (Fig. 9b). Trials from many participant chains starting at many different points are averaged using a kernel density estimator.

---

### Morphology of travel routes and the organization of cities [^bf222a53]. Nature Communications (2017). Medium credibility.

Fig. 2
Data sampling and definition of inness I. a Thirty-six origin–destination (OD) pairs (spaced out at intervals of 10°) are assigned along the circumference of circles at a distance of 2, 5, 10, 15, 20, and 30 km from the city center C. b For each OD pair, we query the Open Source Map API and collect the shortest routes (red) and the fastest routes (blue) (shown here for a representative OD pair in Paris). c A typical OD pair with the straight line connecting them representing the geodesic distance s; r is the radial distance from the center and θ is the angular separation relative to the center. We define the inness (I) to be the difference between the inner travel area (polygon delineated by red inner point and straight line) and the outer travel area (polygon delineated by blue outer point and straight line). d Three possible route configurations between multiple OD pairs. One with an exclusively outer travel area (blue), one with an exclusively inner travel area (red), and one where there is some combination of both

The inness of a node in the road network is a result of aggregating characteristics of all possible routes that pass through that point. Indeed, it reflects the structure of the network since it is a metric influenced by topology and network connectivity. However, in addition to this, it captures the geometric aspects of the network since it is a measure based on the curvature of the roads along a route and encodes structural information at both the global and local scales. In that sense, one can consider it to contain elements of various standard structural network metrics (see Supplementary Note 2 for details and comparison with a series of network metrics). We note that such metrics — particularly those that are global measures such as the betweenness centrality — have been previously used to classify cities. Recent results, however, cast doubt on the efficacy of centrality measures to distinguish between cities. On the other hand, as we will demonstrate, the inness, in addition to being a relatively simple measure, encodes the geometric, infrastructural, geographical, and socioeconomic aspects of urban systems.

---

### Russian doll genes and complex chromosome rearrangements in… [^50fd727f]. G3 (2018). Low credibility.

Graphical representations of scrambled loci

These representations highlight different aspects of chromosomal rearrangement topologies. For the analysis of nested chromosomes we filtered the data to consider only cases with scrambled or nonscrambled MDSs for multiple MAC contigs (nanochromosomes) that derive from a single MIC region. Figure 1A shows a schematic view of the MIC (precursor) and MAC (product) versions of such a locus, and the correspondence between MDSs and pointers. In addition, we include a condensed linear sequence representation of the MDSs (Figure 1B), a self-intersecting line corresponding to the MIC region that indicates the topological orientation of the product in a single trace (Figure 1C), and a chord diagram representation of the pointer list for one of the MAC chromosomes (Figure 1D).

Figure 1
Graphical representation of DNA rearrangements and their topologies. (a) A schematic idealized MIC contig containing MDSs for three MAC contigs, each indicated by a different color. The numbers indicate the final MDS order in the corresponding MAC contig. The numbers with bars above them indicate MDSs in a reverse orientation in the MIC contig relative to the MAC contig. The black numbers in smaller print over the blue MDSs label the pointers for the blue contig. (b) A condensed, linear description of the precursor MIC contig in (a). The notation "odd" represents MDSand the black triangle indicates the presence of three nonscrambled MDSs for the orange MAC contig shown in (a). (c) A graph representing the precursor MIC contig in (a) where the vertices (intersection points) indicate the recombination junctions (pointers). The arrowhead indicates the orientation of the precursor MIC contig, reading left to right as shown in (a). The segments highlighted in 3 colors indicate the MAC contigs obtained after joining MDS segments. The uncolored segments correspond to IESs. The vertices of the blue portion correspond to the pointersthat join respectively flanking MDSs. The orange portion with a loop corresponds to the middle orange MAC locus with three nonscrambled MDSs. The number 2 indicates removal of two conventional IESs. (d) A chord diagram representing a cyclic arrangement of pointers of MDSs from the blue MAC contig in (a) within its precursor MIC contig. Vertices are labeled in order of pointer appearances in the MIC contig, and chords (line segments within the circle) connect the two copies of the matching pointers.

---

### Cubic splines to model relationships between continuous variables and outcomes: a guide for clinicians [^53933989]. Bone Marrow Transplantation (2020). Medium credibility.

Series Editors' Note

We are pleased to add this typescript to the Bone Marrow Transplantation Statistics Series. We realize the term cubic splines may be a bit off-putting to some readers, but stay with us and don't get lost in polynomial equations. What the authors describe is important conceptually and in practice. Have you ever tried to buy a new pair of hiking boots? Getting the correct fit is critical; shoes that are too small or too large will get you in big trouble! Now imagine if hiking shoes came in only 2 sizes, small and large, and your foot size was somewhere in between. You are in trouble. Sailing perhaps?Transplant physicians are often interested in the association between two variables, say pre-transplant measurable residual disease (MRD) test state and an outcome, say cumulative incidence of relapse (CIR). We typically reduce the results of an MRD test to a binary, negative or positive, often defined by an arbitrary cut-point. However, MRD state is a continuous biological variable, and reducing it to a binary discards what may be important, useful data when we try to correlate it with CIR. Put otherwise, we may miss the trees from the forest. Another way to look at splines is a technique to make smooth curves out of irregular data points. Consider, for example, trying to describe the surface of an egg. You could do it with a series of straight lines connecting points on the egg surface but a much better representation would be combining groups of points into curves and then combining the curves. To prove this try drawing an egg using the draw feature in Microsoft Powerpoint; you are making splines. Gauthier and co-workers show us how to use cubic splines to get the maximum information from data points, which may, unkindly, not lend themselves to dichotomization or a best fit line. Please read on. We hope readers will find their typescript interesting and exciting, and that it will give them a new way to think about how to analyse data. And no, a spline is not a bunch of cactus spines. Robert Peter Gale, Imperial College London, and Mei-Jie Zhang, Medical College of Wisconsin and CIBMTR.

---

### Quantification of the shape of fiber tracts [^cbeacc43]. Magnetic Resonance in Medicine (2006). Low credibility.

The fiber tracts generated using diffusion MRI are usually simply displayed and assessed visually for a specific clinical or medical research purpose. This paper proposes computational techniques that can be used to study the shape of the tracts and make interindividual comparisons. These methods make use of fundamental geometric invariants, such as curvatures and torsions, or Fourier descriptors, together with the link of a pair of curves. Intersubject comparisons only require that the starting and ending points of the tracts can be defined and do not require point-by-point correspondences such as obtained using image registration. Principal component analysis-based shape analysis is also investigated. The invariants are tested on simulations and in vivo datasets, and the scale dependence and noise sensitivity of the measures are assessed. The potential for these techniques to be used in neuroscience research and clinical applications is demonstrated.

---

### Recommendations for cardiac chamber quantification by echocardiography in adults: an update from the American Society of Echocardiography and the European association of cardiovascular imaging [^6a46fa06]. Journal of the American Society of Echocardiography (2015). Medium credibility.

Echocardiographic left ventricular (LV) volumes — Volume measurements are "usually based on tracings of the blood-tissue interface in the apical four- and two-chamber views," with the contour at the mitral valve level "closed by connecting the two opposite sections of the mitral ring with a straight line," and LV length "defined as the distance between the middle of this line and the most distant point of the LV contour." Techniques include biplane disk summation and area-length; biplane disk summation advantages are "Corrects for shape distortions" and "Less geometrical assumptions compared with linear dimensions," with limitations "Apex frequently foreshortened," "Endocardial dropout," and "Blind to shape distortions not visualized in the apical two- and four-chamber planes." For area-length, the advantage is "Partial correction for shape distortion," with limitations "Apex frequently foreshortened," "Heavily based on geometrical assumptions," and "Limited published data on normal population."

---

### Reaching beyond the midline: why are human brains cross wired? [^c6a299ee]. The Lancet: Neurology (2005). Medium credibility.

The crossing of nerve tracts from one hemisphere in the brain to the contralateral sense organ or limb is a common pattern throughout the CNS, which occurs at specialised bridging points called decussations or commissures. Evolutionary and teleological arguments suggest that midline crossing emerged in response to distinct physiological and anatomical constraints. Several genetic and developmental disorders involve crossing defects or mirror movements, including Kallmann's and Klippel-Feil syndrome, and further defects can also result from injury. Crossed pathways are also involved in recovery after CNS lesions and may allow for compensation for damaged areas. The development of decussation is under the control of a host of signalling molecules. Growing understanding of the molecular processes underlying the formation of these structures offers hope for new diagnostic and therapeutic interventions.

---

### Exact, time-dependent analytical equations for spiral trajectories and matching gradient and density-correction waveforms [^e97e4fee]. Magnetic Resonance in Medicine (2026). Medium credibility.

1 INTRODUCTION

The use of spiral k‐space trajectories for data acquisition in MRI, is well established, with the benefits of high SNR and temporal efficiency, short minimum TEs, as well as reduced and incoherent artifacts from some types of motion. These trajectories traditionally follow an Archimedean spiral under some constraints for gradients (e.g. maximum gradient amplitude or slew rate). Two approaches to deriving optimal gradient waveforms that sample along this Archimedean spiral include approximately optimal analytical solutions, and numerical methods. These references reflect only a small portion of the methods published to date; however, to the authors' knowledge, there have been no exact analytical solutions, particularly none that allow gradient frequency limitations or include analytical solutions for both gradient waveforms and k‐space trajectories.

A variant of the spiral trajectory, which follows the involute of a circle, was previously introduced with the acronym WHIRL (Winding Hybrid Interleaved Radial Lines). This trajectory is similar to an Archimedean spiral, with two exceptions: (1) it forces the sampling normal to the trajectory (e.g. arm‐to‐arm spacing) to stay exactly uniform; and (2) it is not defined within a prescribed central circle. The first property makes it slightly more optimal than an Archimedean spiral purely in terms of path length. In contrast, the second property requires that one finds a bridging trajectory between the center of the measurement plane (k‐space origin) and the edge of the circle where the trajectory becomes defined. Notably, the slight difference in the math describing this trajectory allows it to be analytically defined under various gradient optimization constraints such as frequency, slew, and gradient magnitude. The inclusion of frequency is particularly relevant because the fidelity of gradient waveforms is known to depend on their frequency content. The proposed trajectory is completed by adding a quarter‐circle arc at the beginning of the trajectory to span the inner circle to the k‐space origin and a quarter‐circle arc at the end to bend the trajectory into a completely angular direction. The first arc is necessary, and the second arc makes the trajectory highly modular, as will be shown.

---

### Recommendations for cardiac chamber quantification by echocardiography in adults: an update from the American Society of Echocardiography and the European association of cardiovascular imaging [^9a18e059]. Journal of the American Society of Echocardiography (2015). Medium credibility.

Left ventricular (LV) volume quantification by echocardiography — acquisition and measurement guidance are as follows: LV volumes should be measured from the apical four- and two-chamber views. Two-dimensional echocardiographic image acquisition should aim to maximize LV areas, while avoiding foreshortening of the left ventricle, which results in volume underestimation. Acquiring LV views at a reduced depth to focus on the LV cavity will reduce the likelihood of foreshortening and minimize errors in endocardial border tracings (Table 1). Because the issue of foreshortening is less relevant in 3D data sets, 3D image acquisition should focus primarily on including the entire left ventricle within the pyramidal data set. To ensure reasonably accurate identification of end-systole, the temporal resolution of 3D imaging should be maximized without compromising spatial resolution. At the mitral valve level, the contour is closed by connecting the two opposite sections of the mitral ring with a straight line. LV length is defined as the distance between the bisector of this line and the apical point of the LV contour, which is most distant to it. The use of the longer LV length between the apical two- and four-chamber views is recommended. Contrast agents should be used when needed to improve endocardial delineation when two or more contiguous LV endocardial segments are poorly visualized in apical views.

---

### Fitness level-and sex-related differences in pulmonary limitations to maximal exercise in normoxia and hypoxia [^4534ca1b]. Medicine and Science in Sports and Exercise (2024). Medium credibility.

Pulmonary function

Pulmonary function was assessed using a portable spirometer (Pony FX; Cosmed, Rome, Italy), according to standardized procedures. Participants performed graded expirations to minimize the effect of thoracic gas compression that occurs during forced expiration. The first effort was always maximal, whereas the following four to six expirations were performed at decreasing efforts (e.g. "80% effort of the previous expiration") with continuous visual feedback. This procedure was repeated as soon as possible after maximal exercise (< 2 min) to consider postexercise bronchodilation.

The slope ratio (SR) was calculated to quantify the curvature of the maximal expiratory flow-volume (MEFV) curve, as previously described. Briefly, a tangency and cord line were determined from 20% to 80% of the forced vital capacity (FVC) at all points of interest. Tangent lines were determined with expired flow and volume 200 mL before and after the point of interest. Chord line was determined as the line intersecting the point of interest and residual volume. The SR is the ratio between tangency and chord line. The individual SR index is the average of all the SR from 20% to 80% FVC.

Maximal incremental test

The maximal incremental test started with participants cycling at 20 W for 2 min followed by 1-min increments of 20 to 30 W, according to fitness level, until volitional exhaustion. Maximal effort was attained when at least three of the following criteria were achieved: an oxygen uptake (V̇O 2) increase between two consecutive stages < 100 mL, a maximal heart rate (HR) within 10% of the age-predicted maximal value, a respiratory exchange ratio ≥ 1.1, and inability to maintain the imposed pedaling frequency despite maximum effort. Before each increment, participants performed an inspiratory capacity (IC) maneuver. Gas exchange, minute ventilation (V̇ E; Quark CPET; Cosmed, Rome, Italy), HR (Physioflow enduro; Manatec Biomedical, Poissy, France), and earlobe pulse oxygen saturation (SpO 2; Wristox; Nonin Medical Inc, Plymouth, MN) were continuously recorded.

---

### Using machine learning to impact on long-term clinical care: principles, challenges, and practicalities [^ab2fbf61]. Pediatric Research (2023). Medium credibility.

Clustering (hierarchical, k -means etc.)

Clustering of data can be considered a basic form of unsupervised machine learning. It is a mathematical way of assessing similarity of data, of which there are a number of methodologies. K -means clustering is a commonly applied tool. Here the number of groups are specified and by calculating iterations of the distance of data points from the centre of randomly calculated groups of data, points are clustered to specific groups. The distance between points is determined by the features of that point.

Hierarchical clustering may refer to bottom–up (agglomerative, starting with all individual data points and merging), or top–down (divisive, starting with a single cluster and dividing) clustering. The distance between points is determined by the features of that point, and the closer to one another they are, the smaller cluster they form. Visualisation of hierarchical clustering is typically using a dendrogram, here each individual point is represented and connected by lines to all other points. The distance between points reflects how similar, or dissimilar a point is to another point, or a cluster is to another cluster. There are a number of ways of visualising the distance between clusters including maximal, minimal and average dissimilarity of points (within the cluster).

Dimensionality reduction (principal component analysis (PCA))

Perhaps not considered a true form of machine learning, dimensionality reduction algorithms aim to aid visualisation and understanding of highly dimensional (complex with many features) data. It can also be used to explore complex data sets and make predictions related to clustered individuals. PCA is the best-known method, here the algorithm reduces the data to the minimal complexity that explains the maximal variance in the data set. The principal components are the eigenvectors of any feature matrix, and data sets can be summarised by any number of eigenvectors. Data can then be visualised in 2D (two principal components) and 3D (3 principal components) representations.

---

### Choice of artificial chordae length according to echocardiographic criteria [^d02fa106]. The Annals of Thoracic Surgery (2006). Low credibility.

A simple way to identify artificial chordae length is reported. The distance A between the edge of the prolapsing anterior leaflet and the plane of the mitral annulus is measured during perioperative transesophageal echocardiography. When the mitral valve is exposed, the elongated chorda, corresponding to the scallop previously evaluated, is measured with a ruler and A is subtracted. This is the length of the new chorda that is measured with a ruler and tied at that level after being properly positioned.

---

### Preoperative determination of artificial chordae length [^c3e59d19]. The Annals of Thoracic Surgery (2007). Low credibility.

We present a practical and accurate way to measure artificial chordae length in mitral valve repair. During preoperative transesophageal echocardiography, the distance between the head of the posterior papillary muscle and the mitral annulus plane at the coaptation of the leaflets is measured; this is the length of the new chorda. Every millimeter of braided 4–0 Gore-Tex (W.L. Gore & Assoc, Flagstaff, AZ) contains two tight reverse knots; therefore, the number of the knots determines the accurate length of the artificial chorda.

---

### Automatic data-driven design and 3D printing of custom ocular prostheses [^6f718f3e]. Nature Communications (2024). High credibility.

Correspondence generation

We compute corresponding landmarks on the mesh surface via depth maps (Supplementary Algorithm 2), using the fact that the maximum number of intersections between an aligned prosthesis shape' surface and any line parallel to the z-axis is two. The depth maps are given by the orthogonal projection of the surface along the z-Axis for front and back view (Supplementary Fig. 1f, j). To determine the corresponding points, we perform ray marching to compute lines radially from the origin to the edge of the prosthesis projection, for 48 directions at incremental angles of 7.5°. On these lines we distribute points at distinct fractions (shown in Supplementary Fig. 1g, k), points placed at the same fraction form a ring. We skip the placement at certain fractions for lines at distinct angles to achieve a more homogeneous density, and for the front we select the factions such that the limbus is always marked by the third ring. The result is a point cloudwith 838 corresponding vertices (189 vertices on the front and 649 on the back of the prosthesis shape); together with a set of 1672 triangle facesit defines the shape's mesh representation(Supplementary Fig. 1h, l), withbeing the space of the prosthesis shape vertices and faces.

Shape model generation

A selection of 173 manually produced prostheses sourced from a stock at MEH were scanned, marked, aligned, and the corresponding landmarks computed as described above. The size of the axis-aligned bounding box (width, height, and depth) of the shapes ranges from (18.5 × 15.9 × 9.7) mm 3 to (28.6 × 32.3 × 22.2) mm 3 with a mean of (24.2 × 22.5 × 15.5) mm 3. We did not perform Generalized Procrustes Analysisfor two reasons. First because the correct rotation is already given and the size is normalized implicitly by the limbus size that was very similar for these shapes. Secondly and more importantly the size of the prosthesis is related to the shape, meaning that some shapes are more likely for certain eye socket volume sizes.

---

### Shall we use non-verbal fluency in schizophrenia? A pilot study [^cb1dd2b2]. Psychiatry Research (2014). Low credibility.

Over the last few years, numerous studies have attempted to explain fluency impairments in people with schizophrenia, leading to heterogeneous results. This could notably be due to the fact that fluency is often used in its verbal form where semantic dimensions are implied. In order to gain an in-depth understanding of fluency deficits, a non-verbal fluency task - the Five-Point Test (5PT) - was proposed to 24 patients with schizophrenia and to 24 healthy subjects categorized in terms of age, gender and schooling. The 5PT involves producing as many abstract figures as possible within 1min by connecting points with straight lines. All subjects also completed the Frontal Assessment Battery (FAB) while those with schizophrenia were further assessed using the Positive and Negative Syndrome Scale (PANSS). Results show that the 5PT evaluation differentiates patients from healthy subjects with regard to the number of figures produced. Patients׳ results also suggest that the number of figures produced is linked to the "overall executive functioning" and to some inhibition components. Although this study is a first step in the non-verbal efficiency research field, we believe that experimental psychopathology could benefit from the investigations on non-verbal fluency.

---

### Computed tomography imaging in the context of transcatheter aortic valve implantation (TAVI) / transcatheter aortic valve replacement (TAVR): an expert consensus document of the Society of Cardiovascular Computed Tomography [^6e41ac5f]. Journal of Cardiovascular Computed Tomography (2019). High credibility.

Contouring tools for annular segmentation — Freehand tool or Hounsfield-based contour detection yields a "Non-smoothened, irregular line following path of cursor or detected attenuation threshold" and can cause "Systematic overestimation of perimeter due to non-smoothened contour; Smoothing algorithms, can allow for more realistic perimeter assessment." Polygon methods use "Manual placed segmentation points connected by straight line without interpolation" and "Depending on the number of dots, this may yield a closer estimate of perimeter than freehand contouring without smoothing," whereas spline methods use "Manual placed segmentation points connected by a cubic spline interpolation – 'elastic ruler'" enabling "Accurate quantification of annular perimeter."

---

### Modeling the electrical resistivity of polymer composites with segregated structures [^06c2b58d]. Nature Communications (2019). High credibility.

Fig. 7
Voronoi tessellations (represented in red solid lines). Voronoi geometries are constructed based on center points of silica fillers (gray circles) a with a diameter of 4 μm and b with a diameter of 20 nm over the 2D model illustrated in Supplementary Fig. 10(b) and (d), respectively. A straight line connecting the center points of the two nearest silica fillers (represented in black dashed line in a) in the normal direction of a red conducting path (the side of a Voronoi tessellation) is associated with a neck in the 2D model. c Average number of CNT crosses per neck/average neck length for micro- and nano-silica composites with respect to silica contents

The total resistance of the composite system can be determined by considering two factors: the number of the current paths and the average resistivity of the paths. To be specific, a current path is formed by connecting sides of Voronoi tessellations such that it traverses the simulation domain, and the number of such paths is proportional to the amount of the current flowing across the domain. In general, the longer lengths of the tessellation sides that form the path are, the less number of contacts among CNTs are passed, indicating that the smaller number of contact resistors exist in a current path. Furthermore, the resistivity of a side in a Voronoi tessellation is inversely proportional to the number of its crossing CNTs. Since each side can be included in a traversing current path, the average of its resistivity characterizes the average total resistance. Thus, the total resistance of the composite system decreases as the number of current paths increases, while the total resistance increases as the average resistivity of the paths increase. However, the impacts of two factors on the resistance change of the composite differ depending on the condition of the composite system. For example, when the number and resistivity of the paths are small as shown in Fig. 7a, the change in the number of the current paths mainly affects the change in the total resistance. On the other hand, when the number and resistivity of the paths are large as shown in Fig. 7b, the change in the average resistivity of the paths has a predominating effect on the change in the total resistance.

---

### Cone photoreceptor definition on adaptive optics retinal imaging [^d6ba0e27]. The British Journal of Ophthalmology (2014). Low credibility.

Automated algorithm cone identification

The retinal images were processed with a customised program coded using MATLAB R2010a (MathWorks Inc, Natick, Massachusetts, USA), similar to a previously described method by Li and Roorda. The manufacturer's counting software was not used, as it could not perform the count on the sampled windows used in this study. The acquired images were converted to 8-bits and cropped to 300×300 px (∼240×240 μm) sampling window.

A low-pass filter was applied prior to the automated counting algorithm for all subjects at all eccentricities. The number of spurious peaks were reduced by transformation to frequency domain using fast Fourier transform and preprocessed with a low-pass filter before converting them back to the spatial domain (figure 3 A). The regional maxima of the photoreceptors' centres were computed using an 8-connected neighbourhood. A Delaunay triangulation with its corresponding Voronoi tessellation was calculated resulting in a set of edges linking all the maxima points. Average number of photoreceptors surrounding each cone was calculated by determining the average number of edges originating from each maximum point. The average distance of all the edges was taken as the average inter-photoreceptor distance. The photoreceptor size was approximated by measuring the area of the joint pixels surrounding each maximum, with a greyscale value greater than the average between a peak and its local baseline. The grey scale value of the local baseline is calculated as the average value of the pixels that form the edges of the Voronoi cell of a given peak (figure 3 B). The equivalent diameter of a circle with the same area as the one calculated is taken as the diameter of the photoreceptor. Inter-photoreceptor distance was therefore measured by automated technique from the centre of one photoreceptor to its neighbours.

Figure 3
(A) Spatial frequency technique for processing of adaptive optics images. (B) Voronoi cell analysis for inter-photoreceptor distance approximation.

---

### What curves are parallel? The core feature of preschoolers' intuitive parallel category [^1a68bb22]. Child Development (2024). Medium credibility.

Existing evidence has revealed that humans can spontaneously categorize many geometric shapes without formal education. Children around 4years could distinguish between intersecting lines and parallel lines. Three features can be used to identify parallel lines, namely "translational congruence", "never meet", and "constant distance". This study separated them by using pairs of curves that possess only one of these features. Two experiments across 2021–2023, respectively, compared the relative priority of "translational congruence" with "constant distance", and "never meet" with "constant distance" among 3- to 5-year-old Chinese preschoolers (N total = 314, 48% female). The results showed that preschoolers consistently grouped "constant distance" curves with parallel lines. This suggests that the core feature of intuitive parallel category is "constant distance" at this age.

---

### Morphology of travel routes and the organization of cities [^ecc6c05b]. Nature Communications (2017). Medium credibility.

Fig. 1
Biasing forces found in urban morphology. Three schematic urban street arrangements share similar topological structure, but different geometric layouts resulting in varying dynamics. a A grid structure where the shortest paths between points at the same radius show no directional bias. b Repulsive forces relative to the origin (marked in blue) emerge as we break the grid symmetry by relocating the four outer points on the inner equidistant ring line. Paths lying on this ring now have the shortest paths that traverse the periphery and avoid the center. c Further perturbing the topology by increasing connectivity to the center (marked as four green lines) now leads to shortest paths that go through the center as if an attractive force is present (marked in red)

To capture whether such an effect manifests itself at the scale of the city, or is indeed neutral due to the "detuning" at smaller scales, we define a metric called the inness I. Figure 2c illustrates how a typical route between any origin–destination (OD) pair can be divided into segments that are directionally biased toward or away from the city center as measured relative to the geodesic distance s between the pair. We label points lying closer to the center than the geodesic inner points while those lying further away are outer points. For example, in the schematic shown in Fig. 2c, points located in the pink shaded area are inner points, and those on the opposite side (shaded blue) are outer points. We define an inner travel area delineated by the polygon of inner points and the geodesic line, to which we assign a positive sign. Conversely, an outer travel area is defined by the geodesic line and the collection of outer points, whose sign is negative. Having adopted this convention, I is the difference between the inner area and outer travel areas:which can be calculated using the shoelace formula for polygons (see Methods). In Fig. 2d, we show three possible idealizations of a route; one with only outer travel area (blue), one with only inner travel area (red), and one with a mixture of both outer and inner travel areas (combination of blue and red).

---

### Recommendations on the echocardiographic assessment of aortic valve stenosis: a focused update from the European association of cardiovascular imaging and the American Society of Echocardiography [^d1beadff]. Journal of the American Society of Echocardiography (2017). Medium credibility.

Aortic stenosis Doppler quantitation — Table 1 directs recording and measurement steps across data elements. For LVOT diameter, measure "Inner edge to inner edge," in "Mid-systole," "Parallel and adjacent to the aortic valve or at the site of velocity measurement," and note "Diameter is used to calculate a circular CSA*." LVOT velocity recording includes "Velocity baseline and scale adjusted to maximize size of velocity curve" and a "Time axis (sweep speed) 50–100 mm/s," while measurement uses "Maximum velocity from peak of dense velocity curve" and "VTI traced from modal velocity." For AS jet velocity, use "CW Doppler (dedicated transducer)" with "Multiple acoustic windows (e.g. apical, suprasternal, right parasternal)" and "Report window where maximum velocity obtained"; measurement specifies "Maximum velocity at peak of dense velocity curve," "Avoid noise and fine linear signals," "VTI traced from outer edge of dense signal," and "Mean gradient calculated from traced velocity curve." Valve anatomy recording uses "Parasternal long- and short-axis views" and "Zoom mode," and measurement includes "Identify number of cusps in systole, raphe if present," "Assess cusp mobility and commissural fusion," and "Assess valve calcification."

---

### Echocardiographic assessment of valve stenosis: EAE / ASE recommendations for clinical practice [^6285f7b1]. Journal of the American Society of Echocardiography (2009). Medium credibility.

Mitral stenosis quantitation (Table 7) — standardized echocardiographic acquisition and measurements are outlined as follows: For planimetry, use "2D parasternal short-axis view" to "determine the smallest orifice by scanning from apex to base," then measure the "contour of the inner mitral orifice," "include commissures when opened," perform measurement "in mid-diastole (use cine-loop)," and "average measurements if atrial fibrillation." For mitral flow, record "continuous-wave Doppler" from "apical windows often suitable (optimize intercept angle)" with settings to "obtain well-defined flow contour," and measure "mean gradient from the traced contour of the diastolic mitral flow" and "pressure half-time from the descending slope of the E-wave (mid-diastole slope if not linear)," with "average measurements if atrial fibrillation." For systolic pulmonary artery pressure, use "continuous-wave Doppler" with "multiple acoustic windows to optimize intercept angle" and measure the "maximum velocity of tricuspid regurgitant flow" with "estimation of right atrial pressure according to inferior vena cava diameter." For valve anatomy, acquire "parasternal short-axis view," "parasternal long-axis view," and "apical two-chamber view," then assess "valve thickness (maximum and heterogeneity)," "commissural fusion," "extension and location of localized bright zones (fibrous nodules or calcification)," "valve pliability" and the "subvalvular apparatus (chordal thickening, fusion, or shortening)," and "Detail each component and summarize in a score."

---

### Quantitative imaging metrics for the assessment of pulmonary pathophysiology: an official American Thoracic Society and Fleischner society joint workshop report [^6517cbfd]. Annals of the American Thoracic Society (2023). High credibility.

Basic stereological measurements — first-order parameters and probes identify that "First-order parameters are volume (three-dimensional [3D]), surface (two-dimensional [2D]), length (one-dimensional [1D]), and number (zero-dimensional [0D])." Measurements "are performed using geometric test probes, such as points (0D), lines (1D), planes (2D), or volumes (3D)." These probes create countable events in the image, and "Raw counts provide ratios… that are multiplied by the reference space volume to obtain absolute measures for the lung or subcompartment."

---

### Realization and topological properties of third-order exceptional lines embedded in exceptional surfaces [^d357310a]. Nature Communications (2023). High credibility.

As the counterpart of Hermitian nodal structures, the geometry formed by exceptional points (EPs), such as exceptional lines (ELs), entails intriguing spectral topology. We report the experimental realization of order-3 exceptional lines (EL3) that are entirely embedded in order-2 exceptional surfaces (ES2) in a three-dimensional periodic synthetic momentum space. The EL3 and the concomitant ES2, together with the topology of the underlying space, prohibit the evaluation of their topology in the eigenvalue manifold by prevailing topological characterization methods. We use a winding number associated with the resultants of the Hamiltonian. This resultant winding number can be chosen to detect only the EL3 but ignores the ES2, allowing the diagnosis of the topological currents carried by the EL3, which enables the prediction of their evolution under perturbations. We further reveal the connection between the intersection multiplicity of the resultants and the winding of the resultant field around the EPs and generalize the approach for detecting and topologically characterizing higher-order EPs. Our work exemplifies the unprecedented topology of higher-order exceptional geometries and may inspire new non-Hermitian topological applications.

---

### How accurate are subjective judgements of a continuum? [^7ae4189a]. Histopathology (2003). Low credibility.

Aims

To assess the accuracy of subjective judgements of a uni-dimensional continuum.

Methods and Results

Twenty-four observers were asked to estimate the position of a dot placed between two lines using a 100-point scale. Each observer judged 20 different positions. Ninety-five percent of observations were between -7 and +9 of the true value. The median and the mean value of the estimates for each position were within one or two points of the true value in most cases with a maximum deviation of five. There was perfect correlation between the ranks of the median and the mean and the true value (correlation coefficient +1, P < 0.00001). The kappa values for interobserver agreement varied from 0.98 for two categories to 0.55 for 10 categories and 0.39 for 20 categories. Information transmitted increased from 0.98 bits with two categories to 2.83 bits with 20 categories.

Conclusions

The experiment indicates that subjective judgements can be accurate but it is necessary to use a large number of categories. One hundred-point scales allow confidence intervals to be calculated and the intervals are reduced if the results from several observers are pooled. The mean and the median of the judgements of a large number of observers are close to objective reality and this approach could be used to define a gold standard of rankings of pathological continua such as cervical dyskaryosis or tumour differentiation. There is a reciprocal relationship between kappa values and information transmitted which demonstrates the fallacy of using kappa statistics in studies of continua.

---

### Neochords: how long, how many, too many? [^3d0e916a]. JTCVS Techniques (2023). Medium credibility.

Our final comment on location relates to the concept of avoiding the implantation of neochordae that would cross the midline or equator of the mitral valve. If the en face mitral valve is divided into 4 quadrants, the midline is defined as a vertical line extending from the center of the A2 segment on the anterior annulus to the center of P2 on the posterior annulus, and the equator is a horizontal line extending from the nadir between the anterior and posterior heads of each papillary muscle (Figure 2). Although we are actively studying the effect of neochordae crossing the midline and equator, our current practice is to use the posterior heads of each papillary muscle for neochordae to the posterior leaflet and the anterior papillary heads for anterior leaflet neochordae. Similarly, neochordae to A3 or P3 should be fixed to the posteromedial papillary muscle and A1 or P1 to the anterolateral papillary muscle.

Figure 2
The midline of the mitral valve is defined by a vertical line extending between the anterior and posterior annulus in the center of A2 and P2. The equator is defined as a horizontal line extending between the nadir of the anterior and posterior heads of the anterolateral and posteromedial papillary muscles.

---

### Topological acoustic triple point [^53f31fe1]. Nature Communications (2021). High credibility.

Vorticity and nodal lines

We can define the vorticity of a Dirac point when the Hamiltonian has thesymmetry. The effective Hamiltonian around a Dirac point can be written as a 2 × 2 real-symmetric matrix. The vorticity is defined as the winding number ofaround the Dirac point. Although the vorticity can easily be defined locally around the Dirac point, its global definition is nontrivial. A careful analysisshows that a two-band insulator with Euler numberhas even number of Dirac points such that the total sum of their vorticity N t satisfies the relation.

This can be directly applied to the TATP: because the Euler number for the transverse acoustic phonons is 2, there must be a minimum of four Dirac points on a sphere surrounding the ATP, such that the total sum of their vorticity is. As we change the radius of this sphere, the trajectories of the Dirac points form nodal lines, so that there must be a minimum of four nodal lines emanating from the TATP. Because two nodal lines emanating from the TATP can smoothly be connected, there must be a minimum of two nodal lines passing through the TATP (i.e. a nodal line emanating from the TATP is one half of a full nodal line passing through the TATP).

---

### 3D-FVS: construction and application of three-dimensional fundus vascular structure model based on single image features [^844c2c47]. Eye (2023). Medium credibility.

Vascular structure surface model

Considering the optic disc was one of the widest research areas in ophthalmic related diseases, our method only studied on it and these areas were labelled by a professional doctor firstly. In this stage, the methods used to build vascular structure surface models were the same as which was implemented in SimVascular, a software used to construct hemodynamic model in the following steps. Firstly, this method required to extract the centreline and downsample the points on it. Then the radius of cross-section corresponding to the point will be calculated and circles with these points as the centre will be drawn. Finally, these contours will be connected smoothly to form the vascular structure surface model.

This study utilized the Zhang-Suen thinning algorithm to skeletonize the segmented fundus vascular images. Each iteration step of this algorithm was to corrode the target pixels satisfying certain conditions. This algorithm was iteratively executed until no new pixels were corroded. The output of this skeletonization step was illustrated in Supplementary Fig. 1a. Then all the points on the skeleton line will be traversed for finding the coordinates of the endpoints and intersections of the skeleton line, as shown in Supplementary Fig. 1b, by calculating the number of points near the point with the size of 3 × 3 area. When the points on the skeleton line were too dense, it will lead to the intersection between the corresponding contours of every two points (which was shown in Fig. 2j), and the blood vessel modelling process cannot be completed at this time. Therefore, downsample was used to prevent intersections between the corresponding contours of every two feature points by removing points in a fixed number of intervals.

---

### Echocardiographic assessment of valve stenosis: EAE / ASE recommendations for clinical practice [^2c2713d4]. Journal of the American Society of Echocardiography (2009). Medium credibility.

Aortic stenosis quantitation — table-based acquisition and measurement standards specify LVOT diameter recording in 2D parasternal long-axis view using zoom with gain optimized to the blood–tissue interface, measured inner edge to inner edge in mid-systole, parallel and adjacent to the aortic valve or at the site of velocity measurement, with diameter used to calculate a circular CSA; LVOT velocity recording uses pulsed-wave Doppler from apical long axis or five-chamber view with sample volume just on the LV side, velocity baseline/scale maximized, time axis (sweep speed) 100 mm/s, low wall filter, and a smooth, well-defined peak, measured as maximum velocity from the peak of the dense curve with VTI traced from modal velocity; AS jet velocity recording uses CW Doppler with multiple acoustic windows, decreased gains/increased wall filter with baseline and scale adjustments, gray scale spectral display with expanded time scale, and range/baseline set so the signal fits but fills the vertical scale, measured as maximum velocity at the peak of the dense signal while avoiding noise and fine linear signals, with VTI traced from the outer edge, mean gradient calculated from the traced curve, and the window of maximum velocity reported; valve anatomy is recorded in parasternal long- and short-axis views with zoom, and measurements identify the number of cusps in systole (raphe if present), assess cusp mobility and commissural fusion, and assess valve calcification.

---

### Nonverbal executive function is mediated by language: a study of deaf and hearing children [^05063595]. Child Development (2017). Low credibility.

Executive Function

Odd one out span (Henry, 2001) is a measure of executive‐loaded visuospatial working memory in which the child has to process which shape is the odd one out while storing the location of each odd shape in a grid. At the end of each trial of items, the child must recall the locations of the odd shapes in correct sequence by pointing to the correct box on a series of empty grids. Trials gradually increase in number to a maximum of six locations to recall. After two errors within a block, the test is terminated. The total number of trials with locations correctly recalled is then calculated.

In the backward spatial span task (Wechsler Nonverbal Scale of Ability, Wechsler & Naglieri, 2006), children are instructed to tap blocks in a sequence reversed from one shown by the experimenter. Trials gradually increase ranging up to a span of nine. After two errors at the same span length, the test is terminated and one point awarded for each correct sequence to give a score. This is also a test of executive‐loaded visuospatial working memory.

For design fluency (NEPSY, Korkman, Kirk, & Kemp, 1998), children are given a sheet of paper showing boxes containing dot arrays and instructed to produce as many different designs as possible, in 1 min, by joining two or more dots with a straight line. The assessment measures visuospatial cognitive fluency. A score is calculated from the total number of unique designs created.

Children's Color Trails Test 1 and 2 (Llorente, Williams, Satz, & D'Elia, 2003) is a test of cognitive shifting. In Test 1, children are required to draw a line connecting each numbered circle (from 1 to 15) as quickly as possible. All odd numbers are printed in a yellow circle and even numbers are printed in a pink circle. Test 2 contains two sets of encircled numbers: One set printed in a pink background and another printed in a yellow background. The child is instructed to connect numbers in ascending order, alternating between pink and yellow circles. In the present study, an interference score was calculated to give "additional time" taken in the second condition.

---

### Realization and topological properties of third-order exceptional lines embedded in exceptional surfaces [^51c380af]. Nature Communications (2023). High credibility.

Here, we report the experimental realization of EL3 entirely embedded on ES2. The EL3 (ES2) is formed by order-3 (order-2) defective EPs. Both the EL3 and ES2 run continuously through the entire 3D parameter space, which is homeomorphic to a 3-torus by design. Such geometry presents an unexpected difficulty for topological characterization. The prevailing methods that extract topological properties of nodal degeneracies are based on the principle of homotopy group. Under such an approach, topological invariants are evaluated either on a 2-sphere enclosing the entire nodal structure, with the topological charges of a Weyl point being an important case; or on a 1-sphere encircling the nodal structure, such as the characterization of topological nodal lines. and order-2 EP lines. However, any enclosing sphere of a single EL3 would encounter ill-behaved spectral singularity on the ES2, thus defying the continuous requirement for spectral winding. In a recent study, it is theoretically shown that the resultants of the Hamiltonian matrix can be viewed as auxiliary manifolds associated with but different from the eigenvalue manifolds. Here, based on the intersection multiplicity of the resultants determining the location of EPs, we further uncover that a "resultant vector field" can be uniquely chosen to vanish only at the EL3 and remain continuous at the ES2, leading to a resultant winding number for diagnosing the topology of the EL3 while ignoring the influence of the ES2. The validity of our approach is verified by successfully predicting the local evolution of a touching point (TP) of two EL3 under perturbation. Our study expands the understanding of non-Hermitian topology by unveiling novel topological scenarios exclusive to higher-order EP structures.

---

### A deep-learning-based framework for identifying and localizing multiple abnormalities and assessing cardiomegaly in chest X-ray [^f4942464]. Nature Communications (2024). High credibility.

The CTR can be calculated using the convention of measuring the thoracic diameter (L) as the distance from the inner margin of the ribs at the level of the dome of the right hemidiaphragm and the cardiac diameter (L 1 + L 2) as the horizontal distance between the rightmost and leftmost margins of the cardiac shadow. In our study, the calculation of the CTR was based on the segmentation of both lungs and the heart in CXRs. In particular, we employed attention UNet to develop the deep model for the segmentation of both lungs and the heart, where the input image size was 512 × 512, the number of epochs was set to 100 and the batch size was set to 4. The initial learning rate was 0.00001; when the loss of the validation set increased for two consecutive epochs, the learning rate was reduced by half. Once the binary mask of both lungs and the heart was obtained, the thoracic diameter (L) and the cardiac diameter (L 1 + L 2) could be calculated by the proposed algorithm, where the process for doing so is described as follows.

Step 1: The closed morphology operation was applied to the mask to eliminate holes and burrs.

Step 2: By using the connected area labelling approach, the two largest connected areas of the lung and the largest connected area of the heart were preserved in the mask.

Step 3: The Canny operator was applied to the mask to obtain the single-pixel boundary between the lung and the heart.

Step 4: Traversing upwards from the lowest point of the right lung boundary using a number of horizontal lines, at least two intersections were encountered between each horizontal line and the boundary. The first two intersections were determined from left to right, and the distance between these two intersections was calculated. As the upwards traversal process proceeded, a number of difference values between two adjacent distances could be obtained. Note that the horizontal line that determined the maximum difference value can be regarded as a tangent line passing through the right diaphragm.

---

### Exact, time-dependent analytical equations for spiral trajectories and matching gradient and density-correction waveforms [^ced202c6]. Magnetic Resonance in Medicine (2026). Medium credibility.

2.4 Inner arc

To define the spiral trajectory for r <, a quarter‐circle k‐space arc of radiusis used to connect the center of k‐space to the circle involute described above, as illustrated in Figure 1A–C in blue. This inner arc, which itself has a fixed radius of curvature R C = , is designed to meet the WHIRL trajectory at a k‐space radius of r = , and = 1. Knowing the relevant variables for the WHIRL trajectory at this point allows one to create an appropriate gradient waveform that matches the gradient, slew, and k‐space waveforms smoothly between the arc and the WHIRL trajectory. There are many gradient solutions to achieve this inner‐arc trajectory; for this work the arc is defined in three stages played sequentially, From Equation (10), G is the integral of, is defined to maintain the circular trajectory on the arc, and the variables C, t are local to the stage, and TA and TB are chosen to smoothly match the WHIRL trajectory at the point of intersection, including all the parameters shown in the gray inset of Figure 1A. This smooth inner arc trajectory mitigates gradient and slew rate performance requirements near the k‐space center to increase trajectory fidelity; however, the total duration of this arc is typically a few hundred μs.

2.5 Outer arc

We have extended the previous WHIRLED PEAS to include a quarter‐circle k‐space arc at the outer edge of the involute as well, such that the trajectory ends in a purely angular direction (= 0), as seen in red in Figure 1A–C. This outer arc with a radius of curvaturejoins smoothly with the outer edge of the involute and allows mirror images of the trajectory to be pieced together for seamless spiral out/spiral in acquisitions with no additional trajectory calculations. The addition of this outer arc increases the required readout timeby a few microseconds and decreases the total gradient time by a few microseconds due to a slight reduction in required refocusing areas; neither change is substantial.

---

### The effect of pelvic incidence on outcomes after hip arthroscopy for femoroacetabular impingement and acetabular labral tears [^2292690b]. The American Journal of Sports Medicine (2024). Medium credibility.

FAI and Spinopelvic Imaging Parameters

Standing anteroposterior and Dunn lateral radiographs were used to obtain alpha angle, lateral center-edge angle, limb-length discrepancy, Tönnis grade, and acetabular inclination. Additionally, while PI is traditionally extrapolated from standing lateral radiographs, recent studies have shown conventional supine, advanced imaging modalities (ie, MRI and CT) to be more reliable assessments of sagittal parameters. As such, the present study employed previously validated methodologies to obtain spinopelvic measurements exclusively from available MRI or CT scans.,

Specifically, using separate sagittal cuts, the center points of circles outlining the bilateral femoral heads were identified and a line was subsequently drawn to connect these center points. The midpoint of this line (ie, center of the bicoxofemoral axis) was marked on a sagittal cut that incorporated the center of the sacral endplate. PI was then derived as the angle produced by a perpendicular line from the midpoint of the sacral endplate (S1) to the center of the bicoxofemoral axis.PT was calculated as the angle between the line connecting the center of the bicoxofemoral axis to the center of the sacral endplate and the vertical axis. Next, SS was measured as the angle between a line drawn along the superior border of the sacral endplate and the horizontal axis (Figure 1). As previously described, by integrating multiple views (ie, coronal, sagittal, and axial cuts) to determine the level of maximum congruence between the femoral heads/acetabulum at the 3-o'clock position, acetabular version was derived from the angle formed by a line that passed through the anterior and posterior bony edges of the acetabular rim and a line perpendicular to an interischial line that connects both posterior margins of the ischium. Intermeasurement reliability analyses were performed on available study patients with both MRI and CT imaging to assess the cross-modality reliability for measurements of PI, PT, and SS. On the basis of the renewed Roussouly sagittal profile classification, patients were stratified into low-PI (< 45°), moderate-PI (45° ≤ PI ≤ 60°), and high-PI (> 60°) cohorts.

---

### Bone cancer, version 2.2025, NCCN clinical practice guidelines in oncology [^0075abab]. Journal of the National Comprehensive Cancer Network (2025). High credibility.

Regarding diagnostic procedures for chordoma - NCCN, more specifically with respect to biopsy, NCCN 2025 guidelines recommend to ensure appropriate communication between the surgeon, musculoskeletal or interventional radiologist, and bone pathologist.

---

### Theory of branching morphogenesis by local interactions and global guidance [^34973bae]. Nature Communications (2021). High credibility.

Comparison between analytical model and simulations

Importantly, Eq. (1) describing the probability of branch orientation attains a steady-state solution (∂ t P st (ψ, t) = 0) that is largely independent of the form of the external field, i.e. it applies generically to different geometries after defining the relative branch alignment with respect to the external field. This solution predicts that the alignment of angles with respect to the polarity of the external field will be determined by the von Mises distribution (circular normal distribution):with a concentration parameter given by ν ≡ μ f c / D, and I 0 (ν) is the modified Bessel function of the first kind of order zero. The fluctuations in the angular alignment as determined by the variance will thus follow a universal scaling approximately given by σ 2 ∝ D / μ f c that underlines the relative contribution of the local noise to the external guidance. For an axial (linear) field parallel to the horizontal axis, for instance, the above solution applies to the distribution of the local angles φ of the branch segments (Fig. 1 d). In a radial external field emerging from a central point of origin, however, the alignment of a branch is determined by the angle difference ψ ≡ φ − θ between its local angle φ and its angle θ with respect to the origin of the external field, and thus ψ, rather than φ, is predicted to follow the von Mises distribution (see Supplementary Figs. 4–9 for the alignment angles for different model assumptions). Comparing these analytical criteria with the numerical simulations led to excellent agreement without using any fit parameter (Fig. 1 d–f).

To summarize, the combination of analytical modelling and numerical simulations allows us to make a number of predictions for different topological and geometrical properties of branched structures: A key signature of external guidance is that branching angles should conform to a von Mises distribution while the overall branching structure in an axial field can adopt a well-defined conical domain in the absence of defined boundaries. Furthermore, a signature of the stochastic nature of branching and annihilating random walks is that even with external guidance, the local branch length or overall network size and shape should be highly variable to random branching events and local density-driven termination of tip growth.

---

### Novel flight style and light wings boost flight performance of tiny beetles [^4b3201a5]. Nature (2022). Excellent credibility.

Average wingbeat frequency was calculated as the mean of the wingbeat frequency in all recordings. In each recording, the number of frames was counted in several complete kinematic cycles, 104 cycles in total.

For the mathematical description of the kinematics of the wings and elytra, we used the Euler angles system, (Fig. 2b) based on frame-by-frame reconstruction of the location of the insect's body parts (wings, elytra and body itself) performed in Autodesk 3Ds Max. Three-dimensional models of the body and elytra were obtained by confocal microscope image stacking, and the flat wing model was based on light microscopy photos of dissected wings. We used the rigid flat wing model for reconstruction of the kinematics because the deformations of the wings are minor (Supplementary Information). First, we prepared frame sequences with four full kinematical cycles in each. The frames were then centred and cropped by point between the bases of the wings and then placed as orthogonal projections. Virtual models of body parts were placed into a coordinate system with two image planes. Then we manually changed the position and rotated body parts until their orthogonal projections were superimposed on the image planes. For calculating the Euler angles, a coordinate system was created (Fig. 2a). The X0Y plane is a plane parallel to the stroke plane, and intersecting with the base of wing or elytron, which is positioned in the zero point. To determine the position of the stroke plane, we calculated the major axis trend line of the wingtip coordinates instead of the linear trend line, because the wingtip trajectory of P. placentis forms a wide scatter plot. Stroke deviation angle (θ) and positional angle (φ) were calculated from the coordinates of the base and apex. Pitch angle (ψ) is the angle between the stroke plane and the chord perpendicular to the line between the base and apex. The body pitch angle (χ) is the angle between the stroke plane and longitudinal axis of the body, calculated as the line between the tip of the abdomen and the midpoint between the apical antennomeres. Pitch angle (β) of the stroke plane relative to the horizon was also measured.

---

### Diffusion sampling schemes: a generalized methodology with nongeometric criteria [^59d3d131]. Magnetic Resonance in Medicine (2023). Medium credibility.

Purpose

The aim of this paper is to show that geometrical criteria for designing multishell < mml:math xmlns:mml = "http://www.w3.org/1998/Math/MathML" > < mml:semantics > < mml:mrow > < mml:mi > q < /mml:mi > < /mml:mrow > < mml:annotation > $$ q $$ < /mml:annotation > < /mml:semantics > < /mml:math > -space sampling procedures do not necessarily translate into reconstruction matrices with high figures of merit commonly used in the compressed sensing theory. In addition, we show that a well-known method for visiting k-space in radial three-dimensional acquisitions, namely, the Spiral Phyllotaxis, is a competitive initialization for the optimization of our nonconvex objective function.

Theory and Methods

We propose the gradient design method WISH (WeIghting SHells) which uses an objective function that accounts for weighted distances between gradients within M-tuples of consecutive shells, with < mml:math xmlns:mml = "http://www.w3.org/1998/Math/MathML" > < mml:semantics > < mml:mrow > < mml:mi > M < /mml:mi > < /mml:mrow > < mml:annotation > $$ M $$ < /mml:annotation > < /mml:semantics > < /mml:math > ranging between 1 and the maximum number of shells < mml:math xmlns:mml = "http://www.w3.org/1998/Math/MathML" > < mml:semantics > < mml:mrow > < mml:mi > S < /mml:mi > < /mml:mrow > < mml:annotation > $$ S $$ < /mml:annotation > < /mml:semantics > < /mml:math >. All the < mml:math xmlns:mml = "http://www.w3.org/1998/Math/MathML" > < mml:semantics > < mml:mrow > < mml:mi > M < /mml:mi > < /mml:mrow > < mml:annotation > $$ M $$ < /mml:annotation > < /mml:semantics > < /mml:math > -tuples share the same weight < mml:math xmlns:mml = "http://www.w3.org/1998/Math/MathML" > < mml:semantics > < mml:mrow > < mml:msub > < mml:mrow > < mml:mi > ω < /mml:mi > < /mml:mrow > < mml:mrow > < mml:mi > M < /mml:mi > < /mml:mrow > < /mml:msub > < /mml:mrow > < mml:annotation > $$ {\omega}_M $$ < /mml:annotation > < /mml:semantics > < /mml:math >. The objective function is optimized for a sample of these weights, using Spiral Phyllotaxis as initialization. State-of-the-art General Electrostatic Energy Minimization (GEEM) and Spherical Codes (SC) were used for comparison. For the three methods, reconstruction matrices of the attenuation signal using MAP-MRI were tested using figures of merit borrowed from the Compressed Sensing theory (namely, Restricted Isometry Property -RIP- and Coherence); we also tested the gradient design using a geometric criterion based on Voronoi cells.

Results

For RIP and Coherence, WISH got better results in at least one combination of weights, whilst the criterion based on Voronoi cells showed an unrelated pattern.

Conclusion

The versatility provided by WISH is supported by better results. Optimization in the weight parameter space is likely to provide additional improvements. For a practical design with an intermediate number of gradients, our results recommend to carry out the methodology here used to determine the appropriate gradient table.

---

### 2020 focused update of the 2017 ACC expert consensus decision pathway on the management of mitral Regurgitation: a report of the American college of cardiology solution set oversight committee [^10ea950e]. Journal of the American College of Cardiology (2020). High credibility.

Figure 6 — Underestimation of effective regurgitant orifice area (EROA) by two-dimensional proximal isovelocity surface area (2D PISA) in secondary mitral regurgitation (MR) is illustrated by a 2D PISA-calculated EROA of 0.17 cm^2 with regurgitant volume (Rvol) 22 mL, whereas proper continuous wave jet tracing yields EROA 0.21 cm^2 and Rvol 25 mL, and three-dimensional (3D) vena contracta reconstruction shows a vena contracta-derived area of 0.52 cm^2 with Rvol 64 mL (0.5 cm^2 × 128 cm); the discrepancy reflects the crescent-shaped MR jet that violates the circular orifice assumption of 2D PISA.

---

### Real-time trajectory guide tracking for intraoperative MRI-guided neurosurgery [^9672911e]. Magnetic Resonance in Medicine (2023). Medium credibility.

2 METHODS

2.1 Computational approach to real‐time device tracking

The current trajectory of the guide can be tracked by obtaining two points along the central axis of the guide's cylindrical alignment stem. Exploiting the sparse object space, such points are readily computed by processing radial acquisitions from a plane intersecting the stem, as shown in Figure 1D–F. In practice, rather than perform 1D correlations in the image domain, each readout in the frequency domain is multiplied with the precomputed Fourier transform of the theoretical stem projection. That product is zero padded and inverse Fourier transformed to yield the interpolated correlation input to the peak finder. Multiple radial readouts are acquired with pulse repetition time on the order of 10–12 ms. Thus, by using 10–20 radial readouts, the system computes a new stem‐plane intersection point every 100–200 ms. This process of computing the stem‐plane intersection point is performed in two different offset planes, as shown in Figure 2C, to obtain a line representative of the current trajectory.

FIGURE 2
Computation of a refined pivot point. Manually selected pivot points are inherently imprecise, and error in the pivot point results in magnified error at target depth, as illustrated on preoperative MRI (A). For the dorsal amygdala target, (red dot) extrapolating out along dotted line through an incorrectly chosen pivot (yellow ✖) will result in an incorrect aim point (green ✖). The interventional device will pass through the true physical pivot point (yellow dot). If aligned with the aim point that is based on an incorrect pivot, it will follow the dashed line trajectory, placing the tip at an incorrect target (red ✖). (B) Illustration of operator's view of acquisition plane, showing aim point (green) and a progression (dashed arrows) of five stem‐plane intersection points (blue dots) as the ball joint is reoriented. (C) Computing stem‐plane intersection points (blue dots) at two positions along the stem's length yields a line (blue arrow) representing the current trajectory. (D) The distinct trajectory guide orientations are recorded, and since all trajectories are physically constrained to pass through the pivot point (the center of the trajectory guide's ball joint), computing the intersection of those three‐dimensional lines yields that pivot point (E).

---

### Anterior mitral leaflet mobility is limited by the basal stay chords [^d7acb891]. Circulation (2003). Low credibility.

Background

We hypothesize that 2 tendon-like anterior basal stay chords, which remain taut during the entire cardiac cycle, limit the motion of the anterior mitral leaflet.

Methods and Results

Sonomicrometric crystals were implanted in 6 sheep at the insertion of stay chords at anterior mitral leaflet (S1 and S2), papillary muscle tips, fibrous trigones, mitral annulus, and the tip of the anterior leaflet (AL). Distances between crystals were recorded before and after section of stay chords. During the cardiac cycle, the angle alpha between mitral annulus and AL changed by +54.2 ± 12.4 degrees; the angles between mitral annulus and S1 (beta1) changed by +25.7 ± 14.6 degrees, and between mitral annulus and S2 (beta2) by +20.4 ± 7.8 degrees. During diastole, AL twice crossed the virtual plane formed by the stay chords: during E-wave by a maximum of 6.5 mm (mean, 2.5 ± 2.2 mm) and during A-wave by a maximum of 3.2 mm (mean, 1.7 ± 0.9 mm). After section of both stay chords, total anterior mitral leaflet motion increased as follows: AL, +6.9 ± 3.4 degrees; S1, +13.1 ± 4.4 degrees; and S2, +30.9 ± 11.7 degrees (P < 0.05).

Conclusions

Although the lateral movement of anterior mitral leaflet is limited by stay chords, the midportion moves unimpaired toward the septum, like a sail, between the 2 stay chords during diastole. A diastolic left ventricular-inflow and systolic left ventricular-outflow funnel mechanism is created. Stay chord section increased lateral anterior mitral leaflet movement.

---

### Depth relationships and measures of tissue thickness in dorsal midbrain [^c9d8dce5]. Human Brain Mapping (2020). Medium credibility.

Third, for the intercollicular sulcus (ICS) of SC, we calculated the line between the peaks of left and right SC calculated as described above. The intersection point between this line with the plane‐of‐best‐fit through the CA was located, and the vertex of S 1 closest to this point, within 0.25 mm of the plane of best fit, was defined to be the center of the intercollicular sulcus. For the inferior sulcus, we repeated the same process with left and right peaks of IC.

Once we obtained the six points of interest, we measured each of their thickness values using three different metrics. For Euclidean distance, we used the distance along the surface normal from S 1 to S PAG. For level‐set physical distance, we used integrated path distance along the streamline originating from each point to the point where it intersected the PAG. For normalized distance, we linearly interpolated the w ‐distance map at the point where the streamlines of interest intersected the PAG. Lastly, we applied a Gaussian‐weighted smoothing kernel (2‐mm diameter, 1‐mm full‐width‐at‐half‐maximum [FWHM]) to each of these points to obtain estimates of the six thickness values. For each of n vertices within 1 mm of the peak or sulcus in question, its thickness value t was given a weight A according to its manifold distance d m to the center point of the kernel: whereis the standard deviation of the Gaussian function, and FWHM. The final thickness value was then calculated as the weighted sum.

---

### Deep learning-based CT radiomics for feature representation and analysis of aging characteristics of Asian bony orbit [^0bf8b467]. The Journal of Craniofacial Surgery (2021). Medium credibility.

Description Method of Connected Component Shape

In order to determine whether the area, and height, of bony orbit change with age, the characteristics of the orbit are extracted and analyzed automatically by means of connected component shape descriptor in this paper. The connected component refers to the collection region of adjacent pixels composed of the same pixel value in the image. For example, there are 2 connected domains, that is, left and right orbital regions, as shown in Figure 4 A. In addition, the relationship between orbital shape and age is analyzed by the perimeter and roundness of bony orbit. As shown in Figure 4 A, point A is the highest point of the supraorbital margin and point B is the point at which the vertical line passing through point A intersects the infraorbital margin. The true length of segment AB equals to the height of the bony orbit. Roundness C r is the degree to which a connected component is shaped close to a circle and is defined as follows:

Wherein, F is the area of the connected component and MD is the maximum distance from the center of the connected component to its boundary.

Shape Context Method

In order to further determine whether the aging characteristics of the bony orbit profile exist in the whole or local area of the orbital contour, the shape context algorithm is adopted to classify the orbit of different age groups in this paper. The shape context algorithm, treats the contours of the image as a set of points to match the point set, so that the similarity between contours is measured by the calculating similarity, and then the contours are classified and recognized.

The difference between the 2 object shapes is measured by the shape context distance which name is D SC, and the smaller D SC indicates more similarities between the 2 shapes. The 2 orbital contours with high similarity are determined to belong to the same age group.

---

### Adapting the dejour classification of trochlear dysplasia from qualitative radiograph-and CT-based assessments to quantitative MRI-based measurements [^2a2814e7]. Knee Surgery, Sports Traumatology, Arthroscopy (2025). Medium credibility.

Trochlear measurement protocol

Four readers (ED, TP, AG, CT; orthopaedic surgeons qualified, and trained in the reference centre) independently made seven measurements (rounded to the nearest whole number) for all knees, using Horos™ (Horos Project):
(1) PBCL (Figure 2) The PBCL is defined in three steps. Step 1: Select the axial MRI slice that crosses the centre of the medial condyle. Step 2: Select the sagittal MRI slice that crosses the most posterior point of the medial condyle. Step 3: Draw the PBCL in the axial slice, which passes through the subchondral bone at the posterior aspect of the medial and lateral femoral condyles.
(2) Trochlear shape (Figure 3) Scrolling from cranial to caudal, the first slice is selected in which the trochlear cartilage is visible, showing/covering at least the entire lateral facet. The trochlear shape is described according to the cartilage contour as (a) concave (trochlea with a sulcus, as well as medial and lateral facets), (b) flat (trochlea with no evident sulcus nor medial facet) or (c) convex (trochlea with no sulcus nor medial facet, and domed lateral facet).
(3) Sulcus angle (Figure 4) Scrolling from cranial to caudal, the first slice is selected where the trochlear cartilage is visible, showing the sulcus formation and the medial facet. If the trochlea is concave or flat, the sulcus angle is measured in three steps (for convex trochleae, the sulcus angle is noted as 'unmeasurable'). Step 1: the trochlear groove cartilage (TGC) point, the lateral trochlear cartilage (LTC) peak and the medial trochlear cartilage (MTC) peak are digitized. Step 2: A line (LTC–TGC) connecting points TGC and LTC and a line (TGC–MTC) connection points TGC and MTC are drawn. Step 3: The sulcus angle is measured as the angle between lines LTC–TGC and TGC–MTC.
(4) Lateral trochlear inclination (LTI) (Figure 5) Scrolling from cranial to caudal, the first slice is selected where the trochlear cartilage is visible, showing the sulcus formation and the medial facet. If the trochlea is concave or flat, the LTI is measured in four steps (for convex trochleae, the LTI is noted as 'unmeasurable'). Step 1: The TGC point and the LTC peak are digitized. Step 2: A line (LTC–TGC) connecting points TGC and LTC is drawn. Step 3: Copy and paste the PBCL and translate it anteriorly to intersect line LTC–TGC at point TGC. Step 4: The LTI is measured as the angle between lines LTC–TGC and PBCL. The angle is considered positive if LTC is anterior to the PBCL. The angle is considered negative if LTC is posterior to PBCL.
(5) Cranial trochlear orientation (CTO) (Figure 6) Scrolling from cranial to caudal, the first slice is selected in which the trochlear cartilage is visible, showing/covering at least the entire lateral facet. The CTO is measured in four steps. Step 1: The most lateral (L) and medial (M) points on the subchondral bone covered by cartilage are digitized. Step 2: A line (L–M) connecting point L and point M is drawn. Step 3: Copy and paste the PBCL and translate it anteriorly to intersect line L–M at point L. Step 4: The CTO is the angle between lines L–M and PBCL. The angle is considered positive if point M is anterior to the PBCL. The angle is considered negative if point M is posterior to the PBCL.
(6) Central trochlear bump in the axial plane (Figure 7) The axial plane central trochlear bump is selected in four steps. Step 1: In the sagittal plane, select the slice that passes through the TGC and choose the most cranial axial slice. Step 2: Copy and paste the PBCL in the most cranial axial slice and translate it until it becomes tangent to the anterior margin of the femoral cortex. Step 3: Copy and paste the translated PBCL in the axial slice that shows the TGC. Step 4: The central prominence in the axial plane is the distance from the 'translated PBCL' to point TGC.
(7) Central trochlear bump in the sagittal plane (Figure 8)

---

### Enhancing haptic continuity in virtual reality using a continuity reinforcement skeleton [^6ae7159f]. Nature Communications (2025). High credibility.

Results

One dimensional (1D) CRS device and quantification of continuity

The 1D CRS device, shown in Fig. 2a, features a design with five pixels that can be independently adjusted in height, each powered by a small linear servo. To address the loss of haptic information typically experienced between pixels, the 1D CRS device (Fig. 2a) incorporates a 0.1-mm-thick steel beam on the pixels. Each pixel point is connected to the beam using a fishing line, facilitating movement along the beam's length while managing its off-plane displacement. The choice of fishing line as a connector serves a dual purpose: it reduces interference with the haptic interface while ensuring adequate connection strength. Furthermore, the device uses the intrinsic interpolation nature of buckled beams. This is achieved by compressing the beam at its two ends, an action managed by boundary servos. These boundary servos control the total lengths of the beam in the display area to satisfy the geometric constraint (see Supplementary Movie 2 for the display effect).

Fig. 2
Quantification of continuity.

a An 1D Continuity Reinforcement Skeleton (CRS) device. b Definition of distortion in haptic displays. c Measurement of distortion of a haptic display using Digital Image Correlation (DIC) Method. d Three basic configurations of haptic displays' differentandcurves.

To assess the effect of the CRS, it is necessary to define metrics to quantify continuity, as illustrated in Fig. 2b, where a column of pixel points with a spacing ofdisplay a single-peaked sinusoidal wave with a wavelength of. The blue dashed line represents an ideal waveform, while the red solid line represents the actual shape. Two distinct types of distortion is evident when the spacing is comparable to the wavelength: shape distortion and peak position distortion. Shape distortion refers to the discrepancy between the ideal and the actual waveforms, while the peak position distortion is defined as the deviation between the ideal peak position and its actual location. To quantify these distortions, we assume the positions of ideal peaks~, in whichandrepresent the first and last possible peak positions. A mean peak position distortioncan be defined as:in whichis the actual peak position deviated from the ideal position. It should be emphasized thatis the expectation algorithm in probability, not the Young's modulus. The mean shape distortioncan be defined as:in whichis the ideal shape andis the actual shape (See Supplementary Note 2 for the expression of).

---

### Guidelines for performing a comprehensive transthoracic echocardiographic examination in adults: recommendations from the American Society of Echocardiography [^139aca36]. Journal of the American Society of Echocardiography (2019). High credibility.

Parasternal long-axis (PLAX) view — left ventricle linear measurements specify that LV wall thickness and chamber dimension are measured at end-diastole, defined as the first video frame immediately after mitral leaflet closure, and if mitral motion is not visible, end-diastole may be identified as the peak of the R wave on the electrocardiogram; papillary muscles should not be visible in the PLAX view, the electronic caliper is positioned at the interface of the compacted myocardium of the interventricular septum and a line drawn perpendicular to the long axis of the left ventricle to the inner border of the compacted myocardium of the posterior wall, the measurement should be obtained at a level just below the MV leaflet tips, the interventricular septum and LV posterior wall should be measured at the same time and level as the LV end-diastolic dimension, only the compacted tissue of the septum should be included taking care to avoid including RV trabeculation, the insertion of the moderator band, or the TV apparatus, care must be taken to avoid including the MV apparatus, the echo loop should be advanced frame by frame to aid in differentiating posterior wall from leaflets and chordae tendineae, the LV end-systolic dimension should be obtained at the smallest cavity dimension usually the frame preceding the initial early diastolic opening of the MV just distal to the MV leaflet tips, and in the presence of isolated thickening of the basal septum the measurement location is LV apex to just beyond the septal bulge making all linear measurements at this level and these measurements should remain perpendicular to the long axis of the ventricle.

---

### Geometric characteristics of bicuspid aortic valves [^0d823006]. JTCVS Techniques (2021). Medium credibility.

The following geometric parameters were measured:
A. The length of the raphe (Figure 1, A and B).
B. The absolute sinus surfaces (Figure 1, C and D) to evaluate the morphological trend of sinuses within the bicuspid asymmetry. This enabled us to determine the contribution of each sinus to the total aortic sinus surface and to assess their correlation with other parameters.
C. Relative sinus surface, which is the corresponding surface compared with a reference circle with a fixed radius and center E (Figure 1, E and F) and was given as a percentage of each sinus exceeding the reference circle. Three fixed points were placed at the level of maximum sinus dimensions (points J, G, and H). Then another series of three fixed points were placed on the created circle on the corresponding lines toward J, G, and H, respectively named I, K, and L. The distance |GK|, |HL|, and |IJ| were measured. The other 3 lines were drawn between I, K, and L and the center of the circle E (segments |IE|, |KE|, and |LE|), and the sections were measured. The left relative sinus was obtained as | HL|/HE. Similarly, the relative surfaces of the other sinuses were calculated as | GK|/GE and |IJ|/IE, for the right and noncoronary sinsues (NCS), respectively.
D. The coaptation angle α,: The angle between 2 lines drawn from nonfused commissures to the coaptation midpoint (Figure 2, A and B).
E. The angle β: The angle between 2 lines drawn from 1 nonfused commissure and the center point of the perfect circle created (Figure 2, C and D).
F. The angle γ: The angle between the raphe, and a line drawn between the commissures and the perfect midpoint (Figure 2, E and F). Angles γ 1 and γ 2 were comprised between each of the nonfused commissures and the raphe toward the coaptation midpoint.
G. Angles ε 1 and ε 2 (Figure 2, G and H): The angles between lines drawn from nonfused commissures on 1 hand and fused commissure on the other hand toward the perfect midpoint. Together with β, they were used to determine position consistency between commissures. To confirm the hypothesis of the fixed position of the commissures between the right and the left cusp, and the left and the noncoronary cusp, ε 2 should be a constant.
H. Aortic dimensions. Aortic annulus, aortic root, sinotubular junction, ascending aorta, and the aortic arch were measured. The aortic annulus was determined following the Society of Cardiovascular Computed Tomography guidelines. Figure E2 shows the method used in the case of the BAV with only 2 sinuses.

---

### Haplotype sequence collection of ABO blood group alleles by long-read sequencing reveals putative A1-diagnostic variants [^ab6b00b4]. Blood Advances (2023). Medium credibility.

Table 3.
Overview of genetic diversity among the 154 ABO haplotype sequences

Table 4.
High degree of fixed differences between ABO groups

Figure 3.
Maximum-likelihood phylogenetic tree based on the entire ABO gene locus. All ABO groups form distinct evolutionary clades with an additional split of ABO∗O.01.01 into 2 subgroups (g1 and g2). Bootstrap support is provided for main branching points. The tree was rooted with central chimpanzee sequence (not shown).

Figure 4.
Median-joining haplotype network inferred from all 154 ABO sequences. Phylogenetic network showing the evolutionary relationships among ABO haplotypes. Each circle represents a unique haplotype with the size being proportional to the number of sequences represented. Haplotype circles are colored according to the ABO allele groups; black dots represent missing intermediate haplotypes (ie, unsampled, likely ancient haplotypes). Mutational steps between haplotypes are displayed as hatch marks along the connection lines. The length of the connection lines is not scaled by phylogenetic distance.

Most of the nucleotide differences found between ABO groups were fixed, that is, SNVs for which 1 group has 1 allele and the other group the other allele (Table 4). The 2 ABO∗O.01 subgroups (ie, ABO∗O.01.01 and ABO∗O.01.02) had on average 84 nucleotide differences between 2 random sequences, of which 73 were fixed between ABO∗O.01 subgroups. This was in the same order as, for example, comparing ABO∗O.01.01 and ABO∗B, highlighting the deep divergence of the 2 ABO∗O.01 subgroups.

We also observed 4 fixed SNVs, one 1-bp and one 12-bp indel in all ABO∗A1. 01 haplotypes sequenced in this study compared with the ISBT reference sequence NG_006669.2 (LRG_792) for the ABO blood group, also an ABO∗A1.01 allele. This reference sequence is an artificially assembled ABO∗A1.01 allele on an ABO∗O.01 background. Hence, it may be possible that the observed differences are relicts to be corrected of the old ABO∗O.01 background sequence in the current ISBT reference sequence.

---

### Ultra-high dynamic range quantum measurement retaining its sensitivity [^63f3f730]. Nature Communications (2021). High credibility.

Algorithm design

To design our eventual algorithm, its principle is explored in more detail with additional simulations. Fig. 3a shows the result for changing the relative number of iterations for each area, which reveals that there is a trade-off between the lowest uncertainty reached for measurement times at the steep region and at long measurement times. In other words, depending on T meas, a different relative number of iterations gives the lowest uncertainty. When fixing these (Figs. 2a and 3a), the uncertainty is not optimised, and thus it can display very steep curves that can be tuned to even sub-Heisenberg-like scaling (for examplein Fig. 3a).

Fig. 3
Simulation analyses.

a For different relative numbers of iterations of the subsequences (written directly left of each curve) of areas A, the uncertainty σ B with respect to measurement time T meas changes. Depending on the measurement time, a different combination gives the lowest uncertainty. b Minimised uncertainty for a large-range sequence by optimally combining the subsequences (red line). The dashed lines give the uncertainty for single-area sequences (A 0 blue, A 0 /2 magenta, A 0 /4 olive, A 0 /8 grey). See Supplementary Note 1 for maximum uncertainty ∝ range. c The relative number of iterations for each area (A 0 blue crosses, A 0 /2 magenta circles, A 0 /4 olive triangles, A 0 /8 grey diamonds kept at 10 0) for each measurement time to minimise the uncertainty, which results in the red line in b. The vertical arrows indicate when a subsequence for its area turns on, since its relative number of iterations becomes significant. The green dashed line gives the relative difference between the most-sensitive small-range sequence (blue dashed line in b) compared to the optimally combined large-range sequence. This difference scales inversely with the measurement time. d When looking at the turning-on points (yellow crosses, fit with black dotted line) for many sequences with different areas (largest area blue line, smallest area red line), it scales asfor short measurement times. Please note that the optimally combined result in b scales as, since it includes relatively large areas only, equivalent to the lowest lines in this plot.

---

### Bone cancer, version 2.2025, NCCN clinical practice guidelines in oncology [^099e1105]. Journal of the National Comprehensive Cancer Network (2025). High credibility.

Regarding surgical interventions for chordoma - NCCN, more specifically with respect to surgical resection, NCCN 2025 guidelines recommend to consider achieving local tumor control by either limb-sparing excision or limb amputation, individualized for a given patient.

---

### Bone cancer, version 2.2025, NCCN clinical practice guidelines in oncology [^e61ac135]. Journal of the National Comprehensive Cancer Network (2025). High credibility.

Regarding diagnostic investigations for chordoma, more specifically with respect to imaging for staging, NCCN 2025 guidelines recommend to consider obtaining PET/CT from skull base to mid-thigh in patients with chordoma. Consider obtaining bone scan if PET/CT is negative.

---

### 2020 focused update of the 2017 ACC expert consensus decision pathway on the management of mitral Regurgitation: a report of the American college of cardiology solution set oversight committee [^097203dc]. Journal of the American College of Cardiology (2020). High credibility.

Table 5 — pathoanatomically directed techniques for secondary MR describes repair versus replacement approaches. A restrictive remodeling rigid annuloplasty ring may be used as primary modality for annular dilatation mechanism, may be used in conjunction with secondary or tertiary chordal cutting, and may be used with other adjunctive procedures (e.g., papillary muscle sling), but should be avoided as sole therapy in setting of Carpentier Type IIIB mechanism with left ventricular inferobasal aneurysm. Chord-sparing MV replacement may be used as primary modality for annular dilatation when severe leaflet tethering (i.e., > 10 mm tenting height) or presence of inferobasal aneurysm and is reasonable to consider in preference to MV repair for patients with severe ischemic MR.

---

### Network community structure of substorms using superMAG magnetometers [^9dd9b34b]. Nature Communications (2021). High credibility.

Fig. 1
The community structure of a substorm on the 16/03/1997.

The abscissa of all panels is normalized time (is onset (dashed green line) and(dashed purple line) is the time of maximum auroral bulge expansion). Vertical gray dashed lines show ten normalized minute intervals within the expansion phase. a, b Plots individual communities as circles where the size of the circle reflects the number of connections within the community. The ordinate plots the mean magnetic local time/latitude (MLT/MLAT in h/degrees) of the community, and, and the color indicates the proportion of connections with each time lag, ∣ τ c ∣. The dashed lines overplotted are the edges of the auroral bulge (MLT) and the onset location (MLAT), found from auroral images. c, d Show the spatial extent of each community, where the dots are the magnetometer locations and the shading is the extent. Color represents the mean MLT of the stations contained within each community. e Plots the modularity, Q, (blue line) and the random phase surrogate (black line). f Plots the normalized number of connections, both within the nightside (solid blue) and within the SCW (dashed blue), as well as their surrogates (solid and dashed black, respectively, both near-zero throughout). The right ordinate plots (negative) SML (red).

Figure 1 a, b visualizes the overall importance in the network, and physical location, of the network communities as a function of time, see "Methods," "Community detection and network parameters." The edge-betweenness algorithm does not pre-define how many communities there should be so the number of communities (plotted as circles) at each time is completely unconstrained and changes throughout the substorm. The network has been constructed by identifying connections using the canonical cross-correlation (CCC) lag at which the CCC between each pair of magnetometers is at its peak so that each connection has an associated lag, τ c. The magnitude of the lag ∣ τ c ∣ indicates whether connections within a given community are formed rapidly (zero CCC lag i.e. τ c = 0 (gray)) or whether they are associated with propagation and/or expansion (non-zero CCC lags from 1 to 15 min (blue-red)), see "Methods," "Calculating the direct network."

---

### Recommendations for cardiac chamber quantification by echocardiography in adults: an update from the American Society of Echocardiography and the European association of cardiovascular imaging [^194fdbe5]. Journal of the American Society of Echocardiography (2015). Medium credibility.

Left atrial (LA) volume quantification by echocardiography is described using two-dimensional echocardiography (2DE) and three-dimensional (3D) approaches, with 2D volumetric measurements based on tracings from apical four- and two-chamber views; at the mitral valve level the contour is closed by a straight line, endocardial tracing excludes the atrial appendage and pulmonary veins, LA length L is the shortest long axis from apical two- and four-chamber views, and the two lengths should not differ more than 5 mm; volumes can be computed by an area-length approximation or by a disk summation technique, and 3D data sets are usually acquired from the apical approach using a multibeat full-volume acquisition. For the 2DE area-length technique, advantages include accurate assessment of asymmetric remodeling of the left atrium and being a more robust predictor of cardiovascular events than linear or area measurements, whereas limitations include geometric assumptions about LA shape, few accumulated data on normal population, and that single plane volume calculations are inaccurate because they assume A1 = A2. For 3D data sets, advantages are no geometrical assumption about LA shape and greater accuracy compared with 2D measurements, while limitations include dependence on adequate image quality, lower temporal resolution, limited data on normal values, and that patient's cooperation is required.

---

### Context-dependent dynamics lead to the assembly of functionally distinct microbial communities [^2b520739]. Nature Communications (2020). High credibility.

Fig. 1
Microcosm communities approach distinct equilibria.

a Relative abundances of the top 20 Amplicon Sequence Variants (ASVs) across the ten microcosms during the course of the serial transfer experiment. ASVs are listed one time each on the bar plot, with taxonomic classification in the legend. The DNA concentrations for each timepoint are graphed above as points, with a Loess fit as a solid line. b Communities change quickly and then stabilize in the two-dimensional Non-metric Multidimensional Scaling (NMDS) plot of Bray–Curtis dissimilarities of the microcosm community compositions. The microcosm name is listed in black next to the Day 0 point for each microcosm, and the lines connect the timepoints. Colored numbers indicate the mean effective number of species for each community post Day 21. c The Bray–Curtis dissimilarity of ASV relative abundances between adjacent days decreases over the course of the experiment. The thick black line shows a Loess fit to all data points, and the thin line marks Day 21. d At the end of the experiment, most ASVs were present in only one microcosm (top), but ASVs present in more microcosms tended to have higher mean relative abundances (bottom), shown as black circles with ± 1 standard deviation error bars.

---

### Recommendations for cardiac chamber quantification by echocardiography in adults: an update from the American Society of Echocardiography and the European association of cardiovascular imaging [^9470949b]. Journal of the American Society of Echocardiography (2015). Medium credibility.

Echocardiographic left ventricular (LV) internal linear dimensions — Linear internal measurements of the LV "should be acquired in the parasternal long-axis view carefully obtained perpendicular to the LV long axis, and measured at the level of the mitral valve leaflet tips," and electronic calipers "should be positioned on the interface between myocardial wall and cavity and the interface between wall and pericardium." Techniques include M-mode tracing and 2D-guided linear measurements; M-mode advantages are "Reproducible," "High temporal resolution," and "Wealth of published data," with limitations "Beam orientation frequently off axis" and "Single dimension, i.e., representative only in normally shaped ventricles." For 2D-guided linear measurements, an advantage is "Facilitates orientation perpendicular to the ventricular long axis," with limitations "Lower frame rates than M-mode" and "Single dimension, i.e., representative only in normally shaped ventricles."

---

### Morphology and microcirculation changes of the optic nerve head between simple high myopia and pathologic myopia [^f1e4c4c3]. BMC Ophthalmology (2023). Medium credibility.

Parameters from Optos and SS-OCT measurements

We used the Optos to perform digital photography, and the images were exported into the Image-pro Plus (version 6.0) to measure the morphology of ONH. The size, disc-fovea distance (DFD), angle α, tilt, rotation, peripapillary atrophy (PPA) area, and PPA radian were measured from these photographs by the aforementioned retinal ophthalmologists (Fig. 1). The area of PPA (an inner crescent of the chorioretinal atrophy with the visible sclera and choroidal vessels) and ONH were expressed as the total number of pixels using the Image-Pro Plus. The angle α between retinal temporal arterial vascular arcades was measured from the centre of ONH with 250 pixels' radius. The definitions of tilt and rotation were explained before. Briefly, the tilt was quantified by the tilt index, defined as the ratio between the largest diameter (LD) and the minor diameter (SD) of ONH. ONH was considered a tilt when the tilt index was above 1.3. The rotation was defined as the angle between the long axis and the vertical meridian of ONH. The vertical meridian was defined as a vertical line that passed through the centre of ONH and at 90° from the horizontal line, which connects the fovea and the centre of ONH. The ONH was considered rotated when the rotation angle was more significant than 15°.

Fig. 1
Parameters by Optos. (A) The area of ONH was outlined manually. The tilt index was defined as the ratio between the largest diameter (LD) and ONH's minor diameter (SD). Rotation was measured between the LD and the vertical meridian identified as a vertical line 90°from the horizontal line connecting the fovea and the centre of ONH. DFD was measured between the macular central fovea to the centre of ONH; (B) The angle α: A circle (centre: the centre of ONH; radius: 250 pixels) with two intersection points with the upper and lower main temporal retinal arteries was measured for the angle formed by these two intersections and the centre of the circle; (C) The area of PPA was outlined manually; (D) PPA radian is the radian of PPA centred on the ONH.

---

### What are the sex-based differences of acetabular coverage features in hip dysplasia? [^f9c4bfb2]. Clinical Orthopaedics and Related Research (2024). Medium credibility.

Fig. 3
The variables related to innominate bone rotation have been depicted. (A) The superior iliac wing angle is determined as the point where a line connecting the inner edge of the anterior superior iliac spine and the front edge of the sacroiliac joint intersects with a horizontal line on the axial plane. (B) The inferior iliac wing angle is determined by the intersection of a line connecting the front part of the anterior inferior iliac spine and the rear part of the ilium with a horizontal line on the axial plane. (C) The ischiopubic angle is determined as an angle by the crossing of a line connecting the front upper edge of the pubic symphysis and the ischial spine, with a sagittal line on the axial plane; SIA = superior iliac wing angle; IIA = inferior iliac wing angle; IPA = ischiopubic angle.

Fig. 4
Acetabular coverage parameters have been depicted. (A) Acetabular inclination was measured within the coronal plane that passes through the center of the femoral head. Acetabular inclination is formed by a line connecting the upper and lower edges of the acetabulum and a horizontal line. (B) Superior acetabular sector angles were measured within the coronal plane that passes through the center of the femoral head. Acetabular sector angles were formed by the point where a line connecting the center of the femoral head and the edge of the acetabulum intersects with a horizontal line. (C) Acetabular anteversion was measured within the axial plane that passes through the center of the femoral head. It is determined as the angle created by the intersection of a line connecting the anterior and posterior edges of the acetabulum with a sagittal line. (D) The angles representing the anterior and posterior acetabular sector angles are determined within the axial plane that passes through the center of the femoral head. The acetabular sector angle is determined by the point where a line connecting the center of the femoral head and the edge of the acetabulum intersects with a horizontal line. (E) The measurements for the acetabular anteversion angle, anterior acetabular sector angles, and posterior acetabular sector angles were taken at intervals of 5 mm, starting 10 mm distal to the femoral head center and continuing up to 20 mm proximal to the femoral head center. (F) 3D image diagram of the posterior ASA and anterior ASA at each acetabular level; AI = acetabular inclination; ASA = acetabular sector angle; AcAV = acetabular anteversion.

---

### Cutting edge or blunt instrument: how to decide if a stepped wedge design is right for you [^471f52f2]. BMJ Quality & Safety (2021). High credibility.

When might I consider doing a stepped wedge trial?

Research designs are shaped as much by practical constraints as by abstract schemes, and it is always a good idea to start with the constraints and work towards a design, rather than start with a design and try to fit it to constraints. These constraints will be unique to each research context, and box 1 lists some areas to think about. Still, there are some common features of settings where a stepped wedge trial might be considered as a possible design, and we now review these.

Box 1
Practical constraints on the design of a longitudinal cluster randomised trial

Are there limits on the time available to complete the evaluation, on the number of clusters, or on the number of participants (or the rate at which you can recruit participants) at each cluster? These constraints put limits on the overall scale of the evaluation, or force trade-offs between different design characteristics.
How will participants and their data be sampled in your study: as a series of cross-sectional surveys, as a continuous stream of incident cases, as a cohort followed over time, or some other way? Does the timescale divide into cycles, seasons or milestones that influence how you will sample participants and data?
Is there a limit on how many clusters can implement the intervention at the same time in the evaluation? If this is constrained by research resources (eg, if there are only enough trained research staff to implement the intervention one cluster at a time) then implementation must be staggered in some way.
If implementation is to be staggered, is there a minimum 'step length'? If the same team delivers the intervention in different clusters at different steps, then bear in mind it may take some time to get the intervention fully operational at a site, and the team will also need time to relocate from one cluster to the next.

---

### Guidelines for performing a comprehensive transthoracic echocardiographic examination in adults: recommendations from the American Society of Echocardiography [^1213731c]. Journal of the American Society of Echocardiography (2019). High credibility.

Left ventricular (LV) linear measurements and related timing — make linear LV measurements in the parasternal long‑axis (PLAX) view with the chamber optimally centered and as perpendicular as possible to the long axis, take LV dimension measurements just beyond the mitral valve (MV) leaflet tips while avoiding mitral chordal and papillary muscle apparatus and right‑sided structures, move measurements slightly apical if a basal septal bulge is present, measure the left atrial anterior‑posterior diameter using M‑mode or two‑dimensional (2D) imaging with 2D preferred, and use systolic timing for left ventricular outflow tract (LVOT) and aortic annulus diameters and diastolic timing for aortic measurements; define the outflow tract diameter by the septum and anterior mitral leaflet at the location yielding laminar flow just proximal to the AV.

---

### Effective use of tables and figures in abstracts, presentations, and papers [^9d553efc]. Respiratory Care (2004). Low credibility.

In some situations, tables, graphs, and figures can present certain types of information (including complicated relationships and sequences of events) more clearly and in less space than the same information would require in sentence form. However, do not use tables, graphs, and figures for small amounts of data that could be conveyed clearly and succinctly in a sentence. Also, do not reiterate in sentences the data that are shown in a table, graph, or figure: the point of creating a table or graph or figure is to eliminate that type of sentence from your manuscript. In building a data table you must balance the necessity that the table be complete with the equally important necessity that it not be too complex. Sometimes it is helpful to break a large table into several smaller ones to allow the reader to identify important information easily, but, conversely, it is a common mistake of novice authors to split up into several tables data that belong in one table. In almost all cases, only one table or graph or figure should be included in an abstract, and then only if it can convey essential information in less space and in a more easily interpretable way than the sentence form. For a poster, in almost all instances you should use only one typeface and one font in a table, graph, or figure. In general, do not use bold, italics, or color unless you are presenting a great deal of data and you need to highlight certain data values and you are certain that using bold, italics, or color will improve readability, which is rare. Do not include identical information in a table and a graph/figure. In reporting a clinical trial you will need to include a patient flow chart that identifies the number of patients initially screened for the study, the number of patients who were excluded (and why) after initial screening or in the final analysis, and how many patients entered, exited early, and completed each arm of the study. A treatment protocol should also be described with a flow chart. In preparing a graph the most common error is to include a line that suggests an unsubstantiated extrapolation between or beyond the data points. In selecting the graph's axes, avoid truncating, enlarging, or compressing the axes in ways that might make the graph confusing or misleading. To prepare clear, accurate, easily interpretable tables, graphs, and figures, rely on the rules described in authoritative guides such as the Council of Science Editors' Scientific Style and Format and the American Medical Association's Manual of Style.

---

### Artificial web of disclination lines in nematic liquid crystals [^11e593ab]. Nature Communications (2017). Medium credibility.

Disclination lines in nematic LCs appear when the director makes a continuous π rotation along a closed loop, converting n to − n. Because of the physical equivalence of n and − n, there is no discontinuity of the LC structure except along the line singularity running somewhere inside the loop. Depending on the sense of rotation of the director along the loop, there arise two subtypes referred to as 1/2 and −1/2-strength disclinations, although they are not topologically distinct. This type of disclination lines are densely formed at the phase transition, when the isotropic liquid is suddenly cooled down to the nematic phase, because of the nucleation of numerous nematic LC domains with random director orientations. The disclination lines thus formed, however, rapidly disappear through pair annihilation and loop shrinkage for the aforementioned equivalence of 1/2 and −1/2 disclinations. The time evolution of disclination lines at the phase transition has intrigued even cosmologists as a laboratory model of the early universe, based on the mathematical equivalence of fundamental equations governing these two entirely different systems. For the past decade, there have been attempts for artificial manipulation of disclination lines by means of topologically conflicted boundaries – and by use of topological objects like colloidal inclusions. Nevertheless, their inherent readiness for annihilation has hampered the realization of condensed array of free-standing disclination lines in nematic LCs as those involving line intersectoins.

We describe here a scheme to design and fabricate a free-standing network of twist disclination lines without the aid of colloidal particles. The key ingredient is the substrates with a microscopically patterned surface alignment for LC molecules that not only nucleate twist disclination lines but also exert elastically mediated forces on the disclination lines in such a way as to stabilize intersecting disclination lines. In the next section, we present the theoretical expressions of the forces in play in this system, followed by the experimental demonstration that a free-standing web of 1/2-strength disclination lines can be stably formed in thin LC cells through a proper combination of orientationally patterned confining surfaces. According to the theoretical estimates of the forces acting between disclination lines and between the patterned surface and the disclination line, twist disclination lines are prevented from annihilation through the balance of the elastic forces over a wide range of intersecting angles. In this regard, the present disclination web can be regarded as a two-dimensional analog of the cholesteric blue phase.

---

### A selection and targeting framework of cortical locations for line-scanning fMRI [^7d5ce816]. Human Brain Mapping (2023). Medium credibility.

3 RESULTS

3.1 Anatomical measures confirm accurate line‐planning

First, we used anatomical information to assess planning accuracy. We created a binarized mask representing the nominal line by taking the middle 16 voxels (indicative of the nominal 4 mm gap between saturation pulses) in the phase encoding direction along the frequency encoding direction. Of note, due to the imperfect nature of these saturation slabs, there are contaminating signals coming from outside the region‐of‐interest (Raimondo, Knapen, et al; Raimondo, Priovoulos, et al.). Because the full registration cascade from target vertex to the line through the low‐resolution image, partial FOV image, and single slice is known, we can project the nominal line image back onto the surface (Figure 3a, b). This showed that for all subjects, the line was indeed placed on the target site as per the overlap of the line (white) and target vertex (red spot) (Figure 3c).

FIGURE 3
Assessment of line‐placement accuracy using anatomical measures. The registration cascade from target vertex (a) to line‐scanning acquisition (b; outer right panel) is known after registering the anatomical image from Session 1 (high‐res) to the anatomical image from Session 2 (low‐res). Within Session 2, we acquired a partial field‐of‐view image (partial FOV), as well as the anatomical slice without OVS pulses (slice). From this slice, we created an image representing the nominal line (line). For each subject, we projected this nominal line image back to the surface from which the target vertex originated, showing sufficient overlap between the target vertex (red dot) and nominal line image (white patches) (c). The patches represent the location at which the nominal line image intersects with GM and looks scattered due to unfolding of the cortex. (d) Variation in registration outcomes after registration anatomies from Sessions 1 and 2, a hundred times for each subject. (e) Effect of subject motion by means of manual alignment of the single slice images on positional stability of the target coordinate. (f) Curvature distributions within the gray patch intersecting with the target location of (c). The curvature is measured as 1/r, where r is the radius of an inscribed circle. Since mean curvature is the average of the two principal curvatures, it has the units of 1/mm.

---

### A critical edge number revealed for phase stabilities of two-dimensional ball-stick polygons [^9a5a5d21]. Nature Communications (2024). High credibility.

As the amorphous state is more stable than crystal at finite temperatures, we expect that, driven by entropy, the crystal state will spontaneously destabilize into the amorphous state. To check this, MD simulations starting from crystalline morphology are performed at pressureand various temperatures. As quantified by the bond-orientational order parameter(see Methods for the definition) plotted in Fig. 3b, which initially keeps a high value (larger than 0.8) corresponding to the rhombic crystal state, and then decays after certain simulation steps until a very low value due to its amorphous nature, the amorphization takes place at, lower than the melting pointmanifested by the sharp changes in the caloric and density curves plotted in Fig. 3c. The non-equilibrium amorphous state whose potential energy and density are close to those of crystal is featured by the mixing of two isotopes, as shown in the inset of Fig. 3b, in agreement with our theoretical prediction described above. At lower temperatures, the fact that amorphization does not occur within the finite simulation time should be attributed to the existence of relatively high energy barrier(s) between the crystalline and amorphous states. To verify this, we manually introduce a very small disordered region (about 30 monomers) into the crystalline configuration (see Methods for technical details) and run NPT simulations at, 2.86, and 2.88, respectively. The evolution of the two monomers in each unit-cell is traced by the unit-cell order parameter defined as, where the number of unit-cells n equals to half of the number of monomers, l (t) is the distance between the center-of-masses (COMs) of the two monomers originally in the same unit-cell at time t, = 5.77 is the cut-off value of l, andis the Heaviside step function. This order parameter quantifies the fraction of remaining unit-cells at time t, taking a value close to 1 in crystal and 0 in liquid. The time evolution of d insteps after a relaxation ofsteps is shown in Fig. 3d, demonstrating that, once the energy barrier is overcome, the system will rearrange into the amorphous state continuously. We expect that d would finally drop to approximately zero after sufficiently long time, as a result of reorganization of the whole system. Although regular MD simulations at much lower temperatures would suffer from very slow dynamics, we have managed to verify that the amorphous state is still more stable than the crystalline state even at a temperature as low as T = 1.5 by running an additional REMD simulation focusing on the low-temperature region (see Supplementary Fig. S 4 in SI). Moreover, we never observe an inverse pathway from the amorphous state back to the crystal, as appeared in the simulation for the hard-triangle system, in agreement with the fact that the amorphous state is more stable than the crystal benefiting from the large configurational entropy.

---

### SNMMI procedure standard / EANM practice guideline for amyloid PET imaging of the brain 1.0 [^e640d942]. Journal of Nuclear Medicine (2016). Medium credibility.

Amyloid PET brain imaging — positive scan interpretation and regional patterns state that in patients with significant amounts of Aβ deposition in the brain, radiotracer uptake in gray matter blurs the distinction of the gray/white junction; a key feature for distinguishing Aβ 'positive' from 'negative' patients is loss of gray/white matter contrast with uptake extending to the edge of the cortex forming a smooth, regular boundary, and a convex outer surface may be outlined while gaps between the two hemispheres may no longer be defined or may appear as a thin regular line; abnormal uptake tends to be symmetrical, with most distinct accumulation in lateral temporal and frontal lobes, posterior cingulate cortex/precuneus, and parietal lobes while the sensorimotor and visual cortex can be relatively spared; striatal uptake (notable in the caudate head) is often found and may be decisive in subjects with major cortical atrophy, and in hereditary forms of AD particularly intense striatal uptake has been described; the cerebellar cortex does not usually show uptake in the majority of amyloid-positive subjects, thus the cerebellum can generally be used as a reference region for visual as well as for semi-quantitative interpretation; an intermediate (or indeterminate) scan pattern may also be encountered and package inserts should be consulted for the number of affected cortical regions required to define a "positive" scan.

---

### Measurement of cortical thickness from MRI by minimum line integrals on soft-classified tissue [^0361785e]. Human Brain Mapping (2009). Low credibility.

Estimating the thickness of the cerebral cortex is a key step in many brain imaging studies, revealing valuable information on development or disease progression. In this work, we present a framework for measuring the cortical thickness, based on minimizing line integrals over the probability map of the gray matter in the MRI volume. We first prepare a probability map that contains the probability of each voxel belonging to the gray matter. Then, the thickness is basically defined for each voxel as the minimum line integral of the probability map on line segments centered at the point of interest. In contrast to our approach, previous methods often perform a binary-valued hard segmentation of the gray matter before measuring the cortical thickness. Because of image noise and partial volume effects, such a hard classification ignores the underlying tissue class probabilities assigned to each voxel, discarding potentially useful information. We describe our proposed method and demonstrate its performance on both artificial volumes and real 3D brain MRI data from subjects with Alzheimer's disease and healthy individuals.

---

### Recommendations for cardiac chamber quantification by echocardiography in adults: an update from the American Society of Echocardiography and the European association of cardiovascular imaging [^75098a94]. Journal of the American Society of Echocardiography (2015). Medium credibility.

Table 5 — Echocardiographic assessment of LV mass (linear method, M‑mode tracing) emphasizes acquisition and use characteristics: linear internal measurements should be obtained from the parasternal approach, perpendicular to the LV long axis at the level of the mitral valve leaflet tips; M‑mode measurements should be from a targeted short‑axis (SAX) or parasternal long‑axis (LAX) view, and all measurements should be at end‑diastole. Advantages are that the method is fast and widely used, has demonstrated prognostic value, is fairly accurate in normally shaped ventricles (e.g., systemic hypertension, aortic stenosis), and is simple for screening large populations. Limitations include frequent off‑axis beam orientation, the cubed nature of linear measurements increasing error impact, overestimation of LV mass, and inaccuracy with asymmetric hypertrophy, dilated ventricles, and diseases with regional wall‑thickness variation.

---

### Biologically encoded magnonics [^7420781c]. Nature Communications (2019). High credibility.

Spatial localization of spin-wave amplitude

Building on the knowledge that the geometric chain features have a direct influence on the magnonic structure, we next analyzed the spatial distribution of magnon amplitude to understand the microscopic origin of the angular-dependent band structure. For this purpose, we present in Fig. 4c, the spatial distribution of spin-wave amplitude exemplarily for the continuous resonance line forming the upper envelope of the FMR spectrum simulated for the curved chain. It now becomes apparent that the envelope line does not represent the anisotropy of a single chain segment, but, surprisingly, represents a standing spin wave that shifts through the chain as the magnetic field angle is changed. Thereby, the spin-wave amplitude is always localized in those chain segments that are approximately aligned with the external field, in the sense that the line is composed of easy axis resonances, as was already inferred from the majority criterion (Fig. 4a). At 150° (position V, W in Fig. 4c), the amplitude is localized in particle pair 2 and 3, then at 100° (O-Q) in pair 3 and 4, and at 60° (H-J) in the triplet 4, 5, and 6.

As a general rule, we observe that coupled systems avoid line crossings and instead exhibit band deflection at points where the resonances of decoupled systems would otherwise cross, which can be most prominently observed at O-R in Fig. 4c. This effect leads to unusual line deformations, which deviate from the symmetry of chain segments and are mediated by a spatially shifting spin-wave amplitude. On the other hand, when looking at any short enough line segment, one finds the local effective anisotropy of one or multiple particles to be represented. For example, the triplet 4, 5, 6 in Fig. 4c has a resonance line tracking its anisotropy along the path from F to M. This tracking is further illustrated in Fig. 4a, where the local effective anisotropy of individual particles becomes apparent although the lines are intersected by band gaps.

---

### Three-dimensional visualization improves the endoscopic diagnosis of superficial gastric neoplasia [^ba266de1]. BMC Gastroenterology (2021). Medium credibility.

Fig. 1
Definition of the concordance rate of lesion extent. a Endoscopic image of a gastric neoplasia using NBI. A superficial protruded-type lesion (adenoma) is evident on the lesser curve of the lower gastric body. b Delineation of the tumor margin is performed. The blue line is the tumor extent line drawn by a participant. c According to the histopathological findings, the tumor extent (red lines) is reconstructed on an endoscopic image. The white lines are the cutting lines of a resected specimen. d The calculation of the concordance rate of lesion extent. Yellow circles and yellow cross marks show coincident and non-coincident evaluating points, respectively. In this case, 16 of the 18 evaluation points were coincident, indicating a coincident rate of lesion extent of 88.9% (16/18)

Fig. 2
Definition of the evaluation points for outside the lesion. a If the drawn line passes through the cutting lines outside the actual tumor margin, the intersections are evaluated as incorrect points. The black line shows the drawn line and dotted lines show the cutting lines. The yellow circles and yellow cross marks show the correct and incorrect evaluation points, respectively. b If the drawn line passes inside the tumor margin, the evaluation points that the drawn line do not pass through on the lesion border are evaluated as incorrect points

Twelve study participants were blinded to the endoscopic findings and histopathological diagnoses of the enrolled superficial gastric neoplasias. These participants were 4 novices (young physicians with no endoscopic practice), 4 trainees (physicians with experience performing ESD in 30–300 cases) and 4 experts (endoscopists with experience performing ESD in over 300 cases and Board-certified Fellows of the Japan Gastroenterological Endoscopy Society). A crossover design for evaluating the 2D and 3D images was used to reduce bias.

---

### Unveiling magmatic structures and connectivity beneath the lunar oceanus procellarum region from GRAIL gravity data [^a042ed9e]. Nature Communications (2024). High credibility.

a – c Horizontal slices at depths of 3.5, 5.5, and 10 km. d – g Vertical depth slices. The locations of the vertical depth slices are indicated by black dotted lines in (a)–(c). The blue dashed lines in (a)–(i) correlate with the 160 kg/m 3 density contrast contour line, which is taken to be the magmatic body surface. The vertical axis is exaggerated by a factor of 10 relative to the horizontal axis. The symbols "I, II, III, IV, V" in (a)–(c) represent distinct magma chamber compartments.

Figures 2 c, 3 c, 4, and 5 exhibit distinct belt structures oriented NNW–SSE with density contrasts ranging from 160 to ~700 kg/m 3. These belt structures correspond to the belt gravity anomalies depicted in Figs. 2 b and 3b and match the PKT border magmatic intrusions as identified in a previous study. We observe that the density contrast of the intrusions from the inversion gradually decreases from the center to the edges. This is mainly due to the smoothing nature of the inversion method used; the actual density contrast variation within the intrusions may not be as pronounced. The density model for area A (Figs. 2 c and 4) shows that the border intrusion spans from near the surface down to depths of 10–13 km with a length of ~800 km, a thickness of 8–11 km, and a width of 130–270 km. In study area B, the western branch intrusion is ~600 km in length, ~140 km in width, and ~8–10 km in thickness, and the middle branch intrusion is about 550 km long, 80 km wide, with a thickness ranging from 5 to 9 km. The western PKT border intrusions become thinner and narrower, and the depth of the top surface increases toward the north.

---

### Impact and characterization of serial structural variations across humans and great apes [^7fb5239f]. Nature Communications (2024). High credibility.

Noise-reduction in pairwise alignments for subsequent segmentation

Pairwise alignments are retrieved from minimap2 in. paf format, in which each alignment can be interpreted as a four-dimensional vector from start (query-start/target-start) to end (query-end/target-end) coordinates. To prepare subsequent compression steps, alignments are pre-processed in multiple ways: First, alignments are filtered by a minimum length threshold (l), removing very short alignments. Second, alignment breakpoint coordinates are rounded in x and y direction to the closest multiple of a rounding parameter (r). Finally, alignment vectors are shortened along the x or y axis in case they do not have a slope of exactly 1 or -1 until they do so. The choice of r and l directly influence the expected dimensionality and complexity of the segmented dotplot. To maximize information content while limiting the size of segmented dotplots, we set l and r to be stepwise functions of the sequence length:
l = r = 100 for sequences smaller than 50 kbp
l = r = 1.000 for sequences between 50 kbp and 500 kbp
l = r = 10.000 for sequences between 500 kbp and 5 Mbp
l = r = 20.000 for sequences larger or equal to 5 Mbp

Alignment segmentation and dotplot condensation

A custom algorithm converts the pairwise alignment returned by minimap2 into a segmented representation (NAHRwhals step 3) which facilitates downstream analysis and implicitly identifies repeat pairs required for subsequent steps. Following noise-reduction, borders, or 'gridlines', separating unique sequence blocks, are inferred in an iterative way (Fig. S3). In the first iteration, horizontal and vertical gridlines are drawn starting from each start- or endpoint of any alignment. In every subsequent step, overlaps between existing gridlines and alignments are determined, with the points of overlaps serving as a new source for spawning a new gridline in perpendicular direction. This process is repeated until no new gridlines can be spawned. In rare cases where the determined grid exceeds predefined maximum dimensions (default: n_rows + n_cols ≤ 250; n_alignments ≤ 150), the parameters for minimum alignment length (l) and rounding (r) are doubled until dimension requirements are met. Any sequence interval between two gridlines is then considered a segment, and any pairwise alignment can be expressed as a matrix of alignment of segments (x: Ref, y: Query) (Fig. S3B).

---

### On convex decision regions in deep network representations [^b0b918c2]. Nature Communications (2025). High credibility.

We now sample N s pairs of points within the given predicted class label and compute the shortest path in the graph between the pairs using Dijkstra's algorithm. For each path, we compute a score between 0 and 1. The path score is defined as the proportion of the number of nodes on the shortest path, without the endpoints, inside the decision region (i.e. with the same predicted label). If an edge directly connects the pair of nodes, the score is 1. If the points are not connected, the score is 0. We average the scores for all paths within one class to get a convexity score per class per layer. To get one convexity score per layer, we average over all paths regardless of class. Uncertainties are calculated as the standard error of the mean, where we set n as the number of points in the given class. This is likely a conservative estimate since the mean is based on many more pairs than there are points.

The runtime complexity of this procedure is, where N denotes the number of data points, D is the dimensionality of the representations and N c is the number of classes. See Supp. Mat. 1.4 for details.

Euclidean convexity is also measured for each layer and class separately. To measure the convexity of class C in layer l, we first extract hidden representations at l of all points predicted to belong to class C. We sample N s pairs of points. For each pair, we compute the N p = 10 equidistant points on the linear segment connecting the representations of the two endpoints. We feed the interpolated points to the rest of the network (after layer l). The score for each pair is then the proportion of the interpolated points that are also predicted to belong to class C. Finally, to get the score of Euclidean convexity for the whole class, we average the scores over all the pairs of points. To get the Euclidean convexity for each layer, we average over all classes.

---

### Functional anatomy and surgical principles of mitral repair for the Barlow valve: past legacy guides the future [^2538126c]. JTCVS Techniques (2021). Medium credibility.

Barlow Valve Repair: Understanding Functional Prolapse

From a surgical perspective, the Barlow Valve represents the most severe degenerative form of mitral valve disease. Anatomically, the leaflet tissue is diffusely thickened and excessive and may have varying degrees of calcification, chords may be elongated and thickened, and the annulus may be severely dilated. Importantly, there frequently is also functionally abnormal annular motion, as advances in echocardiography can now demonstrate. The posterior annulus moves outward and downward during systole (Figure 1). Irrespective of the presence of true "anatomic prolapse" of the free edge of one or both leaflets, as Klautz and colleagues describe, the "movement of the annulus causes any opposing segment to appear prolapsing". Thus, the valve may be competent in early systole, but with pathologic annular outward and downward motion, "functional prolapse" occurs in later systole. This explains the murmur that John Barlow detected occasionally commencing in mid-systole but nevertheless having a mitral origin.

Figure 1
Abnormal annular motion causing functional prolapse in the Barlow valve. The posterior annulus moves outwards (orange dotted lines) and downward during systole (arrows).

---

### Cutting second-order chords does not prevent acute ischemic mitral regurgitation [^2583dcf9]. Circulation (2004). Low credibility.

Background

Cutting anterior mitral leaflet second-order chordae has been proposed for repair in ischemic mitral regurgitation (IMR). We examined the efficacy of such chordal cutting in preventing acute IMR.

Methods and Results

Six sheep underwent radiopaque marker placement (left ventricle, mitral annulus, papillary muscles [PMs], and leaflets). The largest second-order chord from each PM was encircled with exteriorized wire snares. Three-dimensional marker coordinates were obtained with biplane videofluoroscopy before and during acute ischemia (80 seconds of mid-circumflex occlusion). Color Doppler transesophageal echocardiography was used to grade MR on a 0 to 4+ scale. Data were acquired immediately before and after dividing second-order chordae. Slope of the end-diastolic volume-stroke work relationship (PRSW) was calculated to assess systolic function. Chordal cutting increased anterior leaflet inflection angle (155 ± 12 versus 162 ± 9 degrees; P = 0.03), resulting in a flatter leaflet, but did not increase effective leaflet length (1.97 ± 0.24 versus 2.08 ± 0.23 cm; P = 0.15); PRSW decreased (63 ± 15 versus 56 ± 12 mm Hg; P = 0.008). Both before and after chordal cutting, ischemia caused: Septal-lateral annular dilation (P = 0.005), posterior PM displacement away from the mid-septal annulus (P = 0.06), increased leaflet tenting area (P = 0.001), and increased leaflet tenting volume (P = 0.002). Before chordal cutting, MR increased significantly during ischemia (0.5 ± 0.3 versus 1.7 ± 0.4; P < 0.001), and IMR increased similarly even after the second-order chords were cut (0.7 ± 0.4 versus 1.9 ± 0.9; P < 0.001).

Conclusions

Cutting second-order chordae resulted in LV systolic dysfunction and neither prevented nor decreased the severity of acute IMR, septal-lateral annular dilation, leaflet tenting area, or leaflet tenting volume.

---

### Guidelines and recommendations for performance of the fetal echocardiogram: an update from the American Society of Echocardiography [^15fb0e56]. Journal of the American Society of Echocardiography (2023). High credibility.

Fetal echocardiography — standard biometry at the four-chamber view includes calculating the cardiothoracic ratio from the inside circumference (or area) of the chest and the epicardial surface of the heart, and determining the cardiac angle by bisecting the chest with a line from the sternum to the spine and measuring the angle at which the ventricular septum would intersect that line.

---

### Pelvic organ prolapse: ACOG practice bulletin, number 214 [^c527778a]. Obstetrics and Gynecology (2019). High credibility.

Pelvic organ prolapse (POP) staging — maximal extent relative to the hymen — is defined as follows: Stage 0: No prolapse; anterior and posterior points are all −3 cm, and C or D is between −TVL and − (TVL − 2) cm. Stage I: The criteria for stage 0 are not met, and the most distal prolapse is more than 1 cm above the level of the hymen (less than −1 cm). Stage II: The most distal prolapse is between 1 cm above and 1 cm below the hymen (at least one point is −1, 0, or +1). Stage III: The most distal prolapse is more than 1 cm below the hymen but no further than 2 cm less than TVL. Stage IV: Represents complete procidentia or vault eversion; the most distal prolapse protrudes to at least (TVL − 2) cm. Stages are based on the maximal extent of prolapse relative to the hymen, in one or more compartments.

---

### Standardization of spirometry 2019 update. An official American Thoracic Society and European Respiratory Society technical statement [^df365e99]. American Journal of Respiratory and Critical Care Medicine (2019). High credibility.

Back-extrapolated volume (BEV) on the volume–time curve — Time 0 is found by drawing a line with a slope equal to peak flow through the point of peak flow on the volume–time curve and setting Time 0 to the point where this line intersects the time axis. The BEV is equal to the volume of gas exhaled before Time 0, which, in these two examples from the same patient, is 0.136 L for the left panel (acceptable) and 0.248 L for the right panel (unacceptable). For this patient, the BEV limit is 5% FVC = 0.225 L.

---

### Computing and visualising intra-voxel orientation-specific relaxation-diffusion features in the human brain [^001414c9]. Human Brain Mapping (2021). Medium credibility.

Comparingpeak‐specificvalues against their respectivecoordinates did not reveal a clear relationship betweenand peak orientation (Figure S2). As detailed in the Supporting Information, the inability to detect a subtle variation ofwith varying fibre orientation is attributed to the relatively high uncertainty of the 5Ddistributions. Despite the fact that no globalbehaviour could be teased out, the proposed method allowed the detection of relaxation differences between distinct WM tracts. As shown in Figure 7, these differences are best visualised in ascale spanning a more constrained interval of values than thescale used in Figure 6. Inspection of Figure 7 reveals that both the CST and the forceps major tracts are characterised by considerablyvalues. These observations are in accordance with the results of Lampinen et al. (2020), where longervalues were consistently found in the CST. The longerof the CST is also observed in voxels containing fibre crossings, withdifferences being discerned between the ODF lobes corresponding to the CST and the lobes that capture fibre populations from other tracts (see bottom right panels of Figure 7). Moreover, inter‐trackdifferences can also be observed in the tractograms displayed in Figure S3 of the Supporting Information, where the spatial distribution ofstreamlines correlates well with theODFs of Figure 7. While the exact mechanisms driving the longvalues found in the CST and the forceps major are still unclear, it is worth mentioning that these tracts are known to feature higher‐than‐average fractions of large axons (Dell'Acqua et al. 2019), meaning that differences in surface relaxation might play a part in determining the inter‐tractdifferences.

FIGURE 7
Orientation Distribution Function (ODF) maps coloured according to the orientation‐resolved means of T 2, Ê[T 2]. The Ê[T 2] values are displayed on a linear colour scale. The left and top‐right panels display the sets of ODF glyphs superimposed on a grey‐scaled map showing the signal fractions from the 'big' and 'thick' bin populations (1 − f thin) (non‐fibre‐like components). The zoom‐ins in the lower‐right panel offer a more detailed look into selected regions (continuous line boxes) and voxels (dashed line boxes) containing crossing between fibre populations with distinct Ê[T 2]. The observed high‐ T 2 components are assigned to the forceps major (yellow boxes) and the corticospinal tract (magenta boxes)

---

### Tracing multiple scattering trajectories for deep optical imaging in scattering media [^4bc9fcd5]. Nature Communications (2023). High credibility.

Proof of concept with numerical simulation

We performed numerical simulations to validate our proposed method of solving the inverse scattering problem (Fig. 3). Here, we consider a case where a target object is covered with multiple discrete phase plates whose phase functions are known a priori (Fig. 3a). Four phase plates are placed at depths ofμm, respectively, from the target object shown in the inset in Fig. 3a. The phase functionsof the four layers are shown in Fig. 3b. We set the size of each phase map as 200 × 200 μm 2, while that of the target object is set as 45 × 45 μm 2. Each phase map is filled with a random phase pattern to mimic a realistic scattering medium. In addition, different polygonal patterns and numbers are superimposed on each layer for ease of performance evaluation of the proposed algorithm (see Supplementary Section Numerical demonstration of MST algorithm with randomly patterned layers for the case of phase plates filled only with random phase patterns). Then, we numerically generate the reflection matrix R of the sample at a wavelength of 900 nm and an angular coverage of 1.0 NA based on Eq. (1).

Fig. 3
Numerical demonstration of tracking multiple scattering trajectories.

a Schematic of the sample configuration. Four phase plates are placed on top of a target object at a distance ofμm, respectively, from the target object at. Inset: ground-truth target object. Scale bar: 10 μm. b Ground-truth phase functionsof the four scattering layers in a. The side lengths of the phase maps are (100, 130, 160, 200) μm from the left. Scale bars: 30 μm. c Identified phase functionsby MST algorithm. d Conventional confocal reflectance image of the target. Scale bar: 10 μm. e MST image by rectifying the identified multiple scattering trajectory. Color scales in d, e are normalized by the maximum amplitude in e. f Ballistic wave intensity of the normally incident plane wave measured after each phase plate before (red circular dots) and after (blue square dots) the application of MST algorithm. g The performance of MST algorithm by evaluatingandwith the iteration process. h Angular spread function of a normally incident plane wave in the spatial frequency domain measured underneath each phase plate. i Same as h, but after rectifying the multiple scattering trajectory. Angular spread functions are displayed in the spatial frequency coordinateswith its center corresponding to. Scale bar: 0.1.

---

### Guidelines for performing a comprehensive transthoracic echocardiographic examination in adults: recommendations from the American Society of Echocardiography [^f4da9c21]. Journal of the American Society of Echocardiography (2019). High credibility.

Table 3 — two-dimensional linear measurements in the parasternal window PLAX view list core 2D grayscale metrics and illustrate alignment effects on values. In PLAX view, the listed measurements include IVS end-diastole thickness, LVIDd, LVPWd, and RV diameter end-diastole. Biplane imaging can assist with proper perpendicular alignment for the most accurate 2D measurements, with an example where LVIDd is 47.0 mm. When off-axis, biplane imaging shows the consequence of off-axis measurements: the LVIDd is decreased by 3.0 mm from 47.0 mm to 44.0 mm. With a sigmoid septum, when the measurement is moved slightly toward the LV apex just beyond the septal bulge, LVIDd is 53 mm and IVS is 7.0 mm; when the measurement is made at the MV leaflet tips, including the septal bulge, LVIDd is 38.0 mm and IVS is 17.0 mm.

---

### International consensus statement on nomenclature and classification of the congenital bicuspid aortic valve and its aortopathy, for clinical, surgical, interventional and research purposes [^ce4e7ff0]. European Journal of Cardio-Thoracic Surgery (2021). High credibility.

Congenital bicuspid aortic valve (BAV) diagnosis by transthoracic echocardiography and pathology — Parasternal short‑axis imaging can show 'the existence of only 2 commissures (asterisks) delimiting only 2 cusps', while parasternal long‑axis imaging 'shows systolic doming of the fused (conjoined) cusp (arrow), common for right-left coronary cusp fusion'.Pathology demonstrates 'the area of the raphe (dashed line) from the left ventricular perspective, forming an obtuse angle between the fused cusps', and a comparator shows 'a tricuspid aortic valve with acquired rheumatic fusion shows the cleavage plane with acute angle (yellow arrow)'.

---

### Anatomical considerations regarding the location and boundary of the depressor anguli oris muscle with reference to botulinum toxin injection [^3329eb52]. Plastic and Reconstructive Surgery (2014). Low credibility.

Background

Hyperactivity of the depressor anguli oris muscle can lead to a drooping of the mouth corner, which can give a sad, tired, or almost angry look in some patients. Botulinum toxin type A has recently been used to relax these hyperactive muscles. However, it is difficult to inject botulinum toxin type A into the depressor anguli oris muscle because its medial border overlaps with the depressor labii inferioris, and its lateral border is adjacent to the risorius, zygomaticus major, and platysma muscles. The aims of this study were to determine the topography of the facial muscles at the mouth corner and to provide critical information for determining the safest and most effective depressor anguli oris muscle botulinum toxin type A injection site.

Methods

Forty-two hemifaces from Korean and Thai adult cadavers were dissected.

Results

The location of the modiolus was 11.0 ± 2.6 mm (mean ± SD) lateral and 8.9 ± 2.8 mm inferior to the cheilion. The angle formed by the sagittal line passing through the modiolus (LV) and the line connecting the modiolus and the intersection point of the lateral border of the depressor anguli oris muscle and the mandibular border (LP2) was 44.7 ± 13.7 degrees. The angle formed by LV and the line connecting the modiolus and the most concave point of the medial border of the depressor anguli oris muscle (LP3) was 31.8 ± 8.5 degrees.

Conclusion

These results suggest that the fan-shaped area bounded by LP2, LP3, and the mandibular border is the safest and most effective depressor anguli oris muscle injection site.

---

### 2020 focused update of the 2017 ACC expert consensus decision pathway on the management of mitral Regurgitation: a report of the American college of cardiology solution set oversight committee [^e1f65020]. Journal of the American College of Cardiology (2020). High credibility.

Algorithm for determining eligibility for transcatheter mitral valve (MV) intervention — transthoracic echocardiography (TTE), clinical assessment, and transesophageal echocardiography (TEE) steps are specified, including anatomic thresholds. TTE directs to "Quantitation of MR using integrated methods†; confirm moderately severe or severe MR" and to "Distinguish mechanism of MR: primary versus secondary (versus mixed)." Clinical assessment should "Confirm NYHA status," "Assess adequacy of GDMT, as well as CRT and revascularization when indicated," and "Confirm MDT consensus recommendation for transcatheter treatment." TEE should "Confirm mechanism of MR and location of MR jet(s); exclude perforations and clefts" and "Assess for presence and location of calcification†," and then confirm favorable pathoanatomy. For primary MR, favorable features are "grasping zone ≥ 10 mm and without calcification," "flail width < 15 mm," "flail gap < 10 mm," and "single middle segment prolapse." For secondary MR, favorable features are "grasping zone ≥ 10 mm and without calcification," "coaptation depth < 11 mm," and "coaptation length (overlap length) > 2 mm." When calcification is uncertain, the page advises to "Consider cardiac CT if degree and location of calcification are unclear."

---

### 2020 focused update of the 2017 ACC expert consensus decision pathway on the management of mitral Regurgitation: a report of the American college of cardiology solution set oversight committee [^efc47fd8]. Journal of the American College of Cardiology (2020). High credibility.

Mitral regurgitation severity assessment — comprehensive transthoracic echocardiography: Evaluation of MR severity requires a comprehensive TTE and no single echocardiographic parameter should be the sole arbiter; the effects of chronic MR on left ventricle (LV) and left atrium (LA) and pulmonary artery pressure must be considered in an integrative fashion. Clinicians often use color flow Doppler (CFD) to form an initial impression, which should only be a starting point requiring further confirmation using a Bayesian approach that integrates multiple factors. After the initial impression, one should consider whether LA and LV sizes are normal and whether MR is holosystolic; if MR appears severe from a large CFD jet but LA/LV sizes are normal and MR is limited to late systole, the impression is most likely an overestimate. One should consider common reasons for overestimation such as high MR driving velocity and MR duration limited to very early or very late systole. When multiple specific parameters for mild or severe MR align with the initial impression, MR can be correctly graded with high probability, a scenario relatively common in practice, especially with mild MR and a structurally normal mitral valve (MV).

---

### Isentress [^58c6e69e]. FDA (2024). Medium credibility.

[Figure B]

Step 2. Fill the dosing syringe. Start with the plunger pushed all the way inside the barrel of the syringe. Insert the tip of the syringe into the water and pull back on the plunger to the 5 mL marking on the barrel of the syringe (see FIGURE C).

[Figure C]

Step 3. Pour out remaining water from mixing cup (see FIGURE D).

[Figure D]

Step 4. Add the 5 mL of water from the dosing syringe back into the mixing cup by pressing down on the plunger (see FIGURE E).

[Figure E]

Step 5. Open 1 foil packet. There is a notch that you can use to tear open the foil packet, or you may use scissors to cut along the dotted line. Pour entire contents into mixing cup (see FIGURE F).

[Figure F]

Step 6. Close the attached lid to seal the mixing cup (see FIGURE G). It will snap shut.

[Figure G]

Step 7. Swirl the mixing cup to mix using a gentle circular motion for 30–60 seconds (see FIGURE H). Do not turn the mixing cup upside down. The liquid will be cloudy.

---

### Deep learning-assisted comparative analysis of animal trajectories with deepHL [^c62158cc]. Nature Communications (2020). High credibility.

The maximum distance, which was derived from a finding of DeepHL, is more useful for evaluating the PD symptoms than conventional measures based on the movement speed. Note that the new feature is designed based on an insight drawn from an analysis by deep learning. These results suggest that DeepHL helps find a novel measure not directly linked to the movement speed, that is, a straight-line distance within a certain time window. When the aim of an animal is to visit all locations in an area, the travel distance over a short duration commonly becomes longer. Besides, it is well known that rodents, including mice and rats, spontaneously prefer to explore an environment, particularly in novel places. Thus, DeepHL may capture the fact that the abnormal behavior of the 6-OHDA lesion model of PD hinders such spontaneous behavioral traits of normal mice. Indeed, the 6-OHDA lesion mouse model appears to remain in the same place. Although this hypothesis should be verified based on the causality between behavioral traits and neural activity patterns underlying PD symptoms using neuronal recording together with its optogenetic manipulation in the basal ganglia and motor cortex, it is beyond the scope of this study.

Behavioral features of mice

According to Kravitz et al. ambulation was defined as periods when the velocity of the animal's center point averaged > 2 cm/s for at least 0.5 s. Immobility was defined as continuous periods of time during which the average change of the trajectory was < 1 cm for at least 1 s. Fine movement was defined as any movement that was not ambulation or immobility. Maximum travel distance within a ± 60-s window was defined as the maximum straight-line distance between the center of the window and each point within the window. Note that each feature value is computed for each entire 10-min trajectory.

6-OHDA injection of mice

Under isoflurane anesthesia, 6-OHDA (4 mg/ml; Sigma) was injected through the implanted cannulae (AP −1.2 mm, ML 1.1 mm, DV 5.0 mm, 2 μl). Animals were allowed to recover for at least 1 week before post-lesion behavioral testing.

---

### 3D visual guide to lines and stripes in chest radiography [^8deda201]. Radiographics (2023). Medium credibility.

Chest radiography continues to be the first-line imaging modality for evaluation of the chest. Interpretation is based on the understanding of complex three-dimensional (3D) structural relationships, which are translated into a two-dimensional (2D) plane. These 2D projections form multiple "lines and stripes" on chest radiographs, representing the interfaces between the pulmonary parenchyma, pleura, and normal mediastinal structures. Given the subtlety of overlying tissue and the need to mentally synthesize planar images into three dimensions, structural relationships may be difficult to appreciate. An understanding of these relationships forms the basis of recognizing pathologic conditions and providing an accurate differential diagnosis, which can assist in targeted appropriate further workup. On a 2D radiograph, this means recognizing the normal lines and stripes as well as their appearance when effaced or displaced. Once this abnormality is identified, a focused differential diagnosis can be generated, which can be further narrowed on the basis of other factors, such as patient history or ancillary findings. Three-dimensional cinematic rendering is an innovative tool that can help radiologists grasp these anatomic relationships and discern subtle findings at radiography. This technique allows improved visualization of structures such as the pleura that are difficult to appreciate with traditional imaging modalities. The authors provide an updated review of lines and stripes on chest radiographs, using 3D cinematic rendering as a teaching tool. © RSNA, 2023 Quiz questions for this article are available in the supplemental material.

---

### Fluid migrations and volcanic earthquakes from depolarized ambient noise [^13ee79e6]. Nature Communications (2021). High credibility.

Fig. 1
Maps of resultant lengths and azimuths from ambient noise at Campi Flegrei.

a The resultant length (R) is plotted with a squared interpolation from each station between 0.2 and 1 Hz during periods of low seismic release (2009, 2017). The continuous white segments show the corresponding azimuths (only for R > 0.25). The patterns are imposed over mapped fault strikes, fractures, and craters –. The Solfatara crater (S) and Monte Nuovo (M) are marked on the maps. The wide black dot is the stationary point of maximum vertical deformation for the last 36 years. The dotted black line marks the transfer structure (R > 0.31). The dotted white line contours the portion of the NW-SE extensional faults that shows R > 0.5 and the same azimuths over a decade. b Same map obtained using noise recorded over six months in 2018. The black cross shows the centre of the high-attenuation anomaly in Fig. 2a. Part of the transfer structure depolarizes due to fluid injections and migrations (black ellipse). c Same map obtained using two months of noise recorded before the Md3.1 earthquake (December 6 th, 2019, circled number 1) after fluids migrated to the east and west reservoirs. d Same map obtained using two months of noise after the Md3.3 earthquake (April 26 th, 2020, circled number 2), when the transfer structure reappears.

---

### Optimal coil array design: the two-coil case [^202c1833]. Magnetic Resonance Imaging (2007). Low credibility.

The optimization problem for coil arrays is largely unsolved, even for the case of a two-coil system. This paper reports a systematic computer simulation to investigate the maximal achievable signal-to-noise ratio (SNR) with a two-coil receiver system where, using cancellation circuitry, mutual inductance is made zero. Both symmetrical and asymmetrical solutions with respect to two-coil geometry are considered. SNR is measured at a single point at a certain depth and also along a longitudinal or transverse line at the same depth. The conducting medium containing these regions of interest is assumed to be an infinite half space, an infinite cylinder or a finite sphere. The previous coil array design using a "magical" overlap only approximates the optimal solution for the infinite half space. For the infinite cylinder and the finite sphere, optimal solutions can be quite different from the "magical" overlap.

---

### Dynamic imaging of fibrin network formation correlated with other measures of polymerization [^8962ef54]. Blood (2008). Low credibility.

Using deconvolution microscopy, we visualized in real time fibrin network formation in the hydrated state. Individual mobile fibers were observed before the gel point determined by eye. After gelation, an initial fibrin network was seen, which evolved over time by addition of new fibers and elongation and branching of others. Furthermore, some fibers in the network moved for a time. We quantified network formation by number of branch points, and longitudinal and lateral growth of fibers. Eighty percent of branch points were formed, and 70% of all fibers reached their maximum length at the gel point. In contrast, at the gel point, fiber diameter, measured as fluorescence intensity, was less than 25% and turbidity was less than 15% of the maximum values of the fully formed clot. The cumulative percentage of fibers reaching their final length and the number of branch points attained maximum values at 60% of maximum turbidity. Lateral fiber growth reached a plateau at the same time as turbidity. Measurements of clot mechanical properties revealed that the clots achieved maximum stiffness and minimum plasticity after the structural parameters reached their maxima. These results provide new information on the relative time sequence of events during fibrin network formation.

---

### Theory of branching morphogenesis by local interactions and global guidance [^6de26efd]. Nature Communications (2021). High credibility.

To determine how the morphology and shape of a branching structure is affected by local intrinsic vs. global extrinsic cues, we then asked whether the two key parameters of local self-avoidance f s and of external guidance f c could give rise to qualitatively different types of morphologies. Indeed, building a phase diagram of branching morphologies revealed key differences: in the presence of an external, axially oriented (linear) gradient, branched structures adopt triangular shapes, branching in a cone-shape with a well-defined angle that becomes smaller for increasing guidance strength f c (Fig. 1 c). On the other hand, changing the self-avoidance strength f s gave rise to denser branches with increased local alignment, but did not markedly change the overall shape.

Derivation of the continuum model

To back the qualitative insights of the morphology diagram obtained from simulations more quantitatively, we sought to develop an analytical theory of branching via external guidance, which falls under the class of branching and interacting random walksin an external field. Starting from a microscopic description of branching and elongation events, we derived a (continuum) Fokker–Planck equation for the tip growth and branching under the influence of external field guiding elongation (as described in detail in Supplementary Note 1, see also Supplementary Figs. 1–3). In particular, we obtained an equation for the time evolution of the probability of a tip to grow in a given direction, as determined by the alignment angle ψ relative to the polarity of the external field. In the absence of an external field, this direction is subjected to two types of random fluctuations: a branch tip undergoing elongation exhibits a small rotational diffusion that is described by small continuous changes in the alignment angle (bounded by ψ e at each time point), while branching events lead to abrupt jumps of larger maximal magnitude ψ b in the branch orientation. To account for the latter, non-local changes in the alignment angle ψ, we turned to the theory of Lévy flights, where a generalized Fokker–Planck equation has been proposed. Crucially, using a jump size distributionto describe the difference in the alignment angle beforeand after ψ an elongation or branching event, we could integrate these two sources of stochasticity into macroscopic "diffusion" and "mobility" coefficientsand, respectively. Finally, consistent with the implementation of the simulations, the effect of the external guidance could then be incorporated by a drift term, leading to the Fokker–Planck equation:which reflects a sinusoidal reorientation of the active tip by the external field.

---

### Geospatial mapping of distribution grid with machine learning and publicly-accessible multi-modal data [^c7745818]. Nature Communications (2023). High credibility.

Road modeling and link prediction

We further integrate road information to enrich the features for predicting whether there is a line connection between two predicted poles. Specifically, each road can be represented as a series of line segments. If a detected pole or a street view point has a distance ≤ D attach to a road, it will be attached to that road (Fig. 2 c). All attached street view points and poles are sorted in order along the road. Moreover, to reduce the number of poles missed by the pole detector, we insert pole(s) between a pair of poles if the distance between them is greater than a threshold D insert.

We develop a link prediction model that takes feature variables for a pair of poles as inputs and outputs whether there is a line connection between the pole pair. Any pair of poles with a distance less than a threshold D cand is considered as a candidate. We consider various types of classification models including logistic regression, decision tree, random forest, support vector machine, and gradient boosting. Feature candidates include (1) Distance between the two poles. (2) Whether the two poles are on the same road. (3) Whether the two poles are next to each other along the road. (4) Fraction of street view images with power lines detected between the two poles. (5) Minimum and average differences between the power line directions estimated from street view images and the direction of the line connecting the two poles. The small difference gives evidence that there is a power line connecting the two poles. (6) Whether either of the poles is detected by the pole detector or inserted. (7) Whether either of the poles is at a road intersection. (8) Whether the two poles are at the same road intersection. (9) The binary prediction of the modified Dijkstra's algorithm, running on a raster map. This algorithm finds the most efficient paths to connect poles: On a geospatial raster, each cell is assigned with a weight. By setting the weights at the positions of roads to be lower than others, connecting poles along a road is preferable (see the weight assignment scheme in Supplementary Note 1).

The best feature set and hyperparameters for link prediction are selected based on the 9-fold cross-validation on the San Carlos development set which are divided into 9 subsets according to the boundary divisions of the 9 census tracts in San Carlos. The output of the link prediction module is a geospatial graph with predicted poles as nodes and predicted line connections as edges.

---