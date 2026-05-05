# LeetCode Problems

## 1. Two Sum
**Description:** Given an array of integers, return indices of the two numbers such that they add up to a specific target.

**Approach:**
- Use a hashmap to store the difference between the target and each number.
- Check if the number exists in the hashmap.

**Complexity Analysis:**
- Time complexity: O(n)
- Space complexity: O(n)

**Example:**
```plaintext
Input: nums = [2,7,11,15], target = 9
Output: [0, 1]
```

**Algorithm Walkthrough:**
1. Initialize an empty hashmap.
2. Loop through the array and calculate the expected number for each element.
3. If the expected number is in the hashmap, return the indices.

---

## 2. Assign Cookies
**Description:** Assume you have `g` children with cookies of different sizes. Each child can be assigned at most one cookie. Find the maximum number of children you can satisfy.

**Approach:**
- Sort both arrays (children and cookies).
- Iterate through both and assign cookies greedily.

**Complexity Analysis:**
- Time complexity: O(g log g + s log s)
- Space complexity: O(1)

**Example:**
```plaintext
Input: g = [1,2,3], s = [1,1]
Output: 1
```

**Algorithm Walkthrough:**
1. Sort the children and cookies arrays.
2. Use two pointers to iterate through both arrays, attempting to satisfy as many children as possible.

---

## 3. Move Zeroes
**Description:** Given an array, move all zeros to the end without changing the order of non-zero elements.

**Approach:**
- Use two pointers to swap elements when a zero is found.

**Complexity Analysis:**
- Time complexity: O(n)
- Space complexity: O(1)

**Example:**
```plaintext
Input: nums = [0,1,0,3,12]
Output: [1,3,12,0,0]
```

**Algorithm Walkthrough:**
1. Iterate through the array, using one pointer to find non-zero elements.
2. Swap them with the positions of zero elements.

---

## 4. Palindrome Number
**Description:** Determine whether an integer is a palindrome. An integer is a palindrome when it reads the same backward as forward.

**Approach:**
- Convert the integer to a string and check if it reads the same forward and backward.

**Complexity Analysis:**
- Time complexity: O(n)
- Space complexity: O(1)

**Example:**
```plaintext
Input: x = 121
Output: true
```

**Algorithm Walkthrough:**
1. Convert the integer to a string.
2. Compare the string with its reverse to determine if it's a palindrome.



** Author**

arunchary
