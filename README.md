# Microfinance-Incentives-to-Repay-and-Overindebtedness-Evidence-from-a-Household-Survey-in-Bolivia

I designed a household survey and collected data from around 1000 microfinance clients in Bolivia in 2002.
The data collected was used published in my Ph.D. Dissertation "Microfinance, Incentives to Repay and, Overindebtedness: Evidence from a-Household Survey in Bolivia" in 2008 and available in this repository.

The main goal of the empirical analysis was to determine the statistical significance of different factors associated with overindebtedness of households during the 1998-2001 financial crises. The main priority of the empirical analysis was to determine which explanatory variables were statistically significantly associated with overindebtedness.  At the end, the main results were estimated using the "xtlogit" command in Stata version 9.

The goals of this repository are the following:
1) Replicate in Python some of the data wrangling previously done in Stata
2) Replicate, if possible, the main results of the Dissertation publised on page 150 and page 156.  As shown in the analysis, logit estimation using "Statsmodel" in Python is similar to logit estimation using the "logit" command in Stata, but there is no equivalent of "xtlogit" in Python.
3) Find best Hyperparameter for SVM, Classification Trees and Logistic Regression, and compare the scores of these models with KNN.
