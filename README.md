# blind-2-75
buy and sell stocks
blind 75

part -2 

buy and sell stock 

analysis:

non increasing array - > max profit =0

non decreasing array -> max profit =last - first

random array

we need to keep track of 2 things

min price seen so far, so that it acts as benchmark to track max profit in upcoming days.

max profit seen so far. 

i.e if the current element is least,update min price.

else update max profit based on already seen min price .

time complexity: O(n)

space complexity: O(1) 

https://leetcode.com/problems/best-time-to-buy-and-sell-stock/submissions/1594399866/
