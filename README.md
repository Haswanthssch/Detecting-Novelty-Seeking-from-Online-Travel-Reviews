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

```
📁 novelty-seeking-detection/
├── data/                  # TripAdvisor Reviews Dataset
├── models/                # Saved Models (BERT, BiGRU, CNN)
├── notebook/              # Jupyter Notebooks for training & evaluation
├── utils/                 # Preprocessing and helper functions
├── README.md              # Project documentation
└── requirements.txt       # Required Python packages
```

---

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/novelty-seeking-detection.git
   cd novelty-seeking-detection
   ```

2. **Create a virtual environment (optional):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # or venv\Scripts\activate on Windows
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the training notebook:**
   Open `notebook/train_model.ipynb` in Jupyter Notebook or any Python IDE.

---

## 🔮 Future Work

- Integrate attention mechanisms for deeper contextual understanding
- Extend model to other personality traits (e.g., extroversion, openness)
- Deploy model as an API for integration with tourism platforms

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🤝 Acknowledgements

- TripAdvisor for review dataset
- Research papers on BERT, GRU, and CNN architectures
- Hugging Face for transformer models

---

