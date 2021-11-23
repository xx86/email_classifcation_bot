# email_classifcation_bot
Bot that manages unmanaged email accounts, alerts when real humans email these inboxes.

history.txt - remembers last emails pulled for each account to avoid double dipping.
clf.joblib - classification model pipeline.
inbox-parser.json - token for gmail api
training_data.ipynb - tool to train and create .joblib pipeline.
trainig_data.csv - training data data for training data.

changelog
11/23/2021
  - Implemented MLP classification neural network instead of Naive Bayes.
  - Runs on schedule.

needs
  - Self-training (possible with Scikit Learn libraries, needs some human supervision)
  - Slack log dump
  - Hosted
