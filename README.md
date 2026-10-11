# Interpretable Ensemble Learning for Landslide Susceptibility Mapping: A Case Study of Bhutan

## Overview

Landslides pose significant risks to communities, infrastructure, and the environment, particularly in mountainous regions such as Bhutan. Identifying areas susceptible to landslides can support hazard assessment, land-use planning, and disaster risk management.

This research project investigates the application of machine learning techniques to landslide susceptibility assessment in Bhutan. Multiple classification algorithms are explored and compared to examine their predictive performance, alongside methods for interpreting model behavior and understanding the influence of input features.

This project was conducted as part of the **CSE498R research project** at North South University.

## Objectives

- Develop machine learning models for landslide susceptibility assessment.
- Compare the predictive performance of different classification algorithms.
- Investigate ensemble learning approaches for landslide susceptibility prediction.
- Explore model interpretability to better understand the factors influencing model predictions.
- Examine the potential application of data-driven methods to landslide susceptibility assessment in Bhutan.

## Dataset

This project uses the publicly available **Bhutan Data** dataset published on Mendeley Data.

- **Dataset:** Bhutan Data
- **Author:** Maher Al-Zuhairi
- **Version:** 1
- **Publication year:** 2019
- **Format:** CSV
- **Dataset source:** [Mendeley Data — Bhutan Data](https://data.mendeley.com/datasets/kr62jwy9vw/1)

The dataset provides data used to investigate landslide susceptibility in Bhutan. It serves as the basis for training and evaluating the machine learning models.

The dataset is not included in this repository. Please download it from the original source and consult its documentation and license before use.

## Methodology

The project follows a machine learning workflow for landslide susceptibility assessment.

1. **Data exploration and preparation:** Inspect the dataset, examine the input features, and prepare the data for modeling.
2. **Data preprocessing:** Apply the preprocessing steps required for the selected algorithms.
3. **Model development:** Train multiple machine learning classifiers using the prepared dataset.
4. **Model evaluation:** Compare predictive performance using the evaluation metrics implemented in the notebook.
5. **Model interpretability:** Analyze model behavior and feature contributions using the explainability techniques implemented in the project.
6. **Comparative analysis:** Examine the experimental findings and discuss their implications for landslide susceptibility assessment.

Refer to the notebook and research report for the exact implementation, experimental setup, evaluation strategy, and findings.

## Machine Learning Models

The project investigates the following classification algorithms:

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Extreme Gradient Boosting (XGBoost)

These models are compared to examine the effectiveness of different machine learning approaches for landslide susceptibility assessment.

## Technologies and Tools

- **Python** — Programming language for data analysis and model development.
- **Google Colab** — Cloud-based development and experimentation environment.
- **Pandas** — Data manipulation and analysis.
- **NumPy** — Numerical computing.
- **Scikit-learn** — Machine learning algorithms, preprocessing, and evaluation.
- **XGBoost** — Gradient-boosted decision tree modeling.
- **Matplotlib and Seaborn** — Data visualization.

Additional libraries may be required depending on the notebook's imports and implemented explainability techniques.

## Repository Structure

```text
Interpretable-Ensemble-Learning-for-Landslide-Susceptibility-Mapping/
├── code/
│   └── Landslide_Susceptibility_Assessment_in_Bhutan_using_Machine_Learning_and_Explainable_AI.ipynb
├── docs/
│   └── [Research Report PDF]
└── README.md
```

- **`code/`** — Contains the Jupyter Notebook for data analysis, model development, experimentation, and evaluation.
- **`docs/`** — Contains the research report in PDF format.
- **`README.md`** — Provides an overview of the project, dataset, tools, and instructions.

Replace `[Research Report PDF]` with the actual filename of your report.

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Karmaaa7/Interpretable-Ensemble-Learning-for-Landslide-Susceptibilty-Mapping.git
cd Interpretable-Ensemble-Learning-for-Landslide-Susceptibilty-Mapping
```

### 2. Download the dataset

Download the dataset from [Mendeley Data](https://data.mendeley.com/datasets/kr62jwy9vw/1).

Extract the CSV file and make it accessible to the notebook. If the notebook uses Google Drive paths, upload the dataset to your Google Drive and update the file path accordingly.

### 3. Open the notebook

Open the notebook in the `code/` directory using Google Colab or a compatible Jupyter environment.

You can open it in Google Colab by uploading the notebook or opening it from your GitHub repository.

### 4. Install dependencies

Install the required libraries if they are not already available in the environment.

```python
%pip install pandas numpy scikit-learn xgboost matplotlib seaborn
```

Other dependencies may be necessary depending on the notebook's imports.

### 5. Run the experiments

Execute the notebook cells in order. Ensure that the dataset path, library dependencies, and other configuration settings are correct.

## Results and Evaluation

The experimental results, model comparisons, visualizations, and interpretability analysis are documented in the notebook and research report.

Please refer to these files for the actual evaluation metrics and findings. Results should be interpreted in the context of the dataset, validation strategy, and experimental limitations.

## Limitations

- Model performance depends on the quality and representativeness of the dataset.
- Evaluation scores alone do not establish real-world predictive reliability.
- Results from sampled locations should not automatically be interpreted as a complete, geographically validated susceptibility map.
- Independent validation and additional geographical data may be necessary before applying the models to operational landslide risk management.

## Academic Information

- **Course:** CSE498R — Research Project
- **Institution:** North South University
- **Research Title:** Interpretable Ensemble Learning for Landslide Susceptibility Mapping: A Case Study of Bhutan
- **Research Supervisor:** Dr. Dr. Mohammad Monirujjaman Khan

## Dataset Citation

Al-Zuhairi, M. (2019). *Bhutan Data* (Version 1). Mendeley Data. https://doi.org/10.17632/kr62jwy9vw.1

Please consult the original dataset page for its license and attribution requirements.

## Acknowledgements

The author acknowledges Maher Al-Zuhairi for making the Bhutan Data dataset publicly available for research and analysis.

The author also acknowledges the research supervisor for their guidance and feedback throughout the CSE498R research project.