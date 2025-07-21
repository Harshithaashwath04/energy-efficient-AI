# Energy-Efficient AI for IoT Edge Devices: A Green AI Approach

## Overview
This project develops energy-efficient machine learning models (LightGBM and CatBoost) to predict energy consumption in blockchain-based IoT edge systems. It employs model pruning (83% and 75% energy reductions) and reinforcement learning (RL)-based scheduling (20-35% savings) to enable real-time predictions on a simulated Raspberry Pi (3.95W). SHAP analysis identifies key features like `data_size` for 0.39 kWh savings, promoting sustainable AI deployment on resource-constrained devices.

## Features
- Energy-efficient model pruning for LightGBM and CatBoost.
- RL-based task scheduling for optimized energy use.
- Real-time energy prediction on a simulated Raspberry Pi.
- SHAP-based interpretability for feature importance.

## Prerequisites
- Python 3.8+
- Required libraries: `pandas`, `numpy`, `lightgbm`, `catboost`, `scikit-learn`, `matplotlib`, `seaborn`
- Google Colab environment (optional for cloud-based execution)
