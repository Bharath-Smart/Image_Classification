# Image_Classification

In this project, I have used dataset of Plant Pathology 2020 - FGVC7 from Kaggle. 
### Description
#### Problem Statement
Misdiagnosis of the many diseases impacting agricultural crops can lead to misuse of chemicals leading to the emergence of resistant pathogen strains, increased input costs, and more outbreaks with significant economic loss and environmental impacts. Current disease diagnosis based on human scouting is time-consuming and expensive, and although computer-vision based models have the promise to increase efficiency, the great variance in symptoms due to age of infected tissues, genetic variations, and light conditions within trees decreases the accuracy of detection.

#### Specific Objectives
Objectives of ‘Plant Pathology Challenge’ are to train a model using images of training dataset to:
1) Accurately classify a given image from testing dataset into different diseased category or a healthy leaf
2) Accurately distinguish between many diseases, sometimes more than one on a single leaf
3) Deal with rare classes and novel symptoms
4) Address depth perception—angle, light, shade, physiological age of the leaf
5) Incorporate expert knowledge in identification, annotation, quantification, and guiding computer vision to search for relevant features during learning.

#### Conclusion
1) Trained with Resnet50 on 5000 images with custom data loader, augmentation functions using GPU accelerators
2) Achieved 0.9 AUROC score when tested on 2000 images using the pretrained model & fine tuning the final layers

![image](https://github.com/Bharath-Smart/Image_Classification/assets/84274467/9f6292d9-d924-41ab-90fa-5cd3fe33ae76)

![image](https://github.com/Bharath-Smart/Image_Classification/assets/84274467/69e4080c-9c01-481c-a5c4-b437360cd2c0)

