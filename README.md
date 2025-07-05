# Iris-Prediction

A machine learning project that predicts iris flower species using the classic Iris dataset. This project implements a K-Nearest Neighbors (KNN) classifier in a Jupyter Notebook to classify iris flowers into three species: Iris-setosa, Iris-versicolor, and Iris-virginica.

## Features

- 🌸 **Species Classification**: Predicts iris flower species based on sepal and petal measurements
- 📊 **Data Visualization**: Interactive plots and correlation heatmaps for exploratory data analysis
- 🤖 **Machine Learning**: K-Nearest Neighbors algorithm implementation using scikit-learn
- 📈 **Model Evaluation**: Comprehensive performance metrics including accuracy, confusion matrix, and classification report
- 📓 **Interactive Notebook**: Step-by-step implementation in Jupyter Notebook format

## Dataset

This project uses the famous Iris dataset, which contains 150 samples of iris flowers with the following features:

- **SepalLengthCm**: Length of the sepal in centimeters
- **SepalWidthCm**: Width of the sepal in centimeters
- **PetalLengthCm**: Length of the petal in centimeters
- **PetalWidthCm**: Width of the petal in centimeters
- **Species**: Target variable with three classes:
  - Iris-setosa
  - Iris-versicolor
  - Iris-virginica

## Prerequisites

Before running this project, make sure you have the following installed:

- Python 3.7 or higher
- Jupyter Notebook or JupyterLab
- Required Python packages (see installation instructions below)

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/CresthaRaman/Iris-Prediction.git
cd Iris-Prediction
```

### 2. Install Dependencies

Install the required Python packages using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

Or if you prefer using conda:

```bash
conda install pandas numpy matplotlib seaborn scikit-learn jupyter-notebook
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open and Run the Notebook

1. Open `Iris.ipynb` in your browser
2. Run all cells sequentially to see the complete analysis
3. Explore the data visualization and model results

## Project Structure

```
Iris-Prediction/
│
├── README.md                 # Project documentation
├── Iris.ipynb               # Main Jupyter notebook with ML implementation
└── Iris.csv                 # Iris dataset
```

## Implementation Details

The project follows a standard machine learning workflow:

1. **Data Loading**: Load the Iris dataset from CSV file
2. **Exploratory Data Analysis**: 
   - Display dataset information and statistics
   - Create correlation heatmaps to understand feature relationships
3. **Data Preprocessing**: 
   - Split features (X) and target variable (y)
   - Divide data into training and testing sets (70-30 split)
4. **Model Training**: 
   - Implement K-Nearest Neighbors classifier with k=20
   - Train the model on the training dataset
5. **Model Evaluation**:
   - Make predictions on test data
   - Calculate accuracy score
   - Generate confusion matrix
   - Produce detailed classification report

## Results

The K-Nearest Neighbors model achieves excellent performance on the Iris dataset:

- **Accuracy**: 100% on the test set
- **Precision**: 1.00 for all three species
- **Recall**: 1.00 for all three species
- **F1-Score**: 1.00 for all three species

This high performance is typical for the Iris dataset, as it's a well-separated, clean dataset that's ideal for classification algorithms.

## Key Libraries Used

- **pandas**: Data manipulation and analysis
- **numpy**: Numerical computations
- **matplotlib**: Basic plotting and visualization
- **seaborn**: Statistical data visualization
- **scikit-learn**: Machine learning algorithms and evaluation metrics

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please:

1. Fork the repository
2. Create a new feature branch (`git checkout -b feature/your-feature-name`)
3. Make your changes and commit them (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature-name`)
5. Create a new Pull Request

### Ideas for Contributions

- Implement additional classification algorithms (Random Forest, SVM, etc.)
- Add cross-validation for more robust model evaluation
- Create interactive visualizations using plotly
- Add feature scaling/normalization techniques
- Implement hyperparameter tuning
- Add model comparison and selection

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgements

- The Iris dataset was originally collected by Edgar Anderson and made famous by Ronald A. Fisher
- Thanks to the scikit-learn community for providing excellent machine learning tools
- Inspiration from the classic machine learning educational examples

---

**Note**: This project is designed for educational purposes and demonstrates fundamental machine learning concepts using one of the most well-known datasets in the field.