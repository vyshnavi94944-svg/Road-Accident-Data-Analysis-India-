# Road Accident Data Analysis (India)

## Project Overview

This project analyzes recorded road accident data in India from 2021 to 2024 using Python and Pandas. The analysis follows a structured data-analysis workflow covering data loading, acquisition, extraction, validation, cleaning, aggregation, analysis, visualization, and interpretation.

The project focuses on identifying accident patterns, trends, severity categories, causes, vehicle types, speed-limit conditions, alcohol involvement, pedestrian involvement, and daylight-related accident patterns.

**Team:** Data Analysis Essentials – Cornerstone Project  
**Project:** Road Accident Data Analysis (India)  
**Dataset:** Road Accident Data – 2021–2024

---

## Problem Statement

Road accidents are a major public safety concern, and accident records can be difficult to understand when stored as raw data. Analyzing accident information across different years and accident categories requires systematic data analysis.

This project applies data-analysis techniques to study road accident records from 2021 to 2024, identify important patterns, and present the findings through clear visualizations.

---

## Objectives

- Study recorded road accident patterns in India from 2021–2024.
- Analyze accident trends across different years.
- Examine accident severity categories.
- Identify important accident causes.
- Analyze accident involvement by vehicle type.
- Examine accidents exceeding the recorded road speed limit.
- Analyze alcohol involvement and pedestrian involvement.
- Compare accident patterns based on daylight conditions.
- Validate and clean the accident dataset.
- Aggregate accident data for meaningful comparison.
- Present findings using statistical analysis and visualizations.
- Interpret the results and identify important accident patterns.

---

## Scope and Significance

### Scope

The project is limited to the road accident records represented in the supplied dataset. It covers recorded accident data from 2021 through 2024 and focuses on accident categories, severity, causes, vehicle types, speed-limit conditions, alcohol involvement, pedestrian involvement, and daylight conditions.

### Significance

The analysis provides a structured way to understand patterns in recorded road accident data. It helps organize accident information and makes comparisons across years and accident categories easier through data analysis and visualization.

The project is intended for educational and data-analysis purposes and should be interpreted within the scope and limitations of the supplied dataset.

---

## Dataset

### Dataset Description

The project uses a road accident dataset covering recorded accident data from 2021 to 2024.

The dataset contains information that can be used to analyze:

- Accident year
- Accident severity
- Accident causes
- Vehicle types
- Road speed-limit conditions
- Alcohol involvement
- Pedestrian involvement
- Daylight conditions
- Other recorded accident-related categories

### Data Source

The project uses the road accident dataset supplied for the Data Analysis Essentials project.

The analysis is performed on the records available in the supplied dataset.

---

## Project Workflow

The project follows an eight-module data-analysis workflow:

1. **Data Loading & Reading**
2. **Data Acquisition & Filtering**
3. **Data Extraction**
4. **Data Validation & Cleaning**
5. **Data Aggregation & Representation**
6. **Data Analysis**
7. **Data Visualization**
8. **Results & Interpretation**

The overall workflow can be represented as:

```text
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
Data Analysis
     ↓
Data Visualization
     ↓
Results & Interpretation
Repository Structure
Road-Accident-Data-Analysis(India)/
│
├── data/
│   ├── README.md
│   ├── raw/
│   │   └── india_road_accidents.csv
│   └── processed/
│       └── aggregated_road_accidents.csv
│
├── notebooks/
│   ├── Stage_1_Data_Loading/
│   │   ├── Stage_1_Data_Loading.ipynb
│   │   └── README.md
│   │
│   ├── Stage_2_Data_Acquisition/
│   │   ├── Stage_2_Data_Acquisition.ipynb
│   │   └── README.md
│   │
│   ├── Stage_3_Data_Extraction/
│   │   ├── Stage_3_Data_Extraction.ipynb
│   │   └── README.md
│   │
│   ├── Stage_4_Data_Validation_Cleaning/
│   │   ├── Stage_4_Data_Validation_Cleaning.ipynb
│   │   └── README.md
│   │
│   ├── Stage_5_Data_Aggregation/
│   │   ├── Stage_5_Data_Aggregation.ipynb
│   │   └── README.md
│   │
│   ├── Stage_6_Data_Analysis/
│   │   ├── Stage_6_Data_Analysis.ipynb
│   │   └── README.md
│   │
│   ├── Stage_7_Data_Visualization/
│   │   ├── Stage_7_Data_Visualization.ipynb
│   │   └── README.md
│   │
│   └── Stage_8_Results_Interpretation/
│       ├── Stage_8_Results_Interpretation.ipynb
│       └── README.md
│
├── outputs/
│   └── visualizations/
│
├── review-ppts/
│   └── Road_Accident_Data_Analysis.pptx
│
├── README.md
├── requirements.txt
└── .gitignore
Data Processing and Analysis
Data Loading and Reading

Stage 1 loads the road accident dataset using Python and Pandas.

The initial inspection includes:

Loading the dataset
Viewing the first records
Viewing the last records
Checking dataset dimensions
Checking column names
Checking data types
Inspecting dataset information
Generating descriptive statistics
Exploring categorical values
Data Acquisition and Filtering

Stage 2 focuses on selecting the required accident records and filtering the relevant data for further analysis.

The filtering process helps prepare the dataset for extraction, validation, and cleaning.

Data Extraction

Stage 3 extracts the important fields required for road accident analysis.

The extracted information is used for:

Accident comparisons
Category-wise analysis
Year-wise analysis
Severity analysis
Cause analysis
Vehicle-type analysis
Speed-limit analysis
Other accident-related comparisons
Data Validation and Cleaning

Stage 4 checks the quality and consistency of the accident dataset.

The validation and cleaning process includes:

Checking missing values
Checking duplicate records
Checking data consistency
Checking data types
Validating relevant accident categories
Cleaning records where required
Preparing the dataset for aggregation and analysis

Data cleaning improves the reliability and consistency of the subsequent analysis.

Data Aggregation and Representation

Stage 5 groups and summarizes accident data to make meaningful comparisons.

The aggregation process is used to represent accident information across:

Years
Accident severity
Accident causes
Vehicle types
Speed-limit conditions
Alcohol involvement
Pedestrian involvement
Daylight conditions
Data Analysis

Stage 6 performs descriptive and statistical analysis of the cleaned and aggregated accident data.

The analysis focuses on:

Year-wise accident trends
Accident severity
Major accident causes
Vehicle involvement
Speed-limit conditions
Alcohol involvement
Pedestrian involvement
Daylight conditions
Relationships between selected accident variables
Data Visualization

Stage 7 creates visual representations of the analyzed accident data.

The visualization outputs are stored in:

outputs/visualizations/

The visualizations include charts for:

Accident counts by state
Accident distribution by state
Fatalities by state
Accidents versus fatalities
Accident distribution
Distribution of fatalities
Severe and minor injuries by state
Accidents versus total injuries

These visualizations make accident patterns and relationships easier to understand.

Results and Interpretation

Stage 8 interprets the analyzed results and visualizations.

The interpretation focuses on identifying important accident patterns and explaining the observations obtained from the analysis.

The results are presented within the scope of the available dataset.

Key Findings

The analysis presented in the project identifies the following observations:

2024 recorded the highest number of accidents with 72 cases.
Fatal accidents were the most common severity category, with 118 cases.
Overspeeding was the leading recorded cause, appearing in 74 accidents.
Two-wheelers were the most common vehicle type, involved in 81 accidents.
81.7% of the recorded accidents exceeded the road speed limit.
21.7% of accidents involved alcohol.
29.6% of accidents involved pedestrians.
Daylight accidents were more common, with 135 recorded cases.

These findings describe patterns observed in the supplied dataset and should be interpreted within the dataset's scope.

Data Visualization

The project visualization outputs are available in:

outputs/visualizations/

The visualization stage provides graphical representations of accident counts, fatalities, injuries, distributions, and relationships between accident-related variables.

Visualizations help convert the processed accident data into a form that is easier to compare and interpret.

Implementation Workflow
1. Data Loading & Reading
              ↓
2. Data Acquisition & Filtering
              ↓
3. Data Extraction
              ↓
4. Data Validation & Cleaning
              ↓
5. Data Aggregation & Representation
              ↓
6. Data Analysis
              ↓
7. Data Visualization
              ↓
8. Results & Interpretation
Output Flow
Raw Dataset
     ↓
Cleaned Dataset
     ↓
Aggregated Data
     ↓
Analysis
     ↓
Visualizations
     ↓
Key Insights
Limitations
The analysis is limited to the accident records available in the supplied dataset.
The dataset covers the period from 2021 to 2024.
Recorded accident categories may not represent every possible road accident factor.
The analysis describes patterns in the available data and does not establish causation.
Missing or incomplete information in the source dataset can affect some analyses.
The findings should be interpreted within the scope of the dataset rather than as a complete representation of all road accidents in India.
The results are intended primarily for educational and data-analysis purposes.
How to Run the Project
Requirements

Python 3 and the packages listed in requirements.txt.

Install the required packages using:

pip install -r requirements.txt
Running the Notebooks

The project notebooks can be opened using Google Colab or Jupyter Notebook.

Recommended execution order:

Stage 1 → Stage 2 → Stage 3 → Stage 4
        → Stage 5 → Stage 6 → Stage 7 → Stage 8

Run the notebook cells from top to bottom so that the output of each stage can be used by the subsequent stages where required.

Review Presentation

The project presentation is included in the repository under:

review-ppts/Road_Accident_Data_Analysis.pptx

The presentation covers:

Problem Statement
Introduction
Current Approach and Limitations
Proposed Approach
Dataset Description
Code Snippets
Methodology
Data Visualization
Key Insights and Analysis
Implementation Workflow
Conclusion
Team Information

Project: Road Accident Data Analysis (India)

Course: Data Analysis Essentials
Project Type: Cornerstone Project

Team Member	Roll Number
N.V. Nanda Kishore	25B11CS644
P. Lakshmanudu	25B11CS774
B. Harshini	25B11CSA80
D. Sai Vyshnavi	25B11CS246
Y. Ram Prasad	25B11CSA47

Guide: Mr. K. Ashok Teja, Assistant Professor, CSE Department

Tools and Technologies
Python 3 — programming and data analysis
Pandas — data loading, filtering, cleaning, grouping, and aggregation
NumPy — numerical calculations and analysis
Matplotlib — data visualization
Seaborn — statistical visualization
Google Colab — notebook execution
Jupyter Notebook — notebook-based analysis
Conclusion

This project demonstrates a complete data-analysis workflow for road accident data using Python.

The project covers data loading, acquisition, extraction, validation, cleaning, aggregation, analysis, visualization, and interpretation.

Data cleaning and preprocessing improve the reliability of the analysis, while visualizations make accident patterns and trends easier to understand.

The analysis identifies important patterns related to accident years, severity, causes, vehicle types, speed-limit conditions, alcohol involvement, pedestrian involvement, and daylight conditions.

The project provides a structured approach for understanding recorded road accident patterns and demonstrates how data analysis and visualization can be applied to road safety data.

Future Scope

Future work can include:

Using larger accident datasets
Incorporating more recent or live accident data
Adding additional accident-related variables
Performing advanced statistical analysis
Applying predictive analysis and machine learning
Developing interactive dashboards