# MASSIKA-IKHLEF-
# Hybrid Approach for Constrained Portfolio Optimization using MLP and NSGA-II

This repository contains the official implementation of a hybrid financial engineering framework that combines Artificial Neural Networks (Multi-Layer Perceptron) and Multi-Objective Evolutionary Algorithms (NSGA-II) to solve the constrained portfolio selection problem.

##  Overview

Traditional portfolio optimization models (like Markowitz's mean-variance framework) often struggle when real-world constraints—such as cardinality, transaction costs, and bounding limits—are introduced, turning the problem into a highly non-linear, NP-hard combinatorial challenge.

This project proposes a two-stage hybrid methodology:
1. Asset Selection and Filtering (MLP): A Multi-Layer Perceptron network captures non-linear market dynamics and patterns to forecast asset behavior and filter the investment universe.
2. Multi-Objective Optimization (NSGA-II): An advanced Non-dominated Sorting Genetic Algorithm II explores the decision space using continuous operators (such as the BLX crossover) to construct a high-quality, well-distributed Pareto optimal front balancing return and risk.

##  Key Features

Non-linear Modeling: Financial time-series filtering through a robust MLP architecture.
Realistic Constraints: Handles strict real-world trading limits (cardinality constraints, floor/ceiling bounds).
Advanced Exploration: Implements continuous genetic operators like the Blend Crossover (BLX) to prevent premature convergence and maintain population diversity.
Multi-Objective Evaluation: Generates and visualizes clean Pareto fronts (Risk vs. Return).

## Tech Stack and Libraries

The project is built using Python and leverages the following standard scientific computing libraries:
numpy and pandas - Data manipulation and vectorization
scikit-learn/ tensorflow - Neural network architecture (MLP)


