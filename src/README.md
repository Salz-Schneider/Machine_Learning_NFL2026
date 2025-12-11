# Source Code

This directory contains reusable Python modules and utility functions for the project.

## Structure

- **data_processing.py**: Functions for data loading, cleaning, and preprocessing
- **feature_engineering.py**: Feature creation and transformation functions
- **model_utils.py**: Helper functions for model training and evaluation
- **visualization.py**: Custom visualization functions

## Usage

Import functions from these modules in your notebooks:

```python
import sys
sys.path.append('../../src')

from data_processing import load_data, preprocess_data
from feature_engineering import create_features
from model_utils import train_model, evaluate_model
```

## Best Practices

- Keep functions modular and well-documented
- Add docstrings to all functions
- Write unit tests for critical functions
- Follow PEP 8 style guidelines
