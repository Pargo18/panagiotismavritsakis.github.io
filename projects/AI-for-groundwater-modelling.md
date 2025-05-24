---
layout: single
title: "AI for Groundwater Modelling"
permalink: /projects/AI-for-groundwater-modelling/
---

Numerical modeling in hydrology and climate science often requires immense computational resources—especially for high-resolution, long-term simulations. As the demand for fast, accurate, and scalable forecasting grows, AI-based surrogate models offer a promising alternative.

This project explores the use of **Neural Operators**, particularly the **Adaptive Fourier Neural Operator (AFNO)** and **Deep Operator Network (DON)**, as efficient surrogates for hydrological modeling. These architectures go beyond conventional deep learning by learning mappings between functional spaces, enabling faster and more generalizable solutions to spatiotemporal problems.

## Project Highlights

- ⚡ **Surrogate Modeling for Hydrology**: Replaces traditional physics-based models with fast, data-driven approximations.
- 🧠 **Advanced Neural Operators**: Implements and compares AFNO and DON with classical LSTM and CNN-based models.
- 🔬 **Physics-Informed Learning**: Infuses models with hydrological constraints for improved accuracy and interpretability.
- 🌍 **Spatiotemporal Forecasting**: Predicts variables like groundwater head across both time and space.

## Tech Stack

- **Frameworks**: PyTorch, DeepXDE, Keras, JAX, nvidia-modulus
- **Architectures**: LSTM, CNN, AFNO, DON
- **Metrics**: NSE, RMSE, spatial distribution error

## Key Insights

- Neural Operators achieved **significant speed-ups** over numerical models with comparable or better accuracy.
- AFNO and DON showed strong generalization on unseen regions and hydrological conditions.
- Physics-informed constraints helped maintain **physical realism** while reducing overfitting.