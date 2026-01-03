# Gravity as Constraint Compliance

**A thermodynamic framework for quantum gravity that quantizes the interface, not spacetime.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview

Jacobson showed Einstein's equation emerges from thermodynamics on local horizons. This paper answers the question he left open: *what should be quantized?*

**Answer:** The constraint interface itself. Null surfaces aren't thermodynamic systems—they're checkpoints that validate whether metric deformations are admissible. The Clausius relation δQ = TδS is an admissibility constraint, not emergent thermodynamics.

Key object (Clausius residual):
```
Δ_Σ ≡ δQ - TδS
```

- Classical GR: ⟨Δ_Σ⟩ = 0
- Quantum corrections: Var(Δ_Σ) > 0

## Key Results

- **Localized quantumness**: The quantized subsystem is the certification interface, not the metric or unspecified "horizon microstates"
- **Distinct noise channel**: Certification fluctuations yield stochastic focusing noise (∝ ℓ_P²/A), independent of stress-energy correlators
- **Curvature corrections**: Non-equilibrium certification generates higher-curvature EFT terms
- **ℏ as resolution**: Planck's constant sets the certification resolution scale via ΔA_min ~ Gℏ

## The One-Line Version

Gravity is classical because it's an equation of state. Quantum gravity describes fluctuations of the constraints that make that state well-defined.

## Building

```bash
cd paper
pdflatex thermodynamic_gravity.tex
bibtex thermodynamic_gravity
pdflatex thermodynamic_gravity.tex
pdflatex thermodynamic_gravity.tex
```

## Paper

**Title:** Gravity as Constraint Compliance: A Thermodynamic Framework for Quantum Gravity
**Target:** Foundations of Physics
**Status:** In preparation

## Citation

```bibtex
@unpublished{todd2025gravity,
  title={Gravity as Constraint Compliance: A Thermodynamic Framework for Quantum Gravity},
  author={Todd, Ian},
  note={In preparation},
  year={2025}
}
```

## License

MIT License
