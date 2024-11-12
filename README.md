# ICPC

![Dataset Augmentation](images/algorithm-flow.png "Dataset Augmentation Flow Diagram")

# Dataset Augmentation Pipeline

This system generates code samples that align with a desired rating description. It takes the following inputs:
1. **Problem Statement**
2. **Criterion Description**
3. **Desired Rating Description**

The system uses:
- **Code Generating LLM (LMCG)** to generate code.
- **Quality Scoring LLM (LMQS)** to evaluate and score the generated code.

---

## Steps to Run

### Execution Information

**Requirements**:
- `Transformers`
- `PEFT`
- `Torch`

**Note**: Update code parameters such as paths (e.g., where the code is crawled) before running.

---

### 1. Set Up the Working Directory

Change your working directory to:
cd ICPC/Code_Augmentation

### 2. Set Up the virtual Environment

$ python -m venc venv

### 3. Installing Dependencies

$ source venv/bin/activate

$ pip install -r requirments.txt

### 4. Starting the Dataset Augmentation pipeline

$ python CA.py

## Output 

Check ICPC/code_augmentation/CA/datasets for the generated datasets

Check ICPC/code_augmentation/CA/models for the DPO fine-tuned models on the generated datasets


