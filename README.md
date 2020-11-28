# Social-Network-Analysis
Exploring classroom atmosphere via relationship network

Social network anlaysis has found utility is institutional, classroom and analyses of networked data in socially-based educational games. However, the utility of the method largely rests on being able to ascribe meaning to the structure of the network. Without meaningful interpretation of structure there is no added value to a networked model, you will find more success simply regressing your outcome against student characteristics. Understanding measures of centrality and network structure in SNA are therefore an important, though difficult, aspect of the method. As with all SNA work, the vocabulary can be daunting though the ideas are relatively intuitive.

## Packages:
library(tidyverse)
library(igraph)

## Terminology
Degree centrality: Degree centrality measures # the number of its adjacent edges for each layer .

Closeness centrality: Closeness centrality measures how many **steps** is required to access every other vertex from a given vertex.
It is the **average length** of the shortest path between the node and the other nodes. 

Betweenness centrality: It is a measure of how often a node is a bridge between other nodes.The vertex and edge betweenness are (roughly) defined by the number of geodesics (shortest paths) going through a vertex or an edge.


## Goals for this unit

* Be able to generate a basic sociogram
* Be able to apply and interpret a range of centrality measures to a network
* Be able to apply and interpret a range of clustering procedures to a network

## Tasks for this unit

In this unit you will be working towards building several social network diagrams (graphs/sociograms) of a school classroom and then analyzing both centrality measures and clusters within the network. As background to this task please read over the follwing materials and watch the methodological videos. If you find any other useful materials please add them under Additional Materials at the end of the this page and pull request the change back to this repo.

## Readings

[Bakharia, A., & Dawson, S. (2011). SNAPP: A Bird’S-eye View of Temporal Participant Interaction. In Proceedings of the 1st International Conference on Learning Analytics and Knowledge (pp. 168–173). Banff, Alberta, Canada:ACM.](https://doi.org/10.1145/2090116.2090144)

[Hanneman, R. & Riddle, M. (2005). Introduction to Social Network Methods. Riverside, CA:  University of California, Riverside](http://faculty.ucr.edu/~hanneman/)  
  * [Chapter 10: Centrality & Power](http://faculty.ucr.edu/~hanneman/nettext/C10_Centrality.html)  
  * [Chapter 11: Cliques & Subgroups](http://faculty.ucr.edu/~hanneman/nettext/C11_Cliques.html)  

## Videos

[Williams, N. (2014). Basics of Social Network Analysis.](https://www.youtube.com/watch?v=PT99WF1VEws)

[Complexity Labs. (2015). Social Network Analysis Overview.](https://www.youtube.com/watch?v=fgr_g1q2ikA)

[Complexity Labs. (2015). Network Centrality.](https://www.youtube.com/watch?v=NgUj8DEH5Tc)

[Complexity Labs. (2015). Network Clustering & Connectedness.](https://www.youtube.com/watch?v=2Oa7mef77nM)


## Additional Materials
[iGraph. (2016). Get Started with R iGraph](http://igraph.org/r/#docs)

[Social Network Analysis with R - Examples](https://www.youtube.com/watch?v=0xsM0MbRPGE)
