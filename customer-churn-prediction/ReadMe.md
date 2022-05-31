# Customer Churn analysis

## Snowpark Python for Data Science
<img src="arch.jpg" />

<b>
As a data engineering and data science team member at a Telecom company, we have been tasked to build an end to end data pipeline and model in snowflake to support customer churn analysis by data science team. For this we have some customer data that our data science team would need.  We are responsible to build a feature store for the data science team. </b>


# Challenges
* As Data Engineers we want to build an end to end pipeline within snowflake and reduce the overall cost and technology footprints so that there are less point of failures
* On one hand we have customer billing and demographics data saved in semi structured format (PARQUET) and on other we have unstructured data in the form of emails
* We want to simplify the data pipeline by ingesting and processing the data closer within snowflake
But there are multiple developers persona in our team. Some know SQL, Some are Java and python professionals
* We also need to make data scientist’s life easier by cleaning, formatting, transforming and creating a feature store for them to refer in churn analysis

# Machine Learning Pipeline

Run the notebooks starting from **01~** to **03**. we will go through the implementation of each one of the steps in the Machine Learning Pipeline. 

We will discuss:

1. **Data Preparation and Analysis**
2. **Feature Engineering**
3. **Feature Selection**
4. **Model Training**
5. **Obtaining Predictions / Scoring**