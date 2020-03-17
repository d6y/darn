# Noodling with DARN

Start with:

```
$ jupyter lab
```

# Install

First install Miniconda3 MacOSX 64-bit pkg (Python 3.7)

Then:

```
$ conda create -n darn python=3
$ cd darn

$ more .envrc
eval "$(conda shell.bash hook)"
conda activate darn

$ conda install -c conda-forge jupyterlab=1.1.4
$ conda install -c anaconda cmake -y 
$ conda install -c conda-forge nodejs -y 
$ jupyter labextension install @jupyterlab/plotly-extension 
$ jupyter labextension install @shahinrostami/theme-purple-please 
```

To reset:

```
$ conda remove --name darn --all
```


