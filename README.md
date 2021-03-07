# hylang-jupyter-notesbooks

Here you find examle Jupyter Hy Language (hylang) Notebooks for my book [A Lisp Programmer Living in Python-Land: The Hy Programming Language](https://leanpub.com/hy-lisp-python).

There is another git repository that contains all of the book examples that you should clone if you have not already done so:

    git clone https://github.com/mark-watson/hy-lisp-python.git
    

Note: December 19, 2020: I am just getting started, please visit later.

## Installing the Hy Plugin for Jupyter

The source code is [here](https://github.com/Calysto/calysto_hy)

Assuming that you have Jupyter Notebook installed, install these three dependencies:

    pip3 install git+https://github.com/ekaschalk/jedhy.git
    pip3 install git+https://github.com/Calysto/calysto_hy.git
    python3 -m calysto_hy install

Start the sample notebook using:

    jupyter notebook Hy_get_started.ipynb
