# ScientificTextClassification_LLMBased

This project aims to classify scientific texts into 34 different topics using Large Language Models (LLMs), specifically utilizing the DeBERTa model. The topics include areas such as nutrition, endocrinology, optics, artificial intelligence, neurobiology, zoology, and more. The same text can belong to more than one category or none of them.

## Project Structure

```ScientificTextClassification/
│
├── data/
│   ├── raw/                  # Raw data files
│   ├── processed/            # Processed data files
│
├── notebooks/
│   ├── 01_data_preprocessing.ipynb  # Notebook for data preprocessing
│   ├── 02_model_training.ipynb      # Notebook for model training
│   ├── 03_model_evaluation.ipynb    # Notebook for model evaluation
│   ├── 04_inference.ipynb           # Notebook for making predictions
│
├── scripts/
│   ├── preprocess.py          # Script for data preprocessing
│   ├── train.py               # Script for model training
│   ├── evaluate.py            # Script for model evaluation
│   ├── predict.py             # Script for making predictions
│
├── README.md
├── LICENSE
├── requirements.txt
└── .gitignore
```



## Getting Started

### Prerequisites

- Python 3.8 or higher
- [pip](https://pip.pypa.io/en/stable/)

### Installation

1. Clone the repository:

```
git clone https://github.com/yourusername/ScientificTextClassification.git
cd ScientificTextClassification
´´´

\begin{itemize}
\item{}
\end{itemize}
