---
title: The Muggle World vs the Wizarding World
prev: temporal analysis
next: da
---

A large part of the Harry Potter story takes place in the Wizarding World. This world has all sorts of amazing creatures and people. However, the Wizarding World is special due to the fact that it is set to take place parallel to our own world. Therefore it is of interest to see how Harry connects with people before the Wizarding World has been established in the books, in contrast to after it has been introduced. Therefore we have looked at chapter 1-4 in Harry Potter and the Philosophers Stone, as well as the collective network of the first 17 chapters of the first book.

Beneath you can see a visualization of the graphs:
<iframe
  src="/images/MugglesvWizards/Network.html"
  style="width:100%; height:700px;"
></iframe>

Here it is evident that not only is the second network way larger, but there are also more communities surrounding Harry. The Dursley community that is domimant in the first network looks tiny compared to the network of wizards in the second. The vast amount of characters and interconnectons help build this world up from a readers point of view.

Looking a bit more into these two networks, we have compared the communities of the two networks

|Distribution of size of communities|
:-----------------------------------:
|![](/images/MugglesvWizards/community_distribution.png)|
|Matrix that shows community change|
|![](/images/MugglesvWizards/community_change_matrix.png)|

From the community change matrix we get three key observations: First of all community 1 does not change after the first 4 chapters up until chapter 17, which is probably due to community 1 consisting of characters such as Arabella Figg, Mr Paws, Snowy, Tufty, and Gordon, which are all relatively unknown characters in the Harry Potter universe that are probably not mentioned from the rest of the chapters. 

Secondly, the characters from network 0 in chapter 1-4 go from being in a single community to being spread across 5 different communities, this makes sense since the characters include Albus Dumbledore, Minerva McGonagall, Rubeus Hagrid, Lily Potter, and James Potter, which are all magical people. In the first 4 chapters the magical world is very one dimensional, but as the magical world is revealed these characters are split into many sub-communities of the Wizarding World, which explains the scattering.

Thirdly, community 2 is quite untouched by the chapters, except for a few characters. This is because the network includes the Dursleys along with Harry Potter, since he spends his time in the beginning with these characters. However as the Wizarding World is introduced, the connection between the other wizard characters becomes stronger and thus he swaps community.

(HER KAN VI INKLUDERE DET VIGTIGSTE ORD FRA HVER COMMUNITY)


Looking at the degree distributions...
|Distribution of degree of communities|
:-----------------------------------:
|![](/images/MugglesvWizards/Degree%20distribution.png)|
|Matrix that shows the degree assortativity between characters.|
|![](/images/MugglesvWizards/degree%20assortativity%20matrix.png)|


Finally we can look at the modularity...
![](/images/MugglesvWizards/modularity%20graphs.png)

