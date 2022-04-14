## Citation
Mimura, K., Minabe, S., Nakamura, K., Yasukawa, K., Ohta, J., Kato, Y. Automated detection of microfossil fish teeth from slide images using combined deep-learning models. *submitted to Computers & Geosciences*

# About
**eNetV2_for_ai_ichthyolith** reclassifies regions detected by the object detection model Mask R-CNN using the image classification model EfficientNet-V2. The codes use outputs of [ai_ichthyolith](https://github.com/KazuhideMimura/ai_ichthyolith), an application of Mask R-CNN for detection of microfossils, to minimalize manual work.

# How to use
All the codes are for Google Colaboratory

## training and validation
1. collect images of each class 

# References
He, K., Gkioxari, G., Dollár, P., & Girshick, R. (2017). Mask r-cnn. *In* Proceedings of the IEEE international conference on computer vision (pp. 2961-2969). [[GitHub](https://github.com/matterport/Mask_RCNN)] [[paper](https://openaccess.thecvf.com/content_iccv_2017/html/He_Mask_R-CNN_ICCV_2017_paper.html)]

Tan, M., & Le, Q. (2021, July). Efficientnetv2: Smaller models and faster training. *In* International Conference on Machine Learning (pp. 10096-10106). PMLR. [[GitHub](https://github.com/google/automl/tree/master/efficientnetv2)] [[paper](http://proceedings.mlr.press/v139/tan21a.html)]

## Dataset availability
Training, validation datasets are temporally available at Author's [Google Drive](https://drive.google.com/drive/folders/1QC7deWgQRFkoDdOLao3SatYC6TO4moeT?usp=sharing).

# notes
## log
2022/4/14: released

## Todo
1. confirmation of operation
2. describe # How to use
3. translate Japanese comments to English. 
