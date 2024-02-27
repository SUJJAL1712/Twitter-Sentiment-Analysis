# Twitter-Sentiment-Analysis

This project focuses on performing sentiment analysis using a dataset from Kaggle. The analysis is aimed at classifying tweets into positive or negative sentiments. This README provides an overview of the steps taken in the Jupyter notebook to accomplish this task.

Steps Overview:

1. Initializing
The project begins with the setup phase, including installing necessary packages like kaggle for data downloading.

3. Data Acquisition
Kaggle API is utilized to fetch the Sentiment140 dataset. Instructions are provided to configure the Kaggle API key properly for data downloading.
The dataset named sentiment140.zip is then downloaded and extracted for analysis.

5. Importing Libraries
Essential Python libraries such as NumPy, pandas, re (for regular expressions), nltk (for natural language processing), sklearn (for machine learning models and metrics) are imported

6. Preprocessing Data
The notebook outlines the preprocessing steps required to clean and prepare the textual data for analysis. This includes removing special characters, converting text to lowercase, removing stopwords, and applying stemming.

8. Feature Extraction
TF-IDF Vectorizer is used for converting text data into numerical format, making it suitable for machine learning model input.

10. Model Training
A Logistic Regression model is trained on the preprocessed data. This section includes splitting the dataset into training and testing sets, model training, and predictions.

12. Model Evaluation
The trained model's performance is evaluated on both training and test data to assess its accuracy in sentiment classification.

14. Saving the Trained Model
The trained model is saved to disk using pickle for future use, allowing for sentiment analysis without retraining.

16. Using the Saved Model
Instructions are provided on how to load the trained model from disk and use it to make predictions on new data samples.
Model Accuracy

The notebook concludes with showcasing the model's accuracy on training and test datasets. However, specific accuracy figures are to be found within the notebook execution results.

Conclusion

This project demonstrates the end-to-end process of sentiment analysis on tweet data, from data acquisition and preprocessing to model training, evaluation, and deployment. The Logistic Regression model's ability to classify sentiments showcases the potential of machine learning in understanding and analyzing human emotions expressed through text.
