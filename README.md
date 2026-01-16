# Monopoly Simulator

Which Monopoly properties are the best to purchase?

This project uses Monte Carlo simulation to model millions of turns of the board game Monopoly under official rules in order to analyze landing probabilities and property value. The simulator tracks player movement, jail mechanics, and doubles to determine which spaces are visited most frequently and how game rules affect strategy.

The goal is to provide a data-driven view of Monopoly: instead of relying on intuition, we estimate which properties generate the most traffic and therefore the most potential rent.

## Features

- 🎲 Realistic dice rolling with doubles logic  
- 🚔 Jail rules (three doubles sends you to jail, doubles to escape, third attempt forces exit)  
- 🃏 Chance and Community Chest card effects  
- 🔁 Monte Carlo simulation of millions of turns  
- 📊 Landing frequency analysis  
- 📈 Visualization of space visit probabilities  

---

## Project Structure

```text
monopoly-simulator/
├── src/
│   ├── board.py
│   ├── spaces.py
│   ├── cards.py
│   ├── dice.py
│   ├── player.py
│   ├── game.py
│   └── simulation.py
├── experiments/
├── notebooks/
├── data/
└── README.md
