# Analyze customer satisfaction with products

## Dataset
Data will be collected from an S** platform, including comments and ratings of products. The data will cover 10 main topics: Home and Life, Men's Fashion, Phones and Accessories, Electronics, Computers and Laptops, Men's Shoes, Watches, Sports and Travel, Jewelry Accessories, and Beauty. Each topic will include 30-50 products, with each product having 30-50 comments and star ratings.

The data will be filtered as follows: removing empty comments, converting comments and ratings into evaluation keys.
- Products rated 5 stars will be assigned a key of 1.
- Products rated <= 4 stars will be assigned a key of 0.
- The total dataset will include 33,453 comments and customer satisfaction evaluation keys.
  - Key == 1: indicates satisfaction with the product.
  - Key == 0: indicates dissatisfaction with the product.

## Purpose of the Study
-  Evaluate User Satisfaction
    - Determine user satisfaction levels with products through interactions and feedback on social media.
    - Analyze factors influencing user satisfaction, such as product quality, customer service, price, etc.
- Understand User Needs and Desires
    - Collect and analyze data from posts, comments, and reviews on social media to better understand user needs and desires.
    - Identify trends and consumption patterns through discussions and feedback on social media.
- Improve Products and Services:
    - Enhance products and services based on actual user feedback.
    - Propose strategies and measures to increase customer satisfaction.
    - 
## Results
```sh
Train: 0.9632
Val:  0.9276
Test: 0.93335325762104
```
