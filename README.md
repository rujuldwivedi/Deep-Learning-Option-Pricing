# Deep Learning Option Pricing

## Overview
**The main files are named 'CodeX.ipynb' where X denotes a natural number denoting the week of progress.**

This repository presents an exploration into pricing European-style options using Physics-Informed Neural Networks (PINNs) under the Black-Scholes model and its extensions, including stochastic volatility models and jump-diffusion models. By leveraging deep learning, we aim to solve partial differential equations (PDEs) relevant to option pricing, offering a modern alternative to traditional numerical methods (like FDM).

## Project Structure

### Introduction to Financial Mathematics

This section provides a foundational overview of key concepts in option pricing theory:
- **The Black-Scholes Model**: Understanding the classical approach to option pricing.
- **Risk-Neutral Pricing**: Discussing the significance of risk-neutral measures in finance.
- **The Greeks**: Analyzing the sensitivity of option prices to various factors.

### Physics-Informed Neural Networks (PINNs) for Option Pricing

Here, we delve into the application of PINNs for solving PDEs:
- **Formulation of PDEs as Loss Functions**: Translating the mathematical problem into a form suitable for neural network training.
- **Incorporating Boundary and Initial Conditions**: Ensuring the PINNs adhere to financial constraints.
- **Implementing PINNs**: Solving the Black-Scholes equation and its extensions under various scenarios.

### Comparison with Traditional Methods

This section evaluates the performance of deep learning approaches relative to classical methods:
- **Finite Difference Methods (FDM)**: Traditional numerical technique for solving PDEs.
- **Finite Element Methods (FEM)**: A more advanced approach often used for complex financial models.
- **Accuracy and Efficiency Analysis**: Comparing the results obtained from PINNs with those from FDM and FEM.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss any improvements.

## Acknowledgements

I would like to express my deepest gratitude to Dr. Lok Pati Tripathi for his invaluable guidance and support throughout this project. His expertise and insights have been instrumental in shaping the direction and success of this work. This project would not have been possible without his encouragement and mentorship.
