# TATA-Online-Retail

### Dashboard Link : 

### Data Source: CSV (online retail dataset TATA)

## Problem Statement:
The objective of this project is to analyze retail transaction data to generate actionable business insights that support data-driven decision-making. Using the dataset provided by the Tata Group via Forage, the goal is to evaluate key performance indicators such as revenue trends, customer purchasing behavior, product performance, and regional sales distribution.

The analysis aims to identify high-performing products and regions, detect patterns in customer repeat purchases, and uncover opportunities to improve sales and profitability. Additionally, the project focuses on cleaning and transforming raw data, creating meaningful visualizations, and presenting insights through an interactive dashboard (e.g., in Power BI) to assist stakeholders like the CEO and CMO in strategic planning.

### Steps followed:

- Task 1 :

To prepare for your meeting, you need to draft questions that you think will be important and relevant to the CEO and CMO. This preparation will be your guide as you develop your presentation.

For this task, you are only required to draft the questions. Make sure to think both quantitatively and qualitatively.

You’ve been provided a dataset in the resources below to use as the basis for your exploration. Review this data, taking note of what information has been provided, what insights you can garner, and what is relevant to both the CEO and CMO respectively.

Create a set of four questions that you anticipate each business leader will ask and want to know the answers to. Make sure you differentiate your questions, as both the CEO and CMO view business decisions through different lenses.

Submit your eight questions in total (4 for the CEO and 4 for the CMO) in the text submission box below. 

- Submission:

[1] Which product category has the highest demand, and which has the lowest demand?
	This analysis helps the CEO see which products are popular and which are underperforming. Based on this, the company can invest more in successful categories and work     on improving the less successful ones.

[2] Are there specific months with higher and lower revenues? 
	It allows the CEO to make better decisions for increasing sales during low-performing periods and maintaining growth during high-performing months.
	
[3] Which countries show the highest and lowest sales performance?
	By identifying the highest and lowest sales-performing countries, the CEO can evaluate market strength in different regions. This insight supports better decision-making, such as focusing more resources and marketing efforts in high-performing countries, and developing targeted strategies to improve sales in weaker markets.

[4] Which items have the maximum and minimum unit price values?
	This analysis helps the CEO identify the most expensive and least expensive products in terms of unit price. By understanding price variations, the CEO can evaluate product positioning in the market.

[5] Which customers have the highest repeat purchases, and how much revenue do they generate?
	This question helps the CMO identify the most loyal customers who make repeat purchases and contribute significantly to revenue. By understanding who these customers are, the CMO can measure customer loyalty and overall value. This insight helps in building strong retention strategies, such as loyalty programs.

[6] Which regions show the strongest customer engagement?
	This question helps the CMO understand where customers are most active and engaged with the brand. By analyzing regions or demographic groups with the highest engagement, the CMO can identify the most responsive audiences. This insight helps in improving marketing strategies, targeting the right customer segments, 	and allocating advertising budgets more effectively.

[7] Which months have the highest repeat customer activity?
	CMO can recognize seasonal loyalty patterns and customer buying behavior. This insight helps in planning targeted retention campaigns, loyalty offers, and personalized marketing during high-activity months. 

[8] What percentage of total customers are repeat customers?
	A higher percentage of repeat customers indicates strong customer satisfaction and effective retention strategies. This insight helps the CMO evaluate the success of marketing campaigns and loyalty programs. It also supports decision-making to improve customer experience, increase retention, and reduce customer churn by focusing on strategies that encourage customers to buy again.

- Task 2 :

In this task, you will be required to read the questions carefully and understand the business requirement. Once you have an idea of what is required from the perspective of the CEO and CMO, you will need to come up with the perfect visual, which will illustrate what the senior managers are looking for in each scenario. Remember, data can be presented in multiple types of charts, but you are required to select the visual that would best display the information which is being presented.

You will be provided with resources on how to select visuals based on the different scenarios. These are available in the resources below. These resources will help you get an idea of which visual to select for the given business scenario and will also guide you on how to choose the right chart or graph for your data. Each question will contain a unique scenario, and you will be expected to answer the questions based on that scenario.

To complete this task, answer the multiple-choice quiz. Start the quiz by clicking ‘Start your quiz’ below. Please note there are 5 multiple-choice questions to complete in this task. Please be patient as each question loads.



<img width="1036" height="509" alt="Image" src="https://github.com/user-attachments/assets/06ccbb30-2020-45ea-ba83-b48126980fff" />


<img width="1036" height="514" alt="Image" src="https://github.com/user-attachments/assets/58ad8ae1-4031-4dfe-98e4-6ba1adde63f6" />


<img width="1021" height="506" alt="Image" src="https://github.com/user-attachments/assets/7119c7f7-f8c7-4658-8672-d9e2a4ff8eac" />


<img width="1059" height="519" alt="Image" src="https://github.com/user-attachments/assets/f65dec94-0c1f-4af4-b39c-4d90a250fba1" />


<img width="1006" height="534" alt="Image" src="https://github.com/user-attachments/assets/ecb8a3ad-ee49-476f-b68d-d9861926c5cb" />


- Task 3 :
In this task, you will create the visuals around four of the questions that the CEO and CMO have requested. You can use either Tableau or Power BI to create the visuals and we’ve provided the data in the resources below.


### Cleaning Data:

- Step 1: Converted data types for all columns using Power Query and performed a comprehensive data quality check to ensure accuracy and consistency.

- Step 2: Applied a filter in Power Query to exclude negative values by restricting the Quantity column to values greater than 1.

- Step 3: Applied the same filtering approach in Power Query to ensure all values in the Unit Price column are positive by setting the filter to greater than 0.


Question 1
The CEO of the retail store is interested to view the time series of the revenue data for the year 2011 only. He would like to view granular data by looking into revenue for each month. The CEO is interested in viewing the seasonal trends and wants to dig deeper into why these trends occur. This analysis will be helpful for the CEO to forecast for the next year.


- Step 4:Created a calculated column to derive revenue by multiplying the Quantity and Unit Price columns.

- Step 5: Created the first report view page aligned with the initial business question.
  
- Step 6: Sourced the TATA logo from the official website and set it as the canvas background.

- Step 7: Customized the report aesthetics by adjusting the wallpaper color for better visual appeal.

- Step 8: Added a line chart to visualize total values over time.

- Step 9: Configured the chart to display data for the year 2011 and included all months within that year for detailed analysis.

<img width="933" height="499" alt="Image" src="https://github.com/user-attachments/assets/e4ed4a2b-53e9-46ff-8560-1ed7e3d17257" />  


Question 2
The CMO is interested in viewing the top 10 countries that are generating the highest revenue. Additionally, the CMO is also interested in viewing the quantity sold along with the revenue generated. The CMO does not want to have the United Kingdom in this visual.

- Step 10: Addressed the second requirement by selecting a bar chart to represent total quantity and total revenue by country.

- Step 11: Applied the Top N filter to display only the top 10 countries based on the required metric.

- Step 12: Excluded the United Kingdom as per the requirements by using the basic filtering option in the filter pane and unchecking the specific country.

<img width="938" height="498" alt="Image" src="https://github.com/user-attachments/assets/3824e481-665b-4ba4-b2ff-23730463e181" />


Question 3
The CMO of the online retail store wants to view the information on the top 10 customers by revenue. He is interested in a visual that shows the highest revenue-generating customer at the start and gradually declines to the lower revenue-generating customers. The CMO wants to target the higher revenue generating customers and ensure that they remain satisfied with their products.

- Step 13: For the third report view, select a column chart to visualize the data.

- Step 14: Configured the chart to represent total revenue by customers.

- Step 15: Applied a Top N filter to display the top 10 customers based on total revenue.

<img width="931" height="493" alt="Image" src="https://github.com/user-attachments/assets/8c96f5f7-93a2-44cc-9d73-70885f43eef4" />
  

Question 4
The CEO is looking to gain insights on the demand for their products. He wants to look at all countries and see which regions have the greatest demand for their products. Once the CEO gets an idea of the regions that have high demand, he will initiate an expansion strategy which will allow the company to target these areas and generate more business from these regions. He wants to view the entire data on a single view without the need to scroll or hover over the data points to identify the demand. There is no need to show data for the United Kingdom as the CEO is more interested in viewing the countries that have expansion opportunities.

- Step 16: For the final report view page, select a map visualization to display total units sold by country.

- Step 17: Used a filled map to enhance visual clarity and provide better geographical representation compared to a standard map.

- Step 18: Excluded the United Kingdom as per the requirements by applying a filter in the filter pane.

- Step 19: Successfully submitted the report for the TATA project.

<img width="854" height="432" alt="Image" src="https://github.com/user-attachments/assets/181440e7-1abe-4937-b286-046879bdfd51" />

- Step 20: Develop a script and record a video presenting findings to the CEO and CMO based on the four questions they asked and the visuals created in the previous tasks.


<img width="762" height="446" alt="Image" src="https://github.com/user-attachments/assets/d6e495b4-5c5b-4712-ab41-c13341418865" />




