# Automatic Speech Severity Classification using Temporal, Prosodic & Spectral Features

This repository is a continuation of [Automatic-Speech-Disorder-Detection](https://github.com/Bhanuu01/Automatic-Speech-Disorder-Detection), extending our prior work on dysarthric speech detection by focusing on **severity classification** using multi-domain feature fusion and deep learning models.

> ⚠️ This research is currently under review. Code and experimental assets will be released post-publication.

---

## 🔍 Project Overview

While earlier work focused on binary detection of speech disorders, this study addresses the **classification of dysarthria severity** using a richer set of speech features and advanced models. We evaluate features across **temporal**, **prosodic**, and **spectral** domains and conduct experiments in both **speaker-dependent** and **speaker-independent** settings.

Key additions in this phase:
- Multi-feature group analysis (15+ features)
- Augmentation methods: VTLP, pitch/formant/speaking rate modification
- Robust classification using LSTM and TDNN
- Experiments on TORGO and UASpeech datasets

---

## 🔬 Techniques & Highlights

- 🎯 **Feature domains**:  
  - *Temporal*: Duration, AZCR  
  - *Prosodic*: Pitch, Loudness  
  - *Spectral*: MFCC, STFT, Spectral Flatness/Entropy

- ⚙️ **Models tested**:  
  SVM, RF, ANN, CNN, LSTM, TDNN

- 🔁 **Augmentation**:  
  Improved generalization using speech transformation techniques

- 📈 **Performance gains**:  
  - Up to **61.1% CER reduction** over MFCC-only baseline  
  - Combined temporal–prosodic–spectral features outperform isolated features  
  - Strong generalization to unseen speakers

---

## 📊 Dataset Information

This study uses:
- **TORGO** dataset – [Access here](https://www.cs.toronto.edu/~complingweb/data/TORGO/torgo.html)
- **UASpeech** dataset – [Access here](http://www.isle.illinois.edu/sst/data/UASpeech/)

Due to dataset licenses, we cannot redistribute data directly in this repository.

---

## 📂 Related Work

This is a follow-up to:  
🔗 [Automatic-Speech-Disorder-Detection](https://github.com/Bhanuu01/Automatic-Speech-Disorder-Detection) – focused on binary classification using augmented MFCC and traditional ML.

---

## 📬 Contact

For academic queries or collaboration opportunities, please reach out to:

**Bhanuja Karumuru**  
📧 bhanujakarumuru2@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/bhanujakarumuru)
