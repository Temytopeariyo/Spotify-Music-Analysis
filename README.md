# Spotify-Music-Analysis
# Spotify Music tracks performance Report

### Introduction

This project provides a comprehensive view of musical tracks listening trends, and insights, which can be used to make informed entertainment decisions. 
I deemed it fit to delve into an in-depth exploration of online musical tracks performance in entertainment industry espciailly as it relates to Artists data, leveraging the tracks dataset. 
Hence, I Welcome you to the intriguing world of data analysis! This analysis aims to uncover valuable insights and trends that lie within the data, shedding light on the dynamics of online streams, 
listeners behavior, and more. Join me on this adventure journey as we navigate through the track numbers, revealing actionable findings that can drive strategic entertainment decisions and enhance positive artists performance in the forseeable future. 
This musical tracks Performance report provides information on tracks online streams, Artists name, Track relaease date and track performance based on streams. The report allows you to visualise at a glance the tracks performance as they relate to different artists and their performance based on danceability,	valence, energy,	acousticness,	instrumentalness, liveness, and speechiness of their tracks.



!(![image](https://github.com/Temytopeariyo/Spotify-Music-Analysis/assets/81833143/17ab73f3-21b9-4770-aba4-1ee30d9aabef)


This way, Artists can see their performance and improve on their musical (song recording) strategy.


You can interact with the report [HERE]()


### Data Source
The data used for this project was from Onyx Data (DataDNA Dataset Challenge).

### Task
* Streaming trends: Analyzing yearly streams as it relates to two decades interval.

* Monthly Track streaming Performance: Recognizing top month with highest average streams based on tracks. 

* Artist Most streamed track and total streams Correlation: Exploring correlations between tracks and number of streams.

* Top 5 most streamed tracks and the artists: Top N (5) most streamed tracks was recognised in relation to the artists.

* Playlist and Artist names: The distribution portray how spotify playlist affect Artist performance.

### Data Preparation and Transformation
To make ready dataset for the analysis, Power Bi was used to turn the unrelated sources of data into coherent, visually immersive, and interactive insights. In response to the given task, a careful assessment of the necessary database tables was carried out. Specifically, the database table was imported from excel and tested for errors. The table which formed the basis for the subsequent steps was not free from as Streams, in shazam charts, Key column  were all detected having an error and empty cells which were corrected, replaced with 0 and None respectively. The Day, Month and Year columns were also harmonised into a new single column for easy understanding. The 3 columns were subsequently deleted from the table as the new one that combined all has been added to the table. 

The power query was closed and the dataset applied accordingly and ready for visuals. From this dataset, another table was created for the date so as to have it according to Day, Month and year of track relaese with the formular below:


!(![image](https://github.com/Temytopeariyo/Spotify-Music-Analysis/assets/81833143/ba0e30f8-70fb-4623-8c19-bcab0f926ebd)

the above was marked as date table afterwards and created as measures with Day of week, Month, and year. These measures became the central point where all the other informations related to Date in our analysis could link to. By using specific measures from this table of dataset, we established connections to other related distributions. 

### Data Modelling
Since I have establised another table, the logical representation of how data is structured and related within the tool and the collection of tables and relationships between them that are used to create reports and visualizations was necessary, hence the intergration of tables was involved (one to many)


!(![image](https://github.com/Temytopeariyo/Spotify-Music-Analysis/assets/81833143/55a3d484-dd97-46f6-987d-db12fe15acda)


### Data Exploration and Visualization
As the data was structured, I made sure I created related calculations that would help the analysis. These calculations included key measures from this dataset and the following measures were created for easy visualizing: Average income, Bike Buyers, Non buyers, Number of Femaie buyers, Number of Male buyers and Total participants. These measures became the central point where all the other informations in our analysis could link to. 

### Sales Report - Visualization
During the visualization process, a comprehensive overview of our sales and customer metrics was provided through an information cards. The measures were dragged and dropped into these information cards and the Average income, Bike Buyers, Non buyers, Number of Femaie buyers, Number of Male buyers and Total participants were all showcased. For enhanced analytical exploration, slicers were introduced, allowing for focused drill-through. These slicers, Gender, Marrital Status and region facilitated more targeted analysis. The sales report was differenciated in terms of sales, income,age bracket, education, commute distance with the use of navigation button shown below:

![image](https://github.com/Temytopeariyo/Bike-Sales-Performance-Report/assets/81833143/aba78dc6-826a-4869-b340-e293b35e9c56)



Recognizing the potential need to address questions related to quantities purchased as it relates to income by occupation of customers, I implemented a navigation button. This button enabled a seamless transition to an analysis centered on quantities, addressing a specific aspect of the data for a more comprehensive perspective. The visual reports in terms of both average of income and Occupation is shown below:

![image](https://github.com/Temytopeariyo/Bike-Sales-Performance-Report/assets/81833143/6b933381-e17a-4d1f-a0b7-eaa84808dc72)

### Sales Report - Visualization
Within the sales report, a range of visualizations were constructed to illuminate various aspects. Firstly, a visual depiction of age bracket distribution in relation to total sales that was generated, shedding light on how different age groups contribute to overall sales. Similarly, separate visuals illustrated the correlation between customer gender, marital status, and total sales, offering distinct insights.The visual report is shown below:

![image](https://github.com/Temytopeariyo/Bike-Sales-Performance-Report/assets/81833143/c006587a-d30c-4d1e-a7f9-1704af24c982)
![image](https://github.com/Temytopeariyo/Bike-Sales-Performance-Report/assets/81833143/94ac879d-d39d-4c26-9625-5c211574f5be)


Employing a map visualization, geographical data was harnessed to reveal the origins of sales and their magnitudes across region in the state on the second sheet of the project. The visual report is shown below:

![image](https://github.com/Temytopeariyo/Bike-Sales-Performance-Report/assets/81833143/0a21e1d2-f5f8-4dcd-9b3e-a4d4bb1e8bd4)


Incorporating the slicers enhance navigation that helps us differenciate Gender, Marital Status, and Region dispositions toward bike purchase. A consistent framework was established for the sales performance report, enabling a cohesive analysis across regions by selecting through the slicers to visualise bike purchased through the use of navigation button shown below:


![image](https://github.com/Temytopeariyo/Bike-Sales-Performance-Report/assets/81833143/c09460ba-3ff4-4cef-9f41-108c03b190fb)

You can interact with the report HERE

### Insights and Recommendations
The top customers, based on their significant sales contributions, play a vital role in boosting the company's revenue. These high-value customers likely possess considerable purchasing power attributed to their occupation, age bracket, Education and Commute distance. 

Our analysis covered a range of intriguing sales trends. The total customers across the distributions amounted to 1,000 out of which, 511 were Males and 489 were Females. Notably, 481 out of the 1,000 were bike buyers and the remining 519 were none bike buyers. Based on the occupational distribution of Bike buyers, Professional occupational group has the highest customers of bike buyers followed by Skilled Manual which recorded 115, while Clerical has 88, Management 75 and the least bike buyers based on the occupational category is Manual with a total number of 55 bike buyers.
There was a notable surge in total sales, reaching 200 quantities sold based on commute distance of 0 -1 mile to the store. While quantities sold witnessed a decrease to 33 on the commute distance above 10 miles to the Bike store. An unprecedented peak emerged to the distance of 2-5 miles, recording the highest 95 sales despite its distance to the bike store. Summarily, one can hardly say that the commute distance greatly affects bike purchase as customers living 2.5 miles to the Bike store buy more than the customers living 1-2 miles. Hence, the analysis provides a positive outlook for sales beyond the parameters provided.

You can interact with the report HERE
