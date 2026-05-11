# Smart-Motion-Signal-Analysis
# Smart Motion Signal Analysis 🚀

This project demonstrates the intersection of **Computer Vision** and **Digital Signal Processing (DSP)**. It captures motion from a webcam and converts it into a 1D intensity signal.

## How it works:
1. **Frame Differencing**: Calculating the absolute difference between consecutive frames.
2. **Signal Generation**: Summing pixel intensities to create a motion signal.
3. **Peak Detection**: Using `scipy.signal.find_peaks` to count distinct movements.

## Visualization:
result (2).png

## Requirements:
- OpenCV
- NumPy
- Matplotlib
- SciPy
