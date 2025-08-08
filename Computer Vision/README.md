I took a Computer Vision course as part of my Master's degree in Data Science @ Maastricht University. 

The [course](https://courserepository.maastrichtuniversity.nl/p/module/EN/9602/KEN4255) began with foundational computer vision techniques—image processing, feature detection, tracking, and geometric transformations—before progressing to modern deep learning approaches, including neural networks and transformers. It covered key methods for enabling machines to interpret visual data, with applications in autonomous navigation, object recognition, and human interaction. It had two assignments that are explained below:

[Image Stitching](https://drive.google.com/file/d/1gelXlBVJP6xVnWR-0MiCCjzoSMt8G9hi/view?usp=sharing): (Individual Project)

- Used Harris corners and SIFT features,  2 distance metrics to match features in two image halves (Left, Right)
- Implemented the RANSAC algorithm from scratch, to improve matches and estimate transformation matrix 
- Stitched / combined both images to create one panorama 
- Performed ablation study to understand the effect of different hyperparameters (# of matched points, distance metrics, inlier - threshold, # of iterations, # of points used for estimation)

[Generalized DeepFakes](https://drive.google.com/file/d/18lA3Rd7fmPsQhwGO3sI4M5_nDAWWKbVQ/view?usp=sharing): (Group Project)

- Created [custom dataset](https://www.kaggle.com/datasets/datasriram/computer-vision-assignment-2) that combines DeepFakes from multiple generation techniques 
- Tested 5 deep learning techniques (VGG16, Resnet18, EffecientNet, ViT, DINOv2) on previously seen and unseen DeepFake generation techniques 
- Confirmed results from research literature ; transformer based models generalize better than neural network based method 
- Responsible for hypothesis, dataset creation, training script for DINOv2 and testing script for all models 
