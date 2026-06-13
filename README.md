# Logic Relativity (LR)

**A Minimal Relativistic Superfluid Framework for Spacetime, Matter, and Cosmology**  
*Independent theoretical and numerical research — Work in progress*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/thinus283-ux/LR)
[![GitHub stars](https://img.shields.io/github/stars/thinus283-ux/LR?style=social)](https://github.com/thinus283-ux/LR/stargazers)

> “Spacetime tells matter how to move; matter tells spacetime how to curve.”  
> — John Archibald Wheeler

Baryonic matter displaces a single, nearly incompressible relativistic superfluid — the **Exotic Displacement Field**. All geometry, curvature, particles, dynamics, and the arrow of time emerge from its hydrodynamic behavior, vorticity, and non-linear responses. The framework is strictly minimal: one fundamental field, one action, no additional fundamental scalars or particles.

---

## Abstract

Logic Relativity proposes a continuum effective field theory in which spacetime and matter arise as collective excitations of a single relativistic superfluid. The theory recovers General Relativity in high-density regimes via Vainshtein-like screening while providing a natural mechanism for flat galactic rotation curves through topological stress sourced by displacement vorticity. Numerical implementations on the SPARC galaxy sample yield a median RMS residual of **4.82 km/s** across 174 galaxies. Preliminary cosmological analyses show substantial reduction in Hubble and S₈ tensions. Compact objects terminate in non-singular rotating topological solitons. All results are reproducible via publicly available Jupyter notebooks.

---

## Theoretical Framework

### Ontological Foundations

1. The Exotic Displacement Field is a single nearly incompressible relativistic superfluid characterized by background density ρ₀ and finite sound speed cₛ.
2. Matter and fields correspond to dynamic displacement excitations (“bubbles”) within this fluid.
3. High density or vorticity triggers non-linear hydrodynamic responses and topological transitions that stabilize structure.
4. The theory is formulated as a consistent effective continuum hydrodynamic field theory. The vorticity 2-form is closed in irrotational and weakly turbulent regimes; non-linear response provides screening of topological effects at high density.

The velocity potential φ, 4-velocity u^μ, stiffness deformation σ, and Kalb-Ramond field B_μν represent distinct hydrodynamic and geometric degrees of freedom of the single underlying field.

### Fundamental Action

```math
S = \int d^4x \sqrt{-g} \Bigg[
\frac{R}{16\pi G}
- \rho_0 \sqrt{1 - \frac{1}{2c_s^2} g^{\mu\nu} \partial_\mu \phi \partial_\nu \phi}
- \lambda(x) (\nabla_\mu u^\mu)
- \frac{\kappa}{2} (\nabla_\mu u^\mu)^2
- V(\sigma)
- \frac{1}{12} H_{\mu\nu\lambda} H^{\mu\nu\lambda}
- \alpha \, F(\partial u) \wedge B
- \xi R \sigma
\Bigg]
```

where:
- First term: Einstein-Hilbert
- Second term: K-essence-like kinetic term for the displacement field
- Remaining terms: Lagrange multiplier for incompressibility, stiffness potential, Kalb-Ramond field strength, topological coupling to displacement vorticity, and non-minimal curvature coupling.

### Field Equations (from explicit variation)

**Modified Einstein equations**
```math
G_{\mu\nu} + \Lambda_{\rm eff} g_{\mu\nu} = 8\pi G_{\rm eff} \left( T_{\mu\nu}^{\rm fluid} + \mathcal{T}_{\mu\nu}^{\rm topology} \right)
```

**Kalb-Ramond equation**
```math
\nabla^\lambda H_{\lambda\mu\nu} + \alpha \, F_{\mu\nu}(\partial u) = 0
```

The topological stress-energy tensor sourced by displacement vorticity provides the additional gravitational effect observed in galactic rotation curves while remaining screened in the solar system.

### Key Mechanisms

- **Galactic dynamics**: Topological stress from the Kalb-Ramond sector clamps rotation curves in low-density regimes.
- **Solar-system recovery**: Non-linear fluid response + Vainshtein-like screening restores standard PPN parameters (γ ≈ 1, β ≈ 1) at high density.
- **Compact objects**: Gravitational collapse terminates in stable, non-singular rotating layered echo-cavity topological solitons carrying angular momentum via coherent rotation and quantized vortices. The exterior geometry approaches the Kerr metric at large distances.
- **Cosmology & arrow of time**: The universe begins in a maximally compressed, high-tension state. Explosive tension release generates acoustic shockwaves; primordial particles emerge as self-trapped standing waves. Irreversible tension release and vorticity dissipation establish the cosmological and thermodynamic arrows of time. Time dilation acts as an active regulator, suppressing density evolution in dense regions and preventing singularities.
- **Particle emergence**: Acoustic excitations on the effective fluid metric freeze out as elementary particles.

---

## Numerical Validation & Results

All results below are obtained from the public notebooks in this repository and are fully reproducible.

### SPARC Galaxy Rotation Curves (175 galaxies)

- **Data**: Official SPARC `Rotmod_LTG.zip` (publicly available)
- **Method**: Custom composite model combining baryonic contributions with stress and vortex-clamping profiles; `scipy.optimize.curve_fit` with morphology-adaptive initial guesses and multi-start rescue
- **Results** (preliminary):
  - Galaxies successfully fitted: 174
  - **Median RMS**: 4.82 km/s
  - **Mean RMS**: 6.73 km/s
  - 43 galaxies < 3 km/s
  - 66 galaxies < 4 km/s
  - 89 galaxies < 5 km/s
  - Best: 0.09 km/s | Worst: 38.44 km/s

These residuals are competitive with or better than many standard NFW-based ΛCDM fits reported in the literature for the same sample. Full per-galaxy fits, residuals, and comparison tables are available in the notebooks.

### Cosmological Tensions (preliminary MCMC analyses)

- Hubble tension reduced to ~0.1σ level in current implementation
- S₈ tension reduced to ~1.8σ level
- Full chains, priors, and comparison runs available in `Mcmc_Hubble_s8_tention.ipynb` and related notebooks

### Compact Objects — Modified TOV

- Successful numerical integration across multiple parameter sets (central densities 10¹⁴–10¹⁶ g/cm³, γ ≈ 2.0–2.6)
- Finite, non-singular cores demonstrated (typical radii 200–500 km in macroscopic examples)
- Density profiles flatten at the core due to stiff equation-of-state saturation and time-dilation regulation
- Rotation support qualitatively increases effective radius and stability
- No mathematical singularity at r = 0

### Theoretical Consistency Checks

- PPN parameters recovered: γ ≈ 1, β ≈ 1 (screened at solar-system densities)
- Linear stability analysis around FLRW backgrounds: no ghosts or gradient instabilities
- Stiff-matter limit approached from below with transition rate outpacing potential instability growth
- Causality preserved (signal propagation bounded by c)

All stability, PPN, and ghost-free notebooks are included.

---

## Repository Structure (Recommended)

```
LR/
├── README.md
├── LICENSE
├── .gitignore
├── requirements.txt          # or environment.yml
├── notebooks/
│   ├── data/                 # SPARC data handling
│   ├── SPARC/
│   │   ├── SPARC_data.ipynb
│   │   ├── Real_SPARC_galaxies.ipynb
│   │   ├── 175_SPARC_test.ipynb
│   │   └── H1_175_SPARC_galaxy_results.ipynb
│   ├── Cosmology/
│   │   ├── Cosmology_solver.ipynb
│   │   ├── Mcmc_Hubble_s8_tention.ipynb
│   │   └── S8_Hubble_tention.ipynb
│   ├── Compact_Objects/
│   │   └── TOV_test.ipynb
│   ├── Stability/
│   │   ├── Ghost_free_stability_check.ipynb
│   │   ├── No_ghost_test.ipynb
│   │   └── K_essence_stability_check.ipynb
│   ├── Gravity_Tests/
│   │   ├── PPN.ipynb
│   │   ├── Gravitational_lensing_test.ipynb
│   │   ├── Weak_lensing_test.ipynb
│   │   └── Bullet_cluster_test.ipynb
│   └── CMB/
│       ├── CMB_TT_ET.ipynb
│       └── Full_CMB_power_spectrum_test.ipynb
├── figures/                  # Exported high-quality plots (PNG/SVG)
├── src/                      # Future: core Python modules extracted from notebooks
├── docs/                     # Paper draft, extended appendices (future)
└── data/                     # Cached or processed datasets (optional)
```

**Current state**: All notebooks are in the root for rapid development. Migration to the above structure is in progress.

---

## Getting Started

### Quick Run (Google Colab — recommended)
1. Open any notebook directly from the repository.
2. Click “Open in Colab”.
3. Run cells sequentially. Data is downloaded automatically where needed.

### Local Installation
```bash
git clone https://github.com/thinus283-ux/LR.git
cd LR
pip install -r requirements.txt
jupyter notebook
```

Core dependencies: `numpy`, `scipy`, `matplotlib`, `emcee` (for MCMC notebooks), `astropy` (optional).

---

## Limitations & Open Questions (Transparency)

- The current SPARC implementation uses a phenomenological stress + vortex-clamping profile. A fully derived effective description from the action is under development.
- Cosmological tension results are preliminary; full covariance analysis and extended datasets are ongoing.
- The topological sector requires further analytic work on degrees of freedom and quantization.
- Systematic comparison against MOND, superfluid dark matter, and other alternatives is planned.
- No claims are made of finality. This is active research.

Feedback, scrutiny, and collaboration are welcome.

---

## Roadmap

- [ ] Extract core functions into reusable Python modules (`src/`)
- [ ] Generate and embed publication-quality figures in README and notebooks
- [ ] Complete per-galaxy residual plots and comparison tables
- [ ] Full MCMC pipeline with publication-ready corner plots and statistics
- [ ] Extended TOV + rotation + GW echo predictions
- [ ] Draft manuscript / arXiv preprint
- [ ] Community discussion (Issues enabled)

---

## Appendices (Summary)

Detailed derivations of the action variation, fluid + topological stress-energy tensors, acoustic metric, high-density equation of state, time-dilation regulation, thermodynamic relations, explicit PPN parameters, and topologically protected vorticity currents are provided in the original long-form appendices within the repository notebooks and will be migrated to `docs/`.

---

## Citation

If you use or reference this work, please cite the repository and relevant notebooks:

```bibtex
@software{LR2026,
  author = {Thinus Pieterse},
  title  = {Logic Relativity: A Minimal Relativistic Superfluid Framework},
  url    = {https://github.com/thinus283-ux/LR},
  year   = {2026}
}
```

---

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

**Contact / Discussion**  
Open an Issue or start a Discussion on this repository. All constructive feedback is appreciated.

*Last major update: June 2026*
```

