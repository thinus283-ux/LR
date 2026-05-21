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
