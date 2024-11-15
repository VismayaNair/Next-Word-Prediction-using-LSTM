# Next-Word-Prediction-using-LSTM

## AIM

To develop an LSTM-based model for predicting the next word in a text corpus.

## Problem Statement and Dataset
Build a neural network-based text generator to produce new sequences from a given corpus by tokenizing text, creating n-grams, padding sequences, and encoding labels.

DESIGN STEPS
STEP 1:
Use fit_vectorizer to initialize and fit a TextVectorization layer on the corpus for word-to-integer tokenization.

STEP 2:
Generate n-grams for each sentence using n_gram_seqs, creating sequential input data.

STEP 3:
Pad these sequences to a uniform length with pad_seqs, enabling consistent input shapes for training.

STEP 4:
Split each sequence into features and labels, where features contain all words except the last, and labels are the last word.

STEP 5:
One-hot encode the labels with a vocabulary size from total_words for categorical prediction.

STEP 6:
Construct a TensorFlow dataset with these features and labels, batching them for efficient processing.

STEP 7:
Build the model with an Embedding layer, Bidirectional LSTM for sequence processing, and Dense layer with softmax for word prediction.

STEP 8:
Compile and train the model using categorical cross-entropy loss and the Adam optimizer.
## PROGRAM
### Name:
### Register Number:

### 1.fit_vectorizer function
Include your code here

### 2. n_grams_seqs function
Include your code here

### 3. pad_seqs function
Include your code here

### 4. features_and_labels_dataset function
Include your code here

### 5.create_model function
Include your code here

## OUTPUT
### 1. fit_vectorizer output


### 2. n_grams_seqs output


### 3. pad_seqs output


### 4. features_and_labels_dataset output


### 5. Training Loss, Validation Loss Vs Iteration Plot

Include your plot here

### 6. Sample Text Prediction
Include your sample text prediction here.

## RESULT
