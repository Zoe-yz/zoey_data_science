# **Project: Predicting Boston Housing Prices**

### **Install**

This project requires **Python** and the following Python libraries installed:

*   NumPy
*   Pandas
*   matplotlib
*   scikit-learn
*   seaborn
*   scipy

You will also need to have software installed to run and execute a Jupyter Notebook

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.

### **Code**

The code is provided in the Predict_Boston_House_Prices.ipynb notebook file.

### **Run**

In a terminal or command window, navigate to the top-level project directory ```Predict_Boston_House_Prices/``` (that contains this README) and run one of the following commands:


```
ipython notebook Predict_Boston_House_Prices.ipynb
```

or

```
jupyter notebook boston_housing.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### **Data**

The boston_dataset is loaded from sklearn. The original dataset is the dictionary, so I abstract the data of features and the data of target variable from boston_dataset and form a new dataset named "boston".

**Data Set Characteristics:**  

*   Number of Instances: 506 
*   Number of Attributes: 13 numeric/categorical predictive. Median Value (attribute 14) is usually the target.
*   **Features:**
        * - CRIM:     per capita crime rate by town
        * - ZN:       proportion of residential land zoned for lots over 25,000 sq.ft.
        * - INDUS:    proportion of non-retail business acres per town
        * - CHAS:     Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
        * - NOX:      nitric oxides concentration (parts per 10 million)
        * - RM:       average number of rooms per dwelling
        * - AGE:      proportion of owner-occupied units built prior to 1940
        * - DIS:      weighted distances to five Boston employment centres
        * - RAD:      index of accessibility to radial highways
        * - TAX:      full-value property-tax rate per $10,000
        * - PTRATIO:  pupil-teacher ratio by town
        * - B:        1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
        * - LSTAT:    % lower status of the population

*   **Target Variable:**
        * - MEDV:     Median value of owner-occupied homes in $1000's
