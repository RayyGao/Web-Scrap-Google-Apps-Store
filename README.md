## Web-Scrap-Google-Apps-Store
This project is about Google Apps store review scraping. 

# Content
1. Web scraping on Google App Store: Scrapy
2. Recommendation System
3. Spam Review Analysis

# Web Scraping
Used Scrapy for web scraping. Google Apps store reviews are limited in the single App webpage. 8972 reviews in total.

# Recommendation System
This system is based on Doc2Vec algorithm in the package Gensim. It can transform a long string to a numeric vector with the dimension the user chooses.

How to recommend in this system? It is highly relied on cosine similarity with different reviews after Doc2Vec is used.

But this requires a solid assumption: all the reviews are reliable.

Really?

# Fake/Spam Review Detection
Most fake reviews are duplicates. How to categorize them is a problem.
Reference: https://www.cs.uic.edu/~liub/FBS/fake-reviews.html
Type 1: Duplicates from different users on the same apps

Type 2: Duplicates from the same user on different apps

Type 3: Duplicates from the same user on the same apps

Type 4: Duplicates from different users on different apps


# Blog Post and Result
https://blog.nycdatascience.com/student-works/recommendation-system-spam-review-detection/

# Author
Author: Xu Gao, a graduate student learning Financial Engineering at Tandon School of Engineering in New York University. He is highly interested in quantitative finance and data science. BTW, he loves games and enjoys analysing them by using data.
