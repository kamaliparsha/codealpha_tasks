# Task 3 — Sentiment Analysis of Movie Reviews

## Project Overview

This project performs sentiment analysis on movie reviews using Python and the VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analysis tool.

The objective is to classify movie reviews into positive, negative, or neutral sentiment categories and evaluate the predictions against the original dataset labels.

This project was completed as part of the **CodeAlpha Data Analytics Internship — October Batch**.

## Dataset

- **Dataset:** NLTK Movie Reviews Dataset
- **Total Reviews:** 2,000
- **Negative Reviews:** 1,000
- **Positive Reviews:** 1,000

The dataset contains movie reviews with their corresponding original sentiment labels.

## Tools and Technologies

- Python
- Pandas
- NLTK
- VADER Sentiment Analyzer
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Jupyter Notebook

## Project Workflow

1. Loaded the NLTK Movie Reviews dataset.
2. Extracted movie review text and original sentiment labels.
3. Applied the VADER sentiment analyzer to each review.
4. Classified reviews as positive, negative, or neutral.
5. Compared predicted sentiments with the original dataset labels.
6. Generated evaluation metrics and visualizations.

## Key Results

| Metric | Result |
|---|---:|
| Total reviews analyzed | 2,000 |
| Positive predictions | 1,382 |
| Negative predictions | 617 |
| Neutral predictions | 1 |
| Evaluation coverage | 1,999 |
| Accuracy on non-neutral predictions | 63.53% |

**Evaluation note:** The accuracy calculation covers 1,999 non-neutral predictions. The single neutral prediction is excluded from this accuracy calculation.

## Visualizations

The project generates the following visualizations:

1. **Predicted Sentiment Distribution** — Shows the distribution of positive, negative, and neutral predictions.
2. **VADER Confusion Matrix** — Compares the predicted sentiment labels with the original dataset labels.

## Output Files

The notebook generates the following files:

| File | Description |
|---|---|
| `sentiment_predictions.csv` | Review-level sentiment predictions |
| `classification_report.csv` | Classification evaluation metrics |
| `confusion_matrix.csv` | Confusion matrix values |
| `confusion_matrix.png` | Confusion matrix visualization |
| `evaluation_summary.csv` | Summary of evaluation results |
| `sentiment_distribution.png` | Predicted sentiment distribution chart |

## Project Notebook

`CodeAlpha_SentimentAnalysis.ipynb`

The notebook contains the complete implementation, sentiment predictions, evaluation, and visualizations.

## How to Run the Project

1. Open `CodeAlpha_SentimentAnalysis.ipynb` in Google Colab or Jupyter Notebook.
2. Run the notebook cells sequentially.
3. Install the required Python packages if prompted.
4. Allow the notebook to download the NLTK dataset if required.
5. Review the sentiment predictions, evaluation results, and generated visualizations.

## Internship Details

- **Organization:** CodeAlpha
- **Domain:** Data Analytics
- **Batch:** October Batch
- **Task:** Task 3 — Sentiment Analysis

## Acknowledgement

- NLTK Movie Reviews Dataset
- VADER Sentiment Analysis Tool
- CodeAlpha Data Analytics Internship

## Author

**Parsha Kamali**

GitHub: [kamaliparsha](https://github.com/kamaliparsha)

---

This project was developed for educational purposes as part of the CodeAlpha Data Analytics Internship.
