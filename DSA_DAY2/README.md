# DSA_Challenge_DAY2
#DrGViswanathan Teaches Day Challenge
Welcome to my coding challenge repository! This repo contains my solutions for the #DrGViswanathan Teaches day challenge, where I tackled fundamental programming problems to strengthen my problem-solving skills.
🎯 Challenge Overview
This challenge focuses on implementing clean, efficient solutions to classic coding problems. Each solution demonstrates different algorithmic approaches and data structure usage covering arrays, strings, linked lists, and binary trees.
📝 Problems Solved
1. FizzBuzz (LeetCode #412)
Difficulty: Easy
Topic: Array, String, Math
Given an integer n, return a string array where for each integer i in the range [1, n]:

"FizzBuzz" if i is divisible by both 3 and 5
"Fizz" if i is divisible by 3
"Buzz" if i is divisible by 5
str(i) otherwise

Solution Approach: Iterate through numbers 1 to n
Use modulo operator to check divisibility
Handle conditions in order of precedence (FizzBuzz first)


Key Concepts: Modulo arithmetic for divisibility checks
Conditional logic with proper precedence
Time complexity: O(n), Space complexity: O(n)

2. Group Anagrams (LeetCode #49)
Difficulty: Medium
Topic: Array, Hash Table, String, Sorting
Given an array of strings strs, group the anagrams together.
Solution Approach:Use character frequency counting as key
Create array of size 26 for each string to count letters
Convert frequency array to tuple for hashing
Group strings with same frequency pattern


Key Concepts:Character frequency analysis
Hash table with custom keys
Time complexity: O(n * m), Space complexity: O(n * m)

3. Remove Linked List Elements (LeetCode #203)
Difficulty: Easy
Topic: Linked List, Recursion
Given the head of a linked list and an integer val, remove all nodes with val.
Solution Approach:Handle removal of head nodes first
Traverse list and skip nodes with target value
Update pointers to maintain list integrity


Key Concepts:Linked list traversal and manipulation
Pointer management
Time complexity: O(n), Space complexity: O(1)

4. Same Tree (LeetCode #100)
Difficulty: Easy
Topic: Binary Tree, Depth-First Search, Recursion
Given the roots of two binary trees p and q, check if they are the same.
Solution Approach:Recursive comparison of tree nodes
Base cases: both null (true), one null (false)
Compare values and recursively check subtrees


Key Concepts:Binary tree traversal
Recursive problem solving
Time complexity: O(min(m,n)), Space complexity: O(min(m,n))

🚀 Getting Started
