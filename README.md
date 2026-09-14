# PPE Detection using YOLOv5

## Project Overview

This project uses YOLOv5 for Personal Protective Equipment (PPE) object detection.

The model detects four classes:
- Boots
- Helmet
- Person
- Vest

## My Contribution

Implemented the YOLOv5 object-detection workflow, including dataset preparation, model setup, training, and evaluation/performance analysis.

## Dataset

The project uses a PPE object-detection dataset from Roboflow.

The model was evaluated on four PPE-related classes:
- Boots
- Helmet
- Person
- Vest

**Dataset source:** [Roboflow – PPE Dataset for Workplace Safety](https://universe.roboflow.com/n-4cjfd/ppe-dataset-for-workplace-safety-2rrlg/dataset/1)

## Model Training

The training configuration used:

| Setting | Value |
|---|---|
| Model | YOLOv5s |
| Pretrained weights | `yolov5s.pt` |
| Image size | 640 |
| Batch size | 16 |
| Epochs | 30 |
| Dataset configuration | `data.yaml` |

## Results

The reported evaluation results from the project are:

| Metric | Value |
|---|---:|
| Precision | 0.966 |
| Recall | 0.947 |
| mAP@50 | 0.972 |
| mAP@50-95 | 0.770 |
| FPS | 75.64 |

## Project Structure

```text
PPE-Detection-YOLOv5/
├── README.md
├── PPE_Detection_YOLOv5_P.ipynb
└── M.txt
```

- `yolo5code.ipynb` — project notebook containing the YOLOv5 setup and training workflow.
- `M.txt` — reported model evaluation results.

## Technologies

- Python
- YOLOv5
- Object Detection
- Roboflow Dataset
