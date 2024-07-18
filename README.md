# PyCPT 

PyCPT is a python interface to CPT, the IRI Climate Predictability Tool.

I made minor changes to the core pycpt plotting functions to include administrative boundary shape files.

**Steps to follow**

1. Clone this github as follows:

`git clone https://github.com/tamiratB/pyESA`

2. Copy the following files from the cloned repository to the specified directory:

`cp pyESA/pycpt/src/pycpt/{subseasonal.py,notebook.py}`   `/home/username/miniconda3/envs/pycpt-2.8.2/lib/python3.10/site-packages/pycpt/`

*Next steps:*

3. Run the Jupyter Notebook and select "Restart & Clear Output".
4. Define the path to your regional shapefiles (refer to the update in `exampleNotebooks/pycpt-operational.ipynb` given in this github).
5. Run all cells in `pycpt-operational.ipynb`.

Enjoy!

