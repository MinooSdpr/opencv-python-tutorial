# OpenCV Image Processing Basics 🖼️🔍

This repository provides a beginner-friendly walkthrough of fundamental image processing tasks using **OpenCV**. Whether you're just starting with computer vision or brushing up on the basics, this repo covers essential operations such as reading and writing images, drawing, color space conversion, cropping, image addition, thresholding, and morphological operations.

---

## 📁 Contents

### 01. **Reading and Writing Images**

* Load images from disk using `cv2.imread()`
* Save processed images using `cv2.imwrite()`
* Display images using `cv2.imshow()`

### 02. **Drawing on Images**

* Draw lines, rectangles, circles, and text using OpenCV's drawing functions

### 03. **Color Space Conversion**

* Convert images between color spaces: BGR ↔️ Grayscale, HSV, LAB, etc.
* Use `cv2.cvtColor()` for transformations

### 04. **Cropping and Pasting**

* Crop regions of interest (ROI) from images
* Paste or replace regions in the same or different images

### 05. **Adding Images and Applying Thresholding**

* Image blending and addition using `cv2.add()` and `cv2.addWeighted()`
* Apply simple and adaptive thresholding techniques

### 06. **Morphological Operations**

* Erosion, Dilation
* Opening, Closing
* Morphological gradients and top-hat/black-hat transformations

---

## 🛠️ Requirements

* Python 3.x
* OpenCV (`opencv-python`)

Install dependencies:

```bash
pip install opencv-python
```
