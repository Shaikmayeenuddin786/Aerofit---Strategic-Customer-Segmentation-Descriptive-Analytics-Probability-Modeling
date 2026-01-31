# Aerofit---Strategic-Customer-Segmentation-Descriptive-Analytics-Probability-Modeling
# **Aerofit - Customer Segmentation,Product Strategy Analysis (Descriptive Analytics + Probability Modeling)**

*This project demonstrates the application of descriptive statistics and probability theory to solve real-world business problems in the retail/fitness industry.*

## **Project Overview**
A comprehensive descriptive analytics project for Aerofit, a leading fitness equipment manufacturer, to identify customer characteristics for each treadmill model and create targeted marketing strategies. This analysis helped Aerofit understand their customer base across three product tiers and develop data-driven recommendations for sales optimization.

## **Business Problem**
Aerofit needed to identify the characteristics of the target audience for each type of treadmill to provide better recommendations to new customers. The company wanted to understand whether there were significant differences in customer demographics across their product lineup (KP281, KP481, KP781) to optimize marketing efforts and improve sales effectiveness.

## **Objectives**
- Identify distinct customer segments for each treadmill model (KP281, KP481, KP781)
- Develop customer profiles using descriptive statistics and probability analysis
- Create actionable insights for targeted marketing and sales recommendations
- Establish a data-driven framework for product positioning and pricing strategy

## **Why This Project**
This project demonstrates the ability to translate raw customer data into strategic business insights. Focuses on foundational descriptive analytics - a critical skill for understanding customer behavior and informing business strategy.


## **Technical Stack**
- **Python 3.8+**: Primary analysis language
- **Pandas & NumPy**: Data manipulation and numerical computations
- **Matplotlib & Seaborn**: Data visualization and chart generation
- **Jupyter Notebook**: Interactive analysis environment
- **SciPy**: Statistical analysis and probability calculations



# **Project Features**

### **Data Analysis & Exploration**
- **Dataset Analysis**: 180 customer records with 8 attributes (Product, Age, Gender, Education, Marital Status, Usage, Fitness, Income, Miles)
- **Data Quality Checks**: Missing value analysis, outlier detection using IQR method, data type validation
- **Statistical Summaries**: Comprehensive descriptive statistics for both categorical and numerical variables

### **Visual Analytics & Customer Profiling**
- **Univariate Analysis**: Distribution plots for numerical variables (Age, Income, Fitness) and categorical variables (Product, Gender, Marital Status)
- **Bivariate Analysis**: Product vs. demographic comparisons using count plots and box plots
- **Customer Segmentation**: Created detailed profiles for each product tier showing clear demographic patterns

### **Probability & Statistical Analysis**
- **Marginal Probabilities**: Calculated overall product purchase distributions (KP281: 44%, KP481: 33%, KP781: 22%)
- **Conditional Probabilities**: Key insights including 68% probability of fitness level 4-5 customers buying KP781
- **Contingency Tables**: Two-way tables showing relationships between product choice and customer attributes

### **Business Insights Generation**
- **Customer Profiles**: 
  - KP281: Entry-level users, younger demographic, lower income, casual fitness enthusiasts
  - KP481: Intermediate users, balanced gender distribution, moderate income, regular exercisers
  - KP781: Advanced users, predominantly male, high income, serious fitness enthusiasts
- **Strategic Recommendations**: Targeted marketing strategies, upselling frameworks, product placement guidelines

## **Repository Structure**
```
Aerofit-Customer-Analysis/
│
├── data/
│   └── dataset_aerofit.csv          # Original dataset (180 records)
│
├── notebooks/
│   └── Aerofit-Descriptive Statistics&Probability.ipynb   # Complete Jupyter notebook analysis
│
├── outputs/
│   ├── visualizations/               # All generated plots and charts
│   ├── customer_profiles/            # Detailed customer segment profiles
│   └── probability_tables/           # Contingency tables and probability calculations
│
├── docs/
│   └── Aerofit_Final_Report.pdf      # Complete project documentation
│
├── README.md                         # Project overview (this file)
```


## **Key Findings**
1. **Clear Income Segregation**: KP781 buyers earn 65% more than KP281 buyers
2. **Gender-Based Patterns**: 80% of KP781 buyers are male vs. 57% female for KP281
3. **Fitness Level Correlation**: Higher fitness levels strongly predict premium product purchases
4. **Usage Patterns**: KP781 users plan 50% more weekly usage than KP281 users

## **Business Impact**
The analysis provided Aerofit with:
- **Targeted Marketing Strategies**: Different approaches for each customer segment
- **Product Positioning**: Data-backed justification for tiered pricing
- **Sales Enablement**: Probability-based recommendation framework for sales teams
- **Customer Journey Mapping**: Clear path from entry-level to premium products

## **How to Run This Project**
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Open `notebooks/Aerofit_Analysis.ipynb` in Jupyter
4. Run cells sequentially to reproduce the analysis

## **Lessons Learned**
- Foundational descriptive analytics provides critical business insights before predictive modeling
- Customer segmentation reveals hidden patterns in purchasing behavior
- Probability analysis offers quantifiable guidance for business decisions
- Clear visualizations communicate complex findings to non-technical stakeholders

---
