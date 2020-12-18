---
id: friends
name: Friends and Natives
heading: How do natives behave with friends ? 
image: "https://picsum.photos/id/395/250"  
---

You have just set foot on new land. Before trying to make contact with the native, let us study how they treat their friends.

The first step is to see how far away friends live from one another. We start with the USA.

<br>
<br>
<br>
<p>
<center><img src="img/distancebtwfiendsshousefoursquareUS.JPG" alt="drawing" width="750"/></center>
<p/> <br>
While most friends live close to us, the distance between friends' house can still reach big numbers (this can be explained by the fact that if one person from the east coast is friend with smebody from the west coast, our distance should be very big. <br>
We notice that our distribution plot is very similar to the one we obtained with the datasets from Gowalla and Brightkite. This result intuitively makes sense, since we work on the same country. The only different parameter is the year of study (and it shouldn't impact much our results, people don't move a lot overall). We now have a look at other countries.


<br>

<p style="color:black;font-size:25px;"><b>Comparing countries</b></p>
 <p>
<center><img src="img/distancebtwfiendsshousefoursquareAll.JPG" alt="drawing" width="750"/></center>
</p>
<br>

When we plot our results for all our countries, we notice that the countries with the widest areas are also the ones with the distribution of friends that is the most spread out (Russia and the US being enormous countries, no wonder that there are friends that live far away !) In order to confirm our hunch, we compte the 0.8 quantile for our distance and we get the following results :

<p>
<center><img src="img/nbOfFriendOfNativesJP.png" alt="drawing" width="750"/></center>
<p/>

<html>
<center>
  <head>
    <title>Distance between users : 0.8 th quantile</title>
    <b>Distance between users : 0.8 th quantile</b>
  </head>
  <body>
    <table border="collapse" style="width:100%">
      <tr>
        <th scope="row">Countries</th>
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
        <th scope="row">Most friends live within ... km</th>
        <th>2425</th>
        <th>400</th>
        <th>551</th>
        <th>117</th>
        <th>270</th>
        <th>312</th>
        <th>482</th>
        <th>64</th>
        <th>110</th>
      </tr>
    </table>
  </body>
  </center>
</html><br>

While this data confirms our hunch (with the US having friends who live further apart and Thailand being a small country, we find it normal that users live close together), we can't help but notice a strange value. Indeed, in India, the 8th quantile is only of 117 km. This can come from the fact that the richest part of India is the North. We expect most of our users to be living here and therefore close together. <br>

<p style="color:black;font-size:25px;"><b>Number of friends</b></p>

We now have a look at the number of friends of users. We notice a very big discrepency between the median and the mean. As is the case with social network, there are some "super-users" or influencers which attract a lot of friends. (Try to make contact with them, they will be able to introduce you to new people !)<br>
<p>
<center><img src="img/US_flag.jpg" alt="drawing" width="150"/><center/>
<p/>
 
In the US, most users don't have many friends on Foursquare. This can come from the fact that Foursquare being a position-based social network, it is more expercience-based then social based. We notice the presence of "super-users" like mentionned before. Since we have the values for friends in 2012 and 2014, we compare these numbers and notice a short increase. We can imagine that this low increase is due to the fact that Foursquare was launched in 2009 in the US and we are studying the numbers of 2013. The hype had the time to die down, all the people that wanted to join foursquare have already joined it by then.<br>
If you go to the US, natives have on average	7.95 friends in the new dataset (2013)
 <br>

 <p>
<center><img src="img/nbOfFriendOfNativesUS.png" alt="drawing" width="750"/></center>
<p/>


<p>
<center><img src="img/JP_flag.png" alt="drawing" width="150"/></center>
<p/> <br>
On average in Japan, natives have more friend than the US : 8.04 friends in 2013. We don't know if it is Japanese people being more sociable or them having more "super-users".
There is a difference of 3 friends between the median and the mean in the new dataset (2013)
 Also the number of "super user" and number of friend increase more in time ! This can be explained by the fact that Foursquare was still growing in Japan : people are still interested by the app and still join it.


<p>
<center><img src="img/nbOfFriendOfNativesJP.png" alt="drawing" width="750"/></center>
<p/>

We now present the numbers for other countries.

<html>
<center>
  <head>
    <title>Average and median of number of natives friends in the new dataset (2013)</title>
    <b>Average and median of number of natives friends in the new dataset (2013)</b>
  </head>
  <body>
    <table border="1">
      <tr>
        <th scope="row">Countries</th>
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
        <th scope="row">Mean</th>
        <th> 7.95</th>
        <th>8.04</th>
        <th>8.38</th>
        <th>8.92</th>
        <th>9.46</th>
        <th>9.48</th>
        <th>9.94</th>
        <th>10.66</th>
        <th> 11.11</th>
      </tr>
      <tr>
      <th scope="row">Median</th>
        <th>3.00</th>
        <th>3.00</th>
        <th>4.00</th>
        <th>4.00</th>
        <th>4.00</th>
        <th>4.00</th>
        <th>4.00</th>
        <th>4.00</th>
        <th>4.00</th>
      </tr>
    </table>
  </body>
  </center>
</html><br>
