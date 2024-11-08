<div align="center">

  <a href="https://imgbb.com/"><img src="https://i.ibb.co/5LHZgs5/natural-language-processing.png" alt="natural-language-processing" border="0"></a><br /><a target='_blank' href='https://imgbb.com/'></a> 
  ## University Named Entity Recognition (NER) with BERT
</div> 

<br></br>

This repository contains code to fine-tune the `bert-base-cased` model for Named Entity Recognition (NER) on university-related data, targeting entities such as department names, course titles, and academic roles.

## **Table of Contents**
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Requirements](#requirements)
4. [Setup](#setup)
5. [Training the Model](#training-the-model)
6. [Evaluating the Model](#evaluating-the-model)
7. [Inference](#inference)
8. [Results](#results)

## **Project Overview**

This project fine-tunes `bert-base-cased` for Named Entity Recognition (NER) on university data to identify specific entities in academic text. This model is useful for processing university documents and extracting structured information.

###  <a href="https://imgbb.com/"><img src="https://i.ibb.co/D9vKsxH/dataset.png" alt="dataset" border="0"  width="50"></a> Dataset

The dataset should contain labeled examples with tokens, labels, and annotations for entities relevant to university text. The labeling follows the BIO format (e.g., `B-BRANCH`, `I-BRANCH`, `O`).

**Example Format**:
```plaintext
Token    Label
Computer B-BRANCH
Science  I-BRANCH
is       O
a        O
subject  O
```

<br></br>


3. [Requirements](#requirements)


<div id="badges" align="start">

  <a >
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="tensorflow"/>
  </a>


   <a >
    <img src="https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252" alt="colab"/>

     
  </a>

   <a >
    <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="tensorflow"/>

  </a>
 
</div>


<a >
<img src="https://i.ibb.co/k2F2Bgz/llms-800x800.png" alt="llms-800x800" border="0"  width="100"/>
  </a>



  4. [Acknowledgments](#acknowledgments)

During overall training how to load dataset ,prepare dataset,tokenized dataset and how to train the model and after how to evaluate the model.we test and validate model on both test and validations dataset we can run multiple epochs to decreased the validation loss.


# Note:- For More details about how to fine tune bert-base-case please check the google colab notebook.



