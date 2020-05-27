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
   
   - create a directory darknet/data/obj and put all the images and .txt files in this directory
 
## Configuring :
   - Find darknet/cfg/yolov3.cfg file 
   - Copy and paste it in the same directory with the name yolov3-custom.cfg
### Editing yolov3-custom.cfg :
  ![](https://github.com/IITBRacing/Object-Detection-20---21-DV/blob/master/training/train_local/pics/1.jpg)
  
  Make sure that the Training is uncommented and testing is commented in the .cfg file
  and the subdivision is set to 16 by default and incase your machines runs out of memory change it to 32.
 
   
   
   
