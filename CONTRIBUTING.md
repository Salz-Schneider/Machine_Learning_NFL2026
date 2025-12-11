# Contributing Guidelines

Thank you for contributing to our NFL 2026 Machine Learning project! This guide will help ensure smooth collaboration.

## 🔄 Workflow

1. **Pull latest changes** before starting work:
   ```bash
   git pull origin main
   ```

2. **Create a feature branch** for your work:
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make your changes** and commit regularly:
   ```bash
   git add .
   git commit -m "Descriptive commit message"
   ```

4. **Push your branch** and create a pull request:
   ```bash
   git push origin feature/your-feature-name
   ```

## 📝 Commit Message Guidelines

- Use clear, descriptive commit messages
- Start with a verb (Add, Update, Fix, Remove, etc.)
- Examples:
  - `Add exploratory data analysis notebook`
  - `Update feature engineering pipeline`
  - `Fix data preprocessing bug`

## 📓 Notebook Conventions

### Naming
- Use descriptive names with numbers for order
- Format: `01_descriptive_name.ipynb`
- Examples:
  - `01_initial_data_exploration.ipynb`
  - `02_player_statistics_analysis.ipynb`

### Structure
- Start with a markdown cell describing the notebook
- Include author and date
- Add section headers using markdown
- Clear cell outputs before committing (optional but recommended)

### Code Style
- Follow PEP 8 guidelines
- Add comments for complex logic
- Keep cells focused on single tasks
- Use meaningful variable names

## 🗂️ File Organization

### Notebooks
- `notebooks/exploratory/`: Data exploration and analysis
- `notebooks/modeling/`: Model development and training
- `notebooks/evaluation/`: Model evaluation and comparison

### Models
- Save trained models with descriptive names
- Include version/date in model names
- Document model parameters in a separate JSON or text file

### Data
- **Never commit large data files to git**
- Place raw data in `data/raw/`
- Place processed data in `data/processed/`
- Document data sources and preprocessing steps

## 🤝 Code Review

- Review teammate's pull requests
- Provide constructive feedback
- Test notebooks before approving
- Check for:
  - Code quality
  - Documentation
  - Reproducibility

## 📦 Dependencies

- Add new dependencies to `requirements.txt`
- Use specific version numbers when possible
- Test that installation works

## 🔍 Before Submitting

- [ ] Code runs without errors
- [ ] Notebook outputs are clear and informative
- [ ] Added documentation where needed
- [ ] No sensitive data or credentials committed
- [ ] Large files not committed (check `.gitignore`)
- [ ] Tested on clean environment (if possible)

## 🐛 Reporting Issues

- Use GitHub Issues for bug reports
- Include:
  - Clear description
  - Steps to reproduce
  - Expected vs actual behavior
  - Screenshots if applicable

## 💡 Questions?

If you have questions, reach out to the team through the course channels or GitHub discussions.

## 📚 Resources

- [Jupyter Notebook Best Practices](https://jupyter-notebook.readthedocs.io/)
- [Git Tutorial](https://git-scm.com/docs/gittutorial)
- [PEP 8 Style Guide](https://pep8.org/)
- [Kaggle Competition Rules](https://www.kaggle.com/competitions/nfl-big-data-bowl-2026/rules)

---

Happy coding! 🏈📊
