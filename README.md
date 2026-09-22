# ODE course example sheets

This folder contains three example-sheet notebooks and their corresponding
solutions. Example 3 also uses `examples_3_data.csv`.

## Option 1: Run the notebooks locally

Install [Miniconda](https://docs.conda.io/projects/miniconda/en/latest/) or
Anaconda, open a terminal in this folder, and create the supplied environment:

```bash
conda env create -f environment.yml
conda activate ode-course
```

You can then start JupyterLab:

```bash
jupyter lab
```

Open one of `examples_1.ipynb`, `examples_2.ipynb`, or `examples_3.ipynb` in
the browser window that appears. To remove the environment later, run
`conda env remove -n ode-course`.

Alternatively, open this folder in **Visual Studio Code** (with the Python and
Jupyter extensions) or **PyCharm** (with Jupyter notebook support). Select the
Python interpreter or notebook kernel named `ode-course` before running cells.

## Option 2: Run the notebooks online with Google Colab

1. Go to [Google Colab](https://colab.research.google.com/) and sign in.
2. Choose **File > Upload notebook**, then upload the example `.ipynb` file
   you want to use.
3. Run each cell using its play button or choose **Runtime > Run all**.

Colab already provides the Python packages used by these notebooks, so the
Conda environment file is not needed there. For Example 3, open the **Files**
panel on the left and upload `examples_3_data.csv` as well. The notebook and
CSV should remain in the same working directory. Colab session files are
temporary, so the CSV may need to be uploaded again after reconnecting.
