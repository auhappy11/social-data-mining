# Sentiment Analysis on Outbreak of Covid-19 in USA and its Changes over time

The project was done as submission for the course ILS-Z 639. The individual project explores on the changes in public's sentiment over time regarding Covid-19 outbreak.
The keyword "quarantine" was chosen to focus and the analyzed tweets from first 6 months after the outbreak.
The following research question was proposed to conduct the study:
* How does public's sentiment change towards "quarantine" between the start of Covid-19 and after six months of the outbreak?

Tweets only written in English were collected and duplicates were deleted.

Under data folder, there are 6 csv files, which has data for each month from March to August.
Train dataset was downloaded from Sentiment140. The csv file can be found online. The dataset glove.twitter.27B.200d was used to pretrained embedding document, which can also be downloaded from online.

Under code folder, there are 2 ipynb files:
1. DataExtraction.ipynb is used for data collection using snscrape package and saving the files as csv format.
2. sentimentAnalysis.ipynb is used to perform sentiment analysis using LSTM. It includes appropriate preprocessing and labelling process.
