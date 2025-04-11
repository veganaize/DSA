DSA Notes
=========


:art: Design
------------

* Design code before writing:
  - To have a plan & avoid getting stuck.
  - To collaborate on approach for solution.
  - Because jumping straight into coding, on large projects, is a bad idea.


[Dynamic Arrays](https://en.wikipedia.org/wiki/Dynamic_array)
----------------

* Random access of any element (via index).
* Occasionally resized (copies elements; typically faster than dynamic allocations required by linked list).
* Typical "array" type for scripting languages (typically with static array(s) utilized internally).
* Complexities:
  - Lookup by index: `O(1)` time
  - Lookup by value: `O(n)` time
  - Insertion / Deletion: `O(n)` time


[Linked Lists](https://en.wikipedia.org/wiki/Linked_list)
--------------

* Each element dynamically allocated (typically slower than occasional copies required by dynamic array).
* Complexities:
  - Lookup: `O(n)` time
  - Insertion / Deletion: `O(1)` time


[Stacks](https://en.wikipedia.org/wiki/Stack_(abstract_data_type))
--------

* Features:
  - last in, first out (LIFO)
* Implementation:
  - As a dynamic array
  - As a linked list
* Operations:
  - `push` (aka. `append`)
  - `pop`
* Useful for tasks divided into sub-tasks:
  - Tracking tokens while parsing


[Strings](https://en.wikipedia.org/wiki/String_(computer_science)) & Static 
[Arrays](https://en.wikipedia.org/wiki/Array_(data_structure))
--------

* An array is a contiguous sequence of the same type.
* A string is a (typically read-only) array of characters.
* A memory buffer is (pre)allocated for all elements.
* Cannot be resized at runtime; must re-allocate buffer & copy.


<img src="https://user-images.githubusercontent.com/7102064/160022421-ed9425eb-6a6b-4849-a090-5a27542b60c3.png" width="24px"
/> Videos
---------

* BINARY TREES
  - [Binary tree traversal - breadth-first and depth-first strategies](https://youtu.be/9RHO6jU--GU) - mycodeschool
* HEAPS
  - [Heaps in 3 minutes — Intro](https://youtu.be/0wPlzMU-k00) - Michael Sambol


:books: Books
-------------

* [Programming Interviews Exposed](https://web.archive.org/web/20200218054807/http://www.piexposed.com/)
* [Cracking the Coding Interview](https://www.crackingthecodinginterview.com/)
* [Beyond Cracking the Coding Interview](https://bctci.co)
