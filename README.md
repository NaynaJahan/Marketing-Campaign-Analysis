# Marketing-Campaign-Analysis
The goal of the project is to create prediction models that will show which consumer categories respond best to marketing efforts from telecommunications companies and provide strategic insights to improve the efficacy of future initiatives.

The main goal of this study is to develop and assess predictive models that pinpoint the consumer groups most likely to react favourably to advertising campaigns and offer useful information for improving future marketing tactics. To support our project aim, we asked the following questions:
1. Which customer segments are most responsive to marketing campaigns?
2. What strategies can be derived from the model outputs to improve future campaigns?

## To answer these questions, we had the following objectives:
1. Create statistical models. For predictive analysis, create a non-parametric model (decision tree) and a parametric model (logistic regression).
2. Analyse and contrast models: To evaluate the models, use cross-validation and performance indicators including accuracy, precision, recall, F1-score, and ROC-AUC.
3. Extrapolate knowledge: Examine the models’ results to see which aspects have the greatest influence, then turn those findings into business plans.

## Model Development:
1. **Logistic Regression:** A parametric model that belongs to the family of generalised linear models made for binary classification tasks was the initial model used for the project. The model optimised the likelihood function using the lbfgs solver and used Maximum Likelihood Estimation (MLE) for parameter estimation. This model was chosen due to its interpretability and ability to draw attention to the most significant predictive characteristics, offering insightful information about consumer behaviour. A variety of metrics, including accuracy, precision, recall, F1 score, and ROC-AUC, were used to analyse the logistic regression model’s performance to fully examine its classification effectiveness.
2. **Decision Tree:** Set to a maximum depth of 5, this model served as the project’s non-parametric model. As it can capture non-linear correlations in the data and offer an interpretable visualisation of feature importance, this non-parametric model was selected to help identify which qualities have the greatest influence on the prediction 
To preserve consistency in the comparative analysis and provide an equitable evaluation of performance across models, the model was assessed using the same metrics as the logistic regression model.
