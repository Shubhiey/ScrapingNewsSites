# ScrapingNewsSites

## The Data Set
   The dataset is a csv file containing the following three attributes.
    Id - generated Id for a single row
    Headline - The news headline in text format.
    ChanceOfVirality - The chances of the news going viral
    (Bigger the value of this attribute, Higher the Chances!)

   The data has been obtained by scraping famous news websites in India(Their names are listed Below).
   ##### - Google News
   ##### - Fox News
   ##### - NBC News
   ##### - Google News
   ##### - InShorts
   ##### - Hindustan Times
   ##### - Yahoo News

   The data set has currently 9.8K rows, but it can vary between 9.5K-11K rows based on the content available on these websites at the time you run the python code. This news was collected only on a single day, and you can obviously get more data by running the python code for more number of days and keep appending the data generated.


## The Code

   This data has been created by scraping websites using Pyhon code. The file is a Jupyter notebook and requires Jupuyer to be installed before exexution.
   ### Pre-requisites and Dependencies
   ##### - Beautiful Soup 4
   ##### - Requests
   ##### - lxml
   ##### - Pandas
   To anticipate the virality of a news, the code looks for certain keywords in the headlines which are listed in the google sheet below (The Common words column is not used as they are common to many sentences).
    https://docs.google.com/spreadsheets/d/1lzJ9WBHcpLg4Un_Y6ogXfoQsrJ0oulKYv04NCXxuoSc/edit#gid=8

   ### Important:- This process, to anticipate virality of a news, has been inspired by the blog below.
   https://buffer.com/resources/the-most-popular-words-in-most-viral-headlines

## Note :-
   The code generates a csv file containing the dataset. The contents of the dataset as well as total number of headlines are HIGHLY dependent on the content available on the above mentioned websites at the time of execution of the code.

