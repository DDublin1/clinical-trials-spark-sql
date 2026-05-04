# Data

## Dataset: ClinicalTrials.gov Registry

**Source:** [ClinicalTrials.gov — Download](https://clinicaltrials.gov/ct2/resources/download)  
**Format:** CSV (`Clinicaltrial_16012025.csv`)  
**Size:** ~500,000+ rows  
**License:** Public domain (US National Library of Medicine)

### Key Columns
| Column | Description |
|--------|-------------|
| NCT Number | Unique trial identifier |
| Study Title | Full title of the clinical trial |
| Study Status | Trial status (e.g., COMPLETED, RECRUITING) |
| Conditions | Medical conditions under study |
| Interventions | Treatments or interventions applied |
| Sponsor | Lead sponsoring organisation |
| Start Date | Trial start date |
| Completion Date | Trial completion date |
| Study Type | INTERVENTIONAL, OBSERVATIONAL, etc. |
| Phases | Trial phase (Phase 1–4) |

### Setup
Download the full dataset from ClinicalTrials.gov and place `Clinicaltrial_16012025.csv` in this folder before running the notebook.

Upload to Databricks DBFS or configure the notebook path accordingly.
