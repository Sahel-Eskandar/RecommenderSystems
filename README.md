# RecommenderSystems
The Project is asking for a user-item recommendation system. It provides us with binary synthetic data for 28 items and 100 users. Data includes liked (a binary label) and x (a covariate value) that reflects users' preferences. A signal has added to raw data so that to be detected and be removed before processing.
After visualizing the user-item-liked matrix, diagonal patterns are detected and removed from the data before any analysis.
To find the item-item relationship, mean-centred cosine is a good starting point. A Cosine similarity measures similarity between two sequences of numbers by looking into the cos⁡〖(θ)〗 of two vectors, A and B. 
 
Item-item summary:
	Normalize user vectors to unit vectors.
	Construct a new item-by-item matrix.
	Compute the cosine similarity between all items in the matrix.
User-item summary:
	Define a neighbourhood of items.
	Calculate the score for all items for a specific user.
	Sort by the n highest scores (most recommended)
Machine Learning Methods: 
	SVD, NMF, SlopeOne, KNNBasic, KNNWithMeans, KNNBaseline, CoClustering, BaselineOnly, NormalPredictor

Attached you can find the Jupyter notebook.

	Model	Train Accuracy	Test Accuracy	Max CrossVal	Timespan
	Boosting DT	0.922465	0.894737	0.880716	0:00:00.044
	Random Forest Ens	0.954274	0.891228	0.880716	0:00:00.072
	Logistic Regression	0.876740	0.880702	0.882704	0:00:00.022
	Bagging DT	0.952286	0.863158	0.890656	0:00:00.040
	Support Vector Machine	0.835785	0.859649	0.852883	0:00:00.004
	KNN	0.881511	0.856140	0.831014	0:00:00.003
	Decision Tree	1.000000	0.831579	0.868787	0:00:00.008

<img width="676" alt="image" src="https://user-images.githubusercontent.com/59935915/214961231-af75f137-43fe-429a-9216-b3043037aecb.png">

