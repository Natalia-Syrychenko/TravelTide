### TravelTide Customer Segmentation
[Tableau](https://public.tableau.com/app/profile/natalia.syrychenko/viz/TravelTideCustomerSegmentation_17255559951330/TravelTide_Customer_Segmentation?publish=yes)
<img width="794" alt="Screenshot 2024-09-17 at 18 35 17" src="https://github.com/user-attachments/assets/47f3e3f6-1b86-40b5-8cc5-d71109341522">

## Introduction
Since its launch in April 2021, TravelTide has rapidly grown into a prominent player in the online travel industry, leveraging cutting-edge data capabilities to offer the most comprehensive booking catalog. CEO Kevin Talanick is focused on strengthening customer loyalty and retention.

## Objectives
Segment customers based on their behavior and develop a personalized rewards program that ensures they continue to choose TravelTide for their travel needs.

## Methodology
The analysis began by extracting raw data from four key tables using SQL. We then processed and analyzed the data, employing segmentation techniques and Tableau visualizations to identify users with over seven sessions between January 4, 2023, and the most recent data. Each user was then matched with a proposed perk tailored to their behavior.
  
## Project Overview 
The TravelTide project focuses on segmenting customer data to provide data-driven recommendations that help enhance customer retention. The project is carried out for TravelTide, a fast-growing e-booking startup that has seen steady growth since its inception in 2021. The goal is to support the Head of Marketing, Elena Tarrant, by understanding customer behavior and creating personalized marketing strategies to encourage customers to sign up for the company's new rewards program.

The project is divided into four main stages, each building on the previous one:

- **Exploratory Data Analysis (EDA)**
- **Feature Engineering**
- **Customer Segmentation**
- **Presentation of Results**
  
## Project Outcome: Customer Segmentation and Perk Strategy
- **Business Traveler (18.34%):** *Free Access to Airport Lounge*
- **Luxury Travelers (18.19%):** *Free hotel night*
- **Hesitant Customers / Early bookers (16.09%):** *Free cancellation*
- **Solo (15.94%):** *Free checked bag*
- **Budget Travelers (14.09%):** *Discount on excursions and car rental*
- **Loyal Customers (11.22%):** *Free Airport Transfers*
- **Others (6,14%):** *Welcome drink*

## Data Insights:
  Through the segmentation, the following insights were gathered:
  
- Business travelers and luxury travelers make up the largest customer groups.
- A significant portion of solo travelers fall into the 36-50 age range.
- Majority of our clients are women.
- Loyal customers are primarily single, while business and luxury travelers tend to be married.
- Parenting status shows that the majority of business travelers do not have children, while most loyal customers do.

## Insights:
During the data analysis, inconsistencies were found in the number of nights (-2, -1, and 0). Following management's decision, these were replaced with 1. Additionally, I adjusted 38 rooms listed as 0 to 1, given no cancellations and the fact that over 80% of travelers rent 1 room. The adjustments made to the nights and rooms ensure greater consistency and accuracy in future analysis, leading to more reliable decision-making.

## Recommendations:
To further improve segmentation and offer personalized services, it’s essential to collect more detailed customer insights. Key information includes:

- **customer feedback:** Reviews of previous trips,
- **preferences:** Travel preferences, favorite destinations,
- **accommodation needs:** Housing requirements,
- **dietary preferences:** Nutritional wishes,
- **service ideas:** Suggestions for new services.
  
Implementing automated surveys and gathering detailed customer insights will enable more precise segmentation, leading to personalized services and enhanced customer satisfaction and ensure TravelTide continues to grow as a leader in the travel industry.

## Folder Structure
- /TravelTide_Customer_Segmentation_SQL_/ - SQL scripts used for exploring the dataset.
- /TravelTide_presentation_Syrychenko/ - Final presentation.
  
## Tools and Technologies
- **Tableau**: Used for creating the interactive dashboard
- **SQL**: Used for querying and extracting relevant data

## About Me
I am Dr. Natalia Syrychenko, a finance professional transitioning into data analytics. This project is part of my portfolio demonstrating my skills in data visualization and customer analysis. I specialize in leveraging data-driven insights to help businesses optimize their decision-making processes.
