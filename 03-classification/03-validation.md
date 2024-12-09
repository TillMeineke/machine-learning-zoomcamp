# 3.3 Setting up the validation framework

<<<<<<< HEAD
<!-- markdownlint-disable MD033 -->
<!-- markdownlint-disable MD045 -->
<a href="https://www.youtube.com/watch?v=_lwz34sOnSE&list=PL3MmuxUbc_hIhxl5Ji8t4O6lPAOpHaCLR"><img src="images/thumbnail-3-03.jpg"></a>

=======
>>>>>>> 3387f3e (Patch 4 (#12))
[Slides](https://www.slideshare.net/AlexeyGrigorev/ml-zoomcamp-3-machine-learning-for-classification) empty?

## Notes

Splitting the dataset with **Scikit-Learn**.

**Classes, functions, and methods:**

```python
train_test_split # Scikit-Learn class for splitting dataset into two parts. The `test_size` argument states how large the test set should be. The `random_state` argument set a random seed for reproducibility purposes.

df.reset_index(drop=True) # reset the indices of a dataframe and delete the previous ones.
df.x.values # extract the values from x series
del df['x'] # delete x series from a dataframe
```

The entire code of this project is available in [this jupyter notebook](https://github.com/alexeygrigorev/mlbookcamp-code/blob/master/chapter-03-churn-prediction/03-churn.ipynb).

|⚠️|The notes are written by the community.<br>If you see an error here, please create a PR with a fix.|
|---|:-:|

* [Notes from Peter Ernicke](https://knowmledge.com/2023/09/27/ml-zoomcamp-2023-machine-learning-for-classification-part-3/)

## Navigation

* [Machine Learning Zoomcamp course](../)
* [Session 3: Machine Learning for Classification](./)
* Previous: [Data preparation](02-data-preparation.md)
* Next: [EDA](04-eda.md)
