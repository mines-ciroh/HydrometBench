# WSF Benchmark Forecast Archive

Benchmark data archive associated with:

> *A Community Evaluation Protocol for Seasonal Water Supply Forecasting in the Western U.S.*  
> Joshua T. Sturtevant, Andrew W. Wood, Chris D. Frans, Ian M. Ferguson, and Thomas C. Pagano  
> *Water Resources Research* (in review)

## Archive

The archive is deposited on HydroShare:

> **DOI:** *(to be added on publication)*

It contains the analysis-ready NetCDF (`wsf_obs_with_all_forecasts.nc`), per-agency source
data, site metadata, GIS layers, and full documentation (`README.md`, `data_dictionary.md`,
`provenance.md`).

## Companion code repositories

Two companion repositories support the archive:

| Repository | Purpose |
|---|---|
| [wsf-archive-assembly](https://github.com/mines-ciroh/wsf-archive-assembly) | Per-agency download/parse workflows and the notebook that assembles the NetCDF from source data |
| [wsf-protocol-paper](https://github.com/mines-ciroh/wsf-protocol-paper) | Skill-statistics notebook and figure scripts that reproduce the WRR manuscript results |

> **Note:** Both repositories are private pending manuscript acceptance and will be made
> public on publication.

## Archive contents (v1.0)

| Item | Description |
|---|---|
| `proc_data/wsf_obs_with_all_forecasts.nc` | Analysis-ready NetCDF (sites × init_date × percentile × method × year) |
| `source_data/` | Per-agency source files (NRCS, RFCs, CA DWR, WSF Rodeo, observations) |
| `other_data/metadata/` | Site crosswalk and forecast-location tables |
| `other_data/gis/` | RFC boundary shapefile and basin geopackage |

**26 sites · 9 forecast methods · Jan–Apr initializations · WY1990–2023**  
Units: thousand acre-feet (KAF) · Quantiles: exceedance probabilities f10/f30/f50/f70/f90
