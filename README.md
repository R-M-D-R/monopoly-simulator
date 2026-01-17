# Monopoly Simulator

Which Monopoly properties are the best to purchase?

This project uses Monte Carlo simulation to model millions of turns of the board game Monopoly under official rules in order to analyze landing probabilities and property value. The simulator tracks player movement, jail mechanics, and doubles to determine which spaces are visited most frequently and how game rules affect strategy.

![Landing Probability](images/monopoly-heat-map.png)

The goal is to provide a data-driven view of Monopoly: instead of relying on intuition, we estimate which properties generate the most traffic and therefore the most potential rent.

## Motivation

While watching a family game of Monopoly, I became curious whether the “best” properties are actually the ones players assume. This project applies probability, statistics, and simulation to analyze Monopoly using real mechanics rather than intuition.

## Features

- Realistic dice rolling with doubles logic  
- Jail rules (three doubles sends you to jail, doubles to escape, third attempt forces exit)  
- Monte Carlo simulation of millions of turns  
- Landing frequency analysis  
- Visualization of space visit probabilities  

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib

---

## Project Structure

```text
monopoly-simulator/
│
├── monopoly-simulator.py
├── monopoly-board.xlsx
├── README.md
├── requirements.txt
└── .gitignore

