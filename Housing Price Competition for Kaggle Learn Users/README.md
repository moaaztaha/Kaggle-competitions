# Housing-Price-Competition-for-Kaggle-Learn-Users

## Imutation&Median

- [x] Use Only Numerical data
- [x] deal with missing data
    - [x] Imputation
- [x] Submit 

___

## One-hot Encode

- [x] Libraries
- [x] Load data
- [x] Remove columns with the most missing values
- [x] Categorical data -> One-Hot Encoded
- [x] Imputation
    - [x] Numerical -> Median
- [x] Save the model
- [x] Preprocess the Test set
- [x] Submit if you got better results

##### Old score
- MAE:  17807.438333333328
- RMSE 33919.31112490001

#### Current score
- MAE: 17492.58344748858
- RMSE: 33657.29332096441

___

## Pipelines

- [x] Use Pipelines with low cardinality 
- [x] Use Pipelines with all categorical features

* MAE: 17741.26297945205

___

## Pipelines_less_missing

- [x] Remove columns with too many missing values
- [x] Use Pipelines

* MAE: 17609.825650684932
* Kaggle score: 16347.22769

---

## Pipelines without missing categorical columns

- [x] Remove categorical with missing value
- Better results on train.csv but slightly worse on test.csv
- MAE: 17523.535102739726
- Kaggle score: 16356.22338

---

## Cross-validation 

- [x] cross-validation

- [x] Visualize the results

#### Cross-validation with less missing features and 250 estimators
- MAE: 17448.4844109589
- Kaggle score: 16373.11794

#### Cross-validation with all the data and 300 estimators
- MAE: 17479.838664383562
- Kaggle score: 16423.34155

---

## XGBoost with low-cardinality & less missing categorical columns

- [x] Remove categorical features with high cardinality
- [x] Check the number of missing values
- [x] Cross-validation
- [x] Use it with less missing categorical columns
#### With low cardinality
- CV MAE: 16476.5398727939
- Kaggle score: 15017.66000
#### With less missing categorical columns
- CV MAE: 16272.231832972175
- Kaggle score: 14984.44846