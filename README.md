# AtliQ Hardware - Business-Insight-360
## Project Overview 
This Power BI project focuses on analyzing in-store and online sales growth of the company. The dashboard addresses stakeholder queries in finance, sales, marketing, and supply chain, providing a comprehensive overview of the company's performance in these key areas.This empowers decision-makers with valuable information to navigate and optimize AtliQ Hardware's performance across diverse business realms.

## What I learnt from this Project - Key Learnings :
### Data Analysis Process : 
Importing data from SQL/Excel >Transforming data>KPIs with DAX >> Building tables >> Data modeling with star/snowflake schema >> Creating and publishing reports online with auto-refresh for SQL and Excel data files.

### Technical Skills : 
. Data Collection and Exploration -Collecting data from various sources, analyzing and uncovering insights to understand patterns and relationships.

· Power Query (M language) - It is an ETL (Extract, Transform, Load) tool for Power BI.

· Data Modeling -Involves establishing relationships between tables, defining calculated columns and measures. It helps in organizing data effectively to enable users to extract data from multiple tables.

· Data Analysis Expressions (DAX)- It is a language used in Power BI to create custom calculations or aggregations by building measures and calculated columns.

· DAX Studio- Used for performance optimization.

· Power BI Service: A cloud-based platform that helps users to create, share, edit and collaborate on interactive reports and dashboards.

### Power BI core techniques implemented : 
• Structuring the Business model

• Calculated columns and Measures

• Implementing Parameters

• Bookmarks to switch between two visuals

• Page navigation techniques

• Important DAX functions

• Dynamic titles on the visuals based on the applied filters

• KPI indicators

• Conditional formatting using icons or background colour

• Collaboration, workspace, access permissions in Power BI services.

### Dashboards and Visualization : 
· Utilizing various visualization techniques.

· Following 15 guidelines for dashboard design.

### Business Fundamentals :
· Structuring and undersatanding the Business model.

· Understanding Finance, Sales, Marketing & Supply Chain functions.

· Gaining consumer goods business domain knowledge.

### Communication skills : 
· Utilizing UAT (User Acceptance Test) on improving good communication, collaboration and meeting stake holder needs.

· Recognizing the importance of stakeholder feedback.

### Business Terms used :
• Gross price • Pre-invoice deductions • Post-Invoice deductions • Net Invoice sale • Net Sales • Gross Margin • COGS - cost of goods sold • Manufacturing Cost • YTD - Year to Date • YTG - Year to Go

## About AtliQ Hardware
AltiQ Hardware is a rapidly expanding company in recent years whose head office is situated in Delhi, India and they have many regional office through out the India. AtliQ has established its presence across the global market. Specializing in the sale of computers and computer accessories and the company operates through three primary channels:

![Alt text](D:\1AA Code_basics\Altiq_project\Inkedgit_image2.jpg)

Despite its remarkable growth, AltiQ Hardware recently encounters unexpected setbacks with the launch of a new store. This setback was identified through surveys, intuitive observations and comprehensive Excel analyses but AltiQ Hardware's competitors possess well-equipped analytics teams, enabling them to make informed, data-driven decisions. In response to these challenges, AltiQ Hardware recognizes the importance of establishing its own analytics team. The objective is to leverage data-driven insights for better decision-making and to ensure the company's growth and competitiveness within the industry.

## About Dataset :
In a database design, there are typically two primary types of tables: Dimension tables and Fact tables. Fact table : A fact table contains records that combine attributes from different dimension tables.Examples of Fact tables include recording of sales transactions, order quantities, or financial transactions.

Dimension table : It provides the context and background information for the measures recorded in the fact table.Examples of Dimension tables include tables storing customer names, addresses, or product categories.

### Terms included in the dataset .
Two Excel/CSV files named gdb041 and gdb056 were imported into Power BI

gdb041 :

1. **dim_customer**
   - Markets - 27 [India, China, etc]
   - Channels - 3 [Retail, Direct, Distributor]
   - Platforms - Brick & Mortar, E-commerce
   - Customers

2. **dim_product**
   - Divisions - 3
   - Segments - 6
   - Category - 14
   - Variants


3. **dim_market**
   - Markets
   - Regions - 4
   - Sub_zones - 7


4. **dim_date**
   -date,month
   -fiscal year - A fiscal year is a 12-month period that a company uses for financial planning and reporting. It may not necessarily match the calendar year.
   -ytd/ytg

5. fact_forecast_monthly This table is used to forecast the customer’s need in advance, which can help in Higher customer satisfaction and cost effective Inventory

6. fact_sales_monthly This table contains the number of products sold and its details

gdb056 :

1. freight_cost : This table contains details of travel,employement cost and other cost for each market.

2. gross_price : Contains details of gross prices of each products.

3. manufacturing_cost : Contains details of manufacturing costs of each products

4. Pre_invoice_dedutions : Discounts in percenatage fpr each customers

5. Post_invoice_deductions : Post invoice deductions and other deductions details 

Note : The data records were imported from SQL database . Additionaly few of the excel/CSV files were imported later.

## Data Modeling
Data modeling is the process of representing relationship between the tables .

Snowflake scheme is used as a method for data modeling in this project.In a snowflake schema, the data is organized into a hierarchy of multiple related tables, resembling the shape of a snowflake when visualized. It involves defining and organizing data elements, their attributes, and the relationships between them to create a blueprint for how data should be stored, accessed, and managed .

The main idea behind snowflake modeling is to normalize the data by breaking it down into smaller, more manageable tables with fewer redundant data, reducing data duplication and improving data integrity.

## Project Outcome :
By utilizing this report, stakeholders gain valuable insights to make informed decisions across different departments. Whether it's optimizing finances, boosting sales, refining marketing strategies or enhancing supply chain efficiency, the Power BI dashboard equips decision-makers with the tools to drive effective and strategic actions ensuring AtliQ Hardware stays on the path of sustained growth and success.

