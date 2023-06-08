# intel-oneAPI

#### Team Name - Hackie bits
#### Problem Statement - The challenge is to develop a real-time object detection model for autonomous vehicles using computer vision techniques and Intel® AI Analytics Toolkits its libraries, and SYCL/DPC++ Libraries.
#### Team Leader Email - ayushsonone27@gmail.com

## A Brief of the Prototype:
Datasets drive vision progress, yet existing driving datasets are limited in 
terms of visual content, scene variation, the richness of annotations, and the geographic 
distribution and supported tasks to study multitask learning for autonomous driving the 
images for "other vehicle", "pedestrian", "traffic light", "traffic sign", "truck", "train", "other 
person", "bus", "car", "rider", "motorcycle", "bicycle", "trailer” can be used for training. Goal is 
to detect and classify traffic objects in a video in real-time using two approaches. We can 
train the two state-of-the-art models YOLO and Faster R-CNN on the Berkeley DeepDrive 
dataset to compare their performances and achieve a comparable mAP to the current state.

## Tech Stack: 
Model zoo Intel architecture pre trained models from oneApi Ai 
Analytics Toolkit used here for computer vision.
YOLOv4 Algorithm
python openCV
python numpy
##intel oneDNN toolkit
   
## Step-by-Step Code Execution Instructions:
1. pip install openCV
2. pip install numpy
3. cd oneDNN
4. mkdir build && cd build
5. !cmake /content/oneDNN
6. !make -j$(nproc)
7. pip install onednn-cpu-gomp
8. pip install onednn-cpu-tbb

## What I Learned:
   Learnt about AI ML and technologies used here which is most beneficial now, and also learned how to improve previous versions. 
