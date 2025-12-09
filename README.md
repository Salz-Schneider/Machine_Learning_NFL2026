# Machine Learning NFL 2026 - Kaggle Competition

This repository contains our team's work for the **Kaggle NFL Big Data Bowl 2026 - Prediction** competition, developed as part of the Machine Learning course at UHasselt.

## 📊 About the Competition

The [NFL Big Data Bowl 2026](https://www.kaggle.com/competitions/nfl-big-data-bowl-2026) is a competition focused on using machine learning to predict player performance and game outcomes in the NFL. Our project applies various ML techniques to analyze and predict NFL game data.

## 🎯 Project Overview

This project demonstrates the application of machine learning concepts learned in the course to real-world sports analytics. We explore different models, feature engineering techniques, and evaluation metrics to develop accurate predictions.

## 📁 Repository Structure

```
├── notebooks/          # Jupyter notebooks with analysis and modeling
│   ├── exploratory/   # Exploratory data analysis
│   ├── modeling/      # Model development and training
│   └── evaluation/    # Model evaluation and results
├── models/            # Trained models and model artifacts
├── data/              # Data files (not tracked in git - see .gitignore)
│   ├── raw/          # Raw competition data
│   └── processed/    # Processed/engineered features
├── src/               # Source code for reusable functions
├── requirements.txt   # Python dependencies
└── README.md         # This file
```

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab
- Git

### Installation

1. Clone this repository:
```bash
git clone https://github.com/Salz-Schneider/Machine_Learning_NFL2026.git
cd Machine_Learning_NFL2026
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

4. Download the competition data from [Kaggle](https://www.kaggle.com/competitions/nfl-big-data-bowl-2026/data) and place it in the `data/raw/` directory.

## 📓 Notebooks

Our analysis is organized into several notebooks:

- **Exploratory Data Analysis**: Understanding the data, visualizations, and initial insights
- **Feature Engineering**: Creating and selecting relevant features for modeling
- **Model Development**: Training and tuning various ML models
- **Model Evaluation**: Comparing models and analyzing results
- **Final Predictions**: Generating predictions for submission

## 🤖 Models

We experimented with various machine learning models including:

- Linear Regression
- Random Forest
- Gradient Boosting (XGBoost, LightGBM)
- Neural Networks
- Ensemble Methods

Model artifacts and trained models are saved in the `models/` directory.

## 👥 Team

This project was developed as part of the Machine Learning course at UHasselt.

## 📄 License

This project is for educational purposes as part of the Machine Learning course at UHasselt.

## 🙏 Acknowledgments

- UHasselt Machine Learning Course
- Kaggle and NFL for hosting the Big Data Bowl competition
- The NFL Big Data Bowl community for insights and discussions

## 📧 Contact

For questions about this project, please reach out through the course channels.

---

**Note**: This repository is actively maintained as part of our course project. Check back for updates as we progress through the competition!