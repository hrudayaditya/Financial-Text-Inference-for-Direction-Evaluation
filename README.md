# Financial News Sentiment Project (FinBERT, DeBERTa, Baselines, StockNet)

This repo contains code and notebooks for a financial NLP project focused on **entity-aware sentiment classification** on financial news headlines, along with **baselines**, **FinBERT**, **DeBERTa-v3**, **StockNet utilities**, and **error analysis**.

The code is designed to run on **Google Colab** with minimal dependencies.

---

## Project Overview

### Tasks
1. **Entity-aware sentiment classification (primary task)**
   - Input: news headline/title
   - Output: sentiment label in `{negative, neutral, positive}`
   - Models: TF-IDF baselines, FinBERT, DeBERTa

2. **StockNet movement / regime pipeline (exploratory)**
   - Text + price alignment utilities
   - Builds datasets from StockNet tweets and raw prices

3. **Error analysis**
   - Exports up to **100 misclassified examples** for manual annotation
   - Includes automatic heuristics (negation, numbers, tickers, etc.)


---


## Quickstart (Google Colab)

### 1) Open a notebook in Colab
Upload the notebook file (or open from GitHub).

### 2) Install dependencies
