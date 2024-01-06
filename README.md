# DeepWalk

This repository aims to reproduce the DeepWalk method as originally presented in the paper titled "DeepWalk: Online Learning of Social Representations".

## Files Overview:

### 1. deepwalk.ipynb:
   - Designed for datasets loaded in .csv files.
   - Contains the primary implementation of the DeepWalk method, producing a 128-dimensional embedding with Graph information.
   - Includes an evaluation using Node Classification.

### 2. deepwalk_PPI.ipynb:
   - Tailored for the Pytorch Geometric datasets.
   - Adapts the content of the previous file for compatibility with these datasets.

### 3. deepwalk_PPI.ipynb:
   - Tailored for the PPI dataset.
   - Adapts the content of the previous file for compatibility with this dataset.

### 4. linkprediction.ipynb
  - Evaluation of an embedding using Link Prediction

### 5. Link_prediction_Pytorch_Geometric.ipynb
  - Tailored for the Pytorch Geometric datasets
  - Adapts the content of the previous file for compatibility with these datasets.

**Reference:**
Perozzi, B., Al-Rfou, R., & Skiena, S. (2014, August). Deepwalk: Online learning of social representations. In Proceedings of the 20th ACM SIGKDD international conference on Knowledge discovery and data mining (pp. 701-710).

