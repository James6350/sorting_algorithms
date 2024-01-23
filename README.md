# Sorting Algorithms Project

## Overview
This project focuses on implementing and understanding various sorting algorithms. Each group of two students is required to pair program for at least the mandatory part. The learning objectives include knowledge of sorting algorithms, Big O notation, time complexity evaluation, selection of the best sorting algorithm, and understanding stable sorting algorithms.

## Requirements
### General
- **Allowed Editors:** vi, vim, emacs
- **Compilation:** Ubuntu 20.04 LTS, using gcc with options -Wall -Werror -Wextra -pedantic -std=gnu89
- **File Endings:** All files should end with a new line
- **README.md:** A mandatory file at the root of the folder, explaining the project
- **Coding Style:** Use the Betty style, checked with betty-style.pl and betty-doc.pl
- **Global Variables:** Not allowed
- **Functions:** No more than 5 functions per file
- **Standard Library:** Unless specified otherwise, refrain from using standard library functions like printf, puts, etc.
- **Header File:** Include prototypes of all functions in a header file named sort.h
- **Include Guard:** All header files should have include guards
- **List/Array Size:** A list/array does not need to be sorted if its size is less than 2.

### GitHub
- **Repository:** One project repository per group. Avoid cloning/forking a repository with the same name before the second deadline to prevent a 0% score.

## Data Structure and Functions
### Functions
#### `print_array`
```c
void print_array(const int *array, size_t size);
```
Prints an array of integers.

#### `print_list`
```c
void print_list(const listint_t *list);
```
Prints a doubly linked list of integers.

### Data Structure
```c
/**
 * struct listint_s - Doubly linked list node
 *
 * @n: Integer stored in the node
 * @prev: Pointer to the previous element of the list
 * @next: Pointer to the next element of the list
 */
typedef struct listint_s
{
    const int n;
    struct listint_s *prev;
    struct listint_s *next;
} listint_t;
```

## Sorting Algorithms
Implement at least four different sorting algorithms. Use the provided print_array and print_list functions for testing.

## Big O Notation
Understand and explain:
- O(1)
- O(n)
- O(n!)
- O(n^2)
- O(log(n))
- O(n log(n))
- O(n + k)

## Readme Content
Your README.md file should cover the following sections:
1. **Overview:** Briefly explain the purpose and goals of the project.
2. **Requirements:** List the general and GitHub requirements.
3. **Data Structure and Functions:** Provide information on the given functions and data structure.
4. **Sorting Algorithms:** Mention the implemented sorting algorithms and how to test them.
5. **Big O Notation:** Explain the different notations and their significance.
6. **Tests:** Offer a tip on testing sorting algorithms with large sets of random integers.

## Note
Ensure that your project adheres to the specified guidelines to avoid any issues during evaluation.
