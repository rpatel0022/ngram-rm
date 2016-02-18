# ngram-rm
Given a string and bag of overlapping n-grams, remove all n-grams from the string.

Overview
========
This Algorithm and implementation is used to remove potentially variable length
 and overlapping n-grams from a string. This algorithm is optimal for running 
large amounts of strings on the same bag of n-grams. This is because the n-grams
are put through a preprocessing step in order to make the string comparison and 
removal much faster.

There are two different implementations of this project. One in python and one
in C. This is to have both a quicker prototyping script or code for some 
ML applications that use python. The other is in C in order to take full 
advantage of its speed and memory control.

Both the C and Python versions will be created as libraries, and will have
individual tests in the `tests/` directory, which will test and benchmark a 
large dataset. Full documentation for building and using this libraries 
can be found in the `doc/` directory.

There is also specific documentation that describes the algorithm itself in detail
in the `doc/` directory.


Python
======
TODO: Basic python documentation

C
=
TODO: Basic C documentation
