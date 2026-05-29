# Physics-Informed AI Framework for Structural Failure Prediction in Rotating Disk Systems

## Overview

This project presents a physics-informed artificial intelligence framework for predicting structural failure in rotating disk systems.

The framework integrates:

- Classical rotating disk stress analysis
- Von Mises failure criterion
- Physics-informed dataset generation
- Machine learning-based failure prediction

## Dataset

A synthetic dataset containing 50,000 rotating disk configurations was generated using analytical elasticity equations under varying:

- Density
- Young's Modulus
- Poisson Ratio
- Yield Strength
- Inner Radius
- Outer Radius
- Disk Thickness
- Rotational Speed

## Machine Learning Models

The following models were evaluated:

- Random Forest
- XGBoost
- Support Vector Machine (SVM)
- Multi-Layer Perceptron Neural Network

## Results

| Model | Accuracy |
|---------|---------|
| Random Forest | 97.87% |
| XGBoost | 98.87% |
| Support Vector Machine | 99.49% |
| Neural Network | 99.23% |

SVM achieved the best performance with an accuracy of 99.49%.

## Figures

The repository contains all figures used in the paper, including:

- Stress distributions
- Dataset generation workflow
- AI framework
- ROC curves
- Confusion matrix
- Feature importance analysis

## Paper

The full research paper is available in:

paper/Physics_Informed_AI_Rotating_Disk_Failure_Prediction.pdf

## Author

Abhaya Kanwar

Jaypee University of Information Technology

Department of Computer Science (AI & ML)

## Keywords

Physics-Informed Machine Learning, Structural Failure Prediction, Rotating Disk Systems, Structural Health Monitoring, Predictive Maintenance, Support Vector Machine, Engineering Reliability, Von Mises Criterion
