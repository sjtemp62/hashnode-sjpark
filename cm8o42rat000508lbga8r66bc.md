---
title: "Today I Learned (2025-03-25)"
datePublished: Tue Mar 25 2025 06:25:04 GMT+0000 (Coordinated Universal Time)
cuid: cm8o42rat000508lbga8r66bc
slug: til-2025-03-25
tags: algorithms, python, leetcode, til

---

## \[LeetCode\]

### \[TwoSum\]

* Question Understanding
    
    * You are given an array of integers called `nums` and an integer `target`.
        
    * You may assume that each input has exactly one solution.
        
    * Return the indices of the two numbers such that they add up to the target.
        

Answer Code :

```python
class Solution:
    def twoSum(self, nums: List[int], target: int) -> List[int]:
        for idx in range(len(nums) - 1):
            for idx2 in range(idx + 1, len(nums)):
                if nums[idx] + nums[idx2] == target:
                    return [idx, idx2]
```

## \[Python\]

### \[Type Hint\]

* `int`
    
* `float`
    
* `str`
    
* `List[int]`
    
* `Tuple[str, int]`
    
* `Dict[str, int]`
    

Note : ‘List’, ‘Dict’, and ‘Tuple’ require typing module,

so you need to import them like this:

```python
from typing import List, Dict, Tuple
```

## \[English\]

### » assume

* **ACCEPT :** to accept something to be true without question or proof:
    
* **PRETEND TO HAVE :** to pretend to have a different name or be someone you are not, or to express a feeling falsely:
    
* **TAKE CONTROL :** to take or begin to have responsibility or control, sometimes without the right to do so, or to begin to have a characteristic:
    
* **Korean)** 추정하다, 가정하다
    

### » may / may not

* **POSSIBILITY** : used to express possibility
    
* **PERMISSION** : used to ask or give permission
    
* **WISH** : used to introduce a wish or a hope
    

### » indices

* **plural of index**
    

### » plural

* a word or form that expresses more than one