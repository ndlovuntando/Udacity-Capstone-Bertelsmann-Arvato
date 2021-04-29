# Udacity-Capstone-Bertelsmann-Arvato
Udacity capstone project for the Machine Learning Engineer Nanodegree

## Installation
To run the Jupyter notebooks and python scripts, you will need a standard installtion of Anaconda with Python 3.6.x

Additional libraries needed:
- sklearn
- matplotlib
- numpy
- pandas
- seaborn

## Project Motivation
This project was done as the capstone requirement for Udacity's Machine Learning Engineer Nanodegree. The goal was to characterize what types of individuals are more likely to be customers of a mail-order retailer and predict which customers would respond positively to marketing campaigns.

## Data
The data used for this project not publically available. It was provided only to those participating in the "in class" competition.

## Files
- Arvato Project Workbook Jupyter Notebook
- imgs - direcoty of images extracted from the Jupyter notebook
- project report udacity.pdf - Analysis report


## Results
The detailed analysis of the results can be read in project report udacity.pdf.

### Customer segmentation
- One group was found to be more likely to be customers: These indivduals were more religious, older and savers.
- Two groups were found to be less likely to be customers: 1) Individuals with low purchasing activity and wealth (also younger) and 2) Individuals from areas with low population density and were less cultural minded/religiousness

### Marketing predictions
The final model had an auc_roc score of 0.7478 and a Kaggle score of 0.80027 (https://www.kaggle.com/c/udacity-arvato-identify-customers/leaderboard).

Model | Local score |Kaggle Score
--- | --- | ---
AdaBoost | 0.7431 | 0.79327
XG Boost | 0.7478 | 0.80027

