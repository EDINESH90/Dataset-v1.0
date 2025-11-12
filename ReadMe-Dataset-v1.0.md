==========================================
  CAR PARKING LOT DATASET - Version 1.0
==========================================

Dataset Overview
----------------
This dataset is created for car parking lot detection and analysis tasks.
It contains 50 images and 50 corresponding annotation files.
The annotations are formatted for YOLO-based object detection models.

------------------------------------------
Folder Structure
------------------------------------------
HP-PK-DS-TrV1.0/
│
├── images/          -> 50 parking lot images
│     ├── img_001.jpg
│     ├── img_002.jpg
│     └── ...
│
├── labels/          -> 50 YOLO-format annotation files
│     ├── img_001.txt
│     ├── img_002.txt
│     └── ...
│
└── ReadMe-HP-PK-DS-TrV1.0.txt


------------------------------------------
Annotation Format
------------------------------------------
Each .txt file in the "labels" folder follows the YOLO format:

<class_id> <x_center> <y_center> <width> <height>

All values are normalized between 0 and 1
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
- Total Images: 50
- Total Labels: 50
- Image Resolution: Variable (typically resized to 640x640 for training)
- Image Format: JPG
- Annotation Format: YOLO (.txt)


------------------------------------------
Purpose of the Dataset
------------------------------------------
- Car and parking slot detection
- Parking occupancy analysis
- Model training and evaluation for AI-based parking management systems


------------------------------------------
Version History
------------------------------------------
Version : v1.0
Content : 50 images + 50 annotations
Date    : YYYY-MM-DD
Notes   : Initial release of car parking lot dataset


------------------------------------------
Credits / Notes
------------------------------------------
This dataset was manually curated and annotated for research and development use.
Use it for academic and industrial AI applications related to parking lot management.


==========================================
END OF FILE
==========================================

