# Dataset Augmentation

![Dataset Augmentation](images/final_CA.png "Dataset Augmentation Flow Diagram")

# Dataset Augmentation Pipeline

This system generates code samples that align with a desired rating description. It takes the following inputs:
1. **Problem Statement**
2. **Criterion Description**
3. **Desired Rating Description**

The system uses:
- **Code Generating LLM (LM<sub>CG</sub>)** to generate code.
- **Quality Scoring LLM (LM<sub>QS</sub>)** to evaluate and score the generated code.

---

## Steps to Run

### Execution Information

**Requirements**:
- `Transformers`
- `PEFT`
- `Torch`

**Note**: Update code parameters such as paths (e.g., where the code is crawled) before running.

---

### 1. Starting the Dataset Augmentation pipeline

$ python CA.py

## Output 

Check ICPC/code_augmentation/CA/datasets for the generated datasets

Check ICPC/code_augmentation/CA/models for the DPO fine-tuned models on the generated datasets


