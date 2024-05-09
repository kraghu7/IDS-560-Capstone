
README for Contract Prediction Notebook
(kritikaraghhuwanshi.17@gmail.com)


#### Overview
This Jupyter notebook provides a complete workflow for predicting contract awards. It includes data preprocessing, exploratory data analysis, model training, and evaluation.

#### Requirements
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

#### Installation
To install the required Python libraries, run the following command:
```
pip install pandas numpy matplotlib seaborn scikit-learn
```

#### Dataset
The notebook expects a dataset with specific fields relevant to contracts, such as 'Contract_Awarded', 'Award Type', and 'Type of Contract'.

#### Usage
1. Load your dataset into the notebook.
2. Follow the steps in the notebook to preprocess the data.
3. Execute the cells under the "Model Training" section to train the models.
4. Review the model performance metrics and visualizations generated at the end of the notebook.

#### Features
- **Data Preprocessing**: Includes handling missing values and scaling numerical data.
- **Model Training**: Compares several models (e.g., Random Forest, Decision Tree) on the preprocessed data.
- **Performance Evaluation**: Evaluates models based on accuracy, precision, recall, and F1-score.
- **Visualization**: Visualizes the most common award types and contract types among awarded contracts.