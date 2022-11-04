# Everything I know about graph representation learning

I am leaning _very heavily_ on Hamilton's (Graph Representation Learning Book)(https://www.cs.mcgill.ca/~wlh/grl_book/) 
and the Stanford (CS224W Course: Machine Learning with Graphs)[https://web.stanford.edu/class/cs224w/]
## What is a graph?

A graph is a way to represent data. 
What is special or unique about a graph is that (in comparison to data that you'd normally see in an excel sheet, for example) it represents entities and the relationships between them. 
Graphs have nodes (things) and edges (relationships)

An intuitive example of this is a family tree - you have people, and their relationships to other people:
- A is a father of B 
- B is a sibling of C, D
- etc. 

Mathematically this is represented as:

$$ G = (V,E) 

I like food and I feel it is a relatable concept (who doesn't eat?!) so the remainder of this post will refer to ingredients and the relationships that exist between them.
Here is a graph of 
