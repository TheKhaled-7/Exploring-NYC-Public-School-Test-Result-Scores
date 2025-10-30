# NYC Public Schools SAT Performance Analysis

## 📊 Project Overview
This project analyzes the SAT performance of New York City public schools to identify top-performing institutions and examine borough-level educational trends. The analysis addresses three key questions about school performance using standardized test data.

## 🎯 Objectives
- Identify the best math-performing schools in NYC
- Determine the top 10 schools based on overall SAT scores
- Analyze borough-level performance variations and identify areas with the highest score disparities

## 📁 Dataset
The analysis uses `schools.csv` containing NYC public school data with the following relevant columns:
- `school_name`: Name of the school
- `borough`: NYC borough location
- `average_math`: Average math SAT score (max 800)
- `average_reading`: Average reading SAT score (max 800) 
- `average_writing`: Average writing SAT score (max 800)

## 🔍 Key Analysis Questions

### 1. Best Math Schools
**Question:** Which schools are the top performers in mathematics?
- **Criteria:** Schools with average math scores greater than 640/800
- **Output:** Sorted list of schools by math performance

### 2. Top 10 Overall SAT Performers
**Question:** Which 10 schools have the highest combined SAT scores?
- **Methodology:** Sum of math, reading, and writing scores
- **Output:** Ranked list of top 10 schools

### 3. Borough Performance Analysis
**Question:** Which borough shows the largest variation in SAT performance?
- **Metrics:** Standard deviation of total SAT scores by borough
- **Additional Insights:** Number of schools, average SAT scores per borough
- **Output:** Borough with highest score variability and related statistics

## 💻 Technical Implementation
- **Language:** Python
- **Libraries:** Pandas for data manipulation and analysis
- **Methods:** Data filtering, aggregation, grouping, and statistical analysis

## 📈 Key Findings
The analysis reveals:
- Top-performing math schools exceeding 640 average score
- Elite schools dominating overall SAT performance
- Boroughs with significant educational outcome disparities
- Quantitative insights for educational policy decisions

## 🛠️ Usage
```python
import pandas as pd
schools = pd.read_csv("schools.csv")
# Run analysis cells to reproduce results
```

## 👥 Stakeholders
- Education policymakers
- School administrators
- Parents and students
- Educational researchers
- Government agencies

This analysis provides data-driven insights to support educational decision-making and resource allocation across New York City's public school system.
