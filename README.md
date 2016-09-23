Scientific Software Development in Python (AIMS Rwanda, 2016)
=============================================================
([Vincent Delecroix](http://www.labri.fr/perso/vdelecro/), LaBRI, Bordeaux, France)

This github repository contains material used to teach Python
at AIMS Rwanda in fall 2016. You can also find complementary information on
[AIMS Rwanda website](https://sites.google.com/a/aims.ac.rw/academic/scientific-software-development-in-python).

At the bottom of this page you can find a list of references and some tips
for the jupyter notebook.

Week 1
------

To download a document right click on a link and chose "Save link as".

- [Jupyter worksheet 1](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet1.ipynb) basic Python and plotting
- The second worksheet has been split into two parts
    - [Jupyter worksheet 2.1](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet2.1.ipynb) lists and for loops
    - [Jupyter worksheet 2.2](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet2.2.ipynb) conditionals
    - (you can still access the [Old Jupyter worksheet 2](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet2.ipynb))
- [Jupyter worksheet 3](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet3.ipynb) functions


References
----------

Beyond the material available in this repository, you might want to consult:

- The "Help" menu available in each Jupyter worksheet
- [Python 3 documentation](https://docs.python.org/3/): contains among others a tutorial for Python3 and a complete description the standard Python library
- [Scipy lectures](http://www.scipy-lectures.org/): Python tutorial in 3 sections starting from learning Python up to using advanced features of scipy and pandas
- [Scipy website](http://scipy.org/): information about the SciPY stack. Contains links to other resources.
- [Project Euler](https://projecteuler.net/): more than 500 exercises that have to be solved with a computer
- [IPython tutorial](https://ipython.org/ipython-doc/3/interactive/tutorial.html): tutorial about IPython

Tips and tricks
---------------

1. To start the Jupyter notebook:

   - open a terminal
   - run the command `jupyter notebook`

2. To stop the Jupyter notebook

   - for each open worksheet, go to the menu and do "File -> Save and Checkpoint"
     (in order to save your work) and then "File -> Close and Halt"
   - go in the terminal where you launched the notebook and press `Ctrl-C` right
     after you need to press `y` and `Enter` (you have 5 seconds to do this
     second step)

3. (for AIMS computers) in order to see the `matplotlib` images
   embedded in the browser you need to execute the following line in a code cell

       %matplotlib inline

Copyright notice
----------------
Copyright (C) 2016 Vincent Delecroix <vincent.delecroix@u-bordeaux.fr>

This work is licensed under a Creative Commons Attribution-NonCommercial 4.0
International License (CC BY-NC-SA 4.0). This license allows you to reuse this
material at your convenience but:
 - it can not be used as part of a commercial activity
 - you need to specify the original author and sources

You can either read the
[Creative Commons Deed](https://creativecommons.org/licenses/by-nc-sa/4.0/)
(Summary) or the [Legal Code](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode)
(Full licence).
