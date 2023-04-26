Load the Jupyter notebook and make sure in the same directory you find our data ‘reddit_w_extr_summ.csv’.

1. Run all the set up cells to ensure all packages are imported
2. Run the cells in subsections summarization, classification
3. Under Main, run the classification comparison cells
    I. If you want to change the golden labels y you can do so by changing the variable y.
    II. If you want to change the data to classify you can do so by changing the variable summary_pred
    III. Run the classification comparison cells to get results
    
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