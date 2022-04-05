# House Rocket - Data Analysis
 House Hocket (fictional) Company data analysis and hypothesis validation. 
 
<img width="1796" alt="house rocket wallpaper" src="https://user-images.githubusercontent.com/97196457/160295938-aaa525e3-6d60-4bc4-801a-b5f5982efe7c.png">

# 1. Business Problem 🤵
House Rocket is a digital platform in which its business model is based on the purchase and sale of properties. As a data scientist, my mission is to validate business hypotheses and recommend the purchase of properties based on criteria, as well as set the sale price and profit.

This dataset contains properties prices for King County, one of 39 counties in the US state of Washington.

<img width="1483" alt="king country" src="https://user-images.githubusercontent.com/97196457/161308932-b025b7d7-922b-4114-93d6-f182bf5a91ca.png">

# 2. Business Assumptions 👀
- The data analyzed was from May 2014 to May 2015;
- The seasons of the year, for simplicity, were defined as:
  - "Summer" starts in March and ends in August;
  - "Winter" starts in September and ends in February.

The criterion to recommend the properties to be acquired was based on the 'condition' attribute and the price:
- The "condition" attribute must be greater than or equal to 3. This is equivalent to the "'condition_type" attribute being regular or good;
- The property price must be less than the region's median price (zipcode).

# 3. Business Result

![dash results](https://user-images.githubusercontent.com/97196457/161179006-a7c0b79a-03a4-443a-a1bd-494ce14cab3e.png)

Result of the deal of 10579 properties:
- Total cost: US$4094212008.00;
- Total sold: US$4851233774.00; 
- Total profit: US$757021766.00.

# 4. Validation of Business Hypotheses

#### H1 - Properties with 3 bathrooms have a 15% MoM average growth.

![newplot (11)](https://user-images.githubusercontent.com/97196457/161087580-170206c2-9ab4-4d74-a27b-13f28a3441e6.png)

**False**! Average month-over-month growth for 3 bathroom properties is **23.28%**.

For comparison purposes, follow the chart with all the properties:

![MoM all](https://user-images.githubusercontent.com/97196457/161171579-75129e0b-060a-493c-a3ed-0d47e76505fd.png)

#

#### H2 - Properties without a basement have a total area (of the lot) 40% larger, on average, than properties with a basement.

![average batch per basement](https://user-images.githubusercontent.com/97196457/161133267-24e18a7a-4fbb-4334-bbf7-57d49a277222.png)

**False**! Properties without a basement have a total area (of the lot) **22,56%** larger, on average, than properties with a basement.

#

#### H3 - Properties with water view are 20% more expensive on average.

![average price per water view](https://user-images.githubusercontent.com/97196457/161134150-54eca024-822f-4820-8b7f-caf131f26d33.png)

**False**! Properties with water view are **212,64%** more expensive on average.

#

#### H4 - Properties with a construction date less than 1955 are 20% cheaper on average.

![average price per year built](https://user-images.githubusercontent.com/97196457/161134770-01978059-0cc6-454d-a433-3a0f9e26166d.png)

**False**! Properties with a construction date less than 1955 are 0.78% cheaper on average, an irrelevant difference that can be seen in the graph.

# 5. Conclusion 📍

I consider that most of the objectives have been completed that have already determined more elaborate properties to be purchased, in addition to stipulating a sale value based on seasonality. As well as the validation of hypotheses.

I haven't completed all the goals, like deploying an online dashboard, to start a machine learning project right now, and I believe this will be more beneficial for me. 

# 6. Next Steps 👣

- Create and verify more business hypotheses;
- Generate top 5 insights;
- Analyze correlation in depth to gain insights;
- Deploy a online dashboard to CEO.

# 7. Tools Used 🛠️
- Python 3.8.12;
- Jupyter Notebook;
- Git/GitHub/GitHub Desktop;
- Adobe Photoshop;
- Notion;
- Vegas Pro 15.

#


<a href="#top">Back to top</a>
