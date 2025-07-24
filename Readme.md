# ICP 4 – Big Data Analyticss

It demonstrates data manipulation using pandas, data cleaning, filtering, and visualization.
## Tasks Completed
 Create and manipulate DataFrames
 Read and clean external CSV data
 Perform statistical analysis
 Filter data with conditions
 Drop and convert columns
 Create scatter plot for Duration vs Calories


## Output 
Scatter plot created between Duration and Calories.


## ICP 5: ML Pipeline with RandomizedSearchCV and Custom Dataset

### Dataset
- **Iris.csv**: A multiclass classification dataset with flower measurements and species labels.

### Tasks completed
Loaded the `iris.csv` dataset
Split into features (X) and target (y)
Built a pipeline with:
StandardScaler for feature scaling
PCA for dimensionality reduction
Classifier (RandomForestClassifier)
 Used `RandomizedSearchCV` for hyperparameter tuning
Evaluated model performance using:
  - 3-fold CV
  - 5-fold CV
  - 7-fold CV

### Outcome
Successfully built and evaluated a machine learning pipeline using `RandomizedSearchCV` and custom CSV input with consistent, high-performing results.

# ICP 6: Feedforward Neural Network with Keras

To build a deep feedforward neural network using the **Keras Sequential API** on the **MNIST dataset**, and experiment with:
- Hidden layers and neuron configurations
- Activation functions (`ReLU`, `tanh`, `sigmoid`)
- Optimizers (`adam`, `sgd`, `rmsprop`)
- Techniques like Batch Normalization and Dropout
### Optimizer Comparison
| Optimizer | Test Accuracy |
|----------|----------------|
| adam     | 98.22%         |
| sgd      | 97.23%         |
| rmsprop  | **98.54%**     |

### Final Optimized Model
- Layers: 5+ hidden layers with `ReLU`
- Enhancements:
  - `BatchNormalization` for stable training
  - `Dropout (0.1)` to prevent overfitting
- Trained for 30+ epochs
- **Final Test Accuracy: 98.54%**


## Student Information
- **Name:** Mandava Anuhya
- **Regd no:** 700767039
- **Course:** DSA 5620 – Big Data Analyticss
- **Semester:** Summer 2025
