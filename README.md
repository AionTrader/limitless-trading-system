<p align="center">
  <img src="assets/logo.png" alt="Limitless Logo" width="200"/>
</p>
# Project Limitless — Human-AI Trading System (HITL-first)

**Limitless** is a Human-in-the-Loop (HITL) trading assistant that merges market data, news sentiment, and behavioral analysis to enhance trader precision and speed.  
It doesn’t replace the trader — it *amplifies* them.

---

## Vision

Create an intelligent, interpretable trading co-pilot that learns from human intuition while leveraging machine efficiency.

Limitless integrates:
- **Market data**: price, volume, volatility metrics.
- **Sentiment analysis**: from news and social networks.
- **Human decision feedback**: the trader approves or modifies signals before execution.

Goal: **turn trading into a collaborative intelligence** — man and machine working as one.

---

## System Overview

| Stage | Description |
|--------|--------------|
| **Data ingestion** | Gathers market, news, and sentiment data from public APIs. |
| **Signal generation** | Machine learning models estimate market direction probabilities. |
| **HITL loop** | User reviews predictions in an interactive dashboard before execution. |
| **Paper trading** | Simulated execution with real-time feedback and risk tracking. |
| **Learning feedback** | The system improves by analyzing user decisions and outcomes. |

---

## Current Phase: 0 — Setup

Repo initialized  
Next step: Data ingestion pipeline (historical + real-time)  
Goal: build dataset foundation for ML models

---

## Tech Stack

- **Python 3.10+**
- **Pandas / NumPy** — data wrangling
- **scikit-learn / PyTorch / TensorFlow** — ML models
- **Streamlit / Dash** — visualization
- **PostgreSQL / Parquet** — storage
- **APIs:** yfinance, AlphaVantage, Finnhub, NewsAPI, Reddit/Twitter read-only

---

## Setup (Developer Instructions)

```bash
# Create environment
conda create -n limitless python=3.10 -y
conda activate limitless

# Install dependencies
pip install -r requirements.txt
