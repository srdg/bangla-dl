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

* Image size used is 28 x 28
* The model is still not robust enough, accuracy can be improved using inception.
