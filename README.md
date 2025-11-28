# Text Classification with XLNet

This repository contains a Jupyter notebook includes data cleaning, dataset preparation, tokenization, HuggingFace Datasets, model fine-tuning, and accuracy evaluation using Trainer API.

---

## 🚀 Highlights / Features

## 🔹 Data preprocessing

✨ Cleaning raw text

✨ Removing unwanted patterns (emojis, mentions, URLs)

✨Handling whitespace, special characters, and noise

## 🔹 Dataset balancing

✨ Addressing class imbalance

✨ Undersampling based on smallest label count

✨ Ensuring equal representation of each class


## 🔹 Train–Validation–Test splitting

✨Creating separate datasets for training, tuning, and evaluating

✨ Ensuring reproducibility using random_state

## 🔹 Creating HuggingFace Datasets

✨ Converting Pandas DataFrames → Dataset objects

✨ Building a DatasetDict for train/test organization

## 🔹 Tokenization

✨ How XLNet tokenizes text

Understanding: 
-- input_ids
-- attention_mask
-- token truncation (max_length)
-- padding (max_length and batch padding)

## 🔹 Model Fine-Tuning

✨ Loading XLNetForSequenceClassification

✨ Defining label mappings (num_labels, id2label)

✨ Training using the Trainer API

## 🔹 Evaluation

✨ Using HuggingFace evaluate library

✨ Understanding logits, predictions, accuracy

✨ Using compute_metrics to integrate evaluation into training

## 🔹 Debugging & Experimentation

✨ Creating smaller subsets for faster testing

✨ How .shuffle() and .select() help debug models quickly
