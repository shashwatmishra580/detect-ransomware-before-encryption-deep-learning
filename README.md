
# Detect Ransomware Before It Encrypts Files
## Using Deep Learning Models | IIITA DeLTA 2026

### Overview
Deep learning based ransomware detection system that identifies ransomware processes before encryption begins by analyzing Windows API call sequences.

### Models Implemented
- CNN-LSTM (Baseline)
- 3-Scale Multi-Kernel CNN
- 5-Scale Multi-Kernel CNN (Proposed)

### Key Results
| Model | Accuracy | Errors |
|---|---|---|
| CNN-LSTM | 99.30% | 89 |
| 3-Scale CNN | 99.53% | 76 |
| 5-Scale CNN | 99.59% | 60 |

### Novel Contribution — Early Detection Analysis
Model detects ransomware with 77.8% accuracy after observing just 20 API calls — well before encryption begins. This quantifies HOW EARLY ransomware can be detected, not just HOW ACCURATELY.

### Dataset
Kaggle: Malware Analysis Datasets API Call Sequences

### Tech Stack
Python | TensorFlow | Keras | Google Colab | Sklearn

### Internship
IIITA DeLTA 2026 — Computer Vision and Biometrics Lab
Project ID: DELTA26_037
