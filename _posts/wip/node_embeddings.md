---
title: Node Embeddings 
date: 21/03/2022
---

# What is a node embedding?


Node embedding is the act of taking nodes in a graph and representing them in a way that is easier for us to use.
It is a technique used in graph machine learning. 
It's necessary, as the current machine learning methods are designed for regular inputs, e.g. sliding windows for NLP and CV tasks.
Graphs, however, are not suited to these sliding window approaches, as there is no obvious start point or direction in which to slide a window. 
Because of this, it is beneficial to learn an embedding of a graph, upon which these traditional techniques can be applied. 

# How do we create an embedding?

Embedding a graph is a lossy technique, not all information in the graph will make it into the final embedding.
A successful embedding will therefore preserve useful information, while discarding less relevant details.
Therefore as the practitioner we must determine what information is useful, and doing so will guide us into designing a useful embedding. 

We are looking for a representation in the embedding space, that serves as a good match or proxy for the graph in it's original form.
More precisely, we want nodes that are similar in the graph, to be near each other in our embedding space. 

## How do we define similarity?

