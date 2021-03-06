# Face-detection-with-opencv
**Feature-based face detection algorithms** are fast and effective and have been used successfully for decades.

Here the technique i used is cascade classifiers first described by **Paul Viola** and **Michael Jones** in their 2001 paper titled "[Rapid Object Detection using a Boosted Cascade of Simple Features](https://ieeexplore.ieee.org/document/990517)".

In the above paper,effective features and range of very simple or weak features in each face are learned by using the [AdaBoost algorithm](https://machinelearningmastery.com/boosting-and-adaboost-for-machine-learning/).


As Classifier Cascade face detection algorithm is provided in [OpenCV library](https://opencv.org/) i used this library to detect face in the photograph.

## Images used 
1. **single face image**
   ![my image](https://github.com/kuluruvineeth/Face-detection-with-opencv/blob/main/test1.jpg)
   
2. **multiple face image**
   ![Group photo extracted from internet](https://github.com/kuluruvineeth/Face-detection-with-opencv/blob/main/test2.jpg)
   
   
 ## Result after processing  
 1. ![transformed image1](https://github.com/kuluruvineeth/Face-detection-with-opencv/blob/main/f_test1.jpg)
 2. ![transformed image2](https://github.com/kuluruvineeth/Face-detection-with-opencv/blob/main/f_test2.jpg)
 
 ## Requirements
 * [opencv](https://pypi.org/project/opencv-python/)
 * [haarcascade frontalface default](https://raw.githubusercontent.com/opencv/opencv/master/data/haarcascades/haarcascade_frontalface_default.xml)

## Conclusion
The results are not that perfect but perhaps better results can be achieved with further tuning after many hit and trial methods


