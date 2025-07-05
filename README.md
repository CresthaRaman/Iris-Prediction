# Iris-Prediction

## Project Description

This project demonstrates machine learning classification using the famous Iris dataset. The goal is to predict the species of Iris flowers based on their physical characteristics (sepal and petal measurements). This is a classic beginner-friendly machine learning project that showcases data analysis, visualization, and classification techniques using Python and scikit-learn.

## Dataset

The project uses the **Iris dataset** (`Iris.csv`), which contains 150 samples of Iris flowers with the following features:

- **Id**: Unique identifier for each sample
- **SepalLengthCm**: Length of the sepal in centimeters
- **SepalWidthCm**: Width of the sepal in centimeters  
- **PetalLengthCm**: Length of the petal in centimeters
- **PetalWidthCm**: Width of the petal in centimeters
- **Species**: Target variable with three classes:
  - Iris-setosa
  - Iris-versicolor
  - Iris-virginica

The dataset is well-balanced with 50 samples per species and is commonly used for learning classification algorithms.

## Project Workflow

The machine learning pipeline in `Iris.ipynb` follows these steps:

1. **Data Loading**: Import the Iris dataset using pandas
2. **Data Exploration**: 
   - Display dataset shape and basic information
   - Show first few rows to understand the data structure
3. **Data Visualization**: 
   - Create correlation heatmap using seaborn to understand feature relationships
4. **Data Preprocessing**:
   - Split features (X) and target variable (y)
   - Split data into training (70%) and testing (30%) sets using `train_test_split`
5. **Model Training**: 
   - Train a K-Nearest Neighbors (KNN) classifier with k=20
6. **Model Evaluation**:
   - Calculate accuracy score
   - Generate confusion matrix
   - Create detailed classification report with precision, recall, and F1-score

## Requirements

The project requires the following Python libraries:

```bash
pip install scikit-learn pandas matplotlib seaborn numpy
```

### Individual Library Installation:
- **scikit-learn**: For machine learning algorithms and evaluation metrics
- **pandas**: For data manipulation and analysis
- **matplotlib**: For basic plotting and visualization
- **seaborn**: For advanced statistical visualizations
- **numpy**: For numerical computations (typically installed with scikit-learn)

## Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/CresthaRaman/Iris-Prediction.git
   cd Iris-Prediction
   ```

2. **Install required dependencies**:
   ```bash
   pip install scikit-learn pandas matplotlib seaborn numpy
   ```

3. **Run the Jupyter notebook**:
   ```bash
   jupyter notebook Iris.ipynb
   ```
   
   Or if using JupyterLab:
   ```bash
   jupyter lab Iris.ipynb
   ```

4. **Execute the cells**: Run all cells in order to see the complete workflow from data loading to model evaluation.

## Results

The K-Nearest Neighbors classifier with k=20 achieved excellent performance on the Iris dataset:

- **Accuracy**: 100% (1.0)
- **Precision**: 1.00 for all classes
- **Recall**: 1.00 for all classes
- **F1-Score**: 1.00 for all classes

The perfect classification results demonstrate that the Iris dataset features provide clear separation between the three species, making it an ideal dataset for learning classification concepts.

### Key Findings:
- All three Iris species can be perfectly distinguished using the four flower measurements
- The correlation heatmap reveals strong relationships between petal measurements and species classification
- KNN with k=20 proved to be an effective algorithm for this particular dataset

## License

This project is created for educational purposes. The Iris dataset is publicly available and commonly used in machine learning education and research. Feel free to use this code for learning and educational activities.