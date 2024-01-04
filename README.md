# Insights_Supply_Chain_Issue - Power BI
- This project is a part of [Codebasics](https://codebasics.io/challenge/codebasics-resume-project-challenge) Challenge #2: Generate Insights to Solve a Supply Chain Issue in the FMCG domain 

Problem Statement

- Link to [Portfolio Website](https://codebasics.io/portfolio/Amogh-Sawant)
- Link to [Live Dashboard](https://www.novypro.com/project/insights-for-supply-chain-issue)

## Problem statement

Problem Statement
AtliQ Mart is a growing FMCG manufacturer headquartered in Gujarat, India. It is currently operational in three cities Surat, Ahmedabad, and Vadodara. They want to expand to other metros/Tier 1 cities in the next 2 years.

AtliQ Mart is currently facing a problem where a few key customers did not extend their annual contracts due to service issues. It is speculated that some of the essential products were either not delivered on time or not delivered in full over a continued period, which could have resulted in bad customer service. Management wants to fix this issue before expanding to other cities and requested their supply chain analytics team to track the ’On time’ and ‘In Full’ delivery service level for all the customers daily basis so that they can respond swiftly to these issues.

The Supply Chain team decided to use a standard approach to measure the service level in which they will measure ‘On-time delivery (OT) %’, ‘In-full delivery (IF) %’, and OnTime in full (OTIF) %’ of the customer orders daily basis against the target service level set for each customer.

### Task List
You are a data analyst who has been provided with sample data to work on the following tasks.
- Create the metrics according to the metrics list.
- Create a dashboard according to the requirements provided by stakeholders in the business review meeting. You will be provided with the transcript of this business review meeting in comic form.
- Create relevant insights not provided in the metric list/stakeholder meeting.

## Data Model

<p align="center">
    <img src='https://github.com/amoghsawant17/Insights_Supply_Chain_Issue/blob/main/views_snap/data_model.png' height="400">
</p>

## Home View

<p align="center">
    <img src='https://github.com/amoghsawant17/Insights_Supply_Chain_Issue/blob/main/views_snap/home.png' width="600">
</p>

## Overview

<p align="center">
    <img src='https://github.com/amoghsawant17/Insights_Supply_Chain_Issue/blob/main/views_snap/overview.png' width="600">
</p>

## Customer Insights View

<p align="center">
    <img src='https://github.com/amoghsawant17/Insights_Supply_Chain_Issue/blob/main/views_snap/customer_insights.png' width="600">
</p>

## Order Insights View

<p align="center">
    <img src='https://github.com/amoghsawant17/Insights_Supply_Chain_Issue/blob/main/views_snap/order_insights.png' width="600">
</p>

## Feedback View

<p align="center">
    <img src='https://github.com/amoghsawant17/Insights_Supply_Chain_Issue/blob/main/views_snap/feedback.png' width="600">
</p>

## Things that I learned from this Project
- I Learned, how to use bookmarks and selection for different purposes. (Page navigation buttons in the dashboard were achieved using bookmarks and selection same as a website page navigation.
- Tried using the color palette and sticking with those colors throughout the dashboard ([Color palette link](https://colorhunt.co/palette/0766ad29adb2c5e898f3f3f3))

## Some Key Metrics
- Orders are nothing but unique requests placed by a customer on a given date.
- Within an order, a customer could request multiple items. Each of these items requested within the order is called an order line.
- Line Fill Rate is an important metric for the supply planning team to understand how many lines they shipped out of the total lines ordered. This metric does not consider the delivery time of the order.
  - Line Fill Rate for an order = order lines fulfilled / lines ordered
- Volume fill rate or case fill rate is a similar metric useful for the supply planning team to understand the total quantity they can ship for a customer per order or for a given period.
  - Volume Fill rate for an order = total quantity shipped / total quantity ordered
- Measuring On-Time delivery %
  - Unlike Line Fill Rate, this measure is measured at the order level. It determines if an order is delivered as per the agreed time with the customer.
  - This metric is important for the warehouse & distribution team.
  - An order is On Time only when all the line items inside the order are delivered on time.
- Measuring In Full Delivery %
  - Unlike Line Fill Rate, this measure is measured at the order level. It determines if an order is delivered in full as per the requested quantity by the customer.
  - This metric is important for the supply planning team.
  - An order is In Full only when all the line items inside the order are delivered In Full.
- Measuring On Time In Full (OTIF) %
  - Unlike Line Fill Rate, this measure is measured at the order level. It determines if an order is delivered BOTH in full and On Time as per the customer's order request.
  - This metric is important for all the sub-functions in the supply chain team.
  - An order is OTIF only when all the line items inside the order are delivered In Full and ON Time. This is a hard metric that measures the reliability of an order from a customer's point of view.

## Some Important insights from the Dashboard
- In Full Delivery % is 54.2 % in Ahmedabad city which is the highest followed by Surat city.
- On-Time Delivery % is 61 % in Surat city which is the highest followed by Ahmedabad city.
- OTIF Delivery % is 30 % in Surat city which is the highest followed by Ahmedabad city.
- Volume Fill Rate is around 96 % in all cities.
- The line Fill Rate is 67.6 % in Ahmedabad city which is the highest followed by Surat city.
- The highest number of orders given by customers are Lotus Mart with 3550 orders, Acclaimed Stores with 3510 orders, and Coolblue with 2437 orders.
- Overall the In Full Delivery % is 52.8 % which is short of its target by -31 %.
- Overall the On-Time Delivery % is 59 % which is short of its target by -31.5 %.
- Overall the OTIF Delivery % is 29 % which is short of its target by -56 %.
- The number of orders received is around 11,000 from Ahmedabad city and Vadodara city each.
- The Line Fill Rate is around 96 % and the Volume Fill Rate is around 66 % across all categories.
- The delay in delivery is highest among customers such as Lotus Mart, Acclaimed Stores, and Coolblue.
- The In Full Delivery % is farther from its target for Vijay Stores, Sorefoz Mart, Info Stores, Elite Mart, and Coolblue which results in a lower OTIF Delivery %.
-  The On-Time Delivery % is farther from its target for Lotus Mart, Acclaimed Stores, and Coolblue which results in a lower OTIF Delivery %.
- The waiting period for delivery is the highest for Lotus Mart, Acclaimed Stores, and Coolblue which is 3+ days of delivery and this might result in higher customer dissatisfaction.
- The Dairy category is ranked highest in terms of order quantity of 10.6 Million units followed by the Food and Beverages category.
- In terms of order quantity, Milk is ranked the highest among all products followed by Curd, Butter, Biscuits, Tea, and Ghee.

## Potential Decisions
1. **Prioritize Customer Relationships:**
   - Focus on improving service levels for key customers like Lotus Mart, Acclaimed Stores, and Coolblue, as they contribute significantly to the order volume.
   - Implement a customer-centric approach to address their specific concerns and reduce delivery delays.

2. **Optimize Delivery Processes:**
   - Streamline the delivery processes to ensure In Full Delivery % and On-Time Delivery % meet or exceed targets for all cities.
   - Analyze and address the reasons behind delays, especially for high-volume customers, to minimize waiting periods and enhance customer satisfaction.

3. **Enhance Product Availability:**
   - Work closely with suppliers to maintain optimal stock levels for essential products to meet customer demands consistently.
   - Implement inventory management strategies to prevent stockouts and ensure full product delivery.

4. **Category-specific Strategies:**
   - Given the high order quantity in the Dairy category, allocate additional resources to manage the supply chain effectively for these products.
   - Monitor and improve the delivery performance for specific categories such as Dairy, Food and Beverages, and prioritize them based on customer demand.

5. **Set Realistic Targets:**
   - Reassess and adjust the target service levels for each customer to more realistic values based on historical performance and customer expectations.
   - Ensure that the revised targets are challenging yet achievable to improve overall service metrics.

6. **Investigate Line Fill Rate Disparities:**
   - Investigate the reasons behind disparities in Line Fill Rates among cities and identify best practices from Ahmedabad and Surat to improve performance in other locations.

7. **Capacity Planning:**
   - Assess the current capacity of the supply chain and evaluate if additional resources are required to handle the expected order volume increase when expanding to new cities.

8. **Technology Integration:**
   - Explore the integration of technology solutions, such as route optimization software and real-time tracking, to enhance delivery efficiency and accuracy.

9. **Customer Communication:**
   - Implement proactive communication channels to keep customers informed about their order status, potential delays, and expected delivery times to manage expectations effectively.

10. **Continuous Monitoring and Improvement:**
    - Establish a continuous monitoring system for key performance indicators and regularly review and adjust strategies to address changing market dynamics and customer expectations.

Implementing these decisions can contribute to resolving the supply chain issues, improving customer satisfaction, and ensuring a smoother expansion into new cities for AtliQ Mart.
