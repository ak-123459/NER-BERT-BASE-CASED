# University Named Entity Recognition (NER) with BERT

This repository contains code to fine-tune the `bert-base-cased` model for Named Entity Recognition (NER) on university-related data, targeting entities such as department names, course titles, and academic roles.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Requirements](#requirements)
4. [Setup](#setup)
5. [Training the Model](#training-the-model)
6. [Evaluating the Model](#evaluating-the-model)
7. [Inference](#inference)
8. [Results](#results)
9. [Acknowledgments](#acknowledgments)

## Project Overview

This project fine-tunes `bert-base-cased` for Named Entity Recognition (NER) on university data to identify specific entities in academic text. This model is useful for processing university documents and extracting structured information.

#  <a href="https://imgbb.com/"><img src="https://i.ibb.co/D9vKsxH/dataset.png" alt="dataset" border="0"  width="50"></a> Dataset

The dataset should contain labeled examples with tokens, labels, and annotations for entities relevant to university text. The labeling follows the BIO format (e.g., `B-BRANCH`, `I-BRANCH`, `O`).

**Example Format**:
```plaintext
Token    Label
Computer B-BRANCH
Science  I-BRANCH
is       O
a        O
subject  O
