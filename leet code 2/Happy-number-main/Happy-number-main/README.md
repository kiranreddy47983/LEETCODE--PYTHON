# Happy-number
class Solution(object):     def isHappy(self, n):         s=set()         while n!=1 and n not in s:             s.add(n)             n=sum(int(c)**2 for c in str(n))         return n==1
