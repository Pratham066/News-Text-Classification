# News-Text-Classification

Overview
What exactly News text classification mean?
News Text classification is also known as text tagging or text categorization. It is a process of categorizing text into different organized groups by using NLP(Natural Language Processing), Text classification can automatically analyze text and then they can assign a set of predefined tags or predefined categories based on its content or based on its textual content. Also in news articles, we have a lot of unstructured data such as recent or current news of either general interest or it contains specific topics (i.e. emails, conversations, information, political or trade news, technology news websites and social media handles). But it is very hard to extract value from this data unless it is organized in a certain way. Doing so in earlier times used to be a difficult task and obviously it was expensive since it requires spending a lot of time and resources to manually sort the data or creating handcraft rules or features which requires a lot of maintenance so as to overcome this we started using  NLP. 
Now, Text classifiers with NLP have proven to be a great alternative to structure textual data in a fast, efficient, cost-effective and scalable way.  Here I have named the problem as BBC News Classification because the data set I have taken is downloaded from the BBC News Channel.  The goal here is to build a system that can accurately classify previously unseen news articles into the right categories. So there are various types of categories and we need to classify each and every news into that particular category or predefined categories. So I will be actually developing the entire end to end solution for this.  

Motivation
The motivation behind building this project was to provide the right data acquisition and data preprocessing by applying traditional Machine Learning algorithms and see how LSTM(Long Short Term Memory), shows how efficiently the news can be categorized into predefined categories.  
Goals
To perform Data cleaning and Data preprocessing to check the quality of the data before applying machine learning or data mining algorithms. 
To provide the best accuracy among all the machine learning models.


Approach 
Abstract
We will be classifying data into different categories based on their data set we have . There are 5 categories of news articles (i.e. Bussiness, Entertainment, Sports, Politics, Tech). The data set i have collected is from Kaggle, which contains news articles including these headlines and categories. 

DATASET
Finding an appropriate dataset can be a difficult task. It can be more difficult if we are looking for a dataset that comprises news heading as a type of data value. Processing and extracting features from an audio file can be a difficult task moreover, here the feature extracted are Data Fields (i.e.  Article ID,Article,Category)  from the data set so that we can use these features directly for processing.  
Data Cleaning and Data Preprocessing 

Data Cleaning : So today we all know that we are dealing with textual data therefore are focus here is to convert or normalize the text/data to lower case and to remove all the gibberish and garbage characters also those words which will not contribute to our model building part these are also known as STOPWORDS in NLP.
Data preprocessing : It is a process of transforming raw data into a understandable format. It is also an important step in data mining as we cannot work with raw data.    

METHODOLOGY 
For removing stopwords i have taken the help of NLTK package in python. The Natural Language Toolkit(NLTK) is a platform used for building Python programs that work with human language data for applying in statistical natural language processing(NLP).  

Hyper Parameter Tuning  
In this project, I have used Hyper parameter Tuning individually on each algorithm , It is an essential aspect of mahine learning process. A good choice of hyperparameters can really make a model succeed in meeting desired metric value or on the contrary it can lead to a unending cycle of continuous training and optimization. 
