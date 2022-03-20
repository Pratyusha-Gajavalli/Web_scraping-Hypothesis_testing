# Web_scraping-Hypothesis_testing
# Objective
This project aims to assess if having models in H&M's product imagery have significant impact in driving sales. Women's clothing category have been considered for the analysis.

# Observation
The company has fixed costs of roughly $15M annually in hiring models for product photoshoots under women category alone. This expense does not generate significant additional benefit in revenue. Given this finding, the company will be able to shift this expense and employ models for other promotion strategies.

# Analysis
To prove the finding, a hypothesis test is executed on whether difference in sales between products with and without model-based imagery is significant. Average rating is taken as proxy metric for sales in this analysis.
Hypothesis test -
U1 – Average rating of products with model/size specifications
U2 – Average rating of products without model/size specifications
Null hypothesis – U1 > U2
Alternate hypothesis - U1 < = U2

# Methodology
• Understand the business, website and html page source.
• Identify relevant data metrics like presence of model-based imagery, average ratings, number of reviewers, description, and product category for each product
• Scrape H&M website’s women section to extract these relevant metrics.
• Cleanse, format and standardize the scrapped data across the 2 groups, that is, products with model and without model imagery.
CONFIDENTIAL Page 2
• Add fit relevance score to product descriptions(Used NLTK to Tokenize, Lemmatize, and remove Stopwords. Word2vec Glove was used to train the model)
• Perform exploratory data analysis to assess distribution of products with and without model images in each category, distribution of average rating and number of ratings.
• To substantiate the finding perform a hypothesis testing using t-test

# Results
Null hypothesis is rejected with 95% confidence level for 10 out of 14 product categories used in the analysis. This proves our alternate hypothesis that model based imagery is not impacting the sales much when there is fit related product description.
https://github.com/Pratyusha-Gajavalli/Web_scraping-Hypothesis_testing/issues/1#issue-1174631550

# Thank You!
