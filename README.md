# Supply-Chain-Forecasting-System

**Supply Chain Data Forecasting Model**

**Overview**
This repository contains a project designed to forecast sales and market trends using a machine learning model developed with Python and deployed on AWS. The project aims to help businesses optimize their supply chain processes by providing predictive analytics based on historical data such as sales, product category, and market trend indicators.

The project leverages several AWS services, including S3 for data storage, SageMaker for machine learning model training, and QuickSight for data visualization.

**Project Architecture**

  1.	Data Storage: The raw CSV dataset is stored in an Amazon S3 bucket.
  2.	Data Processing: Data is cleaned, transformed, and encoded using Python libraries such as pandas and scikit-learn.
  3.	Model Development: A Linear Regression model is used for demand forecasting.
  4.	Visualization: Data insights are visualized using AWS QuickSight, enabling users to create interactive charts and reports.
  5.	Deployment: The trained model is saved in a pickle file and uploaded to the S3 bucket for future use.

**First Visualization**
•	X-Axis (Date): The same time period as the first chart, but this time without segmentation by market trend.
•	Y-Axis (Sum of Sales): Displays the total sales value, but in a more general view.
•	**Insight**: This visualization provides a cleaner, overall trend of sales without the market trend context. You can observe the consistency or variance in sales over time but miss the deeper insight of how sales align with the market trend. The sharp fluctuations in sales values are more prominent, showing a high degree of variability day-to-day.



 
Results (via QuickSight for Visualized Chart of the database insights from the analysis of the raw CSV file)
<img width="1658" alt="Screenshot 2024-10-02 at 11 44 23 AM" src="https://github.com/user-attachments/assets/1bcca084-f786-49a0-9448-893e11d48147">




**Second  Visualization** (Sum of Sales by Date and Market Trend):
	•	X-Axis (Date): Represents the time period (from January 2023 to July 2023).
	•	Y-Axis (Sum of Sales): Displays the total sales value.
	•	**Market Trend as Color**: The three market trends (positive, neutral, negative) are differentiated by distinct colors, making it easier to observe how each trend correlates with sales volume. For example, there may be fluctuations in sales that correlate with negative trends and higher peaks with positive trends.
	•	**Insight**: This visualization is effective for understanding how market sentiment (positive, neutral, or negative) impacts the sales over time. It shows that positive market trends generally align with higher sales, while negative trends correlate with lower sales, although both have fluctuations.




<img width="1480" alt="Screenshot 2024-10-02 at 11 43 38 AM" src="https://github.com/user-attachments/assets/8244b1ac-b926-44e9-a543-4ae2082a238f">




**Code**
<img width="1154" alt="Screenshot 2024-10-02 at 11 24 14 AM" src="https://github.com/user-attachments/assets/228db15c-6a0e-4b12-8ad2-6e139b27ebed">

<img width="1129" alt="Screenshot 2024-10-02 at 11 24 18 AM" src="https://github.com/user-attachments/assets/a21181d6-475a-4926-bb73-303f9afcaafd">










