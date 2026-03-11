# MA_SA_Kempgens

## Sentiment Analysis of Online Customer Reviews – Sustainable vs. Conventional Sportswear (Nike & adidas)

This repository contains all code and data for my Master's thesis. I collected online reviews from the Nike and adidas websites and used sentiment analysis (SiEBERT and VADER) to compare how customers evaluate sustainable and conventional sneakers.

## Structure

- `Code/` – All Python scripts (scraping, sentiment analysis, statistics, figures)
- `Data/` – Raw and processed review datasets

## Overview

- **Dataset**: 16,243 reviews collected from nike.com and adidas.com (8,298 after filtering incentivized reviews)
- **Methods**: SiEBERT (Hartmann et al., 2023) and VADER (Hutto & Gilbert, 2014)


## How to run

Requires Python 3.x with `transformers`, `vaderSentiment`, `pandas`, `scipy`, `matplotlib`.

## Citation

Kempgens, R. (2026). Sentiment Analysis of Online Customer Reviews: Comparing Sustainable and Conventional Sportswear Products from Nike and adidas. Master's Thesis.
