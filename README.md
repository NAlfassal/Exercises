# 🚀 ML_Pipelines - Machine Learning & Data Engineering Mastery

> A comprehensive collection of hands-on exercises and projects focused on mastering machine learning pipelines, data preprocessing, and advanced analytics techniques.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0%2B-green)
![License](https://img.shields.io/badge/License-Open%20Source-brightgreen)

---

## 📋 Table of Contents

- [Overview](#overview)
- [Quick Start](#quick-start)
- [Project Structure](#project-structure)
- [Topics Covered](#topics-covered)
- [Learning Path](#learning-path)
- [Skills Developed](#skills-developed)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)

---

## 📌 Overview

**ML_Pipelines** is a carefully curated collection of Jupyter Notebook exercises designed to build expertise in:

- 📊 **Data Exploration & Analysis** - Understanding complex datasets
- 🔧 **Feature Engineering** - Crafting meaningful features from raw data
- 🎯 **Data Preprocessing** - Numerical and categorical pipelines
- ⚙️ **Model Validation** - Cross-validation and performance metrics
- 📈 **Hyperparameter Optimization** - Advanced tuning techniques
- 🚀 **Production-Ready Pipelines** - Scalable ML workflows

This repository demonstrates a **systematic approach** to mastering the complete ML workflow, from raw data exploration to production-ready models.

---

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/NAlfassal/Exercises.git
cd Exercises
```

### 2. Install Dependencies
```bash
#using uv 
uv sync
```

### 3. Launch Jupyter
```bash
jupyter notebook
```

### 4. Explore the Exercises
Navigate to the `ML_Pipelines` folder and start with `01_Tabular_Data_Exploration`

---

## 📂 Project Structure

```
Exercises/
│
├── ML_Pipelines/                           # Main project folder
│   │
│   ├── 01_Tabular_Data_Exploration/
│   │   ├── 01_tabular_data_exploration_ex_01.ipynb
│   │   └── README.md
│   │
│   ├── 02_Numerical_Pipeline/
│   │   ├── 02_numerical_pipeline_ex_00.ipynb
│   │   ├── 02_numerical_pipeline_ex_01.ipynb
│   │   └── README.md
│   │
│   ├── 03_Categorical_Pipeline/
│   │   ├── 03_categorical_pipeline_ex_01.ipynb
│   │   ├── 03_categorical_pipeline_ex_02.ipynb
│   │   └── README.md
│   │
│   ├── 04_Cross_Validation/
│   │   ├── cross_validation_ex_01.ipynb
│   │   └── README.md
│   │
│   └── 05_Parameter_Tuning/
│       ├── parameter_tuning_ex_02.ipynb
│       ├── parameter_tuning_ex_03.ipynb
│       └── README.md
│
├── requirements.txt                        # Project dependencies
├── .gitignore                             # Git configuration
└── README.md                              # This file
```

---

## 🎯 Topics Covered

### 📊 Module 1: Tabular Data Exploration
Understand data structure, perform exploratory data analysis (EDA), and identify patterns

**File:** `01_tabular_data_exploration_ex_01.ipynb`
- Data loading and inspection
- Statistical analysis and profiling
- Missing value detection
- Data visualization
- Correlation analysis

### 🔢 Module 2: Numerical Pipeline
Process numerical features with scaling, normalization, and advanced transformations

**Files:**
- `02_numerical_pipeline_ex_00.ipynb` - Foundations
- `02_numerical_pipeline_ex_01.ipynb` - Advanced techniques

### 🏷️ Module 3: Categorical Pipeline
Handle categorical features with encoding techniques and feature engineering

**Files:**
- `03_categorical_pipeline_ex_01.ipynb` - Basic techniques
- `03_categorical_pipeline_ex_02.ipynb` - Advanced handling

### ✔️ Module 4: Cross-Validation
Implement proper model validation strategies to ensure generalization

**File:** `cross_validation_ex_01.ipynb`
- K-Fold and Stratified K-Fold
- Time series validation
- Performance metrics
- Cross-validation analysis

### ⚙️ Module 5: Parameter Tuning
Optimize hyperparameters using Grid Search, Random Search, and Bayesian Optimization

**Files:**
- `parameter_tuning_ex_02.ipynb` - Intermediate tuning
- `parameter_tuning_ex_03.ipynb` - Advanced optimization

---

## 📚 Learning Path

```
START: Tabular Data Exploration
   ↓
   │ Learn how to understand and analyze data
   ↓
STEP 2: Numerical Pipeline
   ↓
   │ Learn to preprocess numerical features
   ↓
STEP 3: Categorical Pipeline
   ↓
   │ Learn to handle categorical features
   ↓
STEP 4: Cross-Validation
   ↓
   │ Learn proper model validation techniques
   ↓
STEP 5: Parameter Tuning
   ↓
   │ Learn to optimize models for best performance
   ↓
🎓 BUILD YOUR OWN ML PIPELINE!
```

---

## 💡 Skills Developed

### 🔧 Technical Skills

**Data Preprocessing & Cleaning**
- ✅ Data validation and quality checks
- ✅ Handling missing values strategically
- ✅ Outlier detection and treatment
- ✅ Data type conversion and validation

**Feature Engineering**
- ✅ Numerical feature transformation (scaling, normalization)
- ✅ Categorical feature encoding (One-Hot, Label, Target)
- ✅ Feature scaling and standardization
- ✅ Advanced feature engineering techniques

**Model Development**
- ✅ Pipeline construction with scikit-learn
- ✅ Model selection and comparison
- ✅ Cross-validation strategies
- ✅ Performance evaluation and metrics

**Hyperparameter Optimization**
- ✅ Grid Search implementation
- ✅ Random Search techniques
- ✅ Bayesian Optimization
- ✅ Learning curve analysis
- ✅ Model tuning and optimization

**Best Practices**
- ✅ Clean, reproducible code
- ✅ Documentation and comments
- ✅ Version control with Git
- ✅ Scalable pipeline design

### 🎓 Soft Skills

- Problem-solving and analytical thinking
- Systematic approach to machine learning
- Documentation and communication
- Continuous learning mindset

---

## 📦 Requirements

| Library | Version | Purpose |
|---------|---------|---------|
| pandas | ≥1.3.0 | Data manipulation |
| numpy | ≥1.21.0 | Numerical operations |
| scikit-learn | ≥1.0.0 | Machine learning |
| matplotlib | ≥3.4.0 | Data visualization |
| seaborn | ≥0.11.0 | Statistical plots |
| jupyter | ≥1.0.0 | Notebook environment |

See `requirements.txt` for complete list of dependencies.

---

## 🛠️ Installation

### Prerequisites
- Python 3.8 or higher
- pip or uv package manager
- Git

### Step-by-Step Installation

1. **Clone the repository**
```bash
git clone https://github.com/NAlfassal/Exercises.git
cd Exercises
```

2. **Create a virtual environment (optional but recommended)**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
# Using pip
pip install -r requirements.txt

# Or using uv (faster)
uv sync
```

4. **Verify installation**
```bash
python -c "import pandas, numpy, sklearn; print('✅ All libraries installed successfully!')"
```

5. **Launch Jupyter**
```bash
jupyter notebook
```

---

## 💻 Usage

### Running an Exercise

1. **Launch Jupyter:**
   ```bash
   jupyter notebook
   ```

2. **Navigate to the exercise:**
   - Open `ML_Pipelines` folder
   - Choose your desired module

3. **Work through the notebook:**
   - Read the instructions carefully
   - Execute cells sequentially
   - Complete the exercises
   - Experiment and learn!

### Best Practices

- 📝 Take notes while learning
- 🔬 Experiment with parameters
- 📊 Visualize results
- 💾 Save your work regularly
- 🤔 Try variations and modifications

---

## 🎓 Learning Objectives

After completing all exercises, you will be able to:

✨ Explore and understand complex datasets effectively
✨ Build robust data preprocessing pipelines
✨ Engineer meaningful features from raw data
✨ Implement proper model validation techniques
✨ Optimize machine learning models for production
✨ Apply industry best practices to ML projects
✨ Create reproducible and scalable ML workflows
✨ Make data-driven decisions with confidence

---

## 📊 Exercises Overview

| # | Module | File | Level | Duration | Topics |
|---|--------|------|-------|----------|--------|
| 1 | Tabular Data Exploration | `01_tabular_data_exploration_ex_01.ipynb` | 🟢 Beginner | 2-3 hrs | EDA, Statistics |
| 2 | Numerical Pipeline (Intro) | `02_numerical_pipeline_ex_00.ipynb` | 🟢 Beginner | 2-3 hrs | Scaling, Normalization |
| 3 | Numerical Pipeline (Advanced) | `02_numerical_pipeline_ex_01.ipynb` | 🟡 Intermediate | 2-3 hrs | Feature Engineering |
| 4 | Categorical Pipeline (Basic) | `03_categorical_pipeline_ex_01.ipynb` | 🟢 Beginner | 2-3 hrs | Encoding Techniques |
| 5 | Categorical Pipeline (Advanced) | `03_categorical_pipeline_ex_02.ipynb` | 🟡 Intermediate | 2-3 hrs | Advanced Encoding |
| 6 | Cross-Validation | `cross_validation_ex_01.ipynb` | 🟡 Intermediate | 3-4 hrs | Model Validation |
| 7 | Parameter Tuning (Intermediate) | `parameter_tuning_ex_02.ipynb` | 🟡 Intermediate | 3-4 hrs | Hyperparameter Tuning |
| 8 | Parameter Tuning (Advanced) | `parameter_tuning_ex_03.ipynb` | 🔴 Advanced | 4-5 hrs | Advanced Optimization |

**Total Estimated Time:** 20-28 hours

---

## 🔑 Key Concepts

### Pipelines
- Building modular, reusable preprocessing workflows
- Combining multiple preprocessing steps
- Preventing data leakage

### Cross-Validation
- Ensuring model generalization
- Detecting overfitting and underfitting
- Reliable performance estimation

### Feature Engineering
- Creating meaningful features from raw data
- Selecting most important features
- Domain-driven feature creation

### Hyperparameter Tuning
- Finding optimal model parameters
- Balancing performance and complexity
- Resource-efficient optimization

---

## 🌟 Highlights

- ✅ **Comprehensive Coverage** - From basics to advanced techniques
- ✅ **Hands-On Learning** - Learn by doing with real exercises
- ✅ **Progressive Difficulty** - Beginner to advanced level
- ✅ **Best Practices** - Industry-standard approaches
- ✅ **Well-Documented** - Clear explanations and examples
- ✅ **Reproducible** - All notebooks are fully reproducible

---

## 💬 Tips for Success

1. **Follow the learning path** - Don't skip modules
2. **Complete all exercises** - Practice is essential
3. **Experiment freely** - Modify code and see what happens
4. **Take notes** - Document your learnings
5. **Ask questions** - Debug and understand errors
6. **Build projects** - Apply skills to real problems

---

## 🤝 Contributing

Found an issue or have suggestions? Feel free to:
1. Open an issue
2. Submit a pull request
3. Share feedback

---

## 📞 Support

For questions about:
- **Exercises:** Check the notebook documentation
- **Concepts:** Review the README files in each module
- **Technical Issues:** Refer to scikit-learn and pandas documentation

---

## 📄 License

This repository is open-source and available for educational purposes.

---

## 👤 Author

**NAlfassal** - Data Science & Machine Learning Enthusiast

**GitHub:** [@NAlfassal](https://github.com/NAlfassal)

**Repository:** [ML_Pipelines](https://github.com/NAlfassal/Exercises)

---

## 🎯 Next Steps

After mastering these exercises:
- Build end-to-end projects
- Participate in Kaggle competitions
- Contribute to open-source ML projects
- Explore advanced techniques (Deep Learning, NLP, etc.)

---

## ⭐ If you found this helpful, please star the repository!

---

**Last Updated:** June 2026
**Status:** ✅ Active & Growing
**Total Exercises:** 8
**Difficulty Range:** Beginner to Advanced
