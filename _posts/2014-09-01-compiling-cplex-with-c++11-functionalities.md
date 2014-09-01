---
layout: post
title: Compile CPLEX in C++ with C++11 Functionalities
---

CPLEX is a pretty awesome optimization toolbox from IBM, and it is free for academic use. It can be called from C++ (apart from Matlab, Python, etc.), but you may encounter some problems to compile your code.
You will encounter one of them if your code has some C++11 functionalities from the C++ strandard library.

Long story short (I hope to elaborate more soon), CPLEX requires the flag -stdlib=libstdc++, which 'downgrades' the version of the standard library to a version where the C++11 functionalities where not available by default.
This way, your part of the code won't compile.

The good part is that you can still use the C++11 code by including the "Technical Report 1" part of the library, that is, by adding "tr1/" to the files that the compiler does not found and changing "std::" by "std::tr1::" in the functions that are not found.    
