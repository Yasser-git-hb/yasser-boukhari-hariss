# Intelligent Performance Monitoring of a Reverse Osmosis Desalination Plant

## Overview

This project was developed during my **Final Year Project (PFA)** at **OCP Phosboucraa – Laâyoune, Morocco**, in collaboration with the **École Nationale Supérieure des Mines de Rabat (ENSMR)**.

The objective was to develop an intelligent approach for monitoring and analyzing the performance of an industrial **seawater reverse osmosis (RO) desalination plant** using SCADA historical data, physical modeling, and Machine Learning techniques.

The project combines:

- Process engineering
- Energy performance analysis
- Hydraulic modeling
- Industrial data analytics
- Machine Learning
- Interactive visualization


---

# Objectives

The main objectives of this project were:

- Analyze the hydraulic and energetic performance of the desalination process.
- Reconstruct key industrial performance indicators.
- Evaluate the **Specific Energy Consumption (SEC)**.
- Study pressure losses throughout the process.
- Analyze the relationship between hydraulic parameters and energy consumption.
- Develop predictive models for SEC estimation.
- Create an interactive monitoring dashboard for performance analysis.


---

# Methodology

## Data Engineering

Industrial SCADA historical data were processed through:

- Data extraction and organization.
- Cleaning and preprocessing.
- Time synchronization between different equipment.
- Creation of analysis-ready datasets.


## Physical and Energetic Analysis

The studied indicators include:

### Specific Energy Consumption (SEC)

\[
SEC=\frac{Electrical\ Energy\ Consumption}{Permeate\ Production}
\]


### Recovery Rate

Evaluation of the water recovery performance of the reverse osmosis process.


### Hydraulic Performance

Analysis of pressure losses across the system:

- Pretreatment stage.
- High-pressure pumping system.
- Reverse osmosis membranes.

The membrane pressure drop was evaluated as:

\[
\Delta P_{membrane}
=
P_{HP1,outlet}
-
P_{reject}
\]


---

# Machine Learning Approach

Different models were investigated to analyze the relationship between operating conditions and energy performance.

## Models Used

- Linear Regression
- Ridge Regression
- Random Forest
- Gradient Boosting


## Applications

The models were used for:

- SEC prediction.
- Comparison between linear and non-linear relationships.
- Identification of influential parameters.
- Analysis of the contribution of hydraulic losses to energy performance.


---

# Dashboard Development

An interactive monitoring dashboard was developed using **Streamlit**.

The dashboard allows visualization of:

- Energy performance indicators.
- SEC evolution.
- Recovery rate.
- Hydraulic parameters.
- Pressure losses.
- Comparison between reverse osmosis lines.


---

# Technologies

## Programming

- Python


## Data Analysis

- Pandas
- NumPy
- Matplotlib


## Machine Learning

- Scikit-learn


## Visualization

- Streamlit


## Data Source

- Industrial SCADA historical database


---

# Project Structure

├── notebooks/
│ ├── 01_data_preparation.ipynb
│ ├── 02_process_diagnosis.ipynb
│ ├── 03_energy_and_ML_analysis.ipynb
│ └── 04_predictive_maintenance.ipynb
│
├── dashboard/
│ └── Streamlit monitoring dashboard
│
├── figures/
│ └── Project illustrations
│
├── report/
│ └── Project documentation
│
├── requirements.txt
└── README.md
---

# Research Perspectives

This project opens several perspectives for future developments:

- Real-time monitoring using live SCADA data streams.
- Advanced anomaly detection methods.
- Physics-informed Machine Learning approaches.
- Predictive maintenance models for desalination equipment.
- Integration of hydraulic and energetic models into a digital twin framework.
- Development of intelligent decision-support tools for industrial water and energy systems.


---

# Author

**Yasser BOUKHARI HARISS**

Engineering Student – Energy Engineering


Interested in:

- Industrial performance optimization.
- Energy efficiency.
- Process modeling.
- Artificial Intelligence applied to industrial systems.
- Data-driven engineering.
- Sustainable water and energy systems.


---

# Acknowledgements

This project was carried out at **OCP Phosboucraa** in collaboration with the **École Nationale Supérieure des Mines de Rabat (ENSMR)**.

I would like to thank my industrial and academic supervisors for their guidance, technical support, and valuable insights throughout this project.
