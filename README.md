# Data_Analysis_on_wallstreetbets_using_redditAPI

**Overview:**

This project involves scraping data from the "wallstreetbets" subreddit using the Reddit API, cleaning and preprocessing the data, and conducting sentiment analysis. The insights derived from this analysis are visualized and compiled into a report.

**Table of Contents:**

  Project Structure
  Installation
  Usage
  Data Description
  Analysis
  Visualizations

**Project Structure:**

  /WallStreetBets-Sentiment-Analysis
  │
  ├── notebooks/
  │   ├── 01_data_scraping.ipynb
  │   └── 02_data_analysis.ipynb
  │
  ├── data/
  │   └── output.csv
  │
  └── README.md

**Installation:**

To run this project, you need to have Python installed along with the following libraries:
  pandas
  numpy
  matplotlib
  seaborn
  nltk
  requests
  
You can install these libraries using pip: pip install pandas numpy matplotlib seaborn nltk requests

**Usage:**

**  Data Scraping:** Run the 01_data_scraping.ipynb notebook to collect data from the "wallstreetbets" subreddit.
**  Data Analysis:** Use the 02_data_analysis.ipynb notebook to clean the data, perform sentiment analysis, and visualize the results.
**  Output: **The processed data is saved in data/output.csv.

**Data Description:**

  The dataset consists of various attributes extracted from subreddit posts, including:
**  subreddit: **Name of the subreddit.
**  title: **Title of the post.
 ** selftext:** Content of the post.
**  upvote_ratio: **Ratio of upvotes to total votes.
**  ups:** Number of upvotes.
  **downs:** Number of downvotes.
 ** url:** Link to the post.
**  sentiment_score:** Score indicating sentiment (positive, negative, neutral).
 ** sentiment_label:** Categorization of sentiment.
 ** stock_mentions:** Stocks mentioned in the post (if any).
  **tokens: **Tokenized words from the post content.

**Analysis:**

  The analysis includes:
      Cleaning and preprocessing of data to remove null values and irrelevant columns.
      Conducting sentiment analysis on post content to classify sentiments as positive, negative, or neutral.
      Exploring correlations among various metrics such as sentiment scores and upvotes.

**Visualizations:**

  Visualizations are created using Matplotlib and Seaborn to represent:
      Correlation matrices.
      Sentiment distribution across posts.
