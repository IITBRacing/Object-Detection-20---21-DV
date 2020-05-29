
### TESTING:

1) The trained weights file shoud be added here 
2) The custom configuration file yolov3-custom.cfg created while training has to be added here
3) detect.py takes pictures from directory specified in line 16 in its code
```python
#images_path = glob.glob(r"address of image directory/*.jpg")
images_path = glob.glob(r"/home/afreed/Desktop/CNN/cones/cone_detection/*.jpg")
```

1) .weights file should be added in this directory to run this detect.py code
2) .weights file will be generated in the same folder in the google drive, after the training is done in  google  colab
3) detect.py will load pictures from a directory because it makes easy to test the trained net
4) Refer to line 16, in [detect.py](https://github.com/IITBRacing/Object-Detection-20---21-DV/blob/master/training/detect.py) to change the directory

