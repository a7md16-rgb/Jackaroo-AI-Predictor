# Jackaroo-AI-Predictor
# Jackaroo-AI Predictor

Final project for the Building AI course

## Summary
Jackaroo-AI is a move-prediction model for the strategic board game Jackaroo. It calculates the best possible card to play based on the current board state to maximize the winning probability for the team.

## Background
Jackaroo is a highly strategic, team-based board game. Players often struggle to decide which card yields the best long-term advantage. An AI assistant can help beginners learn advanced tactics and avoid fatal mistakes.

## How is it used?
Users input their current hand of cards and the positions of the marbles on the board. The AI analyzes the data and suggests the optimal card to play (e.g., using a 4 to move backward into the base, or an 11 to swap places) to secure a win or sabotage opponents.

## Data sources and AI methods
The system uses Reinforcement Learning algorithms trained on thousands of simulated Jackaroo matches to understand exact card values, probabilities, and complex board dynamics.

## Challenges
The main challenge is the hidden information (opponents' hands) and the cooperative nature of the game, requiring the AI to predict both enemy attacks and partner setups without communicating directly.

## What next?
Developing a computer vision feature where players simply point their phone camera at the physical Jackaroo board and their cards to get instant real-time move suggestions.
