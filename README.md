# BrainStation Data Science Capstone : Advanced Skin Segmentation for Enhanced Image Processing and Computer Vision Applications
## Leveraging Machine Learning for Accurate Skin Detection
=========================

### Executive Summary

The problem at hand is in the realm of Image processing and machine learning. The focus is on Skin segmentation. This experiment will help distinguish between skin and non-skin areas in images. 

The aim is to use machine learning techniques to build a robust classification model that can accurately segment skin regions in images. By using the R, G, B color space data from a diverse set of images, we can train a model to recognize diverse skin tones under different conditions. The model will be evaluated for its accuracy, precision, and recall to ensure it performs well across different demographics.

#### Dataset Dictionary

| Feature Name | Description                       | Type        | Range                  |
|--------------|-----------------------------------|-------------|------------------------|
| B            | Blue color intensity              | Int         | 0-255                  |
| G            | Green color intensity             | Int         | 0-255                  |
| R            | Red color intensity               | Int         | 0-255                  |
| Y            | Skin/Non-skin classification label| Int         | 0 (non-skin), 1 (skin) |

Feature Details:

`B (Blue color intensity)`:

Description: Intensity of the blue channel in the RGB color space.
Type: Int.
Range: 0 to 255.


`G (Green color intensity)`:

Description: Intensity of the green channel in the RGB color space.
Type: Int.
Range: 0 to 255.

`R (Red color intensity)`:

Description: Intensity of the red channel in the RGB color space.
Type: Int.
Range: 0 to 255.

`Y`:

Description: Indicates whether the pixel represents skin or non-skin.
Type: Categorical.
Values:
0: Non-skin
1: Skin


### Demo
 
 TBA


### Methodology

TBA 

### Organization

#### Repository 

* `data` 
    - contains link to copy of the dataset (stored in a publicly accessible cloud storage)
    - saved copy of aggregated / processed data as long as those are not too large (> 10 MB)

* `model`
    - `joblib` dump of final model(s)

* `notebooks`
    - contains all final notebooks involved in the project

* `docs`
    - contains final report, presentations which summarize the project

* `references`
    - contains papers / tutorials used in the project

* `src`
    - Contains the project source code (refactored from the notebooks)

* `.gitignore`
    - Part of Git, includes files and folders to be ignored by Git version control

* `conda.yml`
    - Conda environment specification

* `README.md`
    - Project landing page (this page)

* `LICENSE`
    - Project license

#### Dataset
https://archive.ics.uci.edu/dataset/229/skin+segmentation
Bhatt,Rajen and Dhall,Abhinav. (2012). Skin Segmentation. UCI Machine Learning Repository. https://doi.org/10.24432/C5T30C.

### Credits & References

TBA
