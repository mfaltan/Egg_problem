# Egg problem
Solution of problem Two eggs and 100 floor building

Suppose that there is a building with 100 floors. 
You are given 2 identical eggs. 
The most interesting property of the eggs is that every egg has it’s own “threshold” floor. 
Let’s call that floor N. What this means is that the egg will not break when dropped from any floor below floor N, but the egg will definitely break from any floor above floor N, including floor N itself.

 *  First solution is brute force
 *  My solution is binary search (starting in middle, test, on result of test go middle + some value or middle - some value)

