#                               SC1015 Project: An in-depth analysis of Amazon Sales and Review Data 

## Background  

Companies tend to analyze their sales data to decide their sales direction. After all, this is the most accessible and commonly analyzed data. One of such companies is Amazon, a global online retailer. Online shopping websites contains a repository of reviews by shoppers. These reviews are used by other shoppers to decide whether a product is worth purchasing. 

<img  width=70% alt="image" src="https://i.imgur.com/yNjKszW.jpeg">

## Problem Definition

We aim to put the underutilized data of user purchase history and product description to better use, by building a recommendation system based on TF-IDF Vectorization and Cosine Similarity of reviews to improve user experience. This can complement the existing sales data analysis, to improve customer satisfaction in online retail stores, as well as revenue.

 
## Dataset  
We have chosen a dataset from Kaggle which illustrates user reviews of Amazon products over a given period. The link to the data set is at https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset/data. It is built from scraping product details from the official Amazon website. The data contains 1351 rows and is organized into 16 categories, which include key categories such as product_name, category, actual price, discounted price, rating and review content, which we analysed in the project.
 

## Methods
We have followed the process of data analytics as taught in the SC1015 course, in the order of data extraction, data cleaning, exploratory data analysis, data visualization as well as sentiments analysis by means of WordCloud. We conducted the analysis on the review scores to find out the popularity of products. We have included the use of Natural Language Toolkit (NLTK), a powerful and flexible library in performing sentiment analysis and natural language processing (NLP) tasks.  

## Tools Used
Box Plot, Bar Plot, Correlation Matrix, Scatterplot, WordCloud

### TF-IDR Vectorizer
<img width=60% alt="image" src="https://i.imgur.com/5VbUPup.png">

### Cosine Similarity
<img width=60% alt="image" src="https://miro.medium.com/v2/resize:fit:1022/1*-0AjCAVpOI50XySKLCt_Bg.png">

## Conclusion
We have come up with a recommendation system that provides convenience for users as they can find products that they are most likely to be interested in. Additionally, the Exploratory Data Analysis has helped us learnt about what kind of products is popular amongst shoppers and the average discounts that we can set for each categories/sub-categories of product. With our key results presented in the video, we can gear the strategy towards higher customer satisfaction, which can result in more sales and thus higher revenue. 


## Lesson Learnt
Learnt how to use new models such as WordCloud, TF-IDF Vectorizer and Cosine Similarity.
Learnt that we can use words to better understand reviews, and unlock the potential in data analytics.
Understood Privacy & Ethics, and that user have to consent to their reviews to be used for analysis.
    

