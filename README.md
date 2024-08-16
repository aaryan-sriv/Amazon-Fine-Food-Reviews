# Amazon-Fine-Food-Reviews

A base ML project using data extracted from Kaggle to produce a model capable of predicting review scores using testing and training data.It works in the same way a base model does by following the necessary steps such as-

Step 1: Data Collection
1.1 Downloading the dataset from Kaggle (Amazon Fine Food Reviews)
1.2 Loading the dataset into a Jupyter notebook
1.3 Inspecting the dataset structure and features
Columns: Id, ProductId, UserId, ProfileName, HelpfulnessNumerator, HelpfulnessDenominator, Score, Time, Summary, Text

Step 2: Data Preprocessing
2.1 Handling Missing Values
Identifying and handling missing values in the dataset
2.2 Data Cleaning
Removing HTML tags, punctuation, and special characters from review texts
2.3 Text Normalization
Converting text to lowercase
Removing stopwords and stemming/lemmatization

Step 3: Exploratory Data Analysis (EDA)
3.1 Data Visualization
Visualizing the distribution of review scores
Exploring the most frequent words in the reviews
3.2 Sentiment Analysis
Performing sentiment analysis to understand the polarity of reviews

Step 4: Feature Engineering
4.1 Text Vectorization
Converting text data into numerical features using techniques like TF-IDF, Bag of Words, or Word Embeddings
4.2 Additional Features
Creating new features from existing ones, such as review length, word count, etc.

Step 5: Model Building
5.1 Train-Test Split
Split the dataset into training and testing sets
5.2 Model Selection
Choose appropriate models for the task, such as Logistic Regression, Naive Bayes, Random Forest, or LSTM
5.3 Model Training
Train the models on the training data
5.4 Model Evaluation
Evaluate the models using metrics like accuracy, precision, recall, F1-score, and confusion matrix

Step 6: Hyperparameter Tuning
6.1 Grid Search or Random Search
Perform hyperparameter tuning to improve model performance

Step 7: Model Deployment
7.1 Save the Best Model
Save the trained model using libraries like pickle or joblib

Step 8: Conclusion
Using prettytable to form a table consisting of test scores from various models to determine the best model out of these.
Possible improvements can be using Ensemble Learning to further improve the accuracy of data.

