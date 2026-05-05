# Cowley_et_al_2026

## Introduction
Here, we present 4 simple R Markdown templates for creating customizable, modular dashboards for screen data analysis. Built using the flexdashboard and crosstalk R packages, and HTML widgets, these lightweight, easy-to-build HTML dashboards require no complex installation process or installation of licensed software. They support linked visualizations, threshold-based filtering (e.g., Z-score, p-value, fold change), and interactive data exploration and are shared as a standalone HTML file. This framework enables rapid, flexible hit selection across diverse high-throughput screening applications and is designed for users with basic R experience.


## Dashboards
Use the below links to view and explore the functionality of the full interactive version of each dashboard: <br>
<br>
[**VCFG Dataset 1: Primary Screen Dashboard**](https://pmcc-vcfg.github.io/Cowley_et_al_2026/dashboard/VCFG_Data01_primary_dashboard.html)<br>
Dashboard containing filters and a table, with vertical scrolling.

[**VCFG Dataset 2: Viability Screen Dashboard**](https://pmcc-vcfg.github.io/Cowley_et_al_2026/dashboard/VCFG_Data02_viability_dashboard.html) <br>
Dashboard with a one page view, containing filters, tables, and dose response curves.

[**VCFG Dataset 3: Synergy Drug Interaction Screen Dashboard**](https://pmcc-vcfg.github.io/Cowley_et_al_2026/dashboard/VCFG_Data03_synergy_dashboard.html)<br>
Dashboard with a one page view displaying synergy drug interaction data, using filters, scatter plots, tables, dose response curves, and heatmaps.

[**VCFG Dataset 4: Organoid Screen Dashboard**](https://pmcc-vcfg.github.io/Cowley_et_al_2026/dashboard/VCFG_Data04_organoid_dashboard.html)<br>
Dashboard with a one page view displaying filters, tables, scatter plots, and integrated endpoint images for phenotype verification.


## How to use
The /dashboard directory contains full annotated R Markdown scripts for each dashboard. This includes description of data preparation from the imported CSV files and detailed explanation of the different panels used in different layouts.

### Example data
Each dashboard has a corresponding directory in the /data folder.

### Packages
Dashboards were created using R version 4.5.0. See renv.lock for specific packages and versions used.

## License
* Code in this repository is licensed under the MIT License (see license.md)
* Dashboard outputs (HTML files) are licensed under CC BY 4.0.
* Datasets are licensed under CC0 1.0 (public domain) (see license-data.md)

Please cite the associated publication when using this work.
