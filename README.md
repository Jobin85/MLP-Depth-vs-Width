# MLP-Depth-vs-Width
Tutorial and notebook investigating MLP depth vs width on the Energy Efficiency dataset, with baseline comparisons and reproducible experiments.
# MLP Depth vs Width Tutorial

This repository contains my machine learning coursework on how MLP depth and width affect performance on the Energy Efficiency dataset.

## Contents

- `MLP_Depth_vs_Width.ipynb` — full notebook with experiments
- `MLP_Width&Depth_Tutorial.pdf` — tutorial report
- `ENB2012_data.xlsx` — dataset
- `LICENSE` — license file

## What the project covers

- depth comparison
- width comparison
- depth × width grid search
- robustness across random seeds
- residual analysis
- gradient norm analysis
- baseline comparison with Linear Regression, Ridge Regression, and Random Forest

## Dataset

The Energy Efficiency dataset includes eight building features and two regression targets:
- Y1: Heating Load
- Y2: Cooling Load

## Key result

Although different MLP architectures were explored in detail, Random Forest achieved the best overall performance on this small structured tabular dataset.

## How to run

Open the notebook in Jupyter and run all cells in order.

