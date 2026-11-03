# Reproducibility Notes

This repository contains the code used in the manuscript **“Unsupervised Learning for Spatiotemporal Pattern Discovery in Brazilian Ethanol Road Freight Prices: Implications for Sustainable Logistics.”**

## Data

The private ESALQ-Log freight quotation database is not included because redistribution is restricted by the third-party data provider. Public contextual inputs should be obtained from the original sources cited in the manuscript.

## Code provenance

The notebooks in this repository are publication copies derived from the final executed October 2026 analysis notebooks. Outputs were removed before public release, and interactive Google Colab upload steps were replaced by portable path configuration. Analytical parameters, clustering specifications, diagnostics, and model-comparison logic were retained.

## Reproduction

The full workflow requires input files with the structures described in `data/README.md`. Notebook `00_Reproducibility_and_Run_Order.ipynb` documents the intended execution sequence and environment checks.

## Manuscript Data Availability wording

> The analytical code used to generate the results reported in this study is publicly available in the authors’ GitHub repository at: [INSERT GITHUB REPOSITORY LINK]. The private freight data are not included in the repository due to access and redistribution restrictions.
