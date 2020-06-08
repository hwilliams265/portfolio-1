---
layout: post
title: Statistical Analysis of Cancer Data
year: 2019
---

For my Data Science in R class, we were tasked with analyzing a large, publicly available data set. My team chose demographic and geographic cancer incidence data provided by the CDC. The full results of our analysis can be found on [our project website](https://this-is-r-world.netlify.com/big_picture/). In our analysis, we use a linear regression model to predict cancer rates in different regions based on demographic and health factors. Or in simpler terms, we use obesity rates, poverty rates, and doctor visit rates to predict which people are more or less likely die from cancer. 

I've included a few of the more visually interesting figures below. For the full analysis, including our linear model, please visit our project website.

## The Big Picture

Public health is an extremely data-reliant discipline, yet many ailments are difficult to track directly, particularly in rural areas. However as this analysis shows, mortality rates can be predicted with high accuracy using secondary data. While our analysis only focuses on generalized rates of cancer mortality, it's trivial to extrapolate the methods we use to other data sets, such as lung cancer and smoking rates. Additionally, we use a rudimentary linear model in our analysis; future analysis could utilize more robust non-linear models.

![Cancer rates for different agegroups over time](statistical-analysis-of-cancer-data/cancer-rate-bar-chart.png) ![Male vs. female rates of cancers over time](statistical-analysis-of-cancer-data/cancer-rate-scatter-chart.png)