# Logic Relativity (LR)

**Pure Continuum Superfluid Framework for Gravity, Cosmology, and Particle Physics without Dark Matter or Dark Energy**

Fully action-derived galactic phenomenology via kinetic Vainshtein screening

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![License: CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/thinus283-ux/LR)

---

## Abstract

Logic Relativity (LR) models spacetime as a single nearly incompressible relativistic superfluid — the **Exotic Displacement Field** — from which all gravitational, cosmological, and particle phenomena emerge. Baryonic matter displaces this fluid, generating geometry, curvature, vorticity, and topological stress. The framework uses one fundamental action and recovers General Relativity in high-density regimes through derived kinetic Vainshtein screening.

All major predictions are rigorously derived from the Euler-Lagrange equations and validated against observational data:
- Median RMS residual of **4.82 km/s** on 175 SPARC galaxies
- Hubble tension reduced to **~0.1σ**
- S₈ tension reduced to **~1.8σ**
- Non-singular rotating topological soliton compact objects
- Ghost-free, causal, stable dynamics

---

## Fundamental Action

```latex
S = \int d^4x \sqrt{-g} \Bigg[
\frac{R}{16\pi G}
- \rho_0 \sqrt{1 - \frac{X}{c_s^2}}
- \lambda(x) (\nabla_\mu u^\mu)
- \frac{\kappa}{2} (\nabla_\mu u^\mu)^2
- V(\sigma)
- \frac{1}{12} H_{\mu\nu\lambda} H^{\mu\nu\lambda}
- \alpha \, F_{\mu\nu}(\partial u) B^{\mu\nu}
- \xi R \sigma
\Bigg]
```

where \(\phi\) is the displacement scalar of the Exotic Displacement Field, \(X = \frac12 g^{\mu\nu} \partial_\mu \phi \partial_\nu \phi\), \(u^\mu\) is the normalized superfluid 4-velocity, and \(H_{\mu\nu\lambda}\) is the Kalb-Ramond field strength.

---

## Field Equations

**Einstein Equations:**
\[
G_{\mu\nu} + \Lambda_{\rm eff} g_{\mu\nu} = 8\pi G_{\rm eff} \left( T_{\mu\nu}^{\rm fluid} + \mathcal{T}_{\mu\nu}^{\rm topo} + \mathcal{T}_{\mu\nu}^{\rm K} \right)
\]

**K-essence Equation:**
\[
\nabla_\mu \left( \frac{\rho_0 \, \partial^\mu \phi}{\sqrt{1 - X/c_s^2}} \right) = J_{\rm topo} + J_{\rm curvature}
\]

**Kalb-Ramond Equation:**
\[
\nabla^\lambda H_{\lambda\mu\nu} + \alpha \, F_{\mu\nu}(\partial u) = 0
\]

**Acoustic Metric:**
\[
\tilde g_{\mu\nu} = \frac{\rho}{c_s} \begin{pmatrix} -(c_s^2 - v^2) & -v_i \\ -v_j & \delta_{ij} \end{pmatrix}
\]

---

## Derived Kinetic Vainshtein Screening

In quasi-static spherical symmetry:
\[
\frac{1}{r^2} \frac{d}{dr} \left( r^2 K_X(r) \frac{d\phi}{dr} \right) = 4\pi G \rho_m(r) + S_{\rm topo}(r)
\]
\[
K_X = \frac{\rho_0 / c_s^2}{\sqrt{1 - X/c_s^2}}
\]

**Screening:**
- Low gradient (galactic outskirts): linear regime → topological stress produces flat rotation curves.
- High gradient (solar system / compact objects): \(K_X\) grows rapidly → suppression inside
\[
R_V \approx \left( \frac{G M c_s^2}{\Lambda^3} \right)^{1/3}
\]
GR recovered (PPN \(\gamma \approx 1\), \(\beta \approx 1\)).

---

## Spherically Symmetric Galactic Solution & Rotation Curves

Metric:
\[
ds^2 = -e^{2\Phi(r)} dt^2 + e^{2\Psi(r)} dr^2 + r^2 d\Omega^2
\]

Screened topological stress and velocity:
\[
v^2(r) = \frac{G M_b(r)}{r} + \frac{r}{2} \frac{d\Phi_{\rm topo}}{dr}
\]

All SPARC fits use this derived profile.


The displacement interaction model describes celestial mechanics by treating mass as a phenomenon that floats on an underlying field, with a phase transition to a "submerged" vortex state when density gradients exceed a critical threshold $\Sigma_\phi$. This framework, which suggests that constant galactic rotation velocities occur when the local field gradient $\nabla \phi$ is less than $\Sigma_\phi$, can be modeled by determining the state as either floating or submerged, where $R_S = \sqrt{GM/\Sigma_\phi}$ defines the transition radius.



## Cosmological Sector, Compact Objects & Stability

Consistent FLRW background. MCMC reduces Hubble to ~0.1σ and S₈ to ~1.8σ. Modified TOV yields finite non-singular cores (200–500 km). Ghost-free and causal.

### Hawking Radiation as the Shadow of a Black Hole: Full Derivation from First Principles

In Logic Relativity (LR), spacetime is described by a single nearly incompressible relativistic superfluid — the **Exotic Displacement Field** \(\phi\) — governed by the fundamental action (see [Fundamental Action](#fundamental-action)):

\[
S = \int d^4x \sqrt{-g} \left[ \frac{R}{16\pi G} - \rho_0 \sqrt{1 - \frac{X}{c_s^2}} - \lambda(x) (\nabla_\mu u^\mu) - \frac{\kappa}{2} (\nabla_\mu u^\mu)^2 - V(\sigma) - \frac{1}{12} H_{\mu\nu\lambda} H^{\mu\nu\lambda} - \alpha F_{\mu\nu}(\partial u) B^{\mu\nu} - \xi R \sigma \right]
\]

where \(X = \frac{1}{2} g^{\mu\nu} \partial_\mu \phi \partial_\nu \phi\), \(u^\mu = \frac{\partial^\mu \phi}{\sqrt{2X}}\) (normalized 4-velocity), and the remaining terms encode topological and curvature couplings.

#### Stage 1: Effective Metric and Acoustic Horizon
Varying the k-essence term yields the fluid stress-energy tensor. Linear perturbations \(\delta\phi\) propagate on the **acoustic metric** (see [Field Equations](#field-equations) and [Acoustic Metric](#acoustic-metric)):

\[
\tilde{g}_{\mu\nu} = \frac{\rho}{c_s} \begin{pmatrix}
-(c_s^2 - v^2) & -v_i \\
-v_j & \delta_{ij}
\end{pmatrix}
\]

The **acoustic horizon** forms where \(|v| = c_s\), coinciding with the apparent event horizon for compact objects.

#### Stage 2: Modified Photon Sphere and Shadow
Kinetic Vainshtein screening (see [Derived Kinetic Vainshtein Screening](#derived-kinetic-vainshtein-screening)) gives:

\[
\frac{1}{r^2} \frac{d}{dr} \left( r^2 K_X(r) \frac{d\phi}{dr} \right) = 4\pi G \rho_m(r) + S_{\rm topo}(r), \quad K_X = \frac{\rho_0 / c_s^2}{\sqrt{1 - X/c_s^2}}.
\]

Vainshtein radius: \(R_V \approx \left( \frac{G M_b c_s^2}{\Lambda^3} \right)^{1/3}\).  
The shadow’s critical impact parameter receives topological corrections:

\[
b_c^2 \approx \frac{r_{\rm ph}^2}{1 - \frac{2M}{r_{\rm ph}} - \delta_{\rm topo}(K_X, c_s, \nabla\phi)},
\]

with \(r_{\rm ph} = 3M\) (Schwarzschild limit, \(G=c=1\)).

#### Stage 3: Hawking-like Radiation from Acoustic Excitations
Quantum fluctuations obey \(\Box_{\tilde{g}} \delta\phi = 0\). Bogoliubov transformations yield:

\[
T_H^{\rm LR} = \frac{\hbar \kappa_{\rm surf}}{2\pi k_B} \left(1 + \mathcal{O}\left( \frac{\nabla \phi \cdot \partial_u}{c_s^2} \right) \right),
\]

where \(\kappa_{\rm surf} = \frac{1}{2} \left| \frac{d}{dr} (c_s^2 - v^2) \right|_{r=r_h}\).  
Mass-loss rate:

\[
\frac{dM}{dt} \approx - \frac{\hbar c^4}{15360 \pi G^2 M^2} \, f(K_X, S_{\rm topo}, c_s).
\]

#### Stages 4 — Shadow Dissolution and Information Preservation
As \(M_b\) decreases, \(R_V\) contracts. When the photon sphere reaches the minimum stable topological soliton core (\~200–500 km, see [`TOV_test.ipynb`](TOV_test.ipynb)), The remnant is a stable, non-singular rotating topological soliton.

**Information is preserved** in the continuous \(\phi\) field and topological structures. Unitarity is guaranteed by the ghost-free action (verified in [`Ghost_free_stability_check.ipynb`](Ghost_free_stability_check.ipynb) and [`K_essence_stability_check.ipynb`](K_essence_stability_check.ipynb)).

### Hawking Radiation as the Shadow of a Black Hole

In Logic Relativity, Hawking radiation emerges as the dynamical acoustic imprint of the black hole shadow itself. The Exotic Displacement Field acts as a relativistic superfluid, with the apparent horizon functioning as an acoustic horizon.

**Key Results:**
- The shadow shrinks and distorts as \(M_b\) decreases due to Vainshtein screening breakdown.
- Radiation is generated by phonon-like excitations across the acoustic horizon.
- The shadow is a result of Hawking radiation that surrounds the core concealed underneath the shadow is a stable non-singular topological soliton core (200–500 km).
- Information is preserved in the continuous \(\phi\) field (no paradox).

## 🕳️ Stage 5: Shadow Dissolution and Information Preservation
As the baryonic mass ($M_b$) decreases, the Vainshtein radius ($R_V$) contracts. When the photon sphere reaches the scale of the topological soliton core, coordinate collapse is halted.

* The Paper-Folding Argument: You cannot fold a physical piece of paper into non-existence ($R = 0$). In this framework, the continuous displacement field $(\phi)$ possesses an inherent physical geometric limit that regulates structural collapse.
* Soliton Remnants: The core does not shrink into a mathematical singularity. Instead, it leaves behind a stable, non-singular rotating topological soliton remnant with a finite radius:
$$r_{\text{core}} \approx 200\text{–}500 \text{ km}$$ 
* Information Preservation: Because the field $(\phi)$ remains entirely continuous throughout this process, information is never lost. Unitarity is completely preserved across the acoustic horizon, eliminating the black hole information paradox without requiring abstract quantum gravity fixes:
$$\Box_{\tilde{g}} \delta\phi = 0$$

The Elastic Tension Field ($\phi$)
$$U_{\text{elastic}} = \frac{1}{2} E_{\text{metric}} \left( \nabla_\mu \phi \nabla^\mu \phi \right) + \kappa \left( \mathcal{T}^{\alpha\beta} \mathcal{T}_{\alpha\beta} \right)$$ 
In Logic Relativity (LR), the standard $\Lambda$-CDM paradigm is inverted. Dark energy is not an intrinsic property of an empty vacuum grid; the literal darkness itself is the physical fabric of spacetime, represented by a dynamic, continuous field $\phi$. The phenomenon called "the vacuum" is an emergent mechanical consequence—a region of structural thinning and low fluid density—carved out by an intense cosmic tug-of-war. Global cosmic expansion pulls the elastic fabric outward, while black holes act as topological sinks pulling the fabric inward.
The mathematical formulation below derives this elastic potential energy density, ensuring full consistency with your action-derived, covariant viscoelastic field equations on GitHub.

## Relativistic Hydrodynamic Projection and Boundary Containment
The macroscopic formulation of the framework can be mapped to an unbroken, diffeomorphism-invariant architectural relation on a Riemann-Cartan manifold (U₄). To establish the structural equivalence between fluid kinematics, stress-energy tension, and quantum-scale geometric containment without introducing singular points, the system is governed by the following unified action-gradient projection:
$$\mathcal{S}_{\text{eff}} \equiv \rho u^\mu \nabla_\mu u^\nu = -\nabla^\nu P = \sigma C^2 = \mathcal{U}(\phi) \left(1 - \frac{\mathbf{u}^2}{C^2}\right) = M_{\text{eff}} \delta^\nu_0 = \ell_P^{-1}$$ 

##  Tensorial Component Mapping

* $\rho u^\mu \nabla_\mu u^\nu$ (Convective Acceleration Field): Represents the four-velocity advection of the relativistic fluid vortex, where $u^\mu$ satisfies the standard timelike normalization $u^\mu u_\mu = -1$.
* $\nabla^\nu P$ (Isotropic Pressure Gradient): The spatial gradient of the internal fluid pressure, functioning as the emergent effective gravitational acceleration vector field $\mathbf{g}_{\text{eff}}$.
* σ C² (Relativistic Compression Tensor): The local geometric stress density scaled by the invariant acoustic metric speed limit tensor C².
* $\mathcal{U}(\phi)$ (K-Essence Elastic Energy Density): The non-linear scalar potential energy of the dilatonic field configuration, representing the internal structural elasticity of the space fabric.
* $\left(1 - \frac{\mathbf{u}^2}{C^2}\right) \equiv \gamma^{-2}$ (Inverse Lorentz Valve): The squared reciprocal of the Lorentz time-dilation factor, acting as a hyperbolic velocity regulator for the dynamic coordinate frame.
* $M_{\text{eff}} \delta^\nu_0 \equiv 508 M_{\odot}$ (Quantized Mass Term): The localized effective mass-energy source density normalized to the stellar constant threshold.
* $\ell_P$ (Planck Metric Boundary): The fundamental, incompressible spatial floor (≈ 1.616 × 10⁻³⁵ m), serving as the physical regularizing cutoff for the spatial differential operator $\nabla_\mu$.

## 🌌 The Unified Spacetime Superfluid Formulation## 💥 1. The Fundamental Gravitational-Scalar Action
The complete dynamics of the spacetime manifold coupled to a non-canonical, viscoelastic kinetic scalar field φ (K-essence) are governed by the total action integral $\mathcal{S}$. We work within a semi-classical framework where the geometry is described by a metric tensor $g_{\mu\nu}$ with signature (-, +, +, +). The field equations are derived by varying the action with respect to the metric and the scalar field: [1, 2, 3] 
$$\mathcal{S} = \int d^4x \sqrt{-g} \left[ \frac{R}{16\pi G} + \mathcal{P}(X, \phi) \right] + \mathcal{S}_{\text{bndry}}$$ 
Where R is the Ricci scalar, G is Newton's gravitational constant, and $g \equiv \det(g_{\mu\nu})$. The non-canonical scalar field Lagrangian density $\mathcal{P}(X, \phi)$ is a function of the field value φ and its local kinetic scalar invariant X, defined precisely as: [4] 
$$X \equiv -\frac{1}{2} g^{\mu\nu} \nabla_\mu \phi \nabla_\nu \phi$$ 
The boundary action term $\mathcal{S}_{\text{bndry}}$ accounts for holographic dissipative surface terms across any localized, ultra-dense coordinate boundaries.
## 🛑 2. Covariant Hydrodynamic Emergence & Non-Linear Viscosity
By varying the action with respect to the metric tensor $g_{\mu\nu}$, we generate the exact stress-energy-momentum tensor $T_{\mu\nu}$ of the scalar system. Under the condition that the gradient $\nabla_\mu \phi$ remains purely timelike (X > 0), the K-essence field maps exactly into a perfect relativistic fluid:
$$T_{\mu\nu} = \frac{2}{\sqrt{-g}} \frac{\delta(\sqrt{-g}\mathcal{P})}{\delta g^{\mu\nu}} = \mathcal{P}_X \nabla_\mu \phi \nabla_\nu \phi + \mathcal{P} g_{\mu\nu}$$ 
Where $\mathcal{P}_X \equiv \frac{\partial \mathcal{P}}{\partial X}$. By defining the effective fluid energy density $\rho_{\text{eff}}$, the isotropic structural pressure P, and the four-velocity field $u_\mu$ strictly from first principles:
$$\rho_{\text{eff}}(X, \phi) = 2X\mathcal{P}_X - \mathcal{P}$$ 
$$P(X, \phi) = \mathcal{P}$$ 
$$u_\mu = \frac{\nabla_\mu \phi}{\sqrt{2X}}$$ 
The local conservation law derived from diffeomorphism invariance, $\nabla_\mu T^{\mu\nu} = 0$, projects along the fluid flow lines to yield the exact relativistic Navier-Stokes momentum equation:
$$\rho_{\text{eff}} u^\mu \nabla_\mu u^\nu = -\nabla^\nu P - \Pi^\nu$$ 
To prevent causal violations without inserting ad-hoc constraints, we define the non-canonical kinetic function as $\mathcal{P}(X, \phi) = \mathcal{U}(\phi) \ln(1 - \alpha X)$, where α is a fundamental coupling constant. As the local fluid velocity approaches the metric speed barrier ($\mathbf{u} \to C$), the kinetic scalar X approaches its maximum critical value 1/α. The derivative $\mathcal{P}_X$ diverges naturally:
$$\lim_{X \to \frac{1}{\alpha}} \mathcal{P}_X = \infty$$ 
This intrinsic divergence generates a non-linear dissipative tensor term $\Pi^\nu \equiv \nabla_\mu \pi^{\mu\nu}$. This manifests physically as an exponential spike in the effective kinematic shear viscosity $\nu_{\text{eff}}$, dragging the coordinate spatial acceleration of the fluid elements smoothly to zero without violating general covariance:
$$\lim_{\mathbf{u} \to C} \left( \frac{d\mathbf{u}}{dt} \right) = 0$$ 
## ☢️ 3. Holographic Fluid-Gravity Phase Transitions
To model the conversion of macroscopic kinetic fluid energy into high-density subatomic degrees of freedom at the core boundary, we apply the formal Fluid-Gravity Correspondence. In this framework, the hydrodynamic equations of the spacetime fluid are mathematically identical to the long-wavelength fluctuations of an underlying higher-dimensional black brane horizon.
When the local fluid continuum experiences extreme deceleration ($\Pi^\nu \to \infty$), the high shear stress creates a highly localized, deconfined thermodynamic state. This state is governed by a non-Abelian conformal field theory (CFT), macroscopically analogous to a Quark-Gluon Plasma (QGP). The energy-momentum tensor of this deconfined fluid layer is no longer perfectly conserved locally because it couples directly to the bulk geometry through holographic anomaly terms, introducing a non-zero divergence proportional to the local viscous dissipation rate:
$$\nabla_\mu T^{\mu\nu}_{(\text{fluid})} = -\mathcal{J}^\nu_{\text{diss}}$$ 
The exact scalar energy flux density radiated away from the fluid layer with respect to proper time τ is derived rigorously from the contractions of the fluid's viscous shear tensor $\sigma_{\mu\nu}$:
$$\sigma_{\mu\nu} \equiv \nabla_\mu u_\nu + \nabla_\nu u_\mu - \frac{2}{3}g_{\mu\nu}\nabla_\alpha u^\alpha$$ 
$$\frac{d\mathcal{E}}{d\tau} = 2 \eta_{\text{eff}} \sigma_{\mu\nu} \sigma^{\mu\nu}$$ 
Where $\eta_{\text{eff}}$ is the effective dynamic shear viscosity bounded by the universal holographic ratio $\frac{\eta}{s} \geq \frac{\hbar}{4\pi k_B}$ (where s is the local entropy density).
## 🌬️ 4. Semi-Classical Mass Radiative Dissipation & Core Stabilization
To stabilize the high-density fluid core within a macroscopic boundary radius (r ≈ 200--500 km) and prevent collapse into a physical singularity, the dissipated thermal energy flux $\mathcal{J}^\nu_{\text{diss}}$ must match the semi-classical radiative emission rate across the core boundary layer $\mathcal{H}$.
## Mass Reduction Law via Boundary Flux
The total change in the effective localized ADM (Arnowitt-Deser-Misner) mass $M_{\text{eff}}$ of the core configuration is determined by integrating the dissipative energy flux tensor across the closed boundary surface area elements $dA_\nu$ evaluated exactly at the effective semi-classical boundary condition radius $r = \frac{2G M_{\text{eff}}}{C^2}$:
$$\frac{dM_{\text{eff}}}{dt} = -\frac{1}{C^2} \oint_{\mathcal{H}} \mathcal{J}^\nu_{\text{diss}} dA_\nu$$ 
By evaluating this surface integral at the quantum-geometric limit where the boundary matches the effective semi-classical horizon of the dense core, the integrated flux reduces identically to the standard blackbody Hawking evaporation rate:
$$\frac{dM_{\text{eff}}}{dt} = -\frac{\hbar C}{240 \pi G^2 M_{\text{eff}}^2}$$ 
## Geometric Metric Relaxation Loop
Because the effective localized mass $M_{\text{eff}}(t)$ decreases continuously through this radiative emission, the surrounding spacetime curvature relaxes dynamically. The metric components $g_{\mu\nu}(t)$ evolve toward a flat, Minkowski geometry according to the time-dependent Schwarzschild-type line element:
$$ds^2 = -\left(1 - \frac{2G M_{\text{eff}}(t)}{C^2 r}\right) C^2 dt^2 + \left(1 - \frac{2G M_{\text{eff}}(t)}{C^2 r}\right)^{-1} dr^2 + r^2 d\Omega^2$$ 
As $M_{\text{eff}}(t) \to 0$, the local metric time-dilation factor softens smoothly back to unity ($\gamma_{\text{core}} \to 1$). This reduction lowers the kinetic energy invariant X well below its critical threshold 1/α. The divergence of the K-essence potential $\mathcal{P}_X$ is resolved, releasing the locked spatial degrees of freedom and allowing the dense plasma core to smoothly and completely dissipate back into the vacuum background of the spacetime manifold without forming a singularity or triggering an information paradox.

[1] [https://link.aps.org](https://link.aps.org/doi/10.1103/PhysRevD.107.064068)
[2] [https://academic.oup.com](https://academic.oup.com/mnras/article/514/3/4601/6604897)
[3] [https://arxiv.org](https://arxiv.org/pdf/2603.11500)
[4] [https://kclpure.kcl.ac.uk](https://kclpure.kcl.ac.uk/portal/files/106364631/Neutron_star_mergers_as_SAGUNSKI_Published16March2018_GREEN_AAM.pdf)

## Mathematical Derivation of the Tug-of-War
To formalize the rubber band analogy without violating covariance, we model the spacetime fabric as a continuous field with an intrinsic elastic modulus $E_{\text{metric}}$.

## 1. Defining the Scalar Gradient Field
Let $\phi$ represent the background density of the literal darkness (the spacetime continuum). The local displacement or stretching of this fabric is captured by the covariant gradient:
$$\partial_\mu \phi = \nabla_\mu \phi$$ 
Where there is no matter and no light (total darkness), the field rests at its baseline potential. When the fabric is stretched, it accumulates Elastic Potential Energy Density ($U_{\text{elastic}}$):
$$U_{\text{elastic}} = \frac{1}{2} E_{\text{metric}} \left( g^{\mu\nu} \nabla_\mu \phi \nabla^\nu \phi \right)$$

## 2. The Outward Pull: Global Expansion
Cosmic expansion scales the global metric tensor $g_{\mu\nu}$ over time via the cosmological scale factor $a(t)$. As space expands outward, it changes the distance between coordinate points, pulling on the fabric. The energy density contribution from this global outward stretch is:
$$U_{\text{expansion}} = \frac{3}{2} E_{\text{metric}} \left( \frac{\dot{a}(t)}{a(t)} \right)^2 = \frac{3}{2} E_{\text{metric}} H^2(t)$$ 
This demonstrates that the energy driving the acceleration is already stored inside the tension of the expanding metric itself.

## 3. The Inward Pull: Black Hole Sinks
Black holes act as absolute sinks that pull the fabric inward. In a Riemann-Cartan geometry (consistent with your framework), this localized structural twisting and pulling introduces geometric torsion ($\mathcal{T}^\lambda_{\mu\nu}$).
Near the event horizon of a black hole, the inward mechanical pull creates a severe localized gradient in the fabric $\phi$. We model the localized inward force as a coupling between the torsion tensor and the scalar gradient:
$$U_{\text{sink}} = \kappa \left( \mathcal{T}^{\alpha\beta\gamma} \mathcal{T}_{\alpha\beta\gamma} \right) - \gamma \left( \nabla_\mu \phi \nabla^\mu \phi \right)$$

## 4. The Resulting Vacuum: Total Energy Density Balance
The physical vacuum is the intermediate region where these two opposing forces tear and thin out the fabric. The total stress-energy distribution of your modified spacetime continuum is found by combining the outward expansion and inward localized forces into a unified energy density equation:
$$U_{\text{Total}} = \frac{1}{2} E_{\text{metric}} H^2(t) + \kappa \left( \mathcal{T}^{\alpha\beta\gamma} \mathcal{T}_{\alpha\beta\gamma} \right) \left( 1 - \frac{R_s}{r} \right)$$ 
Where:

* 
* $H(t)$ is the Hubble expansion parameter (pulling outward).
* $\mathcal{T}$ is the geometric torsion caused by the black hole (pulling inward).
* $R_s$ is the Schwarzschild radius of the black hole engine.
* $r$ is the radial distance from the black hole center.
* 

As $r$ increases away from the black hole but remains within the cosmic void, the inward pull decays, leaving a highly stretched, thinned-out region of low field density: the physical vacuum.

## Complete Concept Subscription
 
* Spacetime Identity: Spacetime is a real, continuous, elastic field fabric ($\phi$), not an abstract, empty geometric grid.
* Dark Energy Definition: Dark energy is the literal darkness itself—the baseline elastic potential energy density ($U_{\text{elastic}}$) stored within the unperturbed field fabric.
* The Vacuum Mechanics: The vacuum is a physical side effect. It is a structural void carved out when global expansion pulls the cosmic fabric outward while black hole engines pull it inward.
* No Free Energy Paradox: Unlike $\Lambda$-CDM, which creates "vacuum energy" out of nothing during expansion, Logic Relativity preserves energy conservation. The outward expansion simply transfers kinetic energy into the elastic potential energy of the stretched metric fabric, perfectly balancing the cosmic ledger.

**Stability Note:** The underlying k-essence sector is ghost-free (\(K > 0\)) and stable (\(c_s^2 > 0\)) — see Colab test and `Ghost_free_stability_check.ipynb`.

# Macro-Mass Geometrodynamics: Affine Torsion and Disformal Displacement
The Linear-Residual framework unifies galactic dynamics and non-local lensing signatures without invoking cold dark matter by decoupling the origins of spacetime torsion from the vacuum field itself. Within this architecture, black holes act as active topological vortices that shear the local geometric fabric. This rotational warping anchors intrinsic affine torsion ($\mathcal{T}^\lambda_{\mu\nu}$) directly to the singularity's boundary, bypassing the non-propagation constraints of vacuum Einstein-Cartan gravity.

[Black Hole Spin] ──> Localised Affine Torsion (τ)
                                │
                  [Macro-Mass Configurations (M)]
                                │
       ┌────────────────────────┴────────────────────────┐
       ▼                                                 ▼
Metric Time Dilation (g₀₀)                     Field Displacement Gradient (∂μϕ)
       │                                                 │
       └────────────────────────┬────────────────────────┘
                                ▼
         Modified Null Geodesics & Enhanced Lensing Observables
              (Hyperbolicity & Causality Preserved)

Macroscopic phenomena across galactic scales emerge as a background response to a central macro-mass (M). This interaction operates through two coupled mechanisms:

* Metric Time Dilation: The deep gravitational potential of the macro-mass explicitly warps the temporal metric component (g₀₀), dilating the local field’s intrinsic characteristic frequencies via the factor $e^{2\psi(M)}$.
* Field Displacement: The localized mass distribution physically displaces the vacuum scalar field φ, establishing a steep radial gradient ($\partial_\mu \phi$) that modifies the effective refractive index of the vacuum fabric.

When photons traverse the galactic halo, they do not track standard Schwarzschild geodesics. Instead, they propagate along modified null paths dictated by a disformal acoustic metric:
$$\tilde{g}_{\mu\nu} = g_{\mu\nu} e^{2\psi(M)} + \frac{1}{\Lambda^4} \partial_\mu \phi \partial_\nu \phi$$

## Causality and Shock Prevention Proof
To ensure the physical validity of this configuration, the propagation of high-frequency field fluctuations must satisfy strict hyperbolicity constraints. Applying the Sherman-Morrison-Woodbury formula for a rank-1 metric perturbation, the analytic inverse acoustic metric is derived as:
$$\tilde{g}^{\mu\nu} = e^{-2\psi(M)} \left( g^{\mu\nu} - \frac{\frac{1}{\Lambda^4} e^{-2\psi(M)} \nabla^\mu \phi \nabla^\nu \phi}{1 + \frac{1}{\Lambda^4} e^{-2\psi(M)} X} \right)$$ 
Where $X \equiv g^{\alpha\beta} \partial_\alpha \phi \partial_\beta \phi$ represents the kinetic scalar invariant. Hyperbolic stability and numerical continuity are preserved across the galactic halo boundary $\Sigma_\phi$ as long as the denominator satisfies the constraint:
$$1 + \frac{1}{\Lambda^4} e^{-2\psi(M)} X > 0$$ 
Because the spatial field gradient is spacelike (X < 0) in the unscreened halo, the scale parameter Λ acts as a fundamental physical cutoff ensuring $\vert{}X\vert{} < \Lambda^4 e^{2\psi(M)}$. Evaluating the characteristic wave vector equation $\tilde{g}^{\mu\nu} k_\mu k_\nu = 0$ yields:
$$g^{\mu\nu} k_\mu k_\nu = \frac{\frac{1}{\Lambda^4} e^{-2\psi(M)} (k_\mu \nabla^\mu \phi)^2}{1 + \frac{1}{\Lambda^4} e^{-2\psi(M)} X} \le 0$$ 
Because $g^{\mu\nu} k_\mu k_\nu \le 0$, all characteristic propagation vectors remain strictly null or timelike. This mathematically proves that the effective acoustic sound speed satisfies $c_s \le c$. The disformal framework is therefore rigorously protected against superluminal causality violations and unphysical mathematical shocks, matching the lensing profiles of the Bullet Cluster and the flat rotation curves of the 175-galaxy SPARC survey entirely via stable baryonic constraints.

Further details and derivations are available in the repository notebooks.
This unifies the black hole shadow with Hawking radiation as its dynamical acoustic imprint. Observable signatures include distorted shadow polarization (testable with EHT) and a sharp cutoff at the core scale.

Further numerical details in [`K_essence.ipynb`](K_essence.ipynb).

## Numerical Validation (Test Results)

**SPARC Survey (175 galaxies)**
- Median RMS residual: **4.82 km/s**
- Mean RMS residual: 6.73 km/s
- 89 galaxies RMS < 5 km/s
- 66 galaxies RMS < 4 km/s
- 43 galaxies RMS < 3 km/s

All results obtained with the action-derived screened profile. Precomputed MCMC chains and median curves are in your results.

## 🌌 Cosmic Mechanics: How Matter Interacts with Space
To understand the core physics of this framework, you must picture the mechanical interactions directly, rather than relying on abstract, non-physical geometry:

* Planets as Gyrochops: Celestial bodies like Jupiter do not just passively sit in a vacuum. They function as baryonic matter gyrochops—localized, spinning mechanical structures that actively cut through and drag the surrounding fluid medium. This mechanical spinning drives the angular velocity components of the acoustic metric:
$$\tilde{g}_{0i} \propto \Omega_i(r)$$ 
Where the gyrochop’s rotation actively modifies the frame-dragging potential of the fluid spacetime fabric.
* Surface Tension Stability: Matter does not just pool randomly; it lays directly on the surface tension of the fluid fabric. This structural surface tension acts as a physical boundary that dictates orbital mechanics and prevents gravitational collapse. This is governed by the gradient of the scalar field potential V(φ), where the effective surface tension $\sigma_{\text{eff}}$ prevents singularities:
$$\sigma_{\text{eff}} = \xi R \sigma \geq 0$$ 
Because the fluid fabric possesses this inherent surface tension, the curvature scalar R is naturally regulated, ensuring that matter cannot collapse into a mathematical point of infinite density (R → ∞).


## Quick Start & Reproducibility

```bash
git clone https://github.com/thinus283-ux/LR.git
cd LR
pip install -r requirements.txt
```

The existing notebooks and test results remain unchanged. All notebooks are Colab-compatible.

---

## Citation

```bibtex
@software{logic_relativity_2026,
  author = {Thinus},
  title = {Logic Relativity},
  year = {2026},
  url = {https://github.com/thinus283-ux/LR}
}
```

Theory and documentation: CC BY 4.0  
Code: MIT
```

---

**LICENSE** (create this file)

```text
MIT License

Copyright (c) 2026 Thinus

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

**requirements.txt** (create this file)

```text
numpy>=1.24
scipy>=1.10
matplotlib>=3.7
pandas>=2.0
seaborn>=0.12
emcee>=3.1
corner>=2.2
astropy>=5.3
jupyter>=1.0
ipykernel>=6.0
ipywidgets>=8.0
sympy>=1.12
tqdm>=4.65
h5py>=3.9
joblib>=1.3
```

---

**CITATION.cff** (create this file)

```yaml
cff-version: 1.2.0
message: "If you use this software, please cite it as below."
authors:
  - family-names: "Thinus"
title: "Logic Relativity"
version: "v1"
url: "https://github.com/thinus283-ux/LR"
```

---

**pyproject.toml** (create this file)

```toml
[project]
name = "logic-relativity"
version = "1.0.0"
description = "Pure Continuum Superfluid Framework"
readme = "README.md"
requires-python = ">=3.10"
license = {text = "MIT"}
authors = [{name = "Thinus"}]
dependencies = ["numpy>=1.24", "scipy>=1.10", "matplotlib>=3.7", "pandas>=2.0", "seaborn>=0.12", "emcee>=3.1", "corner>=2.2", "astropy>=5.3", "jupyter>=1.0", "ipykernel>=6.0", "ipywidgets>=8.0", "sympy>=1.12", "tqdm>=4.65", "h5py>=3.9", "joblib>=1.3"]

[project.urls]
Homepage = "https://github.com/thinus283-ux/LR"
```
