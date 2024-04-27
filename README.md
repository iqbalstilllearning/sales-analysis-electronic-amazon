![cover_Deck - Electronic Sales Analysis (Amazon)](https://github.com/iqbalstilllearning/sales-analysis-electronic-amazon/assets/105572256/6c561977-bccd-4374-a409-ff9ac382ad95)

# **Problem Statement**
- The source code for this project is available on my GitHub ([Here](https://github.com/iqbalstilllearning/sales-analysis-electronis-amazon))
- The dataset utilized originates from Kaggle ([Here](https://www.kaggle.com/datasets/edusanketdk/electronics)) with 1.292.954 rows and 10 columns.
- The dataset in question is sourced from Amazon and pertains to electronic sales, encompassing various aspects such as user information, item details, ratings, timestamps, and additional attributes.
- The primary objective of this project is to conduct a thorough analysis of the electronic sales data on Amazon and extract valuable insights to guide strategic decision-making.
- The specific focus is on addressing key questions and exploring pertinent factors related to sales performance, customer behavior, and product attributes.
- The analysis aims to provide actionable recommendations for optimizing sales, improving customer satisfaction, and enhancing overall business performance.
- To achieve these goals, we will delve into patterns, trends, and correlations within the dataset, seeking to uncover relationships between user behavior, product characteristics, and sales outcomes.

# **Research Questions**
1. **Time Series Analysis**
   - How is the annual trend in the sales of electronic products? Is there any specific increase or decrease?
   - Are there seasonal patterns in sales, such as during specific years and months?
   - What is the distribution of product ratings across the dataset over the years and months?

2. **Category and Brand Performances**
   - Which category of electronic products is the most popular on Amazon based on sales or average ratings?
   - Are there specific trends in the categories of products sold in different years?
   - Which electronic product brand is the most popular on Amazon based on sales or average ratings?
   - Are there specific trends in the brands of products sold in different years?

3. **User Segmentation**
   - What is the distribution of consumer gender across the entire dataset?
   - Can you identify and segment users based on model or category preferences?
  
# 1. TIME SERIES ANALYSIS
- How is the annual trend in the sales of electronic products? Is there any specific increase or decrease?
![output1](https://github.com/iqbalstilllearning/sales-analysis-electronic-amazon/assets/105572256/e63fc7aa-97ed-4dee-9b0b-1693fe126423)
Electronics sales on Amazon have experienced significant growth in recent years. In 1999, the number of electronics sales on Amazon was only 118 units. However, in 2015, the number of electronic sales on Amazon reached 364,004 units. Unfortunately, there was a drastic decline the following year.

- Are there seasonal patterns in sales, such as during specific years and months?
![output2](https://github.com/iqbalstilllearning/sales-analysis-electronic-amazon/assets/105572256/b6fbd004-af72-461e-a450-6fb8935651a1)
The busiest month all the time (1999-2018) for electronics sales was January, with 140.773 items sold. And the slowest month for electronics sales was October, with 95.084 items sold.
![output3](https://github.com/iqbalstilllearning/sales-analysis-electronic-amazon/assets/105572256/373b6acf-109c-4cdd-ae25-06b07f8e061d)
There seems to be a general upward trend in sales year-over-year, with each year surpassing the previous year's total sales. The analysis reveals that the period between 2009 and 2015 marked the busiest years, with sales evenly distributed across each month. The pinnacle of sales occurred in January 2015.

- What is the distribution of product ratings across the dataset over the years and months?
![output4](https://github.com/iqbalstilllearning/sales-analysis-electronic-amazon/assets/105572256/5d0bacbd-2a93-4d53-8cd3-0889ebb562c4)
![output5](https://github.com/iqbalstilllearning/sales-analysis-electronic-amazon/assets/105572256/b144464d-e131-40af-9b4f-6c5eea23a3f3)
![output6](https://github.com/iqbalstilllearning/sales-analysis-electronic-amazon/assets/105572256/8b976f93-2144-44b9-ba07-1cb4ce070f8d)
![output7](https://github.com/iqbalstilllearning/sales-analysis-electronic-amazon/assets/105572256/1ee4acd9-46d5-4f67-82d9-3ed9abdbcd2b)
The distribution of ratings reveals that consumers predominantly assigned a rating of 5, totaling 755.755, surpassing other ratings. Notably, across the annual spectrum, all ratings peaked in 2015. Similarly, on a monthly basis, January witnessed the highest frequency of ratings.

# 2. Category and Brand Performance
- Which category of electronic products is the most popular on Amazon based on sales or average ratings?
![output8](https://github.com/iqbalstilllearning/sales-analysis-electronic-amazon/assets/105572256/9d4b3e59-c7bf-4bc9-b6b0-8ffa83ae3f1f)
![output9](https://github.com/iqbalstilllearning/sales-analysis-electronic-amazon/assets/105572256/be1f0d66-629b-40cb-b1c2-d85fb8dd88d3)
In terms of sales, the headphones category emerges as the most popular, boasting a total of 359,334 units sold. Conversely, the security & surveillance category lags behind as the least popular, with a total of 10,806 units sold. Shifting focus to average ratings, accessories & supplies claim the top spot, while wearable technology takes the bottom position in terms of consumer satisfaction.

- Are there specific trends in the categories of products sold in different years?
![output10](https://github.com/iqbalstilllearning/sales-analysis-electronic-amazon/assets/105572256/1aea7999-a6b7-4c0f-b563-a2878de43270)
Products in the headphones category were the most sold, especially in 2014 and 2015. Products in the computers & accessories category also saw an increase in sales from 2012 to 2015.

- Which electronic product brand is the most popular on Amazon based on sales or average ratings?
![output11](https://github.com/iqbalstilllearning/sales-analysis-electronic-amazon/assets/105572256/d8f3ae3d-b560-49f0-94a4-fef84abeb7b1)
![output12](https://github.com/iqbalstilllearning/sales-analysis-electronic-amazon/assets/105572256/2f46624b-bfd3-4a68-b488-ffc519ade6e4)
In terms of sales, bose and logitech emerges as the most popular, boasting a total of 29.2k units sold. Conversely, koolertron lags behind as the least popular, with a total of 344 units sold. Shifting focus to average ratings, plemo claim the top spot, while EINCAR takes the bottom position in terms of consumer satisfaction.

- Are there specific trends in the brands of products sold in different years?
![output13](https://github.com/iqbalstilllearning/sales-analysis-electronic-amazon/assets/105572256/d70e5bcf-20ff-46e5-9aca-7dfd1c6abf0c)
In 2014 and 2015, the sales trend for the Mpow and Bose brands increased drastically from previous years. In 2011, Sony became the best-selling brand and in 2012 it was taken over by Logitech.

# 3. User Segmentation
- What is the distribution of consumer gender across the entire dataset?
![output14](https://github.com/iqbalstilllearning/sales-analysis-electronic-amazon/assets/105572256/49c9598a-0b5c-49f7-a738-44c0baed2ca5)

- Can you identify and segment users based on model or category preferences?
![output15](https://github.com/iqbalstilllearning/sales-analysis-electronic-amazon/assets/105572256/b24ce604-f188-44ea-9b49-0edeaf5f21c2)
![output16](https://github.com/iqbalstilllearning/sales-analysis-electronic-amazon/assets/105572256/d71639cf-3347-42e1-a2b7-6e004497c13e)

The consumer gender distribution is nearly equal, with males accounting for 50.2% and females for 49.8%. Based on the model, the highest sales are attributed to the female model. Meanwhile, in terms of categories, headphones have the highest sales.






