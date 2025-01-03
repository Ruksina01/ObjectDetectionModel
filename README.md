# Object Detection with YOLO for Small Objects 🐾🔍👀

Detecting small objects in images is a complex challenge due to their tiny size, limited features, and poor image resolution 🐜📉. This project aims to improve small object detection and counting using the YOLO (You Only Look Once) model, known for its speed and accuracy in real-time 🚀. 

Traditional datasets often focus on larger objects, making it difficult to detect small, less common items 👀. To overcome this, we used the PESMOD (PExels Small Moving Object Detection) dataset 📸, which provides high-quality aerial images specifically designed for small moving object detection ✈️.

We had experimenting with different YOLO versions, we fine-tuned the model for optimal performance 🌱. The model's effectiveness is evaluated using metrics like Precision, Recall, and mean Average Precision (mAP) to assess its accuracy 🎯📊.

This project provides a practical solution for accurate recognition and counting of small objects in complex images or videos 🎥.

## Results 📊

The model performance was evaluated using several metrics such as Precision, Recall, F1-Score, Confidence, and mean Average Precision (mAP) at IoU (Intersection over Union) threshold 0.5. Below are the results for different YOLO model versions:

| Model       | Precision | Recall | F1-Score | Confidence | mAP@0.5 |
|-------------|-----------|--------|----------|------------|---------|
| YOLO11n     | 0.781     | 0.90   | 0.86     | 0.233      | 0.88    |
| YOLO11n-2   | 0.911     | 0.75   | 0.82     | 0.0        | 0.855   |
| YOLO11-3    | 0.886     | 0.99   | 0.96     | 0.223      | 0.982   |
| YOLO10n     | 0.767     | 0.91   | 0.85     | 0.259      | 0.882   |
| YOLOv9t     | 0.856     | 0.90   | 0.86     | 2.17       | 0.880   |
| YOLOv8n     | 0.824     | 0.98   | 0.85     | 0.207      | 0.875   |
| YOLOv8n-2   | 0.778     | 0.98   | 0.95     | 0.353      | 0.967   |

These results highlight the performance of different YOLO versions for small object detection, with YOLO11-3 showing the best overall performance in terms of F1-Score and mAP at 0.982.

## Model Performance Visualization 📈

Below is the performance visualization of the YOLO models for small object detection. The graph compares key metrics such as Precision, Recall, and mAP for different YOLO versions.

![Model Performance Graph](https://github.com/Ruksina01/ObjectDetectionModel/blob/main/visualization.png)

> **Note:** The graph above illustrates the comparison of YOLO models and their respective performance on the PESMOD dataset. You can see how each model performs across different metrics.

