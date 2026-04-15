Variational Graph Auto-Encoders with Matrix Factorization (VGAMF)
This repository contains a TensorFlow implementation of the Variational Graph Auto-Encoder with matrix factorization model for miRNA-disease association prediction, as described in the paper:

Predicting miRNA-Disease Associations Based on Multi-View Variational Graph Auto-Encoder with Matrix Factorization


Features
Multi-view similarity integration for miRNA and disease
Variational Graph Auto-Encoder (VGAE) for feature extraction
Matrix factorization for low-dimensional embedding
Neural network classifier for association prediction
Automatic plotting of ROC and Precision-Recall curves after training
Installation & Environment
Python Version: 3.7 (recommended for TensorFlow 1.15.x compatibility)
Create and activate a virtual environment:
Install dependencies:
Data
Data is provided in the database folder (HMDD v3.2).
Running the Model
Activate your Python 3.7 virtual environment:
Run the main script:
Results:
The script will print average ROC scores and save prediction results as .npy files.
Graphs: ROC and Precision-Recall curves will be displayed automatically at the end of execution.
Output Files
5_fold_add_dot_label_multi.npy — True labels for all test samples
5_fold_add_dot_score_multi.npy — Predicted scores for all test samples
Repository Structure
Notes
Only important files are tracked in git; outputs, virtual environments, and build artifacts are ignored via .gitignore.
For custom experiments, modify parameters in VGAMF_main.py