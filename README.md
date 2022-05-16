# PyBer_Analysis
PyBer Analysis with Python, Pandas, Matplotlib.

# Overview of the analysis:

Pyber is a python based ride-sharing app company. We performed Exploratory data analysis from the CSV files. We created several types of visualization story from data to present complex finding in a way that is informative and engaging to all stakeholders. We used Pandas, SciPy, Numpy to perform various calculations and statistics analysis that would help us to demonstrate the relevance of the data such as:
1.    Number of rides for each city
2.    Which city types are generating the most money
3.    which types of cities need more driver support.

V. Isualize has given us a brand-new assignment. Using our Python skills and knowledge of Pandas, we created a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, we created a multiple-line graph that shows the total weekly fares for each city type. Finally, we submited a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.
# Results:

We used Python skills, Pandas libraries, and mattplotlib in jupyter notebook and retrieved a variety of outputs such as:

•    The total rides for each city type:
Rural        125
Suburban     625
Urban       1625

•    The total drivers for each city type:
Rural         78
Suburban     490
Urban       2405 have more drivers.

•     The total amount of fares for each city type:
Rural        4327.93
Suburban    19356.33
Urban       39854.38 have more fares.

•    The average fare per ride for each city type:
Rural       34.623440 have high average compared to 
Suburban    30.970128
Urban       24.525772

•    The average fare per driver for each city type.
Rural       55.486282 have also high average, whereas
Suburban    39.502714
Urban       16.571468

## PyBer summary DataFrame is created.

<img width="687" alt="Screen Shot 2022-05-15 at 10 44 06 PM" src="https://user-images.githubusercontent.com/92646311/168512336-0a7d4124-9209-435a-a5ad-e7a022b6d5b8.png">


Further we removed the index name("type") and formated the Pyber summary DataFrame to look like this:

<img width="935" alt="Screen Shot 2022-05-15 at 10 45 27 PM" src="https://user-images.githubusercontent.com/92646311/168512350-661ec3bc-98d4-48b7-ac77-51c8336bda24.png">


• Using groupby() we create a new DataFrame showing the sum of the fares for each date where the indices are the city type and date

<img width="583" alt="Screen Shot 2022-05-15 at 10 57 48 PM" src="https://user-images.githubusercontent.com/92646311/168512458-3ad4fa8a-0723-496c-98aa-70fac505a29f.png">

• After reseting the index on the DataFrame:

<img width="583" alt="Screen Shot 2022-05-15 at 10 57 48 PM" src="https://user-images.githubusercontent.com/92646311/168512587-0f6ab37f-45ea-4b70-9f46-f92cab3fa5e8.png">

•  Created a new DataFrame from the pivot table DataFrame using loc on the given dates, and using the "resample()" function by week 'W' and get the sum of the fares for each week.

<img width="312" alt="Screen Shot 2022-05-15 at 11 04 10 PM" src="https://user-images.githubusercontent.com/92646311/168513050-f671ac89-474c-442e-bce3-26aea03ac5c2.png">

• A multiple-line chart is created based on total fares for each city.

<img width="970" alt="Screen Shot 2022-05-15 at 11 11 04 PM" src="https://user-images.githubusercontent.com/92646311/168513623-a13e0a63-c664-4777-a33c-eeab1a85b2fb.png">

1. End of the Febrauary is high point for each three city types. 
2. Rural and urban cities have an increased is april whereas suburban cities have increased in end of april. 
3. Urban city has more volume in rides, drivers and fares compared to rural and suburban cities.

# Provide three business recommendations to the CEO 


1.Based on the graph and analysis, we can predict that we can generate more money in rural and suburban cities by offering  various promotions to enhance new and existing cutomers.

2. Hiring more drivers in rural and sububan cities may  will also helpful to increase the business in each city types.

3. Increasing a slight rise in fare rates in rural and suburban cities will help to generate company revenue 


