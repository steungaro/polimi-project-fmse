# Frogger in Uppaal - FMSE Project

This repository contains the final project for the Formal Methods for Software Engineering course at Politecnico di Milano (PoliMi). 

## Project Participants

- Nicolò Pallavicini
- Marco Puddu
- Lorenzo Trenti
- Stefano Ungaro

The project models the classic arcade game **Frogger** using [Uppaal](https://uppaal.org/). The goal of the project is to formally verify various properties of the game logic and evaluate probabilities and expected outcomes.

## Repository Contents

- `frogger_symbolic.xml`: The standard symbolic Uppaal model of the game. Used to verify safety and liveness properties using the UPPAAL model checker.
- `frogger_stochastic.xml`: The stochastic extension of the model (Uppaal SMC). Used to evaluate performance metrics and probabilities (e.g., expected survival rates, expected time to win) using UPPAAL Statistical Model Checking.
- `report.pdf`: The complete project report detailing the system requirements, modeling choices, state space optimizations, and the verification results.

## How to Run

1. Download and install [Uppaal](https://uppaal.org/).
2. Open either `frogger_symbolic.xml` or `frogger_stochastic.xml` via the Uppaal GUI.
3. Use the **Simulator** tab to step through the model transitions manually or automatically.
4. Navigate to the **Verifier** tab to load and run the pre-defined queries.
