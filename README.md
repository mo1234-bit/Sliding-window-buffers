# Sliding-window-buffers

This project provides Verilog implementations of sliding window buffers for 3x3 and 5x5 convolution operations, commonly used in image processing and CNNs. The buffers efficiently stream pixel data and generate valid convolution windows in real-time.

## Features
- **Supports 3x3 and 5x5 window sizes** for flexible convolution support.
- **Handles 32x32 pixel streams** with configurable line buffers.
- **Valid signal generation** (`window_valid`) to indicate when a complete window is available.
- **Reset functionality** for initialization.
- **Scalable design** for adapting to larger window sizes.

## Repository Structure
- `buffer.v`: 3x3 sliding window module (`conv_buffer`).
- `buffer_5.v`: 5x5 sliding window module (`conv_buffer_5x5`).

![image](https://github.com/user-attachments/assets/89a6cb2e-ea8d-41f8-9ca3-23633865bd66)
