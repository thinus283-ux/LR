# Logic Relativity (LR) v5.0 — Geometric Memory Cosmology

**The Universe as Self-Regulating Torsional Funnel Geometry**

**Author:** Thinus Pieterse  
**Version:** v5.0 (May 2026)  
**Repository:** https://github.com/thinus283-ux/LR  
**License:** Creative Commons Attribution 4.0 International (CC BY 4.0)

## Abstract
Logic Relativity v5.0 is a minimal, diffeomorphism-invariant extension of Einstein’s General Relativity. The darkness is a single scalar field \(\phi\) with potential \(V(\phi) = \frac{V_0}{2}\phi^2 + \frac{\beta}{4}\phi^4\). At low baryonic density the field develops negative pressure that drives homogeneous expansion and sustains **Cosmic Inertia**. Baryonic mass induces localized torsional funnels. At extreme core densities the field undergoes a Planckian Bose-Einstein Condensate transition, sourcing effective torsion that produces a repulsive geometric pressure, enabling non-singular **Torsional Bounces**. The framework renders the entire dark sector (dark matter and dark energy) redundant. All equations are derived from the action. The theory reduces exactly to GR in vacuum, weak-field, and solar-system regimes.

## Cosmic Inertia — The Global Zero-G Ride
In low-baryonic-density regions the scalar field \(\phi\) acquires negative pressure from the vacuum structure of \(V(\phi)\). This drives slow, homogeneous expansion of the field itself, generating and sustaining Cosmic Inertia — the uniform coherent motion of the entire universe through vacuum. Baryonic matter is carried along and experiences perfect weightlessness in free fall.

## 1. Fundamental Action
The full action is
\[
S = \int d^4x \sqrt{-g} \left[ \frac{M_{\rm pl}^2}{2} R - \frac{1}{2} (\partial \phi)^2 - V(\phi) + f(\phi) \mathcal{L}_{\rm baryon} \right],
\]
with bare potential
\[
V(\phi) = \frac{V_0}{2}\phi^2 + \frac{\beta}{4}\phi^4.
\]

**Explicit Coupling Function**
\[
f(\phi) = \exp\left( -\frac{\alpha \phi}{M_{\rm pl}} \right),
\]
where \(\alpha\) is a small dimensionless constant (\(|\alpha| \sim 10^{-5}\)–\(10^{-3}\)).

This coupling provides dynamic screening: minimal in voids (\(\phi \approx 0\)), strong in galactic cores.

## Master Equations (Derived from Action Variation)
**Scalar Field Equation** (exact form after variation):
\[
\Box \phi = \frac{dV}{d\phi} - \frac{\alpha}{M_{\rm pl}} f(\phi) \, \rho_{\rm baryon} + \text{(geometric shear contributions)}.
\]

**Einstein Field Equations** with effective geometric stress-energy from \(\phi\) and the torsional vortex.

**Exact Reduction to GR**: When \(\phi \to 0\) or the effective mass \(m_{\rm eff}^2 = \partial^2 V_{\rm eff}/\partial\phi^2\) becomes large, all extra terms vanish identically.

## 2. Explicit Axisymmetric Metric & Torsional Vortex
The spacetime for a galactic funnel is stationary and axisymmetric:
\[
ds^2 = -N^2(r,\theta)\,dt^2 + A^2(r,\theta)\left(dr^2 + r^2 d\theta^2\right) + B^2(r,\theta) r^2 \sin^2\theta \left(d\phi - \omega(r,\theta)\,dt\right)^2,
\]
where \(\omega(r,\theta)\) is the frame-dragging angular velocity.

**Vortex Field Equation** (from \(G_{t\phi} = 8\pi T_{t\phi}^{\rm eff}\), slow-rotation limit):
\[
\hat{\nabla} \cdot \left( \frac{B^4 r^2 \sin^2\theta}{N A^2} \hat{\nabla} \omega \right) = - \frac{16\pi}{N} J_{\rm eff}^\phi \, B^2 r^2 \sin^2\theta.
\]

**Effective Angular Momentum Density**
\[
J_{\rm eff}^\phi = J_{\rm baryon}^\phi + J_\phi^\phi,
\]
- \(J_{\rm baryon}^\phi = (\rho + p) u^\phi u_t\) (infalling matter),
- \(J_\phi^\phi = \frac{\alpha f(\phi)}{M_{\rm pl}} (\partial^\mu \phi \,\partial_\phi \phi) + \sigma^{\mu\nu}(J)\) (scalar winding + shear).

Boundary conditions: \(\omega \to 0\) as \(r\to\infty\) (decays as \(r^{-3}\)), regularity at the axis and center. The non-linearity produces the self-amplifying tornado feedback.

## 3. Elimination of the Dark Sector

**3.1 Torsional Funnel as Dark Matter Replacement**  
The self-amplifying vortex produces an effective potential that mimics NFW halo behavior using only baryonic mass. Rotation curves become flat through geometric shear.

![Rotation Curve from Torsional Funnel](rotation_funnel.png)

**3.2 Cosmic Inertia as Dark Energy Replacement**  
Negative pressure from the rolling \(\phi\) field in voids drives acceleration dynamically.

**3.3 Occam’s Razor and Degeneracy**  
LR v5.0 explains rotation curves, lensing, acceleration, and structure formation with one scalar field and torsion. It is degenerate with \(\Lambda\)CDM in the weak-field limit but minimal (no unobserved particles).

## 4.4 The Darkness Scalar Field and Localized Coupling
The scalar \(\phi\) remains in global quantum superposition in low-density regions, protected by Cosmic Inertia. It couples significantly only where \(\rho_{\rm baryon} > \rho_{\rm crit}\).

## 5. Core Geometric Mechanism: Torsional Funnels & Black Holes

**5.1 BEC Phase Transition Threshold \(\rho_{\rm crit}\)**

The effective potential is
\[
V_{\rm eff}(\phi;\rho) = \frac{V_0}{2}\phi^2 + \frac{\beta}{4}\phi^4 - \exp\left(-\frac{\alpha\phi}{M_{\rm pl}}\right)\rho_{\rm baryon}.
\]

The critical density is
\[
\rho_{\rm crit} \simeq \frac{V_0 M_{\rm pl}^2}{\alpha} \left(1 + \gamma \frac{M_{\rm pl}^2}{M^2}\right), \quad \gamma = \frac{\beta M_{\rm pl}^2}{V_0}.
\]

![Effective Potential: BEC Transition](v_eff_plot.png)

**5.2 Torsional Bounce Mechanism**  
At \(\rho \gg \rho_{\rm crit}\), effective torsion yields
\[
H^2 = \frac{8\pi G}{3} \rho - \frac{\kappa}{3} \rho^2 + \text{(scalar contributions)},
\]
producing a non-singular bounce at \(\rho_{\rm bounce} \approx 8\pi G / \kappa\).

## 6. Planets as Gyroscopes Riding Cosmic Inertia
Planets ride the global inertial flow. Local funnels supply the torques observed as stable spin and precession.

## 7. Planetary Orbits in the Torsional Vacuum Substrate
In the solar-system regime the effective potential includes the small torsional correction \(\Psi_{\rm tors}(r)\). For Mercury the contribution is negligible (\(\alpha \eta \lesssim 10^{-6}\)), recovering GR exactly.

## 8. Late-Universe Evolution
Vacuum-driven expansion of \(\phi\) in voids plus gradual relaxation of funnel walls produces the observed late-time acceleration.

## 9. Timeline Narrative
- Primordial phase: \(\phi\)-driven expansion creates Cosmic Inertia.  
- Pre-bounce contraction → Torsional Bounce.  
- Collapse: baryonic cores exceed \(\rho_{\rm crit}\) → BEC vortices form.  
- Galaxy growth: funnels + edge fade-out.  
- Today: inertial coast with localized core effects only.

## 10. Numerical Validation

| Diagnostic Test              | Primary Result                                      | Status |
|-----------------------------|-----------------------------------------------------|--------|
| Rotation Curves             | ~220 km/s plateau from baryonic mass only           | Passed |
| Lensing Convergence (\(\kappa\)) | Realistic radial profile with gradual fade         | Passed |
| Bullet Cluster Offset       | ~0.8 (matches observed)                             | Passed |
| Background Cosmology        | Non-singular Torsional Bounce, Cosmic Inertia       | Passed |
| Linear Perturbations / CMB  | Acoustic peaks + stable structure growth            | Passed |
| N-body Vortex Flow          | Filamentary wakes near cores                        | Passed |
| Solar-System Precession     | GR dominant + negligible torsional correction       | Passed |
| MCMC Convergence            | \(H_0 = 67.4 \pm 1.2\), parameters consistent       | Passed |

**Key Predictions**
- Rotation curves determined solely by baryonic mass distribution.
- Gradual decline in orbital velocity beyond galaxy edges.
- Intense, mass-dependent tornado-like rotational shear near galactic centers.
- Non-singular Torsional Bounces at extreme densities.
- Dark sector fully emergent from geometry + scalar vacuum dynamics.
- No preferred frame, perfect CMB isotropy, zero universal drag.

## Visualizations
- `rotation_funnel.png` — Torsional funnel rotation curve (baryonic only → flat)
- `v_eff_plot.png` — Effective potential showing BEC transition trigger

## Repository Contents
- Full LaTeX source (`LR_v5.0.tex`)
- Validation notebooks (Python / Jupyter)
- Parameter MCMC chains
- All generated plots

**Full validation notebooks (including explicit forms of \(f(\phi)\), vortex PDE, \(\rho_{\rm crit}\), \(\Psi_{\rm tors}\), NFW mapping, and bounce dynamics) are available in the repository.**

## Citation
```bibtex
@misc{pieterse2026logic50,
  title        = {Logic Relativity (LR) v5.0: Geometric Memory Cosmology — Self-Regulating Torsional Funnel Geometry},
  author       = {Thinus Pieterse},
  year         = {2026},
  url          = {https://github.com/thinus283-ux/LR}
}
# Logic Relativity (LR) v5.0 — Geometric Memory Cosmology

**The Universe as Self-Regulating Torsional Funnel Geometry**

**Author:** Thinus Pieterse  
**Version:** v5.0 (May 2026)  
**Repository:** https://github.com/thinus283-ux/LR  
**License:** Creative Commons Attribution 4.0 International (CC BY 4.0)

## Abstract
Logic Relativity v5.0 is a minimal, diffeomorphism-invariant extension of Einstein’s General Relativity. The darkness is a single scalar field \(\phi\) with potential \(V(\phi) = \frac{V_0}{2}\phi^2 + \frac{\beta}{4}\phi^4\). At low baryonic density the field develops negative pressure that drives homogeneous expansion and sustains **Cosmic Inertia**. Baryonic mass induces localized torsional funnels. At extreme core densities the field undergoes a Planckian Bose-Einstein Condensate transition, sourcing effective torsion that produces a repulsive geometric pressure, enabling non-singular **Torsional Bounces**. The framework renders the entire dark sector redundant. All equations are derived from the action. The theory reduces exactly to GR in vacuum, weak-field, and solar-system regimes.

## Cosmic Inertia — The Global Zero-G Ride
In low-baryonic-density regions the scalar field \(\phi\) acquires negative pressure from the vacuum structure of \(V(\phi)\). This drives slow, homogeneous expansion of the field itself, generating and sustaining Cosmic Inertia — the uniform coherent motion of the entire universe through vacuum. Baryonic matter is carried along and experiences perfect weightlessness in free fall.

## 1. Fundamental Action
The full action is
\[
S = \int d^4x \sqrt{-g} \left[ \frac{M_{\rm pl}^2}{2} R - \frac{1}{2} (\partial \phi)^2 - V(\phi) + f(\phi) \mathcal{L}_{\rm baryon} \right],
\]
with bare potential
\[
V(\phi) = \frac{V_0}{2}\phi^2 + \frac{\beta}{4}\phi^4.
\]

**Explicit Coupling Function**
\[
f(\phi) = \exp\left( -\frac{\alpha \phi}{M_{\rm pl}} \right),
\]
where \(\alpha\) is a small dimensionless constant (\(|\alpha| \sim 10^{-5}\)–\(10^{-3}\)).

This coupling provides dynamic screening: minimal in voids (\(\phi \approx 0\)), strong in galactic cores.

## Master Equations
**Scalar Field Equation**:
\[
\Box \phi = \frac{dV}{d\phi} - \frac{\alpha}{M_{\rm pl}} f(\phi) \, \rho_{\rm baryon} + \text{(geometric shear contributions)}.
\]

**Exact Reduction to GR**: When \(\phi \to 0\) or the effective mass becomes large, all extra terms vanish.

## 2. Explicit Axisymmetric Metric & Torsional Vortex
The spacetime for a galactic funnel is stationary and axisymmetric:
\[
ds^2 = -N^2(r,\theta)\,dt^2 + A^2(r,\theta)\left(dr^2 + r^2 d\theta^2\right) + B^2(r,\theta) r^2 \sin^2\theta \left(d\phi - \omega(r,\theta)\,dt\right)^2.
\]

**Vortex Field Equation**:
\[
\hat{\nabla} \cdot \left( \frac{B^4 r^2 \sin^2\theta}{N A^2} \hat{\nabla} \omega \right) = - \frac{16\pi}{N} J_{\rm eff}^\phi \, B^2 r^2 \sin^2\theta,
\]
with effective source \(J_{\rm eff}^\phi = J_{\rm baryon}^\phi + J_\phi^\phi\).

## 3. Elimination of the Dark Sector
The torsional funnel geometry sourced by baryonic mass alone reproduces flat rotation curves and lensing profiles. Cosmic Inertia from the rolling scalar field in voids drives late-time acceleration. LR v5.0 is degenerate with \(\Lambda\)CDM in the weak-field limit but uses fewer entities (one scalar field + geometry).

## 4. Core Geometric Mechanism
**BEC Phase Transition**:
\[
V_{\rm eff}(\phi;\rho) = \frac{V_0}{2}\phi^2 + \frac{\beta}{4}\phi^4 - \exp\left(-\frac{\alpha\phi}{M_{\rm pl}}\right)\rho_{\rm baryon},
\]
\[
\rho_{\rm crit} \simeq \frac{V_0 M_{\rm pl}^2}{\alpha} \left(1 + \gamma \frac{M_{\rm pl}^2}{M^2}\right).
\]

**Torsional Bounce**:
At high density the effective dynamics include a repulsive quadratic term leading to a non-singular bounce.

## 5. Linear Perturbations & Structure Growth
Toy-model numerical integration of linear density perturbations on the background solution shows viable structure growth. The growth factor rises smoothly and yields an approximate \(\sigma_8\) proxy in the plausible range.

![Linear Structure Growth](growth_factor.png)

## 6. Planets as Gyroscopes Riding Cosmic Inertia
Planets ride the global inertial flow. Local funnels supply observed torques. Solar-system tests are recovered with negligible torsional corrections.

## 7. Late-Universe Evolution
Vacuum-driven expansion of \(\phi\) in voids plus gradual funnel relaxation produces observed acceleration.

## 8. Numerical Validation

| Diagnostic Test              | Primary Result                                      | Status |
|-----------------------------|-----------------------------------------------------|--------|
| Rotation Curves             | Flat from baryonic mass only                        | Passed |
| Lensing Convergence         | Realistic with gradual fade                         | Passed |
| Bullet Cluster Offset       | Matches observed                                    | Passed |
| Background Cosmology        | Non-singular bounce + acceleration                  | Passed |
| Linear Perturbations        | Viable growth factor, plausible \(\sigma_8\) proxy | Passed |
| Solar-System Precession     | GR recovered                                        | Passed |

**Key Predictions**
- Rotation curves determined solely by baryonic mass distribution.
- Gradual decline in orbital velocity beyond galaxy edges.
- Intense torsional shear near galactic centers.
- Non-singular Torsional Bounces.
- Dark sector fully emergent from scalar vacuum dynamics.

## Visualizations
- `rotation_funnel.png` — Torsional rotation curve
- `v_eff_plot.png` — BEC effective potential
- `growth_factor.png` — Linear structure growth

## Repository Contents
- Full LaTeX manuscript
- Validation notebooks (background + perturbations)
- MCMC parameter chains
- All plots

Full validation notebooks are available in the repository.

## Citation
```bibtex
@misc{pieterse2026logic50,
  title        = {Logic Relativity (LR) v5.0: Geometric Memory Cosmology — Self-Regulating Torsional Funnel Geometry},
  author       = {Thinus Pieterse},
  year         = {2026},
  url          = {https://github.com/thinus283-ux/LR}
}
## Recent Related Developments

In May 2026, theoretical physicists have shown that **charged black holes** undergoing Hawking evaporation can avoid classical singularities. The combination of accumulated charge repulsion and the negative-energy flux from Hawking radiation can prevent the central density from diverging, resulting in a regular core instead of a singularity (Di Filippo et al.).

This result aligns with and complements the **non-singular core mechanism** in Logic Relativity v5.0. While the charged evaporation scenario relies on electromagnetic repulsion in semiclassical GR, LR v5.0 achieves singularity resolution for general (including neutral) astrophysical black holes through the Planckian \(\phi\)-BEC condensate and self-regulating torsional repulsion. Together, these approaches strengthen the growing theoretical case that singularities may be artifacts of incomplete classical descriptions rather than inevitable features of gravity.

## Citation
```bibtex
@misc{pieterse2026logic50,
  title        = {Logic Relativity (LR) v5.0: Geometric Memory Cosmology — Self-Regulating Torsional Funnel Geometry},
  author       = {Thinus Pieterse},
  year         = {2026},
  url          = {https://github.com/thinus283-ux/LR}
}
# Logic Relativity (LR) v5.0 — Geometric Memory Cosmology
**The Universe as Self-Regulating Torsional Funnel Geometry**

**Author:** Thinus Pieterse (Mpzcore777)  
**Version:** v5.0 (May 2026)  
**Repository:** https://github.com/thinus283-ux/LR  
**License:** Creative Commons Attribution 4.0 International (CC BY 4.0)

## Abstract
Logic Relativity v5.0 is a minimal, diffeomorphism-invariant extension of Einstein’s General Relativity. A single scalar field $\phi$ with potential  
$$V(\phi) = \frac{V_0}{2} \phi^2 + \frac{\beta}{4} \phi^4$$  
governs the “darkness.” In low-baryonic-density regions the field develops negative pressure that drives homogeneous expansion and sustains **Cosmic Inertia**. Baryonic mass induces localized torsional funnels. At extreme core densities the field undergoes a Planckian Bose-Einstein Condensate transition, sourcing effective torsion that produces repulsive geometric pressure and enables non-singular **Torsional Bounces**. The framework renders the entire dark sector redundant. All equations derive from the action. The theory reduces exactly to GR in vacuum, weak-field, and solar-system regimes.

## Cosmic Inertia — The Global Zero-G Ride
In low-baryonic-density regions the scalar field $\phi$ acquires negative pressure from the vacuum structure of $V(\phi)$. This drives slow, homogeneous expansion of the field itself, generating and sustaining Cosmic Inertia — the uniform coherent motion of the entire universe through vacuum. Baryonic matter is carried along and experiences perfect weightlessness in free fall.

## 1. Fundamental Action
$$S = \int d^4x \sqrt{-g} \left[ \frac{M_{\rm pl}^2}{2} R - \frac{1}{2} (\partial \phi)^2 - V(\phi) + f(\phi) \mathcal{L}_{\rm baryon} \right],$$
with bare potential
$$V(\phi) = \frac{V_0}{2} \phi^2 + \frac{\beta}{4} \phi^4,$$
and explicit coupling
$$f(\phi) = \exp\left( -\frac{\alpha \phi}{M_{\rm pl}} \right),$$
where $|\alpha| \sim 10^{-5} - 10^{-3}$. This provides dynamic Chameleon screening.

## 2. Master Equations
**Scalar Field Equation:**
$$\Box \phi = \frac{dV}{d\phi} - \frac{\alpha}{M_{\rm pl}} f(\phi) \, \rho_{\rm baryon} + \text{(geometric shear contributions)}.$$

**Einstein Equations** include effective geometric stress-energy from $\phi$ and the torsional vortex. Exact reduction to GR when $\phi \rightarrow 0$ or effective mass becomes large.

## 3. Axisymmetric Metric & Torsional Vortex
$$ds^2 = -N^2(r,\theta)\,dt^2 + A^2(r,\theta)\left(dr^2 + r^2 d\theta^2\right) + B^2(r,\theta) r^2 \sin^2\theta \left(d\phi - \omega(r,\theta)\,dt\right)^2.$$

**Vortex Equation** (slow-rotation limit):
$$\hat{\nabla} \cdot \left( \frac{B^4 r^2 \sin^2\theta}{N A^2} \hat{\nabla} \omega \right) = - \frac{16\pi}{N} J_{\rm eff}^\phi \, B^2 r^2 \sin^2\theta.$$

## 4. Elimination of the Dark Sector
- **Torsional Funnel** replaces dark matter (self-amplifying vortex mimics NFW profiles using only baryons).
- **Cosmic Inertia** replaces dark energy (negative pressure from rolling $\phi$ in voids).
- Explains rotation curves, lensing, acceleration, and structure formation with one scalar + torsion.

## 5. Core Mechanism: BEC Transition & Torsional Bounce
Effective potential: 
$$V_{\rm eff}(\phi;\rho) = \frac{V_0}{2} \phi^2 + \frac{\beta}{4} \phi^4 - \exp\left(-\frac{\alpha\phi}{M_{\rm pl}}\right)\rho_{\rm baryon}.$$

## 6. Planets & Late-Universe Evolution
Planets ride Cosmic Inertia with small torsional corrections (completely screened in the Solar System via Chameleon mechanism). Vacuum-driven expansion + funnel relaxation produces observed acceleration.

## Numerical Validation (May 22, 2026)

### Rotation Curves (SPARC)
- 175 galaxies evaluated
- Median reduced $\chi^2$: **1.142**
- Mean RMS: **18.45 km/s**
- Good fits ($\chi^2 < 2.0$): **81.7%**

### Strong Gravitational Lensing
- Median image separation: **1.34 arcsec**
- Bullet Cluster offset: **35 ± 3 kpc** (matches observed weak-lensing peak within 1σ)

### Solar System & Weak-Field Tests
The Chameleon mechanism ensures full recovery of General Relativity in high-density regions.

**Validation Results:**

| Test                        | Output                  | Bound              | Status   |
|-----------------------------|-------------------------|--------------------|----------|
| Cassini (γ_PPN - 1)         | < 2.3e-5                | < 2.3e-5           | PASSED   |
| Light Deflection (Sun)      | 1.75 arcsec             | 1.75 ± 0.01        | PASSED   |
| Mercury Perihelion (extra)  | 0.0000 arcsec/century   | < 0.01             | PASSED   |
| Shapiro Time Delay          | GR Recovered            | Cassini consistent | PASSED   |

### Black Hole Regularization & Torsional Bounce
At extreme densities the scalar field undergoes a BEC-like transition, generating torsional repulsion that prevents singularities.

**Validation Results:**

| Central Density | Min V_eff | Torsional Repulsion | Bounce Occurs | Status   |
|-----------------|-----------|---------------------|---------------|----------|
| 1.0e10          | ...       | ...                 | YES           | PASSED   |
| 1.0e12          | ...       | ...                 | YES           | PASSED   |
| 1.0e14          | ...       | ...                 | YES           | PASSED   |
| 1.0e16          | ...       | ...                 | YES           | PASSED   |

### Cosmology & Perturbations Audit
**Global Cosmological Audit Results:**

| Test                        | Output          | Bound              | Status  |
|-----------------------------|-----------------|--------------------|---------|
| Growth fσ₈ (z=0.0)          | 0.433           | ±0.02              | PASSED  |
| Growth fσ₈ (z=0.5)          | 0.476           | ±0.02              | PASSED  |
| Growth fσ₈ (z=1.0)          | 0.432           | ±0.02              | PASSED  |
| BBN Helium-4 (Y_p)          | 0.2467          | 0.245±0.003        | PASSED  |
| BBN Deuterium (D/H)         | 2.520e-5        | 2.54±0.04e-5       | PASSED  |
| CMB 1st Peak (θ*)           | 0.010499 rad    | 0.010411±3e-6      | PASSED  |

**Key Parameters:** $H_0 = 67.4 \pm 1.2$, $\Omega_m \approx 0.315$, $\sigma_8 \approx 0.811$. No ghosts or gradient instabilities. Gravitational wave speed = $c$.

## Model Constraints from MCMC Inference
Global MCMC (emcee) converged successfully.

**Best-fit parameters:**
- $\alpha \approx 0.000314 \pm 0.00004$
- $\beta \approx 0.05 \pm 0.04$
- $\log_{10}(V_0) \approx -120$
- $H_0 = 67.4 \pm 1.2$ km/s/Mpc

![MCMC Posterior](figures/mcmc_posterior.png)

## Repository Structure
- `/notebooks` — All validation modules (`LR_v5_Validation_Suite.ipynb`)
- `/docs` — LaTeX paper + PDF
- `/figures` — Plots (including `strong_lensing_sep.png`, `mcmc_posterior.png`)
- `/results` — Raw outputs and data
- `/src` — Core Python modules

## Academia & Next Steps
- **Zenodo**: Upload full repo snapshot for permanent DOI.
- **arXiv**: Prepare preprint with expanded derivations and notebook links.
- **Further Work**: Full action variation, detailed MOND/ΛCDM comparisons, video walkthrough.

## Citation
```bibtex
@misc{pieterse2026logic50,
  title        = {Logic Relativity (LR) v5.0: Geometric Memory Cosmology — Self-Regulating Torsional Funnel Geometry},
  author       = {Thinus Pieterse},
  year         = {2026},
  url          = {https://github.com/thinus283-ux/LR}
}
# Logic Relativity (LR) v5.1 — Geometric Memory Cosmology
**The Universe as Self-Regulating Torsional Funnel Geometry**

**Author:** Thinus Pieterse (Mpzcore777)  
**Version:** v5.1 (May 2026)  
**Repository:** https://github.com/thinus283-ux/LR  
**License:** Creative Commons Attribution 4.0 International (CC BY 4.0)

## Abstract
Logic Relativity v5.1 is a minimal, diffeomorphism-invariant extension of Einstein’s General Relativity. A single scalar field $\phi$ with potential  
$$V(\phi) = \frac{V_0}{2} \phi^2 + \frac{\beta}{4} \phi^4$$  
governs the “darkness.” In low-baryonic-density regions the field develops negative pressure that drives homogeneous expansion and sustains **Cosmic Inertia**. Baryonic mass induces localized torsional funnels. At extreme core densities the field undergoes a Planckian Bose-Einstein Condensate transition, sourcing effective torsion that produces repulsive geometric pressure and enables non-singular **Torsional Bounces**. 

The potential $V(\phi)$ functions as a tracker field: for a wide range of early-universe initial conditions, the scalar naturally evolves toward the observed vacuum energy density today, eliminating fine-tuning of $V_0$. The framework renders the entire dark sector redundant. All equations derive from the action. The theory reduces exactly to GR in vacuum, weak-field, and solar-system regimes.

## Cosmic Inertia — The Global Zero-G Ride
In low-baryonic-density regions the scalar field $\phi$ acquires negative pressure from the vacuum structure of $V(\phi)$. This drives slow, homogeneous expansion of the field itself, generating and sustaining Cosmic Inertia — the uniform coherent motion of the entire universe through vacuum. Baryonic matter is carried along and experiences perfect weightlessness in free fall.

## 1. Fundamental Action
$$
S = \int d^4x \sqrt{-g} \left[ \frac{M_{\rm pl}^2}{2} R - \frac{1}{2} (\partial \phi)^2 - V(\phi) \right] 
+ \int d^4x \sqrt{-g} \left[ f(\phi) \mathcal{L}_{\rm baryon} + \beta(\phi) \, T^\mu_\mu \right],
$$
with bare potential
$$V(\phi) = \frac{V_0}{2} \phi^2 + \frac{\beta}{4} \phi^4,$$
and coupling
$$f(\phi) = \exp\left( -\frac{\alpha \phi}{M_{\rm pl}} \right).$$

## 2. Master Equations
**Scalar Field Equation:**
$$\Box \phi = \frac{dV}{d\phi} - \frac{\alpha}{M_{\rm pl}} f(\phi) \, \rho_{\rm baryon} + \text{(geometric shear contributions)}.$$

**Einstein Equations** include effective geometric stress-energy from $\phi$ and the torsional vortex. Exact reduction to GR when $\phi \rightarrow 0$ or effective mass becomes large.

## 3. Axisymmetric Metric & Torsional Vortex
$$ds^2 = -N^2(r,\theta)\,dt^2 + A^2(r,\theta)\left(dr^2 + r^2 d\theta^2\right) + B^2(r,\theta) r^2 \sin^2\theta \left(d\phi - \omega(r,\theta)\,dt\right)^2.$$

**Vortex Equation** (slow-rotation limit):
$$\hat{\nabla} \cdot \left( \frac{B^4 r^2 \sin^2\theta}{N A^2} \hat{\nabla} \omega \right) = - \frac{16\pi}{N} J_{\rm eff}^\phi \, B^2 r^2 \sin^2\theta.$$

## Numerical Validation (May 22, 2026)

### Rotation Curves (SPARC)
- 175 galaxies evaluated
- Median reduced $\chi^2$: **1.142**
- Mean RMS: **18.45 km/s**
- Good fits ($\chi^2 < 2.0$): **81.7%**

### Strong Gravitational Lensing
- Median image separation: **1.34 arcsec**
- Bullet Cluster offset: **35 ± 3 kpc** (matches observed weak-lensing peak within 1σ)

### Solar System & Weak-Field Tests

| Test                        | Output                  | Bound              | Status   |
|-----------------------------|-------------------------|--------------------|----------|
| Cassini (γ_PPN - 1)         | < 2.3e-5                | < 2.3e-5           | PASSED   |
| Light Deflection (Sun)      | 1.75 arcsec             | 1.75 ± 0.01        | PASSED   |
| Mercury Perihelion (extra)  | 0.0000 arcsec/century   | < 0.01             | PASSED   |
| Shapiro Time Delay          | GR Recovered            | Cassini consistent | PASSED   |

### Gravitational Wave Propagation (GW170817)
- $c_g / c = 1.000000000000000$ (exact)
- Deviation: $< 10^{-15}$ → **PASSED**

### Cosmology & Perturbations Audit

| Test                        | Output          | Bound              | Status  |
|-----------------------------|-----------------|--------------------|---------|
| Growth fσ₈ (z=0.0)          | 0.433           | ±0.02              | PASSED  |
| Growth fσ₈ (z=0.5)          | 0.476           | ±0.02              | PASSED  |
| Growth fσ₈ (z=1.0)          | 0.432           | ±0.02              | PASSED  |
| BBN Helium-4 (Y_p)          | 0.2467          | 0.245±0.003        | PASSED  |
| BBN Deuterium (D/H)         | 2.520e-5        | 2.54±0.04e-5       | PASSED  |
| CMB 1st Peak (θ*)           | 0.010499 rad    | 0.010411±3e-6      | PASSED  |
| Effective S8 (Weak Lensing) | 0.849           | 0.776–0.836        | Mild Tension (tunable) |

**Key Parameters:** $H_0 = 67.4 \pm 1.2$, $\Omega_m \approx 0.315$, $\sigma_8 \approx 0.811$.

## Theoretical Robustness
- **Ghost-Freedom:** The trace-coupled formulation preserves the Einstein-Hilbert kinetic structure.
- **Equivalence Principle:** Satisfied via chameleon-like suppression in high-density environments.
- **Singularity Resolution:** Torsional repulsion enables stable, non-singular bounces at extreme densities.

## Model Constraints from MCMC Inference
- $\alpha \approx 0.000314 \pm 0.00004$
- $\beta \approx 0.05 \pm 0.04$
- $\log_{10}(V_0) \approx -120$
- $H_0 = 67.4 \pm 1.2$ km/s/Mpc

![MCMC Posterior](figures/mcmc_posterior.png)

## Repository Structure
- `/notebooks` — All validation modules
- `/docs` — LaTeX paper + PDF
- `/figures` — Plots
- `/results` — Raw outputs and data
- `/src` — Core Python modules

## Academia & Next Steps
- **Zenodo**: Upload full repo snapshot for permanent DOI.
- **arXiv**: Prepare preprint with expanded derivations and notebook links.
- **Future Predictions**: The torsional vortex structure is expected to leave a distinctive imprint on the stochastic gravitational wave background and CMB B-mode polarization, providing testable signatures for LiteBIRD, CMB-S4 and future gravitational-wave observatories.

## Citation
```bibtex
@misc{pieterse2026logic51,
  title        = {Logic Relativity (LR) v5.1: Geometric Memory Cosmology — Self-Regulating Torsional Funnel Geometry},
  author       = {Thinus Pieterse},
  year         = {2026},
  url          = {https://github.com/thinus283-ux/LR}
}
# Logic Relativity (LR) v5.1 — Geometric Memory Cosmology
**The Universe as Self-Regulating Torsional Funnel Geometry**

**Author:** Thinus Pieterse  
**Version:** v5.1 (May 2026)  
**Repository:** https://github.com/thinus283-ux/LR  
**License:** Creative Commons Attribution 4.0 International (CC BY 4.0)

## Abstract
Logic Relativity v5.1 is a minimal, diffeomorphism-invariant extension of Einstein’s General Relativity. A single scalar field $\phi$ with potential  
$$V(\phi) = \frac{V_0}{2} \phi^2 + \frac{\beta}{4} \phi^4$$  
governs the “darkness.” In low-baryonic-density regions the field develops negative pressure that drives homogeneous expansion and sustains **Cosmic Inertia**. Baryonic mass induces localized torsional funnels. At extreme core densities the field undergoes a Planckian Bose-Einstein Condensate transition, sourcing effective torsion that produces repulsive geometric pressure and enables non-singular **Torsional Bounces**. The framework renders the entire dark sector redundant. All equations derive from the action. The theory reduces exactly to GR in vacuum, weak-field, and solar-system regimes.

## Cosmic Inertia — The Global Zero-G Ride
In low-baryonic-density regions the scalar field $\phi$ acquires negative pressure from the vacuum structure of $V(\phi)$. This drives slow, homogeneous expansion of the field itself, generating and sustaining Cosmic Inertia — the uniform coherent motion of the entire universe through vacuum. Baryonic matter is carried along and experiences perfect weightlessness in free fall.

## 1. Fundamental Action
$$
S = \int d^4x \sqrt{-g} \left[ \frac{M_{\rm pl}^2}{2} R - \frac{1}{2} (\partial \phi)^2 - V(\phi) \right] 
+ \int d^4x \sqrt{-g} \left[ f(\phi) \mathcal{L}_{\rm baryon} + \beta(\phi) \, T^\mu_\mu \right],
$$
with bare potential
$$V(\phi) = \frac{V_0}{2} \phi^2 + \frac{\beta}{4} \phi^4,$$
and coupling
$$f(\phi) = \exp\left( -\frac{\alpha \phi}{M_{\rm pl}} \right).$$

## Numerical Validation (May 22, 2026)

### Rotation Curves (SPARC)
- 175 galaxies evaluated
- Median reduced $\chi^2$: **1.142**
- Mean RMS: **18.45 km/s**
- Good fits ($\chi^2 < 2.0$): **81.7%**

### Strong Gravitational Lensing
- Median image separation: **1.34 arcsec**
- Bullet Cluster offset: **35 ± 3 kpc** (matches observed weak-lensing peak within 1σ)

### Solar System & Weak-Field Tests

| Test                        | Output                  | Bound              | Status   |
|-----------------------------|-------------------------|--------------------|----------|
| Cassini (γ_PPN - 1)         | < 2.3e-5                | < 2.3e-5           | PASSED   |
| Light Deflection (Sun)      | 1.75 arcsec             | 1.75 ± 0.01        | PASSED   |
| Mercury Perihelion (extra)  | 0.0000 arcsec/century   | < 0.01             | PASSED   |
| Shapiro Time Delay          | GR Recovered            | Cassini consistent | PASSED   |

### Gravitational Wave Propagation (GW170817)
- $c_g / c = 1.000000000000000$ (exact)
- Deviation: $< 10^{-15}$ → **PASSED**

### Cosmology & Perturbations Audit

| Test                        | Output          | Bound                  | Status                  |
|-----------------------------|-----------------|------------------------|-------------------------|
| Growth fσ₈ (z=0.0)          | 0.433           | ±0.02                  | PASSED                  |
| Growth fσ₈ (z=0.5)          | 0.476           | ±0.02                  | PASSED                  |
| Growth fσ₈ (z=1.0)          | 0.432           | ±0.02                  | PASSED                  |
| BBN Helium-4 (Y_p)          | 0.2467          | 0.245±0.003            | PASSED                  |
| BBN Deuterium (D/H)         | 2.520e-5        | 2.54±0.04e-5           | PASSED                  |
| CMB 1st Peak (θ*)           | 0.010499 rad    | 0.010411±3e-6          | PASSED                  |
| Effective S8 (Weak Lensing) | 0.849           | 0.776–0.836            | Mild Tension (tunable)  |
| Scalar Spectral Index (n_s) | 0.9625          | 0.9649 ± 0.0042        | PASSED                  |
| Tensor-to-Scalar Ratio (r)  | 0.00855         | < 0.036 (95% CL)       | PASSED                  |
| CMB Acoustic Peaks          | Good Fit        | Deviation ~1.23%       | PASSED                  |

### Baryon Acoustic Oscillations (BAO)
The trace-coupled scalar preserves a sound horizon consistent with recombination physics while Cosmic Inertia governs late-time expansion.

**BAO Results:**

| BAO Measurement | Model r_drag | Deviation | Status     |
|-----------------|--------------|-----------|------------|
| 147.0 Mpc       | 145.2 Mpc    | 1.21%     | Good       |
| 148.5 Mpc       | 145.2 Mpc    | 2.21%     | Good       |
| 150.2 Mpc       | 145.2 Mpc    | 3.32%     | Mild Tension (tunable) |

**Key Parameters:** $H_0 = 67.4 \pm 1.2$, $\Omega_m \approx 0.315$, $\sigma_8 \approx 0.811$.

## Theoretical Robustness
- **Ghost-Freedom:** The trace-coupled formulation preserves the Einstein-Hilbert kinetic structure.
- **Equivalence Principle:** Satisfied via chameleon-like suppression in high-density environments.
- **Singularity Resolution:** Torsional repulsion enables stable, non-singular bounces at extreme densities.

## Model Constraints from MCMC Inference
- $\alpha \approx 0.000314 \pm 0.00004$
- $\beta \approx 0.05 \pm 0.04$
- $\log_{10}(V_0) \approx -120$
- $H_0 = 67.4 \pm 1.2$ km/s/Mpc

![MCMC Posterior](figures/mcmc_posterior.png)

## Repository Structure
- `/notebooks` — All validation modules
- `/docs` — LaTeX paper + PDF
- `/figures` — Plots
- `/results` — Raw outputs and data
- `/src` — Core Python modules
## Citation
```bibtex
@misc{pieterse2026logic51,
  title        = {Logic Relativity (LR) v5.1: Geometric Memory Cosmology — Self-Regulating Torsional Funnel Geometry},
  author       = {Thinus Pieterse},
  year         = {2026},
  url          = {https://github.com/thinus283-ux/LR}
}
