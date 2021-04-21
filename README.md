# binder-for-gromacs

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/yychuang/binder-for-gromacs/HEAD?filepath=index.ipynb)  (notebook) 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/yychuang/binder-for-gromacs/HEAD?urlpath=lab) (lab)


If you use `environment.yml`, then Binder will use a Miniconda distribution
to install your packages. However, you may still want to use `pip`. In
this case, you should **not** use a `requirements.txt` file, but instead use
a `- pip` section in `environment.yml`. This repository is an example of how
to construct your `environment.yml` file to accomplish this.

* `apt.txt` for apt-installing gromacs
* `environment.yml` for installing the python dependencies
* `postBuild` for jupyter notebook and lab settings

