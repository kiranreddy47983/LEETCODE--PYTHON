# Ugly-number
class Solution(object):     def isUgly(self, n):         if n&lt;1:return False         for d in 2,3,5:             while n%d==0:n//=d         return n==1
