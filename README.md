# DNA Sequence Classification using Enhanced Perceptron

This project applies an Enhanced Perceptron model to classify DNA sequences from SARS and MERS viral genomes. It demonstrates a lightweight and interpretable machine learning approach to sequence classification using custom feature extraction, preprocessing, and early stopping mechanisms.

## 📂 Files Included

- `perceptron.ipynb`: Jupyter notebook containing the complete implementation and evaluation of the model.
- `merged_sars_mers.csv`: The dataset containing labeled SARS and MERS DNA sequences used for training and evaluation.

## 🔍 Problem Statement

Given a set of DNA sequences from two viral types (SARS and MERS), the goal is to build an efficient binary classification model. The project focuses on:
- Sequence preprocessing
- K-mer based feature extraction
- TF-IDF vectorization
- SMOTE for class balancing
- Enhanced Perceptron with early stopping and learning rate decay
- Model evaluation using accuracy, F1-score, and cross-validation

## ⚙️ Technologies Used

- Python
- Scikit-learn
- Pandas / NumPy
- imbalanced-learn
- Jupyter Notebook

## 🚀 How to Run

1. Clone this repository:
   
   `git clone https://github.com/your-username/dna-sequence-perceptron.git`
   `cd dna-sequence-perceptron`

2. Install the required dependencies:

    `pip install -r requirements.txt`

3. Open the notebook:

jupyter notebook perceptron.ipynb

## 📈 Results

The model achieved:
- **Accuracy**: ~99%
- **F1 Score**: ~99%
- Balanced classification across both SARS and MERS classes.

## 📌 Citation

If you use this work in your research, please consider citing the project or the related paper.

## 📬 Contact

For questions or collaborations, feel free to reach out at: lucky25325@gmail.com
