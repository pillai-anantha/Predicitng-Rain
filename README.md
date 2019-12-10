# Predicitng-Rain-Tommorow

# Predicting whether there will be rain the next day in Australia (Python)

# Rain_in_Australia

## Data Preparation

*Read data from 'weatherAUS.csv'

*Drop all rows with NULL and then convert 'Rain Tommorow' and 'Rain Today' varaibles

*Create Train and Test data and then perform feature scaling

## Classification

*Constructed SVC models with linear kernel, polynomial kernel, rbf kernel. Created decision tree and Ada-boost models aswell.

*Used cross validation for evaluating models

*Plotted train and cross-val accuracy against appropriate parameters and created confusion matrixes for all the models

*Constructed learning curves and ROC for all the models

*The SVC model with rbf kernel was the best model with test accuracy of 0.86 (86%) and an AUC of 0.72
