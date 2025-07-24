# Dysarthria Severity Classification using Temporal, Prosodic & Spectral Features

This repository provides a high-level overview of research conducted on automated dysarthria severity classification using machine learning techniques. The study extends traditional MFCC-based methods by integrating features across three domains — **temporal**, **prosodic**, and **spectral** — and evaluates performance using deep learning models such as **LSTM** and **TDNN**.

> 🚧 This research is currently under review for journal publication. Code, models, and detailed results will be released post-acceptance.

---

## 🔬 Summary

Dysarthria, a neuro-motor speech disorder, impacts speech rate, articulation, and vocal modulation. To address the limitations of using only MFCC features, this work introduces a broader feature set and investigates their individual and combined performance for classifying severity levels.

Key contributions:
- Extracted and analyzed 15 features across 3 domains (e.g., **AZCR**, **Spectral Flatness**, **STFT**).
- Compared 7 models including SVM, RF, ANN, CNN, LSTM, and TDNN.
- Performed both **speaker-dependent** and **speaker-independent** evaluations using TORGO and UASpeech datasets.
- Applied augmentation techniques: VTLP, pitch shifting, formant shifting, and speaking rate modification.

---

## 📈 Highlights

- 📉 Achieved **61.1% improvement** in classification error rate over MFCC-only baseline.
- 🔁 Augmentation techniques led to **42.86% relative improvement** in speaker-dependent settings.
- 🤖 TDNN and LSTM showed superior performance with fused feature groups.

---

## 📁 Datasets

Due to licensing restrictions, datasets are not included here. You can request access from:

- **TORGO**: https://www.cs.toronto.edu/~complingweb/data/TORGO/torgo.html  
- **UASpeech**: http://www.isle.illinois.edu/sst/data/UASpeech/

---

## 📌 Note

This is a **research-only** repository placeholder. Code and trained models will be shared after formal acceptance of the associated publication.

---
