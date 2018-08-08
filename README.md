# The Problem #
Write a function that takes two parameters, a string and an integer. 
The function will return another string that is similar to the input string, but with certain characters removed. 

It's going to remove characters from consecutive runs of the same character, where the length of the run is greater than the input parameter.

**Examples**
```
"aaab", 2 => "aab"
"aabb", 1 => "ab"
"aabbaa", 1 => "aba"
```
