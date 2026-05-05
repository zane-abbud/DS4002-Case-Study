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
- access the fake/real news dataset instructions
- review and run the project code
- reproduce exploratory data analysis outputs
- convert article text into numerical features using TF-IDF
- train a logistic regression classifier
- evaluate model performance
- discuss limitations and possible improvements

## Repository Contents

    .
    ├── Supplemental_Materials/
    ├── Hook.pdf
    ├── Rubric.pdf
    └── README.md

## File and Folder Descriptions

### `Supplemental_Materials/`

Contains the materials needed to reproduce and understand the case study. This folder may include dataset instructions, project scripts or notebooks, reference links, background articles, technical documentation, and other supporting resources.

Suggested materials in this folder include:

- `Dataset_Instructions.md`
- project scripts or notebooks
- `News_Literacy_Explainer.md`
- `Text_Classification_Technical_Resource.md`
- `References.md`

### `Hook.pdf`

Introduces the case study scenario, places the student in the role of a junior data analyst, explains the motivation for fake news detection, and gives the student a high-level mission.

### `Rubric.pdf`

Explains the purpose, task, deliverables, and criteria for completing the case study. This document should be used to guide the student’s final report, notebook, or slide deck.

### `README.md`

Provides an overview of the repository and instructions for using the case study materials.

## Methods Used

This case study uses the following methods:

- Exploratory Data Analysis
- Text preprocessing
- TF-IDF feature extraction
- Logistic regression classification
- Train/test split
- Model evaluation using classification metrics
- Responsible interpretation of model limitations

## How to Use This Repository

1. Read `Hook.pdf` to understand the case study scenario and your role.
2. Review `Rubric.pdf` to understand the task, criteria, and expected final product.
3. Open `Supplemental_Materials/` to access the dataset instructions, scripts, references, and background materials.
4. Follow the dataset instructions to download or locate the fake/real news dataset.
5. Run or review the project scripts or notebooks provided in `Supplemental_Materials/`.
6. Reproduce the major workflow steps: data preparation, EDA, TF-IDF feature extraction, logistic regression modeling, and evaluation.
7. Use the supplemental readings and documentation to better understand fake news detection, text classification, TF-IDF, logistic regression, and model interpretation.
8. Create your own final report, notebook, or slide deck explaining the reproduced project.

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

Important limitations to consider include:

- dataset bias
- overfitting
- changing language patterns over time
- dependence on word patterns rather than actual truth
- false positives and false negatives
- limited generalizability to new sources or future news articles

## Author

Created by Adrian Velez for DS 4002: Data Science Project Course.

## Acknowledgements

This case study was created as part of DS 4002 and is based on a previous course project focused on fake news text classification.
