**NHS GP Appointment Data Analysis (England)**

**Project Overview**

This project analyses publicly available NHS GP appointment data to explore patterns in primary care demand across England. The analysis focuses on transforming complex, non-standard reporting tables into a clean analytical dataset and identifying trends that could support operational planning and healthcare service delivery.

Real-world NHS datasets are often distributed in reporting formats rather than analysis-ready structures. This project demonstrates how raw statistical publications can be converted into structured datasets suitable for analysis, insight generation, and future automation.

**Objectives**

Clean and standardise NHS GP appointment datasets

Transform reporting tables into analysis-ready format

Handle multi-sheet Excel files with non-standard headers

Create reusable data cleaning functions

Explore appointment activity trends over time

Apply reproducible analytical workflow principles

**🗂 Dataset**

Source: NHS England Open Data
Dataset: Monthly GP Appointment Statistics

The dataset includes:

Appointment volumes by month

Delivery type (face-to-face, telephone, etc.)

National-level operational activity metrics

Multiple Excel workbooks containing structured reporting tables (e.g., Table 1a)

Key challenge:

Column names were embedded within rows and required restructuring before analysis.

**🛠 Tools & Technologies**

Python

Pandas – data cleaning & transformation

NumPy – numerical handling

Jupyter Notebook

VS Code

Git & GitHub – version control

**Analytical Approach**

The workflow followed a structured analytical pipeline:

Loaded raw NHS Excel workbooks

Identified header rows within reporting tables

Restructured datasets into tabular format

Standardised date fields and month variables

Preserved both reporting month labels and datetime formats

Encapsulated cleaning logic into reusable Python functions

Prepared datasets for exploratory analysis and future modelling

This approach mirrors Reproducible Analytical Pipeline (RAP) principles commonly used within UK government analytical professions.
