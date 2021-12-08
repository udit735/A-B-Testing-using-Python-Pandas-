# A-B-Testing-using-Python-Pandas-
A/B Testing using Python
The following project utilizes A/B testing to gain insights into the data.
A generic online marketplace has two different versions of an ad (one is A and the other is B), which they have placed in emails, as well as in banner ads on Facebook, Twitter, and Google.
I want to know how the two ads are performing on each of the different platforms on each day of the week.

The CSV file contains a table with the following columns:
1. user_id: Unique and Non null values identifying a particular user.
2. utm_source: A UTM code is a snippet of simple code that you can add to the end of a URL to track the performance of campaigns and content. AKA "Urchin Traffic Monitor". For ease of analysis, these four unique values are allowed: 'google', 'facebook', 'twitter' and 'email'.
3. day: Days of week
4. ad_click_timestamp: The time at which the ad was clicked, 'nan' if not clicked.
5. experimental_group: A or B.

Dataset Credit: Codeacademy
