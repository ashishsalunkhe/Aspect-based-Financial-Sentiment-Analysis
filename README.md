# Aspect-based-Financial-Sentiment-Analysis
Aspect based sentiment analysis aims to detect an aspect (i.e. features) in a given text and then perform sentiment analysis of the text with respect to that aspect. This project aims to give a solution for the FiQA 2018 challenge subtask 1. <br>

Given a text instance in the financial domain (microblog message, news statement or headline) in English, detect the target aspects which are mentioned in the text (from a pre-defined list of aspect classes) and predict the sentiment score for each of the mentioned targets. Sentiment scores will be defined using continuous numeric values ranged from -1(negative) to 1(positive). <br>

Model is evaluated on the basis of precision, recall and F1-score for aspect classification approaches and regard to MSE and R Squared(R^2) metrics for sentiment prediction. <br>

An example of the input/output of the task is defined below: <br>

"55": { 

    "sentence": "Tesco Abandons Video-Streaming Ambitions in Blinkbox Sale", 

    "info": [ 

      { 

        "snippets": "['Video-Streaming Ambitions']", 

        "target": "Blinkbox", 

        "sentiment_score": "-0.195", 

        "aspects": "['Corporate/Stategy']" 

      }, 

      { 

        "snippets": "['Tesco Abandons Video-Streaming Ambitions ']", 

        "target": "Tesco", 

        "sentiment_score": "-0.335", 

        "aspects": "['Corporate/Stategy']" 

      } 

    ] 

  } 
