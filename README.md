# news-analysis

OVERVIEW
This project involves web scraping multiple news websites, including Times of India, Hindustan Times, and Odisha TV, to collect and analyze news data. We used BeautifulSoup to scrape and crawl news articles, and the extracted data was stored in a CSV file named news_text_data.csv.

KEY FEATURES:
Web Scraping:
Data was collected from multiple news websites using the BeautifulSoup library, ensuring a diverse dataset covering different news topics.

SENTIMENTAL ANALYSIS:
After collecting the news data, we used spaCy for performing sentiment analysis. The sentiment results provide insights into the tone and emotions conveyed in the articles.

DATABASE STORAGE:
The sentiment-analyzed data was stored in a database using SQLAlchemy for efficient storage and retrieval.

DATA VISUALIZATION:
We visualized the analyzed data using Matplotlib and Seaborn to present trends and insights graphically. These visualizations help in understanding the sentiment distribution across different news sources and topics.

TECHNOLOGIES USED:
BeautifulSoup for web scraping
spaCy for natural language processing and sentiment analysis
SQLAlchemy for database operations
Matplotlib and Seaborn for data visualization
How to Use
Clone the repository.
Install the required dependencies using pip install -r requirements.txt.
Run the scraping script to collect news data.
Perform sentiment analysis using the provided scripts.
Visualize the results to gain insights into the news sentiment.
