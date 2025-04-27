# QS World University Rankings 2025 Prediction Model

## Achieving 0.99 R² Score using Machine Learning and Deep Learning

## Table of Contents

1. [Abstract](#abstract)
2. [Introduction](#introduction)
3. [Objectives](#objectives)
4. [Methodology](#methodology)
   - [Data Collection and Initial Exploration](#data-collection-and-initial-exploration)
   - [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
   - [Data Visualization and EDA](#data-visualization-and-eda)
   - [Model Development](#model-development)
   - [Model Evaluation](#model-evaluation)
   - [Feature Importance and Interpretability](#feature-importance-and-interpretability)
   - [Prediction and Final Visualization](#prediction-and-final-visualization)
5. [Data Science Process](#data-science-process)
   - [Setting the Research Goal](#setting-the-research-goal)
   - [Retrieving Data](#retrieving-data)
   - [Data Preparation](#data-preparation)
   - [Data Exploration](#data-exploration)
   - [Data Modeling](#data-modeling)
   - [Presentation and Automation](#presentation-and-automation)
6. [Results](#results)
7. [Limitations](#limitations)
8. [Conclusion](#conclusion)

## Project Setup

### Prerequisites

- Python 3.8+
- Required packages listed in `requirements.txt`:

```
numpy>=1.20,<2.0
pandas>=1.3,<2.0
matplotlib>=3.4,<4.0
seaborn>=0.11,<0.13
scikit-learn>=0.24,<1.2
tensorflow-macos>=2.6,<2.9
missingno
```

### Installation

1. Clone this repository
2. Create a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

## Abstract

This project focuses on predicting QS World University Rankings for 2025 using advanced machine learning and deep learning techniques. The model achieves an exceptional R² score of 0.99, demonstrating high accuracy in predicting university rankings based on various institutional metrics and performance indicators.

## Introduction

The QS World University Rankings is one of the most widely recognized and influential university ranking systems globally. This project leverages machine learning and deep learning approaches to analyze and predict university rankings, providing valuable insights for educational institutions and stakeholders.

## Objectives

- Develop a highly accurate prediction model for university rankings
- Identify key factors influencing university rankings
- Provide actionable insights for universities to improve their rankings
- Create a reproducible methodology for future ranking predictions

## Methodology

### Data Collection and Initial Exploration

- Dataset: QS World University Rankings 2025 (Top global universities)
- Features include various institutional metrics and performance indicators
- Initial data exploration to understand the structure and quality of the data

### Data Cleaning and Preprocessing

- Handling missing values
- Feature engineering and selection
- Data normalization and standardization
- Outlier detection and treatment

### Data Visualization and EDA

- Distribution analysis of key features
- Correlation analysis
- Trend identification
- Pattern recognition in ranking determinants

### Model Development

- Implementation of various ML and DL models
- Hyperparameter tuning
- Model architecture optimization
- Cross-validation strategies

### Model Evaluation

- R² score analysis
- Error metrics assessment
- Model performance comparison
- Validation strategies

### Feature Importance and Interpretability

- Feature importance ranking
- SHAP values analysis
- Model interpretability techniques
- Key factor identification

### Prediction and Final Visualization

- Final model predictions
- Visualization of results
- Comparative analysis
- Performance metrics presentation

## Data Science Process

### Setting the Research Goal

- Define clear objectives
- Establish success metrics
- Identify key stakeholders
- Set project scope

### Retrieving Data

- Data source identification
- Data collection methodology
- Quality assurance
- Data validation

### Data Preparation

- Data cleaning
- Feature engineering
- Data transformation
- Dataset structuring

### Data Exploration

- Statistical analysis
- Pattern identification
- Correlation studies
- Anomaly detection

### Data Modeling

- Model selection
- Training process
- Validation methodology
- Performance optimization

### Presentation and Automation

- Results visualization
- Automated reporting
- Pipeline development
- Documentation

## Results

The project achieved remarkable results with an R² score of 0.99, indicating that our model explains 99% of the variance in university rankings. Key findings include:

- Highly accurate prediction capabilities
- Robust model performance across different university types
- Significant feature importance insights
- Strong correlation patterns identified

## Limitations

- Data availability and quality constraints
- Temporal limitations of the dataset
- Model complexity considerations
- External factor influences

## Conclusion

This project successfully demonstrates the capability of machine learning and deep learning techniques in predicting university rankings with high accuracy. The methodology and findings provide valuable insights for educational institutions and policymakers in understanding and improving their ranking positions.