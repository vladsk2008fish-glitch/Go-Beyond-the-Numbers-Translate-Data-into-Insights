# Go Beyond the Numbers
### Translate Data into Insights

<p align="center">
  <img src="https://img.shields.io/badge/Google-Advanced%20Data%20Analytics-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google Advanced Data Analytics">
  <img src="https://img.shields.io/badge/Course-02-7C3AED?style=for-the-badge" alt="Course 2">
  <img src="https://img.shields.io/badge/Focus-EDA-14B8A6?style=for-the-badge" alt="Exploratory Data Analysis">
  <img src="https://img.shields.io/badge/Workflow-PACE-F97316?style=for-the-badge" alt="PACE workflow">
</p>

> Coursework for **Course 2** of the **Google Advanced Data Analytics** certificate program. I explore data, identify patterns, and turn analytical results into clear insights.

## Contents

- [About the course](#-about-the-course)
- [Repository contents](#-repository-contents)
- [Tools](#-tools)
- [Analysis approach](#-analysis-approach)
- [Suggested structure](#-suggested-structure)
- [Running the projects](#-running-the-projects)

## About the course

**Go Beyond the Numbers: Translate Data into Insights** focuses on exploring data, identifying meaningful signals, and communicating findings to support decision-making.

This repository contains coursework and learning materials for the course. Its main focus is **Exploratory Data Analysis (EDA)**, data preparation, visualization, and a structured workflow using the **PACE** framework.

## Repository contents

This repository is intended for coursework in data analysis and visualization. Each assignment can be organized as a separate notebook or project, with a brief description of the question, analysis steps, and findings.

> **Note:** No assignment or dataset files are currently present in the repository folder. The structure below is a suggested way to organize them, not a list of files that already exist.

## Tools

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas">
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square" alt="Seaborn">
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square" alt="Matplotlib">
  <img src="https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white" alt="Tableau">
</p>

| Tool | How I use it |
|---|---|
| **Python** | Data analysis and automation of repeatable tasks |
| **pandas** | Cleaning, transforming, and exploring tabular data |
| **NumPy** | Numerical operations and array processing |
| **datetime** | Working with dates and time values |
| **Seaborn** | Statistical data visualization |
| **Matplotlib** | Creating and customizing charts |
| **Tableau** | Interactive visualizations and dashboards |

## Analysis approach

### EDA — Exploratory Data Analysis

- Inspecting data structure, types, and quality;
- Identifying missing values, duplicates, and potential anomalies;
- Summarizing statistics and exploring distributions;
- Analyzing relationships between variables;
- Visualizing patterns;
- Summarizing findings and identifying follow-up questions.

### PACE — A structured workflow

| Stage | How I apply it |
|---|---|
| **P — Plan** | Define the problem, analysis goals, and key questions |
| **A — Analyze** | Prepare and explore the data using EDA |
| **C — Construct** | Create visualizations and communicate the results clearly |
| **E — Execute** | Present findings and identify possible next steps |

## Suggested structure

```text
.
├── README.md
├── eda-banner.svg
├── data/
│   ├── raw/                  # Original data, if sharing is permitted
│   └── processed/            # Prepared datasets
├── notebooks/
│   ├── task-01-eda.ipynb
│   └── task-02-insights.ipynb
├── tableau/
│   └── dashboard-links.md    # Links to published dashboards
└── reports/
    └── findings.md           # Brief findings for each assignment
```

Add only folders and files that match the actual project contents. Before publishing, check whether you are allowed to share the course datasets.

## Running the projects

For Jupyter notebooks, install Python and the required libraries:

```bash
python -m pip install pandas numpy seaborn matplotlib
```

Open the desired `.ipynb` file in **Jupyter Notebook**, **JupyterLab**, or **Visual Studio Code**. `datetime` is part of Python's standard library and does not need to be installed separately. Add links to interactive Tableau dashboards if they have been published.

---

<p align="center">
  <sub>Coursework repository · Google Advanced Data Analytics · Course 2</sub>
</p>
