# Fake News Text Classification Case Study

## Project Overview

This repository contains a DS 4002 case study package designed for 2nd-year UVA students. The case study guides students through reproducing a fake news detection project using text classification. The original project uses article text and headlines from a fake/real news dataset to train a machine learning model that predicts whether an article is real or fake.

The goal of this case study is not to create a perfect misinformation detector. Instead, the goal is to help students understand how raw text data can be cleaned, transformed into numerical features, modeled, evaluated, and interpreted responsibly.

## Case Study Question

How can we build a simple model to classify real vs. fake news while staying honest about the limits of automated misinformation detection?

## Repository Purpose

This repository is meant to serve as a complete case study package. It includes the materials needed for a student to understand the project, reproduce the workflow, and create their own final report, notebook, or slide deck explaining the analysis.

Students should use this repository to:

- understand the fake news classification problem
- load and prepare the fake/real news dataset
- reproduce exploratory data analysis outputs
- convert article text into numerical features using TF-IDF
- train a logistic regression classifier
- evaluate model performance
- discuss limitations and possible improvements

## Repository Contents

├── Hook_Document.pdf
├── Rubric.pdf
├── References.pdf
├── DATA/
├── SCRIPTS/
├── OUTPUT/
└── MATERIALS/

## File and Folder Descriptions

### `Hook_Document.pdf`
Introduces the case study scenario, places the student in the role of a junior data analyst, and explains the high-level mission.

### `Rubric.pdf`
Explains the purpose, task, deliverables, and criteria for completing the case study.

### `References.pdf`
Lists background sources and documentation related to fake news detection, TF-IDF, logistic regression, and text classification.

### `DATA/`
Contains the dataset files or instructions for accessing the fake/real news dataset.

### `SCRIPTS/`
Contains the Python scripts or notebooks used to reproduce the workflow.

### `OUTPUT/`
Contains project outputs such as EDA visuals, model results, classification reports, and confusion matrices.

### `MATERIALS/`
Contains supporting materials, reference links, and background readings.

## Methods Used

- Exploratory Data Analysis
- Text preprocessing
- TF-IDF feature extraction
- Logistic regression classification
- Train/test split
- Model evaluation using classification metrics
- Responsible interpretation of model limitations

## How to Use This Repository

1. Read `Hook_Document.pdf` to understand the case study scenario.
2. Review `Rubric.pdf` to understand the expected final deliverable.
3. Open the dataset or dataset instructions in the `DATA/` folder.
4. Run or review the code in the `SCRIPTS/` folder.
5. Compare your results to the materials in the `OUTPUT/` folder.
6. Use `References.pdf` and the `MATERIALS/` folder to better understand the methods.
7. Create your own final report, notebook, or slide deck explaining the reproduced project.

## Expected Student Deliverable

After working through this case study, students should create a final report, notebook, or slide deck that explains the reproduced workflow from beginning to end.

The final product should include:

1. Project motivation and context
2. Dataset description
3. Data cleaning and preprocessing explanation
4. Exploratory data analysis findings
5. TF-IDF feature extraction explanation
6. Logistic regression model results
7. Model evaluation and interpretation
8. Discussion of limitations and possible improvements

## Notes on Interpretation

This project should be interpreted carefully. A fake news classifier can learn patterns in article text, but it does not truly understand truth, context, or credibility. High accuracy does not automatically mean the model is reliable in every real-world setting.

Important limitations to consider include dataset bias, overfitting, changing language patterns over time, false positives and false negatives, and limited generalizability to new sources or future news articles.

## Author

Created by Adrian Velez for DS 4002: Data Science Project Course.
