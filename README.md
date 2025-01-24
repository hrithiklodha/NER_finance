# Building a Named Entity Recognition (NER) System for Financial Text

This project involves building a Named Entity Recognition (NER) system specifically for financial text. The process includes scraping data from financial websites and then processing the text data to train an NER model.

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.6 or higher
- Jupyter Notebook
- Required Python libraries (listed in `requirements.txt`)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/ner_finance.git
    cd ner_finance
    ```

2. Install the required Python libraries:

    ```bash
    pip install -r requirements.txt
    ```

## Steps to Run

### 1. Run the [scrape_data.ipynb](http://_vscodecontentref_/2) File

This notebook is responsible for scraping financial data from websites.

1. Open the Jupyter Notebook:

    ```bash
    jupyter notebook scrape_data.ipynb
    ```

2. Run all cells in the notebook to scrape the data. The scraped data will be saved to a CSV file.

### 2. Run the [nlp_process.ipynb](http://_vscodecontentref_/3) File

This notebook processes the scraped data and trains the NER model.

1. Open the Jupyter Notebook:

    ```bash
    jupyter notebook nlp_process.ipynb
    ```

2. Run all cells in the notebook to process the data and train the NER model. The trained model will be saved to the specified directory.

## Project Structure

- [scrape_data.ipynb](http://_vscodecontentref_/4): Notebook for scraping financial data.
- [nlp_process.ipynb](http://_vscodecontentref_/5): Notebook for processing text data and training the NER model.
- [README.md](http://_vscodecontentref_/6): This file.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.