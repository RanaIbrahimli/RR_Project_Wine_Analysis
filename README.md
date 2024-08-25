# RR_Project_Wine_Analysis

## Project Overview

The goal of this project is to reproduce the analysis of the red wine dataset originally performed using R, but in Python. This project aims to validate and explore the insights gained from the original analysis while adapting the code and methods to Python. The focus of this work is not on the accuracy of the analytical methods themselves, but rather on the reproducibility, transparency, and documentation of the process.

The original analysis can be found https://www.kaggle.com/code/sagarnildass/red-wine-analysis-by-r/report on Kaggle. This project replicates and enhances that work within a Python environment.

To run the notebook successfully, please ensure that the following Python libraries are installed:
pip install pandas numpy matplotlib seaborn scikit-learn


### Results

In this analysis, I faced challenges in confidently predicting wine quality, particularly for 'Good' and 'Bad' wines, due to the dataset's concentration around 'Average' quality. A more comprehensive dataset would improve model accuracy. Initially, I suspected data issues when noticing some wines lacked citric acid, but further research clarified that citric acid is sometimes added to enhance acidity. I found that alcohol percentage, sulphate, and acid concentrations were key factors influencing wine quality. Notably, I encountered Simpson’s Paradox when volatile acids appeared to increase pH with acidity, revealing complex relationships between variables. For future studies, including wine rankings by multiple tasters could offer additional insights, considering human opinions in the analysis.

### Comparison

My analysis agrees with previuos analysis. Except for:

1. My citric acid distribution is a bit different which can happen due to different bin length. 

2. My m5 model explains a slightly more variance which may be due to internal randomization of the algorithm.
