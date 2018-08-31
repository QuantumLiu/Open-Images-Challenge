# Open-Images-Challenge
Object detection challenge on open images dataset

Open Images Challenge is an object detection challenge on a portion of the open images dataset consisting of 500 classes. The dataset for the competition uses 1.7M training images, 41K validation images. The challenge is evaluated using 100K test images. The total dataset is 0.6-0.7 TB. 

I used the Faster RCNN pretrained model to do object detection. I wrote code based on the object detection tutorial given with Tensorflow's Object Detection API. I used google cloud compute instances to process the data because of the huge quantities involved.

This requires Tensorflow's Object Detection API to run. It scores 0.36121 public score and 0.33093 private score on kaggle evaluation server.

Run frcnn1.py to run inference on 99999 images in the OID challenge2018 set.

Misc files are just files I used for experiments.
