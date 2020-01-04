# H1b Visa prediction(accepence or denial) 

## Project description

There are many people are willing to come USA and work. For them H1b visa or work visa is necessery to in USA. Current project is to find top companies that provide H1b visa with maximum acceptence.

## Data collection and EDA

**.** H1b data hasbeen taken from kaggle.

**.** Since data is data base has been created on postgreSQL and desired data set is imported to jupyter note book for further analysis.

**.** Data is cleaned and performed EDA [Project3_dataCleaning.ipynb](http://localhost:8888/notebooks/swarna-DS/Metis/Metis_BC/Challenges/Project3/Project3_dataCleaning.ipynb)

## Analysis

**.** Data is unbalanced accepted to denial category are 97% vs 3% respectively. class denial- 1 and class accceptence - 0 

**.** Applied logistic regression and Random forest and calculated precision, recall and f1 scores. Recall and f1 scores are very low.

**.** Applied  oversampling using SMOTE followed by Random forest it could slightly improve the F1 score.

**.** Applied XGBoost which incresed f1 score slightly but not significant.

## Conclusion

**.** H1b visa denials are higher in small companies butnot in top companies.

**.** Aim of the project is about to find top companies with highest visa approvals  precision score  can be considered as the desired metrics.

**.** Extracted top companies my calculating "feature importance" by "gain".



