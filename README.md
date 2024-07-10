## Sales-Dashboard
### Project Overview
This analysis unviels the sales activity of a super store in the United States. The analysis focuses on the different product category, state region and customers that complete the sales cycle. In this analysis, I developed visualization for each variable and indicate how it leads to the total sale and profit accumulated by the business. Firstly, I created a Key Performance Indicator(KPI)
The KPIs include;
- Profit
- Sales
- Customers and Total Orders. This gives us clarity on the critical aspect of performance, allowing us to focus on the variables that really matters in this analysis.

I also created visualization for the following;
- Sales by State: Represented by a map.
- Sales by Customer Segment: Represented by a column chart.
- Sales by Product Sub-category: Represented by a cumbo chart.
- Top 10 Customers: Represented by a vertical bar chart.
- Lastly, Rating For Cuisine Types: This shows the relationship / pattern between each rating for each cuisine.
![Screenshot (8)](https://github.com/NURATBASHIRU/Sales-Dashboard/assets/167202411/ad9b48d0-6175-4fae-9639-3565eb317101)


### Data Source
[Kaggle](https://www.kaggle.com/datasets/ahsan81/food-ordering-and-delivery-app-dataset)

### Tools
Excel Workbook
Tableau

### Data Structure
- order_id: Unique ID of the order
- customer_id: ID of the customer who ordered the food
- restaurant_name: Name of the restaurant
- cuisine_type: Cuisine ordered by the customer
- cost: Cost of the order
- day_of_the_week: Indicates whether the order is placed on a weekday or weekend (The weekday is from Monday to Friday and the weekend is Saturday and Sunday)
- rating: Rating given by the customer out of 5
- food_preparation_time: Time (in minutes) taken by the restaurant to prepare the food. This is calculated by taking the difference between the timestamps of the restaurant's order confirmation and the delivery person's pick-up confirmation.
- delivery_time: Time (in minutes) taken by the delivery person to deliver the food package. This is calculated by taking the difference between the timestamps of the delivery person's pick-up confirmation and drop-off information
### Result / Findings
Here is a link to the Tableau Dashboard created for this course; [Tableau](https://public.tableau.com/views/RESTAURANTDATAANALYSIS/Dashboard2?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
- Customers order more during the weekend
- American, Japanese and Italian Cuisines Have the highest order rate
- Shake Shack is the most popular restaurant in New York
- American, Japanese and Italian Cuisines have the highest frequency of '5 star' ratings. Although, we have a significantly high amount of "not given" - customers who have refused to give any rating at all out of the three categories provided - and I recommend that the restaurants should encourage customers to give a rating. so 'Rating' can be properly measured for each cuisine type.

### Recommendations
- The restaurants should increase staff strenght and food availability for weekend sale activities.
- The restaurants should create a niche for the American, Japanese and Italian dishes since they are the most ordered. The restaurants may as well invest more in these dishes while generally improving on the other dishes.
- Restaurants may also create varieties for these dishes. since customers are really invested in it, they mas as well be open to other options.
