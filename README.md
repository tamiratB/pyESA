# PyCPT 

PyCPT is a python interface to CPT, the IRI Climate Predictability Tool (https://iri-pycpt.github.io/).

I made minor changes to the core PyCPT plotting functions to include administrative boundary shapefiles. If you would like to incorporate these changes for your specific country, please follow these steps and refer to the specific example provided in `exampleNotebooks` for Ethiopia. This has been tested with the latest `pycpt-2.8.2` as installed following the instructions at [PyCPT Installation Guide](https://iri-pycpt.github.io/installation/).

**Steps to follow**

1. Clone this github as follows:

`git clone https://github.com/tamiratB/pyESA`

2. Copy the following files from the cloned repository to the specified directory:

`cp pyESA/pycpt/src/pycpt/{subseasonal.py,notebook.py}`   `/home/username/miniconda3/envs/pycpt-2.8.2/lib/python3.10/site-packages/pycpt/`

*Next steps:*

3. Activate your pycpt conda environment (e.g., `conda activate pycpt-2.8.2`)
4. Run the Jupyter Notebook (e.g., `jupyter-notebook`) and select "Restart & Clear Output".
4. Define the path to your regional shapefiles (refer to the update in `exampleNotebooks/pycpt-operational.ipynb` given in this github).
5. Run all cells in `pycpt-operational.ipynb`.

Enjoy!

