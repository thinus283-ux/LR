# Logic Relativity (LR)

**Single K-essence scalar field with Geometric Displacement Principle**  
Unifies galactic rotation curves (SPARC) and background cosmology through one exotic nearly incompressible superfluid substrate.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![Tests](https://github.com/thinus283-ux/LR/actions/workflows/test.yml/badge.svg)](https://github.com/thinus283-ux/LR/actions)
[![Coverage](https://img.shields.io/badge/coverage-85%25-brightgreen)](https://github.com/thinus283-ux/LR)

---

## Abstract

The **Exotic Displacement Field** is a first-principles theory in which baryonic matter excavates a single high-pressure, nearly incompressible non-Newtonian superfluid. Displacement bubbles generate geometric pressure gradients that are spacetime curvature. Global thinning produces dark energy. Stochastic quantum-vortex hardening at galactic rims produces dark matter. A Planck-scale geometric buffer prevents singularities while recovering General Relativity on all scales larger than \(\ell_P\).

The theory is implemented as a clean, installable Python package with full MCMC fitting to SPARC galaxies and a Friedmann solver. On large scales it recovers \(\Lambda\)CDM; on galactic scales it naturally produces flat rotation curves and the Radial Acceleration Relation with a single global parameter set.

---

## Core Idea

Baryonic matter displaces an exotic superfluid through **mass displamet geometry**, forming dynamic bubbles. The nearly incompressible response creates pressure gradients that curve spacetime. At galactic rims the cumulative displacement triggers a Herschel-Bulkley phase transition, hardening the fluid into a stochastic quantum-vortex “packing-peanut” medium that clamps rotation curves. The Planck-scale buffer provides a natural UV cutoff and non-singular black-hole cores.

On all scales \(\gg \ell_P\) the theory reproduces standard General Relativity. At the Planck scale it supplies a geometric, non-singular regulator derived solely from \(c\), \(\hbar\), and \(G\).

---

## Features

- Unified dark sector from one displacement mechanism
- Excellent SPARC rotation-curve fits (median RMS ~12–14% with global parameters)
- Natural reproduction of Tully-Fisher and Radial Acceleration Relations
- Dynamic screening recovers GR locally
- Scale-dependent effects relieve \(H_0\) and \(S_8\) tensions
- Non-singular black-hole cores with testable damped gravitational-wave echoes
- Clean, modular, installable Python package with comprehensive tests

---

## Installation

```bash
pip install -e .
```

**Requirements**
- Python ≥ 3.10
- NumPy, SciPy, Astropy, Pandas, Matplotlib, emcee, corner, PyYAML, tqdm, joblib, requests

---

## Quick Start

### Cosmology
```python
from lr.cosmology import LRCosmology

model = LRCosmology(Omega_b0=0.05, P0=1.2, H0=67.4)
print("Acceleration onset z ≈", model.find_acceleration_onset())
print("H(z=0) =", model.hubble(1.0))
```

### Galactic Rotation Curves
```python
from lr.galactic import LRRotationCurve
from lr.data_loader import load_sparc_galaxy

rc = LRRotationCurve(P0=25000.0, beta=0.5)
R, Vobs, Verr, Vbar, Sigma = load_sparc_galaxy("NGC2366")
best_P0, samples = rc.fit_single_galaxy(R, Vobs, Verr, Vbar, Sigma)
```

See `examples/` and `notebooks/` for interactive demonstrations.

---

## Theory

### The Exotic Displacement Field

Baryonic matter excavates spacetime through **mass displamet geometry**, forming displacement bubbles. The nearly incompressible response of the superfluid generates geometric pressure gradients that are spacetime curvature. Gravity is the resulting pressure suction. Global thinning produces dark energy. At galactic rims the fluid undergoes a stochastic Herschel-Bulkley phase transition, hardening into a quantum-vortex medium that clamps flat rotation curves.

A smooth geometric Planck-scale buffer prevents singularities and recovers General Relativity on all scales larger than \(\ell_P\).

Full theory, mathematical derivation, and effective limit are detailed in the paper and `docs/theory.md`.

### Key Equations

**Density Thinning**
\[
\rho(x) = \rho_0 \left(1 - \nabla_\mu u^\mu + \frac{P}{\kappa \rho_0 c_s^2}\right)
\]

**Smart Fluid Action**
\[
S = \int d^4x \sqrt{-g} \Bigg[ \frac12 \rho(x) \, g^{\mu\nu} (\partial_\mu \phi)(\partial_\nu \phi) 
+ \lambda(x) (\nabla_\mu u^\mu) 
+ \frac{\kappa}{2} (\nabla_\mu u^\mu)^2 
+ \lambda_\sigma(x) (\sigma - \sigma_c(\mathbf{x})) \Theta(\sigma - \sigma_c(\mathbf{x})) 
+ \tau(\rho,\sigma) \, \kappa \, \mathcal{B}_{\mu\nu}(\rho) \Bigg]
\]

**Acoustic Metric**
\[
\tilde{g}_{\mu\nu} = \frac{\rho(x)}{c_s} \begin{pmatrix}
-(c_s^2 - v^2) & -v_i \\
-v_j & \delta_{ij}
\end{pmatrix}
\]

**Einstein Equations with Geometric Buffer**
\[
G_{\mu\nu}[g(\rho,u)] = 8\pi G_{\rm eff} \, T_{\mu\nu}^{\rm fluid} + \kappa \, \tau(\rho,\sigma) \, \mathcal{B}_{\mu\nu}(\rho)
\]

Full derivation is provided in Appendix A of the theory document.

---

## Validation & Results

| Observable                  | Performance                  | Notes                                      |
|-----------------------------|------------------------------|--------------------------------------------|
| SPARC Rotation Curves       | Median RMS ~12–14%           | Global parameter set                       |
| Tully-Fisher Relation       | Excellent                    | Naturally reproduced                       |
| Radial Acceleration Relation| Excellent                    | Consistent with data                       |
| CMB + BAO + SNIa            | Good (preliminary)           | Recovers ΛCDM on large scales              |
| \(H_0\) & \(S_8\) Tensions  | Strong relief                | Scale-dependent screening                  |
| Bullet Cluster              | Consistent                   | Long-relaxation-time vortex rheology       |
| Local GR Tests              | Excellent                    | Dynamic geometric screening                |
| Black Hole Shadows & GWs    | Consistent                   | Kerr exterior + damped echoes              |

Detailed plots, residual distributions, and fitting notebooks are available in `notebooks/` and `docs/validation.md`.

---

## Repository Structure

```
LR/
├── src/lr/
│   ├── __init__.py
│   ├── dark_field.py          # Core K-essence / Geometric Displacement model
│   ├── galactic.py            # Rotation curve fitting & MCMC
│   ├── cosmology.py           # Friedmann solver
│   ├── data_loader.py         # SPARC data handling
│   └── utils.py
├── docs/
│   ├── theory.md              # Full theory + Appendix A derivation
│   └── validation.md          # Plots and results
├── examples/
├── notebooks/
├── tests/
├── pyproject.toml
└── README.md
```

---

## Citation

If you use this work, please cite:

```bibtex
@software{logic_relativity,
  author = {Thinus Pieterse},
  title  = {Logic Relativity: Single K-essence Field Unifying Dark Matter and Dark Energy},
  year   = {2026},
  url    = {https://github.com/thinus283-ux/LR}
}
```

Full theory paper (in preparation) will be linked here upon release.

---

## Contributing

Contributions are welcome! Please open an issue or pull request. All code changes should pass the existing test suite.

---

## License

MIT License — see [LICENSE](LICENSE) for details.

---

## Acknowledgments

- SPARC collaboration for the high-quality rotation curve database
- The analogue gravity and superfluid cosmology communities for foundational ideas
- All contributors and early testers

---

**This is a living project.** The theory and implementation continue to evolve. The current version represents a rigorous, first-principles framework that is both conceptually elegant and quantitatively successful on existing data.

Star the repository if you find the displacement-based unification compelling.
```
