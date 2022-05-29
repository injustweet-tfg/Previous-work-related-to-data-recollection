# TFG
In here can be found different kind of files which were used throughout the whole project.


### CODE
Directory which contains all code which was used in the previous stage.

- [instagram](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/tree/master/code/instagram)         Directory with all code regarding the making of the dictionary and the recollection of posts for its evaluation.
    -  [main.py](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/code/instagram/main.py)              File where the dictionary is first created.
    -  [training.py](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/code/instagram/training.py)          Code where the corpus of complaints is made for the later evaluation of the dictionary.
              
- [twitter](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/tree/master/code/twitter)          Directory that contains the first contacts with the Twitter API.
    - [twitter.py](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/code/twitter/twitter.py)            File that given a username gets his tweets and stores them in JSON format.
    - [twitter_training.py](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/code/twitter/twitter_training.py)  File that given a query gets tweets and stores them in JSON format.
- [compare.py](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/code/compare.py)        File that was used to find out which metrics made the algorithm work best.
- [mean_and_median.py](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/code/mean_and_median.py) Code that helps to find out the size of the posts of each corpus to see which was a better fit.


### CORPUS               
Directory with different corpus.
- [IMDB_Dataset_SPANISH.csv](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/corpus/IMDB_Dataset_SPANISH.csv)      Set of film reviews in spanish.
- [hotelsb_df_es.csv](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/corpus/hotelsb_df_es.csv) Set of hotel reviews in spanish.
- [punta_cana.csv](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/corpus/punta_cana.csv) Set of trip reviews to Punta Cana in spanish.


### DICT                 
Directory with each iteration of the dictionary.
- [FRECUENCIES.csv](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/dict/FREQUENCIES.csv)                 First stage of the dictionary obtained from the main.py
- [FRECUENCIES_DIC.csv](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/dict/FRECUENCIES_DIC.csv)            Iteration of the dictionary which is used for the texts classifications.
- [query_dic.csv](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/dict/query_dic.csv)                   Last version of the dictionary which is used as a query (stream and scrape).

### JSON                
Directory that holds every JSON file used.
- [classified_as_negative.json](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/json/classified_as_negative.json)     File made by tweets which the algorithm classified as "not complaints".
- [classified_as_positive.json](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/json/classified_as_positive.json)     File made by tweets which the algorithm classified as "complaints".
- [examples_scrape.json](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/json/examples_scrape.json)            File that keeps every tweet labeled as a complaint by the algorithm.
- [false_negatives.json](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/json/false_negatives.json)            File made by the manual classification of false negatives found at the file "classified_as_negative.json".
- [false_positives.json](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/json/false_positives.json)            File made by the manual classification of false positives found at the file "classified_as_positive.json".
- [not_examples_scrape.json](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/json/not_examples_scrape.json)        File that keeps every tweet that is not labeled as a complaint by the algorithm.
- [prueba.json](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/json/prueba.json)                     Aux file which does the same as "examples_scrape.json"

### TEXT                 
Directory that holds all purpose files.
- [random_tweets.txt](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/text/random_tweets.txt)
- [training.csv](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/text/training.csv)                    Corpus with complaints that is used to evaluate the dictionary.
- [training.txt](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/text/training.txt)
