# Awesome-performance-tools
A curated list tools for kinds of programming languages to analysis system performance.
- [Awesome python performance tools](#Python)
    - [cProfile](#cProfile)
    - [pyinstrument](#pyinstrument)
    - [line_profiler](#line_profiler)
    - [memory_profiler](#memory_profiler)
    - [psutil](#psutil)
    - [py-spy](#py-spy)
    - [runsnakerun](#runsnakerun)
    - [py-Flame](#py-Flame)
    - [vprof](#vprof)
    - [PyCharm Profiler](#PyCharm_Profiler)
    - [SnakeViz](#SnakeViz)
    - [GProf2Dot](#GProf2Dot)
    - [PyShark](#PyShark)
    - [PyPerformance](#PyPerformance)
    - [Pympler](#Pympler)
    - [Yappi](#Yappi)
    - [PySnooper](#PySnooper)
    - 
- [Awesome C/C++ performance tools](#C/C++)
    - [Valgrind](#Valgrind)
    - [Prevent](#Prevent)
    - [Coverity Static Analysis](#Coverity_Static_Analysis)
    - [Purify](#Purify)
    - [Intel VTune](#VTune)


## Python
* [cProfile](https://docs.python.org/3/library/profile.html) - cProfile and profile provide deterministic profiling of Python programs. A profile is a set of statistics that describes how often and for how long various parts of the program executed
* [pyinstrument](https://pyinstrument.readthedocs.io/en/latest) - Pyinstrument is a Python profiler. A profiler is a tool to help you optimize your code - make it faster
* [line_profiler](https://github.com/rkern/line_profiler) - A module for doing line-by-line profiling of functions
* [memory_profiler](https://pypi.org/project/memory-profiler/) - Monitoring memory consumption of a process as well as line-by-line analysis of memory consumption for python programs
* [psutil](https://psutil.readthedocs.io/en/latest/) - A cross-platform library for retrieving information on running processes and system utilization (CPU, memory, disks, network, sensors) 
* [py-spy](https://github.com/benfred/py-spy) - A sampling profiler for Python programs, extremely low overhead: it is written in Rust for speed
* [runsnakerun](https://github.com/venthur/snakerunner) - Snakerunner is a GUI viewer for Python profiling runs. It provides exorability and overall visualization of the call tree and package/module structures
* [py-Flame](https://github.com/uber/pyflame) - Pyflame is a high performance profiling tool that generates flame graphs for Python
* [vprof](https://github.com/nvdv/vprof) - vprof is a Python package providing rich and interactive visualizations for various Python program characteristics such as running time and memory usage
* [PyCharm Profiler](https://www.jetbrains.com/help/pycharm/profiler.html) - A performance profiling tool built into the PyCharm Integrated Development Environment (IDE) 
* [SnakeViz](https://jiffyclub.github.io/snakeviz/) - SnakeViz is a browser based graphical viewer for the output of Python’s cProfile module and an alternative to using the standard library pstats module
* [GProf2Dot](https://github.com/jrfonseca/gprof2dot) - A Python script to convert the output from many profilers into a dot graph
* [PyShark](https://kiminewt.github.io/pyshark/) - Python wrapper for tshark, allowing python packet parsing using wireshark dissectors
* [PyPerformance](https://github.com/python/pyperformance)
* [Pympler](https://pythonhosted.org/Pympler/) - Pympler is a development tool to measure, monitor and analyze the memory behavior of Python objects in a running Python application
* [Yappi](https://github.com/sumerc/yappi) - A tracing profiler that is multithreading, asyncio and gevent aware
* [PySnooper](https://github.com/cool-RR/pysnooper) -  Add one decorator line to the function you're interested in. Got a play-by-play log of your function.



## C/C++
* [Valgrind](https://valgrind.org/) - Tools that can automatically detect many memory management and threading bugs, and profile your programs in detai
* [Prevent](https://www.cs.cmu.edu/~aldrich/courses/654-sp07/tools/cure-coverity-06.pdf) 
* [Coverity Static Analysis](https://devguide.python.org/advanced-tools/coverity/) - [For static code analysis of Open Source projects](https://www.softwaretestinghelp.com/tools/top-40-static-code-analysis-tools/). 
* [Purify](https://www.ibm.com/support/pages/tools-purify) - A useful tool for finding memory management problems and other sources of intermittent problems
* [Intel VTune](https://www.intel.com/content/www/us/en/develop/documentation/vtune-help/top.html) - Intel® VTune™ Profiler optimizes application performance, system performance, and system configuration for HPC, cloud, IoT, media, storage, and more.
