# **READ ME**

This repository provides tools to scrape the news and podcasts from the University of Chicago's Harris School of Public Policy.
The main news page: https://harris.uchicago.edu/news-events/news

## **HOW TO USE**
1. Open the ipynb file in your local computer
2. Change the path variable in the second block into the path where you want to score the scraped information
3. Use one or many of the functions provided:
  * scrape_news: Scraping news from the main news page
  * scrape_napp: Scraping the podcast from Not Another Politics Podcast
  * scrap_public_money_pd: Scraping the podcast from Public Money Podcast

## **Next Steps**
1. Using lxml to scrape the entire article and build model based on that
2. Using LLM APIs to predict the relevant policy area
