This project focused on analyzing sentiment within Amazon product reviews using the VADER sentiment analysis tool in Python. Initially, the data from the 'amazon_reviews.csv' file was loaded into a Pandas DataFrame for exploratory data analysis (EDA). The dataset was cleaned by handling missing values and converting the 'date' column to datetime format.

The distribution of ratings was visualized using Seaborn, providing an overview of how ratings were distributed among the reviews. Additionally, the count of unique products was explored to understand the frequency of reviews per product.

The VADER sentiment analysis tool was utilized to derive sentiment scores (positive, negative, neutral, and compound) for each review. The relationship between positive and negative sentiment scores and their respective ratings (5 and 1) was visualized to observe any correlation between sentiment and ratings.

Furthermore, the analysis delved into grouping products by their ASIN and determining the average compound sentiment score for each product. This facilitated the identification of top and bottom products based on their sentiment scores, visualized using a bar plot showcasing the products with the highest and lowest average sentiment scores.

Overall, this project showcased the application of sentiment analysis techniques to extract insights from Amazon product reviews, enabling a better understanding of customer sentiment toward various products. The process involved data cleaning, exploratory analysis, sentiment scoring, and visualization, offering valuable insights into product-specific sentiments.
