# Parallel Grayscale Segmentation using 1D K- Means
Segmentation is the process of visualizing and separating different objects in an image 
depending on some data attributes (pixel intensities (most popular), depth, or any other 
data attributes that may be accompanied with each pixel or with a set of neighbouring 
pixels). We’ll do it using pixel intensities on grayscale images.

![alt image](1.png)
The figure above shows a segmented image which was segmented by 3 main objects: 
Grass, Soil, and Mushroom.  
Segmentation using K-Means: 
 
We won’t cover illustration about the K-Means algorithm as it was covered in some 
courses before. But you can refresh your knowledge base by checking [this](https://www.youtube.com/watch?v=RD0nNK51Fp8) video.  Imagine that we will do the segmentation on the above image, we want to segment the 
image to 3 different areas, hence 3 clusters. Convert the colored input image to a 
grayscale image, do the clustering on the values using K=3.
