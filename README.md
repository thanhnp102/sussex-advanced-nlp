# Propaganda Detection

This repository contains the submission for the Advanced Natural Language Processing (ANLP) module assignment as part of my master's degree coursework. The assignment focuses on the challenging task of propaganda detection using various machine learning approaches.

## Assignment Overview

### Task Description
The assignment consists of two main tasks:
1. **Propaganda Presence Detection**: Develop and evaluate at least two approaches to classify whether a sentence contains propaganda or not.
2. **Propaganda Technique Classification**: Given a snippet of text that contains propaganda, classify the specific propaganda technique used.

The approaches explored in this assignment include traditional machine learning methods and advanced pre-trained language models. The report provides an in-depth analysis and comparison of these methods.

### Dataset
The provided dataset contains sentences labeled with one of nine possible classes, including eight propaganda techniques and a "not propaganda" label. The dataset is split into training and testing sets, which are used to build and evaluate the models.

### Methods Implemented
- **Bag-of-Words (BoW) Approach**: A traditional method that represents sentences as collections of word frequencies, using this representation as input for various classifiers such as Logistic Regression, Naïve Bayes, Random Forest, and Support Vector Machines (SVM).
- **Pre-trained Language Models (PLMs)**: A more advanced approach leveraging a fine-tuned BERT model to capture rich semantic information for both propaganda detection and technique classification tasks.

## Results Summary
- The fine-tuned BERT model significantly outperformed traditional Bag-of-Words approaches, achieving high accuracy in both propaganda presence detection (95% accuracy) and technique classification tasks.
- The analysis includes a detailed comparison of models based on accuracy, precision, recall, and F1 scores, highlighting the strengths and weaknesses of each approach.

## Repository Structure
- `Report.pdf`: The main report, written in the style of an academic paper, includes the introduction, related work, methodology, experimental results, and conclusions. The report discusses the approaches used, hyper-parameter settings, evaluation methods, and error analysis.
- `Code_Appendix.ipynb`: The Jupyter notebook with the full analysis.
- `propaganda_dataset_v2/`: Folder containing the training and test datasets in TSV format.

