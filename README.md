# Enhancing-Images-with-OpenCV

## Overview

This project demonstrates color image enhancement using Histogram Equalization in the HSV color space with OpenCV and Python.

The program improves image brightness and contrast while preserving the natural color information of the image. Histogram Equalization is applied specifically to the Value (V) channel in HSV format to avoid unwanted color distortion.

The project also visualizes the intensity distribution of images using histograms for both the original and enhanced outputs.

---

## Features

- Reads and processes a color image using OpenCV
- Converts images from BGR to HSV color space
- Applies Histogram Equalization on the V channel
- Enhances image brightness and contrast
- Converts enhanced image back to BGR format
- Displays original and enhanced images
- Plots BGR histograms for comparison using Matplotlib

---

## Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Project Structure

```bash
.
├── parrot.jpg
├── Image-Enhancement.ipynb
└── README.md
```

---

## How Histogram Equalization Works

Histogram Equalization redistributes pixel intensity values across a wider range to improve image contrast.

The program:
1. Converts the image from BGR to HSV
2. Extracts the Value (V) channel
3. Applies Histogram Equalization using OpenCV
4. Merges the channels back together
5. Converts the image back to BGR format

This enhances brightness and contrast while preserving the original colors.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/bsuryaprakash06/Enhancing-Images-with-OpenCV.git
```

Move into the project folder:

```bash
cd Enhancing-Images-with-OpenCV
```

Install the required libraries:

```bash
pip install opencv-python numpy matplotlib notebook
```

---

## How to Run

Open Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```bash
Image-Enhancement.ipynb
```

Run all cells to execute the program.

---

## Output

### Original Image vs Enhanced Image
<img width="625" height="464" alt="{0A1AEDB4-879D-4FD2-A298-92E3BFE170BE}" src="https://github.com/user-attachments/assets/bf29015e-4266-424e-8904-814f352a7e2a" />

---

## License

This project is open-source and available under the MIT License.
