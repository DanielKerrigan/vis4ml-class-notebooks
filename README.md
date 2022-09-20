# VIS4ML Notebooks

Jupyter notebooks for CS 7295 - Special Topics: Data Visualization for Machine Learning.

You can run these notebooks on [Google Colab](http://colab.research.google.com/github/DanielKerrigan/vis4ml-class-notebooks).

You can also run them locally:

```bash
# clone the repo
git clone https://github.com/DanielKerrigan/vis4ml-class-notebooks.git
cd vis4ml-class-notebooks

# create a virtual environment
conda create -n vis4ml python=3.10
conda activate vis4ml

# if you are using conda, you may need to add conda-forge as a channel
# in order to get the latest version of Altair
conda config --add channels conda-forge
conda config --set channel_priority strict 

# install dependencies
conda install --file requirements.txt

# run the server
jupyter notebook
```
