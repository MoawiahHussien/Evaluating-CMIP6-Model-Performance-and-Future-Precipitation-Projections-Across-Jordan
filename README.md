# Evaluating CMIP6 Model Performance and Future Precipitation Projections Across Jordan's Water Basins Under SSP Scenarios

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXX.svg)](https://doi.org/10.5281/zenodo.XXXXXXX)

## Overview

This repository contains the code and data processing scripts used in the study "Evaluating CMIP6 Model Performance and Future Precipitation Projections Across Jordan's Water Basins Under SSP Scenarios." The research evaluates six CMIP6 models from the RICCAR initiative and projects future precipitation changes under SSP4.5 and SSP8.5 scenarios across Jordan's 12 hydrological basins.


## Detailed Workflow

### Stage 1: Model Evaluation (Scripts 1-2)
**Input**: 
- Observational station data (1971-2014)
- RICCAR CMIP6 model outputs (6 models)

**Process**:
1. Calculate skill metrics (r, NSE, RMSE, MAE, PBIAS) for each model
2. Rank models by basin based on composite performance
3. Identify best-performing model per basin

**Output**:
- Station-level validation metrics
- Basin-level model rankings
- Performance heatmaps

---

### Stage 2: Ensemble Creation (Scripts 3-4)
**Input**: 
- Validated model rankings
- RICCAR NetCDF files (1961-2070)

**Process**:
1. **3-Model Ensemble**: Select top 3 models per basin, create arithmetic mean
2. **6-Model Ensemble**: Use all 6 models with equal weighting

**Output**:
- Ensemble NetCDF files for multiple time periods
- Basin-specific model assignments
- Ensemble summary reports

---

### Stage 3: Ensemble Validation (Scripts 4-5)
**Input**: 
- Ensemble outputs
- Observational data (1971-2014)

**Process**:
1. Validate 3-model and 6-model ensembles
2. Compare ensemble vs. single model performance
3. Analyze basin-specific validation results

**Output**:
- Ensemble validation metrics
- Performance comparison tables
- Basin validation reports

---

### Stage 4: Seasonal Analysis (Scripts 6-7)
**Input**: 
- Best model/ensemble per basin
- SSP4.5 and SSP8.5 scenarios

**Process**:
1. Calculate seasonal means (wet: Oct-Mar, dry: Apr-Sep)
2. Process reference (1995-2014), near-future (2021-2040), mid-future (2041-2060)
3. Calculate temporal differences

**Output**:
- Seasonal precipitation NetCDF files
- Difference maps (Excel format)
- Summary statistics

---

### Stage 5: Visualization (Scripts 8-9)
**Input**: 
- Seasonal precipitation data
- Basin approach assignments
- Difference calculations

**Process**:
1. Create hybrid approach maps (optimal approch per basin)
2. Generate 2×3 panel figures (wet/dry × ref/near/mid)
3. Apply standardized color scales

**Output**:
- Publication-quality precipitation maps
- SSP4.5 and SSP8.5 projections
- Hybrid approach visualization

---


