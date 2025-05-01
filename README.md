# Randomization Inference Analysis 🧪

## Overview 📊
This project demonstrates advanced statistical techniques for estimating causal effects in randomized experiments, focusing on the Get-Out-The-Vote (GOTV) field experiment.

## Key Techniques 🔍
- **Average Treatment Effect (ATE)** estimation
- **Randomization Inference** for hypothesis testing
- **Inverse Probability Weighting (IPW)** estimators
- **Neyman's difference-in-means** estimator

## Mathematical Framework 🔢
The analysis implements several key estimators:

### Neyman Estimator for ATE
$$\hat{\tau} = \frac{1}{n_t}\sum_{i=1}^{n}Y_i T_i - \frac{1}{n_c}\sum_{i=1}^{n}Y_i(1-T_i)$$

### IPW Estimator
$$\hat{\tau}_{IPW} = \frac{1}{n}\sum_{i=1}^{n}\left(Y_i\frac{T_i}{p} - Y_i\frac{1-T_i}{1-p}\right)$$

### Variance Calculation
$$Var(\hat{\tau}) = \frac{s^2_t}{n_t} + \frac{s^2_c}{n_c}$$

## Skills Demonstrated 💪
- Implementation of statistical estimators from mathematical formulations
- Hypothesis testing through both asymptotic and simulation-based approaches
- Working with real experimental data
- Data manipulation and preprocessing in Python
- Analysis of voter behavior and social influence

## Project Significance 🌟
This project showcases the ability to implement and interpret causal inference techniques in a real-world context, providing actionable insights about intervention effectiveness.
