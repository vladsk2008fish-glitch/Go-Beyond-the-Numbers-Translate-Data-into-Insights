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
- [Repository structure](#-repository-structure)
- [Tools](#-tools)
- [Analysis approach](#-analysis-approach)
- [Suggested structure](#-suggested-structure)
- [Running the projects](#-running-the-projects)

## About the course

**Go Beyond the Numbers: Translate Data into Insights** focuses on exploring data, identifying meaningful signals, and communicating findings to support decision-making.

This repository contains coursework and learning materials for the course. Its main focus is **Exploratory Data Analysis (EDA)**, data preparation, visualization, and a structured workflow using the **PACE** framework.

## Repository structure

The repository contains Course 2 labs, their example notebooks and datasets, Tableau workbooks, and the end-of-course TikTok project.

```text
.
├── README.md
├── LICENSE
├── eda-banner.svg
└── Course_2/
    ├── Lab_course_2_modul_2/
    │   ├── Activity_Discover what is in your dataset.ipynb
    │   ├── Exemplar_Discover what is in your dataset.ipynb
    │   └── Unicorn_Companies.csv
    ├── Lab_course_2_module_2.2/
    │   ├── Activity_Structure your data.ipynb
    │   ├── Exemplar_Structure your data.ipynb
    │   └── Unicorn_Companies.csv
    ├── Lab_course_2_module_3.1/
    │   ├── Activity_Address missing data.ipynb
    │   ├── Exemplar_Address missing data.ipynb
    │   └── Unicorn_Companies.csv
    ├── Lab_course_2_module_3.2/
    │   ├── Activity_Validate and clean your data.ipynb
    │   ├── Exemplar_Validate and clean your data.ipynb
    │   └── Modified_Unicorn_Companies.csv
    ├── Project_end_of_course_2/
    │   ├── Activity_Course 3 TikTok project lab.ipynb
    │   ├── tiktok_dataset.csv
    │   └── images/
    │       ├── Analyze.png
    │       ├── Construct.png
    │       ├── Execute.png
    │       ├── Pace.png
    │       └── Plan.png
    ├── Tableau_project_course_2.twbx
    ├── Tableau_project_end_of_course_2.twbx
    └── tiktok_dataset.csv
```

The labs cover discovering a dataset, structuring data, addressing missing values, and validating and cleaning data. The end-of-course project focuses on TikTok data and follows the PACE workflow. The tree above reflects the repository structure shown in the provided screenshots.

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
