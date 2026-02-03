# Video-Swimming-Incident-Detection

Official PyTorch implementation of  
**"Detecting Swimming Incidents in Videos: Dataset and Approach"**

---

## Introduction

This repository contains the official implementation of our work on video-based swimming incident detection**, which aims to detect critical swimming incidents (e.g., struggling, floating, and sinking) in indoor swimming pools using surveillance cameras in a contactless manner.

The proposed method is developed based on recent advances in spatio-temporal action detection, and is evaluated on a newly collected benchmark dataset, **SwimID**, which focuses on realistic swimming scenarios and safety-critical events.

**Note:**  
The source code will be publicly released after the acceptance of the associated paper.

---

## SwimID Dataset

### Dataset Overview

The **SwimID** dataset is designed for spatio-temporal swimming incident detection in indoor swimming pools. It contains:

- Realistic swimming activities captured by fixed CCTV cameras
- Multiple categories of safety-critical swimming incidents
- Dense per-frame annotations with bounding boxes, action labels, and tracking IDs

Due to privacy and safety considerations, the dataset is not publicly downloadable without authorization.

---

### Dataset Access

To download the **SwimID dataset**, please follow the steps below:

1. Sign the Release Agreement
2. Email the signed agreement to:
  
   *mengfanhe@nwafu.edu.cn*

By sending the application, you are agreeing and acknowledging that you have read and understood the terms stated in the Release Agreement.

We will reply with:
- The dataset download link
- Corresponding usage guidelines  

right after we receive your request.

---

## Data Structure

After downloading and extracting the dataset, the directory structure should be organized as follows:

```text
$DATASET_ROOT
├── SwimID
│  ├── 2022_08_01_RGB
│  │  ├── 1
│  │  │  ├── 01
│  │  │  │  ├── 00001.jpg
│  │  │  │  ├── ...
│  │  │  │  └── 00054.jpg
│  │  │  └── ...
│  │  └── 02
│  │     ├── 00001.jpg
│  │     ├── ...
│  │     └── 00071.jpg
│  ├── ...
│  └── xhwt_2023_05_06_RGB
│     ├── NVR_ch1_main_20230506104756_20230506104813
│     ├── ...
│     └── NVR_ch14_main_20230506105710_20230506105725

$ANNOTATIONS_ROOT
├── SwimID-GT.pkl
```

---

## Code Availability

The training and evaluation code will be released upon acceptance of the paper, including:

- Data loading and preprocessing scripts

- Model definitions

- Training and evaluation pipelines

- Configuration files

This repository will be updated accordingly.

---

## License

The dataset and code are released for academic research purposes only.
Commercial usage is strictly prohibited without explicit permission.

Please refer to the Release Agreement for detailed terms.

---

## Contact

If you have any questions regarding the dataset or the paper, please feel free to contact us via email after the paper is published.
