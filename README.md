# Gravity as Constraint Compliance

**Quantization as lattice selection: why dimensional collapse at null surfaces produces discrete certification.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview

Jacobson showed Einstein's equation emerges from thermodynamics on local horizons. This paper answers the question he left open: *what should be quantized?*

**Answer:** The constraint interface itself. Null surfaces are low-dimensional bottlenecks where high-dimensional matter dynamics get certified as admissible. The existing metric structure acts as a lattice—it selects which deformations can pass through. Discreteness is imposed by the interface, not by spacetime geometry.

Key object (Clausius residual):
```
Δ_Σ ≡ δQ - TδS
```

- Classical GR: ⟨Δ_Σ⟩ = 0 (perfect certification)
- Quantum corrections: Var(Δ_Σ) > 0 (finite resolution)

## Key Results

- **Why interfaces quantize**: Dimensional collapse forces collisions (projection degeneracy); pre-existing structure (the lattice) resolves them by selecting admissible outputs
- **Localized quantumness**: The quantized subsystem is the certification interface, not the metric or "horizon microstates"
- **Distinct noise channel**: Certification fluctuations yield stochastic focusing noise (∝ ℓ_P²/A), independent of stress-energy correlators
- **ℏ as lattice spacing**: Planck's constant sets the resolution of the pre-existing structure via ΔA_min ~ Gℏ

## The One-Line Version

Quantization isn't mysterious—it's what happens when high-dimensional dynamics squeeze through low-dimensional bottlenecks with pre-existing structure.

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
@unpublished{todd2026gravity,
  title={Gravity as Constraint Compliance: A Thermodynamic Framework for Quantum Gravity},
  author={Todd, Ian},
  note={In preparation},
  year={2026}
}
```

## License

MIT License
