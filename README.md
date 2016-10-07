Scientific Software Development in Python (AIMS Rwanda, 2016)
=============================================================
([Vincent Delecroix](http://www.labri.fr/perso/vdelecro/), LaBRI, Bordeaux, France)

This github repository contains material used to teach Python
at AIMS Rwanda in fall 2016. You can also find complementary information on
[AIMS Rwanda website](https://sites.google.com/a/aims.ac.rw/academic/scientific-software-development-in-python).

At the bottom of this page you can find a list of references and some tips
for the jupyter notebook.

Week 1: learning Python
-----------------------

To download a document right click on a link and chose "Save link as".

- [Jupyter worksheet 1](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet1.ipynb) basic Python and plotting
- The second worksheet has been split into two parts
    - [Jupyter worksheet 2.1](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet2.1.ipynb) lists and for loops
    - [Jupyter worksheet 2.2](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet2.2.ipynb) conditionals
    - (you can still access the [Old Jupyter worksheet 2](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet2.ipynb))

You can also download [this demo about Fibonacci numbers](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/fibonacci.ipynb) 

Week 2: application to mathematics
----------------------------------

- [Jupyter worksheet 3 (assignment)](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet3-assignment.ipynb) functions. This worksheet is the subject of the first assignment that has to be sent before monday 9pm. To submit your assignment go to the Jupyter menu and download the worksheet in ipynb format ("File -> Download as -> Notebook (.ipynb)"). Then send this file by mail to the tutors. Do not forget to write your name in the worksheet! You are free to ask as many questions as you want to me or the tutors.
    - [correction of the workshet 3 (pdf format)](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet3-corrected.pdf)
    - [additional remarks (pdf format)](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/assignment/remarks_assignment1.pdf).
- [Jupyter worksheet 4](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet4.ipynb) probability.
    - [correction part 1](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet4-1.pdf): correction of the parts "Plotting discrete probability measures" and "Plotting continuous probability measure".
    - [correction part 2](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet4-2.pdf): correction of the parts "Sampling"
- [Jupyter worksheet 5](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet5.ipynb): file input and output.

Starting from thursday and up to the end of the course, there will be a quick questions/answers each morning (10min time).
A sheet of paper will be distributed to each of you with a list of commands. You will have to write down what would be
the output of these commands when run in a Jupyter Notebook. You have to answer without using a computer of course. The material of
the two tests of week 2 are contained in worksheet 1, worksheet 2.1 and workheet 2.2.

The assignment (to be submitted before saturday 11:59:59pm) consists in programming in a Jupyter worksheet:
- a function `digits(n, b)` that returns the list of digits of `n` in base `b`
- a function `prime_range(n)` that returns the list of the prime numbers smaller than `n`
- a function `is_prime(n)` that returns `True` if `n` is prime and `False` otherwise
- a function `gcd(x, y)` that computes the greatest common divisor of `x` and `y`
- solving various problems from [Project Euler](https://projecteuler.net/) with at least:
   - all of the problems: [1](https://projecteuler.net/problem=1), [2](https://projecteuler.net/problem=2), [3](https://projecteuler.net/problem=3)
   - one problem among: [46](https://projecteuler.net/problem=46), [12](https://projecteuler.net/problem=12), [21](https://projecteuler.net/problem=21), [23](https://projecteuler.net/problem=23), [7](https://projecteuler.net/problem=7), [27](https://projecteuler.net/problem=27), [10](https://projecteuler.net/problem=10), [35](https://projecteuler.net/problem=35), [37](https://projecteuler.net/problem=37), [47](https://projecteuler.net/problem=47), [25](https://projecteuler.net/problem=25)
   - one problem among: [28](https://projecteuler.net/problem=28), [46](https://projecteuler.net/problem=46), [9](https://projecteuler.net/problem=9), [39](https://projecteuler.net/problem=39), [14](https://projecteuler.net/problem=14)
   - one problem among: [20](https://projecteuler.net/problem=20), [13](https://projecteuler.net/problem=13), [30](https://projecteuler.net/problem=30), [16](https://projecteuler.net/problem=16)
   - one problem among: [22](https://projecteuler.net/problem=22), [11](https://projecteuler.net/problem=11), [8](https://projecteuler.net/problem=8), [18](https://projecteuler.net/problem=18)
   - the problem [15](https://projecteuler.net/problem=15)

A solution for the arithmetic function can be found [here in pdf format](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/assignment/assignment2-correction.pdf).

You can also download [this demo about timings of the is\_prime function](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/timings.ipynb) 

Week 3: math and programming project
------------------------------------

The program will be confirmed. In each course, there will be 1h dedicated to
learning a new Python technique and 1h for your research project (see below).

New Python techniques to be learned:

- recursion (end of worksheet 3)
- [Jupyter worksheet 6](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet6.ipynb): slicing
- [Jupyter exercises on for loops](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/worksheets/worksheet-exercises-for-loop.ipynb): exercises on for loops

For the assignment you will have research projects in group. Each group will be
made of 3 or 4 students (the constitution will be given on friday evening of
week 2). During the week-end, each group will have to chose three subjects by
order of preference and submit their choices to the tutors before sunday 7pm.
The final decision of project allocation will be made for monday morning.

- [groups](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/assignment/groups_week3.pdf)
- [subjects](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/assignment/subjects_week3.pdf)
- [presentation planning](https://raw.githubusercontent.com/videlec/aims-python-rwanda-2016/master/assignment/planning_friday.pdf)


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
