# MIS 311 - Student Placement Analysis

## Project Overview
This repository showcases my MIS 311 Assignment #1 project, which focuses on exploratory data analysis of a Student Placement dataset. The analysis examines the dataset structure, checks data quality, summarises key characteristics, and identifies meaningful patterns related to student placement outcomes.

## Dataset
The selected dataset contains **2,000 student records and 26 variables**. It includes information on students’ academic background, technical skills, practical experience, soft skills, and placement outcomes.

The main outcome variable is:
- **placed**: `1 = Placed`, `0 = Not Placed`

## Project Objectives
- Understand the overall structure and context of the dataset
- Check for missing values and duplicate records
- Summarise key numerical variables using descriptive statistics
- Identify two meaningful insights related to student placement outcomes
- Present findings through clear visualisations

## Files in This Repository
- `Student_Placement_Analysis.ipynb` – Full exploratory data analysis notebook
- `14_Student Placement.xlsx` – Original dataset used for the analysis
- `README.md` – Project overview and documentation

## Key Findings

### Insight 1: Academic Performance and Selected Soft Skills Differ by Placement Status
Placed students showed higher average **CGPA**, **teamwork**, and **problem-solving** scores than non-placed students. This suggests that student placement outcomes in this dataset may be associated with a combination of academic performance and selected soft skills.

### Insight 2: Greater Internship Experience Is Associated with Higher Placement Rates
The placement rate increased from **41.08%** among students with no internships to **54.53%** among students with two or more internships. This indicates that practical work experience may be an important employability-related factor associated with stronger placement outcomes.

## Tools Used
- Python
- Google Colab
- Pandas
- Matplotlib

## Conclusion
This project demonstrates how exploratory data analysis can be used to transform a raw dataset into meaningful insights. The findings suggest that both academic capability and employability-related experience may be relevant when examining student placement outcomes.
