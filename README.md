# 🍽️ EvoTip
**Genetic Fuzzy Inference System for Tip Recommendation**

## Overview
EvoTip is a recommendation system that predicts appropriate restaurant tip percentages using a fuzzy inference system optimized via a genetic algorithm. The model improves upon a baseline fuzzy controller by evolving membership function parameters to minimize prediction error.

## Key Features
- Multi-stage fuzzy inference system
- Genetic algorithm optimization of membership functions
- Mean Absolute Error (MAE)–based fitness evaluation
- Comparison against a baseline fuzzy model

## Methodology
1. Data preprocessing (clipping, normalization, scaling)
2. Fuzzy rule engineering based on service and food quality
3. Chromosome encoding of membership function parameters
4. Genetic algorithm optimization
5. Out-of-sample model evaluation

## Technologies Used
- Python
- scikit-fuzzy
- EasyGA
- Fuzzy Inference Systems
- Evolutionary Optimization
- Model Evaluation (MAE)

## Results
The optimized fuzzy model achieved lower prediction error than the baseline system, demonstrating the effectiveness of evolutionary tuning for fuzzy controllers.

## Future Work
- Rule-base optimization
- Multi-objective loss functions
- Deployment as an interactive recommendation tool
