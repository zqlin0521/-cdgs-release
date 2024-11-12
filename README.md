# CDGS: Confidence-Aware Depth Regularization for 3D Gaussian Splatting

Code coming soon! We are currently cleaning up and documenting our implementation.

## Overview
CDGS is a confidence-aware depth-based optimization strategy for 3D Gaussian Splatting (3DGS). Our method enhances the original 3DGS through two key components:

1. **Depth Refinement and Alignment**: 
   - Utilizes Depth Anything V2 for initial depth estimation
   - Aligns monocular depth estimates with sparse SfM depth data through gradient descent optimization
   - Improves geometric consistency across multiple views

2. **Confidence-Aware Depth Regularization**:
   - Generates confidence maps from both depth and RGB features
   - Adaptively adjusts depth loss weights during optimization
   - Enables more stable optimization process

## Features
- Enhanced geometric accuracy in 3D reconstruction
- Improved geometric detail preservation in early training stages
- More stable convergence behavior
- Achieves comparable results with only 50% of training iterations
- Comprehensive 2D-3D evaluation framework
