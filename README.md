# Plagiarism-Detector-Web-application-using-NLP-and-Machine-Learning
Created an End to End NLP and machine learning based project using Python and Flask


![Plagiarism](https://github.com/user-attachments/assets/0d6261ed-0268-4a71-9674-df528b349945)


## Introduction
Plagiarism is an act of fraud. It basically means using someone else’s words or ideas without giving them proper credit. It is not in itself a crime but can constitute copyright infringement, that's why it's a serious ethical offense. 

                    
Now, it is generally difficult to detect plagiarism, but by leveraging machine learning techniques and NLP, we can create a robust plagiarism detector that can accurately identify copied content. This project walks you through the process of building a plagiarism detector from collecting the dataset to creating a Flask web application for easy use.
There are few available websites which can detect/catch plagiarism. Few of them are www.ithentical.com, www.turnitin.com, www.plagiarism.org, etc.

## Collecting the Dataset
The first step in developing a plagiarism detector is to obtain a comprehensive dataset. This dataset needs to consist of text documents containing both original and plagiarized content. These datasets can be obtained from online sources like Kaggle, or created by collecting documents manually.

I have already uploaded the dataset to my repository.

Here, I am using a hypothetical dataset that contains pairs of text where each pair includes one original document and one plagiarized version. This dataset will be used to train our machine learning model to differentiate between original and copied content.

## Data Preprocessing
Before feeding the data into the machine learning model, it’s important to preprocess it. 

Preprocessing steps includes:

*Tokenization:* Splitting the text into individual words or tokens.

*Lowercasing:* Converting all text to lowercase to ensure the uniformity.

*Removing Punctuation:* Eliminating punctuation marks to avoid treating them as words.

*Stopwords Removal:* Removing common words like "and", "the", etc., that do not contribute to the meaning of the text.


## Building the Machine Learning Model
I have utilized the “Term Frequency-Inverse Document Frequency” (TF-IDF) vectorizer to convert the text data into numerical features. Subsequently, I have employed these features to train the model. Specifically, I have utilized a logistic regression model in this instance.

## Creating the Flask Web Application
To make our plagiarism detector easily accessible, I have developed a Flask web application. Users can input two text documents into the application and receive a plagiarism score through a user interface.



