# kaggle_practice
My kaggle notebooks for several competitions (go as-is, no clean-up of the code performed)

SBRE_notebook_2.ipynb

Competition URL:
https://www.kaggle.com/c/sberbank-russian-housing-market

This notebook shows how I approached Sberbank Russian Housing Market competition. The main objective of this competition was to
predict real estate prices for a given test set of objects based on a training set with prices available. 
The notebook is self-contained in regard to analysis performed and has comments and should be relatively easy to follow.


CF_notebook_5_all_stores_kernelPP_1.ipynb (1) 
CF_notebook_3_all_stores_2.ipynb (2)

Competition URL:
https://www.kaggle.com/c/favorita-grocery-sales-forecasting

This is a set of notebooks for another competition which objective was to predict unit sales for a grocery store chain.
A total of 54 stores fall into the range of analysis having approx. 4000 different types of units in sale.
The training set is quite volumnous (5 Gb) and my first attempts were to prepare slices of preprocessed data with later
feeding into regressor.
However, later I've found a very elegant kernel which was much shorter, much faster, did not require any cut of data into slices
but contained some tricks with moving averages that did not seem to be explainable or derivable from anything (like "it just 
worked with similar tasks before").
Here I put a notebook with my first straightforward approach(2) (it has an overfitting drawback which was not obvious to me at first and I guess was a keytakeaway from this competition), as well as short and fast version based on a kernel of another author (1).
