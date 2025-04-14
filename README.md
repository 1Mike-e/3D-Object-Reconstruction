# 🧠 Enhanced NeRF in PyTorch

This repository contains a minimal yet enhanced implementation of **Neural Radiance Fields (NeRF)** using **PyTorch**. It is designed for learning and experimenting with neural rendering techniques on synthetic datasets, specifically the [Tiny NeRF dataset](http://cseweb.ucsd.edu/~viscomp/projects/LF/papers/ECCV20/nerf/tiny_nerf_data.npz).

## 🚀 Features

- 🔍 **Data Loader**  
  Efficiently loads and splits the dataset for training and validation.

- 🧱 **Enhanced NeRF Model**  
  Supports positional encoding with configurable frequency bands, deeper MLP architecture, and Xavier weight initialization.

- 🧮 **Fixed Volume Rendering**  
  Implements a numerically stable version of NeRF’s volume rendering algorithm.

- 🎯 **Training Loop**  
  Includes random pixel sampling, ray generation, rendering, loss computation, and validation visualization.

- 📉 **Live Visualization**  
  Displays rendered validation images and loss curve during training.

- 💾 **Progress Logging**  
  Intermediate results are saved in a `progress/` directory for inspection or debugging.

## 📦 Dependencies

Make sure to install the following Python packages:

- `torch`
- `numpy`
- `matplotlib`
- `IPython`
- `wget` (for downloading the dataset)

You can install them using pip:

```bash
pip install torch numpy matplotlib ipython


# Clone the repo
git clone https://github.com/yourusername/enhanced-nerf-pytorch.git
cd enhanced-nerf-pytorch

# Run the script
python3 your_script_name.py
