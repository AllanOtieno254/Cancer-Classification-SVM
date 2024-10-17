# Cancer Classification using SVM

This repository contains a machine learning project aimed at classifying cancer types based on features extracted from cell samples using a Support Vector Machine (SVM) model.

**Introduction to Support Vector Machine(SVM):** Used SVM to build and train a model using human cell records, and classify cells to whether the samples are benign (mild state) or malignant (evil state).

SVM works by mapping data to a high-dimensional feature space so that data points can be categorized, even when the data are not otherwise linearly separable (This gets done by kernel function of SVM classifier). A separator between the categories is found, then the data is transformed in such a way that the separator could be drawn as a hyperplane.**


## Project Structure

- `data/`: Contains datasets used for model training and predictions.
- `models/`: Contains the saved SVM model for making predictions.
- `notebooks/`: Jupyter notebooks for exploratory data analysis and modeling.
- `src/`: Scripts for data preprocessing, model training, and making predictions.
- `requirements.txt`: Required packages for the project.
- `README.md`: Project documentation.
- `LICENSE`: License information.

## Dataset

The dataset used for training and testing can be found in the `data/` folder. Ensure that the feature columns are properly formatted for predictions.

# confusion matrix
<img width="399" alt="confusion matrix" src="https://github.com/user-attachments/assets/8c37eb81-4153-40ed-9551-c623c84b074f">

<img width="386" alt="confusion matrix2" src="https://github.com/user-attachments/assets/189561a1-c94b-488f-b428-616d7194f945">

# field names and descriptions

<img width="307" alt="Screenshot 2024-10-16 084625" src="https://github.com/user-attachments/assets/ce4beb6c-56ca-484d-8dee-1a68a4603366">

# Usage
1Preprocess the data using data_preprocessing.py.
2.Train the model using model_training.py.
3.Make predictions on new data using predictions.py.

### License
Consider using the **MIT License** for your project. You can include a `LICENSE` file with the following content:
  markdown
MIT License

Copyright (c) [year] [your name]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

[...]

## Installation

To install the required packages, run:
```bash
pip install -r requirements.txt
