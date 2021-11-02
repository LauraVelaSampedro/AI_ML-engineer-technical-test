# AI infrastructure and ML engineer technical test

Description: Using one of the pretrained transformers available in huggingface, build a model
to learn how to classify healthcare claims, weeding the facts from the myths. Demonstrate the
performance of the final model.

## General Information

The task in this project is to use Transfer learning for text classification. Specifically, the objective is to build a classification model for health related claims, using one of the pretrained transforrmes available in Huggingface (https://huggingface.co/models). The model is intended to classify a health related claim according to its truthfulness.

The dataset used PUBHEALTH-Healt_fact is provided also by Hugghingface (https://huggingface.co/datasets/health_fact) and contains 12288 health related claims from various sources. Each claim has been labelled as 'true', 'false', 'mixture' or 'unproven' by professional fact checkers and health experts. The PUBHEALTH dataset contains the fields: 'claim_id', 'claim', 'date_published', 'explanation', 'fact_checkers', 'main_text', 'sources', 'label' and 'subjects'.

The resolution of the task has been developed in Google Colab. The file *AI_infrastructure_and_ML_engineer_technical_test_LauraVelaSampedro.ipynb* contains both the code and the execution results.

