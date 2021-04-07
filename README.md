# COVID19 fakenews detection using NLP

One of the sharde tasks of CONSTRAINT 2021's first Workshop on Combating Online Hostile Posts in Regional Languages during Emergency Si​tuation, was about  "*Fighting an Infodemic: COVID-19 Fake News*". Here is my modest participation at the Codalab's competition [COVID19 Fake News Detection in English](https://competitions.codalab.org/competitions/26655#learn_the_details)

The [Fighting an Infodemic: COVID-19 Fake News Dataset](https://arxiv.org/abs/2011.03327) contains tweets along with their associated binary labels: `real` for real/verified COVID19 related informations and `fake` for hoaxes/fake news. 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sithlord-dev/COVID19_fakenews_detection_using_NLP/blob/main/Covid19_fakenews_detection_using_NLP.ipynb)

I used Logistic regression with some fine tunning to achieved an accuracy of 94% with the following score: 

|              |   precision |   recall |   f1-score |     support |
|:-------------|------------:|---------:|-----------:|------------:|
| Fake         |    0.939303 | 0.92549  |   0.932346 | 1020        |
| Real         |    0.93304  | 0.945536 |   0.939246 | 1120        |
| accuracy     |    0.935981 | 0.935981 |   0.935981 |    0.935981 |
| macro avg    |    0.936172 | 0.935513 |   0.935796 | 2140        |
| weighted avg |    0.936025 | 0.935981 |   0.935957 | 2140        |


Source: [COVID19 Fake News Detection in English](https://competitions.codalab.org/competitions/26655#learn_the_details)
