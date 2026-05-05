# Cowley_et_al_2026

## Introduction
Here, we present 4 simple R Markdown-based templates for creating customizable, modular dashboards for screen data analysis. Built using the flexdashboard and crosstalk R packages, and HTML widgets, these lightweight, easy-to-build HTML dashboards require no complex installation process or installation of licensed software. They support linked visualizations, threshold-based filtering (e.g., Z-score, p-value, fold change), and interactive data exploration and are shared as a standalone HTML file. This framework enables rapid, flexible hit selection across diverse high-throughput screening applications and is designed for users with basic R experience.

Each dashboard is designed to suit a different analysis output common in a high-throughput screening platform, but all are completely customisable.

## Dashboards
[**VCFG Data 01: Primary Screen Dashboard**](https://pmcc-vcfg.github.io/Cowley_et_al_2026/dashboard/VCFG_Data01_primary_dashboard.html)
This simple dashboard containing filters and one data table is suited to a large primary screen.

[VCFG Data 02: Viability Screen Dashboard](https://pmcc-vcfg.github.io/Cowley_et_al_2026/dashboard/VCFG_Data02_viability_dashboard.html)

[VCFG Data 03: Synergy Drug Interaction Screen Dashboard](https://pmcc-vcfg.github.io/Cowley_et_al_2026/dashboard/VCFG_Data03_synergy_dashboard.html)

[VCFG Data 04: Organoid Screen Dashboard](https://pmcc-vcfg.github.io/Cowley_et_al_2026/dashboard/VCFG_Data04_organoid_dashboard.html)

## How to use
The /dashboard directory contains full annotated R Markdown scripts for each dashboard. This includes description of data preparation from the imported CSV files and detailed explanation of the different panels used in different layouts.

### Example data
Each dashboard has a corresponding directory in the /data folder.

## License
