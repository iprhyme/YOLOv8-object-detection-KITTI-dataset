# YOLOv8-object-detection-KITTI-dataset
📋 Project Overview
The project follows a structured pipeline for data preparation, model training, and evaluation:

Dataset Preparation:

The KITTI dataset, a widely recognized benchmark in autonomous driving research, was utilized.
Classes include: Car, Van, Truck, Pedestrian, Sitting Person, Cyclist, Tram, and Miscellaneous.

Preprocessing and Augmentation:

Data split: 80% training and 20% validation.
Data augmentation were applied for improved model generalization.

Label Conversion for YOLOv8:

Labels were converted from KITTI format to YOLOv8 format (class label, x-center, y-center, width, height) with normalization.

Model Training:

Utilized YOLOv8n architecture.
Key parameters:
200 epochs
Adam optimizer
Learning rate set to 0.0001 with dropout of 0.2 for better regularization.

Results:

Precision: 89.6%
Recall: 81.3%
mAP50: 89.6%
The model demonstrated strong performance on unseen data, ensuring robustness for real-world applications.
