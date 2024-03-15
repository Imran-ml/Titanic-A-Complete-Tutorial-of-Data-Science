# Titanic a Complete Tutorial of Data Science

## Table of Contents

- [Introduction](#introduction)
- [Environment Setup](#environment-setup)
- [Installation Instructions](#installation-instructions)
- [Resources](#resources)
- [License](#license)
- [Conclusion](#conclusion)
- [About Author](#about-author)

## Introduction

This repository is your gateway to diving into one of the most interesting and historically rich datasets available in the field of data science and machine learning: the Titanic dataset. This project aims to provide a comprehensive, step-by-step guide to understanding, analyzing, and predicting outcomes based on the data from the tragic sinking of the Titanic in 1912.

The primary focus of this project is to offer an accessible yet insightful exploration into the world of machine learning, targeting enthusiasts ranging from beginners to intermediate learners who wish to enhance their skills in data science. By working through the included notebooks, participants will gain hands-on experience with real-world data preprocessing, exploratory data analysis (EDA), feature engineering, and the application of various machine learning models.

## Environment Setup

**Prerequisites**: Ensure Python 3.6 or newer is installed on your system.

1. **Create a Virtual Environment**:
    - Install `virtualenv` if you prefer it over the built-in `venv` (optional):
        ```bash
        pip install virtualenv
        ```
    - Create the environment:
        - With `venv` (Python 3.3+):
            ```bash
            python -m venv env
            ```
        - Or, with `virtualenv`:
            ```bash
            virtualenv env
            ```
    - Activate the environment:
        - Windows: `env\Scripts\activate`
        - Unix/MacOS: `source env/bin/activate`
    - To deactivate: `deactivate`

2. **Dependencies**:
    Ensure all dependencies are listed in `requirements.txt`. Install them using:
    ```bash
    pip install -r requirements.txt
    ```

## Installation Instructions

To use this project, clone the repository and set up the environment as follows:

1. **Clone the Repository**:
    ```bash
    https://github.com/Imran-ml/Name-Entity-Recognition-and-Classification.git
    ```
2. **Setup the Environment**:
    - Navigate to the project directory and activate the virtual environment.
    - Install the dependencies from `requirements.txt`.

## Resources

- **Kaggle Notebook**: [View Notebook](https://www.kaggle.com/code/muhammadimran112233/titanic-a-complete-tutorial-of-data-science)
- **Dataset**: [View Dataset](https://www.kaggle.com/competitions/titanic)

## License

This project is made available under the MIT License.

## Conclusion

We applied various techniques in data preparation and feature extraction. Initially, using the TF-IDF technique for feature extraction did not yield satisfactory results. However, switching to a Sequence extractor using TensorFlow significantly improved our outcomes. Data preprocessing, feature extraction, and hyperparameter tuning were crucial in enhancing the RNN's performance, whereas the Random Forest model underperformed.

For hyperparameter tuning in deep learning models, it's essential to adjust them based on the problem at hand, train, and test the model to evaluate its performance thoroughly. In the case of the Random Forest model, employing a GRID SEARCH approach allows for training across a spectrum of hyperparameters to identify the optimal ones for the final model.

### Hyperparameters for RNN:
After tuning, the optimal hyperparameters included using the Sigmoid activation function for binary output, binary cross-entropy for a two-class classification problem, and the RMSPROP optimizer for enhanced performance. Experimenting with different epochs and batch sizes, we found that 20 epochs and a batch size of 500 were ideal.

### Hyperparameters for RF:
The best parameters for the Random Forest model were identified through grid search, resulting in: {'n_estimators': 200, 'max_features': 'sqrt', 'max_depth': 8, 'criterion': 'gini'}.

The RNN model excelled due to its capability to remember information from previous instances, providing superior results.

## About Author

- **Name**: Muhammad Imran Zaman
- **Email**: [imranzaman.ml@gmail.com](mailto:imranzaman.ml@gmail.com)
- **Professional Links**:
    - Kaggle: [Profile](https://www.kaggle.com/muhammadimran112233)
    - LinkedIn: [Profile](linkedin.com/in/muhammad-imran-zaman)
    - Google Scholar: [Profile](https://scholar.google.com/citations?user=ulVFpy8AAAAJ&hl=en)
    - YouTube: [Channel](https://www.youtube.com/@consolioo)
- **Project Repository**: [GitHub Repo](https://github.com/Imran-ml/Name-Entity-Recognition-and-Classification.git)
