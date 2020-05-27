Inorder to train a network on local PC, 

## Cloning darknet :
  First clone and make darknet at any directory on your PC from
  ```
   git clone https://github.com/pjreddie/darknet
   cd darknet
   make
```
  Once that’s successful, To test the build we can download pre trained YOLO weights and perform detection with the test image.
  ```
  ./darknet detector test cfg/coco.data cfg/yolov3.cfg yolov3.weights data/dog.jpg
```

## Creating dataset :
   Create a dataset same as the one created for google colab, with pics and corresponding .txt annotation file.   
