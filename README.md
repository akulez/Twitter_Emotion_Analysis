# Twitter_Sentiment-Analysis_Classical-Approach
This project focuses on applying classical NLP and Machine Learning models for Predicting Depression from Twitter Tweets. The project was done in several steps as follows:

1. **Exploration**
   - In this part I have focused on conducitng initial analysis of the data using visualization and descriptive statistics.
   - Visualizations including wordcloud were used to better understand the most frequent words.
   - The target variable was encoded, preparing it for further steps.

2. **Text Preprocessing and Vectorization**
   - After exploration, text preprocessing was conducted to refine the text and prepare it for vectorization.
   - Unnecessary stopwords, characters, punctautions and unneeded spaces were removed from the data since they do not add any semantic meaning to our text.
   - Post text preprocessing steps, the text was converted to vectors to prepare it for model fitting.
   - For vectorisation, I decided to use a classical vectorization algorithm, TF-IDF, instead of using anything more complex, since the dataset required use of 
     simpler models, and complex models were overfitting the data.

3. **Model Fitting and Evaluations:**
   - After text vectorization, I fit 3 different statistical models to predict depression from tweets, specifically - Decision Trees, Logisitic Regression and Random      Forests.
   - Complex models were found to overfit the data and the classical models achieved an accuracy of 98%.
   - Accuracy score, f1 score and recall were among the metrics used to evaluate the models.


