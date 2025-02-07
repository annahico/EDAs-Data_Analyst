# London Crime Hypothesis Testing (2008-2016)

## by annahico

## Summary of Project

In this project, I aim to understand the crime rate in London, England, with a focus on violent crime rates and their occurrence throughout the year. The dataset includes all crimes (both violent and non-violent) committed between 2008 and 2016. However, the dataset does not specify the nature of the crimes (violent or non-violent), so we will address this during the preprocessing phase. Additionally, we will identify the months when daylight saving is in effect.

There are one notebook dedicated to this project:

1. **London Crime Hypothesis Testing.ipynb**: Focuses on testing individual factors (borough/location & daylight saving) that may affect the violent crime rate and examines the interactions between location/borough and daylight saving to determine any significant effect on the crime rate.

My initial assumption is that violent crime rates increase when daylight saving is not in effect, meaning nights are longer. Therefore, our hypotheses are:

**Null Hypothesis:** The difference between the violent crime rates when daylight saving is and isn't in effect is less than or equal to 0.  
**Alternative Hypothesis:** The difference between the violent crime rates when daylight saving is and isn't in effect is greater than 0.

We will assume a Type 1 Error rate of 0.05.

## Installation

```plaintext
Packages used:
* Matplotlib
* Numpy
* Pandas
* statsmodels.api
* random
* statsmodels.stats.proportion
```
