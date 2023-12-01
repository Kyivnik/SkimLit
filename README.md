# SkimLit 🤓🔥 - NLP Sequential Sentence Classification
Welcome to SkimLit, a project focused on creating a Natural Language Processing (NLP) model for classifying abstract sentences into their respective roles, such as objective, methods, results, etc. This enables researchers to skim through vast amounts of literature quickly and dive deeper when necessary.

## Overview
In this project, we'll build our largest NLP model by replicating the deep learning architecture introduced in the 2017 paper, "PubMed 200k RCT: a Dataset for Sequential Sentence Classification in Medical Abstracts." The dataset used consists of ~200,000 labeled Randomized Controlled Trial (RCT) abstracts, aimed at exploring the ability of NLP models to classify sentences in sequential order within medical abstracts.

## Project Goals
Download the Dataset: We start by fetching the PubMed RCT200k dataset from GitHub.

Data Preprocessing: Develop a preprocessing function to prepare the dataset for modeling, including tasks like tokenization and embedding creation.

Modeling Experiments: Set up a series of modeling experiments, starting with a baseline TF-IDF classifier and progressively exploring deep models. This includes variations in token embeddings, character embeddings, pretrained embeddings, positional embeddings, and eventually constructing a multimodal model.

Replicating Paper Architecture: Replicate the model architecture presented in the paper PubMed 200k RCT: a Dataset for Sequential Sentence Classification in Medical Abstracts.

Identify Most Wrong Predictions: Develop a mechanism to find the most inaccurate predictions made by the model.

Prediction on Wild Data: Apply the trained model to predict roles of sentences in PubMed abstracts from external sources.

## Background
Before delving into the code, it's recommended to go through the following papers:

[PubMed 200k RCT: a Dataset for Sequential Sentence Classification in Medical Abstracts](Where our data is coming from: PubMed 200k RCT: a Dataset for Sequential Sentence Classification in Medical Abstracts)

Neural networks for joint sentence classification in medical paper abstracts (Where our model architecture is coming from)

## Problem Statement
The increasing number of RCT papers, especially those without structured abstracts, poses a challenge for researchers. These papers can be difficult to read, potentially slowing down the process of extracting valuable information from the literature.

## Solution
SkimLit proposes an NLP model to classify abstract sentences into their roles, allowing researchers to quickly skim through literature. This approach aims to facilitate efficient information retrieval and enable researchers to delve deeper when necessary.

This project was in the course of TensorFlow







