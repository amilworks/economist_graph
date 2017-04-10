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





When I first looked at this graph, I knew plotting the data was going to be easy. I see a scatter plot layered on a line. Easy, right? Well, kind of. In this project, we will try to get as close as we can to the actual output from _The Economist_ using the ggplot library. 



## Inspiration and Documentation

__The Economist__
* How can you not be inspired by their graphs! Look at what they plotted and try to figure out a reason for why, say, a histogram was more useful and informative instead of, say, a scatterplot matrix. 
http://www.economist.com/blogs/graphicdetail

__Harvard Workshop on `ggplot`__
* Harvard put together a workshop that introduced students to `ggplot` in the most Harvard way possible--"reproduce this graph from _The Economist_ given these tools we will discuss in the workshop." Talk about throw them to the lions and come out alive. My first `ggplot` was attempting a scatterplot. They give excellent information here and the challenge was this same exact graph that we will replicate. Unfortunately, they did not give a solution so most of this project was me doing trial and error and a ton of Google searches. I am sure there are better and more efficient solutions to my code, but that is your challenge.
http://tutorials.iq.harvard.edu/R/Rgraphics/Rgraphics.html
