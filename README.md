# Social-Media-Sentiment-Analysis-Twitter

This Notebook implements a sentiment analysis model for tweets using Natural Language Processing (NLP) techniques and Machine Learning algorithms. It classifies tweets into positive, negative, or neutral sentiments using a Multinomial Naive Bayes classifier with TF-IDF features.

# Features

- Data preprocessing: tokenization, stemming, and stop word removal
- TF-IDF vectorization for feature extraction
- Multinomial Naive Bayes classifier
- Hyperparameter tuning using GridSearchCV
- Model evaluation with accuracy score and confusion matrix
- Visualization of results using confusion matrix heatmap and pie chart
- Top tweets analysis and word cloud generation

# Getting Started
To get started follow these steps:

1. **Clone the Repository**:
   - Clone this repository to your local machine.
     ```
     git clone https://github.com/Shreya-Reddy-A/Social-Media-Sentiment-Analysis-Twitter.git
     ```

2. **Install Dependencies**:
   - Navigate into the cloned directory and install the necessary dependencies.
     ```
     cd Social-Media-Sentiment-Analysis-Twitter
     pip install -r requirements.txt
     ```
3. **Dataset**:
    - Ensure you have your Twitter data in CSV format ```('twitter_train.csv' and 'twitter_validate.csv')```.
      
4. Notebook:
   - Launch Jupyter Notebook.
   - Open the `Twitter_Sentiment_Analysis.ipynb` notebook in your browser.
   - Run the cells in the notebook sequentailly.

# Results
  ### Model performance metrics
  ![Screenshot (240)](https://github.com/user-attachments/assets/7bd321c9-683a-4d81-86e3-809224557d3e)
  ### Confusion matrix visualization
  ![Screenshot (240)](https://github.com/user-attachments/assets/b1eb98e8-9046-4b72-8ba6-e10fb8212193)
  ### Pie chart of sentiment distribution
  ![Screenshot (242)](https://github.com/user-attachments/assets/b45dbd79-96ac-4ac0-a71d-86e7fe53ce08)
  ### Word cloud of top tweets
  ![Screenshot (246)](https://github.com/user-attachments/assets/3af3a419-9be7-4e42-8b97-cf831c0cf8f6)

    
