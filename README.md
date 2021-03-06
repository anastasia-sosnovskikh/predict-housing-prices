# predict-housing-prices

*The project is done in `R`.*

The goal of the project is to build a model to predict housing prices in two markets, Pittsburgh, PA and Richmond, VA, using a scraped data set.  
The delivarables include:

* **Predictions**: a single .csv file with 600 housing prices predictions.
* **Non-Technical Report**: a 1 page long .pdf file that discusses the findings and implications tailored for a non-technical desicion maker.
* **Technical Report**: a 4 pages long .pdf report that outlines the process, the decisions behind certain cleaning and preprocessing choices, model selection, etc. for a technical audience.
* **Code**: an .Rmd file with the code including exploratory data analysis, preprocessing, and models' trainings. 

The metric used for acessing the performance was MSE. Random Forest performed best. 

---

### 0. Load Data
The dataset is 1400x16. There are both continious and categorical variables, including missing data.
### 1. Exploratory Data Analysis & Visualizations
Checking the dimentions, getting a glimpse of the data, checking the datatypes, summaries, variables with near-zero variance, unique values, etc.
### 2. Preprocessing
Please see the *Reports* for the details of preprocessing decisisons.
### 3. Training Models 
* **Linear and Non-Linear Models** 
  * LM with *various variables* (3, 7) based on the following selections:   
    **Best Subset** Selection, **Forward Stepwise** Selection, **Backward Stepwise** Selection
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
