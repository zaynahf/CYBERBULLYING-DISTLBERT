DistilBERT-Based Cyberbullying Detection

This repository contains the implementation of a DistilBERT-based text classification model for detecting cyberbullying across categories such as toxicity, sexism, racism, and general abuse. The project is a part of an academic research study aimed at exploring the effectiveness of transformer-based models in comparison to traditional machine learning techniques.

This model is an improved version of the baseline TF-IDF + Logistic Regression model, which can be found here:
https://github.com/zaynahf/cyberbullying-detector


---

📄 Research Context

This implementation supports the findings presented in my research paper titled:

“Cyberbullying Detection Using Text Analysis” 
By Zaynah Farid
Amity University Lucknow Campus
The paper evaluates performance across models, discusses limitations in detecting subtle bias, and explores future directions such as the inclusion of sentiment features using NRCLex and domain-adaptive training.


---

📁 Repository Contents

Due to repeated execution issues with Google Colab and Hugging Face's Trainer interface, the .ipynb file could not be reliably executed or uploaded. As a result, all essential code is documented and preserved in a Word file containing screenshots of each code block used in the development and evaluation of the model.


---

🧠 Model Overview

Model: DistilBERT from Hugging Face Transformers

Task: Multiclass text classification

Labels: Toxicity, Sexism, Racism, YouTube/General

Input: Cleaned, lowercased text

Architecture: DistilBERT base + classification head

Framework: PyTorch + Hugging Face transformers



---

📊 Dataset

The dataset used was compiled from public Kaggle resources, originally labeled for various forms of abusive content. To prevent class imbalance, the data was resampled to ensure equal representation of all categories.


---

⚠️ Limitations

Due to Colab execution failures, dynamic outputs and visualizations were captured as static images.

Emotion-based features (NRCLex) were planned but not integrated in this version due to time and compatibility constraints.
