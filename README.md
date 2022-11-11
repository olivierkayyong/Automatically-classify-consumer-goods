# Automatically classify consumer goods
You are a Data Scientist within the company "Place de marché", which wishes to launch an e-commerce marketplace.

<img src="img.png">

On "Place de Marché", sellers offer items to buyers by posting a photo and a description.

Currently, assigning an item's category is done manually by sellers, and is therefore unreliable. 
In addition, the volume of items is currently very small.

To make the user experience for sellers (facilitate the posting of new items) and buyers (facilitate the search for products) as smooth as possible, 
and with a view to scaling up, it becomes necessary to automate this task.

Linda, Lead Data Scientist, therefore asks you to study the feasibility of an engine for classifying articles into different categories, 
with a sufficient level of precision.

## Your mission
Could you demonstrate, through this modeling approach, the feasibility of automatically grouping products of the same category?

Here are the constraints:

In order to extract the text features, it will be necessary to implement:
two “bag-of-words” type approaches, simple word counting and Tf-idf;
a classic word/sentence embedding type approach with Word2Vec (or Glove or FastText);
a word/sentence embedding approach with BERT;
a word/sentence embedding approach with USE (Universal Sentence Encoder).
