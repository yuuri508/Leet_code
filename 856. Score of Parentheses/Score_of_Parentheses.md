## 856. Score of Parentheses
## Problem Statement

Given a balanced parentheses string `s`, return the score of the string.

The score of a balanced parentheses string is defined according to the following rules:

- `()` has a score of `1`.
- If `A` and `B` are balanced parentheses strings, then `AB` has a score of `A + B`.
- If `A` is a balanced parentheses string, then `(A)` has a score of `2 * A`.

### Examples

**Example 1:**

```text
Input: s = "()"
Output: 1

Input: s = "(())"
Output: 2

Input: s = "()()"
Output: 2

Input: s = "(()(()))"
Output: 6

