# Price Prediction For Cars

### Dataset Description:
- More than 30,000 rows
- 26+ features
- 24% of the data was categorical

### For data prep ▶️ [Data Processing](data_processing.ipynb)
### For ML model ▶️ [ML Model](model.ipynb)


## Data Handling 

### Categorical Features 
- Found patterns using group by
- When no pattern was found, used mode for imputation


### Numerical Features
- Used KNN Imputer to impute values using 3 nearest neighbours

### Encoding 
- Performed encoding through dummies (One hot encoding)

### Selection of Features
- Selected features using correlation matrix
- Kept only 23 columns from 76 columns

![alt text](image.png)

<br/>

## Results
- Decision Tree - MSE: 216047.94700810735, R2: 0.9967441326096554 
- Linear Regression - MSE: 6167293.005773001, R2: 0.9070581856376413
- Random Forest - MSE: 214321.36337854975, R2: 0.9967701524233775