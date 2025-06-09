# Time Series Forecasting Using LSTM in PyTorch

## Project Overview

This project implements a multivariate time series forecasting model using Long Short-Term Memory (LSTM) networks in PyTorch.  
The focus is on daily weather prediction for Madrid (1997-2015), leveraging temporal dependencies and multiple input features.

---

### Environment Setup

To ensure reproducibility and compatibility, please make sure the following environment is set up:

#### Recommended Environment

* **Python** ≥ 3.8
* **PyTorch** ≥ 1.10
* **Google Colab** or **Jupyter Notebook** (recommended for GPU access and visualization)

#### Required Python Libraries

We will be using the following libraries throughout this notebook:

* `torch` — for building and training neural networks
* `numpy` — for numerical operations
* `pandas` — for data manipulation
* `matplotlib` and `seaborn` — for data visualization
* `scikit-learn` — for preprocessing, metrics, and model utilities

#### Install Dependencies

If running locally (not on Colab), install the required libraries using:

```bash
pip install torch numpy pandas matplotlib seaborn scikit-learn
```

If you're using **Google Colab**, all libraries except `seaborn` may already be installed. To be safe, run the following cell:

```python
!pip install --quiet torch numpy pandas matplotlib seaborn scikit-learn
```

#### Mount Google Drive (Colab only)

If your dataset is stored in Google Drive:

```python
from google.colab import drive
drive.mount('/content/drive')
```

---

## Dataset Preparation

1. Download the dataset manually from Kaggle:

   [Weather Madrid LEMD 1997-2015 (Kaggle)](https://www.kaggle.com/datasets/juliansimon/weather_madrid_lemd_1997_2015.csv)

2. Place the downloaded CSV file inside a folder named `data` at the root of the project directory.

3. Ensure the notebook’s path variables point correctly to this file (e.g., `data/weather_madrid.csv`).

---

## How to Run

1. Open the Jupyter notebook or Google Colab notebook provided in the repository.

2. Verify that the data path variables are correctly set to your local dataset location.

3. Run the notebook cells sequentially:

   * Data loading and preprocessing
   * Feature engineering (including categorical variable encoding)
   * Model definition and training with LSTM in PyTorch
   * Evaluation and comparison with baseline models
   * Visualization of predictions and metrics

4. Training progress and metrics will be displayed during execution.

---

## Notes

* GPU acceleration is recommended for faster training, especially on longer sequences or larger batch sizes.
* Random seeds are set in the notebook to ensure reproducibility.
* Hyperparameters such as learning rate, , loss function, num layers, hidden size and others can be adjusted in the notebook.

---

## Disclaimer

This project is for educational and research purposes only.
No guarantees are made regarding prediction accuracy or model robustness.
Use at your own discretion.

---
