# Urdu Corpus for Fake News Detection Task

The Urdu Fake News Corpus contains a collection of news collected from different resources on the Web: established newspapers websites, media companies’ websites, special websites. Fake news was written by different journalists. The news were collected from time period January 2018 to December 2018. All the news were written in Urdu. The process of tagging the corpus was manually performed and the method followed is described in the paper. 

The corpus contains 900 news divided into 500 real news and 400 fake news. The corpus covers news from 5 different topics (domains): 


<p><em><strong>News Catogaries</strong> </em>:</p>
<ul>
<li>Sports</li>
<li>Entertainment</li>
<li>Technology</li>
<li>Business</li>
<li>Health/li>
</ul>

The corpus was split into train and test sets, using around the 70% of the corpus for train and the rest for test. We performed a hierarchical distribution of the corpus, i.e., all the categories keep the 70%-30% ratio.

The corpus is concentrated in the files train.xlsx and test.xlsx. The meaning of the columns is described next:

. Category: indicates the category of the news (true or fake).
. Topic: indicates the topic related to the news.
. Source: indicates the name of the source.
. Headline: contains the headline of the news.
. Text: contains the raw text of the news.
. Link: contains the URL of the source.
. If you use the corpus please cite the following article:

## Authors of the corpus
Juan Manuel Ramírez Cruz (ESIME Zacatenco - IPN), Silvia Úrsula Palacios Alvarado (ESIME Zacatenco - IPN), Karime Elena Franca Tapia (ESIME Zacatenco - IPN), Juan Pablo Francisco Posadas Durán (ESIME Zacatenco - IPN), Helena Montserrat Gómez Adorno (IIMAS - UNAM), Dr. Grigori Sidorov (CIC - IPN)

## Aknowledgments
The work was done with partial support of Red Temática de Tecnologías del Lenguaje, CONACYT project 240844 and SIP-IPN projects 20181849 and 20171813
