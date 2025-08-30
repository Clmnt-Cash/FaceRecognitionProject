# Face Recognition Project

This repository contains a face recognition system implemented in main.ipynb.
It demonstrates how to detect and recognize faces using Siamese Neural Networks (SNNs) built with PyTorch.
I chose PyTorch for this project since I was already familiar with TensorFlow and wanted to explore a different framework. Leveraging GPU support significantly improved training and inference speed.
To design the Siamese Neural Network, I referred to the research paper “Siamese Neural Networks for One-Shot Image Recognition” : https://www.cs.cmu.edu/~rsalakhu/papers/oneshot1.pdf
The main goal of this project was to gain a deeper understanding of neural networks by applying them to a real-world problem.

Currently, the project can:
- Load a dataset of labeled images.
- Use a pretrained model for recognition.
- Train a model from scratch via the early sections of the notebook.

In the future, I plan to extend this work into a full application, enabling face-based authentication for secure access to devices.


## Features

- Face detection and recognition with PyTorch + Siamese Neural Networks.

- Support for pretrained models or training with custom datasets.

- Clear step-by-step explanations for learning and reproducibility.

## Getting Started

1. **Clone the repository**  
```bash
   git clone https://github.com/your-username/face-recognition.git
   cd face-recognition
```
2. **Install required dependencies listed in `requirements.txt`**
```bash
   pip install -r requirements.txt
```
3. Open `main.ipynb` in Jupyter Notebook.
4. Follow the instructions and run the cells to perform face recognition.

## Usage

- Use the provided sample dataset or upload your own labeled images.

- Modify notebook parameters to experiment with different training settings or architectures.

- Re-train the Siamese model from scratch or fine-tune an existing one.