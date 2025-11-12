==========================================
  CAR PARKING LOT DATASET - Version 1.1
==========================================

Dataset Overview
----------------
This dataset is created for car parking lot detection and analysis tasks.
It contains a total of 100 images and 100 corresponding annotation files.
Version 1.1 includes an additional 50 new images and annotations
added to the existing Version 1.0 dataset.

The annotations are in YOLO format and suitable for object detection models.

------------------------------------------
Folder Structure
------------------------------------------
HP-PK-DS-TrV1.1/
│
├── images/          -> 100 parking lot images
│     ├── img_001.jpg
│     ├── img_002.jpg
│     ├── ...
│     └── img_100.jpg
│
├── labels/          -> 100 YOLO-format annotation files
│     ├── img_001.txt
│     ├── img_002.txt
│     ├── ...
│     └── img_100.txt
│
└── ReadMe-HP-PK-DS-TrV1.1.txt


------------------------------------------
Annotation Format
------------------------------------------
Each .txt file in the "labels" folder follows the YOLO format:

<class_id> <x_center> <y_center> <width> <height>

All coordinate values are normalized (0 → 1)
relative to the image width and height.

Example:
0 0.5234 0.6112 0.2156 0.1789
1 0.7452 0.5328 0.1523 0.1334


------------------------------------------
Class Information
------------------------------------------
Class ID | Class Name
----------------------
0        | Car
1        | Parking Slot
2        | Occupied Area (if applicable)


------------------------------------------
Image Information
------------------------------------------
- Total Images: 100
- Total Labels: 100
- Image Resolution: Variable (commonly resized to 640x640 for model training)
- Image Format: JPG
- Annotation Format: YOLO (.txt)


------------------------------------------
Version Details
------------------------------------------
Version  | Description                                  | Total Files | Date
---------------------------------------------------------------------------
v1.0     | Initial dataset with 50 images + 50 labels   | 100 files   | YYYY-MM-DD
v1.1     | Added 50 new images + 50 new labels          | 200 files   | YYYY-MM-DD


------------------------------------------
Purpose of the Dataset
------------------------------------------
- Car and parking slot detection
- Parking occupancy estimation
- Object detection model development and benchmarking
- Research on automated parking management systems


------------------------------------------
Notes
------------------------------------------
- The dataset has been manually annotated for improved accuracy.
- All images are real-world parking lot scenarios captured under
  various lighting and environmental conditions.


------------------------------------------
Credits / Acknowledgment
------------------------------------------
Dataset Version: HP-PK-DS-TrV1.1

------------------------------------------
END OF FILE
==========================================
