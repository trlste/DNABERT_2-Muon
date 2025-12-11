---
library_name: transformers
tags:
- generated_from_trainer
datasets:
- leannmlindsey/GUE
model-index:
- name: DNABERT
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# DNABERT

This model was trained from scratch on the leannmlindsey/GUE virus_species_40 dataset.
It achieves the following results on the evaluation set:
- eval_loss: 8.4762
- eval_model_preparation_time: 0.0024
- eval_accuracy: 0.0001
- eval_runtime: 5.5231
- eval_samples_per_second: 361.572
- eval_steps_per_second: 22.632
- step: 0

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 3e-05
- train_batch_size: 32
- eval_batch_size: 16
- seed: 42
- optimizer: Use OptimizerNames.ADAMW_TORCH_FUSED with betas=(0.9,0.999) and epsilon=1e-08 and optimizer_args=No additional optimizer arguments
- lr_scheduler_type: linear
- lr_scheduler_warmup_steps: 50
- num_epochs: 1.0
- mixed_precision_training: Native AMP

### Framework versions

- Transformers 4.57.3
- Pytorch 2.9.0+cu126
- Datasets 4.0.0
- Tokenizers 0.22.1
