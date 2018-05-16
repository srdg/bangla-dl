# bangla-dl
Classifying handwritten Bengali alphabet characters in real-time.    
Implementation of [_Handwritten Bangla Digit Recognition using Deep Learning by Md Zahangir Alom et. al._](https://arxiv.org/pdf/1705.02680.pdf)

## Dataset
I used the [CMATERdb](https://www.dropbox.com/s/55bhfr3ycvsewsi/CMATERdb%203.1.2.rar) pattern recognition database.

## Requirements
Run in terminal : `sudo -H pip3 -r install requirements.txt`

## Architecture

#### _Conv2D - MaxPool - Conv2D - MaxPool - DropOut - FC - Softmax(Classification)_

## Accuracy

#### Train : ~86%    
#### Test : ~86%

## Sample recognition recorded in real-time

![Detection](https://github.com/srdg/bangla-dl/blob/master/sample_detect.gif)

## Remarks

* Image size used is 32 x 32
* The model is still not robust enough, accuracy can be improved using inception.

## References 

* Inspired from the [work](https://github.com/akshaybahadur21/Devanagiri-Recognizer) of [@akshaybahadur21](https://github.com/akshaybahadur21). 
* Help taken from
  + [OpenCV official documentation](https://docs.opencv.org/3.4/d6/d00/tutorial_py_root.html)
  + [Multi-label classification with keras](https://www.pyimagesearch.com/2018/05/07/multi-label-classification-with-keras/)
* Looking forward to improve accuracy [from this implementation of @dibyatanoy](https://github.com/dibyatanoy/Bengali-Handwritten-Character-Recognition-Using-Convolutional-Neural-Networks).
