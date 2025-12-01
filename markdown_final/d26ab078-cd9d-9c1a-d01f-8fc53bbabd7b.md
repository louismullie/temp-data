# Medical Question & Answer

**Sample ID**: d26ab078-cd9d-9c1a-d01f-8fc53bbabd7b
**Dataset Index**: 182493

---

## Question

1. Given a geometric sequence {aₙ} with a common ratio of q(q ≠ 1), let b₁ = a₁ + a₂ + a₃, b₂ = a₄ + a₅ + a₆, …, bₙ = a₍₃ₙ₋₂₎ + a₍₃ₙ₋₁₎ + a₍₃ₙ₎, …, then the sequence {bₙ}
A. is an arithmetic sequence
B. is a geometric sequence with a common ratio of q
C. is a geometric sequence with a common ratio of q³
D. is neither an arithmetic sequence nor a geometric sequence

---

## Answer

> Let's see… What do we have here? The user is asking whether the sequence ({b_n}), defined by summing consecutive triplets of a geometric sequence ({a_n}) with common ratio (q \\neq 1), is arithmetic, geometric with ratio (q), geometric with ratio (q^3), or neither. Let's break this down step-by-step. First, I need to think about the general form of (a_n) and how to express (b_n) algebraically. Then, I should verify whether the ratio (b_{n+1}/b_n) is constant and, if so, what that constant is. Next, I will check whether the difference (b_{n+1} - b_n) is constant to rule out arithmetic. Finally, I will compare the derived ratio with the answer choices and confirm the correct option.

> Let me first confirm the setup. The original sequence is geometric with first term (a₁) and common ratio (q), so (aₙ = a₁ qⁿ⁻¹). The new sequence is defined by (bₙ = a₍₃ₙ₋₂₎ + a₍₃ₙ₋₁₎ + a₍₃ₙ₎), which sums three consecutive terms of ({aₙ}) starting at index (3n-2). I should double-check that indexing: for (n = 1) we get (a₁ + a₂ + a₃), for (n = 2) we get (a₄ + a₅ + a₆), and so on, which matches the problem statement.

> Now, I will express (bₙ) explicitly in terms of (a₁) and (q). Substituting the geometric formula, (bₙ = a₁ q^(3n−3) + a₁ q^(3n−2) + a₁ q^(3n−1) = a₁ q^(3n−3)(1 + q + q²)). Wait, let me verify the exponent arithmetic: (q^(3n−3) + q^(3n−2) + q^(3n−1) = q^(3n−3)(1 + q + q²)), which is correct. So (bₙ = a₁ (1 + q + q²) q^(3n−3)).

> Next, I should review whether ({bₙ}) is geometric by computing the ratio of successive terms. Let me calculate ([bₙ₊₁/bₙ]): (bₙ₊₁ = a₁ (1 + q + q²) q^(3(n+1)−3) = a₁ (1 + q + q²) q^(3n)), so the ratio is ([q^(3n)/q^(3n−3)] = q³). Hold on, I should verify that the constant factor cancels: yes, (a₁ (1 + q + q²)) appears in both numerator and denominator and cancels out, leaving a constant ratio of (q³).

> I need to ensure this implies ({b_n}) is geometric. By definition, if the ratio of consecutive terms is constant, the sequence is geometric with that common ratio. Here the ratio is (q^3), so ({b_n}) is geometric with common ratio (q^3). Let me reconsider whether any constraint on (q) changes this: the problem states (q \\neq 1), which prevents the trivial case where all terms are equal, but does not affect the ratio calculation, so the conclusion stands.

> But wait, what if the sequence were arithmetic? I should double-check the difference (b_{n+1} - b_n). Using the expression for (b_n), (b_{n+1} - b_n = a_1 (1 + q + q^2) (q^{3n} - q^{3n-3}) = a_1 (1 + q + q^2) q^{3n-3}(q^3–1)). Since (q \\neq 1), (q^3–1 \\neq 0), and the difference depends on (n) via (q^{3n-3}), so the difference is not constant. Therefore, ({b_n}) is not arithmetic.

> Comparing with the options, the correct choice is C, which states that ({bₙ}) is a geometric sequence with a common ratio of (q³). Options A and D are incorrect because the sequence is not arithmetic and is in fact geometric, and option B is incorrect because the ratio is (q³), not (q).

---

The sequence ({bₙ}) is a geometric sequence with a common ratio of (q³). This is because each term (bₙ) is the sum of three consecutive terms of the geometric sequence ({aₙ}), and the ratio of successive terms ([bₙ₊₁/bₙ]) simplifies to (q³). Therefore, the correct answer is **C**.

---

## Step-by-step solution

### Step 1: express (bₙ) in terms of (a₁) and (q)

Given that ({aₙ}) is a geometric sequence with first term (a₁) and common ratio (q), we have:

aₙ = a₁ qⁿ⁻¹

Now, express (bₙ) as the sum of three consecutive terms of ({aₙ}):

bₙ = a₍₃ₙ₋₂₎ + a₍₃ₙ₋₁₎ + a₍₃ₙ₎

Substitute the geometric sequence formula into the expression for (bₙ):

bₙ = a₁ q^(3n−3) + a₁ q^(3n−2) + a₁ q^(3n−1)

Factor out (a₁ q^(3n−3)):

bₙ = a₁ q^(3n−3) (1 + q + q²)

---

### Step 2: determine the ratio of successive terms in ({bₙ})

To determine whether ({bₙ}) is a geometric sequence, we calculate the ratio of successive terms:

[bₙ₊₁/bₙ] = [a₁ q^(3(n+1)−3) (1 + q + q²)/(a₁ q^(3n−3) (1 + q + q²))]

Simplify the expression:

[bₙ₊₁/bₙ] = [q^(3n)/q^(3n−3)] = q³

Since the ratio ([bₙ₊₁/bₙ]) is constant and equal to (q³), the sequence ({bₙ}) is a geometric sequence with a common ratio of (q³).

---

### Step 3: verify other options

- **Option A**: An arithmetic sequence has a constant difference between successive terms. Here, the ratio is constant, not the difference, so ({b_n}) is not an arithmetic sequence.
- **Option B**: The common ratio is (q³), not (q), so this option is incorrect.
- **Option D**: Since ({b_n}) is a geometric sequence, this option is incorrect.

---

## Conclusion

The sequence ({bₙ}) is a geometric sequence with a common ratio of (q³). Therefore, the correct answer is **C**.

---

## References

### Mathematical biases in the calculation of the living planet index lead to overestimation of vertebrate population decline [^9a83596d]. Nature Communications (2024). High credibility.

More formally, the global LPI is calculated as a hierarchical sequence of five geometric means: i.e. a geometric mean of n ratios (p) of population values (N) of two consecutive years of the x th species, i.e. a geometric mean of d species-specific s x of the q th taxon, i.e. a geometric mean of c taxon-specific t q of the b th realm, i.e. a geometric mean of f realm-specific r b, i.e. a geometric mean of h ecosystem-specific e y. The global LPI is then calculated as,

therefore it is the product of the previous year's index (I p) and g. It holds that the logarithm of g is the final lambda (λ) — the mean population growth rate of all populations. The index can be thus expressed as.

In practice, the calculation is performed as a hierarchical sequence of arithmetic means, where in the first step the logarithm of the ratio of population values is averaged arithmetically. The arithmetic mean of logarithms is equivalent to the logarithm of the geometric mean, thus.

The R-function from the package rlpi allows various calculation settings of the LPI. It is possible to change the minimum length of the time series (the number of records, but not the number of years) included in the calculation, the constant replacing zeros, the length of the time series for which the GAM or chain method is used, the GAM smoothing parameter, the limit value for outlying lambda and whether to replace the outlying lambdas, and the use of weighting. The weights of particular taxa and realms were obtained from McRae et al.

The shape of the LPI curve is mostly influenced by two parameters; the number of records in the time series (fullness) and the use of weights (see ref.). The difference between the weighted and unweighted form of the global LPI is 44.5% (much greater decline in the weighted than unweighted form). The effect of weighting for the terrestrial, freshwater and marine LPI causes a 14.8%, 47.3% and 83.5% greater decline, respectively, in the weighted than unweighted form (Supplementary Table 1).

---

### Geometric phase magnetometry using a solid-state spin [^68b9b058]. Nature Communications (2018). Medium credibility.

In Fig. 3 we compare the measured sensitivity and field range for geometric-phase and dynamic-phase magnetometry. For each point displayed, the sensitivity is measured directly at small B (0.01 ~ 0.1 mT), whereas the field range is calculated from the measured values of N and Ω (for geometric-phase magnetometry) and T (for dynamic-phase magnetometry, with T limited by the dephasing time T 2 *), following the scaling laws give above. Since geometric-phase magnetometry has three independent control parameters (T, N, and Ω), B max can be increased without changing sensitivity by increasing N and Ω while keeping the ratio N / Ω fixed. Such "smart control" allows a tenfold improvement in geometric-phase sensitivity (compared to dynamic-phase measurements) for B max ~ 1 mT, and a 400-fold enhancement B max at a sensitivity of ~2 μT Hz −1/2. Similarly, the sensitivity can be improved without changing B max by decreasing the interaction time, with a limit set by the adiabaticity condition.

Fig. 3
Decoupling of magnetic field sensitivity and maximum field range. Measured performance of dynamic-phase (blue dots) and geometric-phase (red squares) magnetometry. Dashed lines are linear fits to data. Dashed arrows indicate the orientation of control parameters Ω, N, T as independent vectors on the (η 2, B max) map. Since a Ramsey sequence used for dynamic-phase magnetometry has only a single control parameter (T), the relations for sensitivity (η ∝ T 1/2) and field range (B max ∝ T −1) are unavoidably coupled as η 2 ∝ B max. In contrast, a Berry sequence used for geometric-phase magnetometry employs all three control parameters, and thus the sensitivity (η ∝ Ω −1 N T 1/2) can be chosen independently of the field range (B m ax ∝ Ω N 1/2 T 0). For example, larger B max with constant η is obtainable with geometric-phase magnetometry by increasing Ω and N while keeping T and the ratio Ω / N fixed. Error bars represent one standard deviation of the results

---

### Modelling sequences and temporal networks with dynamic community structures [^7129d625]. Nature Communications (2017). Medium credibility.

Bayesian Markov chains with communities

As described in the main text, a Bayesian formulation of the Markov model consists in specifying prior probabilities for the model parameters, and integrating over them. In doing so, we convert the problem from one of parametric inference where the model parameters need to be specified before inference, to a nonparametric one where no parameters need to be specified before inference. In this way, the approach possesses intrinsic regularisation, where the order of the model can be inferred from data alone, without overfitting.

To accomplish this, we rewrite the model likelihood, using eqs. (1) and (5), asand observe the normalisation constraints,… Since this is just a product of multinomials, we can choose conjugate Dirichlet priors probability densitiesand, which allows us to exactly compute the integrated likelihood, whereand. We recover the Bayesian version of the common Markov chain formulation (see ref.) if we put each memory and token in their own groups. This remains a parametric distribution, since we need to specify the hyperparameters. However, in the absence of prior information it is more appropriate to make a noninformative choice that encodes our a priori lack of knowledge or preference towards any particular model, which amounts to choosing α x = β rs = 1, making the prior distributions flat. If we substitute these values in eq. (19), and re-arrange the terms, we can show that it can be written as the following combination of conditional likelihoods, wherewithbeing the multiset coefficient, that counts the number of m -combinations with repetitions from a set of size n. The expression above has the following combinatorial interpretation: P ({ x t }| b, { e rs }, { k x }) corresponds to the likelihood of a microcanonical modelwhere a random sequence { x t } is produced with exactly e rs total transitions between groups r and s, and with each token x occurring exactly k x times. In order to see this, consider a chain where there are only e rs transitions in total between token group r and memory group s, and each token x occurs exactly k x times. For the first transition in the chain, from a memory x 0 in group s to a token x 1 in group r, we have the probabilityNow, for the second transition from memory x 1 in group t to a token x 2 in group u, we have the probabilityProceeding recursively, the final likelihood for the entire chain iswhich is identical to eq. (21).

---

### Hand grip strength as a physical biomarker of aging from the perspective of a fibonacci mathematical modeling [^1dd20d12]. BMC Geriatrics (2018). Low credibility.

Background

The Golden Ratio (GR) and the Fibonacci sequence have wide applications in biodiversity research, and recent studies indicate that the GR can be highlighted in the organization and physiological functioning of many body systems. The aim of this cross-sectional descriptive study is to determine the applicability of a mathematical model derived from the Fibonacci sequence to investigate the changes in hand grip strength (HGS) induced by the aging process.

Methods

We assessed the HGS for both hands, using a Saehan hydraulic hand dynamometer in a group of autonomous elderly subjects. One hundred twenty 55-year-old subjects (58 males and 62 females) and seventy 89-year-old subjects (31 men and 39 women) were included in the study group. All subjects were completely independent or independent with minimal assistance in activities of daily living (ADL), as determined after applying the Barthel index of ADL. The data series were statistically processed using descriptive statistics (univariate analysis) and inferential statistical methods (the t test for unpaired groups, with effect size measure - Cohen's d and the ratio of the means method).

Results

The decline of the relative HGS between the two age groups can be expressed by values close to the GR value (p < 0.001), both in relation to body symmetry (left hand/right hand evaluation) and laterality (dominant hand/non-dominant hand evaluation), for both sexes. For the whole group of men and women, the rhythm of HGS decline may be expressed by a value (1.61) notably close to the GR, regardless of body symmetry or laterality.

Conclusions

The common pattern of the relative HGS reduction between 55 and 89years, as expressed by a value notably close to GR, can be considered to be an expression of a specific and predictable manifestation of the aging process, in the absence of disability.

---

### Abstract representations of events arise from mental errors in learning and memory [^5646fd8b]. Nature Communications (2020). High credibility.

Methods

Maximum entropy model and the infinite-sequence limit

Here we provide a more thorough derivation of our maximum entropy model of human expectations, with the goal of fostering intuition. Given a matrix of erroneous transition counts, our estimate of the transition structure is given by. When observing a sequence of nodes x 1, x 2, …, in order to construct the counts, we assume that humans use the following recursive rule: where B t (i) denotes the belief, or perceived probability, that node i occurred at the previous time t. This belief, in turn, can be written in terms of the probability P (Δ t) of accidentally recalling the node that occurred Δ t time steps from the desired node at time t:

In order to make quantitative predictions about people's estimates of a transition structure, we must choose a mathematical form for P (Δ t). To do so, we leverage the free energy principle: When building mental models, the brain is finely tuned to simultaneously minimize errors and computational complexity. The average error associated with a candidate distribution Q (Δ t) is assumed to be the average distance in time of the recalled node from the target node, denoted. Furthermore, Shannon famously proved that the only suitable choice for the computational cost of a candidate distribution is its negative entropy, denoted. Taken together, the total cost associated with a distribution Q (Δ t) is given by the free energy F (Q) = βE (Q) − S (Q), where β, referred to as the inverse temperature, parameterizes the relative importance of minimizing errors versus computational costs. By minimizing F with respect to Q, we arrive at the Boltzmann distribution p (Δ t) = e − β Δ t / Z, where Z is the normalizing partition function. We emphasize that this mathematical form for P (Δ t) followed directly from our free energy assumption about resource constraints in the brain.

---

### Alignment-free population genomics: an efficient estimator of sequence diversity [^6c3f2b55]. G3 (2012). Low credibility.

Derivation of

We wish to know the distribution of shustring lengths as a function of the average number of differences per site. For the derivation of the shustring length distribution, we use the well-kown fact from coalescent theory that the time to the most recent common ancestor of two lineages is approximately exponential with expectation N e, where N e is the effective (haploid) population size.

First, we compute the distribution of X i, i, where we assume that position i in Q and i in S are homologous. The fact that our data are unaligned does not invalidate this assumption for the purpose of deriving. We further assume that no recombination event falls between i and i + X i, i until Q and S coalesce in this genomic region. This is equivalent to assuming that mutation is more frequent than recombination. Moreover, we take π / N e as a proxy for the mutation probability per generation per site. Then we obtain for an exponentially distributed random variable T with expectation N e Second, we compute the distribution of X i, i ′ for i ≠ i ′. We assume that the two subsequences starting at i in Q and at i ′ in S are random words with GC -content 2 p and AT -content 1–2 p. We know from equation 1 inand equation 4 inthatwhich for equiprobable nucleotidessimplifies toIn this case, the distribution of max i ≠ i ′ X i, i ′ is concentrated around x ∼ log 4 (2ℓ S). By combining Equations 1 and 2, we obtainandAs explained in the previous section, we can observewhere f (x) is the absolute number of shustrings of length x for a pair of sequences and ξ is the length of the longest shustring. Now we assume that f (x) is the realization of a Poisson-distributed random variable with parameterand that f (1), f (2),… are independent. We can then readily compute the log-likelihoodfor some C, which does not depend on π. Hence, the maximum-likelihood estimator for π, is given by maximizingOne often needs to computerepeatedly during a sliding window analysis, where an interval Q [i. j] is fixed with, say, j – i = 10 5, i.e. extends over 100 kb. Then, using Q [i, …, j] as the query and S as the subject, the above computations work as well, as we can still assume that every position in Q [i, …, j] has a homolog in S. Here, we observe f (1), f (2),… for the specific window Q [i, …, j], and maximize the likelihood as given in Equation 6.

---

### Modelling sequences and temporal networks with dynamic community structures [^81172c1e]. Nature Communications (2017). Medium credibility.

The above priors make the model fully nonparametric with a joint and marginal probability P ({ x t }, b) = P ({ x t }, b, { e s }) = P ({ x t }| b, { e s }) P (b) P ({ e s }). This approach successfully finds the most appropriate number of groups according to statistical evidence, without overfitting. This nonparametric method can also detect the most appropriate order of the Markov chain, again without overfitting. However, in some ways it is still sub-optimal. The use of conjugate Dirichlet priors above was primarily for mathematical convenience, not because they closely represent the actual mechanisms believed to generate the data. Although the noninformative choice of the Dirichlet distribution (which yields flat priors for { e rs } and { e s }) can be well justified by maximum entropy arguments (see ref.), and are unbiased, it can in fact be shown that it can lead to underfitting of the data, where the maximum number of detectable groups scales sub-optimally as. As shown in ref. this limitation can be overcome by departing from the model with Dirichlet priors, and replacing directly the priors P ({ e rs }|{ e s }) and P ({ e s }) of the microcanonical model by a single prior P ({ e rs }), and noticing that { e rs } corresponds to the adjacency matrix of bipartite multigraph with E edges and B N + B M nodes. With this insight, we can write P ({ e rs }) as a Bayesian hierarchy of nested SBMs, which replaces the resolution limit above by N /ln N, and provides a multilevel description of the data, while remaining unbiased. Furthermore, the uniform prior in eq. (8) for the token frequencies P ({ k x }|{ e rs }, (b) intrinsically favours concentrated distributions of k x values. This distribution is often skewed. We therefore replace it by a two-level Bayesian hierarchy, withand, where q (m, n) is the number of restricted partitions of integer m into at most n parts (see ref.for details).

---

### Accurately clustering biological sequences in linear time by relatedness sorting [^120d0aa3]. Nature Communications (2024). High credibility.

Two different values of k-mer length (k) are computed: one for use with k-mer matching between sequences and the other for use with rare k-mers. The goal of selecting k for k-mer matching is to ensure that k-mer matches between two sequences happen infrequently by chance, while using only a single value of k across all sequences. Hence, k is calculated such that one in every 100 k-mers is expected to be found by chance in sequences at the 99th percentile of input sequence lengths using an alphabet with a given number of letters (x):

The reasoning behind this formula for k was previously described. In contrast, k for rare k-mers is set such that at most 10% of the selected 20,000 (i.e. parameter A) sequences are expected to share a rare k-mer due to chance. Each of N sequences contributes 50 (by default) rare k-mers, and the objective is to find k such that each rare k-mer will be found by chance in less than 40 (i.e. 20,000/50 * 10%) sequences on average. Thus, k for rare k-mers is calculated as:

---

### Accurately clustering biological sequences in linear time by relatedness sorting [^eb9669e1]. Nature Communications (2024). High credibility.

As relatedness sorting progresses, the rank ordering (v) typically stabilizes, with some sequences stabilizing before others. When a sequence's rank order stabilizes below 1000 (i.e. parameter C /2), its partition is split into separate groups at this sequence (Fig. 1J), as long as each new group would contain at least 2000 sequences. Relatedness sorting is continued within each group until all of its sequences stabilize in rank order below 1000 or the maximum number of iterations (i.e. parameter B) is reached. In practice, most groups stabilize in rank order before 2000 iterations and, thus, parameter B is not a limiting factor. Rank order stability is defined as v ≤ 1000 because the sequences are moving within 2000 positions on average (i.e. ± 1000), which is the number of sequences considered in phase 3 of the algorithm (i.e. parameter C).

Phase 3: clustering sequences in linear time

No sequences were clustered in phases 1 or 2, but the sequences were ordered by relatedness in preparation for clustering. Two linear time strategies are used for clustering sequences: (1) The rare k-mer strategy draws sequences for comparison in the exact same manner as used in phase 1, thereby prioritizing sequences sharing the greatest number of rare k-mers; (2) The relatedness sorting strategy selects proximal sequences from the final rank ordering of sequences determined in phase 2. Up to 2000 (i.e. parameter C) total sequences are drawn from the two strategies in proportion to the number of clustered sequences arising from each strategy. That is, when a sequence is added to an existing cluster, Clusterize determines whether the sequence was in the set of sequences originating from rare k-mers and/or relatedness sorting. The count of sequences drawn from each strategy is incremented in accordance with the clustered sequence's origin(s). In this manner, the more lucrative strategy is emphasized when determining where to draw the next 2000 candidate sequences.

K-mer similarity is calculated to the cluster representatives corresponding to all 2000 sequences, and any cluster representative passing the similarity threshold is used for assignment. If none exists, the sequence is aligned with up to 200 (i.e. parameter E) cluster representatives having the highest k-mer similarities. If none of these are within the similarity threshold, the sequence becomes a new cluster representative. To avoid issues with partial-length sequences, the sequences are visited in order of decreasing length so that the cluster representative is always the longest sequence in its cluster.

---

### Molecular constraints on CDR3 for thymic selection of MHC-restricted TCRs from a random pre-selection repertoire [^9d7ffbdd]. Nature Communications (2019). High credibility.

Fig. 8
Frequency scatter plots. a, c Frequency scatter plots among MHC-restricted TCRβ (a) and TCRα (c) repertoires from individual B6 mice. b, d Frequency scatter plots among MHCi TCRβ (b) and TCRα (d) repertoires from individual Quad ko sequences. Each panel contains the comparison of three independent sequence repertoires from each strain of mice with the horizontal axis representing the frequencies of the first repertoire sequences, vertical axis representing the frequencies of the second (red circle) and third (green circle) repertoires. Common sequences between repertoire 1 and 2 are shown as red circles in the first quadrant with horizontal and vertical coordinates representing their respective frequencies in repertoire 1 and 2. Common sequences between repertoire 1 and 3 are shown as green circles with horizontal and vertical coordinates representing their respective frequencies in repertoire 1 and 3. Non-overlapping sequences appear on their respective axes. Top 200 common sequences present in all three repertoires are shown as filled yellow circles. Linear regressions of the frequency distributions between B6 repertoires 1 and 2 are shown in red lines. e CDR3β length-dependent expansion of MHCr and MHCi sequences from pre-selection repertoires. The percentage of expanded TCRβ sequences during thymic selection were plotted according to their CDR3 length for B6, Quad ko and Quad ko Bcl-2 tg. The analysis included common sequences between pre-selection (B6_DN) and MHCr (B6) or MHCi (Q and QB mice) repertoires. Expansion is defined as sequences whose mature frequencies (normalized for all comparing repertoires) were higher than their pre-selection ones. f Charged amino acid usages of CDR3β FG-loop in common sequences between pre-selection and MHCr or MHCi repertoires. B6 (+ 5%), top 5% TCRβ sequences of B6 repertoires; B6 +, B6 −, Q +, and Q − represent mature sequences either expanded (+) or not expanded (−) in frequency compared to their pre-selection repertoire

---

### Species abundance information improves sequence taxonomy classification accuracy [^31c457c8]. Nature Communications (2019). High credibility.

Popular naive Bayes taxonomic classifiers for amplicon sequences assume that all species in the reference database are equally likely to be observed. We demonstrate that classification accuracy degrades linearly with the degree to which that assumption is violated, and in practice it is always violated. By incorporating environment-specific taxonomic abundance information, we demonstrate a significant increase in the species-level classification accuracy across common sample types. At the species level, overall average error rates decline from 25% to 14%, which is favourably comparable to the error rates that existing classifiers achieve at the genus level (16%). Our findings indicate that for most practical purposes, the assumption that reference species are equally likely to be observed is untenable. q2-clawback provides a straightforward alternative for samples from common environments.

---

### Dissecting splicing decisions and cell-to-cell variability with designed sequence libraries [^92c9c73e]. Nature Communications (2019). High credibility.

Most human genes are alternatively spliced, allowing for a large expansion of the proteome. The multitude of regulatory inputs to splicing limits the potential to infer general principles from investigating native sequences. Here, we create a rationally designed library of > 32,000 splicing events to dissect the complexity of splicing regulation through systematic sequence alterations. Measuring RNA and protein splice isoforms allows us to investigate both cause and effect of splicing decisions, quantify diverse regulatory inputs and accurately predict (R 2 = 0.73–0.85) isoform ratios from sequence and secondary structure. By profiling individual cells, we measure the cell-to-cell variability of splicing decisions and show that it can be encoded in the DNA and influenced by regulatory inputs, opening the door for a novel, single-cell perspective on splicing regulation.

---

### Input-output maps are strongly biased towards simple outputs [^50fca0dd]. Nature Communications (2018). Medium credibility.

Many systems in nature can be described using discrete input-output maps. Without knowing details about a map, there may seem to be no a priori reason to expect that a randomly chosen input would be more likely to generate one output over another. Here, by extending fundamental results from algorithmic information theory, we show instead that for many real-world maps, the a priori probability P(x) that randomly sampled inputs generate a particular output x decays exponentially with the approximate Kolmogorov complexity [Formula: see text] of that output. These input-output maps are biased towards simplicity. We derive an upper bound P(x)≲[Formula: see text], which is tight for most inputs. The constants a and b, as well as many properties of P(x), can be predicted with minimal knowledge of the map. We explore this strong bias towards simple outputs in systems ranging from the folding of RNA secondary structures to systems of coupled ordinary differential equations to a stochastic financial trading model.

---

### Immunogenicity and safety of a quadrivalent live attenuated influenza vaccine in children [^d09e355a]. The Pediatric Infectious Disease Journal (2012). Low credibility.

Background

Influenza B viruses from 2 lineages cocirculate annually. Because the single B strain contained in trivalent vaccines may not match the major circulating strain, adding a second B virus could enhance protection. This study compared the safety and immunogenicity of an investigational quadrivalent Ann Arbor strain live attenuated influenza vaccine (Q/LAIV) with that of 2 trivalent vaccines (T/LAIV), each containing a B strain from a different lineage.

Methods

This randomized, double-blind study was designed to demonstrate the immunologic noninferiority of Q/LAIV compared with T/LAIV in children 2–17 years of age by comparing postdose geometric mean titers of hemagglutination inhibition antibodies. Children were randomized 3:1:1 to receive Q/LAIV or 1 of 2 T/LAIV vaccines. Those subjects who were 9–17 years of age received 1 dose, and those 2–8 years of age received 2 doses 1 month apart. Serum immune responses were evaluated 1 month after dose 1 (dose 2 for influenza vaccine-naive subjects aged 2–8 years).

Results

Q/LAIV was noninferior to T/LAIV: upper bounds for all four 95% confidence intervals for the postdose geometric mean titer ratios (T/LAIV divided by Q/LAIV) were ≤ 1.5, the predefined noninferiority margin. The overall seroresponse rates (4-fold rise) were comparable between treatment groups. Safety events were comparable, except that fever was more common after dose 1 in Q/LAIV subjects (5.1%) than in T/LAIV subjects (3.1%) 2–8 years of age.

Conclusions

The immunogenicity of Q/LAIV was noninferior to that of T/LAIV in children aged 2–17 years; safety was also comparable. Q/LAIV may broaden the protection against influenza B strains provided by current trivalent influenza vaccines.

---

### Pneumococcal 13-valent conjugate vaccine (Prevnar 13) [^05d7fb30]. FDA (2018). Low credibility.

Children 5 Through 17 Years of Age

In a US study5(Study 5), a single dose of Prevnar 13 was administered to children 5 through 9 years of age, who were previously vaccinated with at least one dose of Prevnar, and to pneumococcal vaccine-naïve children 10 through 17 years of age.

In children 5 through 9 years of age, serotype-specific IgG concentrations measured 1 month after vaccination were noninferior (i.e., the lower limit of the 2-sided 95% CI for the geometric mean ratio [GMR] of > 0.5) to the corresponding IgG concentrations in toddlers (Study 3) 1 month after a fourth pneumococcal vaccination (after the 4thdose of Prevnar for the 7 common serotypes and after the 4thdose of Prevnar 13 for the 6 additional serotypes) as shown in Tables 22 and 23 respectively.

In children 10 through 17 years of age OPA GMTs, as measured by the mcOPA assay, 1 month after vaccination were noninferior (i.e., the lower limit of the 2-sided 95% CI for the GMR of > 0.5) to mcOPA GMTs in the 5 through 9 year old group for 12 of 13 serotypes (except for serotype 3), as shown in Table 24.

---

### Fine-scale patterns of SARS-CoV-2 spread from identical pathogen sequences [^4c951635]. Nature (2025). Excellent credibility.

Expected relationship with RR of contact

We perform a simulation study to characterize the expected relationship between the RR of observing identical sequences between groups and the RR of contacts between these groups. We illustrate this by looking at transmission between age groups but we expect a similar relationship between the RR of observing identical sequences between regions and the RR of movement between these regions.

To do so, we generate clusters of identical sequences including the age group of the corresponding infected individuals assuming a probability that an infector and an infectee have the same consensus sequences p of 0.7 (close to the value we previously estimated for SARS-CoV-2), a reproduction number R of 1.2 and a sequencing fraction p seq of 0.1.

We use a contact matrix estimated previouslyto characterize disease transmission between age groups. We assume that the probability p A, B for a contact from an infected individual in age group A to occur with a susceptible individual in age group B is equal to:where c A, B is the mean daily number of contacts that an individual in age group A has with individuals in age group B. We introduce an age-specific reproduction number (R A) describing the average number of secondary cases infected by a single primary case within age group A. As different age groups have different average daily total number of contacts, the age-specific reproduction number varies between age groups. It can be derived as:where ρ (C) is the maximum eigenvalue of the matrix C = (c A, B). We then simulate individual clusters of identical sequences using the following steps. First, we initialize clusters by drawing the age of the primary case A primary from a uniform distribution. Second, we simulate clusters as successive infections with identical genomes. At each generation, for each individual infected at the previous generation, let A denote the age of this infectious individual. We use the following procedure:
Draw the number of infections with the same genotype:(Poisson distribution).
Draw the age of these individuals:whereis a multinomial distribution with n trials, k possible events with probabilities (p 1. p k).
Draw the sequencing status of each new cluster member from a Bernoulli distribution of parameter p seq.

We end simulations after ten generations to minimize computational costs.

---

### Determining sequencing depth in a single-cell RNA-seq experiment [^ce3ab87a]. Nature Communications (2020). High credibility.

An underlying question for virtually all single-cell RNA sequencing experiments is how to allocate the limited sequencing budget: deep sequencing of a few cells or shallow sequencing of many cells? Here we present a mathematical framework which reveals that, for estimating many important gene properties, the optimal allocation is to sequence at a depth of around one read per cell per gene. Interestingly, the corresponding optimal estimator is not the widely-used plug-in estimator, but one developed via empirical Bayes.

---

### The effect that genotyping errors have on the robustness of common linkage-disequilibrium measures [^f05eb605]. American Journal of Human Genetics (2001). Low credibility.

The rapid development of a dense single-nucleotide-polymorphism marker map has stimulated numerous studies attempting to characterize the magnitude and distribution of background linkage disequilibrium (LD) within and between human populations. Although genotyping errors are an inherent problem in all LD studies, there have been few systematic investigations documenting their consequences on estimates of background LD. Therefore, we derived simple deterministic formulas to investigate the effect that genotyping errors have on four commonly used LD measures-D', r, Q, and d-in studies of background LD. We have found that genotyping error rates as small as 3% can have serious affects on these LD measures, depending on the allele frequencies and the assumed error model. Furthermore, we compared the robustness of D', r, Q, and d, in the presence of genotyping errors. In general, Q and d are more robust than D' and r, although exceptions do exist. Finally, through stochastic simulations, we illustrate how genotyping errors can lead to erroneous inferences when measures of LD between two samples are compared.

---

### Dynamics of fMRI patterns reflect sub-second activation sequences and reveal replay in human visual cortex [^160d037f]. Nature Communications (2021). High credibility.

Fig. 5
Detecting sparse sequence events with lower SNR.

a Mean standard deviation of classifier probabilities in rest and sequence data (n = 32, t s ≥ 4.17, p s < 0.001, d s ≥ 0.74, two two-sided paired t -tests comparing rest and 2048 ms conditions against 32 ms condition, FDR-corrected). b Mean absolute regression slopes, as in (a) (n = 32, t s ≥ 4.64, p s < 0.001, d s ≥ 0.82, two two-sided paired t -tests comparing rest and 2048 ms conditions against 32 ms condition, FDR-corrected). c Time courses of the regression slopes (signed values, not magnitudes) in rest and sequence data. Vertical lines indicate trial boundaries. d Normalized frequency spectra of regression slopes in rest and sequence data. Annotations indicate predicted frequencies based on Eq. (5). e Mean power of predicted frequencies in rest and sequence data, as in (a). Each dot represents data from one participant (n = 32, t s ≥ 3.10, p s ≤ 0.002, two-sided paired t -tests, FDR-corrected). f Mean standard deviation of rest data including a varying number of SNR-adjusted sequence events (fast or slow). Dashed line indicates indifference from sequence-free rest (n = 32, t s ≥ 2.22, p s ≤ 0.04, 30 two-sided one-sample t -tests against chance, FDR-corrected). g Base-20 log-transformed p values of t -tests comparing the standard deviation of probabilities in (f) with sequence-free rest. Dashed line indicates p = 0.05 (N = 32, t s ≥ 2.22, p s ≤ 0.04, 30 two-sided one-sample t -tests against chance, FDR-corrected). h Frequency spectra of regression slopes in SNR-adjusted sequence-containing rest relative to sequence-free rest. Rectangles indicate predicted frequencies, as in (d). i Mean relative power of predicted frequencies in SNR-adjusted sequence-containing rest (n = 32, t s ≥ 2.28, p s ≤ 0.03, two-sided t -tests against baseline, FDR-corrected). Shaded areas/error bars represent ± 1 SEM. All statistics have been derived from data of n = 32 human participants who participated in one experiment. 1 TR = 1.25 s. Source data are provided as a Source Data file.

---

### Opportunities and challenges associated with clinical diagnostic genome sequencing: a report of the Association for Molecular Pathology [^ddc6fcf3]. The Journal of Molecular Diagnostics (2012). Medium credibility.

Clinical diagnostic genome sequencing — alignment workflows often use a tiered approach: sequences aligning on a subset of the read are assigned a quality score based on mismatches to the reference, nonplaced reads undergo multistep gapped alignment, and probability values are assigned across solutions with the best alignment kept and scored on the Q scale; this may require use of more than one aligner, and for clinical applications, conservative approaches are most appropriate because high confidence should exist when making a call.

---

### Individual differences in belief updating and phasic arousal are related to psychosis proneness [^3118c4bd]. Communications Psychology (2024). Medium credibility.

Normative model for main behavioral task

The normative model for the main task prescribes the following computation:Here, L n was the observer belief after encountering the evidence sample x n, expressed in log-posterior odds of the alternative task states; LLR n was the log-likelihood ratio reflecting the relative evidence for each alternative carried by x n (LLR n = log(p (x n | right)/ p (x n | left))); and ψ n was the prior expectation of the observer before encountering x n. We used this model to derive two computational quantities: CPP and - |ψ |. CPP was the posterior probability that a change in generative task state has just occurred, given the expected H, the evidence carried by x n, and the observer's belief before encountering that sample L n-1, computed as follows (see ref.for derivation):where N(x | S) denoted the probability of sample x given a normal distribution with mean μ S and s.d. σ S. Uncertainty was defined as the negative absolute of the prior (- |ψ n |), reflecting uncertainty about the generative state before observing x n.

Main task model fitting and comparison

We first computed the accuracy of participants' choices with respect to the true final generative state, and compared this to the accuracy yielded by three idealized decision processes presented with identical stimulus sequences: normative accumulation (Eqs. 1 and 2), perfect accumulation, and only using the final evidence sample. For each trial, choice r (left = -1, right = +1) was determined by the sign of the log-posterior odds after observing all samples:for normative, for perfect, andfor last-sample, where n indicated the number of samples presented on trial trl.

We fit variants of the normative model to participants' behavior, assuming that choices were based on the log-posterior odds L n, trl for the observed stimulus sequence on each trial. In line with previous work with this model, different model variants had different combinations of the following free parameters: L n, trl was corrupted by a decision noise term ν, such that choice probabilitywas computed as:

---

### Fast multi-planar gradient echo MR imaging: impact of variation in pulse sequence parameters on image quality and artifacts [^338d03ff]. Magnetic Resonance Imaging (2004). Low credibility.

The purpose of this investigation was to quantitatively evaluate the practical impact of alteration of key imaging parameters on image quality and artifacts in fast multi-planar gradient echo (GRE) pulse sequences. These include multi-planar GRASS (MPGR) and fast multi-planar spoiled GRASS (FMPSPGR). We developed a composite phantom with different T(1) and T(2) values comprising the range of common biological tissues, which was also subjected to periodic motion in order to evaluate motion effects. Magnetic resonance imaging was performed on a GE Signa 1.5-T system. Experimental variations in key parameters included excitation flip angle (FL), echo time (TE), repetition time (TR), and receive bandwidth (BW). Quantitative analysis consisted of signal-to-noise-ratio (SNR) and contrast (CN), image nonuniformity (NU), full-width-at-half-maximum (FWHM) (i.e., blurring or geometric distortion), and ghosting ratio (GR). We found that flip angle, TE, and TR play particularly critical roles in determining image signal, homogeneity, and ghosting artifact with these sequences. Optimum clinical application of these pulse sequences requires careful attention to these imaging parameters and to their complex interactions.

---

### Metformin hydrochloride [^02b5e356]. FDA (2025). Medium credibility.

Specific Populations Renal Impairment

In patients with decreased renal function the plasma and blood half-life of metformin is prolonged and the renal clearance is decreased (see Table 3) [see Dosage and Administration (2.3), Contraindications (4), Warnings and Precautions (5.1) and Use in Specific Populations (8.6)].

Hepatic Impairment

No pharmacokinetic studies of metformin have been conducted in patients with hepatic impairment [see Warnings and Precautions (5.1) and Use in Specific Populations (8.7)].

Geriatrics

Limited data from controlled pharmacokinetic studies of metformin hydrochloride tablets in healthy elderly subjects suggest that total plasma clearance of metformin is decreased, the half-life is prolonged, and Cmaxis increased, compared to healthy young subjects. It appears that the change in metformin pharmacokinetics with aging is primarily accounted for by a change in renal function (see Table 4) [see Warnings and Precautions (5.1) and Use in Specific Populations (8.5)].

Table 4: Select Mean (± S.D.) Metformin Pharmacokinetic Parameters Following Single or Multiple Oral Doses of Metformin Hydrochloride Tablets

Pediatrics

After administration of a single oral Metformin Hydrochloride Tablets 500 mg with food, geometric mean metformin Cmax and AUC differed less than 5% between pediatric type 2 diabetic patients (12–16 years of age) and gender- and weight-matched healthy adults (20–45 years of age), all with normal renal function.

Gender

Metformin pharmacokinetic parameters did not differ significantly between normal subjects and patients with type 2 diabetes mellitus when analyzed according to gender (males = 19, females = 16).

Race

No studies of metformin pharmacokinetic parameters according to race have been performed.

Drug Interactions

In Vivo Assessment of Drug Interactions

Table 5: Effect of Coadministered Drug on Plasma Metformin Systemic Exposure

Table 6: Effect of Metformin on Coadministered Drug Systemic Exposure

*All metformin and coadministered drugs were given as single doses

+AUC = AUC (INF) unless otherwise noted

‡ Ratio of arithmetic means, p-value of difference < 0.05

§AUC (0–24 hr) reported

¶ Ratio of arithmetic means

---

### Probabilities of developing HIV-1 bNAb sequence features in uninfected and chronically infected individuals [^162051b8]. Nature Communications (2023). High credibility.

Global BCR repertoire features under chronic infections are similar to uninfected repertoires with marginal differences

Since chronic infections have been described to interfere with B cell development and functionality, we wondered whether and to what extent they influence memory IgG BCR sequence characteristics. To answer this question, we sequenced BCRs from the IgG + memory compartment of 34 HIV-1 and 12 hepatitis C virus (HCV)-infected individuals and compared them to the 57 uninfected repertoires (Fig. 3a).

Fig. 3
IgG heavy chain repertoire characteristics of uninfected and chronically infected individuals.

a Cohort overview with age and sex distributions. Single dots in age distributions represent individuals, bar graphs and error bars depict mean cohort age ± SD. One individual (HIV-1) reported neither sex nor age. b V gene segment usage distributions for heavy, kappa, and lambda chains, ordered by descending frequencies according to the uninfected control (CTRL) group (n = 57 for CTRL, n = 34 for HIV-1, and n = 12 for HCV). c Mean CDR3 length distributions for heavy, kappa, and lambda chains in amino acids (aa). Left panel shows the mean CDR3 length distributions across individuals for each cohort (n = 57 for CTRL, n = 34 for HIV-1, and n = 12 for HCV) as solid lines and standard deviations as shaded areas. Right panel shows mean CDR3 amino acid length as dots for each individual and cohort statistics as box-plots. d Mean V gene nucleotide mutation (mut.) frequencies for heavy, kappa, and lambda chains. Representation of mean distributions (left panel) and individual means (right panel) as in c for all three cohorts (n = 57 for CTRL, n = 34 for HIV-1, and n = 12 for HCV). One-way ANOVA with a two-sided Tukey-HSD post-hoc test was performed on the means in c and d. e Representative examples of clone trees for the cohorts based on heavy chain sequences. f The weights (i.e. the number of leaves deriving from a given node) were determined for the common ancestor of each clone (ω anc.) and its immediate descendants (ω D). Distributions of their ratios (ω D /ω anc.) were plotted (left panel) to illustrate the clone tree skewness (dashed line = neutral, see methods for details). The right panel shows the mean terminal/mean branch length distribution for clone trees. g Clone size distribution for the cohorts. h Clone diversity determined by Gini-Simpson index and entropy (n = 57 for CTRL, n = 34 for HIV-1, and n = 12 for HCV). Data is presented as mean values ± SD. Box-plots in panels b – d depict 25% and 75% percentiles with medians as average lines and minimum/maximum values as whiskers. Source data are provided as a Source Data file.

---

### Solving the where problem and quantifying geometric variation in neuroanatomy using generative diffeomorphic mapping [^fd44f32f]. Nature Communications (2025). High credibility.

The statistical interpretation allows us to accommodate images with non reference signals, such as missing tissue, tracer injection sites, or other anomalies. At each pixel, the identity of the signal type is modeled as missing data, and maximum likelihood estimators are computed using an Expectation Maximization algorithm, which alternates between the E step: compute posterior probability π i (x) that each pixel corresponds to the reference image rather than one of the non-reference types, and the M step: update parameters by solving a posterior weighted version of the above:As an EM algorithm, this approach is guaranteed to be monotonically increasing in likelihood. An example of posterior weights are shown in the right hand column of Fig. 2 b.

Our approach uses mixtures of Gaussians to model variability in data, to allow large outliers to be accommodated by additional components, even though the Gaussian distribution itself does not have long tails. The Gaussian model allows for closed form expression (in terms of matrix inverse) for contrast transformation parameters. Other groups have used long tailed distributions to model variability and outliers in a robust manner, most notably the exponential distribution for l1 optimization. Techniques such as iteratively reweighted least squares can be applied as in Reuter et al. which lead lead to a weighted least squares problem which is similar to ours.

Nonconvex optimization with low to high dimensional subgroups and resolutions

This registration problem is highly nonconvex, and allows for many local minima. To provide robustness in our solution, we solve a sequence of lower dimensional subproblems, initializing the next with the solution to the previous. (i) 2D slice to slice rigid alignment maximizing similarity to neighbors(ii) 3D affine only alignment, registration using the full model at (iii) low (200 μm), (iv) medium (100 μm), and (v) high (50 μm) resolution. Time varying velocity fields are discretized into 5 timesteps and integrated using the Semi Lagrangian method. For most subproblems, spatial transformation parameters are estimated by gradient descent, and intensity transformation parameters are updated by solving a weighted least squares solution at each iteration. For subproblems that include linear registration only, parameters are estimated using Reimannian gradient descent (discussed in ref.and similar to a second order Gauss–Newton optimization scheme).

---

### How do you design randomised trials for smaller populations? A framework [^45132483]. BMC Medicine (2016). Low credibility.

How should we approach trial design when we can get some, but not all, of the way to the numbers required for a randomised phase III trial?We present an ordered framework for designing randomised trials to address the problem when the ideal sample size is considered larger than the number of participants that can be recruited in a reasonable time frame. Staying with the frequentist approach that is well accepted and understood in large trials, we propose a framework that includes small alterations to the design parameters. These aim to increase the numbers achievable and also potentially reduce the sample size target. The first step should always be to attempt to extend collaborations, consider broadening eligibility criteria and increase the accrual time or follow-up time. The second set of ordered considerations are the choice of research arm, outcome measures, power and target effect. If the revised design is still not feasible, in the third step we propose moving from two- to one-sided significance tests, changing the type I error rate, using covariate information at the design stage, re-randomising patients and borrowing external information. We discuss the benefits of some of these possible changes and warn against others. We illustrate, with a worked example based on the Euramos-1 trial, the application of this framework in designing a trial that is feasible, while still providing a good evidence base to evaluate a research treatment. This framework would allow appropriate evaluation of treatments when large-scale phase III trials are not possible, but where the need for high-quality randomised data is as pressing as it is for common diseases.

---

### Metformin hydrochloride tablet (metformin hydrochloride) [^005f9cc8]. FDA (2023). Medium credibility.

eKinetic study done following dose 19, given fasting

fElderly subjects, mean age 71 years (range 65 to 81 years)

gCLcr = creatinine clearance normalized to body surface area of 1.73 m2

Pediatrics

After administration of a single oral metformin hydrochloride 500 mg tablet with food, geometric mean metformin Cmaxand AUC differed less than 5% between pediatric type 2 diabetic patients (12 to 16 years of age) and gender- and weight-matched healthy adults (20 to 45 years of age), all with normal renal function.

Gender

Metformin pharmacokinetic parameters did not differ significantly between normal subjects and patients with type 2 diabetes mellitus when analyzed according to gender (males = 19, females = 16).

Race

No studies of metformin pharmacokinetic parameters according to race have been performed.

Drug Interactions In Vivo Assessment of Drug Interactions

Table 5: Effect of Coadministered Drug on Plasma Metformin Systemic Exposure

* All metformin and coadministered drugs were given as single doses

†AUC = AUC(INF)

‡Ratio of arithmetic means

§At steady state with topiramate 100 mg every 12 hours and metformin 500 mg every 12 hours;

AUC = AUC0-12h

Table 6: Effect of Metformin on Coadministered Drug Systemic Exposure

* All metformin and coadministered drugs were given as single doses

†AUC = AUC(INF) unless otherwise noted

‡Ratio of arithmetic means, p-value of difference < 0.05

§AUC(0–24 hr) reported

¶Ratio of arithmetic means

---

### How do you design randomised trials for smaller populations? A framework [^9ac3f0db]. BMC Medicine (2016). Low credibility.

Exploring less common approaches to reducing sample size

We now consider some less standard approaches to bringing the sample size requirements closer to the numbers it is feasible to recruit in a reasonable time frame.

Step 3: Relaxing α by a small amount, beyond traditional values

The much-criticised 5% significance level is used widely in much applied scientific research, but is an arbitrary figure. It is extremely rare for clinical trials to use any other level. It may be argued that this convention has been adopted as a compromise between erroneously concluding a new treatment is more efficacious and undertaking a trial of an achievable size and length. Settings where traditionally sized trials are not possible may be just the area where researchers start to break this convention, for good reason.

In considering the type I error, it is critical to consider the question: 'What are the consequences of erroneously deciding to use a new treatment routinely if it is truly not better?'

Taking the societal perspective as before, we might consider the probability of making a type I error, thus erroneously burdening patients with treatments that do not improve outcomes, or even worsen them, while potentially imposing unnecessary toxicity.

First, for conditions where there are only enough patients available to run one modestly sized randomised trial in a reasonable time frame, research progress will be relatively slow, and making a type I error may be less of a concern than a type II error. In contrast, making several type I errors in a common disease could lead in practice to patients taking several ineffective treatments; for a disease area where only one trial can run at any given time, the overall burden on patients is potentially taking one ineffective treatment that does not work.

Thus, if we take the societal perspective with the trials in Table 1 then, if each trial was analysed with α = 0.05 and we see (hypothetically) 40% positive results, then the expected number of false positive trials is given in the final column. We also assumed 10% and 70% positive results, with qualitatively similar conclusions.

---

### Improved haplotype inference by exploiting long-range linking and allelic imbalance in RNA-seq datasets [^7ff9bcd1]. Nature Communications (2020). High credibility.

Let, the opposite of H +. We can now compare the likelihood of concordant (or equal) expression at s (H + [s]) with that of discordant (or equal) expression at s (H − [s].) For ease of notation, letand. Then:The rightmost equality results from the fact that, and hence v i = w 1− i. Since ϵ < 0.5, we have γ 0 > γ 1; by the definition of H +, which proves the inequality.

Having shown that the solution of maximal likelihood under mild conditions is, intuitively, that which has concordant expression at each SNP locus s, we now measure the probability of concordant expression at that SNP, and only phase when that probability is sufficiently high, in order to determine which SNPs can be phased with high accuracy. This probability of concordant expression can be immediately derived from Eq. (14). We assume a uniform error rate of ϵ for ease of notation, though is not required. Let CE(R g, s, H [s]) denote the event of concordant expression at s, thenFurthermore, given N reads, an expression bias β, and a constant error rate ϵ, we compute likelihood of concordant expression using the standard binomial distribution B (N, γ 0) by equating successes in the binomial model to observations of the majority allele, expressed with bias γ 0 (recall γ i takes errors into account):To obtain the bound on the right hand side, apply the Chernoff bound, where X corresponds to the number of successes and μ = E[X] = N β. This bound shows that the probability of concordant expression increases exponentially with the coverage (N).

We remark for large N, the Binomial Distribution B(n, β) converges to the normal distribution, and therefore this probability can always be easily computed.

---

### Evidence that DNA polymerase δ contributes to initiating leading strand DNA replication in Saccharomyces cerevisiae [^ae44d269]. Nature Communications (2018). Medium credibility.

Alignment and normalization

HydEn-seq samples were processed as in ref. Adapter sequence was trimmed from paired-end reads using cutadapt 1.12, discarding pairs where one or both mates were shorter than 15 nt (-m 15, -q 10). Reads derived from oligos used in library preparation were filtered by aligning mate 1 of each pair to an index containing these sequences, and retaining only those that were not mappable (bowtie 1.2, -v2). Retained pairs were subsequently mapped to the S. cerevisiae W303 assembly, retaining only unique alignments, and trimming a single nucleotide from the 3′ end of each read to allow alignment of 100% overlapping pairs (bowtie 1.2, -m 1 -v 2–3 1-best -X1000). Mate 1 of remaining unmapped pairs was then aligned to W303, again retaining only uniquely mappable reads (bowtie 1.2, -m 1 -v 2–best). The positions of the 5′ ends of all uniquely mapped mate 1 reads, from both the paired-end and single-end alignments, were shifted upstream by 1, the implied ribonucleotide location, and bedGraph files containing per-nt counts were generated for each sample using custom scripts.

For the purpose of determining normalization factors, the reads mappable as pairs or mate 1 alone, to multiple locations, were re-aligned with bowtie 1.2 using the same parameters, but omitting -m 1, resulting in a single best alignment for each. BedGraph files were generated as above using all uniquely and non-uniquely mapped reads. From these files, counts of 5′ ends mapping to all SbfI-HF restriction sites, on both strands, were determined. Normalization factors were then calculated using the method implemented in DESeq: for each position, the geometric mean of counts for all samples was determined, as well as the ratio of each sample's count to this value. Sites where zero reads were observed in one or more samples were excluded. The median ratio among all SbfI-HF sites was selected as the normalization factor for each sample. Normalized HydEn-seq counts were subsequently calculated by means of division by these factors.

---

### Benchmarking microbiome transformations favors experimental quantitative approaches to address compositionality and sampling depth biases [^8bc9a56b]. Nature Communications (2021). High credibility.

While metagenomic sequencing has become the tool of preference to study host-associated microbial communities, downstream analyses and clinical interpretation of microbiome data remains challenging due to the sparsity and compositionality of sequence matrices. Here, we evaluate both computational and experimental approaches proposed to mitigate the impact of these outstanding issues. Generating fecal metagenomes drawn from simulated microbial communities, we benchmark the performance of thirteen commonly used analytical approaches in terms of diversity estimation, identification of taxon-taxon associations, and assessment of taxon-metadata correlations under the challenge of varying microbial ecosystem loads. We find quantitative approaches including experimental procedures to incorporate microbial load variation in downstream analyses to perform significantly better than computational strategies designed to mitigate data compositionality and sparsity, not only improving the identification of true positive associations, but also reducing false positive detection. When analyzing simulated scenarios of low microbial load dysbiosis as observed in inflammatory pathologies, quantitative methods correcting for sampling depth show higher precision compared to uncorrected scaling. Overall, our findings advocate for a wider adoption of experimental quantitative approaches in microbiome research, yet also suggest preferred transformations for specific cases where determination of microbial load of samples is not feasible.

---

### Advocating for life support training of children, parents, caregivers, school personnel, and the public [^452b8497]. Pediatrics (2018). Medium credibility.

2010 AHA guidelines for CPR sequence and technique in children — In 2010, the AHA changed the sequence to compressions, airway, breathing/ventilation, with 30 chest compressions followed by 2 breaths for adults with either 1 or 2 rescuers, a ratio of 30:2 for children with 1 rescuer, and a ratio of 15:2 for children with 2 rescuers; the change addressed delays because the previous sequence had delayed the initiation of crucial chest compressions. In infants and children, the new sequence only delays the first breath by 18 seconds. A Japanese study showed traditional CPR (compressions followed by breathing) increased odds of a favorable neurologic outcome in children 1 month after an OHCA (adjusted OR, 2.30 vs 1.05) compared with chest compression–only CPR; therefore, although the AHA still recommends traditional CPR for children, if rescuers cannot provide rescue breaths, they should at least perform chest compressions.

---

### Relative bioavailability of two formulations of venlafaxine extended-release 75-mg capsules in healthy Brazilian male volunteers: a single-dose, randomized-sequence, open-label, two-period crossover study in the fasting and fed States [^9261338a]. Clinical Therapeutics (2010). Low credibility.

Background

The oral antidepressant venlafaxine hydrochloride is a selective serotonin-norepinephrine reuptake inhibitor.

Objective

The aim of this study was to evaluate the bioequivalence of a new generic formulation of venlafaxine extended-release 75-mg capsules (test) and the available branded formulation (reference) to comply with regulatory criteria for marketing of the test product in Brazil.

Methods

This single-dose, randomized-sequence, open-label, 2-period crossover study was conducted in healthy male volunteers and consisted of separate fast- ing and fed phases. A single oral dose of the test or reference formulation was followed by a 7-day washout period, after which subjects received the alternative formulation. There was a 3-month interval between the fasting and fed portions of the study. There was no standardization of race because of the difficulty of achieving standardization in the Brazilian population. Blood samples were collected before dosing and at 0.5, 1, 1.5, 2, 2.5, 3, 3.5, 4, 5, 6, 8, 10, 12, 24, 36, and 48 hours after dosing. Venlafaxine concentrations were determined using an HPLC-MS/MS method. The formulations were considered bioequivalent if the 90% CIs of the geometric mean ratios (test:reference) for C(max) and AUC(0-t) were within the regulatory range of 80% to 125%. Adverse events were monitored through-out the study based on vital signs, laboratory tests, interviews, and spontaneous patient reports.

Results

Forty-eight subjects were enrolled in both phases of the study; all 48 subjects completed the fasting phase, and 1 subject withdrew during the fed phase. The mean (SD) age of participants in the fasting and fed phases was 24.96 (5.5) and 24.90 (4.7) years, respectively; their mean weight was 69.65 (9.6) and 71.00 (10.6) kg and their mean height was 172.0 (6.9) and 173.0 (6.6) cm. Under fasting conditions, the arithmetic mean venlafaxine C(max) was 35.705 (23.946) ng/mL for the test formulation and 34.470 (20.639) ng/mL for the reference formulation, with a geometric mean ratio of 1.04. The arithmetic mean AUC(0-t) for the respective formulations was 562.015 (481.875) and 508.509 (439.456) ng · h/mL, with a geometric mean ratio of 1.11. The arithmetic mean T(max) was 6.188 (1.560) and 5.885 (1.648) hours. Under fed conditions, the arithmetic mean venlafaxine C(max) was 42.892 (24.348) ng/mL for the test formulation and 46.275 (23.011) ng/mL for the reference formulation, with a geometric mean ratio of 0.93. The arithmetic mean AUC(0-t) for the respective formulations was 737.218 (603.998) and 682.124 (524.713) ng · h/mL, with a geometric mean ratio of 1.08. The arithmetic mean T(max) was 6.787 (1.769) and 5.957 (1.661) hours. There were no significant increases in venlafaxine C(max), AUC(0-t), or T(max) for either formulation in the fed phase compared with the fasting phase. In both the fasting and fed portions of the study, the 90% CIs for the ratio (test:reference) of log-transformed C(max) (fasting: 93.24–105.93; fed: 84.67–97.85) and AUC(0-t) (fasting: 102.90–116.71; fed: 98.19–114.41) were within the acceptance range for bioequivalence. The most common adverse events (≥ 5% of subjects) in the fasting phase were nausea (46%), diarrhea (29%), headache (29%), vomiting (15%), and colic (6%); the most common adverse events in the fed phase were nausea (15%), headache (13%), and dizziness (9%).

Conclusion

In this single-dose study in healthy fasting and fed volunteers, the test formulation of venlafaxine extended-release 75-mg capsules met Brazilian regulatory criteria for bioequivalence to the reference formulation.

---

### Prevention of pneumococcal disease among infants and children-use of 13-valent pneumococcal conjugate vaccine and 23-valent pneumococcal polysaccharide vaccine-recommendations of the advisory committee on immunization practices (ACIP) [^30523006]. MMWR: Recommendations and Reports (2010). Medium credibility.

Pneumococcal conjugate vaccines (PCV13 vs PCV7) — post-booster immunogenicity shows geometric mean concentrations (μg/mL) 1 month after the fourth dose with GMC ratios (PCV13/PCV7); for serotype 23F, PCV13 5.1 vs PCV7 7.8 with GMC ratio 0.7 (0.5–0.8), and for serotype 19F, PCV13 6.6 vs PCV7 5.6 with GMC ratio 1.2 (1.0–1.4); noninferiority was defined as a lower limit of the 2-sided 95% CI for the GMC ratio (PCV13 group/PCV7 group) > 0.5.

---

### Opportunities and challenges associated with clinical diagnostic genome sequencing: a report of the Association for Molecular Pathology [^ac422a46]. The Journal of Molecular Diagnostics (2012). Medium credibility.

Clinical diagnostic genome sequencing — base-calling quality scoring uses a Phred score generated on a logarithmic scale (Q = − 10 log E) to estimate error probability, where a Phred of 10 corresponds to a 1/10 probability of error and a Phred of 20 corresponds to 1/100. For sequencing information, the Clinical Laboratory Standards Institute has recommended filtering on a Phred score of 20 to 30, resulting in an error rate of 1/100 to 1/1000, and when interrogating variants in population-level situations such as microbes or tumor samples, higher thresholds may be necessary.

---

### Quantitative imaging metrics for the assessment of pulmonary pathophysiology: an official American Thoracic Society and Fleischner society joint workshop report [^d6563994]. Annals of the American Thoracic Society (2023). High credibility.

Quantitative imaging (QI) — challenges and sources of error emphasize that advances in QI are crucially dependent on technology and computational power, with massive data sets run through "black box" algorithms and distilled into selected "biomarkers" to evaluate their ability to detect, stratify, and monitor lung disease. Numerous imaging modalities, manufacturers, platforms, and algorithms may not integrate smoothly, and emergent QI metrics vary among centers in the methods of acquisition, quantification, interpretation, and extrapolation; technological advances contribute to difficulty in standardization. Systematic errors may arise at each step of image acquisition, processing, and analysis, including 1) technical issues (e.g., depth of inspiration, acquisition protocol, signal-to-noise ratio, resolution), 2) nonrepresentative sampling of parts of interest (e.g., comparing regions, lobes, or airways), and 3) lack of a well-defined reference space, as well as 4) inaccurate landmark coregistration for evaluating paired images obtained at different lung volumes and 5) failure to consider basic physiology and/or biological or spatiotemporal heterogeneity.

---

### An empirical study of the maximum degree of undersampling in compressed sensing for T-weighted MRI [^95dd53df]. Magnetic Resonance Imaging (2018). Low credibility.

Magnetic Resonance Imaging (MRI) is one of the most dynamic and safe imaging modalities used in clinical routine today. Yet, one major limitation to this technique resides in its long acquisition times. Over the last decade, Compressed Sensing (CS) has been increasingly used to address this issue and offers to shorten MR scans by reconstructing images from undersampled Fourier data. Nevertheless, a quantitative guide on the degree of acceleration applicable to a given acquisition scenario is still lacking today, leading in practice to a trial-and-error approach in the selection of the appropriate undersampling factor. In this study, we shortly point out the existing theoretical sampling results in CS and their limitations which motivate the focus of this work: an empirical and quantitative analysis of the maximum degree of undersampling allowed by CS in the specific context of T 2 * -weighted MRI. We make use of a generic method based on retrospective undersampling to quantitatively deduce the maximum acceleration factor R max which preserves a desired image quality as a function of the image resolution and the available signal-to-noise ratio (SNR). Our results quantify how larger acceleration factors can be applied to higher resolution images as long as a minimum SNR is guaranteed. In practice however, the maximum acceleration factor for a given resolution appears to be constrained by the available SNR inherent to the considered acquisition. Our analysis enables to take this a priori knowledge into account, allowing to derive a sequence-specific maximum acceleration factor adapted to the intrinsic SNR of any MR pipeline. These results obtained on an analytical T 2 * -weighted phantom image were corroborated by prospective experiments performed on MR data collected with radial trajectories on a 7 T scanner with the same contrast. The proposed framework allows to study other sequence weightings and therefore better optimize sequences when accelerated using CS.

---

### Accurate assessment of mass, models and resolution by small-angle scattering [^6c6d4167]. Nature (2013). Excellent credibility.

Modern small-angle scattering (SAS) experiments with X-rays or neutrons provide a comprehensive, resolution-limited observation of the thermodynamic state. However, methods for evaluating mass and validating SAS-based models and resolution have been inadequate. Here we define the volume of correlation, Vc, a SAS invariant derived from the scattered intensities that is specific to the structural state of the particle, but independent of concentration and the requirements of a compact, folded particle. We show that Vc defines a ratio, QR, that determines the molecular mass of proteins or RNA ranging from 10 to 1,000 kilodaltons. Furthermore, we propose a statistically robust method for assessing model-data agreements (χ(2)free) akin to cross-validation. Our approach prevents over-fitting of the SAS data and can be used with a newly defined metric, RSAS, for quantitative evaluation of resolution. Together, these metrics (Vc, QR, χ(2)free and RSAS) provide analytical tools for unbiased and accurate macromolecular structural characterizations in solution.

---

### Structure and inference in annotated networks [^535f823a]. Nature Communications (2016). Medium credibility.

Computationally, the most demanding part of the EM algorithm is calculating the sum in the denominator of equation (7), which has an exponentially large number of terms, making its direct evaluation intractable on all but the smallest of networks. Traditionally one gets around this problem by approximating the full distribution q (s) by Monte Carlo importance sampling. In our calculations, however, we instead use a recently proposed alternative method based on belief propagation, which is significantly faster, and fast enough in practice for applications to very large networks.

Final likelihood value

The EM algorithm always converges to a maximum of the likelihood but is not guaranteed to converge to the global maximum — it is possible for there to be one or more local maxima as well. To get around this problem we normally run the algorithm repeatedly with different random initial guesses for the parameters and from the results choose the one that finds the highest likelihood value. In the calculations presented in this paper we did at least 10 such 'random restarts' for each network. To determine which run has the highest final value of the likelihood we calculate the log-likelihood from the right-hand side of (6) using P (A | Θ, s) and P (s | Γ, x) as in equation (2), the final fitted values of the parameters Θ and Γ from the EM algorithm, and q (s) as in equation (7). (As we have said, the right-hand side of (6) becomes equal to the left, and hence equal to the true log-likelihood, when q (s) is given the value in equation (7).)

---

### Correcting for sequencing error in maximum likelihood phylogeny inference [^ce9f3999]. G3 (2014). Low credibility.

Accurate phylogenies are critical to taxonomy as well as studies of speciation processes and other evolutionary patterns. Accurate branch lengths in phylogenies are critical for dating and rate measurements. Such accuracy may be jeopardized by unacknowledged sequencing error. We use simulated data to test a correction for DNA sequencing error in maximum likelihood phylogeny inference. Over a wide range of data polymorphism and true error rate, we found that correcting for sequencing error improves recovery of the branch lengths, even if the assumed error rate is up to twice the true error rate. Low error rates have little effect on recovery of the topology. When error is high, correction improves topological inference; however, when error is extremely high, using an assumed error rate greater than the true error rate leads to poor recovery of both topology and branch lengths. The error correction approach tested here was proposed in 2004 but has not been widely used, perhaps because researchers do not want to commit to an estimate of the error rate. This study shows that correction with an approximate error rate is generally preferable to ignoring the issue.

---

### On the mutational topology of the bacterial genome [^96a62de9]. G3 (2013). Low credibility.

Figure 2
The distribution of the gaps between BPSs. Shown are the four quartiles of a quantile-quantile (Q-Q) plot of the observed sizes of the intervals (gaps) between BPSs vs. the sizes predicted by an exponential distribution. For this analysis, gaps that contained large repeat elements have been removed (see Materials and Methods); this procedure left 1581 BPSs distributed over 4284 kb of the chromosome, giving a mean gap size of 2.71 kb. The observed distribution is significantly different than expected (χ 2 ≈10 4; p ≪ 0.0001).

A more interesting departure from random is revealed by the locations of the mutations. In Figure 3A the 1625 BPSs are collected in 46 bins, each bin approximately 100 kb wide, starting at the origin of replication. The left and right sides of Figure 3A display the same data collected in opposite directions, reproducing the movement of the two replication forks as they traverse the chromosome, but arranged as if each fork continued around the chromosome and back to the origin (i.e. the lower left quadrant is the inverted mirror image of the upper right quadrant, and vice versa); the color changes from blue to magenta at the midpoint of the chromosome. Figure 3A reveals that the mutations are distributed across the genome in a large-scale, periodic pattern that is repeated nearly in mirror-image in the two replichores. The distributions of the mutations per bin between the two replichores are highly correlated (Pearson's correlation coefficient, ρ p, = 0.701, p = 0.0002) (Figure 3B); thus, the pattern appears to reflect genomic features that affect the fidelity of the two replisomes in parallel as they move from the origin to the terminus. Starting from OriC (the top of Figure 3A) the density of mutations in each replichore drops for about 500 kb (bins 2−6, 45−42), then increases, reaching a peak at about 1000 kb from OriC (bins 10 and 37). The density then drops to another low at about 1400 kb from OriC (bins 13−15, 34−32) before climbing to a second peak at about 2100 kb from OriC (bins 20, 25), which is immediately before the terminus region. The density of mutations drops again at the point where each fork would pass the strong termination sites TerD and TerA (located in bins 20 and 21, respectively) for the clockwise-moving fork and TerB and TerC (both located in bin 24) for the counter-clockwise moving fork. Within the inner termination region (bins 21−24) the mutation density is relatively constant and close to the average across the whole genome.

---

### Selecting fitted models under epistemic uncertainty using a stochastic process on quantile functions [^aeeaae45]. Nature Communications (2025). High credibility.

Fitting models to data is an important part of the practice of science. Advances in machine learning have made it possible to fit more-and more complex-models, but have also exacerbated a problem: when multiple models fit the data equally well, which one(s) should we pick? The answer depends entirely on the modelling goal. In the scientific context, the essential goal is replicability: if a model works well to describe one experiment, it should continue to do so when that experiment is replicated tomorrow, or in another laboratory. The selection criterion must therefore be robust to the variations inherent to the replication process. In this work we develop a nonparametric method for estimating uncertainty on a model's empirical risk when replications are non-stationary, thus ensuring that a model is only rejected when another is reproducibly better. We illustrate the method with two examples: one a more classical setting, where the models are structurally distinct, and a machine learning-inspired setting, where they differ only in the value of their parameters. We show how, in this context of replicability or "epistemic uncertainty", it compares favourably to existing model selection criteria, and has more satisfactory behaviour with large experimental datasets.

---

### A probable-acting genetic modifier of Huntington disease frequent in individuals with African ancestry [^da540007]. HGG Advances (2022). Medium credibility.

CAG somatic expansion

The modifiers of the ratio of somatic CAG expansion of disease-associated alleles were assessed through the inclusion of the following explanatory variables; inherited expanded CAG repeat length, the age at sampling, and their interaction (Table S3 Model 1). The inherited expanded CAG repeat length and the age at sampling were shown to have a highly significant association with the ratio of somatic CAG expansions of the disease-associated allele observed in blood DNA (p < 2 × 10 −16). A larger effect was observed for the inherited expanded CAG repeat length with every additional CAG repeat resulting in an increase of 0.131 (p = 8 × 10 −16) in the ratio of somatic expansions; while every year delay in the age at sampling increased the ratio of somatic expansion by 0.008 (p = 1.8 × 10 −3). In line with previous studies, the inherited CAG repeat length was shown to be the primary driver of the ratio of somatic expansion.

Moreover, a highly significant association (p < 2 × 10 −16) was identified between allele structures and the ratio of somatic expansion (Figure S2; Table S3, Model 2). In addition to the CAG repeat, the disease allele structures, Q 1 -0-0-9-2 (p = 7.7 × 10 −4), Q 1 -2-0-9-2 (p = 1 × 10 −5), and Q 1 -2-2-6-3 (p = 0.014) were each shown to have a significant association with the ratio of somatic expansion. Individuals with these disease allele structures had a mean decrease in somatic expansion by 0.26, 0.17, and 0.15, respectively. Thus, individuals with the typical allele structure (Q 1 -2-2-P 2–2) had a significantly higher ratio of somatic expansion overall, while individuals with disease alleles characterized by the loss of CCGCCA sequence had the lowest ratio of somatic expansion.

Potential modifiers of the HD phenotype

---

### Opportunities and challenges associated with clinical diagnostic genome sequencing: a report of the Association for Molecular Pathology [^e8738f75]. The Journal of Molecular Diagnostics (2012). Medium credibility.

Clinical diagnostic genome sequencing — platform-specific error profiles and data representations require algorithmic handling: platforms may have insertion or deletion errors during homopolymer runs or increased sequence errors toward the end of the read; representations can be in color space (AA, AC, CC, GG, or TT) versus base space (A, C, G, T), and these differences must be addressed at the algorithmic level because some sequence errors are correctable.

---

### Probabilistic alignment of multiple networks [^39aa70ac]. Nature Communications (2025). High credibility.

The network alignment problem appears in many areas of science and involves finding the optimal mapping between nodes in two or more networks, so as to identify corresponding entities across networks. We propose a probabilistic approach to the problem of network alignment, as well as the corresponding inference algorithms. Unlike heuristic approaches, our approach is transparent in that all model assumptions are explicit; therefore, it is susceptible of being extended and fine tuned by incorporating contextual information that is relevant to a given alignment problem. Also in contrast to current approaches, our method does not yield a single alignment, but rather the whole posterior distribution over alignments. We show that using the whole posterior leads to correct matching of nodes, even in situations where the single most plausible alignment mismatches them. Our approach opens the door to a whole new family of network alignment algorithms, and to their application to problems for which existing methods are perhaps inappropriate.

---

### Opportunities and challenges associated with clinical diagnostic genome sequencing: a report of the Association for Molecular Pathology [^05d2857b]. The Journal of Molecular Diagnostics (2012). Medium credibility.

Analytical NGS considerations — regulation and validation note that before any new laboratory-developed test is used for patient care, a clinical laboratory undertakes analytical validation, but Food and Drug Administration–approved/cleared tests using next-generation sequencing (NGS) do not exist, so laboratories will for the foreseeable future rely on Clinical Laboratory Improvement Amendment regulations. The purpose of assay validation for a laboratory-developed test is to document that the targeted analyte(s) can be detected in a robust and consistent manner, and in accordance with Clinical Laboratory Improvement Amendment regulations the following analytical characteristics must be documented: accuracy, precision, analytical sensitivity, analytical specificity, reportable range, reference intervals, and any other required performance characteristic. Sequences from NGS are not truly complete because of gaps, GC-rich regions, and bioinformatic limitations regarding indel calling. For nucleic acid sequencing, the standard comparator is traditional Sanger sequencing whose technical capabilities are dwarfed by NGS, and it is practically not feasible to perform Sanger sequencing of whole genomes for reasons of reagent costs, labor, and efficiency of both testing and analysis. All steps of NGS need to be evaluated, including sample library preparation, clonal fragment amplification, the sequencing itself, and data analysis, and quality control metrics need to be determined. Open questions include whether sequencing and documenting representative portions or comparison to online reference sequences would suffice, and what reference materials (RMs) are needed to make validation efficient and meaningful.

---

### Fast and accurate modeling of transient-state, gradient-spoiled sequences by recurrent neural networks [^de525b7e]. NMR in Biomedicine (2021). Medium credibility.

3.2.1 Network structure specification

The RNN architecture described in Section 2.2 was selected for modeling gradient‐spoiled sequence responses. Specifically, at the n ‐th time step, the inputs of the network were tissue parameters in logarithmic scale θ = (log T 1, log T 2) T and time‐dependent sequence parameters β = (T R (n), T E (n), α (n)) T, and the outputs were (M xy (n), ∂M xy (n)/ ∂ θ) T, that is, both the magnetization and derivatives. At the first time step (n = 0), the input for the initial linear layer was the initial magnetization vector M 0 = (M x (0), M y (0), M z (0)) T. Each layer of the GRUs had 32 hidden states, and the whole network has in total 16,643 trainable parameters.

---

### Electron flow matching for generative reaction mechanism prediction [^3ecd344b]. Nature (2025). Excellent credibility.

Central to our understanding of chemical reactivity is the principle of mass conservation 1, which is fundamental for ensuring physical consistency, balancing equations and guiding reaction design. However, data-driven computational models 2–9 for tasks such as reaction product prediction rarely abide by this most basic constraint 10–13. Here we recast the problem of reaction prediction as a problem of electron redistribution using the modern deep generative framework of flow matching 14–16, explicitly conserving both mass and electrons through the bond-electron (BE) matrix representation 17,18. Our model, FlowER, overcomes limitations inherent in previous approaches by enforcing exact mass conservation, resolving hallucinatory failure modes, recovering mechanistic reaction sequences for unseen substrate scaffolds and generalizing effectively to out-of-domain reaction classes with extremely data-efficient fine-tuning. FlowER also enables downstream estimation of thermodynamic or kinetic feasibility and manifests a degree of chemical intuition in reaction prediction tasks. This inherently interpretable framework represents an important step in bridging the gap between predictive accuracy and mechanistic understanding in data-driven reaction outcome prediction.

---

### The SNMMI and EANM practice guideline for small-bowel and colon transit 1.0 [^ea6f1e8b]. Journal of Nuclear Medicine (2013). Medium credibility.

Colon transit reference values — delayed-release capsule method in healthy volunteers — include total number of healthy volunteers 211. The geometric center at 24 h is 2.4 ± 0.9 (n = 209) with 10th–90th percentile 1.47–3.87, with men 2.7 ± 0.9 (n = 72) and women 2.3 ± 0.9 (n = 137). At 48 h, the geometric center is 3.6 ± 1.1 (n = 191) with 10th–90th percentile 2.13–5.00, with men 4.1 ± 1.0 (n = 61) and women 3.4 ± 1.0 (n = 130).

---

### Nivolumab and hyaluronidase-nvhy (Opdivo QVANTIG) [^3586a553]. FDA (2025). Medium credibility.

12.3	Pharmacokinetics

When comparing nivolumab exposures following OPDIVO QVANTIG to those of intravenous nivolumab in CHECKMATE-67T [see Clinical Studies (14.1)], the geometric mean ratios (GMRs) (90% CI) for time-averaged concentration (Cavg) over 28 days and at steady state were 2.10 (2.00, 2.20) and 1.98 (1.87, 2.11), respectively, and for minimum concentration (Cmin) at 28 days and at steady state were 1.60 (1.49, 1.72) and 1.77 (1.63, 1.93), respectively.

Steady state was achieved by 16 weeks. The systemic accumulation ratio was 2.3.

Absorption

The geometric mean bioavailability (CV%) of nivolumab is 74% (14%). Peak concentrations occurred by around 6 days.

Distribution

The geometric mean (CV%) volume of distribution at steady state is 6.8 L (27%).

Elimination

Nivolumab clearance decreases over time, with a mean maximal reduction (CV%) from baseline values of 24.5% (47.6%), resulting in a geometric mean steady-state clearance (CV%) of 8.2 mL/h (53.9%) in patients with metastatic tumors; this decrease in clearance is not considered clinically relevant. Nivolumab clearance does not decrease over time in patients with completely resected melanoma, as the geometric mean population clearance is 24% lower in this patient population compared with patients with metastatic melanoma at steady state.

The geometric mean (CV%) elimination half-life is 25 days (78%).

Specific Populations

Body weight (35 to 153 kg), sex, eGFR (24 to 124 mL/min/1.73 m2), and performance status have no clinically significant effects on the clearance of nivolumab.

---

### Assessing pharmacokinetic interactions between the sodium glucose cotransporter 2 inhibitor empagliflozin and hydrochlorothiazide or torasemide in patients with type 2 diabetes mellitus: a randomized, open-label, crossover study [^01314d25]. Clinical Therapeutics (2015). Low credibility.

Purpose

Empagliflozin is a potent, selective sodium glucose cotransporter 2 inhibitor approved for the treatment of type 2 diabetes mellitus. Thiazide or loop diuretics are commonly prescribed in patients with type 2 diabetes mellitus. This study investigated potential pharmacokinetic drug-drug interactions between empagliflozin and hydrochlorothiazide (HCTZ) or torasemide (TOR).

Methods

This was an open-label, crossover study. Patients with type 2 diabetes mellitus were randomized to receive empagliflozin 25 mg once daily for 5 days and either HCTZ 25 mg once daily for 4 days followed by HCTZ 25 mg once daily plus empagliflozin 25 mg once daily for 5 days or TOR 5 mg once daily for 4 days followed by TOR 5 mg once daily plus empagliflozin once daily for 5 days in 1 of 4 sequences, with at least a 7-day washout period between treatments. Pharmacokinetic parameters of empagliflozin, HCTZ, and TOR were assessed and standard bioequivalence criteria (80%-125%) were applied. Tolerability assessments included the frequency of adverse events and an investigator assessment of global tolerability.

Findings

Mean (SD) age of the 22 patients treated was 54.0 (8.1) years and body mass index was 27.1 (3.7) kg/m(2). Coadministration of empagliflozin with HCTZ or TOR had no effect on exposure to empagliflozin, HCTZ, or TOR. Geometric mean ratios (90% CIs) for empagliflozin AUC over a uniform dosing interval and Cmax at steady state were 107.1% (90% CI, 97.1–118.1) and 102.8% (90% CI, 88.6–119.3), respectively, when coadministered with HCTZ versus administration alone, and 107.8% (90% CI, 100.1–116.1) and 107.5% (90% CI, 97.9–118.0), respectively, when coadministered with TOR versus administration alone. For HCTZ, the geometric mean ratios for AUC over a uniform dosing interval and Cmax at steady state were 96.3% (90% CI, 89.1–104.0) and 101.8% (90% CI, 88.6–116.9), respectively, and for TOR were 101.4% (90% CI, 99.1–103.9) and 104.4% (90% CI, 93.8–116.3), respectively, for combined treatment versus administration alone. The pharmacokinetic profiles of empagliflozin, HCTZ, and TOR were similar after administration alone and in combination. Global tolerability was good for all patients after each treatment, and no severe or serious adverse events were reported.

Implications

No pharmacokinetic drug-drug interaction was observed between empagliflozin and HCTZ or TOR. ClinicalTrials.gov identifier: NCT01276288.

---

### Computational precision of mental inference as critical source of human choice suboptimality [^56c5b7cd]. Neuron (2016). Low credibility.

Making decisions in uncertain environments often requires combining multiple pieces of ambiguous information from external cues. In such conditions, human choices resemble optimal Bayesian inference, but typically show a large suboptimal variability whose origin remains poorly understood. In particular, this choice suboptimality might arise from imperfections in mental inference rather than in peripheral stages, such as sensory processing and response selection. Here, we dissociate these three sources of suboptimality in human choices based on combining multiple ambiguous cues. Using a novel quantitative approach for identifying the origin and structure of choice variability, we show that imperfections in inference alone cause a dominant fraction of suboptimal choices. Furthermore, two-thirds of this suboptimality appear to derive from the limited precision of neural computations implementing inference rather than from systematic deviations from Bayes-optimal inference. These findings set an upper bound on the accuracy and ultimate predictability of human choices in uncertain environments.

---

### Kinship networks of seed exchange shape spatial patterns of plant virus diversity [^1e9934a7]. Nature Communications (2021). High credibility.

Phylogenetic and clustering analysis

FastTree 2.1.9was used to build a maximum-likelihood (ML) tree from the 2006–2007 and 2014–2015 datasets combined under the GTR + CAT model. Branch support was estimated using nonparametric approximate likelihood-ratio tests (aLRT SH-like). TempEst 1.5was used to test for the presence of a temporal signal in the molecular phylogeny by performing regression analyses of genetic divergence between viral sequences against sampling dates.

To evaluate the diversity of viral communities, Cluster Picker 1.3was used to measure the dispersion of haplotypes across the tree and identify clusters of viral sequences that share a common evolutionary history ("phylotypes", subsequently treated as operational taxonomic units [OTUs] in diversity analyses). Clusters were assigned with branch support (aLRT) > 70% and maximum pairwise genetic distance between taxa ≤ 4.5% to minimize the number of singletons, i.e. DNA sequences not assigned to any cluster. Viral diversity was then evaluated using three measures of Hill numbers q D with q = 0 (species richness), q = 1 (exponential of Shannon index) and q = 2 (inverse Simpson index). Sample-size- and coverage-based rarefaction and extrapolation curveswere generated using the R package iNEXT. Extrapolated data was calculated up to a base sample double the size of the smallest reference sample and 95% confidence intervals were derived from 100 bootstrap replicates.

---

### Changes in semantic memory structure support successful problem-solving and analogical transfer [^5231072f]. Communications Psychology (2024). Medium credibility.

Introduction

In our daily life, we constantly deal with problems, ranging from the most mundane (e.g. what to cook for dinner given the ingredients at our disposal), to professional activities (e.g. how to reorganize our current plans to meet a new deadline), up to major societal challenges (e.g. how to find innovative solutions against global warming). How do we find new solutions to problems? While the ability to solve problems is a critical skill for adapting to new situations and innovating, the mechanisms underlying the problem-solving process remain largely unknown.

Among the new problems we face each day, some are well-defined (e.g. playing a jigsaw puzzle). The initial state (i.e. the number of independent pieces) and goal state (i.e. assembling the pieces so it looks like the picture model) are clear, and the solver can apply a set of operations (i.e. interlocking the pieces as a function of their shape) to reach the goal. However, for many of our problems (e.g. organizing work activities during the COVID-19 pandemic), the problem space is ambiguous. No heuristics or existing rules could be applied to transform the initial state into the goal state. Such "ill-defined" problemsthus require additional mental processes, which have been tightly linked to creative thinking –. Ill-defined problem-solving (or creative problem-solving) is often referred to as insight solving, where the solution comes to mind suddenly and effortlessly, with a "Eureka" phenomenon –. According to the Representational Change Theory, solving such problems involves restructuring the initial problem mental representational space, which presumably entails combining elements related to the problem in a new way. In theory, restructuring allows one to change perspective, reframe the problem, or escape its implicitly imposed constraints, leading to creative associations. For instance, consider the following problem: "A man walks into a bar and asks for a glass of water. The bartender points a shotgun at the man. The man says, 'Thank you', and walks out". The problem is ill-defined because the path to finding the solution is to be discovered, and the goal state is vague. Solving this problem first requires asking the right question: in which context would a shotgun and a glass of water help somebody? Rather than relying on obvious associations (e.g. a glass of water is related to thirst), solvers must fill the missing link between the relevant elements of the problem (a shotgun induces fear, and fear can be a remedy for hiccups, as can drinking a glass of water). Hence, restructuring the initial representation of a given problem would allow one to see this link and find its solution.

---

### Dynamics of replication origin over-activation [^f204d022]. Nature Communications (2021). High credibility.

Replication timing data was processed by the sequencing facility using the DRAGEN analysis pipeline (01.003.044.02.05.01.40152). Data received from the facility was then transformed into log 2 ratio coverage tracks using the BAMscale scale method and associated operation log 2 flag. Separation of replication timing regions from very early to very late was completed using the log 2 ratio of re-replication versus G1 (percentile of total ratio-range: 0–10% for Very Early; 10–30% for Early; 30–50% for Mid-Early; 50–70% for mid-Late; 70–90% for late and 90–100% for Very Late, Fig. 6d). R-scripts which were utilized for this task are available in the BAMscale GitHub page.

R ggplot geomboxplot (3.3.3) function was used to create violin plot for the sequencing data. The box range is between the lower quartile (25 th percentile, denoted as Q 1) to upper quartile (75 th percentile, denoted as Q 3). The whisker length is defined as 1.5 * IQR (Interquartile range), where IQR is the distance between Q 3 and Q 1.

Reporting summary

Further information on research design is available in the Nature Research Reporting Summary linked to this article.

---

### Guidelines for validation of next-generation sequencing-based oncology panels: a joint consensus recommendation of the Association for Molecular Pathology and college of American pathologists [^59838d2f]. The Journal of Molecular Diagnostics (2017). Medium credibility.

Sample size metrics — tolerance intervals versus confidence intervals: Although performance is often stated in terms of confidence intervals (CI), the CI of the mean only gives an estimate of the population mean with a stated level of confidence and does not give an indication of the performance of any given sample; to estimate the distribution of the underlying population and the performance of individual samples, the tolerance intervals should be used, with the lower tolerance interval for a normally distributed population determined as x̄ ± k × s, where s is the sample standard deviation (SD) and k is a correction factor, and for two-sided 95% confidence with n = 20 the k value is 2.75, approaching the z-score as the number of samples increases.

---

### Opportunities and challenges associated with clinical diagnostic genome sequencing: a report of the Association for Molecular Pathology [^434309ee]. The Journal of Molecular Diagnostics (2012). Medium credibility.

Clinical diagnostic genome sequencing — consensus calling of heterozygous positions depends on sampling depth because each molecule is sequenced independently; the probability of detecting a second allele is dictated by the sampling probability, and if the second allele must be present in at least 20% of calls for a heterozygous consensus, the position needs to be sampled at least 18 times to be at least 99% confident of detecting both alleles.

---

### Standards and guidelines for validating next-generation sequencing bioinformatics pipelines: a joint recommendation of the Association for Molecular Pathology and the college of American pathologists [^66ddee41]. The Journal of Molecular Diagnostics (2018). Medium credibility.

Variant representation and normalization — left versus right alignment and required conversion: The guideline explains that the common VCF representation uses the left-most "(5') nucleotide base (left justification or left aligned)", whereas HGVS specifies the right-most "(3') nucleotide base position" (right justification), creating risk that automated algorithms using VCF coordinates will generate incorrect HGVS names if they do not convert left-to-right alignment. It emphasizes that "It is essential during assay optimization and subsequent validation" to ensure correct conversion, that a normalized VCF "requires that it be parsimonious and left aligned", that nonnormalized variants may yield incorrect HGVS nomenclature with a "high likelihood of misinterpretation and incorrect reporting", and that during validation "a variant normalization algorithm be incorporated" within the pipeline or annotation tools.

---

### Otoplasty: sequencing the operation for improved results [^e72499ab]. Plastic and Reconstructive Surgery (2005). Low credibility.

Learning Objectives

After studying this article, the participant should be able to: 1. Understand the anatomy and embryology of the external ear. 2. Understand the anatomic causes of the prominent ear. 3. Understand the operative maneuvers used to shape the external ear. 4. Be able to sequence the otoplasty for consistent results. 5. Understand the possible complications of the otoplasty procedure. Correction of prominent ears is a common plastic surgical procedure. Proper execution of the surgical techniques is dependent on the surgeon's understanding of the surgical procedure. This understanding is best founded on an understanding of the historical bases for the operative steps and the execution of these operative steps in a logical fashion. This article describes the concept of sequencing the operation of otoplasty to produce predictable results combining the technical contributions from many authors. The historical, embryological, and anatomic bases for the operation are also discussed. Finally, the authors' preferred techniques are presented. Sequencing the steps in the preoperative assessment, preoperative planning, patient management, operative technique, and postoperative care will produce reproducible results for the attentive surgeon. Careful attention to the details of the operation of otoplasty will avoid many postoperative problems.

---

### Testing for Hardy-Weinberg proportions: have we lost the plot? [^61bccd14]. The Journal of Heredity (2014). Low credibility.

Testing for Hardy-Weinberg proportions (HWP) is routine in almost all genetic studies of natural populations, but many researchers do not demonstrate a full understanding of the purposes of these tests or how to interpret the results. Common problems include a lack of understanding of statistical power and the difference between statistical significance and biological significance, how to interpret results of multiple tests, and how to distinguish between various factors that can cause statistically significant departures. In this perspective, which focuses on analysis of genetic data for nonmodel species, I 1) review factors that can cause departures from HWP at individual loci and linkage disequilibrium (LD) at pairs of loci; 2) discuss commonly used tests for HWP and LD, with an emphasis on multiple-testing issues; 3) show how to distinguish among possible causes of departures from HWP; and 4) outline some simple steps to follow when significant test results are found. Finally, I 5) identify some issues that merit particular attention as we move into an era in which analysis of genomics-scale datasets for nonmodel species is commonplace.

---

### Fine-scale patterns of SARS-CoV-2 spread from identical pathogen sequences [^5848a77a]. Nature (2025). Excellent credibility.

Link between mutations and generations

In this section, we derive the probability distribution of the number of mutations M A B separating the consensus genomes of two infected individuals A and B conditional on the number of transmission generations G A B separating them.

Generation time distribution

We assume that the generation time (that is, the average duration between the infection time of an infector and an infectee) follows a Gamma distribution of shape α and scale β. The time between g generations then follows a Gamma distribution of shape g × α and scale β assuming independence of successive transmission events. Let f α, β (⋅) denote the probability density function of a Gamma distribution of shape α and scale β.

Mutations events

Let M A B denote the number of mutations separating their infecting viruses. Let μ denote the mutation rate of the virus (in mutations per day). Letdenote the evolutionary time separating A and B (in days).

Assuming a Poisson process for the occurrence of mutations, we have:

Probability distribution

Let G A B denote the number of generations separating two infected individuals A and B belonging to the same transmission chain.which is the probability mass function of a negative binomial distribution of parameters:

Application to SARS-CoV-2

We compute these probabilities for SARS-CoV-2 considering a mutation rate μ = 8.98 × 10 −2 substitutions per day (32.76 substitutions per year). We assume that the generation time is Gamma distributed with a mean 5.9 days and s.d. of 4.8 days.

Performance of the RR framework

We conduct a simulation study to evaluate how our RR framework performs under different sequencing scenarios. We also compare the results obtained from a phylogeographical analysis.

---

### Abstract representations of events arise from mental errors in learning and memory [^748e9b84]. Nature Communications (2020). High credibility.

Estimating parameters and making quantitative predictions

Given an observed sequence of nodes x 1, …, x t −1, and given an inverse temperature β, our model predicts the anticipation, or expectation, of the subsequent node x t to be. In order to quantitatively describe the reactions of an individual subject, we must relate the expectations a (t) to predictions about a person's reaction timesand then calculate the model parameters that best fit the reactions of an individual subject. The simplest possible prediction is given by the linear relation, where the intercept r 0 represents a person's reaction time with zero anticipation and the slope r 1 quantifies the strength with which a person's reaction times depend on their internal expectations.

In total, our predictionscontain three parameters (β, r 0, and r 1), which must be estimated from the reaction time data for each subject. Before estimating these parameters, however, we first regress out the dependencies of each subject's reaction times on the button combinations, trial number, and recency using a mixed effects model of the form 'RT~log(Trial)*Stage+Target+Recency+(1+log(Trial)*Stage+Recency|ID)', where all variables were defined in the previous section. Then, to estimate the model parameters that best describe an individual's reactions, we minimize the RMS prediction error with respect to each subject's observed reaction times, where T is the number of trials. We note that, given a choice for the inverse temperature β, the linear parameters r 0 and r 1 can be calculated analytically using standard linear regression techniques. Thus, the problem of estimating the model parameters can be restated as a one-dimensional minimization problem; that is, minimizing RMSE with respect to the inverse temperature β. To find the global minimum, we began by calculating RMSE along 100 logarithmically spaced values for β between 10 −4 and 10. Then, starting at the minimum value of this search, we performed gradient descent until the gradient fell below an absolute value of 10 −6. For a derivation of the gradient of the RMSE with respect to the inverse temperature β, we point the reader to the Supplementary Discussion. Finally, in addition to the gradient descent procedure described above, for each subject we also manually checked the RMSE associated with the two limits β → 0 and β → ∞. The resulting model parameters are shown in Fig. 4 a, b for random walk sequences and Fig. 4 g, h for Hamiltonian walk sequences.

---

### American association for bronchology and interventional pulmonology (AABIP) evidence-based guidelines on bronchoscopic diagnosis and staging of lung cancer [^b49db923]. Journal of Bronchology & Interventional Pulmonology (2025). High credibility.

AABIP guidelines — panel A meta-analysis comparing multiple-tool versus single-tool approaches reports pooled odds ratios (OR) as follows: common effect model OR 1.77 [1.49; 2.10] and random effects model OR 1.78 [1.49; 2.14], with prediction interval [1.36; 2.34]. Heterogeneity is I² = 6.5%, τ² = 0.0057, p = 0.3815. The scale is labeled "Favours Single" to "Favours Multiple" (Odds Ratio [95% CI]).

---

### Opportunities and challenges associated with clinical diagnostic genome sequencing: a report of the Association for Molecular Pathology [^cb811e9e]. The Journal of Molecular Diagnostics (2012). Medium credibility.

Bioinformatics requirements — NGS computational workflow and outputs — are outlined: Only three major computations are performed with NGS data: i) data assembly within base calling at the level of individual reads, ii) alignment of the assembled sequence to a reference sequence, and iii) and variant calling. Considering these steps in greater detail, they can be delineated as follows: i) image processing, ii) base calling and quality scoring, iii) purity filtering, iv) quality control checks, v) alignment to a reference sequence or de novo assembly, vi) SNP-calling or application-specific steps (eg, chromatin immunoprecipitation or RNA sequencing), vii) packaging, and viii) archiving. Typically, analysis begins with a large set of tiled fluorescence or luminescence images of a flow-cell surface recorded after each iterative round of sequencing; the next step, base calling, converts images to sequence reads by localizing clusters or beads and using parameters such as intensity, background, and noise via platform-specific algorithms to generate read sequences and per-base quality scores. As a result of base calling, FASTQ files are generated and are usually platform specific and contain sequencing read data that combine both the sequence and an associated per base quality score; the sequence reads are then aligned to a known reference sequence or assembled de novo, with the appropriate alignment method depending on the sequencing platform, data type, and computational resources. Limitations and error properties are noted: one limitation of short-reads alignment and assembly is the inability to uniquely align much of a read set; error rates for individual NGS reads are higher than for Sanger sequencing, whereas overall accuracy is achieved by sequencing a given region numerous times via the massively parallel process.

---

### Telemedicine for evaluation of retinopathy of prematurity [^f990fc0e]. Pediatrics (2015). Medium credibility.

Retinopathy of prematurity telemedicine — image sequence and standard set specifies that the image sequence for a complete image set of both eyes is listed in Table 2, additional images may be acquired to encompass all 12 clock-hours of the peripheral fundus, the sequence should be identical for all visits, and failure to achieve this standard image set may trigger unnecessary repeat fundus imaging or bedside examination; the ROP-TM image sequence comprises right anterior segment, iris; right disc; right fundus, temporal; right fundus, nasal; right fundus, superior; right fundus, inferior; and corresponding left eye views (left anterior segment, iris; left disc; left fundus, temporal; left fundus, nasal; left fundus, superior; left fundus, inferior).

---

### Detection of partial deletions of the human papillomavirus 16 E6 gene in a subset of oropharyngeal and cervical cancers [^3b10aa78]. Virus Research (2025). Medium credibility.

2.3 Sequence analysis of HPV16 E6

HPV16 E6 was analyzed by Sanger sequencing at nucleotide positions 7243–7662 or 7243–7588. The sequences were amplified by PCR using the primer sets listed in Supplementary Table 1 under conditions detailed in the Supplementary Methods. PCR products were resolved on 2.5% agarose gels, excised, purified, and sequenced. Representative intact and defective HPV16 E6 sequences were deposited in GenBank under accession numbers LC857148–LC857155 (intact) and LC857156–LC857161 (defective).

2.4 Homology modeling of HPV16 E6

The structure of HPV16 E6 was retrieved from the RCSB Protein Data Bank (PDB ID:). Models were visualized with Waals software version 3.0 (Altif Laboratories, Tokyo, Japan).

2.5 Next-generation sequencing

Next-generation sequencing (NGS) of the HPV16 E6 gene was performed using the Ion AmpliSeq Custom White Glove Panel (Thermo Fisher Scientific, Tokyo, Japan). Analyses were conducted on the Ion Chef System and Ion GeneStudio S5 System (Thermo Fisher Scientific) according to the manufacturer's instructions. The complete E6 sequence was determined using seven PCR amplicons covering the following nucleotide positions: 7099–7177, 7161–7247, 7219–7287, 7283–7410, 7339–7463, 7454–7577, and 7522–7644.

2.6 Digital PCR

The ratio of intact to defective E6 sequences was measured by digital PCR using the QuantStudio Absolute Q system (Thermo Fisher Scientific). Primers and probes targeted the E6 -defective region (nucleotides 7310–7424; VIC assay) and a region common to both intact and defective forms (7136–7216; FAM assay). Primer and probe sequences are listed in Supplementary Table 1. The defective-type copy number was calculated by subtracting the VIC result from the FAM result. Each reaction (10 µL) contained 2 μL of Absolute Q Universal Master Mix, 900 nM of VIC and FAM assay primers, 250 nM of VIC and FAM assay probes, and 2 μL template DNA. Reactions were loaded into QuantStudio Absolute Q MAP16 plates and overlaid with 15 μL isolation buffer. Thermal cycling conditions were: 96 °C for 10 min, 40 cycles of 96 °C for 5 s and 60 °C for 30 s. Data were analyzed using QuantStudio Absolute Q Digital PCR Software. All samples were analyzed twice independently.

---

### SARS-CoV-2 diagnostic testing rates determine the sensitivity of genomic surveillance programs [^6e383100]. Nature Genetics (2023). High credibility.

The first step in SARS-CoV-2 genomic surveillance is testing to identify people who are infected. However, global testing rates are falling as we emerge from the acute health emergency and remain low in many low- and middle-income countries (mean = 27 tests per 100,000 people per day). We simulated COVID-19 epidemics in a prototypical low- and middle-income country to investigate how testing rates, sampling strategies and sequencing proportions jointly impact surveillance outcomes, and showed that low testing rates and spatiotemporal biases delay time to detection of new variants by weeks to months and can lead to unreliable estimates of variant prevalence, even when the proportion of samples sequenced is increased. Accordingly, investments in wider access to diagnostics to support testing rates of approximately 100 tests per 100,000 people per day could enable more timely detection of new variants and reliable estimates of variant prevalence. The performance of global SARS-CoV-2 genomic surveillance programs is fundamentally limited by access to diagnostic testing.

---

### Quantifying the local adaptive landscape of a nascent bacterial community [^2c149d31]. Nature Communications (2023). High credibility.

The two sources of noise–genetic drift and measurement noise–both arise from counting processes, so the combined noise will follow var (f t, i) ∝ 〈 f t, i 〉 (see section "Estimation of error parameters"). To account for the inherent discreteness of counting sequencing reads — especially important to accurately model deleterious genotypes that quickly drop to low frequencies — we modeled the observed counts at time t (always measured in generations) of barcode i inserted in a given gene, r t, i, as a negative binomial random variable,

Where R t is the total number of counts, and c t is the measured variance parameter. The final likelihood for the fitness, s, of a given gene knockout is obtained by numerically integrating over f 0, i ('integrated likelihood' with a flat prior) — incorporating the uncertainty in the intercept nuisance parameters into the fitness estimate and turning the problem into a one-dimensional maximum likelihood — and then combining the likelihoods of all barcodes inserted into the gene,

The point estimate of the knockout fitness, is then numerically computed as the maximum likelihood, and the standard error is approximated as the inverse, square-root observed information,

We ran biological replicates for all experiments reported here; to obtain combined genotype fitness estimates across replicates we simply multiplied the likelihoods together, repeating the maximum-likelihood procedure.

As the majority of barcoded knockouts are neutral or nearly so (s ≈ 0), we must have a method to distinguish between likely neutral and selected knockout mutations; this can be accomplished by computing a p -value under the null hypothesis s = 0. For ease of computation and generality we compute the p -value as the posterior probability that the likelihood ratio between null and alternative hypotheses is greater than 1, i.e. the probability that the data more strongly support the null hypothesis over the alternative

---

### Accurate genotyping across variant classes and lengths using variant graphs [^4b562731]. Nature Genetics (2018). Medium credibility.

Genotype estimates from short-read sequencing data are typically based on the alignment of reads to a linear reference, but reads originating from more complex variants (for example, structural variants) often align poorly, resulting in biased genotype estimates. This bias can be mitigated by first collecting a set of candidate variants across discovery methods, individuals and databases, and then realigning the reads to the variants and reference simultaneously. However, this realignment problem has proved computationally difficult. Here, we present a new method (BayesTyper) that uses exact alignment of read k-mers to a graph representation of the reference and variants to efficiently perform unbiased, probabilistic genotyping across the variation spectrum. We demonstrate that BayesTyper generally provides superior variant sensitivity and genotyping accuracy relative to existing methods when used to integrate variants across discovery approaches and individuals. Finally, we demonstrate that including a 'variation-prior' database containing already known variants significantly improves sensitivity.

---

### Considerations for severe acute respiratory syndrome coronavirus 2 genomic surveillance: a joint consensus recommendation of the Association for Molecular Pathology and association of public health laboratories [^5eff2814]. The Journal of Molecular Diagnostics (2025). High credibility.

SARS-CoV-2 genomic surveillance — sampling strategy design: Unbiased sampling is a promising approach for detecting emerging variants, but sequencing all SARS-CoV-2–positive samples is unrealistic; moreover, universal sequencing does not necessarily provide better data than a well-planned sampling strategy that selects a subset of local samples. Sampling options include considering geographic distribution, travel history, clinical presentation, demographic-specific groups, age differences, and other conditions, or using random testing with a predetermined number of samples per day, week, or month.

---

### Bayesian strategy selection identifies optimal solutions to complex problems using an example from GP prescribing [^d1a4b1f1]. NPJ Digital Medicine (2020). Medium credibility.

Another aspect to be mindful of is that Thompson sampling trades between the type-1 error rate and statistical power, implying that to achieve a greater statistical power (relative to a same sample-size equal allocation trial), it is likely to inflate the type-1 error rate. By not trying the null strategy sufficiently, the type-1 error rate may exceed the acceptable threshold. Thus it is judicious to monitor the type-1 error rate and if it exceeds the significance level, adjustments may be required in the allocation algorithm. Recent workis starting to explore adaptive sampling approaches that can control the type-1 error rate, and further work is required to develop such techniques for a Thompson sampling setting.

We did not assess intervention fidelity, that is, whether the intervention was delivered as conceived and in accordance with the materials and instructions provided to participants. Given that the aims were to measure the effectiveness of the strategies in supporting GP-patient interactions where physical activity was discussed, failure to implement the strategies in consultations was ultimately what was tested, in essence assessing the utility of each strategy.

This case study has demonstrated an efficient process providing clear results in a short period of time. Further work should develop methods to understand interactions and sequencing of various and multiple combinations of interventions. Subsequent lines of investigation should also begin to consider the question of fidelity. Given this study demonstrates a process for supporting conversations about PA between GPs and patients, an important next step is to examine the quality and content of those conversations and their impact on measured patient PA.

While the reasons for low incidence of GP patient interaction about PA are complex, these interactions occur in a relatively stable setting with a clear, well-defined outcomes. Further work on other complex problems in similarly well-defined domains, or further investigations of the GP-patient relationship in expanded settings (i.e. with greater numbers of prioritised actions, or broader participant groups) represent exciting directions for future work.

The new frontier of public health is not what behaviours need to change, but rather how to change them. This study shows how new methods can be used to test and optimise implementation of intervention in multiple settings by engaging key actors in a system and moving quickly to the best set of interventions. For PA specifically, data suggested more than 80% of adults visit their GP at least once per year. Rapid identification of appropriate strategies that increase the discussion of PA between GPs and their patients provides new potential avenues for the improvement of public health.

---

### How I read an article that uses machine learning methods [^0f2f5676]. Blood Advances (2023). Medium credibility.

Step 1: Understand the problem being addressed. The first step in reading an ML paper is to understand the problem that the authors are trying to solve and, more importantly, understand the clinical or scientific impact of solving this problem. In other words, if the aim of the study is to solve a clinical problem, how does the answer or the recommendation provided by the algorithm help physicians or researchers in their day-to-day practice, and is this solution mature enough to be implemented in clinical workflows? Major clinical problems in health care can mainly affect either patient outcomes or operations (can I make the process easier and faster for the patient and the health care system?).

Step 2: Assess the quality of the data. The quality of the data used to build the ML model is crucial for the validity of the results. Following are some questions that can be used to evaluate the data:
1 Sample size: Is the size of the training, validation, and test sets enough to build a reproducible and generalizable ML model? Is this size of the data appropriate for the chosen methods (ie, some methods are "data-hungry" and understanding which methods require larger datasets is key)? However, different algorithms require different data types (image, tabular, text, or others) and sizes, and there are no rules of thumb or formulas that can estimate the perfect data.
2 Relevance: Are the data appropriate and relevant to the problem that the model is trying to solve?
3 Accuracy: How are the data collected and annotated (human vs natural language process). How are the data transformed to make it ready for ML use, etc.
4 Consistency: Are the data consistent? Do they have any missing values and how the authors dealt with this?
5 Representativeness: The data should be representative of the population being studied.
6 Balance: The data should be balanced, with roughly equal representation of all relevant classes or groups. However, most health care data are unbalanced. It is critical to understand how the authors dealt with unbalanced data.
7 Bias: To evaluate bias in data, it is important to look at the distribution of certain characteristics, such as race, gender, or socioeconomic status, among the samples in the data set, and how the data were collected. This will help to identify any disparities or overrepresentation of certain groups, which can indicate the presence of bias in the data. It is critical to evaluate bias at this stage because if this is not addressed properly, it could produce a biased model.

---

### Effects of fecal microbiome transfer in adolescents with obesity: the gut bugs randomized controlled trial [^a8ac0754]. JAMA Network Open (2020). High credibility.

Gut Microbiome Differences Between Donors and Participants at Baseline

Profiling of the gut microbiome using metagenomic sequencing revealed differences in community composition between donors and participants at baseline. At the phylum level, we did not observe any difference in Firmicutes to Bacteroidetes ratio (median [IQR] ratio: donors, 1.90 [2.52] vs recipient, 2.16 [6.14]; P = 0.65). At the species level, we observed differences in the abundance of a number of taxa. Donors had an increased abundance of Akkermansia muciniphila (a species commonly associated with obesity protection) (q < 0.25) (Figure 2).

Figure 2.
Gut Microbiome Assessment of Donors and Participants

Boxes indicate interquartile ranges (IQR), and whiskers the range of the data (expanding up to 1.5 × IQR). Each dot indicates an individual's fecal microbiome sample, except for capsule dots, which are the combination of all 4 contributing donor microbiome samples per batch. FMT indicates fecal microbiome transfer.

Despite the difference in overall community structure, microbial diversity was similar between individual donors and participants at baseline (Figure 2). However, FMT treatment used capsules from all 4 donors at once. Analysis confirmed that the microbial profiles of the combined capsule sets were more diverse than those of the individual donor and participant samples at baseline (Figure 2).

---

### VA / DoD clinical practice guideline for the management of type 2 diabetes mellitus [^8da629fa]. VA/DoD (2023). High credibility.

Algorithm — This clinical practice guideline's algorithm is designed to facilitate understanding of the clinical pathway and decision-making process used in managing patients with T2DM. It represents a simplified flow of the management of patients with T2DM and helps foster efficient decision making by providers, and it includes steps of care in an ordered sequence, decisions to be considered, decision criteria recommended, and actions to be taken. The algorithm is a step-by-step decision tree; standardized symbols display each step, arrows connect the numbered boxes indicating the order in which the steps should be followed, and sidebars 1–8 provide more detailed information to assist in defining and interpreting elements in the boxes.

---

### American association for bronchology and interventional pulmonology (AABIP) evidence-based guidelines on bronchoscopic diagnosis and staging of lung cancer [^e5f70036]. Journal of Bronchology & Interventional Pulmonology (2025). High credibility.

AABIP guidelines — panel B meta-analysis of multiple-tool versus single-tool approaches shows common effect model OR 1.63 [1.33; 2.00] and random effects model OR 1.64 [1.33; 2.02], with prediction interval [1.20; 2.24]. Heterogeneity is I² = 0.0%, τ² = 0.0031, p = 0.6847. The axis is labeled "Favours Single" and "Favours Multiple" (Odds Ratio [95% CI]).

---

### Mitigating undersampling errors in MR fingerprinting by sequence optimization [^b078e757]. Magnetic Resonance in Medicine (2023). Medium credibility.

Purpose

To develop a method for MR Fingerprinting (MRF) sequence optimization that takes both the applied undersampling pattern and a realistic reference map into account.

Methods

A predictive model for the undersampling error leveraging on perturbation theory was exploited to optimize the MRF flip angle sequence for improved robustness against undersampling artifacts. In this framework parameter maps from a previously acquired MRF scan were used as reference. Sequences were optimized for different sequence lengths, smoothness constraints and undersampling factors. Numerical simulations and in vivo measurements in eight healthy subjects were performed to assess the effect of the performed optimization. The optimized MRF sequences were compared to a conventionally shaped flip angle pattern and an optimized pattern based on the Cramér-Rao lower bound (CRB).

Results

Numerical simulations and in vivo results demonstrate that the undersampling errors can be suppressed by flip angle optimization. Analysis of the in vivo results show that a sequence optimized for improved robustness against undersampling with a flip angle train of length 400 yielded significantly lower median absolute errors in T₁: 5.6% ± 2.9% and T₂: 7.9% ± 2.3% compared to the conventional (T₁: 8.0% ± 1.9%, T₂: 14.5% ± 2.6%) and CRB-based (T₁: 21.6% ± 4.1%, T₂: 31.4% ± 4.4%) sequences.

Conclusion

The proposed method is able to optimize the MRF flip angle pattern such that significant mitigation of the artifacts from strong k-space undersampling in MRF is achieved.

---

### The problem with plan-Do-study-act cycles [^d75cda90]. BMJ Quality & Safety (2016). Medium credibility.

Just get on with it

While 'planning paralysis' can be an issue in healthcare organisations, the more common problem is a serious underinvestment in the planning phase. The pervasive cultural compulsion to 'just get on with it'leads many teams to move too quickly from 'plan' to 'do'. The consequences of skipping this up-front work can include wasted PDSA cycles or projects that fail altogether. Table 1 describes some of the key failure modes for the planning and preplanning (ie, investigation and problem-framing) steps of the PDSA process.

Table 1
Key failure modes for the investigation/problem framing and plan steps

Why do planning failures present such a challenge to the successful use of PDSA? It is much more difficult to correctly execute and learn from a plan that has not been well thought out. And even perfect execution cannot ensure success if the plan, itself, is wrong.

The iterative nature of PDSA enables course corrections, but this feature of the approach is much more effective if there was a clear and reasoned course in the first place. Many of the barriers to success in the do, study and act phases can be predicted and mitigated through more effective planning.

---

### Temporal variability in quantitative human gut microbiome profiles and implications for clinical research [^c19b42f6]. Nature Communications (2021). High credibility.

Fig. 3
Gains in accuracy in the estimation of the equilibrium abundance are highest for the first five samples for both RMP and QMP.

The availability of multiple timepoints allows improved estimation of the equilibrium genus abundance through summary measures (e.g. median). However, gains in accuracy decrease with additional timepoints. We calculated the error on the median genus abundances (y -axis) depending on the number of timepoints (100 most abundant genera, all participants, timepoints randomly chosen out of the full time series, 10.000 iterations). The elbow of the curve, a point that signifies an optimum in the trade-off between accuracy and sampling effort, lies roughly around 5 samples for both RMP (a) and QMP (b). Gains in accuracy level off afterwards as evidenced by the flatter curves.

---

### Opportunities and challenges associated with clinical diagnostic genome sequencing: a report of the Association for Molecular Pathology [^b330d84f]. The Journal of Molecular Diagnostics (2012). Medium credibility.

Next-generation sequencing (NGS) data analysis and storage — key challenges include variable coverage, interpretation steps, somatic versus germline considerations, and data volume. Beyond sequence errors, inadequate coverage can cause failure to accurately detect nucleotide variation, leading to false-positive and false-negative results, and depending on the sequencing application, the next step may involve quantification of reads, mutation calling, copy number analysis, and/or analysis of structural variations. Today, most users align the NGS reads to a known reference using SNP databases, and in mendelian conditions, use of unaffected family members provides a useful background to identify novel disease-causing mutations, whereas the calling of somatic mutations in malignancies is much more complicated because of the variance in ploidy and purity of the tumor DNA and dependence on the allelic fraction; comparison to nontumor tissue provides an important tool, and elimination of false positives can largely be achieved through verification by conventional PCR and Sanger sequencing, although minimizing false negatives is less straightforward. With respect to data storage, typically tens or hundreds of giga bp of short reads can be generated during one NGS run and the average NGS experiment generates terabytes of raw data, yet the extent of data that need to be retained for NGS assays has not been established, the retention of the complete data is costly and, in many instances, cost prohibitive, and the use of cloud computing is proposed as a potential way to avoid obtaining expensive servers.

---

### Statistical combination schemes of repeated diagnostic test data [^5c639f39]. Academic Radiology (2006). Low credibility.

Rationale and Objectives

When diagnostic tests are repeated and combined, a number of schemes may be adopted. Guidelines for their interpretations are required.

Materials and Methods

Three combination schemes, "and" (A), "or" (O), and "majority" (M), are considered. To evaluate these schemes, dependency by specifying kappa values quantifying repeated test agreement was structured. In a pilot study, the combined accuracies of magnetic resonance imaging using six different pulse sequences of medial collateral ligaments of the elbows of 28 cadavers, with eight having lesions artificially created surgically, were examined. Images were evaluated simultaneously by using a five-point ordinal scale. For each pulse sequence, individuals for whom the diagnosis varied from once to three repetitions were considered.

Results

Scheme M improves diagnostic accuracy when sensitivity and specificity of a single test exceed 0.5, with maximal improvement at 0.79. Under scheme A, sensitivity decreases to 0.38–0.59. Under scheme O, sensitivity increases to 0.53–0.79. Scheme M yields a small improvement, reaching 0.50–0.71. Under scheme A, specificity increases to 0.95–0.98. Under scheme O, specificity decreases to 0.91–0.98. Scheme M also yields a small improvement, reaching 0.94–0.98.

Conclusion

Scheme A is recommended for ruling in diagnoses, scheme O is recommended for ruling out diagnoses, and scheme M is neutral. Consequently, different schemes may be used to optimize the target diagnostic accuracy.

---

### Probabilistic alignment of multiple networks [^5f6f5596]. Nature Communications (2025). High credibility.

Formally, we consider a blueprint L with binary edges (L i j ∈ {0, 1}) from which networks are copied with errors. Each entry A i j in an observed network is assumed to be independently generated from L i j with a copying error probability that depends on L i j. Edges in the blueprint (L i j = 1) are copied with error probability q, whereas non-edges (L i j = 0) are copied with error probability p (see Supplementary Material for the model with uniform copy error probability q = p). This approach shares some features with the approach in Ref. where the goal is to align a noisy network copy with the original network (the blueprint in our case) using a similar probabilistic framework. The crucial difference lies in that, in our case, the blueprint is unknown, so that we need to infer it. This difference is precisely what makes our approach symmetric (the alignment of two networks does not require that we choose one as reference) and what allows us to align multiple networks at the same time without the need to choose an arbitrary blueprint from the set of observed networks.

For simplicity, we consider first the case in which we have a single observation. Given L i j, q, and p, the probability that we observe an edge (A i j = 1) or a non-edge (A i j = 0) is then:

Since the probability of observing each edge is conditionally independent on the others, the total likelihood of observing an adjacency matrix A given a latent blueprint L, q, and p factorizes. Additionally, note that the likelihood depends on the unknown mapping of nodes in the observed network into nodes of the blueprint, which is given by the permutation π of the nodes in the observed network. With this, the likelihood iswhere the edge overlaps between the blueprint and the observations are. For example, o 01 is the number of entries that are 0 in L and 1 in A, for mapping π.

---

### Towards a reference genome that captures global genetic diversity [^45a4aac9]. Nature Communications (2020). High credibility.

The current human reference genome is predominantly derived from a single individual and it does not adequately reflect human genetic diversity. Here, we analyze 338 high-quality human assemblies of genetically divergent human populations to identify missing sequences in the human reference genome with breakpoint resolution. We identify 127,727 recurrent non-reference unique insertions spanning 18,048,877bp, some of which disrupt exons and known regulatory elements. To improve genome annotations, we linearly integrate these sequences into the chromosomal assemblies and construct a Human Diversity Reference. Leveraging this reference, an average of 402,573 previously unmapped reads can be recovered for a given genome sequenced to ~40X coverage. Transcriptomic diversity among these non-reference sequences can also be directly assessed. We successfully map tens of thousands of previously discarded RNA-Seq reads to this reference and identify transcription evidence in 4781 gene loci, underlining the importance of these non-reference sequences in functional genomics. Our extensive datasets are important advances toward a comprehensive reference representation of global human genetic diversity.

---

### Clonal evolution in waldenstrom macroglobulinemia highlights functional role of B-cell receptor [^f54fbb23]. Blood (2001). Low credibility.

The course of clonal evolution of 2 related clones in the blood of a patient with Waldenstrom macroglobulinemia (WM) indicates the functional importance for the expression of the B-cell receptor for the survival of these malignant cells. Protein and nucleotide sequencing of the paraproteins' variable regions revealed 2 predominant Vlambda and 2 VH sequences, each set comprised in the ratio 1:1.5. The 2 VH sequences and 2 Vlambda sequences shared the same VDJ and VJ junctional sequences, respectively, indicating that 2 malignant clones had evolved from a common ancestor. This is the first report on intraclonal heterogeneity in WM. Comparison of the Vlambda and VH sequences with the closest matching known germline genes showed that they contained approximately 10 somatic mutations each. The distribution and type of mutations demonstrate that mutations have continued to accumulate in the malignant clones and that selection has been operating to preserve immunoglobulin structure.

---

### Spin dephasing under nonlinear gradients: implications for imaging and field mapping [^eaf2803c]. Magnetic Resonance in Medicine (2012). Low credibility.

This work examines the prototypical MR echo that would be expected for a voxel of spins evolving in a strong nonlinear field, specifically focusing on the quadratic z(2) - ½(x(2) + y(2)) field. Dephasing under nonlinear gradients is increasingly relevant given the growing interest in nonlinear imaging, and here, we report several notable differences from the linear case. Most notably, in addition to signal loss, intravoxel dephasing under gradients creating a wide and asymmetric frequency distribution across the voxel can cause skewed and nonlinear phase evolution. After presenting the qualitative and analytical origins of this difference, we experimentally demonstrate that neglecting these dynamics can lead to significant errors in sequences that assume phase evolution is proportional to voxel frequency, such as those used for field mapping. Finally, simplifying approximations to the signal equations are presented, which not only provide more intuitive forms of the exact expression but also result in simple rules to predict key features of the nonlinear evolution.

---

### Opportunities and challenges associated with clinical diagnostic genome sequencing: a report of the Association for Molecular Pathology [^e400689e]. The Journal of Molecular Diagnostics (2012). Medium credibility.

Clinical utility of next-generation sequencing (NGS) is characterized by broad application potential, decision impact, and evaluation challenges: Aided by the rapidly decreasing cost of data generation, large-scale personal genome sequencing will be applied to diverse settings, and with proper interpretation NGS will permit a deeper understanding of disease mechanisms, allowing for more evidence-based medical interventions, influencing medical decisions including personalized treatment, monitoring of disease progression, and assessments of disease risk, prognosis, and reproductive matters. Some genome testing will inevitably be offered directly to consumers; in such a setting, consumers will decide independently whether they want to learn about topics ranging from ancestry to disease risks. Clinical utility is described as a measure of the net health benefits, reflected by the balance of benefit versus harm, and accurate evaluation considers factors such as test rationale, patient population, and clinical scenarios, following an individualized evidence-based approach for each patient to separate information with demonstrated medical utility from information with less clear or missing utility evidence. Given NGS data density, variants of unknown significance are encountered many times and our understanding of the biological, pathophysiological, and functional impact of certain genome regions and sequence changes remains limited; thus, the development of evidence-based, validated scientific standards to evaluate clinical utility with accurate genotype-based risk estimation is a considerable challenge, and there is a possibility of potential overinterpretation of results that could lead to unnecessary medical action.

---

### Charting the landscape of priority problems in psychiatry, part 1: classification and diagnosis [^033871c3]. The Lancet: Psychiatry (2016). Medium credibility.

Contemporary psychiatry faces major challenges. Its syndrome-based disease classification is not based on mechanisms and does not guide treatment, which largely depends on trial and error. The development of therapies is hindered by ignorance of potential beneficiary patient subgroups. Neuroscientific and genetics research have yet to affect disease definitions or contribute to clinical decision making. In this challenging setting, what should psychiatric research focus on? In two companion papers, we present a list of problems nominated by clinicians and researchers from different disciplines as candidates for future scientific investigation of mental disorders. These problems are loosely grouped into challenges concerning nosology and diagnosis (this Personal View) and problems related to pathogenesis and aetiology (in the companion Personal View). Motivated by successful examples in other disciplines, particularly the list of Hilbert's problems in mathematics, this subjective and eclectic list of priority problems is intended for psychiatric researchers, helping to re-focus existing research and providing perspectives for future psychiatric science.

---

### Considerations for severe acute respiratory syndrome coronavirus 2 genomic surveillance: a joint consensus recommendation of the Association for Molecular Pathology and association of public health laboratories [^2f3fd16f]. The Journal of Molecular Diagnostics (2025). High credibility.

SARS-CoV-2 genomic surveillance — sample de-identification and nomenclature emphasizes that if patient samples are sequenced, they must be de-identified before uploading to databases, and multiple nomenclature systems exist; it is prudent to use standardized nomenclature (for example SARS-CoV-2 Sequencing for Public Health Emergency Response, Epidemiology, and Surveillance) and example labeling for de-identified next-generation sequencing samples includes state identification, institute or health care organization identification, and randomized and unique identifiers.

---

### EANM practice guideline / SNMMI procedure standard for dopaminergic imaging in parkinsonian syndromes 1.0 [^c1991a8e]. European Journal of Nuclear Medicine and Molecular Imaging (2020). High credibility.

VOI strategies and alternative SBR methods — numeric parameters are dependent on acquisition and reconstruction parameters and on the correctness of placement of VOIs, and SBR differences also occur as the result of VOI strategy, with two approaches commonly employed: one incorporating regions for the caudate and putamen on left and right sides to capture anatomic bounds, and another using small regions of interest sampling the caudate, mid-putamen, and posterior putamen bilaterally. A different approach, the Southampton method, determines SBR from total counts from each striatum using geometrical VOIs sufficiently large to capture all striatal counts including those detected outside anatomical boundaries and a background region from the whole brain minus the striatal VOIs. Several approaches have been proposed to perform semiquantification of DAT SPECT, including individual CT or MRI–guided and machine-learning/textural methods as user-independent classifiers, although these methods still remain in the realm of promising research.

---

### Bi-exponential T2 analysis of healthy and diseased achilles tendons: an in vivo preliminary magnetic resonance study and correlation with clinical score [^d2b26537]. European Radiology (2013). Low credibility.

Objective

To compare mono- and bi-exponential T2 analysis in healthy and degenerated Achilles tendons using a recently introduced magnetic resonance variable-echo-time sequence (vTE) for T2 mapping.

Methods

Ten volunteers and ten patients were included in the study. A variable-echo-time sequence was used with 20 echo times. Images were post-processed with both techniques, mono- and bi-exponential [T2 m, short T2 component (T2 s) and long T2 component (T2 l)]. The number of mono- and bi-exponentially decaying pixels in each region of interest was expressed as a ratio (B/M). Patients were clinically assessed with the Achilles Tendon Rupture Score (ATRS), and these values were correlated with the T2 values.

Results

The means for both T2 m and T2 s were statistically significantly different between patients and volunteers; however, for T2 s, the P value was lower. In patients, the Pearson correlation coefficient between ATRS and T2 s was -0.816 (P = 0.007).

Conclusion

The proposed variable-echo-time sequence can be successfully used as an alternative method to UTE sequences with some added benefits, such as a short imaging time along with relatively high resolution and minimised blurring artefacts, and minimised susceptibility artefacts and chemical shift artefacts. Bi-exponential T2 calculation is superior to mono-exponential in terms of statistical significance for the diagnosis of Achilles tendinopathy.

Key Points

- Magnetic resonance imaging offers new insight into healthy and diseased Achilles tendons
- Bi-exponential T2 calculation in Achilles tendons is more beneficial than mono-exponential
- A short T2 component correlates strongly with clinical score
- Variable echo time sequences successfully used instead of ultrashort echo time sequences.

---

### Epidemiological inference for emerging viruses using segregating sites [^b9b63e0b]. Nature Communications (2023). High credibility.

a The number of sequences sampled over time, calculated using a 4-day time window. b The segregating site trajectory calculated from the binned sequences shown in panel (a). c Estimation of the per-genome, per-transmission mutation rate μ. The histogram shows the fraction of 87 analyzed transmission pairs with consensus sequences that differ from one another by the number of mutations shown on the x-axis. The mean number of mutations per transmission is μ = 0.33 (95% CI = 0.22–0.48). Black dots represent the probability of observing 0, 1, 2, and 3 mutations assuming a Poisson distribution with a mean of 0.33. Vertical black error bars span the probability of observing 0, 1, 2, and 3 mutations assuming Poisson distributions with mean values of 0.22 and 0.48.

We parameterized the model with a per genome, per transmission mutation rate μ using consensus sequence data from established SARS-CoV-2 transmission pairs that were available in the literature – (Methods). Specifically, for each of the 87 transmission pairs we had access to, we calculated the nucleotide distance between the consensus sequence of the donor sample and that of the recipient sample and fit a Poisson distribution to these data (Fig. 6c). Using this approach, we estimated a μ value of 0.33, corresponding approximately to one mutation occurring every 3 transmission events.

Similar to the approach we undertook with our simulated data, we first attempted to jointly estimate R 0 and the timing of the index case t 0 for this segregating site trajectory. We considered a broad parameter space over which to calculate log-likelihood values. Specifically, we considered R 0 values between 1.0 and 4.5 and t 0 values of between December 1st, 2019 and February 14th, 2020. We ran 10 SMC simulations and calculated the mean log-likelihood for each parameter combination (Fig. 7). We estimated R 0 to be 3.0 (95% confidence interval = 1.6 to 4.2), consistent with the R 0 estimate of 2.9 (95% confidence interval = 2.81 to 3.01) arrived at through epidemiological time series analysis. We estimated t 0 to be February 8th, 2020 (95% confidence interval = December 25, 2019, to February 14, 2020).

---

### Scalable spatiotemporal prediction with Bayesian neural fields [^c7f97742]. Nature Communications (2024). High credibility.

Methods

Posterior inference

Let P (Θ f, Θ y, Y) denote the joint probability distribution over the parameters and observable field in Box 1. The posterior distribution is given by Eq. (13) in the main text. We describe two approximate posterior inference algorithms for BNF. In these sections, we define Θ = (Θ f, Θ y), θ = (θ f, θ y) and r = (s, t).

Stochastic MAP ensembles

A simple approach to uncertainty quantification is based on the "maximum a-posteriori" estimate:We find an approximate solution to the optimization problem (15) using stochastic gradient ascent on the joint log probability, according to the following procedure, where B ≤ N is a mini-batch size and (ϵ 1, ϵ 2,…) is a sequence of learning rates:Repeat until convergence

We construct an overall "deep ensemble"containing M ≥ 1 MAP estimates by repeating the above procedure M times, each with a different initialization of θ 0 and random seed.

Stochastic variational inference

A more uncertainty-aware alternative to MAP ensembles is mean-field variational inference, which uses a surrogate posteriorover Θ to approximate the true posterior(13) given the data. Optimal values for the variational parametersare obtained by maximizing the "evidence lower bound":where Eq. (22) follows from the independence of the priors. Finding the maximum of Eq. (22) is a challenging optimization problem. Our implementation leverages a Gaussian variational posterior q ϕ with KL reweighting, as described in Blundell et al. (Sections 3.2 and 3.4 of ref.).

Mean-field variational inference is known to underestimate posterior variance and can also get stuck in local optima of Eq. (21). To alleviate these problems, we use a variational ensemble that is analogous to the MAP ensemble described above. More specifically, we first perform M ≥ 1 runs of stochastic variational inference with different initializations and random seeds, which gives us an ensemble { ϕ i, i = 1, …, M } of variational parameters. We then approximate the posteriorwith an equal-weighted mixture of the resulting variational distributions.

---

### Probabilistic alignment of multiple networks [^f4880076]. Nature Communications (2025). High credibility.

Sampling the space of plausible alignments

By analogy to statistical mechanics, we can associate an "energy"to each blueprint-permutation pair (L, { π k }), so that their posterior is writtenand the energycan be obtained directly from Eq. (6). In this interpretation, the best alignment is the blueprint-permutation pair that minimizes. Importantly, this equivalence enables us to sample over the space of alignments (L, { π k }) using Markov chain Monte Carlo("Methods"; see Supplementary Material and Fig. fig:time_size for the algorithmic complexity of our tool). The sampling of equilibrium alignments from this space allows us to approach the network alignment problem in ways other than just finding the single best alignment.

In particular, by sampling alignments from the posterior distribution, we can estimate the probability p (π k (i k) = i L ∣{ A k }) that node i k in network A k is mapped to node i L in the blueprint as the fraction of sampled permutations in which π k (i k) = i L. Then, we can estimate the most probable mapping for each node π k,⋆ (i k) as the one that maximizes p (π (i k) = i L ∣{ A k }) (Methods). As we show below, in noisy observations, the most plausible alignment does not necessarily recover the ground truth mapping of nodes. This is because for nodes with few connections, copy error can introduce a degree of ambiguity and degeneration in the mappings of node identities. However, we find that the most probable mapping of each individual node recovers the ground truth for their mapping more reliably (Fig. 2). This is, in fact, an expected result from using a probabilistic approach: averages over the ensemble of possible alignments are more accurate at predicting hidden information (in this case, node mappings to the blueprint) than single point estimates (that is, the best alignment) (see for instance Ref.for a discussion in the context of link prediction).

---

### Statistical modeling of RNA structure profiling experiments enables parsimonious reconstruction of structure landscapes [^f507fa1c]. Nature Communications (2018). Medium credibility.

Design matrix

The entries of the design matrix are expressed as functions of the unknown modification probability at unpaired sites (η) and noise parameters (γ). To estimate η, it is helpful to consider a related vector from the model by Aviran et al. namely, β. Recall that β l is the probability that site l is modified when considering all molecules in the sample, or in other words, it is a modification propensity that is aggregated over the many different structures in the ensemble. Importantly, while η is kept constant across all unpaired sites within an ensemble of structures, β l is both site-specific and an ensemble-based average measure. To illustrate the relationship between η and β, consider three sites with the following properties: i is unpaired in all structures, j is paired in all structures, and k is paired in some and unpaired in others. The respective ensemble-average probabilities would then be β i ≈ η, β j ≈ 0, and 0 < β k < η. Thus, estimating β at sites such as i allows one to infer η at reasonable accuracy. However, not knowing which candidate structures are highly abundant, it is not trivial to identify such sites. A conservative approach is to seek sites that are unpaired in all candidate structures, but it may be challenging in cases where structural diversity is high. Here, we estimate η fromempirically by sorting the's from high to low, calculating their mean, and settingas the median of those exceeding the mean. This approach is motivated by the expectation that β l would be large at sites that are primarily unpaired in the ensemble. At the same time, it considers a subset of reactive sites to confer robustness to outliers, which are commonly observed in SP data. If no sites that are unpaired across the ensemble exist, we are likely to underestimate η, which in turn will degrade prediction accuracy.

To estimate β and γ, we use maximum-likelihood estimates derived by Aviran et al.:where X l and Y l (l = 1, 2,… L) are counts of truncations/mutations at site l observed in treated and control samples, respectively, and C l + and C l − are local coverages in said samples. Local coverage at site l in a sample stands for the sequencing depth at l, which definition is straightforward in mutation mode. In truncation mode, local coverage is defined as the number of reads that either stop at or pass through l.

---

### Bayesian genomic-enabled prediction as an inverse problem [^de34a538]. G3 (2014). Low credibility.

A Bayesian inverse regression model

Several methods have been proposed for mitigating ill-conditioned regression problems by shrinking the solution space via restricting the magnitudes of the estimates and their variance. One of the first proposals was the ridge regression estimator. Since model (3) has the form, with, the ridge regression estimator is:with Γ as a diagonal matrix of dimensions n × n with values on the diagonal. Hereis a vector of parameters that reduce ill-conditioning. If their magnitude increases excessively, this can lead to a poor fit of the model to the data. Therefore, the choice of vector γ is critical.

showed that there is a range of γ values where the mean squared error (MSE) of estimates is smaller than the corresponding MSE of the ordinary least squares solution. They minimized MSE by choosingThis requires knowing the true values of b. However, (9) can be used to justify the choicewhere, andare estimates of b, respectively, thus providing a single (global) shrinkage parameter.

In the Bayesian approach, the prior distribution reflects prior beliefs about, and its variance affects the extent to which the least squares estimate moves toward the prior mean. To construct a model along the lines of, we adopted as the conditional prior distribution ofwhere thecoefficients (given) are conditionally independent. Therefore, the joint posterior distribution of b andin model (3) is given by:where(i = 1, …, n) are variance parameters andis the prior distribution of. Usually the conjugate prior foris a scaled inverse χ 2 distribution withdegrees of freedom and scale parameter, that is, From (12), the conditional posterior distribution of b is:Expression (14) indicates that the conditional posterior mean depends on the data, whereas the variance is a fixed but unknown quantity.

The conditional expectation of b in (14) can also be expressed aswhereis known as the 'weighting factor' that weights the least squares estimate.

Because the magnitude of variance ofgrows with i, suggested applying a lower weighting factor for estimates with larger variance. The weighting factor assigns weights close to one to the first elements of, whereas the remaining elements receive lower weights, and can take on values close to zero, or zero itself.

---

### The "hidden noise" problem in MR image reconstruction [^61adf3f6]. Magnetic Resonance in Medicine (2024). Medium credibility.

Purpose

The performance of modern image reconstruction methods is commonly judged using quantitative error metrics like root mean squared-error and the structural similarity index, which are calculated by comparing reconstructed images against fully sampled reference data. In practice, the reference data will contain noise and is not a true gold standard. In this work, we demonstrate that the "hidden noise" present in reference data can substantially confound standard approaches for ranking different image reconstruction results.

Methods

Using both experimental and simulated k-space data and several different image reconstruction techniques, we examined whether there was correlation between performance metrics obtained with typical noisy reference data versus those obtained with higher-quality reference data.

Results

For conventional performance metrics, the reconstructions that matched best with the higher-quality reference data were substantially different from the reconstructions that matched best with typical noisy reference data. This leads to suboptimal reconstruction results if the performance with respect to noisy reference data is used to select which reconstruction methods/parameters to employ. These issues were reduced when employing alternative error metrics that better account for noise.

Conclusion

Reference data containing hidden noise can substantially mislead the ranking of image reconstruction methods when using conventional error metrics, but this issue can be mitigated with alternative error metrics.