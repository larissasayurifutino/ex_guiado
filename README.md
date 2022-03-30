# vozdelas

## About

A real-time monitoring project that shows how many women are interviewed and determines where they need more space in the news.

## Main aim

This project aims:

1. to recognize person entities in journalists texts from [Folha](https://www1.folha.uol.com.br) website, 
2. to classify these entitites by gender, 
3. to quantify the percentage of quotes that were given by women by journalist and editorial branch (next steps) and
4. to suggest female references by topic domain

Secondary aims:

5. to recognize person entities locations in journalists texts from [Folha](https://www1.folha.uol.com.br) website


## How to use it

### To read data

Considering a JSON file run: 02_clean_data.py

### To recognize Person entities and to assign each of them to a gender

Run: 03_entity_recog.py

### To take metrics related to the entities gender

Run: 04_metrics.py

### To visualize the metrics

Run: VIS/metrics.R and VIS/dash.Rmd


## Details

The entity recognition step uses a trained model in Portuguese available at *spacy* library based on the references:

* [https://monkeylearn.com/blog/named-entity-recognition/](https://monkeylearn.com/blog/named-entity-recognition/)


* [https://spacy.io/usage/linguistic-features#tokenization](https://spacy.io/usage/linguistic-features#tokenization)


## Data

* The gender recognition step uses data from brazilian names available at: [https://brasil.io/dataset/genero-nomes/nomes/](https://brasil.io/dataset/genero-nomes/nomes/).



## To do

Develop a version that scraps news texts: 01_webscrap_newspage.py.

## Last update

February 07, 2022


## Author

Larissa Sayuri Futino Castro dos Santos

## Acknowledment

Many thanks to [@rhhernandes](https://github.com/rhhernandes) who shares his knowledge, dream and data for this project.

