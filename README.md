# Semantic Textual Similarity for [Symbolic Goal Learning: Symbolic Goal Learning for Human Instruction Following in Robot Manipulation](https://github.com/ivalab/mmf)
This repository is for pretraining BERT model on semantic textual similarity task for symbolic goal learning for robotic manipulation tasks. 

## Installation
This repository is based on [sentence-transformers](https://github.com/UKPLab/sentence-transformers). For installation, you could refer to the official document.

## Usage
To pretrain BERT model on semantic textual similarity task for explicit human instructions and intents, we need to first create a folder named datasets and download the proposed dataset from [Smartech](). Unzip the file under "datasets" folder. Run the following command to train the model

```
python examples/training/sts/training_gt_rt_exim_ranked_para_bert_base_uncased.py
```
