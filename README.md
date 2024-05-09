**Customer Reviews of Amazon Products**

**Data Collection and Preprocessing**
Utilizing Google Colab, I accessed consumer reviews of Amazon products from the Datafiniti dataset. The dataset comprised various attributes including product names, brands, categories, primary categories, manufacturer information, review ratings, review texts, and usernames. After loading the dataset, I performed initial data cleaning steps such as dropping unnecessary columns, checking for missing values, and ensuring data integrity.

**Exploratory Data Analysis**
To gain insights into the dataset, I visualized the distribution of review ratings using seaborn's countplot. The majority of reviews were positive, with a significant proportion rating products with 5 stars.

**Natural Language Processing (NLP) Analysis**
The project focused on analyzing the textual content of customer reviews using NLP techniques to extract valuable insights. I utilized the NLTK library for text preprocessing, which involved steps like removing HTML content, non-alphabetic characters, tokenization, removing stop words, and lemmatization.

**Sentiment Analysis**
Implemented sentiment analysis to categorize customer sentiments as positive, negative, or neutral. This analysis provided a deeper understanding of customer satisfaction levels and product sentiment trends.

**Machine Learning Models**
**Naive Bayes Classifier**
Trained a Naive Bayes classifier on the bag-of-words representation of the review texts. Achieved an accuracy of approximately 77.96% on the test dataset.

**LSTM Neural Network**
Developed a Long Short-Term Memory (LSTM) neural network model to predict the star ratings of customer reviews. The model utilized word embeddings and achieved an accuracy of approximately 77.22% on the test dataset.

**Word Cloud Visualization**
Created word clouds to visualize the most frequent words in customer reviews, providing a graphical representation of common themes and topics mentioned by customers.

**Conclusion**
The project demonstrated proficiency in data preprocessing, exploratory data analysis, NLP techniques, and machine learning model development. The insights derived from this analysis can assist businesses in understanding customer sentiments, improving product offerings, and enhancing overall customer satisfaction.
