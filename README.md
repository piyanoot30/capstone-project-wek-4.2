# capstone-project-wek-4.2
                                      Coursera Capstone
                        IBM Applied data Science capstone 
          Opening Thai Restaurant in New York City USA.
                           BY: Piyanoot Aiken 
 Introduce 
New York City, often called simply New York, is the most populous city in the United States. With an estimated 2019 population of 8,336,817 distributed over about 302.6 square miles, New York City is also the most densely populated major city in the United States. Located at the southern tip of the State of New York, the city is the center of the New York metropolitan area, the largest metropolitan area in the world by urban landmass. With almost 20 million people in its metropolitan statistical area and approximately 23 million in its combined statistical area, it is one of the world's most populous megacities. New York City has been described as the cultural, financial, and media capital of the world, significantly influencing commerce, entertainment, research, technology, education, politics, tourism, art, fashion, and sports. Home to the headquarters of the United Nations, New York is an important center for international diplomacy.
In this project to find the best location to open the Thai restaurant in the New York City and bring the most way to get successful by competitive the best area and the target. In this project also may determine how population in the area who may like Thai food Such as Asia area by compare the most Thai restaurant in the area. For example in china town may have more Thai restaurant more than the other area because more popular for Asians. Therefor It the key to help find the spot to open Thai restaurant. 
Target Audience of this project and some demographic facts.
To invest the business target it important. In the New York City have Population over 8 million and have more people who speak the most language. To diversity culture and food. In the example china town that most restaurant are Asians food, chinses, Thai, India, Japanese, Korea etc. Since I am from Thailand to open Thai restaurant because Thai food are healthy and have a great ingredient. Every dish is more nurture by using herb it will help new York Lift style who are hurry up to work or don’t have time to cook and may have choice more than fast food.

Data 
To solve the problem, we will need the flowing data:
1.	New York data Containing the neighborhoods and boroughs 
2.	Latitude and Longitude coordinates of those neighborhoods. This is required to plot the map and get the venue data.
3.	Venue data, particularly data relate to restaurants. We are going to use this data to perform future analysis of the neighborhoods.
4.   Foursquare API
Data and Source and method 
We will explore the demographics of the neighborhoods in the New York City. Conducting descriptive analysis using Panda. Additional data will be gleaned by web scraping and API will be used to generate data.
Method 
-	Load data from https://cocl.us/new_york_dataset for New York City Neighborhood Borough designation is scraped using beautiful soup.  Scraped data is transformed to data frame
-	Create map of New York using latitude and longitude values. 

-	Create The API Request URL ‘’'https://api.foursquare.com/v2/venues/search?&client_id={}&client_secret={}&v={}&ll={},{}&radius={}&limit={}'.format(CLIENT_ID, CLIENT_SECRET, VERSION, lat, lng, radius, LIMIT)”  
-	Foursquare is called on showing the list to the neighborhoods within the top ten and this data is mapped  

-	Data analyze the top 10 neighborhoods of New York City by setting set number of clusters =5 and run k-means clustering.
Results for this project after run k-means to clusters the neighborhoods into five (5) clusters, with our clusters established, this data frame is merged with total scores data to provide us with final pieces of criteria in selecting the appropriate neighborhood(s).  

            
Conclusion – after the pandemic hit in 2020 the restaurant have more effect some business are closing permeant to be updated in the map is may be the information will changing very quickly however this project will give you the idea and location which the best to investing.  
