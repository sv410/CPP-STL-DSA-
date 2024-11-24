# CPP-STL-DSA-
https://www.hackerearth.com/practice/notes/standard-template-library/
Data Structures
Data structures are used to store and organize data. An array is an example of a data structure, which allows multiple elements to be stored in a single variable.

C++ includes many other data structures as well, each is used to handle data in different ways.

These are part of the C++ STL, which stands for The Standard Template Library.

C++ STL
STL is a library that consist of different data structures and algorithms to effectively store and manipulate data.

If we say that data structures store data, we can say that algorithms are used to solve different problems, often by searching through and manipulating those data structures.

Using the right data structure and algorithm makes your program run faster, especially when working with lots of data.

The most common data structures are:

Data Structure	Description
Vector	Stores elements like an array but can dynamically change in size. Adding and removing of elements are usually done at the end. Elements can be accessed by index.
List	Stores elements sequentially, where each element is connected to the next. Adding and removing of elements can be done at both ends. Not accessible by index.
Stack	Stores elements in a specific order, called LIFO (Last In, First Out), where elements can only be added and removed from the top. Not accessible by index.
Queue	Stores elements in a specific order, called FIFO (First In, First Out), where elements are added at the end and removed from the front. Not accessible by index.
Deque	Stores elements in a double-ended queue, where elements can be added and removed from both ends. Elements can be accessed by index.
Set	Stores unique elements. Not accessible by index.
Map	Stores elements in "key/value" pairs. Accessible by keys (not by index).
Which one to use depends on your specific needs. One thing they all have in common is that you must include the appropriate header file to use them:

Example
// Include the vector library
#include <vector>

// Include the list library
#include <list>

// Include the set library
#include <set>

// Include the map library
#include <map>

// Include the stack library
#include <stack>

// Include the queue library
#include <queue>
Here is an example of using vectors, after we have included the <vector> library:

Example
// Create a vector called cars that will store strings
vector<string> cars = {"Volvo", "BMW", "Ford", "Mazda"};

// Print vector elements
for (string car : cars) {
  cout << car << "\n";
}
The next chapters will explain how each data structure works and how to use them.

Key Concepts of the STL
The key components of the STL consist of containers, iterators, and algorithms, and the relationship betweem them:

Containers are data structures that provides a way to store data, like vectors, lists, etc.
Iterators are objects used to access elements of a data structure.
Algorithms include functions, like sort() and find(), that perform operations on data structures through iterators.
In Computer Science, data structures and algorithms go hand in hand. A data structure is not worth much if you cannot search through it or manipulate it efficiently using algorithms, and algorithms are not worth much without a data structure to work on.

In the following chapters, you will see how everything is connected.

