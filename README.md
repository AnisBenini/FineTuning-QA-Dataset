# NLP QA Project with LLama 3.2 1B & GPT2 Large

## Project Overview
This project focuses on developing a Question-Answering (QA) system using the LLama 3.2 1B & GPT2 Large model. By leveraging state-of-the-art Natural Language Processing (NLP) techniques, we aim to provide accurate and efficient answers to user queries based on a dataset from Hugging Face.

## Dataset

We utilize the **Glaive Code Assistant dataset** sourced from [Kaggle](https://www.kaggle.com/datasets/thedevastator/glaive-python-code-qa-dataset). This dataset contains approximately **140,000 code-related questions and solutions** designed to support the development of intelligent Python code assistants.

### Key Features:
- **Questions:** Real-world user questions covering a wide range of coding issues, from basic data types to complex object-oriented programming concepts.  
- **Solutions:** Corresponding answers providing detailed code solutions for the questions posed.  
- **Focus:** Around **60% of the content is Python-based**, making it highly relevant for Python-focused QA systems.

By leveraging this dataset, developers can create automated systems capable of accurately responding to coding queries, improving development efficiency, and simplifying workflows for both beginners and advanced programmers.


## Model
We have selected the LLama 3.2 1B & GPT2 Large model for this project due to its:
- High performance in NLP tasks.
- Ability to handle large-scale QA datasets effectively.
- Flexibility in fine-tuning for domain-specific use cases.

## Project Objectives
1. Fine-tune LLama 3.2 1B on the QA dataset to improve its performance.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/AnisBenini/QA-project.git
   cd QA-project
   ```
## Dataset Preparation
Download the dataset from Kaggle and preprocess it using the scripts provided:
Link : https://www.kaggle.com/datasets/thedevastator/glaive-python-code-qa-dataset


## Training the Model
Fine-tune the LLama 3.2 1B & GPT2 Large models using the training script:



## Contributing
We welcome contributions! Please follow these steps:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your commit message"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments
We thank Hugging Face  for providing the creators of LLama 3.2 1B, GPT2 Large & Kaggle for the QA Dataset for their contributions to open-source NLP.

