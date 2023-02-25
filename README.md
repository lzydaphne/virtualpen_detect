# virtualpen_detect
Using openCV to detect pen of different colors with camera


## Step

### 1. Process frame
- Open camera with VideoCapture

### 2. Find pen
- Convert img to HSV (in order to filter colors)
- Create "mask" (techniques to filter colors)
- Using "Find Contour"


### 3. Find contour
- Using "findContours" function
- return to find the position of nib (tip of pen)


### 4. Draw points
- Draw the trace of pen on the image.
