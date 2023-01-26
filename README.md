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

	KNN, Logistic Regression, Support Vector Machine, Decision Tree, Bagging DT, Boosting DT, Random Forest Ens



Here you can find the comparisono between ddifferent methods:

<img width="676" alt="image" src="https://user-images.githubusercontent.com/59935915/214961231-af75f137-43fe-429a-9216-b3043037aecb.png">

