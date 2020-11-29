# Social-Network-Analysis
Exploring classroom atmosphere via relationship network

Social network anlaysis has found utility is institutional, classroom and analyses of networked data in socially-based educational games. However, the utility of the method largely rests on being able to ascribe meaning to the structure of the network. Without meaningful interpretation of structure there is no added value to a networked model, you will find more success simply regressing your outcome against student characteristics. Understanding measures of centrality and network structure in SNA are therefore an important, though difficult, aspect of the method. As with all SNA work, the vocabulary can be daunting though the ideas are relatively intuitive.

## Packages:
`library(tidyverse)`<br>
`library(igraph)`

## Terminology
1. Degree centrality: Degree centrality measures # the number of its **adjacent edges** for each layer .

2. Closeness centrality: Closeness centrality measures how many **steps** is required to access every other vertex from a given vertex.
It is the **average length** of the shortest path between the node and the other nodes. 

3. Betweenness centrality: It is a measure of how often a node is a **bridge** between other nodes.The vertex and edge betweenness are (roughly) defined by the number of geodesics (shortest paths) going through a vertex or an edge.

4. Dyads in a directed graphs. The relationship between each pair of vertices is measured. It can be in three states: mutual, asymmetric or non-existent. 

5. Triad funciton: matrics whose 16 columns contain the counts of triads by class for each graph were provided.
 
6. Clique:  Subgroup with vertices and edges

7. Articulation point: Articuation points or cut vertices are vertices whose removal increases the number of connected components in a graph.


## Tasks for this project

In this project we will be working towards building several social network diagrams (graphs/sociograms) of a school classroom and then analyzing both centrality measures and clusters within the network. 
## Plots

<img src="./Best_Friend_Social_Network.pdf" alt="Editor" width="1000">

## Results and Insights

- After measuring the network, centrality and structural metrics on students' ideas of getting along with others, being best friends with others and intention to work with others, it seems that the class has a harmonous atmosphere that no one has been isolated so far. However, as the visulization and analysis showed, it appears two distinguishable groups bridged by student 13, indicating two possible trends in terms of choosing best friends, and selecting the preferable team player(s). There is also a gender distinction. When it comes to friendships, these teenager girls tend to have bigger social group than their opposite sex. Besides, female students tend to have larger clique than male students. Nonetheless, different gender groups still communicate with each other in the class. Student 8, 11, 14, 16, 20, 21, 22, 23 have quite high centrality in all the networks, which implies that these students serve as important connection to other students.In terms of reciprocity, there are more mutual and asymmeric dyads in "Get on with" network than the other two. 

- To support a more connected and dynamic classroom, the teacher can balance the proportion of students regarding gender when doing group projects to enhance the communication between gender groups. Also, the teacher needs to pay more attention on students who could easily drift away from the class, such as student 18 and 25, both of whom only get involved in the class via student 13. 

- Apart from these results, I am also interested in the hiearchical significance of the three networks.
- The results from this social network analysis remind me of my seventh grade, a time when early adolescents had small cliques representing some of their unique identity and characteristics. There were also popular students that connected different groups.    

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
