# Bank Marketing Campaign Analysis and Predictive Modeling

## Project Overview
This project involves a detailed analysis and predictive modeling of a bank marketing dataset. The dataset contains information about customer interactions during marketing campaigns, including customer demographics, communication details, and the campaign outcomes.

## Dataset Description
The dataset includes the following attributes for each customer interaction:
- Occupation
- Age
- Education level
- Marital status
- Communication channel
- Call timing and duration
- Outcome of the previous marketing campaign
- Conversion status after the call

Each entry represents a unique customer interaction, providing insights into the effectiveness of marketing strategies in the banking sector.

## Data Analysis
The initial data analysis focused on understanding the distribution and summary statistics of various attributes, identifying anomalies like duplicate entries or missing values, and preparing the data for modeling.

### Insights Gained:
- Analysis of conversion rates across different demographics and campaign timings.
- Statistical analysis of call durations and frequencies.
- Seasonal trends impacting the effectiveness of campaigns.

## Predictive Modeling
The goal of predictive modeling in this project is to forecast the likelihood of a customer converting based on their interaction history and profile.

### Models Developed:
1. **Logistic Regression** - Served as a baseline model.
2. **Random Forest Classifier** - Provided improved accuracy and AUC scores, indicating a better performance in distinguishing between converted and not converted outcomes.

### Model Evaluation:
Both models were evaluated based on accuracy and AUC-ROC scores. The Random Forest model, in particular, showed promising results, although it suggested potential overfitting which was addressed through hyperparameter tuning.

## Conclusion
This project illustrates the application of data analytics and machine learning in improving the effectiveness of marketing campaigns. The insights and predictive models developed can help tailor marketing strategies to enhance customer engagement and conversion rates.

## How to Use
1. Clone the repository.
2. Ensure you have Python installed along with libraries like pandas, sklearn, and jupyter.
3. Run the Jupyter notebooks to see the analysis and modeling steps.

## Future Work
- Exploring more sophisticated ensemble methods and deep learning models.
- Implementing feature engineering to uncover more insights from the data.
- Continuous monitoring and updating of models as new data becomes available.
