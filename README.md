# Social-Network-Analysis-on-Dark-Dataset

## Problem Statement

We will be analysing characters and different timelines through the data and find the outcome in respect to-

Important characters
Influential characters
Important timeline

## Dataset understanding and preparation

This dataset contains information about the relationship between the different characters present in different timelines of the Netflix original TV show Dark. Source : https://www.kaggle.com/datasets/deepcontractor/dark-netflix-character-relationship
Nodes: The dataset contains 83 nodes which are the distinct characters,years and type of relationship throughout the 3 seasons of the show
Edges:The dataset contains 215 edges which are the relationships between different characters
Key variables: Character_name
			         Character_years
               Characters_parentOF

    
## Exploratory data analysis

We used Tableau to do data analysis as we can see there are total 27 Character out of which 13 of them are female and 14 are male. Performed positive and negative sentiment analysis on the Dark TV show.

## Analytical approach

1)The most important character in dark
First, let's measure the importance of a node in a network by looking at the number of neighbors it has, that is, the number of nodes it is connected to. 
Note that there is no "correct" way of calculating the most important node in a network, every metric has a different meaning.
According to degree centrality Mikkel Nielsen is the most important node in the network since it is connected to most nodes
Which makes sense if he didn’t time travel in the first place a huge part of the plot wouldn’t have happened.

2) Most influential character in the series
According to the values of betweenness centrality we can see that Noah is the most influential character among all the timelines 
Which makes sense because he’s involved in multiple timelines and he’s seen interacting with a lot of characters on the show

3) Most important timeline in the series
This graph shows which timeline is more prominent. Out of 4 we can see in the graph 2019 is the most prominent followed by 1986, 1953 and the least prominent is 1921.
Here node size is according to degree
Node color is according to modularity class

## Interpretations

Using character relationship data of any tv show(like dark) or movie one can specify multiple network centrality measures that can be instrumental in defining the importance of characters in the show.
Overall, a network-based methodology is a fruitful and powerful technique in show/movie analytics: it can serve as a fully-scaled approach or may complement classical statistical instruments.

## Recommendations

The producers can make another show based on Mikkel Nielsen maybe a prequel,sequel or a spin off show since he was the most important character on the show. 
