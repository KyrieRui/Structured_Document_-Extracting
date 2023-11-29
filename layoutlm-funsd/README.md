---
base_model: microsoft/layoutlm-base-uncased
tags:
- generated_from_trainer
datasets:
- funsd
model-index:
- name: layoutlm-funsd
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# layoutlm-funsd

This model is a fine-tuned version of [microsoft/layoutlm-base-uncased](https://huggingface.co/microsoft/layoutlm-base-uncased) on the funsd dataset.
It achieves the following results on the evaluation set:
- Loss: nan
- Answer: {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 809}
- Header: {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 119}
- Question: {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 1065}
- Overall Precision: 0.0
- Overall Recall: 0.0
- Overall F1: 0.0
- Overall Accuracy: 0.2750

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 2e-05
- train_batch_size: 8
- eval_batch_size: 8
- seed: 42
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: linear
- num_epochs: 15

### Training results

| Training Loss | Epoch | Step | Validation Loss | Answer                                                      | Header                                                      | Question                                                     | Overall Precision | Overall Recall | Overall F1 | Overall Accuracy |
|:-------------:|:-----:|:----:|:---------------:|:-----------------------------------------------------------:|:-----------------------------------------------------------:|:------------------------------------------------------------:|:-----------------:|:--------------:|:----------:|:----------------:|
| 0.0           | 1.0   | 19   | nan             | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 809} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 119} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 1065} | 0.0               | 0.0            | 0.0        | 0.2750           |
| 0.0           | 2.0   | 38   | nan             | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 809} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 119} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 1065} | 0.0               | 0.0            | 0.0        | 0.2750           |
| 0.0           | 3.0   | 57   | nan             | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 809} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 119} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 1065} | 0.0               | 0.0            | 0.0        | 0.2750           |
| 0.0           | 4.0   | 76   | nan             | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 809} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 119} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 1065} | 0.0               | 0.0            | 0.0        | 0.2750           |
| 0.0           | 5.0   | 95   | nan             | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 809} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 119} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 1065} | 0.0               | 0.0            | 0.0        | 0.2750           |
| 0.0           | 6.0   | 114  | nan             | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 809} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 119} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 1065} | 0.0               | 0.0            | 0.0        | 0.2750           |
| 0.0           | 7.0   | 133  | nan             | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 809} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 119} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 1065} | 0.0               | 0.0            | 0.0        | 0.2750           |
| 0.0           | 8.0   | 152  | nan             | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 809} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 119} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 1065} | 0.0               | 0.0            | 0.0        | 0.2750           |
| 0.0           | 9.0   | 171  | nan             | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 809} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 119} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 1065} | 0.0               | 0.0            | 0.0        | 0.2750           |
| 0.0           | 10.0  | 190  | nan             | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 809} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 119} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 1065} | 0.0               | 0.0            | 0.0        | 0.2750           |
| 0.0           | 11.0  | 209  | nan             | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 809} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 119} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 1065} | 0.0               | 0.0            | 0.0        | 0.2750           |
| 0.0           | 12.0  | 228  | nan             | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 809} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 119} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 1065} | 0.0               | 0.0            | 0.0        | 0.2750           |
| 0.0           | 13.0  | 247  | nan             | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 809} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 119} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 1065} | 0.0               | 0.0            | 0.0        | 0.2750           |
| 0.0           | 14.0  | 266  | nan             | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 809} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 119} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 1065} | 0.0               | 0.0            | 0.0        | 0.2750           |
| 0.0           | 15.0  | 285  | nan             | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 809} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 119} | {'precision': 0.0, 'recall': 0.0, 'f1': 0.0, 'number': 1065} | 0.0               | 0.0            | 0.0        | 0.2750           |


### Framework versions

- Transformers 4.35.2
- Pytorch 2.2.0.dev20231123
- Datasets 2.15.0
- Tokenizers 0.15.0
