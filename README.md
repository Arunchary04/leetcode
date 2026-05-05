# LeetCode Problems

## Problem 1: Two Sum
### Description:
Given an array of integers, return indices of the two numbers such that they add up to a specific target.

### Approach:
1. Create a hash map to store the indices of the numbers.
2. Iterate through the array and check if the complement (target - current number) exists in the map.
3. If it exists, return the indices. Otherwise, store the current number's index in the map.

### Example:
- Input: nums = [2, 7, 11, 15], target = 9
- Output: [0, 1] (because nums[0] + nums[1] == 9)


## Problem 2: Assign Cookies
### Description:
Assume you have `g` children with `g` different greed factors. You are given `s` cookies, each with a certain size. Your goal is to assign each cookie to a child greedily (i.e., maximize the number of happy children).

### Approach:
1. Sort both the children and cookie sizes.
2. Use two pointers to traverse the children and cookies arrays.
3. If the current cookie can satisfy the current child's greed, move to the next child. Always move to the next cookie.

### Example:
- Input: g = [1, 2, 3], s = [1, 1]
- Output: 1 (only one child can be satisfied)


## Problem 3: Move Zeroes
### Description:
Given an integer array, move all 0's to the end of it while maintaining the relative order of the non-zero elements.

### Approach:
1. Use a pointer to track the position of the last non-zero element found.
2. Iterate over the array, and for each non-zero element, swap it with the element at the last non-zero position.
3. After processing the entire array, all zeroes will be moved to the end.

### Example:
- Input: nums = [0, 1, 0, 3, 12]
- Output: [1, 3, 12, 0, 0]