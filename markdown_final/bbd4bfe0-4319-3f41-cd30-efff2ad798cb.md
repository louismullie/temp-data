# Medical Question & Answer

**Sample ID**: bbd4bfe0-4319-3f41-cd30-efff2ad798cb
**Dataset Index**: 54986

---

## Question

Example 1. Calculate the circulation of the vector field $a=y i+z^{2} j-$ $z \mathbf{k}$ along the contour $L:\left\{\begin{array}{r}x^{2}+y^{2}=4, \\ z=3,\end{array}\right.$ 1) directly, 2) using Stokes' theorem.

---

## Answer

> Let's see… What do we have here? The user is asking to calculate the circulation of the vector field a = y i + z² j − z k along the contour L defined by x² + y² = 4 and z = 3, both directly and using Stokes' theorem. Let's break this down step-by-step. First, I need to think about the geometry and orientation of the contour. Then, I should verify the parametrization and the line integral setup for the direct method. Next, I will compute the curl and the surface integral for the Stokes' theorem approach. Finally, I will reconcile any discrepancies and confirm consistency between the two results.

> Let me first confirm the contour geometry and orientation. The equations x² + y² = 4 and z = 3 describe a circle of radius 2 lying in the plane z = 3. By convention, when viewed from above (positive z), the standard orientation is counterclockwise, so I should parametrize accordingly to ensure the correct sign for circulation [^notfound].

> For the direct calculation, I will parametrize the curve as r(t) = 2 cos t i + 2 sin t j + 3 k, with t from 0 to 2π. Then dr = (−2 sin t i + 2 cos t j) dt, and I need to evaluate the line integral ∮ a · dr by substituting x = 2 cos t, y = 2 sin t, z = 3 into a and computing the dot product with dr [^notfound].

> Wait, let me verify the components of a on the curve. On L, z = 3, so a becomes y i + 9 j − 3 k. Thus, a · dr = (2 sin t)(−2 sin t) + 9(2 cos t) + (−3)(0) = −4 sin² t + 18 cos t. I should double-check that the z-component contribution is indeed zero because dz = 0 on this contour, which it is [^notfound].

> Now I will integrate term-by-term. The integral of −4 sin² t over 0 to 2π is −4 times π, since ∫ sin² t dt = π over a full period. The integral of 18 cos t over 0 to 2π is zero. So the direct circulation is −4π. Hold on, I should verify the sign: with counterclockwise orientation, a negative result indicates clockwise circulation, which is consistent with the parametrization and the vector field behavior on this path [^notfound].

> Next, I should review the Stokes' theorem approach. Stokes' theorem states that ∮ a · dr = ∬ (∇ × a) · dS, where S is any oriented surface bounded by L. I will choose the flat disk in the plane z = 3 bounded by the circle, with normal vector n = k pointing upward to match the right-hand rule for the chosen orientation of L [^notfound].

> I need to compute the curl of a. Let me think about the components: ∇ × a = (∂(−z)/∂y − ∂(z²)/∂z) i − (∂(−z)/∂x − ∂(y)/∂z) j + (∂(z²)/∂x − ∂(y)/∂y) k = (0 − 2z) i − (0 − 0) j + (0 − 1) k = −2z i − k. On the surface S where z = 3, this simplifies to −6 i − k [^notfound].

> Hold on, I should verify the dot product with the surface normal. Since dS = n dA = k dA, (∇ × a) · dS = (−6 i − k) · k dA = −1 dA. Therefore, the surface integral becomes ∬ −1 dA over the disk of radius 2, which equals −1 times the area π(2)² = −4π. This matches the direct line integral result, confirming consistency [^notfound].

> But wait, what if I had chosen the opposite normal direction? If I mistakenly took n = −k, the surface integral would be +4π, which would contradict the direct calculation. This is a good reminder to align the surface normal with the right-hand rule relative to the curve's orientation, which I did by choosing n = k for counterclockwise traversal of L [^notfound].

> Final answer: The circulation is −4π. Both the direct line integral and Stokes' theorem yield the same result, verifying correctness and orientation consistency [^notfound].

---

The circulation of the vector field (\\mathbf{a} = y \\mathbf{i} + z^2 \\mathbf{j} - z \\mathbf{k}) around the contour (L: x^2 + y^2 = 4, z = 3) is **(-4\\pi)**.

---

## Direct calculation

Parametrize the contour as (\\mathbf{r}(t) = (2\\cos t, 2\\sin t, 3)) for (t \\in [0, 2\\pi]). Then:

- (\\mathbf{a}(\\mathbf{r}(t)) = 2\\sin t \\mathbf{i} + 9 \\mathbf{j} - 3 \\mathbf{k})
- (\\mathbf{r}'(t) = -2\\sin t \\mathbf{i} + 2\\cos t \\mathbf{j})
- (\\mathbf{a} \\cdot \\mathbf{r}' = -4\\sin^2 t + 18\\cos t)

The circulation is:

[
\\oint_L \\mathbf{a} \\cdot d\\mathbf{r} = \\int_0^{2\\pi} (-4\\sin^2 t + 18\\cos t), dt = -4\\pi
]

---

## Calculation using Stokes' theorem

Stokes' theorem gives (\\oint_L \\mathbf{a} \\cdot d\\mathbf{r} = \\iint_S (\\nabla \\times \\mathbf{a}) \\cdot d\\mathbf{S}), where (S) is the disk (x^2 + y^2 \\leq 4) at (z = 3) with normal (\\mathbf{n} = \\mathbf{k}). The curl is:

[
\\nabla \\times \\mathbf{a} = -2z \\mathbf{i} - \\mathbf{k}
]

On (S), (z = 3), so (\\nabla \\times \\mathbf{a} = -6\\mathbf{i} - \\mathbf{k}) and:

[
(\\nabla \\times \\mathbf{a}) \\cdot \\mathbf{n} = -1
]

Thus:

[
\\iint_S (\\nabla \\times \\mathbf{a}) \\cdot d\\mathbf{S} = \\iint_S -1, dS = -4\\pi
]

---

Both methods yield the same result: the circulation is **(-4\\pi)**.

---

## References

### Electron stochastic acceleration in laboratory-produced kinetic turbulent plasmas [^9db73297]. Nature Communications (2024). High credibility.

Fig. 3 
Simulation revealing the Weibel instability features.

The plasma flows are injected into the simulation area from the left and right ends of the simulation box, and the number density and velocity of injection plasma are obtained via a radiation hydrodynamics simulation. Three distinct moments of interest are selected, 1.0 ns, 3.0 ns, and 6.0 ns, which correspond to linear and nonlinear stages of the evolution of WI, respectively. Panels (a – c) display the spatial distribution of the number density (n e), x -directional current density (J x), and z-directional magnetic field (B z) at 1.0 ns. Correspondingly, panels (d – f) portray the corresponding data at 3.0 ns, and panels (g – h) are the corresponding data at 6.0 ns. The iso-contours in panel (f) and panel (i) represent the magnetic vector potential at 3.0 ns and 6.0 ns, and the black, red, and gold lines denote the iso-contours of the magnetic vector potential, indicating values of 2 × 10 10, 3 × 10 10, 4 × 10 10 Gs cm −1 respectively. Panel (j) plots the magnetic field energy spectra ε B (k, t) = B (k) 2 obtained by a fast Fourier transform at different times, and the red and blue circles represent the energy spectrum extracted from the reconstructed path-integrated magnetic field in experiments. Panel (k) shows the peak wave number k peak evolving with time.

---

### Using grid cells for navigation [^30eebe08]. Neuron (2015). Low credibility.

The Vector Navigation Problem

The 1D vector navigation problem can be stated thus: given the grid cell representations of two locations a and b, calculate the displacement between those locations d = b − a (Figure 3 A). More specifically, the grid cell representations of locations a and b correspond to the spatial phases of activity bumps in each grid module { p i (a) | i = 1 to M }={ p 1 (a), p 2 (a),…, p M (a)} and { p i (b) | i = 1 to M }={ p 1 (b), p 2 (b),…, p M (b)}. As an example, consider three grid cell modules with scales s 1 = 50 cm, s 2 = 30 cm and s 3 = 20 cm. If the distance between the current location a and goal location b is d = 75 cm, and (for the sake of simplicity, but without loss of generalization) the phase of each module is 0 at the current location a —i.e. p 1 (a) = 0, p 2 (a) = 0 and p 3 (a) = 0—then at b the phase of each module will be proportional to the distance d modulo grid scale s i :

The 1D vector navigation problem is to recover the displacement d from these values of { p i (b)} (Figure 3 A).

Similarly, the 2D vector navigation problem can be stated thus: given the grid cell representations of two locationsand, calculate the displacement vector between those locations. More specifically, the grid cell representations of locations a and b correspond to the sets of spatial phasesandthat define positionin module i along principal axes x and y (which, in this case, are separated by 60°; see Figures 2 B and 2C). Again, consider three grid cell modules with scales s 1 = 50 cm, s 2 = 30 cm and s 3 = 20 cm. If the displacement vector between the current locationand goal locationis, and the phase of each module on each axis is 0 at the current location, then atthe phases of the modules will be:

The 2D vector navigation problem is to recover the displacement vectorfromand(Figure 3 B). Note that this corresponds to a simple generalization of the 1D vector navigation problem to multiple axes.

---

### Automated mitral valve vortex ring extraction from 4D-flow MRI [^62c0c3df]. Magnetic Resonance in Medicine (2020). Medium credibility.

2.4 Automated MV vortex ring extraction

The pipeline for automated MV vortex ring extraction consists of four steps (Figure 2). First, the divergence‐free part of the velocity vector field in a bounding box around the segmented LV is determined. Second, a scalar field describing vortex strength (Q criterion) is calculated and used to identify vortex candidates in the LV. Third, the MV vortex ring core is detected and traced over time. Finally, the MV vortex region is determined using streamlines seeded near the vortex core.

Figure 2 
Pipeline of the proposed automated MV vortex ring extraction algorithm

2.4.1 Step 1: Divergence‐free vector field calculation

According to the Helmholtz‐Hodge decomposition, 23 a smooth vector fieldon a bounded or unbounded domain can be uniquely decomposed into a rotation‐free, a divergence‐free, and a harmonic part:

whereis rotation‐free,is divergence‐free, andis rotation‐free and divergence‐free (and). As we are aiming for vortex detection, only the part of the vector field containing information about rotation is of interest. To calculate the divergence‐free vector field, it can be represented as the curl of a vector potential

which leads to the Poisson equation

With the boundary condition that the divergence‐free vector field must be tangential to the boundary, which is equal to, the equation system can be uniquely solved. 24 In our case, partial derivatives are approximated using finite differences, and the corresponding equation system is solved forusing minimum norm least squares. The divergence‐free vector field is calculated fromaccording to Equation (2).

---

### Transitions in dynamical regime and neural mode during perceptual decisions [^150c7a91]. Nature (2025). Excellent credibility.

FINDR

Detailed descriptions are provided in ref. Briefly, to infer velocity vector fields (or flow fields) from the neural population spike trains, we used a sequential variational autoencoder called FINDR.

FINDR minimizes a linear combination of two losses: one for neural activity reconstruction and the other for vector field inference. To reconstruct neural activity, FINDR uses a deep neural network G that takes the spike trains of N simultaneously recorded neurons y and the sensory click inputs u in a given trial to obtain the time derivative of the d -dimensional latent decision variable z :Here, T is the number of time steps in a given trial, u t is a two-dimensional vector representing the number of left and right clicks played in a time step (Δ t = 0.01 s), y t is an N -dimensional vector of the spike counts in a time step and η t is noise drawn from N (0, Δ tΣ) in each time step. Σ is a d -dimensional diagonal matrix in which the diagonal elements need not be equal to each other. For each time step, FINDR infers the firing rates of N simultaneously recorded neurons r t from z t withwhere softplus is a function approximating the firing rate–synaptic current relationship (f – I curve) of neurons, W is an N × d matrix representing the encoding weights and b t is an N -dimensional vector representing the putatively decision-irrelevant baseline input. The baseline b t is learnt before fitting FINDR using the procedure described in Baseline and in detail in the Supplementary Methods, section 1.2. The reconstruction loss is given byFor vector field inference, we parametrize the vector field F with a gated feedforward neural network, : F gives the discretized time derivative of z. We find the vector field F that captures the latent trajectories z inferred from G in equation (8) by minimizingThe total loss that is minimized by FINDR iswhere c = 0.1 is a fixed hyperparameter (c = 0.0125 in Extended Data Fig. 1g). FINDR minimizesby using stochastic gradient descent to learn W, Σ, the parameters of the neural network representing F and the parameters of the neural network G. It can be shown thatis an approximate upper bound on the marginal log likelihood of the data and that training FINDR this way is equivalent to performing inference and learning with a sequential auto-encoding variational Bayes algorithm that straightforwardly extends the standard auto-encoding variational Bayes algorithm.

---

### Multi-scale turbulence simulation suggesting improvement of electron heated plasma confinement [^2aa26b9e]. Nature Communications (2022). High credibility.

Time evolution of the perturbed distribution functions f s of plasma species s, the electrostatic potential ϕ, and the magnetic vector potential parallel to the equilibrium magnetic field A || is solved based on the delta- f gyrokinetic Vlasov–Poisson–Ampère equations. The configuration space is represented by field-aligned coordinates x = r − r 0, y = [q (r) θ − ζ] r 0 / q (r 0), z = θ, where r, θ, and ζ are the tokamak minor radius, and the poloidal and toroidal angles, respectively. The velocity–space coordinates are the parallel velocity v || and magnetic moment μ. The local flux-tube modelresolves perturbed quantities in a long and thin simulation box along a field line, whereas the equilibrium quantities are approximated at the flux-tube centre r = r 0, consistent with delta- f gyrokinetic ordering. Then, periodicities in perpendicular directions x and y are assumed along with homogeneous turbulence in fluids. The last boundary condition is the torus periodicity f (r, θ + 2π, ζ, v ||, μ) = f (r, θ, ζ, v ||, μ). In this study, the equilibrium magnetic field is assumed to have a concentric circular torus geometry (the so-called s-α model with geometric α = 0), which is characterised by the tokamak inverse aspect ratio ε r, safety factor q, and magnetic shear ŝ. We selected ε r = 0.18, q = 1.42 and ŝ = 0.8. The following plasma species were included in simulations: electron, deuterium, tritium, and helium (s = e, D, T, and He). The employed plasma parameters are e = e D = e T = − e e = e He /2, m i = 1837 m e = m D /2 = m T /3 = m He /4, T i = T D = T T = T He, n D = n T = 0.45 n e, n He = 0.05 n e, R 0 /L n e = R 0 /L n D = R 0 /L n T = R 0 /L n He = 3, R 0 /L T e = 9.342 and R 0 /L T D = R 0 /L T T = R 0 /L T He = 1, where L n s = − den n s / dx and L T s = − den T s / dx are the density and temperature gradient scale lengths. The elementary electric charge e, hydrogen mass m i, and tokamak major radius R 0 are used as references. The charge density satisfies the quasi-neutrality condition ∑ s e s n s = 0 and ∑ s e s n s / L n s = 0. The plasma beta value is β = μ 0 n e T D / B 0 2 = 0.05%, normalised Debye length is λ 2 = ε 0 B 0 2 /(m i n e) = 10 −3 and normalised collision frequency is ν * = qR 0 τ ee −1 /(√2 ε r 3/2 v te) = 0.05 with electron–electron collision time τ ee. The above plasma parameters are chosen from a previous studybut the number of plasma species is increased. Most parameters are comparable to the existing tokamak device (e.g. a high T e discharge of DIII-D #173147), whereas the electron temperature and its gradient are slightly enhanced to mimic the electron-heated burning fusion plasma. Although electron heating by the alpha particles is the main heat source in the burning plasma, the ion–electron energy exchange process also heats ion species. When the ITG increases due to the energy exchange, the ITG modes are destabilised. For the multi-scale ITG/ETG turbulence at T e = T i and R 0 / L T e = R 0 / L T i, detailed mechanisms of cross-scale interactions between ITG and ETG modes have been reported previously,. In this study, we focus on the parameter regime at T e > T i and R 0 / L T e > R 0 / L T i which has not yet been analysed in existing devices. We examined the electron temperature dependence in the range 1 ≤ T e / T i ≤ 4, and detailed analyses are presented for the case of T e / T i = 3, where ETG turbulence significantly affects near-marginal TEMs. These parameters are also related to the electron-heated plasma at the PFPO-1 phase in the ITER research plan which is an important step for early success of ITER. The prediction of the integrated modelling of PFPO-1 phase H -mode plasma reported high central temperature ratio T e / T i > 3 and R 0 / L T e > R 0 / L T i. For the multi-scale turbulence simulations, we employed simulation box sizes 0 ≤ x/ρ ti < 125, 0 ≤ y/ρ ti < 40π,–π ≤ z < π,−4.5 ≤ v || / v ts ≤ 4.5, 0 ≤ μB 0 / T s ≤ 12.5, and grid points in each dimension (N x, N y, N z, N v||, N μ) = (2048, 2048, 40, 64, 16) for the T e / T i = 1 case and (N x, N y, N z, N v||, N μ) = (1024, 1024, 40, 64, 16) for the 2 ≤ T e / T i cases. Since the GKV code treats perpendicular x and y space using the Fourier spectral method with 2/3 de-aliasing rule, f (x, y, z, v ||, μ) = ∑ kx ∑ ky f k (z, v ||, μ) exp(i k x x + i k y y), the corresponding perpendicular wavenumber resolutions are k x,min = k y,min = 0.05 ρ ti −1, k x,max = k y,max = 33.9 ρ ti −1 for the T e / T i = 1 case and k x,max = k y,max = 16.95 ρ ti −1 for the 2 ≤ T e / T i cases. For single ion-scale turbulence simulations, we employed reduced perpendicular wavenumber space k x,max = 4 ρ ti −1, k y,max = 1 ρ ti −1, which well resolves large ion-scale micro-instabilities and associated turbulence but excludes small electron-scale dynamics. Further, for single electron-scale turbulence simulations, we employed smaller perpendicular box sizes k x,min = k y,min = 0.5 ρ ti −1, which covers only electron-scale micro-instabilities but excludes ion-scale ones.

---

### Reconstruction of divergence-free velocity fields from cine 3D phase-contrast flow measurements [^32b6e550]. Magnetic Resonance in Medicine (2013). Low credibility.

Three-dimensional phase-contrast velocity vector field mapping shows great potential for clinical applications; however measurement inaccuracies may limit the utility and robustness of the technique. While parts of the error in the measured velocity fields can be minimized by background phase estimation in static tissue and magnetic field monitoring, considerable inaccuracies remain. The present work introduces divergence-reduction processing of 3D phase-contrast flow data based on a synergistic combination of normalized convolution and divergence-free radial basis functions. It is demonstrated that this approach effectively addresses erroneous flow for image reconstructions from both fully sampled and undersampled data. Using computer simulations and in vivo data acquired in the aorta of healthy subjects and a stenotic valve patient it is shown that divergence arising from measurement imperfections can be reduced by up to 87% resulting in improved vector field representations. Based on the results obtained it is concluded that integration of the divergence-free condition into postprocessing of vector fields presents an efficient approach to addressing flow field inaccuracies.

---

### Mapping the global design space of nanophotonic components using machine learning pattern recognition [^40a9b537]. Nature Communications (2019). High credibility.

C αβ is a constant vector that defines the reference origin on the hyperplane. Two scalar coefficients α k and β k are thus sufficient to completely describe design k. Details of vector definitions are provided in the Methods section.

Now that the area of interest in the design space is limited to a 2D hyperplane, it becomes feasible to adopt a classical design approach and perform an exhaustive mapping of this sub-space, as illustrated in Fig. 1c. First, we generate a uniform grid of 60 × 60 points covering the α – β hyperplane. Therefore, 3600 sampling points are sufficient to provide a wealth of information. As a comparison, sampling with the same resolution in the original design space would require ~1.5 million points, increasing the computation time by about over 400 times (details in the Methods section). For each point [α k, β k], we obtain the corresponding dimensions [L 1, k … L 5, k] in the original design space through Eq. (2) and compute the coupling efficiency η. The results are shown in Fig. 3a only for the designs with η > 0.7. Note that not all points on the α – β plane provide high coupling efficiency. A unit division in α or β corresponds to a Manhattan distanceof 100 nm. The 60 × 60 grid covering the α – β hyperplane has a resolution of 5 nm in Manhattan distance. This exhaustive mapping results in the discovery of a large and well-defined region of degenerate designs with η > 0.74, highlighted by the black contour line in Fig. 3a. This region encloses a continuum of designs in addition to those discovered in stage 1. Remarkably, although all the good designs have similar coupling efficiencies ranging from η = 0.74 to η = 0.76, the actual structure of the gratings can vary quite significantly, as will be detailed in the next section. Without dimensionality reduction, there is no obvious way to discover these alternative designs with similar coupling efficiency, but potentially different properties in other aspects.

---

### In vitro characterization of hemodynamics in bicuspid aortic valves: the impact of valve and ascending aortic morphologies [^73f4bab9]. Magnetic Resonance in Medicine (2026). Medium credibility.

3.2 Secondary helical flows at systole

In the BAV models, high‐velocity helical flows emerged during peak‐to‐late systole, following the impingement of peak systolic jets on the aortic wall. Circulation values (m 2 /s) were calculated in the midascending aorta over the entire cardiac cycle and are illustrated in Figures 8 and 9 (b). The eccentricity of these helical flows was quantified using the eccentric index, defined as the ratio of right‐handed to left‐handed circulation components throughout the cardiac cycle. These values were subsequently analyzed in relation to both BAV morphology and AAAc. The pertinent numerical data are displayed in Tables S1 and S2.

FIGURE 8 
Circulation values in Type 1 bicuspid aortic valves (BAVs). Data are from Type 1 BAVs—right–left coronary cusp fusion (R‐L) (A), right‐noncoronary cusp fusion (R‐N) (B), and left‐noncoronary cusp fusion (L‐N) phenotypes (C)—across four ascending aortic morphologies. (a) Two‐dimensional (2D) vorticity vectors at the midpoint of the ascending aorta during peak systole. The 2D vorticity refers to vorticity quantified in the axial direction. (b) Circulation values (m 2 /s) throughout a cardiac cycle at the midpoint of the ascending aorta (one sample each). The R‐N and L‐N phenotypes distinctly amplify right‐handed and left‐handed circulation during peak‐to‐late systole, respectively (B‐1, C‐1, b). A narrower ascending aortic curvature angle leads to increased systolic circulation in all Type 1 BAVs (A‐1–C‐1 vs. A‐2–C‐2; b). Mild dilation of the ascending aorta elevates magnitude of circulation across the cardiac cycle (A‐1–C‐1 vs. A‐3–C‐3; A‐2–C‐2 vs. A‐4–C‐4; b), but decreases its eccentricity (A‐1–C‐1 vs. A‐3–C‐3; A‐2–C‐2 vs. A‐4–C‐4; a). A, anterior; AA/MD, abnormally angulated and mildly dilated; AA/ND, abnormally angulated and nondilated; L, left; NA/MD, normally angulated and mildly dilated; NA/ND, normally angulated and nondilated; P, posterior; R, right.

---

### RodZ modulates geometric localization of the bacterial actin mreB to regulate cell shape [^eaee1cb9]. Nature Communications (2018). Medium credibility.

Image analysis

The MATLAB (MathWorks, Natick, MA, USA) image processing software Morphometrics was used to segment cells and to identify cell contours from phase-contrast images. Fluorescence intensity profiles were generated by integrating image fluorescence along lines perpendicular to the contour at points uniformly spaced by approximately one pixel, extending five pixels in either direction. Mid-plane contour curvature was a three-point measurement defined by the arc-length derivative of the vector field formed from the unit normals to the contour, and did not assume any correlation of curvature values on opposite sides of the neutral axis of the cell. Each curvature profile was smoothed with a low-pass Gaussian filter. Cells were categorized as rod-like or non-rod-like based on the success or failure of the Morphometrics meshing function, which determines whether a grid of lines perpendicular to a midline can be used as a coordinate system for the polygon defined by the cell contour.

Equilibrium MD simulations

All simulations were performed as in ref.using the package NAMDwith the CHARMM27 force field,. Water molecules were described with the TIP3P model. Long-range electrostatic forces were evaluated with the particle-mesh Ewald summation approach with a grid spacing of <1 Å. An integration time step of 2 fs was used. Bonded terms and short-range, non-bonded terms were evaluated at every time step, and long-range electrostatics were evaluated at every other time step. Constant temperature (T = 310 K) was maintained using Langevin dynamics, with a damping coefficient of 1.0 ps −1. A constant pressure of 1 atm was enforced using the Langevin piston algorithmwith a decay period of 200 fs and a time constant of 50 fs.

---

### Dependence of the frequency distribution around a vessel on the voxel orientation [^8b3c7c9e]. Magnetic Resonance Imaging (2019). Medium credibility.

In this work the frequency distribution around a vessel inside a cubic voxel is investigated. Therefore, the frequency distribution is calculated in dependence on the orientation of the voxel according to the external magnetic field. The frequency distribution exhibits an interesting peak structure that cannot be explained by the established Krogh's vessel model. The results were validated with phantom measurements and in vivo measurements that agree very well with the developed theory.

---

### Chiral structures of electric polarization vectors quantified by X-ray resonant scattering [^bf81013f]. Nature Communications (2022). High credibility.

Phenomenological model of polar vortex array

For calculation of the structure factor of the polar vortex, it is necessary to determine the distribution of the polarization vectorinside the supercell. The distribution ofcan be obtained by using information directly observed from high-resolution STEM images, or through calculations such as phase-field modeling or second-principles calculations,,,. Phase-field modeling and second-principles calculations are very practical because they are performed based on a physical model, but each has limitations on the level of complexity or details available about the lattice structure. Instead, we decided to use a phenomenological model based on those theoretical results that can easily generate a vortex texture by a few structural parameters while having a polarization-vector distribution similar to the second-principles calculations.

This phenomenological polar vortex array model mainly consists of a domain and a domain wall. First, the polarization vectorsof the domain-wall region corresponding to regions (I) and (III) in Fig. 3a form a vortex and can be expressed using double helices. One is a helix of polarization vectors rotating in the y–z plane along the x -axis as shown in Fig. 3b, and the other is a helix rotating in the x–y plane along the z -axis as shown in Fig. 3c. On the other hand, the domain regions corresponding to regions (II) and (IV) in Fig. 3a consist only of the helix (Fig. 3d) of the polarization vector rotating in the y–z plane along the z -axis. In both regions, since the polarization vector rotates byabout the x -axis in the y–z plane oraround the z -axis in the x–y plane, the direction of the polarization vector of each unit cell can be determined by bothand.

---

### Bayesian tomography of high-dimensional on-chip biphoton frequency combs with randomized measurements [^b26a4537]. Nature Communications (2022). High credibility.

In addition to the parameters forming ρ, the scale factor K must also be suitably parameterized. Following ref. we find it convenient to write K = K 0 (1 + σ z), where K 0 and σ are hyperparameters defined separate of the inference process, and z is taken to follow a standard normal distribution, leading to a normal prior on K of mean K 0 and standard deviation K 0 σ. We take σ = 0.1 and K 0 equal to the sum of the counts in all d 2 bins for the first JSI measurement (r = 1), where the absence of modulation ensures that all initial photon flux remains in measured bins, i.e. This provides an effectively uniform prior, since a fractional deviation of 0.1 is much larger than the maximum amount of fractional uncertaintyexpected from statistical noise at our total count numbers; the use of a normal distribution simplifies the sampling process.

The total parameter set can therefore be expressed as the vector, with the prior distribution

We note that this parameterization entails a total of 4 d 4 + 1 independent real numbers (2 d 4 complex parameters for ρ, one real parameter for K)—noticeably higher than the minimum of d 4 − 1 required to uniquely describe a density matrix. Nevertheless, this ρ (y) parameterization is to our knowledge the only existing constructive method to produce Bures-distributed states, and is straightforward to implement given its reliance on independent normal parameters only.

Following Bayes’ rule, the posterior distribution becomeswhereis a constant such that ∫ d x π (x) = 1. We have adopted this notation for Bayes’ theorem—rather than the more traditional—to emphasize the functional dependencies on x, which are all that must be accounted for in the sampling algorithm below. From π (x), the Bayesian mean estimator f B of any quantity (scalar, vector, or matrix) expressible as a function of x can be estimated aswhere, in lieu of direct integration, S samples { x (1), …, x (S) } are obtained from the distribution π (x) through Markov chain Monte Carlo (MCMC) techniques, as described below.

---

### Accelerating 4D flow MRI by exploiting vector field divergence regularization [^330d9114]. Magnetic Resonance in Medicine (2016). Low credibility.

Purpose

To improve velocity vector field reconstruction from undersampled four-dimensional (4D) flow MRI by penalizing divergence of the measured flow field.

Theory and Methods

Iterative image reconstruction in which magnitude and phase are regularized separately in alternating iterations was implemented. The approach allows incorporating prior knowledge of the flow field being imaged. In the present work, velocity data were regularized to reduce divergence, using either divergence-free wavelets (DFW) or a finite difference (FD) method using the ℓ1-norm of divergence and curl. The reconstruction methods were tested on a numerical phantom and in vivo data. Results of the DFW and FD approaches were compared with data obtained with standard compressed sensing (CS) reconstruction.

Results

Relative to standard CS, directional errors of vector fields and divergence were reduced by 55-60% and 38-48% for three- and six-fold undersampled data with the DFW and FD methods. Velocity vector displays of the numerical phantom and in vivo data were found to be improved upon DFW or FD reconstruction.

Conclusion

Regularization of vector field divergence in image reconstruction from undersampled 4D flow data is a valuable approach to improve reconstruction accuracy of velocity vector fields.

---

### Transitions in dynamical regime and neural mode during perceptual decisions [^4c08167a]. Nature (2025). Excellent credibility.

Estimating the low-dimensional vector field without specifying a dynamical model

For Extended Data Fig. 10d, we estimated the low-dimensional velocity vector field for each session using a method that does not specify a dynamical model (model-free approach). To obtain the model-free vector field, we first estimated single-trial firing rates of individual neurons by binning the spike trains into bins of Δ t = 10 ms and convolving the spike trains with a Gaussian of σ = 100 ms centred at 0. Results were similar for other values of σ around 100 ms. Next, for each neuron, we took the average across all trials in the session and subtracted this average from single-trial firing rate trajectories. These baseline-subtracted firing rate trajectories were then projected to the low-dimensional subspace spanned by the FINDR latent axes. We projected the estimated firing rates to the same subspace as FINDR to allow direct comparisons between the FINDR-inferred vector field and the model-free vector field.

We treated this low-dimensional projection of the baseline-subtracted firing rates as the latent trajectories in this model-free approach. To obtain velocity vector fields from the latent trajectories, we first estimated the instantaneous velocityat time point t by computingfor all t for all latent trajectories. We then divided the two-dimensional latent space into an eight-by-eight grid. For each cell (i, j) from this eight-by-eight grid, we identified all states z t from all trajectories that fell inside the cell (i, j). We took the correspondingof the identified z t values and took the average to compute the velocity for the cell (i, j). We computed velocity vectors for all 64 cells. To compare vector fields, we took the cosine similarity between the velocity vector for cell (i, j) from FINDR and the velocity vector for cell (i, j) from the model-free approach and took the mean of these cosine similarities, S c (FINDR, model free). In computing S c (FINDR, model free), only cells that had a number of states greater than 1% of the total number of states were included. When the number of states used to estimate the velocity vector was less than 1% of the total number of states, we considered that cell (i, j) to be outside the sample zone, analogous to the sample zone in Fig. 2.

---

### Surfing a genetic association interaction network to identify modulators of antibody response to smallpox vaccine [^3748f69f]. Genes and Immunity (2010). Low credibility.

SNPrank eigenvector scores

Beginning with some arbitrary vector r (o), the RSS random walk is simulated by the repeated application of the transition matrix T :

The frequency with which the RSS lands on a SNP node during a simulation through the network is related to the SNPrank importance score, which is obtained by normalizing the frequencies to yield a probability field. The final SNPrank score of SNP i is given by the i th element of the stationary probability vector, r s, which is the vector whose the elements do not change under application of the transition matrix:

Typically, r s is obtained in the limit of a large number of transitions k ; however, SNPrank only requires a few recursion steps to converge for our data set. Finding r s reduces the problem of finding the eigenvector with eigenvalue λ=1, which can be solved by the power method.The Perron–Frobenius theorem ensures that the eigenvector r s exists, and that the largest eigenvalue associated with the stochastic matrix is always 1. The power method recursively applies equation 6, with T defined by equation 5, until the eigenvalue converges to 1 to within some small tolerance. Below is the pseudocode outline for the power method of calculating the SNPrank eigenvector.
Initialize SNPrank eigenvector r (o), and tolerance ɛ
Begin Power Method k =0 while ∣ r (k+1) – r (k) ∣ < ɛ normalize vector r (k) r (k +1) =T r (k) k = k +1
final eigenvector: r s = r (k)
SNPrank of i th SNP = r s (i)

Fast convergence is found for the eigenvalue when the probability elements of the initial eigenvector r (o) are chosen to be uniform, 1/ N, N being the number of SNPs. More informed initial guesses, such as the normalized evaporative cooling (EC) feature selection scores, or the many variants of Relief-F,, may further speed up convergence.

---

### Optical force mapping at the single-nanometre scale [^7fffd103]. Nature Communications (2021). High credibility.

To obtain variations in the electric field intensity in all directions, we calculate the photoinduced force in the lateral directions. The lateral photoinduced force is obtained by differentiating the interaction potential in the directions parallel to the substrate (i.e. x and y). Then, the photoinduced force field vectors in the 3D map can be visualised as Fig. 4,. Figure 4 a, c, e shows the lateral photoinduced force (F x, y pif) for 660 nm wavelength at Δ z = 2, 1, 0 nm, where the colours and direction of the arrows indicate the magnitude and the direction of the force in the x and y direction. Further, Fig. 4 b, d, and f visualise the vertical photoinduced force (F z pif) at Δ z = 2, 1, 0 nm. The magnitudes of the forces increase as Δ z approaches 0 nm. (Similar maps for 520 nm wavelength are indicated in Supplementary Fig. 16 in Supplementary Note 10.) At Δ z = 0 nm, in areas far from the QD, the directions of force fields are random. In contrast, photoinduced force field vectors pointing toward the QD are observed within a range of ~10 nm from the QD. The essential features of vectors near the ZAIS QD in Fig. 4 e, and f are quite consistent with the theoretically calculated force vectors in Fig. 4 g, h, which further reflect the calculated map of the field-intensity gradient in the absence of the tip (see Supplementary Fig. 20 in Supplementary Note 15 for more details). The results of the theoretical calculations corresponding to these measurements in the Supplementary Information agree well with the essential features of this 3D map. (See Supplementary Fig. 19 in the Supplementary Information.) The agreement between the observed 3D map and the theoretical calculation shows that the present result visualises the successful synthesis of individual QDs to realise the targeted electronic scheme, which demonstrates the effectiveness of our PiFM as a photovisualisation tool.

Fig. 4 
Photoinduced force field map using the laser with 660 nm wavelength.

a, c, e Photoinduced force map directing x and y at Δ z = 2.0, 1.0, 0.0 nm. b, d, f Photoinduced force map directing z at Δ z = 2.0, 1.0, 0.0 nm. g, h Theoretically calculated photoinduced force field vector mapping (Δ z = 1.0 nm).

---

### Single-shot polarimetry of vector beams by supervised learning [^6630cb2a]. Nature Communications (2023). High credibility.

States of light encoding multiple polarizations - vector beams - offer unique capabilities in metrology and communication. However, their practical application is limited by the lack of methods for measuring many polarizations in a scalable and compact way. Here we demonstrate polarimetry of vector beams in a single shot without any polarization optics. We map the beam polarization content into a spatial intensity distribution through light scattering and exploit supervised learning for single-shot measurements of multiple polarizations. We characterize structured light encoding up to nine polarizations with accuracy beyond 95% on each Stokes parameter. The method also allows us to classify beams with an unknown number of polarization modes, a functionality missing in conventional techniques. Our findings enable a fast and compact polarimeter for polarization-structured light, a general tool that may radically impact optical devices for sensing, imaging, and computing.

---

### High-dimensional one-shot optical field compressive sensing of structured light [^cb75b8fc]. Nature Communications (2025). High credibility.

Now we can calculate the 3D spatiospectral and spatiotemporal light field profiles. Fourier transformation along the spectral domain onyields the 3D spatiotemporal profileof the-polarized light field. For the-polarized light, the 3D spatiospectral phase profile is, and the amplitude one is. The complex amplitudes of- and-polarized light components unambiguously determine the 3D spatiospectral polarization state with a method different from previous approaches using metasurfaces,. The 3D spatiotemporal field profileis obtained again through Fourier transformation on, and complete light field information is obtained using Eq. (1). The data reconstruction procedure of the 3D spatiotemporal vectorial optical field is systematically illustrated in Fig. 1e, including all key calculation steps mentioned above.

To prove the concept, we first generate less structured light fields with 3D homogeneous linear, circular, and elliptical polarization states, and test the capability of resolving 3D spatiotemporal amplitude, phase, polarization, and wavelength information. An-polarized, 800 nm, 40 fs laser pulse coming from a 1 kHz Ti:Sapphire laser amplifier transmits through a half-wave plate (WPZ2325-795 from Union Optics Inc.) whose optical axis is −15° to the-direction, so the output laser field is expected to be linearly polarized along -30° to the-direction. Figure 2a shows the actual field profile along the linear polarization direction with the carrier laser frequency reduced by 0.4 times for clear illustration. Meanwhile, the polarization directions of the laser field at selected time slices are labeled by white arrows around −30° to the-direction in Fig. 2b. The 3D intensity profile has a 38 fs temporal duration.

Fig. 2 
High-dimensional one-shot optical sensing of homogeneously polarized light.

a The 3D spatiotemporal optical field profile of a femtosecond laser pulse with linear polarization −30° to the-direction. The carrier laser frequency is reduced by 0.4 times for clear illustration. b The 3D spatiotemporal polarization direction (white arrows) and intensity (color map) profiles of the linearly polarized femtosecond laser field for selected time slices. c The polarization parameterdescribing the spectral phase difference between- and-polarized components of the linearly polarized femtosecond laser pulse, the red line is for the experimental (2.17° standard deviation shown in pink area) and the blue line for the calculation results. d and e The same as b, but for right-rotating circular (d) and left-rotating elliptical (e) polarizations.

---

### Flow and pressure measurements in aneurysms and arteriovenous malformations with phase contrast MR imaging [^69e99fae]. Magnetic Resonance Imaging (2016). Low credibility.

Purpose

To explore phase contrast (PC) magnetic resonance imaging of aneurysms and arteriovenous malformations (AVM). PC imaging obtains a vector field of the velocity and can yield additional hemodynamic information, including: volume flow rate (VFR) and intravascular pressure. We expect to find lower VFR distal to aneurysms and higher VFR in vessels of the AVM.

Materials and Methods

Five cerebral aneurysm and three AVM patients were imaged with PC techniques and compared to VFR of a healthy cohort. VFR was calculated in vessel segments in each patient and compared statistically to the healthy cohort by computing the z-score. Intravascular pressure was calculated in the aneurysms and in the nidus of each AVM.

Results

We found that patients with aneurysm had z<-0.48 in vessels distal to the aneurysm (reduced flow), while AVM patients had z>6 in some vessels supplying and draining the nidus (increased flow). Pressures in aneurysms were highly variable between subjects and location, while in the nidus of the AVM patients; pressure trended higher in larger AVMs.

Conclusion

The study findings confirm the expectation of lower distal flow in aneurysm and higher arterial and venous flow in AVM patients.

---

### Mechanical power is maximized during contractile ring-like formation in a biomimetic dividing cell model [^d3be629b]. Nature Communications (2024). High credibility.

Fig. 1 
Patterned light-activation induces cell division-like membrane deformation.

a Schematic of a liposome encapsulating actomyosin. His-tagged proteins were tethered to the membrane via DOGS-NiNTA lipids embedded in the lipid bilayer. Linear F-actin was nucleated by His-mDia1 and tethered to the membrane via His-α-actinin. b Confocal slices of the actin fluorescence image in the midplane and at the bottom surface of the liposome. Similar F-actin organization was consistently obtained in more than 10 independent repeats (e.g. Fig. 4b, Fig. 5a). c Schematic of the patterned light-activation of myosin. (i) Myosin is inhibited during liposome preparation. (ii) Dissociating the actin cortex at the poles by high-power laser (405 nm) to allow membrane expansion during (iii) light-activation by 488 nm laser along the equatorial plane. d Time-lapse images showing the midplane of a light-activated liposome exhibiting cell division-like deformation. e Side view (y–z plane) and furrow (x–z plane) of a three-dimensional reconstruction of the deformed liposome. f PIV of the contracting actomyosin network (left). Yellow arrows show the total displacement, u, over 5 min with vector magnitudes normalized by the maximum. The colormap represents local strain fields (right). g Mean actin flow speed within the liposome over time (n = 5 liposomes and N = 2 independent experiments in 0 nM; n = 5 and N = 2 in 35 nM; n = 5 and N = 3 in 70 nM; n = 4 and N = 2 in 140 nM; n = 5 and N = 2 in 280 nM). h Contour shape of the liposome membrane over time. Time is color-coded. i Aspect ratioof the liposome estimated from ellipse fitting to the contour shape. j Aspect ratio over time (n = 13 liposomes and N = 3 independent experiments in 0 nM; n = 20 and N = 2 in 35 nM; n = 39 and N = 4 in 70 nM; n = 28 and N = 6 in 140 nM; n = 15 and N = 2 in 280 nM). k and l Boxplots showing the time at maximum aspect ratio (k) and maximum aspect ratio (j) (n = 13 liposomes and N = 3 independent experiments in 0 nM; n = 20 and N = 2 in 35 nM; n = 39 and N = 4 in 70 nM; n = 28 and N = 6 in 140 nM; n = 15 and N = 2 in 280 nM). Data are presented as mean ± SD (g, j) or boxplots where the interquartile range (IQR) is between Q1 (25th percentile) and Q3 (75th percentile), the center line indicates the median, whiskers are extended to Q3   +   1.5 × IQR and Q1  −  1.5 × IQR (k, l); * p <  0.05; ** p <  0.01; *** p <  0.001 in a two-sided Wilcoxon rank sum test. n.s. not significant. Scale bars, 10 μm. Source data are provided as a Source Data file.

---

### Longitudinal field controls vector vortex beams in anisotropic epsilon-near-zero metamaterials [^dd68b8a8]. Nature Communications (2025). High credibility.

Given these properties of the metamaterial, the ENZ-related extinction cannot be harnessed by plane wave illumination at normal incidence, as it does not provide a field component along the optical axis. However, linearly or circularly polarized Gaussian beams can acquire a longitudinal field upon focusing. At the same time, the longitudinal field is intrinsic for radial and other vector vortex beams even within the paraxial approximationand can be further enhanced by focusing.

The choice of the initial state of polarization of the beam before focusing allows for tailoring of the energy exchange between the transverse and longitudinal fields, governed by the requirements of divergence-free electric fields from Maxwell’s equations (Fig. 2 a). The relative contribution of the longitudinal component to the total intensity generally increases with the numerical aperture (NA) of the focusing. For a radial beam focused in free space, under low focusing conditions (NA = 0.1), the longitudinal intensity corresponds to less than 1% of the overall intensity in the focal plane (z = 0), whereas the contribution of the longitudinal field overcomes the one of the transverse field intensity at NA ≈ 0.9. As can be expected, an azimuthal beam has a null longitudinal field regardless of the NA, while a linearly polarized beam possesses a nonzero E z although never as strong as that of the radial beam.

Fig. 2 
Vector beam spectroscopy.

a, b Relative energy stored in the (solid lines) transverse and (dashed lines) longitudinal components of the electric field with respect to the total energy contained in the beam for propagation in (a) free space and (b) the metamaterial (the metamaterial parameters are as in Fig. 1 c) for (orange) radial, (purple) linear, and (blue) azimuthal polarization states, calculated in the focal plane (z = 0) with the metamaterial slab being centered on it. c – f Extinction spectra of the metamaterial obtained with focused vector beams at normal incidence for NA of 0.5, 0.7, and 0.85 (increasing with the color tone): (c, d) measured and (e, f) calculated extinction spectra of the metamaterial for (c, e) radial and (d, f) azimuthal beams and for (colored lines) electrodeposited and (greyscale lines) evaporated gold. Extinction spectra are individually normalized to their own maxima for direct comparison.

---

### Multipolar lasing modes from topological corner States [^cd0e3b30]. Nature Communications (2020). High credibility.

Fig. 3 
Corner-state topological lasers.

Optical properties of the topological quadrupole (a – c), dipole (d 1) (d – f), dipole (d 2) (g – i), and monopole lasing modes (j – l). a, d, g, j Measured mode images (left) and calculated z -components of the Poynting vectors (right). The calculation is performed at a z -position of 300 nm above the slab. Scale bars, 5 μm (left and right). b, e, h, k Measured above-threshold PL spectra. The peak wavelengths are 1539.6 nm (b), 1546.1 nm (e), 1549.9 nm (h), and 1553.9 nm (k). The spectral linewidth was resolution-limited in the spectrometer. Insets, measured output intensity of each mode as a function of the polarization angle using a linear polarizer in front of the spectrometer. 0° and 90° are the horizontal and vertical directions, respectively. c, f, i, l Measured L–L curves.

We compare the measured mode images with the calculated electric-field intensity profiles of the corner-state modes (Fig. 3a, d, g, j ; right). The measured images and the corresponding calculated images agree very well. Also, the measured and calculated resonant wavelengths are almost identical. Such good agreement between the measurements and simulations indicates that the measured modes in Fig. 3a, d, g, j correspond to the corner-state quadrupole, dipole (d 1), dipole (d 2), and monopole modes, respectively. We observe split wavelengths of the degenerate dipole corner-state modes (d 1 and d 2). The wavelength split originates from the slightly different coupling strengths between the corners due to the fabrication imperfection. However, their unique and characteristic mode profiles, such as intensity antinodes at the diagonal corners, are clearly observed in the experiment. It can be thought that the spatial symmetries are only 0.25% broken during fabrication, if we consider the small split wavelength of the degenerate dipole corner-state modes. Consequently, corner-state lasing modes spectrally located close to one another are unambiguously identified by comparing spectral imaging measurements with numerical simulation results.

---

### Rapid imaging of fluid flow patterns in a narrow packed bed using MRI [^82f0e8eb]. Magnetic Resonance Imaging (2005). Low credibility.

A gradient echo rapid velocity and acceleration imaging sequence (GERVAIS) has been developed and implemented to image liquid flow within a narrow packed bed. Two-dimensional velocity images have been acquired with an in-plane pixel size of 781 microm x 781 microm, with a data acquisition time of 20 ms for a single velocity component. Images of the x, y and z velocity vectors are reported. Data are reported for Reynolds numbers (based on particle diameter) of 200 and 300. In each case, GERVAIS images are compared with the results of a standard spin-echo phase-encoding velocity measurement. At Re = 200, steady-state flow is expected and the velocity images acquired using both techniques are consistent. At Re = 300, the GERVAIS sequence is able to image the unsteady-state flow field within this system. In contrast, the standard phase-encoding velocity measurement contains significant artefacts.

---

### Supertoroidal light pulses as electromagnetic skyrmions propagating in free space [^386e4cea]. Nature Communications (2021). High credibility.

Energy backflow and Poynting vector singularities

The topological features of electromagnetic fields in supertoroidal pulses are linked to anomalous behavior of energy flow as represented by the Poynting vector S = E × H. An interesting effect for the fundamental TLP is the presence of energy backflow: the Poynting vector at certain regions is oriented against the prorogation direction (blue arrows in Fig. 4 a). Such energy backflow effects have been predicted and discussed in the context of singular superpositions of waves,, superoscillatory light fields,, and plasmonic nanostructures. The Poynting vector map reveals a complex multi-layer energy backflow structure, as shown in Fig. 4 b. The energy flow vanishes at the positions of the electric and magnetic singularities and inherits their multi-layer matryoshka-like structure. Poynting vector vanishes at z = 0 plane, along the z -axis, and on the dual-layer matryoshka-like singular shells (marked by the black bold lines in Fig. 4 b). Importantly, energy backflow occurs at areas of relatively low energy density, and, hence, STLP as a whole still propagates forward. For the temporal evolution of the energy flow of the pulse see Supplementary Videos 4 and 5.

Fig. 4 
Poynting vector fields of toroidal and supertoroidal light pulses.

a, b Contour and arrow plots of the Poynting vector fields in the x – z plane, in logarithmic scale, for a) the fundamental TLP and b the STLP of α = 5. Panels a1 and b1 present the zoom-in plots of the regions of blue boxes in (a) and (b), respectively. Poynting vector field zeros are marked by the black solid lines and black dots. Red and blue bold arrows highlight the regions of energy forward flow and backflow, respectively. Unit for coordinates: q 1.

---

### Theory and computation of hot carriers generated by surface plasmon polaritons in noble metals [^457343aa]. Nature Communications (2015). Medium credibility.

The vector potential of the SPP wave in the metal, with unit amplitude as in the photon case, can be written in second quantized form as:

where, as in the photon case, the normalization constantcan be determined by energy considerations. We write the classical electric field associated with the SPP in the metal as. Using a result in ref. the cycle-averaged energy in the SPP field—which accounts for contributions from both the field in the dielectric and the metal—can be written as, where we defined an effective dielectric constant:

We use the correspondence principle for a quantum statewithSPP quanta. Similar to the photon case, the total energy in the SPP modecan be equated to its classical counterpart, while the square modulus of the electric fieldcan be replaced with its quantum mechanical average, with. We obtain the two equations:

By equating equations (12) and (13), and using q p, z =1/(2 L z), we obtain the normalization constant, and thus the SPP vector potential:

This vector potential is similar to the photon case, equation (7). The key differences are the decay in the z direction for the SPP field, which introduces an effective SPP volume AL z in the vector potential, the appearance of an effective dielectric constant for the medium and the fact that the polarization is transverse magnetic with a direction imposed by the properties of the metal and dielectric material.

Since the form of the SPP vector potential is completely analogous to the one for photons, the decay rate of SPPs to hot electron–hole pairs can be carried out following the same steps as in the photon case discussed above, with the substitutions V → AL z,, and allowing for a finite momentum q p with magnitude. This leads to the SPP–electron coupling matrix element in Table 1 :

---

### Mapping the velocity vector onto the spin vector: two-dimensional velocity-selective spin excitation for MR flow imaging [^ac4ec40a]. Magnetic Resonance in Medicine (2001). Low credibility.

This article presents a two-dimensional velocity-selective spin excitation (2D-VSP) method that enables quantitative imaging of motion in two directions in a single scan, without the need for image subtraction or combination. It is based on the idea of mapping a 2D velocity vector directly onto the transverse magnetization vector, such that the signal intensity reflects the speed of motion, while the signal phase represents the direction of motion. Experimental demonstration is presented in conjunction with an analysis of the accuracy of this method. VSP methods are often limited by inconsistent static signal suppression under variable shim and RF conditions. By using adiabatic RF pulses in a 2D-VSP composite that possesses time-reversal symmetry, consistent background suppression of 30-fold or higher was demonstrated over experimental conditions of +/-200 Hz off-resonance and 30% RF field variation.

---

### Injury triggers fascia fibroblast collective cell migration to drive scar formation through N-cadherin [^6712879b]. Nature Communications (2020). High credibility.

Orientation vector field analysis

Vector fields were generated using ImageJ plugin OrientationJ 2.0.4 – Vector Field. In brief, frame images of the green channel (EPFs) from intravital microscopic recording were subjected to maximum intensity projection. Substacks were created with every 10 frames of the recording. Orientation vector fields were applied with vector field grid size of 150 pixels with 100% length of scale vector. Resulting vector trajectories were converted into masks and overlaid on the original frame image.

Contour line trajectory analysis

Contour lines were derived using ImageJ plugin Interactive 3D surface plot. Maximum intensity substacks were computed using the frame images of the green channel (EPFs) corresponding to 0, 3 and 6 h of the intravital microscopic recording. These frames were subjected to 3D projection with full transparency to create a pseudo z stack. To mark the boundaries of the pseudo z stack, contour lines corresponding to leading front of the frames were overlaid and 3D surface plot were rendered. Contour lines were generated with following parameters: Grid size - full size of the image, Smoothing - 130, Lighting - 0.50 and perspective - 0.0. Resulting contour lines were displayed using standard fire lookup tables from LUT library. The gradient lines perpendicular to the contour lines are used to predict the trajectory of migrating EPF swarms.

---

### Solving the where problem and quantifying geometric variation in neuroanatomy using generative diffeomorphic mapping [^fd44f32f]. Nature Communications (2025). High credibility.

The statistical interpretation allows us to accommodate images with non reference signals, such as missing tissue, tracer injection sites, or other anomalies. At each pixel, the identity of the signal type is modeled as missing data, and maximum likelihood estimators are computed using an Expectation Maximization algorithm, which alternates between the E step: compute posterior probability π i (x) that each pixel corresponds to the reference image rather than one of the non-reference types, and the M step: update parameters by solving a posterior weighted version of the above:As an EM algorithm, this approach is guaranteed to be monotonically increasing in likelihood. An example of posterior weights are shown in the right hand column of Fig. 2 b.

Our approach uses mixtures of Gaussians to model variability in data, to allow large outliers to be accommodated by additional components, even though the Gaussian distribution itself does not have long tails. The Gaussian model allows for closed form expression (in terms of matrix inverse) for contrast transformation parameters. Other groups have used long tailed distributions to model variability and outliers in a robust manner, most notably the exponential distribution for l1 optimization. Techniques such as iteratively reweighted least squares can be applied as in Reuter et al. which lead lead to a weighted least squares problem which is similar to ours.

Nonconvex optimization with low to high dimensional subgroups and resolutions

This registration problem is highly nonconvex, and allows for many local minima. To provide robustness in our solution, we solve a sequence of lower dimensional subproblems, initializing the next with the solution to the previous. (i) 2D slice to slice rigid alignment maximizing similarity to neighbors(ii) 3D affine only alignment, registration using the full model at (iii) low (200 μm), (iv) medium (100 μm), and (v) high (50 μm) resolution. Time varying velocity fields are discretized into 5 timesteps and integrated using the Semi Lagrangian method. For most subproblems, spatial transformation parameters are estimated by gradient descent, and intensity transformation parameters are updated by solving a weighted least squares solution at each iteration. For subproblems that include linear registration only, parameters are estimated using Reimannian gradient descent (discussed in ref.and similar to a second order Gauss–Newton optimization scheme).

---

### Vectorial Doppler metrology [^74ee8230]. Nature Communications (2021). High credibility.

The Doppler effect is a universal wave phenomenon that has spurred a myriad of applications. In early manifestations, it was implemented by interference with a reference wave to infer linear velocities along the direction of motion, and more recently lateral and angular velocities using scalar phase structured light. A consequence of the scalar wave approach is that it is technically challenging to directly deduce the motion direction of moving targets. Here we overcome this challenge using vectorially structured light with spatially variant polarization, allowing the velocity and motion direction of a moving particle to be fully determined. Using what we call a vectorial Doppler effect, we conduct a proof of principle experiment and successfully measure the rotational velocity (magnitude and direction) of a moving isotropic particle. The instantaneous position of the moving particle is also tracked under the conditions of knowing its starting position and continuous tracking. Additionally, we discuss its applicability to anisotropic particle detection, and show its potential to distinguish the rotation and spin of the anisotropic particle and measure its rotational velocity and spin speed (magnitude and direction). Our demonstration opens the path to vectorial Doppler metrology for detection of universal motion vectors with vectorially structured light.

---

### Single-shot polarimetry of vector beams by supervised learning [^73dce65c]. Nature Communications (2023). High credibility.

Discussion

We have experimentally demonstrated the measurement of multiple polarizations in a single shot without polarization optics. The result has been obtained with an original method that combines physical transformation between polarization and spatial degrees of freedom with machine learning to get unprecedented information in a single detection. This approach demonstrates photonic machine learning for a challenging optical application, i.e. polarization imaging.

Our measurement scheme has no bulky optical components and can operate at any wavelength. This allows to overcome the narrowband operation of all polarization cameras based on integrated devices and metasurfaces,. In our setup, both the scattering process and the learning procedure are efficient on a broad spectrum. As the transmitted intensity distribution is highly sensitive to the incoming spectrum, we expect our polarization imaging is able to operate on broadband light by training a wavelength-dependent instrument matrix. The single-shot polarimeter is hence compact, without moving components, broadband, and does not require nanofabrication. Moreover, it provides direct access to properties of the vector field otherwise difficult to quantify, as we demonstrate by measuring the unknown number of polarizations within the vector beam. The device can be developed further by using unsupervised learning methods such as variational autoencoders that generate Stokes parameter distributions from the detected sparse data.

These findings empower compact single-shot polarimetry based on machine learning in a wide variety of contexts, from optical networking to biomedical devices. We foresee the extension of our single-shot approach to the entire electromagnetic spectrum, to subwavelength and topological optical fields, and, more generally, to other optical degrees of freedom, with applications where conventional instruments are useless, as in edge devices and photonic chips. Moreover, partitioned vector beams of quantum light can encode many qubits. Therefore, our results may also open exciting perspectives in the quantum domain, with the possibility to benefit from single-shot polarimetry by machine learning.

---

### Null space imaging: nonlinear magnetic encoding fields designed complementary to receiver coil sensitivities for improved acceleration in parallel imaging [^15c5a123]. Magnetic Resonance in Medicine (2012). Low credibility.

To increase image acquisition efficiency, we develop alternative gradient encoding strategies designed to provide spatial encoding complementary to the spatial encoding provided by the multiple receiver coil elements in parallel image acquisitions. Intuitively, complementary encoding is achieved when the magnetic field encoding gradients are designed to encode spatial information where receiver spatial encoding is ambiguous, for example, along sensitivity isocontours. Specifically, the method generates a basis set for the null space of the coil sensitivities with the singular value decomposition and calculates encoding fields from the null space vectors. A set of nonlinear gradients is used as projection imaging readout magnetic fields, replacing the conventional linear readout field and phase encoding. Multiple encoding fields are used as projections to capture the null space information, hence the term null space imaging. The method is compared to conventional Cartesian SENSitivity Encoding as evaluated by mean squared error and robustness to noise. Strategies for developments in the area of nonlinear encoding schemes are discussed. The null space imaging approach yields a parallel imaging method that provides high acceleration factors with a limited number of receiver coil array elements through increased time efficiency in spatial encoding.

---

### Design of a logarithmic k-space spiral trajectory [^3d2eeeb3]. Magnetic Resonance in Medicine (2001). Low credibility.

Spiral acquisitions are used in fast cardiac imaging because they traverse k-space efficiently and minimize flow artifacts. A variable pitch logarithmic spiral trajectory is designed to critically sample the low-frequency region in k-space and gradually undersample the high-frequency region. An approximate analytical expression for the trajectory provides a fast means to calculate the gradient waveforms and the sampled data points. A numerical method is introduced based on the trajectory curvature and the rate of change in the gradient magnitude with time for the composite Archimedean-logarithmic trajectory. The pulse sequence is implemented and images are acquired on phantoms and human hearts. The images show improved image resolution and some improvement in image quality as a result of increased extent in k-space and reduction in aliasing artifacts, respectively.

---

### Quantitative imaging metrics for the assessment of pulmonary pathophysiology: an official American Thoracic Society and Fleischner society joint workshop report [^59d10d7c]. Annals of the American Thoracic Society (2023). High credibility.

Ventilation–perfusion (V A /Q) distribution modeling is binned into 50 equally spaced (log scale) compartments, with V A /Q ratios <0.005 (shunt) and >100 (dead space) separately calculated, and relative dispersion and gravitational gradients may also be assessed.

---

### Machine learning assisted vector atomic magnetometry [^38133517]. Nature Communications (2023). High credibility.

Fig. 1 
Working principle and schematics of the single-shot all optical vector magnetometer.

a Frequency modulated elliptically polarized light interacts with the 87 Rb atom, coupling the ground state 5 2 S 1/2 (F = 2) and the excited state 5. With the direction of the total magnetic field set as the quantization axis, atomic levels exhibit Zeeman splitting. Frequency modulation of the laser gives rise to frequency sidebands with the intervals of the modulation frequency ω m near the Larmor frequency Ω L. The σ +, σ −, π components of the laser form multiple sets of EIT. b Schematics of the experiment setup. ECDL external cavity diode laser, HWP half-wave plate, QWP quarter-wave plate, PBS polarization beam splitter, PC personal computer.

To extract the vectorial information of the magnetic field from the rotation signals, we adopt an artificial Neural Network (ANN) which is a typical algorithm of ML. By mimicking the way biological neural network learns from experience, the ANN establishes a map between input signals and output results using pre-collected data, and can thus give predictions on unknown parameters, for example, here, on the direction and magnitude of an unknown B. The network weights (parameters) are updated using the gradient descent algorithmto minimize the defined loss function over the training data set. Each time when the NN goes through the whole training data set and returns new weights in the network is called an epoch. The loss decreases as the epoch number increases and the map is eventually established. In our scheme, the demodulated optical rotation signals X 1,2 and Y 1,2 are first collected for a range of field amplitudes and directions, and then are used to train the NN. In the end, an accurate map is established between the signal set (X 1, Y 1, X 2, Y 2) and the parameter set (B, θ, φ), i.e. the three-dimensional field information. Here θ is normally defined as the angle between B and the wave vector k of the laser, and φ is the azimuthal angle in the plane perpendicular to the wave vector with φ = 0 being the horizontaldirection associated with the polarization axis of the optics (Fig. 1).

---

### A novel MRI framework for the quantification of any moment of arbitrary velocity distributions [^6dcae65c]. Magnetic Resonance in Medicine (2011). Low credibility.

MRI can measure several important hemodynamic parameters but might not yet have reached its full potential. The most common MRI method for the assessment of flow is phase-contrast MRI velocity mapping that estimates the mean velocity of a voxel. This estimation is precise only when the intravoxel velocity distribution is symmetric. The mean velocity corresponds to the first raw moment of the intravoxel velocity distribution. Here, a generalized MRI framework for the quantification of any moment of arbitrary velocity distributions is described. This framework is based on the fact that moments in the function domain (velocity space) correspond to differentials in the Fourier transform domain (kv-space). For proof-of-concept, moments of realistic velocity distributions were estimated using finite difference approximations of the derivatives of the MRI signal. In addition, the framework was applied to investigate the symmetry assumption underlying phase-contrast MRI velocity mapping; we found that this assumption can substantially affect phase-contrast MRI velocity estimates and that its significance can be reduced by increasing the velocity encoding range.

---

### Perturbation method for magnetic field calculations of nonconductive objects [^75b53d21]. Magnetic Resonance in Medicine (2004). Low credibility.

Inhomogeneous magnetic fields produce artifacts in MR images including signal dropout and spatial distortion. A novel perturbative method for calculating the magnetic field to first order (error is second order) within and around nonconducting objects is presented. The perturbation parameter is the susceptibility difference between the object and its surroundings (for example, approximately 10 ppm in the case of brain tissue and air). This method is advantageous as it is sufficiently accurate for most purposes, can be implemented as a simple convolution with a voxel-based object model, and is linear. Furthermore, the method is simple to use and can quickly calculate the field for any orientation of an object using a set of precalculated basis images.

---

### Unique huygens-fresnel electromagnetic transportation of chiral dirac wavelet in topological photonic crystal [^b236d2f3]. Nature Communications (2023). High credibility.

Fig. 4 
Response of the structure with M > 0 to a chiral source with counterclockwise phase winding.

a Distribution of the strength of out-of-plane electric-field E z in the central part of the sample, which is obtained by the experimental measurements using a +2π-phase-winding chiral source located at the sample center at f = 1.43 GHz. C 6v -symmetric unit cells are marked by the dashed white lines as the guide for eye. b Distribution of the phase of the out-of-plane electric-field E z under the same condition as a. In all C 6v -symmetric unit cells (marked by the dashed black lines) the phase winds +2 π same as the source. c Distribution of local Poynting vectors obtained by the amplitude a and phase b of the out-of-plane electric-field E z. Local Poynting vectors rotate counterclockwise in individual unit cells (marked by dashed yellow lines), in the same direction of the source. d Distribution of Poynting vectors summed in individual C 6v -symmetric unit cells obtained from c. The Poynting vectors summed in individual unit cells rotate counterclockwise with respect to the sample center, same to the source, corresponding to the paramagnetic chiral response. e – h Same as a – d, but for the results obtained by the full-wave simulations at f = 1.42 GHz.

---

### Pulsed vector atomic magnetometer using an alternating fast-rotating field [^1d78845c]. Nature Communications (2025). High credibility.

Overall, the rotating magnetic field can induce dynamic heading errors in total magnetic field measurements, consisting of a static heading error component and a rotating-field-phase-dependent component. The rotating-field-phase-dependent heading error, B P D, can be eliminated either by selecting appropriate starting phases for the rotating field—ensuring the field initially aligns perpendicularly or maintains a constant angle relative to the spins with alternating start directions—or by averaging the results of four shots, as shown in Table 1. Importantly, the dynamic heading error does not affect measurement of the transverse magnetic fields, regardless of the starting phases of the rotating field.

To investigate the probe beam heading error, the sensor rotates about the y-axis within the xz-plane at an angle of α. This error can introduce a systematic effect in transverse magnetic field measurements that depends on the angle α, with its sign determined by the rotation direction of the rotating field. The measured probe heading error at ω m =  2 π ×  480 Hz is shown in Fig. 4 b, with the theoretical basis provided in Eq. (9). “Theory 1” corresponds to anti-clockwise rotations (Shots 1 and 3 in Table 1), given by, while “Theory 2” represents clockwise rotations (Shots 2 and 4 in Table 1), given by. The probe beam heading error can be effectively canceled by averaging the measurements from two opposite rotating field directions.

The alternating fast rotating magnetic field can generate an eddy current in the electrically conductive magnetic shield. In our four-shot scheme, which alternates the rotation direction, there are two switches within four shots, as shown in Fig. 2. We found that the way the rotating magnetic field is altered affects the eddy current and its induced magnetic field. When the direction of the rotating field changes at the peak values of the field—from negative maximum to positive maximum and vice versa—we refer to this as “Peak-Altering” (Fig. 2, top left). In this case, the average magnetic field caused by the eddy current equals zero. However, if the direction change occurs when the rotating magnetic field is at zero, termed “Zero-Altering” (Fig. 2, top right), it leads to a significant magnetic field caused by the eddy current.

---

### Supertoroidal light pulses as electromagnetic skyrmions propagating in free space [^bf79b728]. Nature Communications (2021). High credibility.

Magnetic field singularities

The magnetic field of STLPs has both radial and longitudinal components,, which lead to a topological structure more complex than the one exhibited by the electric field. Figure 3 comparatively shows the instantaneous magnetic fields for the TLP and the STLP of α = 5. For the fundamental TLP (Fig. 3 a), the magnetic field has ten different vector singularities on the x – z plane, including four saddle points on z -axis and six vortex rings (the surrounding vector distribution forming a vortex loop) away from the z -axis. We note that we only consider the singularities existed at an area containing 99.9% of the energy of the pulse. While the singularity existed at the region far away from the pulse center with nearly zero energy can be neglected. The magnetic field distribution in the vicinity of the singularities is shown in more detail in Fig. 3 a1. Due to the axial symmetry of the pulse, the three singularities away from the z -axis correspond to three rings with vortices rotating clockwise (z = 0) or counter-clockwse (z > 0 and z < 0). For instance, Fig. 3 a2 presents the magnetic field distribution in the z = 0 plane, where the orientation of the magnetic field changes from parallel to the z -axis within the vortex ring to anti-parallel outside the singularity ring. For the STLP (Fig. 3 b), more vector singularities are unveiled in the magnetic field with six saddle points on z -axis and six off-axis singularities. The singularity structure of the STLP is presented in Fig. 3 b1. The orientation of the magnetic field around the on-axis saddle points is alternating between “longitudinal-toward radial-outward point” and “radial-toward longitudinal-outward”, similarly to the on-axis singularities of the TLP. Moreover, the off-axis singularities at z = 0 become now saddle points contributing to the singularity ring in the z = 0 plane. The remaining off-axis singularities are accompanied by clockwise and counter-clockwise magnetic field configurations at x > 0 and x < 0, respectively as shown Fig. 3 b2.

---

### Analysis and correction of gradient nonlinearity and B0 inhomogeneity related scaling errors in two-dimensional phase contrast flow measurements [^65058011]. Magnetic Resonance in Medicine (2005). Low credibility.

Phase contrast flow measurements will be increasingly biased at eccentric positions, where nonlinearity of gradients and inhomogeneity of the main field become important. In theory, they scale the result of phase contrast flow values in two ways: incorrect velocity encoding of moving spins and geometric distortion of the vessel cross-sectional area. A flow phantom, consisting of a 3D grid of interconnected tubes, was used to determine the spatial dependence of the associated scaling factors, which demonstrate that scaling errors in flow can be as large as 20% within the examined volume of 336 x 336 x 336 mm(3). The same phantom was also used to determine and minimize concomitant gradient effects. Correction of the off-center flow values with the local scaling factors and the concomitant gradient phase improves the measurement accuracy substantially, both in the flow phantom and in a volunteer study.

---

### Pulsed vector atomic magnetometer using an alternating fast-rotating field [^b1c62a2d]. Nature Communications (2025). High credibility.

We introduce a vector atomic magnetometer that employs a fast-rotating magnetic field applied to a pulsed 87 Rb scalar atomic magnetometer. This approach enables simultaneous measurements of the total magnetic field and its two polar angles relative to the rotation plane. Operating in gradiometer mode, the magnetometer achieves a total field gradient sensitivity of 35 <mml:math xmlns:mml="http://www.w3.org/1998/Math/MathML"><mml:mi>fT</mml:mi><mml:mo>/</mml:mo><mml:msqrt><mml:mrow><mml:mi>Hz</mml:mi></mml:mrow></mml:msqrt></mml:math> (0.7 parts per billion) and angular resolutions of 6 <mml:math xmlns:mml="http://www.w3.org/1998/Math/MathML"><mml:mi>nrad</mml:mi><mml:mo>/</mml:mo><mml:msqrt><mml:mrow><mml:mi>Hz</mml:mi></mml:mrow></mml:msqrt></mml:math> at a 50 μT Earth field strength. The noise spectra remain flat down to 1 Hz and 0.1 Hz, respectively. Here we show that this method overcomes several metrological challenges commonly faced by vector magnetometers and gradiometers. We propose a unique peak-altering modulation technique to mitigate systematic effects, including a newly identified dynamic heading error. Additionally, we establish the fundamental sensitivity limits of the sensor, demonstrating that its vector sensitivity approaches scalar sensitivity while preserving the inherent accuracy and calibration benefits of scalar sensors. This high-dynamic-range, ultrahigh-resolution magnetometer offers exceptional versatility for diverse applications.

---

### Validation of V-SS-PARSE for single-shot flow measurement [^f1569ac0]. Magnetic Resonance Imaging (2007). Low credibility.

As a variant of Single-Shot Parameter Assessment by Retrieval from Signal Encoding, Velocity Single-Shot Parameter Assessment by Retrieval from Signal Encoding, a single-shot imaging method, has been developed to realize fast and straightforward flow quantification by solving inverse problems. A robust signal model, including its local magnetization and its phase evolution during signaling (resulting in a more precise representation of the sampled signal) is described here. Magnitude, velocity, relaxation rate and frequency information can be retrieved without any extra reference image acquisitions, as demonstrated by phantom studies. In the presence of stationary background, retrieved magnitude maps and velocity maps show results comparable to those obtained by phase-contrast methods (r>.99, P=.005), even with brief single-shot 70-ms acquisition.

---

### Olivar: towards automated variant aware primer design for multiplex tiled amplicon sequencing of pathogens [^96579dc1]. Nature Communications (2024). High credibility.

Calculation of sequence complexity

Sequence complexity is calculated based on Shannon’s entropy. For a DNA sequence S of length L (L > 3) with alphabet {A, T, C, G}, the number of each k -mer (k = 1, 2, 3) is stored as an arraywhere m i (i = 0, 1, …, n) is the number of a certain k-mer, and n = 4 k. For example, if S = ACGCAGCGAGCAG, then c 1 = [4, 4, 5] since there are 4 ‘A’s, 4 ‘C’s and 5 ‘G’s. Then,where e k is the dot product of the two vectors. The complexity of S is the smallest of e 1, e 2 and e 3.

Optimization of PDRs

PDRs are regions where primer candidates are generated, and primer candidates are subsequences of a PDR. A PDR is defined by its start coordinate p and stop coordinate p + l − 1 (closed interval), where l is the length of the PDR (40 by default). All PDRs have the same length. The risk of the PDR is then defined as sum(r [p : p + l − 1]), where r is the risk array.

Generation of one PDR

Each PDR is randomly selected within a certain region C (Supplementary Fig. 12, also see green boxes in Fig. 2 a), the length of C is greater than or equal to l. The risk of all possible PDRs within C is calculated, and PDRs with risk below X th percentile are considered candidate PDRs. Here percentile is defined as a PDR risk threshold below which percentage X of PDRs fall. In short, not all possible PDRs within region C is included for random selection, and the worst PDRs are excluded to accelerate the optimization process. Therefore, a lower X means a more stringent selection on PDR candidates. X is set to 30 by default to balance optimization efficiency and effectiveness (Fig. 2). This is also discussed in “Optimization of PDRs” in Results.

---

### Longitudinal field controls vector vortex beams in anisotropic epsilon-near-zero metamaterials [^0f1b9b12]. Nature Communications (2025). High credibility.

When focused inside the metamaterial, a monochromatic radial beam at a wavelength corresponding to the ENZ condition, acquires a stronger longitudinal field exceeding the transverse field intensity at the much lower NA = 0.4 (Fig. 2 b) due to the metamaterial anisotropy, suggesting the possibility to generate a relatively stronger longitudinal component with less focused beams. Similar observations can be made for the linearly polarized beam, while for the azimuthally polarized beam, the longitudinal component keeps the zero value. This effect is strongly wavelength-dependent because of the drastically different interaction between the longitudinal field and the metamaterial in the different dispersion regimes. While the anisotropy increases in the hyperbolic regime compared to the elliptic one, only the ENZ regime produces a strong damping of the longitudinal field.

This behavior can be directly visualized in the extinction spectra of the radial and azimuthal beams (Fig. 2). Broadband vector vortex beams can be generated by exploiting a glass cone with a 90° aperture. Double total internal reflection of a circularly polarized beam on the conical surface of the mirror creates a non-uniform state of polarization. Radial and azimuthal beams can be obtained from that state by rotating an additional half-waveplate placed after the cone (see “Methods” for more details). Broadband vector beams generated with the described technique were used to implement vector-beam-based spectroscopy (see “Methods”). The measured spectra reveal a significant extinction of the radial beam at normal incidence in the ENZ regime (at approximately 650 nm), which is related to the interaction of the longitudinal field component of the beam with the metamaterial ENZ response. The extinction also increases with a stronger focusing responsible for a stronger longitudinal field along the optical axis of the metamaterial, which exhibits the ENZ behavior (Fig. 2 c). On the contrary, the azimuthal beam does not carry any longitudinal electric field components irrespective of the focusing. Therefore, azimuthally polarized beams are not affected by the ENZ regime, which influences only the field along the metamaterial axis. This results in the different extinction spectra of radial and azimuthal beams by the metamaterial in the ENZ region (Fig. 2 d). Therefore, in the ENZ regime, the metamaterial sensitivity to the angle of incidence shown with plane waves (Fig. 1d–f) can be transformed in a polarization structure sensitivity in the case of strongly focused vector vortex beams. In the experimental extinction spectra obtained with radial beam illumination, the ratio of the magnitudes of the ENZ peak to the T-peak is more than double its theoretical estimate (Fig. 2c, e). Comparing the extinction spectra for the electrodeposited and evaporated gold, one can see that while the widths of the extinction peaks are considerably smaller in the latter case, their magnitudes remain essentially the same, which was not observed for the plane wave case (Fig. 2 e, f). These observations could be an indication of the interconnected nature of the transverse and longitudinal fields in the vector beam.

---

### Theoretical hydraulic consequences of vein graft taper [^e3d25f07]. Journal of Vascular Surgery (2003). Low credibility.

Objective

Internal diameter is a strong predictor of patency of infrainguinal vein grafts. However, most vein grafts are tapered, with variable diameter along their length. It is unknown which diameter is most important in determining graft resistive properties, that is, its mean diameter, minimum diameter, or some geometric combination thereof. The purpose of this analysis was to examine the hydraulic consequences of vein graft tapering, with longitudinal impedance (Z(L)), a conduit-specific measure of pulsatile resistance along straight rigid tubes.

Methods

Proximal and distal graft pressure, pressure gradient (DeltaP), and blood flow (Q) were measured intraoperatively in a 100 cm bypass graft and digitally recorded for 10 seconds at 200 Hz. With the Womersley solution for fully developed fluid flow in a rigid tube, a series of DeltaP waveforms were generated for graft diameters ranging from 1.2 to 8.2 mm. With an axisymmetric form of the Navier-Stokes equations, a second series of DeltaP waveforms were computed for grafts with long smooth symmetric tapers ranging from 0% to 90%, with geometric mean diameter of 3.2, 4.2, and 5.2 mm (%Taper = 100 x [proximal diameter - distal diameter]/proximal diameter). For each set of DeltaP and Q, Z(L) was calculated as DeltaP/Q, plotted over a range of 8 Hz, and integrated over 4 Hz to yield integral Z(L).

Results

The architecture of the calculated DeltaP and Z(L) waveforms closely approximated their measured counterparts, validating the method. As expected, Z(L) was highly diameter-dependent in a nonlinear fashion. With a clinically relevant boundary of less than 50 x 10(3) dyne/cm(5) as "acceptable," the minimum acceptable diameter of nontapered 100 cm bypass conduits was 4.3 mm. Analysis of graft taper revealed that small amounts of taper in large conduits were well-tolerated. For example, introduction of 32% taper in a 5.2 mm graft (6.2 mm --> 4.2 mm) caused only an 8% increase in integral Z(L) (from 32 to 35 x 10(3) dyne/cm(5)). More pronounced taper in smaller conduits rendered them unacceptable. For example, 53% taper of a 4.2 mm graft (5.7 mm --> 2.7 mm) created a conduit with integral Z(L) of 70 x 10(3) dyne/cm(5), well above the acceptable limit. The relationship between Z(L) and percent taper was nonlinear and strongly dependent on mean diameter.

Conclusions

The relationship between Z(L) and diameter in vein grafts is nonlinear; thus Z(L) increases rapidly in conduits smaller than 4 mm. Tapered vein grafts behave hydraulically like nontapered grafts, provided their geometric mean is greater than 4 mm and their degree of taper is less than 40%. Tapered veins are satisfactory conduits for long-segment bypass grafts, provided their mean diameter is acceptable.

---

### K-mer analysis of long-read alignment pileups for structural variant genotyping [^ec73b2ac]. Nature Communications (2025). High credibility.

Methods

Kanpig algorithm

K-mer vectors

Variant sequences are encoded as k-mer vectors. Let n be the set of nucleotides n = {A, G, C, T} and the function E be the two-bit encoding of each element of n such that A = 0; G = 1; C = 2; T = 3. Let S be a string of nucleotides with length l such that S = n 0, n 1, n 2,… n l-1. A k-mer K of size k is a substring of S beginning at 0-based position i and defined as K ki (S) = n i, n i+1,.n i+k-1. K-mer vectors (V) hold the counts of all k-mers inside of a string of nucleotides. Each possible k-mer combination of n can map to a unique index j of a conceptual array V with size | n | k. The index j of K k0 can be calculated using a left bitshift operation (<<) and the formula:

As an example, j of the first 3-mer for the sequence “CAGT” is:

V j is then incremented. Next, for every n from S k.l-1, we alter j via

This operation updates j by first masking (m) the two leftmost bits, left-shifting the remaining bits twice, and adding the current nucleotide’s encoding before again incrementing V j. For the example sequence “CAGT”, the second 3-mer’s j is 7 (binary 000111). Sequences shorter than k cannot be vectorized and therefore return a vector of all zeros.

---

### Longitudinal field controls vector vortex beams in anisotropic epsilon-near-zero metamaterials [^0010e0b5]. Nature Communications (2025). High credibility.

Typically, longitudinal components are present in guided or strongly focused electromagnetic fields and responsible for their transverse spin –. This unusual property, which may be present even in unpolarized light, is an origin of many counterintuitive effects, such as directional scattering, unidirectional coupling to waveguides, lateral optical forces, and photonic topological structures –. The longitudinal field of vector beams has a profound impact on their scattering properties when they interact with matter. In the case of individual nanoparticles, it induces dipoles in the direction of the beam propagation and, therefore, is scattered in the directions normal to the incident wave vector.

Different techniques have been developed for the generation and manipulation of vector vortex beams –, including the use of static phase plates and liquid crystal cells –, as well as spatial light modulators,. It is also possible to generate vector beams from a non-monochromatic source, exploiting the total internal reflection from a glass cone. Metamaterials and metasurfaces with spatially varying distribution of meta-atoms, which imprint the required phase distribution on an incoming optical field, have also been recently shown to provide an excellent platform for the generation and manipulation of structured beams –, potentially easing their integration into photonic devices.

In this paper, we experimentally and theoretically demonstrate that strongly anisotropic metamaterials–here realized as a two-dimensional array of gold nanorods–can be used to modify the polarization structure and modal content of vector beams, exploiting the drastic difference in the metamaterial response to transverse and longitudinal components of the electric field. When vector vortex beams propagate in such media, the balance between longitudinal and transverse electric field components is broken by anisotropic absorption, requiring the redistribution of the energy between these field components, in order to sustain the propagation. This is especially pronounced in the epsilon-near-zero (ENZ) regime of the metamaterial dispersion for focused radial beams at normal incidence propagating along the optical axis, since the effect on the longitudinal field component is the strongest. Under these conditions, the evolution of the energy distribution between the transverse and longitudinal field components of the vector beam results in the filtering of high-order modes of the beam induced by the focusing and, therefore, diffraction suppression. The understanding of the interaction of vector beams with anisotropic metamaterials opens up new opportunities for applications of polarized beams and nanostructured materials in optical trapping, information encoding, and biochemical sensing.

---

### Multiphase flow detection with photonic crystals and deep learning [^3c40760a]. Nature Communications (2022). High credibility.

Predictions of phase fractions with deep neural network

Next we assess the capability of an open-source machine learning algorithm to analyze the microwave transmission measurements (e.g. as shown in Fig. 2), from lab experimental data to simulated data. Prior to settling on this data analytics approach, we considered various statistical methods,, effective medium theory, and physics-based computational inversion as potential means to analyze our microwave transmission measurements. These approaches faced many challenges which precluded our ability to predict the flow characteristics with requisite accuracy. We quantify the accuracy of the data analytics model prediction using prediction accuracy and R 2. In this context, prediction accuracy is the ratio of the number of exactly correct predictions to the total number of data points, and R 2 is 1 minus the ratio of variability in the difference between the model predictions and the data, and the variability in the data (see Methods for more detail on prediction accuracy andscore). With these statistics we assessed the accuracy of several linear machine learning algorithms, such as random forests and support vector machine. Like the conventional analytical techniques these analyses failed to yield the accuracy (e.g. a prediction accuracy of over 98% or ascore over 0.95) required to render these techniques competitive with current technology. Next we turned to Feed Forward Neural Network to train, classify and perform blind tests of 100 experimental measurements consisting of varying the fraction of oil-filled holes in the PC in the range 0–100%. The spectra collected for 360 transmission angles equally spaced over the range 0-360° were randomly split into a set of 80/20 non-overlapping training and blind test data, respectively. Each training dataset consists of the transmission coefficient spectra for one or more incident angles. In the example shown in Fig. 3a, one set of training input data includes a single transmission coefficient spectrum at a specific incident angle of an experimental polar intensity plot. The training dataset along with data labels (fractions of oil) are fed into a supervised Machine Learning classifier through Feed Forward Neural Network to build a training model (see Methods for more details). The accuracy of the training model is then tested on the blind test data. The 2D probability histogram (similar to Confusion Matrix; see Methods) in Fig. 3a shows the prediction accuracy for all the test data predicted with the trained neural network model. The overall prediction accuracy is 99.5%. Also it is particularly significant that after training the neural network model, the phase fraction prediction takes milliseconds, thus this approach enables real-time predictions for industrial applications. (See Methods)

---

### Time reversed optical waves by arbitrary vector spatiotemporal field generation [^e61f1ce3]. Nature Communications (2020). High credibility.

Lossless linear wave propagation is symmetric in time, a principle which can be used to create time reversed waves. Such waves are special "pre-scattered" spatiotemporal fields, which propagate through a complex medium as if observing a scattering process in reverse, entering the medium as a complicated spatiotemporal field and arriving after propagation as a desired target field, such as a spatiotemporal focus. Time reversed waves have previously been demonstrated for relatively low frequency phenomena such as acoustics, water waves and microwaves. Many attempts have been made to extend these techniques into optics. However, the much higher frequencies of optics make for very different requirements. A fully time reversed wave is a volumetric field with arbitrary amplitude, phase and polarisation at every point in space and time. The creation of such fields has not previously been possible in optics. We demonstrate time reversed optical waves with a device capable of independently controlling all of light's classical degrees of freedom simultaneously. Such a class of ultrafast wavefront shaper is capable of generating a sequence of arbitrary 2D spatial/polarisation wavefronts at a bandwidth limited rate of 4.4THz. This ability to manipulate the full field of an optical beam could be used to control both linear and nonlinear optical phenomena.

---

### Top-down perceptual inference shaping the activity of early visual cortex [^da4bf629]. Nature Communications (2025). High credibility.

Identifying active model units

In a given model, we classified Z 1 and Z 2 model units into active and inactive categories based on four criteria (Supplementary Fig. 3). (1) Variance of the mean response to the images in the ‘test’ natural image dataset was found to be orders of magnitude larger for active units than for inactive units. (2) Mean of the response variance (uncertainty) over the same image dataset also creates two clean clusters for active and inactive units. (3) Mean squared pixel intensities of receptive fields are clearly larger for active units than for inactive units. (4) Mean squared pixel intensities of projective fields are also larger for active units than for inactive units. We found that these four criteria consistently cluster units into the same active and inactive sets (for TDVAE, see Supplementary Fig. 3). The number of active Z 1 and Z 2 units is denoted in Supplementary Table 3 for all discussed models. In the paper we only consider active model units.

Z 1 receptive fields in single-layer and hierarchical models

Learned Z 1 receptive fields are localized, oriented and bandpass in both the hierarchical TDVAE model and the single-layer shallow-VAE model (Supplementary Figs. 4, 5). We calculated two quantities for each active Z 1 unit for a more detailed comparison: filter center (estimated as the center of mass of the pointwise squared receptive field) and dominant wave vector (calculated from the maximum position of the squared magnitude of the Fourier transform of the receptive field). To increase the precision of these estimates, we used projective fields instead of receptive fields as they are very similar but less noisy (Supplementary Fig. 5). We found that the empirical distribution of filter centers and dominant wave vectors are very similar in the TDVAE and shallow-VAE models, making them equivalent complete bases in the space of natural training images, at least in terms of first-order probability densities.

---

### Longitudinal field controls vector vortex beams in anisotropic epsilon-near-zero metamaterials [^b1509e4f]. Nature Communications (2025). High credibility.

Structured light plays an important role in metrology, optical trapping and manipulation, communications, quantum technologies and nonlinear optics. Here, we demonstrate an alternative approach for the manipulation of vector beams carrying longitudinal field components using metamaterials with extreme anisotropy. Implementing vectorial spectroscopy, we show that the propagation of complex beams with inhomogeneous polarization is strongly affected by the interplay of the metamaterial anisotropy with the transverse and longitudinal field structure of the beam. This phenomenon is especially pronounced in the epsilon-near-zero regime, exclusively realised for light polarized along the metamaterial optical axis, strongly influencing the interaction of longitudinal fields with the metamaterial. The requirements on the balance between the transverse and longitudinal fields to maintain a polarization singularity at the beam axis allow control of the beam modal content, filtering diffraction effects and tailoring spatial polarization distributions. The understanding of the interaction of vector beams with metamaterials opens new opportunities for applications in microscopy, information encoding, biochemical sensing and quantum technologies.

---

### Probabilistic embedding, clustering, and alignment for integrating spatial transcriptomics data with PRECAST [^65a9b5c6]. Nature Communications (2023). High credibility.

Following this, we generated domain-relevant latent features z r i in the model (5) from the conditional Gaussian distribution, such that z r i ∣ y r i = k ~ (μ k, Σ k), where z r i ∈ R q with q = 10. Structures for μ k and Σ k are shown in Supplementary Data 8. Next, we generatedwith each, performed QR decomposition onsuch that, and assigned, which is a column orthogonal matrix. Then, we generated a batch-loading matrix W r by generatingwith,,, andwith,,. In a similar manner to the generation of W, we performed orthogonalization ofto generate W r. Next, we generated ζ r i in the model (5) bysuchwith σ 1 = 1, σ 2 = 2 and σ 3 = 0.5, where b s c a l e controlled the scales of batch effects. Here, we considered three scales of batch effects, corresponding to low, middle and high, by taking the value of 1, 2, or 3 for b s c a l e, respectively.

Next, we generated a high-dimensional normalized expression matrix using x r i = τ r + W (z r i + ν r i) + W r ζ r i + ε r i, τ r j ~ N (0, 4), ε r i ~ N (0, Λ r), where τ r j is the j -th element of τ r, Λ r = diag(λ r j), j = 1,…, p, λ 1 j = 2(1 + 1.5∣ z 1 j ∣) with; λ 2 j = 2(1 + z 2 j) with; and λ 3 j = 2(1 + 2 z 3 j) with. Finally, we generated raw gene expressionsusing. The term ε r i makes the distribution ofover-dispersed, which better imitates the properties of count expression. In this scenario, for each sample r, we only observed the raw expressionof gene j and spot i and spatial coordinates s r i for spot i.

---

### Using grid cells for navigation [^fac508c8]. Neuron (2015). Low credibility.

Discussion

We have described an algorithmic solution to the computational problem of large-scale vector navigation with grid cells. That is, how to accurately compute translation vectors between arbitrary locations in large-scale 2D space using the grid cell representations of those locations. This problem is the inverse of that thought to be performed by grid cells during path integration—extracting the translation vector between current and goal locations, as opposed to combining a previously known location with a subsequent movement vector to estimate the current location. Specifically, we have shown how the spatial phases of activity in grid cell modules of different spatial scales at start and goal locations can be used to extract the distance and direction between those locations. This is achieved by finding the maximum slope of a plane that fits the family of points defined by the phase difference in each grid module and the inverse scale of that module on at least two non-collinear axes (Figure 4 C). Importantly, this solution is robust to differences in grid orientation between grid modules and ellipticity (i.e. differences in scale between axes) within each grid module. This solution relates to the Fourier shift theorem, whereby the 2D translation applied to a basis set of Fourier components can be recovered from the phase changes across components.

We have also described several neural network implementations of this algorithmic solution, building on a large body of previous work that has explored how grid cells efficiently encode location and might contribute to vector navigation. These models assume only that the grid representations of current and goal locations are known and produce direct vectors between those locations that may traverse previously unknown terrain. Each proposed implementation can decode 2D translation vectors with an accuracy and range that is comparable to the theoretical capacity of the grid cell system, and each model offers specific strengths, weaknesses, and experimental predictions. Several computational implementations that make use of the Chinese Remainder Theorem to perform this conversion have previously been proposed. These models have limitations, however, such as requiring a hard-wired energy landscape or readout weights, producing linear outputs that are only correct modulo the lowest common multiple of grid scales or performing gradient descent on an energy landscape with multiple local minima.

---

### Two-edge-resolved three-dimensional non-line-of-sight imaging with an ordinary camera [^cb69ea4e]. Nature Communications (2024). High credibility.

The second step of the reconstruction approach aims to fit a new accurate range for each identified cluster, shown in Fig. 2 d, by operating on greyscale mappings of the RGB observations and radiosities estimated in the first step. Assumingclustersare computed, for each cluster j we form a greyscale radiosity vectorby setting to zero entries incorresponding to surface elements not present in cluster, with j = 1, 2, …, J. (See the Supplementary Note 4 (S4.1) for more details on this step.) With their angular extents fixed, the clusters collectively produce a contribution to the measured photograph that depends non-linearly on their respective unknown rangesand constituent surface elements (i.e.). The greyscale photograph y grey computed as the sum of the three colour channels is related to the unknown cluster scalar rangesand the estimated vector of radiositiesby:with matrix-vector form, where the weighting factors w j ’s allow the radiosity of each cluster to vary correspondingly when estimating their unknown continuous-valued ranges arranged into the J -dimensional vector,, andis a matrix whose (m, j)-entry models the contribution of cluster j to measurement pixel m. The vectors v, n, b and matrix B are defined as before. We estimate the ranges of all J clusters by solving the optimisation problem, using an accelerated projected gradient algorithm which is detailed in Supplementary Note 4 (S4.1). As confirmed by our FI analyses detailed in Supplementary Note 2, choosing to estimate a single range for each clusterleads to a better-conditioned inverse problem because J ≪ N θ N ψ, compared to the alternative approach that attempts to recover a range for every surface element. Using the estimated ranges, visualised in Fig. 2 e with the corresponding clusters, to construct the forward model, the final 3D full-colour reconstruction (depicted in Fig. 2 f) of the hidden scene is computed by solving the total variation regularised problem:for each of the three colour channels. The total variation seminorm denoted asis used here to encourage piecewise smooth solutions, whilecontrols the trade-off between data consistency and piecewise smoothness. One may bypass the total-variation-constrained reconstruction and directly combine the recovered ranges with the initial full-colour shape reconstructions (in Fig. 2 c) to obtain the fully 3D colour reconstruction of the hidden scene. This simplified variant of TERI which achieves impressive results at comparably lower computational complexity and three alternative reconstruction approaches are investigated in Supplementary Note 6. A narrated overview of the reconstruction procedure is provided in Supplementary Movie 1.

---

### Pulsed vector atomic magnetometer using an alternating fast-rotating field [^59a5ec5d]. Nature Communications (2025). High credibility.

Results

Spin dynamics

The complete description of spin evolution involves density matrix theory. When ground states are distributed according to spin temperature, spin evolution can be effectively described by the Bloch equations,.where γ represents the gyromagnetic ratio, P is spin polarization, and B is magnetic field. The approximation of rotation matrices is utilized to assess spin evolution in the rotating frame, enabling the derivation of analytical solutions to the time-dependent Bloch equation.

As shown in Fig. 1, we assume the spins are fully polarized along the negative y-axis. The magnetic field initially points along the z-axis, while a rotating field originates from the x-axis and rotates counterclockwise in the xy-plane. We have,, and ∣ ϕ x − ϕ y ∣  = π /2. For this assumption, ϕ x = π /2 and ϕ y =  0. We consider the behavior of polarization in a magnetic field, where it undergoes precession in response to the applied field. This magnetic field is composed of both a static and a rotating component. In the presence of these components, the polarization vector evolves according to specific rotations. The spin evolution, without considering spin relaxations, can be expressed as:whereis a 3D rotation matrix for an anti-clockwise rotation of ϕ degrees around the vector v. In the co-rotating reference frame, the effective field after applying the rotating wave approximation is given by. Here,,andare the unit vectors along the x, y and z axes, respectively. We define θ = ω m t and. Eventually, the spin projections can be written as:where. By inserting residual transverse magnetic fields b x and b y into Eq. (2), we can getwhere. The residual magnetic fields in the x-direction, b x, and y-direction, b y, are proportional to the amplitudes of the first harmonic,and, respectively, in the phase shift. The conversion factor for converting from the amplitude of the phase shift to the transverse magnetic field is given by(Table 1 details the sign dependence for b x and b y across various starting phases). Thus, by analyzing the phase shifts of the Larmor precession signal under the fast rotating field, we can measure both the transverse magnetic fields and the total magnetic field.

---

### Optimal design of k-space trajectories using a multi-objective genetic algorithm [^9fca0db2]. Magnetic Resonance in Medicine (2004). Low credibility.

Spiral, radial, and other nonrectilinear k-space trajectories are an area of active research in MRI due largely to their typically rapid acquisition times and benign artifact patterns. Trajectory design has commonly proceeded from a description of a simple shape to an investigation of its properties, because there is no general theory for the derivation of new trajectories with specific properties. Here such a generalized methodology is described. Specifically, a multi-objective genetic algorithm (GA) is used to design trajectories with beneficial flow and off-resonance properties. The algorithm converges to a well-defined optimal set with standard spiral trajectories on the rapid but low-quality end, and a new class of trajectories on the slower but high-quality end. The new trajectories all begin with nonzero gradient amplitude at the k-space origin, and curve gently outward relative to standard spirals. Improvements predicted in simulated imaging experiments were found to correlate well with improvements in actual experimental measures of image quality. The impact of deviations from the desired k-space trajectory is described, as is the impact of using different phantoms.

---

### Spin dephasing under nonlinear gradients: implications for imaging and field mapping [^eaf2803c]. Magnetic Resonance in Medicine (2012). Low credibility.

This work examines the prototypical MR echo that would be expected for a voxel of spins evolving in a strong nonlinear field, specifically focusing on the quadratic z(2) - ½(x(2) + y(2) ) field. Dephasing under nonlinear gradients is increasingly relevant given the growing interest in nonlinear imaging, and here, we report several notable differences from the linear case. Most notably, in addition to signal loss, intravoxel dephasing under gradients creating a wide and asymmetric frequency distribution across the voxel can cause skewed and nonlinear phase evolution. After presenting the qualitative and analytical origins of this difference, we experimentally demonstrate that neglecting these dynamics can lead to significant errors in sequences that assume phase evolution is proportional to voxel frequency, such as those used for field mapping. Finally, simplifying approximations to the signal equations are presented, which not only provide more intuitive forms of the exact expression but also result in simple rules to predict key features of the nonlinear evolution.

---

### Tensorial neutron tomography of three-dimensional magnetic vector fields in bulk materials [^b00baccf]. Nature Communications (2018). Medium credibility.

Knowing the distribution of a magnetic field in bulk materials is important for understanding basic phenomena and developing functional magnetic materials. Microscopic imaging techniques employing X-rays, light, electrons, or scanning probe methods have been used to quantify magnetic fields within planar thin magnetic films in 2D or magnetic vector fields within comparable thin volumes in 3D. Some years ago, neutron imaging has been demonstrated to be a unique tool to detect magnetic fields and magnetic domain structures within bulk materials. Here, we show how arbitrary magnetic vector fields within bulk materials can be visualized and quantified in 3D using a set of nine spin-polarized neutron imaging measurements and a novel tensorial multiplicative algebraic reconstruction technique (TMART). We first verify the method by measuring the known magnetic field of an electric coil and then investigate the unknown trapped magnetic flux within the type-I superconductor lead.

---

### Carrier-envelope phase on-chip scanner and control of laser beams [^1b896baf]. Nature Communications (2023). High credibility.

Model for calculating CEP spatial maps

To model the ΔCEP(x, y, z) spatial map, we used an analytical formula from:wherewith a radial coordinateand z being the distance along the optical axis. We use the Eq. (2) in Figs. 3 – 5 as well as for selected cases of C r and g in the Supplementary information. The model clearly shows how the parameters g, γ or C r (representing the first approximation of the spectral characteristic of the laser beam) can modify the CEP evolution in space.

Relation between pupil function and CEP

We showed that a shaping of the phase front of the pupil function with SLM can affect the CEP landscape. We would like to comment on the relationship between the pupil function and the CEP distributions around the laser focus. Although the SLM does not affect the CEP directly, it adds phase to the laser beam wavefronts which in turn is added to the focal phase distribution. Mathematically speaking, the distribution of the electric field in the focal plane is a Fresnel integral over the pupil function. Thus, shaping the pupil function has the potential to change the intensity and phase distribution about the focal plane. Clearly, the CEP phase is not just the phase of the wavefront, but it results from its relation to the pulse-front surfaces. Therefore, the complete relationship between the pupil function and the focal CEP phase requires demanding spatiotemporal modeling that is beyond the scope of this paper. Here, we decided to overcome this complexity and for the sake of proof-of-principle experiments, we do not aspire to prove the relationship between the pupil function and the focal CEP phase, but we intend to show that it is possible to realize a feedback loop where step-by-step optimization of a pupil function leads to a desired CEP phase distribution in the focus.

---

### Genomic prediction in a small barley population can benefit from training on related populations [^a045705e]. G3 (2025). Medium credibility.

GP models

GP was performed within the 6RW population and by multipopulation GP where a distinct barley population, 2RW, 6RS, or 2RS, was included in the training set used for fitting the model. The models applied in this study are modified versions of the models described in. For prediction within the 6RW population, the applied model can be written as follows:

Here, y is a vector containing the observed phenotypes; µ is the intercept of the model; l is a vector containing the fixed effects associated with year × location × trial, where trial is nested within population; h is a vector of the fixed effects associated with the different heterotic groups (B or R); g a is a vector of SNP-based genomic breeding values for lines with, where G is the genomic relationship matrix andis the additive genetic variance; g l is a vector containing the residual line effects that is not captured by the additive marker effects in,; w is a vector of additive genetics × environment interaction effects with, where environments are nested within population; v is a vector of nonadditive genetics × environment interaction effects with; s is a vector of spatial effects within the field whereThe spatial effects (s) are modeled as a moving window containing the plot itself and the 14 surrounding plots. Plots located at the edge of a field had fewer real neighbors, so the missing neighbors were set to empty plots to preserve the structure of the moving window. For rust resistance, the spatial location of the plots within field was unknown, and therefore, spatial effects were not included. e is a vector of residual effects where. X 1, X 2, and X 3 are the design matrices for the fixed effects. Z 1, Z 2, Z 3, Z 4, and Q j are the design matrices for the random effects. Equation (2) was also applied within each population (6RW, 6RS, 2RW, 2RS) in order to estimate variance components and trait heritability. Before displaying the variance components in a percent stacked bar plot, the estimated values ofandwere multiplied by the mean diagonal of the G matrix to account for inbreeding. Similarly, the spatial variance was multiplied by 15 to account for the contribution of 15 plots within the moving window.

---

### Flow-induced disturbances in balanced steady-state free precession images: means to reduce or exploit them [^69805631]. Magnetic Resonance in Medicine (2009). Low credibility.

In this work computer simulations and phantom measurements are presented that show the effect of flow on in-plane balanced steady-state free precession images. The images were studied for various flow velocities, excitation regions, relaxation times, RF-pulse angles, and off-resonance frequencies. The work shows that flow-induced disturbances are present in the images, but can be reduced by the application of inhomogeneous excitation regions. Also, a velocity quantification method that utilizes the disturbances was developed and proved to quantify flow velocities accurately. The work concluded that the flow-induced disturbances can be reduced to improve image quality, but can also be exploited to quantify the flow velocity.

---

### A single spin in hexagonal boron nitride for vectorial quantum magnetometry [^d6cc021b]. Nature Communications (2025). High credibility.

Vectorial magnetic-field sensing enabled by the low-symmetry spin

Full vectorial sensing enables unambiguous determination of three linearly independent target magnetic field components. In Fig. 4 we present an experimental protocol that can determine three components of a target-field vector with the hBN defect, consisting of measuring ODMR under two bias fields. Figure 4 a presents a schematic of the proposed measurement protocol. Figure 4 b shows the unit vectors associated with the 0.1-mT target magnetic field T (grey) with components T x, y, z and the two arbitrarily oriented bias fields (B 1 in light blue and B 2 in pink), all non-collinear with each other or with any of the defect’s axes. Figure 4 c, d shows the calculated cwODMR spectra with B 1 and B 2, respectively, and the shifts induced by the presence of the target magnetic field. Each component of the target-field (T x, T y, T z, red, blue, and green dashed curves, respectively) induces a significant and distinct shift to each ODMR resonance, enabling determination of all three target-field components unambiguously. This is shown in more detail in Fig. 4 e. Here, the grey vector represents the 0.1-mT target magnetic field, and the shaded pink and light blue clouds indicate the possible solutions for the target-field vector from a 1-second cwODMR measurement with B 1 and B 2, respectively. With B 1 in the y z plane, T y and T z can be determined, but the measurement gives no information on T x component. This is reflected by the cylindrical light blue cloud with its long axis parallel to the x axis. Alternatively, a measurement with B 2 in the x y plane provides information on the target-field orientation within a dome normal to the bias field, thus gaining information on T x. Combined, the two measurements performed with B 1 and B 2 can determine the three components of the target-field vector, represented by the overlap in these two distributions (see inset). In conclusion, the hBN defect offers a route to full vectorial-field mapping of a target field.

---

### Modified oscillating gradient pulses for direct sampling of the diffusion spectrum suitable for imaging sequences [^55670cdb]. Magnetic Resonance Imaging (2003). Low credibility.

A variation of the oscillating gradient spin echo method had been developed, which isolates temporal frequencies of the dephasing spectrum. This allows sampling of the diffusion spectrum, the Fourier transform of the velocity correlation function (VCF). It has been shown that restriction and flow alter this function in ways that can be mathematically characterized, yielding quantitative information on restriction geometry and flow parameters. It is demonstrated that in many systems of interest, dispersion of velocity will produce a peak in the VCF spectrum near omega=0, while restricted diffusion will manifest itself in the spectrum at higher frequencies. The method, therefore, may be useful for decoupling their effects on the apparent diffusion coefficient (ADC), as well as in revealing the physics of both phenomena. This method has been implemented in model systems of packed beads, yielding data consistent with theoretical models of restricted diffusion spectra and data from one previous study. The method may have significant application to biology and medicine, as well as the study of transport phenomena in porous media and complex flow.

---

### Accurate and robust segmentation of neuroanatomy in T1-weighted MRI by combining spatial priors with deep convolutional neural networks [^3423b6ff]. Human Brain Mapping (2020). Medium credibility.

2.3 Data augmentation with random elastic deformations

Deep neural networks, which have a high modeling capacity, are particularly dependent on the availability of large quantities of labeled training data in order to generalize well to new unseen test data. In the context of MRI segmentation, low numbers of training samples are typically encountered due to the high cost of generating manually annotated data. To remedy this problem, data augmentation can be used to artificially expand the training set. Commonly, this is accomplished by applying user‐specified but label‐preserving transformations to the training data, such as reflections, rotations, and flips. However, since in the present work, all images are linearly registered in a common space and are therefore approximately the same size and with the same orientation, these transformations would be counterproductive. Rather, the relevant differences between linearly registered images are local and nonlinear in nature. To create plausible synthetic training samples, we therefore chose to apply random 3D elastic deformations using a method based on Simard, Steinkraus, and Platt (2003).

To generate a random elastic deformation, we first generate a 3D vector field (where each vector element specifies the per‐pixel displacement in each of the x, y, and z directions, respectively) with the same spatial dimensions as the input samples, and then assign each vector element a random value selected from the uniform distribution U (−1,1). The vector field is then smoothed in each direction using Gaussian kernels with standard deviation σ e (controlling the elasticity of the deformation), normalized to have a mean per‐pixel displacement of one, and then multiplied by a constant α i (controlling the intensity of the deformation), producing the final deformation. During training, we apply data augmentation on the fly by generating a different random data augmentation transformation for each sample prior to being fed through the network. The random elastic deformation is then used to interpolate each training sample (i.e. the image appearance patch, the three spatial coordinates patches, and the reference label image) using linear interpolation. We note that applying linear interpolation introduces a slight blurring in the label images, which itself can be useful as a regularization technique (Szegedy, Vanhoucke, Ioffe, Shlens, & Wojna, 2016). The parameters σ e and α i were determined using a coarse grid search, detailed in Section 3.1.3.

---

### A euclidean transformer for fast and stable machine learned force fields [^883743f1]. Nature Communications (2024). High credibility.

We remark that the outlined equivariant architecture does not preclude the modeling of vectorial and tensorial properties, such as atomic quadrupoles or octopoles, up to the set maximum degree. For example, molecular dipoles can be learned by combining invariant partial charge predictions with atomic dipoles extracted from the EVs of degree l = 1,.

A detailed outline of the architectural components and the proposed Euclidean self-attention framework is given in the “Methods” section and in Fig. 3.

Fig. 3 
architecture and building blocks.

a Thetransformer takes atomic types Z = { z 1, …, z n } and atomic positionsand returns a corresponding energy E pot. Within the embedding block Z and R are embedded into invariant features F and equivariant Euclidean variables (EV) X. They are refined via T Euclidean transformer blocks. Per-atom energies are predicted from the final features via a multilayer perceptron (MLP) and are summed up to yield the total energy. b A Euclidean transformer block consists of a Euclidean attention block and an interaction block. Both blocks are enveloped by skip connections which allow to carry over information from prior layers. c The Euclidean attention block aggregates atomic neighborhood information. It consists of two branches one updating the features and one the EV. Within the feature branch the invariant features and the filter vectors w i j are split into h attention heads. Query, key and value vector are constructed from the features via trainable matrices Q, K and V. Query and filter are multiplied point-wise before a dot product with the key vector yields attention coefficients α i j which weight the value vectors during neighborhood aggregation. The aggregated per-head features are stacked back together and yield a single attended feature. The EV branch follows a similar design with the number of heads being determined by the minimum and maximal degree in the network. Instead of an invariant value vector, spherical harmonics vectorsfrom minimal to maximal degree are used for the different heads. d The interaction block exchanges per-atom information between features and EV. It contracts the EV to per-degree invariants and concatenates the result with the invariant features. The concatenated result is passed through an affine transformation which gives updates for the features and the EV. e A pairwise difference vector between EV is contracted to per-degree invariants and passed through an MLP. From the atomic displacement vector the pairwise distance is calculated and expanded in radial basis functions before fed into an MLP. The MLP outputs are summed to yield the filter vector w i j.

---

### Extraordinary momentum and spin in evanescent waves [^8eba57de]. Nature Communications (2014). Medium credibility.

Momentum and spin represent fundamental dynamic properties of quantum particles and fields. In particular, propagating optical waves (photons) carry momentum and longitudinal spin determined by the wave vector and circular polarization, respectively. Here we show that exactly the opposite can be the case for evanescent optical waves. A single evanescent wave possesses a spin component, which is independent of the polarization and is orthogonal to the wave vector. Furthermore, such a wave carries a momentum component, which is determined by the circular polarization and is also orthogonal to the wave vector. We show that these extraordinary properties reveal a fundamental Belinfante's spin momentum, known in field theory and unobservable in propagating fields. We demonstrate that the transverse momentum and spin push and twist a probe Mie particle in an evanescent field. This allows the observation of 'impossible' properties of light and of a fundamental field-theory quantity, which was previously considered as 'virtual'.

---

### Pulsed vector atomic magnetometer using an alternating fast-rotating field [^574f6665]. Nature Communications (2025). High credibility.

Fig. 1 
Experimental setup: Three coils determine the x, y, and z directions.

The sensor head sits on a rotating stage with the cell positioned at the stage’s center. The sensor head can freely rotate in the xz and yz-planes. α is the angle by which the probe beam moves away from the position where the probe beam is perpendicular to the static magnetic field in xz-plane. β is the angle by which the pump beam moves away from the position where the pump beam is perpendicular to the static magnetic field in yz-plane. θ represents angle between the axis of rotation and the rotating field vector. Notably, WP stands for Wollaston prism, and Q-PD stands for quadrant photodiode.

Table 1 
The signs of the systematics as a function of the phases of the rotating magnetic field

The intuitive classical model underlying the operating principle of the FRF vector magnetometer is illustrated in Fig. 1. The scalar magnitude of the total magnetic field, ∣ B tot ∣, depends on the angle between the rotating field B m and the residual magnetic field B 0. When a small residual transverse magnetic field Δb —comprising b x and b y —is present, ∣ B tot ∣ varies with oscillating components at the rotation frequency of B m. The phases and amplitudes of these oscillations are influenced by the angle between B 0 and B m. Consequently, the Larmor precession frequency, proportional to ∣ B tot ∣, also displays oscillating components: a residual field in the x-direction, b x, produces an out-of-phase oscillation, while a residual field in the y-direction induces an in-phase component.

This model provides a fundamental description of the magnetometer’s operation. However, for precise measurements, several systematic effects—some even resulting from hyperfine interactions—require in-depth analysis to account for and minimize potential measurement biases.

Systematics

To achieve high accuracy, systematic errors must be carefully studied and eliminated. In the FRF vector magnetometer, several systematic effects are present. By expanding Eq. (3) into a power series and examining the phase shifts to second order in B m, we can identify two phase-shift contributions from B m :

---

### Current and evolving echocardiographic techniques for the quantitative evaluation of cardiac mechanics: ASE / EAE consensus statement on methodology and indications endorsed by the Japanese society of echocardiography [^0472f168]. Journal of the American Society of Echocardiography (2011). Medium credibility.

3D speckle-tracking echocardiography (3D STE) performance and efficiency—vector density, frame rate, and comparative agreement: 3D STE generates >3,000 vectors per volume and its temporal resolution is the same as the frame rate of real-time 3D data sets (typically 20–30 volumes/sec), and its use was found to reduce the examination time to one third of that for 2D STE; a significantly greater number of segments could be analyzed. The entire left ventricle can be analyzed from a single apical volume, 3D STE can measure all three spatial components of the myocardial displacement vector, and 3D STE–based LV volume measurements were in close agreement with magnetic resonance–derived reference values, with higher levels of agreement than 2D STE in the same patients (higher correlation coefficients, smaller biases, and tighter limits of agreement).

---

### Accelerated 4D-flow MRI with 3-point encoding enabled by machine learning [^44e3f850]. Magnetic Resonance in Medicine (2023). Medium credibility.

FIGURE 5 
RMSE, correlation analysis slope, and R 2 as a function of additional acceleration for 4‐point and 3‐point velocity encoded images (all derived from the same data). All values were computed in segmented vessels. The 3‐point encoding is effective even at high accelerations and even produces lower RMSE and higher correlations compared to 4‐point at the same acceleration. The 3‐point flow encoding does produce a lower velocity value 4‐point and the underestimation increases with additional acceleration

---

### Accelerated 4D-flow MRI with 3-point encoding enabled by machine learning [^def6d70a]. Magnetic Resonance in Medicine (2023). Medium credibility.

5 CONCLUSIONS

Current 4D‐flow MRI scans can be accelerated without further undersampling by using a convolutional neural network to produce three directional velocities from three flow encodings. The training of the convolutional network is dependent on the loss function used, with compensation needed to account for distribution of velocities in the volume of interest.

---

### Recommendations for noninvasive evaluation of native valvular regurgitation: a report from the American Society of Echocardiography developed in collaboration with the Society for Cardiovascular Magnetic Resonance [^1d043137]. Journal of the American Society of Echocardiography (2017). Medium credibility.

Cardiac magnetic resonance (CMR) phase-contrast flow measurement—technical considerations include setting velocity encoding to the lowest feasible without aliasing; centering the imaging plane in the vessel of interest, aligning it orthogonally to the expected main blood flow direction in two spatial directions, and positioning it at the magnet isocenter; and considering phantom or background correction because eddy current–related phase offset errors can still occur.

---

### Pulsed vector atomic magnetometer using an alternating fast-rotating field [^f0563877]. Nature Communications (2025). High credibility.

Discussion

In summary, we present a FRF vector geomagnetic magnetometer. This system is achieved by applying a rotating field to a scalar atomic magnetometer, enabling it to fully determine the magnetic field vector. While the modulation slightly degrades the scalar performance from 28to 35, it provides two additional polar angles with resolutions of 6. This enhancement allows the vector magnetometer to precisely measure two transverse polar angles, eliminating the static heading error common in scalar atomic magnetometers. The unique vector axes are defined by the rotation plane of the applied field, increasing stability compared to relying on mechanical coil orthogonality.

We provide a comprehensive study of the systematics and develop peak-altering fast rotating field modulation to cancel out these effects. Benefits from frequency measurement, such vector magnetometers can achieve high fractional resolution. Additionally, the vector magnetometer retains the accuracy and metrological advantages of scalar atomic magnetometers, such as inherent calibration.

Furthermore, the fundamental sensitivity of the vector magnetometer in total field measurement is identical to that of scalar magnetometers. Compared with approaches using sequential modulation, our proposed vector magnetometer is faster (higher bandwidth) and experiences fewer systematic effects. The FRF vector magnetometer can be further improved to reach quantum-limited sensitivity.

---

### Phase informed model for motion and susceptibility [^b1900879]. Human Brain Mapping (2013). Low credibility.

Performing the Dynamic Distortion Correction

From Eq. (5), the resulting map of local phase changes associated with each time point i can be scaled from radians to a change in B 0 field, ΔΒ 0 i in Hz by dividing by the echo time, TE, of the EPI volume, and a value of 2π since the phases are given in radians (i.e. ΔΒ 0 i = Δ ϕ correction i /(2π TE)). ΔΒ 0 i must be divided by the bandwidth per pixel in the phase‐encode direction, BW PE, to give the relative distortion in voxels, resulting in a voxel displacement map (vdm):Each vdm i describes the voxel displacement in the phase encode direction caused by the change in field at each voxel in the distorted image i with respect to the space of the first image. To calculate the field required to correct for the relative distortion between each image and the first in the time series, the vdm i must be inverted. For this inversion procedure, the forward mapping gives us x′ = f (x) for each value x on a regular grid, where x is a 1‐dimensional column in the phase encode direction. The inverse mapping yields x = f −1 (x ′) for each value x ′ on a regular grid. It is calculated by, for each value x ′, finding the first x i so that f (x i) > x ′ and then finding x by linear interpolation between f (x i −1) and f (x i). This is a valid procedure as long as f (x) is monotonously increasing, which is the case in general. When it is not, i.e. when the off‐resonance field changes very rapidly over space (compared with the effective encoding gradient strength), there will be almost total signal loss in the gradient echo EPI images, so the displacement of the nonexistent signal will not matter. Finally, at each time point i, the original distorted image can be distortion corrected to the space of the first image by resampling distorted image voxels at new locations along the phase encode direction according to the values in the vdm i [Hutton et al. 2002 ; Jezzard and Balaban, 1995].

---

### RSalvador: an R package for the fluctuation experiment [^2553a900]. G3 (2017). Low credibility.

Figure 1 
Contours of the log-likelihood function for the data given in Table 3 of. The four colored dots represent estimates of m and w. The green dot indicates the ML estimates, the blue dot indicates the GF estimates via flan, the purple dot indicates the GF estimates via bz-rates, and the red dot indicates the GF estimates by an earlier implementation of the GF method.

> newton.joint.MK(cairns.foster.data)

[1] 1.3027909 0.7281044

Likelihood ratio C.I.s for m and w can be computed separately as follows.

> confint.profile.m(cairns.foster.data)

[1] 0.9855115 1.6749828

> confint.profile.w(cairns.foster.data)

[1] 0.5209636 1.0298620

The exploration of the GF method drew attention to the issue of parameter identifiability. Only recently did investigators in systems biology and related fields recognize practical identifiability as a problem distinct from the better-known problem of structural identifiability. Practical identifiability considers the effects of the amount and quality of data. Computational difficulties encountered with the Mandelbrot-Koch mutant distribution may also be viewed as practical nonidentifiability. The inability to estimate w in the examples given byis indicative of practical nonidentifiability. In addition, the C.I.s that extend to zero in these examples are a symptom of the same problem. No multi-parameter mutant distribution seems to be immune to practical nonidentifiability.was perhaps the first to document computational difficulties that were due to practical nonidentifiability. In my own simulation exploration of the mutant distribution used byand by, I also found practical nonidentifiability a stubborn problem.

---

### Machine learning assisted vector atomic magnetometry [^dde76480]. Nature Communications (2023). High credibility.

Discussion

We propose a paradigm for atomic vector magnetometry based on machine learning, allowing three dimensional single-shot information extraction using a simple standard scalar magnetometer setup. Acquiring the amplitude and phase of the AC optical rotation signals removes the need for spectral sweep, enabling future real-time measurement of time varying magnetic field. The single-beam all-optical design is suitable for dense integration of the sensor units. We also demonstrate how to obtain vector field sensitivities using the neural network, and the best sensitivities on field amplitude and orientations are about 100 fTandrespectively. The current sensitivities are limited by electronic noises around the relatively low modulation frequency. After removal of such noises, the sensitivity may be further improved using a multipass design. The signal degeneracy for φ and φ + π can be lifted with an angled multi-pass configuration, as shown in our simulation (see Supplementary Note 6), which also removes the dead zone for φ when B is nearly aligned with k of the laser. Furthermore, the dynamic range of detectable magnetic field can be controlled through the resonance linewidth or changing the modulation frequency of the laser. Higher bandwidth can be obtained in vapor cells working in the higher temperature spin-exchange-relaxation-free regime.

Our strategy of using machine learning to simplify the structure of vector NMOR-magnetometers can be extended to other types of atomic magnetometers, as well as multiparameter sensors in general, using the following procedure: (1) Identify a set of observables which are sensitive to the target parameters and can be simultaneously, if possible, recorded in the experiment. The rich degrees of freedom in the interrogating laser or broadly the electromagnetic field, for example the amplitude, polarization, spatial modes, frequency spectra etc. can be all used for encoding the information indirectly and compressively. (2) Stabilize the experiment system as a prerequisite for a robust map between the observable set and the parameter set. (3) Experimentally collect data within a suitable range of target parameters and perform the neural network training to build the map between the signal set and parameter set. The NN structure is chosen according to the complexity level of the problem, and overfitting should be avoided. (4) Conduct real measurements using the trained NN.

---

### An on-chip phased array for non-classical light [^8b1ad0ca]. Nature Communications (2025). High credibility.

Fig. 4 
Squeezed light imaging.

a Experimental setup for the squeezed light measurements. Squeezed light is generated off-chip and transmitted over free space to the chip (blue, Photonics), which is interfaced with electronics (orange, Electronics) for processing. b Illustration of squeezed light transmitted to the chip, showing the Wigner function of the generated squeezed vacuum state as a function of the quadrature observables (Q, P) and the experimental squeezing parameter (r = 1.95). c Sample means and variances of the channel output voltages as a function of time. For each channel, the sample variances are normalized to the mean variance. d Wigner functions of the 32 pixel modes characterized simultaneously as a function of the squeezing parameter (r = 1.95), phase, and geometric efficiency for each channel. The dark and light blue contours correspond to the half-maximum points of the squeezed vacuum and vacuum states, respectively.

To image the squeezed light, the output voltages are read out to a 32-channel digitizer (see data acquisition in Methods). A 0.5 Hz phase ramp is applied to the LO off-chip to acquire voltage samples over various phases, and sample means and variances are calculated over sets of 260,000 voltage samples. The time evolution of the sample means and variances for all 32 pixel modes are shown in Fig. 4 c. Without phase locking, thermal drifts in the fiber-optic setup give rise to nonuniform phase fluctuations on top of the phase ramp, which are coherent across all channels. The corresponding Wigner functions for the source and the pixel modes are shown in Fig. 4 b, d, respectively (see Wigner function calculation in Methods).

---

### ACR-ASNR-SPR practice parameter for the performance of magnetic resonance imaging (MRI) of the pediatric spine [^7c92689e]. SPR/ASNR/ACR (2024). High credibility.

Cerebrospinal fluid (CSF) cine phase-contrast MRI—CSF flow can be imaged with phase-contrast cine MRI evaluation and is most commonly performed at the level of the foramen magnum in cases of known or suspected Chiari type I or idiopathic syringohydromyelia; in the first 6 –12 months of life, there are reduced CSF pulsation velocities that are due to the compliance of unfused cranial sutures, and cardiac gating with either electrocardiogram (ECG) or peripheral leads can be used to reduce cardiac-dependent flow while permitting quantitative velocity and qualitative vector measurements of CSF flow; typical parameters are as follows: Cardiac gating; flip angle 20°; repetition time and echo time (TR/TE), 20/5 ms; slice thickness, 5 mm; field of view, 180 mm; matrix, 256 × 256; and encoding velocity (venc) of either 5 cm/s or 10 cm/s; spinal CSF flow imaging is performed in the axial and/or sagittal planes with sagittal acquisition allowing evaluation of flow ventral to the cervicomedullary junction and dorsal to the cerebellar tonsils, and axial imaging assessing circumferential flow at the cervicomedullary junction including ventrolateral hyperdynamic flow not evident on midsagittal imaging.

---

### Quantitative evaluation of methods to analyze motion changes in single-particle experiments [^75a786ad]. Nature Communications (2025). High credibility.

For Track 2, trajectory coordinates are corrupted with noise from a Gaussian distribution with zero mean and standard deviation σ N to take into account the finite localization precision obtained in tracking experiments. All simulated trajectories were generated without missing frames: no gaps were introduced, yielding continuous tracks to isolate segmentation performance from linking or gap-filling complexities.

All the models share a set of parameters required for the simulations that are described here. Model-specific parameters are defined when describing the details of the models in the following sections.
[K 1, K 2, …, K n]: average values of the (Gaussian) distribution of the generalized diffusion coefficient for each of the n diffusive states considered in a given experiment, with support [10 −12, 10 6] pixel 2 /frame α.
: standard deviations of the (Gaussian) distribution of the generalized diffusion coefficient for each of the n diffusive states considered in a given experiment. If not provided, the standard deviation is considered to be equal to 0 (i.e. the distribution is δ (K − K i)).
[α 1, α 2, …, α n]: average values of the (Gaussian) distribution of the anomalous diffusion exponent for each of the n diffusive states considered in a given experiment, with support (0, 2).
: standard deviations of the (Gaussian) distribution of the anomalous diffusion exponent for each of the n diffusive states considered in a given experiment. If not provided, the standard deviation is considered to be equal to 0 (i.e. the distribution is δ (α − α i)).
L : size of the box in which trajectories are simulated with reflecting boundary conditions.
L FOV : size of the box defining the FOV used for the Challenge datasets. The same particles can enter and exit the FOV over time but, for evaluation purposes, they will be considered as generating different trajectories.
Δ t : sampling time at which the original motion of the particle is tracked. For the Challenge datasets, we consider Δ t = 1.
T : duration of the recording over each FOV, given as the number of time steps Δ t. It also corresponds to the maximum trajectory duration. For the Challenge, we set T = 200;
: minimum duration of a trajectory to be included in the dataset. For the Challenge, we use T = 20;
I bg (Track 1): background level of noise (counts) used in the simulation of videos.
FWHM PSF (Track 1): full width at half maximum in pixels of the point-spread function used to render fluorescent particles.
I tot (Track 1): mean value in counts of the total fluorescence collected for the detected particles.
σ tot (Track 1): standard deviation in counts of the distribution of total fluorescence collected for the detected particles.
I peak (Track 1): mean value in counts of the peak fluorescence collected for the detected particles. Can be calculated as
SNR (Track 1): typical signal-to-noise ratio of the movies, calculated as the average peak intensity over the standard deviation of the noiseand thus equal to
σ N (Track 2): standard deviation of the Gaussian localization noise used to corrupt trajectory coordinates.
: minimum distance between changepoints, corresponding to the minimum amount of time that a particle spends in a state. Shorter segments are eliminated by smoothing the time trace of the state label using a majority filter with a window of 5 steps. For the Challenge, we setframes to test the sensitivity and robustness of the segmentation methods under minimal data conditions.

---

### Interpretation of peripheral arterial and venous Doppler waveforms: a consensus statement from the Society for Vascular Medicine and society for vascular ultrasound [^eda7e5e0]. Vascular Medicine (2020). High credibility.

Peripheral venous circulation—overview notes that venous blood flow is influenced by intrinsic factors including the respiratory cycle, central and segmental venous pressure gradients, vessel compliance, and valve function, as well as extrinsic factors such as gravity, muscle pumps, atmospheric pressure, and external venous compression from an overlying tumor, artery, mass, or fluid collection.

---

### Time reversed optical waves by arbitrary vector spatiotemporal field generation [^7934b438]. Nature Communications (2020). High credibility.

Experimental results

Figure 3 contains various examples of spatiospectral and spatiotemporal control, with additional examples available in the Supplementary Information. The measured 3D optical fields (2D space and 1D time/frequency) are plotted as a sequence of 2D fields, as well as volumetric renderings. The plots contain both amplitude and phase information for these fields for both polarisation components. Examples, such as the spatiotemporal foci of Fig. 3b, d, are similar to typical first demonstrations of time reversal in other wave phenomena, which is a use case of practical application in imaging and nonlinear optics. However, most examples were chosen to be illustrative of the system’s ability to generate beams with arbitrary control over space, time/frequency and polarisation, rather than any specific use case. All beam types are characterised in the frequency domain. For spatiotemporal beam demonstrations, the presented results are Fourier transformed into the time-domain from the measured frequency-dependent fields measured using swept-wavelength digital holography.

Fig. 3 
Selection of vector spatiospectral and spatiotemporal states measured at the distal end of the multimode optical fibre.

Various examples illustrating control of the spatial amplitude, phase and polarisation of a beam as a function of frequency or time. The examples are shown as a sample sequence of measured optical fields, as well as a volumetric rendering of the field as function of space, time/frequency and polarisation. a Spatiotemporal demonstration. b – h Spatiotemporal demonstrations are Fourier transforms of the measured optical fields using swept-wavelength digital holography. Further examples and animations are available in the Supplementary Information.

In Fig. 3a the device of Fig. 2 is used as a programmable dispersive element, which can perform arbitrary mappings between wavelength and 2D space/polarisation. The horizontal and vertical polarisations cycle through spatial fields corresponding with letters of the Latin alphabet in forward and reverse alphabetical order respectively. From these measured optical fields of Fig. 3a it is possible to see that the spatial amplitude and phase in both polarisations can be controlled as a function of wavelength. The overall spectral phase is near constant as a function of wavelength and hence all letters arrive at the same delay.

---

### Real-time photonic blind interference cancellation [^e6dc6fa2]. Nature Communications (2023). High credibility.

Fig. 4 
A typical experimental photonic weight identification with the M 2 mixing matrix.

Step 1 identifies the point of lowest variance, i 0. Step 2 consists of principal component analysis and step 3 of independent component analysis, each optimizing directional vectors about the circle denoting the linear region. A 0 subscript and dashed lines denote initial positions, while solid lines denote final positions. Step 4 optimizes the recovered source signals, freeing them from the linear region to reach higher-amplitude final positions denoted. PCs principal components, ICs independent components.

Estimates of the source signals after step 3 are subject to the cascaded errors of the previous steps stemming from noise, sampling randomness, and the linearity approximation. Furthermore, we seek to increase the amplitude of the recovered signal to maximize its SNR, but that requires pushing i out of the linear region. To address both problems, we add a final step to the algorithm consisting of a kurtosis minimization over the entire weight field, with each IC estimate serving as the initial position. As noise raises the kurtosis, this step optimizes both the ICs’ weights and SNRs without requiring the linearity assumption of Eq. (5). This constitutes step 4. So long as steps 1–3 place the initial IC estimates within the correct convex regions, the optimizer will find the correct kurtosis minima. Experimentally, we find that both the stronger and weaker source signals can be consistently recovered and accurately demodulated under M 1 and M 2.

Low-latency adaptation

Under most wireless communication scenarios, M changes in response to the movement of people and objects in the environment. However, it is assumed to be static during cancellation weight identification. The desired weights must therefore be identified before M meaningfully changes, with the algorithm operating in real-time with low latency. Following weight identification, continuous kurtosis minimization can ensure the weight vectors remain accurate, so the latency of the initial identification represents the limiting factor. Weight identification requires a set of processing iterations, each of which consists of five sequential operations shown in Table 1. Signal acquisition refers to the collection of a set of samples of m (t), the latency of which depends on the sampling rate and sample count, discussed in the following section. We demonstrate consistently successful weight identification for M 1 and M 2 with a signal acquisition latency down to 8.3 μs.

---

### Trajectory optimization based on the signal-to-noise ratio for spatial encoding with nonlinear encoding fields [^7d68a534]. Magnetic Resonance in Medicine (2016). Low credibility.

Purpose

Multiple nonlinear gradient fields offer many potential benefits for spatial encoding including reduced acquisition time, fewer artefacts and region-specific imaging, although designing a suitable trajectory for such a setup is difficult. This work aims to optimize encoding trajectories for multiple nonlinear gradient fields based on the image signal-to-noise ratio.

Theory and Methods

Image signal-to-noise ratio is directly linked to the covariance of the reconstructed pixels, which can be calculated recursively for each projection of the trajectory under a Bayesian formulation. An evolutionary algorithm is used to find the higher-dimensional projections that minimize the pixel covariance, incorporating receive coil profiles, intravoxel dephasing, and reconstruction regularization. The resulting trajectories are tested through simulations and experiments.

Results

The optimized trajectories produce images with higher resolution and fewer artefacts compared with traditional approaches, particularly for high undersampling. However, higher-dimensional projection experiments strongly depend on accurate hardware and calibration.

Conclusion

Computer-based optimization provides an efficient means to explore the large trajectory space created by the use of multiple nonlinear encoding fields. The optimization framework, as presented here, is necessary to fully exploit the advantages of nonlinear fields. Magn Reson Med 76:104-117, 2016. © 2015 Wiley Periodicals, Inc.

---

### Control of the spin geometric phase in semiconductor quantum rings [^4756247f]. Nature Communications (2013). Medium credibility.

Results

Concept of present experiment

Spins in a magnetic field acquire a dynamical phase, which physically corresponds to phase accumulation because of the spin precession around the magnetic field. In a mesoscopic ring system with an inhomogeneous magnetic field, the spins acquire also a geometric phase that depends on the path of the spin. As an example, consider a one-dimensional (1D) ring in a textured magnetic fieldas shown in Fig. 1a. The magnetic field seen by a propagating electron along the ring subtends, from its rest frame, a solid angle in the magnetic-field space. The spin acquires not only a dynamical phase but also a geometric phase, which is proportional to the solid angle (Fig. 1b).

The Bychkov–Rashba spin-orbit (SO) couplingcan be used to create an effective in-plane magnetic-field texture (Fig. 1c). The coupling is induced at an interface between semiconductor layers having different energy gaps by an electric field perpendicular to the layers (say along the z axis). It is a relativistic effect where an electron travelling through an electric field feels an effective SO magnetic field B SO, the direction of which is perpendicular both to the electric field and a wave vector k, that is, B SO ∝ α R (k × e z). Here the electric field enters through the Rashba SO-coupling constant α R that is therefore electrically tunable with a top-gate electrode, and e z denotes a unit vector in z direction. This effective Rashba field couples to the electron spin, which acquires dynamical and geometric phases in the transport around the ring. Interference of these spin-related phases gives rise to conductance oscillations when α R is varied. Recently, the SO-induced geometric phase has been extractedfrom a detailed analysis of spin-interference effects as a function of the SO-coupling constant α R and the ring radius r.

---

### Quantitative imaging metrics for the assessment of pulmonary pathophysiology: an official American Thoracic Society and Fleischner society joint workshop report [^8992bf26]. Annals of the American Thoracic Society (2023). High credibility.

Quantitative imaging metrics—common sources of systematic errors in imaging and analysis include six categories with representative examples: technical issues during acquisition (differences in hardware and software, acquisition protocol, signal-to-noise ratio, and resolution), biased sampling of structure for analysis (comparison of mismatched airways), failure to define an appropriate reference space, issues with segmentation or registration, inaccurate assumptions or simplifications (assuming alveolar airspaces are spheres), and failure to consider spatiotemporal and biological heterogeneity (anatomical or gravitational gradients in tissue density, ventilation, and perfusion).

---

### ACCF / ACR / AHA / ASE / ASNC / HRS / NASCI / RSNA / SAIP / SCAI / SCCT / SCMR 2008 health policy statement on structured reporting in cardiovascular imaging [^7b45a485]. Journal of the American College of Cardiology (2009). Medium credibility.

Study findings—structured reporting commonly groups quantitative measures, qualitative assessments, and calculated data by evaluated structure in logical sequence, references measurements to norms for body size, gender, and age with corresponding Z-scores when relevant, includes physiological and hemodynamic changes (spontaneous or stress-related), and provides clearly identified fields for interpretation, comparison to prior studies, conclusions and impressions, and recommendations; the original clinical question should be explicitly answered, and standard features recommended by cardiovascular imaging societies should be reported using standard data elements and anatomic, morphologic, and functional descriptions, for example the Seventeen-Segment Model for assessing left ventricular function, which is a consensus standard for tomographic imaging and should be used in both stress and rest reports to document ischemia, scarring, or wall motion abnormalities.

---

### VERSE-guided parallel RF excitations using dynamic field correction [^1de83ace]. NMR in Biomedicine (2017). Low credibility.

In all cases a single‐shot spiral‐in excitation k ‐space trajectory was designed using time‐optimal gradient waveforms with maximum gradient amplitude of 30 mT/m and maximum slew rate of 180 T/m/s and encoding a 128 mm FOV with 2 mm resolution and radially undersampled to accelerate (2×) the excitation. The RF and gradient waveforms were sampled with a 6.4 μs dwell time for scanner implementations. Gradient ramps were appended at the beginning of the designed gradient waveforms if they start from a non‐zero value and RF pulses were set to be zero during this time. All computations including RF pulses and gradient designs and numerical simulations were performed in MATLAB (MathWorks, Natick, MA, USA).

We performed parallel RF excitation experiments in both Setup A and Setup B by acquiring axial images with a single‐shot turbo spin echo sequence with the following parameters: FOV = 128 × 128 mm 2 ; T R / T E = 2500/250 ms; matrix size =96 × 96. Multichannel RF pulses and gradient waveforms were time aligned with a sub‐dwell precision of 1 μs and set accurately for all experiments. 40

We first estimated the actual gradient waveforms played out by the scanner via time domain convolution of the nominal waveforms with GIRF computed using the above explained image domain method in Setup A. The RF pulses were designed to achieve 90° flip angle. This initial RF and gradient waveform pair were applied to the algorithm (Figure 1) to calculate the reVERSE pulses by redesigning the RF pulses based on the estimated actual k ‐space trajectories at every iteration for a target maximum peak RF magnitude of 12 μT (~74% reduction relative to the initial peak RF magnitude).

We further obtained the actual gradient waveforms at every iteration of the algorithm by direct field camera measurements in Setup B. Initial RF pulses were designed based on the measured k ‐space trajectories with the target peak RF magnitude of 12 μT (50% reduction relative to the initial peak RF magnitude). The attenuation factor α is set to 0.95 for all experiments to speed up the convergence. We additionally repeat all the experiments in Setup B with the same settings for comparison using the actual gradient waveforms predicted by GIRFs that are computed using the field camera measurements. Matlab source code can be downloaded from.

---

### Chiral structures of electric polarization vectors quantified by X-ray resonant scattering [^8c7ef30d]. Nature Communications (2022). High credibility.

Fig. 2 
Hard X-ray nonresonant and soft X-ray resonant scattering from a polar vortex array.

a Reciprocal space map of (PbTiO 3) n /(SrTiO 3) n (n = 16 unit cells) superlattice around the (0 0 4) PC diffraction peak of the DyScO 3 substrate using nonresonant hard X-rays. b Vertical line profiles corresponding to the truncation rod across the DyScO 3 (0 0 4) PC peak and the q z rod scan across the lateral satellite peaks due to the periodicity of the polar vortex array formed in the PbTiO 3 layer. c Scattering geometry. Anglesandrepresent the incident angle and the sample tilt angle generating the lateral q x component, respectively. d REXS intensities of q z rod scans measured at the first-order satellites of opposite signs. The calculations show the effect of the vertical correlation lengthbetween PbTiO 3 layers. e AT components of the basis Ti 4+ ion obtained from XAS and XLD of a monodomain PbZr 0.2 Ti 0.8 O 3 thin film measured by Arenholz et al. f, g Energy dependence of REXS intensities with right- and left-circularly polarized X-rays and their difference corresponding to X-ray circular dichroism. Intensities were measured at the lateral satellite-peak position (Å − 1,Å − 1). The calculations were obtained using the AT components in e.

To probe the three-dimensional chiral structure, REXS experiments at Ti L 2,3 edges in the soft X-ray regime were performed. To obtain a circular dichroism measurement sensitive to the chiral structure of a polar vortex array, REXS intensities were measured for left- and right-circularly polarized beams at q x = 0.057 Å −1, which is the lateral satellite-peak location corresponding to ~11 nm spacing of the polar vortex pair. To elucidate the three-dimensional structure of a polar vortex array in which resonant ions have different polarization vectors in the lateral direction as well as in the depth direction, it is necessary to measure scattering in reciprocal space in three dimensions as well. To accomplish this, a q z rod scan is performed while maintaining the nonzero q x component corresponding to the lateral periodicity of the polar vortex array. In this scattering geometry, as shown in Fig. 2c, the lateral q x component is obtained by tilting the scattering plane by an angle χ with respect to the surface normal.

---

### European position paper on the management of patients with patent foramen ovale. general approach and left circulation thromboembolism [^3893ac91]. European Heart Journal (2019). High credibility.

Regarding diagnostic investigations for patent foramen ovale, more specifically with respect to evaluation of left circulation thromboembolism, ESC 2019 guidelines recommend to do not use any single variable for a quantitative prediction of recurrences.

---

### Guidelines for noninvasive vascular laboratory testing: a report from the American Society of Echocardiography and the society of vascular medicine and biology [^cc53219c]. Journal of the American Society of Echocardiography (2006). Medium credibility.

Peripheral artery ultrasound technique—color Doppler is used to determine laminar or nonlaminar flow states, with turbulence, persistence (continuous forward flow), and aliasing at sites of disease; pulsed (spectral) Doppler is used to characterize flow and stenosis, and PSV is the primary measure used to quantify disease. Peak velocity measurements are compared between the lesion and proximal segments. Technical parameters include a 5-MHz linear-array transducer for the average adult, higher-frequency probes (7.5-10 MHz) for small or thin patients and lower-frequency probes (3-4 MHz) for larger patients or deep vessels, and use of a small sample volume placed center stream with the Doppler angle at 60 degrees or less; color and spectral Doppler are recorded at each new site as the sample volume is marched through the arterial system.

---

### Cell segmentation-free inference of cell types from in situ transcriptomics data [^83ff1f26]. Nature Communications (2021). High credibility.

Results

The SSAM computational framework

SSAM consists of 4 major steps (Fig. 1), namely (1) mRNA signal estimation and downsampling; (2) computation of cell-type signatures; (3) generation of a cell-type map; and (4) identification of tissue domains.

Fig. 1 
Schematic diagram of the SSAM computational workflow for cell type and tissue domain definition based on gene expression data.

A In step 1, SSAM converts mRNA locations into a vector field of gene expression values. For this, SSAM applies a Gaussian KDE to mRNA locations for each gene and projects the resulting mRNA density values to pixels that represents coordinates in the tissue. The mRNA density estimated per each gene is stacked to produce a ‘gene expression vector field’ over the image. The gene expression vector field is analogous to a 2D/3D image where each pixel/voxel encodes the averaged gene expression of the unit area. Further details of the application of KDE can be found in Supplementary Fig. 1A ; B In step 2, cell-type signatures are identified de novo. First, the gene expression profile at probable cell locations is identified as the local regions in the gene expression vector field where the signal is highest. These downsampled gene expression signals are identified and used for de novo cell type identification by cluster analysis. Alternatively, previously defined cell-type signatures can be used. C In step 3, a cell-type map is generated. For this, the cell-type signatures are mapped onto the gene expression vector field and cell types are assigned based on Pearson’s correlation between each cell-type expression signature to the vector field to define cell-type distribution in situ. Further details about creating the cell-type map can be found in Supplementary Fig. 2A ; D In step 4, the tissue domains are identified. The tissue domain signatures are identified using a sliding window to compute domain signatures based on the count of cell-type labels in the window. The tissue domains are defined by clustering these signatures. Further details on creating the tissue domain map can be found in Supplementary Fig. 2B.

---

### Magnetic charge propagation upon a 3D artificial spin-ice [^322c8ae6]. Nature Communications (2021). High credibility.

With this fundamental understanding we next sought to understand the magnetic configuration of vertex states observed during the switching process to determine if monopole-excitations can be identified and tracked. Figure 3a shows an MFM image following a saturating field along the unit vector (1,−1,0) and subsequent 9.5 mT field along the unit vector (−1,1,0). Optical magnetometry indicates this is within the field range that switching is expected upon L1. A vector map of the magnetic configuration (Fig. 3b) has been produced through observations of the MFM contrast associated with each L1–L2 vertex as well as the surrounding wires. Unmasked images can be found in Supplementary Fig. 5. We note that there are multiple independent means to confirm the presence of a monopole. Firstly, contrast near the L1–L2 vertex is an excellent indication. If three of the four wires have contrast of the same sign, this is a monopole state. This can be further confirmed by then checking contrast upon the opposite ends of the wires. Finally, since the magnetic charge upon the wire ends closest to L1–L2 smears over the vertex area, the absolute magnitude of the phase is increased when compared to an ice-rule state. We have used all three criteria simultaneously to identify monopoles at the L1–L2 vertex. Interestingly, so long as a well-defined field protocol is used, it is also possible to infer the presence of monopoles at the L2–L3 vertex. Here, so long as L3 has been saturated, we expect this sub-lattice to be uniformly magnetised. However, if the extremities of two adjacent L2 nanowires both have positive or negative contrast, a monopole is implied at the L2–L3 vertex.

---

### Electrical control of spins and giant g-factors in ring-like coupled quantum dots [^220b6480]. Nature Communications (2019). High credibility.

Fig. 4 
Quenching the 1e quantum ring by detuning.

a Measurement of d I /d V ds versus V ds recorded along the red detuning vector (c.f. Fig. 1f) for B || = 0.1 T. Detuning is defined as Δ V L,R = (V R − V R0) − (V L − V L0), where (V R0, V L0) are the side-gate voltages when the left and right QD levels are degenerate. E Z denotes the Zeeman splitting. b Numerical calculation of the states for B || = 0.1 T. Here detuning (Δ orb) refers to the extrapolated energy difference between the unperturbed orbitals in the left and right QD (see schematic in h). The colour represents the calculated orbital angular momentum (blue: L z, = −1.3 ħ, black: L z, = 0, red: L z, = 1.3 ħ). c Experimental values of | g *| for B || = 0.04 T (blue) and B || = 0.1 T (orange), extracted from the GS-ES1 transition using on a linear approximation. In the case of B || = 0.04 T, | g *| at zero detuning corresponds to | g 1 *|, while we find a strongly reduced value at B || = 0.1 T due to the orbital change of the 1 st excited state. d Same as panel a, but for B || = 0.2 T and a larger detuning range, showing a detuning-induced spin-change of the 1e ground state. e, f Measurement of d I /d V ds and numerical calculation as a function of detuning for B ⊥ = 0.1 T, where SOI from the ring supresses Zeeman splitting. g Experimental values of g * for the GS-ES1 transition at B ⊥ = 0.1 T. h Calculated probability density (| Φ | 2) of the lowest energy state at infinitesimal B || -field for three different detuning energies. The error bars in c and g represent the uncertainty in energy gap extraction due to measurement noise and resolution.

---

### Machine learning assisted vector atomic magnetometry [^d177da13]. Nature Communications (2023). High credibility.

Multiparameter sensing such as vector magnetometry often involves complex setups due to various external fields needed in explicitly connecting one measured signal to one parameter. Here, we propose a paradigm of indirect encoding for vector atomic magnetometry based on machine learning. We encode the three-dimensional magnetic-field information in the set of four simultaneously acquired signals associated with the optical rotation of a laser beam traversing the atomic sample. The map between the recorded signals and the vectorial field information is established through a pre-trained deep neural network. We demonstrate experimentally a single-shot all optical vector atomic magnetometer, with a simple scalar-magnetometer design employing only one elliptically-polarized laser beam and no additional coils. Magnetic field amplitude sensitivities of about 100 [Formula: see text] and angular sensitivities of about [Formula: see text] (for a magnetic field of around 140 nT) are derived from the neural network. Our approach can reduce the complexity of the architecture of vector magnetometers, and may shed light on the general design of multiparameter sensing.

---

### Identifying domains of applicability of machine learning models for materials science [^72c4ba76]. Nature Communications (2020). High credibility.

An illustrative example

Before describing the details of DA identification and its integration into the ML process, let us illustrate the concept and its utility via a synthetic example (see Fig. 1). We consider a simple two-dimensional representation consisting of independent features x 1 and x 2 that are each distributed according to a normal distribution with mean 0 and variance 2 (N (0, 2)) and a target property y that is a third-degree polynomial in x 1 with an additive noise component that scales exponentially in x 2 :That is, the y values are almost determined by the third-degree polynomial for low x 2 values but are almost completely random for high x 2 values. Discovering applicable domains reveals how different models cope differently with this setting even if they have a comparable average error. To show this, let us examine the error distributions obtained from three different kernelized regression models of the formwith parameter vector ν that are fitted around a training, or fitting (F), setwith three different choices for the kernel function k. We observe:
When using the linear (lin) kernel, the resulting linear model is globally incapable to trace the variation of the third-order polynomial except for a small stripe on the x 1 -axis where it can be approximated well by a linear function. Consequently, there is a very high error globally that is substantially reduced in the DA described by σ lin (x 1, x 2) ≡ −0.3 ≤ x 1 ≤ 0.3.
When using the Gaussian kernel), the resulting radial basis function (rbf) model is able to represent the target property well locally unless (a) the noise component is too large and (b) the variation of the target property is too high relative to the number of training points. The second restriction is because the rbfs have non-negligible values only within a small region around the training examples. Consequently, the discovered DA is not only restricted in x 2 -direction but also excludes high absolute x 1 -values: σ rbf ≡ −3.3 ≤ x 11 ≤ 3.1 ∧ x 2 ≤ 0.1.
In contrast, when using the non-local third-degree polynomial (poly) kernel, data sparsity does not prevent an accurate modeling of the target property along the x 1 -axis. However, this non-locality is counterproductive along the x 2 -axis where overfitting of the noise component has a global influence that results in higher prediction errors for the almost deterministic data points with low x 2 -values. This is reflected in the identified DA σ poly (x 1, x 2) ≡ −3.5 ≤ x 2 ≤ 0.1, which contains no restriction in x 1 -direction, but excludes both high and low x 2 -values. This highlights an important structural difference between the rbf and the polynomial model that is not reflected in their similar average errors.

---

### Variable field of view for spatial resolution improvement in continuously moving table magnetic resonance imaging [^c1d22a58]. Magnetic Resonance in Medicine (2005). Low credibility.

An approach is described in which the field of view (FOV) along the Y (right/left) phase encoding direction can be dynamically altered during a continuously moving table (CMT) coronal acquisition for extended FOV MRI. We hypothesize that with this method, regions of the anatomy exhibiting significantly different lateral widths can be imaged with a matching local FOV(Y), thereby improving local lateral spatial resolution. k-space raw data from the variable-FOV CMT acquisition do not allow simple Fourier reconstruction due to the presence of a mixture of phase encodes sampled at different Deltak(Y) intervals. In this work, we employ spline interpolation to reregister the mixed data set onto a uniformly sampled k-space grid. Using this interpolation scheme, we present phantom and peripheral contrast-enhanced MR angiography results demonstrating an approximate 45% improvement in local lateral spatial resolution for continuously moving table acquisitions.

---