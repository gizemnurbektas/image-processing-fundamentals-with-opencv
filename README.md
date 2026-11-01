# Image Processing Fundamentals with OpenCV

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gizemnurbektas/image-processing-fundamentals-with-opencv/blob/main/Image_Processing_Fundamentals_with_OpenCV.ipynb)

A Google Colab project demonstrating a basic image-processing workflow with OpenCV and Matplotlib. It displays an uploaded source image, converts it to grayscale, applies Gaussian blur, detects edges with Canny, and compares the stages in one figure.

## Notebook and results

Open [`Image_Processing_Fundamentals_with_OpenCV.ipynb`](Image_Processing_Fundamentals_with_OpenCV.ipynb) in Google Colab. The original image and processed visual results are preserved in the notebook’s saved cell outputs. Run the upload cell to use the image again in a new runtime.

## Processing steps

1. Upload and display a source image.
2. Convert it to grayscale.
3. Apply a 5 × 5 Gaussian blur.
4. Detect edges with Canny thresholds of 100 and 200.
5. Compare the original, grayscale, blurred, and edge-detected images.

## Requirements

- Python 3
- OpenCV
- NumPy
- Matplotlib
- Google Colab or Jupyter Notebook

Install the dependencies locally with:

```bash
pip install -r requirements.txt
```

## Project structure

```text
image-processing-fundamentals-with-opencv/
├── Image_Processing_Fundamentals_with_OpenCV.ipynb
├── requirements.txt
├── LICENSE
├── .gitignore
└── README.md
```

The image and generated comparisons are stored as notebook outputs rather than separate image files.
