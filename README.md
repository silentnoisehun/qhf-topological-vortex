# QHF Topological Vortex: Quantum-Hydrodynamic Multi-Qubit Entrainment on Heron QPU

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![IBM Quantum](https://img.shields.io/badge/IBM%20Quantum-Heron%20r2%20(156q)-blue.svg)](https://quantum.ibm.com/)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0003--3986--6039-green.svg)](https://orcid.org/0009-0003-3986-6039)

**Preregistered closed-loop quantum-hydrodynamic simulation coupling macroscopic 2D Gross–Pitaevskii vortex lattice dynamics to multi-qubit entangled topological circuits on superconducting quantum processors (IBM Heron r2).**

**Author:** Máté Róbert (Rongyász)  
**Affiliation:** Silent Coder Labs  
**ORCID:** [0009-0003-3986-6039](https://orcid.org/0009-0003-3986-6039)  
**Contact:** materobi86@gmail.com  

---

## 🌪️ Motivation & Scientific Rationale

Previous single-qubit closed-loop feedback tests confirmed with high precision that single-qubit rotations under projective measurement obey the textbook Born rule without deviation ($d \approx 0$). 

To explore genuine non-equilibrium quantum phenomena where classical simulation fails, this project scales the closed-loop architecture to:
1. **Multi-qubit Entangled Loop Topologies:** Coupling discrete angular momentum states of quantized vortices to continuous multi-qubit entangled ring clusters.
2. **Topological Phase Winding:** Encoding macroscopic phase circulation $\oint \nabla \theta \cdot d\mathbf{r} = 2\pi q$ ($q \in \mathbb{Z}$) into multi-qubit Greenberger–Horne–Zeilinger (GHZ) and cluster states.
3. **Measurement-Induced Phase Transitions (MIPT):** Investigating whether closed-loop nonlinear feedback stabilizes macroscopic entanglement against monitored projective measurements.

---

## 📁 Repository Layout

```
├── docs/                     # Preregistration documents & amendments
├── scripts/                  # Simulation, QPU orchestrators, and statistical analyzers
└── measurement_raw/          # Raw quantum execution counts, calibration snapshots, analysis.json
```
