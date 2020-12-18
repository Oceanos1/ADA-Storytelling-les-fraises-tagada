---
id: context
name: Context
heading: Context of this datastory
subheading: 
image: "https://picsum.photos/id/1/500/500"  
---


In the paper, "Friendship and mobility : User movement in Location-Based Social Networks", the authors answered one important question : what influence do friends have on movements ?
But what if you don't have friends in the first place and just want to blend in ? Imagine : You just arrived in a new country. You don't know how to behave with the locals and what to expect. How friendly are people ? How often is it socially acceptable to meet ? Where should you meet ? Where and when should you go on holidays ?
In this storytelling, we will attempt to answer some of these questions for multiple countries.





We found our datasets “Global-scale Check-in Dataset with User Social Networks” from [two research projects](https://sites.google.com/site/yangdingqi/home/foursquare-dataset#h.p_7rmPjnwFGIx9) (project 5 by Dingqi Yang). The dataset is coming from *Foursquare* and it contains the information of **22,809,624 checkins** by **114,324 users**, **607,333 friendship links** and **3,820,891 POIs**. It contains a set of worldwide check-ins with country flags taken over about two years and two snapshots of the corresponding user social network before (in Mar. 2012) and after (in May 2014) the check-in data collection period.
In order to work with this dataset, we broke it down in smaller datasets, based on countries. In order to learn more on how we broke our dataset down, please consult the scripts ["createSubDataset.ipynb"](https://github.com/epfl-ada/ada-2020-project-milestone-p3-p3_les-fraises-tagada/blob/master/createSubDataset.ipynb) and ["preprocess.ipynb"](https://github.com/epfl-ada/ada-2020-project-milestone-p3-p3_les-fraises-tagada/blob/master/preprocess.ipynb).

![gras](img/test.jpg){: class="rounded"}
