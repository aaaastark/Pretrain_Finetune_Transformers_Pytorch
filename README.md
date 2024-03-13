# **Pre Train and Fine Tune the Transformers with Pytorch**
<br>

| Name 	| Description 	| Links 	|
|:- |:- |:- |
| **:dog: Pretrain Transformer in PyTorch using Hugging Face Transformers** | *Pretrain 67 transformers models on your custom dataset.* |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aaaastark/Pretrain_Finetune_Transformers_Pytorch/blob/master/PreTrain_Transformers_Pytorch.ipynb) [![Generic badge](https://img.shields.io/badge/GitHub-Source-greensvg)](https://github.com/aaaastark/Pretrain_Finetune_Transformers_Pytorch/blob/master/PreTrain_Transformers_Pytorch.ipynb) |
| **:violin: Fine-tune Transformers in PyTorch using Hugging Face Transformers** | *Complete tutorial on how to fine-tune 73 transformer models for text classification — no code changes necessary!* |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aaaastark/Pretrain_Finetune_Transformers_Pytorch/blob/master/FineTune_Transformers_Pytorch.ipynb) [![Generic badge](https://img.shields.io/badge/GitHub-Source-greensvg)](https://github.com/aaaastark/Pretrain_Finetune_Transformers_Pytorch/blob/master/FineTune_Transformers_Pytorch.ipynb)|

<br>

## **Fine Tuning Transformer with Pytorch**

> This guide provides instructions on fine-tuning pre-trained transformers models for classification tasks using PyTorch and the Hugging Face Transformers library. It emphasizes code implementation and adaptability to various needs.

Key points include:

- The tutorial utilizes the AutoClasses feature from the Hugging Face Transformers library, enabling automatic detection of a model's configuration, tokenizer, and architecture based solely on the model's name.
- Prerequisites for using the notebook include basic Python coding knowledge and familiarity with PyTorch and the Transformers library.
- The notebook is structured for reusability, with instructions on how to load different datasets and adapt the code for various classification tasks.
- Basic parameters such as epochs, batch size, max_length, model_name_or_path, and labels_ids are defined.
- The notebook supports various transformer models beyond BERT for classification tasks, with compatibility tested across multiple pre-trained models.
- The dataset used for demonstration is the Large Movie Review Dataset for sentiment analysis, comprising 25,000 polar movie reviews for training and testing.

**Overall, the guide provides a comprehensive approach to fine-tuning transformers models for classification tasks, with a focus on practical implementation and flexibility.**

<br>

## **Pre Training Transformer with Pytorch** 

> This notebook serves as a guide for training transformer models using the Hugging Face Transformers library with a custom dataset. It aims to facilitate both fine-tuning pretrained models and training models from scratch. The tutorial emphasizes reusability and provides detailed explanations for each code cell.

Key aspects of the notebook include:

1. **Prequisites**: Familiarity with PyTorch and the Transformers library is beneficial. The notebook primarily deals with raw text data for training or fine-tuning transformers models. Labeled data is not required.

2. **Utilization**: The notebook can be easily adapted for different datasets by modifying file paths. It includes a custom function, `movie_reviews_to_file`, for processing the dataset into a text file.

3. **Compatibility**: The notebook is compatible with various transformer model architectures available on Hugging Face Transformers. It has been tested with 67 pretrained models, ensuring seamless functionality.

4. **Dataset**: The notebook focuses on pretraining transformers on the Large Movie Review Dataset, which consists of 25,000 labeled movie reviews for sentiment classification. This dataset is chosen for its simplicity and engagement.

5. **Coding**: The notebook provides detailed explanations of each code cell, describing its purpose, code contents, and relevant outputs. It is formatted for easy replication of results.

**Overall, the notebook offers a comprehensive guide for training transformers models on custom datasets using PyTorch and Hugging Face Transformers, promoting reusability and understanding through detailed explanations.**
