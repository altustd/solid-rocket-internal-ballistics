# Solid Rocket Internal Ballistics

**A comprehensive theory and simulation guide to solid rocket motor internal ballistics.**

This repository focuses on the fundamental physics, mathematical modeling, and numerical simulation of what happens inside a solid rocket motor during combustion — from ignition to burnout.

It serves as the **theory companion** to the optimization-focused project:
**[opt-solid-rocket](https://github.com/altustd/opt-solid-rocket)**

---

## What This Book Covers

- Propellant chemistry and burn rate laws
- Zero-dimensional and quasi-1D internal ballistics models
- Chamber pressure and thrust-time curve prediction
- Burn surface regression for complex grain geometries
- Erosive burning, temperature sensitivity, and pressure exponent effects
- Ignition transients and pressure spikes
- Numerical integration methods for ballistic simulation
- Detailed derivations and Python implementations

---

## Project Structure

```bash
solid-rocket-internal-ballistics/
├── index.qmd
├── _quarto.yml
├── chapters/          # Theory and simulation chapters
├── appendices/
├── code/              # Reusable Python simulation modules
├── data/              # Propellant properties and test data
├── figures/
├── _book/             # Rendered output (ignored)
├── requirements.txt
└── README.md