# Data Science Bootcamp – Capstone Project 2

## Disclaimer
This project is prepared for educational purposes at the Data Science Academy Bootcamp. The dataset and scenario are simulated to allow practice of predictive modeling and decision support using SPSS Modeler (Clementine).

---

## Project Overview
Capstone Project 2 focuses on predicting **subscription payment defaults** within 30, 60, and 90 days using statistical and AI-based modeling.  

**Dataset:**
- File: `Ecmp_Crdt_Scr_BA..xls`  
- Created: 01.03.2018  
- Size: ~25,000 subscribers  
- Includes customer demographic and subscription data  

**Business Requirement:**
- Identify which subscriptions have a high probability of **non-payment** within 30, 60, and 90 days.

**Tools & Methods:**
- IBM SPSS Modeler (Clementine)  
- At least two modeling approaches:
  1. Statistical model (e.g., Logistic Regression)
  2. AI model (e.g., Decision Tree, Random Forest, Neural Network)

---

## Methodology: CRISP-DM Framework
The project follows a hierarchical **CRISP-DM methodology**:

1. **Business Understanding**
   - Define the problem: Predict subscription payment defaults
   - Determine key business goals and success criteria

2. **Data Understanding**
   - Explore dataset: missing values, distributions, outliers
   - Visualize customer demographics and subscription features

3. **Data Preparation**
   - Feature engineering:
     - Example: `Abone_Biyolojik_Yas = Reference_Date - Birth_Date`
     - Create averages, ratios, and flag variables
   - Data cleaning and manipulation
   - Summary analytics

4. **Modeling**
   - Build at least two separate models (statistical & AI)
   - Optionally, create a **combined model** integrating both approaches
   - Experiment with hyperparameters and modeling techniques

5. **Model Evaluation**
   - Evaluate performance of each model using appropriate metrics
     - Examples: Accuracy, AUC, Precision, Recall, F1-score
   - Compare statistical vs AI models
   - Document results and insights

6. **Deployment / Decision Support**
   - Integrate final model(s) into a **decision support workflow**
   - Generate actionable insights for subscription management
   - Optional: create visual dashboards or reports

---

## Deliverables
1. **SPSS Modeler Streams**:
   - Separate or combined streams for each model
   - Each step enclosed in a **Supernode** with descriptive naming
2. **Final Report / Presentation**:
   - Summary of each CRISP-DM step
   - Visualizations from data understanding and preparation
   - Modeling results and evaluation
   - Recommendations for decision support

---

## Key Notes
- New variables must be created to enhance model predictive power:
  - Customer age, average usage, payment ratios, flag variables
- Visualizations and summaries are essential for all steps
- This project prepares for more complex real-world business problem solving

---


