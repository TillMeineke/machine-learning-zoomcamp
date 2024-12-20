# 4.8 Summary

<!-- markdownlint-disable MD033 -->
<!-- markdownlint-disable MD045 -->
<a href="https://www.youtube.com/watch?v=-v8XEQ2AHvQ&list=PL3MmuxUbc_hIhxl5Ji8t4O6lPAOpHaCLR"><img src="images/thumbnail-4-08.jpg"></a>

[Slides](https://www.slideshare.net/AlexeyGrigorev/ml-zoomcamp-4-evaluation-metrics-for-classification) empty?

## Notes

General definitions:

* **Metric:** A single number that describes the performance of a model
* **Accuracy:** Fraction of correct answers; sometimes misleading
* **Precision and recall** are less misleading when we have class imbalance
* **ROC Curve:** A way to evaluate the performance at all thresholds; okay to use with imbalance
* **K-Fold CV:** More reliable estimate for performance (mean + std)

In brief, this week was about different metrics to evaluate a binary classifier. These measures included accuracy, confusion table, precision, recall, ROC curves (TPR, FRP, random model, and ideal model), and AUC-ROC. Also, we talked about a different ways to estimate the performance of the model and make the parameter tuning with cross-validation.

The code of this project is available in [this jupyter notebook](./notebook.ipynb).

Add notes from the video (PRs are welcome)

|⚠️|The notes are written by the community.<br>If you see an error here, please create a PR with a fix.|
|---|:-:|

* [Notes from Maximilien Eyengue](https://github.com/maxim-eyengue/Python-Codes/blob/main/ML_Zoomcamp_2024/04_evaluation/Summary_Session_04.md)

## Navigation

* [Machine Learning Zoomcamp course](../)
* [Session 4: Evaluation Metrics for Classification](./)
* Previous: [Cross-Validation](07-cross-validation.md)
* Next: [Explore more](09-explore-more.md)
