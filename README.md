# DSAG-Project – Data Structures and Algorithms Assignment
Data Structures and Algorithms(DSAG) introduced recursion and data structures which were helpful in solving problems using a programming language. Topics covered include stacks, queues, linked lists and trees. Searching techniques and sorting algorithms will also be covered.

### Project Overview
This repository contains my work for the Data Structures and Algorithms (DSAG) module assignment.
The project involves completing coding tasks, applying fundamental data structure and algorithm concepts, and demonstrating practical implementation using Python in Jupyter Notebook.

DSAG Project required us to answer questions designed to showcase our understanding of Data Structures and Algorithms.

### Questions Breakdown
##### Question 1 – Python Quick Start (5 marks)

- Complete the LinkedIn Learning course Python Quick Start.

- Requirements:
    - Complete the e-learning course.
    
    - Obtain and upload the certificate to LinkedIn.
    
    - Provide screenshot proof.

##### Question 2 – Algorithms & Data Structures Problems

- Implemented multiple problems testing knowledge of:
  - Arrays & Lists
  - Sorting & Searching
  - Stacks & Queues
  - Recursion
  - Binary Trees & Graphs

Each solution includes Python code, explanations, and test outputs.

Example snippet:

def binary_search(arr, target):
    low, high = 0, len(arr) - 1
    while low <= high:
        mid = (low + high) // 2
        if arr[mid] == target:
            return mid
        elif arr[mid] < target:
            low = mid + 1
        else:
            high = mid - 1
    return -1

##### Question 3 – Case Study / Application

- Applied DSAG concepts to a real-world style problem.
- Designed an efficient algorithm with time and space complexity analysis.
- Compared brute-force vs optimized approaches.

**Testing & Outputs**

- All implemented code blocks include sample runs and expected outputs.
- Screenshots and inline results in the notebook demonstrate correctness.

**Key Learnings**

- Reinforced understanding of fundamental algorithms and data structures.
- Gained practice in optimizing solutions.
- Strengthened ability to write clean, documented Python code.
