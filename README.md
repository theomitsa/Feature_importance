# Feature_importance
Code for implementing 21 feature importance computation methods. 
NOTES
1.Note that theFeaturewiz and Shapash packages were implemented in a separate Jupyter notebook
and a separate virtual environment that implements an older version of Python (3.7).
At the time of this writing, they were not compatible with Python 3.10.3, which is the Python version used for the remainder of the algorithms.
![image](https://github.com/theomitsa/Feature_importance/assets/48882312/783a65da-33aa-44cc-a54f-eb4795f60c27)
2. Note that it in the pandas get_dummies() method it is best to include drop.first=TRUE to avoid multicollinearity especially for methods sensitive to it such as logistic regression. I did not include it, because my first goal was interpretability and therefore, I wanted to see the contribution of all features.
