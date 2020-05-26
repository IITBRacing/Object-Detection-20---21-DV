### TRAINING:
  Upload TrainYoloV3.ipynb notebook on google colab, make sure to change the directory in the code or maintain the same names (yolov3/images.zip). After Authentication at step-2 let the training file run till the avg.loss is less than 0.1
  
  Use [yolov3_testing.cfg](https://github.com/IITBRacing/Object-Detection-20---21-DV/blob/master/training/yolov3_testing.cfg) with detect.py 
  
### TESTING:

1) .weights file should be added in this directory to run this detect.py code
2) .weights file will be generated in the same folder in the google drive, after the training is done in  google  colab
3) detect.py will load pictures from a directory because it makes easy to test the trained net
4) Refer to line 16, in [detect.py](https://github.com/IITBRacing/Object-Detection-20---21-DV/blob/master/training/detect.py) to change the directory
