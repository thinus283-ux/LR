Logic Relativity — Unified Continuum (LR-UC)
LR-UC v3.2.1 — Peer-Review / Reproducibility Release
Author: Thinus Pieterse
Date: 1 October 2026
Scope: 4D Einstein gravity + conserved relativistic UC continuum + closed effective IR response
�
What this repository is
LR-UC is a research framework in which the dark-matter sector is represented by one conserved relativistic material continuum described by three comoving scalar fields
[ \Phi^A(x^\mu),\qquad A=1,2,3, ]
while the gravitational sector remains ordinary four-dimensional Einstein gravity.
The working ontology is
[ \boxed{ \text{4D Einstein geometry} + \text{baryons} + \text{one conserved UC continuum} + \Lambda. } ]
The continuum is the dark-matter sector. (\Lambda) is dark energy.
The framework deliberately does not introduce:
a fifth spacetime dimension;
a direct baryon–continuum fifth force;
a modified Einstein tensor;
galaxy-specific NFW concentration/scale/truncation parameters;
a hand-imposed halo cutoff;
a fundamental MOND/RAR interpolation law.
The central chain
[ \boxed{ \text{baryonic matter} \rightarrow \text{Einstein geometry} \rightarrow \text{UC deformation / phase-space organization} \rightarrow T_{\mu\nu}^{\rm UC} \rightarrow \text{Einstein geometry}. } ]
The galactic halo is interpreted as a self-gravitating phase-space-organized overdensity of the same universe-filling UC continuum.
The intended formation sequence is
[ \boxed{ \text{cosmological UC} \rightarrow \text{gravitational organization} \rightarrow \text{UC self-gravity} \rightarrow \text{energy + angular-momentum sorting} \rightarrow \text{extended bound population} \rightarrow \text{diffuse overdensity} \rightarrow \rho_{\rm UC,0}. } ]
Angular momentum is not treated as an outward force; energy and angular momentum jointly determine the orbital population.
1. Fundamental equations
The action is
[ S=S_{\rm EH}+S_b+S_{\rm UC}+S_\Lambda ]
with
[ S_{\rm EH}
\frac{c^3}{16\pi G} \int d^4x,\sqrt{-g},R ]
and
[ S_{\rm UC}
-\int d^4x,\sqrt{-g} \left[ \rho_0c^2b+W_{\rm def}(Q)+W_P(b) \right]. ]
The material metric is
[ B^{AB}
g^{\mu\nu} \partial_\mu\Phi^A\partial_\nu\Phi^B. ]
The conserved material current is
[ J^\mu
\frac1{3!} \epsilon^{\mu\nu\rho\sigma} \epsilon_{ABC} \partial_\nu\Phi^A \partial_\rho\Phi^B \partial_\sigma\Phi^C, \qquad \nabla_\mu J^\mu=0. ]
Define
[ b=\sqrt{\det C}, \qquad \bar C=b^{-2/3}C, \qquad S=\frac12\ln\bar C, \qquad Q={\rm Tr}(S^2)\ge0. ]
The representative microscopic deformation law is
[ W_{\rm def}
\mu_0q_0^2 \left[ \sqrt{1+\frac{Q}{q_0^2}}-1 \right], ]
with
[ \mu_0=4\times10^{-16}, \qquad q_0=10^{-3}. ]
The positive Planck-density term is a UV regulator only.
2. Cosmological cold branch
Homogeneous FLRW gives
[ b=a^{-3}, \qquad Q=0, ]
and therefore
[ \boxed{ \rho_{\rm UC}\propto a^{-3}, \qquad p_{\rm UC}=0. } ]
The background equation is
[ H^2= \frac{8\pi G}{3} (\rho_r+\rho_b+\rho_{\rm UC}) + \frac{\Lambda c^2}{3}. ]
The present UC density defines
[ \boxed{ a_{\rm LR}=c\sqrt{G\rho_{\rm UC,0}} \simeq1.1746\times10^{-10}\ {\rm m,s^{-2}}. } ]
3. Weak-field phase space
The exact flow-map construction gives
[ f(\mathbf x,\mathbf v,t)
\int d^3q,\rho_0(\mathbf q) \delta^3[\mathbf x-\mathbf X(\mathbf q,t)] \delta^3[\mathbf v-\dot{\mathbf X}(\mathbf q,t)]. ]
On galactic weak-field scales,
[ \partial_tf + \mathbf v\cdot\nabla_xf
\nabla\Psi\cdot\nabla_vf=0, ]
[ \nabla^2\Psi
4\pi G(\rho_b+\rho_{\rm UC}). ]
The halo therefore has a genuine phase-space state
[ f(E,L_z,L). ]
4. Galactic effective response
The collective polarization is a coarse-grained observable of the same UC material degrees of freedom:
[ P_{\rm UC}
\bar\rho_{\rm UC}(\xi_\ell-\xi_L). ]
Define
[ p=\frac{4\pi GP_{\rm UC}}{a_{\rm LR}}. ]
The current closed infrared energy is
[ \boxed{ W_{\rm IR}
\frac{a_{\rm LR}^2}{4\pi G} \left[ \frac{p^2}{2} + \frac{p^3}{3\chi} + \frac{\alpha_{\rm IR}p^5}{5\chi} \right]. } ]
Its response is
[ \boxed{ g=g_N+a_{\rm LR}p, } ]
[ \boxed{ \frac{g_N}{a_{\rm LR}}
\frac{p^2+\alpha_{\rm IR}p^4}{\chi}. } ]
The physical branch is
[ p^2= \frac{ \sqrt{1+4\alpha_{\rm IR}\chi g_N/a_{\rm LR}}-1 }{ 2\alpha_{\rm IR} }. ]
The effective sector is convex on the physical branch and the solution is single-valued.
5. Deep and high-acceleration limits
Deep infrared:
[ \boxed{ g\simeq\sqrt{\chi a_{\rm LR}g_N}. } ]
High acceleration:
[ \boxed{ \frac{g-g_N}{g_N} \sim \left( \frac{\chi}{\alpha_{\rm IR}} \right)^{1/4} \left( \frac{a_{\rm LR}}{g_N} \right)^{3/4} \rightarrow0. } ]
For a spherical baryon-dominated source:
[ g_{\rm P}
\frac{\sqrt{\chi GM_ba_{\rm LR}}}{r}, ]
[ \rho_{\rm P}
\frac{\sqrt{\chi GM_ba_{\rm LR}}}{4\pi Gr^2}, ]
and
[ \boxed{ V_f^4=\chi GM_ba_{\rm LR}. } ]
The (r^{-2}) branch is an intermediate nonlinear regime, not the final (r\to\infty) law.
6. Finite-mass outer halo
The actual density must be written
[ \rho_{\rm UC}(r)
\rho_{\rm UC,0} + \delta\rho_{\rm UC}(r), ]
with
[ \delta\rho_{\rm UC}\rightarrow0 ]
and
[ \boxed{ 4\pi\int_0^\infty [\rho_{\rm UC}(r)-\rho_{\rm UC,0}]r^2dr<\infty. } ]
The required structure is
[ \boxed{ \text{inner nonlinear} \rightarrow r^{-2}\text{ intermediate} \rightarrow \text{phase-space transition} \rightarrow \rho_{\rm UC,0}. } ]
There is no hand-imposed (r_{\rm cut}).
For a weak-binding population
[ \delta f\propto\mathcal E^n, ]
one obtains
[ \delta\rho\propto\psi^{n+3/2}. ]
A Kepler-like infinite tail has finite excess mass when
[ n>\frac32. ]
A finite binding separatrix gives a smooth outer law
[ \delta\rho\propto (r_{\rm tr}-r)^{n+3/2}. ]
7. Current empirical SPARC calibration
The repository contains a derived 175-galaxy / 3391-point calibration input table.
The baseline baryonic model is
[ V_b^2
V_{\rm gas}^2 + 0.5s_gV_{\rm disk}^2 + 0.7s_gV_{\rm bul}^2. ]
The current rerun gives
[ \boxed{\alpha_{\rm IR}=0.3009683} ]
with
RMS = (10.54648\ {\rm km,s^{-1}})
MAE = (6.09252\ {\rm km,s^{-1}})
reduced (\chi^2=4.44750)
median (s_g=0.88024)
median (\chi_g=0.66706)
geometric-mean (\chi_g=0.52056)
residual-vs-acceleration correlation (r=0.00682).
The earlier (\alpha_{\rm IR}\simeq0.30099) result is therefore reproducible.
8. Baryonic-systematics diagnostic
A separate diagnostic adds one universal gas normalization
[ V_b^2= \eta_gV_{\rm gas}^2 + 0.5s_gV_{\rm disk}^2 + 0.7s_gV_{\rm bul}^2. ]
The diagnostic gives approximately
[ \eta_g=0.40039, \qquad \alpha_{\rm IR}=0.43805, ]
with
RMS = (10.37876\ {\rm km,s^{-1}})
MAE = (5.91569\ {\rm km,s^{-1}})
reduced (\chi^2=4.19520).
This branch is not adopted. It is retained solely to quantify the degree to which baryonic-systematic freedom can absorb residuals.
9. Formation status
The decisive microscopic formation problem remains unresolved.
Existing formation tests did not establish a universal converged (r^{-2}) attractor. This is explicitly retained as a negative/YELLOW result.
The repository therefore does not claim that the microscopic (\Phi^A) dynamics have already derived:
the universal halo normalization (\chi);
the full (f(E,L_z,L));
the (r^{-2}) formation attractor;
the smooth finite-mass outer transition.
Those remain falsifiable targets.
10. Phase-space control test
A lowered-isothermal control with (W_0=16) is included solely as a numerical/mathematical unit test.
It gives:
[ \langle d\ln\rho/d\ln r\rangle\simeq-2.029 ]
over an approximately 1.03-dex interval,
[ \langle d\ln V_c^2/d\ln r\rangle\simeq0.016, ]
finite excess mass, and a near-separatrix exponent
[ 2.534\approx\frac52. ]
This is a control calculation, not a new LR-UC constitutive assumption.
11. What is established vs unresolved
GREEN
4D Einstein geometry
three-scalar conserved continuum
cold FLRW branch
objective deformation invariant
spherical material reduction
corrected IR response algebra
response convexity and uniqueness
analytical BTFR relation
spherical same-source lensing relation
background BBN/CMB-scale checks
reproducible SPARC calibration
phase-space outer-transition control benchmark
YELLOW
microscopic derivation of the effective (W_{\rm IR})
microscopic prediction of (\alpha_{\rm IR})
nonlinear prediction of (\chi_g)
formation of the (r^{-2}) regime
cosmological capture/assembly history
fully derived finite-mass outer transition
3D (f(E,L_z,L))
exact TT/TE/EE spectra
nonlinear matter power spectrum
cluster/merger lensing
full nonlinear hyperbolicity/stability
RED / REMOVED
fifth dimension
direct fifth force
automatic bounce
negative-energy UV branch
hand-inserted RAR interpolation
hard halo cutoff
NFW-like galaxy-specific truncation parameters
phenomenological response lag
quartic fold as the microscopic (p^5) completion
local 114-pc gradient as the final IR law
12. Reproduce everything
Create an environment:
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
Run the full calibration:
PYTHONPATH=src python scripts/calibrate_sparc.py
Run the phase-space control:
PYTHONPATH=src python scripts/run_phase_space_benchmark.py
Run unit tests:
PYTHONPATH=src pytest -q
The current tests cover:
physical response root;
deep infrared normalization;
high-acceleration recovery;
BTFR identity.
13. Repository structure
LR-UC-v3.2.1/
├── README.md
├── CITATION.cff
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE_NOTE.md
├── pyproject.toml
├── requirements.txt
├── .github/
│   └── workflows/
│       └── tests.yml
├── src/
│   └── lr_uc/
│       ├── __init__.py
│       ├── response.py
│       └── calibration.py
├── scripts/
│   ├── calibrate_sparc.py
│   ├── run_phase_space_benchmark.py
│   └── run_all_checks.py
├── tests/
│   └── test_response.py
├── docs/
│   ├── THEORY.md
│   ├── REPRODUCIBILITY.md
│   ├── SCIENTIFIC_STATUS.md
│   └── REVIEW_RESPONSE.md
├── paper/
│   ├── main.tex
│   └── references.bib
├── data/
│   └── derived/
│       ├── README.md
│       └── SPARC_175_pointwise_input.csv
└── results/
    ├── calibration/
    ├── formation/
    ├── figures/
    └── NEW_RUN_REPORT.md
14. Scientific standard for this release
The repository explicitly separates:
[ \boxed{ \text{fundamental theory} \neq \text{effective closure} \neq \text{empirical calibration} \neq \text{unresolved formation prediction}. } ]
A successful fit is not presented as proof of microscopic derivation.
A mathematical asymptotic solution is not presented as proof of dynamical formation.
A lower-(\chi^2) nuisance branch is not silently adopted.
A failed numerical experiment remains a failed test.
That is the reproducibility standard of this branch.
