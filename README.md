Music Recommendation System (Group-26)
Problem Statement: To build a music recommendation system that not only considers the popularity of ths songs, user input or interactions but also the song features in order to recommend best songs that perfectly depicts user's taste and interest.

Approach:

Model 1: User-User Collaborative Filtering: Recommends items to a user based on preferences or behavior of similar users. It identifies patterns in user-item interactions (e.g., count) to make recommendations.

Model 2: Matrix Factorization Recommendation system predicts based on user interaction with the item.

Model 3: Content-Based Music Recommendation System Recommendation system will consider music itself which includes textual data like artist information, song title, song name, album which can offer more accurate personalized recommendations to users.

Implementation: Develop a collaborative system and content-based system that recommends similar songs based on artist and user similarity. Utilize techniques such as TF-IDF or Word2Vec for feature extraction. Implement matrix factorization techniques like Singular Value Decomposition (SVD) to factorize the user-song interaction matrix and cosine similarity. Refining the recommendation system based on performance analysis using hyper parameter tuning. Evaluate the performance of the system using evaluation metrics such as accuracy, RMSE.
