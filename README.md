# nac-2017
NAC2017 talk: A Billion stars in the Jupyter notebook

* [my notebook on nbviewer](http://nbviewer.jupyter.org/github/maartenbreddels/nac-2017/blob/master/nac-2017.ipynb)

* to reproduce
  * (ana)conda
    * conda install -c conda-forge vaex ipyvolume notebook bqplot
  * pip
    * pip install —pre vaex
    * pip install ipyvolume bqplot
    * jupyter nbextension enable --py ipyvolume
    * jupyter nbextension enable --py bqplot
    * jupyter nbextension enable --py widgetsnbextension
