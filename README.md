# Data_Analysis_on_wallstreetbets_using_redditAPI

Overview:

This project involves scraping data from the "wallstreetbets" subreddit using the Reddit API, cleaning and preprocessing the data, and conducting sentiment analysis. The insights derived from this analysis are visualized and compiled into a report.

Table of Contents:

  Project Structure
  Installation
  Usage
  Data Description
  Analysis
  Visualizations

Project Structure:

  /WallStreetBets-Sentiment-Analysis<br/>
  │<br/>
  ├── notebooks/<br/>
  │   ├── 01_data_scraping.ipynb<br/>
  │   └── 02_data_analysis.ipynb<br/>
  │<br/>
  ├── data/<br/>
  │   └── output.csv<br/>
  │<br/>
  └── README.md<br/>

Installation:

To run this project, you need to have Python installed along with the following libraries:<br/>
  pandas<br/>
  numpy<br/>
  matplotlib<br/>
  seaborn<br/>
  nltk<br/>
  requests<br/>
  
You can install these libraries using pip: pip install pandas numpy matplotlib seaborn nltk requests

Usage:

Data Scraping: Run the 01_data_scraping.ipynb notebook to collect data from the "wallstreetbets" subreddit.<br/>
Data Analysis: Use the 02_data_analysis.ipynb notebook to clean the data, perform sentiment analysis, and visualize the results.<br/>
Output: The processed data is saved in data/output.csv.<br/>

Data Description:<br/>

  The dataset consists of various attributes extracted from subreddit posts, including:<br/>
    subreddit: Name of the subreddit.<br/>
    title: Title of the post.<br/>
    selftext: Content of the post.<br/>
    upvote_ratio: Ratio of upvotes to total votes.<br/>
    ups: Number of upvotes.<br/>
    downs: Number of downvotes.<br/>
    url: Link to the post.<br/>
    sentiment_score: Score indicating sentiment (positive, negative, neutral).<br/>
    sentiment_label: Categorization of sentiment.<br/>
    stock_mentions: Stocks mentioned in the post (if any).<br/>
    tokens: Tokenized words from the post content.<br/>

Analysis:

  The analysis includes:
      Cleaning and preprocessing of data to remove null values and irrelevant columns.<br/>
      Conducting sentiment analysis on post content to classify sentiments as positive, negative, or neutral.<br/>
      Exploring correlations among various metrics such as sentiment scores and upvotes.<br/>

Visualizations:

  Visualizations are created using Matplotlib and Seaborn to represent:<br/>
      Correlation matrices.<br/>
      Sentiment distribution across posts.<br/>
