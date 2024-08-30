<H1 align="center">
YOLOv8 Segmentation with DeepSORT Object  </H1>

## Steps to run Code

- Clone the repository.
```
git clone
```
- Goto the cloned folder.
```
cd YOLOv8_Segmentation_DeepSORT_Object_Tracking
```
- Install the Dependencies
```
pip install -e '.[dev]'

```
- Setting the Directory
```
cd ultralytics/yolo/v8/segment

```
- Downloading the DeepSORT Files 
```

https://drive.google.com/drive/folders/1kna8eWGrSfzaR6DtNJ8_GchGgPMv3VC8?usp=sharing
```
- After downloading the DeepSORT Zip file from the drive, unzip it go into the subfolders and place the deep_sort_pytorch folder into the ultralytics/yolo/v8/segment folder

- Downloading a Sample Videos from the Google Drive
- Demo Video 1
```
gdown "https://drive.google.com/uc?id=19P9Cf9UiJ9gU9KHnAfud6hrFOgobETTX"
```

- Demo Video 2
```
gdown "https://drive.google.com/uc?id=1rjBn8Fl1E_9d0EMVtL24S9aNQOJAveR5&confirm=t"
```

- Run the code with mentioned command below.

- For yolov8 segmentation + Tracking
```
python predict.py model=yolov8x-seg.pt source="test1.mp4"
```

### RESULTS

#### Object Segmentation and DeepSORT Tracking (ID + Trails) and Vehicles Counting
![](./ultralytics/figure_speed.png)

#### Object Segmentation and DeepSORT Tracking (ID + Trails)

![](./ultralytics/figure2.png)

### Watch the Complete Step by Step Explanation

- Video Tutorial Link  [`YouTube Link`](https://www.youtube.com/watch?v=0JIPNk21ivU)


[![Watch the Complete Tutorial for the Step by Step Explanation](https://img.youtube.com/vi/0JIPNk21ivU/0.jpg)]([https://www.youtube.com/watch?v=0JIPNk21ivU&t=244s](https://www.youtube.com/watch?v=0JIPNk21ivU))


## References
- https://github.com/ultralytics/ultralytics
