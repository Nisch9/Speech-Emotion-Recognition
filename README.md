
# Speech-Based Emotion Recognition Using Deep Learning

## Summary

Human emotions play a crucial role in communication, and recognizing emotions from speech can significantly improve human-computer interactions. This project aims to develop a deep learning model that analyzes voice patterns and classifies emotions. The goal is to enhance applications in healthcare, virtual assistants, and customer service by making AI more emotionally intelligent.

---

## Objectives

- Develop a deep learning model for classifying emotions from speech.
- Use advanced speech processing techniques to extract meaningful features.
- Improve the accuracy of emotion recognition using state-of-the-art models.
- Compare different deep learning models to determine the best-performing approach.

---

## Methodology

### Dataset
We will use publicly available emotional speech datasets:

- **RAVDESS** – Ryerson Audio-Visual Database of Emotional Speech and Song  
- **CREMA-D** – Crowd-Sourced Emotional Multimodal Actors Dataset  
- **IEMOCAP** – Interactive Emotional Dyadic Motion Capture Database  
- **TESS** – Toronto Emotional Speech Set

### Feature Extraction

We will extract speech features using:

- **MFCCs** (Mel-Frequency Cepstral Coefficients)
- **Spectrograms**
- **Pitch Analysis**

### Model Selection

- Train **CNNs** for spectrogram-based emotion classification.
- Use **LSTMs/RNNs** to model sequential speech data.
- Experiment with **transformer-based models** such as **Wav2Vec** for improved performance.

### Implementation Tools

- **Librosa** for audio preprocessing
- **TensorFlow / Keras** or **PyTorch** for deep learning models
- **Data augmentation** techniques to handle noise and improve generalization

---

## Evaluation

### Qualitative Analysis

- Visualize spectrograms to observe patterns across different emotions.

### Quantitative Analysis

- Accuracy, Precision, Recall, and F1-score
- Confusion Matrix to analyze misclassifications
- Compare model performance against existing research benchmarks

---

## Comparison

We will compare the following architectures:

- **CNN**
- **LSTM / RNN**
- **Transformer-based models (Wav2Vec)**

---

## Dataset Descriptions

| Dataset   | Description |
|-----------|-------------|
| **RAVDESS** | Labeled speech samples across multiple emotions |
| **CREMA-D** | High-quality emotional speech samples from diverse speakers |
| **IEMOCAP** | Real-world dyadic emotional conversations |
| **TESS**    | Female speech recordings labeled by emotion |

---

## References

- Research papers on speech-based emotion recognition
- Studies on deep learning models for audio classification
- TensorFlow and PyTorch documentation
- Librosa documentation for speech feature extraction

---

## Project Board

[GitHub Project Board](https://github.com/users/Nisch9/projects/2/views/1)

---

## Authors

- **Nischith Adavala** – 50591641  
- **Rakshith Reddy Dargula** – 50591661  
- **Sumanth Yalamanchili** – 50604274
