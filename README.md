Initial commit to create the main branch.
# Collaborative Filtering - User Similarity Recommender

This Colab notebook demonstrates a **basic user-based collaborative filtering system** using **Pearson correlation** to calculate user similarities.

## What it does

- Builds a simple user-item ratings matrix.
- Computes pairwise similarity between users using Pearson correlation.
- Recommends items that similar users liked but the target user hasn't rated yet.

## Use cases

✅ Classic example: Movie or product recommendation (like early Netflix/Amazon).  
✅ Good for learning how collaborative filtering works from scratch.

## Relevance to trading

This specific example is not directly for trading, but the **similarity technique** could inspire ideas like:
- Finding similar tickers based on historical option flow patterns.
- Identifying market regimes with similar conditions.
- Building cluster-based signals.

## How to run

1. Open the notebook in Google Colab.
2. Run all cells to see the similarity matrix and recommended items.
3. Try adding more users or items to test how recommendations change.

---

**Author:** *Your Name*
