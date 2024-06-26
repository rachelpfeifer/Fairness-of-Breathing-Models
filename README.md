# Fairness of Breathing Models

Evaluating demographic fairness in respiratory health datasets. Implementing COPD and COVID-19 detection models using breathing audio data from patients infected with these illnesses, and then reducing bias through mitigation algorithms.

## A Guide To This Repository:
The Analysis folder contains the analyses for the demographic parity and equalized odds based on the results obtained. The .ipynb file for demographic parity contains the calculations for the average selection rate before mitigation vs. after mitigation, percent improvement calculations for both the demographic parity ratio and demographic parity difference, and a Welch's Two-sample t-test for the demographic parity difference. The .ipynb file for equalized odds contains calculations for the average false negative rate before mitigation vs. after mitigation, percent improvement calculations for both the equalized odds ratio and the equalized odds difference, and a Welch's Two-sample t-test for the equalized odds difference.

The Figures folder has the two .ipynb files that contain the code that produces the figures for demographic parity and equalized odds. The code generates 6 figures: 3 for demographic parity and 3 for equalized odds.

The Results folder includes two .ipynb files. One .ipynb file is the code for the decision tree model (based on the parameters returned from grid search cross-validation) that is used to produce the metric values for demographic parity before and after mitigation (this is repeated for a total of 30 iterations). The other .ipynb file contains the code for the decision tree model (based on the parameters returned from grid search cross-validation) to determine the metric values for equalized odds before and after mitigation (this is repeated for a total of 30 iterations).
