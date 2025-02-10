# Daily-Leetcode-problem3
PROBLEM

You are given a string s.
Your task is to remove all digits by doing this operation repeatedly:
Delete the first digit and the closest non-digit character to its left.
Return the resulting string after removing all digits.

Intuition

Solution using stack

Approach

Use a stack to process characters one by one.
If the character is a digit, remove the closest non-digit character from the stack.
If the character is not a digit, push it onto the stack.
Construct the resulting string by popping elements from the stack and reversing it.
This approach ensures that we remove all digits according to the given rules efficiently.

Complexity

Time complexity:
O(n)

Space complexity:
O(n)

 
