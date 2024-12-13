# ECS-174
## Installation
``` bash
pip install torch torchvision scikit-learn pandas matplotlib opencv-python
```
## Usage
To use the notebook, please download the zip files from [here](http://shuoyang1213.me/WIDERFACE/index.html) and extract them to this directory.

## Introduction
Convolutional Neural Networks have long been a powerful tool various image recongnition 
task such as handwriting recognition and object detection. However, although CNNs are effective for such tasks, they often require specific hardware 
and many layers to better adapt to training data. This however means paremters in the millions or even billions which result in hardware being unable
to compute such difficult task. Therefore, it is beneficial to find techinques to reduce computation burden on machines by finding ways in convolutional
netowrks to reduce computation burden on lower end machines. Our goal in this project was to provide an implementation of this [research paper]([https://website-name.com](https://arxiv.org/pdf/2208.00087)). 
Through techniques such as low-complexity matrix approximations and simplifying activation functions, our aim was to demonstrate proof that these techinqiues can be a more efficient and less resource intensive.

## Collaboration
### Travis Liang - Coder
- Created implementation of low-compleixty matrix approximations and implementation of simplified activation functions
- Created custom dataset loader for WIDERFACE dataset
- Created the tables on accuracy and runtime
- Contributed to the write-up for the project proposal

### Jeffrey Wang - Writer
- Contributed to the project report
- Contributed to the write-up for the project proposal
- Contributed to the presentation

### Jovan Radovic - Writer and Coder
- Coded Parts of evaluating data
- Contributed to Presentation
- Contributed to the write-up for the project proposal
- Contributed to the project report
