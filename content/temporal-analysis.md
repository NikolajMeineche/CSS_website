---
title: Temporal Analysis
prev: data-analysis
next: mvw
---

In the history of harry potter books, there are 7 books. The first book was published in 1997 and the last book was published in 2007. Troughout the books many characters are introduced and the groups in which the main characters engage change. Futher many many different obstacles and villans appear over the course of the history forcing the characters into new and unexpected situations promoting interactions between previously unknown/insignificant character or even enemies. In this section we aim to give insigth trough a temporal analysis of the books and the characters. The focus is to ovserve the changes in the network over time trough analysis of the accumulated network of each chapter/book.

## Evolution of charcters and their interactions
In order to observe the evolution of the characters and their interactions we have created a network for each chapter and book. The nodes of the network are the characters and the edges are the interactions between them. The edges are weighted by the number of interactions between the characters. 

The following figure shows the evolution of the network over time. The nodes are colored by the community they belong to. The size of the nodes is proportional to the number of interactions of the character. The width of the edges is proportional to the number of interactions between the characters. (The end of each book is a checkpoint in the figure to show the evolution of the network over time)

<iframe
  src="/Networks.html"
  style="width:100%; height:750px"
></iframe>

Further to understand the difference between each book the following figure displays to most signifcant words for each book. The words are extracted from the text of the book and the size of the word is proportional to the significance of the word in the book compared with the words in the other. Notably is how significant horcrux is in the both the 6'th and 7'th book.

<iframe
  src="/WordCloud.html"
  style="width:100%; height:750px"
></iframe>

Here it can be observed how the text clealy follow each individual plot, with mom (Harry and the mirror) and turban (Proffesor Querriel) are significant words in the first book. Diary, pipes and basilisk in the second. And so forth.
## Breaking down the networks

Understanding how the network changes over time in terms of character, interactions can be a challeging task if simplify oberserving and trying to understand the internal structure of network. When a network grows in size key statistics help us under stand the network.

Further in order to access the theese values comparison with 20 random networks of same size and theoritically same number of links is carried out to understand the significance of the values. Allowing to pinpoint where the significance of the network lies.

The density of a networks describes the number of links in the network compared to the maximum number of links possible. Meaning that a network with a density of 1 is a complete network.

![](/images/Temporal/Density.png)

 As expected we see that the density of the network is equal to that of the random networks. Also the network density decreases over time. This reflects that trough out the history many new characters are introduced yet their introduction it's not accompanied by a proportional increase over the course of the history in the number of interactions. This is further supported by the fact that the density in the specific chapter is some what constant fluctuating around ~0.3 to ~0.5. Meaning that the chapter specefic networks are somewhat constant in density but after the introduction of new characters their inclusions in the later chapters is decreased.   
 
 In Terms of the history this can be explained by the fact that the new characters are introduced in the story but they are not part of the main group of characters and thus they do not interact with the main characters. 

 Above mentioned point is further supported when we look at how the nodes link to other node in the networks. Measuring degreee assortativity we can see whether the nodes with high degree link to other nodes with high degree or low degree.


![](/images/Temporal/DegreeAssort.png)

As can be seen in above figure the degree assortativity is negative. Meaning that the nodes with high degree link to nodes with low degree. This fits perfect with the previous observation that the new characters are introduced but they do not interact with the main characters. Also it is expected that a history of a book is not a random process and thus the degree assortativity is not zero. And since the history revolves around the main characters they would be the big center connecting the other characters in the universe



To Summuarize previous observations yield that many new characters are introduced with the main characters but their significance over the course of the history fades. Currently information under standing how the interractions betwen less significant characters is sparse. The Clustering coefficient is a measure of how well connected the neighbors of a node are. Meaning that a node with high clustering coefficient has neighbors that are well connected. 

The following figure shows the clustering coefficient of the network over time. 

![](/images/Temporal/Clustering.png)

Here the accumulated network clearly distinguishes it self from the random networks. The clustering coefficient of the network is much higher than that of the random networks. This means that the neighbors of the nodes are well connected. In the history new characters are thus often introduced as a group the interact with each other aswell as the main characters. This is further supported by the fact that the clustering coefficient is similar to that of the network meaning the groups within each chapter are well connected.

Observing the networks this can also be seen that each outer group are closely connected.

The shortest path of the network is the average shortest path between all nodes in the network. The shortest path is a measure of closely different nodes in is connected the network is. The shorter the path the better connected the network is.

![](/images/Temporal/ShortestPath.png)

As can be seen all nodes are very closely connected with an average shortest path ~1.9 reflecting well upon that fact the each node is closely connected and revolving around the main characters.


## Key Characters

 To acces the significance of the characters the centrallity of their nodes in the networks are considered. The centrallity of a node is a measure of how important/central the node is in the network. 


![](/images/Temporal/ComparedCentrallity.png)

Harry potter stands out as the most important charcter followed by Ron and Hermione. Dumbledore is also a very important character that gains more importance over time even after his death in the 6th book. Snape and Neville are key characters in the first books but their importance reaches a stable level over time. Ginny is almost insignificant in the first book but after her introduction in the second book her importance increases over time well reflecting that in the later books Harry and Ginni starts dating. Voldemort is the main villan of the history even though his actually precens is physically dormant up until the end of the 4th book. His presence and imortans lurks in the shadows trough out the history reaching it's peak in end of the 7th book.


![](/images/Temporal/CharacterCentrallity.png)

The apperance of the chracters in each chapter reflect harry as the main character aswell. Further it shows how Ron and Hermione are the main sidekick of harry and how the seem to appear equally within each chapter.

The only points where harry poters centrallity decreases is the appearence of Snape and Dumbledore. Which reflects the moments where Snape and Dumbledore discuss key matters with Harry in which it is of utmost importance that Harry does not known, For example the fact that Snape is actually a good guy and that Dumbledore is dying or that harry is a horcrux.

## Growing History and Audiance

As reflected in the words clouds of the books the topics of the books change over time. In the begning the books are more focused on the school life of Harry and his friends and the wonders of magic. Over time the books become more mature including more adult topics as first love problems and drame between friends. The books also become darker and more serious as the fight against Voldemort becomes more serious and the war between the good and evil becomes more serious introucing was and death. Consider for instance that in book two where charcters instantly die if they look in to the eyes of the bassilisk lurking in the pipes of the school - they somehow all manage to only opserve it trough reflections meaning that they turn to stone instead of dying. In the later books characters are killed in the most brutal ways without hesitation.

![](/images/Temporal/Licks.png)

This development is reflected in above figure how the books matures over time.




