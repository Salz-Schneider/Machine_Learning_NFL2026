# Data Directory

This directory contains the data files for the NFL Big Data Bowl 2026 project.

## ⚠️ Important Note

**Data files are not tracked in Git due to their size.** The `.gitignore` file excludes all CSV, Parquet, and other large data formats to keep the repository size manageable.

## 📂 Directory Structure

```
data/
├── raw/           # Original, unmodified competition data
└── processed/     # Cleaned and preprocessed data
```

## 📥 Getting the Data

### Option 1: Download from Kaggle (Recommended)

1. Install the Kaggle API:
   ```bash
   pip install kaggle
   ```

2. Set up your Kaggle API credentials:
   - Go to [Kaggle Account Settings](https://www.kaggle.com/account)
   - Click "Create New API Token"
   - Place the downloaded `kaggle.json` in `~/.kaggle/` (Linux/Mac) or `C:\Users\<username>\.kaggle\` (Windows)
   - Set permissions: `chmod 600 ~/.kaggle/kaggle.json` (Linux/Mac)

3. Download the competition data:
   ```bash
   kaggle competitions download -c nfl-big-data-bowl-2026
   unzip nfl-big-data-bowl-2026.zip -d data/raw/
   ```

### Option 2: Manual Download

1. Visit the [competition data page](https://www.kaggle.com/competitions/nfl-big-data-bowl-2026/data)
2. Download the data files
3. Extract them to the `data/raw/` directory

## 📊 Data Files

After downloading, you should have the following files in `data/raw/`:

- `train.csv` - Training data
- `test.csv` - Test data for predictions
- Additional files specific to the NFL 2026 competition

(Update this list based on the actual competition data structure)

## 🔄 Data Processing

Processed data files should be saved to `data/processed/` with clear, descriptive names:

- `train_processed.csv` - Cleaned training data
- `train_features.csv` - Engineered features for training
- `test_features.csv` - Engineered features for test set

## 💾 Storage Best Practices

1. **Keep raw data unchanged** - Always preserve original files in `raw/`
2. **Document transformations** - Note preprocessing steps in notebooks
3. **Use efficient formats** - Consider Parquet for large datasets:
   ```python
   df.to_parquet('data/processed/train_features.parquet')
   df = pd.read_parquet('data/processed/train_features.parquet')
   ```
4. **Version processed data** - Add date/version to filenames if you iterate

## 🔐 Data Privacy

- Never commit personal or sensitive data
- Follow Kaggle competition rules regarding data usage
- Keep competition data private as per Kaggle terms

## 📝 Data Documentation

For each processed dataset, document:
- Source of the data
- Preprocessing steps applied
- Feature descriptions
- Date created

Consider creating a data dictionary file for reference.

## 🔍 Quick Start

```python
import pandas as pd

# Load raw data
train_df = pd.read_csv('data/raw/train.csv')
test_df = pd.read_csv('data/raw/test.csv')

# After preprocessing
train_processed = pd.read_csv('data/processed/train_processed.csv')
```

## ❓ Questions?

If you have questions about the data, check:
1. [Competition data description](https://www.kaggle.com/competitions/nfl-big-data-bowl-2026/data)
2. Competition forums for discussions
3. Team collaboration channels
