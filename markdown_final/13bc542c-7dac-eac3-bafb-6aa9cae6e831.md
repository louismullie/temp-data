# Medical Question & Answer

**Sample ID**: 13bc542c-7dac-eac3-bafb-6aa9cae6e831
**Dataset Index**: 100390

---

## Question

35. How many diagonals does a thirty-four-sided polygon have?

---

## Answer

> Let's see… What do we have here? The user is asking how many diagonals a 34-sided polygon has. Let's break this down step-by-step. First, I need to think about the combinatorial formula for diagonals in an n-sided polygon. Then, I should verify the formula by reasoning about total line segments versus sides. Next, I will plug in n = 34 and compute the result. Finally, I will double-check the arithmetic and state the answer clearly.

> Let me first confirm the standard formula. The number of diagonals in an n-sided polygon is given by n(n − 3)/2, which counts all unordered pairs of vertices minus the n sides of the polygon itself, and then divides by 2 to avoid double-counting each diagonal. Wait, let me verify that logic: total vertex pairs are C(n, 2) = n(n − 1)/2, subtract the n sides to get n(n − 1)/2 − n = n(n − 3)/2, which matches the formula, so the derivation is sound.

> Now, I will substitute n = 34 into the formula. I need to ensure I compute this carefully: 34 multiplied by (34 − 3) equals 34 × 31, which is 1054, and then dividing by 2 gives 527. Hold on, I should verify the multiplication: 30 × 31 = 930 and 4 × 31 = 124, so 930 + 124 = 1054, and 1054 ÷ 2 = 527, confirming the result.

> Hmm, wait a minute, I initially thought the answer might be 561, but that would be the total number of line segments including sides, not diagonals. Let me reconsider: C(34, 2) = 34 × 33 / 2 = 561, and subtracting the 34 sides yields 561 − 34 = 527 diagonals, which aligns with the earlier calculation and corrects my initial overestimate.

> Final answer: A 34-sided polygon has 527 diagonals.

---

The number of diagonals in a 34-sided polygon is **527**. This is calculated using the formula for diagonals in an n-sided polygon: **n(n − 3)/2**, where n = 34. Thus, 34 × 31 / 2 = **527**.

---

## Formula for calculating diagonals in a polygon

The formula to calculate the number of diagonals in an n-sided polygon is:

Number of diagonals = [n(n − 3)/2]

This formula derives from the fact that each vertex connects to **n − 3** other vertices via diagonals (excluding itself and its two adjacent vertices), and each diagonal is counted twice in this total, hence division by 2.

---

## Application of the formula to a 34-sided polygon

For a 34-sided polygon, substitute **n = 34** into the formula:

Number of diagonals = [34(34 − 3)/2] = [34 × 31/2] = [1054/2] = 527

---

## Verification of the result

To verify, consider that the total number of line segments between any two vertices is **C(34, 2) = 561**. Subtracting the 34 sides of the polygon gives 561 − 34 = **527 diagonals**, confirming the result.

---

## Conclusion

A 34-sided polygon has **527 diagonals**, calculated as 34 × 31 / 2 = **527**.

---

## References

### Geometric frustration in polygons of polariton condensates creating vortices of varying topological charge [^3bf44056]. Nature Communications (2021). High credibility.

We observe that in some instances for frustrated odd-numbered polygons, the condensates do not successfully "agree" with each other on which direction to form a current. This leads to a state that does not have a single central vortex but rather forms a vortex–antivortex pair as shown in Fig. 5. Figure 5a, b shows the experimental real-space magnitude of the PL and phase, respectively. The diagonal dashed lines are guide to the eye marking a split in density across the condensate polygon. Figure 5c shows a zoomed-in region corresponding to the black dashed square. A vortex–antivortex pair can be observed with cores separated by ~1 μm. Figure 5d–g shows a corresponding numerical simulation of a condensate steady state with a vortex–antivortex pair, obtained by displacing pump spot number 4 in the pentagon by 2.8 μm radially outwards. Figure 5h shows that the measured phase difference between the vertices 0–1, 1–2, 2–3, and 0–3 is equal to π, whereas the phase of condensate 4 is not well defined due to destructive interference, fracturing it into two parts. Line profiles taken along the black circles in Fig. 5c, f unveil an opposite 2 π phase winding about each of the vortex cores (see Fig. 5i).

Fig. 4
Single shot of a pentagon of polariton condensates with a doubly charged vortex at the centre.

Pentagon condensate with a charge m = 2 vortex. a Experimental real-space PL and b, c phase extracted from interferometry from a single instance of the condensate. Simulated steady state m = 2 vortex wavefunction d real-space density, g Fourier-space density, and e, f real-space phase. c, f Zoomed-in regions of the dashed squares in b, e, respectively. h Phase difference between adjacent condensates (black dots) around the polygon extracted from the black circles in b. The red line is the expected phase difference of θ i, i +1 = 4 π /5. Green and blue dash-dotted lines mark the maximum deviation. i Line profile extracted along the black circle in c, f demonstrating a full 4 π phase winding. Yellow dots correspond to azimuthal angle equal to zero. Experimental data are represented by the coloured disks and numerical simulation by the black-dotted curve.

---

### Selective phase separation of transcription factors is driven by orthogonal molecular grammar [^9a1ece60]. Nature Communications (2025). High credibility.

Contact map definition

From the system graph creation process, contact matrices for all molecule combinations, over all frames are computed. This information is also useful for understanding the specific residues which drive condensation. As such, this information is aggregated during graph computation. Contact maps can be divided into two categories: intramolecular contact maps (interactions between particles in the same molecule copy), corresponding to the diagonal sub-matrices (I i i) in Supplementary Fig. 2, and intermolecular contact maps (interactions between particles of two different molecules), corresponding to the off-diagonal sub-matrices (I i j) in Supplementary Fig. 2. Since individual molecules of the same type are indistinguishable at the macroscale, only unique combinations of molecules need to be stored in different matrices, such that a single contact map for each intermolecular pairing and intramolecular contact map is computed. These maps contain the data for all copies of the same molecule pairs and for all timeframes studied. The contact maps by particle index (Figs. 3 a–c and 4 a–c in manuscript and Supplementary Figs. 34–60 parts A, D, G- if D or G present) display the contact information as a contact probability: the contact information is normalised by the number of frames, N f r a m e s and where N i and N j are the number of copies of molecule types i and j in the simulation.

When the contact information is presented based on residue type in a molecule (Figs. 4 d–f and 5 d–f in manuscript and Supplementary Figs. 34–60 parts B, E, H- if E or H present), a summation over the information in the contact maps by particle index to group interactions by residue type (equivalent to a matrix reduction operation). The presentation of normalised residue contact maps (Supplementary Figs. 34–60 parts C, F, I- if F or I present) applies a second normalisation step to the contact map by residue type of, with N j, r 1 the number of residue r 1 in molecule i and N j, r 2 the number of residue r 2 in molecule j.

---

### Prevalence of positional skull deformities in 530 premature infants with a corrected age of up to 6 months: a multicenter study [^81980f66]. BMC Pediatrics (2019). Medium credibility.

Comparison of the incidence of left- and right-sided plagiocephaly

Among the 271 cases of plagiocephaly, 188 (69.4%) cases met the right-sided plagiocephaly criteria (right oblique dimension – left oblique dimension ≥ 0.3 cm), which was significantly higher than the number of cases with left-sided plagiocephaly [83 (30.6%)] (P < 0.05).

CI, DD, and incidence of PD in preterm infants with different gestational ages at birth

DD (0.516 ± 0.363) and CI (0.885 ± 0.060) of the < 32-week group were significantly higher than those of the other two groups (p < 0.05). DD (0.437 ± 0.346) and CI (0.882 ± 0.067) of the 32–34-week group were significantly higher than those of the > 34-week group (0.387 ± 0.305, 0.875 ± 0.066). The infants in the < 32- week group had the highest incidence of plagiocephaly (58.4%) and brachycephaly (92.6%), which was remarkably higher than that of the other two groups (p < 0.05). The incidence of plagiocephaly (49.1%) and brachycephaly (83.7%) in the 32–34 week group was slightly higher than that of the > 34-week group (p < 0.05). The < 32-week group had the lowest incidence of dolichocephaly (1.5%), and the 32–34-week group (3.7%) and > 34-week groups (3.4%) showed similar incidence rates (Table 3).

Table 3
CI, DD, and incidence of PD in preterm infants with different gestational ages at birth

a: p < 0.05, compared with the < 32-week group; b: p < 0.05, compared with the 32–34-week group

CI, cranial index; DD, diagonal difference; N, number of cases; PD, positional deformity; W, Gestational week

---

### The emergence of geometric order in proliferating metazoan epithelia [^48beb717]. Nature (2006). Excellent credibility.

The predominantly hexagonal cell pattern of simple epithelia was noted in the earliest microscopic analyses of animal tissues, a topology commonly thought to reflect cell sorting into optimally packed honeycomb arrays. Here we use a discrete Markov model validated by time-lapse microscopy and clonal analysis to demonstrate that the distribution of polygonal cell types in epithelia is not a result of cell packing, but rather a direct mathematical consequence of cell proliferation. On the basis of in vivo analysis of mitotic cell junction dynamics in Drosophila imaginal discs, we mathematically predict the convergence of epithelial topology to a fixed equilibrium distribution of cellular polygons. This distribution is empirically confirmed in tissue samples from vertebrate, arthropod and cnidarian organisms, suggesting that a similar proliferation-dependent cell pattern underlies pattern formation and morphogenesis throughout the metazoa.

---

### Genome-wide fine-mapping identifies pleiotropic and functional variants that predict many traits across global cattle populations [^677a18e5]. Nature Communications (2021). High credibility.

Fig. 3
The estimation of the indictive number of pleiotropic QTL across 34 traits (tr01–tr34) for each chromosome segments.

a An asymmetric matrix of the variance and covariance of local gEBV of 34 traits for a chromosome segment. The asymmetry (the colour difference between elements above and below the diagonal) of the matrix is due to the use of two sets of local gEBV to calculate the covariance from different training populations (bulls or cows). The yellow colour indicates positive values and the dark colour indicates negative values. The diagonal elements are labelled as red 'V' (variance) and the off-diagonal elements are labelled as grey 'C' (covariance). b Equation (2) uses the inverse of the weighted correlation (r weighted) of the asymmetric variance and covariance matrix (panel a) to estimate the number of QTL within each segment (n (QTL) segment). c boxplot for the estimation of the number of QTL across 39,635 chromosome segments in bull data. d Boxplot for the estimation of the number of pleiotropic QTL across 40,763 chromosome segments in cow data. Each dot on c and d indicate the estimated number of causal QTL per segment. For each box, the minimum is the lowest point, the maximum is the highest point, whiskers are maxima 1.5 times of interquartile range, the bottom bound, middle line and top bound of the box are the 25th percentile, median and the 75th percentile, respectively.

Selection of 80k variants that best explain local gEBV variance

We wish to identify a reduced panel of variants that could be used to predict the breeding value of all 34 traits. To do this we looked for variants within each chromosomal segment that were highly correlated with the local gEBV for all traits by calculating:wherewas the amount of local gEBV variance explained by each variant, Var(g local) was the local gEBV variance, r 2 (g local, x) was the squared correlation between the vector of local gEBV (g local) and the vector of the genotype allele count of the variant (x). The sum across 34 traits, was calculated for each variant and used to select variants ranked in the top 3 in both sexes per segment. This led to the selection of 80k variants (83,455) as shown in Fig. 1. The original multi-trait GWAS p -value of these 80k variants are shown in Supplementary Fig. 11.

---

### Integrating genetic regulation and single-cell expression with GWAS prioritizes causal genes and cell types for glaucoma [^645aed56]. Nature Communications (2024). High credibility.

Fig. 2
Enrichment and colocalization analysis of eQTLs and sQTLs with POAG and IOP associations.

Quantile-quantile (Q-Q) plots of POAG cross-ancestry (a) and IOP (b) GWAS -log 10 (P -value) compared to expectation for the best eQTL per eGene sets (eVariants with FDR < 0.05) of the most significantly enriched tissues based on adjusted fold-enrichment (colored points), compared to all variants in the GWAS (black points). Grey line represents the diagonal. QTLEnrich (one-sided test; see Methods) was applied to assess GWAS p -value enrichment among the eQTL sets. Bonferroni correction was applied. c Histogram of percent of GWAS loci with ≥ 1 colocalizing e/sQTL (colocalization posterior probability (CLPP) > 0.01 from eCAVIAR and/or regional colocalization probability (RCP) > 0.1 from enloc) for POAG cross-ancestry, POAG European (EUR) ancestry subset, and IOP European ancestry GWAS meta-analyses. Numbers above the bars represent the number of loci with at least one colocalizing e/sQTL. Red, dark blue, and light blue bars indicate percentage of loci with at least one colocalizing eGene, sGene, or both, respectively. e/sGene, gene with at least one significant e/sQTL. d Scatter plot comparing unique number of e/sGenes that significantly colocalized per GWAS locus versus unique number of e/sGenes tested per locus. Points are color-coded by number of GWAS loci. The black line represents the diagonal. e Violin plots showing the distribution of the unique number of colocalizing eGenes (red), sGenes (dark blue), or both (light blue) per locus for the three GWAS meta-analyses tested. The number of GWAS loci that colocalized with eGenes, sGenes, or both shown in the violin plot are N = 69, 36, 76, respectively, for POAG cross-ancestry, N = 34, 17, 36, respectively, for POAG EUR, and N = 76, 40, 79, respectively, for IOP (Supplementary Data 16). The center line in the box plots contained within each violin plot shows the median, the box edges depict the interquartile range (IQR), and whiskers mark 1.5x the IQR. The violin plot edges represent the minima and maxima values. f, Stacked histogram showing the number of colocalizing e/sGenes per gene biotype for each GWAS. Protein coding (light blue), lincRNA (brown), antisense (grey), pseudogenes (yellow), and other (dark blue).

---

### A universal state and its relaxation mechanisms of long-range interacting polygons [^8b86753c]. Nature Communications (2019). High credibility.

Methods

Experimental details

Our system is made up of Nd 2 Fe 14 B magnetic particles with various shapes: disc, hexagon, pentagon, square and triangle, and all particles are coated with a smooth nickel layer. We show the top and side views of the particles in Supplementary Fig. 1. In the x – y plane, all polygons have a center-to-vertex distance 3.00 ± 0.03 mm and the discs have a radius of 3.00 ± 0.03 mm; in the z direction, all particles have the thickness 2.97 ± 0.03 mm. The particles have a strong permanent magnetization along the z direction, with a maximum magnetic field B ~ 0.5 T at the magnetic poles. In the x - y plane, the anisotropic magnetic field can extend its influence to large distances of multiple particle size. Using a force sensor, we can directly measure the repulsive interaction force between two particles, with different relative orientations (e.g. edge-to-edge, edge-to-tip, and tip-to-tip), as shown in Supplementary Fig. 2a, b for square and triangle particles, respectively. The force profile is close to a power-law, F ~ r −4.2 (or an interaction potential U (r) ~ r −3.2). Significant anisotropy can be observed at small and medium r. With these magnetic particles, we can study single-particle behaviors in systems with long-range and anisotropic interactions.

We confine the particles between two glass plates to form a single-layer 2D system. The thickness of the spacer is carefully controlled at 3.12 ± 0.04 mm, which ensures that the particles do not tilt significantly (the tilting angle is less than 5 degrees) in all experiments. To provide external excitations, we use a plate with randomly pinned magnets slowly moving back and forth under the 2D system, with an amplitude A = 420 mm and period T = 4.9 s, as illustrated in Supplementary Fig. 3 and Supplementary Movie 1. The perturbation strength can be controlled by the distance H between the perturbation plate and the system confining box. After each set of perturbations (50 cycles), the perturbation plate is removed, and the system relaxes into a new mechanical equilibrium configuration, which sits at one specific local minimum of the potential energy landscape. We record plenty of such local minima configurations (typically more than 500) and probe their transition kinetics.

---

### Vigorous convection as the explanation for pluto's polygonal terrain [^f3ee2dfc]. Nature (2016). Excellent credibility.

Pluto's surface is surprisingly young and geologically active. One of its youngest terrains is the near-equatorial region informally named Sputnik Planum, which is a topographic basin filled by nitrogen (N2) ice mixed with minor amounts of CH4 and CO ices. Nearly the entire surface of the region is divided into irregular polygons about 20–30 kilometres in diameter, whose centres rise tens of metres above their sides. The edges of this region exhibit bulk flow features without polygons. Both thermal contraction and convection have been proposed to explain this terrain, but polygons formed from thermal contraction (analogous to ice-wedges or mud-crack networks) of N2 are inconsistent with the observations on Pluto of non-brittle deformation within the N2-ice sheet. Here we report a parameterized convection model to compute the Rayleigh number of the N2 ice and show that it is vigorously convecting, making Rayleigh-Bénard convection the most likely explanation for these polygons. The diameter of Sputnik Planum's polygons and the dimensions of the 'floating mountains' (the hills of of water ice along the edges of the polygons) suggest that its N2 ice is about ten kilometres thick. The estimated convection velocity of 1.5 centimetres a year indicates a surface age of only around a million years.

---

### Danger zone assessment in small-sided recreational football: providing data for consideration in relation to COVID-19 transmission [^01df355b]. BMJ Open Sport & Exercise Medicine (2021). High credibility.

What are the new findings?

During recreational small-sided football games, limited time (34–115 s/h) within a 1.5 m danger zone was observed, and ~80% of all entries in the zone were shorter than 2 s.
Game format had no or very limited effect on time in the danger zone and on number and duration of contacts.
Recreational small-sided football is better defined as sporting activity with brief, sporadic contact rather than a contact sport.
Effects of game format variables were trivial to moderate, but 3v3 on a 31×15.5 m pitch had the lowest time in danger zone (within 1.5 m) and number of contacts per per cent infected player, and game format with few players also complies with the authorities' recommendation limiting the contact with a high number of people.

How might it impact on clinical practice in the future?

Authorities and governing bodies can use these scientific data to evaluate safe reopening of football for recreational players.
As football is the most popular sport in the world, reopening of grassroots football, when safe, may have a major impact on public health around the world during and after COVID-19.

---

### Data-driven identification of distinct pain drawing patterns and their association with clinical and psychological factors: a study of 21, 123 patients with spinal pain [^402f99d4]. Pain (2024). Medium credibility.

2.3.2. Pain drawing characteristics

We identified the following pain drawing characteristics: number of anatomical regions, number of strokes and points, overlapping polygons, and area inside and outside the human body silhouette. The pain drawing polygons were analyzed in relation to 46 predefined anatomical regions based on the study by Margolis et al.which was not visible to patients when completing the pain drawing. The anatomical subdivision was superimposed on data only during analyses (Supplementary materials Figure S1). The presence of pain in anatomically distinct areas was of relevance for our analyses, but the relevance of pain in the same anatomical areas on the left vs right side required careful consideration. A priori, we decided that the important information was the presence of unilateral vs bilateral pain. In situations of unilateral pain, it was not considered important for analyses of pain drawing characteristics whether this was left- or right-sided. We reasoned that the presence of unilateral leg pain on the right side vs the left side represented specific details of unilateral leg pain and not a principally different characteristic of the pain drawing. For analyses, unilateral pain was mirrored to the left side of the body. A binary data set of pain drawing markings inside the 46 anatomical regions was then created and used. The area inside the human body silhouette was determined using MATLAB intersect function(The MathWorks, Inc. v. 2020a). The number of pain sites was derived from the pain drawing as the sum of the 46 anatomical regions marked. The number of strokes, single points, and overlapping polygons was extracted from raw data. The areas inside and outside of the human body silhouette were calculated. Overlapping areas of polygons from different strokes were only counted once in the total area calculation.

---

### Clustering by measuring local direction centrality for data with heterogeneous density and weak connectivity [^fcddd465]. Nature Communications (2022). High credibility.

Estimation of the number of boundary points for determining T DCM

As shown in Supplementary Fig. 12a, we constructed a Triangulated Irregular Network (TIN) to connect all points. In graph theory, the degree of a vertex is defined as the number of edges incident to the vertex and each edge connects two vertexes. Based on this law, we can obtain:where deg(v i) represents the degree of vertex v i, V denotes the total number of vertexes, and E represents the total number of edges. In a graph, each triangle has three edges and each edge is shared by two triangles except the outermost edges. Actually, for a TIN that has a single connected component, the total number of boundary points is equal to that of the outermost edges, since all the outermost edges are connected end to end by boundary points and form a closed polygon. This law can be summarized as:where F and B refer to the total number of triangles and boundary points respectively. Meanwhile, 2D Euler's formula can be considered as follows:

By combining these formulas, we can infer the solution of B as follows:

However, the number of initial boundary points in the whole TIN is not equal to the total number of boundary points in the separated clusters. To conduct an accurate estimation, the whole TIN should be treated as multiple sub-networks (Supplementary Fig. 12b). Given C clusters, the number of boundary points in clusters can be solved as follows:where F is the total number of intra-cluster triangles in the multiple separated networks. V is known in a given dataset (i.e. n), but F and C are not. The initial F is the total number of triangles in the whole TIN, which includes the triangles connecting different clusters, i.e. cross-cluster triangles whose three vertices are not all in the same cluster (otherwise is intra-cluster triangle). Using the excessive number of triangles would make the number of boundary points B smaller than the true value. To identify the cross-cluster triangles, we set a judgment rule:where v 1, v 2, v 3 are the three vertices of a triangle, and σ (v i, v j) is an indicator function:

---

### Geometric frustration in polygons of polariton condensates creating vortices of varying topological charge [^f34bd15d]. Nature Communications (2021). High credibility.

Fig. 2
Extraction of the g (1) from stationary and circulating states in both a hexagon and heptagon.

a, b Real- and Fourier-space PL imaging of a hexagon and heptagon in different coupling configurations achieved by tuning the polygon radius. Two leftmost columns show condensation of a hexagon into in-phase (m = 0) and anti-phase (m = 3) configurations, whereas four rightmost columns show in-phase (m = 0) and vortex formation (m = ± 1, ± 2, ± 3) of a heptagon. c Extracted (red crosses) and calculated (black dots) mutual first-order coherence g (1) versus parameter d extracted from the interferogram between condensates for different polygon configurations. The values of g (1) lie upon the continuous function (green dot-dashed line) given by, where x has replaced the discrete parameter d. The point at d = 0 corresponds to the autocorrelation of the condensate wavefunction at zero time delay and is set as g (1) (0) = 1. The radii of the polygons are written in the top left hand corner of the real-space images in a. All real- and Fourier-space images are plotted on the same scale defined on the scale bar at the end of each row.

---

### Invariant and smooth limit of discrete geometry folded from bistable origami leading to multistable metasurfaces [^e4527d16]. Nature Communications (2019). High credibility.

Closer examinations in Fig. 5e–i reveal that each panel displays a dominant diagonal about which the panel bends more than the other diagonal. Figure 5f, g is a schematic that shows the difference between an isometrically deformed origami panel and a non-isometrically deformed origami panel, assuming that straight creases remain straight. An isometrically deformed origami panel will display a single curvature because the Gaussian curvature is zero everywhere inside the panel. On the other hand, a non-isometrically deformed origami panel displays double curvature (negative Gaussian curvature) because this deformation mode stores less elastic energy. For the thinner panels as shown in Fig. 5h, by comparing the depth of bending (the black lines), we identify obvious dominant diagonals (AE and E′C) that align with the alternating asymmetric triangulation. In Fig. 5i, we also see that the dominant diagonals are AE and E′C for the thicker hypar model; however, the more in-plane deformation makes the dominant out-of-plane bending diagonals less distinguishable as in the thinner panels.

We collect positional information from the 3D images to compare with the analytical predictions in Fig. 2e. We sample coordinates of the mountain vertices to get estimates for the coefficient k. We then pick the middle points of square creases to form a zig-zag path (i.e. the green lines in Fig. 5e) to estimate the folding angles (ρ) of the corrugations.

---

### Machine learning model for predicting the conversion to dementia using the cube copying test [^cec799ee]. Journal of Alzheimer's Disease (2025). Medium credibility.

Our findings suggest that very early signs of constructional apraxia-like symptoms are already present during the preclinical or MCI stages in individuals who will eventually convert to AD, DLB, or FTD and that these subtle changes can be detected using high-precision AI technology. Visuospatial dysfunction in patients with dementia encompasses difficulties in object recognition, spatial orientation, figure-ground discrimination, visual integration, and visual attention. – These impairments are often reflected in CCT drawings as inappropriate sizes, inaccurate line lengths and shapes, failures in connecting lines or positioning, lack of parallelism, missing elements, unnecessary lines, and distortions or simplifications of three-dimensional structures.–

In this study, converters' drawings exhibited greater discrepancies from the reference values for the number of lines in all directions (horizontal, vertical, and diagonal) and the number of vertices compared to those of non-converters. These deviations likely reflect characteristics such as drawing with multiple discontinuous lines rather than a single straight line, producing wavy lines, endpoints failing to overlap at a single point, and lines that were inappropriately segmented or connected at incorrect points.

Converters also exhibited shorter horizontal and vertical lines and longer diagonal lines than non-converters, along with greater variance in the lengths of all line types. This pattern suggests a distorted drawing style characterized by compromised perspective and reduced accuracy. Additionally, the average angle differences between lines of the same type, as well as the variance of angle differences between horizontal and diagonal lines, were larger. These findings indicate that converters' drawings lacked parallelism, reflecting inconsistency in their drawing styles (Figure 7).

Figure 7.
Characteristics of converters' drawings. (a) Multiple discontinuous, wavy lines instead of a single straight line. (b) Lines segmented at intersections with other lines. (c) Endpoints do not converge at a single point. (d) Incorrect connection positions of endpoints. (e) Lengths and angles between lines of the same type differ, causing a lack of parallelism.

---

### Flat square knots: are 3 throws enough? [^b21be78c]. American Journal of Obstetrics and Gynecology (2007). Low credibility.

Objective

The objective of the study was to determine the integrity of flat square knots.

Study Design

Three sutures were used in both 0 and 2–0 suture gauges: poliglecaprone 25 (Monocryl), polyglactin 910 (Vicryl), and silk. For each, flat square knots were tied with either 3 or 5 throws. Knots were tested to failure. The major outcome measured was the proportion of 3 throw knots untying, compared with that of 5 throw knots.

Results

There were high rates of untying for the poliglecaprone 25 and for the polyglactin 910 with both suture gauges when tied with only 3 throws. The failure rate decreased significantly when the throws were increased. There was no statistical benefit to increasing the number of throws for silk.

Conclusion

Knot failure is decreased by increasing the number of throws for poliglecaprone 25 and polyglactin 910. However, there is no advantage to increasing the number of throws from 3 to 5 for silk.

---

### Principal component analysis revisited: fast multitrait genetic evaluations with smooth convergence [^07cd4d1d]. G3 (2024). Medium credibility.

Standard singular value decomposition-based PCA

PCA reduces the dimensionality of data while preserving its essential information. PCA is computed formultivariate observation matrix, where n is the number of individuals and m traits. If, it is practical to calculate it formatrix of. Otherwise, it is calculated formatrix of. Let us represent a scaled symmetric covariance matrixas a product of two orthonormal matricescontaining orthogonal unit vectors as columns and one diagonal matrixsuch as. Orthogonality ofmeans that.is the square diagonal matrix with the singular values ofon the diagonal. Now, if we multiply both sides from left and right withand, respectively, we obtain, where the right hand side of equation contains eigenvalues of matrixin the diagonal in the ascending order. This decomposition is related to singular value decomposition (SVD). For PCA, the singular values are the square roots of the eigenvalues of the covariance matrix, and both eigenvalues and singular values provide insights into the phenotypic variability and importance of different components (eigenvectors or basis vectors) in transforming and summarizing the observed phenotypic profiles.

---

### Geometric frustration in polygons of polariton condensates creating vortices of varying topological charge [^6de4c478]. Nature Communications (2021). High credibility.

We provide further evidence on the formation of a circulating polariton current by investigating condensation in the single shot regime where a single instance of the condensate polygon is excited and measured. Figure 3a shows the experimental real-space PL of a frustrated pentagon (N = 5), wherein we observe an even number of interference fringes between neighbouring condensates. Figure 3b shows the Fourier-space PL where we observe an absence of radial nodal lines in contrast to Fig. 1k. We point out that the presence of radial nodal lines in the Fourier space PL would evidence anti-phase locked condensates, corresponding to standing wave formation along the polygon and a zero-net current. Here, however, the lack of nodal lines suggests the presence of a net particle current along the polygons edge. For comparison, we show numerical simulations in Fig. 3e, f of the real- and Fourier-space density of the condensate wavefunction resulting in a stable discrete vortex solution with a winding m = −1. We note that the winding number sign in simulation is stochastically determined from random initial conditions.

Fig. 3
Single shot of a pentagon of polariton condensates with a singly charged vortex at the centre.

Pentagon condensate with a charge m = − 1 vortex. a Experimental real-space PL, b Fourier-space PL and c, d phase extracted from interferometry from a single instance of the condensate. Simulated steady state m = −1 vortex wavefunction e real-space density, f Fourier-space density, and g, h phase. d, h Zoomed-in regions of the dashed squares in c, g, respectively. i Phase difference between adjacent condensates (black dots) around the polygon extracted from the black circles in c. The red line is the expected phase difference of θ i, i +1 = 2 π /5. Green and blue dash-dotted lines mark the maximum deviation. j Line profile extracted along the black circle in d, h demonstrating a full 2 π phase winding. Yellow dots correspond to azimuthal angle equal to zero. Experimental data are represented by the coloured disks and numerical simulation by the black-dotted curve.

---

### Effect of video monitor size on polyp detection: a prospective, randomized, controlled trial [^cb918bf3]. Gastrointestinal Endoscopy (2019). Medium credibility.

Background and Aims

The adenoma detection rate (ADR) is the most important quality metric for colonoscopy. Numerous factors are known to influence ADR. However, no data on the effect of monitor size on ADR exist. The aim of this study was to compare the ADR and polyp detection rate (PDR) achieved using 2 different-size video monitors (19-inch diagonal and 32-inch diagonal).

Methods

In a single-center, prospective, randomized clinical trial, endoscopists were randomized on a daily basis to perform routine ambulatory colonoscopies with either a 32-inch diagonal or a 19-inch diagonal video monitor.

Results

The study was conducted between October 2013 and April 2014 in an outpatient center of a tertiary referral hospital. Fifteen endoscopists performed 1795 outpatient colonoscopies (mean age, 55 years; 56% women; screening, 56%). There was no substantial difference in baseline patient characteristics between the 2 arms. The overall ADR (27.4% vs 27.9%; P = 0.80) and PDR (32.8% vs 34.4%; P = 0.50) were not significantly different between the 32-inch and 19-inch monitor group, respectively. The findings were not significantly altered when stratified by indication, cecal intubation, bowel preparation, operator experience, and time of endoscopy as well as in a multivariable model that included these variables as potential confounders (all P > .05). Overall, the ADR and PDR for each individual endoscopist did not appear to be influenced by monitor size.

Conclusions

The results of this trial do not support the notion that larger video monitors improve ADR. Future efforts to increase ADR should focus on other aspects of colonoscopy. (Clinical trial registration number: NCT01952418.).

---

### Geometric frustration in polygons of polariton condensates creating vortices of varying topological charge [^5ef65e9f]. Nature Communications (2021). High credibility.

Although the frustrated vortex regime can be classified from the nontrivial interference patterns appearing in the real- and Fourier-space PL, it does not concretely verify the presence of a vortex state. We therefore resolve the spatial phase distribution of the vortex using off-axis digital holography(see "Experimental techniques" in "Methods"). During condensation, the vortex formation stochastically results in either clock- or anticlock-wise winding of the phase along the polygon edge. Averaging over several condensate instances would therefore skew direct measurement of the phase. Instead, in order to view the vortex state, we utilise a single condensate realisation detection scheme, whereby each image of the polygon is the result of a single instance of the condensate formation. Figure 3c shows the experimental phase of the condensates with a m = −1 vortex, extracted from its interferogram, where it can be seen to spiral about the polygon's centre. Figure 3d shows a zoomed-in region corresponding to the black dashed square in Fig. 3c. Figure 3g, h show a corresponding real-space phase map from the simulation in Fig. 3e, f. To further verify that the entire condensate possesses a circulating current, we directly measure the phase coming from the bright emission spots at the polygon vertices where most of the condensate resides. The experimentally measured relative phase between neighbouring condensates is demonstrated with black dots in Fig. 3i, which are extracted from the regions denoted by black circles in Fig. 3c. The relative phases are close to the expected vortex value of θ i, i +1 = 2 π /5 (red line) with a maximal deviation of 0.6 radians (blue and green dash-dotted lines). Line profiles taken along the black circles in Fig. 3d, h are shown in Fig. 3j and unveil a full 2 π phase winding about the vortex core, where the experimental data are represented by the coloured disks and the numerical simulation by the black-dotted curve.

---

### Localized detection and classification of abnormalities on FFDM and tomosynthesis examinations rated under an FROC paradigm [^85d0e35d]. AJR: American Journal of Roentgenology (2011). Low credibility.

Objective

The purpose of our study was to assess diagnostic performance when retrospectively interpreting full-field digital mammography (FFDM) and breast tomosynthesis examinations under a free-response receiver operating characteristic (FROC) paradigm.

Materials and Methods

We performed FROC analysis of a previously reported study in which eight experienced radiologists interpreted 125 examinations, including 35 with verified cancers. The FROC paradigm involves detecting, locating, and rating each suspected abnormality. Radiologists reviewed and rated both FFDM alone and a combined display mode of FFDM and digital breast tomosynthesis (DBT) (combined). Observer performance levels were assessed and compared with respect to the fraction of correctly identified abnormalities, the number of reported location-specific findings (both true and false), and their associated ratings. The analysis accounts for the number and locations of findings and the location-based ratings using a summary performance index (Λ), which is the FROC analog of the area between the receiver operating characteristic curve and the diagonal (chance) line.

Results

Under the FROC paradigm, each reader detected more true abnormalities associated with cancer, or a higher true-positive fraction, under the combined mode. In an analysis focused on both the number of findings and associated location-based ratings, each of the radiologists performed better under the combined mode compared with FFDM alone, with increases in Λ ranging from 5% to 34%. On average, under the combined mode radiologists achieved a 16% improvement in Λ compared with the FFDM alone mode (95% CI, 7–26%; p < 0.01).

Conclusion

We showed that DBT-based breast imaging in combination with FFDM could result in better performance under the FROC paradigm.

---

### Higher-order triadic interactions: insights into the multiscale network organization in schizophrenia [^ceb54832]. Human Brain Mapping (2025). Medium credibility.

Compared to pairwise interactions, the number of triple interactions increases by a factor ofif all triple interactions are considered, and the number of triple interactions increases by a factor ofif all unique triple interactions are considered. The computation of all triple interactions for each subject is highly computationally intensive and requires significant time, even when utilizing large cluster servers. For our experiments, we utilized a high‐performance computing system equipped with NVIDIA GTX 1080 Ti GPUs, dual AMD EPYC 7551 32‐core processors (totaling 64 threads), and 350GB of RAM.

2.2 Triple Interactions Preserve Meaningful Brain Connectivity Patterns

To visualize these triple functional connectivity patterns more directly, we flattened the 3D tensor into a 2D matrix, where the connectivity pattern is again observed along the diagonal, as shown in Figure 2A. Compared to pairwise functional connectivity, derived from Pearson correlation and mutual information (shown on the left side of Figure 1C), we demonstrate that meaningful brain network connectivity is captured within triple network interactions. Given the large number of triple interactions, we identified the strongest and weakest interactions within the flattened triple interaction matrix. The strongest unique triple interaction involves HC‐IT (ICN 70), PL (ICN 34), and VI‐OT (ICN 15), as depicted on the left side of Figure 2B. In contrast, the weakest triple interaction involves SC‐EH (ICN 38), PL (ICN 36), and SM (ICN 59). This is a straightforward way to understand the connections within these large, complex tensors, while another approach involves extracting the latent factors that underlie them.

FIGURE 2
Multiscale triadic interactions in brain networks. The higher‐order triadic interaction matrix is shown in (A). There are a total oftriple interactions, with the maximum (HC‐IT, PL, VI‐OT) and minimum (SC‐EH, PL, SM) interactions identified within the multiscale human brain, as shown on the left and right sides of (B).

---

### ScConfluence: single-cell diagonal integration with regularized inverse optimal transport on weakly connected features [^37de2316]. Nature Communications (2024). High credibility.

Seurat

We compare scConfluence to Seurat v3 as the v3 refers to the version aimed at tackling diagonal integration. In practice, we used the R package Seurat v4.3.0 which finds anchor pairs between cells from different modalities by searching for Mutual Nearest Neighbors after having reduced the dimension of the data with Canonical Correlation Analysis (CCA). Before running the CCA, all modalities are converted to the same features so we followed the same protocol as described above in "Building the common features matrix" section, as it coincides with the indications described in the tutorials available in the Seurat documentation. We ran the Seurat method with default parameters, except for the Protein and smFISH datasets where we set the latent dimension to 15 since the default number of latent dimensions was close to or even higher than the number of features measured. For gene imputation in the scRNA-smFISH experiment, we used the TransferData function as indicated in the documentation.

LIGER

We compare scConfluence to Liger using the R package rliger v1.0.0. Liger relies on integrative non-negative matrix factorization (NMF) to perform diagonal integration and also requires as a first step to convert all modalities to common features. We did this step in the same way as for Seurat. For all datasets except the cell lines, we ran Liger with default parameters. On the cell lines simulated experiment, using the default setting of 30 latent dimensions resulted in the embeddings from different modalities being completely separated. Since the latent dimensions can be interpreted as clusters in NMF we used this to set the number of latent dimensions to 3 which greatly improved Liger's results. We could not tune other baselines similarly for this experiment as the dimension of their latent space can't be interpreted similarly and this did provide a competitive advantage to liger since we used the knowledge that there were 3 main clusters in the dataset (which usually can't be known when integrating new datasets). For the Protein and smFISH datasets we set the latent dimension to 15 since the default number of latent dimensions was close to or even higher than the number of features measured. For gene imputation in the scRNA-smFISH experiment, we used a knn regression with the scRNA embeddings serving as reference to predict the expression levels of held-out genes for smFISH embeddings.

---

### Evaluation of clinical prediction models (part 2): how to undertake an external validation study [^4f4df74a]. BMJ (2024). Excellent credibility.

The calibration curve's confidence interval is important to reveal the precision of the calibration assessment. It also quantifies the uncertainty of the actual risk in a group of individuals defined by a particular predicted value. For example, for the group of individuals with an estimated risk of 0.8 in figure 5, the 95% confidence interval around the curve suggests that this group's actual risk is likely between 0.78 to 1.

Quantifying calibration performance

Calibration plots with calibration curves should also be supplemented with statistical measures that summarise the calibration performance observed in the plot. Calibration should not be assessed using the Hosmer-Lemeshow test, or related ones like the Nam-D'Agostino test or Gronnesby-Borgan test, because these require arbitrary grouping of participants that, along with sample size, can influence the calculated P value, and does not quantify the actual magnitude or direction of any miscalibration. Rather, calibration should be quantified by the calibration slope (ideal value of 1), calibration-in-the-large (ideal value of 0) and — for binary or time-to-event outcomes — the observed/expected (O/E) ratio (ideal value of 1) or conversely the E/O ratio. A detailed explanation for each of these measures is given in supplementary material S3. Estimates of these measures should be reported alongside confidence intervals, and derived for the dataset as a whole and, ideally, also for key subgroups (eg, different ethnic groups, regions). To quantify overall miscalibration based on the calibration curve, the estimated or integrated calibration index can be used, which respectively measure an average of the squared or absolute differences between the estimated calibration curve and the 45 degree (diagonal) line of ideal calibration.

---

### Multifetal gestations: twin, triplet, and higher-order multifetal pregnancies: ACOG practice bulletin, number 231 [^cc52f840]. Obstetrics and Gynecology (2021). High credibility.

Death of one fetus in twin gestation — incidence, risks, and management: In the first trimester, a substantial number of women with multifetal gestations undergo spontaneous reduction of one or more fetuses, commonly referred to as the "vanishing twin", and the probability of this reduction increases with the number of gestational sacs: 36% for twins, 53% for triplets, and 65% for quadruplets; in the second trimester and third trimester, up to 5% of twins and 17% of triplets undergo death of one or more fetuses. Subsequent to the demise of one twin after 14 weeks of gestation, the risk of death of the co-twin is 15% in monochorionic gestations and 3% for dichorionic gestations, and the risk of neurologic abnormality in the surviving twin is greater in monochorionic gestations (18%) versus dichorionic gestations (1%). Although immediate delivery of the co-twin has not been demonstrated to be of benefit, in monochorionic twin gestations in which death of one fetus is identified before 34 weeks of gestation, management should be based on the condition of the mother or surviving fetus; in the absence of another indication, delivery before 34 weeks of gestation is not recommended, and care should be individualized with consultation with a physician with training in maternal–fetal medicine is recommended.

---

### The expected behaviour of random fields in high dimensions: contradictions in the results of bansal and peterson [^657f9d59]. Magnetic Resonance Imaging (2022). Medium credibility.

Bansal and Peterson (2018) found that in simple stationary Gaussian simulations Random Field Theory incorrectly estimates the number of clusters of a Gaussian field that lie above a threshold. Their results contradict the existing literature and appear to have arisen due to errors in their code. Using reproducible code we demonstrate that in their simulations Random Field Theory correctly predicts the expected number of clusters and therefore that many of their results are invalid.

---

### What is the best surgeon's knot? Evaluation of the security of the different laparoscopic knot combinations [^80bd5066]. Journal of Minimally Invasive Gynecology (2018). Low credibility.

Study Objective

To investigate the security of various knot combinations in laparoscopic surgery.

Design

Prospective nonrandomized trial (Canadian Task Force classification II).

Setting

Storz Training Centre, Sao Paulo, Brazil.

Intervention

Different knot combinations (n = 2000) were performed in a laparoscopic trainer. Dry or wet 2.0 polyglycolic acid or dry 2–0 poliglecaprone 25 was used. The tails were cut at 10mm, and the loops were tested in a dynamometer. The primary endpoints were the forces at which the knot combination opened or at which the suture broke. Resulting tail lengths were measured.

Measurements and Main Results

Surprisingly, the combination of a 2-throw half knot (H2) and a symmetric 1-throw half knot (H1s) (a surgical flat knot) opened at < 1 Newton (N) in 2.5% of tests and at < 10 N in 5% of tests. This occasional opening at low forces persisted after 1 or 2 additional H1s knots. A sequence of an H2 or a 3-throw half knot (H3) followed by a H2, either symmetric or asymmetric (H2H2 or H3H2), resulted in 100% secure knots that never opened at forces below 30 N. Other safe combinations were H2H1s followed by 2 blocking half hitches, and a sequence of 5 half hitches with 3 blocking sequences.

Conclusion

A traditional surgical knot (H2H1s) occasionally opens with little force and thus is potentially dangerous. Safe knots are H2H2 and H3H2 combinations, a sequence of 5 half hitches with 3 blocking sequences, and H2H1s together with 2 blocking half hitches.

---

### Towards a data-integrated cell [^72145394]. Nature Communications (2019). High credibility.

Fixing the number of clusters

The number of clusters, k, is a key parameter. On one hand, small values of k allow for integrating the input networks via NMTF's dimensionality reduction. On the other hand, large values of k allow for more accurate decomposition (with lower RSE), with the extreme case being placing each gene in a different cluster leading to the exact decomposition. Finding a suitable value of k that properly balances these two is a problem for which there is no gold standard procedure.

To avoid the circular argument of choosing the value of k that produces the most enriched clusters of genes and then validating the clusters based on their enrichments, we follow a completely different approach based on clustering stability analysis, inspired by Brunet et al. For a fixed value of k, when using random initial solutions, the decomposition process is non-deterministic and different runs result in similar, but different solutions. For a given run, by applying the hard clustering procedure to the corresponding matrix factor G, we obtain a clustering that we encode in an association matrix C, which is a 0–1 matrix in which C (i, j) = 1 if genes i and j belong to the same cluster, and 0 otherwise. Then, we compute, the average of the association matrices over ten different runs, and measure the stability of these clusterings according to the following dispersion coefficients:

where n is the number of genes and offdiag is the vector containing off-diagonal entries of. When clusterings are identical, off-diagonal entries ofare either 0 or 1 and bothandequal 1 (provided that the k clusters have the same size and that n / k is integer). On the other hand, if the clusterings are random and independent from each other, off-diagonal entries ofare expected to be all close to 1 / k and the two scores are expected to be close to 0.

The idea is to choose the value of k such that the obtained clusters are the most stable (for whichandare maximum). As presented in Supplementary Fig. 9, the most stable clusterings are achieved for k = 50, which is the value that we used in the main document.

---

### VA / DoD clinical practice guideline for management of bipolar disorder [^127e0c9a]. DoD/VA (2023). High credibility.

VA/DoD Clinical Practice Guideline — bipolar disorder algorithm structure and legend define a step-by-step decision tree with standardized symbols and arrows connecting numbered boxes indicating the order in which the steps should be followed; it includes steps of care in an ordered sequence, decisions to be considered, decision criteria recommended, and actions to be taken. Rounded rectangles represent a clinical state or condition; hexagons represent a decision point in the process of care, formulated as a question that can be answered "Yes" or "No".; rectangles represent an action in the process of care; and ovals represent a link to another section within the algorithm. Sidebars 1–7 provide more detailed information to assist in defining and interpreting elements in the boxes, and Appendix M contains alternative text descriptions of the algorithm.

---

### The management of major depressive disorder: synopsis of the 2022 U.S. department of veterans affairs and U.S. department of defense clinical practice guideline [^3528b93a]. Annals of Internal Medicine (2022). High credibility.

Algorithm for major depressive disorder (MDD) — this CPG's algorithm is designed to facilitate understanding of the clinical pathway and decision making process used in managing patients with MDD; it represents a simplified flow of the management of patients with MDD and helps foster efficient decision making by providers; it includes an ordered sequence of steps of care, decisions to be considered, recommended decision criteria, and actions to be taken; the algorithm is a step-by-step decision tree with standardized symbols and arrows connecting numbered boxes indicating the order in which steps should be followed, and sidebars provide more detailed information; shape legend: rounded rectangles represent a clinical state or condition, hexagons represent a decision point formulated as a question that can be answered "Yes" or "No", rectangles represent an action in the process of care, and ovals represent a link to another section within the algorithm; Appendix G contains alternative text descriptions of the algorithm.

---

### An exact arithmetic toolbox for a consistent and reproducible structural analysis of metabolic network models [^a0e79d55]. Nature Communications (2014). Medium credibility.

Essential and synthetic lethal reactions

In a metabolic model, a reaction is predicted to be essential if disabling it blocks the biomass reaction. To find all such reactions, we first compute some modes involving the biomass reaction, and then test those reactions that are active in each of those modes for essentiality. To test whether a reaction i is essential, we check whether the biomass reaction can be active when equation (1) holds with v i = 0. Note that every reaction in an enzyme subset with the biomass reaction is automatically essential. To find all the remaining ones, we generate a short flux mode u in the reduced network such that u biomass = 1 by minimizing the 1-norm of u, and then check essentiality of each reaction i active in u by checking for feasibility of equation (1) with v i = 0 and v biomass = 1. In this way, for each i, we obtain a certificate of essentiality or a vector v with v i = 0 and v biomass = 1.

A pair of reactions is called synthetic lethal if neither of them is essential, but disabling both of them disables growth. To compute all pairs of synthetic lethal reactions, we use the vector u from the previous step together with the vectors v corresponding to each nonessential reaction i active in u. Let L be the number of such vectors. Let G denote the set of nonessential reactions active in at least one of these vectors. We construct a matrix M of size | G | with M i, j being the number of modes that contain both i and j, with the diagonal element M i, i being the number of vectors that contain reaction i. The pair { i, j } is synthetic lethal for the L vectors if and only if each one of them contains either i or j, which is to say that M i, i + M j, j − M i, j = L, so we only check pairs satisfying this condition. This leads to a substantial reduction in the number of checks.

---

### Mono-planar T-Hex: speed and flexibility for high-resolution 3D imaging [^e6b14d76]. Magnetic Resonance in Medicine (2022). Medium credibility.

FIGURE 1
A, Gray dots depict part of the hexagonal grid in a transverse section of a stack of spirals or echo‐planar readouts. Blue dots mark the revolutions acquired within a shot for N = 1, 2, and 3 shots per k‐space plane. B, The hexagonal grid is described by oblique coordinates. All existing distances between grid points are represented in distances of the origin to points in one dodecant (yellow wedge), including its edges. Blue rings mark the distances reflected in (A), and the red ring highlights a distance not available with integer N. C, This distance is used when tilting the grid with respect to the rotational axis of the stack. The FE lines or spiral revolutions acquired in three subsequent shots are highlighted in red, orange, and yellow. D, The hexagonal grid is tilted as shown in (C). Red and yellow dots mark the points of the hexagonal grid that are covered by two subsequent shots. Green lines in the background show that all points of the hexagonal grid lie on nodes of a finer, rectilinear lattice, from which the starting angle of each spiral shot can be derived. Subsequent shots start with linearly progressing angles. The pattern is repetitive. E, Background: An entire mono‐planar T‐Hex stack of spirals cut open. The uppermost shot and the sites of puncture of the spirals are marked in dark gray. The resulting hexagonal grid shows the tilt as visualized in (C) and (D). In a representative patch, grid points that belong to spiral shots with the same phasing are colored the same. Foreground: Cross‐section corresponding to the stack in the upper panel, the acquisition time point is color‐coded, indicating a smoothfilter. Owing to the cross‐sectional depiction, "holes" appear on the central k‐space axis. In fact, this region is equally uniformly sampled, since all spirals start from the rotational axis of the cylinder

---

### Finding defects in glasses through machine learning [^fb0d1f69]. Nature Communications (2023). High credibility.

We conclude that even though the number of recorded transitions is the most important feature to predict which pair forms a double well, as seen in Fig. 5 b, a filter based solely on them still misses many pairs of interest and therefore is not the most efficient.

In Fig. 6 b, we focus on the distribution of the classical splitting Δ E, or energy difference between the two IS. When Δ E is large, the transition path between IS rarely forms a DW, or a TLS (red region). On the other hand, there are many pairs with a very small Δ E which are not necessarily more likely to be DW or TLS, hence the yellow region (could be any of TLS, DW, or non-DW). Ultimately we find a 'sweet spot' (green region), where TLS are more frequent. The ML model also captures this feature, as seen from the SHAP parameter of Δ E in Fig. 5 a. The next most important feature according to the ML model is the largest particle displacement, reported in Fig. 6 c. When it is larger than ~0.8 σ we rarely find TLS and DW, but we do not find them also when. The second row in Fig. 5 a confirms that the ML model has discovered this feature. In Fig. 6 d, we report the total displacement d. If d > 0.9 σ the pair is so different that it is not likely to be a TLS or DW, while this probability increases for smaller d. In Fig. 6 e, we report the distribution of off-diagonal elements Δ 0, measured using the WKB approximation as explained in ref. We find that the distribution obtained from TLS and DW scales as 1/Δ 0, in good agreement with the standard TLS model.

Finally, if one is interested in identifying TLS in a 'quick and dirty' way, we propose to use the number of recorded transitions to filter DW from non-DW, and then to select a sweet spot for the classical energy splitting and the displacements for selecting optimal TLS candidates.

---

### Parafermions in moiréminibands [^9d4a5fca]. Nature Communications (2025). High credibility.

In this work, we provide numerical evidence showing that the non-Abelian RR FCI at 3/5 filling can be realized in a moiré system. In particular, we perform many-body exact diagonalization on an exemplary moiré flat band based on a double twisted bilayer graphene (dTBG) model with tunable quantum geometry. First, we obtain the expected number of degenerate ground states appearing at momenta fulfilling the generalized Haldane statistics. After that, we verify the persistence of the many-body energy gap upon insertion of magnetic flux (i.e. twisted boundary conditions) and find that, on average, each ground state has a many-body Chern number of 3/5. More strikingly, we show that the state counting in the low-energy sector of the particle-cut entanglement spectrum (PES) exactly matches the number of allowed quasi-hole excitations. In addition, we find that the RR phase is destroyed when the average quantum metric of the considered flat band approaches asymptotically the ideal value for the second Landau level (LL), highlighting both the usefulness and the limitations of this quantity as a heuristic indicator for the emergence of non-Abelian phases. Finally, we show that the RR phase is less stable at 2/5 filling but still present — as reflected in the quasi-particle excitations accessed through the hole entanglement spectrum —, signaling the robustness of moiré-based parafermion FCIs.

---

### Realizing tight-binding hamiltonians using site-controlled coupled cavity arrays [^111523e9]. Nature Communications (2023). High credibility.

Note that, we assume thatis translationally invariant, and hence the number of functional parametersandneeded to model the device behavior can be restricted to 3 and 12 respectively.

We visualize this process in Fig. 3a where we show how we can use the model to predict the location of eigenenergies by finding the eigenvalues of the modified Hamiltonian. Starting with the initialand updating its diagonal terms by evaluating the functionat each site of the array for a particularwe predict the eigenvalues of the modified Hamiltonian as:

Fig. 3
Electrical control model and eigen-energy prediction.

a Visualization of the optimization process depicting how the model takes in the system Hamiltonianand fits for the functionwhich connects the applied voltage profile to change in onsite potentials. We predict the position of eigen-energies on application of by calculating the change in onsite potentials which lie along the Hamiltonian diagonal and finding the eigenvalues of the modified Hamiltonian. The optimization is initialized usingshown in the matrix form (only real part is depicted). All entries are in, with diagonal terms denoting the deviations in resonant frequency about the mean (dark purple:deviation, tan:deviation) and super/sub diagonal terms denoting the hopping rates.denote indices of sites in neighborhood of siteon which the functionis being applied on. The coefficientsare denoted in hues of blue andare denoted in hues of purple. b Violin plot denoting the fitting error normalized to the mean hopping rateacrosspoints. c Prediction accuracy plot where the x-axis denotes the random generation, and the y-axis denotes the wavelength. The location of the measured eigen-energies is denoted by the dark black lines in background. The radii of the circles denote the deviation of the predicted value from measured values (scale on top). The color of the dots denotes the overall prediction error for that generation.

---

### Finding spatially variable ligand-receptor interactions with functional support from downstream genes [^77717180]. Nature Communications (2025). High credibility.

Methods

Identifying cell-cell interaction interfaces constrained by interaction capacity

The inputs of SPIDER are the spatial gene expression matrixand the spot coordinatesof the ST data, with m denoting the number of spatial spots and n denoting the number of genes. From the gene set, we extract the ligand and receptor gene setthat contains genes participating in known ligand-receptor interactions. In this work, we use the LR pairs from CellTalkDB, which contains 3398 human LR pairs and 2033 mouse LR pairs.

We first evaluate the interaction capacity for spot by the total expression of ligand and receptor (LR) genes. Given the interaction capacity per spot, we can then use a power diagram to identify varying numbers of interfaces for spots with different interaction capacities. Similar to the Delaunay triangulation, the power diagram generated polygons representing spots, and we consider spots with adjacent polygons to be potentially interacting. To generate a power diagram, we lift spots from the Euclidean spaceonto a paraboloid in. This construction incorporates the interaction capacity c s of spot s with a scaling function f, defining its lifted height h s inThe lifting equation and capacity scaling are detailed in Supplementary Method 1.1. The interaction capacity c s modifies the paraboloid, with larger capacities pulling it downward, resulting in more extensive downward-facing facets. The convex hull of this adjusted paraboloid forms these facets, which correspond to the power diagram for the points. This lifting process determines the capacity-driven paraboloid and, consequently, the capacity-guided polygons representing the points.

---

### Predicting the frequencies of drug side effects [^0d801a96]. Nature Communications (2020). High credibility.

The objective function and decomposition algorithm

Let us denote our drug side effect matrix for n drugs and m side effects with the matrix, whereif the drug side effect pair (i, j) is very rare,(rare),(infrequent),(frequent) or(very frequent) andotherwise. We denote the set of frequency classes withand the set of zero values with. Our matrix decomposition model approximates the data matrix R by the product of two low-rank matrices, as follows:whereis the matrix of drug signatures (each row contains a drug feature vector) andis the matrix of side effect signatures (each column contains a side effect feature vector). The rank ofis k < < min(n, m), that is, the number of components in the signatures. To learn our model in Eq. (2), we minimise the following loss:subject to non-negative constraints

whereis the Frobenius norm andindicates element-wise matrix multiplication, are projection functions to discriminate between the observed and unobserved entries in R, that is, iforotherwise; iforotherwise. Our matrix decomposition model assigns different levels of confidence associated with the data.is a model parameter that is set to account for the lower confidence on the unobserved associations in the matrix.

To minimise Eq. (3) subject to non-negative constraints, we developed an efficient multiplicative learning algorithm inspired by the diagonally rescaled principle of non-negative matrix factorisation. The algorithm consists of iteratively applying the following multiplicative update rules:

Following the guidelines to implement NMF, a small number ε = 10⁻¹⁶ was added to the denominators in Eq. (4) to prevent division by zero, and we initialised W and H as random dense matrices uniformly distributed in the range [0, 0.1]. Furthermore, to avoid the well-known degeneracyassociated with the invariance WH under the transformationand, for a diagonal matrix, we normalised H at each iteration as follows:where h p denotes the vector corresponding to the p th row in H.

---

### FDA oral history interview, trepagnier-FDA and hurricane katrina… [^88b5cb6b]. FDA (2025). Medium credibility.

stilts, so they were like eight feet, 10 feet above the water, regular water line. But the water had come up so high, it had totally just washed them all — every last one of them were gone along. And this was like not a major hurricane. This was just like a 1 or 2. say, like the late '50s and '60s were raised. They were on piers up off the ground. And our house was probably like two feet, two and a half feet on piers. And then I had, during the course of living there, I had bought the house next door. when the old lady died, because it was a rental double, and when she died, I bought that house, and it was a ranch-style flat right on the ground. And I had a friend of mine living on one side, and this old lady that had been living there for years was living on the other. JS: The 29th is when it made landfall, on Monday, Monday the 29th. TT: Twenty-seventh. So this was the 27th, that night.

Then the next morning we woke up about 8: 00, and we were in the living room, and we just turned on the television, and the mayor was talking about mandatory evacuation, and we kind of just looked at each other and said, "You know, I think this is 7. we decided to take a secondary old highway which went over two or three little bridges between Louisiana and Mississippi, and we were doing great. We were sailing along. And all of a sudden the traffic stopped, and we got way out in, they call it the Rigolets. It's the area where Louisiana and Mississippi meet, and it's very marshy. It's real watery. already starting to surge from the hurricane. It was pushing the water up through the Gulf into these Rigolets, which dumps into the lakes, in Lake Pontchartrain. And it was 9. where all the tornadoes hit. She went to an area that was — it was bad where her house is, because I saw where she was living. I mean, I knew Patt for 30 years.

I'd gone to her house after the hurricane, several months later, and it was pretty devastated as far as.

---

### Task-induced brain state manipulation improves prediction of individual traits [^e515be89]. Nature Communications (2018). Medium credibility.

Finally, to explicitly explore the macroscale networks related to gF and perturbed by each task, we assigned each edge in m +, int and m −, int to a pair of canonical networks (i.e. edge (i, j) would be assigned to the network that includes node i and the network that includes node j; see Functional parcellation and network definition for an explanation of the canonical networks). Edge counts were normalized to account for network sizes as follows:whereandrepresent the relative contributions of connections between canonical networks A and B to the intersection CN and AN, respectively; andare the numbers of edges between A and B in the intersection CN and AN, respectively; andare the total numbers of edges in the intersection CN and AN, respectively; E A, B is the number of edges between A and B in the whole brain; and E tot is the total number of edges in the whole brain. Because these analyses do not evaluate network overlap and sparse networks facilitate interpretation of results, these steps were performed on networks generated with an edge-selection threshold of P < 0.001. Assignments are visualized in a 10 × 10 matrix. These are diagonally symmetric matrices, and therefore we only display the bottom triangle of each HCP matrix and the upper triangle of each PNC matrix (Fig. 2d).

Code availability

Matlab scripts to run the main CPM analyses can be found at. BioImage Suite tools used for analysis and visualization can be accessed at. Matlab scripts written to perform additional post-hoc analyses are available from the authors upon request.

Data availability

The HCP data that support the findings of this study are publicly available on the ConnectomeDB database. The PNC data that support the findings of this study are publicly available on the database of Genotypes and Phenotypes (dbGaP, accession code); a data access request must be approved to protect the confidentiality of participants.

---

### Healthy housing reference manual [^4530c378]. CDC (2006). Medium credibility.

Healthy housing — exterior walls and siding materials note that in frame construction the base material of exterior walls is called sheathing, which may be square-edge, shiplap, tongue-and-groove boards, or plywood or oriented strand board (OSB), and that sheathing stiffens the frame to resist sway; for this reason it is applied diagonally to brace walls against racking. In older homes, asbestos-cement siding shingles can still be found, and asbestos and cement shingles used until the early 1970s are fire resistant but also a health hazard. Vinyl siding is manufactured from polyvinyl chloride (PVC), which has provided impact-resistance, rigidity, and strength, but the use of vinyl siding is not without controversy because PVC is known to cause cancer in humans; accidental fires in vinyl-sided buildings are more dangerous because vinyl produces toxic vapors when heated. Cedar wood shingles and aluminum are manufactured with a backer board that gives insulation and fire-resistant qualities.

---

### Approximations to the expectations and variances of ratios of tree properties under the coalescent [^cf6c6a02]. G3 (2022). Medium credibility.

We have found that approximations for fixed n and in the limit asare quite accurate in predicting the expected values seen in coalescent simulations of the ratios (Fig. 2). For the variances, the approximations are generally less accurate, although in most cases, graphs of the approximations and simulated values have similar shape (Fig. 4). These approximations are obtained from a Taylor approximation for the variance of a ratio (equation 4), and higher-order approximations of this variance could potentially be applied by use of Taylor's theorem; as the order of the approximation increases, however, the complexity of the resulting formula also increases. For those variances for which the approximation and simulation are not close in Fig. 4, we advise caution in using the variances in settings in which a precise approximation is needed.

---

### Universality in long-distance geometry and quantum complexity [^47f080b3]. Nature (2023). Excellent credibility.

A careful analysis, confirms this picture and shows that the very largest additive discrepancy from thedistance is found near the cut locus, so for all U and, As, theandBerger spheres agree on distances to within a picometre. (A two-dimensional example that shows the same phenomenon is given in Supplementary Information 3).

Finally, let us examine the role of curvature. At large, the metric becomes strongly curved: the easy–easy section becomes very negatively curved, and the easy–hard sections become very positively curved. We call the σ x and σ y directions easy because they are cheap to move it, whereas the σ z direction is hard to move in for. The curvature length, which is also the distance to the cut locus in the hard direction, becomes very short. The high curvature explains how the metric can hide lots of volume at short distances that are invisible at long distances. Consider an operational definition of volume that counts how many marbles can be packed into the space: if we can cram in n (r) marbles each of radius r, then the volume is proportional to. Although the volume grows without bound as, the effective volume n (r) r 3 at any finite value of r does not. Instead, the effective volume grows like r −1 as we take r smaller and only levels off atonce r is less than the curvature length. Thus even asthe effective volume, as probed by experiments with finite resolution, stays finite.

Euclidean group

Consider parallel parking a unicycle.

The unicycle starts facing parallel to the curb and ends facing parallel to the curb but displaced sideways by z. The configuration space of the unicycle is its possible locations { y, z } and orientations { θ }, forming the Euclidean group SE(2). There are three primitive operations: roll forwards or backwards; turn; or drift sideways (perpendicular to the rolling direction). We model the difficulty of any parking manoeuvre withThe cost of parkingis the length ∫d s of the shortest path that connects our starting configuration { θ, y, z } = {0, 0, 0} to our parking spot {0, 0, z }.

---

### Lattice-free prediction of three-dimensional structure of programmed DNA assemblies [^f682273c]. Nature Communications (2014). Medium credibility.

Tile-based assemblies with non-parallel four-way junctions

Next, we tested the ability of our approach to model extended, repeating tile-based structures in which duplexes at four-way junctions are not forced to reside in either parallel or anti-parallel configurations. As a critical evaluation of the empirical four-way junction model, we revisited the tile-based ribbon previously studied by Mao and Seeman(Fig. 1). We studied eight variants of the original 21 × 21 bp flat structure by independently varying the lengths of the two duplex arms from 20 to 22 bps. Because each of the four-way junctions in the final assembly are interconnected by B-form DNA duplexes that resist bending, twisting and stretching, over- and under-winding and stretching induced by these mismatches in tile dimensions are expected to result in ribbon structures that deviate from the flat, ground-state structure observed for the 21 × 21 bp case. Geometric arguments based on the natural pitch of B-form DNA suggest that a single deletion (insertion) in the x-direction, n x = 20 (22) bp, will result in a left (right)-handed twist about the x-direction (Fig. 3a and Supplementary Fig. 12). In contrast, a single deletion (insertion) in the y-direction, n y = 20 (22) bp, will result in a right (left)-handed twist about the x-direction (Fig. 3a and Supplementary Fig. 12). Following this geometric argument, six tile designs consist of non-conflicting handedness or chirality, whereas two cases, (n x, n y) = (20, 20) and (22, 22) bp, consist of conflicting handedness (Fig. 3a and Supplementary Fig. 12). Interestingly, the model predicts that the (20, 20) design is left-handed about the x-direction, whereas the (22, 22) design is right-handed. In contrast, the model predicts a handedness in each of the other six cases that is consistent with the preceding geometric argument (Supplementary Fig. 12). Experimentally, we synthesized N × 4 lattices instead of N × 2 lattices to resolve their handedness within the limited resolution of AFM. Synthesized structures agreed with model predictions for the (21, 21), (22, 21) and (22, 22) designs in which folding was successful, whereas low synthesis yields of the (20, 20) and (20, 21) designs in diverse buffer conditions precluded a determination of ribbon structure (Supplementary Figs 13 and 14). Although resolving the origin of this failure to self-assemble remains for future work, an intriguing possibility is that the (20, 20) and (20, 21) designs with a left-handed twist about the x-direction force the immobile four-way junctions, which are flanked by four bps T-A, C-G, A-T and G-C and first introduced by Seeman, into energetically unstable conformations.

---

### The definition and measurement of heterogeneity [^cd67f037]. Translational Psychiatry (2020). Medium credibility.

Methods that do not require a priori stratification

There are three main approaches to quantify heterogeneity when no compelling a priori stratification exists: (A) treating heterogeneity as the "volume" of a space that completely encloses one's data points, (B) clustering-based methods, and (C) dendrogram-based methods.

Heterogeneity as a convex hull volume

Roughly speaking, the space enclosed by the smallest perimeter around all pairwise paths in one's data is a convex hull. The volume of this space is sometimes used as a heterogeneity index, but if data are not distributed uniformly within the convex hull, heterogeneity will be overestimated (Fig. 4a–c). We know of no psychiatric study using convex hull volume to quantify heterogeneity.

Fig. 4
Illustration of convex hull and dendrogram-based heterogeneity indices for non-categorical systems.

Panel a illustrates the basic concept of a convex hull on synthetic 2-dimensional data. The volume of the hull is taken as an index of heterogeneity. Panel b shows one problem with the convex hull method, which occurs when data lie along a lower dimensional surface (here just a curve). In this example, the data are all concentrated along the outer border of the hull, leaving the core unoccupied. However, the convex hull volume index will nonetheless count the empty space toward the heterogeneity value. Panel c illustrates the effect of outliers on convex hull volume. Since a convex hull is found by creating a "shell" around one's data, outlying points will expand this shell in ways that leave much of the convex hull empty (though still counting toward the heterogeneity value). Panel d shows the dendrogram computed using agglomerative clustering for a simple mixture of five 2-dimensional (2D) Gaussians. The functional diversity (FD) measure, shown in the title, is the sum of all branch lengths in this tree. Panel e shows a simple simulation with five 2D Gaussians (standardized to lie within the bounds [−1.5, 1.5] in both axes) that were progressively separated further. One can appreciate that the FD measure decreases as the distributions become more distinct. This is the opposite effect demonstrated by the convex hull volume, insofar as FD increases as the space becomes more densely populated with data points.

---

### A design principle of polymers processable into 2D homeotropic order [^a9d31e4f]. Nature Communications (2016). Medium credibility.

How to orient polymers homeotropically in thin films has been a long-standing issue in polymer science because polymers intrinsically prefer to lie down. Here we provide a design principle for polymers that are processable into a 2D homeotropic order. The key to this achievement was a recognition that cylindrical polymers can be designed to possess oppositely directed local dipoles in their cross-section, which possibly force polymers to tightly connect bilaterally, affording a 2D rectangular assembly. With a physical assistance of the surface grooves on Teflon sheets that sandwich polymer samples, homeotropic ordering is likely nucleated and gradually propagates upon hot-pressing towards the interior of the film. Consequently, the 2D rectangular lattice is constructed such that its b axis (side chains) aligns along the surface grooves, while its c axis (polymer backbone) aligns homeotropically on a Teflon sheet. This finding paves the way to molecularly engineered 2D polymers with anomalous functions.

---

### Three-dimensional echocardiography in congenital heart disease: an expert consensus document from the European association of Cardiovascular imaging and the American Society of Echocardiography [^10c6a8b3]. Journal of the American Society of Echocardiography (2017). Medium credibility.

Summation of disc method — The semi-automated summation of disc method is the least constrained by geometry and should be included with post-processing software particularly for ventricles of abnormal morphology.

---

### Multifetal gestations: twin, triplet, and higher-order multifetal pregnancies: ACOG practice bulletin, number 231 [^e67f15e2]. Obstetrics and Gynecology (2021). High credibility.

Multifetal gestations — antenatal corticosteroids: In singleton gestations at risk of delivery between 24 weeks and 34 weeks of gestation, antenatal corticosteroids decrease neonatal death, respiratory distress syndrome, intraventricular hemorrhage, and necrotizing enterocolitis, and although benefit in multifetal gestations needs further research, the National Institutes of Health recommends that, unless a contraindication exists, a course of antenatal corticosteroids should be administered to all patients who are at risk of delivery within 7 days and who are between 24 weeks and 34 weeks of gestation, irrespective of the fetal number. During the periviable period, use should be considered in the context of a family's decision regarding resuscitation. Regularly scheduled repeat courses or serial courses (more than two) are not recommended; a single repeat course should be considered in women with a gestation of less than 34 weeks who have an imminent risk of preterm delivery within the next 7 days and whose prior course was administered more than 14 days previously, and rescue-course corticosteroids could be provided as early as 7 days from the prior dose.

---

### Hourly step recommendations to achieve daily goals for working and older adults [^588d8957]. Communications Medicine (2024). Medium credibility.

Figure 3 shows the predicted mean step counts and 95% CI for the rest of the day, given the step counts accumulated from 6 p.m. to 11 p.m. adjusting for age group, BMI group and sex. Overall, there was little difference in the conditional predicted mean step counts for the rest of the days between the weekdays and the weekends. On weekdays, participants who accumulated 6000 steps by 6 p.m. had a 0.692 probability of achieving 10,000 steps (all the goals) by the end of the day (refer to the Goal 3 diagonal line in Fig. 3, Table 3, and Supplementary Table S2). Similarly, participants who had accumulated 7000 steps by 7 p.m. 8000 steps by 8 p.m. 8500 steps by 9 p.m. and 9500 steps by 10 p.m. achieved 10,000 mean steps by the end of the day with a probability of 0.910, 0.982, 0.700, and 1, respectively. On weekends, participants who had accumulated 6500 steps by 6 p.m. 7000 steps by 7 p.m. 8000 steps by 8 p.m. 8500 steps by 9 p.m. and 9500 steps by 10 p.m. achieved 10,000 mean steps by the end of the day with probability 0.852, 0.583, 0.947, 0.717 and 1, respectively. The step counts required to achieve 5000 and 7500 steps by the end of the day can be found in Supplementary Tables S3 and S4, respectively.

---

### Integer topological defects offer a methodology to quantify and classify active cell monolayers [^094b9046]. Nature Communications (2025). High credibility.

To test the relation between cellular flows and active forces from experimental data, we decomposed each of them into parallel and perpendicular components relative to the principal axis of local Q in regions outside defect cores (Supplementary Fig. 5). In Fig. 4 b–d, we have shown parallel components on asters and spirals (θ 0 = π /4) and perpendicular components on targets and spirals (θ 0 = π /4), as they represent the primary components associated with inward flows on the corresponding patterns. Concerning the ∇ ⋅ ρ Q term, the parallel components exhibited negative correlations with net velocity, while the perpendicular components showed positive correlations (Fig. 4 b), another indication that the linear theory cannot completely explain the observed phenomena. However, these components showed a consistent negative correlation (Fig. 4 c) for the ρ Q ⋅ (∇ ⋅ ρ Q) term and a consistent positive correlation (Fig. 4 d) for the (ρ Q ⋅ ∇) ⋅ ρ Q term. These results provided evidence for the relevance of the two nonlinear active forces to cellular flows.

Predicting cellular flows from local orientations

From the experimental data, we extracted the value of each term in Eq. (2), (5) using the average net velocities, orientations, and densities. To quantitatively assess our theory, we identified the best-fit values of the coefficients in Eq. (2), (5) via the Bayesian inference method (Methods) applied to outer regions (100 μ m < r < 500 μ m). During fitting, we replaced ρ in Eq. (2), (5) with the normalized density ρ / ρ 0, where ρ 0 represents mean density. The fits yielded values for five model parameters: For each defect type, we determined the best-fit values (Supplementary Tab. 1) and then averaged these values across various defect types to yield, with SDs as errors. Although the SD in these coefficients were large due to differences in cell conditions, the signs of these coefficients — — were maintained.

---

### Recommendations for noninvasive evaluation of native valvular regurgitation: a report from the American Society of Echocardiography developed in collaboration with the Society for Cardiovascular Magnetic Resonance [^f59ef754]. Journal of the American Society of Echocardiography (2017). Medium credibility.

Left ventricular volume calculation by short-axis summation — example and method show that sequential short-axis slices from the mitral annular plane (base) to the apex are summed using volume = area × thickness to compute LV end-diastolic volume (LVEDV) and LV end-systolic volume (LVESV); in the example, LV EDV = 41 mL + 41 mL + 38 mL + 34 mL + 28 mL + 19 mL + 5 mL = 206 mL and LV ESV = 0 mL + 30 mL + 27 mL + 24 mL + 18 mL + 3 mL + 0 mL = 102 ml; this methodology requires no geometric assumptions.

---

### Improved prediction of protein-protein interactions using alphaFold2 [^936b4ccc]. Nature Communications (2022). High credibility.

MSA block diagonalization

In addition to the default AF2 MSA, we generated an additional MSA by simply concatenating diagonally MSAs generated independently from each of the two chains. These MSAs were constructed by running HHblitsversion 3.1.0 against uniclust30_2018_08with these options:

The concatenation is done by joining side-by-side the two input chains; then sequences from one MSA are added, aligned to the corresponding input chain. Each sequence in the MSA is then elongated with gaps (on the right side if it is the left sequence MSA or the other way around), to reach the length of the two concatenated input chains. The process is then repeated for the other input chain MSA to complete the block diagonalization.

Paired MSA generation

In addition to the block diagonalization MSAs, we used a "paired MSA", constructed using organism information, where sequences are matched based on their organism origins, (Fig. 6). The rationale behind using a paired MSA is to identify inter-chain co-evolutionary information. An unpaired MSA has a limited inter-chain signal since the chains are treated in isolation.

The organism information was, using the OX identifier, extracted from the two HHblits MSAs. Next, all hits with more than 90% gaps were removed. From all remaining hits in the two MSAs, the highest-ranked hit from one organism was paired with the highest-ranked hit of the interacting chain from the same organism. Pairing the correct sequences should result in MSAs containing inter-chain co-evolutionary information.

Number of effective sequences (Neff)

To estimate the information in each MSA, we clustered sequences at 62% identity, as described in a previous study. The number of clusters obtained in this way has been used to indicate a N eff value for each MSA.

Unaligned FASTA sequences were extracted from the three AF2 default MSAs. Obtained sequences were processed with the CD-HIT softwareversion 4.7 using the options:

We calculated the Neff scores separately for paired and AF2 MSAs.

---

### Deep neural networks using a single neuron: folded-in-time architecture using feedback-modulated delay loops [^5fd7166a]. Nature Communications (2021). High credibility.

It has been shown that dynamic sparsity, can outperform dense networks and, fundamentally, Fit-DNNs are intrinsically compatible with certain kinds of sparsity. However, in our approach, removing or adding a delay loop would change an entire diagonal in the hidden weight matrices. Therefore, sparsity training algorithms such as those discussed in refs. and related works are not directly applicable to the Fit-DNN. Our preliminary tests have shown that removing the weights of a diagonal at the same time disturbs the previous training too much, so the method fails. Nevertheless, we expect that it is possible to find a suitable method to optimize the choice of delays. Therefore, further investigation of specific sparsity training methods for the Fit-DNN would be very welcome. One candidate for such a method could be pruning by slowly fading diagonals that contain weaker connections on average.

Even with a fixed sparse connectivity, we can perform image classification using only a single dynamical neuron. This case, in particular, highlights one of the most exciting aspects of the Fit-DNN architecture: many hardware implementations of DNNs or related systems have suffered from the large amount of elements that need to be implemented: the active neurons as well as the connections with adjustable weights. The Fit-DNN overcomes both of these limitations; no matter how many neurons are functionally desired, physically we only require a single one. Even though we advocate for sparse connectivity in this paper, a fully connected DNN would only require a linear scaling of the number of delay loops with the number of nodes per layer N. This represents a major advantage as compared to directly implemented networks, where the number of connections grows quadratically. Thus, where it is acceptable to use sparse networks, increasing the number of layers L or the number of nodes per layer N for the Fit-DNN only requires more time, but not more hardware elements.

---

### Mean-field theory of random close packings of axisymmetric particles [^90ce5be7]. Nature Communications (2013). Medium credibility.

Finding the optimal random packing of non-spherical particles is an open problem with great significance in a broad range of scientific and engineering fields. So far, this search has been performed only empirically on a case-by-case basis, in particular, for shapes like dimers, spherocylinders and ellipsoids of revolution. Here we present a mean-field formalism to estimate the packing density of axisymmetric non-spherical particles. We derive an analytic continuation from the sphere that provides a phase diagram predicting that, for the same coordination number, the density of monodisperse random packings follows the sequence of increasing packing fractions: spheres < oblate ellipsoids < prolate ellipsoids < dimers < spherocylinders. We find the maximal packing densities of 73.1% for spherocylinders and 70.7% for dimers, in good agreement with the largest densities found in simulations. Moreover, we find a packing density of 73.6% for lens-shaped particles, representing the densest random packing of the axisymmetric objects studied so far.

---

### Effects of effective stereotactic radiosurgery for brain metastases on the adjacent brain parenchyma [^f492b163]. British Journal of Cancer (2020). Medium credibility.

Interestingly, NAA values correlate positively in all three locations (r = 0.7); for example, when the value at the contrast-enhancing part is significantly lower than at the opposite side at a certain time point, it is the same for the first and the second ring (Fig. 4). This also applies to a lesser degree to Cr (r = 0.35). In the case of Cho, the enhancing part behaves differently than the respective rings (r = −0.01). Cho and Cr develop in a similar way and interact positively for the core of the lesion (r = 0.49) and the second ring (r = 0.42), while NAA develops independently of all other values.

Fig. 4
Correlation matrix for N-acetyl-aspartate (NAA) of the core, the 1st and the 2nd ring.

The main diagonal displays the density function of the normalised values of NAA of each localisation. In the cells above the main diagonal, correlation coefficients and in the remaining cells the pairwise scatterplots are created.

ADC of the entire lesion and of the adjacent parenchyma was constantly elevated (P < 0.001) (Fig. 2c) compared to the contralateral healthy brain. Interestingly, even in the four patients without residual changes on morphological MRI, the ADC was elevated at the site where the lesion was treated.

rCBV in the entire lesion (P < 0.001) and in the contrast-enhancing rim (P < 0.001) increased significantly, as did CBF in the contrast-enhancing rim (P = 0.009). rCBV showed a further significant increase in the entire lesion (P = 0.036) and the contrast-enhancing rim (P = 0.044) during the observation period. The perfusion parameters of the adjacent parenchyma remained normal throughout the observation time.

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

### Relative, local and global dimension in complex networks [^59592537]. Nature Communications (2022). High credibility.

It is then natural to define the local dimension of a node i by averaging the relative dimension of the nodes displaying a peak in their transient responses relative to i before a given time τ aswhereis the indicator function. Whilst the local dimension can be likened to a measure of centrality, it also directly captures the dimension of the local embedding space. In Fig. 1 c we observe the increasing effect of the boundaries on local dimension as we increase the scale. Near the centre of the line, and when considering nearby nodes (at short scales), one can expect to estimate a dimension near 1, or equivalently 2 for the grid shown in Fig. 1 d. We observe in Fig. 1 c a central region withthat becomes increasingly smaller as scale τ increases; at short scales, the central region is insensitive to the boundaries since the diffusion has not yet reached them. This 'boundary insensitive central region' collapses at τ = 1 (corresponding to the spectral gap of the graph) when all nodes have aggregated information about the boundaries of the line graph.

Finally, we can define a graph measure of dimension by averaging the local dimensions across multiple scales to obtain the global dimensionstill dependent on τ. In Fig. 1 e we display the global dimension (as a ratio to the expected Euclidean dimension) for the line and grid graphs and their periodic equivalents (the circle and sphere graphs respectively).

Whilst the periodic equivalents do not contain boundaries, they are still constrained to a compact space that will introduce topological effects, e.g. on a periodic graph the diffusion will interact with itself at the opposite side to the initial condition. We first notice that the non-periodic graphs display a maximum in global dimension, likely when the effect of the boundaries is lowest. In contrast, the periodic graphs do not exhibit a peak of the same magnitude suggesting that the topological effect of a compact space has less impact on the global dimension than the presence of a boundary.

---

### Shape morphing of plastic films [^835f8daf]. Nature Communications (2022). High credibility.

Through discrete peeling of the film belt, local curvature can be programmed and thus different polygonal shapes such as triangle, quadrangle, pentagon and hexagon were also obtained by simply arranging the adhesive layers with predetermined widths and intervals according to the interior angles and side lengths of the targeted shape and peeling the film under the according parameters (Fig. 3e and Supplementary Movie 7). Taking right triangle with an interior angle of 60° and shortest side of 10 mm and the 80 μm thick PTFE film at a peeling angle of 180° as an example, the diameter of the peeled film, d is ~2 mm and thus the widths of adhesive tapes (w a = (180 - θ)π d /360, θ is the interior angle) are 2.62 mm, 1.57 mm and 2.09 mm for interior angles of 30°, 90°, and 60°, respectively and intervals are 17.3, 10 and 20 mm, respectively (Fig. 3e, left). When peeling the film at peeling angle of 180°, the default right triangle was obtained (Supplementary Movie 7). Furthermore, complex 3D structures can be designed and fabricated through a multistep peeling process. For example, a two-step peeling process with orthogonal peeling directions and opposite curling directions can form hyperboloids (Fig. 3f and Supplementary Movie 8). In step I, a PTFE film (4 cm × 2 cm) was attached on two separated adhesive tapes (1 cm × 2 cm with an interval of 2 cm) and peeled off along the red line (Fig. 3f, left); in step II, the other side of the PTFE film was adhered on the adhesive tape (2 cm × 2 cm) and peeled off along the blue line with different peeling angles for the hyperboloids and semi-hyperboloids, before which the parts adhered in the first step were cut into parallel strips along their curling direction. More complex final 3D geometries can also be programmed by designing the layout of the 2D precursors and peeling them along the default routes (adhered regions, peeling direction, and peeling angle). Using this method, we obtained seventeen highly complex 3D geometries from ten 2D precursors and remarkably good agreement between experimental results and FEA predictions further verified the versatility of this shape-morphing strategy and the accuracy of the models (Fig. 4). Apart from the polymer films, the peeling-induced shape morphing strategy is also applicable to other materials capable of plastic deformation, such as metals (copper, silver, aluminum, nickel, titanium, and iron), semiconductor polymer films (poly(3-hexylthiophene-2,5-diyl), P3HT), filter paper, and composite films ranging from centimeter to micrometer (Supplementary Fig. 18).

---

### Biomechanical evaluation of double-strand (looped) and single-strand polyamide multifilament suture: influence of knot and suture size [^ee70ce2b]. Hand (2015). Low credibility.

Background

Flexor tendon repair in zone II remains a vexing problem. Repair techniques have been developed to strengthen and optimize the number of core strands crossing a repair. A polyamide looped suture doubles the number of core strands for every needle path. This simplifies repairs, but the knot remains a potential weakness. The purpose of our study was to create a biomechanical model used to evaluate the bulky knot of a looped suture as it may be weaker, resulting in greater deformation.

Methods

Using machined steel rods to hold our suture constructs, we compared four different knot configurations using looped and non-looped sutures in 3–0 and 4–0 varieties using a four-core strand technique. The constructs were tested under increased cyclic loading recording both forces applied and suture construct lengthening ("clinical gapping") and ultimate breaking strength.

Results

During continuous periods of cyclic loading, we measured permanent deformation and ultimate breaking strength. Permanent deformation results when there is no recoverable change after force removal defined as a permanent rod separation (or gapping) of 2 mm. Four-strand 3–0 and 4–0 looped sutures failed at 39.9 and 27.1 N faring worse than a four-strand non-looped suture which reached a rod separation of 2 mm at 60.7 and 41.3 N. The ultimate breaking strength demonstrated absolute failure (construct rupture) with the 3–0 looped suture breaking at the knot at 50.3 N and the non-looped suture at 61.5 N. For the 4–0 suture, these values were 32.4 and 41.76 N.

Conclusion

Within the constraints of this model, a looped suture fared worse than a non-looped suture especially when comparing 4–0 and 3–0 sutures. However, two-knot 3–0 looped suture constructs did resist the force generally accepted as occurring with early non-resistive tendon motion protocols, while two-knot 4–0 looped suture constructs did not.

Clinical Relevance

This paper provides a description of a model to evaluate various suture materials and knot strengths in isolation of the tendon itself. This allowed us to evaluate mechanical differences between looped and non-looped sutures for polyamide, which are commonly used in flexor tendon repair. These differences between sutures may impact choices for a suture type selected for these repairs.

---

### A compendium of genetic regulatory effects across pig tissues [^de1981b8]. Nature Genetics (2024). High credibility.

Fig. 2
molQTL discovery.

a, Pearson's r between the proportion of detectable eGenes and sample size across 34 tissues. b, Proportions of detectable eMolecule (blue) and specific molQTL (red) for different molecular phenotypes in 34 tissues. * indicates the interaction of cis -eQTLs (ieQTL). Cell type* and Ancestry* are for cell-type ieQTL (cieQTL) and breed/ancestry ieQTLs (bieQTL), respectively. c, Distribution and the average number of independent cis -eQTL per gene. Tissues (x axis) are ordered by increasing sample size. The color key is the same as in a. d, Number of eGenes (triangle) and average number of independent cis -eQTL (square). e, The comparison of cis - h 2 (blue) and median expression levels (red) of genes with different numbers of detectable independent cis -eQTL across tissues. The top labels show nominal P values (uncorrected for multiple testing) from one-sided Student's t tests. f, Internal validation of cis -eQTL. Bars represent Pearson's r of the normalized effects of cis -eQTL between validation and discovery groups. Points represent the π 1 statistic measuring the replication rate of cis -eQTL. g, Spearman's ρ of effect sizes (aFC in log 2 scale) between cis -eQTL and ASE at matched loci (n = 4,417) in muscle. h, A cis -eQTL (rs331530041) of EMG1 in muscle is shared across eight ancestry groups. i, Spearman's correlation of the cis -eQTL effects between eight breeds of the muscle (left) and between muscle and other 33 tissues (right). The P value is obtained from a two-sided Wilcoxon rank-sum test. j, Proportion of bieQTL that are validated with the ASE approach. The number of validated bieQTLs out of the total number of bieQTLs tested is shown to the right of each bar. k, Effect of eVariant (rs344529295) of GRHPR interacted with the Duroc ancestry enrichment in muscle. The two-sided P value is calculated by the linear regression bieQTL model. The lines are fitted by a linear regression model using the geom_smooth function from ggplot2 (v3.3.2) in R (v4.0.2). l, Proportion of cieQTL that are validated by the ASE approach. m, Effect of eVariant (rs344431919) of FGD2 interacted with monocyte enrichment in blood. The two-sided P value is calculated by the linear regression cieQTL model. The lines are fitted using the same method as in k. aFC, allelic fold change.

---

### Nuclear fission modes and fragment mass asymmetries in a five-dimensional deformation space [^6c6f5020]. Nature (2001). Excellent credibility.

Nuclei undergoing fission can be described by a multi-dimensional potential-energy surface that guides the nuclear shape evolution — from the ground state, through intermediate saddle points and finally to the configurations of separated fission fragments. Until now, calculations have lacked adequate exploration of the shape parameterization of sufficient dimensionality to yield features in the potential-energy surface (such as multiple minima, valleys, saddle points and ridges) that correspond to characteristic observables of the fission process. Here we calculate and analyse five-dimensional potential-energy landscapes based on a grid of 2,610,885 deformation points. We find that observed fission features — such as the distributions of fission fragment mass and kinetic energy, and the different energy thresholds for symmetric and asymmetric fission — are very closely related to topological features in the calculated five-dimensional energy landscapes.

---

### Recommendations for cardiac chamber quantification by echocardiography in adults: an update from the American Society of Echocardiography and the European association of cardiovascular imaging [^08aae061]. Journal of the American Society of Echocardiography (2015). Medium credibility.

Left atrial (LA) linear and area measurements — the most widely used linear dimension is the anteroposterior (AP) measurement in the parasternal long-axis using M-mode or, preferably, two-dimensional echocardiography (2DE), but the AP linear dimension should not be used as the sole measure of LA size; LA area can be planimetered in apical four- and two-chamber views, and optimal contours should be obtained while avoiding foreshortening.

---

### Danger zone assessment in small-sided recreational football: providing data for consideration in relation to COVID-19 transmission [^11855778]. BMJ Open Sport & Exercise Medicine (2021). High credibility.

During the COVID-19 pandemic, physical inactivity has increased, and a wide range of sporting activities locked down, with possible long-term implications for public health. Football is the most popular sport worldwide, and recreational football training leads to broad-spectrum health effects. Football is, however, deemed a contact sport with frequent close contact important to consider during COVID-19 pandemic.

Objectives

This study investigated time spent with close contact (danger zone (DZ) within 1.5 m), number of contacts and time per contact, and compared game formats in recreational small-sided football games for young and adult male football players.

Methods

Movement analyses were performed on 10 Hz Global Positioning System (GPS) data collected during various small-sided football games prior to the COVID-19 outbreak.

Results

Time spent in the DZ was 4.3–7.9 s/h per per cent infected players, corresponding to 34.3–114.8 s/h if one player was infected. Number of contacts with one infected player was 23.5–87.7 per hour, with an average contact time of 1.1–1.4 s, and a total number of contacts of 311–691 per hour with all players. 53%-65% of all contacts were shorter than 1 s and 77%-85% shorter than 2 s. Trivial to small effects were found for number of participants and area per player, whereas standard of play and playing with/without boards had no effect.

Conclusion

This study demonstrated that during small-sided football limited time is spent within DZ and that player contacts are brief. Recreational football may therefore more appropriately be deemed as sporting activity with brief, sporadic contact.

---

### EAE / ASE recommendations for image acquisition and display using three-dimensional echocardiography [^c42d2a11]. Journal of the American Society of Echocardiography (2012). Medium credibility.

Three-dimensional stress echocardiography — orientation and display: Conventional 2D stress echocardiograms are usually analyzed side by side, and new 3D stress software allows the same multiview format; it is recommended to use this display methodology when available. There is a limit to the number of views that can be simultaneously displayed on a monitor, and an alternative is to select one view and display it simultaneously with the same view obtained at other stages.

---

### Expert gaze as a usability indicator of medical AI decision support systems: a preliminary study [^a4e9fb8e]. NPJ Digital Medicine (2024). Medium credibility.

Fig. 3
Visual attention to relevant regions (AOIs) of the AI support interface.

a is a depiction of the stimuli used in the experiment, with the bitewing being in the center surrounded by user interface elements with the right-side elements related to the AI support, which were not visible in the no AI condition. b shows the average fixation count for dentists viewing with (light blue) and without AI (dark blue). The black error bars represent a confidence interval at 95%.

Scanpath transitional behavior

We also looked at experts' gaze transitions between AOIs when they have the option for AI support. Figure 4 reports the total number of transitions from each AOI to another AOI shown in Fig. 3 a. Higher transitions are represented by warmer colors from one AOI to another AOI read in the manner of from left to bottom. With the AI support option, dentists had the highest gaze transitions from the AI list of findings to the bitewing (912 transitions) and the second-highest transitions being from bitewing back to the AI list of findings (896 transitions). The map of the teeth and bitewing also had a high number of transitions to and from. In general, fewer transitions were apparent when experts had no option for AI support, though interesting enough, the highest transitions were similar to the AI support condition, but at a much lower magnitude: 131 transitions from AI findings to bitewing and 127 transitions from bitewing to the AI findings. Without the AI support option, transitions to and from the tooth map were much less frequent, as the map was empty.

Fig. 4
Gaze transitional behavior between AOIs with and without AI support.

As we are interested in gaze transitions from one AOI to another, we exclude gaze transitions within an AOI as visualized by missing values along the diagonal. The warmer color tiles represent a higher number of gaze transition from one AOI to another AOI, read in the manner of from left to bottom.

---

### High-dimensional topographic organization of visual features in the primate temporal lobe [^ad111b4d]. Nature Communications (2023). High credibility.

Clustering analysis using a Gaussian mixture model

We fitted 25D feature map of each monkey with a Gaussian mixture model using the expectation-maximization algorithm (Matlab's fitgmdist function). We constrained the covariance matrix for each component to be diagonal, resulting in 50 parameters per component (25 for the mean, 25 for the variances). We further regularized the covariance matrix by adding a constant (10⁻⁵) to the diagonal. The number of components (= clusters) was predefined, and the procedure was repeated 500 times for each number of clusters between 2 and 30.

To find the optimal number of clusters, we evaluated the Bayesian information criterion:where L is the log-likelihood of the model, N is the number of squares and M is the number of parameters in the model, that is, M = 51 C -1 where C is the number of clusters and the contributions arose from means, variances, and mixture proportions (which have to add to 1). For each number of clusters, BICs were averaged across 500 repetitions of clustering.

Selecting preferred images of a specific brain region

The 25D feature selectivity of a specific brain region was first obtained using the methods described above (Quantification of feature selectivity to object-space stimuli). Then we assumed the response of this region to an image is a linear combination of its 25 coordinates. We usedto denote the weighting function. 25D coordinates were then averaged for all images in each block and the difference between "positive" and "negative" blocks was computed for each IC.was used to denote thecoordinate of the difference for theIC. Then we have:whereis the 25D selectivity measured using fMRI.

Using linear algebra, could be determined by inverting the matrix:

Then we used the same approach as described above (Selection of representative images for 25D feature space) to select representative images for the interested brain region, by sorting the angles between the 25D coordinates of all images and. To select the representative images for different subregions resulting from the clustering analysis (Fig. S5j), an additional criterion was added: the angle between the 25D coordinate of the selected image and the average feature of the interested cluster needed to be the smallest of all clusters.

---

### Progress towards health equity in Vietnam: evidence from nationwide official health statistics, 2010–2020 [^42adb639]. BMJ Global Health (2024). High credibility.

The concentration curve is used to represent the relative inequality between groups in natural order. The independent variable is the cumulative percentage of regions sorted by economic level, with a value range of (0,1). The dependent variable is the cumulative percentage of observed indicators for the corresponding provinces, with a value range of (0,1). If the health status of provinces with different economic levels is equal, the concentration curve is on the diagonal. If the health indicators in low-income provinces have lower values, the concentration curve is located below the diagonal, and if they have higher values, the concentration curve is located above the diagonal. The further the curve is from the diagonal, the more unequal the values. The Concentration Index is a quantification of the concentration curve, the absolute value of which is twice the area between the concentration curve and the diagonal, with the Concentration Index values in a range of (–1,1). If the health status related to the economic level is equal, the Concentration Index value is 0. When the concentration curve is above the diagonal, the Concentration Index value is negative, indicating that the indicator is more inclined towards impoverished provinces. When the concentration curve is below the diagonal, the Concentration Index value is positive, indicating that the indicator is more inclined towards affluent provinces. The Concentration Index formula is as follows:

where h is the health indicator value for each province, μ is the average for each province, and r is the cumulative percentage of provinces sorted by per capita income or incidence of poverty.

Tools provided by the International Center for Equity in Health were used to analyse the development trends of absolute health differences at the regional level and to identify vulnerable areas, and the TI was used to find regions with significant internal differences. The TI describes inequalities that do not exist in natural order groups and can be decomposed into different regions by measuring intragroup and intergroup differences and their respective contributions to the overall difference. Overall differences can be decomposed into intragroup and intergroup differences, as shown below:

whereis the intergroup difference, is the intragroup difference, G is 6, representing the number of Vietnam's socioeconomic subregions, is the number of provinces in the g th region, is the proportion of the absolute value of the health indicators of province i in the region andis the proportion of health indicator values in the g th region at the national level.

---

### Enhancing detection of topological order by local error correction [^a888c506]. Nature Communications (2024). High credibility.

Computing the probabilities requires contracting a 2D tensor network (Fig. 6), which is in general # P -hard. In practice, however, the states we encounter have finite correlation length, and the computation becomes remarkably efficient throughout much of the phase diagram. In particular, we work on a strip of finite height L x and infinite length L y, and introduce boundary matrix product states (MPS) to efficiently capture the effect of the environment — that is, the sites different from the one currently being sampled. Because singular-value decomposition truncation is used at each step to prevent the bond dimension of the boundary MPS from growing exponentially, the method is approximate; however, we only discard singular values < 10⁻⁸, so truncation errors are insignificant. Details of the boundary conditions and contraction ordering are discussed in the Supplementary Information.

Fig. 6
PEPS sampling algorithm.

Expectation values are computed with respect to both(back) and(front). a Tracing, or averaging over measurement outcomes can be done by contracting the physical indices, and is needed to compute marginal probabilities. b To compute the probability of a particular Z basis measurement, the physical index is assigned a particular value a b. c We can efficiently contract a 2D PEPS tensor network on an infinite strip of finite height, by using a left and right boundary MPS (only top four rows shown). The probability distribution for projective measurements on a particular site, e.g. x y = 11, can then be computed efficiently. d Once an entire column has been sampled, the measurement-dependent MPO can applied to the boundary MPS. Although performing this contraction exactly causes the bond-dimension to grow rapidly, away from phase boundaries, finite bond dimension is sufficient for accurate simulation. See Supplementary Information for more details.

In our simulations, we choose L x = 300 unit cells and sample 1000 columns, giving us access to very large snapshots with 600,000 qubits. To minimize boundary effects, we compute observables supported on sites at least 30 unit cells away from the boundaries. Near the phase boundaries, the bond dimension (entanglement) of the boundary MPS becomes large due to the large correlation length, which increases the computational demands for sampling (gray data points in Fig. 2 g). We numerically confirm this phase boundary with an independent calculation (see Supplementary Information).

---

### Medial packing and elastic asymmetry stabilize the double-gyroid in block copolymers [^4ba32a38]. Nature Communications (2022). High credibility.

Triply-periodic networks are among the most complex and functionally valuable self-assembled morphologies, yet they form in nearly every class of biological and synthetic soft matter building blocks. In contrast to simpler assembly motifs – spheres, cylinders, layers – networks require molecules to occupy variable local environments, confounding attempts to understand their formation. Here, we examine the double-gyroid network phase by using a geometric formulation of the strong stretching theory of block copolymer melts, a prototypical soft self-assembly system. The theory establishes the direct link between molecular packing, assembly thermodynamics and the medial map, a generic measure of the geometric center of complex shapes. We show that "medial packing" is essential for stability of double-gyroid in strongly-segregated melts, reconciling a long-standing contradiction between infinite- and finite-segregation theories. Additionally, we find a previously unrecognized non-monotonic dependence of network stability on the relative entropic elastic stiffness of matrix-forming to tubular-network forming blocks. The composition window of stable double-gyroid widens for both large and small elastic asymmetry, contradicting intuitive notions that packing frustration is localized to the tubular domains. This study demonstrates the utility of optimized medial tessellations for understanding soft-molecular assembly and packing frustration via an approach that is readily generalizable far beyond gyroids in neat block copolymers.

---

### Medial packing and elastic asymmetry stabilize the double-gyroid in block copolymers [^f77b759f]. Nature Communications (2022). High credibility.

Fig. 2
Subdomain tessellations for strong-segregation chain packing.

Schematic of chain packing within a variably-shaped morphology is shown in (a) where z labels local extension of blocks from the IMDS. b Shows a (volume balanced) tessellation of the nodal region of DG, generated via the medial SST construction. c Shows a sequence of medial SST geometries (at fixed composition f = 0.3) highlighting lateral spreading of terminal webs achieved via parametric variation of DG generating surfaces (as described in the text).

Per Eq. (2), maximizing entropy of component blocks is equivalent to minimizing second-moments of volume measured relative to the IMDS. Chain packing is, in this sense, a variant of the quantizer problem, which seeks tessellations that minimize the second-moment of distance from a set of generating points, generalized to measure distance with respect to generating surfaces. Given an IMDS shape, the medial map would provide the optimal I α for each domain considered in isolation. However, as shown in Supplementary Note 3, the medial map generically fails to satisfy the local volume balance constraint. Moreover, stable morphologies also optimize the competition between IMDS area minimization and block stretching.

To model this thermodynamic competition and test how closely physical assemblies come to realizing medial packing, we apply the following medial SST approach to DG morphologies (see Methods, Supplementary Note 3–4). In brief, our approach, summarized in Supplementary Fig. 7, uses the medial map of gyroidal surfaces to generate terminal sets (both A and B ends) from which a set of space filling chain trajectories are derived along with an IMDS consistent with the volume balance constraint for each chain trajectory, resulting in mutually compatible terminal boundaries, IMDS, and trajectories, as shown in Fig. 2 b. We then optimize the computed free energies over the variational family of generating gyroidal surfaces – corresponding to variable shapes and sizes of the terminal surfaces as shown Fig. 2 c — to determine and analyze thermodynamically preferred DG chain packing. Notably, local volume balance generally requires some measure of tilt between trajectories and the IMDS, a signature of the deviation from strictly medial packing which we return to below.

---

### Diffusion tensor subspace imaging of double diffusion-encoded MRI delineates small fibers and gray-matter microstructure not visible with single encoding techniques [^80fc0fbd]. Magnetic Resonance in Medicine (2025). Medium credibility.

3.2 MRI acquisition

All MRI data were collected with a Bruker 7T preclinical scanner using a 40‐mm quadrature coil to transmit and receive signal. A high‐resolution anatomical image was collected using a three‐dimensional (3D) T 2 ‐weighted RARE pulse sequence with 300‐micron isotropic voxel size. Both SDE and DDE diffusion‐weighted MRIs (DWIs) were collected using a 3D spin‐echo echo‐planar imaging (EPI) pulse sequence with spatial resolution of 300‐micron isotropic voxel dimensions. Multishell SDE DWIs were collected using echo time (TE)/repetition time (TR) = 41/800 ms (temporal lobe) or TE/TR = 45/800 ms (brain stem), six segments, and diffusion encoding using pulse timings of δ = 5 ms and ∆ = 25 ms with b(# directions) = 1000(32), 2000(32), and 4000(56)s/mm 2 along with two unweighted images.

For DDE, a similar 3D spin‐echo EPI pulse sequence was used to collect images in the same scan session as the SDE with TE/TR = 76/800 ms (temporal lobe) and TE/TR = 82/800 ms (brain stem), four segments, and cubic encoding (i.e. all 64 combinations of 8 PFG1 and 8 PFG2 directions defined by the vertices of a cube, over a range of the 9 b ‐value pairs b 1 / b 2 = 1000/1000, 1000/2000, 1000/4000, 2000,1000, 2000/2000, 2000/4000, 4000/1000, 4000/2000, and 4000/4000 s/mm 2). In different scans sessions, the specimens were imaged again with TE/TR = 78/400 ms, four segments, and 250‐micron isotropic resolution and using more comprehensive dodecahedral angular sampling (i.e. all 400 combinations of 20 PFG1 and 20 PFG2 directions defined by the vertices of a dodecahedron) with a range of b 1 /b 2 combinations (1200 DWIs) with b 1 / b 2 = 1000/1000, 1000/2000, and 2000/2000 s/mm 2. These encoding schemes are shown in Figure 1. For all DDE scans and for both specimens, the first and second PFG blocks had identical timings with δ = 5 ms, ∆ = 25 ms, and mixing time τ m = 16 ms between them.

---

### Recommendations for cardiac chamber quantification by echocardiography in adults: an update from the American Society of Echocardiography and the European association of cardiovascular imaging [^79b1194c]. Journal of the American Society of Echocardiography (2015). Medium credibility.

Echocardiographic assessment of right atrial (RA) size — volume by 2D describes that "2D volumetric measurements are usually based on tracings of the blood-tissue interface on the apical four-chamber view" and that "At the tricuspid valve level, the contour is closed by connecting the two opposite sections of the tricuspid ring with a straight line". It adds, "Volumes can be computed by using either the single plane area-length" or "the disks summation technique", performed in a "2D view". The listed advantage is "More representative of actual RA size than linear dimensions", while limitations include "Assumes a symmetrical shape of the cavity", "Single plane volume calculation may be inaccurate since it assumes that RA enlargement is symmetrical", and "Normal values not well established".

---

### Dual communities in spatial networks [^80bf37aa]. Nature Communications (2022). High credibility.

Creation of dual graphs: planar networks

In this manuscript, we mostly restrict our analysis to planar, connected graphs. A graph G = (V, E) with vertex set V and edge set E is called planar if it may be drawn in the plane without two edges crossing. For a plane graph G, it is straightforward to establish a duality to another graph, referred to as the plane dual or simply dual graph and denoted as G *. The dual graph is constructed using the cycles of graph G where a cycle is defined to be a path that starts and ends in the same vertex consisting of otherwise distinct vertices. For a graph with M edges and N nodes, these cycles form the graph's cycle space of dimension N ✱ = M − N + 1. A particular basis of this space is given by the faces of the plane embedding, such that the dual graph G ✱ = (V *, E *) has a vertex corresponding to each face. Two dual verticesandare connected by a dual edgeif the two corresponding cycles share an edge. For a weighted graph, the edge weight of the dual edge is chosen to be the inverse of the corresponding edge shared by the two cycles. Furthermore, we adopt the following convention; if two cycles share k edges e 1. e k with weights w 1. w k, we lump them together into a single dual edge e * with edge weightthus avoiding multi-edges in the dual graph and refer to this model as the reduced dual graph. Note that the definition of the edge-cycle incidence matrix C needs to be adjusted for the reduced dual graph.

Creation of dual graphs: non-planar networks

For non-planar networks, the basis of the cycle space may no longer be uniquely determined based on the graph's embedding. Different basis choices result in different dual graphs. When calculating the dual graph of the non-planar European topology shown in Fig. 5 f–g, we used the graphs' minimum cycle basis to create the dual graph.

Hierarchical decomposition of dual graph

We assign m hierarchy levels based on repeated spectral bisection of the dual graph using the following procedure:
Assign dual communities to the graph by making use of the Fiedler vectorof the dual graph G *
Identify the edges that lie on the boundary between the two communities by checking for edges in the primal shared by faces corresponding to dual nodes of both communities
Remove the boundary edges from the graph thus creating two primal subgraphs G 1 and G 2
Repeat the process m times

---

### Expert panel on integrated guidelines for cardiovascular health and risk reduction in children and adolescents: summary report [^a7f90d07]. Pediatrics (2011). Medium credibility.

Figure 2–3 — Atherosclerosis maps of the right coronary artery show PDAY males by age 15–24 and 25–34 stratified by number of risk factors (0, 1, 2, 3+), with sample sizes for 15–24 of n = 149, n = 219, n = 93, and n = 31 and for 25–34 of n = 87, n = 208, n = 172, and n = 59, respectively; these computerized images are prevalence maps of fatty streaks and raised lesions with color intensity reflecting lesion density and grade, and severity/extent increased as the number of risk factors increased.

---

### Efficient classical sampling from gaussian boson sampling distributions on unweighted graphs [^7b2529aa]. Nature Communications (2025). High credibility.

Gaussian Boson Sampling (GBS) is a promising candidate for demonstrating quantum computational advantage and can be applied to solving graph-related problems. In this work, we propose Markov chain Monte Carlo-based algorithms to sample from GBS distributions on undirected, unweighted graphs. Our main contribution is a double-loop variant of Glauber dynamics, whose stationary distribution matches the GBS distribution. We further prove that it mixes in polynomial time for dense graphs using a refined canonical path argument. Numerically, we conduct experiments on unweighted graphs with 256 vertices, larger than the scales in former GBS experiments as well as classical simulations. In particular, we show that both the single-loop and double-loop Glauber dynamics improve the performance of original random search and simulated annealing algorithms for the max-Hafnian and densest k-subgraph problems up to 10 ×. Overall, our approach offers both theoretical guarantees and practical advantages for efficient classical sampling from GBS distributions on unweighted graphs.

---

### Trametinib (Mekinist) [^44317672]. FDA (2025). Medium credibility.

The dosage of trametinib dimethyl sulfoxide PO for treatment of melanoma in adults with BRAF V600E or V600K mutation (unresectable or metastatic) is 2 mg PO daily until disease recurrence or unacceptable toxicity

---

### Combinatorial summation of feynman diagrams [^42481276]. Nature Communications (2024). High credibility.

Feynman's diagrammatic series is a common language for a formally exact theoretical description of systems of infinitely-many interacting quantum particles, as well as a foundation for precision computational techniques. Here we introduce a universal framework for efficient summation of connected or skeleton Feynman diagrams for generic quantum many-body systems. It is based on an explicit combinatorial construction of the sum of the integrands by dynamic programming, at a computational cost that can be made only exponential in the diagram order on a classical computer and potentially polynomial on a quantum computer. We illustrate the technique by an unbiased diagrammatic Monte Carlo calculation of the equation of state of the 2DSU(N) Hubbard model in an experimentally relevant regime, which has remained challenging for state-of-the-art numerical methods.

---

### A soft photopolymer cuboid that computes with binary strings of white light [^998e393d]. Nature Communications (2019). High credibility.

Fig. 4
Output generated by pairs of two-bit strings. a Expected and corresponding b experimental results of the 16 (2² × 2²) patterns generated at the polymer cuboid output (yz plane) by all combinations of a pair of 2-bit binary strings introduced along the y and z axis. Each output pattern comprises different combinations of carrier configurations 0D (red), 1DH (blue), 1DV (green), and 2D (gray), which can be quantified through c corresponding FFT spectra of experimental results. (Bits 0 and 1 are represented by white and black bars, respectively; scale bar in b = 200 μm; in b, c, blue (minimum) to red (maximum) intensity scales are provided.)

Most significantly, its quaternary output enables the system to perform two fundamental operations of binary arithmetic — addition and subtraction (Fig. 5). The scheme in Fig. 5a depicts the addition of two binary strings, 10 and 01, input, respectively, through Beams Y and Z; in all cases, MI of uniform Beam X generates carriers throughout the cuboid. The place value of the binary strings increases from right to left for Beam Y and from top to bottom for Beam Z. The strings divide the cuboid into voxels, each of which contains 0, 1, or 2 encoder populations that operate on carriers and generate a unique output. The sum in binary form is read from the antidiagonal of the output; each element is the result of the operations of encoders with the same place value on the carriers. To interpret results, we assign a value of 0 to configuration 0D, 1 to 1DH and 1DV, and 0 carry 1 (0C1) to 2D. In Fig. 5a, the addition of 01 and 10 generates an antidiagonal of two elements comprising the 1DV and 1DH configurations, respectively. This correctly represents a sum of 11. For the addition of 0 1 and 0 1 shown in Fig. 5b, the first element of the antidiagonal reads "0C1" and the carried value is read from the off-diagonal as 1. Because the second element of the antidiagonal is 0, the sum is 10. Experimental examples of addition in the 2² × 2² system (Fig. 4) are tabulated in Fig. 5c and classified according to the absolute value of the sum. Because the addition of different pairs of numbers can have the same sum, the 10 tabulated patterns correspond to four unique results. Interestingly, although addition is commutative, our system has the ability to distinguish between the 1DH and 1DV configurations, which both correspond to "1". This allows the identity of the input binary strings to be elucidated from the result.

---

### Trametinib (Mekinist) [^7f25adc1]. FDA (2025). Medium credibility.

The dosage of trametinib dimethyl sulfoxide PO for treatment of solid tumors in adults with BRAF V600E mutation (unresectable or metastatic, progressed following prior treatment, no satisfactory alternative therapy) is 2 mg PO daily until disease recurrence or unacceptable toxicity

---

### Recommendations for cardiac chamber quantification by echocardiography in adults: an update from the American Society of Echocardiography and the European association of cardiovascular imaging [^6a46fa06]. Journal of the American Society of Echocardiography (2015). Medium credibility.

Echocardiographic left ventricular (LV) volumes — Volume measurements are "usually based on tracings of the blood-tissue interface in the apical four- and two-chamber views", with the contour at the mitral valve level "closed by connecting the two opposite sections of the mitral ring with a straight line", and LV length "defined as the distance between the middle of this line and the most distant point of the LV contour". Techniques include biplane disk summation and area-length; biplane disk summation advantages are "Corrects for shape distortions" and "Less geometrical assumptions compared with linear dimensions", with limitations "Apex frequently foreshortened", "Endocardial dropout", and "Blind to shape distortions not visualized in the apical two- and four-chamber planes". For area-length, the advantage is "Partial correction for shape distortion", with limitations "Apex frequently foreshortened", "Heavily based on geometrical assumptions", and "Limited published data on normal population".

---

### Shadows of anyons and the entanglement structure of topological phases [^5e2aae4c]. Nature Communications (2015). Medium credibility.

Discussion

We have illustrated how the eigenvalue spectrum of the one-dimensional (quantum) transfer matrix provides a holographic description of the dispersion relations of elementary excitations in the full two-dimensional quantum system. This holds true even in systems with topological order, where the elementary excitations are anyons. The presense of topological order gives rise to particular (virtual) symmetries of the transfer matrix. By carefully studying the manifestation of these symmetries in the fixed-point subspace, we were able to relate the different topological sectors of the physical excitations to corresponding topologically non-trivial symmetry sectors (domain walls) at the virtual level. This shows, in particular, that the existence of anyon excitations requires a particular type of symmetry breaking of the doubled virtual symmetry in the fixed-point subspace of the transfer matrix, whereas topological phase transitions give rise to a fixed-point subspace with a larger or smaller degeneracy.

While these results might be reminiscent of the closely related bulk-edge correspondence observed in chiral topological phases, we would like point out the subtle differences. In the PEPS formalism, the properties of the edge states are determined by the fixed points of the transfer matrix, whereas here we explicitly consider the complete (long-distance) spectrum of the transfer matrix. In addition, the framework for characterizing topological order in PEPS using MPOs, which is of central importance for our results, has so far only been made explicit for the non-chiral string net models, and it remains to be clarified how the recently discovered chiral PEPSfit within this framework.

This technique holds a powerful potential for studying fundamental questions of topological order and topological phase transitions. While we have studied transfer matrices originating from a tensor network representation of the ground state, the results presented in this paper should generalize to the full-quantum transfer matrix obtained from representing the ground state as an imaginary time-path integral. Whereas the exact path integral representation can have a gauge theory as virtual boundary, the PEPS truncation will eliminate the gauge degrees of freedom. Correspondingly, the local order parameter measuring the symmetry breaking transitions at the PEPS virtual level will map to a string operator in the temporal direction of the full-path integral.

---

### An analytical theory of balanced cellular growth [^98f39440]. Nature Communications (2020). High credibility.

Without dependent reactants, A is a square matrix with a unique inverse A⁻¹, and x ≡ [P, a] T is the corresponding vector of independent concentrations. Multiplying both sides of the mass balance constraint (1) by A⁻¹, we obtain (Theorem 5)The right-hand side of the mass balance constraint (1) quantifies how much of each component x i needs to be produced to offset the dilution that would otherwise occur through the exponential volume increase at rate μ.quantifies the proportion of flux v j invested into offsetting the dilution of component i, and we thus name A⁻¹ the investment (or dilution) matrix; see Supplementary Fig. 1 for examples. In contrast to the mass-normalized stoichiometric matrix A, which describes local mass balances, A⁻¹ describes the structural allocation of reaction fluxes into offsetting the dilution of all downstream cellular components, carrying global, systems-level information.

From the kinetic equation (Eq. (3)), p j = v j / k j (a), and inserting v j from the investment equation (Eq. (4)) giveswhere ∑ i sums over the total protein and individual reactant concentrations (Theorem 6). Substituting these expressions into the total protein sum (Eq. (2)) and solving for μ results in the growth equation (Theorem 7)

As detailed in "Methods" (Theorems 5–7), a corresponding result also holds for BGSs with dependent reactants. Thus, for any active matrix A with full column rank (in particular for all active matrices of EGSs) and for any corresponding concentration vector x, there are unique and explicit mathematical solutions for the fluxes v, individual protein concentrations p, and growth rate μ. If μ (Eq. (6)) and all individual protein concentrations p j (Eq. (5)) are positive, the cellular state is a BGS; otherwise, no balanced growth is possible at these concentrations.

---

### Symbiosis limits establishment of legumes outside their native range at a global scale [^b1ba5e30]. Nature Communications (2017). Medium credibility.

To convert the geographic names in the ILDIS database into usable geographic coordinate data, we downloaded a shapefile containing the standardized TDWG geographic regions as polygons, then matched these polygons to ILDIS geographic names. Where TDWG polygons and ILDIS geographic names could not be matched, we used the next available polygon in the geographic hierarchy (for example, if we could not find a polygon corresponding to an area name, we used the region name instead). Moving up to the next geographic level was only necessary for less than 10% of recorded regions and did not exceed one level. Once all geographic areas were matched to polygons, we only retained those at the lowest available hierarchical scale.

Before analysis we merged any species range polygons that were touching each other and had the same introduction status, to prevent biases in the number of ranges due to finer subdivision within some areas. This way, all final polygons represent non-contiguous ranges.

We checked the accuracy of the polygon occurrences by comparing our polygon data to occurrence records in the Global Biological Information Facility (GBIF). GBIF gives higher resolution point occurrence records, but for far fewer species (1,830 species) and invasive or introduced status is not recorded for each GBIF record. We found that, on average, ILDIS polygons for each species captured 93% of GBIF points (see Supplementary Fig. 2 for some example species maps). For points that fell outside ILDIS polygons, we calculated the geographic distance to the nearest ILDIS polygon and found that most points were geographically very close to an ILDIS polygon, with no obvious bias in the distribution of geographic distances between symbiotic and non-symbiotic legumes (Supplementary Fig. 3). There was no obvious differences in the presence or number of 'unknown' introduction status polygons between symbiotic and non-symbiotic species (Supplementary Fig. 4), indicating that any ambiguities in polygon status was not different between our legume comparison groups. Together, these indicate that ILDIS geographic range data was reliable.

---

### Medial packing and elastic asymmetry stabilize the double-gyroid in block copolymers [^136613e3]. Nature Communications (2022). High credibility.

Triply-periodic networks are among the most complex and functionally valuable self-assembled morphologies, yet they form in nearly every class of biological and synthetic soft matter building blocks. In contrast to simpler assembly motifs - spheres, cylinders, layers - networks require molecules to occupy variable local environments, confounding attempts to understand their formation. Here, we examine the double-gyroid network phase by using a geometric formulation of the strong stretching theory of block copolymer melts, a prototypical soft self-assembly system. The theory establishes the direct link between molecular packing, assembly thermodynamics and the medial map, a generic measure of the geometric center of complex shapes. We show that "medial packing" is essential for stability of double-gyroid in strongly-segregated melts, reconciling a long-standing contradiction between infinite- and finite-segregation theories. Additionally, we find a previously unrecognized non-monotonic dependence of network stability on the relative entropic elastic stiffness of matrix-forming to tubular-network forming blocks. The composition window of stable double-gyroid widens for both large and small elastic asymmetry, contradicting intuitive notions that packing frustration is localized to the tubular domains. This study demonstrates the utility of optimized medial tessellations for understanding soft-molecular assembly and packing frustration via an approach that is readily generalizable far beyond gyroids in neat block copolymers.

---

### Quantifying entanglement in a 68-billion-dimensional quantum state space [^b339b52f]. Nature Communications (2019). High credibility.

Adaptive sampling algorithm

For each configuration, experimental data are stored in nodes in a quad-tree decomposition of P whose levels describe increasingly fine detail. The i th node corresponds to a square area ofat locationwith span. Nodes are sampled by placing the corresponding, one-dimensional local patterns on the DMDs and generating a coincidence histogram during acquisition time T a = 0.5 s. Coincidences C i are counted within a 1-ns coincidence window centered on the coincidence peak; accidental coincidences A i are counted in a 1-ns window displaced 2 ns from the coincidence window. Coincidence and accidental values are appended to a list each time the node is sampled. The estimated count rate, whereis a calibrated, relative fiber coupling efficiency. Optionally, A i can be subtracted from C i for accidental removal. Uncertainty is computed by assuming Poissonian counting statistics for C i and A i and applying standard, algebraic propagation of error through the calculation of the entanglement quantity (Eq. (3)).

The data collection algorithm consists of a partitioning phase followed by an iterative phase. During partitioning, the algorithm repeatedly iterates through a scan-list of leaves of the tree. Node i is considered stable when sgn(αR T − R i) is known to at least β standard deviations of certainty, where splitting threshold α (0 ≤ α ≤ 1) and stability criterion β are user-chosen heuristics. Stable nodes are no longer measured. If a node is stable and R i ≥ αR T, the node is split into four equal-sized sub-quadrants, which are initially unstable and added to the scan-list. Optionally, a maximum resolution (maximum tree depth) may be set.

The transition to the iterative phase occurs when the percentage of unstable leaves is < Γ, a user-chosen parameter. At this point, stability is ignored and all leaf nodes are scanned repeatedly and guaranteed to have the same total acquisition time. Various final stopping criteria can be used; we chose a fixed total run time. Note that heuristic parameters α, β, and γ may be changed during operation if desired. For the data shown in this manuscript, α = 0.002, β = 2, and Γ = 0.15 with a 30-h runtime.

The probability distributionis computed by uniformly distributing the estimated count rate (with or without accidental subtraction) from each leaf node across its constituent elements in, followed by normalization.

---

### As-3 [^4f47e930]. FDA (2025). Medium credibility.

Statement of idenity

ADDITIVE SOLUTION FORMULA 3 (AS-3), 250 mL

---

### The conserved microRNA miR-34 regulates synaptogenesis via coordination of distinct mechanisms in presynaptic and postsynaptic cells [^a696d247]. Nature Communications (2020). High credibility.

miR-34 plays different roles on the two sides of the synapse

Although we observed significant structural phenotypes on both sides of the synapse in miR-34 null animals, it remained possible that these defects reflected a single underlying target gene mechanism acting in either motor neurons or muscle cells. To determine the cellular source of miR-34 action for NMJ growth, we used our miR-34SP under control of cell type-specific GAL4 drivers. Interestingly, we discovered that miR-34 is required on both sides of the synapse to achieve normal bouton numbers. Expression of miR-34SP specifically in the muscle compartment with DMef2-GAL4 is sufficient to reduce NMJ growth to levels approaching the severity of ubiquitous expression of miR-34SP (Fig. 3b, c, e (red bars); displayed relative to appropriate driver crossed with Scramble-SP controls) or the null mutation (Fig. 1d). However, when we inhibited miR-34 presynaptically using a motor neuron-specific driver (OK6-GAL4) we observed the opposite phenotype resulting in NMJ overgrowth (Fig. 3d) with a significant increase in bouton number (Fig. 3e, green bar). Because miR-34 inhibition in motor neurons gave a surprising result, we asked if overexpression of miR-34 might yield a reciprocal effect. Indeed, expression of a UAS-miR-34(+) strainunder control of OK6-Gal4 caused a significant decrease in type 1 bouton number relative to the OK6-Gal4 control (Fig. 3e, far right red bar); unfortunately, expression of UAS-miR-34(+) in muscle was early lethal. These results indicate that miR-34 plays different roles in the presynaptic and postsynaptic compartments, suggesting a working hypothesis that the key downstream target genes in motor neurons and muscle cells are distinct.

---

### An interplay between cellular growth and atypical fusion defines morphogenesis of a modular glial niche in drosophila [^f8aa5ec3]. Nature Communications (2022). High credibility.

Quantification of clone volumes for Raeppli-CAAX

Raeppli TFP1 clones were chosen for quantification as it is the strongest and sharpest of the four Raeppli fluorophores. Only clones in the ventral nerve cord were measured. Volumes were measured in 3D images using Volocity 6.3 (Quorum technologies).

Quantification of clone overlap for Raeppli-CAAX

Z stacks of Raeppli - CAAX 53E clones induced in CG were visualised in Icy v2.1.4.0 (Institut Pasteur and France Bioimaging, license GPLv3). Boundaries of all one-colour clones, for each of the 4 possible, were mapped manually and outlined with polygons. The same was done in the rare case of full colour overlap. Partial overlaps between clones (defined as an overlap between the colours of adjacent clones that do not cover fully any of the two clones) were then counted manually, with their position recorded on the stack by drawing an ellipse.

The clones were counted in the VNC only, stopping at the middle of the neuropile coming from the ventral side, as the great majority of NSCs are located ventrally.

The number of overlaps counted corresponds to the number of fusion events, that we then divided by the total number of clones to generate a "Number of events/clones".

Quantification of clone number, size, and colour for Raeppli-NLS

Z stacks of Raeppli - NLS clones induced in CG were visualised in Icy v2.1.4.0 (Institut Pasteur and France Bioimaging, license GPLv3). The z dimension of the stack was reduced to encompass clones from the most ventral side up to the neuropile, then a max intensity projection was performed to get a 2D representation of the clones. Clone boundaries were mapped manually, based on changes in colour combination, and outlined with polygons. Boundaries were verified back on the 3D z-stack in case of ambiguity brought by the 2D projection. The total number of clones identified was then recorded (Number of clones), as well as the number of nuclei (Number of nuclei per clone) and the colour combination (Number of colours per clone) for each clone. These counts were obtained in the VNC only.

---

### Trametinib (Mekinist) [^694c6afd]. FDA (2025). Medium credibility.

The dosage of trametinib dimethyl sulfoxide PO for treatment of anaplastic thyroid cancer in adults with BRAF V600E mutation (locally advanced or metastatic) is 2 mg PO daily until disease recurrence or unacceptable toxicity

---

### Trametinib (Mekinist) [^9f1d60cc]. FDA (2025). Medium credibility.

The dosage of trametinib dimethyl sulfoxide PO for treatment of melanoma in adults with BRAF V600E or V600K mutation (unresectable or metastatic, BRAF-inhibitor treatment-naive, monotherapy) is 2 mg PO daily until disease recurrence or unacceptable toxicity

---

### Expert panel on integrated guidelines for cardiovascular health and risk reduction in children and adolescents: summary report [^8714414c]. PES (2012). Medium credibility.

Atherosclerosis lesion mapping in youth — In 15- to 24-year old and 25- to 34-year-old subjects, increasing numbers of cardiovascular (CV) risk factors are linked to both the presence and severity of lesions, and the absence of identified risk factors is associated with a virtual absence of advanced atherosclerotic lesions (American Heart Association Grades IV and V) in 15- to 34-year olds.

---

### Six is enough? Comparison of diffusion parameters measured using six or more diffusion-encoding gradient directions with deterministic tractography [^7b765bb5]. Magnetic Resonance in Medicine (2012). Low credibility.

Diffusion tensor imaging tractography is commonly used to quantify white matter tracts in the human brain via parameters such as fractional anisotropy and mean diffusivity. Simulation studies recommend the use of more than six directions for robust parameter estimates; however, no study has examined the impact of the number of gradient directions on deterministic tractography-derived diffusion parameters in human brain. Here, for 10 major white matter tracts in 11 healthy volunteers at 1.5 T, six-direction diffusion tensor imaging data were compared to 30- or 60-direction data, keeping scan time and number of b = 0 images constant within each test. Mean diffusivity was systematically lower for six-direction protocols (20/40 comparisons); six-direction data had higher fractional anisotropy in the superior longitudinal fasciculus and smaller tract volume for the genu of the corpus callosum. In general, parameter differences due to the number of directions were smaller than those from intersubject variation or signal-to-noise ratio. Despite some absolute differences, standard deviations were significantly different for only one of 160 comparisons. Thus, six-direction data provide diffusion measures with comparable robustness to 30- or 60-direction data and yield appropriate parameter values for most white matter tracts, although there are clear advantages in acquiring higher angular resolution data.

---

### A need to improve the assessment of environmental hazards for falls on stairs and in bathrooms: results of a scoping review [^67f916f4]. BMC Geriatrics (2018). Low credibility.

Grab bars

Although most checklists assessed grab bars in bathrooms, there was a lot of variation as to where (in the bathtub, shower and/or next to the toilet) and how they were assessed. For instance, in some checklists, grab bars were assessed with a single item and a bathroom would need to have grab bars in three locations (toilet, bath, shower) not to be hazardous, while in others, grab bars were also assessed with a single item but the presence of only one grab bar was enough to code the item as having the grab bar present. In other studies, each location was assessed separately and one, two or three items were listed in the checklist accordingly. Two checklists coded the lack of grab bars as a hazard only if the person needed them, one coded using a grab bar as a hazard, and another described grab bars as assistive devices and did not consider their absence to be an environmental hazard.

None of the checklists distinguished between diagonal, horizontal or vertical grab bars in the tub/shower; or documented where they were situated (e.g. side wall and/or back wall). Four checklists assessed grab bar placement; one had objective height measures, whereas others relied on subjective criteria such as "properly installed", "properly placed", or "can be reached without leaning enough to lose balance". Four checklists assessed if grab bars were sturdy or well anchored to walls. Illustrations of grab bars in another checklist included two types that were not fixed to a wall. Only three checklists provided a definition of grab bars or specified that towel racks are not grab bars.

Summary of key findings related to stairs/steps

Thirty-nine checklists included items on stairs and/or steps. Most (n = 22, 63%) assessed both indoor and outdoor stairs/steps, while eleven (31%) assessed only indoor stairs/steps and two assessed only outdoor stairs/steps. The location of stairs/steps (whether indoors or outdoors) was not differentiated in four of the checklists (10%). Very few checklists assessed the number of stairs/steps or staircases in the home.

---

### Pulsed accretion in a variable protostar [^1d284ba0]. Nature (2013). Excellent credibility.

Periodic increases in luminosity arising from variable accretion rates have been predicted for some pre-main-sequence close binary stars as they grow from circumbinary disks. The phenomenon is known as pulsed accretion and can affect the orbital evolution and mass distribution of young binaries, as well as the potential for planet formation. Accretion variability is a common feature of young stars, with a large range of amplitudes and timescales as measured from multi-epoch observations at optical and infrared wavelengths. Periodic variations consistent with pulsed accretion have been seen in only a few young binaries via optical accretion tracers, albeit intermittently with accretion luminosity variations ranging from zero to 50 per cent from orbit to orbit. Here we report that the infrared luminosity of a young protostar (of age about 10(5) years) increases by a factor of ten in roughly one week every 25.34days. We attribute this to pulsed accretion associated with an unseen binary companion. The strength and regularity of this accretion signal is surprising; it may be related to the very young age of the system, which is a factor of ten younger than the other pulsed accretors previously studied.

---

### Recommendations for cardiac chamber quantification by echocardiography in adults: an update from the American Society of Echocardiography and the European association of cardiovascular imaging [^194fdbe5]. Journal of the American Society of Echocardiography (2015). Medium credibility.

Left atrial (LA) volume quantification by echocardiography is described using two-dimensional echocardiography (2DE) and three-dimensional (3D) approaches, with 2D volumetric measurements based on tracings from apical four- and two-chamber views; at the mitral valve level the contour is closed by a straight line, endocardial tracing excludes the atrial appendage and pulmonary veins, LA length L is the shortest long axis from apical two- and four-chamber views, and the two lengths should not differ more than 5 mm; volumes can be computed by an area-length approximation or by a disk summation technique, and 3D data sets are usually acquired from the apical approach using a multibeat full-volume acquisition. For the 2DE area-length technique, advantages include accurate assessment of asymmetric remodeling of the left atrium and being a more robust predictor of cardiovascular events than linear or area measurements, whereas limitations include geometric assumptions about LA shape, few accumulated data on normal population, and that single plane volume calculations are inaccurate because they assume A1 = A2. For 3D data sets, advantages are no geometrical assumption about LA shape and greater accuracy compared with 2D measurements, while limitations include dependence on adequate image quality, lower temporal resolution, limited data on normal values, and that patient's cooperation is required.

---

### Lomotil [^bfcb0fa6]. FDA (2022). Medium credibility.

HOW SUPPLIED

Tablets — round, white, with SEARLE debossed on one side and 61 on the other side and containing 2.5 mg of diphenoxylate hydrochloride and 0.025 mg of atropine sulfate, supplied as:

NDC Number Size

0025-0061-31 bottle of 100

0025-0061-51 bottle of 500

0025-0061-52 bottle of 1,000

0025-0061-55 bottle of 2,500

0025-0061-34 carton of 100 unit dose

Liquid — containing 2.5 mg of diphenoxylate hydrochloride and 0.025 mg of atropine sulfate per 5 ml; bottles of 2 fl oz (NDC Number 0025-0066-02). Dispense only in original container.

A plastic dropper calibrated in increments of 1/2 mL (1/4 mg) with a capacity of 2 mL (1 mg) accompanies each 2-oz bottle of Lomotil liquid. Only this plastic dropper should be used when measuring Lomotil liquid for administration to children.

---

### Tretinoin [^5e84ee25]. FDA (2024). Medium credibility.

The dosage of tretinoin PO for treatment of acute promyelocytic leukemia in adults (consolidation therapy) is 45 mg/m² PO daily, in 2 divided doses, 2 weeks on and 2 weeks off, for 7 courses

---

### Sample sizes based on three popular indices of risks [^4a61a58f]. General Psychiatry (2018). Low credibility.

Sample size justification is a very crucial part in the design of clinical trials. In this paper, the authors derive a new formula to calculate the sample size for a binary outcome given one of the three popular indices of risk difference. The sample size based on the absolute difference is the fundamental one, which can be easily used to derive sample size given the risk ratio or OR.