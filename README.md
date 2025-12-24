# Comparative Analysis of Drug-Likeness Filters on FDA-Approved Drugs

## Overview
This project evaluates the applicability of commonly used drug-likeness filters
(Lipinski, Ghose, Veber, and Egan) on FDA-approved drugs using molecular descriptors
computed from SMILES strings.

## Tools & Libraries
- Python
- RDKit
- Pandas
- Matplotlib
- Numpy

## Dataset
- FDA-approved drugs obtained from PubChem

## Methodology
- Computation of 8 molecular descriptors
- Application of four drug-likeness filters
    - Lipinski Filter
    - Ghose Filter
    - Veber Filter
    - Egan Filter
- Comparative analysis of pass/fail distributions

## Results
- Filter-wise pass frequency analysis
- Descriptor-wise failure trends
- Distribution of compounds passing multiple filters

## Files
- `main.ipynb`
- `data/` – Raw and processed datasets
- `visualizations/` – Generated plots
- `report/` – LaTeX report and compiled PDF

## Key Insight
The study reinforces that these physicochemical guidelines are only an early screening tool
and do not provide definite predictions for clinically successful drugs
