# 📊 Task 4: Data Storytelling & Statistical Validation
## Project Overview
This task focuses on transforming analytical findings into a business narrative and validating key insights using statistical methods. The project uses the Netflix content dataset to derive meaningful business insights through storytelling and hypothesis testing.
---
## Objective
The objective of this task is to:
- Convert data analysis findings into a compelling business story.
- Apply statistical validation techniques to support analytical conclusions.
- Present insights in a way that is understandable for business stakeholders.
---
## Dataset Information
- **Dataset:** Netflix Titles Dataset
- **Total Records:** 8,807
- **Total Features:** 12
### Features Used:
- show_id
- type
- country
- release_year
- rating
- duration
- listed_in
- description
---
## Data Storytelling Insights
### 1. Content Type Distribution
- Netflix contains significantly more Movies than TV Shows.
- Movies account for approximately 69.6% of total content.
### 2. Country-wise Content Production
- The United States contributes the highest amount of content.
- India ranks second in content production.
### 3. Content Rating Analysis
- TV-MA is the most common content rating on Netflix.
- Adult-oriented content dominates the platform.
### 4. Release Year Trends
- Netflix content production increased rapidly between 2015 and 2019.
- Content additions declined after 2020.
---
## Statistical Validation
### Hypothesis
**Null Hypothesis (H₀):**
Netflix has an equal distribution of Movies and TV Shows.
**Alternative Hypothesis (H₁):**
Netflix does not have an equal distribution of Movies and TV Shows.
---
## Statistical Test Used
- **Test:** Chi-Square Goodness-of-Fit Test
- **Library:** SciPy
### Observed Values
| Content Type | Count |
|--------------|-------|
| Movies | 6131 |
| TV Shows | 2676 |
### Expected Values
| Content Type | Expected Count |
|--------------|---------------|
| Movies | 4403.5 |
| TV Shows | 4403.5 |
---
## Results
| Metric | Value |
|---------|--------|
| Chi-Square Statistic | 1355.40 |
| P-Value | 1.03 × 10⁻²⁹⁶ |
---
## Conclusion
Since the p-value is significantly less than 0.05, we reject the null hypothesis.
This confirms that Netflix's content distribution is not equally divided between Movies and TV Shows. Movies significantly dominate the platform's content library.
---
## Tools & Technologies Used
- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Jupyter Notebook
---
## Project Files
```
Task4-Data-Storytelling-Statistical-Validation/
│
├── Task4_Statistical_Validation.ipynb
├── Netflix_Statistical_Report.docx
├── Presentation.pptx
├── Images/
└── README.md
```
---
## Key Learning Outcomes
- Data storytelling techniques
- Business insight communication
- Statistical hypothesis testing
- Chi-Square test implementation
- Data-driven decision making
- Professional reporting and presentation
---
## Author
**Yuva Teja**
Data Analyst Internship Project
GitHub: https://github.com/Yuvatejayeturi
