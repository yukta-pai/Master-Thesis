# Master-Thesis: AI-Driven Hedge Fund Portfolio Allocation

This thesis explores the use of artificial intelligence in **Fund of Hedge Funds** (FoHF) portfolio allocation. The goal is to **generate enhanced alpha** by leveraging machine learning for hedge fund return prediction, followed by portfolio optimization via reinforcement learning.

## Overview

- **Objective:** Predict hedge fund returns and construct a portfolio that maximizes risk-adjusted returns (Sharpe Ratio).
- **Dataset:** Historical performance and metadata of ~4,500 hedge funds.
- **Approach:**  
  - Benchmark multiple machine learning models for return prediction.
  - Identify the most effective model based on predictive accuracy and computational efficiency.
  - Use reinforcement learning for optimal portfolio allocation using predicted returns.

## Key Highlights

- **Machine Learning Models Compared:**
  - Linear Regression
  - Random Forest
  - Support Vector Regression
  - Neural Networks
  - Gradient Boosting Machines (GBM)

- **Model Selection Outcome:**
  - **Gradient Boosting** was shortlisted as the best trade-off between predictive performance and training time.

- **Portfolio Allocation:**
  - Reinforcement Learning agent trained to **maximize the Sharpe Ratio**.
  - Dynamic allocation strategy that selects from **4,500+ hedge funds**.

## Tech Stack

- Python 3.x
- NumPy, Pandas
- Scikit-learn, XGBoost
- TensorFlow / PyTorch (if applicable)
- OpenAI Gym / Custom RL Environment
- Matplotlib, Seaborn
