# Detecting Novelty Seeking from Online Travel Reviews: A Deep Learning Approach

## 📌 Project Overview

This project presents a **deep learning-based classification framework** to automatically detect the **Novelty Seeking (NS)** personality trait from online travel reviews. It addresses the challenge of analyzing large volumes of unstructured review data by using a hybrid **BERT-CNN-BiGRU** model to improve the accuracy and efficiency of NS detection.

### 🔍 Motivation

Understanding NS personality traits can be crucial in the **tourism industry**, influencing:
- Tourist motivations
- Destination selection
- Personalized marketing and recommendations

Manual classification is not feasible due to data size and complexity. Our system automates this process using **state-of-the-art NLP techniques**.

---

## ⚙️ System Architecture

### 🔹 Existing System

- Manual classification or use of simple machine learning algorithms.
- **Disadvantages:**
  - Low accuracy
  - High processing time

### 🔹 Proposed System

- Utilizes **BERT** for feature extraction
- Uses **Bi-GRU** for sequential data learning
- Shows significantly **higher accuracy** and **faster processing**

### 🔹 Extension Concept

- Developed a **hybrid model** combining:
  - **BERT** (contextual embeddings)
  - **CNN** (feature detection)
  - **Bi-GRU** (sequence modeling)
- Achieves **>95% accuracy**, outperforming standalone models like CNN or LSTM.

---

## 📊 Model Performance

| Model           | Precision | F1 Score |
|----------------|-----------|----------|
| BERT + BiGRU   | 93.4%     | 93.3%    |
| BERT + CNN + BiGRU (Hybrid) | **>95%**  | **>95%** |

---

## 🛠️ Requirements

### 🔧 Hardware Requirements

- **Processor**: Intel i3 or higher
- **Hard Disk**: Minimum 40 GB
- **RAM**: 4GB or higher

### 💻 Software Requirements

- **OS**: Windows 10 or higher
- **Language**: Python 3.x
- **IDE**: Jupyter Notebook / VS Code
- **Libraries**:
  - `transformers`
  - `tensorflow` / `keras`
  - `sklearn`
  - `pandas`, `numpy`, `matplotlib`

---

## 📂 Project Structure

