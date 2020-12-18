---
id: POIs
name: POIs
heading: Behaving like natives
subheading: 
image: "img/coffee.jpg"
---

Now that we have an idea of how sociable natives are, we need to identify how they behave and in particular the places of interests they go to. We'll call them POIs. In order to do so, we must identify the places they go to, at what frequency, and what combinations of places they go on the same day.

We first have a look at the USA. In the table below, you will find the top thirty of the most visited POIs in the US dataset. It can be helpful to know which seats are popular and which are not, especially if your goal is to make friends. We put the number of Check-ins so as to compare the values and to see how much more popular are the top values in comparaison with the other values.

<br> 

| POIs              | Number of checkins | POIs | Number of checkins |
|:--------          |:-------:|--------:|:--------:|
| Home (private)    | 57'199 | Residential Building (Apartment / Condo) | 16191   |
|----
| Office            | 46'155 | Fast Food Restaurant 	   |14766   |
|----
| Coffee Shop 	     | 41905 | Mall   | 14572   |
|----
| Airport            | 39503 | Road 	   |12690 	   |
|----
| Gym	              | 33533 	 | Church	   |12532  |
|----
|American Restaurant| 31631 | Pizza Place   |12442   |
|----
|     Bar	        | 28661 | Burger Joint   |12078   |
|----
|Grocery Store| 27498 | Park  |11782   |
|----
|Building| 20612 | General Travel  |10658  |
|----
| Hotel  | 20564 | Sandwich Place    |10499   |
|----
| Gas Station / Garage 	| 20206 | Italian Restaurant 	 |9326   |
|----
| Other Great Outdoors    | 17650 | Train Station   |9325   |
|----
|Mexican Restaurant   |17331 | Neighborhood | 8906   |
|----
|Gym / Fitness Center 	| 16570| Theme Park  |8455   |
|----
| Department Store  | 16465 | Miscellaneous Shop  |8379   |
|----
|=====
{: rules="groups"}

<br> <br> 

We now plot the values:


 ![image](img/NbOfCheckinsPerPoisUS.png){: style="float: left"; height="55%"; width="55%"}

You have the answer, these are the most famous types of places in USA when you only look at the number of check-ins. On the one hand, a lot of people check-in while at home or on the workplace. This results seems logical because they are the two places where people spend the most time. On the other hand, you will find POIs that don't have a lot of checkins like Paella, Moroccan, Swiss, Portugueuse and Turkish restaurants. If you plan to open a restaurant in America, you would prefer to avoid this kind of restaurants because of their have poor success. If you want to bring in customers, still with the local cuisine.
Some other interesting results are roof decks with 29 checkins (going on roofs is not a very good way to socialize), conventions with 4 and Internet Cafe with 91 checkins. The later shows that these places are not as much popular in USA as they used to be. Indeed, most people in America have computers at home, while in South Korea it is still common to go to an Internet Café to work or play.

---

Something else that is also interesting to observe is the combination of activities. What is the average day of an American citizen in terms of destinations ? We have paired the visited places together and you can see in the figure below the result.

 ![image](img/nbofcheckinsforplacesvisitedtogetherUS.png){: style="float: center"; margin-right: 10em; height="55%"; width="55%"}

When we look at the places visited together, we notice that there are a lot of them that are of the form (Place, Home (private)) This comes from the fact that, as we have seen before, Home (private) is the most popular chackin place for our population. We notice that among our popular combinations, we have some that can be explained both intuitively and culturally. For example, the combination (Coffee Shop, Office) comes from the fact that "coffee breaks" at the coffee shop are very popular in America and also because taking breakfast at a Coffee shop is also popular. The combination, (Airport, Hotel) can be explained intuitively as "when we come from the airport, we have to find a hotel to stay". However, the fact that it is the fifth most popular combination can only be explained as "In the US, since the country is so large, it is much more common to travel by plane".


Now let's take the dataset of Japan to look at the same information as before. We start with the popular destinations :

   ![image](img/NbOfCheckinsPerPoisJapan.JPG){: style="float: center"; margin-right: 10em; height="55%"; width="55%"}
   
If we look top 20 POIs of Japan, Train Station is top 1. What we can guess is that Japanese people use the public transport a lot, both for work and leisure purposes. The japanese Shinkansen is renowned in the whole world and this could explain its success. Moreover, car ownership is not especially common in Japan. For the other POIs, we notice that local food is privileged with noodle houses and Japanese Restaurants in the top 5 of most popular POIs. We are also glad to see that Arcades survived somewhere at least. The fact of having arcades is a cultural thing.
Unfortunately Train Stations are a very busy place, it is not very proctical for meeting people, especially if they are all on their phones. So much for making friends.

If we pair the places visited on the same day, we get the following figure.

 ![image](img/nbofcheckinsforplacesvisitedtogetherJapan.JPG){: style="float: center"; margin-right: 10em; height="55%"; width="55%"}
It becomes difficult to infer meaningful information from the combinations of checkins since "Train Station" is extremely prevalent.


---

Now that we have had a detailed view for Japan and the US, let us have a look of the most popular POIs for our other countries.

 In order to achieve this goal, the same procedure was applied to the other countries announced previously. Since we want to make friends, we do a filtered results where we remove private places where you can't come in and socialize. For example, we removed "Home (private)".

 So we have (from left to right countries with the most checkins):
<br> 

 |       USA | Indonesia | Brazil           | Turkey | Japan        | Malaysia | Mexico | Thailand | Philippines |
|:-------- |:-------:|--------:|:--------:|:-------- |--------:|:--------:|:-------- |:-------:|
| Office  | Mall |Office      |  Café   | Train Station | Mall | Office | Mall | Mall |
|----
|Coffee shop|Indonesian Restaurant|   Mall | Mall    | Subway         | Malaysian Restaurant | Mall | Thai Restaurant | Office |
|----
| Airport |Church | Neighborhood |   Restaurant   | Convenience Store | Asian Restaurant | Mexican Restaurant | Train Station | Coffee shop |
|---- 
| Gym | Asian Restaurant | Gym  |   Café   | Ramen/Noodle House |  Indian Restaurant | Gym | Coffee shop | Fast food restaurant |
|----
| American Restaurant | Airport | Brazilian Restaurant  | Beach   | Japanese Restaurant | Café | Coffee shop | Japanese Restaurant | Church |
|----
|=====
{: rules="groups"}

<br> <br> 
The first thing you can notice is the type of restaurant that is in each country. A Mexican restaurant will be more popular in Mexico, while a Japanese restaurant will be more popular in Japan. "In Rome, eat as Romans eat".

Then, we notice that some POIs come back in several countries. This is logical : no matter the country, people have to go to the office or buy products at the mall. Therefore, if you didn't have the time to study the country beforehand, you can still go to these places to socialize. For example the Mall comes back in the top POIs of 7 of the 9 countries we studied.
