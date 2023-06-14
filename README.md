

# Northwind Traders Sales Performance Dashboard


![Screenshot 2023-06-13 182747](https://github.com/Harsh-2412/Northwind_Traders/assets/110857650/9b39a5c8-2470-49b6-844e-87e5a49090ec)

Business Problem:
As a BI Developer for Northwind Traders, the primary objective is to develop a high-level KPI dashboard for the executive team. The purpose of this dashboard is to provide a quick and comprehensive understanding of the company's performance in key areas, including:
>  * Sales Trends: 
>  * Product Performance:
>  * Key Customers:
>  * Shipping Costs: 
  ----
## **Solution**


### **Part 1:**

To achieve this objective, the project attempts to follow a real-world scenario where data is stored in the cloud and data pipelines are employed for automation. The dataset is uploaded into AWS S3 buckets , and Database, schema, and Snowpipe(data pipeline) are created in Snowflake to facilitate efficient data ingestion.
Power BI is utilized for data import using the IMPORT method, which offers advantages such as improved query performance, version control and handling Data manipulations. Power Query is used for data cleaning, manipulation, and data modeling to establish relationships between different entities within the dataset.

### **Part 2:**

In the second phase of the project, the data is categorized into four main areas: 
* Revenue patterns
* Product metrics
* Key customers
* Freight analysis.

Analytics techniques like ABC classification and RFM analysis, are applied to extract valuable insights.

> * ABC Classification: This technique categorizes products based on their revenue contribution, assigning them into groups such as "A" for high-value products, "B" for medium-value products, and "C" for low-value products. This helps in understanding the importance and impact of different products on overall revenue.
 > * RFM Analysis: RFM stands for Recency, Frequency, Monetary, and it is used to segment customers based on their transactional behavior. By analyzing the recency of customer purchases, their frequency of purchases, and the monetary value of their transactions, customers can be segmented into different groups, such as "VIP" customers, "Regular" customers, and "Churned" customers. This segmentation allows for targeted marketing and customer retention strategies.


The insights obtained from these analyses are then translated into meaningful visualizations using Power BI. The resulting KPI dashboard provides a comprehensive view of sales trends, product performance, key customers, and shipping costs. It not only empowers the executive team to make informed business decisions but also enables ongoing analysis and decision-making as new data is incorporated.
In conclusion, the Northwind Traders Project showcases the utilization of cloud-based data storage, data pipeline automation, and advanced data analytics techniques. By implementing this project, Northwind Traders can easily effectively monitor and analyze sales performance, product metrics, customer behavior, and shipping costs, leading to enhanced decision-making and business growth.
