# LR-UC v3.2 — Fresh Calibration and Control-Run Report

**Date:** 1 October 2026

## 1. Core LR-UC calibration rerun

The frozen LR-UC infrared response was independently recalibrated against the supplied 175-galaxy / 3391-point derived SPARC table.

The core fit uses:

- one universal `alpha_IR`;
- one `s_g` per galaxy;
- one effective `chi_g` per galaxy;
- the standard baryonic coefficients `gas=1`, `disk=0.5`, `bulge=0.7`;
- the supplied pointwise velocity uncertainties in the weighted objective.

Fresh result:

- `alpha_IR = 0.3009682979`
- RMS = `10.5464755 km/s`
- MAE = `6.0925223 km/s`
- global reduced `chi2 = 4.4475022`
- median `s_g = 0.8802428`
- median `chi_g = 0.6670564`
- geometric mean `chi_g = 0.5205555`
- residual correlation with `log10(g_b/a_LR) = 0.0068211`

The universal infrared coefficient is therefore numerically stable relative to the previous calibration (`~0.30099 -> 0.300968`).

## 2. Baryonic-systematics diagnostic

A separate experiment introduced exactly one conventional baryonic nuisance parameter:

\[
V_b^2=\eta_gV_{\rm gas}^2+0.5s_gV_{\rm disk}^2+0.7s_gV_{\rm bul}^2.
\]

The diagnostic fit gives approximately:

- `eta_g = 0.4003944`
- `alpha_IR = 0.4380499`
- RMS = `10.3787585 km/s`
- MAE = `5.9156885 km/s`
- reduced `chi2 = 4.1951966`

This numerically improves the residuals, but it is **not adopted into the core theory**. The result may be absorbing baryonic mass-model systematics rather than representing new LR-UC physics. It is retained in `results/calibration/baryonic_systematics_diagnostic.csv` for transparency.

## 3. Phase-space outer-transition control

The W0=16 lowered-isothermal control run gives:

- transition radius `x_tr = 3791.4288`;
- finite dimensionless excess mass `203.8082`;
- an approximately `r^-2` region spanning `1.02696 dex`;
- mean density slope `-2.02867` in that interval;
- mean `d ln(Vc^2)/d ln(r) = 0.01623` there;
- near-separatrix density exponent `2.53372`;
- analytic expectation for `delta f proportional to binding energy`: `2.5`.

This is a **control benchmark only**. It validates the mathematical architecture of a smooth phase-space transition; it does not establish that the microscopic Phi^A dynamics have already generated this structure.

## 4. Reproducibility checks

The repository unit tests pass:

`4 passed`

The calibration and phase-space scripts rerun successfully from the repository root.

## 5. Scientific decision

The core LR-UC response remains the publication baseline.

The universal gas normalization is retained only as a diagnostic branch.

The decisive unresolved physics remains the self-consistent cosmological phase-space formation problem that must derive:

1. the intermediate `r^-2` regime;
2. the formation normalization `chi`;
3. the energy/angular-momentum structure `f(E,L_z,L)`;
4. the smooth finite-excess-mass transition into the cosmological UC background.
