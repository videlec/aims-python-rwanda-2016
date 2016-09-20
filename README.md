Scientific Software Development in Python (AIMS Rwanda lectures 2016)
=====================================================================
([Vincent Delecroix](http://www.labri.fr/perso/vdelecro/), LaBRI, Bordeaux, France)

These are notes, exercises and worksheets that are used during the teaching of Python
at AIMS Rwanda in fall 2016. You can also find complementary information on
[AIMS Rwanda website](https://sites.google.com/a/aims.ac.rw/academic/scientific-software-development-in-python).

Week 1: learning the Python language
------------------------------------

Each worksheet will occupy a whole seance. You first need to download the worksheet on your computer and then access it through the jupyter notebook.

- [Jupyter worksheet 1](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet1.ipynb) basic Python and plotting ([view it online (read-only version)](http://nbviewer.jupyter.org/github/videlec/aims-python-rwanda-2016/blob/master/worksheets/worksheet1.ipynb))
- [Old Jupyter worksheet 2](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet2.ipynb) This worksheet is now splitted into two parts:
    - [Jupyter worksheet 2.1](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet2.1.ipynb) lists and for loops ([view it online](http://nbviewer.jupyter.org/github/videlec/aims-python-rwanda-2016/blob/master/worksheets/worksheet2.1.ipynb))
    - [Jupyter worksheet 2.2](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet2.2.ipynb) conditionals ([view it online](http://nbviewer.jupyter.org/github/videlec/aims-python-rwanda-2016/blob/master/worksheets/worksheet2.2.ipynb))
- [Jupyter worksheet 3](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet3.ipynb) functions ([view it online](http://nbviewer.jupyter.org/github/videlec/aims-python-rwanda-2016/blob/master/worksheets/worksheet3.ipynb))

The subject of the assignment is [arith.pdf](https://github.com/videlec/aims-python-rwanda-2016/raw/master/assignment/arith.pdf). You
should program all functions inside a single Jupyter worksheet. To submit your assignment,
go to the Jupyter menu and download the worksheet in ipynb format ("File ->
Download as -> Notebook (.ipynb)"). Then send this file by mail to the tutors.

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

- PYthon classes
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
