# Banking-and-Marketing
Transform customer data with R
# 🏦 Bank Marketing Analysis

**Predicting Term Deposit Subscriptions through Data-Driven Customer Insights**

*by Candace Grant*

---

## 📊 Project Overview

This project analyzes a comprehensive marketing dataset from a Portuguese banking institution's direct marketing campaigns. Using advanced R analytics, we explore customer behavior patterns and develop predictive models to determine the likelihood of term deposit subscriptions.

### 🎯 **Objective**
Develop a robust predictive classification model that accurately determines whether a client will subscribe to a term deposit (binary outcome: 'yes' or 'no') based on customer demographics, financial history, and campaign interactions.

### 📈 **Business Impact**
Understanding customer subscription patterns enables banks to:
- Optimize marketing campaign targeting
- Improve resource allocation
- Increase conversion rates
- Enhance customer segmentation strategies

---

## 🗂️ Dataset Information

**Source:** [UCI Machine Learning Repository](https://doi.org/10.24432/C5K306)  
**Citation:** Moro, S., Rita, P., & Cortez, P. (2014). Bank Marketing Dataset.

### 📋 **Dataset Characteristics**
- **Rows:** 45,211 customer records
- **Features:** 17 variables (after preprocessing)
- **Target Variable:** Term deposit subscription (binary: yes/no)
- **Campaign Type:** Phone-based direct marketing
- **Challenge:** Multiple contacts often required for successful conversions

---

## 🛠️ **Technical Stack**

```r
# Core Libraries Used
library(tidyverse)    # Data manipulation and visualization
library(readxl)       # Excel file reading
library(dplyr)        # Data transformation
library(ggplot2)      # Advanced plotting
library(knitr)        # Report generation
```

---

## 📁 **Project Structure**

```
bank-marketing-analysis/
├── 📄 Data606Homework1.Rmd     # Main analysis notebook
├── 📊 data/
│   └── bank-full.xls           # Raw dataset
├── 📈 plots/                   # Generated visualizations
├── 📋 README.md                # Project documentation
└── 🎯 results/                 # Model outputs and insights
```

---

## 🔍 **Analysis Workflow**

### 🧹 **Data Preprocessing**
- **Quality Assessment:** Identified 'unknown' values as missing data (not recognized by R as NA)
- **Feature Engineering:** Removed columns with >70% missing data
- **Column Renaming:** Enhanced interpretability with descriptive variable names
- **Data Cleaning:** Streamlined dataset for optimal modeling performance

### 📊 **Exploratory Data Analysis**
- **Customer Demographics:** Age, job type, education level, marital status
- **Financial Profile:** Account balance, existing loans, credit history
- **Campaign Metrics:** Contact frequency, timing, previous campaign outcomes
- **Relationship Analysis:** Job type vs. mortgage/loan patterns

### 🎨 **Key Visualizations**
- Term deposit subscription rates by job category
- Mortgage and personal loan distributions across professions
- Customer segmentation patterns
- Campaign effectiveness metrics

---

## 💡 **Key Insights**

### 🔍 **Data Quality Discoveries**
- Missing values coded as 'unknown' rather than standard NA values
- Strategic removal of low-information columns improved data quality
- Preprocessing enhanced model readiness and interpretability

### 📈 **Customer Behavior Patterns**
- Clear relationships between job type and financial product preferences
- Varying subscription rates across different customer segments
- Campaign contact patterns influence conversion success

---

## 🚀 **Getting Started**

### **Prerequisites**
```r
# Install required packages
install.packages(c("tidyverse", "readxl", "dplyr", "ggplot2", "knitr"))
```

### **Running the Analysis**
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/bank-marketing-analysis.git
   ```

2. **Open R/RStudio**
   ```r
   # Set working directory
   setwd("path/to/bank-marketing-analysis")
   ```

3. **Run the analysis**
   ```r
   # Open and knit the R Markdown file
   rmarkdown::render("Data606Homework1.Rmd")
   ```

---

## 📋 **Variable Dictionary**

| Variable | Description | Type |
|----------|-------------|------|
| `job` | Client occupation | Categorical |
| `marital_status` | Marital status | Categorical |
| `education_level` | Education level | Categorical |
| `avg_yearly_balance` | Average yearly balance | Numerical |
| `mortgage` | Housing loan status | Binary |
| `personal_loan` | Personal loan status | Binary |
| `recency` | Days since last contact | Numerical |
| `prior_contacts` | Previous campaign contacts | Numerical |
| `subscribed` | **Target:** Term deposit subscription | Binary |

---

## 🎯 **Results & Impact**

### ✅ **Completed Milestones**
- [x] Comprehensive data quality assessment
- [x] Strategic feature selection and engineering
- [x] Exploratory data analysis with visualizations
- [x] Customer behavior pattern identification

### 🔮 **Future Enhancements**
- [ ] Advanced predictive modeling (Random Forest, XGBoost)
- [ ] Cross-validation and model performance metrics
- [ ] Customer lifetime value analysis
- [ ] Campaign optimization recommendations

---

## 📞 **Contact**

**Candace Grant**  
📧 [your.email@example.com](mailto:your.email@example.com)  
💼 [LinkedIn Profile](https://linkedin.com/in/yourprofile)  
🐙 [GitHub Portfolio](https://github.com/yourusername)

---

## 📜 **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 **Acknowledgments**

- **UCI Machine Learning Repository** for providing the comprehensive dataset
- **R Community** for excellent data science packages and documentation
- **Portuguese Banking Institution** for contributing valuable real-world data

---

<div align="center">

**⭐ If you found this analysis helpful, please consider giving it a star! ⭐**

*Built with ❤️ and R*

</div>
