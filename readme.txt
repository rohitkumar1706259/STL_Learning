The Standard Template Library (STL) is a set of C++ template classes to provide common programming data structures and functions such as lists, stacks, arrays, etc. It is a library of container classes, algorithms, and iterators. It is a generalized library and so, its components are parameterized. A working knowledge of template classes is a prerequisite for working with STL.

STL has four components

Algorithms
Containers
Functions
Iterators
Algorithms

The header algorithm defines a collection of functions especially designed to be used on ranges of elements.They act on containers and provide means for various operations for the contents of the containers.

Algorithm
Sorting
Searching
Important STL Algorithms
Useful Array algorithms
Partition Operations
Numeric
valarray class
Containers




Containers or container classes store objects and data. There are in total seven standard “first-class” container classes and three container adaptor classes and only seven header files that provide access to these containers or container adaptors.

Sequence Containers: implement data structures which can be accessed in a sequential manner.
vector
list
deque
arrays
forward_list
Container Adaptors : provide a different interface for sequential containers.
queue
priority_queue
stack
Associative Containers : implement sorted data structures that can be quickly searched (O(log n) complexity).
set
multiset
map
multimap
