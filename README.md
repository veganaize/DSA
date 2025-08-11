* [Problems/](Problems/)
  - [CTCI.md](Problems/CTCI.md)
  - [DP PATTERNS.md](Problems/DP_PATTERNS.md)
  - [PARETO.md](Problems/PARETO.md)


[Data Structure](https://en.wikipedia.org/wiki/Data_structure) & 
[Algorithm](https://en.wikipedia.org/wiki/Algorithm) Notes
================


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
  - Insertion / Deletion: `Amortized O(1)` | `O(n)` time


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
  - [Boosters](https://drive.google.com/file/d/16C9gz9waj0A9XmVlaOgbDgEQZkATuRNY/preview)
  - [Question Landscape](https://drive.google.com/file/d/1Bu4cHzbY0uZg2TcPjdvy_hhNF7_HOlZJ/preview)
  - [Catalog of DSA Topics](https://bctci.co/topics-image)
  - [Interview Checklist](https://drive.google.com/file/d/1Q9Uc-1UdvyaqbkTGSaZ3-aVEYX5ImZMl/preview)
  - [Post Mortem Exmple Log](https://drive.google.com/file/d/1LG-aUqjEbTVddkjeuCHMtROlm9BMIhDb/preview)
  - [Post-Mortem](https://docs.google.com/spreadsheets/d/1phKTGfnQtuElTQ4BQSBfa1H5QO1-Ip9j8NRVZkR_FTk)
  - [\[Python\] Interview Cheat Sheet](https://docs.google.com/document/d/1LtXh1oew6pZ9D4s5mw_33jzA2UwBfnv9jWh1bkSRTCc)
  - [Nine Free Chapters](https://drive.google.com/drive/folders/1AdUu4jh6DGwmCxfgnDQEMWWyo6_whPHJ)
  - [Set & Map Implementations](https://docs.google.com/document/d/e/2PACX-1vRWfoJWWNp49cIZxDCZPkvQ2o8WOImKWLkimF7lhnsY-CmT1kREPP0duEKmnXyf-rPG1B0QGsxmcITy/pub)
  - [Monotonic Stacks & Queues](https://docs.google.com/document/d/e/2PACX-1vT29T3Tfvdkd-IGI2HCIgtAbWwYZ76pHCSlTkuyHiCvRqU5BD6S6_MJWcZl0Rgw1C2uhMykFFkNLHDu/pub)
  - [Union-Find](https://docs.google.com/document/d/e/2PACX-1vRwYsi-g1CKIDpbfhB5Xm9Lp1-OL1ooVI5i3kR4yFMX2ME14ODGZva9dabMM8Pe-Tduj4on8V8TGviZ/pub)
  - [All problems, solutions & test cases](https://bctci.co/all-problems)
