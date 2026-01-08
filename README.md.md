# Victoria Road Accidents & Weather Impact Analysis

## Objective
To analyse the relationship between weather conditions and road traffic accidents in Victoria and assess how extreme heat events influence accident frequency.

## Data Sources
- Victorian road accident data (public dataset)
- Daily weather data (NOAA)

## Methodology
- Data cleaning and reshaping into tidy format
- Statistical distribution fitting (Poisson, Negative Binomial)
- Feature engineering using Excess Heat Factor (EHF)
- Regression modelling (Linear Models, GAM)
- Model comparison using AIC

## Key Insights
- Accident counts exhibit overdispersion, best modelled using Negative Binomial distribution
- Temperature shows stronger predictive power than EHF alone
- Weather variables improve model interpretability but require additional features (e.g. precipitation)

## Tools
R, tidyverse, fitdistrplus, ggplot2

## Business Relevance
Insights from this analysis could assist emergency services in anticipating demand during extreme weather conditions.
