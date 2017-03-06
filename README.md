[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org:/repo/ncsu-libraries/pandas-code4lib-2017)

# Data analysis with Python: An introduction to Pandas and Jupyter Notebooks @ Code4Lib 2017

## Intro

These are the materials for the workshop "Data analysis with Python: An introduction to Pandas and Jupyter Notebooks" presented at Code4Lib 2017 in Los Angeles, CA

## Getting Started

This workshop can be run entirely in a web browser with no prerequisites installed, using a freely available service called "Binder". It can be started by clicking on the badge at the top of this README that says "launch binder". This will spin up a running instance of the Jupyter notebooks in this repository. However, the binder service is not always reliable, so you may need to run a local version of the Jupyter notebook server. We recommend using Anaconda if you do not have Python 3 installed on your computer.

### Anaconda Setup

You can download Anaconda from: https://www.continuum.io/downloads

Be sure to choose the right version for your OS, and also to choose the Python 3.6 version. Once this is installed, either clone or download this repository.

Open a shell of your choice (or the command prompt in Windows if you don't have an alternative shell installed) and run the following commands (replacing /path/to/pandas-code4lib-2017 with the location you downloaded/cloned the repository):

    cd /path/to/pandas-code4lib-2017

    pip install -r requirements.txt

    jupyter notebook

At this point, a web browser should open with a listing of the files in the repository. You're ready to go!

### For participants who already use Python 3

If you already have Python3 and pip installed on your machine, you don't need to install Anaconda. You can just clone the workshop GitHub repository and run the same commands as above.

## Authors

* Kevin Beswick <kdbeswic@ncsu.edu>
* Bret Davidson <bddavids@ncsu.edu>
* Nushrat Khan  <njkhan@ncsu.edu>
