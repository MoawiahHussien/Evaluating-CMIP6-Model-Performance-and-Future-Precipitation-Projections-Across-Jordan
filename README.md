# Evaluating CMIP6 Model Performance and Future Precipitation Projections Across Jordan's Water Basins Under SSP Scenarios

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXX.svg)](https://doi.org/10.5281/zenodo.XXXXXXX)

## Overview

This repository contains the code and data processing scripts used in the study "Evaluating CMIP6 Model Performance and Future Precipitation Projections Across Jordan's Water Basins Under SSP Scenarios." The research evaluates six CMIP6 models from the RICCAR initiative and projects future precipitation changes under SSP4.5 and SSP8.5 scenarios across Jordan's 12 hydrological basins.

## Repository Structure
Observational Data + RICCAR Climate Data
              ↓
    ┌─────────────────────┐
    │ Model Evaluation    │ (Scripts 1-2)
    │ - Skill metrics     │
    │ - Basin rankings    │
    └─────────────────────┘
              ↓
    ┌─────────────────────┐
    │ Ensemble Creation   │ (Scripts 3-4)
    │ - 3-model ensemble  │
    │ - 6-model ensemble  │
    └─────────────────────┘
              ↓
    ┌─────────────────────┐
    │ Ensemble Validation │ (Scripts 4-5)
    │ - Performance tests │
    │ - Basin comparison  │
    └─────────────────────┘
              ↓
    ┌─────────────────────┐
    │ Seasonal Analysis   │ (Scripts 6-7)
    │ - SSP4.5 & SSP8.5  │
    │ - Temporal changes  │
    └─────────────────────┘
              ↓
    ┌─────────────────────┐
    │ Visualization       │ (Scripts 8-9)
    │ - Hybrid maps       │
    │ - Final projections │
    └─────────────────────┘
