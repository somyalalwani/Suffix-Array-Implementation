# Data Structures & Algorithms for Problem Solving

## Language Used : C/C++


**PROBLEM 1: Implementation of suffix array**

**AIM:** Implement a Suffix Array that is capable of performing following operations on Strings in a most efficient way.

1. Given a string S print its minimum lexicographic rotation. **O(nlogn)**
2. Given an integer K, print the length of the longest substring that appears in the text at least K times.If no such substring exist, print -1. **O(nlogn)**
3. Given a strings S determine its longest substring that is also a palindrome. In the case of multiple solutions, print the lexicographically smallest palindrome.  **O(nlogn)**

### EXAMPLE:

**Input String: S = “dcabca”**

1. All possible rotation are “dcabca” , “cabcad” , “abcadc” , “bcadca” , “cadcab” ,  “adcabc”.
    Among all lexicographically minimum is “abcadc”.

2. If K=2 than since “ca” is a substring that appears twice and its length is 2, so the answer is 2

3. Since only length 1 substring are palindromic, and among them “a” is lexicographically smallest, hence answer is “a”.


**INPUT FORMAT: You will be given a large string S (length <= 10 ^5 ). Print the corresponding output for each case Q1a, Q1b and Q1c.**

**Constraints:**

- 1 <= String length <= 10^
- String consist of either Lower/Upper Case Alphabet and Numeric digits.
