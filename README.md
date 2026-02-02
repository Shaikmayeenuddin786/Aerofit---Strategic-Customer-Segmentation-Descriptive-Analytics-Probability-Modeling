# **Aerofit - Customer Segmentation,Product Strategy Analysis (Descriptive Analytics + Probability Modeling)**


## **Why This Project**
This project demonstrates the ability to translate raw customer data into strategic business insights. Focuses on foundational descriptive analytics - a critical skill to solve real-world business problems in the retail/fitness industry.

## **Business Problem**
*Strategic Market Segmentation & Product Positioning.*
A comprehensive descriptive analytics project for Aerofit, a leading fitness equipment manufacturer.
Aerofit Treadmill Customer Analysis - To identify the characteristics of the target audience for each type of treadmill 
offered by the company, to provide a better recommendation of the treadmills to the new customers. The company also wanted to understand whether there were significant differences in customer demographics across their three flagship treadmill models (KP281, KP481, KP781) to and develop data-driven recommendations to optimize marketing efforts and improve sales effectiveness.

### **Pain Points**
- Customer-Product Mismatch: Lack of a structured framework to match new customers to the right treadmill model, leading to potential dissatisfaction or lost sales.
- Marketing Inefficiency: Broad, "one-size-fits-all" marketing efforts due to an unclear understanding of the unique demographic signatures of each product tier.
- Untapped Upsell Potential: An inability to distinguish between entry-level and premium buyers, resulting in missed opportunities to move high-income prospects toward premium models.


## **Objectives**
- Identify distinct customer segments for each treadmill model (KP281, KP481, KP781)
- Develop customer profiles using descriptive statistics and probability analysis
- Create actionable insights for targeted marketing and sales recommendations
- Establish a data-driven framework for product positioning and pricing strategy


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


# **Final Business Insights & Recommendations**
## **Top 10 Insights & Recommendations**

### 1. Product Popularity:
- KP281 is the most popular product (44% of sales), followed by KP481 (33%), and KP781 (23%). This shows a healthy distribution across price points.


### 2. Gender Preference:
- Males dominate premium purchases: 80% of KP781 buyers are male
- Females: 57% of KP281 buyers are female
- KP481 has balanced gender distribution


### 3. Income :
- KP781 buyers have highest average income ($74,000)
- KP481 buyers have moderate income ($55,000)
- KP281 buyers have lowest average income ($45,000)


### 4. Age Patterns:
- KP781 buyers are slightly older (average 29 years)
- KP281 attracts youngest customers (average 28 years)


### 5. Fitness Level:
- KP781 buyers rate themselves as most fit (average 4.5/5)
- KP481 buyers are moderately fit (average 3.5/5)
- KP281 buyers are least fit (average 3.0/5)


### 6. Usage Patterns:
- KP781 users plan to use treadmill most frequently (5 times per week)
- KP481 users plan moderate usage (4 times/week)
- KP281 users plan least usage (3 times/week)


### 7. Marital Status Impact:
- Partnered individuals slightly prefer KP281 and KP481
- Single individuals show higher preference for KP781 (58% of KP781 buyers are "single")


### 8. Probability Scenarios:
- A male customer has 34% probability of buying KP781
- A high-income customer (>$50K) has 58% probability of buying KP781
- A highly fit customer (level 4-5) has 68% probability of buying KP781


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
