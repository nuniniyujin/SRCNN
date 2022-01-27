# Super-resolution with deep learning
* Survey made about Super resolution state of the art architecture.
* Please check : SRCNN/Deep_learning_super_resolution_survey.pdf

## SRCNN

* SRCNN architecture : 
* Implementation of SRCNN by matlab :
![image](https://user-images.githubusercontent.com/80272042/151383045-d22eeaab-ec50-40b4-9b69-9d22e4714000.png)


Super resolution is to recover Low resolution images to Highresolution  images,  but  there  are  many  ways  to  recover  indifferent way. It is called Regular Inverse Problem or ill-PosedProblem that there are no unique answers as shown in Figure 1.SRCNN(Super-Resolution  Convolutional  Network)  is  thefirst  convolutional  neural  network  proposed  by  Dong  to  dealwith  Single  Image  Super  Resolution(SISR)  in  2014.  At  thetime when CNN was just introduced, so only 3 convolutionallayers  were  used  without  stacking  hundreds  of  layers,  andit  showed  higher  performance  values  compared  to  methodswithout   deep   learning.   (Figure   2).   This   study   shows   thepossibility  that  deep  learning  can  be  applied  to  the  super-resolution field as well. When constructing an architecture, themeaning  of  each  convolutional  layer  is  interpreted  in  termsof  traditional  super-resolution,  and  each  layer  is  in  chargeof  patch  extraction,  non-linear  mapping,  and  reconstruction.From  a  given  low  resolution  image,  first  convolution  layerextracts feature maps. The Second layers map non linearly tohigh  resolution  patch  problems.  The  last  layer  combines  theprediction to produce high-resolution output.

![image](https://user-images.githubusercontent.com/80272042/151383954-de80abcd-dd90-424c-92c3-7e5b0c5c96a3.png)

![image](https://user-images.githubusercontent.com/80272042/151384082-11e79b4a-3205-4214-939f-bff87cdd1c47.png)



Matlab DEMO file for SRCNN Architecture based on paper : 
C. Dong, C. C. Loy, K. He, and X. Tang, “Learning a deep convolutional network for image super-resolution,” in Proceedings of the European Conference on Computer Vision, 2014.
