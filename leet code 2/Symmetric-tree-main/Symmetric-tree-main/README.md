# Symmetric-tree
class Solution(object):     def isSymmetric(self, r):         def s(l,r):             if not l or not r:return l is r             return l.val==r.val and s(l.left,r.right) and s(l.right,r.left)         return s(r.left,r.right)
