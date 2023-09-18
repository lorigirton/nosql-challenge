# nosql-challenge

This challenge is part of the UNC Data Analytics Bootcamp where a fictional food magazine, Eat Safe, Love, tasked me to utilize the UK Food Standards Agency evaluation system to evaluate the data to help the magazine decide where to focus for future articles. 

I began by importing data and creating a Mongo database called "uk_food" and collection named "establishments."  Then I used the NoSQL_setup_starter.ipynb to import the libraries PyMongo, Pretty Print, and Pandas. I then updated the database by adding and dropping some restaurants. Next, I used the NoSQL_analysis_starter.ipynb to help the agency find locations they wished to visit based on rating values and hygeine scores and narrow down by location. Last, I built an aggregation pipeline to find how many establishments in each local authority area with a hygiene score of 0, sorted the results from highest to lowest and returned the top ten areas.

References
UK Food Standards AgencyLinks to an external site. (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GBLinks to an external site.. Contains public sector information licensed under the Open Government Licence v3.0Links to an external site.
Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).
I also utilized the Tutor assigned to me by the bootcamp as well as the AskBCS Learning Assistants to complete this assignment. 
