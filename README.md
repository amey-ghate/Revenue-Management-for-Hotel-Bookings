# Revenue Management for Hotel Bookings - Analytical Report

## Introduction

This repository contains the project conducted by Group 11, which consists of Amey Ghate, Sameer Ahmed, and Spandan Pal, submitted to Dr. Guoming Lai in May 2024. The project explores the application of sophisticated revenue management techniques to a 100-room hotel, focusing on optimizing room allocations to maximize revenue through the strategic balance of group and transient bookings.

## Problem Statement

The core challenge addressed in this study is the strategic allocation of rooms between group and transient bookings in a 100-room hotel. The decision-making process is complicated by the need to balance the financial security provided by group bookings against the potential for higher revenue from transient guests, who may book closer to their arrival date. This project develops a dynamic decision-support model that adjusts room allocations in real-time based on booking trends, historical data, and forecasted market conditions to enhance the hotel's revenue per available room (RevPAR).

## Dataset Overview

The analysis utilizes the "Hotel Booking Demand" dataset available on Kaggle, which offers detailed booking information for two types of accommodations: a city hotel and a resort hotel. The dataset contains 119,390 entries and 32 columns, providing insights into booking lead times, guest demographics, room rates, and more. Our team focused on entries where bookings were not canceled (`is_canceled` column = 0) to ensure the analysis reflected actual stays and genuine customer behavior.

### Key Components of the Dataset Include:
- **Booking Timeframe**: Analysis of when bookings were made to determine lead times.
- **Stay Details**: Insights into the length of stay and demographics of guests.
- **Facilities Usage**: Data on the use of additional facilities like parking spaces.
- **Room Rates**: Exploration of pricing strategies across different times of the year.
- **Data Anonymity**: All personally identifying information has been removed.

The data was further processed to filter out canceled bookings, focusing the analysis on genuine stays, which provided a clearer picture of occupancy and revenue trends.

## Capacity Control Model

Our approach involved implementing a capacity control model that uses statistical data to decide the optimal allocation of rooms to either group or transient guests based on expected revenue calculations. This model helps in:
- Determining when to reserve rooms for high-value transient guests.
- Comparing expected revenues from group versus transient bookings to make informed decisions.

## Results and Implications

The application of our capacity control model and data-driven strategies has significantly improved our understanding of hotel revenue management. We successfully:
- Developed a model that dynamically adjusts room allocations.
- Provided strategic insights that can help hotel managers adjust pricing and improve profitability.
- Enhanced our analytical skills, providing us with invaluable experience in handling real-world data.

## Conclusion

As budding data analysts and scientists, we are proud of the insights and contributions this project has brought to the field of hospitality management. We've gained substantial knowledge and experience in applying data analysis techniques to solve complex problems, enhancing our skills and preparing us for future challenges in the data science field.

## Future Directions

The models and strategies we developed hold potential for integration into live hotel booking systems, application across multiple properties, and refinement through advanced machine learning techniques. We look forward to exploring these opportunities as we continue to grow in our careers as data scientists.

---
For more details on our findings, methodologies, and code, please refer to the Jupyter notebooks and scripts provided in this repository.
