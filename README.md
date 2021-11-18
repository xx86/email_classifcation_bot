# email_classifcation_bot
Bot that manages unmanaged email accounts, alerts when real humans email these inboxes.

Need to look into hosting.
Need to put on timed loop.
Need to tweak classification model to reflect business questions.

history.txt - remembers last emails pulled for each account to avoid double dipping.
clf.joblib - classification model pipeline.
inbox-parser.json - token for gmail api
training_data.ipynb - tool to train and create .joblib pipeline. 
