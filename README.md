# Deep Learning Option Pricing

![Project Banner](banner.png)

## Table of Contents
- [Overview](#overview)
- [Key Concepts](#key-concepts)
- [Implementation Details](#implementation-details)
- [Results](#results)
- [Usage](#usage)
- [Acknowledgements](#acknowledgements)
- [References](#references)

## Overview

This repository presents an innovative exploration into pricing European-style options using Physics-Informed Neural Networks (PINNs) under the Black-Scholes model and its extensions, including stochastic volatility models and jump-diffusion models. By leveraging deep learning techniques, we aim to solve partial differential equations (PDEs) relevant to option pricing, offering a modern and efficient alternative to traditional numerical methods.

Our approach progresses from implementing a basic Neural Network to solve standard PDEs, advancing to non-linear PDEs, and culminating in the application of PINNs to solve the Black-Scholes PDE. The project's pinnacle is the integration of an LSTM layer to tackle multi-asset PDEs, showcasing the versatility and power of deep learning in financial modeling.

**Key Features:**
- Implementation of Neural Networks for solving PDEs
- Application of PINNs to the Black-Scholes model
- Integration of LSTM layers for multi-asset pricing
- Comparative analysis with traditional numerical methods


## Key Concepts

### Introduction to Financial Mathematics

1. **The Black-Scholes Model**
   - Foundation of modern option pricing theory
   - Assumptions and limitations
   - The Black-Scholes-Merton differential equation

2. **Risk-Neutral Pricing**
   - Concept of risk-neutral measure
   - Application in option pricing

3. **The Greeks**
   - Delta, Gamma, Theta, Vega, and Rho
   - Significance in risk management

### Physics-Informed Neural Networks (PINNs)

1. **PDE as Loss Functions**
   - Formulation of the optimization problem
   - Incorporation of physical laws into neural networks

2. **Boundary and Initial Conditions**
   - Techniques for enforcing constraints
   - Soft vs. hard enforcement methods

## Implementation Details

Our project follows a progressive implementation approach:

1. **Basic Neural Network for Standard PDEs**
   - Implementation: `Code1.ipynb` and `Code2.ipynb`
   - Objective: Solve simple, linear PDEs using feedforward neural networks

2. **Neural Network for Non-linear PDEs**
   - Implementation: `Code3.ipynb`, `Code4.ipynb` and `Code5.ipynb`
   - Objective: Extend the NN approach to handle non-linear PDEs

3. **PINN for Black-Scholes PDE**
   - Implementation: `Code6.ipynb`, `Code7.ipynb`
   - Objective: Apply PINN framework to solve the Black-Scholes equation

4. **LSTM-enhanced PINN for Multi-asset PDEs**
   - Implementation: `Code8.ipynb`
   - Objective: Integrate LSTM layers to handle temporal dependencies in multi-asset scenarios

## Results

Our implementation yielded promising results, demonstrating the efficacy of deep learning approaches in option pricing. Below are some key visualizations:

![Result 1](images/output1.jpg)

![Result 2](images/output2.jpg)

![Result 3](images/output3.jpg)

![Result 4](images/output4.jpg)

![Result 5](images/output5.jpg)

![Result 6](images/output6.jpg)

![Result 7](images/output7.jpg)

![Result 8](images/output8.jpg)

![Result 9](images/output9.jpg)

![Result 10](images/output10.jpg)

![Result 11](images/output11.jpg)


For a complete analysis of our results, please refer to the individual notebook files (`CodeX.ipynb`, X denotes week of progress).

## Usage

To run the notebooks:

1. Ensure you have Jupyter installed:
   ```
   pip install jupyter
   ```
2. Launch Jupyter Notebook:
   ```
   jupyter notebook
   ```
3. Navigate to the desired `CodeX.ipynb` file and run the cells sequentially.

## Acknowledgements

I would like to express my deepest gratitude to Dr. Lok Pati Tripathi for his invaluable guidance and support throughout this project. His expertise and insights have been instrumental in shaping the direction and success of this work. This project would not have been possible without his encouragement and mentorship.

## References

1. Black, F., & Scholes, M. (1973). The Pricing of Options and Corporate Liabilities. Journal of Political Economy, 81(3), 637-654.
<!-- Add DOI or link -->

2. Raissi, M., Perdikaris, P., & Karniadakis, G. E. (2019). Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear partial differential equations. Journal of Computational Physics, 378, 686-707.
<!-- Add DOI or link -->

3. [TensorFlow](https://github.com/tensorflow/tensorflow)
<!-- Add specific commit or version used -->

4. [PyTorch](https://github.com/pytorch/pytorch)
<!-- Add specific commit or version used -->

5. <!-- Add any other relevant papers, books, or repositories used in your project -->

---

**Note**: This project is part of a B.Tech Project (BTP) and is intended for educational and research purposes. For any commercial use, please consult the appropriate licensing and regulatory requirements.
