# Automatic Speech Severity Classification

This repository extends the earlier SPCOM 2024 work on dysarthric speech classification into a broader severity-classification study using temporal, prosodic, and spectral features together with augmentation and deep learning models.

The main goal here was to move beyond a narrower MFCC-centered setup and test how well fused feature groups generalize across datasets and speakers.

## What this work covers

- temporal, prosodic, and spectral feature extraction
- speaker-dependent and speaker-independent experiments
- augmentation methods such as VTLP and pitch, formant, and speaking-rate changes
- classical and neural models including SVM, random forest, ANN, CNN, LSTM, and TDNN
- evaluation on TORGO and UASpeech

## Main takeaways

- combined temporal, prosodic, and spectral features performed better than isolated feature groups
- augmentation improved robustness on low-resource dysarthric speech data
- the strongest setup reduced character error rate by up to 61.1% over the MFCC-only baseline discussed in the write-up

## Relationship to the earlier project

This repo is a follow-up to:

- https://github.com/Bhanuu01/Automatic-Speech-Disorder-Detection

The earlier work focused on in-domain augmentation for severity classification from speech. This phase broadened the feature space, model choices, and evaluation setup.

## Current status

This line of work later led into the journal paper:

- *Fusion of data augmentation for improved dysarthria severity classification*

Public assets in this repo are limited, but the project remains part of my speech and machine learning research path.

## Contact

- LinkedIn: https://www.linkedin.com/in/bhanujakarumuru/
- Email: bk3170@nyu.edu
