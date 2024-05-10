**Amazon Product Review**

This repository contains Python code for analyzing Amazon product reviews using both traditional machine learning and deep learning techniques. The analysis pipeline includes data preprocessing, exploratory data analysis (EDA), model training, and evaluation.

**Dataset:**

The dataset used for analysis is the Amazon Consumer Reviews of Amazon Products dataset, obtained from Kaggle. It contains information about various Amazon products along with user reviews and ratings.

**Analysis Steps:**

**Data Preparation:**

The dataset is downloaded from Kaggle and loaded into a Pandas DataFrame. Unnecessary columns are dropped, and missing values are handled.

**Exploratory Data Analysis (EDA):**

Visualizations are created to understand the distribution of review ratings and explore the most frequent words in the reviews using word clouds.
Text Preprocessing: Text data preprocessing steps are applied, including removing HTML content, non-alphabetic characters, stopwords, and lemmatization.

**Model Training (Naive Bayes):**

A Naive Bayes classifier is trained on the Bag-of-Words representation of the text data. This model serves as a baseline for comparison.

**Deep Learning Model Training (LSTM):**

An LSTM neural network model is trained using Keras for text classification. Word embeddings are utilized to capture semantic information, providing more nuanced insights into the review sentiments.

**Evaluation and Comparison:**

Both models are evaluated, and their accuracies are compared using bar plots. Additionally, sample predictions are showcased to demonstrate the models' performance.

**Technologies Used:**

**Python Libraries:**   Pandas, NumPy, Matplotlib, Seaborn, NLTK, BeautifulSoup
**Machine Learning Tools:**    scikit-learn
**Deep Learning Frameworks:**    TensorFlow, Keras
