# Web Scraping and Sentiment Analysis of Steam Game Reviews

## Description
Focuses on extracting and processing user reviews for a specific game (I chose Elden Ring) from the Steam community website. The primary tasks performed include:

1. **Web Scraping using Selenium:** Fetching reviews from Steam using Selenium to navigate and extract data from dynamic web pages.
2. **Data Manipulation and Cleaning:** Utilizing pandas for data manipulation and cleaning tasks, including handling text data and converting strings to numeric values.
3. **Natural Language Processing:** Using nltk to process review texts, including tokenization, stopword removal, and sentiment analysis.
4. **Visualization:** Creating visualizations using Plotly and Matplotlib to analyze the review sentiments and other trends.

## Features
- Selenium for web scraping dynamic content.
- Data manipulation using pandas, including conversion of text to datetime and numeric formats.
- Sentiment analysis using the nltk library's SentimentIntensityAnalyzer.
- Data visualization with Plotly and Matplotlib, including pie charts and box plots.
- Word Cloud generation for text data visualization.

## Visuals
### Pie chart representing the distribution of different review types
![reviews_pie_chart](https://github.com/mmeru/steam-review-scraping/assets/42815425/5552aaec-b8ff-4676-bd45-fa1ffbb3a14e)
### Box plot displaying the distribution of polarity scores categorized by the type of review
![polarity_box_plot](https://github.com/mmeru/steam-review-scraping/assets/42815425/8f6c6b50-7c00-46cb-b1b2-7ee709b509c6)

## Dependencies
- Python 3.x
- selenium==4.9.0
- pandas
- nltk
- plotly
- matplotlib
- wordcloud

## Setup
1. **Selenium WebDriver**: Ensure you have the appropriate WebDriver installed for your browser (e.g., Edge WebDriver for Microsoft Edge).
2. **Python Libraries**: Install the required Python libraries using pip:
   ```bash
   pip install selenium pandas nltk plotly matplotlib wordcloud

## Usage
1. Replace game_id variable with the Steam game ID of your choice.
2. Run the notebook cells sequentially to perform web scraping, data cleaning, analysis, and visualization.
