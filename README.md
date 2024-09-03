# Final-Year-Project
The aim of this project is to create an advanced object recognition system for 3D point cloud data from LiDAR sensors that uses the YOLO architecture to properly identify and localize items in 3D space, such as automobiles and pedestrians. Using the KITTI dataset, it extends the YOLO model, which was originally built for 2D photos, to handle 3D data by transforming LiDAR point clouds into Bird's Eye View (BEV) maps and altering the architecture to anticipate 3D bounding boxes. The model is trained using data augmentation and transfer learning approaches to improve detection accuracy. Post-processing refines bounding boxes and improves categorization, with performance measured by Intersection over Union (IoU) and mean Average Precision (mAP). The system aims for real-time detection and high accuracy, addressing issues such as small object detection and efficient processing of sparse 3D data.

### Project objective
1) Develop and implement a robust system to accurately detect and locate basic objects within a point cloud using advanced object detection algorithms.
2) Explore and evaluate various feature extraction techniques such as PointNet++, RCNN variants, voxelization, and cutting-edge object detection algorithms like Complex YOLO and 3D YOLO.
3) Optimize the model for real-time or near-real-time performance, ensuring its practical deployment in busy parking lots or urban environments.

### Methodology
1) Data Collection: Use the KITTI dataset, which provides annotated 3D point cloud data from LiDAR sensors, ensuring comprehensive coverage and high-quality annotations.
2) Data Preprocessing: Convert the 3D point cloud into a Bird's Eye View (BEV) map, normalize data, and align existing annotations to the processed point clouds.
3) Model Adaptation: Modify the YOLO architecture to handle 3D data, incorporating features such as 3D bounding box regression, and adapting the model's convolutional layers to process depth 
   information.
4) Training: Train the adapted YOLO model using a combination of data augmentation techniques and transfer learning, optimizing the loss function to handle 3D bounding boxes and object 
   classes.
5) Evaluation: Validate the model's performance using standard metrics like Intersection over Union (IoU) and mean Average Precision (mAP), and test in real-world scenarios for generalization.

### Features
1) 3D Object Detection: Extends YOLO's capabilities to detect objects in 3D space, including height, width, depth, and orientation.
2) Real-Time Performance: Ensures the model runs at speeds suitable for real-time applications, maintaining a balance between accuracy and efficiency.
3) Scalability and Flexibility: Designed to adapt to various LiDAR datasets and environments, improving robustness in diverse conditions.
4) Enhanced Accuracy for Small Objects: Integrates techniques to improve the detection of small and distant objects, which are often challenging in LiDAR data.

### Project Outcome
The expected outcome is a functional system capable of accurately detecting and identifying objects in point cloud data. The system should work effectively in real-world environments, such as parking lots, demonstrating its potential for broader applications.
