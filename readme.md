# Transfer Learning for Fault Diagnosis 
The detail of WDMAN can be find in the following paper.

[A Deep Transfer Model With Wasserstein Distance Guided Multi-Adversarial Networks for Bearing Fault Diagnosis Under Different Working Conditions](https://ieeexplore.ieee.org/document/8713860)

The datasets used in this paper can be download by https://data.mendeley.com/datasets/ykbc8hntzx/1

or

https://drive.google.com/open?id=1D-6edhtnyQ13P5F9QBJIFblFJkiU3Uiq

"run_main_TAN.py" is the main program, you can run this text by:
```
python run_main_TAN.py
```

or you can change the paremeter and run:
```
python run_main_TAN.py --epoch 10000 learning_rate 0.001
```


For better understanding, we run an example. The accuracy curve is shown as follows (The X-axis should be epoch times 10, Y-axis is the accuracy):

![accuracy](https://github.com/mingzhangPHD/Transfer-Learning-for-Fault-Diagnosis/blob/master/WDMAN/results/WDMAN_X/CaseDE12K_dataset_0_nx1200_class10__1_nx1200_class10/RecordAccuracy.jpeg)

The WD distance during the transfer period is presented as follows:

![WD](https://github.com/mingzhangPHD/Transfer-Learning-for-Fault-Diagnosis/blob/master/WDMAN/results/WDMAN_X/CaseDE12K_dataset_0_nx1200_class10__1_nx1200_class10/RecordWD.jpeg)

Requestments:
you can pip or conda the toolkits in the requestments.txt
or run pip install -r requirements.txt

Issues:
  1. "Load failed" is a note, not a bug, you can run this code normally.
  2. The "TypeError: can't pickle FlagValues" problem has been solved.


# Citation

If you use this code and datasets for your research, please consider citing:

```
@ARTICLE{8713860, 
author={M. {Zhang} and D. {Wang} and W. {Lu} and J. {Yang} and Z. {Li} and B. {Liang}}, 
journal={IEEE Access}, 
title={A Deep Transfer Model With Wasserstein Distance Guided Multi-Adversarial Networks for Bearing Fault Diagnosis Under Different Working Conditions}, 
year={2019}, 
volume={7}, 
number={}, 
pages={65303-65318}, 
keywords={Fault diagnosis;Rolling bearings;Data models;Wavelength division multiplexing;Convolution;Employee welfare;Training;Transfer learning;fault diagnosis;convolutional neural network;multi-adversarial networks}, 
doi={10.1109/ACCESS.2019.2916935}, 
ISSN={2169-3536}, 
month={},}
```






# Bearing-Fault-Diagnosis-using-Transfer-Learning
