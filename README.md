# HiEUM: Unsupervised Moving Object Detection (Re-implementation)

This repository contains an educational and qualitative re-implementation of the paper:

**Highly Efficient and Unsupervised Framework for Moving Object Detection in Satellite Videos**  
Chao Xiao et al., IEEE TPAMI.

## Overview
This project reproduces the main algorithmic pipeline of the HiEUM framework, including:
- Dataset reduction for hardware-limited environments
- Background modeling and motion extraction
- Initial sparse representation
- Pseudo-label generation and refinement
- Iterative self-evolution and sparse feedback
- Final moving object detection

The implementation focuses on qualitative analysis and algorithmic understanding rather than quantitative benchmarking.

## Original Work
- Official paper and code: https://github.com/ChaoXiao12/Moving-object-detection-in-satellite-videos-HiEUM

## Disclaimer
This is **not the official implementation**.  
All credits for the original method belong to the authors.

## Qualitative Results

Below are qualitative results from different phases of the HiEUM pipeline:

### Phase 3 – Foreground Extraction
![Phase 3](figures/phase3_foreground_extraction.png)

### Phase 4 – Sparse Motion Map
![Phase 4](figures/phase4_sparse_map.png)

### Phase 6 – Refinement
![Phase 6](figures/phase6_refinement.png)

### Phase 9 – Final Moving Object Detection
![Phase 9](figures/phase9_final_detection.png)
