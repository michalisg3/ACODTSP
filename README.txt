﻿ACODTSP
=======

A C++ implementation of the Dynamic Benchmark Framework published in the following paper:

M. Mavrovouniotis, S. Yang, M. Van, C. Li, and M. Polycarpou. Ant colony optimization algorithms for dynamic 
optimization: A case study of the dynamic travelling salesperson problem. ``IEEE Computational Intelligence 
Magazine'', 15(1), pp. 52-63, Feb. 2019

This is an open source library that provides the implementation of existing ant colony optimization
(ACO) algorithms proposed for the dynamic travelling salesman problem (DTSP). The source code is 
provided for research purposes to provide an easy and efficient platform for everyone to compare 
and evaluate their algorithms. The ACODTSP library is implemented in the C++ language and provides 
the implementation of two DTSP variations: 1)DTSP with weight channges, and 2) DTSP with node
changes.

Written by Michalis Mavrovouniotis, 2019. 


CONTENTS
=======
Implementation of ACO frameworks and variations
ACO.cpp
ACO.hpp

The code of the ACO algorithms is based on the ACOTSP implementation 
of Thomas Stuetzle: ACO algorithms for the TSP, version 1.03 
www.aco-metaheuristic.org/aco-code


Implementation of the dynamic benchmark framework
DTSP.cpp 
DTSP.hpp

Implementation of performance and behaviour measurements
stats.cpp
stats.hpp

The main method of the implementation
main.cpp


Contact
=======
Michalis Mavrovouniotis
m.mavrovouniotis(at)hotmail.com
Please let me know for any bugs/improvements/additions.
