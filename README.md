# LC-Python1
## Array data structure、704. Binary Search、27. Remove Element 
May 09, 2023 

This is my first day to begin the data structure and algorithms study. \
In this blog, I will record the daily challenges I solve on leetcode, the difficulties I meet in the study process, and the total time taken to finish the daily tasks. \
This daily challenge project is guided by Carl, a very famous programmer. Hopefully after two months of hard work, I will gain a deeper understanding of the data structures and algorithms. And use Python to generate more efficient solutions for business problems. 

## Array data structure
[Reading in github](https://github.com/youngyangyang04/leetcode-master)

## 704. Binary Search
[Video in bilibili](https://www.bilibili.com/video/BV1fA4y1o715/?vd_source=63f26efad0d35bcbb0de794512ac21f3) \
For a sorted array with no repeated items, binary search can be used. \
To get the middle index of an array, middle = left + (right - left) // 2 is better than middle = (left + right) // 2. \
while (left <= right), the next possible loop would be middle - 1 rather than middle.

#### 35. Search Insert Position
Use the examples given to test the loop, and decide what result to return when the item is not found in the list. Here the left is finally returned.

#### 34. Find First and Last Position of Element in Sorted Array
Firstly, use binary search to check if the target is in the array.\
Then, use **two pointers**: a left and a right one to determine the window.

<img src="https://github.com/gyjbb/Leetcode-Python1/blob/main/Screen%20Shot%202023-05-11%20at%2012.29.36%20AM.png" width="600" height="400">


#### 69. Sqrt(x)
Here the right pointer used x//2 rather than x. Time will be saved.\
Used if mid > x / mid rather than x < mid**2, So the calculation will not exceed x's constraint. \

<img src="https://github.com/gyjbb/Leetcode-Python1/blob/main/Screen%20Shot%202023-05-11%20at%203.26.48%20PM.png" width="400" height="250">

#### 367.


## 27. Remove Element
[Leetcode link](https://leetcode.com/problems/remove-element/) \
[Reading in github](https://github.com/youngyangyang04/leetcodemaster/blob/master/problems/0027.%E7%A7%BB%E9%99%A4%E5%85%83%E7%B4%A0.md) \
The elements in arrays are linked and can't be directly removed, but can be covered.\
So we can use **two pointers**: a fast index and a slow index, to solve this question.
- fast pointer：find elements for the new array，the new array doesn't contain the target element;
- slow pointer：point to the index of elements in the new array.

<img src="https://github.com/gyjbb/Leetcode-Python1/blob/main/Screen%20Shot%202023-05-10%20at%205.46.43%20PM.png" width="500" height="220">

#### 26.
#### 283.
#### 844.
#### 977.


[*Markdown reference*](https://leetcode.com/discuss/general-discussion/1560831/markdown-reference-for-leetcode-formatting-cheatsheet)
