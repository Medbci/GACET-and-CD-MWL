# GACET: Graph-Aware Cross-domain EEG Transformer 

## Data Description
The full dataset will be made publicly available upon the acceptance of the paper.
For now, sample data for `subject1` is provided under the `data/` directory to allow for testing the code and reproducing the core results.

## Environment
- Python 3.12.6  
- PyTorch 2.4.0  
- CUDA 12.1  
- Hardware: Dual NVIDIA GeForce RTX 3090 GPUs  


```plaintext
GACET/
├── data/               # Single-subject sample data for running train_model.ipynb
├── feature/            # Implementations of DE, PSD, and SampEn feature extraction
├── pre_processing/     # Data pre-processing scripts
├── train/              # Model definitions and required runtime files
├── log/                # Significance analysis results and cross-day evaluation logs
├── Performance of GACET.pdf   # Summary of performance and evaluation results
└── train_model.ipynb   # Jupyter notebook for training and evaluating the model
```
