# Image Processing Lab

This lab implements intensity transformations and histogram processing using Python, `scikit-image`, `NumPy`, and `Matplotlib`.

## Tasks

### 1. Intensity Rescaling

- Loaded the moon image from `skimage.data`.
- Calculated the 3rd and 80th percentiles.
- Rescaled the intensity values between these percentiles.
- Displayed the rescaled image and its histogram.

### 2. Histogram Equalization

- Applied histogram equalization to the moon image using `exposure.equalize_hist()`.
- Displayed the equalized image.
- Plotted the histogram after equalization.

### 3. Histogram Matching

- Used the Chelsea image as the source image.
- Used the rocket image as the reference image.
- Matched Chelsea’s histogram to the rocket image using `exposure.match_histograms()`.
- Displayed the source, reference, and matched images.

## Libraries Used

- NumPy
- Matplotlib
- scikit-image
