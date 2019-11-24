# Movie-recommendation-system
This is a movie-recommendation project that makes use of model based item-item collaborative filtering algorithm. It takes the title of your favourite movie and outputs a list of recommendations alongwith a similarity measure of the recommendation with respect to your favourite movie (distance of the recommended movie from your favourite movie). It has been developed in stages. In the first stage, a readily available dataset was used to train the model. In the second stage, a datadet was developed by scraping web pages off popular movie reviews site imdb. This was done so as to make latest recommendations and the project more suitable for real-time application. In the third stage, an effort was made to personalise the recommendations further by considering an input that better describes people's view than ratings. It made use of reviews. It made use of scraped reviews by analysing the sentiment(at various degrees) of the reviews. And then the output of this analysis was fed to the model to train it. 

project_practice.ipynb : First stage project where model was built and also consists of exploratory analysis and cleaning of the data.

project_for_webscrape.ipynb : Project that takes scraped data as input.

project_for_reviews.ipynb : Project that takes reviews as input

scrape_data.ipynb : Code to scrape all the required data.

review_processing.ipynb : Code to analyse reviews and score it based on its sentiment.

Rest of the .csv files consist of the scraped data and the readily available dataset that was used. The .txt files were used for processing reviews.
