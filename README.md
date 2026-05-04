# Clinical Trials Data Analysis

Large-scale analysis of 500,000+ US clinical trials using Apache Spark SQL on Databricks.

## Overview

This project analyzes data from the ClinicalTrials.gov registry using Apache Spark and Databricks. The analysis covers 522,000+ clinical trial records and explores key trends in medical research.

## Key Analyses

- **Trial Type Distribution** — Breakdown of observational studies, interventional studies, and other trial types
- **Top Medical Conditions** — Identification of the most researched conditions in the registry
- **Trial Duration Analysis** — Statistical analysis of average trial length and trends
- **Diabetes Research Trends** — Temporal analysis of diabetes-related clinical trials over time
- **Multi-condition Parsing** — Extraction and analysis of conditions across multiple trial records

## Technologies Used

- **Apache Spark** — Distributed data processing and analytics
- **Databricks** — Managed Apache Spark platform
- **Spark SQL** — SQL-based data analysis and transformation
- **Python** — Data manipulation and visualization

## Dataset

- **Source**: ClinicalTrials.gov registry
- **Records**: 522,000+ clinical trials
- **File**: `Clinicaltrial_16012025.csv`

## Project Structure

```
clinical-trials-spark-sql/
├── README.md
├── .gitignore
└── notebooks/
    └── clinical_trials_analysis.ipynb
```

## Getting Started

### Prerequisites

- Apache Spark 3.x
- Databricks workspace or local Spark installation
- Python 3.8+
- Jupyter or Databricks notebook environment

### Running the Analysis

1. Clone this repository
2. Open `notebooks/clinical_trials_analysis.ipynb` in your Databricks workspace or Jupyter
3. Update the data file path to point to your `Clinicaltrial_16012025.csv` file
4. Run all cells to execute the full analysis pipeline

## Notebook Contents

The notebook includes:

- Data import and preprocessing
- Exploratory data analysis (EDA)
- SQL-based aggregations and transformations
- Condition-based filtering and analysis
- Temporal trend analysis
- Data visualizations and summary statistics

## Results

The analysis reveals:

- Distribution of trial types across the registry
- Most commonly researched medical conditions
- Average trial duration and duration trends
- Growth trends in diabetes-focused research
- Patterns in clinical trial registration over time

## Notes

- Data preprocessing handles missing values and inconsistent formatting
- Multi-condition trials are parsed to extract individual condition entries
- All analyses use Spark SQL for scalability and performance
- Visualizations are generated using matplotlib and Spark DataFrames

## Author

Data analysis project exploring large-scale medical research trends.

## License

This project is provided as-is for educational and research purposes.
