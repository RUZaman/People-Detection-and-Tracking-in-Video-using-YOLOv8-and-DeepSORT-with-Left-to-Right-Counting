<H1 align="center">
People Detection and Tracking in Video using YOLOv8 and DeepSORT with Left to Right Counting  </H1>

https://www.youtube.com/watch?v=EV-dmxfP-l4


## Steps to run Code
- Create a new conda environment with Python 3.8,python 3.9 and activate this environment
```
conda create -n yolov8 python=3.8
conda activate yolov8
```
- Clone the repository
```
git clone https://github.com/noorkhokhar99/People-Detection-and-Tracking-in-Video-using-YOLOv8-and-DeepSORT-with-Left-to-Right-Counting.git
```
- Goto the cloned folder.
```
cd People-Detection-and-Tracking-in-Video-using-YOLOv8-and-DeepSORT-with-Left-to-Right-Counting
```

- Setting the Directory.
```
cd detect

```
- donwload from here https://github.com/noorkhokhar99/Real-Time-Object-Segmentation-and-Tracking-using-YOLOv8-Vehicles-Counting/tree/main/deep_sort_pytorch deep_sort_pytorch and put folder detect


- For yolov8 object detection + Tracking + people Counting

```
python predict.py model=yolov8l.pt source="PETS09-S2L2-raw.mp4" show=True

```

### RESULTS

<p align="center">
<img src="https://github.com/noorkhokhar99/People-Detection-and-Tracking-in-Video-using-YOLOv8-and-DeepSORT-with-Left-to-Right-Counting/blob/main/Quick%20thumbnail%20Ideas.png">
</p>






### Inference on a video:
https://www.youtube.com/c/pyresearch


