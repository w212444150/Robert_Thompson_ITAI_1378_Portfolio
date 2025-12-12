# Classical Image Classification (HOG & SVM)

## Problem Statement
Classifying images using classical machine learning techniques before the advent of Deep Learning.

## Approach
- **Feature Extraction:** Used HOG (Histogram of Oriented Gradients) and LBP (Local Binary Patterns).
- **Classifier:** Trained a Support Vector Machine (SVM) on these features.

## Results & Findings
- The SVM trained on HOG features was faster and less memory-intensive than training on raw pixels.
- **Key Insight:** Raw pixels are noisy; extracted features capture the actual "shape" of the object.

## Technologies Used
- Scikit-Learn (SVM)
- Scikit-Image (HOG/LBP)
- Matplotlib
