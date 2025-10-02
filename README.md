ChocoCrunch Analytics
A comprehensive data analytics project for global chocolate products, extracting data from the OpenFoodFacts API, cleaning and analyzing nutritional information, and providing insights through both SQL and Power BI visualizations.
Project Overview
ChocoCrunch Analytics collects and explores data for ~12,000 chocolate products worldwide. The focus is on nutritional analysis, product categorization, and trend visualization to aid health-conscious decisions and industry benchmarking.
Key Features
o	Automated extraction of chocolate product data from OpenFoodFacts API.
o	Advanced pandas-based cleaning to manage nulls, duplicates, and datatype issues.
o	Feature engineering, including calculation of sugar-to-carb ratio and food processing categories.
o	SQL database schema designed for scalable bulk insertion and relational analytics.
o	Exploratory Data Analysis and visualization using matplotlib, seaborn, and Power BI.
Directory Structure
o	Choco_Crunch_Analysis.ipynb – Main notebook for API extraction, data cleaning, transformation, feature engineering, and EDA.
o	Final_conn.ipynb – Contains the SQL schema, Python bulk insertion logic, and table creation for MySQL/XAMPP or cloud databases.
o	ChocoCrunch-Analytics.pptx – Executive summary and dashboard highlights showing the workflow and core findings.
Technology Stack
o	Python (pandas, numpy, matplotlib, seaborn, requests, pymysql)
o	SQL (MySQL, TiDB Cloud/XAMPP)
o	Power BI (for interactive dashboards)
o	API-first architecture for scalable data extraction and transformation
Installation & Setup
Dependencies:
Install required packages via pip:
o	pip install pandas numpy matplotlib seaborn requests pymysql
Database Configuration:
o	Set up MySQL Cloud with required tables.
o	Update DB credentials in the notebooks as needed.
API Extraction:
o	Run the main notebook to pull data from OpenFoodFacts, clean, and transform.
Data Loading:
o	Use Final_conn.ipynb to load cleaned data into your SQL database.
Visualization:
o	Use EDA sections or export to Power BI for creating dashboards.
Usage Workflow
o	Run API extraction to generate raw datasets.
o	Clean and transform data, addressing missing and outlier entries.
o	Perform feature engineering (e.g., sugar-to-carb ratios, ultra-processed categorization).
o	Load processed data to SQL, ensuring foreign key relations.
o	Execute SQL queries for summary statistics and market insights.
o	Visualize analytics and derived metrics in notebooks and Power BI.
Core Analysis & Insights
o	Identification of top chocolate brands by market presence.
o	Health impact assessment through derived nutrition metrics (e.g., caloric, sugar distributions).
o	Classification of products by NOVA processing group and ultra-processing status.
o	Market share and competitive analysis via SQL and dashboard visualizations.
Power BI Demo
o	Interactive bar charts, pie charts, and box plots summarizing key nutrition and product distribution metrics.
o	Dashboard available for demo of findings and visual exploration.
Contributing
Please use issues or pull requests to suggest improvements or report bugs. Ensure that data privacy and compliance are maintained with all source APIs.
License
Open-source for educational and non-commercial use. Refer to included license or specify your preferred sharing terms.



