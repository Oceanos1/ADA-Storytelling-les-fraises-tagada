---
id: POIs
name: POIs
heading: Behaving
subheading: Like Natives
image: "img/coffee.jpg"
---

Now that we have an idea of how sociable natives are, we need to identify how they behave and in particular the places of interests they go to. We'll call them POIs. In order to do so, we must identify the places they go to, at what frequency, and what combinations of places they go on the same day.

In the table below, you will find the top thirty of the most visited POIs in the US dataset. It can be helpful to know which seats are popular and which are not, especially if your goal is to make friends.

| POIs              | Number of checkins | POIs | Number of checkins |
|:--------          |:-------:|--------:|:--------:|
| Home (private)    | 36'438 | Mall   | 9'426   |
|----
| Airport           | 21'801 | Fast Food Restaurant 	   |8'887   |
|----
| Coffee Shop 	    | 20'811 | General Travel   | 8'565   |
|----
| Office            | 20'787 | Mexican Restaurant 	   |7'727   |
|----
| Grocery Store	    | 15'759 | Train Station 	   |6'786   |
|----
|American Restaurant| 14'837 | Park   |6'651   |
|----
|     Bar	        | 14'528 | Neighborhood   |6'650   |
|----
|Gas Station / Garage| 14'478| Theme Park  |6'351   |
|----
|Other Great Outdoors| 13'201| Pizza Place   |6'076   |
|----
| Hotel             | 12'247 | Burger Joint 	   |5'759   |
|----
| Building 	        | 11'960 | Gym / Fitness Center |5'748   |
|----
| Gym               | 11'308 | Church   |5'502   |
|----
|Road               | 11'219 | Miscellaneous Shop | 5'326   |
|----
|Residential Building| 10'521| Sandwich Place  |5'247   |
|----
| Department Store  | 10'248 | Bank   |5'172   |
|----
|=====
{: rules="groups"}

---

Let's now remove POIs that can't really be visited by a traveler or that don't really make sense in the context of meeting new people. Here's the top 10 POIs:

| POIs    | Number of checkins | 
|:--------|:-------:|
| Coffee Shop   | 20’811   | 
|----
| Grocery Store |  15’759  |
|----
| American Restaurant 	   | 14’837   | 
|----
| Bar   | 14’528  | 
|----
| Gas Station / Garage	   | 14’478   | 
|----
| Gym   | 11’308  | 
|----
| Department Store |  10’248  |
|----
| Mall 	   | 9’426   | 
|----
| Fast Food Restaurant   | 8’887  | 
|----
| Mexican Restaurant  | 7’727   | 


You have the answer, these are the most famous types of places in USA when you only look at the number of check-ins. On the other hand, you will find POIs that don't have a lot of checkins like Paella, Moroccan, Swiss, Portugueuse and Turkish restaurants. This data can always be useful to you, for example if you plan to open a restaurant in America because you would prefer to avoid this kind of restaurants because of their poor success.
You'll also find other interesting results like roof decks with only 29 checkins, conventions with 4 and Internet Cafe with 91 checkins, probably because they are not as much popular in USA as they used to be. For example, most people in America have computers at home, while in South Korea it is still common to go to an Internet café to work or play.

---

Something else that is also interesting to observe is the combination of activities. We have paired the visited places together and you can see in the figure below the result.

 ![image](img/nbofcheckinsforplacesvisitedtogetherUS.png){: style="float: center"; margin-right: 10em; height="55%"; width="55%"}

---

 This beginning of POI analysis is done on the dataset of a single country and although it can be very useful for someone going to America, it can be interesting to ask which POI are the most frequented independently of the country.