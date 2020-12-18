---
id: POIs
name: POIs
heading: Behaving
subheading: Like Natives
image: "https://picsum.photos/id/2/500/500"
---

Now that we have an idea of how sociable natives are, we need to identify how they behave and in particular the places of interests they go to. We'll call them POIs. In order to do so, we must identify the places they go to, at what frequency, and what combinations of places they go on the same day.

Here's the top most 30 frequented POIs in the USA dataset:

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

Now let's remove the POIs that can't be really visited by a traveller or that doesn't really make sense for meeting new people. Here's the top 10 POIs:

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

Here you are, those place are the most famous according to the number of checkins ! As opposite, we find that some of the place that have the less checkins are Paella, Moroccan, Swiss, Portugueuse and Turkish restaurants. It can always be useful data if you plan to open a restaurant in USA since you might want to avoid those restaurant type.
You'll also find some other interesting low results like Roof Deck with only 29 checkins, convention with 4 and Internet Cafe with 91 checkins.

We might also want to analyse why they go out and to do so, we pair places visited together and you can see in the following figure our results.


 ![image](img/nbofcheckinsforplacesvisitedtogetherUS.JPG){: style="float: center"; margin-right: 10em; height="55%"; width="55%"}