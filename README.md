# BERTweet-MBTI

Training a BERTweet model with a neural network head to classify MBTI type of social media posts.

sub_eda

- Used to separate each user's social media posts into separate samples
- Generates one_post_per_row.csv

one_post_per_row.csv

- Used for training models and data analysis

bertweet_eda.ipynb

- Performs exploratory data analysis and analyzes results of final models

classification_models_1.ipynb

- Designs and trains two types of classification models: 16-way and 4-headed binary
- Calculates initial evaluation metrics for each model
- No pre-existing codebase was used here, but libraries are used extensively
