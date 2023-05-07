---
title: Data Analysis
prev: "/"
next: temporal-analysis
---
# The Data
For this project we have based our data collection from the Harry Potter books. We have also used the full character list along with each character's associated aliases from [the Harry Potter fandom wiki](https://harrypotter.fandom.com/wiki/Category:Individuals). From this we have created an expanding network that adds characters as nodes and character co-occurences as edges between characters. This way we have analysed both the expanding cumulative network, as well as dived into specific chapters to further investigate.

Along the network we have also constructed dynamic text for each character, so that every time a character is mentioned, we extract the text from both the current sentence, but also from adjacent sentences.

<hr class="border-b-2 border-gray-400 mt-8 mx-4">

# Data Properties
When looking at some of the properties of the data:
![](/images/Network%20Properties%20per%20book.png)

We see that the number of nodes and edges increase for each book, as more characters are introduced. We also see that the density increases for each book, as the number of edges increase faster than the number of nodes. It is rather interesting to see that the nodes and edges grow by after the same trend, but just at different orders of magnitude. Finally, we see that the network centralization decreases for each book, as the networks become more decentralized. This is due to the fact that the number of edges increase faster than the number of nodes, which means that the networks become more dense, and therefore more decentralized.

From a network perspective, this means that the networks become more complex and decentralized as the books progress, which is in line with the narrative of the books, as the story as the books introduce more side characters and subplots.

For the dynamic text analysis, we can get some quick statistics on the number of words in each character's dynamic text. The below figure shows the evolution of the number of words in each character's dynamic text for each book.
![](/images/text%20properties%20per%20book.png)

From the sentence and word counts over time for specific characters, we notice that the number of words and sentences variate heavily from chapter to chapter between characters. Some characters (i.e. Harry Potter) are clearly are more prominent in the story, than others. It is also clear that some characters are very "seasonal". For instance, Dudley Dursley seems to have more words and sentences ascribed to him at the beginning of each book, when Harry is typically in the muggle world.


<hr class="border-b-2 border-gray-400 mt-8 mx-8">


# Limitations of the data

When it comes to cleaning the book texts, we broke them down to the individual sentence level. This is a very narrow scope, which means that we are able to capture the context of a character occurance, but it also means that we are not able to capture the context of a character occurance on a larger scale, such as a paragraph or a page. Additionally, we leave the text as is, without checking for any spelling errors or dialect differences.

Our detection of characters based on their names and associated aliases e.g also mean that we cannot detect when characters are using disguises such as polyjuice potions to appear as other characters. As well as this multiple characters have the same first names which makes it infeasible to distinguish which character is currently appearing in the sentence. This also include obscure characters such as `wizard who claimed to be a dragon killer`, whose first name in our libriary is `wizard` which means that every instance of the word wizard will add to the wrong node.

However, even though there are some flaws, our dataset has proven to be quite stable and gives a good representation of the books and character connections as a whole.
