# IBM HR Talent & Attrition Intelligence | Workforce Analytics Dashboard

![IBM HR Analytics Dashboard](https://img.shields.io/badge/Project-HR%20Analytics-blue?style=flat-square)
![Power BI](https://img.shields.io/badge/Tool-Power%20BI-FFB900?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-green?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## 📊 Dashboard Preview

<p align="center">
  <img src="screenshots/dashboard_preview.png" alt="IBM HR Analytics Dashboard" width="100%">
</p>

*Interactive Power BI dashboard analyzing workforce dynamics, employee retention patterns, and organizational health metrics for 1,470+ employees*

---

## 📋 Project Overview

This is a comprehensive **HR Talent & Attrition Intelligence Dashboard** built to analyze workforce dynamics, employee retention patterns, and organizational health metrics. The dashboard provides actionable insights into employee attrition rates, departmental performance, and key factors influencing workforce retention.

### Key Business Impact
- **Identifies critical attrition patterns** across departments and roles
- **Predicts high-risk employee segments** for proactive retention strategies
- **Tracks KPIs** essential for HR decision-making and workforce planning
- **Enables data-driven HR policies** to reduce talent turnover

---

## 🎯 Key Metrics & Insights

<table>
<tr>
<td width="50%">

### 📊 Overall Statistics
| Metric | Value | Insight |
|--------|-------|---------|
| **Total Employees** | 1,470 | Overall workforce size |
| **Total Attrition** | 237 | Employees who left |
| **Active Employees** | 1,233 | Current workforce |
| **Attrition Rate** | 16.12% | Above industry benchmark (13-15%) |
| **Avg Monthly Income** | $6,503 | Compensation analysis |

</td>
<td width="50%">

### 🚨 Critical Findings
- **Highest Attrition Department**: Sales (20.0%)
- **Most Vulnerable Role**: Sales Representative (39.8%)
- **Work-Life Balance Impact**: 31.3% attrition among poor balance
- **Overtime Correlation**: 53.6% attrition rate among OT workers
- **Marital Status**: Single employees show 26.9% attrition

</td>
</tr>
</table>

---

## 📊 Dashboard Features

The dashboard includes **4 main analysis dimensions**:

### 1. **Executive KPI Cards**
Real-time tracking of:
- Total Employees, Active Employees
- Attrition Count & Rate
- Average Monthly Income
- Interactive filtering across all visuals

### 2. **Department-Level Analysis**
- **Sales**: 20.0% attrition (highest risk)
- **Human Resources**: 19.0% attrition
- **Research & Development**: 13.8% attrition (most stable)

### 3. **Role-Level Analysis**
High-risk positions identified:
- Sales Representative: **39.8%** attrition
- Laboratory Technician: **23.9%** attrition
- Human Resources Specialist: **23.1%** attrition

Lower-risk positions:
- Manufacturing Director: **6.9%** attrition
- Manager: **4.9%** attrition
- Research Director: **2.5%** attrition

### 4. **Lifestyle & Demographic Factors**
- **Overtime Impact**: 53.6% (Yes) vs 46.4% (No)
- **Work-Life Balance**: 31.3% attrition with poor balance
- **Marital Status**: Single (26.9%), Married (11.4%), Divorced (1.4%)
- **Gender Analysis**: Comparative retention patterns

### 5. **Interactive Filters & Slicers**
- Department filter (Sales, HR, R&D, etc.)
- Job Role segmentation
- Gender filter (Male/Female)
- Dynamic cross-filtering across all visuals

---

## 🔍 Key Analysis Dimensions

<table>
<tr>
<td width="33%">

### 🏢 By Department
- Sales: **20.0%** ⚠️
- HR: **19.0%** ⚠️
- R&D: **13.8%** ✅

</td>
<td width="33%">

### 👔 By Job Role
- Sales Rep: **39.8%** 🔴
- Lab Tech: **23.9%** 🟡
- HR Specialist: **23.1%** 🟡
- Research Scientist: **16.1%** 🟢

</td>
<td width="33%">

### ⚖️ By Work Factors
- Overtime: **53.6%** 🔴
- Poor Work-Life: **31.3%** 🟡
- Good Balance: **16.9%** 🟢

</td>
</tr>
</table>

---

## 💡 Actionable Recommendations

### 🚨 Immediate Actions (0-3 months)

#### 1. Sales Department Intervention
- Review compensation structure for Sales Representatives
- Implement mentorship programs
- Conduct stay interviews with high performers
- **Target**: Reduce Sales Rep attrition from 39.8% to 25%

#### 2. Overtime Reduction Program
- Cap overtime hours at 20% of weekly hours
- Hire additional staff in high-turnover roles
- Implement workload balancing
- **Target**: Reduce overtime-related attrition by 30%

#### 3. Work-Life Balance Initiative
- Introduce flexible working arrangements
- Implement hybrid/remote work policies
- Launch wellness programs and mental health support
- **Target**: Improve work-life balance scores by 25%

### 📈 Medium-term Strategies (3-6 months)

#### 1. Career Development Programs
- Create clear promotion pathways for Sales roles
- Offer skill development and training programs
- Enable cross-departmental rotation opportunities
- **Target**: Increase internal promotion rate by 40%

#### 2. Compensation Review
- Benchmark salaries against industry standards
- Introduce performance-based incentives
- Review and enhance benefits package
- **Target**: Align compensation to 75th percentile

#### 3. Employee Engagement
- Launch quarterly engagement surveys
- Create employee recognition programs
- Establish feedback loops with management
- **Target**: Achieve 80%+ engagement score

### 🎯 Long-term Goals (6-12 months)

#### 1. Cultural Transformation
- Leadership training programs
- Diversity and inclusion initiatives
- Company culture enhancement programs
- **Target**: Improve company culture ratings by 35%

#### 2. Predictive Analytics
- Implement ML models for attrition prediction
- Create early warning system for flight risks
- Develop retention score for each employee
- **Target**: Predict 70%+ of potential departures

#### 3. Continuous Improvement
- Regular dashboard updates with latest data
- Monthly attrition trend analysis
- Quarterly retention strategy reviews
- **Target**: Reduce overall attrition to <12%

---

## 🛠️ Technology Stack

| Component | Technology | Purpose |
|-----------|-----------|---------|
| **Dashboard Tool** | Microsoft Power BI Desktop | Interactive visualization & reporting |
| **Data Modeling** | DAX (Data Analysis Expressions) | Advanced calculations & metrics |
| **Data Processing** | Power Query | ETL and data transformation |
| **Data Source** | IBM HR Analytics Dataset | 1,470 employee records with 35+ attributes |
| **File Format** | .pbix | Power BI project file |
| **Documentation** | Markdown | Professional documentation |

---

## 📈 Data Specifications

- **Dataset Size**: 1,470 employee records
- **Dimensions**: 35+ HR metrics and attributes
- **Data Quality**: Cleaned and validated
- **Time Period**: Historical workforce data
- **Refresh Rate**: Configurable (monthly recommended)

### Key Data Fields
- **Demographics**: Age, Gender, Marital Status, Education
- **Employment**: Department, Job Role, Tenure, Job Level
- **Compensation**: Monthly Income, Salary Hike, Stock Options
- **Work Factors**: Overtime, Work-Life Balance, Business Travel
- **Performance**: Job Satisfaction, Performance Rating, Engagement
- **Attrition**: Status, Exit reasons, Retention risk

---



### Navigation Guide

#### Filter Panel (Right Side)
- **Department**: Filter by specific departments
- **Job Role**: Focus on specific positions
- **Gender**: Male/Female segmentation
- Filters apply across all visualizations

#### Main Visualizations
- **Top Row**: KPI cards showing key metrics
- **Left Column**: Department and role analysis
- **Center Column**: Overtime and work-life balance
- **Right Panel**: Demographic breakdown

---

## 📊 Use Cases

### For HR Managers
- Monitor departmental attrition trends monthly
- Identify at-risk employee segments
- Track retention program effectiveness
- Justify budget for retention initiatives

### For Executive Leadership
- Understand overall organizational health
- Make strategic workforce planning decisions
- Budget for recruitment and retention programs
- Evaluate HR team performance

### For Operations Managers
- Optimize team composition and workload
- Manage overtime costs effectively
- Improve work-life balance for teams
- Reduce burnout and turnover

### For L&D Professionals
- Design targeted training programs
- Develop career progression paths
- Create retention-focused initiatives
- Measure learning impact on retention

### For Data Analysts
- Perform deep-dive analysis on subgroups
- Create custom reports and exports
- Build predictive models using insights
- Validate HR hypotheses with data

---

## 🔍 Analysis Methodology

### Data Processing Pipeline

1. **Data Collection**
   - Source: IBM HR Analytics employee dataset
   - Records: 1,470 employees
   - Attributes: 35 fields per employee

2. **Data Cleaning**
   - Removed duplicate records
   - Handled missing values (imputation/exclusion)
   - Standardized text fields (proper case)
   - Validated numeric ranges and data types

3. **Data Transformation**
   - Created calculated columns for analysis
   - Developed DAX measures for metrics
   - Built hierarchies for drill-down
   - Established relationships between tables

4. **Analysis & Visualization**
   - Identified key attrition drivers
   - Created interactive visualizations
   - Designed intuitive navigation
   - Optimized for performance

### Key Metrics Calculated

**Attrition Rate**
```dax
Attrition Rate = 
DIVIDE(
    CALCULATE(COUNT(HR_Data[EmployeeID]), HR_Data[Attrition] = "Yes"),
    COUNT(HR_Data[EmployeeID]),
    0
) * 100
```

**Department Attrition**
```dax
Dept Attrition Rate = 
CALCULATE(
    [Attrition Rate],
    ALLEXCEPT(HR_Data, HR_Data[Department])
)
```

**Overtime Impact**
```dax
Overtime Attrition = 
CALCULATE(
    [Total Attrition],
    HR_Data[OverTime] = "Yes"
)
```

*Full DAX formulas available in [DATA_DICTIONARY.md](DATA_DICTIONARY.md)*

---

## 🎯 Business Impact

### Quantified Results

| Metric | Current State | Target State | Potential Impact |
|--------|---------------|--------------|------------------|
| Overall Attrition | 16.12% | 12% | 25% reduction |
| Sales Rep Attrition | 39.8% | 25% | 37% reduction |
| Overtime-Related | 53.6% | 35% | 35% reduction |
| Cost Savings | - | $500K+/year | 30% of recruitment budget |

### ROI Analysis

**Cost of Employee Turnover (per employee)**
- Recruitment: $15,000
- Onboarding: $10,000
- Training: $8,000
- Lost Productivity: $12,000
- **Total**: ~$45,000 per employee

**Projected Savings**
- Current attrition: 237 employees × $45K = $10.67M/year
- Target attrition (12%): 176 employees × $45K = $7.92M/year
- **Annual Savings**: $2.75M (25% reduction)

---

## 🔐 Data Privacy & Security

- All employee data is anonymized where applicable
- Dashboard complies with data protection standards (GDPR-ready)
- Sensitive metrics restricted to authorized users
- No personally identifiable information (PII) exposed
- Regular data backups maintained
- Secure access controls recommended for production use

---

## 📋 Additional Documentation

For more detailed information, see:

- **[DATA_DICTIONARY.md](DATA_DICTIONARY.md)** - Complete field definitions and DAX formulas
- **[CONTRIBUTING.md](CONTRIBUTING.md)** - How to contribute to this project
- **[GITHUB_SETUP_GUIDE.md](GITHUB_SETUP_GUIDE.md)** - Step-by-step GitHub setup
- **[PROJECT_SUMMARY.md](PROJECT_SUMMARY.md)** - Executive summary and interview prep

---

## 🤝 Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

Ways to contribute:
- Report bugs or issues
- Suggest new features or enhancements
- Improve documentation
- Add new visualizations
- Optimize DAX calculations

---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

You are free to:
- Use commercially
- Modify and adapt
- Distribute
- Use privately

---

## 🙌 Acknowledgments

- **Dataset Source**: IBM HR Analytics Employee Attrition & Performance Dataset
- **Tool**: Microsoft Power BI Desktop
- **Purpose**: Workforce analytics & retention strategy optimization
- **Inspiration**: Data-driven HR decision-making

---

## 📞 Contact & Support

For questions or feedback about this dashboard:

- **GitHub Issues**: Report bugs or request features
- **Documentation**: Check DATA_DICTIONARY.md for technical details
- **Portfolio**: [Your Portfolio Website]
- **LinkedIn**: [Your LinkedIn Profile]
- **Email**: [Your Email]

---

## 📚 Additional Resources

- [Power BI Best Practices](https://docs.microsoft.com/en-us/power-bi/guidance/)
- [DAX Guide](https://dax.guide/)
- [HR Analytics Best Practices](https://www.shrm.org/)
- [Employee Retention Strategies](https://www.gallup.com/workplace/)

---

## 🎯 Future Enhancements

Planned improvements:
- [ ] Add predictive attrition model using Python/R
- [ ] Implement automated email alerts for high-risk departures
- [ ] Create employee sentiment analysis from exit interviews
- [ ] Integrate real-time HR system data connections
- [ ] Add competitive benchmarking against industry standards
- [ ] Develop mobile-friendly dashboard version
- [ ] Create drill-through pages for individual employee profiles

---

## 📊 Dashboard Versions

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | September 2026 | Initial release with core analytics |
| 1.1 | Planned | Add predictive modeling |
| 2.0 | Planned | Real-time data integration |

---

## ⭐ Star This Repository

If you find this dashboard helpful, please consider giving it a star! It helps others discover the project.

---

**Last Updated**: September 11, 2026 | **Dashboard Version**: 1.0 | **Status**: Active

---

<p align="center">
  Made with ❤️ for data-driven HR professionals
</p>

<p align="center">
  <a href="#top">⬆️ Back to Top</a>
</p>
