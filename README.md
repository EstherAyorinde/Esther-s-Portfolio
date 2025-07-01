# AfriTech Electronics Analysis

![image alt](https://github.com/EstherAyorinde/Esther-s-Portfolio/blob/main/Screenshot_1-7-2025_13412_png.pngtree.com.jpeg)
---

## Introduction

**AfriTech Electronics Ltd** is a leading provider of electronics based in the United States.They offers a wide range of innovative products including laptops, smartphones, tablets, and smartwatches and also focused on delivering high-quality products and excellent customer service. The project is to analyze and data-driven insights to enhance customer and sale service, resolve crisis and complaints efficiently, and strengthen its brand and social media reputation. The tools used are PostgreSQL and Power BI.

## Problem Statement
1.Protecting Market Position: The company is experiencing a surge in negative social media conversations about its products and customer service. These conversations are damaging its brand image.
2. Customer Complaints: Complaints related to product defects, delays in customer support response and billing issues have been rising, leading to a drop in customer satisfaction.
3. Product Recalls: Recent product recalls have received significant media attention, causing panic
among customers and stakeholders.
4. Competitive Pressure: Rivals are gaining market share by exploiting AfriTech Electronics Ltd.’s reputation challenges.

## Skills
---
  These Power Bi Feature were used:
  - DAX,
  - Measures,
  - Data Modelling,
  - visualisation,
  - Page Navigation

## Data Modeling
---
Power BI automatically created relationships among the dataset tables based on matching column names and data types.

### Auto-detected Relationships

- `public Customerdata` (CustomerID) → `public SocialMediadata` (CustomerID) – *Many-to-One*
- `publc customerdata` (CustomerID) → `public Transactiondata` (customerID) – *Many-to-One*
- `public Socialmediadata` (interactiondate) → `public brandmention` (Interactiondate) – *Many-to-One*

These relationships are single-directional and were not manually adjusted. No additional data modeling (calculated tables or manual joins) was required beyond the Power BI defaults.

![Afrotech_data_model png](https://github.com/user-attachments/assets/938b892c-0542-499f-b056-f9b31344222d)


## Visualization
---

This report have 3 pages:
1. Customer & Sales Insights
2. Brand Sentiment & Social Media Analysis
3. Customer Complaints & Crisis Management 

You can interact with the analysis here

## Analysis:
---
### Customer Information:
![Screenshot 2025-05-22 073512](https://github.com/user-attachments/assets/ce149f46-5550-472b-96bc-265ad4497380)


The Store have a total of 200 Customers and total revenue of $57.53M.
74k transaction were made in the years.

### Brand sentitment and social Media Analysis:
---
![Screenshot 2025-05-20 161437](https://github.com/user-attachments/assets/813204a7-1d8d-47ee-8d1e-e7917cbc7058)


They operate on 5 social Media platform with the engagement score of 292.47M.
The store has the brand mention of 38k in all the platform.
They have 99.97 top influeners.
Image post has the highest engagement, followed by Video and Story.
TikTok and Instagram have the most brand mentions
There is even distribution across all content types; image and story types slightly dominate.
Returning customers give the most negative feedback.



### Customer Complaints & Crisis Management:
![Screenshot 2025-05-20 200002](https://github.com/user-attachments/assets/da44c016-14b0-4940-a944-9309420ec30c)

13k Complaint was made on their product.
Their average response time to complaint is 189.97 minutes.
Instagram and LinkedIn have the highest complaint volumes.
67.76% of the complaints are resolved, while 32.24% was not resolved.

## Recommendation:
Focus on the retaining returning customers and addressing their concerns.
Pay attention to the complaint and response to their complaint early.
Focus Campaigns on region with the low income to increase Returns.
Invest in customer retention strategies for VIPs and high spending customers
focus on the product with consistent issue and improving post sale service.

## THANK YOU. 


