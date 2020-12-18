---
id: Mobility
name: Of knowledge and power
heading: Predicting movements
subheading: 
---

Now that you start to know the behaviours of natives and their behaviours with friends, it is time to seal the deal ! Let us befriend a native ! <br>
<p style="color:black;font-size:25px;"><b>The first Checkin of the day</b></p>

Everyone knows that the best way to make friends with somebody is to <s> stalk them until they finally acknowledge us </s> pay attention to their centres of interests, we have created a model to predict the places where our friends are most likely to present themselves ! In order to do our study, we took all our check-ins and classified them as "first check-in of the day" or "Other check-ins". This classification seemed particularly interesting because it gives us the order in which people go to POIs during their day. It is also interesting because it is very rare that users check-in only once in the day (see table below).<br>

<html>
<center>
  <head>
    <title>Percents of times a user checked-in only once in the day</title>
    <b>Percents of times a user checked-in only once in the day</b>
  </head>
  <body>
    <table border="1">
      <tr>
        <th>US</th>
        <th>Japan</th>
        <th>Brazil</th>
        <th>India</th>
        <th>Malaysia</th>
        <th>Turkey</th>
        <th>Mexico</th>
        <th>Thailand</th>
        <th>Phillipines</th>
      </tr>
      <tr>
        <th>45%</th>
        <th>26%</th>
        <th>41%</th>
        <th>40%</th>
        <th>36%</th>
        <th>47%</th>
        <th>52%</th>
        <th>37%</th>
        <th>36%</th>
      </tr>
      
    </table>
  </body>
  </center>
</html><br>

A first example : we have seen in the last part that American users mostly checked-in from their houses. However, the first place from which they will check-in will be their office ! As shown in the figure below. We can interpret this as "American people go first to their office to work, they check-in from their house after work".

<tr>
<center><img src="img/first_POI_USA.png" alt="drawing" width=500 height=480/></center>
<tr/> <br>

From the graph, we also see that Coffee Shops are a popular place to check-in for the first time. This shows that American people like starting their day with a nice hot drink. <br>
Overall, most of the time, the distribution of POIs of the first checkins is the same as the distribution of the POIs of checkins. Sometimes we get no additional information from studying the first checkin of the day. For example, we have seen that Japanese users mostly check-in from train stations and the first Checkin of the day happens in a train station for 1/3 of the times. Every other places have indivifually less than a 5% chance of being chosen as the first check-in of the day ! However, other times, we get interesting results : in India also, we have a high probability of checking in a mall or in a Home (respectively 12 % and 10 %). These two places were already indicated as very popular from our overall checkin study. However, their position is inverted ! Indeed,  they were respectively the second and first most popular POIs to check-in at. This inversion can be due to the fact that people check-in at home after work (at the end of the day) and go shopping before that.<br>
<table>
<center>
  <tr>
    <td><img src="img/Number_checkins_per_poi_ID.png" width=500 height=480></td>
    <td><img src="img/first_POI_India.png" width=500 height=480></td>
  </tr>
  </center>
</table>
If the most popular POI is often the first POI our users check-in to, this can be due to multiple factors. A first case can be, when the most popular POIs are so popular that they overwhelm other POIs (like in Japan) or when the most popular place is a place where you spend your morning (at work for example). Another case is when users check-in only a few times per day (Like in Mexico where most of the time, users check-in only once a day)(See figure below which are very close from one another).

<table>
<center>
  <tr>
    <td><img src="img/Number_checkins_per_poi_Mexico.png" width=500 height=480></td>
    <td><img src="img/first_POI_Mexico.png" width=500 height=480></td>
  </tr>
  </center>
</table>
When we studied our cities, we were intrigued by the case of Brazil. Indeed : If the home is at least twice as popular as any other POI in term of total checkins, the numbers are more balanced when it comes to only the first checkin ! This seems to go with our idea that people check-in to their house only at the end of the day, after work or after leaisure activities.
<table>
<center>
  <tr>
    <td><img src="img/Number_checkins_per_poi_BR.png" width=500 height=480></td>
    <td><img src="img/first_POI_BR.png" width=500 height=480></td>
  </tr>
  </center>
</table>

<p style="color:black;font-size:25px;"><b>Other Checkins</b></p>

Let's imagine now that you have missed your friend. You know where he checked in and you want to know where he is going to check-in next (so that you can surprise him). We have the solution for you ! Based on the first Checkin of the day, we have put in place a predictor that can guess where our friend will go next ! For example, 
