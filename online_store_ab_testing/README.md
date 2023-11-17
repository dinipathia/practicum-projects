## Data

1. Marketing calendar events in 2020
- name : name of marketing event
- regions : regions where the campaign take place
- start_dt : campaign start date
- finish_dt : campaign end date

2. Table of all users who registered in the online store start from 7 to 21 December 2020
- user_id
- first_date : date of registration (sign up)
- region
- device : device used for registration

3. Table of all events from new users throughout the period of 7 December 2020 to 1 January 2021
- user_id
- event_dt : date and time of the event
- event_name : name of the event
- details : additional information of the event (such as, total order amount in USD for the purchase event)

4. Table of a list of experimental participants
- user_id
- ab_test : name of experiment
- group : group of experiment
  
## Goal:

This project aims to evaluate A/B testing analysis of an international online store that has been conducted previously, with goal of experimental testing: examining users' engagement of an improved recommendation system

## Libraries used:

pandas

numpy

math

scipy

seaborn

matplotlib
