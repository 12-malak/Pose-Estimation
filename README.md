## :running: :walking: :dancer: Pose-Estimation
![pose_with_action](https://user-images.githubusercontent.com/62059604/99776776-5db0de00-2b37-11eb-97e7-b39f53f2d703.gif)

![Untitled design (4)](https://user-images.githubusercontent.com/62059604/99800421-5818bf80-2b5a-11eb-83ad-c0fe6a2d48be.png)

![Untitled design (5)](https://user-images.githubusercontent.com/62059604/99800592-9e6e1e80-2b5a-11eb-8f70-4796dd0ee36a.png)

- This repository represents **" Action Recognition Using Alphapose "**.
- With the help of this project we can detect the human Actions/Activities based on the **Human Pose**.
  


## 🏽‍ Download Object Detection Model
- Download the object detection model manually : **yolov3-spp.weights** file from following Drive Link
- https://drive.google.com/file/d/1h2g_wQ270_pckpRCHJb9K78uDf-2PsPd/view?usp=sharing
- Download the weight file and Place it into **" detector/yolo/data/ "** folder.

##  🏽‍ For Pose Tracking, Download the object tracking model
- For pose tracking, download the object tracking model manually: **" JDE-1088x608-uncertainty "** from following Drive Link 
- https://drive.google.com/file/d/1oeK1aj9t7pTi1u70nSIwx0qNVWvEvRrf/view?usp=sharing
- Download the file and Place it into **" detector/tracker/data/ ".** folder.

## 🏽‍ Download Fast.res50.pt file
- Download the **" fast.res50.pth "** file from following Drive Link 
- https://drive.google.com/file/d/1WrvycZnVWwltSa6cjeTznEFOyNAwHEZu/view?usp=sharing
- Download the file and Place it into **" pretrained_models/ ".** folder.

## :desktop_computer:	Installation

### Requirements
* Python 3.5+
* Cython
* PyTorch 1.1+
* torchvision 0.3.0+
* Linux
* GCC<6.0, check https://github.com/facebookresearch/maskrcnn-benchmark/issues/25

## :gear: Setup
1. Install PyTorch :-
```bash
$ pip3 install torch==1.1.0 torchvision==0.3.0

```
2. Install :-
```bash
$ export PATH=/usr/local/cuda/bin/:$PATH

```
```bash
$ export LD_LIBRARY_PATH=/usr/local/cuda/lib64/:$LD_LIBRARY_PATH

```
```bash
$ pip install cython

```
```bash
$ sudo apt-get install libyaml-dev

```
```bash
$ python setup.py build develop --user

```
```bash
$ python -m pip install Pillow==6.2.1

```
```bash
$ pip install -U PyYAML

```


