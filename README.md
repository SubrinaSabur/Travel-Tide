# Travel-Tide
Travel Tide Customer Segmentation and Personalized Perks.
The Travel Tide project involved customer segmentation and assigning perks by analyzing customer behavior. The project was conducted using SQL, Python, feature engineering, and visualization to optimize Travel Tide's loyalty program.

## Project Overview

This project focuses on segmenting customers and offering tailored perks based on an analysis of customer behavior from six months of archived data in 2023. The goal is to enhance customer retention and boost the number of loyal customers for Travel Tide by offering personalized perks.

After analyzing data from 5,998 customers, they were segmented into 10 distinct groups. Most perks were allocated using data-driven insights, and the analysis revealed that segmentation provides a clearer understanding of customer behavior. As a result, assigning perks tailored to each group is likely to be of significant value to them.


## Methodology

The analysis encompassed an exploration of several key factors:
- **User Demographics**: Age, location, and gender.
- **Trip Booking Patterns**: Booking history, preferred destinations, and trip durations.
- **Booking Frequency**: How often customers booked trips.
- **Spending Habits Per Trip**: Average spend per trip.
- **Observed Behaviors**: Key actions during the booking process.

A **rules-based approach** was employed to segment customers into 10 distinct groups. One of these groups, called **"Other Customers"**, includes individuals who did not align with specific segmentation criteria, though they have previously made purchases from Travel Tide. This segmentation methodology provided insights that were used to offer personalized perks to each group, enhancing customer engagement and loyalty.

## Features

- **Customer Segmentation**: Groups customers based on various behavioral and demographic factors.
- **Tailored Perks**: Provides personalized perks for each customer segment based on insights derived from data.
- **Data-Driven Analysis**: Uses data analysis to understand customer behavior and drive retention strategies.

## Technologies Used

- **Python** for scripting and data processing.
- **Pandas** for data manipulation and analysis.
- **Scikit-learn** for applying segmentation techniques.
- **Matplotlib / Seaborn** for data visualization.
- **SQL** for data pre-processing and feature engineering:
  - **Data Pre-processing**: Conducted directly within the `session_table` as part of the initial SQL query.
  - **Feature Engineering**: Handled in a second SQL query named `user_table`.
  - **Final DataFrame**: The result of the second SQL query was used to create the `user_table` DataFrame in Pandas for further analysis.

## Access the Colab Notebook

#**Recommendation**

1. Pilot Study: Implement a pilot project to test the allocated perks and measure their impact on customer behavior. This preliminary phase will help evaluate the effectiveness of the perks before a full-scale rollout.

2. A/B Testing: Conduct A/B testing to assess the effectiveness of different sets of rules and perks. This approach will compare the performance of various rule configurations to determine which set provides the best outcomes for Travel Tide.

3. Unit Testing: Perform unit testing to ensure that each individual component of the rule logic functions correctly. For example, verify that a rule designed to classify users as "Senior Travelers" based on age correctly identifies users with the appropriate attributes.

4. Integration Testing: Execute integration testing to confirm that multiple rules work together seamlessly. This ensures that there are no conflicts, such as a user being incorrectly classified as both "Frequent Fliers" and "Family Trip" due to overlapping criteria.

5. Customer Feedback and Follow-Up: Continuously collect and analyze customer feedback to refine and enhance the perk offerings. This ongoing process will help in adapting the perks to better meet customer needs and preferences.

Access the Google Colab notebook for this project [(here)](https://colab.research.google.com/drive/1dCTobnHSQ9BevEg-pD5J1RlKarA79HUR?usp=sharing) 
## Presentation

Watch the presentation video [here](https://drive.google.com/file/d/1vL48dkpPK_etCOSxM_dQj4367zQ3BgSA/view?usp=sharing) 
 
