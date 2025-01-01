# NLP QA Project with LLama 3.2 3B

## Project Overview
This project focuses on developing a Question-Answering (QA) system using the LLama 3.2 3B model. By leveraging state-of-the-art Natural Language Processing (NLP) techniques, we aim to provide accurate and efficient answers to user queries based on a dataset from Hugging Face.

## Dataset
We utilize a QA dataset sourced from Hugging Face. The dataset has been carefully chosen to ensure its quality and relevance to the project. It contains:
- Questions: Diverse types of questions, including factual, conceptual, and open-ended.
- Contexts: Supporting passages or documents from which the answers can be derived.
- Answers: Ground truth labels for supervised training.

## Model
We have selected the LLama 3.2 3B model for this project due to its:
- High performance in NLP tasks.
- Ability to handle large-scale QA datasets effectively.
- Flexibility in fine-tuning for domain-specific use cases.

## Project Objectives
1. Fine-tune LLama 3.2 3B on the QA dataset to improve its performance.
2. Evaluate the model using established metrics such as Exact Match (EM) and F1 score.
3. Deploy the model for real-time QA tasks via a simple and user-friendly interface.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Dataset Preparation
Download the dataset from Kaggle and preprocess it using the scripts provided:
Link : https://www.kaggle.com/datasets/thedevastator/glaive-python-code-qa-dataset
```bash
python preprocess_data.py --input path/to/dataset --output path/to/preprocessed/data
```

## Training the Model
Fine-tune the LLama 3.2 3B model using the training script:
```bash
python train.py --data path/to/preprocessed/data --model llama-3.2-3b --output path/to/model/output
```

## Evaluation
Evaluate the model's performance on the validation set:
```bash
python evaluate.py --model path/to/model/output --data path/to/preprocessed/validation/data
```
Metrics such as EM and F1 score will be reported.

## Deployment
Run the model as a QA API service:
```bash
python app.py --model path/to/model/output
```
Access the service locally at `http://localhost:8000`.

## Repository Structure
```
.
├── data/                     # Contains raw and preprocessed datasets
├── models/                   # Stores trained models and checkpoints
├── scripts/                  # Scripts for training, evaluation, and preprocessing
├── app.py                    # API for serving the QA model
├── requirements.txt          # Python dependencies
├── README.md                 # Project documentation
└── ...
```

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
We thank Hugging Face  for providing the creators of LLama 3.2 3B & Kaggle for the QA Dataset for their contributions to open-source NLP.

