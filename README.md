# Replicating a Graph from _The Economist_

## Data Scientists and Visualizations

If you have not already seen, head over to _The Economist_ and check out their website. In particular, look at the graphs they created here: 

http://www.economist.com/blogs/graphicdetail

The graphs they created are perhaps the paragon of data visualization. Their graphs are crisp, clean, and informative. Forget the article, the entire meat of the story is told through a graph that a five year old can read. Every data scientist faces, at some point, the question of, "what significant question do I answer through data visualization." Data scientists can clean and manipulate data like no other person can. But, I would argue, they are not true data scientists if they cannot form questions that no one knew they wanted answers to. 

## The Problem

The problem is I cannot teach you how to ask fascinating questions about the data you just cleaned. Actually, nobody can help you. There is no algorithm that can teach you what to extract from your data to answer a burning question. However, what you can do is become familar with a wide variety of topics such as sports, politics, technology, finance, and, most importantly, _your_ interests. You do not have to be an expert in every topic, but learn the patterns and problems that those topics face. Only then will you begin to see the interconnectedness across all disciplines. 

## Project Abstract

In this project, we will tackle __Data Visualization__ in `R` using the beautiful package `ggplot`. In particular, we will try our best to replicate this graph created by _The Economist_. 



![Economist](https://cloud.githubusercontent.com/assets/22850980/24850224/0dedd2e8-1d84-11e7-88e6-4137b3f662fb.jpg)



When I first looked at this graph, I knew plotting the data was going to be easy. I see a scatter plot layered on an $R^2$ line. 
