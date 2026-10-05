# Data Mining and Machine Learning for Bioinformatics

A GitHub Pages teaching site and hands-on Jupyter Notebook for a **Master's-level flipped classroom**.

## Session

- **Topic:** Data Mining and Machine Learning for Bioinformatics
- **Format:** Flipped Classroom + Problem-Based Learning + GitHub Lab
- **In-class duration:** 120 minutes
- **Language:** English
- **Core workflow:** Explore → Prepare → Train → Evaluate → Interpret → Defend → Reproduce

## Repository Structure

```text
.
├── index.html
├── style.css
├── pre-class/
│   └── index.html
├── concept/
│   └── index.html
├── dataset/
│   └── index.html
├── lab/
│   └── index.html
├── assignment/
│   └── index.html
└── notebooks/
    └── bioinformatics_ml.ipynb
```

## Run the Notebook

Recommended options:

- GitHub Codespaces
- JupyterLab
- VS Code with the Jupyter extension

Install requirements:

```bash
pip install pandas numpy scikit-learn jupyter
```

Then open:

```text
notebooks/bioinformatics_ml.ipynb
```

## Student Workflow

1. Complete the Pre-Class page.
2. Review the Machine Learning Concepts page.
3. Fork the repository.
4. Open a Codespace or clone the fork.
5. Run and modify the notebook.
6. Complete the Model Defense.
7. Choose one after-class extension.
8. Update the README with your results.
9. Commit and push.
10. Submit your repository URL.

## Learning Outcomes

Students will be able to prepare biomedical data, build supervised classification models, evaluate models using multiple metrics, interpret feature importance, discuss limitations, and document a reproducible machine-learning experiment.

## Teaching Note

The lab intentionally emphasizes reasoning rather than maximizing accuracy. Students should justify model selection using evaluation evidence and biomedical context. Feature importance should not be interpreted as proof of causality.


## Case Study Dataset

The course uses the **Breast Cancer Wisconsin Diagnostic Dataset** stored in `dataset/cancer.csv`. The notebook and Dataset page load this local CSV file. The website includes the task, sample size, predictors, target classes, feature groups, starter code, and research questions.

## V4 — Jupyter Notebook Lab Edition

The hands-on session is now designed to be completed inside one guided Jupyter Notebook. It contains 14 steps covering ML concepts, the Breast Cancer Wisconsin dataset, EDA, preprocessing, leakage prevention, Logistic Regression, Decision Tree, Random Forest, metric comparison, confusion matrix, ROC curves, feature importance, model defense, mini challenges, reflection, and a GitHub exit ticket.

Recommended in-class workflow: students fork the repository, open the notebook in GitHub Codespaces/Jupyter, complete TODO tasks, run one challenge, save, commit, and push.
