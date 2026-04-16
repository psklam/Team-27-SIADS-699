Predicting Pre-Release Financial Success of Movies and Actor "Star Power" Clustering

This project applies both supervised and unsupervised machine learning methods to IMDB data (2000-2025) to predict the pre-release financial success of movies and identify similarities between and the "star power" of actors. These results will synthesized into our overall analysis of how movies, actors, and success has changed over the years.

Using pre-release movie features such as budget, genre, cast as well as many engineered features depicting historical success of specific genres, actors, and genre-actor combinations, we trained several classification models - including a Logistic Regression Classifer, Decision Tree Classifier, Random Forest Classifier, and a Gradient Boosting Classifier - to predict whether or not a movie would be successful. While results showed decent predictive power, performance was significantly lower than we would have expected. Some limitations and issues we ran into included a lack of high signal (and limited ability to engineer) features, some incomplete revenue data points caused by the emergence of streaming platforms, a material shift in the overall success rate of movies between our training, validation, and test sets, and the inherent variance in any one movie success, even for very notable and successful actors. However, we were able to create a useful predictive model that could be used to decide whether or not it would be a good financial decision to move forward with a movie based on a set of pre-release features.

We also performed a clustering analysis to create actor groups which define their success, activity, and prominence in the film industry. Each cluster is defined both qualitatively and quantitatively, both of which are used in our temporal synthesis of the movie industry.

Our goal is to both provide a powerful tool for studios and production companies to use to help evaluate if their decision to book a specific movie is a good one as well as educate our audience on the ever-changing trends in the movie industry and how those changes have influenced overall movie financial success.

Authors: Peter Sklamberg, Evgeny Kuzmin, Benjamin Wilson
Course: University of Michigan - SIADS 699 (Capstone)
