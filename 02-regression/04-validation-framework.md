# 2.4 Setting up the validation framework

<!-- markdownlint-disable MD033 -->
<!-- markdownlint-disable MD045 -->
<a href="https://www.youtube.com/watch?v=ck0IfiPaQi0&list=PL3MmuxUbc_hIhxl5Ji8t4O6lPAOpHaCLR&index=15"><img src="images/thumbnail-2-04.jpg"></a>

[Slides](https://www.slideshare.net/AlexeyGrigorev/ml-zoomcamp-2-slides)

## Notes

In general, the dataset is split into three parts: training, validation, and test. For each partition, we need to obtain feature matrices `X` and vectors of targets `y`. First, the size of the partitions is calculated. Next, the records are shuffled to ensure that the values of the three partitions contain non-sequential records from the dataset. Finally, the partitions are created using the shuffled indices.

**Pandas attributes and methods:**

```python
`df.iloc[]` # returns subsets of records of a dataframe, being selected by numerical indices
`df.reset_index()` # restate the original indices
`del df[col]` # eliminates target variable
```

**Numpy methods:**

```python
`np.arange()` # returns an array of numbers
`np.random.shuffle()` # returns a shuffled array
`np.random.seed()` # set a seed
```

The entire code of this project is available in [this jupyter notebook](https://github.com/alexeygrigorev/mlbookcamp-code/blob/master/chapter-02-car-price/02-carprice.ipynb).

<table>
   <tr>
      <td>⚠️</td>
      <td>
         The notes are written by the community. <br>
         If you see an error here, please create a PR with a fix.
      </td>
   </tr>
</table>

* [Notes from Peter Ernicke](https://knowmledge.com/2023/09/19/ml-zoomcamp-2023-machine-learning-for-regression-part-3/)

## Navigation

* [Machine Learning Zoomcamp course](../)
* [Session 2: Machine Learning for Regression](./)
* Previous: [Exploratory data analysis](03-eda.md)
* Next: [Linear regression](05-linear-regression-simple.md)
