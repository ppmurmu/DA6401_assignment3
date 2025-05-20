# 🧠 DA6401 - Assignment 3 

This repository consists of following files:

## Vanilla RNN
- 📓 `vanilla_seq2seq.ipynb` : Python notebook file that contains experiments ran to train the vanilla sequence to sequence model.
- `predictions_vanilla.csv` : CSV file with output on test data with best model (vanilla)

## Attention RNN
- 📓 `attention_seq2seq.ipynb` : Python notebook file that contains experiments ran to train the attention sequence to sequence model.
-  `predictions_attention.csv` : CSV file with output on test data with best model (attention)


## 📊 Report
Report is available on wandb: 
[Click here](https://wandb.ai/cs24m033-iit-madras/DA6401-A3/reports/Assignment-3--VmlldzoxMjgwNTE2Nw?accessToken=5nqcxf6p738qfze3yr0kwl22ifb76655apqairok5rgj4ygfu9jqij5j5j51mfu7)
or
https://wandb.ai/cs24m033-iit-madras/DA6401-A3/reports/Assignment-3--VmlldzoxMjgwNTE2Nw?accessToken=5nqcxf6p738qfze3yr0kwl22ifb76655apqairok5rgj4ygfu9jqij5j5j51mfu7

## 🎯 About the assignment
The goal is to build a model that takes a romanized string as input (e.g., "ghar") and produces the corresponding word in Devanagari (e.g., "घर").

## 🧬 About the dataset
We use the Dakshina dataset provided by Google Research, which contains word pairs in the following format:
Latin script (romanized version)
Native script (Devanagari or other Indian scripts)
