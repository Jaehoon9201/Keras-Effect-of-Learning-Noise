# Keras-Effect-of-Learning-Noise
# Code will be uploaded soon
It shows the effect of learning random noise when training a neural network model.

* Related Paper(my paper) : “Fault Diagnosis of Inverter Current Sensor Using Artificial Neural Network Considering Out-of-distribution”, 2021 IEEE Energy Conversion Congress and Exposition-Asia(ECCE-Asia), Singapore, May 24-27, 2021 (Accepted, 1st author, To be published)

## Why I Training a Random Noise

This idea came up with below refereces which deal with using a random noise when training a machine learning model. Random noise dataset could  be  generally  applied  as  the additional input data, weights, gradients, or outputs. Also, complex  inputs  like  noises  could  improve  the  OOD detection.

[Ref1](http://arxiv.org/abs/1511.06807) -  A.  Neelakantan  et  al.,  "Adding  Gradient  Noise  Improves Learning for Very Deep Networks,"  arXiv:1511.06807 [cs, stat],  Nov.  2015,  Accessed:  Mar.  31,  2021.  [Online]. Available: http://arxiv.org/abs/1511.06807. 

Ref2 - C.  M.  Bishop,  "Training  with  Noise  is  Equivalent  to Tikhonov Regularization,"  Neural Computation, vol. 7, no. 1, pp. 108–116, Jan. 1995, doi: 10.1162/neco.1995.7.1.108. 

Ref3 - J.  Sietsma  and  R.  J.  F.  Dow,  "Creating  artificial  neural networks that generalize," Neural Networks, vol. 4, no. 1, pp. 67–79, Jan. 1991, doi: 10.1016/0893-6080(91)90033-2. 

[Ref4](http://arxiv.org/abs/1812.04606) - D.  Hendrycks,  M.  Mazeika,  and  T.  Dietterich,  "Deep Anomaly  Detection  with  Outlier  Exposure," arXiv:1812.04606 [cs, stat], Jan. 2019, Accessed: Mar. 31, 2021. [Online]. Available: http://arxiv.org/abs/1812.04606.



## Proposed Training Method 
![image](https://user-images.githubusercontent.com/71545160/118598819-a943fc00-b7e9-11eb-96a4-a62e8dd6f55a.png)

## Results of the Proposed Methed
![image](https://user-images.githubusercontent.com/71545160/118599818-160bc600-b7eb-11eb-8532-247d2e4aca72.png)

