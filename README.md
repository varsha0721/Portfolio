# 🗺️ Varsha's Portfolio
Welcome to my data science portfolio! Here, I document a summary of my projects in the data science field.

# 📃 Table of Contents
- [MLE](https://github.com/varsha0721/Portfolio/blob/main/README.md#mle)
- [Regression](https://github.com/varsha0721/Portfolio/blob/main/README.md#regression)
- [Classification](https://github.com/varsha0721/Portfolio/blob/main/README.md#Classification)
- [NLP](https://github.com/varsha0721/Portfolio/blob/main/README.md#NLP)
- [R](https://github.com/varsha0721/Portfolio/blob/main/README.md#R)

# MLE
<table>
  <thead>
    <tr>
      <th colspan="2">Project Overview</th>
      <th colspan="2">Key Techniques</th>
      <th>Project Description</th>
    </tr>
    <tr>
      <th>Project Link</th>
      <th>Tools</th>
      <th>Category</th>
      <th>Details</th>
      <th>Breif Introduction</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="7" valign="top"><a href="https://github.com/varsha0721/Housing-Price-Prediction--Regression--Sphinx--MlFlow--Docker"> Housing Price Prediction--Sphinx--MlFlow--Docker</a></td>
      <td rowspan="7" valign="top">
        <ul>
          <li>Python</li>
          <li>MLFlow</li>
          <li>Docker</li>
          <li>VS Code</li>
          <li>Jupyter-Notebook</li>
          <li>Conda</li>
          <li>Sphinx</li>
        </ul>
      </td>
      <td><strong>1. Python Libraries and Modules</strong></td>
      <td>
        <ul>
          <li><code>argparse</code> (for accepting user inputs)</li>
          <li><code>logging</code> (for writing logs and console messages)</li>
          <li><code>pickle</code> (for saving and reusing model objects)</li>
          <li><code>unittest</code> (for writing test cases)</li>
          <li><code>sphinx</code> (for documentation)</li>
          <li><code>packaging</code> (to create and manage Python packages)</li>
        </ul>
      </td>
      <td rowspan="7" valign="top"><p> Developed and implemented an end-to-end machine learning pipeline for housing price prediction. The project involved cleaning and preprocessing data, generating features, and training predictive models using Linear Regression, Decision Tree, and Random Forest algorithms. Experiment tracking was performed using MLFlow, and the pipeline was modularized into scripts for ingestion, training, and scoring. The workflow was containerized with Docker for reproducibility, incorporating Docker Volumes and Mounts for efficient data management, and deployed as a scalable solution with environment management using Conda.</P>
    </tr>
    <tr>
      <td><strong>2. Data Preparation and Evaluation</strong></td>
      <td>
        <ul>
          <li>EDA</li>
          <li>Handling missing values</li>
          <li>Transformations</li>
          <li>Feature engineering and correlation analysis</li>
          <li>Sampling techniques and train-test splits</li>
          <li>Model Evaluation</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>3. Machine Learning Algorithms</strong></td>
      <td>
        <ul>
          <li>Linear Regression</li>
          <li>Decision Tree</li>
          <li>Random Forest</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>4. Version Control and Environment Management</strong></td>
      <td>
        <ul>
          <li><code>conda</code> (environment setup and management)</li>
          <li>VS Code (IDE configuration with formatting tools like <code>black</code>, <code>isort</code>, and <code>flake8</code>)</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>5. Experiment Tracking</strong></td>
      <td>
        <ul>
          <li>MLFlow (for managing and tracking model training experiments)</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>6. Containerization</strong></td>
      <td>
        <ul>
          <li>Docker (for creating, running, and managing containerized environments)</li>
          <li>Docker Volumes and Mounts (for file management and environment access)</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>7. Packaging and Deployment</strong></td>
      <td>
        <ul>
          <li>Building and installing <code>.whl</code> packages</li>
          <li>Pushing Docker images to Docker Hub for sharing and deployment</li>
        </ul>
      </td>
    </tr>
    </td>
  </tbody>
</table>

# Regression
<table>
  <thead>
    <tr>
      <th colspan="2">Project Overview</th>
      <th colspan="2">Key Techniques</th>
      <th>Project Description</th>
    </tr>
    <tr>
      <th>Project Link</th>
      <th>Tools</th>
      <th>Category</th>
      <th>Details</th>
      <th>Brief Introduction</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="6" valign="top"><a href="https://github.com/varsha0721/Housing-Price-Prediction--Regression/tree/main"> Housing Price Prediction -- Regression</a></td>
      <td rowspan="6" valign="top">
        <ul>
          <li>Python</li>
          <li>Jupyter Notebook</li>
          <li>Scikit-learn</li>
          <li>XGBoost</li>
          <li>LightGBM</li>
          <li>Pandas, NumPy</li>
          <li>Matplotlib, Seaborn</li>
        </ul>
      </td>
      <td><strong>1. Data Exploration and Preprocessing</strong></td>
      <td>
        <ul>
          <li>EDA (Exploratory Data Analysis)</li>
          <li>Handling missing values</li>
          <li>Outlier detection and removal</li>
          <li>Feature engineering</li>
          <li>Standardization and normalization</li>
        </ul>
      </td>
      <td rowspan="6" valign="top">
        <p>
          This project aims to develop a machine learning model for predicting housing prices based on property features like location, size, and number of bedrooms. The project follows a structured workflow, including data preprocessing, feature engineering, model training, and evaluation. Multiple regression models were implemented, including Linear Regression, Random Forest, and Gradient Boosting. The final model was evaluated using R-squared, MAE, and RMSE to ensure high accuracy.
        </p>
      </td>
    </tr>
    <tr>
      <td><strong>2. Machine Learning Models</strong></td>
      <td>
        <ul>
          <li>Linear Regression</li>
          <li>Random Forest Regressor</li>
          <li>Gradient Boosting (XGBoost, LightGBM)</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>3. Model Evaluation</strong></td>
      <td>
        <ul>
          <li>R-Square (R²)</li>
          <li>Mean Absolute Error (MAE)</li>
          <li>Root Mean Squared Error (RMSE)</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>4. Data Visualization</strong></td>
      <td>
        <ul>
          <li>Correlation heatmaps</li>
          <li>Feature importance plots</li>
          <li>Distribution and trend analysis</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>5. Feature Engineering</strong></td>
      <td>
        <ul>
          <li>Creating new features from existing data</li>
          <li>Transforming categorical variables</li>
          <li>Feature selection for better model performance</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>


# Classification
<table>
  <thead>
    <tr>
      <th colspan="2">Project Overview</th>
      <th colspan="2">Key Techniques</th>
      <th>Project Description</th>
    </tr>
    <tr>
      <th>Project Link</th>
      <th>Tools</th>
      <th>Category</th>
      <th>Details</th>
      <th>Brief Introduction</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="6" valign="top"><a href="https://github.com/yourusername/loan-approval-prediction"> Loan Approval Prediction - Classification</a></td>
      <td rowspan="6" valign="top">
        <ul>
          <li>Python</li>
          <li>Jupyter Notebook</li>
          <li>Scikit-learn</li>
          <li>XGBoost</li>
          <li>LightGBM</li>
          <li>Support Vector Machine (SVM)</li>
          <li>Pandas, NumPy</li>
          <li>Matplotlib, Seaborn</li>
        </ul>
      </td>
      <td><strong>1. Data Exploration and Preprocessing</strong></td>
      <td>
        <ul>
          <li>Data overview and feature analysis</li>
          <li>Handling missing values</li>
          <li>Encoding categorical variables</li>
          <li>Feature engineering</li>
          <li>Standardization of numerical features</li>
        </ul>
      </td>
      <td rowspan="6" valign="top">
        <p>
          This project aims to develop a predictive model for loan approvals based on applicant data such as income, credit history, and loan amount. It assists financial institutions in making data-driven decisions and streamlining the loan approval process. 
          Multiple classification models were implemented, including Logistic Regression, Decision Trees, Random Forest, SVM, and Gradient Boosting (XGBoost, LightGBM). The final model was evaluated using accuracy, precision, recall, F1-score, and ROC-AUC.
        </p>
      </td>
    </tr>
    <tr>
      <td><strong>2. Machine Learning Models</strong></td>
      <td>
        <ul>
          <li>Logistic Regression</li>
          <li>Decision Trees</li>
          <li>Random Forest Classifier</li>
          <li>Support Vector Machine (SVM)</li>
          <li>Gradient Boosting (XGBoost, LightGBM)</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>3. Model Evaluation</strong></td>
      <td>
        <ul>
          <li>Accuracy</li>
          <li>Precision, Recall, and F1-Score</li>
          <li>ROC-AUC Score</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>4. Data Visualization</strong></td>
      <td>
        <ul>
          <li>Feature importance analysis</li>
          <li>Correlation heatmaps</li>
          <li>Class distribution plots</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>5. Feature Engineering</strong></td>
      <td>
        <ul>
          <li>Creating new features from applicant attributes</li>
          <li>Transforming categorical variables</li>
          <li>Feature selection for model optimization</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>


# NLP

# R
