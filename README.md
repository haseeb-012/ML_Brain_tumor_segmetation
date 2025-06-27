# Brain Tumor Segmentation with YOLO 11 and SAM2

This repository contains a project for brain tumor segmentation using the latest object detection and segmentation models: **YOLO 11** and **SAM2**. The approach leverages advanced deep learning techniques to accurately detect and segment brain tumors in MRI scans.


## Overview

Brain tumor segmentation is a crucial task in medical image analysis, aiding clinicians in diagnosis and treatment planning. This project applies state-of-the-art deep learning models to automate the segmentation process, aiming for high accuracy and reliability.

- **YOLO 11**: Used for robust detection of tumor regions.
- **SAM2**: Utilized for fine-grained segmentation within detected regions.


## Dataset

The project is designed to work with publicly available brain tumor MRI datasets (e.g., BraTS)
 [link] (https://universe.roboflow.com/brain-tumor-detection-wsera/tumor-detection-ko5jp/dataset/8). Please ensure your dataset is organized as expected or update the data loading code accordingly.

## Model Details

- **YOLO 11**: [Official YOLO documentation](https://github.com/ultralytics/ultralytics)
- **SAM2**: [Segment Anything Model](https://segment-anything.com/)

The models are either loaded from pre-trained weights or trained from scratch based on configuration.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Acknowledgements

- [Ultralytics YOLO](https://github.com/ultralytics/ultralytics)
- [Meta AI SAM](https://segment-anything.com/)
- Brain MRI datasets (e.g., [BraTS Challenge](https://www.med.upenn.edu/cbica/brats2020/data.html))

---
For questions or support, please open an issue in this repository.
