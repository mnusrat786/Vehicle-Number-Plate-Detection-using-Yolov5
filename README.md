# Vehicle Number Plate Detection using YOLOv5

This project implements vehicle number plate detection using the YOLOv5 object detection framework.

## Dataset

- The dataset was collected from an **IP camera feed**.
- All images were manually annotated using **LabelImg** in YOLO format.
- The dataset was then split into training and validation sets.

## Model

- The YOLOv5 model was used for training and inference.
- Training was done using the official YOLOv5 repository with default settings and custom dataset configurations.

## Project Structure

- `annotations/` – YOLO-format label files  
- `coco/` – Dataset structure following COCO-like format  
- `runs/train/` – YOLOv5 training logs and checkpoints  
- `yolov5-master/` – Cloned YOLOv5 repository  
- `train_valid_split_yolov5.py` – Script used to split data into training and validation sets  
- `Results/` – Detection results and sample outputs  

## Getting Started

1. Clone this repository.
2. Place your annotated dataset in the appropriate directory.
3. Use the YOLOv5 training pipeline to start training.
4. Run inference using the trained weights to detect number plates in real-time or from images.

---

This project was created as a practical experiment to learn real-time object detection workflows using custom data and YOLOv5.


# Results
![image](https://github.com/mnusrat786/Vehicle-Number-Plate-Detection-using-Yolov5/assets/45511078/e9cdc4ca-7c8d-445c-8ec9-742203e8c815)
![image](https://github.com/mnusrat786/Vehicle-Number-Plate-Detection-using-Yolov5/assets/45511078/a3fa3dc4-e10d-4e66-9ba1-fdf911c8e9ed)


