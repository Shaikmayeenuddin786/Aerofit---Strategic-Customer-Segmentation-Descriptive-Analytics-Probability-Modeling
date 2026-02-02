# **Aerofit - Customer Segmentation,Product Strategy Analysis (Descriptive Analytics + Probability Modeling)**
---

## **Quick Section Summary**
- **Business Problem** - What challenge Aerofit faced
- **Objectives** - What the analysis aimed to achieve
- **Technical Stack** - Tools and technologies used
- **Project Features** - What you actually built/analyzed
- **Repository Structure** - How the project is organized
- **Top Business Insights & Recommendations** - Actionable business outcomes


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

![DATASET INFORMATION](https://github.com/user-attachments/assets/e0dc8090-9595-47bd-b714-c554cf656f1e)

![MISSING VALUES_PERCENTAGE CHECK](https://github.com/user-attachments/assets/9c9a8494-037e-4e91-b320-9c09a64f7965)

![STATISTICAL SUMMARY_NUMERICAL   CATEGORICAL COLUMNS](https://github.com/user-attachments/assets/f3238378-57ee-454e-8a9a-ae69aa4548ca)


### **Visual Analytics & Customer Profiling**
**UNIVARIATE ANALYSIS (CATEGORICAL & NUMERICAL VARIABLES):**
  
  ***CATEGORICAL***
  - KP281 is the most popular model at 44%, showing that entry-level treadmills have the market appeal.
  - More female customers (58%) than male (42%), suggesting Aerofit products appeal more to women overall.
  - Most customers are partnered (59% vs 41% single), indicating treadmills might be purchased more for family or shared household use.
  
  ***NUMERICAL***
  - Age distribution is normal: Most customers are in their 20s-30s (mean 28.8)
  - Income varies widely: shows most customers earn $40K-$60K, but there's a long tail of higher earners that could be targeted for premium models.
  - Fitness selfratings: The average fitness of 3.3/5 suggests customers are moderately active, with fewer at the extremes (very unfit)
  - Education : Most customers have approx 16 years of education 

![UNIVARIATE ANALYSIS - CATEGORICAL VARIABLES](https://github.com/user-attachments/assets/d1ba23d4-5641-493f-8a58-41a3cc78234d)
![UNIVARIATE ANALYSIS - NUMERICAL VARIABLES](https://github.com/user-attachments/assets/401d730a-32c4-4fd3-8232-f3c04c71b570)

**BIVARIATE ANALYSIS:** 

  - *Gender segmentation is clear:* The top-left chart shows females prefer KP281, males dominate KP781, and KP481 has more balanced gender distribution. This is one of your strongest patterns.
  - *Income is the strongest predictor:* The middle-bottom chart clearly shows KP781 buyers have much higher incomes than other groups, with almost no overlap in income ranges between products.
  - *Fitness level increases with product tier:* The top-right chart shows KP781 buyers rate themselves as most fit (mostly 4-5), while KP281 buyers are least fit (mostly 3-4).
  - *Age differences are minimal:* The bottom-left chart shows all three products have similar age ranges, with only slight variations - age isn't a major differentiator.
  - *Usage patterns align with product tiers:* The bottom-right chart shows KP781 buyers plan highest weekly usage (mostly 4-5 times), while KP281 buyers plan lowest usage (mostly 2-3 times).

![BIVARIATE ANALYSIS - PRODUCT VS OTHER VARIABLES](https://github.com/user-attachments/assets/fb522707-dd38-4aaa-bd21-7a4690dbc245)

 

### **Probability & Statistical Analysis**
- **Marginal Probabilities**: Calculated overall product purchase distributions (KP281: 44%, KP481: 33%, KP781: 22%)
- **Conditional Probabilities**: Key insights including 68% probability of fitness level 4-5 customers buying KP781
- **Contingency Tables**: Two-way tables showing relationships between product choice and customer attributes

<img width="801" height="397" alt="image" src="https://github.com/user-attachments/assets/7b668fc8-da47-4f80-a91e-e97a95c04b34" />




### **Business Insights Generation**
**Customer Profiles**: 
  - KP281: Entry-level users, younger demographic, lower income, casual fitness enthusiasts
  - KP481: Intermediate users, balanced gender distribution, moderate income, regular exercisers
  - KP781: Advanced users, predominantly male, high income, serious fitness enthusiasts
    
![CUSTOMER PROFILE FOR KP281](https://github.com/user-attachments/assets/76d2856e-12e9-4cb5-b161-74cd3659b868)
![CUSTOMER PROFILE FOR KP481](https://github.com/user-attachments/assets/40cb9106-5e11-4257-8746-257ac2272c72)
![CUSTOMER PROFILE FOR KP781](https://github.com/user-attachments/assets/e1db3a36-739f-4ecd-9041-dcd4f2920ab8)


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
## **Top 8 Insights & Recommendations**

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

  
# **RECOMMENDATIONS**

### Targeted Marketing Campaigns:
- KP781: Target males with high income, emphasize advanced features
- KP481: Market to both genders, highlight value for money
- KP281: Focus on mostly on females and beginners, stress ease of use

### Product Placement: 
- Place KP781 in high-end fitness stores
- KP481 in general sports stores &
- KP281 in department stores.

### Upselling Strategy: 
- Create a loyalty program to move KP281 customers to KP481, and KP481 customers to KP781 as their fitness improves.
  
### Gender-Specific Features: 
- Consider adding more features to appeal females in KP781
### Financing: 
- Offer financing options for KP781 to make it accessible to middle-income serious fitness enthusiasts.
### Marital Status : 
- Create family/friend referral programs, especially for KP281 and KP481 which are popular among partnered individuals.

---

## **How to Run This Project( Anaconda - Jupyter notebook)**
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Open `notebooks/Aerofit_Analysis.ipynb` in Jupyter
4. Run cells sequentially to reproduce the analysis


---
