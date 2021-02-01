# Thinkful-Predicting-cancer-mortality
Creating regression model using EDA and multiple methods, including ensemble and boosting methods.  Created for Thinkful Capstone 2

# Dataset
Using conglommerated data from data.world, with added additional features from IHME, to predict cancer death rate.  Data from IHME concerning physical activity, obesity, and alcohol consumption prevelance were joined to the initial dataset.  All features were examined to ensure values were within logical guidelines (no average ages exceeded the lifespan of a human, for example).  Given that each row represents a county, geographical region was introduced as a categorical feature, with regions defined by the offical divisions set by the Department of Health & Human Services.  Further work on the model could include different divisions of counties to determine similar areas that produce similar target values.


# Insights
Highest performing GradientBoosting model using 26 features.  All else being equal, physical activity was the predominant explanatory feature, followed by the percent of the population having post-secondary education and high median incomes.  The model outperformed all other methods and improved over the course of testing by 2.56% over an initial GradientBoosting regression.
