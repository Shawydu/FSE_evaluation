### Merge Intervals
Given an array of intervals where intervals[i] = [starti, endi], merge all overlapping intervals, and return an array of the non-overlapping intervals that cover all the intervals in the input. 

Tests:
```
a)
Input: [[1,3],[2,6],[8,10],[15,18]]
Output: [[1,6],[8,10],[15,18]]
b) 
Input: [[1,4],[4,5]]
Output: [[1,5]]
c)
Input: [[0,0], [1,1]]
Output: [[0,0], [1,1]]
```

Constraints:
```
0 <= starti <= endi <= 104
starti is sorted
```

### Move Zeros
Given an integer array nums, move all 0's to the end of it while maintaining the relative order of the non-zero elements.

Tests:
```
a)
Input: nums = [0,1,0,3,12]
Output: [1,3,12,0,0]
b)
Input: nums = [1,2,0,3,0,1,2]
Output: [1.2,3,1,2,0,0]
c)
Input: nums = [0,0,0,1]
Output: [1,0,0,0]
d)
Input: nums = [1,2,1,1]
Output: [1,2,1,1]
e)
Input: nums = [0]
Output: [0]
```

Constraits:
```
1 <= nums.length <= 104
```
