# KaggleChallenge

Cdiscount.com generated nearly 3 billion euros last year, making it France’s largest non-food e-commerce company.
While the company already sells everything from TVs to trampolines, the list of products is still rapidly growing. 
By the end of this year, Cdiscount.com will have over 30 million products up for sale.
This is up from 10 million products only 2 years ago. Ensuring that so many products are well classified is a challenging task.

Currently, Cdiscount.com applies machine learning algorithms to the text description of the products in order to automatically predict their category. As these methods now seem close to their maximum potential, Cdiscount.com believes that the next quantitative improvement will be driven by the application of data science techniques to images.

In this challenge we will be building a model that automatically classifies the products based on their images. 

The data set Cdiscount.com is making available is unique and characterized by superlative numbers in several ways:

Almost 9 million products: half of the current catalogue
More than 15 million images at 180x180 resolution
More than 5000 categories: yes this is quite an extreme multi-class classification!

The data is present in BSON format.

Have used Keras preprocessing library to read from bson and Convolution Neural Networks from tensor flow to process images and predict categories.
