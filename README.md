# Quantum-Enhanced Part-of-Speech Tagger 🌟

This repository presents a **Quantum-Enhanced Part-of-Speech (POS) Tagger**, a novel project integrating quantum computing with natural language processing (NLP). By leveraging **PennyLane** and **PyTorch**, we explore how quantum circuits can enhance the accuracy and efficiency of POS tagging.

---

## 🧩 **Overview**

The goal of this project is to assign grammatical tags (e.g., noun, verb, adjective) to words in sentences using two approaches:

1. **Classical LSTM:** A standard Long Short-Term Memory (LSTM) network serves as the baseline.
   
![image](https://github.com/user-attachments/assets/fb16c47e-13d8-4fa0-8ed5-bf69299a33a1)

A schematic for a classical long short-term memory (LSTM) cell.

2. **Quantum LSTM (QLSTM):** An innovative model embedding quantum circuits into the LSTM architecture, enabling enhanced learning capabilities.
   
![image](https://github.com/user-attachments/assets/0dbd9eb8-a38e-4ebd-b188-349599af6638)

The proposed quantum long short-term memory (QLSTM) architecture. Each VQC box is of the form as detailed in above figure. The σ and tanh blocks represent the sigmoid and the hyperbolic tangent activation function, respectively.

---

## Methodology

The project methodology follows a structured pipeline designed to achieve accurate and efficient part-of-speech tagging using advanced computational techniques. The steps are detailed below:

### 1. Data Preparation
The data preparation phase involved collecting and preprocessing textual data to ensure compatibility with the tagging algorithm. Key tasks included:
- Cleaning and tokenizing raw text data.
- Annotating text with correct part-of-speech tags.
- Splitting data into training, validation, and testing sets.

### 2. Quantum-Inspired Model Architecture
A Variational Quantum Classifier (VQC) model was designed for the POS tagging task. The model leverages quantum circuits to enhance computational efficiency and achieve improved accuracy. **(Insert quantum circuit screenshot here)**.

### 3. Model Training
The training phase involved:
- Feeding the annotated dataset into the VQC model.
- Optimizing the circuit parameters using a hybrid quantum-classical training loop.

### 4. Evaluation
The model was evaluated based on standard metrics such as accuracy, precision, recall, and F1-score. The results were compared with classical models to highlight the advantages of the quantum approach.

### 5. Visualization and Analysis
Visual tools were employed to interpret the model's predictions and error distribution. This step helped identify strengths and weaknesses in the model's performance.

---

## ⚙️ **Features**

- **Data Preparation:** 
  - Sentence dataset with corresponding POS tags.
  - Efficient `word-to-index` and `tag-to-index` mappings for processing.

- **Model Construction:**
  - **Classical LSTM:** Implements a traditional LSTM network.
  - **Quantum LSTM:** Integrates a parameterized quantum circuit using PennyLane.

- **Training and Evaluation:**
  - **Optimizer:** Stochastic Gradient Descent (SGD) with Negative Log-Likelihood Loss.
  - **Metrics:** Accuracy and loss trends over epochs.
  - Comparative analysis between classical and quantum models.

---

## 🚀 **Quantum Advantage**

### Why Quantum?
The **Quantum LSTM** model explores how quantum computation can revolutionize NLP tasks:
- **Expressive Representations:** Quantum circuits may capture complex word relationships and grammatical contexts.
- **Potential Speedups:** Quantum computation can optimize specific components of the tagging process.

---

## 📊 **Results**

Both models were evaluated on a held-out dataset, with results visualized through training history plots showcasing:

- Loss trends
- Accuracy comparisons

The **QLSTM** demonstrated potential advantages in feature representation and learning efficiency. 

---

## 🛠️ **Getting Started**

### Prerequisites
- Python 3.6+
- Libraries: 
  - [PennyLane](https://pennylane.ai/)
  - [PyTorch](https://pytorch.org/)
  - NumPy, Matplotlib, and more (see `requirements.txt`).

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/MaazMKhan3/Quantum-LSTM.git
   cd Quantum-LSTM
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Usage
1. Open the provided Jupyter notebook:
   ```bash
   jupyter notebook Quantum_POS_Tagger.ipynb
   ```
2. Run cells sequentially to:
   - Prepare the dataset
   - Build classical and quantum LSTM models
   - Train and evaluate models

3. View results and training plots.

---

## 📂 **Project Structure**
```
📁 LSTM
├── 📄 README.md          # Project overview
├── 📄 requirements.txt   # Dependencies
├── 📂 models             # Classical and quantum LSTM implementations
├── 📂 data               # Dataset and preprocessing scripts
├── 📂 results            # Training plots and evaluation metrics
└── 📄 Quantum_POS_Tagger.ipynb # Main Jupyter notebook
```

---

## 🤔 **Future Work**

- Experiment with alternative quantum circuit designs.
- Explore other NLP tasks (e.g., sentiment analysis, text classification) using QLSTM.
- Investigate scalability and optimization of quantum-enhanced NLP models.

---

## ✨ **Conclusion**

This project demonstrates the exciting potential of quantum computing in NLP, specifically for POS tagging. The **QLSTM** showcases a novel avenue for enhancing classical models, paving the way for further exploration in quantum-enhanced machine learning.

---

## 🤝 **Contributions**

Contributions, issues, and feature requests are welcome! Feel free to fork the repository and submit pull requests.

---

## 📜 **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## **Team Members**

Haris Hussain
Maaz Khan
Areeb-Ul-Haq
