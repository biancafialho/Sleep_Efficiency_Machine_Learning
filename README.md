# Random Forest Regressor for Sleep Efficiency Prediction

## Overview

This GitHub repository contains the implementation of a Random Forest Regressor for predicting sleep efficiency based on various sleep-related variables. The model has shown promising results, achieving a Mean Absolute Percentage Error (MAPE) of 4.7%. This indicates that the model can be effectively utilized in real-world scenarios for sleep efficiency prediction.

## Results

The model analysis reveals that three key variables significantly influence the target variable (Sleep Efficiency):

1. **Light Sleep Percentage**
2. **Awakenings**
3. **Deep Sleep Percentage**

The charts provided in the repository visually demonstrate the impact of these variables on sleep efficiency. Understanding these influential factors is crucial for interpreting the model's predictions and gaining insights into the dynamics of sleep patterns.

## Model Validation

The MAPE of 4.7% attests to the model's accuracy in predicting sleep efficiency. This validation metric indicates a low level of error in the model's predictions, further supporting its reliability for practical applications.

## Exploratory Data Analysis (EDA) Insights

During the Exploratory Data Analysis (EDA), several key insights emerged, shedding light on the relationships between different variables and sleep efficiency:

1. **Gender Balance:**
   - The dataset exhibits a balanced distribution in terms of gender percentage.

2. **Gender-specific Sleep Efficiency Patterns:**
   - Women tend to demonstrate greater variability in sleep efficiency compared to men.
   - Women generally have a slightly lower ability to achieve efficient sleep, whereas men exhibit a higher level of efficiency with less variability in this category.

3. **Deep Sleep Percentage and Sleep Efficiency:**
   - Individuals with a low percentage of deep sleep tend to have lower sleep efficiency.
   - On the other hand, those who spend more than half of their total sleep time in deep sleep stages show better sleep efficiency.

4. **Light Sleep Duration and Efficiency:**
   - There is an inverse relationship between the time spent in light sleep and sleep efficiency.
   - Individuals who have less time in light sleep phases tend to experience higher sleep efficiency.

5. **Smoking and Sleep Efficiency:**
   - Non-smokers generally exhibit a higher level of sleep efficiency, showcasing lower variability in comparison to smokers.
   - Smokers, especially those with sleep efficiency levels below 0.6, demonstrate lower sleep efficiency on average.

These insights provide a deeper understanding of the factors influencing sleep efficiency within the dataset, enabling better interpretation and utilization of the Random Forest Regressor model results. The model's ability to align with these EDA findings further enhances its credibility in capturing and leveraging meaningful patterns in sleep-related data.
