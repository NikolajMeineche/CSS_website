---
title: Dumbledore's Army
prev: mvw
next: sa
---

An interesting moment in the Harry Potter books is the formation of Dumbedore's Army, witch is event intuitively shouldh from a character perspective forms a lot of bonds between characters that weren't closely connected before. This means that a large amount of edges should be made, after the formation of the army. As well as this, some of the students also team up with professors and janitors in the form of the Inquisitorial Squad. When regarding chapters 1-17 and 18-38 in book 5 of the series, we get the following before and after pictures of the network, in regards to the formation of Dumbledore's Army:

<iframe
  src="/images/DumbleArmy/Networks.html"
  style="width:100%; height:750px;"
></iframe>

Here it is apparent that while there may not be way more communities in the latter network, it does seem like the characters in the first network are generally connected across groups, while everything seems to be directly connected to the main characters in the second network. This shows that after the formation of the army, the story starts to revolve around the group and their collected actions.



|![](/images/DumbleArmy/CommunitryDist.png)|
:-----------------------------------:
|![](/images/DumbleArmy/CommunityChange.png)|

### Book 5 Chapters 1-17
| Community 0                   | Community 1                   | Community 2                            | Community 3                   | Community 4                   |
|-------------------------------|-------------------------------|----------------------------------------|-------------------------------|-------------------------------|
| Harry Potter                  | Lord Voldemort               | Sirius Black                           | Fred Weasley                  | Draco Malfoy                  |
| Ron Weasley                   | Dudley Dursley               | Remus Lupin                            | George Weasley                | Gregory Goyle                 |
| Hermione Granger              | Vernon Dursley               | Wizard   | Ginny Weasley                 | Pansy Parkinson               |
| Albus Dumbledore              | Three Muggle boys            | Molly Weasley                          | Neville Longbottom            | Lucius Malfoy                 |
| Dolores Umbridge              | Petunia Dursley              | Arthur Weasley                         | Cho Chang                     | Vincent Crabbe                |

### Book 5 Chapters 18-38
| Community 0            | Community 1        | Community 2           | Community 3          | Community 4          |
|------------------------|--------------------|-----------------------|----------------------|----------------------|
| Harry Potter           | Sirius Black       | Neville Longbottom    | Dudley Dursley       | George Weasley       |
| Ron Weasley            | Remus Lupin        | Ginny Weasley         | Vernon Dursley       | Fred Weasley         |
| Hermione Granger       | Molly Weasley      | Draco Malfoy          | Petunia Dursley      | Ali Bashir           |
| Albus Dumbledore       | Dai Llewellyn      | Lord Voldemort       | Arabella Figg        | Angelina Johnson     |
| Dolores Umbridge       | Black Lake         | Luna Lovegood         | Dementors            | Alicia Spinnet       |


From the community distributions we see that characters are generally split into smaller communities in the later chapters, which strengthens the idea that more of the story line becomes more focused on the main group in the later chapters. It can also be seen that most of the communities have their characters scattered in new communities, which emphasizes the fact that this is a moment where many new connections are formed.

One noteworthy change in communities would be community 2, where Harry Potter, Ron Weasley, Hermione Granger, Albus Dumbledore, and Dolores Umbridge are the most central characters in the early chapters. However, this changes in the later chapters where Harry, Ron and Hermione, are grouped closer with other Hogwarts students rather than the schools teachers. This reflects that the formation of the army results in the student acting more on their own, without the involvement of adult supervision. 

It can also be seen from the community matrix that a rather large part of the characters from the first chapters are not mentioned in the final chapters and vice versa. This emphasizes that many characters appear either in the beginning or the end of the book, which can be interpreted as a significant turning point in the series.

(HER KAN VI INKLUDERE DET VIGTIGSTE ORD FRA HVER COMMUNITY)
<hr class="border-b-2 border-gray-400 mt-8 mx-4">

Regarding the degree distributions below it can be observed that the later chapters have a few more very high degree nodes that indicate that some nodes play a more central part of the later chapters, which matches well with what we previously observed. It can also be observed that the network of the later chapters seem to follow a more heavy tailed distribution which further emphasizes the previous observation.

(AFSNIT OM DEGREE ASSORTATIVITY MAtrix)

|![](/images/DumbleArmy/DegreeDist.png)|
:-----------------------------------:
|![](/images/DumbleArmy/DegreeAssort.png)|
<hr class="border-b-2 border-gray-400 mt-8 mx-4">

In the following plots it is evident that compared to a random network, the modularity increases significantly in the later chapters even though the total modularity drops a bit. This aligns very well with the previous analyses of the network, that suggest that the army strengthens the importance of the central group of characters.
![](/images/DumbleArmy/ModularityTest.png)

<hr class="border-b-2 border-gray-400 mt-30 mx0">

In conclusion there seems to be a large change in character dynamics before and after the formation of Dumbledore's Army. This results in the story revolving around the army and the group of characters within it. It is also evident that many characters that appear before the formation of the army no longer appear after the formation, indicating that the formation is a pivitol moment in the book, that drives the main storyline to introduce new characters and interconnections between them.

![](/images/DumbleArmy/SentimentDA.png)
|![](/images/DumbleArmy/WordCloudBook517.png)|
:-----------------------------------:
|![](/images/DumbleArmy/WordCloudBook538.png)|

