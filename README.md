# scicar23
Slides, notebooks and supporting material for the scicar23 conference

- [Slidedeck](https://docs.google.com/presentation/d/1ZUxhiTCeah78pEVXIJLKkl0oaeWsUkJKkJHwZQNHBj8/edit?usp=sharing)
- [Notebook: Little Picture Sea Ice](https://github.com/littlepictures/scicar23/blob/main/notebooks/LittlePicture_MeltingPoints.ipynb)
- [Notebook: SciCAR Sentinelhub](https://github.com/littlepictures/scicar23/blob/main/notebooks/SciCAR_Sentinelhub.ipynb)
- [Notebook: SciCAR CCI](https://github.com/littlepictures/scicar23/blob/main/notebooks/SciCAR_ClimateDAta.ipynb)
- [Notebook: SciCAR Sea Ice Animation](https://github.com/littlepictures/scicar23/blob/main/notebooks/SciCAR_SeaIceAnimation.ipynb)

To run these notebooks, you need to have the following python packages installed
- jupyterlab
- jupyterlab-geojson
- xcube
- xcube-cci
- xcube-sh

`xcube`, `xcube-cci`, and `xcube-sh` can be installed through conda.
The conda package manager itself can be obtained in the [miniconda
distribution](https://docs.conda.io/en/latest/miniconda.html). 
Once conda is installed, the environment can be installed like this:

```
$ conda create --name scicar23 --c conda-forge xcube xcube-cci xcube-sh jupyterlab jupyterlab-geojson
$ conda activate scicar23
```

Alternatively, you can install the environment with the `environment.yml` file.
To do so, in this folder run:

```
$ conda env create
$ conda activate scicar23
```
