# Camelot PDF Table Extraction
Jupyter notebook for extracting tables from PDF documents using Camelot

Camelot is an open-source Python library, that enables developers to extract all tables from the PDF document and convert it to Pandas Dataframe format: https://camelot-py.readthedocs.io/

#### Installation

1. Camelot has two dependencies Ghostscript and Tkinter which must first be installed. The installation process differs depending on your operating system: https://camelot-py.readthedocs.io/en/master/user/install-deps.html#install-deps
2. Install Camelot: pip install "camelot-py[cv]" OR conda install -c conda-forge camelot-py.
Note: Camelot only works with text-based PDFs, not scanned documents.
3. Visual debugging using Camelot's `plot()` function requires matplotlib which is an optional dependency. You can install it using `pip install camelot-py[plot]` if matplotlib is not already included in your python development environment.

#### Quickstart

Useful quickstart guides can be found here:

- Extract Tables from PDF file in a single line of Python Code
- Extracting tabular data from PDFs made easy with Camelot.
