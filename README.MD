# Object Detection using Yolo

**Part A Notebook -**
[![Open Jupyter Notebook](Images/nbviewer_badge.png)](https://nbviewer.jupyter.org/github/SKrishna93/PPEDetectionYOLOv3/blob/main/EVA5S13_PartA.ipynb)

**Part B Notebook -**
[![Open Jupyter Notebook](Images/nbviewer_badge.png)](https://nbviewer.jupyter.org/github//SKrishna93/PPEDetectionYOLOv3/blob/main/EVA5S13_PartB.ipynb)

## Objective

### Part 1 (OpenCV Yolo)

1. Run the given code on own system [Source](https://pysource.com/2019/06/27/yolo-object-detection-using-opencv-with-python/)

2. Take an image of yourself, holding another object which is there in COCO data set (search for COCO classes to learn)

3. Run this image through the code above.

4. Share link to the implementation and the inferenced image.

### Part 2 (Dataset Annotation)

* Share the dataset annotated using [YoloV3 Annotation Tool](https://github.com/miki998/YoloV3_Annotation_Tool)

### Part 3 (Training Custom Dataset using YoloV3)
  
1. Train YoloV3 on the above self annotated dataset.

2. Download a very small video from Youtube which shows the classes.

3. Run inference on the video

# Part A Solution

* Loaded the pretrained yolo weights to the OpenCV Yolo Model
* Did inference on own image having COCO Class


# Part B Solution

* Implemented YoloV3 code
* Trained the model on 4 classes 
  * Hardhat
  * Mask
  * Boots
  * Vest
* Ran inference on a Youtube Video
  
## Hyperparameters

* Batch Size: 20
* Epochs: 70
* Augmentation: RICAP
  
## Train and Test Batches

<img src="Images/train_batch0.png" width="500px" height='500' float='left'>
<img src="Images/test_batch0.png" width="500px" height='500' float='right'>

## Result
<img src="Images/results.png" width = "800px">
<img src="Images/Result.PNG" width = "800px">
