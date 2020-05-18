# IE_Hygieia_Shiny_Apps
All the Shiny Application development that took place in the final semester's Industrial Experience project as part of the Hygieia team at Monash University.

# Twitter Extraction Widget : https://shivong27.shinyapps.io/Twitter_Analytics_Hygieia/

The Twitter Shiny application helps the user understand what people are talking about on infections in the online world. It also helps them understand which organizations are concerned about one’s health (e.g. WHO, CDC) by looking at the most popular twitter handles which tweet about a particular infection, pandemic news etc. Although it is a general Tweets extraction application, we have left it upto the user to search whatever he/she wants. 

In the making of this application, a Twitter developer account was used which can be accessed here : https://developer.twitter.com/en , this platform helps the developer, like us, to create an API (Application Programming Interface) to connect to core Twitter data over the past few days and bring them into a statistical analysis software like R, SPSS etc. To be successful in connecting to Twitter, we used access tokens and other keys to connect to our developer account application on Twitter developer. In our case, we used to connect the API in R, so that we could import the data into the Shiny framework to build our application. 

Shiny is an open-source R package that makes it easy to build interactive web apps straight from R. We used shinyapp.io to host our webapp, as it is as simple as pushing a button to deploy the web application to cloud. We have used a dynamic wordcloud to show the most number of words that pop up for one particular topic, as we believe that it is pretty good at summarizing what is being talked about one particular topic on online. 


# Plotly Viz Widget : https://shivong27.shinyapps.io/PlotlyViz_Hygieia/

# Weather API Widget : https://shiivong.shinyapps.io/Weather_Hygieia/

# Nearest Hospital Finder : https://shivong27.shinyapps.io/NearestHospitalFinder_Hygieia/

This application helps the user find the nearest hospital in Victoria, Australia based on LGA (Local Government Area), Type of Hospital (Public or Private) and most importantly, by the preferred language of the user (English, Hindi, Mandarin, Arabic etc.). The list of hospital datasets comes from a government website and includes the coordinates for the hospitals, their names, which LGA they are situated in, their postcode etc. To make things interesting and to develop a proof of concept, we randomly added languages as a new column to showcase that we can match people with Hospitals based on their preferred language. For e.g. if an Iranian man wants to see a doctor who speaks Farsi, as the man is not very good at English, then it would be one hell of a problem to locate a doctor who could. But not with our application, we can pinpoint exactly where the Hospital is located on the map and give information about it to the concerned person.

We used Leaflet, which is one of the most popular open-source javascript library for interactive maps. It’s used by websites like Github, NY Times, Flickr etc. for their platforms. Leaflet allows us to integrate an interactive map and build on top of it, it allows us to add markers, add polygons, add different shapes, play around with the coordinate system, draw points to cover an area, cluster points on a map as one etc. We can also use custom map layers as basemaps, create popups for the user and much more. The best part is that it works effortlessly with R and especially Shiny, it has it’s own render functions for input and output. You can read more about the library at : https://rstudio.github.io/leaflet/ 

