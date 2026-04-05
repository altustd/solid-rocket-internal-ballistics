# Solid Rocket Internal Ballistics

A comprehensive theory and simulation guide to **solid propellant rocket motor internal ballistics**.

This repository covers the fundamental physics, mathematical modeling, and numerical simulation of solid rocket motor combustion — from ignition to burnout. It serves as the **theory companion** to the optimization project [`opt-solid-rocket`](https://github.com/altustd/opt-solid-rocket).

## Features

- Detailed derivations of 0D and quasi-1D internal ballistics models
- Chamber pressure and thrust-time curve prediction
- Burn surface regression for complex grain geometries (burnback analysis)
- Propellant burn rate laws (Vieille’s law, temperature sensitivity, erosive burning)
- Ignition transients and initial pressure spikes
- Nozzle flow (Saint-Venant / isentropic relations)
- Python implementations with clean, reusable code
- Interactive Quarto book with executable examples

## Project Structure

```bash
├── appendices
│   ├── a-derivations_files
│   │   └── libs
│   │       ├── bootstrap
│   │       ├── clipboard
│   │       └── quarto-html
│   ├── b-propellant-database_files
│   │   └── libs
│   │       ├── bootstrap
│   │       ├── clipboard
│   │       └── quarto-html
│   ├── c-python-modules_files
│   │   └── libs
│   │       ├── bootstrap
│   │       ├── clipboard
│   │       └── quarto-html
│   ├── d-numerical-methods_files
│   │   └── libs
│   │       ├── bootstrap
│   │       ├── clipboard
│   │       └── quarto-html
│   ├── a-derivations.qmd
│   ├── b-propellant-database.qmd
│   ├── c-python-modules.qmd
│   └── d-numerical-methods.qmd
├── chapters
│   ├── 00-preface_files
│   │   └── libs
│   │       ├── bootstrap
│   │       ├── clipboard
│   │       └── quarto-html
│   ├── 01-intro_files
│   │   └── libs
│   │       ├── bootstrap
│   │       ├── clipboard
│   │       └── quarto-html
│   ├── 02-propellants_files
│   │   └── libs
│   │       ├── bootstrap
│   │       ├── clipboard
│   │       └── quarto-html
│   ├── 03-grain-design_files
│   │   └── libs
│   │       ├── bootstrap
│   │       ├── clipboard
│   │       └── quarto-html
│   ├── 04-burnback-simulation_files
│   │   ├── figure-pdf
│   │   │   └── cell-2-output-1.pdf
│   │   └── libs
│   │       ├── bootstrap
│   │       ├── clipboard
│   │       └── quarto-html
│   ├── 05-internal-ballistics_files
│   │   └── libs
│   │       ├── bootstrap
│   │       ├── clipboard
│   │       └── quarto-html
│   ├── 06-burning-rate-and-kn_files
│   │   └── libs
│   │       ├── bootstrap
│   │       ├── clipboard
│   │       └── quarto-html
│   ├── 07-erosive-burning_files
│   │   └── libs
│   │       ├── bootstrap
│   │       ├── clipboard
│   │       └── quarto-html
│   ├── 08-performance-modeling_files
│   │   └── libs
│   │       ├── bootstrap
│   │       ├── clipboard
│   │       └── quarto-html
│   ├── 09-ignition-transient_files
│   │   └── libs
│   │       ├── bootstrap
│   │       ├── clipboard
│   │       └── quarto-html
│   ├── 10-full-simulation_files
│   │   └── libs
│   │       ├── bootstrap
│   │       ├── clipboard
│   │       └── quarto-html
│   ├── 00-preface.qmd
│   ├── 01-intro.qmd
│   ├── 02-propellants.qmd
│   ├── 03-grain-design.qmd
│   ├── 04-burnback-simulation.qmd
│   ├── 05-internal-ballistics.qmd
│   ├── 06-burning-rate-and-kn.qmd
│   ├── 07-erosive-burning.qmd
│   ├── 08-performance-modeling.qmd
│   ├── 09-ignition-transient.qmd
│   └── 10-full-simulation.qmd
├── code
├── data
├── figures
├── index_files
│   └── libs
│       ├── bootstrap
│       │   ├── bootstrap-138a6193a3bd40baf1e627da441a4734.min.css
│       │   ├── bootstrap-icons.css
│       │   ├── bootstrap-icons.woff
│       │   └── bootstrap.min.js
│       ├── clipboard
│       │   └── clipboard.min.js
│       └── quarto-html
│           ├── tabsets
│           ├── anchor.min.js
│           ├── popper.min.js
│           ├── quarto-syntax-highlighting-845c23b38eaddc0f92fda52bfe77a8c8.css
│           ├── quarto.js
│           ├── tippy.css
│           └── tippy.umd.min.js
├── outputs
├── scripts
├── styles
│   └── styles.css
├── README.md
├── _quarto.yml
├── index.qmd
├── project_tree.txt
├── references.bib
├── repomix-output.xml
├── requirements.txt
└── styles.css

