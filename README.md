# Image-Compression-with-K-Means-Klustering

## Files included in this repository
- MatLab-Octave/image_compression.m (Octave/MATLAB script for the Image Compression with K-means Klustering)
- data/data.mat (Example Dataset for K-means)
- data/bird small.png (Example Image)
- MatLab-Octave/displayData.m (Displays 2D data stored in a matrix)
- MatLab-Octave/drawLine.m (Draws a line over an exsiting figure)
- MatLab-Octave/plotDataPoints.m (Initialization for K-means centroids)
- MatLab-Octave/plotProgresskMeans.m (Plots each step of K-means as it proceeds)
- MatLab-Octave/runkMeans.m (Runs the K-means algorithm)
- MatLab-Octave/findClosestCentroids.m (Find closest centroids)
- MatLab-Octave/computeCentroids.m (Compute centroid means)
- MatLab-Octave/kMeansInitCentroids.m (Initialization for K-means centroids)

In this project, I implement the K-means algorithm and use it for image compression. I first started on an example 2D dataset (data.mat) to helped me gain an intuition of how the K-means algorithm works. After that, I used the K-means algorithm for image compression by reducing the number of colors that occur in an image to only those that are most common in that image.
