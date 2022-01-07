# Introduction
This repo aims to store common tools on volume visualization.

# Env Setting Up
## yt dev

````
conda create -n vis_tools python=3.8
conda activate vis_tools
conda install -c conda-forge yt --only-deps
conda install -c conda-forge cython
pip install --upgrade pip


git clone https://github.com/yt-project/yt vis_yt
cd vis_yt
pip install -v -e .
````
## yt_idv
```
install yt-idv
cd ~
git clone git://github.com/yt-project/yt_idv
cd yt_idv
pip install -e .
conda install -c conda-forge jupyterlab
pip install pooch
pip install h5py
pip install pandas
```

## Glue

```
conda install -c glueviz glueviz=1.0
conda install -c glueviz glue-vispy-viewers
glue
```

## Napari
```
conda install -c conda-forge napari
conda update napari
pip install "napari[all]"
napari
```


## Scenepic
```
pip install scenepic
```

## Ipyvolume
```
pip install ipyvolume
$ conda install -c conda-forge nodejs 
$ jupyter labextension install @jupyter-widgets/jupyterlab-manager
$ jupyter labextension install ipyvolume
$ jupyter labextension install jupyter-threejs
```

# Reference
* http://docs.glueviz.org/en/stable/getting_started/index.html
* https://napari.org/tutorials/fundamentals/getting_started.html
* https://yt-idv.readthedocs.io/en/latest/usage.html
* https://microsoft.github.io/scenepic/
* https://ipyvolume.readthedocs.io/en/latest/