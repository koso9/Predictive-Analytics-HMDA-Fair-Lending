# **Analyzing Racial Disparities in Mortgage Approvals Using HMDA Data**

## **📊 Overview**
This project uses the Home Mortgage Disclosure Act (HMDA) dataset to explore whether racial and ethnic factors influence mortgage approval outcomes. By combining **regulatory data** with Python analytics, the project aims to identify potential disparities in lending practices.

---

## **💡 Why It Matters**
Understanding the role of race in mortgage approvals is critical for:
- **Fair Lending Practices**: Ensuring equal opportunities for all applicants.
- **Regulatory Compliance**: Assisting lenders in meeting federal anti-discrimination standards.
- **Data-Driven Insights**: Using statistical models to uncover systemic issues.

This project highlights expertise in **financial data analysis**, **regulatory datasets**, and **predictive modeling**.

---

## **✨ Key Features**
### **1. HMDA Data Integration**
- Fetches live HMDA data via the CFPB API for specified institutions and years.
- Loads data into a structured format for analysis.

### **2. Exploratory Data Analysis (EDA)**
- Examines race and ethnicity distributions for applicants and co-applicants.
- Analyzes loan approval rates across different racial groups.

### **3. Predictive Modeling**
- Builds a logistic regression model to assess:
  - Likelihood of approval based on race, income, and loan amount.
  - Statistical significance of race and ethnicity in decision-making.

### **4. Visualizations**
- Generates charts showing:
  - Approval/denial rates by race and ethnicity.
  - Income distribution across racial groups.
  - Correlations between key variables.

---

## **🛠️ Technology Stack**
- **Python**: Core programming language.
- **Libraries**:
  - `requests`: For API integration.
  - `pandas`: Data manipulation.
  - `statsmodels` or `scikit-learn`: For logistic regression.
  - `matplotlib` and `seaborn`: For visualizations.
- **API**: CFPB HMDA Data Browser for fetching live data.

---

## **🚀 Installation**
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/hmda-race-analysis.git
   cd hmda-race-analysis
