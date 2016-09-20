Scientific Software Development in Python (AIMS Rwanda lectures 2016)
=====================================================================
([Vincent Delecroix](http://www.labri.fr/perso/vdelecro/), LaBRI, Bordeaux, France)

These are notes, exercises and worksheets that are used during the teaching of Python
at AIMS Rwanda in fall 2016. You can also find complementary information on
[AIMS Rwanda website](https://sites.google.com/a/aims.ac.rw/academic/scientific-software-development-in-python).

Week 1
------

The program of the week consists in 4 worksheets and an assignment. To download
the documents right click on each link below and chose "Sage link as".

- [Jupyter worksheet 1](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet1.ipynb) basic Python and plotting ([view it online (read-only version)](http://nbviewer.jupyter.org/github/videlec/aims-python-rwanda-2016/blob/master/worksheets/worksheet1.ipynb))
- The second worksheet has been split into two parts
    - [Jupyter worksheet 2.1](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet2.1.ipynb) lists and for loops ([view it online](http://nbviewer.jupyter.org/github/videlec/aims-python-rwanda-2016/blob/master/worksheets/worksheet2.1.ipynb))
    - [Jupyter worksheet 2.2](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet2.2.ipynb) conditionals ([view it online](http://nbviewer.jupyter.org/github/videlec/aims-python-rwanda-2016/blob/master/worksheets/worksheet2.2.ipynb))
  (you can still access the [Old Jupyter worksheet 2](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet2.ipynb))
- [Jupyter worksheet 3](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet3.ipynb) functions ([view it online](http://nbviewer.jupyter.org/github/videlec/aims-python-rwanda-2016/blob/master/worksheets/worksheet3.ipynb))

The subject of the assignment is [arith.pdf](https://github.com/videlec/aims-python-rwanda-2016/raw/master/assignment/arith.pdf)
and you can use the following [template worksheet](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/assignment/arith.ipynb). To submit your assignment go to the Jupyter menu and download the
worksheet in ipynb format ("File -> Download as -> Notebook (.ipynb)"). Then
send this file by mail to the tutors. Do not forget to include your name
on the worksheet!

Week 2 (subject to changes)
---------------------------

- monday: (worksheet 4 "arrays and matrices" and worksheet 5 "random generation")
   - remarks on assignment of week 1
   - new Python builtins: `enumerate`, `zip`, `min`, `max`, `sum`, `sorted`
   - array and matrices with numpy/scipy
   - slicing (list, arrays, matrices)
   - making and analyzing samples (law of large number, central limit theorem, ...)
- tuesday (worksheet 6 "input/output and data analysis")
   - file input/output
   - string manipulations and formatting
   - csv, json and xml formats
   - data analysis (statistics)
- wednesday (worksheet 7 "more Python, more algorithms")
   - new Python datatypes: `set`, `tuples`, `frozenset`, `dict`
   - more iterators with `itertools`
   - combinatorics and discrete probabilities
- thursday:
   - "Python cheat sheet"
   - [git](https://git-scm.com/book/en) cloning (? to confirm ?)
   - Python scripts and modules
   - documentation and doctests
   - IPython
   - start of assignment

The subject of the assignment will probably be about problems from [Project Euler](https://projecteuler.net)

Week 3 (subject to changes)
---------------------------

- Python classes
- more statistics (tests and p-values)
- random generation (and properties) of combinatorial objects
- solving ODE and PDE with scipy 

The subject of the assignment are some projects to be realized in groups. To submit
your assignment you will need to push your changes to the git server at AIMS Rwanda (subjects and
instructions to come).

References
----------

Beyond the material available in this repository, you might want to consult:

- [Python 3 documentation](https://docs.python.org/3/): contains a tutorial for Python3 as well as the description of all modules of the standard library
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

3. (for the Jupyter on AIMS computers) in order to see the images produced by
   matplotlib.pyplot inside the browser you need to execute once these two lines
   in a code cell

    import matplotlib
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
