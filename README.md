 # Self Healing AI for Network Security
This repository contains notebooks and models for detecting cyber threats and classifying attacks using machine learning and deep learning techniques. Following that, real-time implementation was done using synthetic data and self-healing mechanisms were implemented. 

## Project Overview

This project aims to enhance cybersecurity by implementing the following primary tasks:

1. **Threat Detection**: Using an ensemble of Artificial Neural Networks (ANN) and Long Short-Term Memory (LSTM) models.
2. **Attack Classification**: Using a Decision Tree model to classify different types of attacks.
3. **Self-Healing Mechanism**: Based on attack classification, implementing self-healing mechanisms in real-time.
4. **Dashboards and Visualisation**: Use of dashboards for real-time threat detection and attack classification. 



## Notebooks

### 1. Threat Detection Model - Ensembling LSTM and ANN
This notebook includes the following:
- **Data Loading and Preprocessing**: Loading the dataset, handling missing values, encoding categorical variables, and feature scaling.
- **Model Training**:
  - **ANN Model**: Binary classification using a deep neural network.
  - **LSTM Model**: Sequential data classification using LSTM layers.
  - **Ensemble Model**: Combining predictions from ANN and LSTM models.
- **Model Evaluation**: Accuracy, confusion matrix, ROC curve, and AUC score.
- **Model Saving**: Saving the trained models and ensemble model.

### 2. Attack Classification
This notebook includes:
- **Data Loading and Preprocessing**: Combining multiple datasets, handling missing values, encoding categorical variables, and feature scaling.
- **Model Training**: Decision Tree model to classify different types of attacks.
- **Model Evaluation**: Accuracy, confusion matrix, and classification report.
- **Model Saving**: Saving the trained Decision Tree model.

### 3. Dashboard
This notebook includes:
- **Real-Time Monitoring**: Streaming data, making predictions using the ensemble model, and logging results.
- **Visualization**: Displaying real-time predictions and plotting attack distribution.
- **Self-Healing Dashboard**: Using the Decision Tree model for real-time attack classification and visualization.

## Models

The following models are trained and saved in this project:
- ANN Model: `ANN_model.h5`
- LSTM Model: `LSTM_model.h5`
- Ensemble Model: `ensemble_model.pkl`
- Decision Tree Model: `decision_tree_model.joblib`

**Also, note that, these models were originally saved on my drive so they have their paths accordingly. Please change the paths according to your need on your side.**

## Dependencies

To run the notebooks and scripts in this repository, you need the following libraries:
<li> `numpy` </li> 
<li>  `pandas`</li> 
<li>  `seaborn`</li> 
<li>  `matplotlib`</li> 
<li>  `sklearn`</li> 
<li>  `tensorflow`</li> 
<li>  `joblib` </li> 

You can install these dependencies using the following command:

```bash
pip install numpy pandas seaborn matplotlib scikit-learn tensorflow joblib
```

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/threat-detection-and-attack-classification.git
   cd threat-detection-and-attack-classification
   ```

2. **Run the Notebooks**: Open the Jupyter notebooks in the order mentioned above and run the cells.

3. **Monitor Real-Time Data**: Use the Dashboard notebook to visualize and monitor real-time predictions.

4. **Analyze Results**: Use the saved models to make predictions on new data and analyze the results.

## Future Work

<li> Enhance the real-time dashboard with additional visualizations. </li>
<li> Implement more advanced machine learning models for improved accuracy. </li>
<li> Explore other datasets for a more comprehensive analysis.</li>

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any improvements or new features.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.




