---
title: "Today I Learned (2025-03-26)"
datePublished: Wed Mar 26 2025 02:56:18 GMT+0000 (Coordinated Universal Time)
cuid: cm8pc24qo000009l71uzn4xjo
slug: today-i-learned-2025-03-26
tags: python, english, leetcode, til

---

## \[LeetCode\]

### \[[**26\. Remove Duplicates from Sorted Array**](https://leetcode.com/problems/remove-duplicates-from-sorted-array/)**\]**

* Question Understanding
    
    * You need to work on the original array and modify it in-place.
        
    * You need to remove duplicates.
        
    * You need to return `k`, the number of unique elements.
        
    * **Constraints**
        
        * `nums` is sorted in non-decreasing order
            
        * `nums` not empty
            

```python
class Solution:
    def removeDuplicates(self, nums: List[int]) -> int:
        wr_idx = 1
        for idx in range(1, len(nums)):
            if nums[idx] != nums[idx - 1]:
                nums[wr_idx] = nums[idx]
                wr_idx += 1
        return wr_idx
```

* Time & Space Complexity
    
    * Time: O(n)
        
    * Space: O(1) — in-place modification
        

## \[English\]

### \[Word\]

* **hence**
    
    * **Cause & Result)** that is the reason or explanation for = therefore
        
    * **Time Flow)** from this time = starting now, or after a particular time
        
    * **KR) (원인과 결과)** 그래서, 그렇기때문에, 그러므로 / **(시간형)** 지금으로부터, 이후로
        
* **assert**
    
    * **Claiming something is true)** to say that something is certainly true
        
    * **Power behavior)** to do something to show that you have power
        
    * **In programming)** to test if a condition is true — if not, it raises an error
        
    * **KR)** **(주장)** 강하게 주장하다, 단언하다, **(권한행사)** 권한/권력/영향력을 행사하다, 자신의 존재를 드러내다. **(프로그래밍)** 조건이 참인지 확인하고, 거짓이면 오류를 발생시킴
        

### \[Sentence\]

* **You need to work original array, modify in-place way.**
    
    * work original array → work on the original array
        
        * "Work” is intransitive verb, so it needs to be used with “on”.
            
    * array, modify → array and modify
        
        * Do not connect two independent sentences with just a comma.
            
    * modify in-place way → modify it in-place.
        
        * Do not keep stacking nouns together unnatrually.
            
        * “in-place” is adverb. It describes the method of modification.
            
* **You need to return** `k`**, the unique elements number.**