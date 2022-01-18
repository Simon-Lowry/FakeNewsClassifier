# Fake News Classifier

This application was created as my final project for a course in Tech University Dublin on the Foundations and Artificial Intelligence. The project was done in Python and Jupiter Notebooks and made use of libraries such as Sklearn, Pandas, Spacy, re (regular expression), Matplotlib and the time library as well. The result of the project and my final grade was 73%. The repo contains three documents from this submission:
- The Project Iniation Document
- The Project Development Solution (which includes the code)
- Jupyter Notebook with coded solution

The remainder of this readme is some sample text from the Project Iniatiation Document.

The proposed idea is to try out a number of different classifier models and determine which approach produces the best results for classifying fake news. The data will undergo various manipulations and Natural Language Processing techniques to get into condition for the models to be applied.  The models that will be applied are Naive Bayes, Support Vector Machines, Random Forest algorithms.  ascertain the most effective model for determining fake news amongst these. 

## Data analysis
During this stage I’ll be looking to get a sense of the dataset and it’s properties with performing some data analysis.
This will help to summarize some of the main characteristics of the dataset, uncover some details about it and gain a
better understanding of the dataset overall. This will be done using a combination of using libraries such as pandas
and matplotlib or tableau for producing some visualizations.

## Data Cleaning and Preprocessing
After gaining more insight into the data set there will then be a data cleaning and preprocessing stage. During this
stage, the data will undergo a number of procedures in order to change into a format that allows for the models to
obtain greater performance. This will involve applying methods to deal with missing data, removing any
unnecessary special character, as well as punctuation marks, removing urls, removing double spaces & line breaks.
There will also be the removal of stopwords, which are commonly occurring words within a given language which
don’t actually provide any additional meaning such as ‘a’ or ‘the’. The data will then be changed into lower case as
well.

## Model Selection
As mentioned previously, the models that will be applied are Naive Bayes, Support Vector Machines, Random Forest
algorithms. Each of these will be applied with a few to finding the most effective model for determining fake news. If
time allows there may also apply some deep learning techniques applied and included in the model selection.
To assess the effectiveness of the models, the following evaluation metrics will be used: precision, recall, and f1
score. These are commonly used metrics that can be used to assess the performance of binary classification
problems.

Precision gives the number of correct predictions made.
Precision = TruePositives / (TruePositives + FalsePositives)

Recall gives the number of positives class predictions from all of the positive examples in the dataset.
Recall = TruePositives / (TruePositives + FalseNegatives)

F1-score is the combination of both precision and recall into a single calculation which enables both of these to be
captured.
F1-score = (2 * Precision * Recall) / (Precision + Recall)

## Results and Discussion
The results of the model performance evaluation will lead then to some discussion and visualizations in the final
solutions report. This will illustrate how well our models have performed on the data set and which of the models
has been shown to be




