# yolov4-deepsort
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1fe17ThS0sKWpdDFITD9qyKdw-yV3tyUc?usp=sharing)

Object tracking implemented with YOLOv4, DeepSort, and TensorFlow. YOLOv4 is a state of the art algorithm that uses deep convolutional neural networks to perform object detections. We can take the output of YOLOv4 feed these object detections into Deep SORT (Simple Online and Realtime Tracking with a Deep Association Metric) in order to create a highly accurate object tracker.

## Demo of Object Tracker on Persons
<p align="center"><img src="outputs/demo1.gif"\></p>
Here, other objects like bicycle and suitcase are also been detected and tracked.

## Demo of Object Tracker on Cars
<p align="center"><img src="data/helpers/cars.gif"\></p>

### Demo of Object Tracker set to only track the class 'person'
<p align="center"><img src="data/helpers/demo.gif"\></p>
Here, only persons are been detected and tracked.

### References
  * [Deep SORT Repository](https://github.com/nwojke/deep_sort)
