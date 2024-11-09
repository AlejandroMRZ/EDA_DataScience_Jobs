**Exploratory Data Analysis on Global Data Science Job Postings**

### Author: Alejandro Martinez Ruiz
### Date: November 2024

---

### **Table of Contents**
1. Introduction  
2. Objectives of the Analysis  
3. Data Sources and Description  
4. Methodology  
5. Analysis Overview  
6. Challenges and Solutions  
7. Results and Conclusions  
8. Data Sources References

---

### **1. Introduction**
In this project, we conducted an **Exploratory Data Analysis (EDA)** on global Data Science job postings. The analysis was aimed at helping a multinational company, 'X', better understand the current labor market and make an informed decision on where to establish a new Data Science department. The need for highly qualified Data Scientists is growing exponentially, and understanding the geographical distribution of job opportunities, salary trends, and skills demanded in this field is crucial for hiring strategy and organizational growth.

---

### **2. Objectives of the Analysis**
The main objectives of this project were to:
- Analyze **salary trends** for Data Scientist roles across different regions such as the **US, UK, and Asia**.
- Examine the **most in-demand skills** in Data Science to identify key areas for recruiting and training.
- Provide **cost-benefit insights** regarding where the company should focus its **hiring efforts**, considering factors like average salaries, benefits, and office expenses.
- Explore the distribution between **remote and onsite job offerings** to help assess flexibility in hiring and workforce distribution.

---

### **3. Data Sources and Description**
- **Job Posting Data**: The primary dataset contained over **785,000** job postings across multiple regions, including information such as **job title**, **location**, **work mode** (onsite or remote), **salary data**, and required **skills**. This data was sourced from public job portals during **2023**.
- **University Rankings**: To further understand talent availability, we obtained data from *Edurank.org*, which provided a list of the top **20 universities** specializing in Data Science. This helped in evaluating talent availability in different regions.
- **Salary Data**: Supplementary salary data for the **UK** was also used to help fill gaps where job posting datasets lacked full salary details. These insights were collected from well-known sources and government reports.

---

### **4. Methodology**

#### **Tools Used**:
- **Python Libraries**: For the data analysis, **Pandas** was used for data cleaning and manipulation, **Matplotlib** and **Seaborn** for visualizations, and **Folium** for geographic analysis.

#### **Data Cleaning and Preparation**:
- **Handling Missing Values**: Many job postings had **missing salary data**. Instead of attempting to impute these values, we focused on analyzing only those records where salaries were explicitly provided to ensure accuracy.
- **Standardizing Data**: One significant challenge was dealing with inconsistent **country names** across different datasets, such as the difference between "United States" and "United States of America". These inconsistencies were corrected to facilitate effective merging and analysis.

#### **Data Analysis Techniques**:
- **Exploratory Data Analysis (EDA)**: The initial exploration involved calculating **summary statistics** and plotting various distributions to better understand the dataset.
- **Salary Analysis**: To compare salaries across regions, we created **box plots** and **bar charts** to highlight differences in compensation for Data Scientists in the **US**, **UK**, and **Asia**.
- **Geographic Visualization**: Using **Folium**, we visualized the **distribution of job postings** by country. This helped in understanding regional disparities in job opportunities.
- **Skills Analysis**: A **word cloud** was used to visualize the **most demanded skills** across job postings. This visualization was particularly useful for understanding what employers are seeking in Data Scientists globally.

---

### **5. Analysis Overview**

#### **Salary Comparison**:
- The average salary for Data Scientists in the **US** was found to be approximately **$160,000**, compared to **$80,000** in the **UK**. This stark difference highlighted the higher demand and cost associated with hiring in the US. The **box plot** provided clear visual evidence of this disparity, showing not only a higher median salary in the US but also a greater spread in the salary distribution.

#### **Remote vs Onsite Jobs**:
- Analysis of job postings revealed a **10:1 ratio** of onsite to remote positions. This suggests that despite the rise in remote work, **onsite positions** still dominate in the field of Data Science, which may influence where to focus recruitment efforts depending on company flexibility.

#### **Skills Analysis**:
- The **skills analysis** showed that **Python, SQL, and Machine Learning** are among the top skills in demand. The word cloud visualization effectively captured the relative importance of different skills, with larger words indicating higher frequency.

#### **University Ranking Analysis**:
- The data from *Edurank.org* showed that **top universities** for Data Science are concentrated in the **US** and **UK**. This aligns with the higher demand and salaries seen in those countries and highlights regions where the best talent may be sourced.

---

### **6. Challenges and Solutions**
- **Inconsistent Country Naming**: Merging datasets from different sources proved challenging due to inconsistent naming conventions for countries. This was resolved by creating a **mapping dictionary** to standardize country names.
- **Missing Salary Data**: A significant portion of job postings lacked salary information. To maintain reliability, only postings with explicit salary information were used in salary comparisons.
- **Geographic Representation**: The initial attempts at mapping job postings were challenging due to **missing or incorrect geographic data**. This was resolved by focusing on available data and adjusting for known discrepancies (e.g., renaming countries to match map labels).

---

### **7. Results and Conclusions**
- **Hiring Recommendations**: Based on the analysis, hiring in the **UK** could be a more cost-effective strategy for expanding a Data Science team, considering the lower salary expectations and lower office costs. However, the **US** remains a competitive market due to the higher number of top universities and possibly more experienced talent.
- **Talent Pool Insights**: The **US** and **UK** together have a strong concentration of top universities, suggesting that these regions may offer a higher quality of talent, albeit at a higher cost.
- **Remote Work Consideration**: Given the relatively low number of remote job postings, it might be more practical to consider **onsite hiring** for most roles, unless the company is specifically targeting global talent who can work remotely.

---

### **8. Data Sources References**
- **Job Posting Data**: Collected from various online job portals during **2023**.
- **University Rankings**: Sourced from *Edurank.org* ([https://edurank.org/cs/data-science/](https://edurank.org/cs/data-science/)).
- **Salary Data**: Supplementary salary data sourced from **industry reports** and **government statistics** for better comparison between the **UK** and **US**.

---


