# object-detection
paper list and slides for object-detection with deep learning


## Slides

* 2019/04/17 | __You only look once -- path to design a detector__ | [pptx](https://github.com/fwcore/object-detection/blob/master/YOLO.pptx) | [pdf](https://github.com/fwcore/object-detection/blob/master/YOLO.pdf)

* 2019/05/03 | __SSD: single shot detector__ | [pptx](https://github.com/fwcore/object-detection/blob/master/SSD.pptx) | [pdf](https://github.com/fwcore/object-detection/blob/master/SSD.pdf)

## Paper lists

* You Only Look Once: Unified, Real-Time Object Detection | [arXiv:1506.02640](arXiv:1506.02640)
	- YOLO v1
	- frame object detection as a __regression problem to spatially separated bounding boxes and associated class probabilities__

* YOLO9000: Better, Faster, Stronger | [arXiv:1612.08242](https://arxiv.org/abs/1612.08242)
	- YOLO v2
	- pre-defined anchors
	- bounded x, y, w, h, probability
	- darknet-19: lighter
	- pass-through
	- multi-scale training

* YOLOv3: An Incremental Improvement | [arXiv:1804.02767](https://arxiv.org/abs/1804.02767)
	- YOLO v3
	- slight improvement in accuracy
	- darknet-53: heavier
	- change loss function to cross-entropy with logistic regression for each class

* Optimizing the Trade-off between Single-Stage and Two-Stage Object Detectors using Image Difficulty Prediction | [arXiv:1803.08707](https://arxiv.org/abs/1803.08707) | SYNASC 2018
	- two-stage detectors, such as Faster R-CNN, reach the highest accuracy rates, but are typically slower.
	- single-stage detectors, such as YOLO and SSD, reach lower accuracy rates, but are much faster.
	- propose to use an image difficulty predictor to achieve an optimal trade-off between accuracy and speed in object detection: hard => two-stage, easy => single-stage.

* Large-Scale Object Detection of Images from Network Cameras in Variable Ambient Lighting Conditions | [arXiv:1812.11901](https://arxiv.org/abs/1812.11901) | MIPR 2019
	- examine YOLO's ability to detect objects in different scenarios (e.g., daytime vs. night), leveraging the cameras' ability to rapidly retrieve many successive images for evaluating detection consistency
	- YOLO struggles to consistently detect the same humans and cars as their positions change from one frame to the next
	- it also struggles to detect objects at night time

* Object Detection with Deep Learning: A Review | [arXiv:1870.05511](https://arxiv.org/abs/1807.05511)


## Read/Watch further

* TED talk on YOLO: [How computers learn to recognize objects instantly | Joseph Redmon](https://www.youtube.com/watch?v=Cgxsv1riJhI)

* YOLO v2 | YOLO Object Detection | [Youtube](https://www.youtube.com/watch?v=VOC3huqHrss)

* YOLO v3 | Joseph Redmon | [Youtube](https://www.youtube.com/watch?v=MPU2HistivI)

* Siraj Raval's [Youtube video](https://www.youtube.com/watch?v=4eIBisqx9_g) on YOLO, and its [Github repo](https://github.com/llSourcell/YOLO_Object_Detection). It covers a brief history of object detection before deep learning era.

* Real-time Object Detection with YOLO, YOLOv2 and now YOLOv3 | [Medium 2018]

* [OpenVINO-YoloV3](https://github.com/PINTO0309/OpenVINO-YoloV3)

* [The Modern History of Object Recognition -- Infographic](https://medium.com/@nikasa1889/the-modern-history-of-object-recognition-infographic-aea18517c318)
