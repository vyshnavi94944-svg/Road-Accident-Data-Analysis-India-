# Data

## Overview

This directory contains the datasets used in the Road Accident Data Analysis (India) project.

The project uses recorded road accident data from 2021 to 2024 for data loading, extraction, validation, cleaning, aggregation, analysis, and visualization.

---

## Dataset Files

The `data` directory is organized into two main sections:

```text
data/
│
├── README.md
│
├── raw/
│   └── india_road_accidents.csv
│
└── processed/
    └── aggregated_road_accidents.csv
Raw Data

The raw dataset is stored in:

data/raw/india_road_accidents.csv

This file contains the original road accident records used as the starting point for the analysis.

The raw data is preserved separately so that the original dataset remains available throughout the project workflow.

Processed Data

The processed dataset is stored in:

data/processed/aggregated_road_accidents.csv

This file contains the aggregated accident data generated during the data-analysis workflow.

The processed data is used for further analysis and visualization.

Data Processing Workflow

The dataset follows the following processing workflow:

Raw Dataset
     ↓
Data Loading
     ↓
Data Acquisition & Filtering
     ↓
Data Extraction
     ↓
Data Validation & Cleaning
     ↓
Data Aggregation & Representation
     ↓
Processed / Aggregated Dataset
     ↓
Data Analysis
     ↓
Data Visualization
Data Analysis

The dataset is used to analyze:

Accident counts
Fatalities
Severe injuries
Minor injuries
Total injuries
Accident distribution
State-wise accident patterns
Relationship between accidents and fatalities
Relationship between accidents and total injuries
Data Integrity

The raw dataset is kept separate from the processed dataset.

This separation helps maintain the original data while allowing cleaned and aggregated data to be generated for analysis.

The project does not modify the original raw dataset directly.

Usage

The raw dataset can be used as the input for the Stage 1 to Stage 4 notebooks.

The processed and aggregated dataset can be used by the later analysis and visualization stages.

The recommended workflow is:

Raw Data
   ↓
Validation & Cleaning
   ↓
Aggregation
   ↓
Analysis
   ↓
Visualization
Note

The analysis and findings in this project are based on the road accident records available in the supplied dataset covering 2021–2024.

The dataset should be interpreted within the scope of the available records.