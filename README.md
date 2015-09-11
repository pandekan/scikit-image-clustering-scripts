# Scikit Image Clustering Scripts:
`Python` scripts using `scikit-image` and `scikit-learn` to cluster images.

## files:
**otsu_thresholding.py**: Performs the Otsu thresholding and show the original gray-scale image and the binarized image.  
**histogram.py**: Calculates & show the histogram of the gray scale image.  
**dilation.py**: Dilates the binary thresholded image to fill holes.  
**equalization.py**: Thresholding a histogram-equalized image (enhanced in contrast).  
**kmeans_clustering.py**: Performs a k-means clustering followed by an Otsu thresholding.
**gaussian_mixture_model.py**: Gaussian Mixture Model on image population.
**mean_shift.py**: Performs the Mean Shift algorithm on the image.
**adaptive_filters.py**: Compare adaptive filters (lee, frost, kuan) to mean/median filters.

## Prerequisites:
**numpy & scipy**: `pip install numpy scipy`
**scikit-image**: `pip install scikit-image`
**scikit-learn**: `pip install scikit-learn`
**pyradar**: `pip install pyradar`
