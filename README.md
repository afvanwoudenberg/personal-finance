# Personal Finance

The CAMT.053 file format is a standard XML format for exporting transactions and account balances to, for example, an accounting package. Most (European) banks allow their customers to download their transactions and balances in this file format from their banking portal. This repository contains a Jupyter Notebook that shows how to import CAMT.053 files into a Pandas dataframe. Besides reading CAMT.053 files into dataframes, the Jupyter notebook also demonstrates how to categorize transactions and display some useful graphs using Matplotlib.

## Getting Started

### Prerequisites

* [Anaconda](https://www.anaconda.com/distribution/) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) must be installed on your machine.
* You should have basic knowledge of using Anaconda or Miniconda.

### Installing

1. Clone the repository:
```bash
git clone https://github.com/afvanwoudenberg/personal-finance.git
```

2. Navigate into the project folder:
```bash
cd personal-finance
```

3. Create the conda environment from the environment.yml file:
```bash
conda env create -f environment.yml
```

4. Activate the conda environment:
```bash
conda activate personal-finance
```

5. Download CAMT.053 files from your banking portal and place them into the import folder.

6. Start Jupyter Notebook:
```bash
jupyter notebook
```

7. Open `personal_finance.ipynb` in the browser and run the notebook. You may want to personalize and extend the code that takes care of categorizing the transactions.

### Additional Files

Included are four XSLT stylesheets that take care of flattening the CAMT.053 files. These files are referenced from the Jupyter Notebook.

### Links

Blog post: https://aswinvanwoudenberg.com/posts/from-camt053-to-charts/

## Author

Aswin van Woudenberg ([afvanwoudenberg](https://github.com/afvanwoudenberg))

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

