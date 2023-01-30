[Original repo](https://github.com/ultralytics/yolov5/tree/v7.0)

# yolov5r7 with MLflow support

This is yolov5 v7.0, with added mlflow support.

## Usage

1. Run `train.py`, `detect.py`, `segment/train.py` etc. as you normally would.

2. There will be a resulting `mlruns` directory that resides under `yolov5`.

3. Under `yolov5`: Run `mlflow ui` and open the UI from your browser.
