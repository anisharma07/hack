# Odd Palindromes

## Description

Given a string of lowercase alphabets A of size N and an integer array B of size Q.

Return an array of integers C of size Q where C[i] = the number of palindromes centered at index B[i].

**NOTE**: Only odd length palindromes have a center.

## Input

The first argument given is the string A.
The second argument given is the integer array B.

## Output

Return an array of integers C of size Q where C[i] = the number of palindromes centered at index B[i].

## Constraints

- 1 <= N <= 10^5
- 1 <= Q <= 10^5
- 1 <= B[i] <= N

## Examples

### Example 1:

**Input 1:**

- A = "aaa"
- B = [1, 2, 3]

**Output 1:**

- C = [1, 2, 1]

**Explanation 1:**

- For B[i] = 1, { "a" }
- For B[i] = 2, { "aaa", "a" }
- For B[i] = 3, { "a" }

### Example 2:

**Input 2:**

- A = "ababab"
- B = [1, 2, 3, 4, 5, 6, 7]

**Output 2:**

- C = [1, 1, 2, 4, 2, 1, 1]

## Function Signature

```cpp
vector<int> Solution::solve(string A, vector<int> &B) {
    // Implementation here
}
```
