# predict-housing-prices

### 0. Load Data
The dataset is 1400x16. There are both continious and categorical variables, including missing data.
### 1. Exploratory Data Analysis & Visualizations
Checking the dimentions, getting a glimpse of the data, checking the datatypes, summaries, variables with near-zero variance, unique values, etc.
### 2. Preprocessing
Please see the *Reports* for the details of presroessing decisisons.
### 3. Training Models 
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

### 4. Choose the best model

**Mean Squred Error (MSE)** was used to compare perfomance of the models. 
Lowest MSE was used to choose the best model. RF performed the best.
