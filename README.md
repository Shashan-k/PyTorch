
# PyTorch Learning Examples

This repository contains a collection of PyTorch examples and learning materials demonstrating fundamental concepts in deep learning using PyTorch.

## Environment Setup

- Python 3.x
- PyTorch 2.6.0+cu124
- CUDA support (if available)

## Topics Covered

### 1. Tensor Operations
- Creating tensors using different methods:
  - `torch.empty()`
  - `torch.zeros()`
  - `torch.ones()`
  - `torch.rand()`
  - `torch.tensor()`
- Random seed setting for reproducibility
- Basic tensor operations and manipulations

### 2. CUDA Support
- GPU availability checking
- CUDA device information
- Moving tensors between CPU and GPU

## Getting Started

1. Ensure you have Python installed
2. Install PyTorch:
```bash
pip install torch
```

3. Verify CUDA availability (if using GPU):
```python
import torch
print(torch.cuda.is_available())
print(torch.cuda.device_count())
print(torch.cuda.get_device_name(0))
```

## Project Structure

```
pytorch/
├── Pytorch_2.ipynb    # Main Jupyter notebook with examples
└── README.md          # This file
```

## Usage

The examples are provided in a Jupyter notebook format. You can run them sequentially to learn about different PyTorch concepts. Each section includes:
- Code examples
- Explanatory comments
- Expected outputs

## Requirements

- Python 3.x
- PyTorch 2.6.0 or later
- Jupyter Notebook
- CUDA toolkit (optional, for GPU support)

## License

This project is open source and available under the MIT License. 
=======
# PyTorch
>>>>>>> origin/main
