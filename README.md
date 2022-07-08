# Artificial-Neural-Network
**Object Detection using R-CNN**  
The main objective is to detect the ships in satellite images. Dataset is made up of 4000 80x80 RGB photos labeled with "ship" or "no-ship" classifications and saved as a 19200-item list. These images were extracted from ‘Planet satellite imagery collected over the San Francisco Bay and San Pedro Bay areas of California’.  

Dataset : [Ships in Satellite Imagery](https://www.kaggle.com/datasets/rhammell/ships-in-satellite-imagery)

# Summary of the Model
![image](https://user-images.githubusercontent.com/67818318/177931042-69d5750e-21fe-4ff2-acdc-ecfa73af8d79.png)

Multi-step approach in R-CNN:
* Generate region proposals: selective search
* classify the content of the region proposals within a refined bounding box.


# Implementation of RCNN

**Main steps process to implementing an R-CNN object detector:**
1. Build an object detection dataset using Selective Search : data_preprocessing  
2. Apply rcnn algorithm :
 * Basic RCNN based on region proposal
 * RCNN using bounding box regression



**Basic RCNN implementation in detail:**  

![image](https://user-images.githubusercontent.com/67818318/177929852-83bb395a-e810-42b1-8c92-72fdbdb88ed6.png)


