# Consumer Insights Analysis
<img src="https://github.com/user-attachments/assets/11233608-f2cc-4944-ae09-4519bb68a4b2" width="200"/>

This project was completed as part of a qualitative & quantitative analysis externship with **Beats by Dre**, based in California.

The company wanted to analyze customer reviews to guide product development and strategy for Beats' Pill Wireless Speakers. The dataset for this project was sourced/scraped from Amazon product reviews for various Beats by Dre audio devices. The dataset contains key information like review text, rating, helpful count, verified purchase status, and product attributes, used for sentiment analysis and insights into consumer experiences.

Key areas of this experience include:
- Leveraging web scrapers to collect consumer feedback from Amazon. Data was collected using the Oxylabs Scraper API, with a custom Python script to scrape and structure Amazon product reviews. [> full code](Amazon_Review_Scraper.ipynb)<br>
- Cleaning messy data. [> full code](Beats_Data_Cleaning.ipynb)<br>
- Utilizing **visualization tools** like Matplotlib and Seaborn to uncover trends, outliers, and correlations in the dataset. [> full code](Beats_Visualizations.ipynb)<br>
- Performing **sentiment analysis** using TextBlob to classify and analyze brand perception. [> full code](Sentiment_Analysis.ipynb)<br>
- Translating data into **strategic recommendations and reports**<br><br>

## Executive Summary
### Overview of Findings

- Sentiment skews positive, but not passionately so.
- Quality is a core value driver for satisfied buyers, particularly for bass strength and clarity in a compact form. 
- Low-Rated reviews frequently mentioned charging issues, Bluetooth disconnection, and non-working product upon receiving it.
- Price is not driving dissatisfaction. In fact, customers who are happy see it as justified. 

![Average Rating](https://github.com/user-attachments/assets/f4a49200-da88-4fd7-8440-e0b35b30169e)

### Competitive Analysis (Wireless Speakers)
- Beats' speakers has a solid average rating (4.62), but exhibits the highest standard deviation among brands, indicating inconsistency across customer experiences.
- Brands like JBL and Sony had clusters in the high subjectivity + high polarity range, a sign of stronger emotional engagement, Beats showed less emotionally expressive language in comparison.
- Without strengthening emotional engagement and resolving inconsistency, Beats risks losing brand preference to competitors.<br><br>
  

![dfdsjfld](https://github.com/user-attachments/assets/501ba66e-f193-4176-a031-d59c3b357746)










