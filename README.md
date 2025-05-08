# E-commerce Women Clothing Review
## Project Overview & Goals
This project aims to analyze customers reviews of women’s clothing from an anonymous ecommerce retailer to uncover insights into customer sentiment, key product attributes, and the impact of customers’ content on purchase decisions. We will leverage NLP and other Machine Learning techniques to extract patterns  from customers' reviews. By conducting this analysis, we aim to provide actionable recommendations that e-commerce businesses can apply to improve product offerings, personalize marketing strategies, and enhance customer experience.

## Source of Data:
For this project, we are considering the dataset available on Kaggle website. The link is provided below: https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews   

### Description of key variables
This dataset contains 23,486 customer reviews from a women’s clothing e-commerce platform, anonymized for privacy. It includes 10 features, such as product ID, reviewer age, review text, rating (1-5), recommendation status (binary), and product category details (division, department, and class name).

**Clothing ID**: Integer Categorical variable that refers to the specific piece being reviewed.

**Age**: Positive Integer variable of the reviewers age.

**Title**: String variable for the title of the review.

**Review Text**: String variable for the review body.

**Rating**: Positive Ordinal Integer variable for the product score granted by the customer from 1 Worst, to 5 Best.

**Recommended IND**: Binary variable stating where the customer recommends the product where 1 is recommended, 0 is not recommended.

**Positive Feedback Count**: Positive Integer documenting the number of other customers who found this review positive.

**Division Name**: Categorical name of the product high level division.

**Department Name**: Categorical name of the product department name.

**Class Name**: Categorical name of the product class name.


## Scope of Analysis:
The dataset is ideal for NLP analysis, sentiment classification, and customer behavior modeling. Potential applications include:
### Sentiment Analysis:
Predicting review sentiment from text and ratings.
### Text Mining & Topic Modeling
Identify common themes in reviews (e.g. sizing, materials quality, color)
### Predictive Modeling
Identifying key factors that drive product recommendations based on review content and ratings.
### Feature Engineering
Extracting insights from text for customer preferences and product trends.
