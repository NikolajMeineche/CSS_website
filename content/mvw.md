---
title: The Muggle World vs the Wizarding World
prev: temporal analysis
next: da
---

A large part of the Harry Potter story takes place in the Wizarding World. This world has all sorts of amazing creatures and people. However, the Wizarding World is special due to the fact that it is set to take place parallel to our own world. Therefore it is of interest to see how Harry connects with people before the Wizarding World has been established in the books, in contrast to after it has been introduced. Comparing the accumulative networks before and after the Wizarding World has been introduced, we can see how the network of characters change.

Beneath you can see a visualization of the graphs:
<iframe
  src="/images/MVW/Networks.html"
  style="width:100%; height:750px;"
></iframe>

Here it is evident that not only is the second network way larger, but there are also more communities surrounding Harry. The Dursley community that is domimant in the first network looks tiny compared to the network of wizards in the second. The vast amount of characters and interconnectons help build this world up from a readers point of view.

Looking a bit more into these two networks, we have compared the communities of the two networks

|![](/images/MVW/CommunityDistribution.png)|
:-----------------------------------:
|![](/images/MVW/CommunityMatrix.png)|

### Book 1 Chapters 1-4
| Commnuity 1 | Community 2 | Community 3 |
|:-----------:|:------------:|:------------:|
| Rubeus Hagrid| Muggle Boys | Harry Potter |
| Albus Dumbledore  | Stan Shunspike | Dudley Dursley |
| Gringotts Head Goblin  | Phyllidia Spore | Vernon Durslet |
| Lord Voldemort | Pomona Sprout | Petunia Dursley |
| Wizard | Bathilda Bagshot | Arabella Figg|


### Book 1 All Chapters
| Community 0         | Community 1                   | Community 2                 | Community 3 | Community 4     | Community 5               |
|--------------------|-------------------------------|-----------------------------|--------------|-----------------|---------------------------|
| Harry Potter       | George Weasley                | Three Muggle boys           | Percy Weasley | Dudley Dursley  | Charlie Weasley           |
| Ron Weasley        | Madam Malkin                  | Magical Menagerie| Dean Thomas  | Vernon Dursley  | Lord Voldemort            |
| Hermione Granger   | Fred Weasley                  | Stan Shunpike               | Cho Chang    | Petunia Dursley | Gringotts Head Goblin      |
| Rubeus Hagrid      | Oliver Wood                   | Pomona Sprout               | Black Lake   | Hedwig          | Bill Weasley              |
| Albus Dumbledore   | Wizard | Emeric Switch   | Sorting Hat  | Fat Friar       | Dai Llewellyn             |


From the community change matrix we get three key observations: First of all community 1 does not change after the first 4 chapters up until chapter 17 (Becomes Community 2), which is probably due to community 1 consisting of characters such as Arabella Figg, Mr Paws, Snowy, Tufty, and Gordon, which are all relatively unknown characters in the Harry Potter universe that are probably not mentioned from the rest of the chapters. 

Secondly, the characters from network 0 in chapter 1-4 go from being in a single community to being spread across 5 different communities, this makes sense since the characters include Albus Dumbledore, Minerva McGonagall, Rubeus Hagrid, Lily Potter, and James Potter, which are all magical people. In the first 4 chapters the magical world is very one dimensional, but as the magical world is revealed these characters are split into many sub-communities of the Wizarding World, which explains the scattering.

Thirdly, community 2 is quite untouched by the chapters, except for a few characters. This is because the network includes the Dursleys along with Harry Potter, since he spends his time in the beginning with these characters. However as the Wizarding World is introduced, the connection between the other wizard characters becomes stronger and thus he swaps community.



<hr class="border-b-2 border-gray-400 mt-8 mx-4">

Looking at the degree distributions below we see that there are a couple of central characters, namely Vernon Dursley and Harry Potter, that have high degrees compared to the rest of the characters in the first chapters. However when looking at chapters 1-17 we almost see a straight line in the log-log scale, indicating something close to a heavy tailed distribution, meaning that some of the characters, make up for the majority of edge connections. This is also without considering weighting of edges, which would probably skew the distribution even more. 

|![](/images/MVW/DegreeDist.png)|
:-----------------------------------:
|![](/images/MVW/DegreeAssort.png)|

Looking at the degree assortativity matrix we can also see that in both networks, there seems to be a tendency for higher values away from the diagonal of the matrix(except for a few cases, which are more prevalent in chapters 1-4). This intuitively means that characters with many connections tend to interact with characters without many connections. And vice versa if many values lie close to the diagonal, central characters will probably interact with other central characters allowing to grasp which characters that are more important to the story. By looking at the matrix we can see that the latter is only the case in few instances. It points towards the main characters, like Harry, tend to interact with many side characters in both the early and later chapters. This makes sense given the large amount of side characters, that only get few mentions throughout the book.

<hr class="border-b-2 border-gray-400 mt-8 mx-4">

Finally we can look at the modularity where we compare it with the average modularity of the same network but with swapped edges that should only alter the modulraity of the community if there is infact a significant pattern in the partitioning. Here it can be seen that both partitioning represent a significant pattern in the network, however the modularity of the network is higher in the first chapters than in the later chapters. This is probably due to the fact that the network's partitioning is more modular in the first chapters, since the characters are more separated into different groups.

![](/images/MVW/Modularity.png)

In conclusion, there seems to be a large change between the characters before and after the Wizarding World is introduced. This makes sense as a large part of the story and characters take place in here, and as more characters are introduced, the more intricate the network of characters will be.

<hr class="border-b-2 border-gray-400 mt-30 mx0">

Diving further into the characters in the communities in this moments, we can also examine the text that surrounds the most important characters. Looking into the sentiment and word clouds of some of the key characters which can be seen below:

![](/images/MVW/SentimentMVW.png)

Looking at the sentiment characters like Harry, Hagrid, and Dudley seem to be portrayed in the neutral sentiment range, while Dumbledore is mostly portrayed positively, and Quirrel is portrayed mostly negatively. The latter two make sense, as they are known for being good and evil respectively. There is however a visible increase in Harry's average sentiment score, after the fourth chapter, which indicates that the switch to the wizarding world is mostly a positive change for him. 

Looking into the word clouds for the characters before and after Harry entering the wizarding world we get the following:

|![](/images/MVW/WordCloud4.png)|
:-----------------------------------:
|![](/images/MVW/WordCloud17.png)|

In the worldcloud of the first four chapters we see how there for all four characters is a big focus the Durley familiy. This makes sense since the first four chapters are mostly about Harry's life with the Dursleys. However in the worldcloud of the last 17 chapters we see how the focus is more on the magical world and the characters that are introduced here.

Dursley apperance in the first four chapters is focused on food (sausages/juicy) along with the significant scene where provides him with a pig tail using his Umbrelle wand(present in both their wordclouds).

For Dumbledore and Harry potter we see how the Philisopher's stone becomes a key part of their indenitety in the final stage of book. Also Professor Quirrell is heavily influced by his obsesion to get the stone from the mirror. 