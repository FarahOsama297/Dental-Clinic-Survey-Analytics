# Patient Satisfaction Survey Analysis

This project analyzes patient satisfaction data collected from a dental clinic survey. The goal is to clean the dataset, evaluate reliability, explore correlations, run regression analysis, and generate key insights about factors influencing patient commitment and recommendation behavior.

## 1. Data Cleaning
- Removed duplicate entries
- Translated Arabic responses into English
- Removed noisy and invalid values
- Standardized all survey items
- Generated descriptive statistics for all questions

## 2. Descriptive Statistics
Calculated mean, median, standard deviation, and distribution patterns for all survey questions to understand response behavior.

## 3. Reliability Analysis (Cronbach’s Alpha)
- Overall Cronbach’s Alpha: 0.9119
- Confidence interval: 0.885 – 0.935
This indicates excellent internal consistency.

### Dimension-Level Reliability
- Sensory: 0.57
- Emotional: 0.62
- Professional: 0.41

## 4. Correlation Analysis
- Sensory and Emotional dimensions are moderately correlated.
- Sensory–Professional and Emotional–Professional show weak correlations.
- A correlation matrix and heatmap were generated to visualize relationships between all survey questions.
- A separate chart shows the correlation of each question with the commitment variable.

## 5. Regression Analysis
- Sensory coefficient: 0.188
- Emotional coefficient: 0.222
- Professional coefficient: -0.001
- Intercept: 2.012 (first model) and 3.031 (second model)
- MSE: 0.595
- R²: 0.088

Regression results indicate that Sensory and Emotional dimensions positively influence commitment, while Professional has little effect.

## 6. Visualizations
The project includes:
- Heatmap of all survey question correlations
- Bar chart showing correlation with commitment
- Scatter plots for top correlated questions
- Regression coefficient plot
- Histograms and boxplots for Sensory, Emotional, and Professional dimensions
- Scatter plots of each dimension vs. commitment

## 7. Demographic Insights

### By Age Group
- Ages 18–25: highest commitment (3.63)
- Ages 26–35: 3.52
- Ages 36–45: 3.43
- Ages 46–60: no valid data

Younger patients show slightly higher commitment.

### By Gender
- Female: 3.63
- Male: 3.50

Females show slightly higher commitment.

## Conclusion
This project provides a full end-to-end analysis of patient satisfaction including data cleaning, reliability testing, correlation study, regression modeling, and visual analytics. It highlights key factors that influence patient commitment and recommendation behavior.

## Tools & Technologies
- Python
- Google Colab
- Pandas, NumPy
- Matplotlib, Seaborn
- Statsmodels / Scikit-learn
