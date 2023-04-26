# CIS530FinalProject
We investigate whether machine learning classification
algorithms suffer a decrease in performance when
classifying text summaries as opposed to the original
raw text. Using a data set of Reddit Posts
(with their abstractive summaries), we create extractive
summaries using BART, and apply popular M.L.
algorithms. The results show that, on average, the performance
of the algorithms was slightly worse when
classifying the extractive summaries compared to the
raw text. However, the decrease in performance was
not significant and did not affect the overall accuracy
of the algorithms. Abstractive summaries did not yield
equally satisfying results. This suggests that using
extractive summaries as input for classification algorithms
can be an effective way to reduce the amount
of data without sacrificing performance.


Load the Jupyter notebook and make sure in the same directory you find our data ‘reddit_w_extr_summ.csv’.

Run all the set up cells to ensure all packages are imported
Run the cells in subsections summarization, classification
Under Main, run the classification comparison cells I. If you want to change the golden labels y you can do so by changing the variable y. II. If you want to change the data to classify you can do so by changing the variable summary_pred III. Run the classification comparison cells to get results
The output of running the classification comparison cells with output.csv

using y = output.gold_labels

summary_pred = output.predicted

-------- Classification on extractive summary using RF & count embeddings----------------

Completed in 0.5343027114868164 seconds

acc 0.860324

F1 0.860145

roc_auc 0.926109

[[1851 509]

[ 68 1703]]
