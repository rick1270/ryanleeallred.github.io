---
layout: post
title:  Regression Modeling
category: R
---
Regression modeling is a form of predictive modelling technique which investigates the relationship between a dependent (target) and independent variable (s) (predictor). This technique is used for forecasting, time series modelling and finding the causal effect relationship between the variables.  It attempts to minimize the residual errors in your data.

Beware of outliers!  Outliers have a way of throwing off models, so you may wish to prune them with something like:

`df[np.abs(df.Data-df.Data.mean()) <= (3*df.Data.std())]`

This keeps only the ones that are within +3 to -3 standard deviations in the column 'Data'.
