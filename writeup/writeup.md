# **Finding Lane Lines on the Road** 

## Description

The goal of this project was to find the lane lines on the road from an image. The source of the images is a camera mounted to the front of the car. The lane lines were found using only computer vision techniques within the pipeline


## Summary of Pipeline

The following is a top level description of the pipeline used to detect the lane lines

* Color threshold mask
* Grayscale conversion
* Gaussian blur filter
* Canny edge detection
* Region masking
* Hough line transform
* Line filtering
* Combine with weighting 

## Pipeline Details

![Input Image](images/input_image.jpg)

**Color threshold mask**

![color threshold low](images/color_threshold_low.jpg)
![color threshold high](images/color_threshold_high.jpg)

---
**Grayscale conversion**

![grayscale image](images/gray_img.jpg)

---
**Gaussian blur filter**

![blur image](images/blur_img.jpg)

---
**Canny edge detection**

![canny edge detection](images/edge_img.jpg)

---
**Region masking**

![region of interest](images/region_of_interest.jpg)
![masked image](images/masked_img.jpg)

---
**Color threshold mask application**

![color threshold application](images/masked_filt_img.jpg)

---
**Hough line transform**

![hough line transform](images/hough_line.jpg)

---
**Line filtering**

![filterd lines](images/line_img.jpg)

---
**Combine with weighting**

![combined image](images/combined_img.jpg)

---

## Potential Issues

## Possible Improvements
