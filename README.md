# BERTweet-MBTI

Training a BERTweet model with a feedforward neural network head to classify MBTI type of social media posts.
No pre-existing codebase was used in this repository, but libraries were used extensively.

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

betweet_MBTI_a.ipynb

- Very similar to classification_models_1.ipynb, but tests different hyperparameters
