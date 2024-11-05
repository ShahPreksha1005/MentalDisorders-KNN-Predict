# MentalHealth-DALYs-Analysis

### Project Overview
This project analyzes the burden of mental illnesses from 1990 to 2019 across various disorders, including depressive disorders, anxiety, bipolar disorder, schizophrenia, and eating disorders. Using data on Disability-Adjusted Life Years (DALYs) rates, this analysis explores the data through univariate, categorical, and bivariate lenses, providing insights into mental health trends and correlations among disorders.

### Key Objectives
- **Data Exploration:** 
  - Summarize and visualize DALYs rates for each mental illness.
  - Perform univariate, categorical, and bivariate analyses to uncover trends and relationships.
- **Modeling with K-Nearest Neighbors (KNN):**
  - Classify DALYs rates into 'high,' 'medium,' and 'low' categories.
  - Evaluate model performance using precision, recall, and F1-score across classes.

### Data Analysis
1. **Basic Information & Univariate Analysis:**
   - Examines the distribution of DALYs rates, highlighting that depressive disorders have the highest mean rate.
   - Visualized with histograms and density plots.

2. **Categorical Variables Analysis:**
   - Distribution analysis across 228 entities, 205 unique country codes, and years from 1990 to 2019.

3. **Bivariate Analysis:**
   - Scatter and box plots reveal correlations among disorders, with moderate correlations identified between certain pairs (e.g., bipolar disorder and eating disorders).

### KNN Modeling for Classification
- Trained a K-Nearest Neighbors model with varying values of K to classify DALYs rates.
- Analyzed model performance using precision, recall, and F1-score metrics for each class label.
- Insights gained from the classification report on model accuracy and balance across classes.

### Key Findings
- **Correlations:** Moderate positive correlations exist between some mental illnesses.
- **Model Performance:** The KNN model demonstrates moderate success in predicting DALYs rates across classes, with performance varying by class.

### Future Directions
- Test additional classification models (e.g., SVM, Random Forest) for improved accuracy.
- Perform deeper analysis on specific disorders and country-wise trends.

