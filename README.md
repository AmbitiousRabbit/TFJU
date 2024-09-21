# The Film Junky Union

The Film Junky Union, a new edgy community for classic movie enthusiasts, is developing a system for filtering and categorizing movie reviews. The goal is to train a model to automatically detect negative reviews. You'll be using a dataset of IMBD movie reviews with polarity labelling to build a model for classifying positive and negative reviews.

# Project description of the dataset
  * `review`: the review text
  * `pos`: the numerical identity of the reviews' sentiment, '0' for negative and '1' for positive
  * `sp`: the categorical identity of the reviews' sentiment
  * `ds_part`: 'train'/'test' for the train/test part of dataset, correspondingly
  * `title_type`: this indicates if its a full- or short- length movie
  * `primary_title`: the movie title may have different variations in different languages
  * `original_title`: the original final production title
  * `start_year`: this is the release date of the movie
  * `end_year`: this is the ending date of the movie if its part of a series
  * `runtime_minutes`: the total length of the movie in minutes
  * `is_adult`: whether or not a film is adult rated
  * `genres`: the film categories the movie falls into 
  * `average_rating`: the average IMBD rating
  * `votes`: the total number of votes the movie has acquired on the site


# Project Process

## Step 1 | Access & Study the data
* Open and skim to become familiarize with the data
## Step 2 | Prepare the data
* Convert the data to the necessary types
* Find & Eliminate errors in the data
## Step 3 | Analyze the data
* Conduct EDA & SDA while exercising the 5 analytic frameworks (if applicable):
  * What happened? - Descriptive 
  * Why did it happen? - Diagnostic 
  * What will happen? - Predictive
  * How can we make it happen? - Prescriptive
## Step 4 | Build a Sentiment Analysis model 
* Consider and select an algorithm that is useful to analyze the wording and context based on the users' film review that can pinpoint a positive or negative review.
## Step 5 | General Conclusion
* State found insights in a clear, concise manner.
