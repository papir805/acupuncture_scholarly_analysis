# acupucture_scholarly_analysis - Statistical analysis of scholarly article regarding effects of acupuncture treatment on systolic and diastolic blood pressure.
## Goal: I wanted to apply my knowledge of areas in Statistics such as hypothesis testing, confidence intervals, and linear regression modeling, to real world data, as well as to learn more about the Python packages that would enable me to do so.

Important libraries used: `Pandas`, `NumPy`, `SciPy`, `Statsmodels`, and `Matplotlib`

## How to use:
[Click here](https://github.com/papir805/acupuncture_scholarly_analysis/blob/master/scholarly_analysis_github.ipynb) to see the .ipynb Jupyter notebook file that contains the Python code, along with the outputs of that code, as well as any relevant mathematical formulas, rendered in LaTeX, that were used during the process.  

Backup: [Click here](https://nbviewer.org/github/papir805/acupuncture_scholarly_analysis/blob/master/scholarly_analysis_github.ipynb) if the first link isn't able to render the notebook properly.

## What does this contain?
- Hypothesis testing for:
  - Difference in population proportions
    - Using Z and Chi-Square Distributions
  - Significance in slope of our linear regression
    - Using ANOVA and the F Distribution, as well as the student t Distribution
- Constructing confidence intervals for:
  - Difference in population proportions
    - Using Z Distribution
  - Slope of our linear regression model
- Simple linear regression modeling to:
  - Predict diastolic blood pressure, after acupuncture treatments, using age as the predictor variable
  - Predict systolic blood pressure, after acupuncture treatments, using age as the predictor variable
- Multiple linear regression modeling to:
  - Predict systolic blood pressure, after acupuncture treatments, using age, gender, and treatment group
