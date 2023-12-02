# Fine-Tuning BERT for Named Entity Recognition

This repository contains a project where a pre-trained BERT model is fine-tuned for the task of Named Entity Recognition (NER) in Arabic. It demonstrates the process of adapting a BERT model to a specific NER task, using the `aubmindlab/bert-base-arabertv02` model and the Polyglot-NER dataset.

## Overview

Named Entity Recognition is a common task in natural language processing that involves identifying named entities (like names of people, organizations, locations, etc.) in text. This code showcases how to fine-tune a pre-trained BERT model specifically for NER in Arabic. The code fine-tunes the model 3 times. One with 1k examples, two with 3k examples, 3 with 3k examples and freezing the embedding layers of the pretrained model..

## Repository Structure

- `FineTune_BERT.ipynb`: Jupyter notebook containing the entire process of fine-tuning the BERT model, including data preparation, model training, and evaluation.
- `requirements.txt`: List of Python packages required to run the notebook.


