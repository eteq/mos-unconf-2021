# mos-unconf-2021

Erik Tollerud (@eteq)


These materials are heavily derived from the Astropy workshop on specutils (https://github.com/astropy/astropy-workshop) and the JWebbinar (https://github.com/spacetelescope/jwebbinar_prep/tree/webbinar2)


## Instructions at unconf

1. Either clone https://github.com/eteq/mos-unconf-2021 if you know git, or use the ZIP download option to get the notebooks.
2. Make sure you followed the instructions you got and that are pinned in the Slack thread to install the things you need.
3. If you followed those instructions, do conda activate mos-unconf in a terminal
4. ``cd`` into wherever you downloaded the notebooks
5. Do jupyter notebook to start jupyter - it should open a web browser.

If you’re having trouble, don’t worry, you can follow along with by screen and then once we are doing our own time I or someone else can help you.


## Install instructions

For this unconference session (same session on Tuesday and Thursday) you will need a Python environment set up that is capable of running Jupyter notebooks with the astropy and specutils packages.If you are new to Python, you may want to look here for some resources on how to install and learn the basics of Python.Depending on your preferences and system choices, you may find the install instructionsthere sufficient, but note that many scientists find it easier to use the Anacondapython distribution and package manager: https://www.anaconda.com/products/individual.Once you have python installed, in most cases it will be sufficient to simplyexecute the following command at a terminal:$ pip install specutils astropy matplotlib jupyterOr if you are using anaconda:$ conda create -n mos-unconf -c astropy specutils astropy matplotlib jupyter$ conda activate mos-unconfIf you are more comfortable using a graphical interface, you can use Anaconda Navigator - you can create a new environment in the "Environment" section (call it "mos-unconf") and make sure the "astropy", "matplotlib", "jupyter", and "specutils" packages are checked.  If you don't see one of these you might need to add the "conda-forge" channel in the "channels" button.Optionally, if you want to try out the specviz tool (which we may talkabout in a later part of the session), you will also need to do:$ pip install jdavizAlthough if you have trouble with this step you might find it easier tojust watch along with the demo anyway!Unconference session 1: Spectral analysis with Astropy and specutils

For this unconference session (same session on Tuesday and Thursday) you will need a Python environment set up that is capable of running Jupyter notebooks with the astropy and specutils packages.
If you are new to Python, you may want to look here for some resources on how to install and learn the basics of Python.
Depending on your preferences and system choices, you may find the install instructions
there sufficient, but note that many scientists find it easier to use the Anaconda
python distribution and package manager: https://www.anaconda.com/products/individual.
Once you have python installed, in most cases it will be sufficient to simply
execute the following command at a terminal:

$ pip install specutils astropy matplotlib jupyter

Or if you are using anaconda:

$ conda create -n mos-unconf -c astropy specutils astropy matplotlib jupyter
$ conda activate mos-unconf

If you are more comfortable using a graphical interface, you can use Anaconda Navigator - you can create a new environment in the "Environment" section (call it "mos-unconf") and make sure the "astropy", "matplotlib", "jupyter", and "specutils" packages are checked.  If you don't see one of these you might need to add the "conda-forge" channel in the "channels" button.

Optionally, if you want to try out the specviz tool (which we may talk
about in a later part of the session), you will also need to do:

$ pip install jdaviz

Although if you have trouble with this step you might find it easier to
just watch along with the demo anyway!

