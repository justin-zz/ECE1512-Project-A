# SSM & VLM Experiments with Comprehensive Lossy-ness Measurement

## Project Overview
This repository contains a comprehensive implementation for evaluating **State Space Models (SSMs)** and **Vision-Language Models (VLMs)** with token pruning and lossy-ness measurement. The project compares different architectures and analyzes the trade-offs between efficiency and information preservation.

## Features

### 🔬 SSM Implementation
- **Causal Mamba**: Sequential processing with causal attention
- **Bidirectional Mamba**: Bidirectional context understanding
- **Custom Text Dataset**: Synthetic dataset with complex patterns for evaluation

### VLM with Token Pruning
- **Saliency-based Pruning**: Dynamic token selection based on importance scores
- **Comprehensive Metrics**: Multi-faceted lossy-ness measurement
- **Flexible Pruning Ratios**: Configurable from 10% to 100% token retention

### Analysis & Visualization
- **Multi-panel plots**: Comprehensive visual comparison of all metrics
- **Efficiency-Loss Trade-off**: Identification of optimal operating points
- **Detailed Reporting**: Quantitative analysis of pruning effects

## Quick Start

### Installation
The code automatically installs required dependencies:

```bash
# Dependencies will be installed automatically when running the script
# Manual installation if needed:
pip install torch torchvision matplotlib numpy tqdm scipy scikit-learn
