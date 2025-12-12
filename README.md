# Employee Attrition Analysis

A comprehensive visual analytics project examining employee attrition patterns using the IBM HR Analytics dataset. This study employs data visualization techniques to uncover factors influencing employee retention, including work-life balance, overtime, compensation, and satisfaction metrics.

**Status:** Archived / Refactored

## Description

This project analyzes 1,470 employee records with 31 attributes to identify key drivers of employee attrition. Through sophisticated visualizations built with Python's Seaborn and Matplotlib libraries, the analysis reveals:

- Work-life balance impact on retention (poor balance → 30%+ attrition rate)
- Overtime correlation with 2.5x higher attrition
- Compensation trajectory differences between retained and departed employees
- Demographic and departmental attrition patterns

## Project Structure

```
.
├── code.ipynb           # Jupyter notebook with analysis and visualizations
├── content/
│   └── dataset.csv      # IBM HR Analytics dataset (1,470 records)
├── images/              # Generated visualization outputs
├── report.tex           # LaTeX source for IEEE-formatted report
├── LICENSE              # MIT License
├── CONTRIBUTING.md      # Contribution guidelines
├── CHANGELOG.md         # Version history
└── README.md            # This file
```

## Setup / Installation

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

Or create a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

## Usage

1. Launch Jupyter:
   ```bash
   jupyter notebook
   ```

2. Open `code.ipynb`

3. Run all cells to reproduce the analysis and generate visualizations

### LaTeX Report (Optional)

To compile the report:
```bash
pdflatex report.tex
```

## Key Visualizations

The notebook generates 10+ visualizations including:
- Feature importance (Random Forest analysis)
- PCA biplot for risk clustering
- Kaplan-Meier retention curves
- Satisfaction density plots
- Demographic facet analysis

## Dataset

The IBM HR Analytics Employee Attrition dataset includes:
- **Demographics:** Age, Gender, Marital Status
- **Professional:** Job Role, Department, Job Level, Years at Company
- **Compensation:** Monthly Income, Salary Hike, Stock Options
- **Satisfaction:** Job Satisfaction, Environment Satisfaction, Work-Life Balance

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Authors

- Muhammad Ibrahim Kiani
- Muhammad Abdullah Ali
- Muhammad Abdullah Aamir

FAST NUCES, Islamabad
