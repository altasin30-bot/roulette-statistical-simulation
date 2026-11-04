# 🎡 Lucky or Rigged? Testing Fairness in Roulette

A Python simulation project that answers one question:
**Is the roulette wheel fair, and can a player win in the long run?**

## What this project does
- **Part A:** Interactive roulette game (virtual coins)
- **Part 1:** Simulates 100,000 spins and studies the data
- **Part 2:** Chi-square test: is the wheel fair? (also catches a rigged wheel)
- **Part 3:** One-sample t-test: does a Red bet win or lose on average?
- **Part 4:** 300 simulated players: what happens to their money?

## Key results
- The fair wheel passes the chi-square test; a rigged wheel is detected
- A Red bet loses about 2.7% per coin (house edge = 1/37)
- Most of the 300 simulated players end with less than they started with

## Files
- `Roulette_Project.ipynb`: full code, outputs and explanations
- `Lucky_or_Rigged_Testing_Fairness_in_Roulette.pptx`: presentation slides

## How to run
Open the notebook in Google Colab and click `Runtime → Run all`.

## Tools
Python, NumPy, SciPy, Matplotlib
