# NIDS
Network Intrusion Detection System
# Intrusion Detection System (IDS) Project

This repository contains the code and resources for an Intrusion Detection System (IDS) project. The IDS is designed to analyze network traffic data and classify it as either normal or malicious. It aims to provide an effective solution for detecting and preventing network attacks.

## Table of Contents
- [Project Overview](#project-overview)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Evaluation](#model-evaluation)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
The project focuses on developing an efficient IDS using machine learning techniques. It involves data preprocessing, feature engineering, model training, and comparative analysis of different classification algorithms. The goal is to accurately classify network traffic and improve the overall security of network systems.

## Dependencies
- Python 3.7+
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook (for running the code samples)

## Installation
1. Clone this repository: `git clone https://github.com/AAdebusuyi/NIDS.git`
2. Install the required dependencies: `pip install -r requirements.txt`

## Usage
1. Preprocess the raw network traffic data to remove noise and irrelevant information.
2. Perform feature engineering to extract relevant features from the preprocessed data.
3. Split the dataset into training and testing sets (e.g., 75% for training and 25% for testing).
4. Train the IDS models using the chosen classification algorithms (e.g., Random Forest, Decision Tree, KNN).
5. Evaluate the performance of the models using various metrics such as accuracy, precision, recall, and F1 score.
6. Visualize the results and compare the performance of the different algorithms.

## Dataset
The project uses two widely used datasets in the network security and intrusion detection field: the CIC-IDS2017 dataset and the CSE-CICIDS2018 dataset. The CIC-IDS2017 dataset was created by the Canadian Institute for Cybersecurity (CIC), while the CSE-CIC-IDS2018 dataset is a collaborative project between the Communications Security Establishment (CSE) and the CIC. These datasets provide a realistic representation of network traffic data and contain both benign and malicious traffic samples.

## Model Evaluation
The performance of the IDS models was evaluated using various metrics on the testing set. The metrics include accuracy, precision, recall, and F1 score. The results showed that the Random Forest algorithm outperformed the other two algorithms (Decision Tree and KNN) in terms of overall performance and accuracy.

## Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
