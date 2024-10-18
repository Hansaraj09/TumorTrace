Welcome to TumorTrace: Precision Segmentation for Brain Tumors.

This reposioty levarges instance segmentation for Brain Tumor Detection.

**What is instance segmentation??**

Instance segmentation goes a step further than object detection. It involves identifying individual objects in an image and segmenting them from the rest of the image. Instance segmentation is useful when you need to know not only where objects are in an image but also what their exact shape is.

Now let's have a walk through this repository

This repository is created using the YOLOv8 which is a state-of-the-art object detection algorithm known for its high accuracy and real-time performance and Roboflow for datasets and streamlining the workflow.

**Datasets**

1. The dataset is curated from **Roboflow** which is present in YOLOv8 format.
2. It includes 3 classes of brain tumors viz 1,2,3. To use the dataset one needs to have a Roboflow API key.
3. The dataset is divided into train, valid, and test folders having images in ".jpg" format along with their labels present in ".txt" format inside the label folder.


**Runs folder**

1. The runs folder contains the segment folder which in turn contains 3 folders _viz._ predict2, train3 and val.
2. The train3 folder contains all the Box plots, confusion matrix, and model best weights. These were created during the custom training of the YOLOv8 model.
3. The inferencing is done using the best model weights, and the results are saved in the predict2 folder.
4. The val folder contains the validation of the custom model.

**Confusion Matrix**

![confusion_matrix](https://github.com/user-attachments/assets/0b55b4cd-fcf3-4149-bd5f-ab00aa25733e)

**Result Plots**

![results](https://github.com/user-attachments/assets/317d8d3d-9585-4088-87ce-2a5c777272c4)

**Some Results**

![cys_18_jpeg_jpg rf ccb75c976020a206c28e1d617e1a3ac7](https://github.com/user-attachments/assets/56cda1d5-60a0-45f0-818f-2c4f1f848b7c)

![cys_26_jpeg_jpg rf be73dccd37ea18f71895bfdc3263578b](https://github.com/user-attachments/assets/e3b5f4e5-8ba0-454a-ac29-287dae904f21)
