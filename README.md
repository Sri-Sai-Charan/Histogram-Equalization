# Histogram-Equalization
Histogram equalization is a method in image processing of contrast adjustment using the image's histogram.This method usually increases the global contrast of many images, especially when the image is represented by a narrow range of intensity values. 

## Overview

### Approach:
#### Histogram Equalization 
    is a computer image processing technique used to improve contrast in images. It accomplishes this by effectively spreading out the most frequent intensity values, i.e. stretching out the intensity range of the image. This method usually increases the global contrast of images when its usable data is represented by close contrast values. This allows for areas of lower local contrast to gain a higher contrast. A color histogram of an image represents the number of pixels in each type of color component. Histogram equalization cannot be applied separately to the Red, Green and Blue components of the image as it leads to dramatic changes in the image’s color balance. However, if the image is first converted to another color space, like HSL/HSV color space, then the algorithm can be applied to the luminance or value channel without resulting in changes to the hue and saturation of the image.

#### Adaptive Histogram Equalization 
    differs from ordinary histogram equalization in the respect that the adaptive method computes several histograms, each corresponding to a distinct section of the image, and uses them to redistribute the lightness values of the image. It is therefore suitable for improving the local contrast and enhancing the definitions of edges in each region of an image.

## Usage
```python
python3 histogram_equalization.py 
```

## Results
![image](Results/og.png)
<br>
<p align='center'>Original Image</p>
<br>
<img src='Results/adaptive_hist.png'>
<br>
<p align='center'>Adaptive Histogram</p>
<br>
<img src='Results/hist.png'>
<br>
<p align='center'>Histogram Equalization</p>
<br>

## Folder Structure
```
📦Histogram-Equalization
 ┣ 📂media
 ┃ ┗ 📂problem_1
 ┣ 📜.gitignore
 ┣ 📜LICENSE
 ┣ 📜README.md
 ┗ 📜histogram_equalization.py
```
