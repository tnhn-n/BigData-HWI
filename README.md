# Stylometric Analysis of Balzac's Works

This project explores the stylistic and linguistic features of Honoré de Balzac’s literary texts using Natural Language Processing (NLP) and statistical visualization. It includes readability metrics, part-of-speech (POS) tagging, type-token ratio (TTR) analysis, and word cloud generation — all applied to a corpus of Balzac's novels.

The analysis is performed using Python and visualized in a Quarto report (`.qmd`) rendered to HTML.

## Features

- **Flesch-Kincaid Readability Scores** (based on average word and sentence lengths)
- **Average Sentence and Word Lengths**
- **POS Distribution** per text (nouns, verbs, adjectives, adverbs)
- **Type-Token Ratio** for lexical richness
- **Global Word Cloud** of the most frequent lemmatized terms
- **Altair visualizations** of all the metrics
- **Reproducible Quarto report**

## Visuals

The report includes interactive charts (via Altair) and a high-res word cloud that help interpret stylistic variations across selected works.


## Setup Instructions

These steps allow you to recreate the environment and render the report.

1. **Clone the Repository**
   ```bash
   git clone https://github.com/tnhn-/BigData-HWI.git
   cd BigData-HWI

2.Install Required Packages
pip install -r requirements.txt

3. Download spaCy Language Model
python -m spacy download fr_core_news_sm

4. Render the Quarto Report
quarto render my_report.qmd --to html



# License

MIT License. See LICENSE file for details.

---