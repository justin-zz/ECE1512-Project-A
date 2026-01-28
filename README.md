# SSM & VLM Experiments with Comprehensive Lossy-ness Measurement


## Project Overview

<div align="center">
<img src="/images/quadratic.png" width="500" height="200" alt="Quadratic nature of attention">   
<br>
  
<img src="/images/s4model.png" width="500" height="200" alt="S4 model of SSM">  
</div>
This repository contains a comprehensive implementation for evaluating <b>State Space Models (SSMs)</b> and <b>Vision-Language Models (VLMs)</b> with token pruning and lossy-ness measurement. The project compares different architectures and analyzes the trade-offs between efficiency and information preservation. For more information read the <a href="/Project A Report - Justin Zhang Zhong.pdf">report</a>    on this work.

## Features
  
### SSM Implementation
<div align="center">
<img src="/images/mamba.png" width="500" height="200" alt="Mamba's selection mechanism">   
<br>
<img src="/images/bimamba.png" width="300" height="500" alt="Bidirectional Mamba pipeline"> 
</div>

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
