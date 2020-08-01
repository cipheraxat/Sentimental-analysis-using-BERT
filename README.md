# Sentimental-analysis-using-BERT


### Prerequisites

- Intermediate-level knowledge of Python 3 (NumPy and Pandas preferably, but not required)
- Exposure to PyTorch usage
- Basic understanding of Deep Learning and Language Models (BERT specifically)


### Project Outline

**Step 1**: Introduction (this section)

**Step 2**: Exploratory Data Analysis and Preprocessing

**Step 3**: Training/Validation Split

**Step 4**: Loading Tokenizer and Encoding our Data

**Step 5**: Setting up BERT Pretrained Model

**Step 6**: Creating Data Loaders

**Step 7**: Setting Up Optimizer and Scheduler

**Step 8**: Defining our Performance Metrics

**Step 9**: Creating our Training Loop

**Step 10**: Loading and Evaluating our Model


## Introduction

### What is BERT

BERT is a large-scale transformer-based Language Model that can be finetuned for a variety of tasks.

For more information, the original paper can be found [here](https://arxiv.org/abs/1810.04805). 

[HuggingFace documentation](https://huggingface.co/transformers/model_doc/bert.html)

[Bert documentation](https://characters.fandom.com/wiki/Bert_(Sesame_Street)) ;)


!(https://github.com/cipheraxat/Sentimental-analysis-using-BERT/blob/master/Images/BERT_diagrams.png)

## Exploratory Data Analysis and Preprocessing

I used the SMILE Twitter dataset.

_Wang, Bo; Tsakalidis, Adam; Liakata, Maria; Zubiaga, Arkaitz; Procter, Rob; Jensen, Eric (2016): SMILE Twitter Emotion dataset. figshare. Dataset. https://doi.org/10.6084/m9.figshare.3187909.v2_


## Defining our Performance Metrics

Accuracy metric approach originally used in accuracy function in [this tutorial](https://mccormickml.com/2019/07/22/BERT-fine-tuning/#41-bertforsequenceclassification).

## Creating our Training Loop

Approach adapted from an older version of HuggingFace's `run_glue.py` script. Accessible [here](https://github.com/huggingface/transformers/blob/5bfcd0485ece086ebcbed2d008813037968a9e58/examples/run_glue.py#L128).

