# Intro to ESMs

This module was written as an intro to Earth System Models as a whole, how to use them, and how to interpret their data. The module will include 6 labs that go along with the main chapters, but for now Labs 1, 2, 4, and 5 are available.

- Chapter 1 — Introduction to Earth System Models - Lab 1: Done
- Chapter 2 — Radiative Forcing and Climate Sensitivity - Lab 2: Done
- Chapter 3 — Climate Feedbacks - Lab 3: In Progress
- Chapter 4 — Multi-Model Ensembles (CMIP) - Lab 4: Done
- Chapter 5 — Detection and Attribution (DAMIP) - Lab 5: Done
- Chapter 6 — Quantifying Model Uncertainty -  Lab 6: In Progress
- Supplementary Chapter 1 — Initial Condition Ensembles
- Supplementary Chapter 2 — Perturbed Parameter Ensembles
- Supplementary Chapter 3 — Emergent Constraints

## Setup

The labs need Python with a set of climate-data packages. The `environment.yml` file in this repository lists them.

1. Install [Miniforge](https://github.com/conda-forge/miniforge) (or any conda distribution) if you don't already have one.
2. From the root of this repository, create and activate the environment:

   ```bash
   conda env create -f environment.yml
   conda activate esm-intro
   ```

3. Start Jupyter and open a lab from the `module/` folder:

   ```bash
   jupyter lab
   ```

   If you use VS Code instead, open a notebook and follow the step 2 and then select the `esm-intro` kernel.

## Authors

Module materials written and developed by **Tyler Herrington** and **Matthew Mast**, under supervision from the original course creator, **Dr Chris Fletcher**, University of Waterloo.

## Version

Version 1.0, November 2026
   
