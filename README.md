# Data inputs (not distributed)

This directory is intentionally empty of study data. The public repository contains **code and documentation only**.

## Restricted private input
`ethanol_freight_private.csv` — private ESALQ-Log ethanol road-freight quotation panel. Expected structure:
- one column named `Data`;
- remaining columns correspond to origin-destination routes;
- route labels follow `Municipality (UF) → Municipality (UF)`;
- route columns contain nominal freight quotations; missing quotation cells remain missing (not zero);
- study window: January 2021 through July 2026.

The private file is not redistributed because it was supplied for academic use under third-party restrictions.

## Public/contextual inputs
Place the following files in this directory using the names below (or adapt the configuration cells):
- `regioes_geograficas_composicao_por_municipios_2017_20180911.csv` — IBGE municipality-to-Immediate/Intermediate Geographic Region composition.
- `prod_cana_municipal.csv` — municipal sugarcane production (IBGE/PAM; 2021–2024 as used in the study).
- `prod_etanol_estadual.csv` — annual state ethanol production (Conab contextual series).
- `loc_usinas_etanol.csv` — ethanol plant/location and milling-capacity context (MapBiomas-derived study input).
- `distribuidoras.csv` — destination distributor counts/context (ANP-derived study input).
- `postos.csv` — destination fuel-station counts/context (ANP-derived study input).
- Optional `producao_etanol_mensal.csv` — monthly state ethanol production (ANP). If absent, the temporal notebooks attempt to download the official ANP open-data file.

The code preserves the original analysis logic and expects the column structures used in the study. Public source references and access details are documented in the manuscript.
