# TFG
Código empleado para diversas funciones auxiliares del proyecto.



### CODE
Directorio con el código empleado

- [instagram](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/tree/master/code/instagram)         Directorio de códigos relacionados con la creación del diccionario y corpus de evaluación
    -  [main.py](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/code/instagram/main.py)              Código con el que se creó el diccionario
    -  [training.py](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/code/instagram/training.py)          Código con el se creó el corpus de denuncias laborales para la determinación de la estadísticas del diccionario
              
- [twitter](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/tree/master/code/twitter)          Directorio de códigos previos que emplean API de twitter
    - [twitter.py](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/code/twitter/twitter.py)            Código que obtiene tweets dado un usuario
    - [twitter_training.py](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/code/twitter/twitter_training.py)  Código que obtiene tweets en base a un consulta
- [compare.py](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/code/compare.py)        Código para la obtención de las métricas del diccionario
- [mean_and_median.py](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/code/mean_and_median.py) Código para la evaluación de longitudes de texto de corpus


### CORPUS               
Directorio con corpus
- [IMDB_Dataset_SPANISH.csv](https://github.com/injustweet-tfg/Previous-work-related-to-data-recollection/blob/master/corpus/IMDB_Dataset_SPANISH.csv)      Corpus de reviews de películas en español

### DICT                 
Directorio con los diccionarios de todas las iteraciones
- FRECUENCIES.csv                 Diccionario original obtenido a partir del código main.py
- FRECUENCIES_DIC.csv             Diccionario empleado para la clasificación de textos
- query_dic.csv                   Porción del diccionario FRECUENCIES_DIC.csv para consultas de datos (stream y scrape)

### JSON                
Directorio con todos los archivos json utilizados
- classified_as_negative.json     Fichero formado por tweets que el algoritmo ha clasificado como negativos o "no denuncias"
- classified_as_positive.json     Fichero formado por tweets que el algoritmo ha clasificado como positivos o "denuncias"
- examples_scrape.json            Fichero donde se almacenan todos los tweets recogidos por el algoritmo que clasifica como denuncias
- false_negatives.json            Fichero formado por la clasificación manual de falsos negativos encontrados en "classified_as_negative.json"
- false_positives.json            Fichero formado por la clasificación manual de falsos positivos encontrados en "classified_as_positive.json"
- not_examples_scrape.json        Fichero donde se almacenan todos los tweets recogidos por el algoritmo que clasifica como no denuncias
- prueba.json                     Fichero auxiliar que tiene la misma función que "examples_scrape.json"

### TEXT                 
Directorio con archivos de distintos propósitos auxiliares a los códigos usados
- random_tweets.txt
- training.csv                    Corpus con textos de denuncias laborales para evaluación del diccionario
- training.txt
