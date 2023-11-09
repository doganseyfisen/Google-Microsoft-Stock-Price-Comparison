# Google-Microsoft-Stock-Price-Comparison

This project is designed to provide a visual comparison of the closing stock prices between Google (GOOG) and Microsoft (MSFT) over a specified time period. We use Python for data manipulation and Matplotlib for data visualization.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python (3.x recommended)
- [JupyterLab or Notebook](https://jupyter.org/) (optional, for interactive execution)
- Pandas (Python library for data manipulation)
- Matplotlib (Python library for data visualization)

You can install the required libraries using pip:

```bash
pip install pandas matplotlib
```

## Usage

1. Clone this repository or download the `notebook.ipynb` file.
2. Obtain historical stock price data in CSV format for Google (GOOG) and Microsoft (MSFT) for the desired time frame. You can download these CSV files from [Yahoo Finance](https://finance.yahoo.com/) or any other reliable source.
3. Rename the CSV files as "GOOG.csv" and "MSFT.csv" and place them in the same directory as the `notebook.ipynb` file.

## Running the Code

Open your command prompt or terminal and navigate to the directory containing the `notebook.ipynb` file and CSV files. Then, run the following command:

```bash
jupyter notebook notebook.ipynb
```
or
```bash
jupyter-lab notebook.ipynb
```

This will execute the Python script and generate a line plot comparing the closing stock prices of GOOG and MSFT over time. Additionally, it will highlight the highest and lowest prices with markers and display the average prices at the end of the plot.

## Sample Output

![output](https://github.com/doganseyfisen/Google-Microsoft-Stock-Price-Comparison/assets/118891768/f9ac4a30-213e-44de-94ed-cd11cf74031e)

## Contributing

If you wish to contribute to this project, feel free to create a pull request. We welcome any enhancements or additional features.

## Author 

Doğan Seyfi Şen

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
