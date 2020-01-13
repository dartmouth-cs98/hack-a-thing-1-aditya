## Hack-A-Thing 1: Face-Detection in Images/Videos


### Tutorial
- Worked through a tutorial on face detection in images and videos with the OpenCV library and deep learning.

### What I learned
- Through this tutorial I learned how to harness the power of the OpenCV library to detect faces in images and videos. I also learned how OpenCV prepares images for classification based on their deep learning models.

### What didn't work
- One thing I had trouble wrapping my head around how OpenCV's library does pre-processing on images and prepares the image for classification through their pre-trained deep learning models. But thankfully the tutorial had another section explaining the whole procedure!

### Links
https://www.pyimagesearch.com/2018/02/26/face-detection-with-opencv-and-deep-learning/

### How to Run

1. Go to your terminal window and for the following paste these commands:

    - For images: python face-detect.py --image [your_image] --prototxt deploy.prototxt.txt \
	--model res10_300x300_ssd_iter_140000.caffemodel
    - For videos: python face-detect-video.py --prototxt deploy.prototxt.txt \
	--model res10_300x300_ssd_iter_140000.caffemodel