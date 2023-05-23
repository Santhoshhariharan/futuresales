# Sales Prediction using Advertisement and Previous Year Sales Data

This repository contains a predictive model that aims to forecast future sales for a company based on advertisement data and previous year sales data. The model utilizes machine learning techniques to analyze historical patterns and relationships between advertising efforts and sales performance, enabling accurate sales predictions.

## Project Structure

The repository consists of the following files:

- `data/`: This directory contains the dataset files used for training and testing the predictive model. Ensure that the necessary data files are placed in this directory before running the code.
- `notebooks/`: This directory contains Jupyter notebooks that walk through the data analysis, model development, and evaluation process.
- `src/`: This directory contains the source code for the predictive model.
  - `data_preparation.py`: This script handles data preprocessing tasks such as cleaning, feature engineering, and splitting the dataset into training and testing sets.
  - `model.py`: This script implements the predictive model, training it on the training data and generating sales predictions for the test data.
  - `evaluation.py`: This script evaluates the performance of the model by calculating relevant metrics and generating visualizations.
  - `main.py`: This script serves as the entry point to the project, orchestrating the data preparation, model training, prediction, and evaluation steps.
- `requirements.txt`: This file lists the dependencies required to run the project. Install the dependencies by running `pip install -r requirements.txt`.
- `README.md`: This file provides an overview of the project, its structure, and instructions for running the code.

## Usage

To use the predictive model and generate sales predictions, follow these steps:

1. Clone the repository to your local machine: 
```
git clone https://github.com/your-username/sales-prediction.git
```

2. Navigate to the project directory:
```
cd sales-prediction
```

3. Install the required dependencies:
```
pip install -r requirements.txt
```

4. Place the advertisement data and previous year sales data in the `data/` directory. Ensure that the data files are in the appropriate format.

5. Open a terminal or command prompt and run the following command to execute the main script:
```
python src/futuresales.py
```

6. The script will preprocess the data, train the model, generate sales predictions, and evaluate the model's performance. The results will be displayed in the terminal and saved in the `results/` directory.

## Contributing

If you'd like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your contribution: `git checkout -b feature/your-feature`.
3. Commit your changes: `git commit -am 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Submit a pull request with a detailed description of your changes.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to explore, use, and modify the code according to your needs.

![image](https://github.com/Santhoshhariharan/futuresales/assets/104808335/5e008310-8b82-40c4-8473-605ece3bd714)
![image](https://github.com/Santhoshhariharan/futuresales/assets/104808335/4e8fc2b7-cffa-4a19-99ad-4d78b3388a50)
![image](https://github.com/Santhoshhariharan/futuresales/assets/104808335/9c0b116d-bf8a-4c6d-90fb-67f92d0fafac)
![image](https://github.com/Santhoshhariharan/futuresales/assets/104808335/b09b6a2b-e98e-435a-9e69-0007ac1206b6)
![image](https://github.com/Santhoshhariharan/futuresales/assets/104808335/8fecb68a-0dba-4678-9b15-81bb84ba270b)
