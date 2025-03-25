# Chronic Kidney Disease (CKD) Prediction

## Overview
This project predicts the likelihood of Chronic Kidney Disease (CKD) based on various health parameters using machine learning techniques. The goal is to provide an early detection system that can help in medical diagnosis.

## Features
- Data preprocessing and feature selection
- Machine learning model training and evaluation
- Visualization of key insights


## Technologies Used
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib/Seaborn (for visualization)


## Installation
### Prerequisites
Ensure you have Python installed (>=3.7). Install the required dependencies using:

```bash
pip install -r requirements.txt
```

## Usage
### Training the Model
Run the following command to train the model:
```bash
python train.py
```

### Making Predictions
Once trained, you can make predictions using:
```bash
python predict.py --input sample_data.csv
```


Then access predictions via:
```bash
http://localhost:5000/predict
```

## Model Performance
The model is evaluated using the following metrics:
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC curve

## Future Improvements
- Enhance feature engineering
- Experiment with different ML models (e.g., Random Forest, XGBoost, Deep Learning)

## Contributing
Contributions are welcome! Feel free to submit pull requests or raise issues.

## License
This project is licensed under the MIT License.

---
Developed by **Mohammed Ameruddin**
