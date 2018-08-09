# The Problem #

## Description ## 
Write a function that takes two parameters, a string and an integer. 
The function will return another string that is similar to the input string, but with certain characters removed. 

It's going to remove characters from consecutive runs of the same character, where the length of the run is greater than the input parameter.

## given / when / then ## 
**given** a string containing a sequence of characters  
**when** I am provided with a number representing the maximum number of consecutive duplicate characters within the string
**then** I will return a substring of the original string where consecutive runs of the same character are limited to the maximum number specified


## Examples ##
```
"aaab", 2 => "aab"
"aabb", 1 => "ab"
"aabbaa", 1 => "aba"
```

