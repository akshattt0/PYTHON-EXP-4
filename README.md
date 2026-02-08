
# Experiment 4: Python Tuples

---

## Title

Tuples in Python: Creation, Access, and Operations

---

## Aim

To study the tuple data structure in Python and perform operations such as creation, indexing, slicing, and the use of built-in tuple functions.

---

## Objectives

- Understand the concept of tuples in Python  
- Learn the properties and advantages of tuples  
- Perform indexing and slicing operations on tuples  
- Use built-in functions available for tuples  
- Understand the immutable nature of tuples  

---

## Theory

### Introduction to Tuples

A tuple is a collection data type in Python used to store multiple values in a single variable. Tuples are similar to lists but are immutable, meaning their elements cannot be changed after creation. Tuples are created using parentheses, with elements separated by commas.

**Example:**  
`(10, 20, 30)`

---

### Characteristics of Tuples

- Ordered collection of elements  
- Indexed data structure  
- Immutable after creation  
- Allows duplicate values  
- Can store different data types  

---

### Uses of Tuples

Tuples are used where data integrity is important. They are faster than lists and are commonly used to store fixed data such as coordinates, days of the week, and database records.

---

### Creating Tuples

Tuples can be created in the following ways:
- Using parentheses  
- Without parentheses (tuple packing)  
- Using the `tuple()` constructor  

A single-element tuple must include a trailing comma.

**Example:**  
`(10,)`

---

### Indexing in Tuples

Tuple elements are accessed using index values starting from `0`. Both positive and negative indexing are supported in Python.

---

### Slicing in Tuples

Slicing is used to extract a portion of a tuple.

**Syntax:**  
`tuple_name[start : end : step]`

Where:
- `start` indicates the beginning index  
- `end` indicates the stopping index (excluded)  
- `step` specifies the interval between elements  

---

### Immutability of Tuples

Once a tuple is created:
- Elements cannot be added  
- Elements cannot be removed  
- Elements cannot be modified  

Any modification attempt results in an error.

---

### Built-in Tuple Functions

- `len()` – Returns the total number of elements  
- `max()` – Returns the largest element  
- `min()` – Returns the smallest element  
- `sum()` – Returns the sum of numeric elements  
- `count()` – Returns the occurrence count of an element  
- `index()` – Returns the index position of an element  

---

### Difference Between List and Tuple

| List | Tuple |
|------|-------|
| Mutable | Immutable |
| Uses `[ ]` | Uses `( )` |
| Slower | Faster |
| Dynamic | Fixed size |

---

## Conclusion

Thus, Python tuples and their operations were studied successfully. This experiment provided an understanding of tuple creation, indexing, slicing, immutability, and the use of built-in functions, highlighting the importance of tuples in storing fixed data.

