# Applying Data Science Group Project – PHMAP 2023 Challenge

Welcome to our **Applying Data Science** group project repository!

This project explores the development of **predictive algorithms** for system health and performance monitoring using multivariate time-series data from the [PHMAP 2023 Data Challenge](https://data.phmsociety.org/phmap-2023-data-challenge/).

We compare **deep learning** and **traditional machine learning** approaches—including **CNN**, **LSTM**, **SVM**, **XGBoost**, and hybrid models—across a sequence of diagnostic tasks. The objective is to assess the **effectiveness, limitations, and real-world applicability** of each model for fault detection and classification in complex systems.

---

## Repository Structure


- **dataset/**  
  Raw and preprocessed train/test data

- **EDA&DataProcessing/**  
  Exploratory analysis and feature engineering

- **models/**  
  All model implementations (CNN, LSTM, SVM, XGB)  

---

## Project Outline

- **Multistage Downstream Tasks**  
  - **Task 1**: Normal/Abnormal classification  
  - **Task 2**: Fault type classification (bubble, valve, unknown)  
  - **Task 3**: Bubble source localization  
  - **Task 4**: Faulty SV identification  
  - **Task 5**: SV opening ratio prediction (regression)

- **Modeling**
  - **CNN** for capturing local patterns from raw pressure sequences
  - **CNN + LSTM** for learning temporal dynamics and long-term dependencies
  - **XGBoost & SVM** using handcrafted statistical features for robust tabular modeling

- **Data Processing**
  - Feature extraction (mean, std, min, max for each sensor)
  - Label extraction

---

## Tools & Libraries

- **Programming**: Python (Jupyter notebooks)
- **ML/DL Frameworks**: PyTorch, scikit-learn, XGBoost..
- **Visualization**: Seaborn, Matplotlib

---

## Acknowledgement

Dataset provided by the [PHMAP 2023 Data Challenge](https://data.phmsociety.org/phmap-2023-data-challenge/).  
This project is part of the **Applying Data Science** course at the University of Manchester.

---

