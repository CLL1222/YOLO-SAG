YOLO-SAG re-implementation using PyTorch

### Installation

```
pip install -r requirements.txt
```

### Train

* Configure your dataset path in `train.py` for training
* Run `yolo train model=yolov8n.pt data=$.yaml epochs=150 imgsz=640 batch=16` for training, `$` represents the name of the yaml file.

### Val

* Configure your dataset path in `val.py` for testing
* Run `yolo val model = yolov8n.pt data = $.yaml` for testing, `$` represents the name of the yaml file.


#### Reference

* https://github.com/ultralytics/ultralytics
