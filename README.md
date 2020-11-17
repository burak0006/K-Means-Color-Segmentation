# K-Means-Color-Segmentation
This algorithm performs segmentation based on colors by assuming that objects are colored distinctively. It might not be sensitive about color and bright variations across the objects, but performs really well for the objects with distinct colors

K-means is a unsupervised machine learning algorithm and used for color segmentation as prior information is unknown regarding the colors.

## K-Means Clustering

K-means clustering is a clustering method that subdivides a single cluster or a collection of data points into K different clusters or groups. The algorithm analyzes the data to find organically similar data points and assigns each point to a cluster that consists of points with similar characteristics. Each cluster can then be used to label the data into different classes based on the characteristics of the data (https://analyticsindiamag.com/beginners-guide-to-k-means-clustering/)

You must import below libraries before running. Scikit learn contain many useful ML libraries including K-means. Color segmentation is perfomed by grouping every pixel into a different clusters based on their RGB values.

## Preparation
### Library
- PIL
- OpenCV 2
- numpy
- pandas

Execute following commands for install library:
```sh
$ pip install opencv-python
$ pip install numpy
$ pip install matplotlib
$ pip install matplotlib
```
