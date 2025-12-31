# The Problem

## Description 
Write a function that takes two parameters, a string and an integer. 

When called, the function will remove characters from consecutive runs of the same character, 
where the length of the run is greater than the input parameter.

### Acceptance criteria 
**Given** a string containing a sequence of characters  

**When** I am provided with a number representing the maximum number of consecutive duplicate characters within the string

**Then** I will return a substring of the original string where consecutive runs of the same character are limited to the maximum number specified

## Examples ##
```
"aaab", 2 => "aab"
"aabb", 1 => "ab"
"aabbaa", 1 => "aba"
```

