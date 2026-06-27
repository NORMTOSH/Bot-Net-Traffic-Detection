# Machine Learning for Detecting Botnet Traffic

## Overview
This project develops and evaluates deep learning models for detecting botnet traffic in IoT network datasets. It performs data exploration, preprocessing, feature analysis, and trains multiple neural network architectures including CNN, LSTM, GRU, and hybrid CNN-LSTM/CNN-GRU models.

## Features
- Exploratory Data Analysis (EDA)
- Data preprocessing and labeling
- IoT botnet traffic classification
- Multiple deep learning baselines
- Hybrid deep learning architectures
- Performance comparison of models

## Dataset
The notebook uses the **N-BaIoT** dataset (loaded from Kaggle input files), containing:
- Benign network traffic
- Mirai attack variants
- Gafgyt attack variants
- Device metadata and feature descriptions
- Link: https://www.kaggle.com/code/normangitosh/machine-learning-for-detecting-botnet-traffic

## Project Workflow
1. Load device and feature information
2. Import benign and attack traffic
3. Label attack classes
4. Merge datasets
5. Perform EDA
6. Preprocess data
7. Train CNN, LSTM, and GRU models
8. Train Hybrid CNN-LSTM and CNN-GRU models
9. Compare model performance

## Models
| Model | Purpose |
|-------|---------|
| 1D CNN | Spatial feature extraction |
| LSTM | Sequential traffic analysis |
| GRU | Efficient sequence learning |
| Hybrid CNN + LSTM | Combined spatial & temporal learning |
| Hybrid CNN + GRU | Lightweight hybrid architecture |

## Technologies
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras

## Repository Structure
```
.
├── machine_learning_for_detecting_botnet_traffic.ipynb
└── README.md
```

## Getting Started
Install dependencies:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
```

Run the notebook in Jupyter Notebook or upload it to Kaggle with the N-BaIoT dataset available.

## Results
The notebook compares multiple deep learning architectures for IoT botnet detection and highlights the effectiveness of hybrid CNN-based models for learning both spatial and temporal traffic patterns.

## Future Improvements
- Hyperparameter optimization
- Cross-validation
- Additional IoT datasets
- Explainable AI (SHAP/LIME)
- Real-time deployment

## License
This project is intended for academic and research purposes.

## Author
Norman Gitonga
