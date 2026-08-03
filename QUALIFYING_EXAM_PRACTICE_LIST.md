# Complex Analysis Qualifying Exam — Priority Practice List

This list is based on all 156 exercises in the repository:

- 9 questions in `Exams/main.tex`;
- 40 questions from the August 2018, August 2020, August 2024, and January 2025 qualifying exams;
- 107 textbook exercises in `Exercise/complex.tex`.

The ordering gives the most weight to questions that appeared on a qualifying exam, especially when essentially the same textbook exercise later appeared on an exam. Check an item only after you can solve it from a blank page, justify every theorem's hypotheses, and explain the proof aloud.

## If time is short — do these 12 first

1. The contour-integral proof of the Fundamental Theorem of Algebra ([January 2025, I.1](<Qualifying Exam/main.tex#L1973>)).
2. Count the roots of \(z^9+z^5-8z^3+2z+1\) in \(1<|z|<2\) ([August 2024, I.3](<Qualifying Exam/main.tex#L1586>)).
3. Prove uniqueness of the solution to \(e^z=cz\), \(|c|>e\), in \(\operatorname{Re}z<1\) ([January 2025, I.2](<Qualifying Exam/main.tex#L2147>)).
4. Rule out boundary blow-up for a holomorphic function on the disk ([August 2018, I.3](<Qualifying Exam/main.tex#L182>)).
5. Prove that continuity on \(\mathbb C\) plus analyticity off \([-1,1]\) implies entire analyticity ([January 2025, I.3](<Qualifying Exam/main.tex#L2219>)).
6. Construct a holomorphic logarithm of the quotient of two functions with identical zeros ([August 2018, I.2](<Qualifying Exam/main.tex#L115>)).
7. Map a vertical strip conformally onto the disk ([August 2018, I.1](<Qualifying Exam/main.tex#L76>)).
8. Prove the derivative bound for a self-map of the right half-plane fixing a positive point ([August 2020, II.4](<Qualifying Exam/main.tex#L1391>)).
9. Prove normality from the disk-area bound \(\iint_D|f|\le1\) ([August 2018, II.5](<Qualifying Exam/main.tex#L945>)).
10. Prove the moving-preimage/Hurwitz result for \(f_n\to f\) ([August 2020, II.3](<Qualifying Exam/main.tex#L1380>)).
11. Use Mittag-Leffler to prove \(Af+Bg=1\) for entire functions without common zeros ([August 2020, II.1](<Qualifying Exam/main.tex#L1306>)).
12. Prove that the critical points of a nonconstant harmonic function are isolated ([January 2025, II.2](<Qualifying Exam/main.tex#L2383>)).

## Tier 1 — Must practice

### 1. Fundamental Theorem of Algebra by several methods

- [ ] Prove the FTA using the maximum modulus principle ([August 2020, I.4](<Qualifying Exam/main.tex#L1168>)).
- [ ] Prove it using Liouville's theorem ([January 2025, I.4](<Qualifying Exam/main.tex#L2274>)).
- [ ] Complete the partial-fraction identity and contour-integral proof ([January 2025, I.1](<Qualifying Exam/main.tex#L1973>)).

Why: the FTA appeared three times in four recorded qualifying exams, with three different requested proofs.

### 2. Rouché's theorem and counting zeros

- [ ] Count the zeros of \(z^9+z^5-8z^3+2z+1\) in \(1<|z|<2\) ([August 2024, I.3](<Qualifying Exam/main.tex#L1586>)).
- [ ] Show that \(ze^{a-z}=1\), \(a>1\), has exactly one root in the closed unit disk and prove that it is positive ([August 2020, I.3](<Qualifying Exam/main.tex#L1087>)).
- [ ] Show that \(e^z=cz\), \(|c|>e\), has exactly one solution in \(\operatorname{Re}z<1\) ([January 2025, I.2](<Qualifying Exam/main.tex#L2147>)).
- [ ] Show that \(f(z)=z^n\) has exactly \(n\) solutions in the disk when \(|f|<1\) on the unit circle ([text exercise](<Exercise/complex.tex#L3827>)).

Why: you should be able to choose the comparison function and contour yourself, not only recognize Rouché after being told to use it.

### 3. Liouville, growth, and maximum/minimum modulus arguments

- [ ] Prove that an entire \(f\) satisfying \(|f(z)|\le M|z|^{1/2}\) outside a disk is constant ([August 2020, I.1](<Qualifying Exam/main.tex#L961>)).
- [ ] Prove the general version: \(|f(z)|\le M|z|^n\) outside a disk implies that \(f\) is a polynomial of degree at most \(n\) ([text exercise](<Exercise/complex.tex#L2317>)).
- [ ] If entire \(f,g\) satisfy \(f(0)=g(0)\ne0\) and \(|f|\le|g|\), prove \(f=g\) ([August 2018, I.5](<Qualifying Exam/main.tex#L489>)).
- [ ] If an analytic function has a global interior minimum of its modulus, prove that it vanishes there or is constant ([text exercise](<Exercise/complex.tex#L2369>)).

### 4. Boundary blow-up contradiction on the disk

- [ ] Prove that every holomorphic function on the unit disk has a sequence \(|z_n|\to1\) for which \(\{f(z_n)\}\) is bounded ([August 2018, I.3](<Qualifying Exam/main.tex#L182>)).
- [ ] Solve the equivalent sequential formulation from August 2024 ([August 2024, I.2](<Qualifying Exam/main.tex#L1520>)).

Why: this exact idea returned six years later. Know how to remove the finitely many zeros and apply the maximum modulus principle to the reciprocal.

### 5. Cauchy's formula, residues, and winding numbers

- [ ] Compute \(\int_\gamma z^n\,dz\) for every integer \(n\), and \(\int_\gamma dz/z\) around a polygon ([Fall 2025, I.1–2](<Exams/main.tex#L76>)).
- [ ] Evaluate a contour integral with poles of different orders and determine which poles lie inside the contour ([Fall 2025, II.1–2](<Exams/main.tex#L242>)).
- [ ] Prove \(\int_\gamma dz/z=\log r+i\theta+2\pi i k\) for a path from \(1\) to \(re^{i\theta}\) ([August 2020, I.2](<Qualifying Exam/main.tex#L1005>); same as [text exercise](<Exercise/complex.tex#L2569>)).
- [ ] Derive the local integral \(\int_\gamma [f(z)-f(z_0)]^{-1}dz=2\pi i/f'(z_0)\) ([January 2025, I.5](<Qualifying Exam/main.tex#L2304>)).
- [ ] Practice winding-number integrals over noncircular curves ([text exercises](<Exercise/complex.tex#L3121>), [second set](<Exercise/complex.tex#L3206>)).

### 6. Removable sets and Morera's theorem

- [ ] Prove that a continuous function on \(\mathbb C\) which is analytic off \([-1,1]\) is entire ([January 2025, I.3](<Qualifying Exam/main.tex#L2219>); same as [text exercise](<Exercise/complex.tex#L2961>)).

Why: be ready to subdivide triangles intersecting the segment and use continuity to control the thin pieces.

### 7. Analytic logarithms, zeros, and branches

- [ ] If holomorphic \(F,G\) on a half-plane have the same zeros with the same multiplicities, prove \(F=e^hG\) for holomorphic \(h\) ([August 2018, I.2](<Qualifying Exam/main.tex#L115>)).
- [ ] Prove that \(z^\alpha\) has a single-valued analytic branch on an annulus iff \(\alpha\in\mathbb Z\) ([August 2020, II.5](<Qualifying Exam/main.tex#L1403>)).
- [ ] Give the principal branch and exact branch cuts of \(\sqrt{1-z^3}\) ([Fall 2025, I.7](<Exams/main.tex#L186>)).
- [ ] Prove that no logarithm branch exists on \(\mathbb C\setminus\{0\}\) ([text exercise](<Exercise/complex.tex#L1150>)).

### 8. Conformal maps and Möbius transformations

- [ ] Map a vertical strip conformally onto the disk ([August 2018, I.1](<Qualifying Exam/main.tex#L76>)).
- [ ] Map the complement of a line segment analytically onto the disk and decide whether the map can be one-to-one ([Fall 2025, I.6](<Exams/main.tex#L178>); prototype [text exercise](<Exercise/complex.tex#L1513>)).
- [ ] Find every Möbius automorphism of the disk ([text exercise](<Exercise/complex.tex#L1363>)).
- [ ] Classify the Möbius maps having specified fixed points \(0\) and/or \(\infty\) ([Fall 2025, I.3](<Exams/main.tex#L157>)).
- [ ] Decide whether the disk can be mapped conformally onto a punctured disk ([text exercise](<Exercise/complex.tex#L1499>)).

### 9. Schwarz lemma and half-plane self-maps

- [ ] If a one-to-one analytic map sends the right half-plane into itself and fixes \(a>0\), prove \(|f'(a)|\le1\) ([August 2020, II.4](<Qualifying Exam/main.tex#L1391>); same as [text exercise](<Exercise/complex.tex#L5769>)).
- [ ] Derive the two-sided Schwarz–Pick bounds for a disk map with arbitrary \(f(0)\) ([text exercise](<Exercise/complex.tex#L4016>)).
- [ ] Derive growth bounds for analytic functions with positive real part using a Möbius transformation ([text exercise](<Exercise/complex.tex#L4115>)).

### 10. Normal families from estimates

- [ ] Decide whether \(\mathcal F=\{f\in H(D):\iint_D|f|\le1\}\) is normal, and prove the answer ([August 2018, II.5](<Qualifying Exam/main.tex#L945>)).

Why: this requires converting an area integral into a uniform bound on compact subsets, typically through the mean-value property or Cauchy estimates.

### 11. Operations on normal families

- [ ] Prove that normality of \(\mathcal F\subset H(G)\) implies normality of \(\mathcal F'=\{f':f\in\mathcal F\}\) ([January 2025, II.5](<Qualifying Exam/main.tex#L2550>); same as [text exercise](<Exercise/complex.tex#L5339>)).
- [ ] If \(\mathcal F\) is normal and \(g\) is analytic and bounded on bounded sets, prove \(\{g\circ f:f\in\mathcal F\}\) is normal ([August 2024, II.3](<Qualifying Exam/main.tex#L1804>); same as [text exercise](<Exercise/complex.tex#L5446>)).
- [ ] Prove the closed-curve criterion for convergence in \(H(G)\) ([August 2024, II.2](<Qualifying Exam/main.tex#L1798>)).

### 12. Hurwitz-type convergence and moving points

- [ ] If \(f_n\to f\) in \(H(G)\), \(f\) is nonconstant, and \(b=f(a)\), find \(a_n\to a\) with \(f_n(a_n)=b\) eventually ([August 2020, II.3](<Qualifying Exam/main.tex#L1380>)).
- [ ] If one-to-one \(f_n\) converge in \(H(G)\), prove the limit is one-to-one or constant ([text exercise](<Exercise/complex.tex#L5561>)).
- [ ] Prove \(f_n(z_n)\to f(z)\) when \(f_n\to f\) locally uniformly and \(z_n\to z\) ([January 2025, II.4](<Qualifying Exam/main.tex#L2505>); same as [text exercise](<Exercise/complex.tex#L5109>)).

### 13. Weierstrass products and prescribed zeros

- [ ] Construct an entire function having a zero of order \(n\) at each positive integer \(n\) ([August 2024, II.5](<Qualifying Exam/main.tex#L1965>)).
- [ ] Construct an elementary entire function vanishing at every \(ne^{2\pi ik/n}\) ([January 2025, II.3](<Qualifying Exam/main.tex#L2435>)).
- [ ] Construct an analytic function on the disk having the unit circle as a natural boundary ([August 2024, II.4](<Qualifying Exam/main.tex#L1863>); same as [text exercise](<Exercise/complex.tex#L5999>)).
- [ ] Construct an entire function vanishing on the integer lattice ([text exercise](<Exercise/complex.tex#L6024>)).

### 14. Mittag-Leffler and analytic Bézout identities

- [ ] Given entire \(f,g\) with no common zeros, prove that entire \(A,B\) exist with \(Af+Bg=1\) ([August 2020, II.1](<Qualifying Exam/main.tex#L1306>)).
- [ ] Construct a meromorphic function with prescribed poles, principal parts, zeros, and multiplicities ([text exercise](<Exercise/complex.tex#L6270>)).

### 15. Basic analyticity, inverse functions, and reflection

- [ ] From \(h=g\circ f\), with \(h\) one-to-one and \(g'\ne0\), prove a merely continuous \(f\) is analytic and find \(f'\) ([August 2024, I.1](<Qualifying Exam/main.tex#L1416>); same as [text exercise](<Exercise/complex.tex#L976>)).
- [ ] Prove that \(f^*(z)=\overline{f(\bar z)}\) is analytic on the reflected region ([August 2024, I.5](<Qualifying Exam/main.tex#L1733>); same as [text exercise](<Exercise/complex.tex#L1116>)).
- [ ] If an entire function is real on the real axis and imaginary on the imaginary axis, prove it is odd ([August 2020, I.5](<Qualifying Exam/main.tex#L1234>)).
- [ ] Check analyticity directly with the Cauchy–Riemann equations for the Fall 2025 example ([Fall 2025, I.5](<Exams/main.tex#L169>)).

### 16. Open mapping and restricted ranges

- [ ] Prove that an analytic function whose image is contained in a circle is constant ([Fall 2025, I.4](<Exams/main.tex#L165>); same as [text exercise](<Exercise/complex.tex#L1526>)).
- [ ] Classify all entire \(f\) satisfying \(f(\lambda z)=\lambda f(z)\) for every \(|\lambda|=1\) ([August 2018, I.4](<Qualifying Exam/main.tex#L351>)).
- [ ] Prove that a nonconstant bounded holomorphic function on \(\operatorname{Im}z<1\) cannot be real-valued on the entire real axis ([August 2018, II.3](<Qualifying Exam/main.tex#L729>)).

### 17. Harmonic functions

- [ ] Prove that a nonconstant harmonic function is an open map ([August 2024, II.1](<Qualifying Exam/main.tex#L1794>); same as [text exercise](<Exercise/complex.tex#L6393>)).
- [ ] Prove that the critical set \(\{u_x=u_y=0\}\) of a nonconstant harmonic function has no limit point in the region ([January 2025, II.2](<Qualifying Exam/main.tex#L2383>); same as [text exercise](<Exercise/complex.tex#L6640>)).
- [ ] Prove that \(\log|f|\) is harmonic when analytic \(f\) has no zeros ([text exercise](<Exercise/complex.tex#L6449>)).
- [ ] Prove the area mean-value property for harmonic functions ([text exercise](<Exercise/complex.tex#L6480>)).

## Tier 2 — Important advanced coverage

### 18. Infinite-product functional equations

- [ ] Determine every entire solution of \(f(3z)=(1-3z)f(z)\) as an infinite product ([August 2018, II.1](<Qualifying Exam/main.tex#L537>)).

### 19. Local geometry at a double zero

- [ ] If \(F(z_0)=F'(z_0)=0\) and \(F''(z_0)\ne0\), construct two orthogonal curves through \(z_0\) on which \(F\) is real, with a minimum on one and a maximum on the other ([August 2018, II.2](<Qualifying Exam/main.tex#L637>)).

### 20. Polynomial approximation versus compact convergence

- [ ] Construct polynomials converging pointwise to \(1,0,-1\) according as \(\operatorname{Re}z>0,=0,<0\), then prove the sequence cannot be locally bounded ([August 2018, II.4](<Qualifying Exam/main.tex#L808>)).

### 21. Laurent series and isolated singularities

- [ ] Find all three Laurent expansions of \(1/[z(z-1)(z-2)]\) centered at zero ([text exercise](<Exercise/complex.tex#L3477>)).
- [ ] Analyze the cluster values near an accumulation point of poles ([text exercise](<Exercise/complex.tex#L3602>)).

### 22. Residues for real integrals

- [ ] Evaluate \(\int_0^\infty \cos(ax)/(1+x^2)^2\,dx\) for \(a>0\) by residues ([text exercise](<Exercise/complex.tex#L3680>)).

### 23. Boundary modulus and finite Blaschke products

- [ ] Classify analytic functions near the closed disk satisfying \(|f|=1\) on the unit circle ([text exercise](<Exercise/complex.tex#L4243>)).
- [ ] If two zero-free analytic functions have equal modulus on a boundary circle, prove they differ by a unimodular constant ([text exercise](<Exercise/complex.tex#L3916>)).

### 24. Riemann mapping and topology of punctures

- [ ] Study a bounded one-to-one analytic map on a punctured region and prove that a punctured disk cannot map one-to-one onto an annulus with positive inner radius ([text exercise](<Exercise/complex.tex#L5622>)).
- [ ] Use symmetry and uniqueness in the Riemann mapping theorem to locate the image of the upper half of a symmetric region ([text exercise](<Exercise/complex.tex#L5700>)).

### 25. Subharmonic functions

- [ ] Prove that composition with a one-to-one analytic map preserves subharmonicity ([January 2025, II.1](<Qualifying Exam/main.tex#L2376>)).

### 26. Runge and approximation obstructions

- [ ] Give a function analytic near a compact annulus that cannot be approximated there by functions analytic on the disk ([text exercise](<Exercise/complex.tex#L6147>)).

### 27. Phragmén–Lindelöf

- [ ] Prove the strip version with growth \(\exp(Ae^{a\operatorname{Re}z})\), and understand why \(a<1\) is sharp ([text exercise](<Exercise/complex.tex#L4786>)).
- [ ] Prove the boundary estimate with one exceptional boundary point and sub-polynomial blow-up ([text exercise](<Exercise/complex.tex#L4996>)).

## Lower-priority warm-ups

Use these for speed, but do not spend your main study time on them before completing Tier 1:

- roots and polar form ([Exercise/complex.tex, line 112](<Exercise/complex.tex#L112>));
- basic topology of metric spaces ([Exercise/complex.tex, line 269](<Exercise/complex.tex#L269>));
- elementary path parametrization and direct integration ([Exercise/complex.tex, line 1588](<Exercise/complex.tex#L1588>));
- basic power-series radii ([Exercise/complex.tex, line 860](<Exercise/complex.tex#L860>));
- elementary uniqueness of primitives and integration by parts ([Exercise/complex.tex, line 1747](<Exercise/complex.tex#L1747>)).

## Recommended order

1. First pass: items 1–9 (core first-semester techniques).
2. Second pass: items 10–17 (convergence, factorization, and harmonic theory).
3. Third pass: items 18–27 (Part II and advanced topics).
4. Final review: redo every qualifying-exam question above under a 20–25 minute limit without notes.

A solution counts as exam-ready only if you can state exactly why the relevant hypotheses hold—for example, why a quotient has removable singularities, why a logarithm exists on the domain, which zeros lie inside a Rouché contour, or why a family is locally bounded.
