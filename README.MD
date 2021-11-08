# CalTrans Project Learning Model Environment  
Description:  
This is the demo version of the CalTrans Project real-time vehicle detection part  
This version can process the video stream from the camera and detect the vehicles  
Environment is based on the [opencv-python](https://opencv-python-tutroals.readthedocs.io/en/latest/) [numpy](https://www.numpy.org/), and [Flask](https://flask.palletsprojects.com/en/1.1.x/).  
Dowload [yolov3 weights](https://pjreddie.com/media/files/yolov3.weights), and save [yolov3.cfg](https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg?raw=true) and [coco.names](https://github.com/pjreddie/darknet/blob/master/data/coco.names)  
Place the yolov3.weights, yolov3.cfg, and coco.names in the same folder as the python script.  
Install run the following command:  
`pip install flask`  
`pip install opencv-python`  
`pip install numpy`  
Clone the repository:  
`git clone https://github.com/RuitaoWu/CalTransProjLearningModel.git`  
`cd CalTransProjLearningModel`  
`python3 app.py`  
---  
Working Tree update  
```  
C:.  
│   .gitignore  
│   app.py  
│   coco.names  
│   model.py  
│   objRealTimeDectector.py  
│   README.MD  
│   sample.MP4  
│   ssd-ream-time.py  
│   yolov3.cfg  
│   yolov3.weights  
│
├───templates  
│       index.html  
```  