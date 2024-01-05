# Amazon Alexa Reviews Sentiment Analysis

This Python script conducts sentiment analysis on Amazon Alexa reviews using the VADER sentiment analysis tool. The analysis includes creating a pie chart to visualize the distribution of ratings and determining the overall sentiment (Positive, Negative, or Neutral) based on the reviews.

## Code Structure

1. *Importing Libraries:*
   - Libraries such as pandas, seaborn, matplotlib.pyplot, and nltk.sentiment.vader are imported for sentiment analysis.

2. *Reading Data:*
   - Amazon reviews data is loaded into a Pandas DataFrame using pd.read_csv, specifying a custom delimiter as '\t' (tab-separated).

3. *Pie Chart of Ratings:*
   - The script generates a pie chart illustrating the distribution of ratings using Seaborn and Matplotlib.

4. *Sentiment Analysis:*
   - Utilizing the VADER sentiment analysis tool from NLTK, the script calculates positive, negative, and neutral sentiments for each review.

5. *Overall Sentiment:*
   - Total positive, negative, and neutral scores are summed up, and a function (sentiment_score) determines the overall sentiment based on the highest score.

## How to Use

- Ensure required libraries are installed (pandas, seaborn, matplotlib, nltk).
- Replace "Amazon.txt" with the path to your dataset.
- Run the script.
- Feel free to customize colors, titles, or adapt the code to your specific use case.

## Dependencies

- pandas
- seaborn
- matplotlib
- nltk

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Honey Patel
