# How-Word-Networks-Change-with-Age
This project explores how semantic word networks evolve across the human lifespan—from early childhood to old age—using graph-based models to simulate lexical retrieval and analyze cognitive aging in language


# 🧠 How Word Networks Change with Age

This project explores how semantic word networks evolve across the human lifespan—from early childhood to old age—and how these structural changes impact lexical retrieval. Using graph-based models built from age-specific word association data, the project simulates lexical access to investigate cognitive aging and language development.

## 📌 Overview

Language is a reflection of how knowledge is stored and retrieved in the brain. While vocabulary size tends to increase with age, memory retrieval becomes more difficult. This project models and compares semantic networks across different age groups to better understand how **network connectivity** influences **retrieval efficiency**.

## 🚀 Project Objectives

- Build graph-based semantic networks for multiple age groups  
- Simulate lexical access using graph traversal algorithms  
- Compare metrics like edge density, clustering coefficient, and average path length  
- Test the hypothesis: *Connectivity, not vocabulary size, determines retrieval efficiency*


## 📂 Project Structure
word-networks-aging/
├── data/               # Age-specific word association datasets
├── notebooks/          # Jupyter notebooks for building graphs and analysis
├── src/                # Python scripts for modeling and metrics
├── results/            # Visualizations and output graphs
└── README.md           # This file


## 🔬 Methodology

- **Graph Construction**: Nodes represent words, edges represent associative strength  
- **Age Groups**: Children (<3), Teenagers, Adults, Older Adults  
- **Graph Algorithms**: BFS/DFS and spreading activation to simulate retrieval  
- **Metrics Evaluated**:
  - Edge Density
  - Clustering Coefficient
  - Average Retrieval Path Length

## 🧪 Results Summary

- **Children**: Sparse networks with long retrieval paths  
- **Teenagers**: Dense and highly clustered networks → faster retrieval  
- **Older Adults**: Despite larger vocabularies, weaker connectivity → slower access

These findings align with prior cognitive linguistics research (e.g., Wulff, 2016) suggesting that **network structure**, not just word count, is crucial for lexical access.

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/word-networks-aging.git
   cd word-networks-aging



   
