# COVID-19 Daily Cases Prediction with LSTM 🦠📈

This project demonstrates the use of **Long Short-Term Memory (LSTM)** networks to predict daily COVID-19 cases. The model is trained on historical data and used to forecast future cases. 🎯📊

---

## Table of Contents 📑
1. [Overview](#overview-)
2. [Installation](#installation-)
3. [Usage](#usage-)
4. [Code Structure](#code-structure-)
5. [Results](#results-)
6. [License](#license-)

---

## Overview 🚀

This project:
- Uses **LSTM** to model and predict daily COVID-19 cases. 🤖📈
- Leverages historical data from the COVID-19 dataset provided by Johns Hopkins University. 🧠🔍
- Implements data preprocessing, model training, and forecasting. 📊📉

---

## Installation 🛠️

To run this project, you need to install the required libraries. Run the following commands:

```bash
!pip install torch pandas numpy matplotlib seaborn scikit-learn tqdm
```

---

## Usage 🖥️

1. **Load Dataset**: The script downloads and loads the COVID-19 dataset.
2. **Preprocess Data**: Applies data preprocessing, including normalization and sequence creation.
3. **Build Model**: Defines and trains an LSTM model for time series prediction.
4. **Evaluate Model**: Evaluates the model's performance on test data.
5. **Forecast Future Cases**: Predicts future COVID-19 cases using the trained model.

---

## Code Structure 🗂️

- **Data Preparation**:
  - Downloads and preprocesses the COVID-19 dataset.
  - Splits the data into training and test sets.

- **Model Definition**:
  - Defines an LSTM model for time series prediction.
  - Implements a custom PyTorch module for COVID-19 case prediction.

- **Training**:
  - Trains the LSTM model using historical data.
  - Tracks training and test loss over epochs.

- **Evaluation**:
  - Evaluates the model's performance on test data.
  - Visualizes actual vs. predicted cases.

- **Forecasting**:
  - Predicts future COVID-19 cases using the trained model.
  - Visualizes historical and predicted cases.

---

## Results 📊

- **Training/Test Loss**: The model achieves low training and test loss.
- **Prediction Accuracy**: Visualizes the model's predictions against actual data.
- **Future Forecast**: Predicts future COVID-19 cases with reasonable accuracy.

---

## License 📜

This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it as needed.

---

## Example Output 🖼️

Here’s an example of the model's training progress:

```plaintext
Epoch 0 train loss: 0.123 test loss: 0.045
Epoch 10 train loss: 0.045 test loss: 0.032
```

---

## Dependencies 📦

- `torch`
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `tqdm`

---

## Author 👨‍💻

This project was created by **[Navid Falah](https://github.com/navidfalah)**. Feel free to reach out for questions or collaborations at **navid.falah7@gmail.com**! 🤝
