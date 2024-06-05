# Housing_Problem

-> It is an Advanced Regression problem and a Kaggle Competition for those who want to polish their Data Science Pipeline.

### Data Set:
Here is the attached link to the dataset, you can just download it from here: [Dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)
-> You can skim the dataset page and get a high-level idea of the dataset's features and the problem's shape.

### Solution:

1) First I understand the data by looking into its feature types, there were more than two feature types in the dataset.
2) After that, I started looking at the basic points of the dataset, like using the describe() method to find out any np.nan values, to find out the no of data points total
in the dataset, it will show you a rough estimate of the outliers in the dataset so you can tackle them.
3) Then I preprocessed the dataset by handling the np.nan values, removing the outliers, and checking relationships between different features of the dataset. Point 3 has an in-depth analysis performed in the notebook that I attached, so look into that.
5) At Last, I split the dataset and used the XGBoost Model for training. I also used other tree-based models for this problem but XGBoost works much better on this. 
