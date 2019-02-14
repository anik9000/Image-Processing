# Image-Processing

Assignment-I
====================================================
Part 1: Histogram Modification
====================================================
I investigated the effect of an inverse gamma correction point operation given by an equation (see Assignment 1 notebook) on a perfectly normal image. The above point operation would produce an image which has to be gamma corrected to restore its original contrast. I included the original image and the pre-gamma corrected image in my report.
====================================================
Part 2: Image Histogram
====================================================
Given an image and a number of intensity bins, I computed its histogram. I have Written the histogram values to a file and plot it.
Run the code on the original image (lena) I used above for bins = 2, 128, and 256. Also run the code on the pre-gamma corrected image which I produced above for bins 2, 128, and 256.
=====================================================
Part 3: How Histogram Equalization Improves Contrast
=====================================================
Code to achieve histogram equalization. Use 256 bins. 
Included copies of the original and equalized histograms in this report as well as the original and equalized images.
======================================================================================================================================


Assignment-II
=====================================================
Part 1: Spatial filtering
=====================================================
Write a Python function that uses the convolution method to perform spatial filtering on an image. Start by padding the image with 5 rows and columns to the border of the image, the value of the padding should be 0. Apply an averaging filter and Gaussian filter with a kernel size of 5x5 to image given below.  Display the filtered image in the report. 
======================================================================
 part 2: Image sharpening by Unsharp Masking and Highboost Filtering
======================================================================
Write a Python function to perform the following steps.
1. Blur the original image (Output of the first exercise)
2. Subtract the blurred image from the original (mask)
3. Add the mask to the original
Display the sharpened image in the report.
=======================================================================================================================================



  

