# Sentiment Analysis on Stock Data Using Natural Language Processing

This project focuses on creating a sentiment classifier model using customer messages. The goal is to solve a binary classification problem that categorizes stock-related sentiment data as positive or negative. A sentiment of **1** indicates positive sentiment, while **0** indicates negative sentiment.

### Resources:
The primary resource used for this project is the **Python & Machine Learning for Financial Analysis** course on Udemy.

### Key Steps:
1. **Importing Required Libraries**:
   - Libraries such as `pandas`, `numpy`, `seaborn`, `matplotlib`, `nltk`, `gensim`, and `tensorflow` were used for data manipulation, visualization, and model building.

2. **Exploratory Data Analysis (EDA)**:
   - Analyze the dataset to understand its structure and explore patterns.

3. **Data Cleaning**:
   - Clean the text data by removing unnecessary punctuation and stopwords, ensuring the dataset is ready for analysis.

4. **Data Visualization**:
   - Visualize the cleaned dataset and plot a word cloud to identify the most frequent terms.

5. **Data Preparation**:
   - Tokenize the text and apply padding to handle varying text lengths for model training.

6. **Building the Sentiment Classifier**:
   - Develop a custom deep neural network for sentiment analysis using an embedding layer and LSTM (Long Short-Term Memory) network.

7. **Prediction & Model Evaluation**:
   - Use the trained model to make predictions and assess performance using metrics like the confusion matrix.

### Libraries and Tools Used:
- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical operations and handling data arrays.
- **seaborn, matplotlib**: For visualizations and data plotting.
- **nltk, gensim**: For text processing tasks like tokenization and stopword removal.
- **tensorflow**: For building and training the deep learning model (LSTM network).

### Conclusion:
This project applies sentiment analysis to stock-related data, classifying messages as either positive or negative. The trained model can help identify the sentiment of customer feedback, which can be valuable for financial analysis, trading strategies, and decision-making based on market sentiment.
