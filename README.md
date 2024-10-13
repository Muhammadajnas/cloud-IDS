# Cloud Intrusion Detection using Stacked Contractive Auto-Encoder (SCAE) and Support Vector Machine (SVM)

## Overview
This project presents a novel **Cloud Intrusion Detection System (CIDS)** utilizing **Stacked Contractive Auto-Encoder (SCAE)** for unsupervised feature extraction and **Support Vector Machine (SVM)** for classification. The system effectively detects malicious attacks in cloud computing environments by addressing challenges like large-scale network traffic, high dimensionality, and feature redundancy.

## Key Features
- **Unsupervised Feature Extraction**: Uses SCAE to automatically learn robust low-dimensional features from raw network traffic data.
- **Hybrid Learning Approach**: Combines the strengths of deep learning (SCAE) and shallow learning (SVM) to improve detection accuracy and reduce computational overhead.
- **Cloud-Specific Intrusion Detection**: Detects both "north-south" and "east-west" traffic within cloud environments.

## Methodology
- **Data Preprocessing**: Network traffic data from the **KDD Cup 99** and **NSL-KDD** datasets is preprocessed, including normalization and feature scaling.
- **Feature Learning**: The SCAE model is trained to extract essential features, which are then used as input to the SVM classifier.
- **Classification**: The SVM classifier distinguishes between normal and malicious traffic (e.g., DoS, Probe, R2L, U2R attacks).
- **Performance Metrics**: Precision, recall, F1-score, and AUC are used to evaluate the system’s performance.

## Datasets
- **KDD Cup 99**: Contains 494,021 training and 292,300 testing records.
- **NSL-KDD**: Consists of 125,973 training and 18,794 testing records.

## Results
The proposed **SCAE+SVM** model achieves higher detection accuracy compared to traditional methods:
- **KDD Cup 99**: 98% accuracy
- **NSL-KDD**: 87% accuracy

## Installation
To set up the project locally:
1. Clone this repository:
   ```bash
   git clone https://github.com/muhammadajnas/cloudIDS.git
   
## Future Work
Extend the model to detect zero-day and advanced persistent threats (APTs).
Deploy the system in a real-time cloud environment using Kubernetes for scalability.
License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For further details, reach out to:

## Muhammad Ajnas
# Email: muhammadajnas2001@gmail.com



