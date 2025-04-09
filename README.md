
# Computer Vision Assignments 📷

This repository contains a collection of assignments exploring fundamental image processing operations using **OpenCV**, **NumPy**, and **Matplotlib**. The tasks demonstrate various transformations, filtering, and analysis techniques applied to grayscale and binary images.

---

## 📁 Assignments Overview

### 1. **Geometric Transformations**
- **Scaling**: Resize image by a percentage scale.
- **Rotation**: Rotate image by a given angle.
- **Translation**: Shift image along x and y axes.
- **Reflection**: Flip the image along x, y, and both axes.
- **Shearing**: Apply horizontal shearing transformation.

📂 *Files:*
- `scaling_rotation_translation.py`
- `reflection.py`
- `shearing.py`

---

### 2. **Point Processing Techniques**
- **Negative Transformation**: Invert pixel values.
- **Gamma Correction**: Non-linear intensity transformation.
- **Log Transformation**: Logarithmic enhancement of pixel intensities.

📂 *Files:*
- `negative_transformation.py`
- `gamma_correction.py`
- `log_transformation.py`

---

### 3. **Filtering Techniques**
- **Low-Pass Filtering**: Smooth image using averaging filter.
- **High-Pass Filtering**: Detect edges using a sharpening filter.

📂 *Files:*
- `low_high_pass_filter.py`

---

### 4. **Frequency Domain Filtering**
- **Fourier Transform**: Visualize magnitude spectrum.
- **Low-Pass & High-Pass Filtering**: Apply frequency domain masks.

📂 *Files:*
- `fourier_filtering.py`

---

### 5. **Logical & Morphological Operations**
- **Bitwise Operations**: Perform union, intersection, difference, and XOR on binary shapes.

📂 *Files:*
- `bitwise_operations.py`

---

### 6. **Edge & Corner Detection**
- **Canny Edge Detection**: Detect object edges using gradients.
- **Harris Corner Detection**: Detect corners based on structure tensor.

📂 *Files:*
- `canny_edges.py`
- `harris_corners.py`

---

## 🧰 Requirements

Install the following Python libraries before running the code:

```bash
pip install opencv-python numpy matplotlib
```

---

## 🖼️ Image Files

Make sure you have the required image files in the working directory:
- `grayscale_image.jpg`
- `image_converted.jpg`

Ensure these are valid grayscale images for accurate results.

---

## 📌 Notes

- Visual outputs are displayed using **Matplotlib**.
- All operations assume proper grayscale images as input.
- Fourier transforms require 2D grayscale input; validations are included.

---

## 🤓 Author

Created by [Your Name] for Computer Vision course assignments.
