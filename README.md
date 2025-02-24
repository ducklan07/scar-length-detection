# scar-length-detection
# Image Augmentation and Scar Measurement

This project demonstrates image augmentation techniques using CLAHE (Contrast Limited Adaptive Histogram Equalization) and measures the length of scars in medical images. The project uses OpenCV and Matplotlib for image processing and visualization.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Usage](#usage)
- [Example](#example)
- [License](#license)

## Introduction

The goal of this project is to enhance medical images using CLAHE and measure the length of scars. The user can visualize the top 3 contours detected in the image and select the one that best represents the scar. The selected contour is then used to estimate the length of the scar.

## Requirements

- Python 3.7+
- OpenCV
- NumPy
- Matplotlib

## Usage

1. Place your images in the project directory. For example, `day0_scar.png` and `day2_scar.png`.

2. Open the Jupyter Notebook `image_augmentation.ipynb`:
    ```bash
    jupyter notebook image_augmentation.ipynb
    ```

3. Run the cells in the notebook to apply CLAHE, visualize the top 3 contours, and measure the length of the scar.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
