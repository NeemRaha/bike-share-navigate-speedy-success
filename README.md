# bike-share-navigate-speedy-success

This project is about the Bike-Share Capstone project from Coursera's Google Data Analytics specialization.

You can find the certification course at - https://www.coursera.org/professional-certificates/google-data-analytics

I am going to showcase my journey in form of Q&A. This will help you understand my thought process which you can apply to many other projects.

Section 1: ASK
What is the problem you are trying to solve?
Business Objective: To maximize the number of annual memberships by converting casual riders to annual members.

How can your insights drive business decisions?
The effort to find out trends on how the usage of cycles for annual members differ from the casual riders with the help of visualizations and key findings that will help to make recommendations that can be considered by the company in order to increase the annual memberships.

Section 2: PREPARE
The dataset required for this business objective should be of the past 12 months. Here, we are considering data from July 2020 till June 2021.

The data was made available by Motivate International Inc. under the appropriate license which ensures credibility of the data. This is public data that you can use to explore how different customer types are using Cyclistic bikes.

The data file consisted of different folders for each month of a particular year and also quarterly data year wise was made available.

As we had to consider only the data related to the past 12 months, I downloaded the csv files as per the requirement and stored it in a single folder so they are easier to access and work on.

The data-privacy issues prohibit you from using riders’ personally identifiable information. This means that we won’t be able to connect pass purchases to credit card numbers to determine if casual riders live in the Cyclistic service area or if they have purchased multiple single passes. This ensures data integrity.

Dataset - rb.gy/agptn7


Section 3: PROCESS
I am using Python language for working on data as it is more accessible and easier to use.

The first step while starting any analysis is to import appropriate libraries in the notebook.

Some of the important libraries are:

Pandas - Pandas allows importing data from various file formats such as comma-separated values (CSV), JSON, SQL, Excel. Pandas allows various data manipulation operations such as merging, reshaping, selecting, as well as data cleaning, and data wrangling features.
Numpy - It can be used to perform a number of mathematical operations like trigonometric, statistical, and algebraic on arrays.
Matplotlib and Seaborn - It is used to create graphical analysis of the data.
Datetime - These classes provide a number of functions to deal with dates, times and time intervals.


Section 4: ANALYSIS
After cleaning the data, it is important to aggregate, organize and format the data. Here we need to perform calculations(descriptive analysis) and understand the trends present in the data.

Section 5: SHARE
We use python libraries like seaborn and matplotlib to plot visualizations.

Through visualizations, we can observe that the number of casual riders is approximately equal to the number of annual members. The 57.1% of total population are annual membership holders.


Section 6: ACT
As observed from the analyses, the number of casual riders is more than the number of annual membership holders. We can increase the fare of casual rides (which will help generate more revenue initially) and at the same time, reduce the cost of annual membership. This will pull more riders towards annual membership.

As observed, most of the casual riders ride on Fridays. We can hold special weekend discounts on annual membership to attract the customers. At the same time, we can offer a guarantee of bikes being available to annual membership holders on weekends, but the same can’t be guaranteed to casual riders.

As we noticed from the graph, on average, casual riders ride for approximately 47 mins. We can have a scheme like “more discounts on more miles” where the riders can get discounts like 10% on 10 more mins of ride, 20% on 20 more mins and so on. These discounts will be used against purchase of annual membership.

We can also smoothen the process of acquiring annual membership by making the whole process simple and completing it online too. On the other hand, casual riders should come to bike centers to get their bikes. This might pull some people towards annual membership, but in the long run, this will hurt the company’s image. So we should try not to fall for this dark/anti-pattern.

We have observed that approximately more than half of the casual members use Docker bikes for travelling, so we can offer special incentives in order to increase conversion from casual to annual.
