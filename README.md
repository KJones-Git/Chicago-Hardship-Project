# **Chicago Hardship Index Analysis**

<div align="center">
  <img src="https://github.com/KJones-Git/Chicago-Hardship-Project/blob/014f4154fc28c218db55f7893ea573bbe8cb2f82/chicago_hardship.jpeg?raw=true" alt="Chicago Hardship Project" width="750"/>
</div>


## **Project Overview**
This project analyzes socioeconomic factors influencing hardship levels across Chicago's different neighborhoods. The goal is to identify which parameters had the most influence on the **Hardship Index** and to classify neighborhoods into **high** and **low hardship** categories using **Random Forest Classification**.

## **Dataset & Preprocessing**
- **Dataset:** Chicago Hardship Index data
  - This data set was provided during a census done in 2012
- **Preprocessing Steps:**
  - Removed duplicates and missing values
  - Encoded categorical variables
  - Scaled numeric features where necessary
  - Transformed **Hardship Index** into a binary classification target

## **Modeling Approach**
- **Algorithm Used:** Random Forest Classifier
- **Hyperparameter Tuning:** GridSearchCV to optimize parameters
- **Final Model Accuracy:** **89.50% (cross-validated)**

## **Key Findings (Feature Importance)**
| Feature                   | Importance |
|---------------------------|------------|
| **Per Capita Income**      | 39.0%      |
| **Households Below Poverty** | 21.0%  |
| **% Without HS Diploma**   | 15.0%      |
| **% Unemployed**           | 13.0%      |
| **Housing Density**        | 7.0%       |
| **% Under 18 or Over 64**  | 5.0%       |

## **Conclusion & Next Steps**
This model provides insights into the factors contributing to the hardship rankings, highlighting the need for targeted interventions in **income support, education, and employment programs**. Notably, **Per Capita Income emerged as the most influential feature**, reinforcing the strong correlation between economic status and hardship levels. Future enhancements could include geospatial analysis and time-series modeling to track trends over time.



## **Contributions**
Contributions are welcome! Feel free to open an issue or submit a pull request.

---
### 🖋 Author: Kyle Jones
|Website     |  Handle   | 
|---------|-----------------|
|Github| https://github.com/KJones-Git        |
|Tableau |   https://public.tableau.com/app/profile/kyle.jones8049/vizzes      |
|LinkedIn |  https://www.linkedin.com/in/kylelaurencejones/      |
