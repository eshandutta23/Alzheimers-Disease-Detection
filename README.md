---
dataset_info:
  features:
  - name: image
    dtype: image
  - name: label
    dtype:
      class_label:
        names:
          '0': Mild_Demented
          '1': Moderate_Demented
          '2': Non_Demented
          '3': Very_Mild_Demented
  splits:
  - name: train
    num_bytes: 22560791.2
    num_examples: 5120
  - name: test
    num_bytes: 5637447.08
    num_examples: 1280
  download_size: 28289848
  dataset_size: 28198238.28
license: apache-2.0
task_categories:
- image-classification
language:
- en
tags:
- medical
pretty_name: Alzheimer_MRI Disease Classification Dataset
size_categories:
- 1K<n<10K
---
# Alzheimer_MRI Disease Classification Dataset

The Falah/Alzheimer_MRI Disease Classification dataset is a valuable resource for researchers and health medicine applications. This dataset focuses on the classification of Alzheimer's disease based on MRI scans. The dataset consists of brain MRI images labeled into four categories:

- '0': Mild_Demented
- '1': Moderate_Demented
- '2': Non_Demented
- '3': Very_Mild_Demented

## Dataset Information

- Train split:
  - Name: train
  - Number of bytes: 22,560,791.2
  - Number of examples: 5,120

- Test split:
  - Name: test
  - Number of bytes: 5,637,447.08
  - Number of examples: 1,280
