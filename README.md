## About

Public health researcher working across nutrition, tobacco, and health policy. Most of what you'll find here is replication code for peer-reviewed studies: randomized trials, national survey epidemiology, evidence synthesis, and cost analyses.

## What's in my repos

### Randomized trials and experiments

**[swaps](https://github.com/rulm0000/swaps)** (Stata). Replication pipeline for a food-swap RCT. Participant characteristics, primary treatment effects, moderation analyses, Bonferroni-Holm corrected p-values, effects by food group, and ClinicalTrials.gov reporting exports.  
Paper: [Grummon et al., *PLOS Medicine* (2026)](https://doi.org/10.1371/journal.pmed.1004847)

**[social_media_wl](https://github.com/rulm0000/social_media_wl)** (Stata). Social media warning label trial. Mixed-effects models of perceived message effectiveness and awareness by warning topic, carryover sensitivity, moderator analyses, and CONSORT counts, plus a secondary study comparing AI-generated with human-selected priority messages.  
Paper: [Grummon et al., *JAMA Health Forum* (2026)](https://doi.org/10.1001/jamahealthforum.2026.3014)

### Survey epidemiology (BRFSS)

**[Smoking-Prevalence-Analysis-2018-2024](https://github.com/rulm0000/Smoking-Prevalence-Analysis-2018-2024)** (SAS, Stata, Python). Urban-rural differences in adult smoking prevalence, 2018-2024. Survey-weighted logistic and GEE models for all 50 states plus nationwide, simple slopes for significant year-by-rurality interactions, predicted probability panels, and choropleth maps.

**[mastersthesis](https://github.com/rulm0000/mastersthesis)** (Python). Master's thesis analysis of pooled BRFSS data: weighted descriptive statistics and state-level odds ratio choropleth maps.

### Evidence synthesis

**[unhealthy-food-umbrella](https://github.com/rulm0000/unhealthy-food-umbrella)** (R, Python). Umbrella review of ultra-processed foods and health outcomes. Sensitivity analyses, heterogeneity assessment, and publication-ready forest plots.  
Paper: [Ulm et al., *Child and Adolescent Psychiatry and Mental Health* (2026)](https://doi.org/10.1186/s13034-026-01079-4)

### Health economics

**[Treatment_Survivorship_Costing_CRC](https://github.com/rulm0000/Treatment_Survivorship_Costing_CRC)** (Python). Colorectal cancer treatment and survivorship cost estimation, with weighted averages by age group, race, sex, and stage.

## Methods and tools

Survey-weighted regression, mixed-effects models, GEE and cluster-robust inference, moderation and subgroup analysis, multiple-comparison correction, meta-analysis and heterogeneity assessment, cost estimation, and geospatial visualization.

Stata, SAS, R, and Python (pandas, geopandas, matplotlib, plotly).

## Notes on data

These repositories hold analytic code. Restricted, licensed, or oversized inputs such as raw survey exports, licensed product catalogs, and BRFSS or ACS source files are intentionally excluded; each README documents where to obtain them and how to rebuild the analytic files.
