# The Computer Vision Workshop

1. Basics of Image Processing
2. Common Operations When Working with Images
3. Working with Histograms 
4. Working with Contours 
5. Face Processing in Image and Video
6. Object Tracking
7. Object Detection and Face Recognition
8. OpenVINO with OpenCV


## Requirements
```
open3d==0.16.0
opencv-contrib-python==4.8.0.74
numpy==1.25.0
matplotlib==3.4.3
imutils==0.5.4
scikit-image==0.21.0
scikit-learn==1.3.0
cmake
dlib

```

### Insatlling required Packages
```bash
# Create a virtual environment
$  python -m venv packt
# Activate the environment
$ source packt/bin/activate
# Install required packages into this virtual environment
$ pip install -r MyRequirements.txt
```

# 1. Basics of Image Processing
## Numpy Arrays
```python
import numpy as np

# numpy 2D array formed as (number of rows, number of columns)
# for image pixels we will use np.uint8 data-type

# Create a 4x3 2D array filled with zeros
img0 = np.zeros(4, 3)
# Create a 4x3 2D array filled with ones
img1 = np.ones(4, 3)
# Create a 4x3 2D array filled with random numbers
imgr = np.rand(4, 3)

# View the shape of the array
img0.shape
```
