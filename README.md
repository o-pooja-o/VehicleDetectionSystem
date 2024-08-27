## Vehicle Identification and Smart Traffic Control System

During our exploration of vision systems, my team undertook a project focused on identifying vehicles at traffic lights. The key aspect of this project was counting the number of vehicles to implement a smart traffic control system that operates based on real-time identification, aiding in reducing congestion during high traffic volumes.

### Initial Approach (v1)
Initially, we utilized the YOLO v8 Object Detection library along with the Keras CV library for this task. However, we encountered some challenges in accurately counting the vehicles using Keras CV.

### Improved Approach
To address these issues, we transitioned to using pretrained YOLO v8 model weights from Ultralytics. This switch significantly improved the speed and accuracy of vehicle categorization and counting in our dataset.

### Testing and Results
We tested both models on random traffic images. For testing purposes, you can select any three images of traffic at signals from the web to evaluate the accuracy. The system also generates a report file that includes bounding boxes and confidence scores.

### Some useful links
https://docs.ultralytics.com/models/yolov8/#usage-examples
https://docs.ultralytics.com/guides/object-counting
https://learnopencv.com/object-detection-using-kerascv-yolov8/

### Dataset used in v1
https://universe.roboflow.com/roboflow-100/vehicles-q0x2v
