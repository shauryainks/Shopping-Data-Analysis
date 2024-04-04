# Shopping Data Analysis

This repository contains scripts for analyzing shopping data stored in a CSV file (`shopping.csv`). The Python script (`shopping.py`) utilizes machine learning techniques to train a model and evaluate its performance on predicting whether a visitor made a purchase based on various features.

## Files

1. **shopping.csv**: This file contains the shopping data. Each row represents a visitor session on a shopping website, and columns represent different features such as administrative details, duration, bounce rates, exit rates, page values, etc. The last column indicates whether the visitor made a purchase (`Revenue`).

2. **shopping.py**: This Python script reads the data from `shopping.csv`, preprocesses it, splits it into training and testing sets, trains a k-nearest neighbor classifier (k=1), and evaluates the model's performance. It provides metrics such as accuracy, sensitivity, and specificity.

## Usage

To run the analysis script:

1. Ensure you have Python installed on your system.
2. Install the required dependencies using pip:

```bash
pip install -r requirements.txt
```

3. Run the script by providing the path to the data file (`shopping.csv`) as a command-line argument:

```bash
python shopping.py shopping.csv
```

## Requirements

- Python 3.x
- scikit-learn

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

