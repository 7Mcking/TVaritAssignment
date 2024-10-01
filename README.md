# TVarit Assignment

This repository contains a Jupyter Notebook for analyzing and processing a dataset related to temperature measurements. The notebook includes data loading, preprocessing, visualization, and model training steps.

## Requirements

To run the notebook, you need to have the following libraries installed:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- tensorflow

You can install the required libraries using the following command:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/TVaritAssignment.git
cd TVaritAssignment
```

2. Ensure you have the dataset file `TVaritDoc.csv` in the same directory as the notebook.

3. Open the Jupyter Notebook:

```bash
jupyter notebook ASSIGNMENT.ipynb
```

4. Run the cells in the notebook to execute the analysis and model training steps.

## Notebook Overview

The notebook is structured as follows:

1. **Import Required Libraries**: Import necessary libraries for data processing and model training.
2. **Load the Dataset**: Load the dataset from a CSV file and display basic information.
3. **Data Preprocessing**: Check for missing values, unique values, and aggregate data by `part_id`.
4. **Data Visualization**: Generate various plots to visualize the data.
5. **Prepare Dataset for Training**: Define functions to split the data into training and testing sets.
6. **Model Training**: Train a machine learning model using the prepared dataset.



## Future Work

1. **Hyperparameter Tuning**: Experiment with different hyperparameters for the models to improve performance.
2. **Feature Engineering**: Explore additional features that could be derived from the existing data to enhance model accuracy.
3. **Model Optimization**: Try other advanced models and optimization techniques to achieve better results.
4. **Cross-Validation**: Implement cross-validation to ensure the robustness of the model.
5. **Data Augmentation**: Consider augmenting the dataset if possible to provide more training data for the models.

## Conclusion

 Model Architectures tried are LSTM, CNN. The results of the model training are unsatisfactory in both cases. As of now I am letting it be due to lack of time.  

This notebook provides a comprehensive workflow for analyzing and processing temperature measurement data. While the initial model results were not satisfactory, there are several avenues for future work that could lead to improved performance. The steps outlined in this notebook serve as a solid foundation for further experimentation and optimization.

## Acknowledgments
- Thanks to TVarit for providing the dataset and the assignment.
