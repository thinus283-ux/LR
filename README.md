# Logic Relativity (LR) v2.5 — Unified Cosmological Framework

**The Mother of All Theories**

A particle-free cosmological model in which gravity, structure formation, cosmic expansion, and black hole interiors emerge from baryonic mass interacting with a single real physical medium called **“The Darkness”** — a viscoelastic cosmic fluid.

**Core Principle:** *Only mass matters.*

---

## Abstract

Logic Relativity (LR) v2.5 proposes a unified, particle-free cosmological framework in which gravity, structure formation, cosmic expansion, and black hole interiors emerge from baryonic mass interacting with a single real physical medium called **“The Darkness”** — a viscoelastic cosmic fluid.

The medium follows a natural density-dependent gradient and is governed by the Maxwell-Cattaneo constitutive relation, ensuring causality. The framework is fully consistent with General Relativity in the curved-spacetime regime and reduces to special-relativistic viscoelastic hydrodynamics in locally flat frames.

**Core Principle:** *Only mass matters.*

---

## Key Simulation Results (Colab v2.5)

- **Lagging Wake**: Density field trails moving mass cores → natural support for flat rotation curves.
- **Gravitational Wave Damping**: High-frequency components attenuated 60–80% vs vacuum GR.
- **JWST Structure Catalyst**: Sharp +10% growth acceleration at k ≈ 0.1 h/Mpc → explains early massive structures.
- **Frozen Core (Singularity Resolution)**: Stable finite central potential instead of GR collapse to infinity.
- **Chromatic Boundary Lensing**: Frequency-dependent deflection anomaly peaks at cluster edges.

---

## Formal Methods — GR + SR Foundation

The framework is fully derived from Einstein’s field equations with the Darkness stress-energy tensor. The shear stress evolves via the Maxwell-Cattaneo constitutive relation.

**Special Relativity Limit**  
In locally flat spacetime the theory reduces to special-relativistic viscoelastic hydrodynamics satisfying Minkowski-space conservation and the Lorentz-covariant Maxwell-Cattaneo equation. This guarantees strict causality and Lorentz invariance. The full GR theory is a consistent curved-spacetime generalization.

---

## Final Cosmological Pillars

- **The End of Voids**: Voids contain the most elastic state of the Darkness, providing a natural lower bound that prevents cosmic tearing.
- **Entropy without Heat Death**: Energy recycling through Frozen Cores suggests a cyclic or steady-flow universe.

The natural "coldness" of the Darkness — its relaxed, low-energy elastic state — acts as the supportive baseline that balances the perturbations caused by baryonic mass.

---

## Conclusion

Logic Relativity v2.5 unifies cosmic expansion, structure formation, rotation curves, gravitational waves, black hole interiors, void stability, and long-term cosmic evolution through one viscoelastic medium fully consistent with both General and Special Relativity.

**No dark matter particles. No separate vacuum energy. Only mass matters.**

---

## Repository Contents

- `docs/LR_v2.5_Full_Suite.md` — Main paper
- `simulations/` — Colab notebooks and raw data
- `figures/` — All simulation plots

## Citation

```bibtex
@misc{pieterse2026logic,
  title        = {Logic Relativity (LR) v2.5: Unified Cosmological Framework},
  author       = {Thinus Pieterse},
  year         = {2026},
  doi          = {10.5281/zenodo.20185320},
  url          = {https://github.com/thinus283-ux/LR}
}

Zenodo Record: https://doi.org/10.5281/zenodo.20185320License: Creative Commons Attribution 4.0 International (CC BY 4.0)
---

## Logic Relativity (LR) v3.5.1: A Covariant, Action-Derived Viscoelastic Field Theory Replacing the Dark Sector

**Title:** Logic Relativity (LR) v3.5.1: A Covariant, Action-Derived Viscoelastic Field Theory Replacing the Dark Sector

**Abstract:**  
Logic Relativity v3.5.1 presents a mathematically complete and numerically validated cosmological framework in which dark matter and dark energy emerge from the viscoelastic response of a single cosmic medium (“The Darkness”) to baryonic mass. All dynamics are derived from a diffeomorphism-invariant action using extended irreversible thermodynamics. General covariance is enforced by a projected Lie derivative in the Maxwell-Cattaneo constitutive relation. Finite relaxation times generate retarded density wakes that naturally produce flat rotation curves and accelerated early structure formation matching JWST observations. At extreme densities the logistic kernel saturates, forming stable non-singular “Frozen Cores” (confirmed in collapse simulations). A minimal electromagnetic coupling predicts observable chromatic boundary lensing, a clear falsifiable signature. LR v3.5.1 is a closed, self-consistent, simulation-tested alternative field theory.

**Core Principle:** *Only mass matters.* Dark matter and dark energy emerge entirely from the viscoelastic response of a single cosmic medium — “The Darkness” — to baryonic mass.

### Metric Convention
We adopt the mostly-plus signature (−, +, +, +).

### 1. Fundamental Action
$$
\mathcal{S} = \frac{1}{16\pi} \int d^4x \sqrt{-g}\, R + \mathcal{S}_{\rm baryon} + \mathcal{S}_{\rm Darkness} + \mathcal{S}_{\rm EM}
$$

**Darkness Lagrangian density:**
$$
\mathcal{L}_{\rm Darkness} = -\rho(\delta) - \frac{1}{2} \pi_{\alpha\beta}\pi^{\alpha\beta} - \frac{\tau_v(\delta)}{4} (\mathcal{D}\pi_{\alpha\beta})(\mathcal{D}\pi^{\alpha\beta}) + \eta(\delta) \, \pi_{\alpha\beta}\sigma^{\alpha\beta}
$$

**Electromagnetic coupling:**
$$
\mathcal{S}_{\rm EM} = -\frac{1}{4} \int d^4x \sqrt{-g} \, \mathcal{F}(\delta) \, F_{\alpha\beta}F^{\alpha\beta},
$$
where
$$
\mathcal{F}(\delta) = 1 + \alpha \, (\nabla_\lambda\delta)(\nabla^\lambda\delta) + \beta\eta(\delta)
$$
and \(\alpha\) and \(\beta\) are small dimensionless coupling constants (\(|\alpha|, |\beta| \ll 1\)) constrained by gamma-ray burst timing and lensing observations. \(\delta\) is the baryonic density contrast computed with the proper volume element, and \(\eta(\delta)\), \(\tau_v(\delta)\), \(\rho(\delta)\) are modulated by the smooth logistic kernel \(\mathcal{R}(\delta)\).

### 2. Master Field Equations

**Einstein Field Equation (\(\Lambda = 0\)):**
$$
G_{\mu\nu} = 8\pi \left( T_{\mu\nu}^{\rm baryon} + T_{\mu\nu}^{\rm Darkness} \right)
$$

**Darkness Stress-Energy Tensor:**
$$
T_{\mu\nu}^{\rm Darkness} = (\rho(\delta) + p(\delta)) u_\mu u_\nu + p(\delta) g_{\mu\nu} + \pi_{\mu\nu}
$$

**Covariant Maxwell-Cattaneo Constitutive Relation:**
$$
\tau_v(\delta) \, \mathcal{D} \pi^{\mu\nu} + \pi^{\mu\nu} = 2\eta(\delta) \, \sigma^{\mu\nu}
$$

**Projected Lie Derivative (Covariant Rate Operator):**
$$
\mathcal{D} \pi^{\mu\nu} = \Delta^\mu{}_\alpha \Delta^\nu{}_\beta \Bigl( u^\lambda \nabla_\lambda \pi^{\alpha\beta} + \pi^{\lambda\beta} \nabla_\lambda u^\alpha + \pi^{\alpha\lambda} \nabla_\lambda u^\beta \Bigr)
$$

**Shear Tensor:**
$$
\sigma^{\mu\nu} = \Delta^\mu{}_\alpha \Delta^\nu{}_\beta \nabla^{(\alpha} u^{\beta)} - \frac{1}{3} \Delta^{\mu\nu} \theta, \quad \theta = \nabla_\lambda u^\lambda
$$

**Projector:**
$$
\Delta^\mu{}_\nu = \delta^\mu{}_\nu + u^\mu u_\nu
$$

**Modified Photon Ray Equation (Chromatic Boundary Lensing):**
$$
\frac{D k^\mu}{d\lambda} = -\frac{1}{2} g^{\mu\nu} \partial_\nu \ln\mathcal{F}(\delta) \,(k^\alpha k_\alpha) - \frac{\beta}{2} (\partial^\mu\eta(\delta)) (u^\gamma k_\gamma)^2
$$

### 3. Geometric & Thermodynamic Consistency
- **General Covariance:** The projected Lie derivative \(\mathcal{D}\) guarantees frame-indifference in all coordinate systems, including near event horizons.
- **Second Law of Thermodynamics:** \(\pi_{\mu\nu}\sigma^{\mu\nu} \geq 0\) holds globally whenever \(\eta(\delta) > 0\).

### 4. Momentum Exchange & Lagging Wake
$$
\nabla_\mu T^{\mu\nu}_{\rm Darkness} = -Q^\nu
$$

**Newtonian tracking acceleration:**
$$
\mathbf{a}_{\rm wake} = -\frac{4\pi G \eta(\delta) \tau_v(\delta)}{1 + \tau_v(\delta) \partial_t} \Bigl( \nabla^2 \mathbf{v} + \frac{\partial\mathbf{v}}{\partial t} \Bigr) + \text{retarded gravitational pull from trailing wake}
$$

### 5. Frozen Core Singularity Resolution
At \(\delta \to \delta_{\rm crit}\):
- \(\tau_v(\delta) \to 0\) exponentially,
- \(\pi^{\mu\nu} \to 0\),
- Pressure \(p(\delta)\) saturates.

**Interior metric (regular, non-singular):**
$$
ds^2 = -e^{2\Phi(r)} dt^2 + \left(1 - \frac{2m(r)}{r}\right)^{-1} dr^2 + r^2 d\Omega^2
$$
with finite central mass \(m(0)\) and bounded curvature invariants. High-resolution 1D radial collapse simulations confirm density plateaus at \(\rho_{\rm max}\) with shock-front formation and no singularity.

### 6. Key Predictions & Falsifiability
- Flat galactic rotation curves via lagging wake (no dark matter particles)
- Accelerated early galaxy formation consistent with JWST halo mass function and UV luminosity
- Chromatic boundary lensing: distinct deflection angles for radio, optical, and X-ray photons at density gradients
- High-frequency primordial gravitational wave damping (LIGO bands unaffected)
- Stable cosmic voids
- Non-singular Frozen Cores (numerically verified)
**This v3.5.1 update builds directly on the existing v2.5 framework already documented above.** It provides the fully covariant, action-principle derivation while preserving all simulation-validated predictions (lagging wakes, Frozen Cores, chromatic lensing, etc.). All prior Colab notebooks and figures in `/simulations/` and `/figures/` remain fully compatible; v3.5.1 is the rigorous field-theoretic foundation that unifies them.



