# Leetcode-Python1
## 代码随想录算法训练营第一天|数组理论基础、704. 二分查找、27. 移除元素 
May 09, 2023 

This is my first day to begin the data structure and algorithums study on leetcode. \
In this blog, I will record the daily challenges I solve on leetcode, the difficuties I meet in the study process, and the total time taken to finish the daily tasks. \
This daily challenge project is guided by Carl, a very famous programmer. Hopefully after two months of hard work, I will gain a deeper understanding of the data structures and algorithums. And use Python to generate more efficient solutions for business problems. 

## Array data structure
[Reading in github](https://github.com/youngyangyang04/leetcode-master)

## 704. Binary Search
[Video in bilibili](https://www.bilibili.com/video/BV1fA4y1o715/?vd_source=63f26efad0d35bcbb0de794512ac21f3) \
When see a sorted array with no repeated items, could use binary search. \
To get the meddle index of an array, middle = left + (right - left) // 2 is better than middle = (left + right) // 2. \
while (left <= right), the next possible loop would be middle - 1 rather than middle.

#### 35. Search Insert Position
Use the real case to run the loop, and define what to return if the item is not found in the list. Here the left is finally returned!

#### 34. Find First and Last Position of Element in Sorted Array

#### 69.
#### 367.


## 27. Remove Element
[Leetcode link](https://leetcode.com/problems/remove-element/) \
[Reading in github](https://github.com/youngyangyang04/leetcodemaster/blob/master/problems/0027.%E7%A7%BB%E9%99%A4%E5%85%83%E7%B4%A0.md) \
Because the elements in arrays are linked and can't be directly removed. Can only be covered.\
So we can use **double pointers** a fast index and a slow index, and two for loops to solve this question.
- 快指针：寻找新数组的元素 ，新数组就是不含有目标元素的数组
- 慢指针：指向更新 新数组下标的位置

<img src="https://github.com/gyjbb/Leetcode-Python1/blob/main/Screen%20Shot%202023-05-10%20at%205.46.43%20PM.png" width="500" height="250">

#### 26.
#### 283.
#### 844.
#### 977.


[*Markdown reference*](https://leetcode.com/discuss/general-discussion/1560831/markdown-reference-for-leetcode-formatting-cheatsheet)
