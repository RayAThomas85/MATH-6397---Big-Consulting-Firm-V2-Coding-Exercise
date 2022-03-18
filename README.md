# MATH-6397---Big-Consulting-Firm-V2-Coding-Exercise

#First Exercise (Clustering):
Data Challenge Case Study

Background:
You own an E-commerce store that has flourished since its inception, but in the past few years, revenues have remained stagnant and increased spending on advertisements have not yielded expected results. Through membership applications, you have a database of customers with basic demographic and spending information. Additionally, you also have total spending for each customer (in USD).
Problem Statement:

You would like to inform the marketing team on how they should target their customers for their advertisements. You would like to use customer segmentation techniques to find different segments (clusters) of customers to fine-tune the service you offer your customers to better suit their needs. Please document your work clearly using either python or R for your analysis. You should submit your work in a notebook or a Markdown. Please include the following in your analysis:

A.	EDA (Exploratory Data Analysis) 
B.	Clustering technique of your choice (K-means, Hierarchal Clustering, etc.) to identify unique customer segments of data. Please utilize visualizations to make it clear how the resulting segments can inform the marketing team (Age Group, Gender, Interests, etc.)

The dataset can be found here:
\\Customer_Data.csv

 
Columns:
•	Index: Unique Customer ID
•	Gender: Male/Female	
•	Age: Customer Age
•	Annual Income: Customer’s Annual Income ($1000 USD)
•	Total Spending: Total Spending (USD) over lifetime per customer
•	Interests: Customer’s primary interest/hobbies (e.g. hiking, camping)



#Second Exercise (Using NLP to Classify Article Category):
Task Description 

1 Overview 

In this task, you will apply the machine learning techniques to a real-world dataset. Academia and training courses focus on applying a specific algorithm to carefully preprocessed toy datasets. This task will require that you make decisions such as which classifier to use, which features to use, how to train the classifier, etc. You will find that real world datasets are more difficult to work with, and that careful tuning is required to get optimal performance. 

2 Dataset 
In this project you will work with a labeled dataset of news articles. 

•	Each instance in the dataset consists of the text of a New York Times article published between 2000 and 2003. Each article comes from one of four newspaper sections: News, Classifieds, Opinion, and Features. This dataset has been culled from the Linguistic Data Consortium's New York Times Annotated Corpus. 
•	For your convenience the text has been slightly preprocessed: punctuation and formatting (such as paragraphs) have been removed, and all characters have been converted to lower case. 
•	The articles are stored in data train.txt and data valid.txt. Each line in the file is a single article. Each article consists of a space-separated list of words. 
•	The labels (the sections the articles came from) are stored in the labels train.txt and labels valid.txt. 
•	Each line in the file is a single label. The nth line in the labels train.txt file contains the label for the article stored on the nth line of the data train.txt file. 
•	The labels are numerical to make it easier to use them, but we have also provided the original text labels in labels train original.txt and labels test original.txt. The mapping is: 

- News: 0 
- Opinion: 1 
- Classifieds: 2 
- Features: 3 

YOUR TASK is to write a classifier which can correctly predict the label of a given article. You will need to implement some more sophisticated methods of feature generation, classification, or both. For instance, you might experiment with various techniques to combat over fitting, or you might use a dimensionality reduction technique to generate better features. 

3 Deliverables 
Create a document that describes how you solved the problem. It should contain detailed discussion about which methods you tried, results on their comparative performance, and a discussion about which methods worked best and why. It should follow the following simple outline: Introduction,
Suggested Techniques 
A few classification techniques you may want to review/investigate: 
	1. Logistic regression 
	2. Neural networks 
	3. k-nearest neighbors 
	4. Support vector machines 
A few techniques for generating features that you may want to investigate: 
	1. Dimensionality reduction 
	2. The “bag of words" model 
	3. n-gram models (including smoothing techniques) 
	4. Other kinds of vector space models (see http://www.jair.org/media/2934/live-2934-4846-jair.pdf for several types of such models) 
	5. TF-IDF
