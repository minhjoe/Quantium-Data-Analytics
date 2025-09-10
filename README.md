# Quantium-Data-Analytics

This repository contains results of the completed tasks for the **Quantium Data Analytics Virtual Experience Program** by Forage.  
The program is designed to replicate life in the Retail Analytics and Strategy team at Quantium, using Python.

---

## Dependencies

To run the project, the following dependencies are required:

- Jupyter Notebook (install)  
- pandas (install)  
- NumPy (install)  
- xlrd (install - Anaconda | install - PyPI)  
- Matplotlib (install)  
- seaborn (install)  

---

## Introduction

Quantium has had a data partnership with a large supermarket brand for the last few years who provide transactional and customer data. You are an analyst within the Quantium analytics team and are responsible for delivering highly valued data analytics and insights to help the business make strategic decisions.

Supermarkets will regularly change their store layouts, product selections, prices and promotions. This is to satisfy their customer’s changing needs and preferences, keep up with the increasing competition in the market or to capitalise on new opportunities. The Quantium analytics team are engaged in these processes to evaluate and analyse the performance of change and recommend whether it has been successful.

In this program you will learn key analytics skills such as:

- Data wrangling  
- Data visualization  
- Programming skills  
- Statistics  
- Critical thinking  
- Commercial thinking  

---

## Task 1: Data Preparation and Customer Analytics

**Objective:**  
Conduct analysis on your client's transaction dataset and identify customer purchasing behaviours to generate insights and provide commercial recommendations.

**Background:**  
You are part of Quantium’s retail analytics team and have been approached by your client, the Category Manager for Chips, who wants to better understand the types of customers who purchase Chips and their purchasing behaviour within the region.

The insights from your analysis will feed into the supermarket’s strategic plan for the chip category in the next half year.

**Task:**  
We need to present a strategic recommendation to Julia that is supported by data which she can then use for the upcoming category review. However, to do so we need to analyse the data to understand the current purchasing trends and behaviours. The client is particularly interested in customer segments and their chip purchasing behaviour. Consider what metrics would help describe the customers’ purchasing behaviour.

**Steps to get started:**
- Download the resource CSV data files and begin performing high level data checks such as:
  - Creating and interpreting high level summaries of the data  
  - Finding outliers and removing these (if applicable)  
  - Checking data formats and correcting (if applicable)  
- Derive extra features such as pack size and brand name from the data.  
- Define metrics of interest to enable you to draw insights on who spends on chips and what drives spends for each customer segment.  

**Important attributes:**  
- **LIFESTAGE**: Customer attribute that identifies whether a customer has a family or not and what point in life they are at e.g. are their children in pre-school/primary/secondary school.  
- **PREMIUM_CUSTOMER**: Customer segmentation used to differentiate shoppers by the price point of products they buy and the types of products they buy. It is used to identify whether customers may spend more for quality or brand or whether they will purchase the cheapest options.  

**Outcome:**  
Form a strategy based on the findings to provide a clear recommendation to Julia the Category Manager, ensuring that insights have a strong commercial application.

---

## Task 2: Experimentation and Uplift Testing

**Objective:**  
Extend your analysis from Task 1 to help you identify benchmark stores that allow you to test the impact of the trial store layouts on customer sales.

**Background:**  
You are part of Quantium’s retail analytics team and have been approached by your client, the Category Manager for Chips, who has asked us to test the impact of the new trial layouts with a data-driven recommendation on whether or not the trial layout should be rolled out to all their stores.

**Task:**  
Julia has asked us to evaluate the performance of a store trial which was performed in stores 77, 86 and 88.  

To get started, use the `QVI_data` dataset (or your output from Task 1) and consider the monthly sales experience of each store. This can be broken down by:  

- Total sales revenue  
- Total number of customers  
- Average number of transactions per customer  

Create a measure to compare different control stores to each of the trial stores. To do this, write a function to reduce having to re-do the analysis for each trial store. Consider using Pearson correlations or a metric such as a magnitude distance (e.g. `1 - (Observed distance – Minimum distance) / (Maximum distance – Minimum distance)`) as a measure.  

Once you have selected your control stores, compare each trial and control pair during the trial period. You want to test if total sales are significantly different in the trial period and if so, check if the driver of change is more purchasing customers or more purchases per customer, etc.  

**Outcome:**  
Provide a data-driven recommendation on whether the trial store layouts should be rolled out more broadly.

---

## Task 3: Analytics and Commercial Application

**Objective:**  
Use your analytics and insights from Task 1 and Task 2 to prepare a report for your client, the Category Manager.

**Background:**  
Task 3 is targeted specifically at building your ability to recognise commercial, actionable insights from your analysis and displaying it in a clear and concise way for your client, with minimal jargon. At Quantium, our analyst graduates sometimes work as what we like to call "hybrids" (a mix of analyst and consultant duties) so developing your presentation skills early is a huge win!

As both technical tasks 1 and 2 were open ended in terms of insights, this model answer will focus on the layout and the order of your inclusions, including where to include graphs, taglines, written insights and recommendations.

As part of Quantium’s retail analytics team, you have been conducting a range of analysis on transaction and purchase behaviour data to provide key recommendations to your client, the Category Manager of Chips, who is putting together their strategic plan.

**Task:**  
With our project coming to an end, it is time to send a report to Julia, based on our analytics from the previous tasks. We want to provide her with insights and recommendations that she can use when developing the strategic plan for the next half year.

As best practice at Quantium, we like to use the "Pyramid Principles" framework when putting together a report for our clients. If you are not already familiar with this framework you can find quick introductions online.

**For this report, we need to include:**
- Data visualisations  
- Key callouts  
- Insights  
- Recommendations and/or next steps  

**Considerations for the presentation/report:**
- Data literacy level of your audience  
- Table of contents / agenda  
- Problem statement / purpose  
- Overview and context  
- Content balance  
- Layout and content display  
- Summary / next steps  

---

## Key Learning Outcomes

- Performing detailed data wrangling and feature engineering.  
- Generating actionable insights from customer transaction data.  
- Designing and evaluating experiments to test business changes.  
- Communicating findings and recommendations effectively using commercial thinking.  
- Applying structured frameworks (e.g., Pyramid Principles) to create client-ready reports.  

