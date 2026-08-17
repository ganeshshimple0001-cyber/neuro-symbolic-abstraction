# Neuro-Symbolic Abstraction for ARC-AGI

## Overview
This repository contains the official code and documentation for our submission to the **ARC Prize 2026 - Paper Track**. Our approach introduces a Neuro-Symbolic Hybrid architecture that bridges deep neural perception with explicit symbolic program synthesis to solve 2D grid transformations.

## Key Features
- **Object-Centric Perception:** Detects and clusters discrete visual entities within the grid states based on spatial and color properties.
- **Symbolic Program Synthesis:** Generates explicit transformation rules (such as symmetry, rotation, and translation) rather than guessing raw pixels blindly.
- **Interpretable Logic Engine:** Validates operational steps transparently against few-shot examples to ensure high reliability.

## Repository Structure
- `solution.py`: The core code implementing the neuro-symbolic solver and symbolic transformation engine.
- `README.md`: Project description and documentation.
