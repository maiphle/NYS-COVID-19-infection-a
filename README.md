# Executive Summary

In addressing the impact of vaccination rates on COVID-19 in New York State, our analysis encompassed spatial and temporal patterns, regional disparities, and public sentiment.

The first factor analysis unveiled significant disparities among counties, pinpointing positive impacts in Richmond, Rockland, and Suffolk, and negative effects in Essex, Yates, and Tompkins. The second factor analysis revealed a noteworthy effect of initial vaccines but highlighted challenges like seasonal factors and emerging variants.

In evaluating model performance, the Linear Regression model showcased strong explanatory power (R-squared = 0.85) in training but demonstrated lower predictive accuracy (RMSE = 193.55) in testing. The ARIMAX model, on the other hand, outperformed Linear Regression in predictive accuracy, demonstrating lower RMSE values for both training (45.86) and testing (350.87), and proving effective in capturing percentage differences (MAPE = 0.29 for training, 1.60 for testing) and maintaining high correlation with actual values (0.99 for training, 0.88 for testing).

Recommendations arising from the analyses include prioritizing targeted interventions in counties with highest severity of virus spread in the population, acknowledging temporal considerations such as seasonal factors and emerging variants, addressing public concerns through tailored communication strategies, and favoring the ARIMAX model for forecasting due to its superior predictive accuracy.

In conclusion, our analyses provide nuanced insights into the dynamics of COVID-19 in New York State, emphasizing the need for tailored interventions and effective communication strategies.


# Problem Description

To evaluate the impact of vaccination rates in New York State on subsequent COVID-19 infection rates, and to understand how public sentiment, as reflected through Twitter data, aligns with or influences these health metrics.

- Understanding the dynamics of COVID-19 in New York State: This involves analyzing the spatial and temporal patterns of the virus, including its spread across different counties and regions, as well as its fluctuations over time. This information is crucial for identifying hotspots and implementing targeted interventions.
- Identifying regional disparities and temporal trends: Examining variations in virus spread across different regions and over time can reveal potential inequities and highlight areas needing prioritized attention. This analysis helps identify communities disproportionately affected and tailor interventions accordingly.
- Analyzing public sentiment towards the pandemic: Understanding public attitudes and anxieties towards COVID-19 is essential for effective communication strategies.
