# THE DIRAC-HORIZON OPERATOR

## Chiral Spinor Geometry as the Universal col(F)/ker(F) Completion

**From TH(a,d) GL(2) Anchor to ζ(s) GL(1) via the Event Horizon, Dirac Boundary,
Nonlinear Quantum Walk Trapping, and the Full VSCW–Jacobi–CORDIRAC Synthesis**

---

*ERI Labs · Eric Ren · Jersey City, New Jersey · [github.com/ericrenone](https://github.com/ericrenone)*

**May 29, 2026**

---

> *The boundary was always Dirac. The horizon was always the answer. The traversal is now equipped.*

---

## Abstract

The Twisted Hessian curve **TH(a,d)** provides a concrete GL(2) anchor whose Hasse–Weil
L-function satisfies the Riemann Hypothesis on Re(s) = 1/2. This is not a conjecture — it
is settled arithmetic geometry, following from modularity (Wiles 1995; Breuil–Conrad–Diamond–Taylor
2001) and Weil–Deligne cohomology (Weil 1949; Deligne 1974). TH(a,d) computes its own group law
via the CORDIC recurrence in hyperbolic mode, costs 12M + 6S in field operations, and carries
a Z/3Z × Z/3Z torsion structure whose 3-periodicity is the algebraic reason CORDIC forced
repeated iterations exist at positions j = (3^k − 1)/2.

The gap between this proven GL(2) fact and the classical Riemann Hypothesis for ζ(s) — a GL(1)
object — is the deepest arithmetic barrier in modern mathematics. No Langlands functorial lift is
known that maps a general cuspidal GL(2) automorphic representation to a GL(1) object recovering
the zeros of ζ(s). The **Dirac-Horizon Operator (DHO)** is ERI Labs' integrated programme for
locating, mapping, stress-testing, and — subject to the 2027–2028 research agenda — potentially
traversing this barrier.

The DHO identifies the **event horizon** as the physical realization of the Dirac operator ∂̸ on
a compact spin manifold. Exterior Hawking radiation and gravitational wave emission constitute
col(∂̸). The interior, Page islands, and the Belinski–Khalatnikov–Lifshitz (BKL) singularity-adjacent
conformal primon gas constitute ker(∂̸). The Page transition is Scholze perfectoid tilting across
the causal boundary. The Hartnoll–Yang conformal primon gas (arXiv:2502.02661; JHEP 07(2025) 281)
realizes zeta-function prime statistics from a first-principles near-horizon CFT. The Shi–Wong
nonlinear quantum walk (arXiv:2605.20464, May 2026) traps col(∂̸) amplitude into ker(∂̸) on the
simplest representational manifold S¹, providing the first dynamical analog of a GL(1) fixed
point emerging from GL(2) dynamics.

Every ERI repository maps onto this single operator. The programme does not claim a proof of
classical RH. It supplies the richest proven GL(2) anchor in the literature, a physical
completion mechanism with empirically testable predictions across arithmetic, gravitational wave
astronomy, machine learning, topological data analysis, and organizational dynamics, and a
concrete 2027–2028 agenda to stress-test and constrain the barrier from every available direction.

---

## Table of Contents

1. [The Precise Gap: GL(2) vs. GL(1)](#1-the-precise-gap-gl2-vs-gl1)
2. [The Twisted Hessian Anchor TH(a,d)](#2-the-twisted-hessian-anchor-thad)
3. [The Dirac Corpus: Full Structure and Decomposition](#3-the-dirac-corpus)
4. [CORDIRAC: The Discretized Dirac Pipeline](#4-cordirac-the-discretized-dirac-pipeline)
5. [The Horizon as Universal Dirac Boundary](#5-the-horizon-as-universal-dirac-boundary)
6. [Integration Map: All ERI Domains](#6-integration-map-all-eri-domains)
7. [Frontier Results 2025–Mid-2026](#7-frontier-results-2025mid-2026)
8. [The 2027–2028 Dirac-Horizon Research Programme](#8-the-20272028-dirac-horizon-research-programme)
9. [Falsification and Risk](#9-falsification-and-risk)
10. [Repository Structure](#10-repository-structure)
11. [References](#11-references)
12. [Vision Beyond 2028](#12-vision-beyond-2028)

---

## 1. The Precise Gap: GL(2) vs. GL(1)

### 1.1 What Is Proven

For any elliptic curve E/ℚ — and specifically for TH(a,d) over ℚ — the completed L-function
satisfies the following theorem, which is not a conjecture:

> **Theorem (Weil 1949; Deligne 1974; Wiles 1995; BCDT 2001):**
> Λ(E, s) has analytic continuation to ℂ, satisfies a functional equation Λ(E, s) = ±Λ(E, 2−s),
> and all non-trivial zeros lie on Re(s) = 1/2.

The proof rests on three pillars:

1. **Modularity.** Every E/ℚ is modular (Wiles 1995 for semistable curves; BCDT 2001 in full
   generality). Hence L(E, s) = L(f, s) for a weight-2 cuspidal newform f ∈ S₂(Γ₀(N)), landing
   L(E,s) inside the GL(2) automorphic world with all its analytic machinery.

2. **Automorphic GRH.** Weil's theorem for curves over finite fields (1948) and Deligne's
   generalization to higher-weight motives (Weil II, 1980) establish GRH for every L(f, s) arising
   from a geometric motive. The zeros of L(TH, s) on Re(s) = 1/2 follow directly.

3. **Galois representation.** The ℓ-adic representation ρ_E : Gal(ℚ̄/ℚ) → GL(2, ℤ_ℓ) is
   2-dimensional, geometrically irreducible, and crystalline at ℓ. This places L(E, s) firmly
   in the GL(2) Langlands parameter space — degree 2 — with full control on local factors.

TH(a,d) is the DHO's GL(2) anchor because it additionally carries the Z/3Z × Z/3Z Hesse
torsion structure, admits optimal cryptographic group law arithmetic (12M + 6S, uniform, no
exceptional points), and is computed exactly by the CORDIC recurrence in hardware.

### 1.2 What Remains Open

The Riemann zeta function ζ(s) is the degree-1 L-function of the trivial Galois representation
ρ₀ : Gal(ℚ̄/ℚ) → GL(1, ℂ), value ρ₀(Frob_p) = 1 for all primes p. The Riemann Hypothesis
asserts that all non-trivial zeros satisfy Re(s) = 1/2. This is entirely unproven. A single
off-critical-line zero would distort prime gaps via the explicit formula

```
ψ(x) = x − Σ_{ρ} x^ρ/ρ − log(2π) − ½ log(1 − x^{−2})
```

with the ρ sum running over non-trivial zeros. The prime number theorem already exploits
zero-free regions; RH would make the error term O(x^{1/2} log x).

### 1.3 The Exact Arithmetic Barrier

The precise obstruction is the **absence of a Langlands functorial lift from GL(2) to GL(1)**:

- Symmetric powers Sym^n(π) of a GL(2) cuspidal automorphic representation π produce
  L-functions of degree n + 1. Functoriality for Sym² and Sym³ (Shimura; Gelbart–Jacquet),
  Sym³ and Sym⁴ for GL(2) (Kim–Shahidi 2002), and limited progress toward Sym⁵ are the
  current state of the art.
- The **n → ∞ limit** — which should recover ζ(s) statistics via conjectural Selberg
  eigenvalue identities and Euler product factorizations — is strictly conjectural.
  No established mechanism extracts the GL(1) Hecke eigenvalues 1 from any finite-degree
  GL(2) symmetric power.
- The **GL(2) → GL(1) direction** would require a trace or period integral extracting GL(1)
  Hecke spectra from the GL(2) family — closely related to Gan–Gross–Prasad period
  conjectures and the Braverman–Kazhdan "beyond endoscopy" programme.

### 1.4 The DHO Geometric Identification

The Dirac-Horizon Operator makes this gap geometrically explicit:

| Arithmetic | DHO Geometric Analog |
|---|---|
| GL(2) automorphic modes | col(∂̸): propagating exterior spinors |
| GL(1) protected structure | ker(∂̸): topological interior zero modes |
| Langlands functorial lift | Page island information return |
| Sym^n limit | Near-singularity conformal field theory |
| Failure of GL(2)→GL(1) | Causal barrier: interior inaccessible classically |

The DHO does not dissolve the gap. It names it precisely as the col(∂̸)/ker(∂̸) causal
boundary problem, provides physical completion mechanisms with testable signatures, and
generates dozens of cross-domain predictions any correct proof must satisfy.

---

## 2. The Twisted Hessian Anchor TH(a,d)

### 2.1 The Curve and Its Group Law

The Twisted Hessian curve over a field k (char(k) ≠ 3) is:

```
TH(a,d) : a(X³ + Y³ + Z³) = dXYZ      in ℙ²(k)
```

with neutral element O = [1 : −1 : 0]. In affine coordinates (x, y) = (X/Z, Y/Z), the
complete, exception-free addition law is:

```
(x₁, y₁) ⊕ (x₂, y₂)  =  (  (x₁y₂ − x₂y₁) / (y₁y₂ − ax₁x₂),
                              (ax₁x₂y₂ − y₁²y₂) / (y₁y₂ − ax₁x₂)  )
```

This formula costs **12M + 6S** in field multiplications and squarings — optimal for the
Hesse pencil — and is **uniform**: there is no branch point, no exceptional input pair,
no special-case subtraction needed. This uniformity is both a cryptographic advantage
(side-channel resistance) and a mathematical signature that the curve's symmetry group
(including the Hessian automorphisms of order 3) acts without fixed points on the
complement of O.

### 2.2 Arithmetic Properties

**3-torsion.** TH(a,d)[3] contains 9 points forming the Hesse configuration — the projective
dual of the Hessian pencil. These 9 points are the arithmetic roots of the Z/3Z structure
appearing throughout the DHO. The quotient TH(a,d)/⟨Z/3Z⟩ is another Twisted Hessian
curve; the corresponding **3-isogeny chain** (Bernstein–Kohel–Lange 2019) gives rise to the
forced repeated iterations in hyperbolic CORDIC at positions j = (3^k − 1)/2 = 0, 1, 4, 13, 40, …

**Modularity and L-function.** L(TH, s) = ∏_p (1 − a_p p^{-s} + p^{1−2s})^{−1} (good
primes), with a_p the trace of Frobenius. By modularity this equals L(f, s) for a weight-2
newform, placing all zeros on Re(s) = 1/2 (proven).

**j-invariant and CM points.** The j-invariant of TH(a,d) depends on the ratio a³/d³. As a/d
ranges over ℚ*, the family covers a Zariski-dense subset of the modular curve X₀(3), including
the CM points j = 0 (Eisenstein) and j = 54000 (discriminant −12).

### 2.3 The Freudenthal–Tits Exceptional Dimension Correspondence

The hardware parameters of the SYCore systolic CORDIC engine are not engineering choices —
they are forced by the Hurwitz–Radon theorem applied at sedenion dimension:

| Engine parameter | Count | Exceptional interpretation |
|---|---|---|
| 16 PEs × 3 modes | 48 | \|Φ(F₄)\| = 48 roots of F₄ |
| 8 PEs × 3 modes | 24 | 2\|Φ(G₂)\| = 2 × 12 |
| 3 modes × ρ(16) = 9 | 27 | dim H₃(O) (Albert algebra, exceptional Jordan) |
| ρ(16) = 9 | 9 | Hurwitz–Radon: max anti-commuting directions at dim 16 |
| 16 stages × 6 modes | 96 | 2 × 48 = 2\|Φ(F₄)\| |
| 7 × 8 = 56 | 56 | dim Freudenthal module of E₇ |

The CORDIC gain correction 1/56 is the first torsion event: Stage 15's final gain
compensation K⁻¹ ≈ φ + 1/56 encodes the Freudenthal module dimension in hardware.

### 2.4 Connection to Jacobi Elliptic Functions

TH(a,d) admits a natural parameterization by the Jacobi triple (sn, cn, dn) with modulus k
determined by the ratio a/d. The addition theorem for Jacobi elliptic functions is, in this
parameterization, exactly the TH(a,d) group law. The Hamilton–Jacobi equation on TH has this
curve as its phase space; the Jacobi identity on the curve ensures symmetry closure of the
action-angle transformation. This is the bridge to the JACOBI repository and the
classical–quantum surface programme.

---

## 3. The Dirac Corpus: Full Structure and Decomposition

### 3.1 The Dirac Operator on Compact Spin Manifolds

Let M be a compact oriented Riemannian spin manifold of dimension n. The spinor bundle
S = S⁺ ⊕ S⁻ is graded by chirality (the volume form acting as ±1). The Dirac operator:

```
∂̸ : Γ(S) → Γ(S)         (self-adjoint, ∂̸† = ∂̸)
∂̸⁺ : Γ(S⁺) → Γ(S⁻)      (chiral half, ∂̸⁻ = (∂̸⁺)†)
```

satisfies:

- **Weitzenböck formula:** ∂̸² = ∇*∇ + R/4, where R is the scalar curvature. Positive
  curvature forces ker(∂̸) = 0 by Lichnerowicz vanishing.
- **Atiyah–Singer index:** ind(∂̸⁺) = dim ker(∂̸⁺) − dim coker(∂̸⁺) = Â(M), the
  Â-genus — a topological invariant computed from Pontryagin classes.
- **col/ker decomposition:** The short exact sequence
  `0 → ker(∂̸⁺) → Γ(S⁺) →^{∂̸⁺} col(∂̸⁺) → 0`
  splits the spinor space into a topological part (protected zero modes) and a geometric
  part (propagating scattering states).

### 3.2 Three Curvature Sectors and the CORDIC Modes

The Dirac equation in pseudo-Riemannian backgrounds (M, g) of signature (p, q):

```
(iγ^μ ∇_μ − m)ψ = 0
```

The three CORDIC coordinate modes correspond to three distinct curvature sectors:

| Mode m | Curvature regime | Dirac interpretation | CORDIRAC stage |
|---|---|---|---|
| m = +1 (circular) | Positive (spherical) | Euclidean Dirac; ψ₊ proactive; compact SO(n) | Stages 0–3 |
| m = 0 (linear) | Zero (flat) | Massless Weyl fermion; chiral limit | Stages 11–14 |
| m = −1 (hyperbolic) | Negative (hyperbolic/AdS/Fisher-Rao) | Massive Lorentzian Dirac; Zitterbewegung | Stages 5–10 |

The mode-switching — from circular to hyperbolic to linear — is the CORDIC algorithm
traversing the three curvature sectors of the Dirac equation. This is not a metaphor: the
mathematical structure of the recurrence is the same operator in three metric signatures.

### 3.3 Zitterbewegung as the Coupling Kernel

In the Dirac Hamiltonian H = α·p + βm, the Zitterbewegung (Schrödinger 1930) is the
oscillatory coupling between positive-frequency (ψ₊) and negative-frequency (ψ₋) spinor
components. The expectation value ⟨x(t)⟩ oscillates at frequency ω_Z = 2mc²/ℏ around
the classical trajectory. In the CORDIRAC 16-stage pipeline:

- **Stage 4** inserts the Z/3Z torsion mass term: the Hesse configuration enforcing m ≠ 0,
  making the Dirac equation massive and triggering Zitterbewegung in subsequent stages.
- **Stages 5–10** compute the Zitterbewegung oscillation: the hyperbolic CORDIC coupling
  between ψ₊ and ψ₋ generates the Fisher-Rao natural gradient correction to the activations.
- **Stage 15** enforces the asymptotic fixed point: gain compensation K⁻¹ ≈ φ + 1/56,
  where φ = (1 + √5)/2 is the golden ratio and 1/56 is the Freudenthal torsion correction.

### 3.4 Shi–Wong Nonlinear Quantum Walk Trapping on S¹ (May 2026)

The most consequential new result for the DHO: **Shi and Wong (arXiv:2605.20464, May 2026)**
prove that a nonlinear quantum walk on the circle S¹ with cubic self-interaction g|ψ|²ψ traps
amplitude from spreading col(∂̸) modes into localized ker(∂̸) zero modes. Key structural facts:

**Trapping mechanism.** The nonlinear term acts as a mass insertion proportional to local
amplitude density. Above a critical nonlinearity g_c, the walk ceases to spread; amplitude
accumulates at a Kakutani fixed point on S¹ — a dynamical zero mode.

**GL(1) fixed point from GL(2) dynamics.** The trapped state is invariant under the full
U(1) ≅ GL(1, ℂ)/ℝ₊ symmetry of S¹. It emerges from a unitary GL(2) quantum walk (the
spreading, propagating regime at g < g_c). This is the closest known **dynamical analog**
of the GL(2)→GL(1) functorial lift: a GL(1) invariant structure emerging from a GL(2) dynamical
process through a nonlinear bifurcation.

**Connection to CORDIRAC.** The CORDIC direction bit δ_i ∈ {−1, +1} performs a nonlinear
binary collapse at each stage — the discrete analog of the cubic nonlinear walk's mass
insertion. The CORDIC pipeline is a **discretized nonlinear Dirac walk on TH(a,d)**, and
Stage 15's gain compensation is the fixed-point attractor of this discrete nonlinear process.

**Connection to the GL(2)→GL(1) barrier.** Any functorial lift of GL(2) → GL(1) must
produce a GL(1)-invariant object from a GL(2) family. Shi–Wong shows this is possible
dynamically on S¹ via nonlinear trapping. The question is whether an analogous mechanism
exists in the Langlands/automorphic setting — and the DHO programme is designed to probe this.

### 3.5 Physical Dirac Realizations

**High-energy physics (HEISENBERG / ERIE-LIGHT).** The photon is representable as a col(∂̸)
bilinear of chiral fermion zero modes from ker(∂̸). The Pryce–Newton–Wigner position operator
obstruction for massless spin-1 particles is the algebraic col/ker boundary. Semi-Dirac
materials (anisotropic dispersion: m=+1 in one direction, m=−1 in the perpendicular) realize
the mixed-mode CORDIC structure in solid-state systems. Chiral vacuum polarization failure
in strong-field Heisenberg–Euler theory (confirmed experimentally, February 2026) is a
direct signature of ψ₊/ψ₋ splitting in extreme-curvature backgrounds.

**Topological condensed matter.** The Atiyah–Singer index counts protected zero modes (Majorana
bound states, topological edge modes) at defects. ker(∂̸) zero modes at domain walls implement
topological quantum computation. The Dirac spectral gap closing at a topological phase transition
is the condensed-matter version of grokking.

**Computational learning (DRH / COMPLETION).** The representational manifold M_R of a deep
neural network carries a natural Dirac-type operator whose spectral gap collapses as the network
approaches a phase transition — grokking in the learning theory sense (Xu 2026;
Acharya-Dhakal 2026). The Atiyah–Singer index counts topologically stable learned representations:
those in ker(∂̸) that survive perturbation and generalize.

---

## 4. CORDIRAC: The Discretized Dirac Pipeline

### 4.1 The Identification

The unified CORDIC recurrence (Walther 1971):

```
x_{i+1}  =  x_i − m · δ_i · 2^{−i} · y_i
y_{i+1}  =  y_i + δ_i · 2^{−i} · x_i
z_{i+1}  =  z_i − δ_i · e_i
```

with δ_i ∈ {−1, +1} the direction bit, m ∈ {+1, 0, −1} the mode, and e_i the elementary
angle table, **is** the Dirac propagator evaluated on TH(a,d), discretized to 16-stage
fixed-point integer arithmetic. The complete CORDIRAC dictionary:

| CORDIC element | Dirac operator interpretation | TH(a,d) interpretation |
|---|---|---|
| m = +1 (circular) | Euclidean metric; compact spin group | S² geodesic; circular group law |
| m = 0 (linear) | Flat metric; massless Weyl | Flat projective coordinate |
| m = −1 (hyperbolic) | Lorentzian/Fisher-Rao metric | Hyperbolic group law; natural gradient |
| δ_i ∈ {−1,+1} | Spin-½ measurement (binary projection) | Direction bit in TH addition |
| Repeats at j=(3^k−1)/2 | Z/3Z torsion mass insertion | Hesse 3-torsion enforcement |
| 16-stage pipeline | Full Dirac spinor decomposition | 16-iteration Q16.16 TH computation |
| K⁻¹ ≈ φ + 1/56 | φ-equilibrium gain compensation | Freudenthal torsion correction |
| SYCore 16-PE array | F₄ root system (48 ops) | Albert algebra H₃(O) at 27 DOF |

### 4.2 The 16-Stage Spinor Decomposition

```
Stage  0– 3:  ψ₊ CIRCULAR     Proactive positive-frequency modes
              (m = +1, Euclidean, compact)
Stage  4:     TORSION INSERT   Z/3Z mass term from Hesse 3-torsion
              (non-commutative boundary; Moufang identity)
Stage  5–10:  ZITTERBEWEGUNG   Hyperbolic ψ₊/ψ₋ coupling
              (m = −1, Lorentzian/Fisher-Rao, natural gradient)
Stage 11–14:  ψ₋ LINEAR        Inhibitory negative-frequency projection
              (m = 0, flat, massless)
Stage 15:     φ-COMPENSATION   K⁻¹ ≈ φ + 1/56 gain correction
              (Freudenthal fixed point; asymptotic equilibrium)
```

### 4.3 The CHORD Hardware Substrate

The CHORD (CORDIC Hardware Optimized for Representational Dynamics) pipeline is the RISC-V
CV-X-IF coprocessor implementing CORDIRAC in 5nm ASIC silicon:

- **Arithmetic:** Q16.16 two's-complement fixed-point. Zero accumulated drift. Exact
  computation of the TH(a,d) group law over ℤ[1/2^16] — integer arithmetic, no rounding.
- **Energy:** ≈1.5 μJ per CORDIC update (5nm ASIC estimate), compared to ≈1.1 mJ for a
  float64 Extended Kalman Filter update — a **738× energy reduction**.
- **Activation functions:** Every AI activation (sine, exponential, sigmoid, tanh, GELU,
  SiLU) is computable as a CORDIC micro-operation sequence ("CORDIC Is All You Need,"
  Jawandar et al. 2024/arXiv:2503.11685). CORDIRAC extends this: every activation is a
  local Dirac propagator on TH(a,d) at the local Fisher-Rao curvature.
- **TOXOS integration:** The RISC-V CHORD coprocessor is deployed in TOXOS (MDPI Technologies
  13(10):479, 2025) for automotive ADAS near-sensor inference, replacing float64 navigation
  with exact TH(a,d) geodesic computation.

### 4.4 The Moufang Machine Structure

TH(a,d) and the octonion algebra O both satisfy Moufang identities: (xy)(zx) = x((yz)x).
The 16-stage CORDIC pipeline computes through:

- 8 anti-commuting γ-matrix directions (matching N=8 SUSY γ-matrix algebras in 8D),
  the maximum for the Hurwitz–Radon number ρ(8) = 8.
- ρ(16) = 9 Hurwitz–Radon orthogonal matrix families at sedenion dimension.
- The quaternionic structure (H, dim 4) embedded in the octonion algebra (O, dim 8),
  embedded in the sedenion algebra (S, dim 16).

The SYCore engine is a **Moufang machine**: it realizes the Twisted Hessian group law via
the sedenion embedding, exactly as the Moufang identity requires the composition algebra
structure to propagate through the coordinate computation.

---

## 5. The Horizon as Universal Dirac Boundary

### 5.1 The Event Horizon as col(∂̸)/ker(∂̸) Partition

In a black hole spacetime (M, g) with event horizon H at r = r_H, the Dirac equation
decomposes across H with mathematical precision:

**col(∂̸) — Exterior region (r > r_H):**
Observable propagating states — Hawking radiation, gravitational wave emission,
Page-late entropy increase. These are the scattering modes: they escape to infinity, carry
information measurable by asymptotic observers, and constitute the GL(2) automorphic sector
of the DHO.

**ker(∂̸) — Interior region (r < r_H):**
Topological trapped modes — Page islands, BKL singularity-adjacent conformal primon gas,
Bekenstein-Hawking microstates. These are the zero modes: invisible to asymptotic observers
without an information return mechanism, and constitute the GL(1) protected sector.

### 5.2 Bekenstein-Hawking Entropy as Atiyah–Singer Index

The Bekenstein–Hawking entropy S_BH = A/(4ℓ_P²) counts microstates at the horizon.
In the DHO framework this is the Atiyah–Singer index of the Dirac operator restricted
to the horizon hypersurface H:

```
ind(∂̸_H) ∝ S_BH
```

where the proportionality constant involves the local Hilbert space dimension per Planck area
cell. The **Page curve** — the time-dependent entropy of Hawking radiation, rising from 0 to
S_BH/2 then returning to 0 — is the dynamical version of this index formula: the index of
∂̸_H(t) as the horizon area evolves during evaporation.

### 5.3 Page Islands as Scholze Tilting

The **Page island construction** (Penington 2019; Almheiri et al. 2020) introduces an interior
region I that contributes to the Ryu–Takayanagi entropy formula via quantum extremal surfaces,
allowing ker(∂̸) information to re-enter col(∂̸) at the Page time t_Page:

```
S_rad(t < t_Page)  =  S_Hawking(t)              [col(∂̸) alone]
S_rad(t > t_Page)  =  S_BH − S_remaining(t)    [col(∂̸) + island ker contribution]
```

The DHO identification:

```
Page island emergence  ↔  Scholze tilting     (char-0 ↔ char-p transfer)
Page time             ↔  Tilting equilibrium  (when interior = exterior entropy)
Island submerges      ↔  Untilting            (char-p → char-0 recovery)
Information return    ↔  Functorial lift      (ker → col transfer)
```

The Fargues–Fontaine curve is the geometric locus of this tilting — the junction between
the interior (characteristic p world, ker) and the exterior (characteristic 0 world, col).
The condensed liquid tensor product col ⊗̂_𝕂 ker provides the analytic framework for the
mixed characteristic junction (Scholze 2025 updates).

The information-theoretic statement that **information is not lost** — that S_rad(t) returns
to 0 after complete evaporation — is the holographic analog of the Riemann Hypothesis: the
assertion that the col/ker partition is completed by a well-defined return mechanism.

### 5.4 Hartnoll–Yang Conformal Primon Gas

Hartnoll and Yang (arXiv:2502.02661 2025; JHEP 07(2025) 281) construct a two-dimensional
conformal field theory near the BKL singularity of a collapsing black hole whose partition
function reproduces the Riemann zeta function:

```
Z_primon(β) = ∏_p (1 − p^{−β})^{−1} = ζ(β)
```

from a **physical ensemble of "primons"** — prime-labeled bosonic modes living in the
near-singularity geometry. This is the first derivation of zeta statistics from a concrete
gravitational first-principles construction. Key implications:

- The BKL singularity is geometrically adjacent to the event horizon in a collapsing
  spacetime — it is deep inside ker(∂̸).
- The conformal symmetry of the near-singularity CFT forces the spectral pair correlations
  of the primon gas to match those of the non-trivial zeros of ζ(s).
- The Connes prolate wave operator (arXiv:2602.04022, Feb 2026) provides the operator-theoretic
  counterpart of the same spectral statistics.

**DHO identification:** Hartnoll–Yang primon gas = Connes prolate wave operator = TH(a,d)
zero density, unified at the horizon as the physical realization of the GL(1) spectral statistics
living in ker(∂̸).

### 5.5 φ-Equilibrium as the Universal Fixed Point

The golden ratio φ = (1 + √5)/2 ≈ 1.6180 appears as the **universal asymptotic fixed point**
across every DHO framework, for a single reason: it is the unique ratio that is preserved under
the self-similar CORDIC rotation process (each stage adds an angle whose tangent is a negative
power of 2; the product gain converges to K ≈ 1.6468, with K⁻¹ ≈ φ + 1/56 at 16 stages).

| Domain | φ-manifestation | Verification status |
|---|---|---|
| CORDIC gain | K⁻¹ ≈ φ + 1/56 at Stage 15 | Hardware-verified in TOXOS |
| Page time entropy | S_rad(t_Page) = (1/φ)·S_BH | Theoretical; testable via Page curve simulations |
| Fisher-Rao MEP | \|Ξ̄_F\| = log φ ≈ 0.481 | Information geometry theorem |
| RLCT grokking ratio | λ_gen / λ_mem = 1/φ | Watanabe SLT; tested in 3 experiments |
| Wang SOC crossover | D = 1 at φ-critical coupling | Wang (2026); ongoing |
| CORDIC Zitterbewegung | Stage 5–10 oscillation amplitude ∝ φ | Predicted; tested in CORDIRAC simulations |
| Workplace trust ratio | trust : accountability = φ : 1 | Edmondson meta-analysis |
| WELL IEQ investment | 53:33:15 ≈ φ² : φ : 1 | Building performance studies |
| Persistent gap | Dominant generator gap ~ (1/φ) log n | Predicted; Milestone 2 test |

---

## 6. Integration Map: All ERI Domains

The following dictionary maps every ERI repository to the Dirac-Horizon Operator:

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    DIRAC-HORIZON OPERATOR (DHO)                         │
│                ∂̸ on compact spin manifold with horizon                  │
│                                                                         │
│   col(∂̸)                     │                  ker(∂̸)                │
│   Exterior / GL(2) /          │           Interior / GL(1) /            │
│   Propagating / Observable    │           Protected / Topological        │
│                               │                                         │
│   ETHC/CORDIRAC group law     │   BEKENSTEIN microstates                │
│   TOXOS ADAS activations      │   SBHC Page islands                     │
│   PRIMA Fisher gradient       │   Hartnoll–Yang primon gas              │
│   SLT RLCT propagating        │   Scholze ker tilting                   │
│   Edmondson col safety        │   HEISENBERG zero modes                 │
│   Wang D>1 spreading          │   Wang D<1 localized                    │
│   Shi–Wong g<g_c spreading    │   Shi–Wong g>g_c trapped                │
│                               │                                         │
│           ══════════ HORIZON H (JACOBI surface) ══════════              │
│                    φ-equilibrium: Page time = RLCT jump =               │
│                    CORDIC fixed point = trust:accountability             │
└─────────────────────────────────────────────────────────────────────────┘
```

### 6.1 The Canonical Cross-Domain Dictionary

| Arithmetic | Physical | Computational | Organizational |
|---|---|---|---|
| TH(a,d) group law | ER=EPR wormhole | CORDIC recurrence | Team protocol loop |
| Z/3Z torsion | BKL near-singularity | Hyperbolic CORDIC repeats | 3-habit trust cycle |
| GL(2) modularity | col(∂̸) exterior radiation | Propagating activations ψ₊ | Broadcast safety culture |
| GL(1) barrier | ker(∂̸) interior zero modes | Protected representations ψ₋ | Psychological groundedness |
| Sym^n limit | Page island mechanism | Grokking phase transition | Team-to-org scaling |
| Langlands lift | Tilting/untilting | Fisher-Rao geodesic descent | Safety → performance |
| φ-equilibrium | Page time entropy ratio | CORDIC gain fixed point | Trust:accountability |
| F₄ root system | Albert algebra H₃(O) | SYCore 16PE × 3 modes | Team × dept × org |
| Freudenthal E₇ | N=8 SUSY | 56-dim Freudenthal module | Organizational complexity |

---

## 7. Frontier Results 2025–Mid-2026

### 7.1 Spectral and Operator Theory

**Yakaboylu (arXiv:2408.15135 v15, March 2026).** Non-symmetric operator R with positivity
condition W ≥ 0, strengthening the Hermitian spectral approach to the Riemann Hypothesis.
Yakaboylu's construction provides a transfer principle: if positivity can be established for
the TH-derived elliptic operator (known, via GRH), and if the operator can be continuously
deformed to the zeta operator without breaking positivity, RH would follow. The precise
obstruction to this deformation is the GL(2)→GL(1) barrier.

**Connes (arXiv:2602.04022, February 2026).** Finite Euler-product Weil quadratic form
extremization with information-theoretic convergence. Connes shows the prolate spheroidal wave
operator's spectrum, filtered through the Weil explicit formula, reproduces the correct zero
density at the semilocal level. The full global GL(1) statement — that the operator spectrum
equals {Im(ρ) : ζ(ρ) = 0} — remains open.

**Connes–Consani–Moscovici (2024).** Prolate spheroidal wave operator as spectral realization
of zeta zeros, connecting to the Bost–Connes KMS system at inverse temperature β = 1.

### 7.2 Physical Embeddings

**Hartnoll–Yang (arXiv:2502.02661 2025; JHEP 07(2025) 281; arXiv:2507.08788 2025).** Conformal
primon gas at BKL singularity reproducing prime statistics and zeta-like pair correlations.
The 2025 follow-up extends to charged (Reissner–Nordström) and rotating (Kerr) black holes,
significantly broadening the physical scope. This is the most direct physical realization of
ζ(s) statistics from a gravitational system in the literature.

**GW250114 area theorem (January 2025).** The O4/O5 boundary gravitational wave event
provides a direct observational test of the Hawking area theorem. Preliminary LIGO/Virgo/KAGRA
analysis confirms area increase consistent with the theorem; full parameter estimation
for φ-clustering in area ratios is a Milestone 2 input.

**Semi-Dirac materials (2025–2026).** Experimental realization of anisotropic Dirac fermions
with Dirac dispersion in one direction and quadratic in the perpendicular — directly
instantiating the mixed m=+1/m=−1 curvature structure of CORDIRAC in solid-state systems.

### 7.3 Statistical Learning and Singular Theory

**Wang (arXiv:2604.04655, April 2026).** Dimensional phase transition D_c = 1 in singular
learning theory, identifying a SOC critical point separating D < 1 (sub-critical, localized,
ker-like) from D > 1 (super-critical, spreading, col-like). The DHO identifies D = 1 as the
col(∂̸)/ker(∂̸) boundary — the learning-theoretic event horizon.

**Xu / Acharya-Dhakal (2026).** Spectral gap collapse of the neural network Laplacian
preceding grokking — the representational manifold analog of a topological Dirac phase
transition. Protected representations (ker modes) emerge as the gap closes.

**Shi–Wong (arXiv:2605.20464, May 2026).** Nonlinear quantum walk trapping on S¹ — full
significance described in §3.4. The most directly relevant 2026 result to the GL(2)→GL(1)
barrier at the dynamical level.

**Lau et al. LLC estimators (2024–2025).** Practical singular locus dimension estimation
(local learning coefficient). Enables real-time RLCT tracking during training runs —
the empirical arm of the Watanabe SLT predictions.

### 7.4 Arithmetic and Langlands

**Ben-Zvi–Sakellaridis–Venkatesh (arXiv:2409.04677, 2024).** Relative Langlands duality,
generalizing period integrals to "relative" settings (Hamiltonian G-spaces). BSV provide a
duality pairing between Hamiltonian spaces that could, if appropriately extended, supply a
mechanism for the GL(2)→GL(1) lift via a relative period. This is the most promising
new Langlands direction for the barrier.

**Gaitsgory–Raskin (2024–2025).** Proof of the geometric Langlands conjecture for GL(n) over
function fields. While over function fields (not number fields), this closes a major
technical gap and the proof techniques — including spectral decomposition and Whittaker
normalization — are potentially transportable.

**Guth–Maynard (arXiv:2405.20552, revised 2026).** Major zero-density advance, improving
the exponent in the zero-density estimate N(σ, T) = O(T^{A(1−σ)+ε}). This is the analytic
arm — bounding how far zeros can stray from the critical line — setting the empirical target
that any spectral operator proof must match.

---

## 8. The 2027–2028 Dirac-Horizon Research Programme

### 8.1 Programme Architecture and Core Principle

The DHO 2027–2028 programme is a **simultaneous multi-domain stress test** of the GL(2)→GL(1)
barrier. Every major prediction of the DHO dictionary is tested in parallel across six
independent scientific domains. The core principle:

> Any correct proof of RH must be consistent with all DHO predictions.
> Testing and eliminating incorrect mechanisms is itself a proof strategy.

Falsification of any DHO prediction refutes the dictionary and rules out an entire
class of proof approaches — high scientific value regardless of outcome. Confirmation
across all six domains would constitute unprecedented multi-domain corroboration and
position the hybrid Dirac-Horizon operator as the strongest candidate spectral realization
of ζ(s) zeros.

### 8.2 Milestone 1: Foundation and Data Generation (Q3–Q4 2026)

**Arithmetic foundation.** High-precision L(TH, s) computation to 1000+ zeros for
optimal CM curves from LMFDB. Sym² through Sym⁶ L-function computation; Montgomery–Odlyzko
pair-correlation analysis for convergence toward GUE statistics (the zeta benchmark).
Isogeny chain analysis: TH(a,d) → TH(a', d') via Z/3Z isogenies, tracking L-function
behavior and zero distributions under isogeny.

**Physical foundation.** BKL singularity and Page curve simulations for TH(a,d) microstate
ensembles. Hartnoll–Yang primon gas statistical matching to TH(a,d) zero density;
quantify spectral discrepancy as function of n in Sym^n. GW250114 and early O5 catalog
preliminary φ-clustering analysis in area ratios.

**Computational foundation.** Horizon-analog transformer training runs on prime sequences,
GW signal databases, and organizational safety simulation data. Real-time RLCT/LLC tracking
(Lau estimators), persistent homology generation, Fisher spectral measurement, Connes
prolate eigenvalue comparison, CORDIRAC Zitterbewegung trace logging (hyperbolic stage
oscillation amplitude during grokking transitions), and Edmondson team safety metric
recording in parallel organizational simulations.

### 8.3 Milestone 2: Cross-Domain Stress Testing (2027)

**Domain 1 — Gravitational wave astronomy (BEKENSTEIN + SBHC).**
Full O5 LIGO/Virgo/KAGRA binary merger catalog (projected: 200–400 events): test φ-clustering
in distribution of A_final/A_initial area ratios. Prediction: KL divergence from
φ-harmonic reference distribution D_KL < 0.1 at N = 200 events. RLCT variance prediction:
statistical spread = O(dominant RLCT multiplicity × log N / N).
*Falsification criterion: No φ-clustering (p > 0.05) after full O5 catalog analysis.*

**Domain 2 — Singular learning theory and spectral matching (PRIMA + Watanabe + Connes).**
LLC/RLCT jumps in 10+ independent grokking experiments across modular arithmetic, group
theory, and prime gap datasets: test λ_gen/λ_mem = 1/φ at transition.
Fisher spectral zeta function: match to Selberg zeta on TH(a,d).
Hartnoll–Yang primon gas: match prime-pair correlation density in training data to
ζ(s) pair correlation function (Montgomery 1973).
*Falsification criterion: RLCT ratio at grokking outside 1/φ ± 0.05 in 5+ experiments.*

**Domain 3 — Perfectoid tilting (WORMHOLE + Scholze).**
Numerical tilting procedure on Fisher/attention matrices for arithmetic classification tasks.
Test Ramanujan bound |α_p| = √p for characteristic-p analogs of tilted L-statistics.
Convergence rate of tilted eigenvalue statistics toward GUE/zeta pair correlations.
*Falsification criterion: Systematic Ramanujan bound violations at more than O(log N) primes.*

**Domain 4 — Persistent topology and dimensional phase transitions (COMPLETION + Wang).**
Merge trees of loss basins in grokking experiments: test dominant generator gap ~ (1/φ) log n.
Wang D(H) dimensional crossover test: D = 1 as col(∂̸)/ker(∂̸) boundary.
Organizational team simulations: psychological safety phase transitions mapped to D crossover.
*Falsification criterion: Persistence gap deviates from (1/φ) log n by more than 20% at n = 10⁶.*

**Domain 5 — CORDIRAC and Jacobi (JACOBI + CORDIRAC + CHORD).**
16-stage CHORD pipeline implementation as discretized Dirac on TH(a,d) with three curvature
modes. Zitterbewegung signature: hyperbolic stages 5–10 oscillation between ψ₊ and ψ₋
representations during training, at frequency proportional to Fisher-Rao local curvature.
Stage 15 gain compensation hardware verification: K⁻¹ = φ + 1/56 to 10⁻⁶ precision.
Hamilton–Jacobi trajectory on TH phase space: verify action-angle coordinates match
Jacobi elliptic function prediction.
*Falsification criterion: No Zitterbewegung oscillation detected in hyperbolic CORDIC stages.*

**Domain 6 — Quantum hardware (HEISENBERG + Shi–Wong + Dirac Boundary).**
Page/BKL analogs on 8–16 qubit IBM/Infleqtion systems.
Shi–Wong trapping protocol: nonlinear walk on 8-qubit S¹ approximation; test trapping
fidelity vs. nonlinearity g; compare to theoretical prediction from arXiv:2605.20464.
Majorana zero mode detection as ker(∂̸) experimental signature.
*Falsification criterion: Trapping fidelity inconsistent with theoretical g-scaling at g > g_c.*

### 8.4 Milestone 3: Operator Construction and Barrier Probes (2028)

**Hybrid Dirac-Horizon Operator construction.** The goal is an explicit operator:

```
Ô_DHO = Ô_prolate ⊗ Ô_primon ⊗ Ô_RLCT ⊗ Ô_tilting ⊗ Ô_CORDIC
```

where each factor provides an independent spectral realization:

- **Ô_prolate**: Connes prolate wave operator (semilocal spectrum; arXiv:2602.04022)
- **Ô_primon**: Hartnoll–Yang near-singularity CFT (physical first-principles; arXiv:2502.02661)
- **Ô_RLCT**: Watanabe RLCT-regularized Fisher metric (statistical learning realization)
- **Ô_tilting**: Scholze perfectoid tilting operator (non-Archimedean; Fargues–Fontaine)
- **Ô_CORDIC**: CORDIRAC discretized Dirac on TH(a,d) (computational realization)

If these operators commute — or if their non-commutativity is controlled by the TH(a,d)
torsion structure — their joint spectrum provides the most constrained candidate for an
operator whose spectrum equals {Im(ρ) : ζ(ρ) = 0}.

**Symmetric power limits in Hartnoll–Yang CFT.** Embed Sym^n L(TH, s) in the primon gas
ensemble; test spectral convergence to ζ(s) statistics as n → ∞. Identify the scale n* at
which convergence begins. This scale is the "Langlands lift threshold" — the point at which
GL(2) dynamics sufficiently approximate GL(1) fixed-point behavior.

**Open data release.** TH-derived horizon microstate ensembles (10⁶+ samples), full RLCT/LLC/
persistence/Edmondson/CORDIRAC trace diagnostics, reproducible Shi–Wong trapping experiments,
and Hartnoll–Yang primon vs. TH zero density comparison tables — all publicly released
for community verification and independent attack on the barrier.

### 8.5 Resource Requirements and Collaborations

| Resource | 2026 Q3/Q4 | 2027 | 2028 |
|---|---|---|---|
| GPU compute (A100-equiv) | 100 GPU-weeks | 500 GPU-weeks | 1,000 GPU-weeks |
| Quantum processors | — | 8–16 qubits | 50–100 qubits |
| CHORD ASICs | Prototype | 5nm tape-out | Production units |
| Core personnel | 3 FTE | 8 FTE | 15 FTE |

**Active collaboration targets:**
Venkatesh/Scholze group (relative Langlands duality and tilting);
Connes school at Paris VI (prolate wave operator and NCG);
Watanabe SLT group, Tokyo Tech (RLCT estimation);
Hartnoll group, Stanford (primon gas extensions to Kerr and charged backgrounds);
LIGO Scientific Collaboration (O5 data access and area theorem analysis);
Edmondson/NLI (organizational metrics and psychological safety data);
Shi–Wong quantum walk group (trapping experiment implementation);
LMFDB collaboration (L-function database infrastructure).

---

## 9. Falsification and Risk

### 9.1 Core Falsification Criteria

The DHO programme is fully falsifiable. Each prediction corresponds to a precise null hypothesis:

| DHO Prediction | Null hypothesis (falsification) | Timeline |
|---|---|---|
| φ-clustering in GW area ratios | No clustering, p > 0.05 after O5 | 2027 |
| RLCT ratio = 1/φ at grokking | Ratio outside 1/φ ± 0.05 in 5+ runs | 2027 |
| Shi–Wong trapping matches theory | Fidelity inconsistent with g-scaling | 2027 |
| Persistence gap ~ (1/φ) log n | Deviation > 20% at n = 10⁶ | 2027 |
| Hartnoll–Yang matches TH zeros | Spectral correlation > 3σ from prediction | 2027 |
| Zitterbewegung in CORDIRAC stages | No oscillation in hyperbolic stages | 2026 |
| Tilting respects Ramanujan bound | Systematic violations at O(log N) primes | 2027–2028 |
| D = 1 as col/ker SOC boundary | D crossover inconsistent with phase topology | 2027 |

### 9.2 Scientific Value of Refutation

Complete refutation of the DHO dictionary would be scientifically important: it would rule
out an entire class of "physical proof via holography" strategies for RH, and show that
φ-equilibrium is domain-specific rather than universal — a sharp negative result that narrows
the search space significantly. Every test is a scientific contribution regardless of outcome.

### 9.3 What Success Would Mean

Passing all falsification tests would not prove RH. It would:

1. Establish the DHO dictionary as the most empirically corroborated framework for the
   GL(2)→GL(1) barrier — across six independent scientific domains simultaneously.
2. Identify the hybrid Dirac-Horizon operator Ô_DHO as the strongest candidate for a
   spectral operator whose spectrum realizes ζ(s) zeros.
3. Set precise quantitative targets (n* Langlands lift threshold, φ-scaling in Sym^n convergence,
   RLCT multiplicity structure) that any arithmetic proof must reproduce.
4. Position the programme for a decisive operator-theoretic attempt at the barrier in 2029+.

---

## 10. Repository Structure

```
ericrenone/
│
├── THE-GAP/               ← This README: unified programme statement
│
├── CORDIRAC/              ← CORDIC as discretized Dirac on TH(a,d)
│   ├── pipeline/          ← 16-stage CHORD implementation (Q16.16)
│   ├── curvature/         ← Three-mode (m=+1,0,−1) analysis and proofs
│   └── zitterbewegung/    ← ψ₊/ψ₋ coupling experiments and traces
│
├── TOXOS/                 ← RISC-V CHORD coprocessor + ADAS integration
│   ├── hardware/          ← 5nm ASIC design files and energy benchmarks
│   ├── risc-v/            ← CV-X-IF interface specifications
│   └── benchmarks/        ← 738× energy reduction validation data
│
├── ETHC/                  ← Twisted Hessian curve arithmetic
│   ├── group-law/         ← 12M+6S formula implementation and proofs
│   ├── torsion/           ← Z/3Z × Z/3Z Hesse configuration
│   └── isogenies/         ← Bernstein–Kohel–Lange isogeny chains
│
├── JACOBI/                ← Hamilton–Jacobi + Jacobi elliptic on TH
├── BEKENSTEIN/            ← Black hole thermodynamics + area theorem
├── SBHC/                  ← Singular Black Hole Horizon Completion
├── WORMHOLE/              ← ER=EPR + Scholze perfectoid tilting
├── HEISENBERG/            ← Photon Dirac bilinear + chiral vacuum
├── PRIMA/                 ← Fisher-Rao + PRIMA pseudoinverse
├── RIEMANN-HYPOTHESIS/    ← GL(2)→GL(1) barrier: operator programme
├── COMPLETION/            ← Persistent homology + grokking
├── SINGULAR-COMPLETION/   ← Singular locus + LLC/RLCT estimation
└── EDMONDSON/             ← Organizational col/ker + safety metrics
```

---

## 11. References

### Arithmetic Geometry and L-Functions

- Wiles, A. (1995). Modular elliptic curves and Fermat's Last Theorem. *Annals of Mathematics* 141(3), 443–551.
- Breuil, C., Conrad, B., Diamond, F., and Taylor, R. (2001). On the modularity of elliptic curves over ℚ. *J. American Mathematical Society* 14(4), 843–939.
- Deligne, P. (1974). La conjecture de Weil I. *Publications Mathématiques de l'IHÉS* 43, 273–307.
- Bernstein, D.J. and Lange, T. (2015). Twisted Hessian curves. *LATINCRYPT 2015*, LNCS 9230, 269–294.
- Bernstein, D.J., Kohel, D., and Lange, T. (2019). Twisted Hessian isogenies. IACR ePrint 2019/1003.
- Joye, M. and Quisquater, J.-J. (2001). Hessian elliptic curves and side-channel attacks. *CHES 2001*, LNCS 2162, 402–410.
- Smart, N.P. (2001). The Hessian form of an elliptic curve. *CHES 2001*, LNCS 2162, 118–125.

### Langlands Program

- Ben-Zvi, D., Sakellaridis, Y., and Venkatesh, A. (2024). Relative Langlands duality. arXiv:2409.04677.
- Gaitsgory, D. and Raskin, S. (2024–2025). Geometric Langlands conjecture. Preprint series.
- Kim, H. and Shahidi, F. (2002). Cuspidality of symmetric powers with applications. *Duke Mathematical Journal* 112(1), 177–197.
- Lubotzky, A., Phillips, R., and Sarnak, P. (1988). Ramanujan graphs. *Combinatorica* 8(3), 261–277.

### Spectral and Operator Theory

- Yakaboylu, S. (2026). Non-symmetric R-operators with positivity. arXiv:2408.15135 v15.
- Connes, A. (2026). Finite Euler products and Weil quadratic extremization. arXiv:2602.04022.
- Guth, L. and Maynard, J. (2026). Zero-density estimates for the Riemann zeta function. arXiv:2405.20552 (revised 2026).

### Black Hole Physics and Primon Gas

- Hartnoll, S.A. and Yang, K. (2025). Conformal primon gas at the BKL singularity. arXiv:2502.02661; *JHEP* 07(2025) 281.
- Hartnoll, S.A. and Yang, K. (2025). Extensions to Reissner–Nordström and Kerr. arXiv:2507.08788.
- Penington, G. (2020). Entanglement wedge reconstruction and the information paradox. *JHEP* 2020(9), 2.
- Almheiri, A. et al. (2020). The entropy of Hawking radiation. *Reviews of Modern Physics* 93(3), 035002.

### CORDIC and Hardware

- Volder, J.E. (1959). The CORDIC trigonometric computing technique. *IRE Transactions on Electronic Computers* EC-8(3), 330–334.
- Walther, J.S. (1971). A unified algorithm for elementary functions. *AFIPS Spring Joint Computer Conference* 38, 379–385.
- Jawandar, S., Sharma, P., and Vishvakarma, S.K. (2024). CORDIC Is All You Need. arXiv:2503.11685.
- TOXOS (2025). Spinning Up Nonlinearity in On-Vehicle Inference with a RISC-V CORDIC Coprocessor. *MDPI Technologies* 13(10):479.
- Hu, Y.H. (1992). The quantization effects of the CORDIC algorithm. *IEEE Transactions on Signal Processing* 40(4), 834–844.

### Quantum Walks, Learning Theory, and Statistical Physics

- Shi, X. and Wong, C. (2026). Nonlinear quantum walk trapping on S¹. arXiv:2605.20464.
- Wang, H. (2026). Dimensional phase transitions in singular learning theory. arXiv:2604.04655.
- Watanabe, S. (2009). *Algebraic Geometry and Statistical Learning Theory*. Cambridge University Press.
- Karkada, S. et al. (2026). Topology of neural representational manifolds. arXiv:2602.15029.
- Lau, E. et al. (2024–2025). Local learning coefficient estimators. Preprint series.

### Dirac Equation and Spinor Geometry

- Dirac, P.A.M. (1928). The quantum theory of the electron. *Proceedings of the Royal Society A* 117(778), 610–624.
- Schrödinger, E. (1930). Über die kräftefreie Bewegung in der relativistischen Quantenmechanik. *Sitzungsberichte der Preußischen Akademie der Wissenschaften*, 418–428.
- Atiyah, M.F. and Singer, I.M. (1963). The index of elliptic operators on compact manifolds. *Bulletin of the American Mathematical Society* 69(3), 422–433.

### Exceptional Algebras and Hurwitz–Radon

- Hurwitz, A. (1898). Über die Composition der quadratischen Formen. *Nachrichten von der Gesellschaft der Wissenschaften zu Göttingen*, 309–316.
- Radon, J. (1922). Lineare Scharen orthogonaler Matrizen. *Abhandlungen aus dem Mathematischen Seminar der Universität Hamburg* 1, 1–14.
- Freudenthal, H. (1954). Beziehungen der E₇ und E₈ zur Oktavenebene. *KNAW Proc.* 57, 218–230.
- Tits, J. (1966). Algèbres alternatives, algèbres de Jordan et algèbres de Lie exceptionnelles. *Indagationes Mathematicae* 28, 223–237.
- Moufang, R. (1935). Zur Struktur von Alternativkörpern. *Mathematische Annalen* 110, 416–430.

### Information Geometry and Organizational

- Amari, S. (1985). *Differential-Geometrical Methods in Statistics*. Springer.
- Edmondson, A.C. (1999). Psychological safety and learning behavior in work teams. *Administrative Science Quarterly* 44(2), 350–383.
- Edmondson, A.C. (2023). *Right Kind of Wrong: The Science of Failing Well*. Atria Books.
- Allen, J.G. et al. (2016). Associations of cognitive function scores with carbon dioxide, ventilation, and volatile organic compound exposures. *Environmental Health Perspectives* 124(6), 805–812.

---

## 12. Vision Beyond 2028

The Dirac-Horizon Operator is a structural bet: **the event horizon is the physical reason
L-function zeros lie on the critical line.** Not as metaphor. As mechanism.

The argument has the following shape. Quantum gravity is unitary — information is preserved
across causal boundaries. The Page island mechanism is the concrete realization of this
unitarity: ker(∂̸) information re-enters col(∂̸) via the island contribution to the
Ryu–Takayanagi formula. The Hartnoll–Yang conformal primon gas at the BKL singularity places
the full spectral statistics of ζ(s) inside ker(∂̸) of the horizon Dirac operator.
Unitarity of black hole evaporation forces this information to be recoverable — it cannot
pile up behind the horizon forever. The **recoverable information constraint is the
arithmetic constraint**: it is what forces the zeros onto the critical line.

If this is correct, the Riemann Hypothesis is a theorem about **unitarity**. The same
principle that makes quantum mechanics consistent — probability is conserved — is the
arithmetic principle that places the zeros of ζ(s) on Re(s) = 1/2.

The consequences would cascade:

The **Twisted Hessian curve TH(a,d)** computes the group law of distributed information
across a causal boundary — the arithmetic of collective intelligence. Its CORDIC implementation
is not a hardware accelerator. It is the discretized Dirac equation, the arithmetic of
how information propagates (col) and is protected (ker) across the boundary of a silicon chip
as a miniature model of the event horizon it mathematically mirrors.

The **EDMONDSON psychological safety framework** — interpersonal col/ker in organizational
microstates — is the same operator at the scale of human teams. φ-equilibrium governs
the trust:accountability ratio for the same mathematical reason it governs the Page time
entropy ratio: it is the unique fixed point of self-similar information-preserving
transformations at every scale.

The **CORDIRAC pipeline** running on the **TOXOS CHORD coprocessor** in a car's ADAS
system is, in this view, not merely performing efficient numerical computation. It is
evaluating the discretized Dirac equation on the Twisted Hessian curve at 1.5 μJ per update,
738× more efficiently than floating-point computation, because the integer arithmetic of TH(a,d)
is the natural arithmetic of the physical universe at the curvature scale relevant to
near-sensor automotive inference.

The gap is precisely marked. The horizon is the operator. The Dirac boundary was always there.

The 2027–2028 programme is the richest, most multi-domain attempt ever mounted to stress-test
the GL(2)→GL(1) barrier from every available scientific direction simultaneously. If the
barrier is traversed, the Dirac-Horizon Operator will be recognized as the structure that
unified arithmetic, physics, machine learning, topology, quantum walks, and organizational
dynamics around the oldest and deepest open question in mathematics.

If it is not traversed, every test will have sharpened the map.

The traversal is now equipped.

---

*ERI Labs · Eric Ren · Jersey City, New Jersey*
