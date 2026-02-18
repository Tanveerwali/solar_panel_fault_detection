Solar Panel Fault Detection – Bird Droppings (YOLOv11)

This project demonstrates object detection of bird droppings on solar panels using YOLOv11.
It is a small-scale, portfolio-focused project intended for learning and experimentation.

📌 Project Overview

Model: YOLOv11 (Ultralytics)

Task: Object Detection

Primary Class: bird_drop

Annotation Tool: CVAT

Training Environment: Google Colab

Due to limited data, the model focuses on one reliable class (bird droppings) rather than multiple fault types.

🏷 Dataset & Annotation

Total Images: 99

Total Labels: 99

Classes Used:

bird_drop

Annotation Format: YOLO

Annotation Tool: CVAT

⚠️ The dataset is intentionally small and was created for educational and portfolio purposes, not production use.

All bounding boxes were manually annotated in CVAT and exported in YOLO format.


🧠 Model Training

Epochs: 50

Image Size: 640 × 640

Optimizer: Auto (Ultralytics default)

Loss: YOLOv11 detection loss

Training was performed on Google Colab using a custom dataset.


⚠️ Limitations

Small dataset size

Single-class detection

Possible false positives on visually similar faults

Not suitable for real-world deployment


🚀 Future Improvements

Increase dataset size

Add additional classes:

electrical_damage

physical_damage

Improve bounding box tightness

Train with class-balanced data

Evaluate with mAP metrics


🧪 Tools & Technologies

Python

YOLOv11 (Ultralytics)

CVAT

Google Colab

OpenCV

📎 Disclaimer

This project is for learning and portfolio demonstration only.
It does not represent a production-ready solar fault detection system.
