# MultiObject_Tracking using [ByteTrack](https://github.com/ifzhang/ByteTrack) Combined with [RetinaNet](https://github.com/facebookresearch/detectron2/blob/main/MODEL_ZOO.md#retinanet)
Tracking Bolts and Nuts in real time using ByteTrack  Combined with RetinaNet_ResNet50+FPN from detectron2 as object detector.

## Why ByteTrack ?

as the challenge was about Multi Object Tracking, (object detector followed by tracker), it was necessary to look  for sota of [MOT approaches](https://paperswithcode.com/paper/bytetrack-multi-object-tracking-by-1)  in papers with code and ByteTracker was among it.

## Why RetinaNet ?

- to avoid copypasting tutorials that combines yolo with  ByteTrack 
- a non-complex model from my comfort zone to save time in implementation
- can do the job


## Cusomized Codes

- the original **export_model.py** is from detectron2 [repo](https://github.com/facebookresearch/detectron2/tree/main/tools/deploy)

- the original **onnx_inference.py** is from BYTETRACK [repo](https://github.com/ifzhang/ByteTrack/tree/main/deploy/ONNXRuntime) 

## Challeneges

Limited acces to gpu on colab that imposed training the model for only 3 epochs (6 continuous hours).

## Visual result

<img src='https://github.com/Sahar-DataScience/MultiObject_Tracking-StromaVsion/blob/main/result4.gif' width='60%'/>

