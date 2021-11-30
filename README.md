#Intra-Inter View Interaction Network for Light Field Image Super-Resolution
===
This repository contains official pytorch implementation of Intra-Inter View Interaction Network for Light Field Image Super-Resolution in TMM 2021, by Gaosheng Liu, Huanjing Yue, Jiamin Wu, and Jingyu Yang.[LF-IINet](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9599365)
##Dataset
We use the processed data by [LF-DFnet](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9286855), including EPFL, HCInew, HCIold, INRIA and STFgantry datasets for training and testing. Please download the dataset in the official repository of [LF-DFnet](https://github.com/YingqianWang/LF-DFnet).
##Code
###Dependencies and Installation
* Ubuntu 18.04
* Python 3.6
* Pyorch 1.3.1+torchvision0.4.2+cuda92
* Matlab
###Prepare Training and Test Data
* To generate the training data, please first download the five datasets and run:
  'GenerateTrainingData.m'
* To generate the training data, pease run:
  'GenerateTestData.m'
###Train
* Run:
  'python train.py'
###Test
* Run:
  'python test.py'
###Visual Results
* to merge the Y, Cb, Cr channels, please run:
  'GenerateResultImages.m'
##Citiation
If you find this work helpful, please consider citing the following papers:
'@article{liu2021intra,
  title={Intra-Inter View Interaction Network for Light Field Image Super-Resolution},
  author={Liu, Gaosheng and Yue, Huanjing and Wu, Jiamin and Yang, Jingyu},
  journal={IEEE Transactions on Multimedia},
  year={2021},
  publisher={IEEE}
}'
'@article{liu2021intra,
  title={Intra-Inter View Interaction Network for Light Field Image Super-Resolution},
  author={Liu, Gaosheng and Yue, Huanjing and Wu, Jiamin and Yang, Jingyu},
  journal={IEEE Transactions on Multimedia},
  year={2021},
  publisher={IEEE}
}'
##Acknowledgement
Our work and implementations are inspired by following projects:
[LF-DFnet](https://github.com/YingqianWang/LF-DFnet)
[LF-InterNet](https://github.com/YingqianWang/LF-InterNet)

