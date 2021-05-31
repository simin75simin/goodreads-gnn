# goodreads-gnn
use graph neural networks (GNNs) to do various interesting machine learning on goodreads.com

# current goal
- learn more about gnn
- build the graph by writing crawlers

# Graphs
---
## the reader graph
- unique username as nodes
- directed edge (u,v) if u follows v

## the author graph
- unique author names as nodes
- edge undecided

## the book graph
- book as nodes
- edge constructed via a relatedness index, consisting of but not limited to: tfidf scores between 'read' users' ratings, author 'distance' on author graph

# Traditional analysis
---
- though this repo's main goal is to use GNN to do nontrivial, useful analysis on goodreads.com, traditional analysis like connectedness, pagerank are still useful and would probably be included.

# GNN
---
## prediction
- book score
- user's review on book (leading to a recommendation system)

# Motivation for the project - why this project?
- i think GNNs are somewhat like CNNs, it will revolutionize machine learning in more than one major way. so better do more things with it. it's been around for a couple of years already.
