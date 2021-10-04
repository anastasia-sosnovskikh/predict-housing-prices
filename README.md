# predict-housing-prices

## 0. Load Data
1400x16 dataset, both continious and categorical variables, including missing data
## 1. Exploratory Data Analysis & Visualizations
## 2. Preprocessing
## 3. Training Models 
* **Linear Model (LM)** 
  * LM with *various variables* (3, 7) based on the following selections: **Best Subset** Selection, **Forward Stepwise** Selection, **Backward Stepwise** Selection
  * **Ridge Regression**
  * **Lasso Regression**
  * **Principle Component Regression (PCR)**
  * **Partial Least Squares Regression (PLS)**
  * **Polynomials**
  * **Splines**
* **Tree-based Models**
  * **Trees**
  * **Bagged Tree**
  * **Random Forest**
  * **Boosted Trees**
* **K-Nearest Neighboor (KNN)**

## 4. Choose the best model

**Mean Squred Error (MSE)** was used to compare perfomance of the models. 
Lowest MSE was used to choose the best model. RF performed the best.
