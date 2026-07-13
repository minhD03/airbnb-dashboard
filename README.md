# Airbnb Review Dashboard: [Live Report](https://app.fabric.microsoft.com/view?r=eyJrIjoiMGU4Y2Q0NTAtNzU1ZC00NDIwLTg2NzItMGUxOTA0MWE1NDg3IiwidCI6IjZhNjhlMmQxLWQ4OGQtNDEyYi1iOTgyLWQ0YWVkNWY1MTcxNiJ9)

## Table of Contents

- [1) Introduction](#1-introduction)
- [2) Datasets](#2-datasets)
- [3) Screenshots](#3-screenshots)
- [4) Key Measures](#4-key-measures)
- [5) Key findings](#5-key-findings)
- [6) Conclusions](#6-conclusions)

## 1) Introduction:
This dashboard is the continuous of the [Airbnb project](https://github.com/minhD03/airbnb-project.git), using the datasets collected from the project. 

Problem Statement: For accommodation platforms such as Airbnb, customer reviews significantly influence booking decisions and host reputation. However, understanding what drives positive and negative guest experiences requires analyzing large volumes of review data alongside listing characteristics.

This project aims to answer the following business questions:

- What is the overall sentiment of Airbnb guest reviews?
- Which hosts consistently deliver positive customer experiences?
- Does listing price influence guest satisfaction?
- Which room types receive the most favorable reviews?
- How has customer engagement changed over time?
- Is there any measurable relationship between Full Moon events and guest review sentiment?
- Which listings generate the highest customer engagement?

## 2) Datasets:
![alt text](https://github.com/minhD03/airbnb-dashboard/blob/32c601e26889f6ea4bd409a972dd85aa0e9d4d54/images/data.png)
The dataset contains information including:
- Reviews from customer and full moon labelled: I want to digest deeper to see whether full moon days affect the reviews sentiments.
- Hosts and their Listings.
- Date tables.
  
## 3) Screenshots:
![alt text](https://github.com/minhD03/airbnb-dashboard/blob/1b005ecdff67b3859ec6545a6bd9ca6436c6582a/images/dashboard.png)

## 4) Key Measures:
### a) Full moon reviews sentiment:
Investigate the impacts of full moon days with review sentiments.
### b) Hosts with review counts: 
Uncover the hosts and see who has the most positive and negative reviews.
### c) Price and Room Type Reviews:
See the trends of Room Type and Price range that customer prefers.

## 5) Key findings:
These are my findings:
- From all reviews, 56.76% reviews are from positive while the rest are either negative or neutral. Furthermore, all the positive reviews are outstanding the rest in all categories.
- Over the time, while the number of positive reviews increased dramatically, the neutral and negative slowly went up. This indicated that the hosts are listening and improving their listings.
- Surprisingly, the Entire Home/Apartment and Private Room shows the most attractive to customers.
- In the price range, the price below 100$ magetized customers most. However, the numbers of both negative and positive reviews are quite close, indicating the unstable quality of these accommodation.
- However, when the range increase to below 200$, the positve surpassed negative and even further when above 200$ with almost no negative reviews. These accommodations have higher and more stable qualities.
- As a result, the higher price ranges has drawn no attention to the customers.
- Overall, Martin has the most positive reviews with 3.1k reviews, illustrating his dedication to his accommodation, followed by Frank, Single Hostel Berlin and Michael.
- When it comes to superhost, Martin was still on the top but the followings were Simon, Stefan and Stella.
- For non-Superhost, Single Hostel Berlin took the top spot, followed by Frank, Alex and Christina.
- However, unlike other hosts, Kristina and Katarina had almost equal number of positive and negative. This means that their accomodation are quite fluctuating in terms of quality and statisfaction (1k and 800 respectively).
- For top Listings, "Central flat near Alex with fiber optic Internet" from Sven attracted customers most with nearly 900 reviews, followed by "Nena Apartments Metropolpark Studio" and "Serviced Apartment - Studio in Prenzlauer Berg".
- Among these top listings, the positive reviews were surpassed the rest. However, only "Central, cosy and one of a king" from Henrik has a surprisingly huge number of positive reviews over the rest. This indicated that his accomodation quality has the highest satisfaction among those with the same price range.
- For full moon days, the ratio of neutral and negative reviews were quite closer to positive. This demonstrated that the standard of customer has raised higher when in the full moon day as these days might be memorable for customers in some events.

## 6) Conclusions:

This project demonstrates how Business Intelligence and data analytics can transform Airbnb listing and review data into actionable insights for understanding customer satisfaction and accommodation performance. The analysis revealed that positive reviews dominate overall customer feedback, indicating strong guest satisfaction across the platform. Room type analysis showed that Entire Home/Apartment and Private Room listings attract the highest customer engagement, while pricing analysis suggested that higher-priced accommodations generally achieve more consistent positive sentiment compared with lower-priced listings. Host-level analysis highlighted significant differences in performance, with several hosts maintaining strong customer satisfaction through consistently positive reviews. Furthermore, the investigation of Full Moon events provided an example of hypothesis-driven analysis, showing that external factors had limited impact on review sentiment compared with accommodation quality and customer experience. Overall, this dashboard enables stakeholders to evaluate performance trends, identify improvement opportunities, and make data-driven decisions to enhance guest satisfaction and listing success.
