# Trader Performance vs Market Sentiment (Fear/Greed) — Hyperliquid

This project analyzes how Bitcoin market sentiment (Fear vs Greed) relates to trader behavior and performance on Hyperliquid.

## Repo Contents
- `src/analysis.py` : end-to-end pipeline (load → clean → merge → metrics → charts → insights tables)
- `outputs/` : generated charts/tables used in the analysis
- `requirements.txt` : dependencies

## Setup
```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
source .venv/bin/activate

pip install -r requirements.txt
