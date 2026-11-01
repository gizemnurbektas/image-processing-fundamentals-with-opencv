# Image Processing Fundamentals with OpenCV

A Google Colab project demonstrating a basic image-processing workflow with OpenCV and Matplotlib. It displays an uploaded source image, converts it to grayscale, applies Gaussian blur, detects edges with Canny, and compares all four stages in a single figure. The notebook’s executed cells preserve the visual outputs.

## Notebook

Open [`Image_Processing_Fundamentals_with_OpenCV.ipynb`](Image_Processing_Fundamentals_with_OpenCV.ipynb) in Google Colab or Jupyter. In Colab, run the upload cell and choose the image you want to process.

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

## Run in Google Colab

Open the notebook and run the cells in order. When prompted, upload a JPEG or PNG. The final cell displays the four-stage comparison. The current notebook uses the image supplied to its Colab upload cell; the source image can be added as `images/sample.jpg` when packaging the assets separately.

## Project structure

```text
image-processing-fundamentals-with-opencv/
├── Image_Processing_Fundamentals_with_OpenCV.ipynb
├── requirements.txt
├── LICENSE
├── .gitignore
└── README.md
```
