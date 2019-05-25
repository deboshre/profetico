Profetico
https://profetico.ml/#!/
An online prediction system which learns on historical data and predicts events for the next required dates.

Data Collection
These are the codes used for data collection:
ACLED (manual download)
GDELT 
First, manual download
Extracting data from links : GDELT Data Extraction.ipynb
Twitter
Tweet_Archive_API.ipynb : For collecting twitter archive data
tweet_collection.ipynb: For collecting twitter streaming data

Filtering the data related to election
Filter 90 days prior data manually
Use filter.ipynb to check for election keyword threshold.

Data Merge and Feature Extraction
First, the data is merged manually.
Use Data Processing and Feature Extraction.ipynb to extract features using Google NLP. 
Word2vec conversion: word2vec.ipynb
Feature Selection: svm.ipynb
Prediction: 
Indonesia_Phased_LSTM.ipynb
India_Phased_LSTM.ipynb
Thailand_PhasedLSTM.ipynb
Front end: front_end folder contains all the files used for creating the website.
Evaluation: evaluation.ipynb
JSON dump: To dump the json files created by the prediction models for the front-end code : Jsondump.ipynb
