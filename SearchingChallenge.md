Searching Challenge

Have the function SearchingChallenge(str) take the str parameter being passed and find the longest substring that contains k unique characters, where k will be the first character from the string. The substring will start from the second position in the string because the first character will be the integer k. For example: if str is "2aabbacbaa" there are several substrings that all contain 2 unique characters, namely: ["aabba", "ac", "cb", "ba"], but your program should return "aabba" because it is the longest substring. If there are multiple longest substrings, then return the first substring encountered with the longest length. k will range from 1 to 6.
Once your function is working, take the final output string and concatenate it with your ChallengeToken, and then replace every third character with an X. 

Your ChallengeToken: qfl1hbyd7c
Examples

Input: "3aabacbebebe" 
Output: cbebebe 
Final Output: cbXbeXeqXl1XbyX7c
