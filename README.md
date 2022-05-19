# Assignment-4-18-05-2022
Assignment 4
def twoSum(self, nums: List[int], target: int) -> List[int]: for i in range(len(nums)): for j in range(i + 1, len(nums)): if nums[j] == target - nums[i]: return [i, j]

