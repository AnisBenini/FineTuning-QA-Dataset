# 🧠 NLP QA Project with LLaMA 3.2 1B & GPT-2 Large

## 📌 Project Overview
This project focuses on developing a **Question-Answering (QA) system** by fine-tuning **LLaMA 3.2 1B** and **GPT-2 Large** on a dataset containing **140,000 Python-related QA pairs**. Our goal is to improve **model accuracy, efficiency, and contextual understanding** in code-related queries.

## 📊 Dataset
We use the **Glaive Code Assistant Dataset** from [Kaggle](https://www.kaggle.com/datasets/thedevastator/glaive-python-code-qa-dataset), which is designed for training intelligent Python assistants.

### 🔹 Key Features:
✅ **140,000+ questions & solutions** related to Python programming.  
✅ **Structured QA format** for fine-tuning NLP models.  
✅ **60% Python-focused content**, ensuring high relevance for coding queries.  
✅ **Real-world user queries** covering simple to advanced programming topics.  

## 🚀 Models Used
We fine-tune two models:

### 🔷 **LLaMA 3.2 1B**
- **Modern Transformer architecture** optimized for NLP tasks.
- **1.24 billion parameters** enabling strong contextual learning.
- **Handles longer context windows** (2048 tokens).

### 🔷 **GPT-2 Large**
- **Classic Transformer-based model** (774M parameters).
- **More resource-efficient** than newer architectures.
- **1024-token context window** (shorter than LLaMA but effective for structured queries).

## 🎯 Project Objectives
1️⃣ **Fine-tune LLaMA 3.2 1B and GPT-2 Large** for QA.

2️⃣ **Optimize hyperparameters** for better efficiency.

3️⃣ **Compare both models** in terms of accuracy, coherence, and response quality.

4️⃣ **Improve model inference time** using LoRA & QLoRA techniques.

## ⚙️ Installation
Clone the repository and navigate into the project directory:
```bash
git clone https://github.com/AnisBenini/FineTuning-QA_Dataset.git
cd FineTuning-QA_Dataset
```

## 📥 Dataset Preparation
Download the dataset and preprocess it using the provided scripts:
🔗 [Kaggle Dataset](https://www.kaggle.com/datasets/thedevastator/glaive-python-code-qa-dataset)

## 🏋️ Training the Model
Fine-tune the models using the training script:
```bash
python train.py --model llama3.2-1B 
```

## 📈 Evaluation & Testing
🚧 Currently, the project **lacks a formal evaluation phase**. The next steps include:

✅ Implementing **unit tests** to validate functionality.  
✅ Adding **performance metrics** (BLEU, ROUGE, etc.).  
✅ Benchmarking results **against baseline QA models**.  

## 🤝 Contributing
We welcome contributions! Follow these steps:
1. **Fork the repository**.
2. **Create a feature branch**:
   ```bash
   git checkout -b feature/new-feature
   ```
3. **Commit your changes**:
   ```bash
   git commit -m "Add a new feature"
   ```
4. **Push to GitHub**:
   ```bash
   git push origin feature/new-feature
   ```
5. **Submit a pull request**.

## 📜 License
This project is licensed under the **MIT License**. See the `LICENSE` file for details.

## 🙏 Acknowledgments
Thanks to **Hugging Face**, **Meta AI**, and **Kaggle** for providing open-source NLP resources and datasets!
