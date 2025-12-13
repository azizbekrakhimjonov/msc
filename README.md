# Custom Object Detection (YOLOv8)

## 1. Install
python -m venv venv
source venv/bin/activate  (Windows: venv\Scripts\activate)
pip install -r requirements.txt

## 2. Collect images
Put images into:
dataset/images/train
dataset/images/val

## 3. Label images
labelImg
Format: YOLO
Save labels to dataset/labels/

## 4. Train model
python scripts/train.py

## 5. Detect
python scripts/detect.py
