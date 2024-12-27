# Image to Pencil Sketch Converter 🎨🖤  

This project demonstrates how to convert an image into a pencil sketch using the OpenCV library in Python. It’s a simple and fun way to turn your photos into artistic sketches!  

## Features ✨  
- Convert any image to grayscale.  
- Apply inversion and Gaussian blur for smooth transitions.  
- Generate a realistic pencil sketch effect.  
- Display original and sketch images side by side.  

## How It Works 🛠️  
1. **Grayscale Conversion**:  
   The image is converted to shades of gray using OpenCV's `cvtColor` function.  
2. **Inversion**:  
   The grayscale image is inverted, flipping light and dark areas.  
3. **Blurring**:  
   A Gaussian blur is applied to the inverted image to smoothen it.  
4. **Sketch Effect**:  
   The grayscale image is divided by the inverted blurred image to create the sketch effect.  

## Prerequisites 📋  
- Python 3.x  
- OpenCV library  
- Matplotlib library (optional, for visualization)  

Install dependencies using:  
```bash
pip install opencv-python matplotlib
