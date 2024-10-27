
**Pizza Sales Analysis (2015)**

**1. Overview of the Data**
The dataset used for this analysis contains **48,620 rows** of sales data from 2015, focusing on pizza sales. The data was cleaned and processed to ensure accurate insights and analysis.

**2. Data Cleaning and Processing**
Several data cleaning steps were performed to prepare the data for analysis:
- **Pizza Size Column**: Values in the *Pizza_size* column were replaced with standard sizes.
- **New Columns**: 
  - *Total_orders*: A column created to sum the number of orders.
  - *Month and Order_day*: Columns derived from the date to track monthly and daily trends.

**3. Formula for Total Orders**
The formula used to calculate total orders is based on the data transformations applied during the cleaning process. 
**Formula-** =1/COUNTIF(B:B,[@[order_id]])     
              _where B:B = order_id column, [@[order_id]] = 1st cell of order_id_

![formula](https://github.com/user-attachments/assets/3a3a634d-aa74-4b6c-a423-fb1eeca0c898)


**4. Insights from the Dashboard**
![Dashboard Img](https://github.com/user-attachments/assets/9aff04de-3d0f-45af-bec6-f538e44f3555)

The dashboard provides several key insights into pizza sales performance for 2015:

- **Total Revenue**: Pizza sales generated a revenue of **$817,860**.
- **Average Order Value**: The average order value was **$38.31**, reflecting customer spending habits.
- **Total Pizza Sold**: A total of **49,574 pizzas** were sold throughout the year.
- **Total Orders**: There were **21,350 total orders**, with an average of **2.32 pizzas per order**.

### Trends and Distribution:
- **Daily Sales Trends**: 
  - The highest number of orders occurred on **Fridays** and **Saturdays**, indicating peak sales on weekends.
  - Monday recorded the lowest number of orders.

- **Hourly Sales Trends**:
  - Peak order times were from **6 PM to 8 PM**, with the highest spike at **7 PM**.
  - Early mornings and late nights had minimal sales activity.

- **Category-wise Sales**:
  - The **Classic** category was the top seller, with **14,088 pizzas sold**, followed by **Supreme** with **11,967**.
  - **Veggie** and **Chicken** categories also performed well with **11,469** and **11,050** pizzas sold, respectively.

- **Size-wise Sales**:
  - **Large pizzas** made up the largest portion of sales (45.89%), followed by **Medium pizzas** (30.49%).
  - **Regular and X-Large** sizes accounted for smaller portions, with **Regular** at 21.77% and **X-Large** at 1.72%.
  
- **Top 5 Pizza Sellers**:
  - The top-selling pizza was **The Classic Deluxe** with **2,653** orders.
  - Other popular pizzas included **The Barbecue Chicken**, **The Hawaiian**, **The Pepperoni**, and **The Thai Chicken**.

- **Bottom 5 Pizza Sellers**:
  - The least popular pizza was **The Soppressata** with only **61 orders**.
  - Other pizzas with low sales included **The Spinach Supreme**, **The Calabrese**, and **The Mediterranean**.

**5. Visualizations**
The dashboard uses various visualizations, including:
- Bar charts for daily and hourly trends.
- Pie charts for category-wise and size-wise sales distribution.
- Ranked bar charts for the top 5 and bottom 5 pizzas.

These visuals provide a clear and easy-to-understand representation of pizza sales performance.

