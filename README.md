# Mask_RCNN for Object Detection

1. Mask_RCNN library cloned from

!git clone https://github.com/matterport/Mask_RCNN.git


2. Kangaroo Object Detection cloned from

!git clone https://github.com/experiencor/kangaroo.git


3. Python code: **Mask_R_CNN_Kangaroo.ipynb**

Follow step by step in the Mask_R_CNN_Kangaroo.ipynb.

First, clone the Mask_RCNN library. Install the libary and verify installation. 

Next, install the Kangaroo dataset, parse annotation files and create a dataset object

Third step is to create a Mask R-CNN model, using pretrained weights on MS COCO dataset. 

In training, we can choose to train the head layers only or all layers. This is documented in the code.

Output

1. able to detect kangaroos in photos (from train/test set, or from random online sources)

2. Get confused by photos of topless soccer players due to similarity in photo color and shape.

Metrics: Train mAP: 0.882; Test mAP:  0.922

This notebook was made based on the link below

https://machinelearningmastery.com/how-to-train-an-object-detection-model-with-keras/

Also, see Matterport Github (cloned in first step) for more information.
