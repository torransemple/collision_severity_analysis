# Twelve years of evidence: modelling the injury severity of single-vehicle collisions pre- and post-20mph (32 km/h) implementation in Edinburgh and Glasgow

This repository contains a statistical analysis of road traffic collision (RTC) severity (see https://doi.org/10.1016/j.aap.2025.108183), comparing the long-term impacts of 20mph speed limit expansions in Edinburgh and Glasgow.

The study focuses on the distinct policy implementation styles:

Edinburgh: A comprehensive, citywide "blanket" 20mph rollout initiated in 2016.

Glasgow: A targeted, incremental expansion of 20mph zones across the urban network during the same period.

## Data Sources

Road Safety Data: Derived from the Department for Transport (DfT) STAT19 database, licensed under the Open Government Licence v3.0.

## Repository Contents

The `Edinburgh` and `Glasgow` folders contain R Markdown scripts to reproduce the collision severity models in Edinburgh (see `Edinburgh_models.Rmd`) and Glasgow (see `Glasgow_models.Rmd`).

The data subfolder within Edinburgh and Glasgow provides collision severity data for pre- and post-20mph collisions in each city: see `ED_SV_PRE20_model_data.csv` and `ED_SV_POST20_model_data.csv` in Edinburgh, and `GLA_SV_PRE20_model_data.csv` and `GLA_SV_POST20_model_data.csv` in Glasgow.

`session_info.txt`: A comprehensive list of R package versions and dependencies used to ensure environment reproducibility.

## Usage

Environment Setup: Ensure you are using R version 4.5.1 or later. Refer to code/session_info.txt for the exact environment configuration.

Installation: Install the necessary libraries by running the following command in the R console:

R

install.packages(c("tidyverse", "cowplot", "janitor", "sqldf", "lme4"))
Data Loading: The scripts are configured to read data directly from this GitHub repository using raw URLs. If you are working offline, please update the file paths to point to your local /data directory.

## Reproducibility and Session Info

To ensure identical results across different operating systems (particularly when using macOS Tahoe aarch64), this project tracks all implicit dependencies. Please consult the session_info.txt file for specific versions of ggplot2, scales, and RSQLite used in the final computation.

Acknowledgments This research utilises public sector information licensed under the Open Government Licence v3.0 from the UK Department for Transport.

### Contact

Email: torran.semple@eng.ox.ac.uk

Alternative: torranas@gmail.com
