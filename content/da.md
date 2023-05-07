---
title: Dumbledore's Army
prev: mvw
next: sa
---

An interesting moment in the Harry Potter books is the formation of Dumbedore's Army, which is an event that intuitively should, from a character perspective, form a lot of bonds between characters that weren't as closely connected before. This means that a large amount of edges should be made, after the formation of the army. As well as this, some of the students also team up with professors and janitors in the form of the Inquisitorial Squad. When regarding chapters 1-17 and 18-38 in book 5 of the series, we get the following before and after pictures of the network, in regards to the formation of Dumbledore's Army:

<iframe
  src="/images/DumbleArmy/Networks.html"
  style="width:100%; height:750px;"
></iframe>

Here it is apparent that while there may not be way more communities in the latter network, it does seem like the characters in the first network are generally connected across groups, while everything seems to be directly connected to the main characters in the second network. This shows that after the formation of the army, the story starts to revolve around the group and their collected actions.



|![](/images/DumbleArmy/CommunitryDist.png)|
:-----------------------------------:
|![](/images/DumbleArmy/CommunityChange.png)|


### Book 5 Chapters 1-17
| Community 0            | Community 1        | Community 2           | Community 3          | Community 4          |
|------------------------|--------------------|-----------------------|----------------------|----------------------|
| Harry Potter           | Sirius Black       | Neville Longbottom    | Dudley Dursley       | George Weasley       |
| Ron Weasley            | Remus Lupin        | Ginny Weasley         | Vernon Dursley       | Fred Weasley         |
| Hermione Granger       | Molly Weasley      | Draco Malfoy          | Petunia Dursley      | Ali Bashir           |
| Albus Dumbledore       | Dai Llewellyn      | Lord Voldemort        | Arabella Figg        | Angelina Johnson     |
| Dolores Umbridge       | Black Lake         | Luna Lovegood         | Dementors            | Alicia Spinnet       |

### Book 5 Chapters 18-38
| Community 0                   | Community 1                   | Community 2                            | Community 3                   | Community 4                   |
|-------------------------------|-------------------------------|----------------------------------------|-------------------------------|-------------------------------|
| Harry Potter                  | Dolores Umbride               | Sirius Black                           | Fred Weasley                  | Draco Malfoy                  |
| Ron Weasley                   | Albus Dumbledore              | Remus Lupin                            | George Weasley                | Gregory Goyle                 |
| Hermione Granger              | Minerva McGonnegal            | Severus Snape                          | Alicia Spinnet                | Bellatrix Lestrange               |
| Ginni Weasley                 | Madam Malking                 | Kreacher                               | Ali Bashir                    | Lord Voldemort                 |
| Neville Longbottom           | Poppy Pomfrey                  | Arthur Weasley                         | Mungo Runham                  | Vincent Crabbe                |



From the community distributions we see that characters are generally split into smaller communities in the later chapters, which strengthens the idea that more of the story line becomes more focused on the main group in the later chapters. It can also be seen that most of the communities have their characters scattered in new communities, which emphasizes the fact that this is a moment where many new connections are formed.

One noteworthy change in communities would be community 0, where Harry Potter, Ron Weasley, Hermione Granger, Albus Dumbledore, and Dolores Umbridge are the most central characters in the early chapters. However, this changes in the later chapters where Harry, Ron and Hermione, are grouped closer with other Hogwarts students rather than the schools teachers. This reflects that the formation of the army results in the student acting more on their own, without the involvement of adult supervision.

In the the community from chapter 1-17, community 2 the most significant nodes are students at hogwarts (with the exeption of Lord Voldemort). In the later chapters it can be seen have Draco Malfoy is established in a new community with his slytherin gang (Crabbe, Goyle), Lord Voldemort and Bellatrix. This signifies his shifting alliance to Umbridge through the 'Inquisitorial Squad'. It can also be seen that the community of Harry Potter and his friends are more closely connected in the later chapters, which is a result of the formation of Dumbledore's Army.

It can also be seen from the community matrix that a rather large part of the characters from the first chapters are not mentioned in the final chapters and vice versa. This emphasizes that many characters appear either in the beginning or the end of the book, which can be interpreted as a significant turning point in the series.

Generally, book 5 signifies a shift in the entire book series, as it lays the ground work for later character motives and developments. This is also the book where the main character Harry Potter starts to become more aware of the political situation in the wizarding world, which is a theme that is further explored in the later books.

<hr class="border-b-2 border-gray-400 mt-8 mx-4">

Regarding the degree distributions below it can be observed that the later chapters have a few more very high degree nodes that indicate that some nodes play a more central part of the later chapters, which matches well with what we previously observed. It can also be observed that the network of the later chapters seem to follow a more heavy tailed distribution which further emphasizes the previous observation.

|![](/images/DumbleArmy/DegreeDist.png)|
:-----------------------------------:
|![](/images/DumbleArmy/DegreeAssort.png)|

Looking at the degree assortativity matrix we can also see that in both networks, there seems to be a tendency for higher values away from the diagonal of the matrix(except for a few cases, which are more prevalent in chapters 1-17). Looking at the degree assortativity matrix for chapters 18-38 is becomes very clear that the history origines from the main characters (High Degree nodes) wich connect to all the smaller side characters


<hr class="border-b-2 border-gray-400 mt-8 mx-4">

In the following plots it is evident that compared to a random network, the modularity increases significantly in the later chapters even though the total modularity drops a bit. This aligns very well with the previous analyses of the network, that suggest that the army strengthens the importance of the central group of characters.
![](/images/DumbleArmy/ModularityTest.png)


In conclusion there seems to be a large change in character dynamics before and after the formation of Dumbledore's Army. This results in the story revolving around the army and the group of characters within it. It is also evident that many characters that appear before the formation of the army no longer appear after the formation, indicating that the formation is a pivitol moment in the book, that drives the main storyline to introduce new characters and interconnections between them.

<hr class="border-b-2 border-gray-400 mt-30 mx0">

The shift towards more adult political themes being discussed is also clear from analysis of the character texts.

From the sentiment analysis over the discussed period, we notice that the character sentiment for all characters is more negative in the the other two moments. A big reason for the formation of Dumbledore's Army comes from the fact that the students bond together as a response to Dolores Umbridge taking on the position as headmistress from Dumbledore. 

The dislike of Umbridge is very clear throughout the character sentiment, as the character sees sginificant negative spikes throughout the middle part of the book start to understand that they do not are not happy with the new teacher Dolores Umbridge, which is also reflected in the sentiment analysis.


![](/images/DumbleArmy/SentimentDA.png)


It can be seen how Neville's sentiment mainly appear negative throughout the later chapters which may be a results of his skills during training in Dumbledore's Army. Neville is often portrayed as a clumsy and insecure character, which is also reflected in the sentiment analysis.

For Harry Potter it can be seen how in the beginning of chapter 17-38, his sentiment is positive rigth after establishing Dumbledore's Army, but then continues to decrease for the remainder of the history. This reflects well how the book becomes more and more dark with his visions of Lord Voldemort and Arthur Weasley being attacked by Nagini in his dreams. The continously negative sentiment of Harry Potter also reflects how the ministry of Magic continues to discredit him and Dumbledore throughout the book and calling them liars for claiming that Lord Voldemort has returned.

|![](/images/DumbleArmy/WordCloudBook517.png)|
:-----------------------------------:
|![](/images/DumbleArmy/WordCloudBook538.png)|

The word clouds further signifies the previously mentioned shift in the story line, as the word cloud from the later chapters contains more words that are related to the political/adult themes of the book such as the word "career" in Ginny's word cloud. Additionally, Harry's constant wondering about why Dumbledore is not talking to him is also reflected in the word cloud, as the word "Professor" is the most frequent word in his word cloud.