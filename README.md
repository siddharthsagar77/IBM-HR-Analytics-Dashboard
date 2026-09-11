# IBM HR Talent & Attrition Intelligence | Workforce Analytics Dashboard

![IBM HR Analytics Dashboard](https://img.shields.io/badge/Project-HR%20Analytics-blue?style=flat-square)
![Power BI](https://img.shields.io/badge/Tool-Power%20BI-FFB900?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-green?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## 📊 Project Overview

This is a comprehensive **HR Talent & Attrition Intelligence Dashboard** built to analyze workforce dynamics, employee retention patterns, and organizational health metrics. The dashboard provides actionable insights into employee attrition rates, departmental performance, and key factors influencing workforce retention.

### Key Business Impact
- **Identifies critical attrition patterns** across departments and roles
- **Predicts high-risk employee segments** for proactive retention strategies
- **Tracks KPIs** essential for HR decision-making and workforce planning
- **Enables data-driven HR policies** to reduce talent turnover

---

## 🎯 Key Metrics & Insights

| Metric | Value | Insight |
|--------|-------|---------|
| **Total Employees** | 1,470 | Overall workforce size |
| **Total Attrition** | 237 | Employees who left |
| **Active Employees** | 1,233 | Current workforce |
| **Attrition Rate** | 16.12% | Industry benchmark: 13-15% |
| **Avg Monthly Income** | $6,503 | Compensation analysis |

### Critical Findings
- **Highest Attrition Department**: Sales (20.0%) - requires immediate attention
- **Most Vulnerable Role**: Sales Representative (39.8% attrition rate)
- **Work-Life Balance Impact**: 31.3% attrition among employees with poor work-life balance
- **Overtime Correlation**: 53.6% attrition rate among overtime workers

---

## 📁 Project Structure

```
IBM-HR-Analytics-Dashboard/
├── README.md                          # Project documentation
├── LICENSE                            # MIT License
├── HR_Dashboard.pbix                  # Power BI dashboard file
├── IBM_HR_Analytics_Report.pdf        # Detailed analysis report
├── data/
│   ├── raw_data/                      # Original dataset
│   └── processed_data/                # Cleaned and transformed data
├── dashboards/
│   ├── screenshots/                   # Dashboard visuals
│   └── dashboard_guide.md             # Navigation guide
├── analysis/
│   ├── attrition_analysis.md          # Detailed findings
│   └── recommendations.md             # Actionable insights
└── docs/
    ├── data_dictionary.md             # Field descriptions
    └── methodology.md                 # Analysis approach
```

---

## 📊 Dashboard Features

### 1. **Executive KPI Cards**
- Total Employees, Active Employees
- Attrition Count & Rate
- Average Monthly Income
- Real-time metric tracking

### 2. **Attrition Analysis**
- **By Department**: Sales (20.0%), HR (19.0%), R&D (13.8%)
- **By Job Role**: Sales Rep (39.8%), Lab Technician (21.9%), HR Specialist (23.1%)
- **By Overtime Status**: Yes (53.6%) vs No (46.4%)
- **By Work-Life Balance**: Poor balance shows highest attrition

### 3. **Demographic Insights**
- **Gender Distribution**: Male vs Female retention patterns
- **Marital Status Impact**: Single (26.9%), Married (11.4%), Divorced (1.4%)
- **Age & Tenure Analysis**: Career stage correlation with attrition

### 4. **Interactive Filters & Slicers**
- Department filter (All, Sales, HR, R&D, etc.)
- Job Role filter
- Gender segmentation
- Dynamic cross-filtering

---

## 🔍 Key Analysis Dimensions

### Department-Level Analysis
- Sales department shows concerning 20% attrition
- R&D maintains lower attrition at 13.8%
- HR department needs retention focus at 19%

### Role-Level Analysis
- **High Risk**: Sales Representative (39.8%)
- **Medium Risk**: Lab Technician (21.9%), HR Specialist (23.1%)
- **Lower Risk**: Manufacturing Director (6.9%), Research Director (2.5%)

### Lifestyle Factors
- **Overtime Impact**: Employees working overtime have 53.6% attrition
- **Work-Life Balance**: Poor balance correlates with 31.3% attrition
- **Income Level**: Lower-income brackets show higher turnover

---

## 💡 Recommendations

### Immediate Actions (0-3 months)
1. **Sales Department Intervention**
   - Review compensation structure for Sales Representatives
   - Implement mentorship programs
   - Conduct stay interviews with high performers

2. **Overtime Reduction Program**
   - Cap overtime hours at 20% weekly
   - Hire additional staff in high-turnover roles
   - Implement workload balancing

3. **Work-Life Balance Initiative**
   - Flexible working arrangements
   - Remote work policies
   - Wellness programs

### Medium-term Strategies (3-6 months)
1. **Career Development**
   - Clear promotion pathways for Sales roles
   - Skill development programs
   - Cross-departmental rotation opportunities

2. **Compensation Review**
   - Benchmark salaries against industry standards
   - Introduce performance-based incentives
   - Review benefits package

### Long-term Goals (6-12 months)
1. **Cultural Enhancement**
   - Employee engagement surveys
   - Leadership training programs
   - Company culture initiatives

---

## 🛠️ Technology Stack

| Component | Technology | Purpose |
|-----------|-----------|---------|
| **Dashboard Tool** | Power BI | Interactive visualization & reporting |
| **Data Source** | IBM HR Dataset | 1,470 employee records |
| **File Format** | .pbix | Power BI project file |
| **Report Export** | PDF | Stakeholder documentation |

---

## 📈 Data Specifications

- **Dataset Size**: 1,470 employee records
- **Dimensions**: 35+ HR metrics and attributes
- **Time Period**: Historical workforce data
- **Refresh Rate**: Configurable (typically monthly)
- **Data Quality**: Cleaned and validated

### Key Data Fields
- Employee Demographics (Age, Gender, Marital Status)
- Employment Details (Department, Job Role, Tenure)
- Compensation (Monthly/Yearly Income)
- Work Factors (Overtime, Work-Life Balance)
- Performance Metrics (Attrition Status, Satisfaction)

---

## 🚀 How to Use

### Prerequisites
- **Power BI Desktop** (Free or Pro version)
- **Power BI Service** account (for sharing)

### Opening the Dashboard
1. Download `HR_Dashboard.pbix`
2. Open with Power BI Desktop
3. Refresh data source (if needed)
4. Explore interactive visualizations
5. Use filters for specific department/role analysis

### Interactive Features
- Click department/role bars to filter data
- Use dropdown slicers for quick views
- Hover over charts for detailed tooltips
- Export reports as PDF/Excel

---

## 📊 Use Cases

### HR Manager
- Monitor departmental attrition trends
- Identify at-risk employee segments
- Track retention program effectiveness

### Executive Leadership
- Understand organizational health
- Budget workforce planning
- Make strategic hiring decisions

### Operations Manager
- Optimize team composition
- Manage overtime costs
- Improve work-life balance

### L&D Professional
- Design targeted training programs
- Develop career paths
- Create retention strategies

---

## 🔐 Data Privacy & Security

- All employee data is anonymized where applicable
- Dashboard complies with data protection standards
- Sensitive metrics restricted to authorized users
- Regular data backups maintained

---

## 📋 Analysis Methodology

### Data Processing Steps
1. **Data Cleaning**: Removed duplicates, handled missing values
2. **Data Transformation**: Created calculated fields and measures
3. **Aggregation**: Department-level and role-level rollups
4. **Validation**: Cross-checked against source systems

### Key Metrics Calculated
- Attrition Rate = (Employees Left / Total Employees) × 100
- By Department & Role = Segmented attrition calculations
- By Demographics = Gender, Marital Status analysis
- By Lifestyle = Overtime, Work-Life Balance correlation

---

## 📞 Contact & Support

For questions about this dashboard or HR analytics:
- Review the data dictionary in `/docs/data_dictionary.md`
- Check methodology in `/docs/methodology.md`
- Refer to detailed analysis in `/analysis/`

---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 🙌 Acknowledgments

- **Dataset Source**: IBM HR Analytics Dataset
- **Tool**: Microsoft Power BI
- **Purpose**: Workforce analytics & retention strategy

---

## 📚 Additional Resources

- [Power BI Best Practices](https://docs.microsoft.com/en-us/power-bi/guidance/)
- [HR Analytics Guide](https://www.shrm.org/)
- [Data Visualization Standards](https://www.tableau.com/about/blog/2016/7/tableau-public-makeover-monday)

---

**Last Updated**: September 2026 | **Dashboard Version**: 1.0

