---
layout: post
title: "Everything I know about graph representation learning"
date: 2022-11-25
permalink: /everything_i_know_grl
---

I am leaning _very heavily_ on Hamilton's (Graph Representation Learning Book)(https://www.cs.mcgill.ca/~wlh/grl_book/) 
and the Stanford (CS224W Course: Machine Learning with Graphs)[https://web.stanford.edu/class/cs224w/]

For a comprehensive overview - look to the above resources.
Below are essentially my notes and learnings derived from them, and so will have a very similar structure.

## What is a graph?

A graph is a way to represent data. 
What is special or unique about a graph is that (in comparison to data that you'd normally see in an excel sheet, for example) it represents entities and the relationships between them. 
Graphs have nodes (things) and edges (relationships)


An intuitive example of this is a family tree - you have people, and their relationships to other people:
- A is a parent of B 
- B is a sibling of C, D
- E is the partner of A

Mathematically this is represented as:

$$ G = (V,E) 

Where G is your entire graph, consisting of V (for nodes, also known as vertices) and E for edges.

I like food and I feel it is a relatable concept (who doesn't eat?!) so the remainder of this post will centre around an ingredient based dataset and the relationships that exist between them.

Here is a graph of 1000 random recipes. Each node (blue dot) is an individual ingredient and the connections between them indicate that they share a recipe together:

![random recipes](/everything_i_know_grl/random_1000_recipes_graph.png)

### So what can we do with machine learning on graphs so far?

#### Node classification

This area is concerned with predicting what features a node may have, given the structure of the rest of the graph

#### Node Clustering

This is concerned with grouping nodes with similar attributes

#### Edge Prediction

Given a node, which other nodes would it be connected to?

#### Graph Generation

Having learnt about a set of graphs, can we make a new one that looks similar?

#### Graph Classification

Like with node classification, can we label an entire graph?

### Graph Clustering

Can we cluster entire groups of graphs together?

## Some traditional techniques
