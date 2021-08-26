# TAMU_Datathon2020

**Challenge:** City Search Tool <br />
**Problem:** Find a way to select the best place on earth to move to based on (suggested) median income of a location, cuisine, primary ethnicity, pollution index, happiness index, number of coffee shops or microbreweries in the city, etc. <br /> <br />


***Columns***  <br />
City Name: City Name <br />
Country: Country Name <br />
Purchase Power: comparing average cost of living with the average local wage <br />
Pollution: low is good. A score of how polluted people find the city, includes air, water, and noise pollution <br />
Health Care: compiled from how citizens feel about their access to healthcare, and its quality (average of health care column from numbeo and movehub dataset) <br />
Quality of Life: balace of health care, pollution, purcahse power, crime rate to give an overall quality of life score <br />
Cost of Living: is an estimation of consumer goods prices including rent comparing to New York City <br />
Safety Index:high safety index means the city is considered very safe <br />
Crime Rating: lower the score the safer people feel in the city <br />
Climate Index: is an estimation of the climate likability of a given city or a country. It is in the range [-100, +100] (higher is better) <br />
Traffic Time Index: average oneway time needed to transport in minutes <br />
lat: latitude of city <br />
lng: longitude of city <br />
City_Codes: City Name encoded as integers  <br /> <br />


What we built: Essentially what we have is a notebook for users to be able to put what they value in terms of what is important to them when moving to a new location. The interactive drop downs and sliders allow the user to do that and utilizes the dataset the TD has given us with the City Search Tool challenge and the dataset that we have found ourselves online.</br>

Challenges in Project: The biggest ones we faced that we ended up not being able to solve due to not enough time or not enough knowledge happened to go with the interactive design and getting the GUI to work with our code. We wanted to have a dropdown box that allowed the user to select what type of plot they wanted to see but it didn't work out so we had to settle with just allowing the user to select the x and y for data visualization. The challenges that we did overcome was, in the beginning, we had only used only three datasets which were ALL from Numbeo but then when we re-read the challenge description it seemed like TD wanted us to use the movehub csv as well so it was quite a bit of time trying to figure out how we were going to merge the numbeo datasets with movehub dataset. In the end, we think it was pretty clever what we had to do, for one we had two columns dealing with pollution in that were attached to the same city/country. We ended up just taking the largest value of pollution because it's' generally a lot of pollution in the world and if a user were to believe that the certain location they moved to was xx in pollution vs in yy pollution they might not be happy so it's better to overshoot the pollution.</br>

What we have learned: Definitely learned how to join multiple datasets and work with python widgets. It's extremely cool to start doing interactive things versus hardcoding everything</br>


### Data Use: 
<p>Effectively used data, acquired additional data </p>

```diff
+ aquired new data by importing three datasets we found

```

### Analytics: 
<p>Effective application of analytics (bonus points for ML/clustering techniques)</p>

```diff
+ Used a decistion tree and random forest regressor

```

 ### Visualization: <p>Solution is visually appealing and useful (Bonus points if you create an interactive tool/application/website)</p>

```diff
+  Used interactive widgets to show our graphs and to let user choose what features to use in the model

```

### Impact: 
<p> Clear impact of solution to solving problem</p>

```diff
+  Solution is to get through the modeling section and get the list of cities, then look up the city based on it's code. <b>The impact of our project is that people will be able to select the best place on earth to move to, based on the features and importance values they they hold to themselves.</b>

```

**Resources** <br />
One data set is from TAMU Datathon from City Search Tool page in TD website and retrieved from https://www.datalogz.io/ <br />
We got three datasets from https://www.numbeo.com <br />
Specifically our Multi_Value_Numbeo.csv is from https://www.numbeo.com/cost-of-living/rankings_current.jsp <br />
The Quality_of_Life_Numbeo.csv is from https://www.numbeo.com/quality-of-life/rankings_current.jsp <br />
The Property_Prices_Numbeo.csv is from https://www.numbeo.com/property-investment/rankings_current.jsp <br />


