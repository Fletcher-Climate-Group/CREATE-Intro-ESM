# Intro to ESMs

This module was written as an intro to Earth System Models as a whole, how to use them, and how to interpret their data. The module will include 6 labs that go along with the main chapters, but for now Labs 1, 2, 4, and 5 are available.

- Chapter 1
- Chapter 2
- Chapter 3
- Chapter 4
- Chapter 5
- Chapter 6
- Supplementary Chapter 1
- Supplementary Chapter 2
- Supplementary Chapter 3

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

   If you use VS Code instead, open a notebook and select the `esm-intro` kernel.
