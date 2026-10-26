# DualFusion

**DualFusion: Dual Adaptive Fusion for Multi-View Pedestrian Detection via View Reliability Modeling and Channel Reweighting**

## Introduction

DualFusion is a multi-view pedestrian detection framework that enhances cross-view feature fusion through view reliability modeling and channel reweighting.

The framework consists of two key components:

- **Cross-View Feature Selector (CVFS):** Models cross-view feature interactions to enhance multi-view feature fusion.
- **Graph-Inspired View-Channel Reweighting (GVCR):** Jointly models view-channel dependencies using global and local descriptors to enhance pedestrian-related features and suppress redundant background responses.

## Framework

The overall architecture of DualFusion.


## Environment

The experiments were conducted using the following environment:

```text
Python: 3.10
PyTorch: 2.4.1
torchvision: 0.19.1
CUDA: 12.1
NumPy: 2.2.6
tqdm: 4.65.2
kornia: 0.8.1
opencv-python: 4.12.0.88
matplotlib: 3.10.7
```


## Datasets

The datasets can be downloaded from the following official sources:

- **WildTrack**: [Download](https://www.epfl.ch/labs/cvlab/data/data-wildtrack/)
- **MultiviewX**: [Download](https://github.com/hou-yz/MultiviewX)
- **CityStreet**: [Download](https://drive.google.com/drive/folders/11hK1REG3P35S9ANXk1YB7C1-_SS_LQGJ?spm=a2c22.12282016.0.0.309d23d4p5YjQ2)

## Training and Evaluation



## Citation

If you find DualFusion useful in your research, please consider citing our paper:

```bibtex
@article{Kong2026DualFusion,
  title   = {DualFusion: Dual adaptive fusion for multi-view pedestrian detection via view reliability modeling and channel reweighting},
  author  = {Weihang Kong and Yong Wang and He Li and Xingchen Zhang},
  journal = {Knowledge-Based Systems},
  year    = {2026},
  pages   = {117202},
  doi     = {10.1016/j.knosys.2026.117202}
}
```
