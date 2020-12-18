---
id: POIs
name: POIs
heading: Behaving like natives
subheading: 
image: "img/coffee.jpg"
---

Now that we have an idea of how sociable natives are, we need to identify how they behave and in particular the places of interests they go to. We'll call them POIs. In order to do so, we must identify the places they go to, at what frequency, and what combinations of places they go on the same day.

In the table below, you will find the top thirty of the most visited POIs in the US dataset. It can be helpful to know which seats are popular and which are not, especially if your goal is to make friends.

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

Here's the top twenty POIs with a visualization:


 ![image](img/NbOfCheckinsPerPoisUS.png){: style="float: left"; height="55%"; width="55%"}

You have the answer, these are the most famous types of places in USA when you only look at the number of check-ins. On the other hand, you will find POIs that don't have a lot of checkins like Paella, Moroccan, Swiss, Portugueuse and Turkish restaurants. This data can always be useful to you, for example if you plan to open a restaurant in America because you would prefer to avoid this kind of restaurants because of their poor success.
You'll also find other interesting results like roof decks with only 29 checkins, conventions with 4 and Internet Cafe with 91 checkins, probably because they are not as much popular in USA as they used to be. For example, most people in America have computers at home, while in South Korea it is still common to go to an Internet Café to work or play.

---

Something else that is also interesting to observe is the combination of activities. We have paired the visited places together and you can see in the figure below the result.

 ![image](img/nbofcheckinsforplacesvisitedtogetherUS.png){: style="float: center"; margin-right: 10em; height="55%"; width="55%"}

When we look at the places visited together, we notice that there are a lot of them that are of the form (Place, Home (private)) This comes from the fact that, as we have seen before, Home (private) is the most popular chackin place for our population. We notice that among our popular combinations, we have some that can be explained both intuitively and culturally. For example, the combination (Coffee Shop, Office) has already been mentionned earlier. While the combination, (Airport, Hotel) can be explained intuitively as "when we come from the airport, we have to find a hotel to stay". However, the fact that it is the fifth most popular combination can only be explained as "In the US, since the country is so large, it is much more common to travel by plane".


Now let's take the dataset of Japan to look at the same information as before. If we paired the most visited places together, we get the following figure.

 ![image](img/nbofcheckinsforplacesvisitedtogetherJapan.JPG){: style="float: center"; margin-right: 10em; height="55%"; width="55%"}

  It becomes difficult to infer meaningful information from the combinations of checkins since if we look top 20 POIs of Japan, Train Station is top 1. What we can guess is that Japanese people use the public transport a lot, both for work and leisure purposes.
  Unfortunately, even if it is a very busy place, it is not very conducive to meeting people, especially if they are all on their phones.

   ![image](img/NbOfCheckinsPerPoisJapan.JPG){: style="float: center"; margin-right: 10em; height="55%"; width="55%"}


---


 This beginning of POIs analysis is done on the dataset of a two different country and although it can be very useful for someone going to America or Japan, it can be interesting to ask which POI are the most frequented independently of the country.

 In order to achieve this goal, the same procedure was applied to the top 10 countries with the most checkins. Remember that this is the filtered results where we removed the checkins that were irrelevant like the home of a user.

 So we have in order from left to right countries with the most checkins:
<br> 

 |       USA | Indonesia | Brazil           | Turkey | Russia | Japan        | Malaysia | Mexico | Thailand | Philippines |
|:-------- |:-------:|--------:|:--------:|:-------- |:-------:|--------:|:--------:|:-------- |:-------:|
| Office  | Mall |Office      |  Café  |Office   | Train Station | Mall | Office | Mall | Mall |
|----
|Coffee shop|Indonesian Restaurant|   Mall | Mall  |Mall   | Subway         | Malaysian Restaurant | Mall | Thai Restaurant | Office |
|----
| Airport |Church | Neighborhood |   Restaurant  | Coffee shop | Convenience Store | Asian Restaurant | Mexican Restaurant | Train Station | Coffee shop |
|---- 
| Gym | Asian Restaurant | Gym  |   Café  | Train Station | Ramen/Noodle House |  Indian Restaurant | Gym | Coffee shop | Fast food restaurant |
|----
| American Restaurant | Airport | Brazilian Restaurant  | Beach   | Restaurant | Japanese Restaurant | Café | Coffee shop | Japanese Restaurant | Church |
|----
|=====
{: rules="groups"}

<br> <br> 
The first thing you can notice is the type of restaurant that is in each country. A Mexican restaurant will be more popular than in Mexico, while a Japanese restaurant will be more popular in Japan. This can be due to the number of people who go there or because it is a popular cuisine in the country.

Then, we notice that some POIs come back in several countries, which would indicate that no matter the culture, they remain important and can be good places by default to meet people, as for example the Mall which comes back in the top 5 of 8 of the 10 countries with the most check-ins.