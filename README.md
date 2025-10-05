# Python List Operations

This project demonstrates fundamental list operations in Python, including creation, modification, and manipulation of lists.

## Overview

The `list_operations.py` script showcases common list methods and operations that are essential for Python programming. It provides a step-by-step demonstration of how to work with lists effectively.

## Features

The script performs the following operations:

- **List Creation**: Initialize an empty list
- **Appending**: Add elements to the end of the list
- **Insertion**: Insert elements at specific positions
- **Extension**: Combine lists using the extend method
- **Removal**: Remove elements from the list
- **Sorting**: Sort list elements in ascending order
- **Indexing**: Find the position of specific values

## Requirements

- Python 3.x

## Installation

No additional packages are required. Simply ensure you have Python installed on your system.

## Usage

1. Navigate to the project directory:
   ```bash
   cd week-2-python
   ```

2. Run the script:
   ```bash
   python list_operations.py
   ```

## Expected Output

```
After appending elements: [10, 20, 30, 40]
After inserting 15 at position 2: [10, 15, 20, 30, 40]
After extending with [50, 60, 70]: [10, 15, 20, 30, 40, 50, 60, 70]
After removing last element: [10, 15, 20, 30, 40, 50, 60]
After sorting in ascending order: [10, 15, 20, 30, 40, 50, 60]
Index of value 30: 3
```

## Code Explanation

### 1. Creating an Empty List
```python
my_list = []
```
Initializes an empty list that will be used for subsequent operations.

### 2. Appending Elements
```python
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)
```
Adds elements to the end of the list one by one.

### 3. Inserting at a Specific Position
```python
my_list.insert(1, 15)
```
Inserts the value `15` at index `1` (the second position), shifting existing elements to the right.

### 4. Extending the List
```python
my_list.extend([50, 60, 70])
```
Adds multiple elements from another list to the end of `my_list`.

### 5. Removing the Last Element
```python
my_list.pop()
```
Removes and returns the last element from the list.

### 6. Sorting the List
```python
my_list.sort()
```
Sorts the list in ascending order (in-place).

### 7. Finding an Index
```python
index_of_30 = my_list.index(30)
```
Returns the index of the first occurrence of the value `30` in the list.

## Learning Objectives

This project helps you understand:

- How to create and initialize lists in Python
- Different methods for adding elements to lists (`append()`, `insert()`, `extend()`)
- How to remove elements from lists (`pop()`)
- How to sort lists in-place (`sort()`)
- How to search for elements and find their positions (`index()`)
- The difference between modifying a list in-place vs. creating a new list

## Additional Resources

- [Python Official Documentation - Lists](https://docs.python.org/3/tutorial/datastructures.html#more-on-lists)
- [Python List Methods](https://docs.python.org/3/tutorial/datastructures.html)

## License

This project is open source and available for educational purposes.
