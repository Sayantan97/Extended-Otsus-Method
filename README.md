# Extended-Otsus-Method
Extending Otsu’s method to automatically segment an image that contains anywhere from two to four regions

In the original Otus’s method for automatic thresholding, we seek to find a threshold t that minimizes the weighted sum of within-group variances for the background and foreground pixels that result from thesholding the grayscale image within the grayscale histogram. Extended the Otsu’s method automatically segments an image that contains anywhere from two to four regions, with the background being one of the four regions. The number of regions in the input image is unknown ahead of time.
