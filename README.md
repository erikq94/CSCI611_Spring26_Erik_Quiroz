# CSCI611 Spring 2026 - Assignment 2

# Erik Quiroz

## How To Run

### Setup

```bash
python3 -m venv venv
source venv/bin/activate
pip install opencv-python torch torchvision jupyter matplotlib numpy scikit-learn
```

### Run Part 1 - Image Filtering

```bash
cd Assignment_2
jupyter notebook image_filtering.ipynb
```

Run all cells top to bottom using Shift+Enter

### Run Part 2 - CNN Classifier

```bash
cd Assignment_2
jupyter notebook build_cnn.ipynb
```

## Results Summary

- Part 1: Applied edge detection, corner detection, blurring and scaling filters
- Part 2: CNN achieved 70% accuracy on CIFAR-10 using Adam optimizer (20 epochs)

## Requirements

- Python 3.x
- opencv-python
- torch
- torchvision
- jupyter
- matplotlib
- numpy
- scikit-learn
