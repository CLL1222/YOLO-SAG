YOLO-SAG re-implementation using PyTorch

### Installation

```
pip install -r requirements.txt
```

### Train

* Configure your dataset path in `train.py` for training
* Run `yolo train model=yolov8n.pt/YOLO-SAG.pt data=$.yaml epochs=150 imgsz=640 batch=16` for training

### Val

* Configure your dataset path in `val.py` for testing
* Run `yolo val model = yolov8n.pt/YOLO-SAG.pt data = $.yaml` for valing

`$` represents the name of the yaml file

The model can autonomously choose between yolov8n.pt or YOLO-SAG.pt.

#### Reference

* https://github.com/ultralytics/ultralytics
