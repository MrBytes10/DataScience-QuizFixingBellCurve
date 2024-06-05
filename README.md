# DataScience-QuizFixingBellCurve

# FixingBellCurve-Ds.Quiz

Question: Generate 1100 numbers, between 90 and 200, using Numpy's arange function. This is a Universe Create problem. Consider that this represents the data of the height of a typical population in the 16-24 age group, in Canada. Perform the usual mean, standard deviation, norm, and fit Bell Curve using SciPy libraries.
Remember to use the following libraries:

- i). Norm of SciPy.stats libraries
- ii). Statistics Libraries
  - Generate a report on the JupyterLab Notebook using markdown textcode and code, and plot. You can then submit the report.
  - An analysis at the end is a must. Also, the report should contain inferences.

# SOLUTION GUIDE

Problem statement:

- Let's assume that the data we generate represents the height of the population of agegroup 16-24 in canada.
- We then fit a curve to it and perform statistical analysis on it.

OBJECTIVE:

- To fit a line curve on a random data by providing initial guesses.
  PERFORM THE FOLLOWING STEPS:

1. Generate 1100 data points between 90 and 200 using numpy arange function
2. Find the mean and the standard deviation of the array.
3. Create random variants of the data using norm.rvs
4. Fit a curve(line) on the data using scipy.curve_fit
5. Check how it fits, by plotting it against the data.
