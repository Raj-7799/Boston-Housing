## Project: Predicting Boston Housing Prices

### Install

This project requires **Python 2.7**(if you complete this project in Python 3.x, you will have to update the code in various places including all relevant print statements) and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

### Run

In a terminal or command window, navigate to the top-level project directory `boston_housing/` (that contains this README) and run one of the following commands:

```bash
ipython notebook boston_housing.ipynb
```  
or
```bash
jupyter notebook boston_housing.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

The modified Boston housing dataset consists of 489 data points, with each datapoint having 3 features. This dataset is a modified version of the Boston Housing dataset found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Housing).

**Features**
1.  `RM`: average number of rooms per dwelling
2. `LSTAT`: percentage of population considered lower status
3. `PTRATIO`: pupil-teacher ratio by town

**Target Variable**
4. `MEDV`: median value of owner-occupied homes

#### Data Distribution
![Data Distribution](/images/data_distribution.png)


#### Performance of Decision trees 
![Decision tree performance](/images/decision_tree_performance.png)

#### Performance Comparision v/s depth
![Performance Comparision](/images/performance_comparision.png)
