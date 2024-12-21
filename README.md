# Baby Cry Classifier

This repository contains the source code and dataset for a deep learning model combining **Support Vector Machine (SVM)** and **Multi-Layer Perceptron (MLP)** architectures to classify baby cries using audio data from the *"Donate a Cry Corpus"* dataset.

## Cry Classifications

The model classifies baby cries into the following categories:

- **hu**: Hungry  
- **bu**: Needs burping  
- **bp**: Belly pain  
- **dc**: Discomfort  

## Features Used

The **Baby Cry Classifier** model leverages 193 features extracted from the audio data of baby cries. These features include:

1. **40 MFCCs**: Mel-frequency cepstral coefficients  
2. **12 chroma features**  
3. **128 mel-spectrogram features**  
4. **7 spectral contrast features**  
5. **6 tonnetz features**  

These features are extracted from the audio samples and serve as inputs to the machine learning algorithms for classification.

---
Explore the repository to learn more about the model and dataset implementation!
