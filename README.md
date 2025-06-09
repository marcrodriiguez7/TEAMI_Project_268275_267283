# Time Series Forecasting Using LSTM in PyTorch

## Project Overview

This project implements a multivariate time series forecasting model using Long Short-Term Memory (LSTM) networks in PyTorch.  
The focus is on daily weather prediction for Madrid (1997-2015), leveraging temporal dependencies and multiple input features.

---

## Dataset Preparation

1. Download the dataset manually from Kaggle:

   [Weather Madrid LEMD 1997-2015 (Kaggle)](https://www.kaggle.com/datasets/juliansimon/weather_madrid_lemd_1997_2015.csv)

2. Place the downloaded CSV file inside a folder named `data` at the root of the project directory.

3. Ensure the notebook’s path variables point correctly to this file (e.g., `data/weather_madrid_LEMD_1997_2015.csv`).

---

## How to Run

1. Open the Jupyter notebook or Google Colab notebook provided in the repository.

2. Verify that the data path variables are correctly set to your local dataset location.

3. Run the notebook cells sequentially
   
4. Training progress and metrics will be displayed during execution.

---

## Notes

* GPU acceleration is recommended for faster training, especially on longer sequences or larger batch sizes.
* Random seeds are set in the notebook to ensure reproducibility.
* Hyperparameters such as learning rate, loss function, num layers, hidden size and others can be adjusted in the notebook.

---

## Disclaimer

This project is intended for educational and research purposes only.
No guarantees are provided regarding the accuracy, reliability, or robustness of the predictions.
Use the results and models at your own discretion and risk.

---
