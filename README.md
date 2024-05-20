# TriviaQA-Fine-tuning-with-BERT
Introduction
This repository contains code for fine-tuning the BERT model on the TriviaQA dataset for question answering (QA) tasks. The TriviaQA dataset consists of trivia questions along with corresponding answers and contexts. The goal is to train a QA model that can accurately answer questions based on the provided context.

What's Included
train.py: Python script for fine-tuning BERT on a subset of the TriviaQA dataset and evaluating the model on a validation set.
evaluate.py: Python script for evaluating a fine-tuned BERT model on a validation set and computing performance metrics such as Exact Match (EM) and F1 score.
requirements.txt: File listing the required Python packages and their versions for running the scripts.
README.md: This file providing an overview of the repository and instructions for usage.
Getting Started
Clone the Repository: Clone this repository to your local machine using git clone https://github.com/SulemanShahani/triviaqa-finetuning.git.
Install Dependencies: Install the required Python packages by running pip install -r requirements.txt.
Fine-tune BERT: Run the train.py script to fine-tune the BERT model on a subset of the TriviaQA dataset. You can specify the number of epochs and other training parameters in the script.
Evaluate Model: After training, run the evaluate.py script to evaluate the fine-tuned model on a validation set. This script computes performance metrics such as Exact Match (EM) and F1 score.
Usage
bash
Copy code
# Fine-tune BERT
python train.py

# Evaluate fine-tuned model
python evaluate.py
Results
After evaluation, the performance metrics (e.g., EM, F1 score) will be printed to the console.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
This project is based on the Hugging Face Transformers library.
The TriviaQA dataset is provided by the Allen Institute for AI.
