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
```

\begin{itemize}
\item{}
\end{itemize}

| Field Name          | Description                                                     |
|---------------------|-----------------------------------------------------------------|
| projectID           | Unique ID associated with each project                          |
| startDate           | Date of the beginning of the project                             |
| endDate             | Date of the ending of the project                                |
| totalCost           | Total cost of the project declared by the applicants             |
| ecMaxContribution   | Maximum expenses that will be covered by the grant               |
| frameworkProgramme  | FP7, H2020, or HE - Multiannual EU program associated to the project. To work with categorical variables, we advise using one-hot-encoding codification |
| Number of papers    | Number of published papers that acknowledge funding from the project |
| Number of patents   | Number of patents resulting from the project                     |
| TFIDF               | TF-IDF vectorization of the title and objective of the project   |
| title               | Title of the project                                             |
| Objective           | Summary of the project                                           |

