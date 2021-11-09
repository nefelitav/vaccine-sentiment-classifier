# Vaccine Sentiment Classifier
In this notebook I used a dataset provided by Dr. Saptarshi Ghosh and Soham Poddar from the Department of Computer Science and Engineering, IIT Kharagpur, India and trained a multinomial Logistic Regression classifier, which classifies a tweet as Neutral, Pro-vax or Anti-vax.  
First of all, I performed some pre-processing and feature engineering on the data, I removed all empty or duplicate rows, I lowercased everything, performed stemming,   stopwords removal, special characters removal, removal of languages other than english, url removal etc.  
Then, I vectorized and calculated TF-IDF on the textual data, so as to perform Logistic Regression. I did the same process for the validation data too, of course.  
Finally, using different metrics, precision, recall, f1, accuracy, confusion matrix, I were able to see the quality of my model.