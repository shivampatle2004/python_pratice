# python_pratice
A structured collection of my Python journey, from basic syntax to advanced data projects. Updated daily as I learn."

# 🐍 Python Practice Journey

A structured, comprehensive tracking repository documenting my continuous programming progress. This codebase transitions from basic data type syntax configurations up to robust engineering logic, complex Object-Oriented Programming (OOP), and optimized numerical matrix operations.

---

## 📚 Complete File-Wise Index & Solved Questions

### 📋 1. Lists & Sequences Array Processing
*   **Target Workspace Notebooks:** `list.ipynb`, `list01.ipynb`, `lst.ipynb`, `List_25_easy_to_hard.ipynb`
*   **Solved Questions (20+ Problems):**
    1. Find the maximum and minimum elements in an unsorted array sequence manually.
    2. Reverse a mutable list data structure in-place vs. creating a secondary shallow copy.
    3. Check if a given array list contains any repeating duplicate elements.
    4. Remove duplicate items from a sequence while cleanly preserving original element ordering.
    5. Find the second largest and second smallest integer entries in a single list traversal pass.
    6. Rotate list values left or right by `k` designated index positions.
    7. Generate a complete frequency map of all unique elements found within a list.
    8. Separate even and odd numbers from a mixed data list into distinct arrays.
    9. Merge two separate, pre-sorted lists into a single uniformly sorted master list array.
    10. Flatten a multi-dimensional nested array structure down into a standard flat list array.
    11. Extract all unique sub-lists or item combination subsets from an explicit target group.
    12. Find overlap intersection elements matching across two distinct sequence variables.
    13. Compute progressive cumulative sums inside an array list across sequential indexes.
    14. Check if an array list's ordering pattern is valid ascending or descending.
    15. Shift all zero values to the tail-end of a list while holding non-zero item placement.
    16. Identify a missing consecutive integer within a linear scalar calculation stream.
    17. Isolate the majority element (element showing up in more than `n/2` total indices).
    18. Find item coordinate pairs whose calculated matching sum equals a strict target value `K`.
    19. Fragment a large, monolithic list variable into smaller, uniformly sized sub-chunks.
    20. Process custom multi-dimensional matrix operations including addition, subtraction, and axis transpose operations.
*   **💡 Key Learnings:** Understood dynamic array properties. Appending items scales smoothly, but inserting elements at index `0` incurs an $O(n)$ index shift cost. Used rapid Python slices `[start:stop:step]` to bypass tedious loops.

---

### 🔤 2. String Manipulation & Text Analysis
*   **Target Workspace Notebooks:** `string00.ipynb`, `string01.ipynb`, `string02.ipynb`, `string1_25_basic_to_hard_all_que_.ipynb`
*   **Solved Questions (20+ Problems):**
    1. Reverse a string value without using native `[::-1]` slice processing.
    2. Check if an input word sequence forms a valid palindrome.
    3. Count total vowels, consonants, digits, and special formatting characters inside a string.
    4. Track and count the frequency of each specific character in a string text block.
    5. Detect if two text inputs form valid anagram patterns.
    6. Find the first non-repeated character in an input string sequence.
    7. Find and print the longest word inside a text sentence string.
    8. Capitalize the first letter of every isolated word across an entire text string.
    9. Clean up strings by stripping unnecessary trailing whitespace and removing special punctuation.
    10. Check if a substring exists within a main body of text without using the `in` operator.
    11. Count the occurrences of a target word inside a larger multi-line paragraph.
    12. Validate if an input string is composed strictly of alphanumeric characters.
    13. Replace all instances of a target character with a different character without using `.replace()`.
    14. Compress strings by counting consecutive characters (e.g., `aabcc` becomes `a2b1c2`).
    15. Extract numerical digit segments from mixed-character string content.
    16. Find the longest common prefix across an array of strings.
    17. Check if a string can be turned into a palindrome by removing at most one character.
    18. Convert Roman numeral strings into primitive mathematical integers.
    19. Implement a custom basic string template parser to swap placeholder variables safely.
    20. Check if a string matches a simple pattern containing wildcard expressions.
*   **💡 Key Learnings:** Python strings are immutable. Standard looping string concatenations create brand new allocations every cycle. Bundling lists of characters via `"".join(list)` is vastly more efficient.

---

### 🔄 3. Loops, Conditions & Layout Patterns
*   **Target Workspace Notebooks:** `python_loops_and_if_statements.ipynb`, `advance_loops_and_statement.ipynb`, `pattens.ipynb`, `patten_02.ipynb`
*   **Solved Questions (20+ Problems):**
    1. Print clear numerical sequences (such as numbers from 1 to 100) using foundational `while` and `for` loops.
    2. Check if a number is even, odd, positive, negative, or exactly zero.
    3. Check if a year is a leap year using chained boolean operators.
    4. Generate a sequence of Prime Numbers across a given lower/upper bound block.
    5. Compute the complete Fibonacci Sequence out to a target limit `N`.
    6. Calculate the mathematical factorial of an integer using iterative logic.
    7. Calculate the sum of all digits contained within a single composite integer.
    8. Check if an integer matches the properties of an Armstrong number.
    9. Print visual nested looping structures (Right-angled triangles, full stars pyramids, mirrored diamonds, and numeric grids).
    10. Build an interactive calculator loop that processes inputs until a dedicated exit command is typed.
    11. Check if a target integer value is a perfect square without utilizing math libraries.
    12. Find the Greatest Common Divisor (GCD) of two integers using the Euclidean algorithm.
    13. Find the Least Common Multiple (LCM) of two user input integer variables.
    14. Convert binary numbers to decimals and vice-versa using conditional loop transformations.
    15. Solve the classic FizzBuzz game challenge out to an arbitrary numeric depth.
    16. Sum all prime numbers falling below a target integer limit.
    17. Find the digital root (repeated addition of digits until a single digit remains).
    18. Build a nested conditional statement matrix validating multi-tiered tax calculations.
    19. Parse and evaluate nested loop structures to count coordinate combinations within bounds.
    20. Implement a sequential sequence tracking pattern checking for continuous input increments.
*   **💡 Key Learnings:** Mastered conditional branching flow rules. Identified how loop control indicators (`break` and `continue`) alter routine processing, and leveraged Python's unique `for...else` closure structure.

---

### 🎯 4. Sets (Unique Datasets & Collection Math)
*   **Target Workspace Notebooks:** `set00.ipynb`, `set_easy_to_hard.ipynb`
*   **Solved Questions (20+ Problems):**
    1. Initialize empty sets vs. set literals and add elements dynamically using `.add()`.
    2. Remove items from a set safely using `.discard()` to avoid KeyErrors vs. using `.remove()`.
    3. Convert a raw list with heavy duplicates into a unique set to clean the dataset.
    4. Check if a specific element exists within a set using high-speed membership testing.
    5. Iterate through un-ordered set elements using a basic `for` loop tracker.
    6. Compute the **Union** of multiple sets to combine all unique records.
    7. Find the **Intersection** of sets to isolate matching items common to both lists.
    8. Calculate the **Difference** between two sets to find items unique to the first collection.
    9. Compute the **Symmetric Difference** to extract items that are in either set, but not both.
    10. Check if a set is a completely isolated **Disjoint Set** from another collection.
    11. Verify **Subset** and **Superset** conditions between multiple evaluation groups.
    12. Remove all elements from an active set at once using the `.clear()` method.
    13. Pop a random, arbitrary item out of a set using `.pop()` and analyze the mutation.
    14. Update an existing set by merging items from another collection using `.update()`.
    15. Use `.intersection_update()` to mutate a set, keeping only elements found in both inputs.
    16. Use frozen sets (`frozenset`) to build an entirely immutable collection.
    17. Find the maximum, minimum, and total sum of values stored inside a numeric set.
    18. Generate a mathematical power set (all possible sub-combinations) from a base set.
    19. Extract unique words from a long multi-line text paragraph using tokenized sets.
    20. Solve real-world inventory tracking problems to spot items missing from a target catalog.
*   **💡 Key Learnings:** Sets rely on underlying Hash Table properties. This grants optimal, constant-time $O(1)$ calculations for adding, removing, and testing containment, outperforming linear list lookup rates ($O(n)$).

---

### 🔒 5. Tuples (Immutable Record Tracking)
*   **Target Workspace Notebooks:** `tupal00.ipynb`, `tuple_easy_to_hard.ipynb`, `tuple_easy_to_hard02.ipynb`
*   **Solved Questions (20+ Problems):**
    1. Instantiate single-element tuples (understanding the trailing comma rule) and multi-element records.
    2. Access tuple data using positive tracking indexes and reverse negative tracking indices.
    3. Trigger and handle a `TypeError` intentionally to prove that tuple data is strictly immutable.
    4. Unpack tuple elements cleanly into isolated standalone variables.
    5. Use the wildcard splat operator (`*`) to group leftover unpacked items into a sub-list.


    -

### 🗃️ 6. Dictionaries & Key-Value Maps
*   **Target Workspace Notebooks:** `dict00.ipynb`, `Dictionary_easy_to_hard.ipynb`
*   **Solved Questions (20+ Problems):**
    1. Merge two independent dictionary elements into a single record dataset.
    2. Sort dictionary records based on values instead of keys (ascending/descending).
    3. Map two separate lists into a key-value dictionary format.
    4. Group a list of objects by a shared property using a dictionary.
    5. Handle nested dictionary maps to extract multi-level data fields safely using `.get()`.
    6. Invert a dictionary by swapping keys and values dynamically.
    7. Count frequency occurrences of characters inside a word using a hash map structure.
    8. Create an automatic fallback dictionary record structure via `.setdefault()`.
    9. Remove target key properties safely from a dictionary without causing errors.
    10. Check if a key exists inside a multi-level record using targeted validation parameters.
    11. Update dictionary records dynamically using the `.update()` method.
    12. Create a shallow copy of a dictionary and explain reference differences in nested components.
    13. Remove and return a key-value pair from a dictionary using `.pop()` and `.popitem()`.
    14. Build a dictionary from scratch using dict comprehensions based on conditional logic filter setups.
    15. Generate a dictionary with default values using `dict.fromkeys()`.
    16. Find the key associated with the maximum or minimum value in a dictionary dataset.
    17. Find the intersecting keys common between two distinct dictionary profiles.
    18. Combine two dictionaries by adding values for keys that appear in both collections.
    19. Convert a complex nested JSON-style data tree completely into a series of structured key updates.
    20. Iterate over keys, values, and key-value tuple pairs utilizing `.keys()`, `.values()`, and `.items()`.
*   **💡 Key Learnings:** Gained deeper insight into Hash Map lookups. Learned how dictionary objects achieve efficient $O(1)$ computational read/write speeds, enabling scalable storage and fast retrieval.

---

### ⚙️ 7. Functional Programming Scopes
*   **Target Workspace Notebooks:** `function00.ipynb`
*   **Solved Questions:** Implemented custom multi-argument routines using variable arguments (`*args`, `**kwargs`), recursive operations for deep factorials, and quick structural data transforms using lambda routines combined with `map()` and `filter()`.
*   **💡 Key Learnings:** Solidified understanding of the **LEGB scoping paradigm** (Local, Enclosing, Global, and Built-in variable resolution layers).

---

### 🏛️ 8. Object-Oriented Programming (OOP)
*   **Target Workspace Notebooks:** `OOPS.ipynb`, `oops_.ipynb`
*   **Solved Questions:** Engineered class objects modeling banking portals, customer balance structures, and vehicle inheritance hierarchies. Applied core concepts like custom properties, constructor initializations, and functional overrides.
*   **💡 Key Learnings:** Mastered data access isolation using private attributes (`__variable`), clean polymorphic overrides, and customized behaviors via built-in magic/dunder methods (`__init__`, `__str__`, `__repr__`).

---

### 📊 9. Vectorized Data Processing with NumPy
*   **Target Workspace Notebooks:** `Numpy.ipynb`
*   **Solved Questions:** Vectorized raw arrays, processed linear systems, completed multi-dimensional matrix cuts, and set up dynamic broad broadcasting scripts across incompatible shapes.
*   **💡 Key Learnings:** Swapped standard Python loops for continuous, contiguous C-array matrix lookups via NumPy, reducing processing times from $O(n)$ down to high-speed vectorized executions.

---

## 📈 General Engineering Habits Picked Up
*   **Complexity Management:** Prioritized optimizing code logic, transforming slow nested loops $O(n^2)$ into fast $O(1)$ hash map references.
*   **Defensive Design:** Integrated early edge-case checks (for conditions like empty arrays or null values) to prevent application failures.


