# Gastrointestinal Polyp Segmentation in PyTorch

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/atp1988/gastrointestinal-polyp/blob/main/Polyp-Net.ipynb)

This repo provides a clean implementation of Polyp Segmentation in Pytorch on standard and real polyp datasets.

## Key Features

- [x] Executable using PyTorch 
- [x] `Polyp-Net` with pre-trained Weights
- [x] Inference example with GUI on FastAPI
- [x] GPU Accelerated 
- [x] Fully integrated with `absl-py` from [abseil.io](https://abseil.io)
- [x] Clean implementation
- [x] MIT License

![demo](https://github.com/atp1988/gastrointestinal-polyp/blob/main/predictions/pred5.png)

#### Dependency Installation

```bash
pip install -r requirements.txt
```

### Detection

```bash
python test.py --image_path data/images/xxx.jpg --mask_path data/masks/xxx.jpg 
```

![demo](https://github.com/atp1988/gastrointestinal-polyp/blob/main/predictions/pred4.png)
