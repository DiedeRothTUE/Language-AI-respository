# Language-AI-respository
This is code used to obtain results in our paper for the Language and ai course. The goal is to use an csv file which contains data from Reddit, with the Author_id, a post and the corresponding political leaning (Centre,Right,Left) of the author. The goal is to use natural language processing to predict political leaning given the used tekst. We will also ude sentiment analysis for this. 
Provided is a Jupiter Notebook, where the cells can be run in descending order. It results in a SVM model with the 10 most infleuntial words and logistic regression model for comparison. 
First the libraries will be loaded, then we will define 2 functions which we need for the data. 
