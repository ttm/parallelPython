# Parallel python processing experiments

This repository is dedicated to scripts for parallel processing, both by multiple processes and by threads, with focus on SMP on a single computer, proper to i3, i5 and i7, for example.

## Background

Python has the Global Interpreter Lock (GIL) which is used to synchronize threads so that only one thread can execute at a time. Parallelism can be reached by using separate processes, each with its own GIL. However, concurrency on a single interpreter is limited. Cython can be released from GIL using with statement.

## Resources
- An introduction to parallel programming: http://sebastianraschka.com/Articles/2014_multiprocessing_intro.html
- Parallel Python Software: http://www.parallelpython.com/
- Python multiprocessing module: https://docs.python.org/2/library/multiprocessing.html
- Python threading module: https://docs.python.org/2/library/threading.html
- Joblib: https://pythonhosted.org/joblib/
- dispy: Python framework for distributed and parallel computing: http://dispy.sourceforge.net/
- Pypar, a python library that provides efficient and scalable parallelism using the message passing interface (MPI) to handle big data and highly computational problems: https://github.com/daleroberts/pypar
- MPI with Python: http://materials.jeremybejarano.com/MPIwithPython/
- Cython: http://cython.org/

### Background resources

- Python 3: https://docs.python.org/3/ 
- IPython: http://ipython.org/

## Further work
These experimental scripts are aimed at making computation faster for scientific goals, within Python framework. Therefore, another set of experiments should make explicit how to use and what are the benefits of Ctypes, Cython and other means to reach C from Python.

## Contact
IRC \#labmacambira @ Freenode
