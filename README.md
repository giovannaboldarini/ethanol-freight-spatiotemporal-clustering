# Data Availability and Input Files

This directory is intentionally distributed without the study datasets.

## Private freight data

The ethanol road-freight quotations analyzed in this study were provided by ESALQ-Log under academic-use restrictions. These data are proprietary third-party data and cannot be publicly redistributed by the authors.

Accordingly, the private freight database used to generate the results reported in the manuscript is not included in this repository.

## Public contextual data

The analytical workflow also uses publicly available contextual data related to ethanol production, sugarcane production, industrial plants, fuel distributors, fuel stations, geographic boundaries, and inflation adjustment.

These datasets must be obtained directly from the original providers cited in the manuscript, including:

- Brazilian National Agency of Petroleum, Natural Gas and Biofuels (ANP);
- Brazilian Institute of Geography and Statistics (IBGE);
- Brazilian National Supply Company (Conab);
- official Brazilian inflation data used for IPCA-based adjustment.

## Running the notebooks

Users with authorized access to the required input datasets should place the corresponding files in this directory or configure the data path as described in `00_Reproducibility_and_Run_Order.ipynb`.

The repository provides the complete analytical code, model specifications, preprocessing procedures, and reproducibility documentation, but does not redistribute restricted third-party data.
