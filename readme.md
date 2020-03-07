# Machine Learning — Hatespeech Detection/Prediction
## Most Current status file: **toxiccomments_first_full_iteration_b.ipynb**

Process: I am currently focusing on the Ridge Regression Classifier as well as the Random Forest Classifier as the most promising Algorythms to use for a Hatespeech Detection/Prediction of Wikipedia comments. As new features I introduced an exclamation count Features, as well as an UpperCase Count Feature (although this Feature is not working at the moment, as it is adding the total count to each row, instead of the count of each single row).\
In the ridge regression I introduced the normalizer=true which slightly improves the result. For the random Classifier I  increased the max width.\
At this point of the process my assumption is, that the algorithms are overfitting while working with the training data (with a result of 98 accuracy). 