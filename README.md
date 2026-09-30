
## Data Cleaning & Preparation

The dataset was cleaned and prepared using Python and Pandas before performing the analysis.

The following steps were completed:

- Loaded the CSV dataset into a Pandas DataFrame.
- Reviewed the dataset structure and data types.
- Removed the unnecessary `Unnamed: 20` column.
- Checked for missing values.
- Converted percentage fields from text format into numerical values.
- Converted `Week_Start_Date` into a datetime format.
- Verified the final dataset structure and data types.
- Prepared the cleaned dataset for further analysis and visualisation.
## Analysis Performed

The following analyses were carried out using Python and Pandas:

### 1. Overall KPI Analysis

Calculated key operational metrics including:

- Average Productivity
- Average Quality
- Average Accuracy
- Average Adherence
- Average Overall Score
- Total Cases Reviewed
- Total Target Cases
- Total Errors
- Total Overtime Hours
- Overall Error Rate

### 2. Performance Status Analysis

Analysed the proportion of records classified as:

- Below Target
- Met Target
- Exceeded Target

### 3. Team Performance Analysis

Compared teams using:

- Productivity
- Quality
- Accuracy
- Adherence
- Overall Score
- Total Cases
- Total Errors
- Error Rate
- Overtime Hours

### 4. Weekly Performance Analysis

Analysed performance trends across the 12 weeks in the dataset to identify changes in:

- Productivity
- Quality
- Accuracy
- Adherence
- Overall Score
- Cases Reviewed
- Errors

### 5. Employee-Level Analysis

Analysed individual employee performance using:

- Average Productivity
- Average Quality
- Average Accuracy
- Average Adherence
- Average Overall Score
- Total Cases
- Total Errors
- Error Rate
- Overtime

### 6. Correlation Analysis

Examined relationships between key performance variables, including:

- Productivity vs Quality
- Productivity vs Accuracy
- Productivity vs Adherence
- Productivity vs Overall Score
- Overtime vs Performance
- Attendance vs Performance
- Cases Reviewed vs Productivity

### 7. Attendance Analysis

Analysed the relationship between:

- Present Days
- Absent Days
- Leave Days
- Productivity
- Overall Score
- Error Rate

### 8. Error Rate Analysis

Calculated error rates at team, employee and performance-status levels to identify patterns in review accuracy and operational performance.

### 9. Data Visualisation

Created charts using Matplotlib and Seaborn to communicate key findings.

### 10. Performance Dashboard

Developed a dashboard summarising the main KPIs and performance trends.
## Key Findings

The analysis identified several important patterns in the content review dataset.

### Overall Performance

- Average productivity was **100.79%**.
- Average quality was **92.41%**.
- Average accuracy was **93.93%**.
- Average adherence was **94.97%**.
- Average overall score was **96.35%**.
- A total of **544,281 cases** were reviewed against a total target of **540,000 cases**.
- The dataset contained **41,420 errors**, giving an overall error rate of **7.61%**.
- **83.83%** of records were classified as either Met Target or Exceeded Target.

### Team Performance

- Team D recorded the highest average productivity at **101.68%** and the highest average overall score at **96.58%**.
- Team C recorded the highest average quality at **93.08%** and the lowest team error rate at **6.96%**.
- Team E recorded the highest average accuracy at **94.14%** and the lowest total overtime at **1,170 hours**.
- Team A had the highest team error rate at **8.15%**.

### Weekly Trends

- Week 3 recorded the highest average overall score at **97.02%**.
- Week 1 recorded the lowest average overall score at **95.34%**.
- Week 3 also recorded the highest average productivity at **102.65%**.
- Week 9 recorded the lowest average quality at **91.64%**.

### Productivity and Quality

The correlation between productivity and quality was approximately **-0.02**, indicating a negligible linear relationship in this dataset.

This suggests that higher productivity was not strongly associated with higher or lower quality scores. Correlation measures association and does not establish causation.

### Overtime

Employee-level analysis found only weak correlations between overtime hours and performance metrics.

The correlation between total overtime and average overall score was approximately **0.07**, suggesting that overtime alone did not strongly explain differences in overall performance within this dataset.

### Error Rate

- The highest employee error rate identified was **11.46%**.
- The lowest employee error rate identified was **4.98%**.
- Employees with higher error rates generally showed lower quality scores in the analysed records.
- One example showed that high productivity can coexist with a higher error rate, demonstrating why multiple performance metrics should be considered together.

### Important Analytical Consideration

Some metrics show very strong correlations because performance measures may be mathematically related or derived from common underlying measures.

For example, productivity and overall score showed a very strong positive correlation. Therefore, these relationships should be interpreted carefully rather than treated as independent business drivers.
## Dashboard & Visualisations

A performance dashboard was created to provide a high-level view of the main operational KPIs.

![Wipro Content Review Performance Dashboard](./visualisations/wipro_content_review_dashboard%20%281%29.png)

The dashboard includes:

- Average Productivity
- Average Quality
- Average Accuracy
- Average Adherence
- Average Overall Score
- Overall Error Rate
- Team Overall Score
- Team Error Rate
- Weekly Overall Score
- Performance Status by Team

### Key Visualisations

The project also includes individual visualisations covering:

- Overall Score by Team
- Error Rate by Team
- Weekly Overall Score
- Productivity vs Quality
- Correlation Matrix
- Top 10 Employees by Error Rate
- Overtime vs Overall Score
- Absence vs Overall Score
- Cases Reviewed vs Productivity
- Error Rate by Performance Status
  
## Business Recommendations

Based on the analysis, the following areas could be considered for further operational review:

### 1. Investigate Error Rates

The overall error rate was **7.61%**, with differences observed across teams and employees.

Teams and employees with comparatively higher error rates could be reviewed to understand whether additional training, quality checks, or process improvements may be appropriate.

### 2. Balance Productivity and Quality

The analysis found a negligible correlation between productivity and quality (**-0.02**).

This indicates that productivity and quality should be monitored as separate performance dimensions rather than relying on productivity alone.

### 3. Review High-Productivity Records

Some employees demonstrated high productivity alongside relatively higher error rates.

This highlights the importance of combining productivity, quality, accuracy and error-rate measures when reviewing operational performance.

### 4. Monitor Weekly Trends

Weekly performance varied across the 12-week period.

Regular monitoring of weekly KPIs could help identify periods where productivity, quality or error rates change noticeably.

### 5. Review Overtime Patterns

Overtime showed only weak correlations with overall performance in this dataset.

Further analysis could examine overtime alongside workload, staffing levels, attendance and case complexity to understand the factors influencing additional working hours.

### 6. Use Multiple KPIs for Performance Monitoring

The analysis demonstrates that a single metric does not provide a complete view of operational performance.

A balanced performance dashboard combining productivity, quality, accuracy, adherence, error rate and workload can provide a broader view of operational trends.

## Skills Demonstrated

### Technical Skills

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Data Cleaning
- Data Transformation
- Exploratory Data Analysis (EDA)
- Data Aggregation
- GroupBy Analysis
- Correlation Analysis
- KPI Analysis
- Data Visualisation
- Dashboard Development

### Analytical Skills

- Business problem analysis
- Performance analysis
- Trend analysis
- Error-rate analysis
- Employee-level analysis
- Team-level analysis
- Operational KPI monitoring
- Identifying patterns and relationships
- Translating data into business insights
- Data-driven recommendations

### Portfolio & Reporting Skills

- GitHub project management
- Jupyter/Google Colab notebooks
- Data storytelling
- Visual communication of insights
- Documentation using Markdown

## How to Run the Project

The analysis was developed using Google Colab and Python.

### Open the Notebook

Open:

`Wipro_Content_Review_Analysis.ipynb`

The notebook contains the complete data cleaning, analysis, visualisations and dashboard development.

### Run the Notebook

The notebook can be opened using:

- Google Colab
- Jupyter Notebook
- JupyterLab

### Required Python Libraries

The analysis uses:

- Pandas
- NumPy
- Matplotlib
- Seaborn

### Dataset

The analysis uses the `content_review_new.csv` dataset.

The dataset should only be shared publicly if it is synthetic, anonymised, or otherwise approved for public use.
