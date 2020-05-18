# IE_Hygieia_Shiny_Apps
All the Shiny Application development that took place in the final semester's Industrial Experience project as part of the Hygieia team at Monash University.

Twitter Extraction Widget : https://shivong27.shinyapps.io/Twitter_Analytics_Hygieia/

The Twitter Shiny application helps the user understand what people are talking about on infections in the online world. It also helps them understand which organizations are concerned about one’s health (e.g. WHO, CDC) by looking at the most popular twitter handles which tweet about a particular infection, pandemic news etc. Although it is a general Tweets extraction application, we have left it upto the user to search whatever he/she wants. 

In the making of this application, a Twitter developer account was used which can be accessed here : https://developer.twitter.com/en , this platform helps the developer, like us, to create an API (Application Programming Interface) to connect to core Twitter data over the past few days and bring them into a statistical analysis software like R, SPSS etc. To be successful in connecting to Twitter, we used access tokens and other keys to connect to our developer account application on Twitter developer. In our case, we used to connect the API in R, so that we could import the data into the Shiny framework to build our application. 

Shiny is an open-source R package that makes it easy to build interactive web apps straight from R. We used shinyapp.io to host our webapp, as it is as simple as pushing a button to deploy the web application to cloud. We have used a dynamic wordcloud to show the most number of words that pop up for one particular topic, as we believe that it is pretty good at summarizing what is being talked about one particular topic on online. 


Plotly Viz Widget : https://shivong27.shinyapps.io/PlotlyViz_Hygieia/

Weather API Widget : https://shiivong.shinyapps.io/Weather_Hygieia/

Nearest Hospital Finder : https://shivong27.shinyapps.io/NearestHospitalFinder_Hygieia/
