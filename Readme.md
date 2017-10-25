NLPG Project
============

# About
The [code is poetry labs](https://cip-labs.net) are working on a broad range of assets, tools and databases for Natural Language Processing for German language. Here you can find training data and other interesting documents.


# Data

## Answer Representation

In Question Answering systems you often need to determine what the question is about. The answer representation gives you a broad knowledge about how the answer should be displayed. In this data set we defined 3 types:
* LIST
* FACT
* PARAGRAPH

A trained classifier should by able to find out the correct response type the question needs.


## Answer Type Detection

Question Answering systems need to know what is required as response. Li and Roth [1] established a widely known taxonmy on answer types in 2006. The data set in this repository is also labeled as Li and Roth suggested it. Since the taxonomy has two layers (top and sub classes) we first describe the top classes with its sub classes (numbers in brackets) here:

* Abbreviation (2)
* Description (4)
* Entity (22)
* Human (4)
* Location (5)
* Numeric (13)

Get more information about this data set from the readme in /answer-type-detection-liroth.

# References

[1] Li, Xin, and Dan Roth. “Learning question classifiers: the role of semantic information.” Natural Language Engineering 12.03 (2006): 229-249.

# More

Click here for more research stuff from [Alexander Bresk](http://alexander.bre.sk/research).
