LeetCode Solutions
This repository contains solutions to various LeetCode problems implemented in Java. Each solution includes an optimized algorithmic approach with detailed explanations.

Problems Solved
1. Two Sum (LeetCode #1)
Difficulty: Easy

Problem Description: Given an array of integers nums and an integer target, return the indices of the two numbers that add up to the target. You may assume each input has exactly one solution, and you cannot use the same element twice.

Approach:

Uses a brute force nested loop approach
Time Complexity: O(n²)
Space Complexity: O(1)
Key Points:

Iterates through each element and checks if another element exists that sums to the target
Returns the indices as a pair
Simple and straightforward approach, suitable for beginners

2. Assign Cookies (LeetCode #455)
Difficulty: Easy

Problem Description: Assume you are an awesome parent and want to distribute cookies to children. You have two arrays: g (greed factors of children) and s (sizes of available cookies). Each child i has a greed factor g[i] and each cookie j has a size s[j]. A child i is content with cookie j if s[j] >= g[i]. The goal is to maximize the number of content children.

Approach:

Uses a two-pointer greedy algorithm after sorting both arrays
Time Complexity: O(n log n + m log m) where n = length of g, m = length of s
Space Complexity: O(1) excluding the sorting space
Key Points:

Sort both arrays in ascending order
Use two pointers to match cookies with children greedily
Assign the smallest sufficient cookie to the least greedy child
Maximizes the number of satisfied children

3. Move Zeroes (LeetCode #283)
Difficulty: Easy

Problem Description: Given an integer array nums, move all zeroes to the end while maintaining the relative order of non-zero elements. You must modify the array in-place and minimize the number of write operations.

Approach:

Uses a two-pointer approach (left and right pointers)
Time Complexity: O(n)
Space Complexity: O(1)
Key Points:

Left pointer tracks the position where the next non-zero element should be placed
Right pointer iterates through all elements
When a non-zero element is found, swap it with the position at the left pointer
Minimizes write operations by only swapping when necessary
Maintains the relative order of non-zero elements
How to Use
Clone the repository
Navigate to the problem folder
Review the solution code and approach
Compile and run: javac solution.java && java Solution

Learning Resources
LeetCode Official
Time and space complexity analysis for each solution
Optimal algorithmic approaches explained


Author
Arunchary04

Last Updated: May 5, 2026
