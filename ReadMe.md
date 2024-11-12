ICPC
├── codes
│   ├── dataset_utils.py: contains helper functions
│   ├── dpo_clean1.py: script to dpo fine-tune a model except phi model
│   ├── dpo_clean1phi.py: script to dpo fine-tune a phi3.5-mini-Instruct
│   ├── dpo_dataset_create.sh: bash script to generate dpo dataset
│   ├── dpo_sys_prompt.txt: text file which has system prompt for dpo
│   ├── dpotrain.sh: bash script to fine-tune a model
│   ├── few_shot_sys_prompt.txt: text file which has system prompt for few-shot
│   ├── grade_utils.py: contains helper functions for grading.py
│   ├── grading.py: script used to grade the test datapoints 
│   ├── lora_clean.py: scipt to lora fine-tune a model 
│   ├── lora_dataset_create.sh: bash script which generates lora dataset
│   ├── lora_sys_prompt.txt: text file which has system prompt for lora
│   ├── lora_utils.py: contains helper functions for grading.py
│   ├── loratrain.sh: bash script to lora fine-tune model using lora_clean
│   ├── model_utils.py: contains helper functions for grading.py
│   ├── scramble-code.py: script to scramble code
│   ├── Untitled document
│   ├── utils.py: contains helper functions for grading.py
│   └── zero_shot_sys_prompt.txt: text file which has system prompt for zero-shot
├── Dataset_Augmentation
│   ├── __pycache__
│   ├── crit-desc
│   ├── crit-ratings
│   ├── dataset-CA
│   ├── images
│   ├── CA.py
│   ├── code_utils.py
│   ├── dpo_clean.py
│   ├── README.md
│   └── requirements.txt
├── Encoder Codes
│   ├── GraphCodeBERT_codes
│   │   ├── dataset
│   │   │   ├── create_dataset.sh
│   │   │   └── create_test_dataset.py
│   │   ├── metrics
│   │   │   ├── create_metrics_dataset.py
│   │   │   ├── micro_results.py
│   │   │   └── rating_wise_confusion_metrics.py
│   │   └── train_graphcodebert.py
│   ├── UniXcoder_codes
│   │   ├── dataset
│   │   │   ├── create_dataset.sh
│   │   │   └── create_test_dataset.py
│   │   ├── metrics
│   │   └── train_unixcoder.py
├── Test Dataset
│   ├── seen test dataset
│   └── unseen test dataset
├── Trained Models
│   ├── codestral-22B DPO
│   ├── granite-8-coder-Instruct-4k DPO
│   ├── phi-3.5-min-Instruct DPO
│   └── qwen-2.5-coder-Instruct DPO

