# pythonPractice

This repository contains code I wrote to solve practice problems with Python.

## Description of practice problems

The `udacity` folder contains problems that I solved for the "Data Structures & Algorithms" Nanodegree program (November 2022).<br>
Any code provided by the class instructor (helper code, solutions) is commented as such at the top of the cell, and also the class instructor provided the test code.  Otherwise the code is mine.

### 1.  `udacity/dataStructuresAndAlgorithms/dataStructures/arraysAndLinkedLists`

**1.1. Strings.ipynb**<br>
Practice with strings. Reverse a string, anagrams, reverse the words in a sentence, & Hamming distance.

**1.2. Implementing and traversing a linked list.ipynb**

**1.3. Linked Lists Basics.ipynb**<br>
Singly vs Doubly linked lists. Write a class for Linked List, not just a class for Node. 

**1.4. Linked List Practice.ipynb**<br>
More practice implementing a linked list, with extra methods:<br>
- Append data to the tail of the list and prepend to the head
- Search the linked list for a value and return the node
- Remove a node
- Pop, which means to return the first node's value and delete the node from the list
- Insert data at some position in the list
- Return the size (length) of the linked list

**1.5. Reverse a Linked List.ipynb**<br>
List is only singly linked.

**1.6. Detecting Loops.ipynb**<br>
Detect if a loop exists in a linked list.

**1.7. Flattening a nested linked list.ipynb**<br>
Suppose you have a linked list where the value of each node is a sorted linked list (i.e., it is a nested list). Your task is to flatten this nested list—that is, to combine all nested lists into a single (sorted) linked list.

**1.8. Create a sorted linked list Exercise.ipynb**<br>
- Given a stream of random integers, create a linked list that is always sorted from ascending order (lowest to highest).  That is, for a class `SortedLinkedList`, write an `append` method that always keeps the list in ascending sorted order
- Given an array of integers, use this linked list to sort them and return a sorted array.  That is, create a new instance of `SortedLinkedList`, then turn the resulting list back into a (sorted) array.

**1.9. Add-One.ipynb**<br>
You are given a non-negative number in the form of list elements. For example, the number `123` would be provided as `arr = [1, 2, 3]`. Add one to the number and return the output in the form of a new list.

**1.10. Duplicate-Number.ipynb**<br>
You have been given an array of length `n`. The array contains integers from `0` to `n - 2`. Each number in the array is present exactly once except for one number which is present twice. Find and return this duplicate number present in the array.

**1.11. Max-Sum-Subarray.ipynb**<br>
You have been given an array containg numbers. Find and return the largest sum in a contiguous subarray within the input array.

**1.12. Pascal's-Triangle.ipynb**<br>
Find and return the `n`th row of Pascal's triangle in the form a list. `n` is 0-based.  For example, if `n = 4`, then `output = [1, 4, 6, 4, 1]`.

**1.13. Even-after-Odd.ipynb**<br>
Given a linked list with integer data, arrange the elements in such a manner that all nodes with even numbers are placed after odd numbers. Do not create any new nodes and avoid using any other data structure. The relative order of even and odd elements must not change.  Example:
- `linked list = 1 2 3 4 5 6`
- `output = 1 3 5 2 4 6`

**1.14. Skip-i-delete-j.ipynb**<br>
You are given the head of a linked list and two integers, i and j. You have to retain the first i nodes and then delete the next j nodes. Continue doing so until the end of the linked list.  Example:
- `linked-list = 1 2 3 4 5 6 7 8 9 10 11 12`
- `i = 2`
- `j = 3`
- `Output = 1 2 6 7 11 12`

**1.15. Swap-nodes.ipynb**<br>
Given a linked list, swap the two nodes present at position `i` and `j`, assuming `0 <= i <= j`. The positions are based on 0-based indexing.  Note: You have to swap the nodes and not just the values.  Do not create a new list.  Example:
- `linked_list = 3 4 5 2 6 1 9`
- `positions = 2 5`
- `output = 3 4 1 2 6 5 9`

### 2.  `udacity/dataStructuresAndAlgorithms/dataStructures/stacksAndQueues`

**2.1. Implement-a-stack-using-an-array.ipynb**<br>
Basic stack class with a python list (array) like a Pringle's can. 

**2.2. Implement-a-stack-using-a-linked-list.ipynb**<br>
Basic stack class with a linked list (wrote a Node class). 

**2.3. Build-a-stack.ipynb**<br>
Basic stack class with a python list.

**2.4. Balanced-parentheses-exercise.ipynb**<br>
Using stacks to make sure the parentheses are balanced in mathematical expressions such as:  ((32+8)∗(5/2))/(2+6)

**2.5. Reverse-Polish-notation.ipynb**<br>
Given a postfix expression as input, evaluate in Reverse Polish notation and return the output.  I didn't get this one 100% of the way.

**2.6. Reverse-a-stack.ipynb**<br>
If your stack initially has 1, 2, 3, 4 (4 at the top and 1 at the bottom), after reversing the order must be 4, 3, 2, 1 (4 at the bottom and 1 at the top).

**2.7. Minimum-bracket-reversals.ipynb**<br>
Given an input string consisting of only { and }, figure out the minimum number of reversals required to make the brackets balanced.

**2.8. Build-a-queue-using-an-array.ipynb**<br>
Practice implementing a queue, using arrays.

**2.9. Build-a-queue-using-a-linked-list.ipynb**<br>
This is more efficient than using an array to implement a queue.

**2.10. Build-a-queue-using-a-stack.ipynb**<br>
Basically you need two stacks, to keep track of items from the perspective of the front of the queue (to be dequeued or popped off the stack) and the back of the queue (enqueued, or pushed onto the tail of the queue)

**2.11. Build-a-queue-using-high-level-python.ipynb**<br>
Queues are super easy using high level Python (list).

**2.12. Reverse-a-queue.ipynb**<br>
Reverse a queue in place.

### 3.  `udacity/dataStructuresAndAlgorithms/dataStructures/recursion`

**3.1. Recursion-introduction.ipynb**<br>  
Calculate the sum of all integers from 1 to 𝑛 using recursion. 

**3.2. Factorial-using-recursion.ipynb**<br>
Use recursion to write a function that will take a number and return the factorial of that number.

**3.3 Reversing-a-string.ipynb**<br>
Use recursion to reverse a string.

**3.4 Checking-Palindrome.ipynb**<br>
Use recursion to check if a string is a palindrome.

**3.5 Add-One-Again.ipynb**<br>
Use recursion to add one to a digit that is represented by an array.

**3.6 Permutation.ipynb**<br>
Use recursion to find all permutations of a list.

**3.7 String-Permutations.ipynb**<br>
Use recursion to find all permutations of a string (try to not reuse method for lists, from above).

**3.8 Keypad-Combinations.ipynb**<br>
Find all possible words you can spell with an integer on a touch-tone phone keypad.

**3.9 Deep-Reverse.ipynb**<br>
Deep reverse a list, meaning also reverse any inner lists.  Pretty easy...

**3.10 Call-stack.ipynb**<br>
Example of watching a recursive function using http://pythontutor.com/

**3.11 Tower-of-Hanoi.ipynb**<br>
TODO:  solve the puzzle with recursion. (I started this, but didn't get it.)

**3.12 Return-Codes.ipynb**<br>
TODO:  solve the puzzle with recursion (inspecting an integer one element at a time). (I started this, but didn't get it.)

**3.13 Return-Subsets.ipynb**<br>
Use recursion to find the power set of a list.

**3.14 Staircase.ipynb**<br>
TODO:  solve the puzzle with recursion, how many ways to go up a staircase, up to 3 steps at a time. (I started this, but didn't get it.)

**3.15 Last-index-recursion.ipynb**<br>
Use recursion to find the last index in a list of a given element.

### 4.  `udacity/dataStructuresAndAlgorithms/dataStructures/trees`

**4.1 01_create_a_binary_tree.ipynb**<br>  

**4.2 02_traverse_a_tree_dfs.ipynb**<br>
Use recursion to traverse a tree depth first, using pre-order, in-order, and post-order.

**4.3 03_traverse_a_tree_bfs.ipynb**<br>
Write a function to traverse a tree breadth first.

**4.4 04_binary_search_tree.ipynb**<br>
Write functions to insert and search a binary search tree.

**4.5 Diameter_of_a_Binary_Tree.ipynb**<br>
Write a function to compute the diameter of a binary tree (max number of edges between two nodes, going up and down the tree)

**4.6 Path-from-root-to-node.ipynb**<br>
Write a function to find the path from the root node of a binary tree (not a BST) to a given value of another node.
TODO:  I solved it with a slightly hacky answer, and didn't understand the instructor's solution.
UPDATE: I solved it a different way with a "stack", and also Steve explained the instructor's solution to me.

### 5.  `udacity/dataStructuresAndAlgorithms/dataStructures/mapsAndHashing`

**5.1 Introduction-to-Maps.ipynb**<br>

**5.2 HashMap.ipynb**<br>
Lots of practice in creating a hash table class.  Create a hash function for strings, and add compression.  Add a rehash function.  Build the hash table as an array of LinkedLists.  (Each LinkedList, one at each index in the hash table, represents the "bucket" of nodes whose key hash to that value).

**5.3 Caching.ipynb**<br>
An example of writing a recursive function while also making use of caching common (repeated) computation results.

**5.4 String-Key-Hash-Table.ipynb**<br>
More practice with writing hash functions and using a hash table.

**5.5 Pair-Sum-to-target.ipynb**<br>
More practice.  Instructor uses a dict while my solution just used a python list.

**5.6 Longest-Consecutive-Subsequence.ipynb**<br>
Find the longest consecutive subsequence of numbers in a given input list, and keep your solution O(n) by using a dict.



