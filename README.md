# Natural Language Generation using Transformer


This repository contains an implementation of a GPT-style language model using PyTorch. The model is designed to handle character-level tokenization and utilizes a Transformer architecture for natural language processing tasks. This specific implementation is focused on predicting the type of graph based on a given query.


# Instructions to Run the Project


Follow the steps below to run the project:

### Step 1: Run the `data-extract.py` file
This script will extract the necessary data for training the model.

```bash
python data-extract.py 
```
### Step 2: Run the `training.py` file

After extracting the data, run the training script to train the model.Please ensure that your comment down  the pickle section in training.p
Ensure that the batch-size is passed with the command (Ex: -batch_size 32)
```bash
python training.py 
```
### Step 3: Run the `gpt.py` file
Finally, run the gpt.py file to use the trained model for generating responses.
Ensure that the batch-size is passed with the command (Ex: -batch_size 32)
```bash
python gpt.py
```
# Acknowledgments

Special thanks to Elliotcodes for helping me understand the architecture of GPT-style models.






