# Gun_Object_Detection

We are  excited to share that our paper has been published on arXiv! 🎉 You can check it out here: [Gun Detection Using Combined Human Pose and Weapon Appearance](http://arxiv.org/abs/2503.12215)

### Dataset Overview

Below is a breakdown of the image counts from various sources in our final dataset:

| **Datasource**       | **Number of Images** |
|----------------------|----------------------|
| IMFDB               | 150                  |
| Monash Guns        | 100                  |
| Real-time CCTV images | 100                  |
| GenAI prompts      | 100                  |
| Benign             | 50                   |
| Roboflow           | 9000                 |
| **Total Images**    | **9500**             |

Annotation Tool - VGG Image Annotator (https://www.robots.ox.ac.uk/~vgg/software/via/via.html)


### Working Notebook 
    November_4.ipynb

### Pre-Req files
    utils.py 
    coco_eval.py
    coco_utils.py
    Data_class.py
    engine.py
    transforms.py

### Requirements
    requirements.txt

### Instructions
    November_4.ipynb - notebook contains the path to train the model, save it and get the prediction results with the saved model. 
    Saved model is not provided here due to memory constraints. This repo can be cloned in order to use this Faster-RCNN model to fine tune your custom dataset. 

