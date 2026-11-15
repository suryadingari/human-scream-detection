# Intelligent Human Scream Detection Using Audio Signal Processing and Machine Learning

An IEEE-published research project focused on detecting human screams from audio signals using machine learning and deep learning techniques. The system explores audio preprocessing, feature extraction, and classification to distinguish scream sounds from non-scream sounds, supporting potential applications in public safety and emergency response systems.

## IEEE Research Publication

**Paper:** Intelligent Human Scream Detection for Crime Control Using Audio Signal Processing and Machine Learning

**Authors:** Dingari Surya, Reshma Raj R S

**Conference:** 2025 IEEE Pune Section International Conference (PuneCon)

**Publication:** IEEE Xplore

**Paper Link:** https://ieeexplore.ieee.org/document/11379355

## Project Overview

Traditional surveillance systems may fail to identify emergency situations when visual monitoring is limited. This research explores an audio-based approach to identifying human distress signals through scream detection.

The project develops and compares machine learning and deep learning models to classify audio signals into two categories:

- Scream
- Non-Scream

## Methodology

The research follows an audio classification pipeline:

1. **Audio Data Collection:** Collecting scream and non-scream audio samples.
2. **Preprocessing:** Preparing audio signals for feature extraction and classification.
3. **Feature Extraction:** Extracting relevant acoustic characteristics, including Mel-Frequency Cepstral Coefficients (MFCCs).
4. **Model Development:** Implementing and training multiple classification models.
5. **Performance Evaluation:** Comparing models using accuracy, precision, recall, F1-score, and confusion matrices.
6. **Audio Classification:** Exploring scream detection from input audio recordings.

## Models Implemented

| Model | Description |
|---|---|
| Support Vector Machine (SVM) | Traditional machine learning classifier |
| Random Forest (RF) | Ensemble-based classification |
| Convolutional Neural Network (CNN) | Deep learning-based audio classification |

## Published Results

The following results are reported in the published research paper:

| Model | Accuracy |
|---|---:|
| CNN | **88.6%** |
| Random Forest | 81.0% |
| SVM | 80.1% |

The CNN achieved the highest reported accuracy among the three evaluated models.

## Technologies Used

- Python
- NumPy
- Pandas
- Librosa
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- Seaborn
- Audio Signal Processing
- Machine Learning
- Deep Learning

## Repository Structure

```text
human-scream-detection/
│
├── README.md
│
└── notebooks/
    └── scream_detection.ipynb
```

## Getting Started

Clone the repository:

```bash
git clone https://github.com/suryadingari/human-scream-detection.git
cd human-scream-detection
```

Install the primary dependencies:

```bash
pip install numpy pandas librosa scikit-learn tensorflow matplotlib seaborn imbalanced-learn joblib
```

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Navigate to `notebooks/scream_detection.ipynb` and execute the cells.

**Note:** The notebook currently references Kaggle dataset paths. Configure the dataset paths and ensure the required audio datasets are available before running the experiments. The prediction preprocessing should also be aligned with the CNN training input before using the inference function.

## Potential Applications

- Public transportation safety
- Smart surveillance systems
- Emergency response frameworks
- Public safety monitoring
- Audio-based distress detection

## Research Significance

This project explores how audio signal processing and machine learning can contribute to automated identification of human distress signals. The comparative evaluation of traditional machine learning algorithms and CNN-based classification provides insights into their effectiveness for scream detection.

## Citation

If you reference this research, please cite the original IEEE publication:

**Dingari Surya and Reshma Raj R S**, "Intelligent Human Scream Detection for Crime Control Using Audio Signal Processing and Machine Learning," 2025 IEEE Pune Section International Conference (PuneCon), 2025.

[View Publication on IEEE Xplore](https://ieeexplore.ieee.org/document/11379355)

---

**Research Publication:** IEEE Xplore  
**Repository:** [Human Scream Detection – GitHub](https://github.com/suryadingari/human-scream-detection)
