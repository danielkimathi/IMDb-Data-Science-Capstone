# IMDb-Data-Science-Capstone
**IMDb Movie Ratings Prediction Capstone Project**

## Project Overview
This project aims to predict IMDb movie ratings using machine learning models, including **Linear Regression**, **K-Nearest Neighbors (KNN)**, and **Decision Trees**. By leveraging insights from movie-related features such as director ratings, runtime, and genre, this project demonstrates the power of feature engineering and model evaluation techniques.

### The notebook contains:
- **Exploratory Data Analysis (EDA)** to uncover key insights from the dataset.
- **Feature engineering** to enhance model accuracy.
- **Training and evaluation** of multiple machine learning models.
- **Conclusions and comparisons** of the models' performance.

---

## How to Use This Notebook
- **Outputs Included**: All cells in the notebook have been executed, and outputs are displayed for easy viewing.
- **Reproducibility**: The notebook is organized and can be run end-to-end without errors if desired.
- **Requirements**: Install the necessary Python libraries listed in the notebook, then download the datasets linked below in the "Datasets" section.

---

## Datasets
The datasets used in this project are hosted externally on Dropbox. You can download the required datasets from the link below:

[**Download Datasets Here**](https://www.dropbox.com/scl/fo/wlst9m82x4sxfwaokrjbd/AORCo7nKZ8eZ9IjXdnufoY8?rlkey=dc0f4kffvjzn1nrcd8yqbzpk7&st=hkuk546y&dl=0)

### Instructions:
1. Extract the datasets into a folder named **Capstone Datasets**.
2. Ensure that the folder structure matches the file paths referenced in the Jupyter Notebook.

---

## Project Highlights:
- **Data Preprocessing**:
  - Handling missing values, encoding categorical data, and creating new features.
  
- **Exploratory Data Analysis (EDA)**:
  - Visualizations of feature relationships and insights into the data.
  
- **Machine Learning Models**:
  - **Linear Regression**: Predicting continuous IMDb ratings.
  - **KNN**: Classifying ratings into groups for categorical analysis.
  - **Decision Tree**: Capturing non-linear relationships and interpreting feature importance.
  
- **Hyperparameter Tuning**:
  - Optimized **K** for KNN and **max depth** for Decision Trees.
  
- **Model Evaluation**:
  - Metrics such as **R²**, **RMSE**, **accuracy**, and **cross-validation results**.
  - Visualizations, including scatterplots, residual plots, and confusion matrices.

---

## Results Summary:
- **Linear Regression**:
  - Achieved 𝑅² = 75.32% on the test set with minimal residual bias.
  
- **K-Nearest Neighbors**:
  - Achieved a mean cross-validation accuracy of 64.88% with 𝐾 = 31.
  
- **Decision Tree**:
  - Optimal depth of 25, achieving a cross-validated accuracy of 80.36%.

---

## Conclusion
This project demonstrates the progression from raw data to actionable insights using machine learning. It serves as a strong foundation for future projects that involve data preprocessing, feature engineering, and model evaluation.




