# Prediction-of-Influence-Scores-of-Scientific-Journals_R-Project
A machine learning model is used to predict the influence scores of scientific journals based on previous records from many journals.

## Objective:
Preparing a dataset for a machine learning project will require predicting the influence scores of scientific journals (regression problem), building different models, and comparing their performance using RMSE values.

## Dataset Description:
The dataset contains information about scientific journals and publishers. The data comes from different sources, including researchers, web scraping and the publishers themselves. It comprises three different files: api_journal11-13-17.csv, api_price11-13-17.csv and estimated-article-influence-scores-2015.csv. Some variables include the ISSN, Journal title, subscription price, number of citations and number of published papers, among others. The output variable is the projected article influence, which can be interpreted as the expected influence of an article published by a given journal.

## Data Files:
# File 1: api_journal11-13-17.csv
1. Issn: The International Standard Serial Number of the publication.
2. Journal-name: The name of the scientific journal.
3. Pub_name: The name of the publisher.
4. Is_hybrid: Electronic and printed versions of journal (1); only electronic version of journal (0).
5. category: The category or scientific field of the journal.
6. url: The web page address of the journal.
   
# File 2: api_price11-13-17.csv
1. id: Observation id.
2. price: The subscription’s price.
3. date_stamp: The date in which in the information was collected.
4. Journal_id: The International Standard Serial Number of the publication.
5. Influence_id: The influence Id.
6. url: The web page address of the journal.
7. license: Rights for publication, distribution, and use of research.

# File 3: estimated-article-influence-scores-201.csv
1. Journal_name: The name of the scientific journal.
2. issn: The International Standard Serial Number of the publication.
3. Citation_count_sum: The total number of citations of journal.
4. Paper_count_sum: The total number of papers published by the journal.
5. Avg_cites_per_paper: The average number of citations per paper.
6. Proj_ai: The projected article influence. The higher the influence, the better the scientific credibility of the journal.
7. Proj_ai_year: The year of projected article influence.

## Compiled Prediction_Models.Rmd file:
1. Prediction_Models_ Slidy_Presentation.
2. Prediction_Models_HTML_Document.
3. Prediction_Models_PDF.

## Data source:
Flourish OA dataset

