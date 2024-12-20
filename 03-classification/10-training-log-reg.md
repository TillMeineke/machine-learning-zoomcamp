
# 3.10 Training logistic regression with Scikit-Learn

<!-- markdownlint-disable MD033 -->
<!-- markdownlint-disable MD045 -->
<a href="https://www.youtube.com/watch?v=hae_jXe2fN0&list=PL3MmuxUbc_hIhxl5Ji8t4O6lPAOpHaCLR"><img src="images/thumbnail-3-10.jpg"></a>

[Slides](https://www.slideshare.net/AlexeyGrigorev/ml-zoomcamp-3-machine-learning-for-classification) empty?

## Notes

This video was about training a logistic regression model with Scikit-Learn, applying it to the validation dataset, and calculating its accuracy.

**Classes, functions, and methods:**

```python
LogisticRegression().fit_transform(x) # Scikit-Learn class for calculating the logistic regression model.

LogisticRegression().coef_[0] # returns the coefficients or weights of the LR model

LogisticRegression().intercept_[0] # returns the bias or intercept of the LR model

LogisticRegression().predict[x] # make predictions on the x dataset

LogisticRegression().predict_proba[x] # make predictions on the x dataset, and returns two columns
# with their probabilities for the two categories - soft predictions
```

The entire code of this project is available in [this jupyter notebook](https://github.com/alexeygrigorev/mlbookcamp-code/blob/master/chapter-03-churn-prediction/03-churn.ipynb).

<table>
   <tr>
      <td>⚠️</td>
      <td>
         The notes are written by the community. <br>
         If you see an error here, please create a PR with a fix.
      </td>
   </tr>
</table>

* [Notes from Peter Ernicke](https://knowmledge.com/2023/09/30/ml-zoomcamp-2023-machine-learning-for-classification-part-10/)

## Navigation

* [Machine Learning Zoomcamp course](../)
* [Session 3: Machine Learning for Classification](./)
* Previous: [Logistic regression](09-logistic-regression.md)
* Next: [Model interpretation](11-log-reg-interpretation.md)
