# Consumer Insights Analysis
<img src="https://github.com/user-attachments/assets/11233608-f2cc-4944-ae09-4519bb68a4b2" width="200"/>

This project was completed as part of a qualitative & quantitative insights externship with **Beats by Dre**, based in California.

The company wanted to analyze customer reviews to guide product development and strategy for Beats' Pill Wireless Speakers. The dataset for this project was sourced/scraped from Amazon product reviews for various Beats by Dre audio devices. The dataset contains key information like review text, rating, helpful count, verified purchase status, and product attributes, used for sentiment analysis and insights into consumer experiences.

Key areas of this experience include:
- Leveraging web scrapers to collect consumer feedback from Amazon. Data was collected using the Oxylabs Scraper API, with a custom Python script to scrape and structure Amazon product reviews. [> full code](Amazon_Review_Scraper.ipynb)<br>
- Cleaning messy data. [> full code](Beats_Data_Cleaning.ipynb)<br>
- Utilizing **visualization tools** like Matplotlib and Seaborn to uncover trends, outliers, and correlations in the dataset. [> full code](Beats_Visualizations.ipynb)<br>
- Performing **sentiment analysis** using TextBlob to classify and analyze brand perception. [> full code](Sentiment_Analysis.ipynb)<br>
- Translating data into **strategic recommendations and reports**<br><br>

## Executive Summary
### Overview of Findings

- 76% of Beats product reviews are 5-star ratings, reflecting high customer satisfaction. The polarity score confirms this: reviews are skewed positive, with a few negative outliers.
- Sound quality is a core value driver for satisfied buyers, particularly for its bass strength and clarity. The lightweight design is also frequently highlighted as positive aspects.
- Themes of gifting, celebration, and personal value are strong in reviews with high sentiment. (polarity > 0.65)
- Product reliability is a key pain point for low-rated reviews, frequently mentioning charging issues, Bluetooth disconnection, and non-working product upon receiving it. 

![dcds](https://github.com/user-attachments/assets/da557b49-3b30-43b1-bfd0-8a2ba8e8c960)


## Insights Deep Dive
### Competitive Analysis (Wireless Speakers)
- Beats ratings fluctuate over time, dipping around 2023 (to ~4.2) before rebounding in 2025.
- Amazon Echo's late entry in 2024 was rated highly (~4.7), which is a rising threat for Beats Speakers, especially in budget or bundled smart-home audio.
- JBL Speakers leads with both strong ratings and loyalty, while Beats enjoys higher emotional pull despite mixed consistency. Amazon Echo and LG lag behind as functional but less emotionally resonant brands.
- Beats' speakers has a solid average rating (4.62), but exhibits the highest standard deviation among brands, indicating risk of churn due to inconsistency across customer experiences.
  
![dfdsjfld](https://github.com/user-attachments/assets/501ba66e-f193-4176-a031-d59c3b357746)

### Sentiment Scores


### High-rated Beats Products
Factor Categories & Associated Keywords:

1. Sound Quality
- `sound`, `audio`, `bass`, `clarity`, `loud`, `volume`, `noise`, `distortion`, `treble`

2. Design & Looks
- `design`, `look`, `color`, `style`, `aesthetic`, `sleek`, `compact`, `small`, `size`, `portable`, `lightweight`

3. Battery
- `battery`, `charge`, `charging`, `power`, `long-lasting`, `recharge`, `life`

4. Connectivity
- `bluetooth`, `wifi`, `connect`, `connection`, `pair`, `airplay`, `apple`, `android`, `wireless`

5. Durability
- `durable`, `sturdy`, `rugged`, `solid`, `built`, `build quality`, `waterproof`, `shock`, `reliable`


6. Price & Value
- `price`, `cost`, `value`, `worth`, `cheap`, `expensive`, `deal`, `affordable`

I used these categories to extract factor-specific word frequencies from review text and visualize their distribution across star ratings. This enables insight into **what factors drive positive reviews**.


- Factors
- Dominant words
- Functionality-related words

### Low-rated Beats Products





## Assumptions and Caveats
Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

- All reviews are from American consumers.
- Reviews are honest and reflective of actual behavior. (No response bias)
- Stated reviews translate into real purchasing decisions.






