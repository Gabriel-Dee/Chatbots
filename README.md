# Chatbots

## A chat bot is a software app used to conduct an on-line chat conversation via text or text-to-speech, with a purpose of providing direct contact with a human being.
## Chat bot is basically AI in action.

## Types of chatbots.
* Simple chatbots - limited capabilities, rule based, task specific
* Smart chatbots - AI enabled
* Hybrid chatbots -  combo of simple and smart chatbots
* Social Messaging chatbots
* Menu based chatbots
* And so on

## Rule based vs Self learning chatbots.
## Rule based - has a set of rules that it follows to answer user queries.

## Self-learned - also called retriever chatbots, where they retrieve info that they have learned and answer the user. They use ML algorithm, can answer questions that even not specified by the programme, can answer unexpected questions.

## Steps involved in building Chatbot with Python and NLTK

1. Reading Text Corpus
2. PreProcessing(Stop words Removal, Lower case conversion etc)
3. Tokenization, Stemming & Lemmatization 
4. Bag of Words
5. One hot encoding

### Tokenisation - converting a sentence into individual words or tokens.
### Stemming - is a process of finding similarities between words with the same root words.
### Lemmatization -  refers to returning the base word.

### Generating Bag Of Words (BOW):- Process of converting words into numbers by generating vector embeddings from the tokens generated.

##           +------------------+
##           |  User message    |
##           +--------+---------+
##                    |   
##         +------------+-------------+
##         |                          |
## +-------v---------+        +---------v--------+
## |Intent           |        | Entity           |
## |Classification   |        |Resolution        |
## +-----------------+        +------------------+
## | Intents         |        | Entities         |
## +-----------------+        +------------------+
##         |                         |
##         +------------+------------+
##                      |
##              +-------v-------+
##              | AI Brain      |
##              +-------+-------+
##                      |
##              +-------v-------+
##              | Response      |
##              | Selection     |
##              +-------+-------+
##                      |
##              +-------v-------+
##              | Response with |
##              | Highest       |
##              | Similarity    |
##              +---------------+

