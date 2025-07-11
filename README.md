## WSUIE 
Source code and dataset for our paper "**[WSUIE: Weakly Supervised Underwater Image Enhancement for Improved Visual Perception](https://ieeexplore.ieee.org/document/9516935)**" by Lin Hong, Xin Wang, Zhenlong Xiao, Gan Zhang, and Jun Liu,

Created by **Lin Hong**, email: eelinhong@ust.hk or 20B953023@stu.hit.edu.cn

![](Introduction.png)

## Requirement
1. Python 3.8.
1. Pytorch 1.4.0

The script to get depth map (https://pan.baidu.com/s/1fNcvkxMT-WhhgUwwYNoKbA), fetch code [pgb8]

## UUIE dataset
[UUIE dataset](https://pan.baidu.com/s/1r8iGIjYK1OC5BKOrq6DFJw) fetch code [3qum] contains 4088 (extend to 4096)raw underwater images and 5629 (extend to 5848) high-quality images, and there are 50 (extend to 200) raw underwater images and 50 high-quality images for the model test. As far as we know, the UUIE is the first public dataset dedicated to the research of weakly supervised underwater image enhancement. It is free for academic research, not for any commercial purposes.

Its folder looks like this:
````
   UUIE
   |-- training set
   |   |-- train A
   |   |-- train B
   |-- test set
   |   |-- test set
````
Samples in UUIE dataset
![](datasetsamples.png)



### Citation

Please cite our papers if you use this dataset, code or any of the models. 

```
@ARTICLE{9516935,
  author={Hong, Lin and Wang, Xin and Xiao, Zhenlong and Zhang, Gan and Liu, Jun},
  journal={IEEE Robotics and Automation Letters}, 
  title={WSUIE: Weakly Supervised Underwater Image Enhancement for Improved Visual Perception}, 
  year={2021},
  volume={6},
  number={4},
  pages={8237-8244},
  doi={10.1109/LRA.2021.3105144}}
```
