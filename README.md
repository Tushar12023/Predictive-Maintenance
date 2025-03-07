# Predictive-Maintenance

## Overview

This project develops a multiclass classification model to predict machine failures in industrial equipment. By leveraging various machine learning algorithms, including Logistic Regression, Random Forest, and Support Vector Machine, the project aims to enhance predictive maintenance strategies, reduce downtime, and improve operational efficiency.

## Table of Contents

- [Project Description](#project-description)
- [Data Pipeline](#data-pipeline)
- [Installation](#installation)
- [Usage](#usage)
- [Model Evaluation](#model-evaluation)
- [Contributing](#contributing)
- [License](#license)

## Project Description

The project involves the following key components:

1. **Data Preprocessing**: A data pipeline is implemented to clean, transform, and load data into a SQL database.
2. **Handling Class Imbalance**: SMOTE (Synthetic Minority Over-sampling Technique) is used to address class imbalance in the dataset.
3. **Model Training**: Multiple classification models are trained and evaluated to predict machine failures.
4. **Results**: The performance of each model is assessed using metrics such as accuracy, precision, recall, and F1-score.

### Data Source

The dataset used in this project is the **AI4I 2020 Predictive Maintenance Dataset**, sourced from the UCI Machine Learning Repository: [AI4I 2020 Dataset](https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset).

## Data Pipeline

The data pipeline consists of the following steps:

1. **Extract**: Data is extracted from CSV files and SQL databases.
2. **Transform**: The data is cleaned and transformed, this includes Feature Engineering, Encoding, Outlier detection, Sampling and Scaling the data
3. **Load**: The processed data is loaded into a SQL database for further analysis and model training.

## Installation

To run this project, you need to have Python installed on your machine. Follow these steps to set up the project:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Tushar12023/Predictive-Maintenance.git
   cd Predictive-Maintenance
   ```

2. **Create a Virtual Environment** (optional but recommended):
   ```bash
   python -m venv venv
   ```

3. **Activate the Virtual Environment**:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. **Install Required Packages**:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Run the Jupyter Notebook**:
   - Start Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - Open the `predictive_maintenance.ipynb` notebook.

2. **Execute the Cells**: Run the cells in the notebook to perform data analysis, model training, and evaluation.

3. **View Results**: The notebook will display the results of the model evaluations, including performance metrics and visualizations.

## Model Evaluation

The models are evaluated using the following metrics:

- **Accuracy**: The proportion of correct predictions.
- **Precision**: The ratio of true positive predictions to the total predicted positives.
- **Recall**: The ratio of true positive predictions to the total actual positives.
- **F1-Score**: The harmonic mean of precision and recall.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to modify any sections to better fit your project specifics, such as adding more details about the data sources, model performance, or any additional features you may have implemented. This README provides a comprehensive overview and clear instructions for users to understand and utilize your project effectively.





   
