# Day25projectinpython
Count words in a sentence in Python program
Problem statement − We are given a string we need to count the number of words in the string

Approach 1 − Using split() function
Split function breaks the string into a list iterable with space as a delimiter. if the split() function is used without specifying the delimiter space is allocated as a default delimiter.

Approach 2 − Using regex module
Here findall() function is used to count the number of words in the sentence available in a regex module.

Approach 3 − Using sum()+ strip()+ split() function
Here we first check all the words in the given sentence and add them using the sum() function.
