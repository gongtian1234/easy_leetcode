# L 349 Intersection of Two Arrays
 
--- 
 
``` 
class Solution(object):
    def intersection(self, nums1, nums2):
        """
        :type nums1: List[int]
        :type nums2: List[int]
        :rtype: List[int]
        """
        # set
        return list(set(nums1) & set(nums2))
 ```