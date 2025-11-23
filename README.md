# Markov Chain Stock Movement Prediction

## Overview

A **Markov Model** is a probabilistic model that describes a system moving between different states over time, where the **next state depends only on the current state**, not on the full history.  
This “memoryless” property makes Markov Chains useful for modeling systems with sequential behavior — including stock price movement states.

In this project, a Markov Chain is used to **predict stock movement for APPLE (AAPL)** for:

- The **next day**
- The **next N days** (multi-step prediction)

The model is trained using historical daily price data, converts returns into states (up, down, neutral), builds a transition matrix, and predicts future movement using deterministic and stochastic methods.

---

## Code Overview

The following image shows the core code used to predict APPLE stock movement using a Markov Chain:

![Code Overview](/overview.png)

---

## Key Features

- Converts daily returns to movement states (up / down / neutral)
- Builds a transition probability matrix from historical data
- Predicts the next state stochastically
- Performs multi-step prediction (N-day forecasting)
- Useful for educational modeling and understanding stock behavior patterns

---

## Notes

- This project predicts **movement direction**, not price.
- Markov models are simplified and assume the future depends only on the present.
- Results are probabilistic and not meant for real trading decisions.
