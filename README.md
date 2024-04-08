# Computer-Vision-egg-grading-system

## Description
Main goal of Computer Vision is to let the system able to see things. Thus, in this research going to develop a vision-based classification system that should be able to classify different grades of eggs. This research can help to grade the eggs without manual grade classification by using image processing techniques.

The objective of this research is to gain experience in applying image processing techniques to solve some bacis business problem. 

Data Split:  90% for training and 10% for testing, employing a 10-fold cross-validation approach

Image Preprocessing techniques: Resizing(256, 256), fastNlMeansDenoisingColored algorithm, Grayscale Conversion, Otsu's thresholding, Morphological "erosion"

![image](https://github.com/esmond09/computer-vision-egg-grading-system/assets/130723274/b53a2fe1-2f9c-4b07-9472-615e4149e1c2)


Result: 
SVM - Accuracy: 0.90, Precision: 0.91, Recall: 0.90

KNN - Accuracy: 0.92, Precision: 0.93, Recall: 0.82

Neural Network - Accuracy: 0.65, Precision: 0.67, Recall: 0.65

Base on the result of trained by 3 models, it shown Neural Network perform lower than other 2 models. There may have some issues considering like lack of data and image preprocessing method.


## Dataset link used google drive
https://drive.google.com/file/d/1nsfiLz5BFed0EjE7S2tUzOm7g9q404fh/view?usp=drive_link

## Data sample
Dark background
![2BG7CROP_DARK_AA05](https://github.com/esmond09/machine-learning-egg-grading-system/assets/130723274/f23340c7-101e-4789-90a3-5a9601e10f20)

Light background
![2BG7CROP_LIGHT_AA02](https://github.com/esmond09/machine-learning-egg-grading-system/assets/130723274/fefc21a7-8cea-4894-a03c-f16f685a7caa)

## Note
You may use your own dataset as well. This research aim to utilize python public library like cv2 for image processing.
