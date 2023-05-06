---
title: The Project
layout: single
next: data-analysis
---

It should be no secret that all three of us consider ourselves huge "Potterheads". We have all read and loved the books multiple times. Thus for us, the reasoning behind starting this project was quite simple: We wanted to work with something we were passionate about and had some degree of expert knowledge in. Choosing this dataset, enabled us to work with more advanced network and text analysis techniques, such as temporal analysis of networks and wordclouds and sentiment analysis. By choosing this dataset we have proposed the following research questions:
- [How do the Harry Potter books change over time?](#how-do-the-books-change-over-time)
- [How do the characters, their interactions / relationships, and language surrounding them change throuhout key moments in the Harry Potter books?](#how-do-the-characters-their-interactions--relationships-and-language-surrounding-them-change-throughout-key-moments-in-the-harry-potter-books)

![test](/images/HarryvVolde.png)

# HOW DO THE BOOKS CHANGE OVER TIME?

 The Harry Potter books where written by J.K. Rowling and initially published between 26th June 1997 – 21st July 2007. The first book (Harry Potter and the Philosopher's Stone) was originally marketed as a kids-book, but as the next 6 books were published in a span of 10 years, the primary audience of the books grew up. We thus wanted to understand if the topics discussed in the books over time became more complex and more adult. This question is answered by 1) looking at the temporal analysis of the character graphs, to understand if the number of key characters and the number of interactions change over time to address a more mature reader with better memory, and 2) looking at the full book texts through wordclouds and Flesch's Reading Ease score over time to understand if the language and themes discuss become more adult and complex. Read more about the answers [here](/temporal-analysis).



# HOW DO THE CHARACTERS, THEIR INTERACTIONS / RELATIONSHIPS, AND LANGUAGE SURROUNDING THEM CHANGE THROUGHOUT KEY MOMENTS IN THE HARRY POTTER BOOKS?

It is no secret that what makes a book or series of book exciting to read are its shocking and exciting key moments, where big changes in character arcs happen. We thus wanted to understand how the characters, their interactions and the language surrounding them changed throughout some identified key moments in the Harry Potter books. This question is answered by 1) looking at the temporal analysis of the character graphs, to understand how how key moments have an effect on sub-communities (i.e. changes in alliance), and 2) looking at the book texts that surrounds a character at a specific time through wordclouds and sentiment analysis to understand if they are portrayed in a different light as there character arch developments are uncovered. The pre-defined key moments we will explore in this work are:
- [The Muggle world vs. the Wizarding world](/mvw): A magical (pun intended) contrast in the first book is the distinction between the first 3 chapters of book one and the remaining part of the first book. The first 3 chapters are set in the Muggle world, where Harry is treated as an outcast and is bullied by his cousin Dudley. The remaining part of the book is set in the Wizarding world, where Harry is treated as a hero and is loved by everyone. We would thus expect to see a clear distinction in the character graphs (if nothing else, simply because of the sheer amount of new characters introduced in the wizarding world) and the sentiment of the books shifting to being more positive.
- [The establishment of Dumbledore's Army](/da): In the fifth book, Harry, Ron, Hermione and other Hogwards pupils establish Dumbledore's Army, a secret organisation that teaches students defensive spells to protect themselves against the dark arts as an answer to the reign of terror under the new headmistress Dolores Umbridge. We would thus expect to see a clear distinction in the character graphs, where the members of Dumbledore's Army are more closely connected to each other, and the sentiment of the books shifting to being more hopeful.
- [Snape's True allegiance](/sa): In the ending of book 6, Severus Snape goes on to kill Albus Dumbledore. This is a huge shock to the reader, as Snape has been portrayed as a good guy (if not suspicious) throughout the entire series. However in book 7, it is later revealed that Snape was in fact a double agent, and was working for Dumbledore all along. We would thus expect to see a clear distinction in the character graphs, where Snape is more closely connected to the Death Eaters after killing Dumbledore and then is linked heavily to especially Dumbledore and Lily Potter after his true alliance is revealed. From a text perspective, we would expect to see Snape's portrayal going from neutral, to negative, to positive (if not still somewhat negative, but with a sad tone).

In summary, our main goal for the end user's experience was to provide a tool that could help them explore the Harry Potter books in a new and way. We wanted to create new-found excitement in the user's mind about this pheominal books series, and give some reasoning behind what makes them so good, namely its dynamically changing and expanding world of characters, their motives and relationships.

The data can be downloaded in our Google Drive and the explainer notebook and GitHub is also available below.


<iframe
  src="Networks.html"
  style="width:100%; height:1200px;"
></iframe>

Test 