# 🧠 Shakespeare Text Generation using Character-Level RNN/LSTM

This project implements a character-level text generation model using RNN and LSTM architectures to generate Shakespeare-style writing. The model is trained on the **Shakespeare Plays Dataset** from Kaggle and uses temperature sampling for generating stylistically consistent text.

---

## 📚 Project Overview

### Objective:
Train a model to generate Shakespeare-style text using character-level RNN and LSTM models. 

### Key Features:
- Character-level input and output
- LSTM architecture with configurable hyperparameters
- Temperature-controlled text generation
- BLEU score evaluation
- Visualization of training/validation loss and accuracy
- Character-level confusion matrix

---

## 📁 Dataset

- **Source:** [Shakespeare Dataset on Kaggle](https://www.kaggle.com/datasets/kingburrito666/shakespeare-plays)
- Contains full text of Shakespeare's plays
- Used for training character-based sequences

---

## ⚙️ Model Configuration

The following hyperparameters were used and tuned:

- `Sequence Length`: 100
- `Embedding Size`: 256
- `Hidden Units`: 512
- `Learning Rate`: 0.001
- `Batch Size`: 128
- `Number of LSTM Layers`: 2
- `Dropout`: 0.2
- `Optimizer`: Adam
- `Temperature (Sampling)`: 0.5

---

## 📊 Evaluation

- **BLEU Score**: `0.31`  
- **Human Evaluation**: Generated text maintains grammatical structure and captures stylistic nuances of Shakespearean English

### ✅ Visuals Included
- Accuracy and Loss plots (Train vs Validation)
- Character-level Confusion Matrix
- Generated text samples at different temperature levels

---

## 🧪 Outputs & Results

### 🎯 Final Validation Accuracy
- Achieved accuracy: **%** (insert final val accuracy from notebook)


---

## 📌 Instructions to Run

1. Clone this repository
2. Upload `kaggle.json` to authenticate
3. Install dependencies:
   ```bash
   pip install -r requirements.txt


