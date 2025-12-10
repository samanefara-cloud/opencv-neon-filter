# opencv-neon-filter
Simple Neon Filter in Python &amp; OpenCV (my day-12 CV practice)
# Neon Filter with OpenCV

This is one of my first computer vision projects (around day 12 of learning CV).  
I load an image in Colab, apply Gaussian blur, detect edges with Canny, and then blend the edges back on the original image to create a simple neon effect.

## What I learned

- Reading images in Colab and converting from BGR to RGB.
- Using GaussianBlur and Canny edge detection in OpenCV.
- Designing helper functions (`apply_blur`, `detect_edges`) and a high-level function (`apply_neon_filter`).
- Blending images with `cv2.addWeighted` to create a neon-style effect.

## How to run

1. Open the notebook `neon_filter.ipynb` in Google Colab.
2. Upload one or more images.
3. Run all cells to see the neon effect on your images.

## Examples

Original vs Neon output:

![original 1](examples/original_1.jpg)
![neon 1](examples/neon_1.jpg)
