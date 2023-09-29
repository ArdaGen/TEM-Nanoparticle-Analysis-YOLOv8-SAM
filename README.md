## S/TEM-Nanoparticle-Analysis-YOLOv8-SAM

![Flow](https://github.com/ArdaGen/STEM-Nanoparticle-Analysis-YOLOv8-SAM/assets/86938894/16041fa4-d9cc-4cea-bba4-60c2d1bcdc13)


<br>
Repository for automated nanoparticle analysis using [YOLOv8](https://github.com/ultralytics/ultralytics) and [segment anything model (SAM)](https://github.com/facebookresearch/segment-anything) in Scanning Transmission Electron Microscopy images.
This material-agnostic ML workflow successfully detects and segments nanoparticles on different catalytic substrate materials.

## Scripts
* **Velox emd** <br>
  Read Velox S/TEM images and metadata
* **Detector** <br>
  Run YOLOv8 on the S/TEM images and generate box prompts <br>
  Generate masks using SAM
* **SAM visualize** <br>
  Visualize segmentations
* **Analysis** <br>
  Particle size and area distribution
## Model weights
Weights for YOLOv8 S/TEM nanoparticle object detection <br>
https://drive.google.com/file/d/18dHxlF30ZkPLlikhx7hBWgXhLkpwIk8v/view?usp=sharing

Weights for SAM <br>
https://drive.google.com/file/d/1iYPrlGzIoN8-sfg2khJIP6mGgFDSNP4-/view?usp=sharing 
<br>
<br>
## Installation
Install [PyTorch](https://pytorch.org/get-started/locally/)
<br>
<br>
Install ultralytics for YOLOv8
```
pip install ultralytics
```
Install segment anything model (SAM)
```
https://github.com/facebookresearch/segment-anything
```


https://github.com/ArdaGen/TEM-Nanoparticle-Analysis-Yolov8-SAM/assets/86938894/58c43ba5-14b6-4961-be76-50267595c13c





