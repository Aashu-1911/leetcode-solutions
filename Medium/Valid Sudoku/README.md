# Valid Sudoku

**Difficulty:** Medium
**Language:** Unknown

## Topics
- Array
- Hash Table
- Matrix

## Performance
- Runtime: N/A
- Memory: N/A

## Approach
try to check whole row using set 
unordered_set<char>seen;
used to check if that char already exist or not 

same check for column just change the index i to j in loops 

then at last check for 3x3 matrix make use of row and col index for each 3x3 matrix and increment by 3 
then for each row and col sem check for row and col use same loops like before and done 

## Complexity
- **Time Complexity:** *O(N)*
- **Space Complexity:** *O(1)*

## Problem Link
https://leetcode.com/problems/valid-sudoku/

---
*Synced automatically by CodeSync.*
