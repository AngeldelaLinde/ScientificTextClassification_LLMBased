# ScientificTextClassification_LLMBased

This project aims to classify scientific texts into 34 different topics using Large Language Models (LLMs), specifically utilizing the DeBERTa model. The topics include areas such as nutrition, endocrinology, optics, artificial intelligence, neurobiology, zoology, and more. The same text can belong to more than one category or none of them.

### Evaluation Criteria
The evaluation criteria for the model is the average ROC AUC value of each category.

## Project Structure

The uploaded notebook is divided in the following categories:
1. data_preprocessing
2. model_training
3. model_inference

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

2. Install the required packages:

```
pip install -r requirements.txt
```

## Data used:

The available data for the classification is the following:

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

After data analysis, it was inferred that the only meaningful information that provided classification criteria for the model is the Objective and title category.

## Authors

This project was created and developed by:

- Ángel de la Linde Valdés
- Alexia Durán Vizcaíno
- María Ordieres Álvarez

We have worked collaboratively to design, implement, and test the scientific text classification model using LLMs. Each of us has contributed to different aspects of the project, including data preprocessing, model training, evaluation, and inference.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
