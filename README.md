# Student Survey Retail Store Analysis in Power BI

## Project Overview
Analyze student spending across various retail stores in the U.S. with a focus on purchases like video games, indoor games, toys, books, and gadgets. Key data points include store location and setting (urban, suburban, rural), used to create visualizations and reports in Power BI.

## Dataset
- **Student Survey**


---

## Power BI Visualizations and Tasks

### 1. Tabular Visualization
- **Objective**: Format TAP based on 'Store location' and 'Store setting':
  - 0 < TAP < 35,000: Red  
  - 35,000 <= TAP < 60,000: Yellow  
  - TAP >= 60,000: Blue  
![Tabular Visualization](https://github.com/Aarthi-Mahalakshmi/StudentSurveyReport_bi/blob/main/Tabular%20Visualization.png?raw=true)

**Achieved**: A color-coded table helps identify store performance based on purchase totals.

### 2. Matrix Visualization
- **Objective**: Show outdoor sports spending across ages and store settings, with color formatting.
![Matrix Visualization](https://github.com/Aarthi-Mahalakshmi/StudentSurveyReport_bi/blob/main/Matrix%20Visualization.png?raw=true)

**Achieved**: Clear visualization of spending patterns across age groups and store settings.

### 3. Funnel Chart
- **Objective**: Display TAP by 'Store setting' with data labels showing percentage relative to the first value.
![Funnel Chart](https://github.com/Aarthi-Mahalakshmi/StudentSurveyReport_bi/blob/main/Funnel%20char.png?raw=true)

**Achieved**: Funnel chart shows the purchase breakdown by store setting.

### 4. Pie Chart
- **Objective**: Display TAP by 'Store location' for **Suburban** 'Store setting' only.
![Pie Chart](https://github.com/Aarthi-Mahalakshmi/StudentSurveyReport_bi/blob/main/Pie%20chart.png?raw=true)

**Achieved**: Pie chart highlights suburban store location purchases.

### 5. Scatter and Sand Dance Plots
- **a) Scatter Plot**: Video games purchase vs. outdoor sports spending across ages.
![Scatter Plot](https://github.com/Aarthi-Mahalakshmi/StudentSurveyReport_bi/blob/main/Scatter%20plot.png?raw=true)

- **b) Sand Dance Plot**: Indoor sports vs. video games spending across ages.
![Sand Dance Plot](https://github.com/Aarthi-Mahalakshmi/StudentSurveyReport_bi/blob/main/Sand%20dance%20plot.png?raw=true)

**Achieved**: Insights into spending behavior through interactive visualizations.

### 6. Data Access Restriction
- **Objective**: Restrict data access based on user mapping (e.g., Mani only views rural data).

**Achieved**: Row-level security ensures user-specific data visibility.

### 7. Power BI Cloud and Dashboard
- **Objective**: Publish the report to Power BI cloud and design a master dashboard with scheduled refresh every 4 hours, six times daily.

**Achieved**: A live dashboard with automated data refresh.

### 8. Q&A Feature
- **a)** Average age of students.
- **b)** Donut chart for TAP by 'Store location'.
![Q&A Feature](https://github.com/Aarthi-Mahalakshmi/StudentSurveyReport_bi/blob/main/Screenshot%20Q&A%20feature.png?raw=true)

**Achieved**: Real-time insights using Power BI Q&A.

---

## Conclusion
This Power BI project automates student spending analysis in retail stores through various visualizations. By utilizing user-based data restriction and dynamic dashboards, decision-makers can easily interpret trends and store performance.

## Tools Used
- Power BI Desktop
- Power BI Service
- Power BI Q&A
- Row-level security (RLS)
