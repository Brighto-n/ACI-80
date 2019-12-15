# ACI-80
Kaggle challenge : Adult Census Income
## Full Analysis : Jupyter Notebook
## Python Packages:
- Scikit-learn
- Pandas
- Numpy
- Seaborn
- Matplotlib
##
> - The data
- There are multiple kinds of features :
- The static description
- native country (+ continent)
- race
- sex
- The conjugal situation
- marital status
- relationship
- single
- The educational background (education / education.num)
- The current job informations
- hours worked per week
- capital (can be positive or negative)
- workclass
- occupation
### Total number of records: 32562
### Individuals making more that $50,000: 7841
### Individuals making at most $50,000: 24720
### Percentage of individuals making more than $50,00: 24.080216202935937

## Classification Models Used:
- "LR", Logistic Regression
- "LDA", Linear Discriminant Analysis
- "KNN", KNeighbors Classifier
- "CART", Decision Tree Classifier
- "NB", Gaussian NB
## Result
- LR,0.999912,(0.000175)
- LDA,0.789541,(0.006553)
- KNN,0.752116,(0.011613)
- CART,0.999868,(0.000281)
- NB,0.985960,(0.003249)
