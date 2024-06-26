# Sentiment Analysis on mobile Reviews

Motivation and Problem:
Customer reviews are essential in business as they greatly affect sales and customer satisfaction. In a market full of choices, these reviews can sway consumer decisions. They're crucial for businesses not only to fix current issues like Product relevance and quality control but also for long-term planning and success. Reviews act as a direct link between customers and companies, offering honest feedback. This feedback is key for improving products, building brand trust, and understanding market trends.
This motivated me to design a system in such a way that it not only collects and interprets customer feedback but also turns it into actionable insights for product development, marketing strategies, and customer service improvement. This system is essential to enhance product quality, elevate customer satisfaction, and reduce the financial and reputational risks linked to product failures.
Solution:
The core of our solution involves the use of advanced algorithms and machine learning models, such as Random Forest Classifier for sentiment analysis and Latent Dirichlet Allocation (LDA), BERT model to accurately classify sentiments and extract relevant topics from text data. 

Data Collection :
The source of the dataset is from Kaggle. We have a set of data with 67,986 data points. In this data, there are 7 types of information about each product review. These include things like the “ProductID”, how “helpful” the review was, the “rating” given, the text of the “Review”, when the review was written (“reviewTime”), the name of the reviewer (“reviewerName”), and a short “summary”. Most of these are just text, but the rating and how helpful the review is a number. We’re interested in the context of the review given by the customers to give suggestions. Our main job is to sort the reviews into two groups: the ones that say good things ("positive") and the ones that say not-so-good things ("negative"). For the negative reviews, a key part of our analysis involves identifying commonly recurring negative phrases, which will assist us in pinpointing prevalent issues. By analyzing these patterns, we'll be able to offer targeted recommendations that are specifically tailored to address these identified concerns.

Data resources Links: https://www.kaggle.com/datasets/grikomsn/amazon-cell-phones-reviews

