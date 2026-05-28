# Cross-Dataset Proteomics Framework

This repository contains a Quarto statistical report that develops and demonstrates a framework for cross-dataset proteomics analysis within a shared omics platform.

The report focuses on how heterogeneous proteomics studies can be preprocessed, modelled, and synthesised so that reproducible biological signals can be distinguished from study-specific variation.

## Report

- Main Quarto source: `BillyJiang_FinalReport_EmilyLin.qmd`
- Rendered HTML report: `BillyJiang_FinalReport_EmilyLin.html`
- Bibliography: `references.bib`
- Custom styling: `custom.css`

## Statistical Scope

The report develops four cross-dataset workflows:

- Protein-level treatment effect synthesis
- Variability and dispersion modelling
- Protein association and co-expression analysis
- Higher-order pathway and module preservation analysis

Each workflow is demonstrated on a controlled synthetic multi-study proteomics collection designed to reflect mixed data granularity, missingness, and between-study heterogeneity.

## Reproducibility

The report is written in Quarto and uses R code chunks for simulation, modelling, visualisation, and table generation. The rendered HTML file is included for direct viewing.

To render the report locally, use:

```bash
quarto render BillyJiang_FinalReport_EmilyLin.qmd
